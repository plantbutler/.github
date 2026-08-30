# Plant Butler

A hobby plant-watering system: an Arduino UNO R4 WiFi with one soil-moisture sensor per pot and a
pump feeding a rotary manifold, a small Python backend on a Synology NAS that stores the readings
and decides when to water, and an Android app to look at the plants and water them by hand.

**Start at [plantbutler/plantbutler](https://github.com/plantbutler/plantbutler)** — the umbrella
repository: what it is, the decisions it rests on, and the five repositories pinned as submodules.

| repo | what it is |
| --- | --- |
| [plan](https://github.com/plantbutler/plan) | the Shape Up plan — what is bet, what waits on what, and why |
| [firmware](https://github.com/plantbutler/firmware) | PlatformIO / Arduino UNO R4 WiFi |
| [backend](https://github.com/plantbutler/backend) | Python container + SQLite on the NAS |
| [app](https://github.com/plantbutler/app) | Kotlin + Jetpack Compose |
| [cad](https://github.com/plantbutler/cad) | OpenSCAD, KiCad, BOM, bench notes |
