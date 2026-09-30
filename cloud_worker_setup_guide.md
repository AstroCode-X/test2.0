# 🛡️ Anleitung: Cloudflare Worker als sicherer Gemini API Proxy

Durch diesen Proxy bleibt dein **Gemini API-Key absolut geheim** auf den Cloudflare-Servern gespeichert. Nutzer im Browser können den Key nicht auslesen oder missbrauchen. Deine Live-Worker-URL lautet: `https://nexus.elias256.workers.dev/`

---

## Schritt 1: Cloudflare Worker erstellen
1. Logge dich auf [cloudflare.com](https://www.cloudflare.com/) ein.
2. Gehe im linken Menü auf **Workers & Pages**.
3. Wähle deinen bestehenden Worker aus oder erstelle einen neuen mit dem Namen `nexus`.

---

## Schritt 2: Code einfügen & Speichern
1. Klicke im Worker auf **Edit code**.
2. Ersetze den gesamten Inhalt durch den Code aus der Datei `worker.js`.
3. Klicke oben rechts auf **Save and deploy**.

---

## Schritt 3: Gemini API-Key als Secret hinterlegen
1. Navigiere in deinem Worker zu **Settings** -> **Variables and Secrets**.
2. Klicke unter **Secrets** auf **Add secret**.
3. **Variable name:** `GROQ_API_KEY`. **Value:** Füge deinen echten groq API-Key ein.
5. Klicke auf **Save and deploy**.

---

## Schritt 4: Verifizierung im Dashboard
Die URL `https://nexus.elias256.workers.dev/` ist bereits fest im Frontend (`index.html`) hinterlegt. Deine KI-Anfragen werden ab sofort sicher über diesen Proxy geleitet!
