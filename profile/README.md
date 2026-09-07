# Plant Butler

A hobby system that waters house plants. An Arduino UNO R4 WiFi with one soil-moisture sensor per
pot, a pump and a manifold that sends water to one pot at a time; a small Python backend on a
Synology NAS (the home server) that stores the readings, decides when to water and sends alerts;
an Android app to look at the plants and water by hand.

**Start at [plantbutler/plantbutler](https://github.com/plantbutler/plantbutler)**: what the
system is, how the parts talk, how to get started, and the decisions it rests on.

| repository | what it is |
| --- | --- |
| [firmware](https://github.com/plantbutler/firmware) | the board: PlatformIO, C++ |
| [backend](https://github.com/plantbutler/backend) | the service: Python, SQLite, one container |
| [app](https://github.com/plantbutler/app) | the phone: Kotlin, Jetpack Compose |
| [cad](https://github.com/plantbutler/cad) | the hardware: OpenSCAD parts, wiring, parts list |
| [plan](https://github.com/plantbutler/plan) | what is being built and in what order |
