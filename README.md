# Awesome-IOT-Audio-Esp32-Airplay-2-Streaming

# Awesome-IOT-Audio-Esp32-Airplay-2-Streaming



Top IOT Audio Esp32 Airplay 2 Streaming (Opensource) 🌟 Star if you like it! 🌟



A curated list of top IoT audio platforms, ESP32 AirPlay 2 & Bluetooth audio receivers, multi-room network streamers, audiophile Linux distributions, and lossless streaming daemons—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [ESP32 AirPlay 2, DSP & Embedded Microcontroller Audio](#esp32-airplay-2-dsp--embedded-microcontroller-audio)

  - [Open-Source AirPlay & AirPlay 2 Receivers](#open-source-airplay--airplay-2-receivers)

  - [Multi-Room Audio & Open-Source Audiophile OS](#multi-room-audio--open-source-audiophile-os)

  - [Open-Source Spotify Connect, Tidal & Streaming Daemons](#open-source-spotify-connect-tidal--streaming-daemons)

  - [Network Music Servers & Whole-Home Audio Orchestration](#network-music-servers--whole-home-audio-orchestration)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, cloud-authenticated audio streaming protocols, proprietary audiophile ecosystems, and subscription-based multi-room music platforms.



* **[Apple AirPlay 2 & HomeKit Cloud Ecosystem](https://apple.com)** - Apple's proprietary wireless streaming protocol and cloud-synced multi-room audio standard for iOS, macOS, and certified speakers.

* **[Roon Labs (Roon & Roon ARC)](https://roon.app)** - Commercial audiophile music management, RAAT multi-room streaming, and cloud-authenticated mobile streaming platform.

* **[Audirvāna](https://audirvana.com)** - Proprietary high-resolution audio playback software featuring kernel-level optimization, UPnP/DLNA streaming, and cloud streaming integration.

* **[Volumio (MyVolumio Cloud & Premium)](https://volumio.com)** - Commercial tier and cloud relay service for Volumio offering multi-room sync, Tidal/Qobuz native integration, and remote access.

* **[Plexamp (Plex Pass)](https://plex.tv)** - Proprietary audiophile music player powered by Plex Media Server with cloud-assisted sonic analysis and loudness leveling.

* **[Spotify Connect](https://spotify.com)** - Proprietary cloud-mediated streaming protocol allowing Spotify apps to hand off playback directly to network-connected speakers and IoT devices.

* **[TIDAL Connect](https://tidal.com)** - Commercial lossless audio casting technology streaming high-resolution FLAC/MQA tracks directly from TIDAL's cloud to compatible hardware.

* **[WiiM / Sonos / BluOS Ecosystems](https://wiimhome.com)** - Commercial IoT wireless audio hardware/cloud platforms integrating AirPlay 2, Spotify Connect, and multi-room grouping.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) ESP32 AirPlay 2 receivers, open-source AirPlay/Spotify daemons, bit-perfect Linux audio OS builds, and whole-home multi-room servers.



### ESP32 AirPlay 2, DSP & Embedded Microcontroller Audio



* **[esp32-airplay2-surround (kristian8606)](https://github.com)** - Open-source ESP32 firmware enabling synchronized AirPlay 2 audio streaming and multi-channel surround setups on low-cost microcontrollers.

* **[ESP32-AirPlay / ESP-RAOP](https://github.com)** - Espressif Audio Development Framework (ESP-ADF) and community open-source AirPlay/RAOP receivers for ESP32 and ESP32-S3 boards.

* **[Squeezelite-ESP32](https://github.com)** - Feature-packed open-source ESP32 audio firmware supporting AirPlay, Spotify Connect, Bluetooth A2DP, Squeezebox/LMS, and I2S DACs.

* **[ESP32-A2DP (pschatzmann)](https://github.com)** - Popular open-source C++ Arduino/ESP-IDF library turning ESP32 boards into Bluetooth A2DP audio sinks and sources with I2S output.

* **[arduino-audio-tools (pschatzmann)](https://github.com)** - Comprehensive open-source audio processing, streaming, codec, and DSP toolkit tailored for ESP32 and embedded microcontrollers.

* **[Euphonium / Louder-ESP32](https://github.com)** - Open-source hardware and firmware ecosystem combining ESP32-S3 with TAS5805M/PCM5102A Hi-Fi DAC/Amp stages for DIY network streamers.



### Open-Source AirPlay & AirPlay 2 Receivers



* **[Shairport Sync](https://github.com)** - The gold-standard open-source AirPlay and AirPlay 2 audio player for Linux and FreeBSD supporting multi-room sync, NQPTP, and bit-perfect ALSA output.

* **[NQPTP](https://github.com)** - Open-source precision timing daemon implementing Apple's non-standard PTP variant required for synchronized AirPlay 2 playback.

* **[OwnTone (formerly forked-daapd)](https://github.com)** - Open-source Linux/FreeBSD media server capable of streaming local music, internet radio, and pipes simultaneously to AirPlay 1 & AirPlay 2 speakers.

* **[UxPlay](https://github.com)** - Open-source AirPlay mirroring and AirPlay audio server for Linux, macOS, and BSD using GStreamer.

* **[RPiPlay](https://github.com)** - Open-source AirPlay mirroring and audio receiver optimized specifically for Raspberry Pi hardware.



### Multi-Room Audio & Open-Source Audiophile OS



* **[moOde audio player](https://github.com)** - Free, open-source audiophile-grade music player OS for Raspberry Pi featuring built-in AirPlay, Spotify Connect, CamillaDSP, and UPnP.

* **[Volumio (Open-Source Core)](https://github.com)** - Open-source headless audiophile music player designed to turn Raspberry Pi and x86 single-board computers into dedicated network streamers.

* **[piCorePlayer](https://picoreplayer.org)** - Tiny, RAM-resident open-source Linux audio distribution for Raspberry Pi combining Squeezelite and LMS with fast boot times and power-loss resilience.

* **[Snapcast](https://github.com)** - Synchronous open-source multi-room client-server audio player ensuring sub-millisecond time-aligned playback across dozens of IoT nodes.

* **[HifiberryOS](https://github.com)** - Open-source Buildroot-based Linux distribution optimized for HiFiBerry DAC/Amp boards with AirPlay, Roon, and Bluetooth support.

* **[CamillaDSP](https://github.com)** - Fast, cross-platform open-source IIR and FIR digital signal processing engine written in Rust for room correction and active crossovers.



### Open-Source Spotify Connect, Tidal & Streaming Daemons



* **[librespot](https://github.com)** - The foundational open-source client library and headless Spotify Connect receiver written in Rust powering almost all DIY IoT audio streamers.

* **[go-librespot](https://github.com)** - Modern, lightweight open-source Spotify Connect daemon written in Go with MPRIS, PulseAudio, and ALSA backends.

* **[Raspotify](https://github.com)** - Zero-configuration open-source Spotify Connect client packaged specifically for Raspberry Pi OS and Debian/Ubuntu IoT devices.

* **[upmpdcli](https://lesbonscomptes.com)** - Open-source UPnP Media Renderer front-end for MPD providing Tidal, Qobuz, and Subsonic streaming gateways for DIY network players.



### Network Music Servers & Whole-Home Audio Orchestration



* **[Lyrion Music Server (formerly Logitech Media Server / LMS)](https://github.com)** - Legendary, actively maintained open-source multi-room audio server supporting Squeezelite, AirPlay bridges, Chromecast, and UPnP.

* **[Music Assistant](https://github.com)** - Open-source music library manager and whole-home audio orchestrator integrating seamlessly with Home Assistant, AirPlay, Snapcast, and Slimproto.

* **[MPD (Music Player Daemon)](https://github.com)** - Flexible, server-side open-source application for playing music over HTTP/RTP/ALSA controlled via lightweight network clients.

* **[Mopidy](https://github.com)** - Extensible open-source music server written in Python supporting local files, Spotify, SoundCloud, and Snapcast multi-room output.

* **[Navidrome](https://github.com)** - Lightweight, modern open-source Subsonic-compatible music server for streaming personal lossless audio libraries to IoT endpoints.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source ESP32 audio projects, AirPlay 2 receivers, audiophile Linux distributions, or multi-room streaming tools.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
