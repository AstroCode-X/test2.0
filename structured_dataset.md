{
  "metadata": {
    "mission": "Dancing with SARS - Lunar SAR & CLPS Control Center",
    "team": "00000000A_LAGRANGE_NEXUS",
    "version": "2.1.0-enhanced",
    "total_targets": 2,
    "total_psr_zones": 1,
    "total_hazard_zones": 1
  },
  "targets": [
    {
      "id": "SAR-001",
      "name": "Shackleton Crater Rim",
      "lat": -89.9,
      "lng": 0.0,
      "polarization": "Circular (CPR = 1.42)",
      "backscatter_db": "-2.4 dB",
      "roughness": "Sehr hoch (Kraterrand)",
      "ice_score": "89 %",
      "illumination_pct": "86 %",
      "slope_deg": "4.2° (Sicher)",
      "thermal_k": "40 K bis 220 K",
      "clps_suitability": "HOCHER WERT (Wassereis + Energie)"
    },
    {
      "id": "SAR-002",
      "name": "Cabeus Crater Floor",
      "lat": -84.9,
      "lng": -35.5,
      "polarization": "Circular (CPR = 1.85)",
      "backscatter_db": "-1.8 dB",
      "roughness": "Dunkler Schattenbereich",
      "ice_score": "94 %",
      "illumination_pct": "12 %",
      "slope_deg": "8.5° (Achtung)",
      "thermal_k": "35 K bis 100 K",
      "clps_suitability": "FORSCHUNGSZIEL (Kältefalle)"
    }
  ],
  "psr_zones": [
    {
      "id": "PSR-SHACKLETON",
      "name": "Shackleton PSR Kältefalle",
      "cpr_value": 1.45,
      "estimated_ice_depth_m": 1.8,
      "coordinates": [
        [-89.5, -20.0],
        [-89.8, 30.0],
        [-88.8, 60.0],
        [-88.2, 10.0],
        [-88.5, -40.0]
      ]
    }
  ],
  "hazard_zones": [
    {
      "id": "HAZARD-01",
      "name": "Tycho Steilhang & Felsfeld",
      "risk_type": "Kippgefahr (>12° Slope)",
      "coordinates": [
        [-41.0, -18.0],
        [-45.5, -18.0],
        [-45.5, -5.0],
        [-41.0, -5.0]
      ]
    }
  ]
}