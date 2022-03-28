# Ouroveon Build Distribution
This contains the current prebuilt binaries for the OUROVEON toolset.


## Release Notes

### **0.6.0 (2022/01/25)**

initial public release

### **0.6.1 (2022/01/31)**

* fix rare LORE playback crash in instant-transition mode
* refactor _Endlesss Exchange_ data format and IPC setup, move to Core app layer
* added `xtras\antenna` demo app for receiving and using _Endlesss Exchange_ data in totally separate app

### **0.6.2 (2022/02/13)**

* rewrite jam viewer rendering to cope with enormous jams on weaker GPU hardware
* rewrite jam browser, add public-archive snapshot data siphoned from Discord/etc
* database query optimisation
* riff playback thread optimisation

### **0.6.3 (2022/03/06)**

* major cross-platform work; initial MacOS Universal builds
* new common async processor for sample-processors
* sample-processor installation refactored
* improvements and OPUS tuning UI for Discord streaming
* specific audio buffer selection on boot-up
* tidy up transition-lock UI in preview mixer
* numerous 3rd party library upgrades
* initial support for Superluminal performance telemetry

### **0.6.4 (2022/03/28)**

* signed, notarised MacOS builds being produced
* fixes and file reshuffling for running as stand-alone app containers on MacOS
* LORE transition fixes for occasional pops
* LORE transition has small, fixed window of per-sample blending to help paper over any major changes between riffs
* FLAC export bug fixed with trailing data
* preview mixer UI expanded with more [repeat] options
* data warehouse UI improvements for 'busy' and 'active' jams
