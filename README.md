# 👋 Hi, I'm Agustín San Román

- 💼 Working as a software engineer for [AIR Institute](https://air-institute.com/).
- ⏳ 6 years of experience in the software industry.
- 🎓 Degree and master's degree in computer engineering from [University of Salamanca](https://www.usal.es/).

## 📫 How to contact me

- 📧 Email: agustinsrg@air-institute.com

## 🎯 Personal projects

I have worked on several personal projects and published them under open source licenses.

You can find a complete list of my personal projects, with a brief description and links to the repositories below.

---

<details>
    <summary>📌 Featured projects (Click to expand)</summary>

### Personal Media Vault

- 🎯 PersonalMediaVault is an open source tool you can use to create an encrypted, easy to backup and easy to access media gallery. It is a privacy and usability focused project, prioritizing keeping media assets private while being able to access them in a convenient and efficient way.
- 🛠 Developed as a web application in the **Go** programming language for the backend components, and **HTML** + **CSS** + **TypeScript** + **Vue** for the user interface. The project also includes a product website powered by **Hugo** + **Docsy** and a CLI tool developed in the **Rust** programming language.
- 🌐 [PersonalMediaVault product website](https://agustinsrg.github.io/pmv-site/)
- 🧬 Main repository: [PersonalMediaVault](https://github.com/AgustinSRG/PersonalMediaVault)
- 🧬 Website source code: [pmv-site](https://github.com/AgustinSRG/pmv-site)
- 🧬 CLI tool source code: [pmv-cli](https://github.com/AgustinSRG/pmv-cli)
- 🧬 Encrypted storage library: [encrypted-storage](https://github.com/AgustinSRG/encrypted-storage)

### RTMP server and video streaming tools

- 🎯 This project consists on multiple backend tools for developing video streaming platforms. This includes an **RTMP** (Real Time Messaging Protocol) server and several tools to encode and server streaming in the **HLS** (HTTP Live Streaming) format.
- 🛠 The tools were developed in the **Go** programming language.
- 🧬 RTMP server: [rtmp-server](https://github.com/AgustinSRG/rtmp-server)
- 🧬 Streaming infrastructure tools: [tcp-video-streaming](https://github.com/AgustinSRG/tcp-video-streaming)
- 🧬 HLS WebSocket CDN: [hls-websocket-cdn](https://github.com/AgustinSRG/hls-websocket-cdn)

### ImageToMapMC

- 🎯 This project is a desktop application for Linux and Windows to generate Minecraft maps from images. It can be used by server administrators to generate the `.dat` files to import into their servers. It can also be used to generate schematics to build the map in survival mode.
- 🛠 The application was developed in the **C++** programming language, using the [wxWidgets](https://www.wxwidgets.org/) GUI library.
- 🧬 Source code repository: [ImageToMapMC](https://github.com/AgustinSRG/ImageToMapMC)

### Showdown ChatBot

- 🎯 This project is a chat bot for the popular Pokémon simulator [Pokémon Showdown](https://pokemonshowdown.com/). It provides room staff many features like automated moderation, games and custom commands. It can also play battles automatically using a simple decision algorithm. This was my first open source project, being used in production for the Spanish room since 2015.
- 🛠 Developed in **JavaScript**, for **Node.js**.
- 🧬 Source code repository: [Showdown-ChatBot](https://github.com/AgustinSRG/Showdown-ChatBot)

### Typescript bean-like ORM

- 🎯 This project is a generic object relational mapping framework for TypeScript and NodeJS. The main purpose is to abstract the database logic from the web application, allowing to change from very different databases (like MySQL and MongoDB) simply changing the data source of the ORM. It is promise-based and the drivers are separated from the core, meaning you only need to import the ones you want to use.
- 🛠 Developed in **TypeScript**.
- 🌐 [Code generation tool](https://agustinsrg.github.io/tsbean-codegen/)
- 🧬 Main repository: [tsbean-orm](https://github.com/AgustinSRG/tsbean-orm)
- 🧬 Drivers: [tsbean-driver-mysql](https://github.com/AgustinSRG/tsbean-driver-mysql) | [tsbean-driver-postgres](https://github.com/AgustinSRG/tsbean-driver-postgres) | [tsbean-driver-mongo](https://github.com/AgustinSRG/tsbean-driver-mongo)
- 🧬 Driver template: [tsbean-driver-template](https://github.com/AgustinSRG/tsbean-driver-template)
- 🧬 Code generation tool: [tsbean-codegen](https://github.com/AgustinSRG/tsbean-codegen)

### WebRTC CDN

- 🎯 This project is a media content delivery network based on the WebRTC protocol. It allows for sending and receiving media streams in real time from the Browser. The use of a CDN instead of peer-to-peer communication can be useful to reduce the bandwidth requirements of the users. For example, in a call of 10 people, instead of having to send the media stream to all the 9 other participants, it sends it to the CDN, which distributes it to the rest of participants.
- 🛠 Server developed in the **Go** programming language. Client developed in **TypeScript**.
- 🧬 Main repository: [webrtc-cdn](https://github.com/AgustinSRG/webrtc-cdn)
- 🧬 JavaScript client: [webrtc-cdn-client](https://github.com/AgustinSRG/webrtc-cdn-client)
- 🧬 Experiments: [webrtc-publish](https://github.com/AgustinSRG/webrtc-publish) | [webrtc-forwarder](https://github.com/AgustinSRG/webrtc-forwarder) | [webrtc-video-filter](https://github.com/AgustinSRG/webrtc-video-filter)

</details>

---

<details>
    <summary>📂 Other projects (Click to expand) </summary>

### Smart Contract Wrapper

- 🎯 This project is a TypeScript library that can be used to simplify the interaction process with Ethereum smart contracts. You can generate a wrapper from the contract ABI, allowing to interact with the smart contract calling the wrapper methods.
- 🛠 Developed in **TypeScript**.
- 🌐 [Smart contract wrapper generator](https://agustinsrg.github.io/smart-contract-wrapper/codegen/)
- 🧬 Source code repository: [smart-contract-wrapper](https://github.com/AgustinSRG/smart-contract-wrapper)

### Async tools for JavaScript

- 🎯 This project is a JavaScript library that provides tools to work with asynchronous functions in JavaScript. It includes and async interval (waits for the async function to end before running it again), an async queue, an async semaphore and an async value provider.
- 🛠 Developed in **TypeScript**.
- 🧬 Source code repository: [async-tools](https://github.com/AgustinSRG/async-tools)

### JavaScript object sanitizer

- 🎯 This project is a JavaScript library that provides a convenient way to sanitize untrusted objects (for example, the ones provided by the user). Ensuring an object follows an schema allows for accessing its properties without the possibility of crashes or unexpected behaviors.
- 🛠 Developed in **TypeScript**.
- 🧬 Source code repository: [javascript-object-sanitizer](https://github.com/AgustinSRG/javascript-object-sanitizer)

### Basic request library

- 🎯 This project is a basic request library aimed to be used by the frontend of web applications to communicate with the backend. It provides a way to define API bindings (to ensure parameters are the correct types and error are handled thanks to TypeScript) and it also provides named requests, to automatically abort duplicate requests.
- 🛠 Developed in **TypeScript**.
- 🧬 Source code repositories: [request-browser](https://github.com/AgustinSRG/request-browser) | [request-axios](https://github.com/AgustinSRG/request-axios)

### Pokemon Showdown bot library

- 🎯 This project is a library for bots to connect to [Pokémon Showdown](https://pokemonshowdown.com/) servers and be able to play battles.
- 🛠 Developed in **TypeScript**.
- 🧬 Source code repositories: [ps-bot-lib](https://github.com/AgustinSRG/ps-bot-lib) | [ps-battle-bot-lib](https://github.com/AgustinSRG/ps-battle-bot-lib)

### Parallel request controller

- 🎯 This project is a backend component to control parallel requests. The main use case for this component is to impose limits on parallel requests when using multiple web servers for horizontal scaling.
- 🛠 Server in the **Go** programming language. Client developed in **TypeScript**.
- 🧬 Source code repository: [parallel-request-controller](https://github.com/AgustinSRG/parallel-request-controller)

### Other small libraries and tools

| Project                                                                                  | Category    | Language       | Description                                                                                                      |
| ---------------------------------------------------------------------------------------- | ----------- | -------------- | ---------------------------------------------------------------------------------------------------------------- |
| **[genv](https://github.com/AgustinSRG/genv)**                                           | **Library** | **Go**         | Golang library to read and parse environment variables.                                                          |
| **[glog](https://github.com/AgustinSRG/glog)**                                           | **Library** | **Go**         | Golang library for logging.                                                                                      |
| **[go-simple-rpc-message](https://github.com/AgustinSRG/go-simple-rpc-message)**         | **Library** | **Go**         | Golang library that implements a very simple RPC message system to be used in a text-based communication system. |
| **[go-child-process-manager](https://github.com/AgustinSRG/go-child-process-manager)**   | **Library** | **Go**         | Golang library to ensure all the child processes are killed if the main process is killed.                       |
| **[go-tls-certificate-loader](https://github.com/AgustinSRG/go-tls-certificate-loader)** | **Library** | **Go**         | Golang library to load TLS certificate and key.                                                                  |
| **[crystals-dilithium-js](https://github.com/AgustinSRG/crystals-dilithium-js)**         | **Library** | **JavaScript** | Javascript implementation of post-quantum signature algorithm: CRYSTALS-Dilithium                                |
| **[Text-Transform](https://github.com/AgustinSRG/Text-Transform)**                       | **Library** | **JavaScript** | Library to build simple text transform tools you can run in your browser.                                        |
| **[psim-log-to-replay](https://github.com/AgustinSRG/psim-log-to-replay)**               | **Tool**    | **JavaScript** | Simple web tool to turn a Pokemon Showdown battle log into a replay.                                             |
| **[eth-test-node-action](https://github.com/AgustinSRG/eth-test-node-action)**           | **CI**      | **Shell**      | GitHub Action to setup an Ethereum node to test Smart Contracts.                                                 |

</details>
