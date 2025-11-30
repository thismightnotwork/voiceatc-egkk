# London Gatwick Airport (EGKK) for VoiceATC

Complete airport configuration for London Gatwick (EGKK) including EAST and WEST sector configurations.

## Download & Installation

1. **Download this repository** by clicking the green "Code" button above → "Download ZIP"
2. **Extract the EGKK folder** from the ZIP
3. **Copy the EGKK folder** to your VoiceATC airports directory:
   - Windows: `%APPDATA%\VoiceATCSimulator\airports\`
4. **Restart VoiceATC** and select EGKK from the airport list

## Folder Structure

The complete EGKK folder should contain:

```
EGKK/
├── EGKK.INFO          (Airport info)
├── EGKK.RW            (Runways)
├── EGKK.MRVA          (Minimum altitudes)
├── EGKK.GEO           (Sector boundaries)
├── EGKK.TFC           (Traffic routes)
├── EAST/              (East sector configuration)
│   ├── EGKKEAST.GP
│   ├── EGKKEAST.DRAW
│   ├── EGKKEAST.SECTORS
│   ├── EGKKEAST.HOLD
│   ├── NAVDIDS/
│   │   ├── EGKKEAST.FIX
│   │   └── EGKKEAST.VOR
│   └── PROCS/
│       ├── EGKKEAST.STR
│       ├── EGKKEAST.TRAN
│       ├── EGKKEAST.IAC
│       └── EGKKEASTWPT.PRONUNCIATION
└── WEST/              (West sector configuration)
    ├── EGKKWEST.GP
    ├── EGKKWEST.DRAW
    ├── EGKKWEST.SECTORS
    ├── EGKKWEST.HOLD
    ├── NAVDIDS/
    │   ├── EGKKWEST.FIX
    │   └── EGKKWEST.VOR
    └── PROCS/
        ├── EGKKWEST.STR
        ├── EGKKWEST.TRAN
        ├── EGKKWEST.IAC
        └── EGKKWESTWPT.PRONUNCIATION
```

## Manual File Creation

If you prefer to create files manually, see the FILES.md document for complete file contents.

## Features

- ✈️ Both runways (08R/26L and 08L/26R)
- 🎯 EAST and WEST sector configurations
- 📍 Key navaids and fixes around Gatwick
- 🛬 ILS approaches for all runways
- 📡 Realistic MVA/MRVA areas
- 🚦 Basic traffic routes

## Configuration Details

**Airport Reference Point:** N051.08.53, W000.11.25  
**Elevation:** 202 feet  
**Transition Altitude:** 6000 feet  
**Runways:**
- 08R/26L (Main runway)
- 08L/26R (Standby runway)

## Contributing

Feel free to submit improvements via pull requests or open issues for bugs/suggestions.

## Based On

Created following the VoiceATC airport creation tutorial: https://www.youtube.com/watch?v=c00SInazaNI
