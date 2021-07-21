<h1 align="center">
<p align="center">
  <img alt="Khepri Logo" src="docs/images/Khepri.png" height="30%" width="40%">
</p>
  Khepri
  <br>
</h1>

<h5 align="center">Free,Open-Source,Cross-platform agent and Post-exploiton tool written in Golang and C++</h5>


![platform](https://img.shields.io/badge/platform-cross-important?color=%23189000) ![Langue](https://img.shields.io/badge/language-golang/c++-orange.svg) ![stars](https://img.shields.io/github/stars/geemion/khepri) ![license](https://img.shields.io/github/license/geemion/khepri)

### Description

Khepri is a Cross-platform agent, the architecture and usage like Coblat Strike but free and open-source.

----
*This project is for learning Golang and C++ only, if someone's rights have been violated, please contact me to remove the project, and the last DO NOT USE IT ILLEGALLY*

<p align="center">
 <img alt="architecture" src="docs/images/architecture.png" height="100%" width="100%">
</p>

- beacon: Agent, written in C++.
- teamserver: Server, written in Golang.
- teamclient: User client, written in C++, the UI use Qt-GUI.  


### Features
<p align="center">
 <img alt="architecture" src="docs/images/teamclient.png" height="100%" width="100%">
</p>

- Supported C2 Protocols:
  - [x] TCP
  - [x] UDP
- Fast network serialization (Protocol Buffers)
- Agent Features:
  - [x] System Information
  - [x] Process Manager
  - [x] File Manager
  - [x] Remote Shell
  - [x] Remote Execution

- Supported operating systems


 | System     | Windows   | Linux       | Macos    |
 |------------|-----------|------------ |----------|
 | beacon     | √         | √           |√         |
 | teamserver | √         | √           |√         |
 | teamclient | √         | √           |√         |


### Quick Start

Please see [Quick Start](docs/quick_start.md)

### TODO
- [ ] Refactor teamserver code
- [ ] Beacon supports more protocols:https、dns
- [ ] Beacon supports https-dns 
- [ ] Beacon supports dynamic plugin
- [ ] Beacon support proxy
- [x] ~~Teamclient support proxy~~
- [ ] Support CI
- [x] ~~Beacon and teamclient support macos~~
- [x] Reduce beacon to ~~100kb~~700kb(~~Don't use openssl~~、support Mingw compile(can't reduce size))
...

### Contributing
Issues and PR is welcome.