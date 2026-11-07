### Hi, I'm Jeevanjot Singh Vital

Desktop and native app engineer in Amritsar, India (IST, UTC+5:30). I build cross-platform desktop apps with Electron, Apple-platform apps with Swift and SwiftUI, and AI-powered tools. Before that, from 2018 to 2022, I shipped blockchain oracles, protocols, bots and open-source tooling.

[Website](https://jeevanjotsinghvital.com) · [LinkedIn](https://www.linkedin.com/in/jeevanjot-singh/) · [YouTube](https://www.youtube.com/@VitalJeevanjot) · [Medium](https://jeevanjotsinghvital.medium.com/) · [DEV](https://dev.to/genievot) · [Devpost](https://devpost.com/genievot)

#### Desktop apps (Electron)

- **[Image Search OCR](https://apps.microsoft.com/detail/9mx9wfk5gcf0)** on the Microsoft Store ([source](https://github.com/VitalJeevanjot/image-ocr-search)): finds images by the words inside them. OCR runs locally on a pool of Tesseract.js workers in the main process, behind a narrow IPC bridge, with search over IndexedDB.
- **[App Website Wrapper](https://apps.microsoft.com/detail/9phk8k3xgzhn)** on the Microsoft Store: turns a website URL or a local HTML project into a signed Android APK. The app drives the build toolchain in child processes and streams their output to the UI.
- **Colour Picker Manage**: a screen colour picker built on Electron's `desktopCapturer`, with an eyedropper mode that stays on top of other windows.
- **Screen Hide**: an always-on-top overlay that covers part or all of the screen with a colour or an image.
- **On-device image tools** (2023): find small images inside large ones (OpenCV.js), and search or classify images by their contents (TensorFlow.js and ml5).
- **Earlier Electron apps** (2018 to 2019): cross-platform crypto wallets ([P3C Wallet](https://github.com/VitalJeevanjot/p3cwallet), [Funcoin Wallet](https://github.com/VitalJeevanjot/Funcoin-Wallet)), a Steem client ([qSteem](https://github.com/VitalJeevanjot/qSteem)) and a Byteball voting app ([Bvoting](https://github.com/VitalJeevanjot/Bvoting)), all built with Quasar.

#### Native apps (Swift and SwiftUI)

- **[PicMik](https://apps.apple.com/app/id6504264044)** on the App Store: pair photos with recorded audio and share them (iPhone and iPad).
- **Tutorials**: [WebKit Viewer](https://github.com/VitalJeevanjot/webkitViewer-tutorial) (WKWebView, a Swift and JavaScript bridge, SwiftData) and [Image Splitter](https://github.com/VitalJeevanjot/ImageSplitter-tut1) (a before-and-after slider for iOS, macOS and visionOS).
- **Virtualization prototypes** (in progress): a macOS VM manager, and a Linux VM runner that provisions Debian with cloud-init and talks to it over a virtio serial console. Both use Apple's Virtualization framework.

#### AI and web

- **[Time&Dime](https://github.com/VitalJeevanjot/time-and-dime)**: a local-first, timed scenario calculator that browser agents can drive through WebMCP tools. Vue 3, Decimal.js, tests and CI. [Live demo](https://time-and-dime.netlify.app)

#### Earlier blockchain work

- **[Say Network / Oracle 2.0](https://github.com/VitalJeevanjot/oracle-service)**: an Aeternity grant project for URL oracles with TLSNotary proofs and encrypted queries ([final report](https://forum.aeternity.com/t/final-report-say-network-oracle-2-0-for-aeternity-q3-final-report/10174))
- **[MOMP](https://github.com/VitalJeevanjot/momp-network-smart_contract)**: send Aeternity to an email address and let the owner claim it with a one-time code
- **[Decentralized Insurance](https://github.com/VitalJeevanjot/decentralized-Insurance)**: winner of Best Superhero.com New DeFi feature at Human DeFi Haeck 2020
- **[Sedo Network](https://github.com/VitalJeevanjot/sedo-network)**: domain escrow settled by Chainlink oracles

#### Merged open-source contributions

- **Quasar**: [quasar #5947](https://github.com/quasarframework/quasar/pull/5947), [quasar-awesome #83](https://github.com/quasarframework/quasar-awesome/pull/83)
- **Okteto**: Helm charts [#41](https://github.com/okteto/charts/pull/41), [#48](https://github.com/okteto/charts/pull/48), [#58](https://github.com/okteto/charts/pull/58), [#59](https://github.com/okteto/charts/pull/59), and node-openfaas [#2](https://github.com/okteto/node-openfaas/pull/2), [#3](https://github.com/okteto/node-openfaas/pull/3)
- **Aeternity**: aestudio [#47](https://github.com/aeternity/aestudio/pull/47) (copy-address feature) and the token migration backend [#2](https://github.com/aeternity/aepp-token-migration-backend-nodejs/pull/2)
- **Events and community**: Python Discord Code Jam 6 team project ([#16](https://github.com/python-discord/code-jam-6/pull/16)), Online MiniHack ([#43](https://github.com/OnlineMiniHack/minihack/pull/43)), Aragon hack docs ([#244](https://github.com/aragon/hack/pull/244)), Obyte oscript-editor ([#10](https://github.com/byteball/oscript-editor/pull/10)) and DevEdmonton ([#171](https://github.com/devedmonton/DES-Website/pull/171))

#### Writing

Tutorials on Aeternity oracles, Chainlink nodes and Okteto on [Medium](https://jeevanjotsinghvital.medium.com/), and a five-part MOMP series on [DEV](https://dev.to/genievot).
