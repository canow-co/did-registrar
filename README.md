# Cheqd DID Registrar

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/cheqd/.github?color=green&label=stable%20release&style=flat-square)](https://github.com/cheqd/.github/releases/latest) ![GitHub Release Date](https://img.shields.io/github/release-date/cheqd/.github?color=green&style=flat-square) [![GitHub license](https://img.shields.io/github/license/cheqd/.github?color=blue&style=flat-square)](https://github.com/cheqd/.github/blob/main/LICENSE)

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/cheqd/.github?include_prereleases&label=dev%20release&style=flat-square)](https://github.com/cheqd/.github/releases/) ![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/cheqd/.github/latest?style=flat-square) [![GitHub contributors](https://img.shields.io/github/contributors/cheqd/.github?label=contributors%20%E2%9D%A4%EF%B8%8F&style=flat-square)](https://github.com/cheqd/.github/graphs/contributors)

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/cheqd/.github/Workflow%20Dispatch?label=workflows&style=flat-square)](https://github.com/cheqd/.github/actions/workflows/dispatch.yml) [![GitHub Workflow Status](https://img.shields.io/github/workflow/status/cheqd/.github/CodeQL?label=CodeQL&style=flat-square)](https://github.com/cheqd/.github/actions/workflows/codeql.yml) ![GitHub repo size](https://img.shields.io/github/repo-size/cheqd/.github?style=flat-square)

## ℹ️ Overview

A cheqd driver for the universal registrar

## Specifications

* [Decentralized Identifiers](https://w3c.github.io/did-core/)

## Build and Run (Docker)

```bash
docker build -f ./docker/Dockerfile . -t exampleorg/uni-registrar-driver-did-example
docker run -p 9080:9080 exampleorg/uni-registrar-driver-did-example
curl -X POST http://localhost:9080/1.0/create -H "Content-Type: application/json"
```

## Build and Run (NodeJS)

```bash
npm start
```

## 💬 Community

The [**cheqd Community Slack**](http://cheqd.link/join-cheqd-slack) is our primary chat channel for the open-source community, software developers, and node operators.

Please reach out to us there for discussions, help, and feedback on the project.

## 🙋 Find us elsewhere

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge\&logo=telegram\&logoColor=white)](https://t.me/cheqd) [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge\&logo=discord\&logoColor=white)](http://cheqd.link/discord-github) [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge\&logo=twitter\&logoColor=white)](https://twitter.com/intent/follow?screen\_name=cheqd\_io) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](http://cheqd.link/linkedin) [![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge\&logo=slack\&logoColor=white)](http://cheqd.link/join-cheqd-slack) [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge\&logo=medium\&logoColor=white)](https://blog.cheqd.io) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge\&logo=youtube\&logoColor=white)](https://www.youtube.com/channel/UCBUGvvH6t3BAYo5u41hJPzw/)
![DIF Logo](https://raw.githubusercontent.com/decentralized-identity/universal-registrar/master/docs/logo-dif.png)

