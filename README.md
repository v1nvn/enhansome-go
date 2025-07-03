# Awesome Go

<a href="https://awesome-go.com/"><img align="right" src="https://github.com/avelino/awesome-go/raw/main/tmpl/assets/logo.png" alt="awesome-go" title="awesome-go" /></a>

[![Build Status](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml/badge.svg?branch=main)](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml?query=branch%3Amain) ⭐ 146,588 | 🐛 124 | 🌐 Go | 📅 2025-06-29
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 377,475 | 🐛 42 | 📅 2025-06-11
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true\&logo=slack\&colorB=red)](https://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)
[![Last Commit](https://img.shields.io/github/last-commit/avelino/awesome-go)](https://img.shields.io/github/last-commit/avelino/awesome-go)

We use the *[Golang Bridge](https://github.com/gobridge/about-us/blob/master/README.md) ⭐ 408 | 🐛 1 | 📅 2023-12-01* community Slack for instant communication, follow the [form here to join](https://invite.slack.golangbridge.org/).

<a href="https://www.producthunt.com/posts/awesome-go?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-go" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=291535&theme=light" alt="awesome-go - Curated list awesome Go frameworks, libraries and software | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

**Sponsorships:**

*Special thanks to*

<div align="center">
<table cellpadding="5">
<tbody align="center">
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-workos">
<img src="https://avelino.run/sponsors/workos-logo-white-bg.svg" width="200" alt="WorkOS"><br/>
<b>Your app, enterprise-ready.</b><br/>
<sub>Start selling to enterprise customers with just a few lines of code.</sub><br/>
<sup>Add Single Sign-On (and more) in minutes instead of months.</sup>
</a>
</td>
</tr>
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-digitalocean">
<img src="https://avelino.run/sponsors/do_logo_horizontal_blue-210.png" width="200" alt="Digital Ocean">
</a>
</td>
</tr>
</tbody>
</table>
</div>

**Awesome Go has no monthly fee***, but we have employees who **work hard** to keep it running. With money raised, we can repay the effort of each person involved! You can see how we calculate our billing and distribution as it is open to the entire community. Want to be a supporter of the project click [here](mailto:avelinorun+oss@gmail.com?subject=awesome-go%3A%20project%20support).*

> A curated list of awesome Go frameworks, libraries, and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python) ⭐ 248,716 | 🐛 492 | 🌐 Python | 📅 2024-08-11.

**Contributing:**

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/main/CONTRIBUTING.md) ⭐ 146,588 | 🐛 124 | 🌐 Go | 📅 2025-06-29 first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors) ⭐ 146,588 | 🐛 124 | 🌐 Go | 📅 2025-06-29; you rock!

> *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

## Contents

* [Awesome Go](#awesome-go)
  * [Contents](#contents)
  * [Actor Model](#actor-model)
  * [Artificial Intelligence](#artificial-intelligence)
  * [Audio and Music](#audio-and-music)
  * [Authentication and OAuth](#authentication-and-oauth)
  * [Blockchain](#blockchain)
  * [Bot Building](#bot-building)
  * [Build Automation](#build-automation)
  * [Command Line](#command-line)
    * [Advanced Console UIs](#advanced-console-uis)
    * [Standard CLI](#standard-cli)
  * [Configuration](#configuration)
  * [Continuous Integration](#continuous-integration)
  * [CSS Preprocessors](#css-preprocessors)
  * [Data Integration Frameworks](#data-integration-frameworks)
  * [Data Structures and Algorithms](#data-structures-and-algorithms)
    * [Bit-packing and Compression](#bit-packing-and-compression)
    * [Bit Sets](#bit-sets)
    * [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
    * [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
    * [Iterators](#iterators)
    * [Maps](#maps)
    * [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
    * [Nullable Types](#nullable-types)
    * [Queues](#queues)
    * [Sets](#sets)
    * [Text Analysis](#text-analysis)
    * [Trees](#trees)
    * [Pipes](#pipes)
  * [Database](#database)
    * [Caches](#caches)
    * [Databases Implemented in Go](#databases-implemented-in-go)
    * [Database Schema Migration](#database-schema-migration)
    * [Database Tools](#database-tools)
    * [SQL Query Builders](#sql-query-builders)
  * [Database Drivers](#database-drivers)
    * [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
    * [Relational Database Drivers](#relational-database-drivers)
    * [NoSQL Database Drivers](#nosql-database-drivers)
    * [Search and Analytic Databases](#search-and-analytic-databases)
  * [Date and Time](#date-and-time)
  * [Distributed Systems](#distributed-systems)
  * [Dynamic DNS](#dynamic-dns)
  * [Email](#email)
  * [Embeddable Scripting Languages](#embeddable-scripting-languages)
  * [Error Handling](#error-handling)
  * [File Handling](#file-handling)
  * [Financial](#financial)
  * [Forms](#forms)
  * [Functional](#functional)
  * [Game Development](#game-development)
  * [Generators](#generators)
  * [Geographic](#geographic)
  * [Go Compilers](#go-compilers)
  * [Goroutines](#goroutines)
  * [GUI](#gui)
  * [Hardware](#hardware)
  * [Images](#images)
  * [IoT (Internet of Things)](#iot-internet-of-things)
  * [Job Scheduler](#job-scheduler)
  * [JSON](#json)
  * [Logging](#logging)
  * [Machine Learning](#machine-learning)
  * [Messaging](#messaging)
  * [Microsoft Office](#microsoft-office)
    * [Microsoft Excel](#microsoft-excel)
    * [Microsoft Word](#microsoft-word)
  * [Miscellaneous](#miscellaneous)
    * [Dependency Injection](#dependency-injection)
    * [Project Layout](#project-layout)
    * [Strings](#strings)
    * [Uncategorized](#uncategorized)
  * [Natural Language Processing](#natural-language-processing)
    * [Language Detection](#language-detection)
    * [Morphological Analyzers](#morphological-analyzers)
    * [Slugifiers](#slugifiers)
    * [Tokenizers](#tokenizers)
    * [Translation](#translation)
    * [Transliteration](#transliteration)
  * [Networking](#networking)
    * [HTTP Clients](#http-clients)
  * [OpenGL](#opengl)
  * [ORM](#orm)
  * [Package Management](#package-management)
  * [Performance](#performance)
  * [Query Language](#query-language)
  * [Reflection](#reflection)
  * [Resource Embedding](#resource-embedding)
  * [Science and Data Analysis](#science-and-data-analysis)
  * [Security](#security)
  * [Serialization](#serialization)
  * [Server Applications](#server-applications)
  * [Stream Processing](#stream-processing)
  * [Template Engines](#template-engines)
  * [Testing](#testing)
    * [Testing Frameworks](#testing-frameworks)
    * [Mock](#mock)
    * [Fuzzing and delta-debugging/reducing/shrinking](#fuzzing-and-delta-debuggingreducingshrinking)
    * [Selenium and browser control tools](#selenium-and-browser-control-tools)
    * [Fail injection](#fail-injection)
  * [Text Processing](#text-processing)
    * [Formatters](#formatters)
    * [Markup Languages](#markup-languages)
    * [Parsers/Encoders/Decoders](#parsersencodersdecoders)
    * [Regular Expressions](#regular-expressions)
    * [Sanitation](#sanitation)
    * [Scrapers](#scrapers)
    * [RSS](#rss)
    * [Utility/Miscellaneous](#utilitymiscellaneous)
  * [Third-party APIs](#third-party-apis)
  * [Utilities](#utilities)
  * [UUID](#uuid)
  * [Validation](#validation)
  * [Version Control](#version-control)
  * [Video](#video)
  * [Web Frameworks](#web-frameworks)
    * [Middlewares](#middlewares)
      * [Actual middlewares](#actual-middlewares)
      * [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
    * [Routers](#routers)
  * [WebAssembly](#webassembly)
  * [Webhooks Server](#webhooks-server)
  * [Windows](#windows)
  * [Workflow Frameworks](#workflow-frameworks)
  * [XML](#xml)
  * [Zero Trust](#zero-trust)
  * [Code Analysis](#code-analysis)
  * [Editor Plugins](#editor-plugins)
  * [Go Generate Tools](#go-generate-tools)
  * [Go Tools](#go-tools)
  * [Software Packages](#software-packages)
    * [DevOps Tools](#devops-tools)
    * [Other Software](#other-software)
* [Resources](#resources)
  * [Benchmarks](#benchmarks)
  * [Conferences](#conferences)
  * [E-Books](#e-books)
    * [E-books for purchase](#e-books-for-purchase)
    * [Free e-books](#free-e-books)
  * [Gophers](#gophers)
  * [Meetups](#meetups)
  * [Style Guides](#style-guides)
  * [Social Media](#social-media)
    * [Twitter](#twitter)
    * [Reddit](#reddit)
  * [Websites](#websites)
    * [Tutorials](#tutorials)
    * [Guided Learning](#guided-learning)

**[⬆ back to top](#contents)**

## Actor Model

*Libraries for building actor-based programs.*

* [Ergo](https://github.com/ergo-services/ergo) ⭐ 4,006 | 🐛 4 | 🌐 Go | 📅 2025-06-30 - An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang.
* [Goakt](https://github.com/Tochemey/goakt) ⭐ 260 | 🐛 1 | 🌐 Go | 📅 2025-07-02 - Fast and Distributed Actor framework using protocol buffers as message for Golang.
* [Hollywood](https://github.com/anthdm/hollywood) ⭐ 1,966 | 🐛 23 | 🌐 Go | 📅 2025-06-06 - Blazingly fast and light-weight Actor engine written in Golang.
* [ProtoActor](https://github.com/asynkron/protoactor-go) ⭐ 5,252 | 🐛 88 | 🌐 Go | 📅 2024-08-22 - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin.

## Artificial Intelligence

*Libraries for building programs that leverage AI.*

* [chromem-go](https://github.com/philippgille/chromem-go) ⭐ 614 | 🐛 11 | 🌐 Go | 📅 2025-04-27 - Embeddable vector database for Go with Chroma-like interface and zero third-party dependencies. In-memory with optional persistence.
* [fun](https://gitlab.com/tozd/go/fun) - The simplest but powerful way to use large language models (LLMs) in Go.
* [langchaingo](https://github.com/tmc/langchaingo) ⭐ 7,028 | 🐛 365 | 🌐 Go | 📅 2025-06-29 - LangChainGo is a framework for developing applications powered by language models.
* [LocalAI](https://github.com/mudler/LocalAI) ⭐ 33,631 | 🐛 481 | 🌐 Go | 📅 2025-07-02 - Open Source OpenAI alternative, self-host AI models.
* [Ollama](https://github.com/jmorganca/ollama) ⭐ 145,368 | 🐛 1,903 | 🌐 Go | 📅 2025-07-02 - Run large language models locally.
* [OllamaFarm](https://github.com/presbrey/ollamafarm) ⭐ 79 | 🐛 0 | 🌐 Go | 📅 2025-02-01 - Manage, load-balance, and failover packs of Ollamas

**[⬆ back to top](#contents)**

## Audio and Music

*Libraries for manipulating audio.*

* [flac](https://github.com/mewkiz/flac) ⭐ 334 | 🐛 8 | 🌐 Go | 📅 2024-08-11 - Native Go FLAC encoder/decoder with support for FLAC streams.
* [gaad](https://github.com/Comcast/gaad) ⭐ 129 | 🐛 2 | 🌐 Go | 📅 2023-01-27 - Native Go AAC bitstream parser.
* [GoAudio](https://github.com/DylanMeeus/GoAudio) ⭐ 377 | 🐛 10 | 🌐 Go | 📅 2024-04-23 - Native Go Audio Processing Library.
* [gosamplerate](https://github.com/dh1tw/gosamplerate) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2024-01-28 - libsamplerate bindings for go.
* [id3v2](https://github.com/bogem/id3v2) ⭐ 347 | 🐛 24 | 🌐 Go | 📅 2023-10-28 - ID3 decoding and encoding library for Go.
* [malgo](https://github.com/gen2brain/malgo) ⭐ 335 | 🐛 9 | 🌐 C | 📅 2024-10-22 - Mini audio library.
* [minimp3](https://github.com/tosone/minimp3) ⭐ 129 | 🐛 0 | 🌐 C | 📅 2023-08-02 - Lightweight MP3 decoder library.
* [Oto](https://github.com/hajimehoshi/oto) ⭐ 1,731 | 🐛 24 | 🌐 Go | 📅 2025-06-27 - A low-level library to play sound on multiple platforms.
* [PortAudio](https://github.com/gordonklaus/portaudio) ⭐ 776 | 🐛 6 | 🌐 Go | 📅 2025-02-06 - Go bindings for the PortAudio audio I/O library.

**[⬆ back to top](#contents)**

## Authentication and OAuth

*Libraries for implementing authentication schemes.*

* [authboss](https://github.com/volatiletech/authboss) ⭐ 3,987 | 🐛 41 | 🌐 Go | 📅 2025-06-26 - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure it, and start building your app without having to build an authentication system each time.
* [branca](https://github.com/essentialkaos/branca) ⭐ 90 | 🐛 0 | 🌐 Go | 📅 2025-06-17 - branca token [specification implementation](https://github.com/tuupola/branca-spec) ⭐ 230 | 🐛 10 | 📅 2025-05-06 for Golang 1.15+.
* [casbin](https://github.com/hsluoyz/casbin) ⭐ 18,818 | 🐛 48 | 🌐 Go | 📅 2025-06-21 - Authorization library that supports access control models like ACL, RBAC, and ABAC.
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2024-03-12 - provides a parser of cookies.txt file format.
* [go-guardian](https://github.com/shaj13/go-guardian) ⭐ 588 | 🐛 12 | 🌐 Go | 📅 2024-07-25 - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication.
* [go-jose](https://github.com/go-jose/go-jose) ⭐ 413 | 🐛 31 | 🌐 Go | 📅 2025-06-26 - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* [goiabada](https://github.com/leodip/goiabada) ⭐ 154 | 🐛 5 | 🌐 Go | 📅 2025-02-24 - An open-source authentication and authorization server supporting OAuth2 and OpenID Connect.
* [gologin](https://github.com/dghubble/gologin) ⭐ 1,914 | 🐛 0 | 🌐 Go | 📅 2025-07-02 - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* [gorbac](https://github.com/mikespook/gorbac) ⭐ 1,632 | 🐛 4 | 🌐 Go | 📅 2024-07-22 - provides a lightweight role-based access control (RBAC) implementation in Golang.
* [gosession](https://github.com/Kwynto/gosession) ⭐ 258 | 🐛 0 | 🌐 Go | 📅 2024-07-31 - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one.
* [goth](https://github.com/markbates/goth) ⭐ 6,074 | 🐛 132 | 🌐 Go | 📅 2025-04-04 - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* [jeff](https://github.com/abraithwaite/jeff) ⭐ 269 | 🐛 2 | 🌐 Go | 📅 2025-01-23 - Simple, flexible, secure, and idiomatic web session management with pluggable backends.
* [jwt](https://github.com/pascaldekloe/jwt) ⭐ 362 | 🐛 0 | 🌐 Go | 📅 2023-04-29 - Lightweight JSON Web Token (JWT) library.
* [jwt](https://github.com/cristalhq/jwt) ⭐ 685 | 🐛 2 | 🌐 Go | 📅 2025-06-22 - Safe, simple, and fast JSON Web Tokens for Go.
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) ⭐ 234 | 🐛 4 | 🌐 Go | 📅 2021-08-01 - JWT middleware for Golang http servers with many configuration options.
* [jwt-go](https://github.com/golang-jwt/jwt) ⭐ 8,213 | 🐛 46 | 🌐 Go | 📅 2025-07-01 - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs.
* [jwx](https://github.com/lestrrat-go/jwx) ⭐ 2,127 | 🐛 4 | 🌐 Go | 📅 2025-07-03 - Go module implementing various JWx (JWA/JWE/JWK/JWS/JWT, otherwise known as JOSE) technologies
* [keto](https://github.com/ory/keto) ⭐ 5,053 | 🐛 59 | 🌐 Go | 📅 2025-07-02 - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models.
* [loginsrv](https://github.com/tarent/loginsrv) ⭐ 1,925 | 🐛 28 | 🌐 Go | 📅 2021-02-27 - JWT login microservice with pluggable backends such as OAuth2 (Github), htpasswd, osiam.
* [oauth2](https://github.com/golang/oauth2) ⭐ 5,638 | 🐛 39 | 🌐 Go | 📅 2025-05-05 - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support.
* [oidc](https://github.com/zitadel/oidc) ⭐ 1,598 | 🐛 30 | 🌐 Go | 📅 2025-07-02 - Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation
* [openfga](https://github.com/openfga/openfga) ⭐ 3,776 | 🐛 129 | 🌐 Go | 📅 2025-07-02 - Implementation of fine-grained authorization based on the "Zanzibar: Google's Consistent, Global Authorization System" paper. Backed by [CNCF](https://www.cncf.io/).
* [osin](https://github.com/openshift/osin) ⭐ 1,927 | 🐛 3 | 🌐 Go | 📅 2025-05-08 - Golang OAuth2 server library.
* [otpgen](https://github.com/grijul/otpgen) ⭐ 139 | 🐛 1 | 🌐 Go | 📅 2024-01-17 - Library to generate TOTP/HOTP codes.
* [otpgo](https://github.com/jltorresm/otpgo) ⭐ 75 | 🐛 2 | 🌐 Go | 📅 2021-02-27 - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
* [paseto](https://github.com/o1egl/paseto) ⭐ 897 | 🐛 6 | 🌐 Go | 📅 2023-02-25 - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
* [permissions](https://github.com/xyproto/permissions) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-12-01 - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt.
* [scope](https://github.com/SonicRoshan/scope) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2021-05-25 - Easily Manage OAuth2 Scopes In Go.
* [scs](https://github.com/alexedwards/scs) ⭐ 2,352 | 🐛 29 | 🌐 Go | 📅 2025-04-17 - Session Manager for HTTP servers.
* [securecookie](https://github.com/chmike/securecookie) ⭐ 81 | 🐛 0 | 🌐 Go | 📅 2023-02-18 - Efficient secure cookie encoding/decoding.
* [session](https://github.com/icza/session) ⭐ 118 | 🐛 4 | 🌐 Go | 📅 2024-08-24 - Go session management for web servers (including support for Google App Engine - GAE).
* [sessions](https://github.com/adam-hanna/sessions) ⭐ 78 | 🐛 4 | 🌐 Go | 📅 2023-07-17 - Dead simple, highly performant, highly customizable sessions service for go http servers.
* [sessionup](https://github.com/swithek/sessionup) ⭐ 127 | 🐛 3 | 🌐 Go | 📅 2025-03-20 - Simple, yet effective HTTP session management and identification package.
* [sjwt](https://github.com/brianvoe/sjwt) ⭐ 122 | 🐛 1 | 🌐 Go | 📅 2024-02-01 - Simple jwt generator and parser.
* [x509proxy](https://github.com/vkuznet/x509proxy) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2025-01-19 - Library to handle X509 proxy certificates.

**[⬆ back to top](#contents)**

## Blockchain

*Tools for building blockchains.*

* [cometbft](https://github.com/cometbft/cometbft) ⭐ 758 | 🐛 272 | 🌐 Go | 📅 2025-07-02 - A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm.
* [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) ⭐ 6,637 | 🐛 272 | 🌐 Go | 📅 2025-07-02 - A Framework for Building Public Blockchains in the Cosmos Ecosystem.
* [gno](https://github.com/gnolang/gno) ⭐ 972 | 🐛 800 | 🌐 Go | 📅 2025-07-03 - A comprehensive smart contract suite built with Golang and Gnolang, a deterministic, purpose-built Go variant for blockchains.
* [go-ethereum](https://github.com/ethereum/go-ethereum) ⭐ 49,229 | 🐛 309 | 🌐 Go | 📅 2025-07-02 - Official Go implementation of the Ethereum protocol.
* [gosemble](https://github.com/LimeChain/gosemble) ⭐ 14 | 🐛 29 | 🌐 Go | 📅 2025-03-10 - A Go-based framework for building Polkadot/Substrate-compatible runtimes.
* [gossamer](https://github.com/ChainSafe/gossamer) ⭐ 451 | 🐛 394 | 🌐 Go | 📅 2025-07-02 - A Go implementation of the Polkadot Host.
* [kubo](https://github.com/ipfs/kubo) ⭐ 16,549 | 🐛 1,104 | 🌐 Go | 📅 2025-07-02 - A blockchain framework implemented in Go. It provides content-addressable storage which can be used for decentralized storage in DApps. It is based on the IPFS protocol.
* [lnd](https://github.com/lightningnetwork/lnd) ⭐ 7,961 | 🐛 812 | 🌐 Go | 📅 2025-07-02 - A complete implementation of a Lightning Network node.
* [solana-go](https://github.com/gagliardetto/solana-go) ⭐ 1,346 | 🐛 140 | 🌐 Go | 📅 2025-03-14 - Go library to interface with Solana JSON RPC and WebSocket interfaces.
* [tendermint](https://github.com/tendermint/tendermint) ⭐ 5,809 | 🐛 23 | 🌐 Go | 📅 2025-06-24 - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.

**[⬆ back to top](#contents)**

## Bot Building

*Libraries for building and working with bots.*

* [arikawa](https://github.com/diamondburned/arikawa) ⭐ 525 | 🐛 35 | 🌐 Go | 📅 2025-07-02 - A library and framework for the Discord API.
* [bot](https://github.com/go-telegram/bot) ⭐ 1,213 | 🐛 12 | 🌐 Go | 📅 2025-05-21 - Zero-dependencies Telegram Bot library with additional UI components
* [echotron](https://github.com/NicoNex/echotron) ⭐ 405 | 🐛 0 | 🌐 Go | 📅 2025-03-19 - An elegant and concurrent library for Telegram Bots in Go.
* [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
* [go-sarah](https://github.com/oklahomer/go-sarah) ⭐ 263 | 🐛 0 | 🌐 Go | 📅 2024-12-01 - Framework to build a bot for desired chat services including LINE, Slack, Gitter, and more.
* [go-tg](https://github.com/mr-linch/go-tg) ⭐ 118 | 🐛 9 | 🌐 Go | 📅 2024-11-25 - Generated from official docs Go client library for accessing Telegram Bot API, with batteries for building complex bots included.
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) ⭐ 377 | 🐛 8 | 🌐 Go | 📅 2024-09-29 - Library to write bots for twitch.tv chat
* [micha](https://github.com/onrik/micha) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2025-05-15 - Go Library for Telegram bot api.
* [slack-bot](https://github.com/innogames/slack-bot) ⭐ 198 | 🐛 8 | 🌐 Go | 📅 2025-07-02 - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
* [slacker](https://github.com/slack-io/slacker) ⭐ 54 | 🐛 9 | 🌐 Go | 📅 2024-11-16 - Easy to use framework to create Slack bots.
* [telebot](https://github.com/tucnak/telebot) ⭐ 4,379 | 🐛 55 | 🌐 Go | 📅 2025-05-28 - Telegram bot framework is written in Go.
* [telego](https://github.com/mymmrac/telego) ⭐ 730 | 🐛 3 | 🌐 Go | 📅 2025-07-01 - Telegram Bot API library for Golang with full one-to-one API implementation.
* [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) ⭐ 6,192 | 🐛 168 | 🌐 Go | 📅 2024-08-14 - Simple and clean Telegram bot client.
* [wayback](https://github.com/wabarc/wayback) ⭐ 1,990 | 🐛 55 | 🌐 Go | 📅 2025-06-30 - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages.

**[⬆ back to top](#contents)**

## Build Automation

*Libraries and tools help with build automation.*

* [1build](https://github.com/gopinath-langote/1build) ⭐ 233 | 🐛 33 | 🌐 Go | 📅 2025-06-05 - Command line tool to frictionlessly manage project-specific commands.
* [air](https://github.com/cosmtrek/air) ⭐ 20,914 | 🐛 178 | 🌐 Go | 📅 2025-05-31 - Air - Live reload for Go apps.
* [anko](https://github.com/GuilhermeCaruso/anko) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2021-03-28 - Simple application watcher for multiple programming languages.
* [gaper](https://github.com/maxclaus/gaper) ⭐ 81 | 🐛 2 | 🌐 Go | 📅 2023-08-08 - Builds and restarts a Go project when it crashes or some watched file changes.
* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
* [gob](https://github.com/kcmvp/gob) ⭐ 13 | 🐛 14 | 🌐 Go | 📅 2025-02-18 - [Gradle](https://docs.gradle.org/)/[Maven](https://maven.apache.org/) like build tool for Go projects.
* [goyek](https://github.com/goyek/goyek) ⭐ 629 | 🐛 2 | 🌐 Go | 📅 2025-06-30 - Create build pipelines in Go.
* [mage](https://github.com/magefile/mage) ⭐ 4,373 | 🐛 128 | 🌐 Go | 📅 2025-06-15 - Mage is a make/rake-like build tool using Go.
* [mmake](https://github.com/tj/mmake) ⭐ 1,727 | 🐛 11 | 🌐 Go | 📅 2023-07-01 - Modern Make.
* [realize](https://github.com/tockins/realize) ⭐ 4,460 | 🐛 72 | 🌐 Go | 📅 2021-05-14 - Go build a system with file watchers and live to reload. Run, build and watch file changes with custom paths.
* [Task](https://github.com/go-task/task) ⭐ 13,056 | 🐛 393 | 🌐 Go | 📅 2025-06-30 - simple "Make" alternative.
* [taskctl](https://github.com/taskctl/taskctl) ⭐ 312 | 🐛 6 | 🌐 Go | 📅 2025-01-18 - Concurrent task runner.
* [xc](https://github.com/joerdav/xc) ⭐ 1,298 | 🐛 16 | 🌐 Go | 📅 2025-05-06 - Task runner with README.md defined tasks, executable markdown.

**[⬆ back to top](#contents)**

## Command Line

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) ⭐ 2,840 | 🐛 11 | 🌐 Go | 📅 2024-10-26 - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [aurora](https://github.com/logrusorgru/aurora) ⭐ 1,456 | 🐛 2 | 🌐 Go | 📅 2025-01-07 - ANSI terminal colors that support fmt.Printf/Sprintf.
* [box-cli-maker](https://github.com/Delta456/box-cli-maker) ⭐ 565 | 🐛 7 | 🌐 Go | 📅 2025-02-02 - Make Highly Customized Boxes for your CLI.
* [bubble-table](https://github.com/Evertras/bubble-table) ⭐ 502 | 🐛 16 | 🌐 Go | 📅 2024-10-31 - An interactive table component for bubbletea.
* [bubbles](https://github.com/charmbracelet/bubbles) ⭐ 6,517 | 🐛 153 | 🌐 Go | 📅 2025-06-29 - TUI components for bubbletea.
* [bubbletea](https://github.com/charmbracelet/bubbletea) ⭐ 32,812 | 🐛 120 | 🌐 Go | 📅 2025-06-30 - Go framework to build terminal apps, based on The Elm Architecture.
* [cfmt](https://github.com/mingrammer/cfmt) ⭐ 106 | 🐛 1 | 🌐 Go | 📅 2018-12-07 - Contextual fmt inspired by bootstrap color classes.
* [cfmt](https://github.com/i582/cfmt) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2021-07-01 - Simple and convenient formatted stylized output fully compatible with fmt library.
* [chalk](https://github.com/ttacon/chalk) ⭐ 465 | 🐛 2 | 🌐 Go | 📅 2019-08-28 - Intuitive package for prettifying terminal/console output.
* [crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2022-07-21 - Dynamic configuration file templating tool for kubernetes manifest or general configuration files.
* [ctc](https://github.com/wzshiming/ctc) ⭐ 50 | 🐛 1 | 🌐 Go | 📅 2023-02-25 - The non-invasive cross-platform terminal color library does not need to modify the Print method.
* [fx](https://github.com/antonmedv/fx) ⭐ 19,639 | 🐛 5 | 🌐 Go | 📅 2025-06-25 - Terminal JSON viewer & processor.
* [go-ataman](https://github.com/workanator/go-ataman) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2020-12-23 - Go library for rendering ANSI colored text templates in terminals.
* [go-colorable](https://github.com/mattn/go-colorable) ⭐ 792 | 🐛 9 | 🌐 Go | 📅 2025-01-10 - Colorable writer for windows.
* [go-colortext](https://github.com/daviddengcn/go-colortext) ⭐ 216 | 🐛 3 | 🌐 Go | 📅 2020-03-29 - Go library for color output in terminals.
* [go-isatty](https://github.com/mattn/go-isatty) ⭐ 864 | 🐛 14 | 🌐 Go | 📅 2024-08-03 - isatty for golang.
* [go-palette](https://github.com/abusomani/go-palette) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2023-03-09 - Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts.
* [go-prompt](https://github.com/c-bata/go-prompt) ⭐ 5,380 | 🐛 115 | 🌐 Go | 📅 2024-07-14 - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) ⭐ 9,794 | 🐛 673 | 🌐 Python | 📅 2025-04-15.
* [gocui](https://github.com/jroimartin/gocui) ⭐ 10,280 | 🐛 60 | 🌐 Go | 📅 2025-05-01 - Minimalist Go library aimed at creating Console User Interfaces.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) ⭐ 553 | 🐛 12 | 🌐 Go | 📅 2023-12-20 - Style terminal text.
* [gookit/color](https://github.com/gookit/color) ⭐ 1,546 | 🐛 5 | 🌐 Go | 📅 2025-06-07 - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
* [lipgloss](https://github.com/charmbracelet/lipgloss) ⭐ 9,195 | 🐛 86 | 🌐 Go | 📅 2025-06-30 - Declaratively define styles for color, format and layout in the terminal.
* [marker](https://github.com/cyucelen/marker) ⭐ 51 | 🐛 4 | 🌐 Go | 📅 2023-10-03 - Easiest way to match and mark strings for colorful terminal outputs.
* [mpb](https://github.com/vbauerster/mpb) ⭐ 2,410 | 🐛 17 | 🌐 Go | 📅 2025-06-05 - Multi progress bar for terminal applications.
* [progressbar](https://github.com/schollz/progressbar) ⭐ 4,433 | 🐛 13 | 🌐 Go | 📅 2025-02-08 - Basic thread-safe progress bar that works in every OS.
* [pterm](https://github.com/pterm/pterm) ⭐ 5,128 | 🐛 59 | 🌐 Go | 📅 2025-06-07 - A library to beautify console output on every platform with many combinable components.
* [simpletable](https://github.com/alexeyco/simpletable) ⭐ 540 | 🐛 5 | 🌐 Go | 📅 2021-04-23 - Simple tables in a terminal with Go.
* [spinner](https://github.com/briandowns/spinner) ⭐ 2,443 | 🐛 17 | 🌐 Go | 📅 2025-01-20 - Go package to easily provide a terminal spinner with options.
* [tabby](https://github.com/cheynewallace/tabby) ⭐ 358 | 🐛 4 | 🌐 Go | 📅 2020-12-23 - A tiny library for super simple Golang tables.
* [table](https://github.com/tomlazar/table) ⭐ 50 | 🐛 1 | 🌐 Go | 📅 2023-05-19 - Small library for terminal color based tables.
* [termbox-go](https://github.com/nsf/termbox-go) ⭐ 4,730 | 🐛 50 | 🌐 Go | 📅 2022-02-08 - Termbox is a library for creating cross-platform text-based interfaces.
* [termdash](https://github.com/mum4k/termdash) ⭐ 2,839 | 🐛 46 | 🌐 Go | 📅 2024-09-24 - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui) ⭐ 13,376 | 🐛 105 | 🌐 Go | 📅 2024-07-22.
* [termenv](https://github.com/muesli/termenv) ⭐ 1,854 | 🐛 37 | 🌐 Go | 📅 2025-05-05 - Advanced ANSI style & color support for your terminal applications.
* [termui](https://github.com/gizak/termui) ⭐ 13,376 | 🐛 105 | 🌐 Go | 📅 2024-07-22 - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib) ⭐ 15,615 | 🐛 97 | 🌐 JavaScript | 📅 2024-01-09.
* [uilive](https://github.com/gosuri/uilive) ⭐ 1,706 | 🐛 12 | 🌐 Go | 📅 2023-07-22 - Library for updating terminal output in real time.
* [uiprogress](https://github.com/gosuri/uiprogress) ⭐ 2,130 | 🐛 28 | 🌐 Go | 📅 2024-02-29 - Flexible library to render progress bars in terminal applications.
* [uitable](https://github.com/gosuri/uitable) ⭐ 741 | 🐛 8 | 🌐 Go | 📅 2022-10-18 - Library to improve readability in terminal apps using tabular data.
* [yacspin](https://github.com/theckman/yacspin) ⭐ 450 | 🐛 6 | 🌐 Go | 📅 2022-01-03 - Yet Another CLi Spinner package, for working with terminal spinners.

**[⬆ back to top](#contents)**

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [acmd](https://github.com/cristalhq/acmd) ⭐ 126 | 🐛 1 | 🌐 Go | 📅 2024-04-26 - Simple, useful, and opinionated CLI package in Go.
* [argparse](https://github.com/akamensky/argparse) ⭐ 623 | 🐛 8 | 🌐 Go | 📅 2022-10-31 - Command line argument parser inspired by Python's argparse module.
* [argv](https://github.com/cosiner/argv) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2020-04-16 - Go library to split command line string as arguments array using the bash syntax.
* [carapace](https://github.com/rsteube/carapace) ⭐ 722 | 🐛 40 | 🌐 Go | 📅 2025-07-01 - Command argument completion generator for spf13/cobra.
* [carapace-bin](https://github.com/rsteube/carapace-bin) ⭐ 1,330 | 🐛 74 | 🌐 Go | 📅 2025-07-02 - Multi-shell multi-command argument completer.
* [carapace-spec](https://github.com/rsteube/carapace-spec) ⭐ 21 | 🐛 15 | 🌐 Go | 📅 2025-06-30 - Define simple completions using a spec file.
* [climax](https://github.com/tucnak/climax) ⭐ 219 | 🐛 7 | 🌐 Go | 📅 2020-09-05 - Alternative CLI with "human face", in spirit of Go command.
* [clîr](https://github.com/leaanthony/clir) ⭐ 193 | 🐛 6 | 🌐 Go | 📅 2024-06-10 - A Simple and Clear CLI library. Dependency free.
* [cmd](https://github.com/posener/cmd) ⭐ 43 | 🐛 1 | 🌐 Go | 📅 2020-09-27 - Extends the standard `flag` package to support sub commands and more in idiomatic way.
* [cmdr](https://github.com/hedzr/cmdr) ⭐ 140 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - A POSIX/GNU style, getopt-like command-line UI Go library.
* [cobra](https://github.com/spf13/cobra) ⭐ 41,002 | 🐛 318 | 🌐 Go | 📅 2025-05-31 - Commander for modern Go CLI interactions.
* [command-chain](https://github.com/rainu/go-command-chain) ⭐ 67 | 🐛 0 | 🌐 Go | 📅 2023-05-03 - A go library for configure and run command chains - such as pipelining in unix shells.
* [commandeer](https://github.com/jaffee/commandeer) ⭐ 176 | 🐛 5 | 🌐 Go | 📅 2022-09-20 - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* [complete](https://github.com/posener/complete) ⭐ 938 | 🐛 24 | 🌐 Go | 📅 2025-03-06 - Write bash completions in Go + Go command bash completion.
* [console](https://github.com/reeflective/console) ⭐ 96 | 🐛 1 | 🌐 Go | 📅 2025-05-05 Closed-loop application library for Cobra commands, with oh-my-posh prompts, and more.
* [Dnote](https://github.com/dnote/dnote) ⭐ 2,885 | 🐛 60 | 🌐 Go | 📅 2024-07-01 - A simple command line notebook with multi-device sync.
* [elvish](https://github.com/elves/elvish) ⭐ 6,048 | 🐛 337 | 🌐 Go | 📅 2025-06-29 - An expressive programming language and a versatile interactive shell.
* [env](https://github.com/codingconcepts/env) ⭐ 120 | 🐛 2 | 🌐 Go | 📅 2024-06-18 - Tag-based environment configuration for structs.
* [flaggy](https://github.com/integrii/flaggy) ⭐ 861 | 🐛 20 | 🌐 Go | 📅 2023-04-03 - A robust and idiomatic flags package with excellent subcommand support.
* [flagvar](https://github.com/sgreben/flagvar) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2024-09-26 - A collection of flag argument types for Go's standard `flag` package.
* [getopt](https://github.com/jon-codes/getopt) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2025-04-26 - An accurate Go `getopt`, validated against the GNU libc implementation.
* [go-arg](https://github.com/alexflint/go-arg) ⭐ 2,158 | 🐛 29 | 🌐 Go | 📅 2025-05-24 - Struct-based argument parsing in Go.
* [go-flags](https://github.com/jessevdk/go-flags) ⭐ 2,663 | 🐛 63 | 🌐 Go | 📅 2024-07-26 - go command line option parser.
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) ⭐ 61 | 🐛 2 | 🌐 Go | 📅 2025-04-15 - Go option parser inspired by the flexibility of Perl’s GetOpt::Long.
* [go-readline-ny](https://github.com/nyaosorg/go-readline-ny) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2025-06-25 - A customizable line-editing library with Emacs keybindings, Unicode support, completion, and syntax highlighting. Used in NYAGOS shell.
* [gocmd](https://github.com/devfacet/gocmd) ⭐ 66 | 🐛 1 | 🌐 Go | 📅 2023-04-04 - Go library for building command line applications.
* [goopt](https://github.com/napalu/goopt) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-06-30 - A declarative, struct-tag based CLI framework for Go, with a broad feature set such as hierarchical commands/flags, i18n, shell completion, and validation.
* [hashicorp/cli](https://github.com/hashicorp/cli) ⭐ 25 | 🐛 3 | 🌐 Go | 📅 2025-06-30 - Go library for implementing command-line interfaces.
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) ⭐ 181 | 🐛 2 | 🌐 Go | 📅 2025-06-19 - cli application framework with auto configuration and dependency injection.
* [job](https://github.com/liujianping/job) ⭐ 148 | 🐛 1 | 🌐 Shell | 📅 2020-06-30 - JOB, make your short-term command as a long-term job.
* [kingpin](https://github.com/alecthomas/kingpin) ⭐ 3,538 | 🐛 28 | 🌐 Go | 📅 2025-06-06 - Command line and flag parser supporting sub commands (superseded by `kong`; see below).
* [liner](https://github.com/peterh/liner) ⭐ 1,064 | 🐛 18 | 🌐 Go | 📅 2023-06-23 - Go readline-like library for command-line interfaces.
* [mcli](https://github.com/jxskiss/mcli) ⭐ 41 | 🐛 2 | 🌐 Go | 📅 2024-04-06 - A minimal but very powerful cli library for Go.
* [mkideal/cli](https://github.com/mkideal/cli) ⭐ 729 | 🐛 4 | 🌐 Go | 📅 2024-02-04 - Feature-rich and easy to use command-line package based on golang struct tags.
* [mow.cli](https://github.com/jawher/mow.cli) ⭐ 886 | 🐛 34 | 🌐 Go | 📅 2024-03-07 - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [ops](https://github.com/nanovms/ops) ⭐ 1,363 | 🐛 140 | 🌐 Go | 📅 2025-06-29 - Unikernel Builder/Orchestrator.
* [pflag](https://github.com/spf13/pflag) ⭐ 2,584 | 🐛 178 | 🌐 Go | 📅 2025-06-28 - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [readline](https://github.com/reeflective/readline) ⭐ 119 | 🐛 2 | 🌐 Go | 📅 2025-05-04 - Shell library with modern and easy to use UI features.
* [sand](https://github.com/Zaba505/sand) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2018-11-21 - Simple API for creating interpreters and so much more.
* [sflags](https://github.com/octago/sflags) ⭐ 161 | 🐛 5 | 🌐 Go | 📅 2025-04-02 - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin, and other libraries.
* [strumt](https://github.com/antham/strumt) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2024-11-17 - Library to create prompt chain.
* [subcmd](https://github.com/bobg/subcmd) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2024-07-03 - Another approach to parsing and running subcommands. Works alongside the standard `flag` package.
* [teris-io/cli](https://github.com/teris-io/cli) ⭐ 131 | 🐛 2 | 🌐 Go | 📅 2021-05-09 - Simple and complete API for building command line interfaces in Go.
* [ts](https://github.com/liujianping/ts) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2019-07-02 - Timestamp convert & compare tool.
* [ukautz/clif](https://github.com/ukautz/clif) ⭐ 129 | 🐛 3 | 🌐 Go | 📅 2019-02-18 - Small command line interface framework.
* [urfave/cli](https://github.com/urfave/cli) ⭐ 23,300 | 🐛 50 | 🌐 Go | 📅 2025-06-14 - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [version](https://github.com/mszostok/version) ⭐ 109 | 🐛 19 | 🌐 Go | 📅 2023-07-24 - Collects and displays CLI version information in multiple formats along with upgrade notice.
* [wlog](https://github.com/dixonwille/wlog) ⭐ 67 | 🐛 1 | 🌐 Go | 📅 2024-11-25 - Simple logging interface that supports cross-platform color and concurrency.
* [wmenu](https://github.com/dixonwille/wmenu) ⭐ 224 | 🐛 3 | 🌐 Go | 📅 2024-11-25 - Easy to use menu structure for cli applications that prompt users to make choices.

**[⬆ back to top](#contents)**

## Configuration

*Libraries for configuration parsing.*

* [aconfig](https://github.com/cristalhq/aconfig) ⭐ 593 | 🐛 17 | 🌐 Go | 📅 2025-06-19 - Simple, useful and opinionated config loader.
* [bcl](https://github.com/wkhere/bcl) ⭐ 26 | 🐛 3 | 🌐 Go | 📅 2025-07-01 - BCL is a configuration language similar to HCL.
* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) ⭐ 1,858 | 🐛 48 | 🌐 Go | 📅 2025-01-05 - Minimalistic configuration reader (from files, ENV, and wherever you want).
* [config](https://github.com/JeremyLoy/config) ⭐ 337 | 🐛 2 | 🌐 Go | 📅 2022-05-30 - Cloud native application configuration. Bind ENV to structs in only two lines.
* [config](https://github.com/num30/config) ⭐ 58 | 🐛 4 | 🌐 Go | 📅 2025-02-23 - configure your app using file, environment variables, or flags in two lines of code
* [configuration](https://github.com/BoRuDar/configuration) ⭐ 108 | 🐛 0 | 🌐 Go | 📅 2025-01-20 - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
* [configure](https://github.com/paked/configure) ⭐ 55 | 🐛 2 | 🌐 Go | 📅 2019-02-18 - Provides configuration through multiple sources, including JSON, flags and environment variables.
* [configuro](https://github.com/sherifabdlnaby/configuro) ⭐ 94 | 🐛 1 | 🌐 Go | 📅 2022-09-26 - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
* [confiq](https://github.com/greencoda/confiq) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2025-02-02 - Structured data format to config struct decoder library for Go - supporting multiple data formats
* [confita](https://github.com/heetch/confita) ⭐ 505 | 🐛 21 | 🌐 Go | 📅 2025-06-27 - Load configuration in cascade from multiple backends into a struct.
* [conflate](https://github.com/the4thamigo-uk/conflate) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2023-07-26 - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
* [env](https://github.com/caarlos0/env) ⭐ 5,601 | 🐛 9 | 🌐 Go | 📅 2025-05-05 - Parse environment variables to Go structs (with defaults).
* [env](https://github.com/junk1tm/env) ⭐ 70 | 🐛 5 | 🌐 Go | 📅 2024-08-15 - A lightweight package for loading environment variables into structs.
* [env](https://github.com/syntaqx/env) ⭐ 6 | 🐛 1 | 🌐 Go | 📅 2024-12-18 - An environment utility package with support for unmarshaling into structs
* [envconfig](https://github.com/vrischmann/envconfig) ⭐ 244 | 🐛 1 | 🌐 Go | 📅 2025-01-31 - Read your configuration from environment variables.
* [envh](https://github.com/antham/envh) ⭐ 100 | 🐛 0 | 🌐 Go | 📅 2024-11-26 - Helpers to manage environment variables.
* [envyaml](https://github.com/yuseferi/envyaml) ⭐ 13 | 🐛 2 | 🌐 Go | 📅 2025-01-09 - Yaml with environment variables reader. it helps to have secrets as environment variable but load them configs as structured Yaml.
* [fig](https://github.com/kkyr/fig) ⭐ 381 | 🐛 5 | 🌐 Go | 📅 2025-06-03 - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
* [genv](https://github.com/sakirsensoy/genv) ⭐ 42 | 🐛 1 | 🌐 Go | 📅 2025-02-28 - Read environment variables easily with dotenv support.
* [go-array](https://github.com/deatil/go-array) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2024-04-20 - A Go package that read or set data from map, slice or json.
* [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) ⭐ 61 | 🐛 1 | 🌐 Go | 📅 2024-04-19 - Go package that fetches parameters from AWS System Manager - Parameter Store.
* [go-cfg](https://github.com/dsbasko/go-cfg) ⭐ 46 | 🐛 2 | 🌐 Go | 📅 2024-08-01 - The library provides a unified way to read configuration data into a structure from various sources, such as env, flags, and configuration files (.json, .yaml, .toml, .env).
* [go-conf](https://github.com/ThomasObenaus/go-conf) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2025-01-28 - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters.
* [go-ini](https://github.com/subpop/go-ini) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2025-06-06 - A Go package that marshals and unmarshals INI-files.
* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) ⭐ 22 | 🐛 7 | 🌐 Go | 📅 2023-10-09 - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
* [go-up](https://github.com/ufoscout/go-up) ⭐ 43 | 🐛 1 | 🌐 Go | 📅 2020-01-14 - A simple configuration library with recursive placeholders resolution and no magic.
* [GoCfg](https://github.com/Jagerente/gocfg) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2025-06-18 - Config manager with Struct Tags based contracts, custom value providers, parsers, and documentation generation. Customizable yet simple.
* [godotenv](https://github.com/joho/godotenv) ⭐ 9,430 | 🐛 77 | 🌐 Go | 📅 2024-12-16 - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [gofigure](https://github.com/ian-kent/gofigure) ⭐ 68 | 🐛 1 | 🌐 Go | 📅 2019-09-15 - Go application configuration made easy.
* [GoLobby/Config](https://github.com/golobby/config) ⭐ 365 | 🐛 2 | 🌐 Go | 📅 2023-01-05 - GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2021-05-24 - Modular JSON configuration. Keep your config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [gonfig](https://github.com/milad-abbasi/gonfig) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2021-08-02 - Tag-based configuration parser which loads values from different providers into typesafe struct.
* [gookit/config](https://github.com/gookit/config) ⭐ 557 | 🐛 10 | 🌐 Go | 📅 2025-04-25 - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
* [harvester](https://github.com/beatlabs/harvester) ⭐ 132 | 🐛 1 | 🌐 Go | 📅 2025-07-01 - Harvester, a easy to use static and dynamic configuration package supporting seeding, env vars and Consul integration.
* [hedzr/store](https://github.com/hedzr/store) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2025-06-29 - Extensible, high-performance configuration management library, optimized for hierarchical data.
* [hjson](https://github.com/hjson/hjson-go) ⭐ 336 | 🐛 4 | 🌐 Go | 📅 2025-04-21 - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* [hocon](https://github.com/gurkankaymak/hocon) ⭐ 85 | 🐛 13 | 🌐 Go | 📅 2025-03-07 - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
* [ingo](https://github.com/schachmat/ingo) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2017-04-03 - Flags persisted in an ini-like config file.
* [ini](https://github.com/go-ini/ini) ⭐ 3,511 | 🐛 64 | 🌐 Go | 📅 2024-05-01 - Go package to read and write INI files.
* [ini](https://github.com/wlevene/ini) ⭐ 17 | 🐛 2 | 🌐 Go | 📅 2025-03-12 - INI Parser & Write Library, Unmarshal to Struct, Marshal to Json, Write File, watch file.
* [joshbetz/config](https://github.com/joshbetz/config) ⭐ 215 | 🐛 0 | 🌐 Go | 📅 2021-11-12 - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) ⭐ 5,253 | 🐛 56 | 🌐 Go | 📅 2025-06-28 - Go library for managing configuration data from environment variables.
* [koanf](https://github.com/knadh/koanf) ⭐ 3,270 | 🐛 11 | 🌐 Go | 📅 2025-06-30 - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
* [konf](https://github.com/nil-go/konf) ⭐ 324 | 🐛 4 | 🌐 Go | 📅 2025-06-30 - The simplest API for reading/watching config from file, env, flag and clouds (e.g. AWS, Azure, GCP).
* [konfig](https://github.com/lalamove/konfig) ⭐ 645 | 🐛 5 | 🌐 Go | 📅 2020-10-28 - Composable, observable and performant config handling for Go for the distributed processing era.
* [kong](https://github.com/alecthomas/kong) ⭐ 2,704 | 🐛 27 | 🌐 Go | 📅 2025-06-30 - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (successor to `kingpin`).
* [mini](https://github.com/sasbury/mini) ⭐ 37 | 🐛 1 | 🌐 Go | 📅 2018-12-26 - Golang package for parsing ini-style configuration files.
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2024-10-31 - Simple useful package for read environment variables.
* [nfigure](https://github.com/muir/nfigure) ⭐ 8 | 🐛 5 | 🌐 Go | 📅 2025-07-02 - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML
* [onion](https://github.com/goraz/onion) ⭐ 118 | 🐛 10 | 🌐 Go | 📅 2023-03-07 - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
* [piper](https://github.com/Yiling-J/piper) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2021-12-03 - Viper wrapper with config inheritance and key generation.
* [sonic](https://github.com/bytedance/sonic) ⭐ 8,299 | 🐛 22 | 🌐 Go | 📅 2025-06-19 - A blazingly fast JSON serializing & deserializing library.
* [store](https://github.com/tucnak/store) ⭐ 275 | 🐛 4 | 🌐 Go | 📅 2023-07-14 - Lightweight configuration manager for Go.
* [swap](https://github.com/oblq/swap) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2025-04-04 - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
* [typenv](https://github.com/diegomarangoni/typenv) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-04-02 - Minimalistic, zero dependency, typed environment variables library.
* [uConfig](https://github.com/omeid/uconfig) ⭐ 71 | 🐛 1 | 🌐 Go | 📅 2024-04-23 - Lightweight, zero-dependency, and extendable configuration management.
* [viper](https://github.com/spf13/viper) ⭐ 28,792 | 🐛 518 | 🌐 Go | 📅 2025-06-27 - Go configuration with fangs.
* [xdg](https://github.com/adrg/xdg) ⭐ 838 | 🐛 5 | 🌐 Go | 📅 2025-06-04 - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
* [yamagiconf](https://github.com/romshark/yamagiconf) ⭐ 18 | 🐛 2 | 🌐 Go | 📅 2025-02-01 - The "safe subset" of YAML for Go configs.
* [zerocfg](https://github.com/chaindead/zerocfg) ⭐ 190 | 🐛 4 | 🌐 Go | 📅 2025-05-08 - Zero-effort, concise configuration management that avoids boilerplate and repetitive code, supports multiple sources with priority overrides.

**[⬆ back to top](#contents)**

## Continuous Integration

*Tools for help with continuous integration.*

* [abstruse](https://github.com/bleenco/abstruse) ⭐ 951 | 🐛 35 | 🌐 Go | 📅 2024-01-31 - Abstruse is a distributed CI platform.
* [Bencher](https://bencher.dev/) - A suite of continuous benchmarking tools designed to catch performance regressions in CI.
* [CDS](https://github.com/ovh/cds) ⭐ 4,727 | 🐛 149 | 🌐 Go | 📅 2025-07-02 - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
* [dot](https://github.com/opnlabs/dot) ⭐ 24 | 🐛 5 | 🌐 Go | 📅 2024-08-01 - A minimal, local first continuous integration system that uses Docker to run jobs concurrently in stages.
* [drone](https://github.com/drone/drone) ⭐ 32,929 | 🐛 74 | 🌐 Go | 📅 2025-07-02 - Drone is a Continuous Integration platform built on Docker, written in Go.
* [go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) ⭐ 16 | 🐛 7 | 🌐 JavaScript | 📅 2024-05-22 - A GitHub Action to track code coverage in your pull requests, with a beautiful HTML preview, for free.
* [go-fuzz-action](https://github.com/jidicula/go-fuzz-action) ⭐ 17 | 🐛 2 | 📅 2024-03-11 - Use Go 1.18's built-in fuzz testing in GitHub Actions.
* [go-semver-release](https://github.com/s0ders/go-semver-release) ⭐ 17 | 🐛 4 | 🌐 Go | 📅 2025-07-02 - Automate the semantic versioning of Git repositories.
* [go-test-coverage](https://github.com/vladopajic/go-test-coverage) ⭐ 157 | 🐛 4 | 🌐 Go | 📅 2025-06-16 - Tool and GitHub action which reports issues when test coverage is below set threshold.
* [gomason](https://github.com/nikogura/gomason) ⭐ 65 | 🐛 3 | 🌐 Go | 📅 2024-07-02 - Test, Build, Sign, and Publish your go binaries from a clean workspace.
* [gotestfmt](https://github.com/GoTestTools/gotestfmt) ⭐ 566 | 🐛 6 | 🌐 Go | 📅 2023-06-06 - go test output for humans.
* [goveralls](https://github.com/mattn/goveralls) ⭐ 790 | 🐛 19 | 🌐 Go | 📅 2023-04-26 - Go integration for Coveralls.io continuous code coverage tracking system.
* [muffet](https://github.com/raviqqe/muffet) ⭐ 2,569 | 🐛 24 | 🌐 Go | 📅 2025-07-02 - Fast website link checker in Go, see [alternatives](https://github.com/lycheeverse/lychee#features) ⭐ 2,794 | 🐛 95 | 🌐 Rust | 📅 2025-06-30.
* [overalls](https://github.com/go-playground/overalls) ⭐ 115 | 🐛 2 | 🌐 Go | 📅 2019-12-30 - Multi-Package go project coverprofile for tools like goveralls.
* [roveralls](https://github.com/LawrenceWoodman/roveralls) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2017-11-19 - Recursive coverage testing tool.
* [woodpecker](https://github.com/woodpecker-ci/woodpecker) ⭐ 5,207 | 🐛 346 | 🌐 Go | 📅 2025-07-03 - Woodpecker is a community fork of the Drone CI system.

**[⬆ back to top](#contents)**

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [go-libsass](https://github.com/wellington/go-libsass) ⭐ 212 | 🐛 17 | 🌐 C++ | 📅 2023-12-05 - Go wrapper to the 100% Sass compatible libsass project.

**[⬆ back to top](#contents)**

## Data Integration Frameworks

*Frameworks for performing ELT / ETL*

* [Benthos](https://github.com/benthosdev/benthos) ⭐ 8,392 | 🐛 528 | 🌐 Go | 📅 2025-07-03 - A message streaming bridge between a range of protocols.
* [CloudQuery](http://github.com/cloudquery/cloudquery) ⭐ 6,132 | 🐛 135 | 🌐 Go | 📅 2025-07-02 - A high-performance ELT data integration framework with pluggable architecture.
* [omniparser](https://github.com/jf-tech/omniparser) ⭐ 1,050 | 🐛 0 | 🌐 Go | 📅 2025-02-21 - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.

**[⬆ back to top](#contents)**

## Data Structures and Algorithms

### Bit-packing and Compression

* [bingo](https://github.com/iancmcc/bingo) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2024-12-09 - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes.
* [binpacker](https://github.com/zhuangsirui/binpacker) ⭐ 231 | 🐛 1 | 🌐 Go | 📅 2021-10-08 - Binary packer and unpacker helps user build custom binary stream.
* [bit](https://github.com/yourbasic/bit) ⭐ 163 | 🐛 1 | 🌐 Go | 📅 2022-12-29 - Golang set data structure with bonus bit-twiddling functions.
* [crunch](https://github.com/superwhiskers/crunch) ⭐ 100 | 🐛 0 | 🌐 Go | 📅 2023-01-14 - Go package implementing buffers for handling various datatypes easily.
* [go-ef](https://github.com/amallia/go-ef) ⭐ 39 | 🐛 2 | 🌐 Go | 📅 2024-06-16 - A Go implementation of the Elias-Fano encoding.
* [roaring](https://github.com/RoaringBitmap/roaring) ⭐ 2,725 | 🐛 72 | 🌐 Go | 📅 2025-06-28 - Go package implementing compressed bitsets.

### Bit Sets

* [bitmap](https://github.com/kelindar/bitmap) ⭐ 339 | 🐛 9 | 🌐 Assembly | 📅 2025-06-28 - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go.
* [bitset](https://github.com/bits-and-blooms/bitset) ⭐ 1,428 | 🐛 3 | 🌐 Go | 📅 2025-06-01 - Go package implementing bitsets.

### Bloom and Cuckoo Filters

* [bloom](https://github.com/bits-and-blooms/bloom) ⭐ 2,617 | 🐛 18 | 🌐 Go | 📅 2024-12-10 - Go package implementing Bloom filters.
* [bloom](https://github.com/zhenjl/bloom) ⭐ 147 | 🐛 1 | 🌐 Go | 📅 2018-04-16 - Bloom filters implemented in Go.
* [bloom](https://github.com/yourbasic/bloom) ⭐ 87 | 🐛 0 | 🌐 Go | 📅 2017-06-19 - Golang Bloom filter implementation.
* [bloomfilter](https://github.com/OldPanda/bloomfilter) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2025-03-20 - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.
* [boomfilters](https://github.com/tylertreat/BoomFilters) ⭐ 1,615 | 🐛 13 | 🌐 Go | 📅 2025-06-30 - Probabilistic data structures for processing continuous, unbounded streams.
* [cuckoo-filter](https://github.com/linvon/cuckoo-filter) ⭐ 301 | 🐛 3 | 🌐 Go | 📅 2023-08-16 - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper are available.
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) ⭐ 1,180 | 🐛 15 | 🌐 Go | 📅 2024-07-15 - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* [ring](https://github.com/TheTannerRyan/ring) ⭐ 141 | 🐛 1 | 🌐 Go | 📅 2020-09-10 - Go implementation of a high performance, thread safe bloom filter.

### Data Structure and Algorithm Collections

* [algorithms](https://github.com/shady831213/algorithms) ⭐ 821 | 🐛 0 | 🌐 Go | 📅 2021-03-17 - Algorithms and data structures.CLRS study.
* [go-datastructures](https://github.com/Workiva/go-datastructures) ⭐ 7,813 | 🐛 30 | 🌐 Go | 📅 2024-05-16 - Collection of useful, performant, and thread-safe data structures.
* [gods](https://github.com/emirpasic/gods) ⭐ 16,992 | 🐛 67 | 🌐 Go | 📅 2025-03-12 - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [gostl](https://github.com/liyue201/gostl) ⭐ 1,096 | 🐛 4 | 🌐 Go | 📅 2025-01-03 - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.

### Iterators

* [goterator](https://github.com/yaa110/goterator) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2024-07-08 - Iterator implementation to provide map and reduce functionalities.
* [iter](https://github.com/disksing/iter) ⭐ 191 | 🐛 0 | 🌐 Go | 📅 2022-03-16 - Go implementation of C++ STL iterators and algorithms.

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for
additional ordered map implementations.

* [cmap](https://github.com/lrita/cmap) ⭐ 96 | 🐛 0 | 🌐 Go | 📅 2023-11-08 - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
* [dict](https://github.com/srfrog/dict) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2024-11-14 - Python-like dictionaries (dict) for Go.
* [go-shelve](https://github.com/lucmq/go-shelve) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2025-04-16 - A persistent, map-like object for the Go programming language. Supports multiple embedded key-value stores.
* [goradd/maps](https://github.com/goradd/maps) ⭐ 49 | 🐛 1 | 🌐 Go | 📅 2025-02-11 - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc.

### Miscellaneous Data Structures and Algorithms

* [concurrent-writer](https://github.com/free/concurrent-writer) ⭐ 57 | 🐛 0 | 🌐 Go | 📅 2017-11-17 - Highly concurrent drop-in replacement for `bufio.Writer`.
* [count-min-log](https://github.com/seiflotfy/count-min-log) ⭐ 67 | 🐛 1 | 🌐 Go | 📅 2025-03-04 - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* [fsm](https://github.com/cocoonspace/fsm) ⭐ 80 | 🐛 3 | 🌐 Go | 📅 2023-02-08 - Finite-State Machine package.
* [genfuncs](https://github.com/nwillc/genfuncs) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2022-08-07 - Go 1.18+ generics package inspired by Kotlin's Sequence and Map.
* [go-generics](https://github.com/bobg/go-generics) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2025-06-09 - Generic slice, map, set, iterator, and goroutine utilities.
* [go-geoindex](https://github.com/hailocab/go-geoindex) ⭐ 358 | 🐛 2 | 🌐 Go | 📅 2018-02-20 - In-memory geo index.
* [go-rampart](https://github.com/francesconi/go-rampart) ⭐ 100 | 🐛 0 | 🌐 Go | 📅 2024-06-26 - Determine how intervals relate to each other.
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) ⭐ 136 | 🐛 1 | 🌐 Go | 📅 2022-06-22 - Region quadtrees with efficient point location and neighbour finding.
* [go-tuple](https://github.com/barweiss/go-tuple) ⭐ 93 | 🐛 0 | 🌐 Go | 📅 2023-09-01 - Generic tuple implementation for Go 1.18+.
* [go18ds](https://github.com/daichi-m/go18ds) ⭐ 46 | 🐛 2 | 🌐 Go | 📅 2023-10-07 - Go Data Structures using Go 1.18 generics.
* [gofal](https://github.com/xxjwxc/gofal) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2019-10-08 - fractional api for Go.
* [gogu](https://github.com/esimov/gogu) ⭐ 105 | 🐛 2 | 🌐 Go | 📅 2023-03-04 - A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library.
* [gota](https://github.com/kniren/gota) ⭐ 3,202 | 🐛 81 | 🌐 Go | 📅 2023-08-09 - Implementation of dataframes, series, and data wrangling methods for Go.
* [hide](https://github.com/emvi/hide) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2021-11-09 - ID type with marshalling to/from hash to prevent sending IDs to clients.
* [hyperloglog](https://github.com/axiomhq/hyperloglog) ⭐ 983 | 🐛 5 | 🌐 Go | 📅 2025-05-19 - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [quadtree](https://github.com/s0rg/quadtree) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2025-04-25 - Generic, zero-alloc, 100%-test covered quadtree.
* [slices](https://github.com/twharmon/slices) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2022-07-08 - Pure, generic functions for slices.

### Nullable Types

* [nan](https://github.com/kak-tus/nan) ⭐ 87 | 🐛 0 | 🌐 Go | 📅 2023-07-06 - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
* [null](https://github.com/emvi/null) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2021-11-09 - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
* [typ](https://github.com/gurukami/typ) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2021-10-15 - Null Types, Safe primitive type conversion and fetching value from complex structures.

### Queues

* [deque](https://github.com/edwingeng/deque) ⭐ 200 | 🐛 0 | 🌐 Go | 📅 2023-09-14 - A highly optimized double-ended queue.
* [deque](https://github.com/gammazero/deque) ⭐ 688 | 🐛 6 | 🌐 Go | 📅 2025-05-01 - Fast ring-buffer deque (double-ended queue).
* [dqueue](https://github.com/vodolaz095/dqueue) ⭐ 0 | 🐛 1 | 🌐 Go | 📅 2025-05-04 - Simple, in memory, zero dependency and battle tested, thread-safe deferred queue.
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) ⭐ 427 | 🐛 5 | 🌐 Go | 📅 2023-05-12 - Concurrent FIFO queue.
* [hatchet](https://github.com/hatchet-dev/hatchet) ⭐ 5,781 | 🐛 81 | 🌐 TypeScript | 📅 2025-07-03 - Distributed, Fault-tolerant task queue.
* [memlog](https://github.com/embano1/memlog) ⭐ 133 | 🐛 0 | 🌐 Go | 📅 2025-06-06 - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka.
* [queue](https://github.com/adrianbrad/queue) ⭐ 310 | 🐛 1 | 🌐 Go | 📅 2025-05-13 - Multiple thread-safe, generic queue implementations for Go.

### Sets

* [dsu](https://github.com/ihebu/dsu) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2022-01-29 - Disjoint Set data structure implementation in Go.
* [golang-set](https://github.com/deckarep/golang-set) ⭐ 4,541 | 🐛 12 | 🌐 Go | 📅 2025-06-10 - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* [goset](https://github.com/zoumo/goset) ⭐ 52 | 🐛 0 | 🌐 Go | 📅 2020-12-11 - A useful Set collection implementation for Go.
* [set](https://github.com/StudioSol/set) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2022-09-08 - Simple set data structure implementation in Go using LinkedHashMap.

### Text Analysis

* [bleve](https://github.com/blevesearch/bleve) ⭐ 10,435 | 🐛 295 | 🌐 Go | 📅 2025-07-01 - Modern text indexing library for go.
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) ⭐ 392 | 🐛 0 | 🌐 Go | 📅 2024-12-16 - Go implementation of Adaptive Radix Tree.
* [go-edlib](https://github.com/hbollon/go-edlib) ⭐ 517 | 🐛 1 | 🌐 Go | 📅 2022-07-03 - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
* [levenshtein](https://github.com/agext/levenshtein) ⭐ 88 | 🐛 1 | 🌐 Go | 📅 2020-10-15 - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) ⭐ 407 | 🐛 3 | 🌐 Go | 📅 2025-05-19 - Implementation to calculate levenshtein distance in Go.
* [mspm](https://github.com/BlackRabbitt/mspm) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2018-05-19 - Multi-String Pattern Matching Algorithm for information retrieval.
* [parsefields](https://github.com/MonaxGT/parsefields) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2019-05-05 - Tools for parse JSON-like logs for collecting unique fields and events.
* [ptrie](https://github.com/viant/ptrie) ⭐ 43 | 🐛 2 | 🌐 Go | 📅 2024-04-05 - An implementation of prefix tree.
* [trie](https://github.com/derekparker/trie) ⭐ 775 | 🐛 13 | 🌐 Go | 📅 2025-05-14 - Trie implementation in Go.

### Trees

* [hashsplit](http://github.com/bobg/hashsplit) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2024-09-30 - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
* [merkle](https://github.com/bobg/merkle) ⭐ 19 | 🐛 2 | 🌐 Go | 📅 2024-07-10 - Space-efficient computation of Merkle root hashes and inclusion proofs.
* [skiplist](https://github.com/MauriceGit/skiplist) ⭐ 286 | 🐛 5 | 🌐 Go | 📅 2023-01-31 - Very fast Go Skiplist implementation.
* [skiplist](https://github.com/gansidui/skiplist) ⭐ 84 | 🐛 0 | 🌐 Go | 📅 2014-11-21 - Skiplist implementation in Go.
* [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
* [treemap](https://github.com/igrmk/treemap) ⭐ 63 | 🐛 2 | 🌐 Go | 📅 2022-03-22 - Generic key-sorted map using a red-black tree under the hood.

### Pipes

* [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) ⭐ 41 | 🐛 3 | 🌐 Go | 📅 2023-04-24 - Go module that processes work concurrently and returns output in a channel in the order of input.
* [parapipe](https://github.com/nazar256/parapipe) ⭐ 37 | 🐛 2 | 🌐 Go | 📅 2024-12-13 - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
* [pipeline](https://github.com/hyfather/pipeline) ⭐ 58 | 🐛 1 | 🌐 Go | 📅 2021-11-02 - An implementation of pipelines with fan-in and fan-out.
* [pipelines](https://github.com/nxdir-s/pipelines) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2025-05-23 - Generic pipeline functions for concurrent processing.

**[⬆ back to top](#contents)**

## Database

### Caches

*Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases.*

* [2q](https://github.com/floatdrop/2q) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2023-03-24 - 2Q in-memory cache implementation.
* [bcache](https://github.com/iwanbk/bcache) ⭐ 160 | 🐛 4 | 🌐 Go | 📅 2023-01-13 - Eventually consistent distributed in-memory cache Go library.
* [BigCache](https://github.com/allegro/bigcache) ⭐ 7,866 | 🐛 99 | 🌐 Go | 📅 2025-05-05 - Efficient key/value cache for gigabytes of data.
* [cache](https://github.com/akyoto/cache) ⚠️ Archived - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
* [cache2go](https://github.com/muesli/cache2go) ⭐ 2,157 | 🐛 35 | 🌐 Go | 📅 2024-07-02 - In-memory key:value cache which supports automatic invalidation based on timeouts.
* [cachego](https://github.com/faabiosr/cachego) ⭐ 373 | 🐛 0 | 🌐 Go | 📅 2025-04-01 - Golang Cache component for multiple drivers.
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) ⭐ 45 | 🐛 2 | 🌐 Go | 📅 2018-01-22 - BigCache with clustering support and individual item expiration.
* [coherence-go-client](https://github.com/oracle/coherence-go-client) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-06-22 - Full implementation of Oracle Coherence cache API for Go applications using gRPC as network transport.
* [couchcache](https://github.com/codingsince1985/couchcache) ⭐ 67 | 🐛 1 | 🌐 Go | 📅 2024-06-16 - RESTful caching micro-service backed by Couchbase server.
* [EchoVault](https://github.com/EchoVault/EchoVault) ⭐ 494 | 🐛 21 | 🌐 Go | 📅 2025-04-24 - Embeddable Distributed in-memory data store compatible with Redis clients.
* [fastcache](https://github.com/VictoriaMetrics/fastcache) ⭐ 2,234 | 🐛 49 | 🌐 Go | 📅 2025-06-03 - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
* [GCache](https://github.com/bluele/gcache) ⭐ 2,689 | 🐛 28 | 🌐 Go | 📅 2024-03-01 - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [gdcache](https://github.com/ulovecode/gdcache) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2021-10-14 - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache.
* [go-cache](https://github.com/viney-shih/go-cache) ⭐ 157 | 🐛 3 | 🌐 Go | 📅 2023-08-30 - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern.
* [go-freelru](https://github.com/elastic/go-freelru) ⭐ 242 | 🐛 16 | 🌐 Go | 📅 2025-06-08 A GC-less, fast and generic LRU hashmap library with optional locking, sharding, eviction and expiration.
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) ⭐ 98 | 🐛 1 | 🌐 Go | 📅 2025-06-03 - Fast in-memory key:value store/cache library. Pointer caches.
* [gocache](https://github.com/eko/gocache) ⭐ 2,684 | 🐛 39 | 🌐 Go | 📅 2025-05-25 - A complete Go cache library with multiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
* [gocache](https://github.com/yuseferi/gocache) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2024-09-18 - A data race free Go ache library with high performance and auto pruge functionality
* [groupcache](https://github.com/golang/groupcache) ⭐ 13,200 | 🐛 42 | 🌐 Go | 📅 2024-11-29 - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [icache](https://github.com/mdaliyan/icache) ⭐ 21 | 🐛 1 | 🌐 Go | 📅 2025-01-09 - A High Performance, Generic, thread-safe, zero-dependency cache package.
* [imcache](https://github.com/erni27/imcache) ⭐ 125 | 🐛 5 | 🌐 Go | 📅 2024-12-14 - A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding.
* [nscache](https://github.com/no-src/nscache) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-07-02 - A Go caching framework that supports multiple data source drivers.
* [otter](https://github.com/maypok86/otter) ⭐ 2,024 | 🐛 2 | 🌐 Go | 📅 2025-06-29 - A high performance lockless cache for Go. Many times faster than Ristretto and friends.
* [pocache](https://github.com/naughtygopher/pocache) ⭐ 225 | 🐛 0 | 🌐 Go | 📅 2025-01-25 - Pocache is a minimal cache package which focuses on a preemptive optimistic caching strategy.
* [ristretto](https://github.com/dgraph-io/ristretto) ⭐ 6,166 | 🐛 5 | 🌐 Go | 📅 2025-06-16 -  A high performance memory-bound Go cache.
* [sturdyc](https://github.com/viccon/sturdyc) ⭐ 1,213 | 🐛 5 | 🌐 Go | 📅 2025-04-04 - A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant.
* [theine](https://github.com/Yiling-J/theine-go) ⭐ 308 | 🐛 6 | 🌐 Go | 📅 2025-03-02 - High performance, near optimal in-memory cache with proactive TTL expiration and generics.
* [timedmap](https://github.com/zekroTJA/timedmap) ⭐ 75 | 🐛 0 | 🌐 Go | 📅 2024-05-05 - Map with expiring key-value pairs.
* [ttlcache](https://github.com/jellydator/ttlcache) ⭐ 1,099 | 🐛 14 | 🌐 Go | 📅 2025-06-17 - An in-memory cache with item expiration and generics.
* [ttlcache](https://github.com/cheshir/ttlcache) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2022-10-02 - In-memory key value storage with TTL for each record.

### Databases Implemented in Go

* [badger](https://github.com/dgraph-io/badger) ⭐ 14,718 | 🐛 30 | 🌐 Go | 📅 2025-07-03 - Fast key-value store in Go.
* [bbolt](https://github.com/etcd-io/bbolt) ⭐ 8,881 | 🐛 49 | 🌐 Go | 📅 2025-07-01 - An embedded key/value database for Go.
* [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
* [buntdb](https://github.com/tidwall/buntdb) ⭐ 4,731 | 🐛 32 | 🌐 Go | 📅 2024-09-10 - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [clover](https://github.com/ostafen/clover) ⭐ 758 | 🐛 21 | 🌐 Go | 📅 2025-02-12 - A lightweight document-oriented NoSQL database written in pure Golang.
* [cockroach](https://github.com/cockroachdb/cockroach) ⭐ 31,040 | 🐛 7,282 | 🌐 Go | 📅 2025-07-03 - Scalable, Geo-Replicated, Transactional Datastore.
* [Coffer](https://github.com/claygod/coffer) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2023-04-09 - Simple ACID key-value database that supports transactions.
* [column](https://github.com/kelindar/column) ⭐ 1,482 | 🐛 26 | 🌐 Go | 📅 2025-06-28 - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) ⭐ 1,520 | 🐛 36 | 🌐 Go | 📅 2023-02-25 - CovenantSQL is a SQL database on blockchain.
* [Databunker](https://github.com/paranoidguy/databunker) ⭐ 1,309 | 🐛 4 | 🌐 Go | 📅 2025-06-17 - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
* [dgraph](https://github.com/dgraph-io/dgraph) ⭐ 20,983 | 🐛 34 | 🌐 Go | 📅 2025-07-02 - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [DiceDB](https://github.com/DiceDB/dice) ⚠️ Archived - An open-source, fast, reactive, in-memory database optimized for modern hardware. Higher throughput and lower median latencies, making it ideal for modern workloads.
* [diskv](https://github.com/peterbourgon/diskv) ⭐ 1,434 | 🐛 8 | 🌐 Go | 📅 2021-11-10 - Home-grown disk-backed key-value store.
* [dolt](https://github.com/dolthub/dolt) ⭐ 18,820 | 🐛 438 | 🌐 Go | 📅 2025-07-03 - Dolt – It's Git for Data.
* [eliasdb](https://github.com/krotik/eliasdb) ⭐ 1,017 | 🐛 13 | 🌐 Go | 📅 2022-08-14 - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [godis](https://github.com/hdt3213/godis) ⭐ 3,711 | 🐛 18 | 🌐 Go | 📅 2025-06-01 - A Golang implemented high-performance Redis server and cluster.
* [goleveldb](https://github.com/syndtr/goleveldb) ⭐ 6,282 | 🐛 108 | 🌐 Go | 📅 2024-05-14 - Implementation of the [LevelDB](https://github.com/google/leveldb) ⭐ 37,805 | 🐛 361 | 🌐 C++ | 📅 2025-01-30 key/value database in Go.
* [hare](https://github.com/jameycribbs/hare) ⭐ 97 | 🐛 1 | 🌐 Go | 📅 2021-02-25 - A simple database management system that stores each table as a text file of line-delimited JSON.
* [immudb](https://github.com/codenotary/immudb) ⭐ 8,765 | 🐛 134 | 🌐 Go | 📅 2025-05-30 - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
* [influxdb](https://github.com/influxdb/influxdb) ⭐ 30,256 | 🐛 2,114 | 🌐 Rust | 📅 2025-07-02 - Scalable datastore for metrics, events, and real-time analytics.
* [ledisdb](https://github.com/siddontang/ledisdb) ⭐ 4,120 | 🐛 0 | 🌐 Go | 📅 2023-10-22 - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo](https://github.com/jmhodges/levigo) ⭐ 419 | 🐛 6 | 🌐 Go | 📅 2022-03-07 - Levigo is a Go wrapper for LevelDB.
* [libradb](https://github.com/amit-davidson/LibraDB) ⭐ 189 | 🐛 2 | 🌐 Go | 📅 2024-04-11 - LibraDB is a simple database with less than 1000 lines of code for learning.
* [LinDB](https://github.com/lindb/lindb) ⭐ 3,042 | 🐛 11 | 🌐 Go | 📅 2025-04-23 - LinDB is a scalable, high performance, high availability distributed time series database.
* [lotusdb](https://github.com/flower-corp/lotusdb) ⭐ 2,188 | 🐛 16 | 🌐 Go | 📅 2025-02-18 - Fast k/v database compatible with lsm and b+tree.
* [Milvus](https://github.com/milvus-io/milvus) ⭐ 35,725 | 🐛 690 | 🌐 Go | 📅 2025-07-03 - Milvus is a vector database for embedding management, analytics and search.
* [moss](https://github.com/couchbase/moss) ⭐ 1,007 | 🐛 46 | 🌐 Go | 📅 2024-12-17 - Moss is a simple LSM key-value storage engine written in 100% Go.
* [nutsdb](https://github.com/xujiajun/nutsdb) ⭐ 3,481 | 🐛 67 | 🌐 Go | 📅 2025-06-07 - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
* [objectbox-go](https://github.com/objectbox/objectbox-go) ⭐ 1,233 | 🐛 17 | 🌐 Go | 📅 2025-03-12 - High-performance embedded Object Database (NoSQL) with Go API.
* [pebble](https://github.com/cockroachdb/pebble) ⭐ 5,364 | 🐛 292 | 🌐 Go | 📅 2025-07-02 - RocksDB/LevelDB inspired key-value database in Go.
* [piladb](https://github.com/fern4lvarez/piladb) ⭐ 207 | 🐛 9 | 🌐 Go | 📅 2020-10-29 - Lightweight RESTful database engine based on stack data structures.
* [pogreb](https://github.com/akrylysov/pogreb) ⭐ 1,343 | 🐛 16 | 🌐 Go | 📅 2025-01-16 - Embedded key-value store for read-heavy workloads.
* [prometheus](https://github.com/prometheus/prometheus) ⭐ 59,276 | 🐛 732 | 🌐 Go | 📅 2025-07-02 - Monitoring system and time series database.
* [pudge](https://github.com/recoilme/pudge) ⭐ 373 | 🐛 0 | 🌐 Go | 📅 2021-07-04 - Fast and simple key/value store written using Go's standard library.
* [redka](https://github.com/nalgeon/redka) ⭐ 3,826 | 🐛 3 | 🌐 Go | 📅 2025-05-15 - Redis re-implemented with SQLite.
* [rosedb](https://github.com/roseduan/rosedb) ⭐ 4,826 | 🐛 2 | 🌐 Go | 📅 2025-04-22 - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
* [rotom](https://github.com/xgzlucario/rotom) ⭐ 39 | 🐛 0 | 🌐 Go | 📅 2024-12-15 - A tiny Redis server built with Golang, compatible with RESP protocols.
* [rqlite](https://github.com/rqlite/rqlite) ⭐ 16,721 | 🐛 71 | 🌐 Go | 📅 2025-07-02 - The lightweight, distributed, relational database built on SQLite.
* [tempdb](https://github.com/rafaeljesus/tempdb) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2018-02-14 - Key-value store for temporary items.
* [tidb](https://github.com/pingcap/tidb) ⭐ 38,663 | 🐛 5,189 | 🌐 Go | 📅 2025-07-02 - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [tiedot](https://github.com/HouzuoGuo/tiedot) ⭐ 2,723 | 🐛 27 | 🌐 Go | 📅 2021-09-05 - Your NoSQL database powered by Golang.
* [unitdb](https://github.com/unit-io/unitdb) ⭐ 123 | 🐛 2 | 🌐 Go | 📅 2023-03-07 - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
* [Vasto](https://github.com/chrislusf/vasto) ⭐ 263 | 🐛 4 | 🌐 Go | 📅 2019-03-07 - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 14,430 | 🐛 953 | 🌐 Go | 📅 2025-07-02 - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.

### Database Schema Migration

* [atlas](https://github.com/ariga/atlas) ⭐ 6,990 | 🐛 215 | 🌐 Go | 📅 2025-07-02 - A Database Toolkit. A CLI designed to help companies better work with their data.
* [avro](https://github.com/khezen/avro) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2024-11-27 - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
* [bytebase](https://github.com/bytebase/bytebase) ⭐ 12,679 | 🐛 117 | 🌐 Go | 📅 2025-07-03 - Safe database schema change and version control for DevOps teams.
* [darwin](https://github.com/GuiaBolso/darwin) ⭐ 149 | 🐛 5 | 🌐 Go | 📅 2023-02-24 - Database schema evolution library for Go.
* [dbmate](https://github.com/amacneil/dbmate) ⭐ 6,103 | 🐛 29 | 🌐 Go | 📅 2025-06-20 - A lightweight, framework-agnostic database migration tool.
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2019-12-26 - Django style fixtures for Golang's excellent built-in database/sql library.
* [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2023-10-09 - CLI-friendly package for go-pg migrations management.
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) ⭐ 86 | 🐛 4 | 🌐 Go | 📅 2025-04-14 - A Go package to help write migrations with go-pg/pg.
* [goavro](https://github.com/linkedin/goavro) ⭐ 1,031 | 🐛 81 | 🌐 Go | 📅 2025-06-09 - A Go package that encodes and decodes Avro data.
* [godfish](https://github.com/rafaelespinoza/godfish) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2025-06-15 - Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3.
* [goose](https://github.com/pressly/goose) ⭐ 8,647 | 🐛 96 | 🌐 Go | 📅 2025-06-28 - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [gorm-seeder](https://github.com/Kachit/gorm-seeder) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2022-11-20 - Simple database seeder for Gorm ORM.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) ⭐ 1,100 | 🐛 17 | 🌐 Go | 📅 2025-03-28 - Database schema migration helper for Gorm ORM.
* [libschema](https://github.com/muir/libschema) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - Define your migrations separately in each library. Migrations for open source libraries. MySQL & PostgreSQL.
* [migrate](https://github.com/golang-migrate/migrate) ⭐ 16,924 | 🐛 431 | 🌐 Go | 📅 2025-04-25 - Database migrations. CLI and Golang library.
* [migrator](https://github.com/lopezator/migrator) ⭐ 178 | 🐛 11 | 🌐 Go | 📅 2024-03-14 - Dead simple Go database migration library.
* [migrator](https://github.com/larapulse/migrator) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2025-04-24 - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
* [schema](https://github.com/adlio/schema) ⭐ 42 | 🐛 2 | 🌐 Go | 📅 2024-12-12 - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
* [skeema](https://github.com/skeema/skeema) ⭐ 1,324 | 🐛 18 | 🌐 Go | 📅 2025-07-02 - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) ⭐ 1,491 | 🐛 94 | 🌐 Go | 📅 2024-06-26 - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) ⭐ 3,347 | 🐛 90 | 🌐 Go | 📅 2025-04-17 - Database migration tool. Allows embedding migrations into the application using go-bindata.
* [sqlize](https://github.com/sunary/sqlize) ⭐ 122 | 🐛 0 | 🌐 Go | 📅 2025-05-18 - Database migration generator. Allows generate sql migration from model and existing sql by differ them.

### Database Tools

* [chproxy](https://github.com/Vertamedia/chproxy) ⭐ 1,364 | 🐛 57 | 🌐 Go | 📅 2025-06-06 - HTTP proxy for ClickHouse database.
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) ⭐ 497 | 🐛 26 | 🌐 Go | 📅 2025-06-27 - Collects small inserts and sends big requests to ClickHouse servers.
* [database-gateway](https://github.com/kazhuravlev/database-gateway) ⭐ 28 | 🐛 14 | 🌐 Go | 📅 2025-06-15 - Running SQL in production with ACLs, logs, and shared links.
* [dbbench](https://github.com/sj14/dbbench) ⭐ 108 | 🐛 11 | 🌐 Go | 📅 2025-07-03 - Database benchmarking tool with support for several databases and scripts.
* [dg](https://github.com/codingconcepts/dg) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2024-08-21 - A fast data generator that produces CSV files from generated relational data.
* [gatewayd](https://github.com/gatewayd-io/gatewayd) ⭐ 263 | 🐛 75 | 🌐 Go | 📅 2025-07-01 - Cloud-native database gateway and framework for building data-driven applications. Like API gateways, for databases.
* [go-mysql](https://github.com/siddontang/go-mysql) ⭐ 4,776 | 🐛 150 | 🌐 Go | 📅 2025-06-11 - Go toolset to handle MySQL protocol and replication.
* [gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) ⭐ 61 | 🐛 13 | 🌐 Go | 📅 2025-06-30 - Multi-tenancy support for GORM managed databases.
* [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
* [octillery](https://github.com/knocknote/octillery) ⭐ 198 | 🐛 6 | 🌐 Go | 📅 2023-11-05 - Go package for sharding databases ( Supports every ORM or raw SQL ).
* [onedump](https://github.com/liweiyi88/onedump) ⭐ 194 | 🐛 0 | 🌐 Go | 📅 2025-07-02 - Database backup from different drivers to different destinations with one command and configuration.
* [pg\_timetable](https://github.com/cybertec-postgresql/pg_timetable) ⭐ 1,192 | 🐛 1 | 🌐 Go | 📅 2025-06-30 - Advanced scheduling for PostgreSQL.
* [pgweb](https://github.com/sosedoff/pgweb) ⭐ 8,935 | 🐛 35 | 🌐 Go | 📅 2025-06-15 - Web-based PostgreSQL database browser.
* [prep](https://github.com/hexdigest/prep) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2017-12-19 - Use prepared SQL statements without changing your code.
* [pREST](https://github.com/prest/prest) ⭐ 4,364 | 🐛 141 | 🌐 Go | 📅 2025-04-29 - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
* [rdb](https://github.com/HDT3213/rdb) ⭐ 543 | 🐛 4 | 🌐 Go | 📅 2025-06-29 - Redis RDB file parser for secondary development and memory analysis.
* [rwdb](https://github.com/andizzle/rwdb) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2017-11-08 - rwdb provides read replica capability for multiple database servers setup.
* [vitess](https://github.com/youtube/vitess) ⭐ 19,760 | 🐛 875 | 🌐 Go | 📅 2025-07-02 - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
* [wescale](https://github.com/wesql/wescale) ⭐ 302 | 🐛 20 | 🌐 Go | 📅 2025-03-07 - WeScale is a database proxy designed to enhance the scalability, performance, security, and resilience of your applications.

### SQL Query Builders

*Libraries for building and using SQL.*

* [bqb](https://github.com/nullism/bqb) ⭐ 171 | 🐛 0 | 🌐 Go | 📅 2025-02-11 - Lightweight and easy to learn query builder.
* [buildsqlx](https://github.com/arthurkushman/buildsqlx) ⭐ 181 | 🐛 7 | 🌐 Go | 📅 2024-04-21 - Go database query builder library for PostgreSQL.
* [builq](https://github.com/cristalhq/builq) ⭐ 94 | 🐛 0 | 🌐 Go | 📅 2024-04-24 - Easily build SQL queries in Go.
* [dbq](https://github.com/rocketlaunchr/dbq) ⭐ 413 | 🐛 1 | 🌐 Go | 📅 2021-02-22 - Zero boilerplate database operations for Go.
* [Dotsql](https://github.com/gchaincl/dotsql) ⭐ 748 | 🐛 8 | 🌐 Go | 📅 2023-11-24 - Go library that helps you keep sql files in one place and use them with ease.
* [gendry](https://github.com/didi/gendry) ⭐ 1,634 | 🐛 19 | 🌐 Go | 📅 2025-03-12 - Non-invasive SQL builder and powerful data binder.
* [godbal](https://github.com/xujiajun/godbal) ⭐ 59 | 🐛 0 | 🌐 Go | 📅 2019-01-30 - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
* [goqu](https://github.com/doug-martin/goqu) ⭐ 2,530 | 🐛 143 | 🌐 Go | 📅 2024-05-22 - Idiomatic SQL builder and query library.
* [gosql](https://github.com/twharmon/gosql) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2022-04-12 - SQL Query builder with better null values support.
* [Hotcoal](https://github.com/motrboat/hotcoal) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2023-12-23 - Secure your handcrafted SQL against injection.
* [igor](https://github.com/galeone/igor) ⭐ 126 | 🐛 0 | 🌐 Go | 📅 2024-04-14 - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [jet](https://github.com/go-jet/jet) ⭐ 3,249 | 🐛 42 | 🌐 Go | 📅 2025-06-26 - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
* [ormlite](https://github.com/pupizoid/ormlite) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2023-01-30 - Lightweight package containing some ORM-like features and helpers for sqlite databases.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) ⭐ 649 | 🐛 41 | 🌐 Go | 📅 2023-05-01 - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [patcher](https://github.com/Jacobbrewer1/patcher) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2025-06-27 - Powerful SQL Query builder that automatically generates SQL queries from structs.
* [qry](https://github.com/HnH/qry) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2024-02-20 - Tool that generates constants from files with raw SQL queries.
* [sg](https://github.com/go-the-way/sg) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2022-05-11 - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go.
* [sq](https://github.com/bokwoon95/go-structured-query) ⭐ 201 | 🐛 2 | 🌐 Go | 📅 2023-01-15 - Type-safe SQL builder and struct mapper for Go.
* [sqlc](https://github.com/kyleconroy/sqlc) ⭐ 15,415 | 🐛 610 | 🌐 Go | 📅 2025-07-02 - Generate type-safe code from SQL.
* [sqlf](https://github.com/leporo/sqlf) ⭐ 180 | 🐛 1 | 🌐 Go | 📅 2025-02-24 - Fast SQL query builder.
* [sqlingo](https://github.com/lqs/sqlingo) ⭐ 428 | 🐛 5 | 🌐 Go | 📅 2025-01-06 - A lightweight DSL to build SQL in Go.
* [sqrl](https://github.com/elgris/sqrl) ⭐ 280 | 🐛 6 | 🌐 Go | 📅 2023-06-15 - SQL query builder, fork of Squirrel with improved performance.
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* [Squirrel](https://github.com/Masterminds/squirrel) ⭐ 7,487 | 🐛 91 | 🌐 Go | 📅 2024-04-24 - Go library that helps you build SQL queries.
* [xo](https://github.com/knq/xo) ⭐ 3,829 | 🐛 53 | 🌐 Go | 📅 2025-06-23 - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

**[⬆ back to top](#contents)**

## Database Drivers

### Interfaces to Multiple Backends

* [cayley](https://github.com/google/cayley) ⭐ 14,945 | 🐛 92 | 🌐 Go | 📅 2025-06-27 - Graph database with support for multiple backends.
* [dsc](https://github.com/viant/dsc) ⭐ 34 | 🐛 1 | 🌐 Go | 📅 2024-12-02 - Datastore connectivity for SQL, NoSQL, structured files.
* [dynamo](https://github.com/fogfish/dynamo) ⭐ 21 | 🐛 2 | 🌐 Go | 📅 2025-06-05 - A simple key-value abstraction to store algebraic and linked-data data types at AWS storage services: AWS DynamoDB and AWS S3.
* [go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) ⭐ 317 | 🐛 1 | 🌐 Go | 📅 2025-04-17 - Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries.
* [gokv](https://github.com/philippgille/gokv) ⭐ 799 | 🐛 43 | 🌐 Go | 📅 2025-06-29 - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).

### Relational Database Drivers

* [avatica](https://github.com/apache/calcite-avatica-go) ⭐ 122 | 🐛 0 | 🌐 Go | 📅 2025-04-16 - Apache Avatica/Phoenix SQL driver for database/sql.
* [bgc](https://github.com/viant/bgc) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2024-03-17 - Datastore Connectivity for BigQuery for go.
* [firebirdsql](https://github.com/nakagami/firebirdsql) ⭐ 242 | 🐛 14 | 🌐 Go | 📅 2025-05-09 - Firebird RDBMS SQL driver for Go.
* [go-adodb](https://github.com/mattn/go-adodb) ⭐ 148 | 🐛 19 | 🌐 Go | 📅 2022-04-21 - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
* [go-mssqldb](https://github.com/denisenkom/go-mssqldb) ⭐ 1,855 | 🐛 177 | 🌐 Go | 📅 2025-04-26 - Microsoft MSSQL driver for Go.
* [go-oci8](https://github.com/mattn/go-oci8) ⭐ 634 | 🐛 21 | 🌐 Go | 📅 2023-10-24 - Oracle driver for go that uses database/sql.
* [go-rqlite](https://github.com/rqlite/gorqlite) ⭐ 165 | 🐛 7 | 🌐 Go | 📅 2025-06-09 - A Go client for rqlite, providing easy-to-use abstractions for working with the rqlite API.
* [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) ⭐ 14,905 | 🐛 61 | 🌐 Go | 📅 2025-06-13 - MySQL driver for Go.
* [go-sqlite3](https://github.com/mattn/go-sqlite3) ⭐ 8,554 | 🐛 202 | 🌐 C | 📅 2025-04-16 - SQLite3 driver for go that uses database/sql.
* [go-sqlite3](https://github.com/ncruces/go-sqlite3) ⭐ 727 | 🐛 6 | 🌐 Go | 📅 2025-06-30 - This Go module is compatible with the database/sql driver. It allows embedding SQLite into your application, provides direct access to its C API, supports SQLite VFS, and also includes a GORM driver.
* [godror](https://github.com/godror/godror) ⭐ 558 | 🐛 2 | 🌐 C | 📅 2025-06-27 - Oracle driver for Go, using the ODPI-C driver.
* [gofreetds](https://github.com/minus5/gofreetds) ⭐ 113 | 🐛 18 | 🌐 Go | 📅 2020-11-30 - Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org).
* [KSQL](https://github.com/VinGarcia/ksql) ⭐ 336 | 🐛 0 | 🌐 Go | 📅 2025-06-08 - A Simple and Powerful Golang SQL Library
* [pgx](https://github.com/jackc/pgx) ⭐ 12,075 | 🐛 231 | 🌐 Go | 📅 2025-06-26 - PostgreSQL driver supporting features beyond those exposed by database/sql.
* [pig](https://github.com/alexeyco/pig) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2021-04-18 - Simple [pgx](https://github.com/jackc/pgx) ⭐ 12,075 | 🐛 231 | 🌐 Go | 📅 2025-06-26 wrapper to execute and [scan](https://github.com/georgysavva/scany) ⭐ 1,438 | 🐛 6 | 🌐 Go | 📅 2025-03-19 query results easily.
* [pq](https://github.com/lib/pq) ⭐ 9,525 | 🐛 338 | 🌐 Go | 📅 2024-11-26 - Pure Go Postgres driver for database/sql.
* [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) ⭐ 450 | 🐛 0 | 🌐 Go | 📅 2024-01-06 - SQLite with pure Go.
* [sqlhooks](https://github.com/qustavo/sqlhooks) ⭐ 656 | 🐛 10 | 🌐 Go | 📅 2024-06-27 - Attach hooks to any database/sql driver.
* [sqlite](https://pkg.go.dev/modernc.org/sqlite) - Package sqlite is a sql/database driver using a CGo-free port of the C SQLite3 library.
* [surrealdb.go](https://github.com/surrealdb/surrealdb.go) ⭐ 278 | 🐛 48 | 🌐 Go | 📅 2025-04-08 - SurrealDB Driver for Go.
* [ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) ⭐ 165 | 🐛 249 | 🌐 Go | 📅 2025-07-01 - native and database/sql driver YDB (Yandex Database)

### NoSQL Database Drivers

* [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) ⭐ 450 | 🐛 38 | 🌐 Go | 📅 2025-06-30 - Aerospike client in Go language.
* [arangolite](https://github.com/solher/arangolite) ⭐ 72 | 🐛 5 | 🌐 Go | 📅 2021-03-10 - Lightweight golang driver for ArangoDB.
* [asc](https://github.com/viant/asc) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-09-20 - Datastore Connectivity for Aerospike for go.
* [forestdb](https://github.com/couchbase/goforestdb) ⭐ 36 | 🐛 7 | 🌐 Go | 📅 2016-12-15 - Go bindings for ForestDB.
* [go-couchbase](https://github.com/couchbase/go-couchbase) ⭐ 323 | 🐛 40 | 🌐 Go | 📅 2024-01-15 - Couchbase client in Go.
* [go-mongox](https://github.com/chenmingyong0423/go-mongox) ⭐ 198 | 🐛 4 | 🌐 Go | 📅 2025-06-18 - A Go Mongo library based on the official driver, featuring streamlined document operations, generic binding of structs to collections, built-in CRUD, aggregation, automated field updates, struct validation, hooks, and plugin-based programming.
* [go-pilosa](https://github.com/pilosa/go-pilosa) ⚠️ Archived - Go client library for Pilosa.
* [go-rejson](https://github.com/nitishm/go-rejson) ⭐ 343 | 🐛 17 | 🌐 Go | 📅 2024-01-17 - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
* [gocb](https://github.com/couchbase/gocb) ⭐ 372 | 🐛 4 | 🌐 Go | 📅 2025-07-01 - Official Couchbase Go SDK.
* [gocosmos](https://github.com/btnguyen2k/gocosmos) ⭐ 22 | 🐛 4 | 🌐 Go | 📅 2024-11-17 - REST client and standard `database/sql` driver for Azure Cosmos DB.
* [gocql](https://gocql.github.io) - Go language driver for Apache Cassandra.
* [godis](https://github.com/piaohao/godis) ⭐ 113 | 🐛 0 | 🌐 Go | 📅 2020-05-12 - redis client implement by golang, inspired by jedis.
* [godscache](https://github.com/defcronyke/godscache) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-02-08 - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
* [gomemcache](https://github.com/bradfitz/gomemcache/) ⭐ 1,820 | 🐛 46 | 🌐 Go | 📅 2025-04-03 - memcache client library for the Go programming language.
* [gomemcached](https://github.com/aliexpressru/gomemcached) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2024-02-19 - A binary Memcached client for Go with support for sharding using consistent hashing, along with SASL.
* [gorethink](https://github.com/dancannon/gorethink) ⭐ 1,653 | 🐛 23 | 🌐 Go | 📅 2024-11-18 - Go language driver for RethinkDB.
* [goriak](https://github.com/zegl/goriak) ⭐ 30 | 🐛 4 | 🌐 Go | 📅 2021-09-15 - Go language driver for Riak KV.
* [Kivik](https://github.com/go-kivik/kivik) ⭐ 323 | 🐛 37 | 🌐 Go | 📅 2025-05-25 - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
* [mgm](https://github.com/kamva/mgm) ⭐ 759 | 🐛 16 | 🌐 Go | 📅 2023-12-18 - MongoDB model-based ODM for Go (based on official MongoDB driver).
* [mgo](https://github.com/globalsign/mgo) ⭐ 1,969 | 🐛 66 | 🌐 Go | 📅 2021-10-29 - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
* [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) ⭐ 8,385 | 🐛 8 | 🌐 Go | 📅 2025-07-02 - Official MongoDB driver for the Go language.
* [neo4j](https://github.com/cihangir/neo4j) ⭐ 29 | 🐛 8 | 🌐 Go | 📅 2015-04-02 - Neo4j Rest API Bindings for Golang.
* [neoism](https://github.com/jmcvetta/neoism) ⭐ 390 | 🐛 12 | 🌐 Go | 📅 2020-02-16 - Neo4j client for Golang.
* [qmgo](https://github.com/qiniu/qmgo) ⭐ 1,324 | 🐛 51 | 🌐 Go | 📅 2024-10-31 - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
* [redeo](https://github.com/bsm/redeo) ⭐ 445 | 🐛 2 | 🌐 Go | 📅 2023-01-20 - Redis-protocol compatible TCP servers/services.
* [redigo](https://github.com/gomodule/redigo) ⭐ 9,830 | 🐛 23 | 🌐 Go | 📅 2025-05-21 - Redigo is a Go client for the Redis database.
* [redis](https://github.com/redis/go-redis) ⭐ 21,032 | 🐛 99 | 🌐 Go | 📅 2025-07-02 - Redis client for Golang.
* [rueidis](http://github.com/rueian/rueidis) ⭐ 2,708 | 🐛 15 | 🌐 Go | 📅 2025-07-03 - Fast Redis RESP3 client with auto pipelining and server-assisted client side caching.
* [xredis](https://github.com/shomali11/xredis) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2019-06-08 - Typesafe, customizable, clean & easy to use Redis client.

### Search and Analytic Databases

* [clickhouse-go](https://github.com/ClickHouse/clickhouse-go/) ⭐ 3,086 | 🐛 90 | 🌐 Go | 📅 2025-07-03 - ClickHouse SQL client for Go with a `database/sql` compatibility.
* [effdsl](https://github.com/sdqri/effdsl) ⭐ 31 | 🐛 3 | 🌐 Go | 📅 2025-06-29 - Elasticsearch query builder for Go.
* [elastic](https://github.com/olivere/elastic) ⭐ 7,471 | 🐛 115 | 🌐 Go | 📅 2024-08-08 - Elasticsearch client for Go.
* [elasticsql](https://github.com/cch123/elasticsql) ⭐ 1,189 | 🐛 13 | 🌐 Go | 📅 2023-08-06 - Convert sql to elasticsearch dsl in Go.
* [elastigo](https://github.com/mattbaird/elastigo) ⭐ 942 | 🐛 69 | 🌐 Go | 📅 2019-02-05 - Elasticsearch client library.
* [go-elasticsearch](https://github.com/elastic/go-elasticsearch) ⭐ 5,901 | 🐛 82 | 🌐 Go | 📅 2025-07-01 - Official Elasticsearch client for Go.
* [goes](https://github.com/OwnLocal/goes) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2020-10-19 - Library to interact with Elasticsearch.
* [skizze](https://github.com/seiflotfy/skizze) ⭐ 92 | 🐛 0 | 🌐 Go | 📅 2016-05-09 - probabilistic data-structures service and storage.
* [zoekt](https://github.com/sourcegraph/zoekt) ⭐ 993 | 🐛 23 | 🌐 Go | 📅 2025-06-27 - Fast trigram based code search.

**[⬆ back to top](#contents)**

## Date and Time

*Libraries for working with dates and times.*

* [approx](https://github.com/goschtalt/approx) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - A Duration extension supporting parsing/printing durations in days, weeks and years.
* [carbon](https://github.com/dromara/carbon) ⭐ 5,089 | 🐛 1 | 🌐 Go | 📅 2025-07-03 - A simple, semantic and developer-friendly time package for golang.
* [carbon](https://github.com/uniplaces/carbon) ⭐ 784 | 🐛 1 | 🌐 Go | 📅 2024-01-17 - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* [cronrange](https://github.com/1set/cronrange) ⭐ 17 | 🐛 2 | 🌐 Go | 📅 2022-09-04 - Parses Cron-style time range expressions, checks if the given time is within any ranges.
* [date](https://github.com/rickb777/date) ⭐ 140 | 🐛 0 | 🌐 Go | 📅 2025-05-27 - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
* [dateparse](https://github.com/araddon/dateparse) ⭐ 2,090 | 🐛 64 | 🌐 Go | 📅 2023-12-30 - Parse date's without knowing format in advance.
* [durafmt](https://github.com/hako/durafmt) ⭐ 504 | 🐛 10 | 🌐 Go | 📅 2021-06-08 - Time duration formatting library for Go.
* [feiertage](https://github.com/wlbr/feiertage) ⭐ 49 | 🐛 1 | 🌐 Go | 📅 2025-04-30 - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
* [go-anytime](https://github.com/ijt/go-anytime) ⭐ 29 | 🐛 4 | 🌐 Go | 📅 2023-01-17 - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance.
* [go-datebin](https://github.com/deatil/go-datebin) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2024-12-04 - A simple datetime parse pkg.
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) ⭐ 222 | 🐛 7 | 🌐 Go | 📅 2024-08-17 - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* [go-str2duration](https://github.com/xhit/go-str2duration) ⭐ 113 | 🐛 1 | 🌐 Go | 📅 2023-10-14 - Convert string to duration. Support time.Duration returned string and more.
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) ⭐ 168 | 🐛 4 | 🌐 Go | 📅 2024-04-23 - Calculate the sunrise and sunset times for a given location.
* [go-week](https://github.com/stoewer/go-week) ⭐ 10 | 🐛 2 | 🌐 Go | 📅 2021-11-15 - An efficient package to work with ISO8601 week dates.
* [gostradamus](https://github.com/bykof/gostradamus) ⭐ 210 | 🐛 1 | 🌐 Go | 📅 2024-12-20 - A Go package for working with dates.
* [iso8601](https://github.com/relvacode/iso8601) ⭐ 151 | 🐛 3 | 🌐 Go | 📅 2025-03-21 - Efficiently parse ISO8601 date-times without regex.
* [kair](https://github.com/GuilhermeCaruso/kair) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2020-06-18 - Date and Time - Golang Formatting Library.
* [now](https://github.com/jinzhu/now) ⭐ 4,537 | 🐛 13 | 🌐 Go | 📅 2025-06-09 - Now is a time toolkit for golang.
* [strftime](https://github.com/awoodbeck/strftime) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2018-02-21 - C99-compatible strftime formatter.
* [timespan](https://github.com/SaidinWoT/timespan) ⭐ 83 | 🐛 3 | 🌐 Go | 📅 2019-03-19 - For interacting with intervals of time, defined as a start time and a duration.
* [timeutil](https://github.com/leekchan/timeutil) ⭐ 192 | 🐛 2 | 🌐 Go | 📅 2019-02-03 - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [tuesday](https://github.com/osteele/tuesday) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2021-06-19 - Ruby-compatible Strftime function.

**[⬆ back to top](#contents)**

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [arpc](https://github.com/lesismal/arpc) ⭐ 1,063 | 🐛 0 | 🌐 Go | 📅 2025-02-20 - More effective network communication, support two-way-calling, notify, broadcast.
* [bedrock](https://github.com/z5labs/bedrock) ⭐ 13 | 🐛 2 | 🌐 Go | 📅 2025-07-01 - Provides a minimal, modular and composable foundation for quickly developing services and more use case specific frameworks in Go.
* [capillaries](https://github.com/capillariesio/capillaries) ⭐ 66 | 🐛 0 | 🌐 Go | 📅 2025-06-12 - distributed batch data processing framework.
* [celeriac](https://github.com/svcavallar/celeriac.v1) ⭐ 72 | 🐛 0 | 🌐 Go | 📅 2024-07-17 - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [committer](https://github.com/vadiminshakov/committer) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2025-06-24 - A distributed transactions management system (2PC/3PC implementation).
* [consistent](https://github.com/buraksezer/consistent) ⭐ 737 | 🐛 6 | 🌐 Go | 📅 2023-11-07 - Consistent hashing with bounded loads.
* [consistenthash](https://github.com/mbrostami/consistenthash) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2024-04-04 - Consistent hashing with configurable replicas.
* [dht](https://github.com/anacrolix/dht) ⭐ 331 | 🐛 3 | 🌐 Go | 📅 2025-06-23 - BitTorrent Kademlia DHT implementation.
* [digota](https://github.com/digota/digota) ⭐ 516 | 🐛 11 | 🌐 Go | 📅 2021-02-14 - grpc ecommerce microservice.
* [dot](https://github.com/dotchain/dot/) ⭐ 86 | 🐛 0 | 🌐 Go | 📅 2019-09-30 - distributed sync using operational transformation/OT.
* [doublejump](https://github.com/edwingeng/doublejump) ⭐ 106 | 🐛 0 | 🌐 Go | 📅 2022-10-19 - A revamped Google's jump consistent hash.
* [dragonboat](https://github.com/lni/dragonboat) ⭐ 5,192 | 🐛 52 | 🌐 Go | 📅 2024-07-12 - A feature complete and high performance multi-group Raft library in Go.
* [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) ⭐ 2,649 | 🐛 29 | 🌐 Go | 📅 2025-07-03 - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures.
* [drmaa](https://github.com/dgruber/drmaa) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2024-07-09 - Job submission library for cluster schedulers based on the DRMAA standard.
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [dynatomic](https://github.com/tylfin/dynatomic) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2020-11-04 - A library for using DynamoDB as an atomic counter.
* [emitter-io](https://github.com/emitter-io/emitter) ⭐ 3,944 | 🐛 15 | 🌐 Go | 📅 2025-03-13 - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
* [evans](https://github.com/ktr0731/evans) ⭐ 4,400 | 🐛 36 | 🌐 Go | 📅 2023-12-26 - Evans: more expressive universal gRPC client.
* [failured](https://github.com/andy2046/failured) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2021-08-02 - adaptive accrual failure detector for distributed systems.
* [flowgraph](https://github.com/vectaport/flowgraph) ⭐ 62 | 🐛 0 | 🌐 Go | 📅 2021-04-24 - flow-based programming package.
* [gleam](https://github.com/chrislusf/gleam) ⭐ 3,526 | 🐛 40 | 🌐 Go | 📅 2025-04-20 - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* [glow](https://github.com/chrislusf/glow) ⭐ 3,217 | 🐛 15 | 🌐 Go | 📅 2018-11-02 - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* [gmsec](https://github.com/gmsec/micro) ⭐ 25 | 🐛 3 | 🌐 Go | 📅 2024-11-01 - A Go distributed systems development framework.
* [go-doudou](https://github.com/unionj-cloud/go-doudou) ⭐ 1,203 | 🐛 34 | 🌐 Go | 📅 2025-06-10 - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity.
* [go-eagle](https://github.com/go-eagle/eagle) ⭐ 2,323 | 🐛 25 | 🌐 Go | 📅 2025-06-19 - A Go framework for the API or Microservice with handy scaffolding tools.
* [go-health](https://github.com/InVisionApp/go-health) ⚠️ Archived - Library for enabling asynchronous dependency health checks in your service.
* [go-jump](https://github.com/dgryski/go-jump) ⭐ 387 | 🐛 1 | 🌐 Go | 📅 2021-10-18 - Port of Google's "Jump" Consistent Hash function.
* [go-kit](https://github.com/go-kit/kit) ⭐ 27,136 | 🐛 57 | 🌐 Go | 📅 2024-07-19 - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [go-micro](https://github.com/micro/go-micro) ⭐ 22,376 | 🐛 19 | 🌐 Go | 📅 2025-07-02 - A distributed systems development framework.
* [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) ⭐ 63 | 🐛 2 | 🌐 Go | 📅 2024-05-13 - MySQL based distributed lock.
* [go-pdu](https://github.com/pdupub/go-pdu) ⭐ 48 | 🐛 0 | 🌐 Go | 📅 2025-01-20 - A decentralized identity-based social network.
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) ⭐ 556 | 🐛 6 | 🌐 Go | 📅 2024-07-25 - A library built to provide support for defining async service health checks for golang services.
* [go-zero](https://github.com/tal-tech/go-zero) ⭐ 31,340 | 🐛 362 | 🌐 Go | 📅 2025-07-02 - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
* [gorpc](https://github.com/valyala/gorpc) ⭐ 709 | 🐛 14 | 🌐 Go | 📅 2022-10-07 - Simple, fast and scalable RPC library for high load.
* [grpc-go](https://github.com/grpc/grpc-go) ⭐ 21,979 | 🐛 136 | 🌐 Go | 📅 2025-07-02 - The Go language implementation of gRPC. HTTP/2 based RPC.
* [hprose](https://github.com/hprose/hprose-golang) ⭐ 1,262 | 🐛 5 | 🌐 Go | 📅 2024-02-18 - Very newbility RPC Library, support 25+ languages now.
* [jsonrpc](https://github.com/osamingo/jsonrpc) ⭐ 187 | 🐛 6 | 🌐 Go | 📅 2025-03-28 - The jsonrpc package helps implement of JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) ⭐ 355 | 🐛 0 | 🌐 Go | 📅 2025-05-21 - JSON-RPC 2.0 HTTP client implementation.
* [K8gb](https://github.com/k8gb-io/k8gb) ⭐ 1,050 | 🐛 88 | 🌐 Go | 📅 2025-07-03 - A cloud native Kubernetes Global Balancer.
* [Kitex](https://github.com/cloudwego/kitex) ⭐ 7,509 | 🐛 54 | 🌐 Go | 📅 2025-06-25 - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice.
* [Kratos](https://github.com/go-kratos/kratos) ⭐ 24,545 | 🐛 122 | 🌐 Go | 📅 2025-06-01 - A modular-designed and easy-to-use microservices framework in Go.
* [liftbridge](https://github.com/liftbridge-io/liftbridge) ⭐ 2,605 | 🐛 43 | 🌐 Go | 📅 2024-04-19 - Lightweight, fault-tolerant message streams for NATS.
* [lura](https://github.com/luraproject/lura) ⭐ 6,576 | 🐛 8 | 🌐 Go | 📅 2025-06-25 - Ultra performant API Gateway framework with middlewares.
* [micro](https://github.com/micro/micro) ⭐ 12,265 | 🐛 7 | 🌐 Go | 📅 2025-07-02 - A distributed systems runtime for the cloud and beyond.
* [mochi mqtt](https://github.com/mochi-co/mqtt) ⭐ 1,563 | 🐛 26 | 🌐 Go | 📅 2025-04-16 - Fully spec compliant, embeddable high-performance MQTT v5/v3 broker for IoT, smarthome, and pubsub.
* [NATS](https://github.com/nats-io/nats-server) ⭐ 17,431 | 🐛 464 | 🌐 Go | 📅 2025-07-02 - NATS is a simple, secure, and
  performant communications system for digital systems, services, and devices.
* [opentelemetry-go-auto-instrumentation](https://github.com/alibaba/opentelemetry-go-auto-instrumentation) ⭐ 614 | 🐛 56 | 🌐 Go | 📅 2025-06-30 - OpenTelemetry Compile-Time Instrumentation for Golang.
* [outboxer](https://github.com/italolelis/outboxer) ⭐ 163 | 🐛 2 | 🌐 Go | 📅 2025-07-01 - Outboxer is a go library that implements the outbox pattern.
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
* [raft](https://github.com/hashicorp/raft) ⭐ 8,663 | 🐛 44 | 🌐 Go | 📅 2025-07-01 - Golang implementation of the Raft consensus protocol, by HashiCorp.
* [raft](https://github.com/etcd-io/raft) ⭐ 866 | 🐛 70 | 🌐 Go | 📅 2025-07-01 - Go implementation of the Raft consensus protocol, by CoreOS.
* [rain](https://github.com/cenkalti/rain) ⭐ 1,049 | 🐛 2 | 🌐 Go | 📅 2025-07-01 - BitTorrent client and library.
* [redis-lock](https://github.com/bsm/redislock) ⭐ 1,629 | 🐛 3 | 🌐 Go | 📅 2025-06-09 - Simplified distributed locking implementation using Redis.
* [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
* [ringpop-go](https://github.com/uber/ringpop-go) ⭐ 850 | 🐛 27 | 🌐 Go | 📅 2023-08-23 - Scalable, fault-tolerant application-layer sharding for Go applications.
* [rpcx](https://github.com/smallnest/rpcx) ⭐ 8,230 | 🐛 6 | 🌐 Go | 📅 2025-04-26 - Distributed pluggable RPC service framework like alibaba Dubbo.
* [Semaphore](https://github.com/jexia/semaphore) ⭐ 94 | 🐛 32 | 🌐 Go | 📅 2023-03-06 - A straightforward (micro) service orchestrator.
* [sleuth](https://github.com/ursiform/sleuth) ⭐ 380 | 🐛 0 | 🌐 Go | 📅 2023-07-09 - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq) ⭐ 10,326 | 🐛 354 | 🌐 C++ | 📅 2025-06-26).
* [sponge](https://github.com/zhufuyi/sponge) ⭐ 2,021 | 🐛 29 | 🌐 Go | 📅 2025-06-27 - A distributed development framework that integrates automatic code generation, gin and grpc frameworks, base development frameworks.
* [Tarmac](https://github.com/tarmac-project/tarmac) ⭐ 335 | 🐛 7 | 🌐 Go | 📅 2025-06-27 - Framework for writing functions, microservices, or monoliths with WebAssembly
* [Temporal](https://github.com/temporalio/sdk-go) ⭐ 656 | 🐛 202 | 🌐 Go | 📅 2025-06-26 - Durable execution system for making code fault-tolerant and simple.
* [torrent](https://github.com/anacrolix/torrent) ⭐ 5,802 | 🐛 63 | 🌐 Go | 📅 2025-07-02 - BitTorrent client package.
* [trpc-go](https://github.com/trpc-group/trpc-go) ⭐ 980 | 🐛 8 | 🌐 Go | 📅 2025-04-18 - The Go language implementation of tRPC, which is a pluggable, high-performance RPC framework.

**[⬆ back to top](#contents)**

## Dynamic DNS

*Tools for updating dynamic DNS records.*

* [DDNS](https://github.com/skibish/ddns) ⭐ 262 | 🐛 1 | 🌐 Go | 📅 2025-05-01 - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
* [GoDNS](https://github.com/timothyye/godns) ⭐ 1,590 | 🐛 16 | 🌐 Go | 📅 2025-07-02 - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.

**[⬆ back to top](#contents)**

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur](https://github.com/aymerick/douceur) ⭐ 252 | 🐛 9 | 🌐 Go | 📅 2022-09-11 - CSS inliner for your HTML emails.
* [email](https://github.com/jordan-wright/email) ⭐ 2,737 | 🐛 54 | 🌐 Go | 📅 2024-02-21 - A robust and flexible email library for Go.
* [email-verifier](https://github.com/AfterShip/email-verifier) ⭐ 1,395 | 🐛 32 | 🌐 Go | 📅 2025-07-01 - A Go library for email verification without sending any emails.
* [go-dkim](https://github.com/toorop/go-dkim) ⭐ 97 | 🐛 5 | 🌐 Go | 📅 2025-02-26 - DKIM library, to sign & verify email.
* [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) ⭐ 72 | 🐛 0 | 🌐 Go | 📅 2025-01-26 - Golang library for providing a canonical representation of email address.
* [go-email-validator](https://github.com/go-email-validator/go-email-validator) ⚠️ Archived - Modular email validator for syntax, disposable, smtp, etc... checking.
* [go-imap](https://github.com/emersion/go-imap) ⭐ 2,207 | 🐛 59 | 🌐 Go | 📅 2025-06-11 - IMAP library for clients and servers.
* [go-mail](https://github.com/wneessen/go-mail) ⭐ 1,026 | 🐛 4 | 🌐 Go | 📅 2025-07-02 - A simple Go library for sending mails in Go.
* [go-message](https://github.com/emersion/go-message) ⭐ 418 | 🐛 31 | 🌐 Go | 📅 2025-02-16 - Streaming library for the Internet Message Format and mail messages.
* [go-premailer](https://github.com/vanng822/go-premailer) ⭐ 171 | 🐛 3 | 🌐 Go | 📅 2025-06-29 - Inline styling for HTML mail in Go.
* [go-simple-mail](https://github.com/xhit/go-simple-mail) ⭐ 678 | 🐛 16 | 🌐 Go | 📅 2024-07-20 - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
* [Hectane](https://github.com/hectane/hectane) ⭐ 224 | 🐛 16 | 🌐 Go | 📅 2020-11-29 - Lightweight SMTP client providing an HTTP API.
* [hermes](https://github.com/matcornic/hermes) ⭐ 2,906 | 🐛 20 | 🌐 Go | 📅 2025-04-04 - Golang package that generates clean, responsive HTML e-mails.
* [Maddy](https://github.com/foxcpp/maddy) ⭐ 5,584 | 🐛 131 | 🌐 Go | 📅 2025-04-16 - All-in-one (SMTP, IMAP, DKIM, DMARC, MTA-STS, DANE) email server
* [mailchain](https://github.com/mailchain/mailchain) ⭐ 143 | 🐛 44 | 📅 2022-04-01 - Send encrypted emails to blockchain addresses written in Go.
* [mailgun-go](https://github.com/mailgun/mailgun-go) ⭐ 730 | 🐛 1 | 🌐 Go | 📅 2025-06-27 - Go library for sending mail with the Mailgun API.
* [MailHog](https://github.com/mailhog/MailHog) ⭐ 14,995 | 🐛 251 | 🌐 Go | 📅 2024-02-13 - Email and SMTP testing with web and API interface.
* [Mailpit](https://github.com/axllent/mailpit) ⭐ 7,304 | 🐛 1 | 🌐 Go | 📅 2025-07-02 - Email and SMTP testing tool for developers.
* [mailx](https://github.com/valord577/mailx) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2025-04-24 - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`.
* [mox](https://github.com/mjl-/mox) ⭐ 5,050 | 🐛 147 | 🌐 Go | 📅 2025-06-09 - Modern full-featured secure mail server for low-maintenance, self-hosted email.
* [SendGrid](https://github.com/sendgrid/sendgrid-go) ⭐ 1,019 | 🐛 32 | 🌐 Go | 📅 2025-05-29 - SendGrid's Go library for sending email.
* [smtp](https://github.com/mailhog/smtp) ⭐ 75 | 🐛 7 | 🌐 Go | 📅 2021-10-20 - SMTP server protocol state machine.
* [smtpmock](https://github.com/mocktools/go-smtp-mock) ⭐ 152 | 🐛 6 | 🌐 Go | 📅 2025-06-24 - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment.
* [truemail-go](https://github.com/truemail-rb/truemail-go) ⭐ 119 | 🐛 1 | 🌐 Go | 📅 2024-08-30 - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more.

**[⬆ back to top](#contents)**

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [anko](https://github.com/mattn/anko) ⭐ 1,522 | 🐛 25 | 🌐 Go | 📅 2025-04-03 - Scriptable interpreter written in Go.
* [binder](https://github.com/alexeyco/binder) ⭐ 79 | 🐛 2 | 🌐 Go | 📅 2022-07-07 - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua) ⭐ 6,634 | 🐛 102 | 🌐 Go | 📅 2024-11-09.
* [cel-go](https://github.com/google/cel-go) ⭐ 2,601 | 🐛 49 | 🌐 Go | 📅 2025-07-01 - Fast, portable, non-Turing complete expression evaluation with gradual typing.
* [ecal](https://github.com/krotik/ecal) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2021-05-23 - A simple embeddable scripting language which supports concurrent event processing.
* [expr](https://github.com/antonmedv/expr) ⭐ 6,977 | 🐛 45 | 🌐 Go | 📅 2025-06-30 - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
* [FrankenPHP](https://github.com/dunglas/frankenphp) ⭐ 9,511 | 🐛 168 | 🌐 Go | 📅 2025-07-01 - PHP embedded in Go, with a `net/http` handler.
* [gentee](https://github.com/gentee/gentee) ⭐ 138 | 🐛 3 | 🌐 Go | 📅 2025-01-31 - Embeddable scripting programming language.
* [gisp](https://github.com/jcla1/gisp) ⭐ 523 | 🐛 1 | 🌐 Go | 📅 2017-08-25 - Simple LISP in Go.
* [go-duktape](https://github.com/olebedev/go-duktape) ⚠️ Archived - Duktape JavaScript engine bindings for Go.
* [go-lua](https://github.com/Shopify/go-lua) ⭐ 3,290 | 🐛 50 | 🌐 Go | 📅 2025-06-05 - Port of the Lua 5.2 VM to pure Go.
* [go-php](https://github.com/deuill/go-php) ⭐ 941 | 🐛 22 | 🌐 Go | 📅 2025-01-06 - PHP bindings for Go.
* [go-python](https://github.com/sbinet/go-python) ⚠️ Archived - naive go bindings to the CPython C-API.
* [goal](https://codeberg.org/anaseto/goal) - An embeddable scripting array language.
* [goja](https://github.com/dop251/goja) ⭐ 6,252 | 🐛 26 | 🌐 Go | 📅 2025-06-30 - ECMAScript 5.1(+) implementation in Go.
* [golua](https://github.com/aarzilli/golua) ⭐ 674 | 🐛 9 | 🌐 C | 📅 2025-02-17 - Go bindings for Lua C API.
* [gopher-lua](https://github.com/yuin/gopher-lua) ⭐ 6,634 | 🐛 102 | 🌐 Go | 📅 2024-11-09 - Lua 5.1 VM and compiler written in Go.
* [gval](https://github.com/PaesslerAG/gval) ⭐ 792 | 🐛 24 | 🌐 Go | 📅 2024-11-28 - A highly customizable expression language written in Go.
* [metacall](https://github.com/metacall/core) ⭐ 1,661 | 🐛 53 | 🌐 C | 📅 2025-07-02 - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more.
* [ngaro](https://github.com/db47h/ngaro) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2018-06-03 - Embeddable Ngaro VM implementation enabling scripting in Retro.
* [prolog](https://github.com/ichiban/prolog) ⭐ 676 | 🐛 23 | 🌐 Go | 📅 2024-11-24 - Embeddable Prolog.
* [purl](https://github.com/ian-kent/purl) ⭐ 41 | 🐛 2 | 🌐 Go | 📅 2014-12-07 - Perl 5.18.2 embedded in Go.
* [starlark-go](https://github.com/google/starlark-go) ⭐ 2,488 | 🐛 64 | 🌐 Go | 📅 2025-07-01 - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution.
* [starlet](https://github.com/1set/starlet) ⭐ 30 | 🐛 2 | 🌐 Go | 📅 2025-04-15 - Go wrapper for [starlark-go](https://github.com/google/starlark-go) ⭐ 2,488 | 🐛 64 | 🌐 Go | 📅 2025-07-01 that simplifies script execution, offers data conversion, and useful Starlark libraries and extensions.
* [tengo](https://github.com/d5/tengo) ⭐ 3,660 | 🐛 84 | 🌐 Go | 📅 2025-05-24 - Bytecode compiled script language for Go.
* [Wa/凹语言](https://github.com/wa-lang/wa) ⭐ 1,588 | 🐛 6 | 🌐 Go | 📅 2025-07-02 - The Wa Programming Language embedded in Go.

**[⬆ back to top](#contents)**

## Error Handling

*Libraries for handling errors.*

* [emperror](https://github.com/emperror/emperror) ⭐ 358 | 🐛 6 | 🌐 Go | 📅 2020-10-04 - Error handling tools and best practices for Go libraries and applications.
* [eris](https://github.com/rotisserie/eris) ⭐ 1,676 | 🐛 5 | 🌐 Go | 📅 2025-04-03 - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
* [errlog](https://github.com/snwfdhmp/errlog) ⭐ 461 | 🐛 0 | 🌐 Go | 📅 2023-06-27 - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
* [errors](https://github.com/emperror/errors) ⭐ 200 | 🐛 11 | 🌐 Go | 📅 2022-06-20 - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
* [errors](https://github.com/neuronlabs/errors) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2019-08-02 - Simple golang error handling with classification primitives.
* [errors](https://github.com/PumpkinSeed/errors) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2022-03-31 - The most simple error wrapper with awesome performance and minimal memory overhead.
* [errors](https://gitlab.com/tozd/go/errors) - Providing errors with a stack trace and optional structured details. Compatible with github.com/pkg/errors API but does not use it internally.
* [errors](https://github.com/naughtygopher/errors) ⭐ 72 | 🐛 0 | 🌐 Go | 📅 2025-01-25 - Drop-in replacement for builtin Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
* [errors](https://github.com/cockroachdb/errors) ⭐ 2,244 | 🐛 18 | 🌐 Go | 📅 2025-05-16 - Go error library with error portability over the network.
* [errorx](https://github.com/joomcode/errorx) ⭐ 1,257 | 🐛 6 | 🌐 Go | 📅 2024-11-08 - A feature rich error package with stack traces, composition of errors and more.
* [exception](https://github.com/rbrahul/exception) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2022-11-21 - A simple utility package for exception handling with try-catch in Golang.
* [Falcon](https://github.com/SonicRoshan/falcon) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-10-10 - A Simple Yet Highly Powerful Package For Error Handling.
* [Fault](https://github.com/Southclaws/fault) ⭐ 284 | 🐛 9 | 🌐 Go | 📅 2025-06-14 - An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values.
* [go-multierror](https://github.com/hashicorp/go-multierror) ⭐ 2,469 | 🐛 28 | 🌐 Go | 📅 2025-07-01 - Go (golang) package for representing a list of errors as a single error.
* [metaerr](https://github.com/quantumcycle/metaerr) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-05-09 - A library to create your custom error builders producing structured errors with metadata from different sources and optional stacktraces.
* [multierr](https://github.com/uber-go/multierr) ⭐ 1,142 | 🐛 2 | 🌐 Go | 📅 2024-04-29 - Package for representing a list of errors as a single error.
* [oops](https://github.com/samber/oops) ⭐ 703 | 🐛 15 | 🌐 Go | 📅 2025-07-02 - Error handling with context, stack trace and source fragments.
* [tracerr](https://github.com/ztrue/tracerr) ⭐ 1,091 | 🐛 3 | 🌐 Go | 📅 2024-05-29 - Golang errors with stack trace and source fragments.

**[⬆ back to top](#contents)**

## File Handling

*Libraries for handling files and file systems.*

* [afero](https://github.com/spf13/afero) ⭐ 6,258 | 🐛 153 | 🌐 Go | 📅 2025-07-01 - FileSystem Abstraction System for Go.
* [afs](https://github.com/viant/afs) ⭐ 338 | 🐛 5 | 🌐 Go | 📅 2025-04-29 - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
* [baraka](https://github.com/xis/baraka) ⭐ 59 | 🐛 2 | 🌐 Go | 📅 2022-09-30 - A library to process http file uploads easily.
* [checksum](https://github.com/codingsince1985/checksum) ⭐ 110 | 🐛 2 | 🌐 Go | 📅 2023-12-19 - Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files.
* [copy](https://github.com/otiai10/copy) ⭐ 761 | 🐛 21 | 🌐 Go | 📅 2025-01-05 - Copy directory recursively.
* [fastwalk](https://github.com/charlievieth/fastwalk) ⭐ 98 | 🐛 3 | 🌐 Go | 📅 2025-06-21 - Fast parallel directory traversal library (used by [fzf](https://github.com/junegunn/fzf) ⭐ 71,464 | 🐛 289 | 🌐 Go | 📅 2025-07-02).
* [flop](https://github.com/homedepot/flop) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2021-12-07 - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
* [gdu](https://github.com/dundee/gdu) ⭐ 4,581 | 🐛 51 | 🌐 Go | 📅 2025-07-02 - Disk usage analyzer with console interface.
* [go-csv-tag](https://github.com/artonge/go-csv-tag) ⭐ 126 | 🐛 0 | 🌐 Go | 📅 2025-06-17 - Load csv file using tag.
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) ⭐ 22 | 🐛 1 | 🌐 Go | 📅 2020-01-03 - Copy files for humans.
* [go-exiftool](https://github.com/barasher/go-exiftool) ⭐ 268 | 🐛 12 | 🌐 Go | 📅 2024-07-18 - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
* [go-gtfs](https://github.com/artonge/go-gtfs) ⭐ 48 | 🐛 0 | 🌐 Go | 📅 2023-08-16 - Load gtfs files in go.
* [go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) ⭐ 1,128 | 🐛 10 | 🌐 Go | 📅 2024-07-02 - A package to convert an HTML template to a PDF file.
* [gofs](https://github.com/no-src/gofs) ⭐ 510 | 🐛 5 | 🌐 Go | 📅 2025-07-02 - A cross-platform real-time file synchronization tool out of the box.
* [gulter](https://github.com/adelowo/gulter) ⭐ 65 | 🐛 0 | 🌐 Go | 📅 2025-03-18 - A simple HTTP middleware to automatically handle all your file upload needs
* [gut/yos](https://github.com/1set/gut) ⭐ 26 | 🐛 13 | 🌐 Go | 📅 2020-11-17 - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
* [higgs](https://github.com/dastoori/higgs) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2022-01-29 - A tiny cross-platform Go library to hide/unhide files and directories.
* [iso9660](https://github.com/kdomanski/iso9660) ⭐ 275 | 🐛 14 | 🌐 Go | 📅 2024-01-23 - A package for reading and creating ISO9660 disk images
* [notify](https://github.com/rjeczalik/notify) ⭐ 918 | 🐛 49 | 🌐 Go | 📅 2024-02-26 - File system event notification library with simple API, similar to os/signal.
* [opc](https://github.com/qmuntal/opc) ⭐ 75 | 🐛 1 | 🌐 Go | 📅 2023-12-01 - Load Open Packaging Conventions (OPC) files for Go.
* [parquet](https://github.com/parsyl/parquet) ⭐ 117 | 🐛 2 | 🌐 Go | 📅 2025-04-17 - Read and write [parquet](https://parquet.apache.org) files.
* [pathtype](https://github.com/jonchun/pathtype) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2021-08-12 - Treat paths as their own type instead of using strings.
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) ⭐ 7,769 | 🐛 123 | 🌐 Go | 📅 2025-06-28 - PDF processor.
* [skywalker](https://github.com/dixonwille/skywalker) ⭐ 103 | 🐛 1 | 🌐 Go | 📅 2021-08-31 - Package to allow one to concurrently go through a filesystem with ease.
* [todotxt](https://github.com/1set/todotxt) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2023-09-21 - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt) ⭐ 2,836 | 🐛 39 | 📅 2025-01-16.
* [vfs](https://github.com/C2FO/vfs) ⭐ 340 | 🐛 9 | 🌐 Go | 📅 2025-05-12 - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.

**[⬆ back to top](#contents)**

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) ⭐ 899 | 🐛 13 | 🌐 Go | 📅 2022-07-28 - money and currency formatting for golang.
* [ach](https://github.com/moov-io/ach) ⭐ 492 | 🐛 13 | 🌐 Go | 📅 2025-07-02 - A reader, writer, and validator for Automated Clearing House (ACH) files.
* [bbgo](https://github.com/c9s/bbgo) ⭐ 1,377 | 🐛 136 | 🌐 Go | 📅 2025-07-02 - A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies.
* [currency](https://github.com/bojanz/currency) ⭐ 593 | 🐛 5 | 🌐 Go | 📅 2025-03-28 - Handles currency amounts, provides currency information and formatting.
* [currency](https://github.com/naughtygopher/currency) ⭐ 61 | 🐛 0 | 🌐 Go | 📅 2025-05-26 - High performant & accurate currency computation package.
* [decimal](https://github.com/shopspring/decimal) ⭐ 6,820 | 🐛 141 | 🌐 Go | 📅 2025-06-24 - Arbitrary-precision fixed-point decimal numbers.
* [decimal](https://github.com/govalues/decimal) ⭐ 173 | 🐛 6 | 🌐 Go | 📅 2025-01-18 - Immutable decimal numbers with panic-free arithmetic.
* [fpdecimal](https://github.com/nikolaydubina/fpdecimal) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2024-11-29 - Fast and precise serialization and arithmetic for small fixed-point decimals
* [fpmoney](https://github.com/nikolaydubina/fpmoney) ⭐ 34 | 🐛 3 | 🌐 Go | 📅 2025-04-16 - Fast and simple ISO4217 fixed-point decimal money.
* [go-finance](https://github.com/alpeb/go-finance) ⭐ 184 | 🐛 1 | 🌐 Go | 📅 2021-12-02 - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
* [go-finance](https://github.com/pieterclaerhout/go-finance) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2024-11-25 - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
* [go-finnhub](https://github.com/m1/go-finnhub) ⚠️ Archived - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
* [go-money](https://github.com/rhymond/go-money) ⭐ 1,777 | 🐛 23 | 🌐 Go | 📅 2025-04-30 - Implementation of Fowler's Money pattern.
* [go-nowpayments](https://github.com/matm/go-nowpayments) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2023-01-24 - Library for the crypto NOWPayments API.
* [ledger](https://github.com/formancehq/ledger) ⭐ 987 | 🐛 7 | 🌐 Go | 📅 2025-07-02 - A programmable financial ledger that provides a foundation for money-moving applications.
* [money](https://github.com/govalues/money) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2025-01-25 - Immutable monetary amounts and exchange rates with panic-free arithmetic.
* [ofxgo](https://github.com/aclindsa/ofxgo) ⭐ 144 | 🐛 0 | 🌐 Go | 📅 2024-04-11 - Query OFX servers and/or parse the responses (with example command-line client).
* [orderbook](https://github.com/i25959341/orderbook) ⭐ 497 | 🐛 5 | 🌐 Go | 📅 2025-04-04 - Matching Engine for Limit Order Book in Golang.
* [payme](https://github.com/jovandeginste/payme) ⭐ 88 | 🐛 1 | 🌐 Go | 📅 2024-08-09 - QR code generator (ASCII & PNG) for SEPA payments.
* [sleet](https://github.com/BoltApp/sleet) ⚠️ Archived - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
* [swift](https://code.pfad.fr/swift/) - Offline validity check of IBAN (International Bank Account Number) and retrieval of BIC (for some countries).
* [techan](https://github.com/sdcoffey/techan) ⭐ 866 | 🐛 21 | 🌐 Go | 📅 2023-09-13 - Technical analysis library with advanced market analysis and trading strategies.
* [ticker](https://github.com/achannarasappa/ticker) ⭐ 5,303 | 🐛 37 | 🌐 Go | 📅 2025-05-29 - Terminal stock watcher and stock position tracker.
* [transaction](https://github.com/claygod/transaction) ⭐ 136 | 🐛 0 | 🌐 Go | 📅 2025-04-24 - Embedded transactional database of accounts, running in multithreaded mode.
* [udecimal](https://github.com/quagmt/udecimal) ⭐ 149 | 🐛 1 | 🌐 Go | 📅 2025-06-19 - High performance, high precision, zero allocation fixed-point decimal library for financial applications.
* [vat](https://github.com/dannyvankooten/vat) ⭐ 116 | 🐛 3 | 🌐 Go | 📅 2023-11-07 - VAT number validation & EU VAT rates.

**[⬆ back to top](#contents)**

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2014-08-16 - Bind form data to any Go values.
* [checker](https://github.com/cinar/checker) ⭐ 42 | 🐛 7 | 🌐 Go | 📅 2025-01-03 - Checker helps validating user input through rules defined in struct tags or directly through functions.
* [conform](https://github.com/leebenson/conform) ⭐ 324 | 🐛 5 | 🌐 Go | 📅 2023-12-23 - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* [form](https://github.com/go-playground/form) ⭐ 843 | 🐛 15 | 🌐 Go | 📅 2025-03-21 - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* [formam](https://github.com/monoculum/formam) ⭐ 192 | 🐛 3 | 🌐 Go | 📅 2022-11-06 - decode form's values into a struct.
* [forms](https://github.com/albrow/forms) ⭐ 142 | 🐛 2 | 🌐 Go | 📅 2022-12-16 - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* [gbind](https://github.com/bdjimmy/gbind) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2022-06-14 - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation
* [gorilla/csrf](https://github.com/gorilla/csrf) ⭐ 1,128 | 🐛 27 | 🌐 Go | 📅 2025-04-14 - CSRF protection for Go web applications & services.
* [httpin](https://github.com/ggicci/httpin) ⭐ 361 | 🐛 9 | 🌐 Go | 📅 2025-06-20 - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.
* [nosurf](https://github.com/justinas/nosurf) ⭐ 1,675 | 🐛 15 | 🌐 Go | 📅 2025-05-13 - CSRF protection middleware for Go.
* [qs](https://github.com/sonh/qs) ⭐ 78 | 🐛 0 | 🌐 Go | 📅 2025-03-15 - Go module for encoding structs into URL query parameters.
* [queryparam](https://github.com/tomwright/queryparam) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2020-09-23 - Decode `url.Values` into usable struct values of standard or custom types.

**[⬆ back to top](#contents)**

## Functional

*Packages to support functional programming in Go.*

* [fp-go](https://github.com/repeale/fp-go) ⭐ 316 | 🐛 4 | 🌐 Go | 📅 2022-12-01 - Collection of Functional Programming helpers powered by Golang 1.18+ generics.
* [fpGo](https://github.com/TeaEntityLab/fpGo) ⭐ 351 | 🐛 0 | 🌐 Go | 📅 2024-10-28 - Monad, Functional Programming features for Golang.
* [fuego](https://github.com/seborama/fuego) ⭐ 144 | 🐛 0 | 🌐 Go | 📅 2024-04-13 - Functional Experiment in Go.
* [go-functional](https://github.com/BooleanCat/go-functional) ⭐ 504 | 🐛 1 | 🌐 Go | 📅 2025-06-13 - Functional programming in Go using generics
* [go-underscore](https://github.com/tobyhede/go-underscore) ⭐ 1,302 | 🐛 4 | 🌐 Go | 📅 2023-02-28 - Useful collection of helpfully functional Go collection utilities.
* [gofp](https://github.com/rbrahul/gofp) ⭐ 150 | 🐛 0 | 🌐 Go | 📅 2021-02-23 - A lodash like powerful utility library for Golang.
* [mo](https://github.com/samber/mo) ⭐ 3,011 | 🐛 23 | 🌐 Go | 📅 2025-07-02 - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...).
* [underscore](https://github.com/rjNemo/underscore) ⭐ 116 | 🐛 2 | 🌐 Go | 📅 2024-12-03 - Functional programming helpers for Go 1.18 and beyond.
* [valor](https://github.com/phelmkamp/valor) ⭐ 17 | 🐛 3 | 🌐 Go | 📅 2023-07-27 - Generic option and result types that optionally contain a value.

**[⬆ back to top](#contents)**

## Game Development

*Awesome game development libraries.*

* [Ark](https://github.com/mlange-42/ark) ⭐ 88 | 🐛 9 | 🌐 Go | 📅 2025-05-16 - Archetype-based Entity Component System (ECS) for Go.
* [Ebitengine](https://github.com/hajimehoshi/ebiten) ⭐ 12,188 | 🐛 304 | 🌐 Go | 📅 2025-07-02 - dead simple 2D game engine in Go.
* [ecs](https://github.com/andygeiss/ecs) ⭐ 146 | 🐛 0 | 🌐 Go | 📅 2024-09-01 - Build your own Game-Engine based on the Entity Component System concept in Golang.
* [engo](https://github.com/EngoEngine/engo) ⭐ 1,802 | 🐛 52 | 🌐 Go | 📅 2025-04-16 - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* [fantasyname](https://github.com/s0rg/fantasyname) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2025-04-25 - Fantasy names generator.
* [g3n](https://github.com/g3n/engine) ⭐ 2,961 | 🐛 37 | 🌐 Go | 📅 2025-02-08 - Go 3D Game Engine.
* [go-astar](https://github.com/beefsack/go-astar) ⭐ 615 | 🐛 3 | 🌐 Go | 📅 2022-01-27 - Go implementation of the A\* path finding algorithm.
* [go-sdl2](https://github.com/veandco/go-sdl2) ⭐ 2,298 | 🐛 87 | 🌐 C | 📅 2025-02-20 - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d](https://github.com/ungerik/go3d) ⭐ 323 | 🐛 2 | 🌐 Go | 📅 2024-05-02 - Performance oriented 2D/3D math package for Go.
* [gonet](https://github.com/xtaci/gonet) ⭐ 1,284 | 🐛 0 | 🌐 Go | 📅 2024-07-25 - Game server skeleton implemented with golang.
* [goworld](https://github.com/xiaonanln/goworld) ⭐ 2,655 | 🐛 27 | 🌐 Go | 📅 2023-11-27 - Scalable game server engine, featuring space-entity framework and hot-swapping.
* [grid](https://github.com/s0rg/grid) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2025-05-09 - Generic 2D grid with ray-casting, shadow-casting and path finding.
* [Harfang3D](https://github.com/harfang3d/harfang3d) ⭐ 618 | 🐛 5 | 🌐 C++ | 📅 2023-09-08 - 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev](https://github.com/harfang3d/harfang-go) ⚠️ Archived).
* [Leaf](https://github.com/name5566/leaf) ⭐ 5,421 | 🐛 24 | 🌐 Go | 📅 2024-05-23 - Lightweight game server framework.
* [nano](https://github.com/lonng/nano) ⭐ 3,041 | 🐛 30 | 🌐 Go | 📅 2025-03-30 - Lightweight, facility, high performance golang based game server framework.
* [Oak](https://github.com/oakmound/oak) ⭐ 1,631 | 🐛 14 | 🌐 Go | 📅 2025-02-16 - Pure Go game engine.
* [Pitaya](https://github.com/topfreegames/pitaya) ⭐ 2,569 | 🐛 58 | 🌐 Go | 📅 2025-06-04 - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
* [Pixel](https://github.com/gopxl/pixel) ⭐ 331 | 🐛 33 | 🌐 Go | 📅 2025-03-07 - Hand-crafted 2D game library in Go.
* [prototype](https://github.com/gonutz/prototype) ⭐ 90 | 🐛 2 | 🌐 Go | 📅 2025-07-01 - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
* [raylib-go](https://github.com/gen2brain/raylib-go) ⭐ 2,096 | 🐛 4 | 🌐 C | 📅 2025-06-17 - Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [termloop](https://github.com/JoelOtter/termloop) ⭐ 1,459 | 🐛 6 | 🌐 Go | 📅 2024-07-29 - Terminal-based game engine for Go, built on top of Termbox.
* [tile](https://github.com/kelindar/tile) ⭐ 196 | 🐛 2 | 🌐 Go | 📅 2025-06-28 - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

**[⬆ back to top](#contents)**

## Generators

*Tools that generate Go code.*

* [convergen](https://github.com/reedom/convergen) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2025-06-11 - Feature rich type-to-type copy code generator.
* [copygen](https://github.com/switchupcb/copygen) ⭐ 391 | 🐛 3 | 🌐 Go | 📅 2025-03-06 - Generate any code based on Go types, including type-to-type converters (copy code) without reflection by default.
* [generis](https://github.com/senselogic/GENERIS) ⭐ 47 | 🐛 0 | 🌐 D | 📅 2022-02-22 - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
* [go-enum](https://github.com/abice/go-enum) ⭐ 839 | 🐛 17 | 🌐 Go | 📅 2025-06-22 - Code generation for enums from code comments.
* [go-enum-encoding](https://github.com/nikolaydubina/go-enum-encoding) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2025-03-14 - Code generation for enum encoding from code comments.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) ⭐ 3,589 | 🐛 11 | 🌐 Go | 📅 2022-08-08 - .NET LINQ-like query methods for Go.
* [goderive](https://github.com/awalterschulze/goderive) ⭐ 1,261 | 🐛 19 | 🌐 Go | 📅 2025-03-06 - Derives functions from input types
* [goverter](https://github.com/jmattheis/goverter) ⭐ 711 | 🐛 16 | 🌐 Go | 📅 2025-06-21 - Generate converters by defining an interface.
* [GoWrap](https://github.com/hexdigest/gowrap) ⭐ 1,228 | 🐛 22 | 🌐 Go | 📅 2025-06-27 - Generate decorators for Go interfaces using simple templates.
* [interfaces](https://github.com/rjeczalik/interfaces) ⭐ 431 | 🐛 14 | 🌐 Go | 📅 2025-06-03 - Command line tool for generating interface definitions.
* [jennifer](https://github.com/dave/jennifer) ⭐ 3,515 | 🐛 17 | 🌐 Go | 📅 2024-09-08 - Generate arbitrary Go code without templates.
* [oapi-codegen](https://github.com/deepmap/oapi-codegen) ⭐ 7,281 | 🐛 691 | 🌐 Go | 📅 2025-06-29 - This package contains a set of utilities for generating Go boilerplate code for services based on OpenAPI 3.0 API definitions.
* [typeregistry](https://github.com/xiaoxin01/typeregistry) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2020-02-20 - A library to create type dynamically.

**[⬆ back to top](#contents)**

## Geographic

*Geographic tools and servers*

* [geoos](https://github.com/spatial-go/geoos) ⭐ 520 | 🐛 20 | 🌐 Go | 📅 2024-07-03 - A library provides spatial data and geometric algorithms.
* [geoserver](https://github.com/hishamkaram/geoserver) ⭐ 92 | 🐛 4 | 🌐 Go | 📅 2023-02-28 - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
* [gismanager](https://github.com/hishamkaram/gismanager) ⭐ 54 | 🐛 1 | 🌐 Go | 📅 2018-10-30 - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
* [godal](https://github.com/airbusgeo/godal) ⭐ 165 | 🐛 7 | 🌐 Go | 📅 2025-02-26 - Go wrapper for GDAL.
* [H3](https://github.com/uber/h3-go) ⭐ 354 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - Go bindings for H3, a hierarchical hexagonal geospatial indexing system.
* [H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2022-05-11 - Conversion utilities between H3 indexes and GeoJSON.
* [H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2022-05-11 - Distribution of Uber H3geo cells by virtual nodes.
* [mbtileserver](https://github.com/consbio/mbtileserver) ⭐ 732 | 🐛 18 | 🌐 Go | 📅 2025-05-21 - A simple Go-based server for map tiles stored in mbtiles format.
* [osm](https://github.com/paulmach/osm) ⭐ 411 | 🐛 6 | 🌐 Go | 📅 2024-05-06 - Library for reading, writing and working with OpenStreetMap data and APIs.
* [pbf](https://github.com/maguro/pbf) ⭐ 50 | 🐛 2 | 🌐 Go | 📅 2025-01-15 - OpenStreetMap PBF golang encoder/decoder.
* [S2 geojson](https://github.com/pantrif/s2-geojson) ⭐ 35 | 🐛 2 | 🌐 Go | 📅 2024-08-16 - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
* [S2 geometry](https://github.com/golang/geo) ⭐ 1,759 | 🐛 34 | 🌐 Go | 📅 2025-07-02 - S2 geometry library in Go.
* [simplefeatures](https://github.com/peterstace/simplefeatures) ⭐ 149 | 🐛 49 | 🌐 Go | 📅 2025-06-20 - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
* [Tile38](https://github.com/tidwall/tile38) ⭐ 9,366 | 🐛 151 | 🌐 Go | 📅 2025-06-17 - Geolocation DB with spatial index and realtime geofencing.
* [Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2022-03-24 A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection.
* [WGS84](https://github.com/wroge/wgs84) ⭐ 138 | 🐛 5 | 🌐 Go | 📅 2025-02-22 - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).

**[⬆ back to top](#contents)**

## Go Compilers

*Tools for compiling Go to other languages and vice-versa.*

* [bunster](https://github.com/yassinebenaid/bunster) ⭐ 2,420 | 🐛 12 | 🌐 Go | 📅 2025-05-18 - Compile shell scripts to Go.
* [c4go](https://github.com/Konstantin8105/c4go) ⭐ 374 | 🐛 27 | 🌐 C | 📅 2024-09-19 - Transpile C code to Go code.
* [esp32](https://github.com/andygeiss/esp32-transpiler) ⭐ 93 | 🐛 0 | 🌐 Go | 📅 2024-08-05 - Transpile Go into Arduino code.
* [f4go](https://github.com/Konstantin8105/f4go) ⭐ 48 | 🐛 7 | 🌐 Go | 📅 2023-08-17 - Transpile FORTRAN 77 code to Go code.
* [go2hx](https://github.com/go2hx/go2hx) ⭐ 137 | 🐛 31 | 🌐 Haxe | 📅 2025-07-02 - Compiler from Go to Haxe to Javascript/C++/Java/C#.
* [gopherjs](https://github.com/gopherjs/gopherjs) ⭐ 12,992 | 🐛 191 | 🌐 Go | 📅 2025-06-16 - Compiler from Go to JavaScript.

**[⬆ back to top](#contents)**

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) ⭐ 13,792 | 🐛 0 | 🌐 Go | 📅 2025-04-12 - A high-performance and low-cost goroutine pool in Go.
* [artifex](https://github.com/borderstech/artifex) ⭐ 212 | 🐛 1 | 🌐 Go | 📅 2024-07-19 - Simple in-memory job queue for Golang using worker-based dispatching.
* [async](https://github.com/yaitoo/async) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2024-11-25 - An asynchronous task package with async/await style for Go.
* [async](https://github.com/reugn/async) ⭐ 249 | 🐛 1 | 🌐 Go | 📅 2025-06-27 - An alternative sync library for Go (Future, Promise, Locks).
* [async](https://github.com/studiosol/async) ⭐ 139 | 🐛 2 | 🌐 Go | 📅 2020-11-19 - A safe way to execute functions asynchronously, recovering them in case of panic.
* [async-job](https://github.com/lab210-dev/async-job) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2022-05-30 - AsyncJob is an asynchronous queue job manager with light code, clear and speed.
* [breaker](https://github.com/kamilsk/breaker) ⭐ 20 | 🐛 0 | 📅 2021-07-11 - Flexible mechanism to make execution flow interruptible.
* [channelify](https://github.com/ddelizia/channelify) ⭐ 33 | 🐛 1 | 🌐 Go | 📅 2021-02-25 - Transform your function to return channels for easy and powerful parallel processing.
* [conc](https://github.com/sourcegraph/conc) ⭐ 9,977 | 🐛 24 | 🌐 Go | 📅 2024-04-26 - `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer.
* [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2022-12-29 - Concurrency limiter with support for timeouts, dynamic priority and context cancellation of goroutines.
* [conexec](https://github.com/ITcathyh/conexec) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2020-06-28 - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) ⭐ 153 | 🐛 0 | 🌐 Go | 📅 2020-06-30 - CyclicBarrier for golang.
* [execpool](https://github.com/hexdigest/execpool) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2021-07-06 - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
* [flowmatic](https://github.com/carlmjohnson/flowmatic) ⭐ 387 | 🐛 1 | 🌐 Go | 📅 2024-09-30 - Structured concurrency made easy.
* [go-accumulator](https://github.com/nar10z/go-accumulator) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2025-04-18 - Solution for accumulation of events and their subsequent processing.
* [go-actor](https://github.com/vladopajic/go-actor) ⭐ 228 | 🐛 0 | 🌐 Go | 📅 2025-06-05 - A tiny library for writing concurrent programs using actor model.
* [go-floc](https://github.com/workanator/go-floc) ⭐ 268 | 🐛 1 | 🌐 Go | 📅 2021-08-10 - Orchestrate goroutines with ease.
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) ⭐ 223 | 🐛 1 | 🌐 Go | 📅 2019-05-14 - Control goroutines execution order.
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2019-03-27 - Manage a pool of goroutines using this lightweight library with a simple API.
* [go-trylock](https://github.com/subchen/go-trylock) ⭐ 37 | 🐛 1 | 🌐 Go | 📅 2021-05-07 - TryLock support on read-write lock for Golang.
* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2024-11-26 - Like `sync.WaitGroup` with error handling and concurrency control.
* [go-workerpool](https://github.com/zenthangplus/go-workerpool) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2022-08-20 - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines.
* [go-workers](https://github.com/catmullet/go-workers) ⚠️ Archived - Easily and safely run workers for large data processing pipelines.
* [goccm](https://github.com/zenthangplus/goccm) ⭐ 73 | 🐛 3 | 🌐 Go | 📅 2023-01-18 - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
* [gohive](https://github.com/loveleshsharma/gohive) ⭐ 53 | 🐛 2 | 🌐 Go | 📅 2023-11-19 - A highly performant and easy to use Goroutine pool for Go.
* [gollback](https://github.com/vardius/gollback) ⭐ 124 | 🐛 1 | 🌐 Go | 📅 2023-02-16 - asynchronous simple function utilities, for managing execution of closures and callbacks.
* [gowl](https://github.com/hamed-yousefi/gowl) ⭐ 70 | 🐛 5 | 🌐 Go | 📅 2023-10-19 - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
* [goworker](https://github.com/benmanns/goworker) ⭐ 2,825 | 🐛 34 | 🌐 Go | 📅 2025-04-15 - goworker is a Go-based background worker.
* [gowp](https://github.com/xxjwxc/gowp) ⭐ 526 | 🐛 3 | 🌐 Go | 📅 2024-09-29 - gowp is concurrency limiting goroutine pool.
* [gpool](https://github.com/Sherifabdlnaby/gpool) ⭐ 90 | 🐛 0 | 🌐 Go | 📅 2019-12-16 - manages a resizeable pool of context-aware goroutines to bound concurrency.
* [grpool](https://github.com/ivpusic/grpool) ⭐ 744 | 🐛 5 | 🌐 Go | 📅 2019-01-27 - Lightweight Goroutine pool.
* [hands](https://github.com/duanckham/hands) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2022-04-05 - A process controller used to control the execution and return strategies of multiple goroutines.
* [Hunch](https://github.com/AaronJan/Hunch) ⭐ 105 | 🐛 2 | 🌐 Go | 📅 2022-06-26 - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
* [kyoo](https://github.com/dirkaholic/kyoo) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2023-02-21 - Provides an unlimited job queue and concurrent worker pools.
* [neilotoole/errgroup](https://github.com/neilotoole/errgroup) ⭐ 165 | 🐛 5 | 🌐 Go | 📅 2023-01-10 - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
* [nursery](https://github.com/arunsworld/nursery) ⭐ 69 | 🐛 1 | 🌐 Go | 📅 2021-07-08 - Structured concurrency in Go.
* [oversight](https://pkg.go.dev/cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2018-01-01 - Run functions in parallel.
* [pond](https://github.com/alitto/pond) ⭐ 1,878 | 🐛 3 | 🌐 Go | 📅 2025-06-20 - Minimalistic and High-performance goroutine worker pool written in Go.
* [pool](https://github.com/go-playground/pool) ⭐ 729 | 🐛 4 | 🌐 Go | 📅 2021-06-28 - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* [rill](https://github.com/destel/rill) ⭐ 1,686 | 🐛 2 | 🌐 Go | 📅 2025-02-02 - Go toolkit for clean, composable, channel-based concurrency.
* [routine](https://github.com/timandy/routine) ⭐ 266 | 🐛 0 | 🌐 Go | 📅 2025-06-09 - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully.
* [routine](https://github.com/x-mod/routine) ⭐ 62 | 🐛 0 | 🌐 Go | 📅 2024-01-11 - go routine control with context, support: Main, Go, Pool and some useful Executors.
* [semaphore](https://github.com/kamilsk/semaphore) ⭐ 103 | 🐛 6 | 🌐 Go | 📅 2020-04-16 - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* [semaphore](https://github.com/marusama/semaphore) ⭐ 178 | 🐛 0 | 🌐 Go | 📅 2021-03-28 - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
* [stl](https://github.com/ssgreg/stl) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2020-07-24 - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
* [threadpool](https://github.com/shettyh/threadpool) ⭐ 104 | 🐛 2 | 🌐 Go | 📅 2020-03-23 - Golang threadpool implementation.
* [tunny](https://github.com/Jeffail/tunny) ⭐ 4,000 | 🐛 8 | 🌐 Go | 📅 2023-03-09 - Goroutine pool for golang.
* [worker-pool](https://github.com/vardius/worker-pool) ⭐ 92 | 🐛 0 | 🌐 Go | 📅 2021-01-17 - goworker is a Go simple async worker pool.
* [workerpool](https://github.com/gammazero/workerpool) ⭐ 1,395 | 🐛 20 | 🌐 Go | 📅 2025-02-13 - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

**[⬆ back to top](#contents)**

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) ⭐ 8,718 | 🐛 42 | 🌐 Go | 📅 2025-04-16 - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [cimgui-go](https://github.com/AllenDang/cimgui-go) ⭐ 421 | 🐛 17 | 🌐 C++ | 📅 2025-07-01 - Auto generated Go wrapper for [Dear ImGui](https://github.com/ocornut/imgui) ⭐ 66,586 | 🐛 1,164 | 🌐 C++ | 📅 2025-06-30 via [cimgui](https://github.com/cimgui/cimgui) ⭐ 1,675 | 🐛 17 | 🌐 Lua | 📅 2025-07-01.
* [Cogent Core](https://github.com/cogentcore/core) ⭐ 2,033 | 🐛 224 | 🌐 Go | 📅 2025-06-30 - A framework for building 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and the web.
* [DarwinKit](https://github.com/progrium/darwinkit) ⭐ 5,272 | 🐛 37 | 🌐 Go | 📅 2025-03-08 - Build native macOS applications using Go.
* [energy](https://github.com/energye/energy) ⭐ 484 | 🐛 8 | 🌐 Go | 📅 2025-06-17 - Cross-platform based on LCL(Native System UI Control Library) and CEF(Chromium Embedded Framework) (Windows/ macOS / Linux)
* [fyne](https://github.com/fyne-io/fyne) ⭐ 26,675 | 🐛 751 | 🌐 Go | 📅 2025-07-02 - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
* [gio](https://gioui.org) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.
* [go-gtk](https://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) ⭐ 2,599 | 🐛 98 | 🌐 C++ | 📅 2023-05-13 - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [Goey](https://bitbucket.org/rj/goey/src/master/) - Cross platform UI toolkit aggregator for Windows / Linux / Mac. GTK, Cocoa, Windows API
* [goradd/html5tag](https://github.com/goradd/html5tag) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2023-12-10 - Library for outputting HTML5 tags.
* [gotk3](https://github.com/gotk3/gotk3) ⭐ 2,167 | 🐛 123 | 🌐 Go | 📅 2024-08-08 - Go bindings for GTK3.
* [gowd](https://github.com/dtylman/gowd) ⭐ 437 | 🐛 7 | 🌐 Go | 📅 2023-02-24 - Rapid and simple desktop UI development with GO, HTML, CSS and NW\.js. Cross platform.
* [qt](https://github.com/therecipe/qt) ⭐ 10,684 | 🐛 373 | 🌐 Go | 📅 2024-03-04 - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [Spot](https://github.com/roblillack/spot) ⭐ 1,227 | 🐛 7 | 🌐 Go | 📅 2024-12-19 - Reactive, cross-platform desktop GUI toolkit.
* [ui](https://github.com/andlabs/ui) ⭐ 8,350 | 🐛 124 | 🌐 Go | 📅 2022-05-19 - Platform-native GUI library for Go. Cross platform.
* [unison](https://github.com/richardwilkes/unison) ⭐ 272 | 🐛 1 | 🌐 Go | 📅 2025-06-27 - A unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported.
* [Wails](https://wails.io) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
* [walk](https://github.com/lxn/walk) ⭐ 6,981 | 🐛 346 | 🌐 Go | 📅 2024-01-21 - Windows application library kit for Go.
* [webview](https://github.com/zserge/webview) ⭐ 13,198 | 🐛 191 | 🌐 C++ | 📅 2025-07-01 - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* [AppIndicator Go](https://github.com/gopherlibs/appindicator) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2025-02-18 - Go bindings for libappindicator3 C library.
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) ⭐ 589 | 🐛 11 | 🌐 Go | 📅 2020-02-27 - OSX Desktop Notifications library for Go.
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) ⭐ 31 | 🐛 3 | 🌐 Go | 📅 2023-10-13 - OSX library to notify about any (pluggable) activity on your machine.
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2019-06-17 - OSX Sleep/Wake notifications in golang.
* [robotgo](https://github.com/go-vgo/robotgo) ⭐ 10,228 | 🐛 135 | 🌐 Go | 📅 2025-06-15 - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* [systray](https://github.com/getlantern/systray) ⭐ 3,501 | 🐛 109 | 🌐 Go | 📅 2024-07-03 - Cross platform Go library to place an icon and menu in the notification area.
* [trayhost](https://github.com/shurcooL/trayhost) ⭐ 256 | 🐛 7 | 🌐 Go | 📅 2023-11-26 - Cross-platform Go library to place an icon in the host operating system's taskbar.
* [zenity](https://github.com/ncruces/zenity) ⭐ 818 | 🐛 5 | 🌐 Go | 📅 2025-06-09 - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.

**[⬆ back to top](#contents)**

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

* [arduino-cli](https://github.com/arduino/arduino-cli) ⭐ 4,585 | 🐛 224 | 🌐 Go | 📅 2025-07-02 - Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects.
* [emgo](https://github.com/ziutek/emgo) ⭐ 1,084 | 🐛 13 | 🌐 C | 📅 2021-12-05 - Go-like language for programming embedded systems (e.g. STM32 MCU).
* [ghw](https://github.com/jaypipes/ghw) ⭐ 1,759 | 🐛 59 | 🌐 Go | 📅 2025-05-24 - Golang hardware discovery/inspection library.
* [go-osc](https://github.com/hypebeast/go-osc) ⭐ 214 | 🐛 19 | 🌐 Go | 📅 2023-01-15 - Open Sound Control (OSC) bindings for Go.
* [go-rpio](https://github.com/stianeikeland/go-rpio) ⭐ 2,245 | 🐛 42 | 🌐 Go | 📅 2023-09-30 - GPIO for Go, doesn't require cgo.
* [goroslib](https://github.com/aler9/goroslib) ⚠️ Archived - Robot Operating System (ROS) library for Go.
* [joystick](https://github.com/0xcafed00d/joystick) ⭐ 68 | 🐛 3 | 🌐 Go | 📅 2023-04-19 - a polled API to read the state of an attached joystick.
* [sysinfo](https://github.com/zcalusic/sysinfo) ⭐ 548 | 🐛 16 | 🌐 Go | 📅 2024-12-09 - A pure Go library providing Linux OS / kernel / hardware system information.

**[⬆ back to top](#contents)**

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) ⭐ 4,116 | 🐛 20 | 🌐 Go | 📅 2024-09-24 - Collection of image processing algorithms in pure Go.
* [bimg](https://github.com/h2non/bimg) ⭐ 2,876 | 🐛 175 | 🌐 Go | 📅 2025-01-23 - Small package for fast and efficient image processing using libvips.
* [cameron](https://github.com/aofei/cameron) ⭐ 127 | 🐛 0 | 🌐 Go | 📅 2025-05-17 - An avatar generator for Go.
* [canvas](https://github.com/tdewolff/canvas) ⭐ 1,592 | 🐛 19 | 🌐 Go | 📅 2025-05-08 - Vector graphics to PDF, SVG or rasterized image.
* [color-extractor](https://github.com/marekm4/color-extractor) ⭐ 98 | 🐛 0 | 🌐 Go | 📅 2023-07-19 - Dominant color extractor with no external dependencies.
* [darkroom](https://github.com/gojek/darkroom) ⭐ 234 | 🐛 12 | 🌐 Go | 📅 2025-06-25 - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
* [draft](https://github.com/lucasepe/draft) ⚠️ Archived - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
* [geopattern](https://github.com/pravj/geopattern) ⭐ 1,274 | 🐛 3 | 🌐 Go | 📅 2019-01-08 - Create beautiful generative image patterns from a string.
* [gg](https://github.com/fogleman/gg) ⭐ 4,618 | 🐛 94 | 🌐 Go | 📅 2023-12-14 - 2D rendering in pure Go.
* [gift](https://github.com/disintegration/gift) ⭐ 1,773 | 🐛 5 | 🌐 Go | 📅 2023-09-20 - Package of image processing filters.
* [gltf](https://github.com/qmuntal/gltf) ⭐ 258 | 🐛 3 | 🌐 Go | 📅 2024-11-12 - Efficient and robust glTF 2.0 reader, writer and validator.
* [go-cairo](https://github.com/ungerik/go-cairo) ⭐ 149 | 🐛 3 | 🌐 Go | 📅 2024-03-04 - Go binding for the cairo graphics library.
* [go-gd](https://github.com/bolknote/go-gd) ⭐ 59 | 🐛 1 | 🌐 Go | 📅 2018-05-07 - Go binding for GD library.
* [go-nude](https://github.com/koyachi/go-nude) ⭐ 419 | 🐛 3 | 🌐 Go | 📅 2023-10-11 - Nudity detection with Go.
* [go-qrcode](https://github.com/yeqown/go-qrcode) ⭐ 721 | 🐛 6 | 🌐 Go | 📅 2025-05-15 - Generate QR codes with personalized styles, allowing adjustments to color, block size, shape, and icons.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2015-08-21 - Port of webcolors library from Python to Go.
* [go-webp](https://github.com/kolesa-team/go-webp) ⭐ 266 | 🐛 7 | 🌐 Go | 📅 2025-03-25 - Library for encode and decode webp pictures, using libwebp.
* [gocv](https://github.com/hybridgroup/gocv) ⭐ 7,128 | 🐛 342 | 🌐 Go | 📅 2025-05-30 - Go package for computer vision using OpenCV 3.3+.
* [goimagehash](https://github.com/corona10/goimagehash) ⭐ 806 | 🐛 13 | 🌐 Go | 📅 2024-01-21 - Go Perceptual image hashing package.
* [goimghdr](https://github.com/corona10/goimghdr) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2019-06-14 - The imghdr module determines the type of image contained in a file for Go.
* [govatar](https://github.com/o1egl/govatar) ⭐ 606 | 🐛 1 | 🌐 Go | 📅 2022-10-04 - Library and CMD tool for generating funny avatars.
* [govips](https://github.com/davidbyttow/govips) ⭐ 1,453 | 🐛 34 | 🌐 Go | 📅 2025-06-14 - A lightning fast image processing and resizing library for Go.
* [gowitness](https://github.com/sensepost/gowitness) ⭐ 3,828 | 🐛 32 | 🌐 Go | 📅 2025-05-27 - Screenshoting webpages using go and headless chrome on command line.
* [gridder](https://github.com/shomali11/gridder) ⭐ 80 | 🐛 0 | 🌐 Go | 📅 2021-09-30 - A Grid based 2D Graphics library.
* [image2ascii](https://github.com/qeesung/image2ascii) ⭐ 923 | 🐛 9 | 🌐 Go | 📅 2022-08-29 - Convert image to ASCII.
* [imagick](https://github.com/gographics/imagick) ⭐ 1,826 | 🐛 3 | 🌐 Go | 📅 2024-12-16 - Go binding to ImageMagick's MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) ⭐ 5,872 | 🐛 131 | 🌐 Go | 📅 2025-01-14 - Fast and simple HTTP microservice for image resizing.
* [imaging](https://github.com/disintegration/imaging) ⭐ 5,510 | 🐛 33 | 🌐 Go | 📅 2023-09-21 - Simple Go image processing package.
* [imagor](https://github.com/cshum/imagor) ⭐ 3,662 | 🐛 39 | 🌐 Go | 📅 2025-06-30 - Fast, secure image processing server and Go library, using libvips.
* [img](https://github.com/hawx/img) ⭐ 156 | 🐛 4 | 🌐 Go | 📅 2015-05-01 - Selection of image manipulation tools.
* [ln](https://github.com/fogleman/ln) ⭐ 3,326 | 🐛 12 | 🌐 Go | 📅 2019-07-19 - 3D line art rendering in Go.
* [mergi](https://github.com/noelyahan/mergi) ⭐ 239 | 🐛 2 | 🌐 Go | 📅 2024-11-05 - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
* [mort](https://github.com/aldor007/mort) ⭐ 513 | 🐛 6 | 🌐 Go | 📅 2023-05-22 - Storage and image processing server written in Go.
* [mpo](https://github.com/donatj/mpo) ⭐ 19 | 🐛 2 | 🌐 Go | 📅 2025-06-05 - Decoder and conversion tool for MPO 3D Photos.
* [picfit](https://github.com/thoas/picfit) ⭐ 2,249 | 🐛 12 | 🌐 Go | 📅 2025-06-10 - An image resizing server written in Go.
* [pt](https://github.com/fogleman/pt) ⭐ 2,089 | 🐛 10 | 🌐 Go | 📅 2019-03-21 - Path tracing engine written in Go.
* [rez](https://github.com/bamiaux/rez) ⚠️ Archived - Image resizing in pure Go and SIMD.
* [scout](https://github.com/jonoton/scout) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-06-30 - Scout is a standalone open source software solution for DIY video security.
* [smartcrop](https://github.com/muesli/smartcrop) ⭐ 1,836 | 🐛 9 | 🌐 Go | 📅 2023-07-06 - Finds good crops for arbitrary images and crop sizes.
* [steganography](https://github.com/auyer/steganography) ⭐ 339 | 🐛 0 | 🌐 Go | 📅 2025-04-02 - Pure Go Library for LSB steganography.
* [stegify](https://github.com/DimitarPetrov/stegify) ⭐ 1,238 | 🐛 0 | 🌐 Go | 📅 2023-04-11 - Go tool for LSB steganography, capable of hiding any file within an image.
* [svgo](https://github.com/ajstarks/svgo) ⭐ 2,201 | 🐛 16 | 🌐 Go | 📅 2022-12-09 - Go Language Library for SVG generation.
* [transformimgs](https://github.com/Pixboost/transformimgs) ⭐ 265 | 🐛 7 | 🌐 Go | 📅 2025-03-28 - Transformimgs resizes and optimises images for Web using next-generation formats.
* [webp-server](https://github.com/mehdipourfar/webp-server) ⭐ 77 | 🐛 0 | 🌐 Go | 📅 2021-01-14 - Simple and minimal image server capable of storing, resizing, converting and caching images.

**[⬆ back to top](#contents)**

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) ⭐ 417 | 🐛 22 | 🌐 Go | 📅 2022-06-27 - Open-Source Platform for Quantified Self & IoT.
* [devices](https://github.com/goiot/devices) ⭐ 265 | 🐛 9 | 🌐 Go | 📅 2016-07-10 - Suite of libraries for IoT devices, experimental for x/exp/io.
* [ekuiper](https://github.com/lf-edge/ekuiper) ⭐ 1,602 | 🐛 56 | 🌐 Go | 📅 2025-07-02 - Lightweight data stream processing engine for IoT edge.
* [eywa](https://github.com/xcodersun/eywa) ⭐ 64 | 🐛 9 | 🌐 Go | 📅 2017-04-12 - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [flogo](https://github.com/tibcosoftware/flogo) ⭐ 2,471 | 🐛 127 | 🌐 CSS | 📅 2024-04-24 - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt](https://github.com/paypal/gatt) ⭐ 1,158 | 🐛 48 | 🌐 Go | 📅 2022-08-17 - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* [gobot](https://github.com/hybridgroup/gobot/) ⭐ 9,208 | 🐛 102 | 🌐 Go | 📅 2025-05-05 - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [huego](https://github.com/amimof/huego) ⭐ 254 | 🐛 10 | 🌐 Go | 📅 2023-06-30 - An extensive Philips Hue client library for Go.
* [iot](https://github.com/vaelen/iot/) ⭐ 65 | 🐛 0 | 🌐 Go | 📅 2019-11-08 - IoT is a simple framework for implementing a Google IoT Core device.
* [mainflux](https://github.com/Mainflux/mainflux) ⚠️ Archived - Industrial IoT Messaging and Device Management Server.
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [rulego](https://github.com/rulego/rulego) ⭐ 1,181 | 🐛 8 | 🌐 Go | 📅 2025-07-02 - RuleGo is a lightweight, high-performance, embedded, orchestrable component-based rule engine for IoT edge.
* [sensorbee](https://github.com/sensorbee/sensorbee) ⭐ 231 | 🐛 39 | 🌐 Go | 📅 2019-11-04 - Lightweight stream processing engine for IoT.
* [shifu](https://github.com/Edgenesis/shifu) ⭐ 1,350 | 🐛 30 | 🌐 Go | 📅 2025-06-23 - Kubernetes native IoT development framework.
* [smart-home](https://github.com/e154/smart-home) ⭐ 92 | 🐛 5 | 🌐 Go | 📅 2025-05-24 - Software package for IoT automation.

**[⬆ back to top](#contents)**

## Job Scheduler

*Libraries for scheduling jobs.*

* [cdule](https://github.com/deepaksinghvi/cdule) ⭐ 55 | 🐛 4 | 🌐 Go | 📅 2024-10-23 - Job scheduler library with database support
* [cheek](https://github.com/bart6114/cheek) ⭐ 190 | 🐛 8 | 🌐 Go | 📅 2025-06-18 - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling.
* [clockwerk](https://github.com/onatm/clockwerk) ⭐ 181 | 🐛 0 | 🌐 Go | 📅 2024-11-05 - Go package to schedule periodic jobs using a simple, fluent syntax.
* [cronticker](https://github.com/krayzpipes/cronticker) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2021-01-02 - A ticker implementation to support cron schedules.
* [go-cron](https://github.com/rk/go-cron) ⭐ 238 | 🐛 0 | 🌐 Go | 📅 2020-02-10 - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [go-quartz](https://github.com/reugn/go-quartz) ⭐ 1,890 | 🐛 3 | 🌐 Go | 📅 2025-05-24 - Simple, zero-dependency scheduling library for Go.
* [gocron](https://github.com/go-co-op/gocron) ⭐ 6,338 | 🐛 17 | 🌐 Go | 📅 2025-05-16 - Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron) ⭐ 3,491 | 🐛 46 | 🌐 Go | 📅 2023-11-27.
* [goflow](https://github.com/fieldryand/goflow) ⭐ 441 | 🐛 11 | 🌐 Go | 📅 2025-02-20 - A simple but powerful DAG scheduler and dashboard.
* [gron](https://github.com/roylee0704/gron) ⭐ 1,037 | 🐛 9 | 🌐 Go | 📅 2023-05-05 - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [gronx](https://github.com/adhocore/gronx) ⭐ 455 | 🐛 6 | 🌐 Go | 📅 2025-05-01 - Cron expression parser, task runner and daemon consuming crontab like task list.
* [JobRunner](https://github.com/bamzi/jobrunner) ⭐ 1,072 | 🐛 10 | 🌐 Go | 📅 2020-11-14 - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [leprechaun](https://github.com/kilgaloon/leprechaun) ⭐ 105 | 🐛 12 | 🌐 Go | 📅 2022-07-12 - Job scheduler that supports webhooks, crons and classic scheduling.
* [sched](https://github.com/romshark/sched) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2025-02-01 - A job scheduler with the ability to fast-forward time.
* [scheduler](https://github.com/carlescere/scheduler) ⭐ 470 | 🐛 8 | 🌐 Go | 📅 2022-06-23 - Cronjobs scheduling made easy.
* [tasks](https://github.com/madflojo/tasks) ⭐ 313 | 🐛 1 | 🌐 Go | 📅 2024-08-31 - An easy to use in-process scheduler for recurring tasks in Go.

**[⬆ back to top](#contents)**

## JSON

*Libraries for working with JSON.*

* [ajson](https://github.com/spyzhov/ajson) ⭐ 276 | 🐛 18 | 🌐 Go | 📅 2024-11-25 - Abstract JSON for golang with JSONPath support.
* [ask](https://github.com/simonnilsson/ask) ⭐ 53 | 🐛 1 | 🌐 Go | 📅 2023-08-28 - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
* [dynjson](https://github.com/cocoonspace/dynjson) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2023-04-12 - Client-customizable JSON formats for dynamic APIs.
* [ej](https://github.com/lucassscaravelli/ej) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-04-07 - Write and read JSON from different sources succinctly.
* [epoch](https://github.com/vtopc/epoch) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2024-02-25 - Contains primitives for marshaling/unmarshalling Unix timestamp/epoch to/from build-in time.Time type in JSON.
* [fastjson](https://github.com/valyala/fastjson) ⭐ 2,388 | 🐛 66 | 🌐 Go | 📅 2024-02-22 - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
* [gabs](https://github.com/Jeffail/gabs) ⭐ 3,512 | 🐛 37 | 🌐 Go | 📅 2024-06-06 - For parsing, creating and editing unknown or dynamic JSON in Go.
* [gjo](https://github.com/skanehira/gjo) ⭐ 130 | 🐛 1 | 🌐 Go | 📅 2021-04-18 - Small utility to create JSON objects.
* [GJSON](https://github.com/tidwall/gjson) ⭐ 15,016 | 🐛 89 | 🌐 Go | 📅 2024-10-10 - Get a JSON value with one line of code.
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2019-10-09 - Go-JsonError is meant to allow us to easily create json response errors that follow the JsonApi spec.
* [go-respond](https://github.com/nicklaw5/go-respond) ⭐ 54 | 🐛 1 | 🌐 Go | 📅 2021-09-24 - Go package for handling common HTTP JSON responses.
* [gojmapr](https://github.com/limiu82214/gojmapr) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2023-06-21 - Get simple struct from complex json by json path.
* [gojq](https://github.com/elgs/gojq) ⭐ 189 | 🐛 1 | 🌐 Go | 📅 2023-06-28 - JSON query in Golang.
* [gojson](https://github.com/ChimeraCoder/gojson) ⭐ 2,687 | 🐛 41 | 🌐 Go | 📅 2021-07-30 - Automatically generate Go (golang) struct definitions from example JSON.
* [htmljson](https://github.com/nikolaydubina/htmljson) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2024-08-22 - Rich rendering of JSON as HTML in Go.
* [JayDiff](https://github.com/yazgazan/jaydiff) ⭐ 109 | 🐛 2 | 🌐 Go | 📅 2024-03-05 - JSON diff utility written in Go.
* [jettison](https://github.com/wI2L/jettison) ⭐ 178 | 🐛 2 | 🌐 Go | 📅 2023-07-28 - Fast and flexible JSON encoder for Go.
* [jscan](https://github.com/romshark/jscan) ⭐ 95 | 🐛 8 | 🌐 Go | 📅 2024-02-02 - High performance zero-allocation JSON iterator.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
* [json2go](https://github.com/m-zajac/json2go) ⭐ 136 | 🐛 1 | 🌐 Go | 📅 2021-12-15 - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2016-11-17 - Go bindings based on the JSON API errors reference.
* [jsoncolor](https://github.com/neilotoole/jsoncolor) ⭐ 47 | 🐛 7 | 🌐 Go | 📅 2024-02-12 - Drop-in replacement for `encoding/json` that outputs colorized JSON.
* [jsondiff](https://github.com/wI2L/jsondiff) ⭐ 583 | 🐛 0 | 🌐 Go | 📅 2025-05-09 - JSON diff library for Go based on RFC6902 (JSON Patch).
* [jsonf](https://github.com/miolini/jsonf) ⭐ 65 | 🐛 0 | 🌐 Go | 📅 2020-12-13 - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo](https://github.com/ricardolonga/jsongo) ⭐ 108 | 🐛 1 | 🌐 Go | 📅 2021-10-04 - Fluent API to make it easier to create Json objects.
* [jsonhal](https://github.com/RichardKnop/jsonhal) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2020-03-24 - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [jsonhandlers](https://github.com/abusomani/jsonhandlers) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2023-03-09 - JSON library to expose simple handlers that lets you easily read and write json from various sources.
* [jsonic](https://github.com/sinhashubham95/jsonic) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-01-15 - Utilities to handle and query JSON without defining structs in a type safe manner.
* [jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) ⭐ 197 | 🐛 0 | 🌐 Go | 📅 2025-06-22 - A fast and convenient library for unstructured JSON data, replacing `encoding/json`.
* [jzon](https://github.com/zerosnake0/jzon) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-10-30 - JSON library with standard compatible API/behavior.
* [kazaam](https://github.com/Qntfy/kazaam) ⭐ 286 | 🐛 23 | 🌐 Go | 📅 2022-06-06 - API for arbitrary transformation of JSON documents.
* [mapslice-json](https://github.com/mickep76/mapslice-json) ⭐ 20 | 🐛 6 | 🌐 Go | 📅 2024-03-08 - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
* [marshmallow](https://github.com/PerimeterX/marshmallow) ⭐ 386 | 🐛 1 | 🌐 Go | 📅 2023-07-03 - Performant JSON unmarshalling for flexible use cases.
* [mp](https://github.com/sanbornm/mp) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2016-05-11 - Simple cli email parser. It currently takes stdin and outputs JSON.
* [OjG](https://github.com/ohler55/ojg) ⭐ 900 | 🐛 0 | 🌐 Go | 📅 2025-06-29 - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath.
* [omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2021-10-12 - Simple JSON parser with validation by condition via golang struct fields tags.
* [ujson](https://github.com/olvrng/ujson) ⭐ 82 | 🐛 1 | 🌐 Go | 📅 2025-01-04 - Fast and minimal JSON parser and transformer that works on unstructured JSON.
* [vjson](https://github.com/miladibra10/vjson) ⭐ 40 | 🐛 3 | 🌐 Go | 📅 2025-06-18 - Go package for validating JSON objects with declaring a JSON schema with fluent API.

**[⬆ back to top](#contents)**

## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) ⭐ 31 | 🐛 1 | 🌐 Go | 📅 2018-07-26 - distilled levelled logging (think of it as stdlib + log levels).
* [glg](https://github.com/kpango/glg) ⭐ 190 | 🐛 3 | 🌐 Go | 📅 2024-09-17 - glg is simple and fast leveled logging library for Go.
* [glo](https://github.com/lajosbencz/glo) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2019-01-23 - PHP Monolog inspired logging facility with identical severity levels.
* [glog](https://github.com/golang/glog) ⭐ 3,601 | 🐛 2 | 🌐 Go | 📅 2025-04-29 - Leveled execution logs for Go.
* [go-cronowriter](https://github.com/utahta/go-cronowriter) ⭐ 57 | 🐛 3 | 🌐 Go | 📅 2021-03-16 - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [go-log](https://github.com/pieterclaerhout/go-log) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2025-02-17 - A logging library with stack traces, object dumping and optional timestamps.
* [go-log](https://github.com/subchen/go-log) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2018-05-19 - Simple and configurable Logging in Go, with level, formatters and writers.
* [go-log](https://github.com/siddontang/go-log) ⭐ 35 | 🐛 2 | 🌐 Go | 📅 2019-02-21 - Log lib supports level and multi handlers.
* [go-log](https://github.com/ian-kent/go-log) ⭐ 42 | 🐛 3 | 🌐 Go | 📅 2018-03-31 - Log4j implementation in Go.
* [go-logger](https://github.com/apsdehal/go-logger) ⭐ 289 | 🐛 3 | 🌐 Go | 📅 2019-05-15 - Simple logger of Go Programs, with level handlers.
* [gone/log](https://github.com/One-com/gone/tree/master/log) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2021-05-24 - Fast, extendable, full-featured, std-lib source compatible log library.
* [httpretty](https://github.com/henvic/httpretty) ⭐ 407 | 🐛 2 | 🌐 Go | 📅 2024-09-23 - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
* [journald](https://github.com/ssgreg/journald) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2021-03-05 - Go implementation of systemd Journal's native API for logging.
* [kemba](https://github.com/clok/kemba) ⭐ 16 | 🐛 5 | 🌐 Go | 📅 2025-05-04 - A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug) ⭐ 11,300 | 🐛 78 | 🌐 JavaScript | 📅 2025-05-13, great for CLI tools and applications.
* [lazyjournal](https://github.com/Lifailon/lazyjournal) ⭐ 588 | 🐛 1 | 🌐 Go | 📅 2025-05-29 - A TUI for reading and filtering logs from journalctl, file system, Docker and Podman containers, as well Kubernetes pods.
* [log](https://github.com/aerogo/log) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2019-10-26 - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
* [log](https://github.com/apex/log) ⭐ 1,369 | 🐛 46 | 🌐 Go | 📅 2023-11-03 - Structured logging package for Go.
* [log](https://github.com/go-playground/log) ⭐ 295 | 🐛 1 | 🌐 Go | 📅 2023-08-17 - Simple, configurable and scalable Structured Logging for Go.
* [log](https://github.com/teris-io/log) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2017-12-04 - Structured log interface for Go cleanly separates logging facade from its implementation.
* [log](https://github.com/heartwilltell/log) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2022-12-06 - Simple leveled logging wrapper around standard log package.
* [log](https://github.com/no-src/log) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2024-11-18 - A simple logging framework out of the box.
* [log15](https://github.com/inconshreveable/log15) ⭐ 1,098 | 🐛 45 | 🌐 Go | 📅 2023-02-21 - Simple, powerful logging for Go.
* [logdump](https://github.com/ewwwwwqm/logdump) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2018-04-02 - Package for multi-level logging.
* [logex](https://github.com/chzyer/logex) ⭐ 42 | 🐛 2 | 🌐 Go | 📅 2024-04-02 - Golang log lib, supports tracking and level, wrap by standard log lib.
* [logger](https://github.com/azer/logger) ⭐ 156 | 🐛 0 | 🌐 Go | 📅 2021-11-22 - Minimalistic logging library for Go.
* [logo](https://github.com/mbndr/logo) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2020-12-27 - Golang logger to different configurable writers.
* [logrus](https://github.com/Sirupsen/logrus) ⭐ 25,345 | 🐛 80 | 🌐 Go | 📅 2025-06-20 - Structured logger for Go.
* [logrusiowriter](https://github.com/cabify/logrusiowriter) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2024-10-09 - `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) ⭐ 25,345 | 🐛 80 | 🌐 Go | 📅 2025-06-20 logger.
* [logrusly](https://github.com/sebest/logrusly) ⭐ 28 | 🐛 3 | 🌐 Go | 📅 2021-07-27 - [logrus](https://github.com/sirupsen/logrus) ⭐ 25,345 | 🐛 80 | 🌐 Go | 📅 2025-06-20 plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logur](https://github.com/logur/logur) ⚠️ Archived - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus) ⭐ 25,345 | 🐛 80 | 🌐 Go | 📅 2025-06-20, [go-kit log](https://github.com/go-kit/kit/tree/master/log) ⭐ 27,136 | 🐛 57 | 🌐 Go | 📅 2024-07-19, [zap](https://github.com/uber-go/zap) ⭐ 23,299 | 🐛 164 | 🌐 Go | 📅 2025-06-02, [zerolog](https://github.com/rs/zerolog) ⭐ 11,561 | 🐛 139 | 🌐 Go | 📅 2025-04-18, etc).
* [logutils](https://github.com/hashicorp/logutils) ⭐ 367 | 🐛 4 | 🌐 Go | 📅 2024-12-02 - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi](https://github.com/mgutz/logxi) ⭐ 358 | 🐛 21 | 🌐 Go | 📅 2020-04-14 - 12-factor app logger that is fast and makes you happy.
* [lumberjack](https://github.com/natefinch/lumberjack) ⭐ 5,146 | 🐛 100 | 🌐 Go | 📅 2024-08-05 - Simple rolling logger, implements io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) ⭐ 33 | 🐛 2 | 🌐 Go | 📅 2018-08-05 - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [noodlog](https://github.com/gyozatech/noodlog) ⭐ 43 | 🐛 8 | 🌐 Go | 📅 2023-04-19 - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings.
* [onelog](https://github.com/francoispqt/onelog) ⭐ 413 | 🐛 2 | 🌐 Go | 📅 2019-03-06 - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) ⭐ 123 | 🐛 9 | 🌐 Go | 📅 2021-01-07 - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [phuslu/log](https://github.com/phuslu/log) ⭐ 778 | 🐛 6 | 🌐 Go | 📅 2025-05-17 - High performance structured logging.
* [pp](https://github.com/k0kubun/pp) ⭐ 1,961 | 🐛 7 | 🌐 Go | 📅 2025-07-01 - Colored pretty printer for Go language.
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) ⭐ 298 | 🐛 10 | 🌐 Go | 📅 2023-10-16 - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
* [seelog](https://github.com/cihub/seelog) ⭐ 1,637 | 🐛 40 | 🌐 Go | 📅 2019-03-04 - Logging functionality with flexible dispatching, filtering, and formatting.
* [sentry-go](https://github.com/getsentry/sentry-go) ⭐ 974 | 🐛 53 | 🌐 Go | 📅 2025-07-02 - Sentry SDK for Go. Helps monitor and track errors with real-time alerts and performance monitoring.
* [slf4g](https://github.com/echocat/slf4g) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-05-06 - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks.
* [slog](https://github.com/gookit/slog) ⭐ 479 | 🐛 3 | 🌐 Go | 📅 2025-06-30 - Lightweight, configurable, extensible logger for Go.
* [slog-formatter](https://github.com/samber/slog-formatter) ⭐ 174 | 🐛 0 | 🌐 Go | 📅 2025-06-30 - Common formatters for slog and helpers to build your own.
* [slog-multi](https://github.com/samber/slog-multi) ⭐ 495 | 🐛 1 | 🌐 Go | 📅 2025-06-24 - Chain of slog.Handler (pipeline, fanout...).
* [slogor](https://gitlab.com/greyxor/slogor) - A colorful slog handler.
* [spew](https://github.com/davecgh/go-spew) ⭐ 6,265 | 🐛 65 | 🌐 Go | 📅 2024-04-06 - Implements a deep pretty printer for Go data structures to aid in debugging.
* [sqldb-logger](https://github.com/simukti/sqldb-logger) ⭐ 377 | 🐛 11 | 🌐 Go | 📅 2023-12-29 - A logger for Go SQL database driver without modify existing \*sql.DB stdlib usage.
* [stdlog](https://github.com/alexcesaro/log) ⭐ 48 | 🐛 1 | 🌐 Go | 📅 2015-09-15 - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [structy/log](https://github.com/structy/log) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2022-01-27 - A simple to use log system, minimalist but with features for debugging and differentiation of messages.
* [tail](https://github.com/hpcloud/tail) ⭐ 2,765 | 🐛 75 | 🌐 Go | 📅 2022-10-25 - Go package striving to emulate the features of the BSD tail program.
* [tint](https://github.com/lmittmann/tint) ⭐ 1,036 | 🐛 0 | 🌐 Go | 📅 2025-06-07 - A slog.Handler that writes tinted logs.
* [xlog](https://github.com/xfxdev/xlog) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2019-01-15 - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [xlog](https://github.com/rs/xlog) ⭐ 139 | 🐛 3 | 🌐 Go | 📅 2024-07-04 - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [xylog](https://github.com/xybor-x/xylog) ⭐ 17 | 🐛 4 | 🌐 Go | 📅 2023-04-24 - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax.
* [yell](https://github.com/jfcg/yell) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2022-03-01 - Yet another minimalistic logging library.
* [zap](https://github.com/uber-go/zap) ⭐ 23,299 | 🐛 164 | 🌐 Go | 📅 2025-06-02 - Fast, structured, leveled logging in Go.
* [zax](https://github.com/yuseferi/zax) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2025-05-13 - Integrate Context with Zap logger, which leads to more flexibility in Go logging.
* [zerolog](https://github.com/rs/zerolog) ⭐ 11,561 | 🐛 139 | 🌐 Go | 📅 2025-04-18 - Zero-allocation JSON logger.
* [zkits-logger](https://github.com/edoger/zkits-logger) ⭐ 28 | 🐛 1 | 🌐 Go | 📅 2023-05-19 - A powerful zero-dependency JSON logger.
* [zl](https://github.com/nkmr-jp/zl) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2025-02-19 - High Developer Experience, zap based logger. It offers rich functionality but is easy to configure.

**[⬆ back to top](#contents)**

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) ⭐ 808 | 🐛 8 | 🌐 Go | 📅 2023-11-17 - Naive Bayesian Classification for Golang.
* [catboost-cgo](https://github.com/mirecl/catboost-cgo) ⭐ 16 | 🐛 4 | 🌐 C | 📅 2025-06-27 - Fast, scalable, high performance Gradient Boosting on Decision Trees library. Golang using Cgo for blazing fast inference CatBoost Model.
* [CloudForest](https://github.com/ryanbressler/CloudForest) ⭐ 743 | 🐛 34 | 🌐 Go | 📅 2022-02-05 - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* [ddt](https://github.com/sgrodriguez/ddt) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2021-02-22 - Dynamic decision tree, create trees defining customizable rules.
* [eaopt](https://github.com/MaxHalford/eaopt) ⭐ 900 | 🐛 9 | 🌐 Go | 📅 2025-01-27 - An evolutionary optimization library.
* [evoli](https://github.com/khezen/evoli) ⭐ 33 | 🐛 21 | 🌐 Go | 📅 2021-10-27 - Genetic Algorithm and Particle Swarm Optimization library.
* [fonet](https://github.com/Fontinalis/fonet) ⭐ 86 | 🐛 2 | 🌐 Go | 📅 2021-06-01 - A Deep Neural Network library written in Go.
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2022-11-29 - Go implementation of the k-modes and k-prototypes clustering algorithms.
* [go-deep](https://github.com/patrikeh/go-deep) ⭐ 550 | 🐛 2 | 🌐 Go | 📅 2024-07-11 - A feature-rich neural network library in Go.
* [go-fann](https://github.com/white-pony/go-fann) ⭐ 115 | 🐛 2 | 🌐 Go | 📅 2015-02-03 - Go bindings for Fast Artificial Neural Networks(FANN) library.
* [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) ⚠️ Archived - Fast and convenient feature processing for low latency machine learning in Go.
* [go-galib](https://github.com/thoj/go-galib) ⭐ 199 | 🐛 0 | 🌐 Go | 📅 2015-12-28 - Genetic Algorithms library written in Go / golang.
* [go-pr](https://github.com/daviddengcn/go-pr) ⭐ 67 | 🐛 0 | 🌐 Go | 📅 2013-06-08 - Pattern recognition package in Go lang.
* [gobrain](https://github.com/goml/gobrain) ⭐ 565 | 🐛 2 | 🌐 Go | 📅 2020-12-12 - Neural Networks written in go.
* [godist](https://github.com/e-dard/godist) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2015-05-11 - Various probability distributions, and associated methods.
* [goga](https://github.com/tomcraven/goga) ⭐ 223 | 🐛 2 | 🌐 Go | 📅 2022-04-13 - Genetic algorithm library for Go.
* [GoLearn](https://github.com/sjwhitworth/golearn) ⭐ 9,408 | 🐛 89 | 🌐 Go | 📅 2024-01-15 - General Machine Learning library for Go.
* [golinear](https://github.com/danieldk/golinear) ⚠️ Archived - liblinear bindings for Go.
* [GoMind](https://github.com/surenderthakran/gomind) ⭐ 98 | 🐛 7 | 🌐 Go | 📅 2022-05-08 - A simplistic Neural Network Library in Go.
* [goml](https://github.com/cdipaolo/goml) ⭐ 1,593 | 🐛 4 | 🌐 Go | 📅 2022-07-15 - On-line Machine Learning in Go.
* [GoMLX](https://github.com/gomlx/gomlx) ⭐ 819 | 🐛 1 | 🌐 Go | 📅 2025-07-02 - An accelerated Machine Learning framework for Go.
* [gonet](https://github.com/dathoangnd/gonet) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2020-04-05 - Neural Network for Go.
* [Goptuna](https://github.com/c-bata/goptuna) ⭐ 268 | 🐛 19 | 🌐 Go | 📅 2024-08-30 - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
* [goRecommend](https://github.com/timkaye11/goRecommend) ⭐ 206 | 🐛 0 | 🌐 Go | 📅 2014-07-29 - Recommendation Algorithms library written in Go.
* [gorgonia](https://github.com/gorgonia/gorgonia) ⭐ 5,795 | 🐛 111 | 🌐 Go | 📅 2024-08-12 - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* [gorse](https://github.com/zhenghaoz/gorse) ⭐ 3 | 🐛 0 | 📅 2025-04-18 - An offline recommender system backend based on collaborative filtering written in Go.
* [goscore](https://github.com/asafschers/goscore) ⭐ 102 | 🐛 3 | 🌐 Go | 📅 2019-08-23 - Go Scoring API for PMML.
* [gosseract](https://github.com/otiai10/gosseract) ⭐ 2,897 | 🐛 33 | 🌐 Go | 📅 2025-03-24 - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* [hugot](https://github.com/knights-analytics/hugot) ⭐ 424 | 🐛 6 | 🌐 Go | 📅 2025-06-26 - Huggingface transformer pipelines for golang with onnxruntime.
* [libsvm](https://github.com/datastream/libsvm) ⭐ 73 | 🐛 1 | 🌐 Go | 📅 2016-05-09 - libsvm golang version derived work based on LIBSVM 3.14.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) ⭐ 2,888 | 🐛 60 | 🌐 Python | 📅 2024-08-03 - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support.
* [neural-go](https://github.com/schuyler/neural-go) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2020-08-31 - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [ocrserver](https://github.com/otiai10/ocrserver) ⭐ 740 | 🐛 4 | 🌐 Go | 📅 2021-08-05 - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
* [onnx-go](https://github.com/owulveryck/onnx-go) ⭐ 800 | 🐛 44 | 🌐 Go | 📅 2024-09-02 - Go Interface to Open Neural Network Exchange (ONNX).
* [probab](https://github.com/ThePaw/probab) ⭐ 20 | 🐛 3 | 🌐 Go | 📅 2015-09-14 - Probability distribution functions. Bayesian inference. Written in pure Go.
* [randomforest](https://github.com/malaschitz/randomForest) ⭐ 53 | 🐛 1 | 🌐 Go | 📅 2024-02-28 - Easy to use Random Forest library for Go.
* [regommend](https://github.com/muesli/regommend) ⭐ 313 | 🐛 0 | 🌐 Go | 📅 2019-08-07 - Recommendation & collaborative filtering engine.
* [shield](https://github.com/eaigner/shield) ⭐ 158 | 🐛 5 | 🌐 Go | 📅 2020-03-04 - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* [tfgo](https://github.com/galeone/tfgo) ⭐ 2,474 | 🐛 20 | 🌐 Go | 📅 2024-03-13 - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
* [Varis](https://github.com/Xamber/Varis) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2018-08-02 - Golang Neural Network.

**[⬆ back to top](#contents)**

## Messaging

*Libraries that implement messaging systems.*

* [ami](https://github.com/kak-tus/ami) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2020-04-02 - Go client to reliable queues based on Redis Cluster Streams.
* [amqp](https://github.com/rabbitmq/amqp091-go) ⭐ 1,796 | 🐛 18 | 🌐 Go | 📅 2025-07-02 - Go RabbitMQ Client Library.
* [APNs2](https://github.com/sideshow/apns2) ⭐ 3,095 | 🐛 33 | 🌐 Go | 📅 2024-10-25 - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.
* [Asynq](https://github.com/hibiken/asynq) ⭐ 11,500 | 🐛 249 | 🌐 Go | 📅 2025-05-15 - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
* [Beaver](https://github.com/Clivern/Beaver) ⭐ 1,569 | 🐛 10 | 🌐 Go | 📅 2025-06-20 - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
* [Bus](https://github.com/mustafaturan/bus) ⭐ 349 | 🐛 0 | 🌐 Go | 📅 2023-05-14 - Minimalist message bus implementation for internal communication.
* [Centrifugo](https://github.com/centrifugal/centrifugo) ⭐ 9,071 | 🐛 22 | 🌐 Go | 📅 2025-07-01 - Real-time messaging (Websockets or SockJS) server in Go.
* [Chanify](https://github.com/chanify/chanify) ⭐ 1,306 | 🐛 14 | 🌐 Go | 📅 2023-06-01 - A push notification server send message to your iOS devices.
* [Commander](https://github.com/jeroenrinzema/commander) ⭐ 67 | 🐛 2 | 🌐 Go | 📅 2021-04-28 - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
* [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) ⭐ 4,920 | 🐛 285 | 🌐 HTML | 📅 2025-07-02 - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
* [dbus](https://github.com/godbus/dbus) ⭐ 1,070 | 🐛 58 | 🌐 Go | 📅 2024-11-09 - Native Go bindings for D-Bus.
* [drone-line](https://github.com/appleboy/drone-line) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2023-02-25 - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
* [emitter](https://github.com/olebedev/emitter) ⭐ 520 | 🐛 4 | 🌐 Go | 📅 2023-04-11 - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* [event](https://github.com/agoalofalife/event) ⭐ 59 | 🐛 0 | 🌐 Go | 📅 2018-02-19 - Implementation of the pattern observer.
* [EventBus](https://github.com/asaskevich/EventBus) ⭐ 1,884 | 🐛 27 | 🌐 Go | 📅 2024-06-19 - The lightweight event bus with async compatibility.
* [gaurun-client](https://github.com/osamingo/gaurun-client) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-08-03 - Gaurun Client written in Go.
* [Glue](https://github.com/desertbit/glue) ⭐ 419 | 🐛 4 | 🌐 Go | 📅 2020-05-20 - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* [go-eventbus](https://github.com/stanipetrosyan/go-eventbus) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2025-05-05 - Simple Event Bus package for Go.
* [Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) ⭐ 245 | 🐛 2 | 🌐 Go | 📅 2025-05-08 - A library for handling mediator patterns and simplified CQRS patterns within an event-driven architecture, inspired by csharp MediatR library.
* [go-mq](https://github.com/cheshir/go-mq) ⭐ 90 | 🐛 1 | 🌐 Go | 📅 2023-10-09 - RabbitMQ client with declarative configuration.
* [go-notify](https://github.com/TheCreeper/go-notify) ⭐ 71 | 🐛 2 | 🌐 Go | 📅 2020-12-11 - Native implementation of the freedesktop notification spec.
* [go-nsq](https://github.com/nsqio/go-nsq) ⭐ 2,631 | 🐛 33 | 🌐 Go | 📅 2025-03-13 - the official Go package for NSQ.
* [go-res](https://github.com/jirenius/go-res) ⭐ 65 | 🐛 8 | 🌐 Go | 📅 2024-10-25 - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
* [go-socket.io](https://github.com/googollee/go-socket.io) ⚠️ Archived - socket.io library for golang, a realtime application framework.
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2024-09-19 - Client library to Viessmann Vitotrol web service.
* [Gollum](https://github.com/trivago/gollum) ⭐ 941 | 🐛 20 | 🌐 Go | 📅 2023-02-15 - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* [golongpoll](https://github.com/jcuga/golongpoll) ⭐ 662 | 🐛 0 | 🌐 Go | 📅 2023-08-20 - HTTP longpoll server library that makes web pub-sub simple.
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) ⭐ 2,078 | 🐛 5 | 🌐 Go | 📅 2017-06-07 - gopush-cluster is a go push server cluster.
* [gorush](https://github.com/appleboy/gorush) ⭐ 8,417 | 🐛 59 | 🌐 Go | 📅 2025-05-12 - Push notification server using [APNs2](https://github.com/sideshow/apns2) ⭐ 3,095 | 🐛 33 | 🌐 Go | 📅 2024-10-25 and google [GCM](https://github.com/google/go-gcm) ⚠️ Archived.
* [gosd](https://github.com/alexsniffin/gosd) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2022-08-17 - A library for scheduling when to dispatch a message to a channel.
* [guble](https://github.com/smancke/guble) ⭐ 160 | 🐛 5 | 🌐 Go | 📅 2017-10-31 - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* [hare](https://github.com/leozz37/hare) ⭐ 53 | 🐛 1 | 🌐 Go | 📅 2022-08-31 - A user friendly library for sending messages and listening to TCP sockets.
* [hub](https://github.com/leandro-lugaresi/hub) ⭐ 146 | 🐛 0 | 🌐 Go | 📅 2020-10-26 - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
* [hypermatch](https://github.com/SchwarzIT/hypermatch) ⭐ 28 | 🐛 1 | 🌐 Go | 📅 2025-02-10 - A very fast and efficient Go library for matching events to a large set of rules
* [jazz](https://github.com/socifi/jazz) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2019-03-21 - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
* [machinery](https://github.com/RichardKnop/machinery) ⭐ 7,772 | 🐛 244 | 🌐 Go | 📅 2025-06-30 - Asynchronous task queue/job queue based on distributed message passing.
* [mangos](https://github.com/nanomsg/mangos) ⭐ 712 | 🐛 30 | 🌐 Go | 📅 2025-05-16 - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
* [melody](https://github.com/olahol/melody) ⭐ 3,935 | 🐛 13 | 🌐 Go | 📅 2025-06-08 - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* [Mercure](https://github.com/dunglas/mercure) ⭐ 4,972 | 🐛 25 | 🌐 Go | 📅 2025-06-27 - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
* [messagebus](https://github.com/vardius/message-bus) ⭐ 277 | 🐛 2 | 🌐 JavaScript | 📅 2021-01-14 - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* [NATS Go Client](https://github.com/nats-io/nats.go) ⭐ 5,995 | 🐛 186 | 🌐 Go | 📅 2025-06-30 - Go client for the NATS
  messaging system.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2018-02-15 - A tiny wrapper around NSQ topic and channel.
* [oplog](https://github.com/dailymotion/oplog) ⭐ 110 | 🐛 1 | 🌐 Go | 📅 2024-09-27 - Generic oplog/replication system for REST APIs.
* [pubsub](https://github.com/tuxychandru/pubsub) ⭐ 438 | 🐛 1 | 🌐 Go | 📅 2024-05-22 - Simple pubsub package for go.
* [Quamina](https://github.com/timbray/quamina) ⭐ 429 | 🐛 16 | 🌐 Go | 📅 2025-07-01 - Fast pattern-matching for filtering messages and events.
* [rabbitroutine](https://github.com/furdarius/rabbitroutine) ⭐ 112 | 🐛 2 | 🌐 Go | 📅 2024-03-03 - Lightweight library that handles RabbitMQ auto-reconnect and publishing retries. The library takes into account the need to re-declare entities in RabbitMQ after reconnection.
* [rabbus](https://github.com/rafaeljesus/rabbus) ⭐ 98 | 🐛 6 | 🌐 Go | 📅 2019-07-23 - A tiny wrapper over amqp exchanges and queues.
* [rabtap](https://github.com/jandelgado/rabtap) ⭐ 270 | 🐛 4 | 🌐 Go | 📅 2025-06-06 - RabbitMQ swiss army knife cli app.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) ⭐ 69 | 🐛 1 | 🌐 Go | 📅 2017-12-07 - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [Ratus](https://github.com/hyperonym/ratus) ⭐ 120 | 🐛 10 | 🌐 Go | 📅 2025-06-20 - Ratus is a RESTful asynchronous task queue server.
* [redisqueue](https://github.com/robinjoseph08/redisqueue) ⭐ 134 | 🐛 7 | 🌐 Go | 📅 2024-03-08 - redisqueue provides a producer and consumer of a queue that uses Redis streams.
* [rmqconn](https://github.com/sbabiv/rmqconn) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2020-01-27 - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
* [sarama](https://github.com/Shopify/sarama) ⭐ 12,066 | 🐛 64 | 🌐 Go | 📅 2025-07-02 - Go library for Apache Kafka.
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) ⭐ 1,555 | 🐛 73 | 🌐 Go | 📅 2020-04-09 - Redis backed unified push service for server-side notifications to mobile devices.
* [Watermill](https://github.com/ThreeDotsLabs/watermill) ⭐ 8,599 | 🐛 122 | 🌐 Go | 📅 2025-05-26 - Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog.
* [zmq4](https://github.com/pebbe/zmq4) ⭐ 1,211 | 🐛 59 | 🌐 Go | 📅 2025-05-11 - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) ⭐ 133 | 🐛 1 | 🌐 Go | 📅 2025-05-11 and [version 2](https://github.com/pebbe/zmq2) ⭐ 19 | 🐛 1 | 🌐 Go | 📅 2025-05-11.

**[⬆ back to top](#contents)**

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) ⭐ 4,612 | 🐛 26 | 🌐 Go | 📅 2025-05-21 - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/xuri/excelize) ⭐ 19,320 | 🐛 123 | 🌐 Go | 📅 2025-06-25 - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [exl](https://github.com/go-the-way/exl) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2024-06-04 - Excel binding to struct written in Go.(Only supports Go1.18+)
* [go-excel](https://github.com/szyhf/go-excel) ⭐ 195 | 🐛 1 | 🌐 Go | 📅 2025-05-08 - A simple and light reader to read a relate-db-like excel as a table.
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) ⚠️ Archived - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [xlsx](https://github.com/tealeg/xlsx) ⭐ 5,981 | 🐛 9 | 🌐 Go | 📅 2025-04-18 - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
* [xlsx](https://github.com/plandem/xlsx) ⭐ 176 | 🐛 13 | 🌐 Go | 📅 2020-11-04 - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.

### Microsoft Word

*Libraries for working with Microsoft Word.*

* [godocx](https://github.com/gomutex/godocx) ⭐ 186 | 🐛 10 | 🌐 Go | 📅 2025-05-25 - Library for reading and writing Microsoft Word (Docx) files.

**[⬆ back to top](#contents)**

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* [alice](https://github.com/magic003/alice) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2017-04-26 - Additive dependency injection container for Golang.
* [autowire](https://github.com/tiendc/autowire) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-09-11 - Dependency injection using Generics and reflection.
* [boot-go](http://github.com/boot-go/boot) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2024-01-29 - Component-based development with dependency injection using reflections for Go developers.
* [componego](https://github.com/componego/componego) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2024-09-29 - A dependency injection framework based on components, allowing dynamic dependency replacement without duplicating code in tests.
* [cosban/di](https://gitlab.com/cosban/di) - A code generation based dependency injection wiring tool.
* [di](https://github.com/goava/di) ⭐ 238 | 🐛 3 | 🌐 Go | 📅 2023-12-16 - A dependency injection container for go programming language.
* [dig](https://github.com/uber-go/dig) ⭐ 4,217 | 🐛 29 | 🌐 Go | 📅 2025-05-13 - A reflection based dependency injection toolkit for Go.
* [dingo](https://github.com/i-love-flamingo/dingo) ⭐ 185 | 🐛 15 | 🌐 Go | 📅 2025-05-27 - A dependency injection toolkit for Go, based on Guice.
* [do](https://github.com/samber/do) ⭐ 2,174 | 🐛 45 | 🌐 Go | 📅 2025-05-05 - A dependency injection framework based on Generics.
* [fx](https://github.com/uber-go/fx) ⭐ 6,624 | 🐛 67 | 🌐 Go | 📅 2025-05-13 - A dependency injection based application framework for Go (built on top of dig).
* [gocontainer](https://github.com/vardius/gocontainer) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2020-03-23 - Simple Dependency Injection Container.
* [goioc/di](https://github.com/goioc/di) ⭐ 365 | 🐛 2 | 🌐 Go | 📅 2024-11-25 - Spring-inspired Dependency Injection Container.
* [GoLobby/Container](https://github.com/golobby/container) ⭐ 592 | 🐛 5 | 🌐 Go | 📅 2024-07-11 - GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language.
* [gontainer](https://github.com/NVIDIA/gontainer) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2025-06-11 - A dependency injection service container for Go projects.
* [gontainer/gontainer](https://github.com/gontainer/gontainer) ⭐ 16 | 🐛 5 | 🌐 Go | 📅 2024-08-05 - A YAML-based Dependency Injection container for GO. It supports dependencies' scopes, and auto-detection of circular dependencies. Gontainer is concurrent-safe.
* [google/wire](https://github.com/google/wire) ⭐ 13,902 | 🐛 110 | 🌐 Go | 📅 2024-07-24 - Automated Initialization in Go.
* [HnH/di](https://github.com/HnH/di) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2024-11-03 - DI container library that is focused on clean API and flexibility.
* [kinit](https://github.com/go-kata/kinit) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2021-06-12 - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
* [kod](https://github.com/go-kod/kod) ⭐ 186 | 🐛 1 | 🌐 Go | 📅 2025-06-30 - A generics based dependency injection framework for Go.
* [linker](https://github.com/logrange/linker) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2025-01-09 - A reflection based dependency injection and inversion of control library with components lifecycle support.
* [nject](https://github.com/muir/nject) ⭐ 30 | 🐛 3 | 🌐 Go | 📅 2025-07-01 - A type safe, reflective framework for libraries, tests, http endpoints, and service startup.
* [ore](https://github.com/firasdarwish/ore) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2025-01-10 - Lightweight, generic & simple dependency injection (DI) container.
* [wire](https://github.com/Fs02/wire) ⭐ 39 | 🐛 1 | 🌐 Go | 📅 2021-08-22 - Strict Runtime Dependency Injection for Golang.

**[⬆ back to top](#contents)**

### Project Layout

***Unofficial** set of patterns for structuring projects.*

* [ardanlabs/service](https://github.com/ardanlabs/service) ⭐ 3,813 | 🐛 0 | 🌐 Go | 📅 2025-06-26 - A [starter kit](https://github.com/ardanlabs/service/wiki) ⭐ 3,813 | 🐛 0 | 🌐 Go | 📅 2025-06-26 for building production grade scalable web service applications.
* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) ⭐ 718 | 🐛 3 | 🌐 Go | 📅 2024-02-01 - A Go application boilerplate template for quick starting projects following production best practices.
* [go-blueprint](https://github.com/Melkeydev/go-blueprint) ⭐ 7,730 | 🐛 43 | 🌐 Go | 📅 2025-06-30 - Allows users to spin up a quick Go project using a popular framework.
* [go-module](https://github.com/octomation/go-module) ⭐ 33 | 🐛 29 | 🌐 Shell | 📅 2025-06-24 - Template for a typical module written on Go.
* [go-sample](https://github.com/zitryss/go-sample) ⭐ 136 | 🐛 0 | 🌐 Go | 📅 2019-01-24 - A sample layout for Go application projects with the real code.
* [go-starter](https://github.com/allaboutapps/go-starter) ⭐ 558 | 🐛 6 | 🌐 Go | 📅 2025-04-09 - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers.
* [go-todo-backend](https://github.com/Fs02/go-todo-backend) ⭐ 332 | 🐛 0 | 🌐 Go | 📅 2023-05-31 - Go Todo Backend example using modular project layout for product microservice.
* [goapp](https://github.com/naughtygopher/goapp) ⭐ 980 | 🐛 0 | 🌐 Go | 📅 2025-01-27 - An opinionated guideline to structure & develop a Go web application/service.
* [gobase](https://github.com/wajox/gobase) ⭐ 65 | 🐛 0 | 🌐 Go | 📅 2023-06-21 - A simple skeleton for golang application with basic setup for real golang application.
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) ⭐ 52,934 | 🐛 94 | 🌐 Makefile | 📅 2025-01-14 - Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) ⭐ 52,934 | 🐛 94 | 🌐 Makefile | 📅 2025-01-14 for more information. Nonetheless, some may find the layout useful.
* [golang-templates/seed](https://github.com/golang-templates/seed) ⭐ 530 | 🐛 0 | 🌐 Makefile | 📅 2025-06-30 - Go application GitHub repository template.
* [goxygen](https://github.com/shpota/goxygen) ⭐ 3,587 | 🐛 15 | 🌐 Go | 📅 2024-12-18 - Generate a modern Web project with Go and Angular, React, or Vue in seconds.
* [insidieux/inizio](https://github.com/insidieux/inizio) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2023-03-17 - Golang project layout generator with plugins.
* [kickstart.go](https://github.com/raeperd/kickstart.go) ⭐ 85 | 🐛 1 | 🌐 Go | 📅 2025-05-05 - Minimalistic single-file Go HTTP server template without third-party dependencies.
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) ⭐ 1,920 | 🐛 23 | 🌐 Go | 📅 2024-11-01 - Go application boilerplate and example applying modern practices.
* [nunu](https://github.com/go-nunu/nunu) ⭐ 2,286 | 🐛 0 | 🌐 Go | 📅 2025-06-14 - Nunu is a scaffolding tool for building Go applications.
* [pagoda](https://github.com/mikestefanello/pagoda) ⭐ 2,559 | 🐛 2 | 🌐 Go | 📅 2025-06-24 - Rapid, easy full-stack web development starter kit built in Go.
* [scaffold](https://github.com/catchplay/scaffold) ⭐ 147 | 🐛 2 | 🌐 Go | 📅 2019-01-10 - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
* [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) ⭐ 26 | 🐛 1 | 🌐 Go | 📅 2025-01-28 - Set of practices and discussions on how to structure Go project layout.

**[⬆ back to top](#contents)**

### Strings

*Libraries for working with strings.*

* [bexp](https://github.com/happy-sdk/happy/tree/main/pkg/strings/bexp) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
* [caps](https://github.com/chanced/caps) ⭐ 58 | 🐛 0 | 🌐 Go | 📅 2023-12-30 - A case conversion library.
* [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
* [gobeam/Stringy](https://github.com/gobeam/Stringy) ⭐ 250 | 🐛 2 | 🌐 Go | 📅 2025-05-19 - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
* [strcase](https://github.com/charlievieth/strcase) ⭐ 8 | 🐛 2 | 🌐 Go | 📅 2025-05-15 - Case-insensitive implementation of the standard library's strings/bytes packages.
* [strutil](https://github.com/ozgio/strutil) ⭐ 207 | 🐛 2 | 🌐 Go | 📅 2025-05-21 - String utilities.
* [sttr](https://github.com/abhimanyu003/sttr) ⭐ 1,129 | 🐛 12 | 🌐 Go | 📅 2025-05-29 - cross-platform, cli app to perform various operations on string.
* [xstrings](https://github.com/huandu/xstrings) ⭐ 1,409 | 🐛 0 | 🌐 Go | 📅 2024-06-06 - Collection of useful string functions ported from other languages.

**[⬆ back to top](#contents)**

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

* [anagent](https://github.com/mudler/anagent) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2018-08-12 - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
* [antch](https://github.com/antchfx/antch) ⭐ 263 | 🐛 4 | 🌐 Go | 📅 2020-05-31 - A fast, powerful and extensible web crawling & scraping framework.
* [archives](https://github.com/mholt/archives) ⭐ 258 | 🐛 7 | 🌐 Go | 📅 2025-06-26 - a cross-platform, multi-format Go library for working with archives and compression formats with a unified API and as virtual file systems compatible with io/fs.
* [autoflags](https://github.com/artyom/autoflags) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2022-06-11 - Go package to automatically define command line flags from struct fields.
* [avgRating](https://github.com/kirillDanshin/avgRating) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2017-08-05 - Calculate average score and rating based on Wilson Score Equation.
* [banner](https://github.com/dimiro1/banner) ⭐ 457 | 🐛 0 | 🌐 Go | 📅 2021-01-04 - Add beautiful banners into your Go applications.
* [base64Captcha](https://github.com/mojocn/base64Captcha) ⭐ 2,254 | 🐛 6 | 🌐 Go | 📅 2025-06-25 - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
* [basexx](https://github.com/bobg/basexx) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2023-07-09 - Convert to, from, and between digit strings in various number bases.
* [battery](https://github.com/distatus/battery) ⭐ 262 | 🐛 7 | 🌐 Go | 📅 2023-09-27 - Cross-platform, normalized battery information library.
* [bitio](https://github.com/icza/bitio) ⭐ 250 | 🐛 1 | 🌐 Go | 📅 2023-03-30 - Highly optimized bit-level Reader and Writer for Go.
* [browscap\_go](https://github.com/digitalcrab/browscap_go) ⭐ 49 | 🐛 8 | 🌐 Go | 📅 2023-06-21 - GoLang Library for [Browser Capabilities Project](https://browscap.org/).
* [captcha](https://github.com/steambap/captcha) ⭐ 159 | 🐛 0 | 🌐 Go | 📅 2025-01-05 - Package captcha provides an easy to use, unopinionated API for captcha generation.
* [common](https://github.com/kubeservice-stack/common) ⭐ 4 | 🐛 6 | 🌐 Go | 📅 2025-06-26 - A library for server framework.
* [conv](https://github.com/cstockton/go-conv) ⭐ 381 | 🐛 1 | 🌐 Go | 📅 2021-08-23 - Package conv provides fast and intuitive conversions across Go types.
* [datacounter](https://github.com/miolini/datacounter) ⭐ 49 | 🐛 2 | 🌐 Go | 📅 2023-04-13 - Go counters for readers/writer/http.ResponseWriter.
* [faker](https://github.com/pioz/faker) ⭐ 99 | 🐛 0 | 🌐 Go | 📅 2023-10-06 - Random fake data and struct generator for Go.
* [ffmt](https://github.com/go-ffmt/ffmt) ⭐ 311 | 🐛 2 | 🌐 Go | 📅 2021-11-19 - Beautify data display for Humans.
* [gatus](https://github.com/TwinProduction/gatus) ⭐ 7,621 | 🐛 220 | 🌐 Go | 📅 2025-07-01 - Automated service health dashboard.
* [go-commandbus](https://github.com/lana/go-commandbus) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2022-01-26 - A slight and pluggable command-bus for Go.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) ⭐ 1,238 | 🐛 4 | 🌐 Go | 📅 2023-05-30 - Generic object pool for Golang.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) ⭐ 2,298 | 🐛 2 | 🌐 Go | 📅 2025-02-23 - Resiliency patterns for golang.
* [go-unarr](https://github.com/gen2brain/go-unarr) ⭐ 295 | 🐛 2 | 🌐 Go | 📅 2024-10-22 - Decompression library for RAR, TAR, ZIP and 7z archives.
* [gofakeit](https://github.com/brianvoe/gofakeit) ⭐ 4,973 | 🐛 13 | 🌐 Go | 📅 2025-06-26 - Random data generator written in go.
* [gommit](https://github.com/antham/gommit) ⭐ 115 | 🐛 1 | 🌐 Go | 📅 2025-06-29 - Analyze git commit messages to ensure they follow defined patterns.
* [gopsutil](https://github.com/shirou/gopsutil) ⭐ 11,281 | 🐛 210 | 🌐 Go | 📅 2025-07-02 - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gosh](https://github.com/osamingo/gosh) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2025-03-22 - Provide Go Statistics Handler, Struct, Measure Method.
* [gosms](https://github.com/haxpax/gosms) ⭐ 1,468 | 🐛 5 | 🌐 Go | 📅 2021-02-05 - Your own local SMS gateway in Go that can be used to send SMS.
* [gotoprom](https://github.com/cabify/gotoprom) ⭐ 108 | 🐛 1 | 🌐 Go | 📅 2024-10-09 - Type-safe metrics builder wrapper library for the official Prometheus client.
* [gountries](https://github.com/pariz/gountries) ⭐ 415 | 🐛 18 | 🌐 Go | 📅 2024-06-04 - Package that exposes country and subdivision data.
* [gtree](https://github.com/ddddddO/gtree) ⭐ 302 | 🐛 34 | 🌐 Go | 📅 2025-06-13 - Provide CLI, Package and Web for tree output and directories creation from Markdown or programmatically.
* [health](https://github.com/alexliesenfeld/health) ⭐ 812 | 🐛 2 | 🌐 Go | 📅 2025-06-27 - A simple and flexible health check library for Go.
* [health](https://github.com/dimiro1/health) ⭐ 450 | 🐛 3 | 🌐 Go | 📅 2023-11-18 - Easy to use, extensible health check library.
* [healthcheck](https://github.com/etherlabsio/healthcheck) ⭐ 274 | 🐛 4 | 🌐 Go | 📅 2023-12-13 - An opinionated and concurrent health-check HTTP handler for RESTful services.
* [hostutils](https://github.com/Wing924/hostutils) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2024-06-05 - A golang library for packing and unpacking FQDNs list.
* [indigo](https://github.com/osamingo/indigo) ⭐ 110 | 🐛 0 | 🌐 Go | 📅 2025-03-22 - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [lk](https://github.com/hyperboloide/lk) ⭐ 387 | 🐛 0 | 🌐 Go | 📅 2023-03-25 - A simple licensing library for golang.
* [llvm](https://github.com/llir/llvm) ⭐ 1,229 | 🐛 18 | 🌐 Go | 📅 2024-12-06 - Library for interacting with LLVM IR in pure Go.
* [metrics](https://github.com/pascaldekloe/metrics) ⭐ 27 | 🐛 3 | 🌐 Go | 📅 2023-03-22 - Library for metrics instrumentation and Prometheus exposition.
* [morse](https://github.com/alwindoss/morse) ⭐ 85 | 🐛 5 | 🌐 Go | 📅 2022-08-30 - Library to convert to and from morse code.
* [numa](https://github.com/lrita/numa) ⭐ 35 | 🐛 1 | 🌐 Go | 📅 2024-10-31 - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
* [openapi](https://github.com/neotoolkit/openapi) ⚠️ Archived - OpenAPI 3.x parser.
* [pdfgen](https://github.com/hyperboloide/pdfgen) ⭐ 75 | 🐛 0 | 🌐 Go | 📅 2018-02-19 - HTTP service to generate PDF from Json requests.
* [persian](https://github.com/mavihq/persian) ⭐ 91 | 🐛 2 | 🌐 Go | 📅 2024-01-28 - Some utilities for Persian language in go.
* [sandid](https://github.com/aofei/sandid) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2025-05-17 - Every grain of sand on earth has its own ID.
* [shellwords](https://github.com/Wing924/shellwords) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2023-04-20 - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [shortid](https://github.com/teris-io/shortid) ⭐ 951 | 🐛 4 | 🌐 Go | 📅 2022-06-17 - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [shoutrrr](https://github.com/containrrr/shoutrrr) ⭐ 1,278 | 🐛 83 | 🌐 Go | 📅 2024-07-26 - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
* [sitemap-format](https://github.com/mingard/sitemap-format) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2022-11-16 - A simple sitemap generator, with a little syntactic sugar.
* [stateless](https://github.com/qmuntal/stateless) ⭐ 1,075 | 🐛 19 | 🌐 Go | 📅 2025-05-23 - A fluent library for creating state machines.
* [stats](https://github.com/go-playground/stats) ⭐ 172 | 🐛 1 | 🌐 Go | 📅 2016-09-07 - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [turtle](https://github.com/hackebrot/turtle) ⭐ 164 | 🐛 3 | 🌐 Go | 📅 2021-10-04 - Emojis for Go.
* [url-shortener](https://github.com/pantrif/url-shortener) ⭐ 50 | 🐛 1 | 🌐 Go | 📅 2023-02-06 - A modern, powerful, and robust URL shortener microservice with mysql support.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2016-12-30 - Generate boilerplate http input and output handling.
* [varint](https://github.com/chmike/varint) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2023-10-07 - A faster varying length integer encoder/decoder than the one provided in the standard library.
* [xdg](https://github.com/rkoesters/xdg) ⭐ 48 | 🐛 2 | 🌐 Go | 📅 2024-05-07 - FreeDesktop.org (xdg) Specs implemented in Go.
* [xkg](https://github.com/go-xkg/xkg) ⭐ 61 | 🐛 1 | 🌐 Go | 📅 2015-01-08 - X Keyboard Grabber.
* [xz](https://github.com/ulikunitz/xz) ⭐ 515 | 🐛 17 | 🌐 Go | 📅 2025-02-27 - Pure golang package for reading and writing xz-compressed files.

**[⬆ back to top](#contents)**

## Natural Language Processing

*Libraries for working with human languages.*

See also [Text Processing](#text-processing) and [Text Analysis](#text-analysis).

### Language Detection

* [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2022-04-30 - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
* [getlang](https://github.com/rylans/getlang) ⭐ 173 | 🐛 4 | 🌐 Go | 📅 2020-12-27 - Fast natural language detection package.
* [guesslanguage](https://github.com/endeveit/guesslanguage) ⭐ 58 | 🐛 1 | 🌐 Go | 📅 2017-11-08 - Functions to determine the natural language of a unicode text.
* [lingua-go](https://github.com/pemistahl/lingua-go) ⭐ 1,251 | 🐛 9 | 🌐 Go | 📅 2025-02-06 - An accurate natural language detection library, suitable for long and short text alike. Supports detecting multiple languages in mixed-language text.
* [whatlanggo](https://github.com/abadojack/whatlanggo) ⭐ 658 | 🐛 13 | 🌐 Go | 📅 2023-03-28 - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).

### Morphological Analyzers

* [go-stem](https://github.com/agonopol/go-stem) ⭐ 82 | 🐛 1 | 🌐 Go | 📅 2018-06-16 - Implementation of the porter stemming algorithm.
* [go2vec](https://github.com/danieldk/go2vec) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2018-08-30 - Reader and utility functions for word2vec embeddings.
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2014-06-17 - Go bindings for the snowball libstemmer library including porter 2.
* [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-03-11 - Sentiment analyzer using sentiwordnet lexicon in Go.
* [govader](https://github.com/jonreiter/govader) ⭐ 50 | 🐛 1 | 🌐 Go | 📅 2025-04-29 - Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment) ⭐ 4,754 | 🐛 55 | 🌐 Python | 📅 2024-03-16.
* [govader-backend](https://github.com/PIMPfiction/govader_backend) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2024-02-25 - Microservice implementation of [GoVader](https://github.com/jonreiter/govader) ⭐ 50 | 🐛 1 | 🌐 Go | 📅 2025-04-29.
* [kagome](https://github.com/ikawaha/kagome) ⭐ 879 | 🐛 4 | 🌐 Go | 📅 2025-06-18 - JP morphological analyzer written in pure Go.
* [libtextcat](https://github.com/goodsign/libtextcat) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2012-12-27 - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [nlp](https://github.com/Shixzie/nlp) ⚠️ Archived - Extract values from strings and fill your structs with nlp.
* [nlp](https://github.com/james-bowman/nlp) ⭐ 457 | 🐛 5 | 🌐 Go | 📅 2021-05-11 - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* [paicehusk](https://github.com/rookii/paicehusk) ⭐ 29 | 🐛 2 | 🌐 Go | 📅 2013-12-16 - Golang implementation of the Paice/Husk Stemming Algorithm.
* [porter](https://github.com/a2800276/porter) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2013-10-03 - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [porter2](https://github.com/zhenjl/porter2) ⭐ 46 | 🐛 1 | 🌐 Go | 📅 2020-10-07 - Really fast Porter 2 stemmer.
* [RAKE.go](https://github.com/afjoseph/RAKE.Go) ⭐ 120 | 🐛 2 | 🌐 Go | 📅 2025-06-12 - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [snowball](https://github.com/goodsign/snowball) ⭐ 38 | 🐛 0 | 🌐 C | 📅 2017-06-27 - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [spaGO](https://github.com/nlpodyssey/spago) ⭐ 1,807 | 🐛 13 | 🌐 Go | 📅 2025-04-01 - Self-contained Machine Learning and Natural Language Processing library in Go.
* [spelling-corrector](https://github.com/jorelosorio/spellingcorrector) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2022-03-23 - A spelling corrector for the Spanish language or create your own.

### Slugifiers

* [go-slugify](https://github.com/mozillazg/go-slugify) ⭐ 95 | 🐛 2 | 🌐 Go | 📅 2020-05-13 - Make pretty slug with multiple languages support.
* [slug](https://github.com/gosimple/slug) ⭐ 1,258 | 🐛 10 | 🌐 Go | 📅 2024-12-23 - URL-friendly slugify with multiple languages support.
* [Slugify](https://github.com/avelino/slugify) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2018-05-01 - Go slugify application that handles string.

### Tokenizers

* [gojieba](https://github.com/yanyiwu/gojieba) ⭐ 2,539 | 🐛 16 | 🌐 Go | 📅 2025-06-06 - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) ⭐ 34,217 | 🐛 690 | 🌐 Python | 📅 2024-08-21 which a Chinese word splitting algorithm.
* [gotokenizer](https://github.com/xujiajun/gotokenizer) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2019-04-10 - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
* [gse](https://github.com/go-ego/gse) ⭐ 2,680 | 🐛 13 | 🌐 Go | 📅 2025-06-09 - Go efficient text segmentation; support english, chinese, japanese and other.
* [MMSEGO](https://github.com/awsong/MMSEGO) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2012-04-18 - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* [prose](https://github.com/jdkato/prose) ⚠️ Archived - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
* [segment](https://github.com/blevesearch/segment) ⭐ 89 | 🐛 5 | 🌐 Go | 📅 2022-12-19 - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) ⭐ 451 | 🐛 5 | 🌐 Go | 📅 2024-02-28 - Sentence tokenizer: converts text into a list of sentences.
* [shamoji](https://github.com/osamingo/shamoji) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-03-22 - The shamoji is word filtering package written in Go.
* [stemmer](https://github.com/dchest/stemmer) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2016-12-07 - Stemmer packages for Go programming language. Includes English and German stemmers.
* [textcat](https://github.com/pebbe/textcat) ⭐ 73 | 🐛 1 | 🌐 Go | 📅 2024-12-06 - Go package for n-gram based text categorization, with support for utf-8 and raw text.

### Translation

* [ctxi18n](https://github.com/invopop/ctxi18n/) ⭐ 72 | 🐛 4 | 🌐 Go | 📅 2024-12-04 - Context aware i18n with a short and consise API, pluralization, interpolation, and `fs.FS` support. YAML locale definitions are based on [Rails i18n](https://guides.rubyonrails.org/i18n.html).
* [go-i18n](https://github.com/nicksnyder/go-i18n/) ⭐ 3,278 | 🐛 15 | 🌐 Go | 📅 2025-07-01 - Package and an accompanying tool to work with localized text.
* [go-mystem](https://github.com/dveselov/mystem) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2016-10-05 - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* [go-pinyin](https://github.com/mozillazg/go-pinyin) ⭐ 1,690 | 🐛 18 | 🌐 Go | 📅 2023-07-12 - CN Hanzi to Hanyu Pinyin converter.
* [go-words](https://github.com/saleh-rahimzadeh/go-words) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2024-02-26 - A words table and text resource library for Golang projects.
* [gotext](https://github.com/leonelquinteros/gotext) ⭐ 473 | 🐛 6 | 🌐 Go | 📅 2025-06-01 - GNU gettext utilities for Go.
* [iuliia-go](https://github.com/mehanizm/iuliia-go) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2025-01-08 - Transliterate Cyrillic → Latin in every possible way.
* [spreak](https://github.com/vorlif/spreak) ⭐ 64 | 🐛 3 | 🌐 Go | 📅 2023-12-09 - Flexible translation and humanization library for Go, based on the concepts behind gettext.
* [t](https://github.com/youthlin/t) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-01-19 - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-01-19, which can extract messages as a pot file from text/html template.

### Transliteration

* [enca](https://github.com/endeveit/enca) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2016-03-15 - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings.
* [go-unidecode](https://github.com/mozillazg/go-unidecode) ⭐ 141 | 🐛 5 | 🌐 Go | 📅 2023-05-14 - ASCII transliterations of Unicode text.
* [gounidecode](https://github.com/fiam/gounidecode) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2015-09-23 - Unicode transliterator (also known as unidecode) for Go.
* [transliterator](https://github.com/alexsergivan/transliterator) ⭐ 45 | 🐛 2 | 🌐 Go | 📅 2024-06-05 - Provides one-way string transliteration with supporting of language-specific transliteration rules.

**[⬆ back to top](#contents)**

## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) ⭐ 374 | 🐛 8 | 🌐 Go | 📅 2022-12-03 - Package arp implements the ARP protocol, as described in RFC 826.
* [bart](https://github.com/gaissmai/bart) ⭐ 73 | 🐛 0 | 🌐 Go | 📅 2025-06-15 - Package bart provides a fast routing table algorithm.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) ⭐ 254 | 🐛 5 | 🌐 Go | 📅 2020-08-14 - Streaming protocolbuffer data over TCP made easy.
* [canopus](https://github.com/zubairhamed/canopus) ⭐ 156 | 🐛 43 | 🌐 Go | 📅 2018-03-25 - CoAP Client/Server implementation (RFC 7252).
* [cidranger](https://github.com/yl2chen/cidranger) ⭐ 946 | 🐛 10 | 🌐 Go | 📅 2023-06-05 - Fast IP to CIDR lookup for Go.
* [cloudflared](https://github.com/cloudflare/cloudflared) ⭐ 10,931 | 🐛 440 | 🌐 Go | 📅 2025-07-01 - Cloudflare Tunnel client (formerly Argo Tunnel).
* [dhcp6](https://github.com/mdlayher/dhcp6) ⭐ 79 | 🐛 3 | 🌐 Go | 📅 2023-02-24 - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [dns](https://github.com/miekg/dns) ⭐ 8,404 | 🐛 11 | 🌐 Go | 📅 2025-06-01 - Go library for working with DNS.
* [dnsmonster](https://github.com/mosajjal/dnsmonster) ⭐ 330 | 🐛 4 | 🌐 Go | 📅 2025-05-14 - Passive DNS Capture/Monitoring Framework.
* [easytcp](https://github.com/DarthPestilane/easytcp) ⭐ 821 | 🐛 4 | 🌐 Go | 📅 2025-06-06 - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful.
* [ether](https://github.com/songgao/ether) ⭐ 80 | 🐛 0 | 🌐 Go | 📅 2016-04-05 - Cross-platform Go package for sending and receiving ethernet frames.
* [ethernet](https://github.com/mdlayher/ethernet) ⭐ 283 | 🐛 0 | 🌐 Go | 📅 2022-02-21 - Package ethernet implements marshaling and unmarshalling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [event](https://github.com/cheng-zhongliang/event) ⭐ 120 | 🐛 0 | 🌐 Go | 📅 2024-12-27 - Simple I/O event notification library written in Golang.
* [fasthttp](https://github.com/valyala/fasthttp) ⭐ 22,701 | 🐛 110 | 🌐 Go | 📅 2025-07-02 - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [fortio](https://github.com/fortio/fortio) ⭐ 3,551 | 🐛 80 | 🌐 Go | 📅 2025-06-23 - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
* [ftp](https://github.com/jlaffaye/ftp) ⭐ 1,360 | 🐛 41 | 🌐 Go | 📅 2025-06-13 - Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959).
* [ftpserverlib](https://github.com/fclairamb/ftpserverlib) ⭐ 448 | 🐛 7 | 🌐 Go | 📅 2025-06-15 - Fully featured FTP server library.
* [fullproxy](https://github.com/shoriwe/fullproxy) ⭐ 81 | 🐛 4 | 🌐 Go | 📅 2023-08-13 - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols.
* [fwdctl](https://github.com/alegrey91/fwdctl) ⭐ 66 | 🐛 12 | 🌐 Go | 📅 2025-01-23 - A simple and intuitive CLI to manage IPTables forwards in your Linux server.
* [gaio](https://github.com/xtaci/gaio) ⭐ 793 | 🐛 17 | 🌐 Go | 📅 2025-06-02 - High performance async-io networking for Golang in proactor mode.
* [gev](https://github.com/Allenxuxu/gev) ⭐ 1,755 | 🐛 14 | 🌐 Go | 📅 2025-06-07 - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
* [gldap](https://github.com/jimlambrt/gldap) ⭐ 114 | 🐛 1 | 🌐 Go | 📅 2024-10-18 - gldap provides an ldap server implementation and you provide handlers for its ldap operations.
* [gmqtt](https://github.com/DrmagicE/gmqtt) ⭐ 1,008 | 🐛 1 | 🌐 Go | 📅 2025-06-24 - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
* [gnet](https://github.com/panjf2000/gnet) ⭐ 10,617 | 🐛 4 | 🌐 Go | 📅 2025-06-20 - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
* [gnet](https://github.com/fish-tennis/gnet) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2025-06-04 - `gnet` is a high-performance networking framework,especially for game servers.
* [gNxI](https://github.com/google/gnxi) ⭐ 275 | 🐛 28 | 🌐 Python | 📅 2025-05-08 - A collection of tools for Network Management that use the gNMI and gNOI protocols.
* [go-getter](https://github.com/hashicorp/go-getter) ⭐ 1,711 | 🐛 178 | 🌐 Go | 📅 2025-06-29 - Go library for downloading files or directories from various sources using a URL.
* [go-multiproxy](https://github.com/presbrey/go-multiproxy) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2025-04-16 - Library for making HTTP requests through a pool of proxies offering fault tolerance, load balancing, automatic retries, cookie management, and more, via http.Get/Post replacement or http.Client RoundTripper drop-in
* [go-powerdns](https://github.com/joeig/go-powerdns) ⭐ 97 | 🐛 0 | 🌐 Go | 📅 2025-06-27 - PowerDNS API bindings for Golang.
* [go-sse](https://github.com/lampctl/go-sse) ⭐ 14 | 🐛 2 | 🌐 Go | 📅 2025-04-18 - Go client and server implementation of HTML server-sent events.
* [go-stun](https://github.com/ccding/go-stun) ⭐ 709 | 🐛 4 | 🌐 Go | 📅 2024-07-01 - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [gobgp](https://github.com/osrg/gobgp) ⭐ 3,822 | 🐛 223 | 🌐 Go | 📅 2025-07-02 - BGP implemented in the Go Programming Language.
* [gopacket](https://github.com/google/gopacket) ⭐ 6,556 | 🐛 360 | 🌐 Go | 📅 2025-03-19 - Go library for packet processing with libpcap bindings.
* [gopcap](https://github.com/akrennmair/gopcap) ⭐ 491 | 🐛 11 | 🌐 Go | 📅 2021-05-17 - Go wrapper for libpcap.
* [GoProxy](https://github.com/elazarl/goproxy) ⭐ 6,397 | 🐛 85 | 🌐 Go | 📅 2025-06-05 - A library to create a customized HTTP/HTTPS proxy server using Go.
* [goshark](https://github.com/sunwxg/goshark) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2017-10-24 - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [gosnmp](https://github.com/soniah/gosnmp) ⭐ 1,195 | 🐛 61 | 🌐 Go | 📅 2025-07-01 - Native Go library for performing SNMP actions.
* [gotcp](https://github.com/gansidui/gotcp) ⭐ 514 | 🐛 0 | 🌐 Go | 📅 2023-08-08 - Go package for quickly writing tcp applications.
* [grab](https://github.com/cavaliercoder/grab) ⭐ 1,444 | 🐛 33 | 🌐 Go | 📅 2024-05-14 - Go package for managing file downloads.
* [graval](https://github.com/koofr/graval) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2020-10-02 - Experimental FTP server framework.
* [gws](https://github.com/lxzan/gws) ⭐ 1,564 | 🐛 0 | 🌐 Go | 📅 2025-05-13 - High-Performance WebSocket Server & Client With AsyncIO Supporting .
* [HTTPLab](https://github.com/gchaincl/httplab) ⭐ 4,078 | 🐛 13 | 🌐 Go | 📅 2024-02-05 - HTTPLabs let you inspect HTTP requests and forge responses.
* [httpproxy](https://github.com/wzshiming/httpproxy) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2025-04-17 - HTTP proxy handler and dialer.
* [iplib](https://github.com/c-robinson/iplib) ⭐ 148 | 🐛 0 | 🌐 Go | 📅 2024-04-06 - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* [jazigo](https://github.com/udhos/jazigo) ⭐ 221 | 🐛 1 | 🌐 Go | 📅 2023-11-02 - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [kcp-go](https://github.com/xtaci/kcp-go) ⭐ 4,283 | 🐛 63 | 🌐 Go | 📅 2025-06-18 - KCP - Fast and Reliable ARQ Protocol.
* [kcptun](https://github.com/xtaci/kcptun) ⭐ 14,162 | 🐛 130 | 🌐 Go | 📅 2025-07-01 - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp](https://github.com/fanux/lhttp) ⭐ 690 | 🐛 7 | 🌐 Go | 📅 2018-04-08 - Powerful websocket framework, build your IM server more easily.
* [linkio](https://github.com/ian-kent/linkio) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2017-08-07 - Network link speed simulation for Reader/Writer interfaces.
* [llb](https://github.com/kirillDanshin/llb) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2016-04-04 - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [mdns](https://github.com/hashicorp/mdns) ⭐ 1,270 | 🐛 40 | 🌐 Go | 📅 2025-07-01 - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [natiu-mqtt](https://github.com/soypat/natiu-mqtt) ⭐ 96 | 🐛 4 | 🌐 Go | 📅 2025-02-17 - A dead-simple, non-allocating, low level implementation of MQTT well suited for embedded systems.
* [nbio](https://github.com/lesismal/nbio) ⭐ 2,537 | 🐛 2 | 🌐 Go | 📅 2025-07-02 - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
* [net](https://golang.org/x/net) - This repository holds supplementary Go networking libraries.
* [netpoll](https://github.com/cloudwego/netpoll) ⭐ 4,348 | 🐛 25 | 🌐 Go | 📅 2025-06-17 - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance.
* [NFF-Go](https://github.com/intel-go/nff-go) ⭐ 1,406 | 🐛 65 | 🌐 Go | 📅 2022-11-22 - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* [nodepass](https://github.com/yosebyte/nodepass) ⭐ 1,079 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - A secure, efficient TCP/UDP tunneling solution that delivers fast, reliable access across network restrictions using pre-established TLS/TCP connections.
* [peerdiscovery](https://github.com/schollz/peerdiscovery) ⭐ 659 | 🐛 5 | 🌐 Go | 📅 2025-01-09 - Pure Go library for cross-platform local peer discovery using UDP multicast.
* [portproxy](https://github.com/aybabtme/portproxy) ⭐ 58 | 🐛 0 | 🌐 Go | 📅 2014-12-13 - Simple TCP proxy which adds CORS support to API's which don't support it.
* [psql-wire](https://github.com/jeroenrinzema/psql-wire) ⭐ 149 | 🐛 16 | 🌐 Go | 📅 2025-07-01 - PostgreSQL server wire protocol. Build your own server and start serving connections..
* [publicip](https://github.com/polera/publicip) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2016-12-29 - Package publicip returns your public facing IPv4 address (internet egress).
* [quic-go](https://github.com/lucas-clemente/quic-go) ⭐ 10,794 | 🐛 189 | 🌐 Go | 📅 2025-06-29 - An implementation of the QUIC protocol in pure Go.
* [raw](https://github.com/mdlayher/raw) ⚠️ Archived - Package raw enables reading and writing data at the device driver level for a network interface.
* [sdns](https://github.com/semihalev/sdns) ⭐ 998 | 🐛 0 | 🌐 Go | 📅 2025-06-30 - A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy.
* [sftp](https://github.com/pkg/sftp) ⭐ 1,585 | 🐛 48 | 🌐 Go | 📅 2025-06-02 - Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>.
* [ssh](https://github.com/gliderlabs/ssh) ⭐ 3,932 | 🐛 56 | 🌐 Go | 📅 2025-01-27 - Higher-level API for building SSH servers (wraps crypto/ssh).
* [sslb](https://github.com/eduardonunesp/sslb) ⭐ 151 | 🐛 11 | 🌐 Go | 📅 2024-02-18 - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [stun](https://github.com/go-rtc/stun) ⚠️ Archived - Go implementation of RFC 5389 STUN protocol.
* [tcpack](https://github.com/lim-yoona/tcpack) ⭐ 170 | 🐛 0 | 🌐 Go | 📅 2023-10-16 - tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program.
* [tspool](https://github.com/two/tspool) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2018-10-29 - A TCP Library use worker pool to improve performance and protect your server.
* [tun2socks](https://github.com/xjasonlyu/tun2socks) ⭐ 3,950 | 🐛 15 | 🌐 Go | 📅 2025-06-20 - A pure go implementation of tun2socks powered by [gVisor](https://gvisor.dev/) TCP/IP stack.
* [utp](https://github.com/anacrolix/utp) ⭐ 178 | 🐛 4 | 🌐 Go | 📅 2023-05-19 - Go uTP micro transport protocol implementation.
* [vssh](https://github.com/yahoo/vssh) ⭐ 973 | 🐛 6 | 🌐 Go | 📅 2023-12-07 - Go library for building network and server automation over SSH protocol.
* [water](https://github.com/songgao/water) ⭐ 2,046 | 🐛 30 | 🌐 Go | 📅 2024-07-30 - Simple TUN/TAP library.
* [webrtc](https://github.com/pions/webrtc) ⭐ 14,997 | 🐛 99 | 🌐 Go | 📅 2025-07-03 - A pure Go implementation of the WebRTC API.
* [winrm](https://github.com/masterzen/winrm) ⭐ 444 | 🐛 47 | 🌐 Go | 📅 2024-07-02 - Go WinRM client to remotely execute commands on Windows machines.
* [xtcp](https://github.com/xfxdev/xtcp) ⭐ 157 | 🐛 0 | 🌐 Go | 📅 2020-02-29 - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.

**[⬆ back to top](#contents)**

### HTTP Clients

*Libraries for making HTTP requests.*

* [axios4go](https://github.com/rezmoss/axios4go) ⭐ 28 | 🐛 3 | 🌐 Go | 📅 2025-01-22 - A Go HTTP client library inspired by Axios, providing a simple and intuitive API for making HTTP requests.
* [azuretls-client](https://github.com/Noooste/azuretls-client) ⭐ 275 | 🐛 6 | 🌐 Go | 📅 2025-07-01 -  An easy-to-use HTTP client 100% in Go to spoof TLS/JA3 and HTTP2 fingerprint
* [fast-shot](https://github.com/opus-domini/fast-shot) ⭐ 85 | 🐛 2 | 🌐 Go | 📅 2024-12-20 - Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client.
* [gentleman](https://github.com/h2non/gentleman) ⭐ 1,111 | 🐛 27 | 🌐 Go | 📅 2023-12-17 - Full-featured plugin-driven HTTP client library.
* [go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) ⭐ 400 | 🐛 5 | 🌐 Go | 📅 2025-06-25 - Get easily stdlib HTTP client, which does not share any state with other clients.
* [go-http-client](https://github.com/bozd4g/go-http-client) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2024-01-28 - Make http calls simply and easily.
* [go-ipmux](https://github.com/optimus-hft/go-ipmux) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2024-03-06 - A library for Multiplexing HTTP requests based on multiple Source IPs.
* [go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) ⭐ 85 | 🐛 0 | 🌐 Go | 📅 2025-07-02 - Go http.RoundTripper that emits open telemetry metrics for HTTP requests.
* [go-req](https://github.com/wenerme/go-req) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2022-07-06 - Declarative golang HTTP client.
* [go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) ⭐ 2,151 | 🐛 72 | 🌐 Go | 📅 2025-07-01 - Retryable HTTP client in Go.
* [go-zoox/fetch](https://github.com/go-zoox/fetch) ⭐ 79 | 🐛 3 | 🌐 Go | 📅 2025-06-23 - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API.
* [grequests](https://github.com/levigross/grequests) ⭐ 2,158 | 🐛 24 | 🌐 Go | 📅 2025-06-06 - A Go "clone" of the great and famous Requests library.
* [heimdall](https://github.com/gojektech/heimdall) ⭐ 2,677 | 🐛 50 | 🌐 Go | 📅 2024-05-29 - An enhanced http client with retry and hystrix capabilities.
* [httpretry](https://github.com/ybbus/httpretry) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2024-05-18 - Enriches the default go HTTP client with retry functionality.
* [pester](https://github.com/sethgrid/pester) ⭐ 652 | 🐛 6 | 🌐 Go | 📅 2022-02-09 - Go HTTP client calls with retries, backoff, and concurrency.
* [req](https://github.com/imroc/req) ⭐ 4,539 | 🐛 72 | 🌐 Go | 📅 2025-06-27 - Simple Go HTTP client with Black Magic (Less code and More efficiency).
* [request](https://github.com/monaco-io/request) ⭐ 292 | 🐛 2 | 🌐 Go | 📅 2024-10-29 - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
* [requests](https://github.com/carlmjohnson/requests) ⭐ 1,610 | 🐛 2 | 🌐 Go | 📅 2025-04-16 - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools.
* [resty](https://github.com/go-resty/resty) ⭐ 11,013 | 🐛 35 | 🌐 Go | 📅 2025-05-11 - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [rq](https://github.com/ddo/rq) ⭐ 53 | 🐛 1 | 🌐 Go | 📅 2019-08-28 - A nicer interface for golang stdlib HTTP client.
* [sling](https://github.com/dghubble/sling) ⭐ 1,705 | 🐛 2 | 🌐 Go | 📅 2025-05-05 - Sling is a Go HTTP client library for creating and sending API requests.
* [tls-client](https://github.com/bogdanfinn/tls-client) ⭐ 1,184 | 🐛 35 | 🌐 Go | 📅 2025-06-17 - net/http.Client like HTTP Client with options to select specific client TLS Fingerprints to use for requests.

**[⬆ back to top](#contents)**

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) ⭐ 1,160 | 🐛 18 | 🌐 C | 📅 2024-07-07 - Go bindings for OpenGL (generated via glow).
* [glfw](https://github.com/go-gl/glfw) ⭐ 1,631 | 🐛 26 | 🌐 C | 📅 2025-03-01 - Go bindings for GLFW 3.
* [go-glmatrix](https://github.com/technohippy/go-glmatrix) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-02-05 - Go port of [glMatrix](https://glmatrix.net/) library.
* [goxjs/gl](https://github.com/goxjs/gl) ⭐ 178 | 🐛 8 | 🌐 Go | 📅 2023-07-05 - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw](https://github.com/goxjs/glfw) ⭐ 83 | 🐛 6 | 🌐 Go | 📅 2023-07-04 - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl](https://github.com/go-gl/mathgl) ⭐ 579 | 🐛 10 | 🌐 Go | 📅 2024-11-03 - Pure Go math package specialized for 3D math, with inspiration from GLM.

**[⬆ back to top](#contents)**

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [bob](https://github.com/stephenafamo/bob) ⭐ 1,336 | 🐛 21 | 🌐 Go | 📅 2025-07-02 - SQL query builder and ORM/Factory generator for Go. Successor of SQLBoiler.
* [bun](https://github.com/uptrace/bun) ⭐ 4,234 | 🐛 30 | 🌐 Go | 📅 2025-06-27 - SQL-first Golang ORM. Successor of go-pg.
* [cacheme](https://github.com/Yiling-J/cacheme-go) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2021-12-18 - Schema based, typed Redis caching/memoize framework for Go.
* [CQL](https://github.com/FrancoLiberali/cql) ⭐ 17 | 🐛 15 | 🌐 Go | 📅 2024-05-21 - Built on top of GORM, adds compile-time verified queries based on auto-generated code.
* [ent](https://github.com/facebook/ent) ⭐ 16,321 | 🐛 588 | 🌐 Go | 📅 2025-06-20 - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
* [go-dbw](https://github.com/hashicorp/go-dbw) ⭐ 17 | 🐛 2 | 🌐 Go | 📅 2025-05-23 - A simple package that encapsulates database operations.
* [go-firestorm](https://github.com/jschoedt/go-firestorm) ⭐ 52 | 🐛 0 | 🌐 Go | 📅 2021-12-13 - A simple ORM for Google/Firebase Cloud Firestore.
* [go-sql](https://github.com/rushteam/gosql) ⭐ 180 | 🐛 7 | 🌐 Go | 📅 2022-06-17 - A easy ORM for mysql.
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) ⭐ 1,566 | 🐛 8 | 🌐 Go | 📅 2025-06-12 - A flexible and powerful SQL string builder library plus a zero-config ORM.
* [go-store](https://github.com/gosuri/go-store) ⭐ 113 | 🐛 1 | 🌐 Go | 📅 2017-02-23 - Simple and fast Redis backed key-value store library for Go.
* [golobby/orm](https://github.com/golobby/orm) ⭐ 160 | 🐛 6 | 🌐 Go | 📅 2023-08-30 - Simple, fast, type-safe, generic orm for developer happiness.
* [GORM](https://github.com/go-gorm/gorm) ⭐ 38,439 | 🐛 461 | 🌐 Go | 📅 2025-06-25 - The fantastic ORM library for Golang, aims to be developer friendly.
* [gormt](https://github.com/xxjwxc/gormt) ⭐ 2,401 | 🐛 56 | 🌐 Go | 📅 2025-06-24 - Mysql database to golang gorm struct.
* [gorp](https://github.com/go-gorp/gorp) ⭐ 3,746 | 🐛 149 | 🌐 Go | 📅 2024-11-19 - Go Relational Persistence, ORM-ish library for Go.
* [grimoire](https://github.com/Fs02/grimoire) ⭐ 163 | 🐛 0 | 🌐 Go | 📅 2021-10-25 - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* [lore](https://github.com/abrahambotros/lore) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2017-10-21 - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* [marlow](https://github.com/marlow/marlow) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2020-08-18 - Generated ORM from project structs for compile time safety assurances.
* [pop/soda](https://github.com/gobuffalo/pop) ⭐ 1,491 | 🐛 94 | 🌐 Go | 📅 2024-06-26 - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [Prisma](https://github.com/prisma/prisma-client-go) ⭐ 2,303 | 🐛 115 | 🌐 Go | 📅 2025-07-02 - Prisma Client Go, Typesafe database access for Go.
* [reform](https://github.com/go-reform/reform) ⭐ 1,444 | 🐛 86 | 🌐 Go | 📅 2023-03-13 - Better ORM for Go, based on non-empty interfaces and code generation.
* [rel](https://github.com/go-rel/rel) ⭐ 783 | 🐛 34 | 🌐 Go | 📅 2024-12-02 - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) ⭐ 6,890 | 🐛 104 | 🌐 Go | 📅 2025-06-27 - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [upper.io/db](https://github.com/upper/db) ⭐ 3,600 | 🐛 159 | 🌐 Go | 📅 2025-03-21 - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
* [Zoom](https://github.com/albrow/zoom) ⭐ 312 | 🐛 2 | 🌐 Go | 📅 2023-02-02 - Blazing-fast datastore and querying engine built on Redis.

**[⬆ back to top](#contents)**

## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Unofficial libraries for package and dependency management.*

* [glide](https://github.com/Masterminds/glide) ⭐ 8,131 | 🐛 400 | 🌐 Go | 📅 2024-07-22 - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* [godep](https://github.com/tools/godep) ⚠️ Archived - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [goop](https://github.com/nitrous-io/goop) ⭐ 775 | 🐛 28 | 🌐 Go | 📅 2015-12-02 - Simple dependency manager for Go (golang), inspired by Bundler.
* [gop](https://github.com/lunny/gop) ⚠️ Archived - Build and manage your Go applications out of GOPATH.
* [gopm](https://github.com/gpmgo/gopm) ⚠️ Archived - Go Package Manager.
* [govendor](https://github.com/kardianos/govendor) ⚠️ Archived - Go Package Manager. Go vendor tool that works with the standard vendor file.
* [gpm](https://github.com/pote/gpm) ⭐ 1,182 | 🐛 11 | 🌐 Shell | 📅 2017-09-28 - Barebones dependency manager for Go.
* [gup](https://github.com/nao1215/gup) ⭐ 415 | 🐛 5 | 🌐 Go | 📅 2025-06-16 - Update binaries installed by "go install".
* [johnny-deps](https://github.com/VividCortex/johnny-deps) ⚠️ Archived - Minimal dependency version using Git.
* [modgv](https://github.com/lucasepe/modgv) ⚠️ Archived - Converts 'go mod graph' output into Graphviz's DOT language.
* [mvn-golang](https://github.com/raydac/mvn-golang) ⚠️ Archived - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
* [syft](https://github.com/anchore/syft) ⭐ 7,271 | 🐛 471 | 🌐 Go | 📅 2025-07-02 - A CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems.
* [VenGO](https://github.com/DamnWidget/VenGO) ⭐ 126 | 🐛 3 | 🌐 Go | 📅 2016-07-14 - create and manage exportable isolated go virtual environments.

**[⬆ back to top](#contents)**

## Performance

* [go-instrument](https://github.com/nikolaydubina/go-instrument) ⭐ 268 | 🐛 0 | 🌐 Go | 📅 2025-05-11 - Automatically add spans to all methods and functions.
* [jaeger](https://github.com/jaegertracing/jaeger) ⭐ 21,540 | 🐛 324 | 🌐 Go | 📅 2025-07-03 - A distributed tracing system.
* [mm-go](https://github.com/joetifa2003/mm-go) ⭐ 171 | 🐛 1 | 🌐 Go | 📅 2025-01-05 - Generic manual memory management for golang.
* [pixie](https://github.com/pixie-labs/pixie) ⭐ 6,077 | 🐛 330 | 🌐 C++ | 📅 2025-07-02 - No instrumentation tracing for Golang applications via eBPF.
* [profile](https://github.com/pkg/profile) ⭐ 2,031 | 🐛 11 | 🌐 Go | 📅 2022-10-20 - Simple profiling support package for Go.
* [statsviz](https://github.com/arl/statsviz) ⭐ 3,307 | 🐛 11 | 🌐 Go | 📅 2025-06-17 - Live visualization of your Go application runtime statistics.
* [tracer](https://github.com/kamilsk/tracer) ⭐ 89 | 🐛 11 | 🌐 Go | 📅 2021-02-27 - Simple, lightweight tracing.

**[⬆ back to top](#contents)**

## Query Language

* [api-fu](https://github.com/ccbrown/api-fu) ⭐ 57 | 🐛 3 | 🌐 Go | 📅 2024-08-29 - Comprehensive GraphQL implementation.
* [dasel](https://github.com/tomwright/dasel) ⭐ 7,493 | 🐛 48 | 🌐 Go | 📅 2025-03-28 - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [gojsonq](https://github.com/thedevsaddam/gojsonq) ⭐ 2,210 | 🐛 26 | 🌐 Go | 📅 2022-11-28 - A simple Go package to Query over JSON Data.
* [goven](https://github.com/SeldonIO/goven) ⭐ 61 | 🐛 6 | 🌐 Go | 📅 2022-04-14 - A drop-in query language for any database schema.
* [gqlgen](https://github.com/99designs/gqlgen) ⭐ 10,395 | 🐛 367 | 🌐 Go | 📅 2025-07-01 - go generate based graphql server library.
* [grapher](https://github.com/reaganiwadha/grapher) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2023-07-21 - A GraphQL field builder utilizing Go generics with extra utilities and features.
* [graphql](https://github.com/tmc/graphql) ⚠️ Archived - graphql parser + utilities.
* [graphql](https://github.com/neelance/graphql-go) ⭐ 4,711 | 🐛 42 | 🌐 Go | 📅 2025-06-12 - GraphQL server with a focus on ease of use.
* [graphql-go](https://github.com/graphql-go/graphql) ⭐ 10,077 | 🐛 237 | 🌐 Go | 📅 2025-04-01 - Implementation of GraphQL for Go.
* [gws](https://github.com/Zaba505/gws) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2020-09-04 - Apollos' "GraphQL over Websocket" client and server implementation.
* [jsonpath](https://github.com/AsaiYusuke/jsonpath) ⭐ 26 | 🐛 1 | 🌐 Go | 📅 2023-10-28 - A query library for retrieving part of JSON based on JSONPath syntax.
* [jsonql](https://github.com/elgs/jsonql) ⭐ 278 | 🐛 5 | 🌐 Go | 📅 2020-11-20 - JSON query expression library in Golang.
* [jsonslice](https://github.com/bhmj/jsonslice) ⭐ 92 | 🐛 3 | 🌐 Go | 📅 2024-10-25 - Jsonpath queries with advanced filters.
* [mql](https://github.com/hashicorp/mql) ⭐ 60 | 🐛 1 | 🌐 Go | 📅 2025-06-24 - Model Query Language (mql) is a query language for your database models.
* [rql](https://github.com/a8m/rql) ⭐ 357 | 🐛 16 | 🌐 Go | 📅 2024-07-25 - Resource Query Language for REST API.
* [rqp](https://github.com/timsolov/rest-query-parser) ⭐ 85 | 🐛 3 | 🌐 Go | 📅 2023-12-04 - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
* [straf](https://github.com/SonicRoshan/straf) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2020-05-16 - Easily Convert Golang structs to GraphQL objects.

**[⬆ back to top](#contents)**

## Reflection

* [copy](https://github.com/gotidy/copy) ⭐ 51 | 🐛 4 | 🌐 Go | 📅 2020-12-28 - Package for fast copying structs of different types.
* [Deepcopier](https://github.com/ulule/deepcopier) ⭐ 457 | 🐛 7 | 🌐 Go | 📅 2020-04-30 - Simple struct copying for Go.
* [go-deepcopy](https://github.com/tiendc/go-deepcopy) ⭐ 98 | 🐛 0 | 🌐 Go | 📅 2025-06-09 - Fast deep copy library.
* [goenum](https://github.com/lvyahui8/goenum) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2024-09-22 - A common enumeration struct based on generics and reflection that allows you to quickly define enumerations and use a set of useful default methods.
* [gotype](https://github.com/wzshiming/gotype) ⭐ 63 | 🐛 1 | 🌐 Go | 📅 2024-09-25 - Golang source code parsing, usage like reflect package.
* [gpath](https://github.com/tenntenn/gpath) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2017-06-04 - Library to simplify access struct fields with Go's expression in reflection.
* [objwalker](https://github.com/rekby/objwalker) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2022-03-04 - Walk by go objects with reflection.
* [reflectpro](https://github.com/gontainer/reflectpro) ⭐ 7 | 🐛 2 | 🌐 Go | 📅 2024-10-01 - Callers, copiers, getters and setters for go.
* [reflectutils](https://github.com/muir/reflectutils) ⭐ 8 | 🐛 2 | 🌐 Go | 📅 2025-05-06 - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string.

**[⬆ back to top](#contents)**

## Resource Embedding

* [debme](https://github.com/leaanthony/debme) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2021-06-06 - Create an `embed.FS` from an existing `embed.FS` subdirectory.
* [embed](https://pkg.go.dev/embed) - Package embed provides access to files embedded in the running Go program.
* [rebed](https://github.com/soypat/rebed) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2022-02-18 - Recreate folder structures and files from Go 1.16's `embed.FS` type
* [vfsgen](https://github.com/shurcooL/vfsgen) ⭐ 982 | 🐛 31 | 🌐 Go | 📅 2023-11-26 - Generates a vfsdata.go file that statically implements the given virtual filesystem.

**[⬆ back to top](#contents)**

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [assocentity](https://github.com/ndabAP/assocentity) ⭐ 17 | 🐛 3 | 🌐 Go | 📅 2025-06-22 - Package assocentity returns the average distance from words to a given entity.
* [bradleyterry](https://github.com/seanhagen/bradleyterry) ⭐ 11 | 🐛 1 | 🌐 Go | 📅 2019-05-02 - Provides a Bradley-Terry Model for pairwise comparisons.
* [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) ⚠️ Archived - Calendar heatmap in plain Go inspired by Github contribution activity.
* [chart](https://github.com/vdobler/chart) ⭐ 774 | 🐛 6 | 🌐 Go | 📅 2021-06-03 - Simple Chart Plotting library for Go. Supports many graphs types.
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) ⭐ 1,255 | 🐛 20 | 🌐 Go | 📅 2022-04-02 - Dataframes for machine-learning and statistics (similar to pandas).
* [decimal](https://github.com/db47h/decimal) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2022-08-12 - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
* [evaler](https://github.com/soniah/evaler) ⭐ 51 | 🐛 5 | 🌐 Go | 📅 2018-07-27 - Simple floating point arithmetic expression evaluator.
* [ewma](https://github.com/VividCortex/ewma) ⭐ 448 | 🐛 5 | 🌐 Go | 📅 2023-12-14 - Exponentially-weighted moving averages.
* [geom](https://github.com/skelterjohn/geom) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2018-01-03 - 2D geometry for golang.
* [go-dsp](https://github.com/mjibson/go-dsp) ⭐ 880 | 🐛 7 | 🌐 Go | 📅 2023-10-09 - Digital Signal Processing for Go.
* [go-estimate](https://github.com/milosgajdos/go-estimate) ⭐ 117 | 🐛 2 | 🌐 Go | 📅 2025-01-19 - State estimation and filtering algorithms in Go.
* [go-gt](https://github.com/ThePaw/go-gt) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2015-09-14 - Graph theory algorithms written in "Go" language.
* [go-hep](https://github.com/go-hep/hep) ⭐ 247 | 🐛 124 | 🌐 Go | 📅 2025-05-26 - A set of libraries and tools for performing High Energy Physics analyses with ease.
* [godesim](https://github.com/soypat/godesim) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2022-06-04 - Extended/multivariable ODE solver framework for event-based simulations with simple API.
* [goent](https://github.com/kzahedi/goent) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2019-04-03 - GO Implementation of Entropy Measures.
* [gograph](https://github.com/hmdsefi/gograph) ⭐ 86 | 🐛 4 | 🌐 Go | 📅 2025-05-18 - A golang generic graph library that provides mathematical graph-theory and algorithms.
* [gonum](https://github.com/gonum/gonum) ⭐ 8,071 | 🐛 246 | 🌐 Go | 📅 2025-06-08 - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* [gonum/plot](https://github.com/gonum/plot) ⭐ 2,875 | 🐛 90 | 🌐 Go | 📅 2025-03-27 - gonum/plot provides an API for building and drawing plots in Go.
* [goraph](https://github.com/gyuho/goraph) ⭐ 743 | 🐛 5 | 🌐 Go | 📅 2022-04-10 - Pure Go graph theory library(data structure, algorithm visualization).
* [gosl](https://github.com/cpmech/gosl) ⭐ 1,856 | 🐛 0 | 🌐 Go | 📅 2025-04-08 - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [GoStats](https://github.com/OGFris/GoStats) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2019-01-14 - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
* [graph](https://github.com/yourbasic/graph) ⭐ 730 | 🐛 6 | 🌐 Go | 📅 2023-05-11 - Library of basic graph algorithms.
* [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) ⭐ 75 | 🐛 5 | 🌐 Go | 📅 2024-08-22 - Tool to manipulate JSONL graphs with graphviz support.
* [ode](https://github.com/ChristopherRabotin/ode) ⭐ 22 | 🐛 1 | 🌐 Go | 📅 2017-03-18 - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [orb](https://github.com/paulmach/orb) ⭐ 1,003 | 🐛 23 | 🌐 Go | 📅 2024-08-07 - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
* [pagerank](https://github.com/alixaxel/pagerank) ⭐ 86 | 🐛 3 | 🌐 Go | 📅 2021-06-19 - Weighted PageRank algorithm implemented in Go.
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2023-12-10 - Tiny linear interpolation library.
* [PiHex](https://github.com/claygod/PiHex) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2025-04-12 - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [Poly](https://github.com/bebop/poly) ⭐ 705 | 🐛 30 | 🌐 Go | 📅 2024-10-21 - A Go package for engineering organisms.
* [rootfinding](https://github.com/khezen/rootfinding) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2020-03-22 - root-finding algorithms library for finding roots of quadratic functions.
* [sparse](https://github.com/james-bowman/sparse) ⭐ 164 | 🐛 5 | 🌐 Go | 📅 2021-07-29 - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* [stats](https://github.com/montanaflynn/stats) ⭐ 2,988 | 🐛 23 | 🌐 Go | 📅 2025-03-25 - Statistics package with common functions missing from the Golang standard library.
* [streamtools](https://github.com/nytlabs/streamtools) ⭐ 1,311 | 🐛 47 | 🌐 Go | 📅 2023-10-19 - general purpose, graphical tool for dealing with streams of data.
* [TextRank](https://github.com/DavidBelicza/TextRank) ⭐ 215 | 🐛 5 | 🌐 Go | 📅 2025-06-14 - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
* [topk](https://github.com/keilerkonzept/topk) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-04-30 - Sliding-window and regular top-K sketches, based on the HeavyKeeper algorithm.
* [triangolatte](https://github.com/tchayen/triangolatte) ⭐ 36 | 🐛 4 | 🌐 Go | 📅 2021-08-04 - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

**[⬆ back to top](#contents)**

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) ⭐ 2,078 | 🐛 72 | 🌐 Go | 📅 2023-05-27 - ACME (Let's Encrypt) client tool with automatic renewal.
* [acopw-go](https://sr.ht/~jamesponddotco/acopw-go/) - Small cryptographically secure password generator package for Go.
* [acra](https://github.com/cossacklabs/acra) ⭐ 1,405 | 🐛 13 | 🌐 Go | 📅 2025-04-17 - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
* [age](https://github.com/FiloSottile/age) ⭐ 19,155 | 🐛 43 | 🌐 Go | 📅 2025-06-15 - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
* [argon2-hashing](https://github.com/andskur/argon2-hashing) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2025-05-13 - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
* [argon2pw](https://github.com/raja/argon2pw) ⚠️ Archived - Argon2 password hash generation with constant-time password comparison.
* [autocert](https://pkg.go.dev/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [BadActor](https://github.com/jaredfolkins/badactor) ⭐ 324 | 🐛 0 | 🌐 Go | 📅 2020-05-28 - In-memory, application-driven jailer built in the spirit of fail2ban.
* [beelzebub](https://github.com/mariocandela/beelzebub) ⭐ 1,190 | 🐛 1 | 🌐 Go | 📅 2025-07-01 - A secure low code honeypot framework, leveraging AI for System Virtualization.
* [booster](https://github.com/anatol/booster) ⭐ 569 | 🐛 73 | 🌐 Go | 📅 2025-03-15 - Fast initramfs generator with full-disk encryption support.
* [Cameradar](https://github.com/Ullaakut/cameradar) ⭐ 4,451 | 🐛 28 | 🌐 Go | 📅 2024-10-11 - Tool and library to remotely hack RTSP streams from surveillance cameras.
* [certificates](https://github.com/mvmaasakkers/certificates) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2022-12-27 - An opinionated tool for generating tls certificates.
* [CertMagic](https://github.com/caddyserver/certmagic) ⭐ 5,267 | 🐛 25 | 🌐 Go | 📅 2025-07-02 - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal.
* [Coraza](https://github.com/corazawaf/coraza) ⭐ 2,728 | 🐛 93 | 🌐 Go | 📅 2025-07-01 - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library.
* [dongle](https://github.com/golang-module/dongle) ⭐ 986 | 🐛 2 | 🌐 Go | 📅 2025-06-30 - A simple, semantic and developer-friendly golang package for encoding\&decoding and encryption\&decryption.
* [encid](https://github.com/bobg/encid) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2024-02-20 - Encode and decode encrypted integer IDs.
* [entpassgen](https://github.com/andreimerlescu/entpassgen) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2024-09-20 - Entropy Password Generator with extensive command line arguments to generate random strings securely including digits, passwords, and passwords built using obscure dictionary words mixed with symbols and digits.
* [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) ⭐ 341 | 🐛 3 | 🌐 Go | 📅 2024-01-13 - A rest application to dynamically update firewalld rules on a linux server.
* [go-generate-password](https://github.com/m1/go-generate-password) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2022-04-17 - Password generator that can be used on the cli or as a library.
* [go-htpasswd](https://github.com/tg123/go-htpasswd) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2025-04-15 - Apache htpasswd Parser for Go.
* [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) ⭐ 535 | 🐛 5 | 🌐 Go | 📅 2022-09-22 - Password validator based on raw cryptographic entropy values.
* [go-peer](https://github.com/number571/go-peer) ⭐ 294 | 🐛 0 | 🌐 Go | 📅 2025-04-30 - A software library for creating secure and anonymous decentralized systems.
* [go-yara](https://github.com/hillu/go-yara) ⭐ 372 | 🐛 8 | 🌐 Go | 📅 2025-07-01 - Go Bindings for [YARA](https://github.com/plusvic/yara) ⭐ 138 | 🐛 1 | 🌐 C | 📅 2020-03-13, the "pattern matching swiss knife for malware researchers (and everyone else)".
* [goArgonPass](https://github.com/dwin/goArgonPass) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2020-12-11 - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) ⭐ 59 | 🐛 0 | 🌐 Go | 📅 2022-08-31 - A probably paranoid package for securely hashing and encrypting passwords.
* [Interpol](https://github.com/avahidi/interpol) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2022-05-29 - Rule-based data generator for fuzzing and penetration testing.
* [lego](https://github.com/go-acme/lego) ⭐ 8,699 | 🐛 158 | 🌐 Go | 📅 2025-07-02 - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [luks.go](https://github.com/anatol/luks.go) ⭐ 90 | 🐛 3 | 🌐 Go | 📅 2025-03-16 - Pure Golang library to manage LUKS partitions.
* [memguard](https://github.com/awnumar/memguard) ⭐ 2,641 | 🐛 8 | 🌐 Go | 📅 2024-04-26 - A pure Go library for handling sensitive values in memory.
* [multikey](https://github.com/adrianosela/multikey) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2024-05-20 - An n-out-of-N keys encryption/decryption framework based on Shamir's Secret Sharing algorithm.
* [nacl](https://github.com/kevinburke/nacl) ⭐ 547 | 🐛 5 | 🌐 Go | 📅 2025-05-18 - Go implementation of the NaCL set of API's.
* [optimus-go](https://github.com/pjebs/optimus-go) ⭐ 360 | 🐛 1 | 🌐 Go | 📅 2020-05-04 - ID hashing and Obfuscation using Knuth's Algorithm.
* [passlib](https://github.com/hlandau/passlib) ⭐ 293 | 🐛 3 | 🌐 Go | 📅 2021-03-23 - Futureproof password hashing library.
* [passwap](https://github.com/zitadel/passwap) ⭐ 66 | 🐛 1 | 🌐 Go | 📅 2025-06-10 - Provides a unified implementation between different password hashing algorithms
* [qrand](https://github.com/bitfield/qrand) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2024-02-08 - Client for the ANU Quantum Numbers (AQN) API, providing quantum-mechanically secure random data.
* [secret](https://github.com/rsjethani/secret) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2024-08-16 - Prevent your secrets from leaking into logs, std\* etc.
* [secure](https://github.com/unrolled/secure) ⭐ 2,311 | 🐛 0 | 🌐 Go | 📅 2024-10-22 - HTTP middleware for Go that facilitates some quick security wins.
* [secureio](https://github.com/xaionaro-go/secureio) ⭐ 34 | 🐛 1 | 🌐 Go | 📅 2020-06-28 - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) ⭐ 200 | 🐛 3 | 🌐 Go | 📅 2021-04-12 - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) ⭐ 471 | 🐛 0 | 🌐 Rust | 📅 2025-04-07 - encrypt/decrypt using ssh keys.
* [sslmgr](https://github.com/adrianosela/sslmgr) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2025-06-02 - SSL certificates made easy with a high level wrapper around acme/autocert.
* [teler-waf](https://github.com/kitabisa/teler-waf) ⭐ 380 | 🐛 8 | 🌐 Go | 📅 2025-03-18 - teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications.
* [themis](https://github.com/cossacklabs/themis) ⭐ 1,924 | 🐛 31 | 🌐 C | 📅 2024-09-12 - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.

**[⬆ back to top](#contents)**

## Serialization

*Libraries and tools for binary serialization.*

* [bambam](https://github.com/glycerine/bambam) ⭐ 65 | 🐛 3 | 🌐 Go | 📅 2016-10-07 - generator for Cap'n Proto schemas from go.
* [bel](https://github.com/32leaves/bel) ⭐ 44 | 🐛 4 | 🌐 Go | 📅 2024-08-01 - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
* [binstruct](https://github.com/ghostiam/binstruct) ⭐ 106 | 🐛 1 | 🌐 Go | 📅 2024-10-01 - Golang binary decoder for mapping data into the structure.
* [cbor](https://github.com/fxamacker/cbor) ⭐ 890 | 🐛 24 | 🌐 Go | 📅 2025-07-01 - Small, safe, and easy CBOR encoding and decoding library.
* [colfer](https://github.com/pascaldekloe/colfer) ⭐ 749 | 🐛 10 | 🌐 Java | 📅 2024-08-07 - Code generation for the Colfer binary format.
* [csvutil](https://github.com/jszwec/csvutil) ⭐ 988 | 🐛 1 | 🌐 Go | 📅 2025-03-15 - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
* [elastic](https://github.com/epiclabs-io/elastic) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2021-05-21 - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
* [fixedwidth](https://github.com/huydang284/fixedwidth) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2019-12-20 - Fixed-width text formatting (UTF-8 supported).
* [fwencoder](https://github.com/o1egl/fwencoder) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2025-02-11 - Fixed width file parser (encoding and decoding library) for Go.
* [go-capnproto](https://github.com/glycerine/go-capnproto) ⭐ 288 | 🐛 1 | 🌐 Go | 📅 2020-01-29 - Cap'n Proto library and parser for go.
* [go-codec](https://github.com/ugorji/go) ⭐ 1,896 | 🐛 2 | 🌐 Go | 📅 2025-06-17 - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [go-csvlib](https://github.com/tiendc/go-csvlib) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2024-10-11 - High level and rich functionalities CSV serialization/deserialization library.
* [gogoprotobuf](https://github.com/gogo/protobuf) ⭐ 5,687 | 🐛 234 | 🌐 Go | 📅 2023-07-27 - Protocol Buffers for Go with Gadgets.
* [goprotobuf](https://github.com/golang/protobuf) ⭐ 9,966 | 🐛 115 | 🌐 Go | 📅 2024-08-05 - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [gotiny](https://github.com/raszia/gotiny) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2024-01-28 - Efficient Go serialization library, gotiny is almost as fast as serialization libraries that generate code.
* [jsoniter](https://github.com/json-iterator/go) ⭐ 13,797 | 🐛 267 | 🌐 Go | 📅 2024-05-27 - High-performance 100% compatible drop-in replacement of "encoding/json".
* [mapstructure](https://github.com/mitchellh/mapstructure) ⚠️ Archived - Go library for decoding generic map values into native Go structures.
* [php\_session\_decoder](https://github.com/yvasiyarov/php_session_decoder) ⭐ 167 | 🐛 3 | 🌐 Go | 📅 2018-11-02 - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [pletter](https://github.com/vimeda/pletter) ⭐ 19 | 🐛 7 | 🌐 Go | 📅 2025-06-16 - A standard way to wrap a proto message for message brokers.
* [structomap](https://github.com/tuvistavie/structomap) ⭐ 144 | 🐛 0 | 🌐 Go | 📅 2019-05-24 - Library to easily and dynamically generate maps from static structures.
* [unitpacking](https://github.com/recolude/unitpacking) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2023-07-08 - Library to pack unit vectors into as fewest bytes as possible.

**[⬆ back to top](#contents)**

## Server Applications

* [algernon](https://github.com/xyproto/algernon) ⭐ 2,921 | 🐛 28 | 🌐 Go | 📅 2025-06-27 - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [Caddy](https://github.com/caddyserver/caddy) ⭐ 65,264 | 🐛 220 | 🌐 Go | 📅 2025-07-01 - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [Clace](https://github.com/claceio/clace) ⭐ 635 | 🐛 2 | 🌐 Go | 📅 2025-06-11 - Clace makes internal tool deployment and management easy by implementing an app server for containerized webapps.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) ⭐ 123 | 🐛 2 | 🌐 Go | 📅 2025-06-04 - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
* [devd](https://github.com/cortesi/devd) ⭐ 3,457 | 🐛 30 | 🌐 Go | 📅 2024-05-01 - Local webserver for developers.
* [discovery](https://github.com/Bilibili/discovery) ⭐ 1,795 | 🐛 26 | 🌐 Go | 📅 2023-07-16 - A registry for resilient mid-tier load balancing and failover.
* [dudeldu](https://github.com/krotik/dudeldu) ⭐ 145 | 🐛 0 | 🌐 Go | 📅 2019-09-22 - A simple SHOUTcast server.
* [Easegress](https://github.com/megaease/easegress) ⭐ 5,835 | 🐛 20 | 🌐 Go | 📅 2025-07-02 - A cloud native high availability/performance traffic orchestration system with observability and extensibility.
* [Engity's Bifröst](https://bifroest.engity.org/) - Highly customizable SSH server with several ways to authorize a user how to execute its session (local or in containers).
* [etcd](https://github.com/etcd-io/etcd) ⭐ 49,741 | 🐛 322 | 🌐 Go | 📅 2025-07-02 - Highly-available key value store for shared configuration and service discovery.
* [Euterpe](https://github.com/ironsmile/euterpe) ⭐ 556 | 🐛 12 | 🌐 Go | 📅 2025-06-07 - Self-hosted music streaming server with built-in web UI and REST API.
* [Fider](https://github.com/getfider/fider) ⭐ 3,583 | 🐛 52 | 🌐 Go | 📅 2025-07-01 - Fider is an open platform to collect and organize customer feedback.
* [Flagr](https://github.com/checkr/flagr) ⭐ 2,504 | 🐛 5 | 🌐 Go | 📅 2025-06-23 - Flagr is an open-source feature flagging and A/B testing service.
* [flipt](https://github.com/markphelps/flipt) ⭐ 4,447 | 🐛 48 | 🌐 Go | 📅 2025-07-02 - A self contained feature flag solution written in Go and Vue.js
* [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) ⭐ 1,685 | 🐛 20 | 🌐 Go | 📅 2025-07-02 - A simple, complete and lightweight self-hosted feature flag solution 100% Open Source.
* [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) ⭐ 143 | 🐛 40 | 🌐 Go | 📅 2025-06-15 - Simple Reverse Proxy with Caching, written in Go, using Redis.
* [gondola](https://github.com/bmf-san/gondola) ⭐ 9 | 🐛 10 | 🌐 Go | 📅 2025-04-19 - A YAML based golang reverse proxy.
* [lets-proxy2](https://github.com/rekby/lets-proxy2) ⭐ 100 | 🐛 42 | 🌐 Go | 📅 2024-04-01 - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
* [minio](https://github.com/minio/minio) ⭐ 53,484 | 🐛 51 | 🌐 Go | 📅 2025-07-01 - Minio is a distributed object storage server.
* [Moxy](https://github.com/sinhashubham95/moxy) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2022-05-17 - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint.
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2020-09-16 - Nginx log parser and exporter to Prometheus.
* [nsq](https://nsq.io/) - A realtime distributed messaging platform.
* [pocketbase](https://github.com/pocketbase/pocketbase) ⭐ 48,067 | 🐛 18 | 🌐 Go | 📅 2025-06-29 - PocketBase is a realtime backend in 1 file consisting of embedded database (SQLite) with realtime subscriptions, built-in auth management and much more.
* [protoxy](https://github.com/camgraff/protoxy) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2020-11-08 - A proxy server that converts JSON request bodies to Protocol Buffers.
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) ⭐ 60 | 🐛 2 | 🌐 Go | 📅 2020-03-10 - Stream database events from PostgreSQL to Kafka.
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2019-10-29 - Relay to load-balance Riemann events and/or convert them to Carbon.
* [RoadRunner](https://github.com/spiral/roadrunner) ⭐ 8,178 | 🐛 78 | 🌐 Go | 📅 2025-07-02 - High-performance PHP application server, load-balancer and process manager.
* [SFTPGo](https://github.com/drakkan/sftpgo) ⭐ 10,644 | 🐛 112 | 🌐 Go | 📅 2025-06-22 - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
* [Trickster](https://github.com/tricksterproxy/trickster) ⭐ 2,031 | 🐛 43 | 🌐 Go | 📅 2025-06-30 - HTTP reverse proxy cache and time series accelerator.
* [wd-41](https://github.com/baalimago/wd-41) ⭐ 149 | 🐛 0 | 🌐 Go | 📅 2024-11-30 - A (w)eb (d)evelopment server with automatic live-reload on file changes.
* [Wish](https://github.com/charmbracelet/wish) ⭐ 4,180 | 🐛 14 | 🌐 Go | 📅 2025-06-23 - Make SSH apps, just like that!

**[⬆ back to top](#contents)**

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

* [go-etl](https://github.com/Breeze0806/go-etl) ⭐ 149 | 🐛 1 | 🌐 Go | 📅 2025-06-30 - A lightweight toolkit for data source extraction, transformation, and loading (ETL).
* [go-streams](https://github.com/reugn/go-streams) ⭐ 2,052 | 🐛 4 | 🌐 Go | 📅 2025-05-11 - Go stream processing library.
* [goio](https://github.com/primetalk/goio) ⭐ 86 | 🐛 8 | 🌐 Go | 📅 2023-06-29 - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2.
* [machine](https://github.com/whitaker-io/machine) ⭐ 162 | 🐛 7 | 🌐 Go | 📅 2025-06-27 - Go library for writing and generating stream workers with built in metrics and traceability.
* [nibbler](https://github.com/naughtygopher/nibbler) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-05-26 - A lightweight package for micro batch processing.
* [stream](https://github.com/youthlin/stream) ⭐ 95 | 🐛 1 | 🌐 Go | 📅 2024-02-08 - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

**[⬆ back to top](#contents)**

## Template Engines

*Libraries and tools for templating and lexing.*

* [ego](https://github.com/benbjohnson/ego) ⭐ 584 | 🐛 10 | 🌐 Go | 📅 2023-03-15 - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [extemplate](https://git.sr.ht/~dvko/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
* [fasttemplate](https://github.com/valyala/fasttemplate) ⭐ 874 | 🐛 12 | 🌐 Go | 📅 2023-08-28 - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/).
* [gomponents](https://www.gomponents.com) - HTML 5 components in pure Go, that look something like this: `func(name string) g.Node { return Div(Class("headline"), g.Textf("Hi %v!", name)) }`.
* [got](https://github.com/goradd/got) ⭐ 37 | 🐛 2 | 🌐 Go | 📅 2024-12-20 - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more.
* [goview](https://github.com/foolin/goview) ⭐ 453 | 🐛 15 | 🌐 Go | 📅 2023-10-29 - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
* [htmgo](https://htmgo.dev) - build simple and scalable systems with go + htmx
* [jet](https://github.com/CloudyKit/jet) ⭐ 1,339 | 🐛 21 | 🌐 Go | 📅 2025-03-23 - Jet template engine.
* [liquid](https://github.com/osteele/liquid) ⭐ 308 | 🐛 29 | 🌐 Go | 📅 2025-06-01 - Go implementation of Shopify Liquid templates.
* [maroto](https://github.com/johnfercher/maroto) ⭐ 2,471 | 🐛 52 | 🌐 Go | 📅 2025-03-21 - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
* [pongo2](https://github.com/flosch/pongo2) ⭐ 2,958 | 🐛 72 | 🌐 Go | 📅 2024-08-14 - Django-like template-engine for Go.
* [quicktemplate](https://github.com/valyala/quicktemplate) ⭐ 3,230 | 🐛 40 | 🌐 Go | 📅 2024-07-21 - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [raymond](https://github.com/aymerick/raymond) ⚠️ Archived - Complete handlebars implementation in Go.
* [Razor](https://github.com/sipin/gorazor) ⭐ 870 | 🐛 2 | 🌐 Go | 📅 2025-03-28 - Razor view engine for Golang.
* [Soy](https://github.com/robfig/soy) ⭐ 175 | 🐛 6 | 🌐 Go | 📅 2024-03-19 - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [sprout](https://github.com/go-sprout/sprout) ⭐ 172 | 🐛 4 | 🌐 Go | 📅 2025-06-30 - Useful template functions for Go templates.
* [tbd](https://github.com/lucasepe/tbd) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2021-08-29 - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata.
* [templ](https://github.com/a-h/templ) ⭐ 9,436 | 🐛 70 | 🌐 Go | 📅 2025-07-02 - A HTML templating language that has great developer tooling.

**[⬆ back to top](#contents)**

## Testing

*Libraries for testing codebases and generating test data.*

### Testing Frameworks

* [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
* [arch-go](https://github.com/fdaines/arch-go) ⭐ 2 | 🐛 0 | 📅 2024-10-30 - Architecture testing tool for Go projects.
* [assert](https://github.com/go-playground/assert) ⭐ 65 | 🐛 2 | 🌐 Go | 📅 2022-09-12 - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
* [baloo](https://github.com/h2non/baloo) ⭐ 779 | 🐛 9 | 🌐 Go | 📅 2022-08-10 - Expressive and versatile end-to-end HTTP API testing made easy.
* [be](https://github.com/carlmjohnson/be) ⭐ 109 | 🐛 1 | 🌐 Go | 📅 2025-01-14 - The minimalist generic test assertion library.
* [biff](https://github.com/fulldump/biff) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2023-01-11 - Bifurcation testing framework, BDD compatible.
* [charlatan](https://github.com/percolate/charlatan) ⭐ 204 | 🐛 2 | 🌐 Go | 📅 2023-11-19 - Tool to generate fake interface implementations for tests.
* [commander](https://github.com/SimonBaeumer/commander) ⭐ 228 | 🐛 33 | 🌐 Go | 📅 2024-04-02 - Tool for testing cli applications on windows, linux and osx.
* [cupaloy](https://github.com/bradleyjkemp/cupaloy) ⭐ 318 | 🐛 14 | 🌐 Go | 📅 2023-05-19 - Simple snapshot testing addon for your test framework.
* [dbcleaner](https://github.com/khaiql/dbcleaner) ⭐ 164 | 🐛 0 | 🌐 Go | 📅 2021-11-10 - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
* [dft](https://github.com/abecodes/dft) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2025-01-25 - Lightweight, zero dependency docker containers for testing (or more).
* [dsunit](https://github.com/viant/dsunit) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2025-05-25 - Datastore testing for SQL, NoSQL, structured files.
* [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) ⭐ 972 | 🐛 7 | 🌐 Go | 📅 2025-06-02 - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
* [endly](https://github.com/viant/endly) ⭐ 267 | 🐛 3 | 🌐 Go | 📅 2025-04-28 - Declarative end to end functional testing.
* [envite](https://github.com/PerimeterX/envite) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2025-06-20 - Dev and testing environment management framework.
* [fixenv](https://github.com/rekby/fixenv) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2024-08-09 - Fixture manage engine, inspired by pytest fixtures.
* [flute](https://github.com/suzuki-shunsuke/flute) ⭐ 20 | 🐛 3 | 🌐 Go | 📅 2025-07-02 - HTTP client testing framework.
* [frisby](https://github.com/verdverm/frisby) ⭐ 276 | 🐛 12 | 🌐 Go | 📅 2020-03-03 - REST API testing framework.
* [gherkingen](https://github.com/hedhyw/gherkingen) ⭐ 82 | 🐛 1 | 🌐 Go | 📅 2024-12-29 - BDD boilerplate generator and framework.
* [ginkgo](https://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
* [gnomock](https://github.com/orlangure/gnomock) ⭐ 1,444 | 🐛 27 | 🌐 Go | 📅 2025-06-26 - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
* [go-carpet](https://github.com/msoap/go-carpet) ⭐ 248 | 🐛 3 | 🌐 Go | 📅 2024-09-30 - Tool for viewing test coverage in terminal.
* [go-cmp](https://github.com/google/go-cmp) ⭐ 4,448 | 🐛 46 | 🌐 Go | 📅 2025-02-21 - Package for comparing Go values in tests.
* [go-hit](https://github.com/Eun/go-hit) ⭐ 260 | 🐛 13 | 🌐 Go | 📅 2024-07-08 - Hit is an http integration test framework written in golang.
* [go-mutesting](https://github.com/zimmski/go-mutesting) ⭐ 656 | 🐛 45 | 🌐 Go | 📅 2024-07-04 - Mutation testing for Go source code.
* [go-mysql-test-container](https://github.com/arikama/go-mysql-test-container) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2022-09-30 - Golang MySQL testcontainer to help with MySQL integration testing.
* [go-snaps](http://github.com/gkampitakis/go-snaps) ⭐ 217 | 🐛 7 | 🌐 Go | 📅 2025-06-04 - Jest-like snapshot testing in Golang.
* [go-testdeep](https://github.com/maxatome/go-testdeep) ⭐ 448 | 🐛 4 | 🌐 Go | 📅 2025-04-17 - Extremely flexible golang deep comparison, extends the go testing package.
* [go-testpredicate](https://github.com/maargenton/go-testpredicate) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2024-11-12 - Test predicate style assertions library with extensive diagnostics output.
* [go-vcr](https://github.com/dnaeon/go-vcr) ⭐ 1,311 | 🐛 4 | 🌐 Go | 📅 2025-06-27 - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
* [goblin](https://github.com/franela/goblin) ⭐ 890 | 🐛 21 | 🌐 Go | 📅 2022-12-22 - Mocha like testing framework of Go.
* [goc](https://github.com/qiniu/goc) ⭐ 861 | 🐛 90 | 🌐 Go | 📅 2024-11-15 - Goc is a comprehensive coverage testing system for The Go Programming Language.
* [gocheck](https://labix.org/gocheck) - More advanced testing framework alternative to gotest.
* [GoConvey](https://github.com/smartystreets/goconvey/) ⭐ 8,361 | 🐛 167 | 🌐 Go | 📅 2024-07-30 - BDD-style framework with web UI and live reload.
* [gocrest](https://github.com/corbym/gocrest) ⭐ 106 | 🐛 2 | 🌐 Go | 📅 2024-09-06 - Composable hamcrest-like matchers for Go assertions.
* [godog](https://github.com/cucumber/godog) ⭐ 2,455 | 🐛 83 | 🌐 Go | 📅 2025-06-13 - Cucumber BDD framework for Go.
* [gofight](https://github.com/appleboy/gofight) ⭐ 440 | 🐛 6 | 🌐 Go | 📅 2025-05-05 - API Handler Testing for Golang Router framework.
* [gogiven](https://github.com/corbym/gogiven) ⭐ 15 | 🐛 4 | 🌐 Go | 📅 2023-04-03 - YATSPEC-like BDD testing framework for Go.
* [gomatch](https://github.com/jfilipczyk/gomatch) ⭐ 48 | 🐛 0 | 🌐 Go | 📅 2021-01-15 - library created for testing JSON against patterns.
* [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
* [Gont](https://github.com/stv0g/gont) ⭐ 83 | 🐛 11 | 🌐 Go | 📅 2025-06-30 - Go network testing toolkit for testing building complex network topologies using Linux namespaces.
* [gospecify](https://github.com/stesla/gospecify) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2011-10-18 - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
* [gosuite](https://github.com/pavlo/gosuite) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2016-10-18 - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
* [got](https://github.com/ysmood/got) ⭐ 269 | 🐛 2 | 🌐 Go | 📅 2025-05-30 - An enjoyable golang test framework.
* [gotest.tools](https://github.com/gotestyourself/gotest.tools) ⭐ 563 | 🐛 30 | 🌐 Go | 📅 2025-02-08 - A collection of packages to augment the go testing package and support common patterns.
* [Hamcrest](https://github.com/rdrdr/hamcrest) ⭐ 30 | 🐛 2 | 🌐 Go | 📅 2021-01-07 - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
* [httpexpect](https://github.com/gavv/httpexpect) ⭐ 2,650 | 🐛 16 | 🌐 Go | 📅 2025-06-02 - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
* [is](https://github.com/matryer/is) ⭐ 1,900 | 🐛 7 | 🌐 Go | 📅 2024-02-08 - Professional lightweight testing mini-framework for Go.
* [jsonassert](https://github.com/kinbiko/jsonassert) ⭐ 138 | 🐛 5 | 🌐 Go | 📅 2024-10-03 - Package for verifying that your JSON payloads are serialized correctly.
* [keploy](https://github.com/keploy/keploy) ⭐ 10,284 | 🐛 238 | 🌐 Go | 📅 2025-07-02 - Generate Testcase and Data Mocks from API calls automatically.
* [omg.testingtools](https://github.com/dedalqq/omg.testingtools) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2021-10-14 - The simple library for change a values of private fields for testing.
* [restit](https://github.com/yookoala/restit) ⭐ 55 | 🐛 6 | 🌐 Go | 📅 2025-04-16 - Go micro framework to help writing RESTful API integration test.
* [schema](https://github.com/jgroeneveld/schema) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2019-10-13 - Quick and easy expression matching for JSON schemas used in requests and responses.
* [stop-and-go](https://github.com/elgohr/stop-and-go) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2024-11-25 - Testing helper for concurrency.
* [testcase](https://github.com/adamluzsi/testcase) ⭐ 123 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - Idiomatic testing framework for Behavior Driven Development.
* [testcerts](https://github.com/madflojo/testcerts) ⭐ 74 | 🐛 1 | 🌐 Go | 📅 2024-12-30 - Dynamically generate self-signed certificates and certificate authorities within your test functions.
* [testcontainers-go](https://github.com/testcontainers/testcontainers-go) ⭐ 4,164 | 🐛 143 | 🌐 Go | 📅 2025-07-01 - A Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done.
* [testfixtures](https://github.com/go-testfixtures/testfixtures) ⭐ 1,164 | 🐛 20 | 🌐 Go | 📅 2025-06-29 - A helper for Rails' like test fixtures to test database applications.
* [Testify](https://github.com/stretchr/testify) ⭐ 24,862 | 🐛 370 | 🌐 Go | 📅 2025-07-01 - Sacred extension to the standard go testing package.
* [testsql](https://github.com/zhulongcheng/testsql) ⭐ 17 | 🐛 3 | 🌐 Go | 📅 2019-09-26 - Generate test data from SQL files before testing and clear it after finished.
* [testza](https://github.com/MarvinJWendt/testza) ⭐ 421 | 🐛 9 | 🌐 Go | 📅 2023-08-21 - Full-featured test framework with nice colorized output.
* [trial](https://github.com/jgroeneveld/trial) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2022-10-05 - Quick and easy extendable assertions without introducing much boilerplate.
* [Tt](https://github.com/vcaesar/tt) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2025-05-18 - Simple and colorful test tools.
* [wstest](https://github.com/posener/wstest) ⭐ 102 | 🐛 1 | 🌐 Go | 📅 2020-12-30 - Websocket client for unit-testing a websocket http.Handler.

### Mock

* [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) ⭐ 1,052 | 🐛 28 | 🌐 Go | 📅 2025-06-06 - Tool for generating self-contained mock objects.
* [genmock](https://gitlab.com/so_literate/genmock) - Go mocking system with code generator for building calls of the interface methods.
* [go-localstack](https://github.com/elgohr/go-localstack) ⭐ 83 | 🐛 2 | 🌐 Go | 📅 2025-06-30 - Tool for using localstack in AWS testing.
* [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) ⭐ 6,389 | 🐛 41 | 🌐 Go | 📅 2024-09-11 - Mock SQL driver for testing database interactions.
* [go-txdb](https://github.com/DATA-DOG/go-txdb) ⭐ 720 | 🐛 2 | 🌐 Go | 📅 2025-03-11 - Single transaction based database driver mainly for testing purposes.
* [gock](https://github.com/h2non/gock) ⭐ 2,180 | 🐛 47 | 🌐 Go | 📅 2024-09-24 - Versatile HTTP mocking made easy.
* [gomock](https://github.com/uber-go/mock) ⭐ 2,882 | 🐛 95 | 🌐 Go | 📅 2025-07-01 - Mocking framework for the Go programming language.
* [govcr](https://github.com/seborama/govcr) ⭐ 188 | 🐛 0 | 🌐 Go | 📅 2025-06-16 - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
* [hoverfly](https://github.com/SpectoLabs/hoverfly) ⭐ 2,421 | 🐛 34 | 🌐 Go | 📅 2025-06-18 - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
* [httpmock](https://github.com/jarcoal/httpmock) ⭐ 2,035 | 🐛 5 | 🌐 Go | 📅 2025-04-05 - Easy mocking of HTTP responses from external resources.
* [minimock](https://github.com/gojuno/minimock) ⭐ 691 | 🐛 9 | 🌐 Go | 📅 2025-06-10 - Mock generator for Go interfaces.
* [mockery](https://github.com/vektra/mockery) ⭐ 6,665 | 🐛 39 | 🌐 Go | 📅 2025-06-27 - Tool to generate Go interfaces.
* [mockhttp](https://github.com/tv42/mockhttp) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2014-10-29 - Mock object for Go http.ResponseWriter.
* [mooncake](https://github.com/GuilhermeCaruso/mooncake) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2022-09-18 - A simple way to generate mocks for multiple purposes.
* [moq](https://github.com/matryer/moq) ⭐ 2,102 | 🐛 27 | 🌐 Go | 📅 2025-02-13 - Utility that generates a struct from any interface. The struct can be used in test code as a mock of the interface.
* [pgxmock](https://github.com/pashagolub/pgxmock) ⭐ 486 | 🐛 0 | 🌐 Go | 📅 2025-06-19 - A mock library implementing [pgx - PostgreSQL Driver and Toolkit](https://github.com/jackc/pgx/) ⭐ 12,075 | 🐛 231 | 🌐 Go | 📅 2025-06-26.
* [timex](https://github.com/cabify/timex) ⭐ 71 | 🐛 1 | 🌐 Go | 📅 2020-08-03 - A test-friendly replacement for the native `time` package.
* [xgo](https://github.com/xhd2015/xgo) ⭐ 407 | 🐛 59 | 🌐 Go | 📅 2025-07-01 - A general pureposed function mocking library.

### Fuzzing and delta-debugging/reducing/shrinking

* [go-fuzz](https://github.com/dvyukov/go-fuzz) ⭐ 4,833 | 🐛 58 | 🌐 Go | 📅 2024-09-24 - Randomized testing system.
* [gofuzz](https://github.com/google/gofuzz) ⚠️ Archived - Library for populating go objects with random values.
* [Tavor](https://github.com/zimmski/tavor) ⭐ 247 | 🐛 53 | 🌐 Go | 📅 2018-10-31 - Generic fuzzing and delta-debugging framework.

### Selenium and browser control tools

* [cdp](https://github.com/mafredri/cdp) ⭐ 754 | 🐛 17 | 🌐 Go | 📅 2024-11-09 - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
* [chromedp](https://github.com/knq/chromedp) ⭐ 11,981 | 🐛 146 | 🌐 Go | 📅 2025-06-20 - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
* [ggr](https://github.com/aerokube/ggr) ⚠️ Archived - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
* [playwright-go](https://github.com/mxschmitt/playwright-go) ⭐ 2,760 | 🐛 54 | 🌐 Go | 📅 2025-05-09 - browser automation library to control Chromium, Firefox and WebKit with a single API.
* [rod](https://github.com/go-rod/rod) ⭐ 6,042 | 🐛 183 | 🌐 Go | 📅 2024-12-07 - A Devtools driver to make web automation and scraping easy.
* [selenoid](https://github.com/aerokube/selenoid) ⚠️ Archived - alternative Selenium hub server that launches browsers within containers.

### Fail injection

* [failpoint](https://github.com/pingcap/failpoint) ⭐ 852 | 🐛 8 | 🌐 Go | 📅 2024-05-28 - An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

**[⬆ back to top](#contents)**

## Text Processing

*Libraries for parsing and manipulating texts.*

See also [Natural Language Processing](#natural-language-processing) and [Text Analysis](#text-analysis).

### Formatters

* [address](https://github.com/bojanz/address) ⭐ 77 | 🐛 0 | 🌐 Go | 📅 2025-03-28 - Handles address representation, validation and formatting.
* [align](https://github.com/Guitarbum722/align) ⭐ 84 | 🐛 0 | 🌐 Go | 📅 2021-09-12 - A general purpose application that aligns text.
* [bytes](https://github.com/labstack/gommon/tree/master/bytes) ⭐ 553 | 🐛 12 | 🌐 Go | 📅 2023-12-20 - Formats and parses numeric byte values (10K, 2M, 3G, etc.).
* [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) ⭐ 86 | 🐛 8 | 🌐 Go | 📅 2024-02-08 - Fixed-width text formatting (encoder/decoder with reflection).
* [go-humanize](https://github.com/dustin/go-humanize) ⭐ 4,572 | 🐛 41 | 🌐 Go | 📅 2025-07-01 - Formatters for time, numbers, and memory size to human readable format.
* [gotabulate](https://github.com/bndr/gotabulate) ⭐ 337 | 🐛 5 | 🌐 Go | 📅 2021-02-09 - Easily pretty-print your tabular data with Go.
* [sq](https://github.com/neilotoole/sq) ⭐ 2,303 | 🐛 31 | 🌐 Go | 📅 2025-04-16 - Convert data from SQL databases or document formats like CSV or Excel into formats such as JSON, Excel, CSV, HTML, Markdown, XML, and YAML.
* [textwrap](https://github.com/isbm/textwrap) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2019-08-03 - Wraps text at end of lines. Implementation of `textwrap` module from Python.

### Markup Languages

* [bafi](https://github.com/mmalcek/bafi) ⭐ 107 | 🐛 0 | 🌐 Go | 📅 2025-03-08 - Universal JSON, BSON, YAML, XML translator to ANY format using templates.
* [bbConvert](https://github.com/CalebQ42/bbConvert) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2024-12-27 - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
* [blackfriday](https://github.com/russross/blackfriday) ⭐ 5,560 | 🐛 218 | 🌐 Go | 📅 2024-01-29 - Markdown processor in Go.
* [go-output-format](https://github.com/drewstinnett/go-output-format) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2024-02-24 - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
* [go-toml](https://github.com/pelletier/go-toml) ⭐ 1,829 | 🐛 33 | 🌐 Go | 📅 2025-05-10 - Go library for the TOML format with query support and handy cli tools.
* [goldmark](https://github.com/yuin/goldmark) ⭐ 4,156 | 🐛 8 | 🌐 Go | 📅 2025-06-13 - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured.
* [goq](https://github.com/andrewstuart/goq) ⭐ 267 | 🐛 3 | 🌐 Go | 📅 2021-09-02 - Declarative unmarshalling of HTML using struct tags with jQuery syntax (uses GoQuery).
* [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) ⭐ 2,906 | 🐛 15 | 🌐 Go | 📅 2025-06-09 - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
* [htmlquery](https://github.com/antchfx/htmlquery) ⭐ 768 | 🐛 8 | 🌐 Go | 📅 2025-06-10 - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
* [htmlyaml](https://github.com/nikolaydubina/htmlyaml) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2024-08-22 -  Rich rendering of YAML as HTML in Go
* [htree](https://github.com/bobg/htree) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-01-14 - Traverse, navigate, filter, and otherwise process trees of [html.Node](https://pkg.go.dev/golang.org/x/net/html#Node) objects.
* [mxj](https://github.com/clbanning/mxj) ⭐ 627 | 🐛 2 | 🌐 Go | 📅 2024-04-03 - Encode / decode XML as JSON or map\[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
* [toml](https://github.com/BurntSushi/toml) ⭐ 4,753 | 🐛 17 | 🌐 Go | 📅 2025-06-06 - TOML configuration format (encoder/decoder with reflection).

### Parsers/Encoders/Decoders

* [allot](https://github.com/sbstjn/allot) ⭐ 59 | 🐛 3 | 🌐 Go | 📅 2022-01-31 - Placeholder and wildcard text parsing for CLI tools and bots.
* [codetree](https://github.com/aerogo/codetree) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2019-10-26 - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
* [commonregex](https://github.com/mingrammer/commonregex) ⭐ 900 | 🐛 2 | 🌐 Go | 📅 2019-11-12 - A collection of common regular expressions for Go.
* [did](https://github.com/ockam-network/did) ⭐ 93 | 🐛 7 | 🌐 Go | 📅 2023-01-03 - DID (Decentralized Identifiers) Parser and Stringer in Go.
* [doi](https://github.com/hscells/doi) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2017-08-21 - Document object identifier (doi) parser in Go.
* [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) ⭐ 147 | 🐛 6 | 🌐 Go | 📅 2025-06-10 - Editorconfig file parser and manipulator for Go.
* [encdec](https://github.com/mickep76/encdec) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2019-11-12 - Package provides a generic interface to encoders and decoders.
* [go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2025-06-07 - High performance effective top level domains (eTLD) extraction module.
* [go-nmea](https://github.com/adrianmo/go-nmea) ⭐ 244 | 🐛 1 | 🌐 Go | 📅 2024-12-09 - NMEA parser library for the Go language.
* [go-querystring](https://github.com/google/go-querystring) ⭐ 2,054 | 🐛 20 | 🌐 Go | 📅 2025-06-23 - Go library for encoding structs into URL query parameters.
* [go-vcard](https://github.com/emersion/go-vcard) ⭐ 116 | 🐛 7 | 🌐 Go | 📅 2024-10-24 - Parse and format vCard.
* [godump](https://github.com/yassinebenaid/godump) ⭐ 215 | 🐛 1 | 🌐 Go | 📅 2025-05-16 - Pretty print any GO variable with ease, an alternative to Go's `fmt.Printf("%#v")`.
* [godump (goforj)](https://github.com/goforj/godump) ⭐ 1,255 | 🐛 10 | 🌐 Go | 📅 2025-06-30 - Pretty-print Go structs with Laravel/Symfony-style dumps, full type info, colorized CLI output, cycle detection, and private field access.
* [gofeed](https://github.com/mmcdole/gofeed) ⭐ 2,709 | 🐛 54 | 🌐 Go | 📅 2025-05-27 - Parse RSS and Atom feeds in Go.
* [gographviz](https://github.com/awalterschulze/gographviz) ⭐ 563 | 🐛 8 | 🌐 Go | 📅 2023-02-28 - Parses the Graphviz DOT language.
* [gonameparts](https://github.com/polera/gonameparts) ⭐ 43 | 🐛 2 | 🌐 Go | 📅 2024-10-04 - Parses human names into individual name parts.
* [ltsv](https://github.com/Wing924/ltsv) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-09-27 - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
* [normalize](https://github.com/avito-tech/normalize) ⭐ 52 | 🐛 0 | 🌐 Go | 📅 2021-04-01 - Sanitize, normalize and compare fuzzy text.
* [parseargs-go](https://github.com/nproc/parseargs-go) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2017-01-24 - string argument parser that understands quotes and backslashes.
* [parth](https://github.com/codemodus/parth) ⚠️ Archived - URL path segmentation parsing.
* [prattle](https://github.com/askeladdk/prattle) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2023-10-27 - Scan and parse LL(1) grammars simply and efficiently.
* [sdp](https://github.com/gortc/sdp) ⚠️ Archived - SDP: Session Description Protocol \[[RFC 4566](https://tools.ietf.org/html/rfc4566)].
* [sh](https://github.com/mvdan/sh) ⭐ 7,832 | 🐛 99 | 🌐 Go | 📅 2025-06-22 - Shell parser and formatter.
* [tokenizer](https://github.com/bzick/tokenizer) ⭐ 127 | 🐛 5 | 🌐 Go | 📅 2025-02-13 - Parse any string, slice or infinite buffer to any tokens.
* [vdf](https://github.com/andygrunwald/vdf) ⭐ 56 | 🐛 5 | 🌐 Go | 📅 2025-07-01 - A Lexer and Parser for Valves Data Format (known as vdf) written in Go.
* [when](https://github.com/olebedev/when) ⭐ 1,437 | 🐛 16 | 🌐 Go | 📅 2025-03-03 - Natural EN and RU language date/time parser with pluggable rules.
* [xj2go](https://github.com/stackerzzq/xj2go) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2021-10-12 - Convert xml or json to go struct.

### Regular Expressions

* [genex](https://github.com/alixaxel/genex) ⭐ 76 | 🐛 0 | 🌐 Go | 📅 2020-01-05 - Count and expand Regular Expressions into all matching Strings.
* [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) ⭐ 85 | 🐛 8 | 🌐 Go | 📅 2025-02-11 - Simple and lightweight wildcard pattern matching.
* [goregen](https://github.com/zach-klippenstein/goregen) ⭐ 92 | 🐛 5 | 🌐 Go | 📅 2022-05-18 - Library for generating random strings from regular expressions.
* [regroup](https://github.com/oriser/regroup) ⭐ 147 | 🐛 1 | 🌐 Go | 📅 2024-10-08 - Match regex expression named groups into go struct using struct tags and automatic parsing.
* [rex](https://github.com/hedhyw/rex) ⭐ 204 | 🐛 0 | 🌐 Go | 📅 2025-03-26 - Regular expressions builder.

### Sanitation

* [bluemonday](https://github.com/microcosm-cc/bluemonday) ⭐ 3,429 | 🐛 25 | 🌐 Go | 📅 2025-04-04 - HTML Sanitizer.
* [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) ⭐ 69 | 🐛 1 | 🌐 Go | 📅 2025-06-01 - A sanitization-based swear filter for Go.

### Scrapers

* [colly](https://github.com/asciimoo/colly) ⭐ 24,382 | 🐛 192 | 🌐 Go | 📅 2025-06-18 - Fast and Elegant Scraping Framework for Gophers.
* [dataflowkit](https://github.com/slotix/dataflowkit) ⭐ 688 | 🐛 4 | 🌐 Go | 📅 2023-03-07 - Web scraping Framework to turn websites into structured data.
* [go-recipe](https://github.com/kkyr/go-recipe) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2023-03-16 - A package for scraping recipes from websites.
* [go-sitemap-parser](https://github.com/aafeher/go-sitemap-parser) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-03-19 - Go language library for parsing Sitemaps.
* [GoQuery](https://github.com/PuerkitoBio/goquery) ⭐ 14,568 | 🐛 3 | 🌐 Go | 📅 2025-06-07 - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
* [pagser](https://github.com/foolin/pagser) ⭐ 108 | 🐛 8 | 🌐 Go | 📅 2023-10-15 - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
* [Tagify](https://github.com/zoomio/tagify) ⭐ 39 | 🐛 2 | 🌐 HTML | 📅 2024-07-18 - Produces a set of tags from given source.
* [walker](https://github.com/cyucelen/walker) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2023-02-17 - Seamlessly fetch paginated data from any source. Simple and high performance API scraping included.
* [xurls](https://github.com/mvdan/xurls) ⭐ 1,224 | 🐛 2 | 🌐 Go | 📅 2025-02-22 - Extract urls from text.

### RSS

* [podcast](https://github.com/eduncan911/podcast) ⭐ 135 | 🐛 6 | 🌐 Go | 📅 2020-11-04 - iTunes Compliant and RSS 2.0 Podcast Generator in Golang

### Utility/Miscellaneous

* [go-runewidth](https://github.com/mattn/go-runewidth) ⭐ 641 | 🐛 16 | 🌐 Go | 📅 2024-07-22 - Functions to get fixed width of the character or string.
* [go-zero-width](https://github.com/trubitsyn/go-zero-width) ⚠️ Archived - Zero-width character detection and removal for Go.
* [kace](https://github.com/codemodus/kace) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2018-08-26 - Common case conversions covering common initialisms.
* [petrovich](https://github.com/striker2000/petrovich) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2023-11-29 - Petrovich is the library which inflects Russian names to given grammatical case.
* [radix](https://github.com/yourbasic/radix) ⭐ 193 | 🐛 0 | 🌐 Go | 📅 2018-03-08 - Fast string sorting algorithm.
* [TySug](https://github.com/Dynom/TySug) ⭐ 19 | 🐛 2 | 🌐 Go | 📅 2023-03-07 - Alternative suggestions with respect to keyboard layouts.
* [w2vgrep](https://github.com/arunsupe/semantic-grep) ⭐ 1,168 | 🐛 0 | 🌐 Go | 📅 2024-08-19 - A semantic grep tool using word embeddings to find semantically similar matches. For example, searching for "death" will find "dead", "killing", "murder".

**[⬆ back to top](#contents)**

## Third-party APIs

*Libraries for accessing third party APIs.*

* [airtable](https://github.com/mehanizm/airtable) ⭐ 80 | 🐛 3 | 🌐 Go | 📅 2025-03-14 - Go client library for the [Airtable API](https://airtable.com/api).
* [anaconda](https://github.com/ChimeraCoder/anaconda) ⭐ 1,144 | 🐛 72 | 🌐 Go | 📅 2024-01-28 - Go client library for the Twitter 1.1 API.
* [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2024-01-26 - Unofficial Golang SDK for AppStore Connect API.
* [aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) ⭐ 21 | 🐛 19 | 🌐 Go | 📅 2025-06-19 - Unofficial Go SDK implementation of the [AWS Encryption SDK](https://docs.aws.amazon.com/encryption-sdk/latest/developer-guide/index.html).
* [aws-sdk-go](https://github.com/aws/aws-sdk-go-v2) ⭐ 3,129 | 🐛 81 | 🌐 Go | 📅 2025-07-02 - The official AWS SDK for the Go programming language.
* [bqwriter](https://github.com/OTA-Insight/bqwriter) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2023-09-11 - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout.
* [brewerydb](https://github.com/naegelejd/brewerydb) ⭐ 20 | 🐛 5 | 🌐 Go | 📅 2015-06-18 - Go library for accessing the BreweryDB API.
* [cachet](https://github.com/andygrunwald/cachet) ⭐ 90 | 🐛 1 | 🌐 Go | 📅 2021-06-22 - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) ⭐ 65 | 🐛 3 | 🌐 Go | 📅 2024-01-27 - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) ⭐ 55 | 🐛 8 | 🌐 Go | 📅 2024-10-10 - Go client library for interfacing with the Clarifai API.
* [codeship-go](https://github.com/codeship/codeship-go) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2020-11-03 - Go client library for interacting with Codeship's API v2.
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) ⭐ 25 | 🐛 2 | 🌐 Go | 📅 2025-02-12 - Go client library for interacting with Coinpaprika's API.
* [device-check-go](https://github.com/rinchsan/device-check-go) ⭐ 24 | 🐛 11 | 🌐 Go | 📅 2025-06-06 - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
* [discordgo](https://github.com/bwmarrin/discordgo) ⭐ 5,445 | 🐛 189 | 🌐 Go | 📅 2025-05-24 - Go bindings for the Discord Chat API.
* [disgo](https://github.com/switchupcb/disgo) ⭐ 103 | 🐛 5 | 🌐 Go | 📅 2025-03-14 - Go API Wrapper for the Discord API.
* [dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2022-12-06 - Unofficial Dusupay payment gateway API Client for Go
* [ethrpc](https://github.com/onrik/ethrpc) ⭐ 272 | 🐛 13 | 🌐 Go | 📅 2024-01-05 - Go bindings for Ethereum JSON RPC API.
* [facebook](https://github.com/huandu/facebook) ⭐ 1,379 | 🐛 0 | 🌐 Go | 📅 2025-06-16 - Go Library that supports the Facebook Graph API.
* [fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2022-06-16 - Unofficial Fasapay payment gateway XML API Client for Golang.
* [fcm](https://github.com/maddevsio/fcm) ⭐ 51 | 🐛 2 | 🌐 Go | 📅 2020-03-06 - Go library for Firebase Cloud Messaging.
* [gads](https://github.com/emiddleton/gads) ⭐ 51 | 🐛 8 | 🌐 Go | 📅 2021-12-13 - Google Adwords Unofficial API.
* [gcm](https://github.com/Aorioli/gcm) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2015-12-04 - Go library for Google Cloud Messaging.
* [geo-golang](https://github.com/codingsince1985/geo-golang) ⭐ 532 | 🐛 7 | 🌐 Go | 📅 2025-03-26 - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://developer.mapquest.com/documentation/api/geocoding/), [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [github](https://github.com/google/go-github) ⭐ 10,849 | 🐛 32 | 🌐 Go | 📅 2025-07-02 - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) ⭐ 1,153 | 🐛 43 | 🌐 Go | 📅 2024-07-27 - Go library for accessing the GitHub GraphQL API v4.
* [go-atlassian](https://github.com/ctreminiom/go-atlassian) ⭐ 166 | 🐛 15 | 🌐 Go | 📅 2025-07-03 - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud)
* [go-aws-news](https://github.com/circa10a/go-aws-news) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2024-06-21 - Go application and library to fetch what's new from AWS.
* [go-chronos](https://github.com/axelspringer/go-chronos) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2018-01-23 - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* [go-gerrit](https://github.com/andygrunwald/go-gerrit) ⭐ 100 | 🐛 24 | 🌐 Go | 📅 2025-06-14 - Go client library for [Gerrit Code Review](https://www.gerritcodereview.com/).
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2017-08-15 - Tiny Go client for HackerNews API.
* [go-here](https://github.com/abdullahselek/go-here) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2020-06-23 - Go client library around the HERE location based APIs.
* [go-hibp](https://github.com/wneessen/go-hibp) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2025-02-27 - Simple Go binding to the "Have I Been Pwned" APIs.
* [go-imgur](https://github.com/koffeinsource/go-imgur) ⭐ 23 | 🐛 4 | 🌐 Go | 📅 2024-07-03 - Go client library for [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) ⭐ 1,539 | 🐛 182 | 🌐 Go | 📅 2025-03-29 - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-lark](https://github.com/go-lark/lark) ⭐ 225 | 🐛 6 | 🌐 Go | 📅 2025-06-13 - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform.
* [go-marathon](https://github.com/gambol99/go-marathon) ⭐ 200 | 🐛 27 | 🌐 Go | 📅 2020-10-01 - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) ⭐ 41 | 🐛 3 | 🌐 Go | 📅 2024-04-24 - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2).
* [go-openai](https://github.com/sashabaranov/go-openai) ⭐ 10,124 | 🐛 211 | 🌐 Go | 📅 2025-06-25 - OpenAI ChatGPT, DALL·E, Whisper API library for Go.
* [go-openproject](https://github.com/manuelbcd/go-openproject) ⭐ 19 | 🐛 5 | 🌐 Go | 📅 2022-11-22 - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
* [go-postman-collection](https://github.com/rbretecher/go-postman-collection) ⭐ 84 | 🐛 2 | 🌐 Go | 📅 2024-05-17 - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
* [go-redoc](https://github.com/mvrilo/go-redoc) ⭐ 85 | 🐛 7 | 🌐 Go | 📅 2025-02-09 - Embedded OpenAPI/Swagger documentation ui for Go using [ReDoc](https://redocly.com/).
* [go-restcountries](https://github.com/chriscross0/go-restcountries) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2021-10-27 - Go library for the [REST Countries API](https://countrylayer.com/).
* [go-salesforce](https://github.com/k-capehart/go-salesforce) ⭐ 44 | 🐛 5 | 🌐 Go | 📅 2025-07-02 - Go client library for interacting with the [Salesforce REST API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm).
* [go-sophos](https://github.com/esurdam/go-sophos) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2022-05-06 - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
* [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2022-10-23 - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-trending](https://github.com/andygrunwald/go-trending) ⭐ 145 | 🐛 1 | 🌐 Go | 📅 2025-04-17 - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) ⭐ 76 | 🐛 10 | 🌐 Go | 📅 2023-04-14 - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2022-10-23 - Go client for the xkcd API.
* [go-yapla](https://gitlab.com/adrienK/go-yapla) - Go client library for the Yapla v2.0 API.
* [goagi](https://github.com/staskobzar/goagi) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-06-21 - Go library to build Asterisk PBX agi/fastagi applications.
* [goami2](https://github.com/staskobzar/goami2) ⭐ 17 | 🐛 2 | 🌐 Go | 📅 2025-03-14 - AMI v2 library for Asterisk PBX.
* [GoFreeDB](https://github.com/FreeLeh/GoFreeDB) ⭐ 87 | 🐛 1 | 🌐 Go | 📅 2025-05-05 - Golang library providing common and simple database abstractions on top of Google Sheets.
* [gogtrends](https://github.com/groovili/gogtrends) ⭐ 84 | 🐛 4 | 🌐 Go | 📅 2023-01-04 - Google Trends Unofficial API.
* [golang-tmdb](https://github.com/cyruzin/golang-tmdb) ⭐ 138 | 🐛 1 | 🌐 Go | 📅 2025-07-02 - Golang wrapper for The Movie Database API v3.
* [golyrics](https://github.com/mamal72/golyrics) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2018-06-30 - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [gomalshare](https://github.com/MonaxGT/gomalshare) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2019-04-29 - Go library MalShare API [malshare.com](https://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) ⭐ 60 | 🐛 7 | 🌐 Go | 📅 2023-05-15 - Go MusicBrainz WS2 client library.
* [google](https://github.com/google/google-api-go-client) ⭐ 4,279 | 🐛 19 | 🌐 Go | 📅 2025-07-02 - Auto-generated Google APIs for Go.
* [google-analytics](https://github.com/chonthu/go-google-analytics) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2015-06-09 - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) ⭐ 4,280 | 🐛 382 | 🌐 Go | 📅 2025-07-03 - Google Cloud APIs Go Client Library.
* [gopaapi5](https://github.com/utekaravinash/gopaapi5) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2020-04-03 - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
* [gopensky](https://github.com/navidys/gopensky) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2025-06-02 - Go client implementation for [OpenSKY Network](https://opensky-network.org/) live's API (airspace ADS-B and Mode S data).
* [gosip](https://github.com/koltyakov/gosip) ⭐ 159 | 🐛 12 | 🌐 Go | 📅 2025-04-09 - Client library for SharePoint.
* [gostorm](https://github.com/jsgilmore/gostorm) ⭐ 129 | 🐛 5 | 🌐 Go | 📅 2017-10-09 - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [hipchat](https://github.com/andybons/hipchat) ⭐ 104 | 🐛 0 | 🌐 Go | 📅 2016-03-24 - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) ⭐ 111 | 🐛 1 | 🌐 Go | 📅 2017-06-12 - A golang package to communicate with HipChat over XMPP.
* [igdb](https://github.com/Henry-Sarabia/igdb) ⭐ 84 | 🐛 3 | 🌐 Go | 📅 2023-01-30 - Go client for the [Internet Game Database API](https://api.igdb.com/).
* [ip2location-io-go](https://github.com/ip2location/ip2location-io-go) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-04-18 - Go wrapper for the IP2Location.io API [IP2Location.io](https://www.ip2location.io/).
* [jokeapi-go](https://github.com/icelain/jokeapi) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2024-12-25 - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/).
* [lark](https://github.com/chyroc/lark) ⭐ 449 | 🐛 19 | 🌐 Go | 📅 2025-05-27 - [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback.
* [lastpass-go](https://github.com/ansd/lastpass-go) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2023-05-25 - Go client library for the [LastPass](https://www.lastpass.com/) API.
* [libgoffi](https://github.com/clevabit/libgoffi) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-08-23 - Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration
* [Medium](https://github.com/Medium/medium-sdk-go) ⭐ 142 | 🐛 6 | 🌐 Go | 📅 2018-10-26 - Golang SDK for Medium's OAuth2 API.
* [megos](https://github.com/andygrunwald/megos) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2021-06-22 - Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster.
* [minio-go](https://github.com/minio/minio-go) ⭐ 2,725 | 🐛 17 | 🌐 Go | 📅 2025-07-01 - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel](https://github.com/dukex/mixpanel) ⭐ 60 | 🐛 6 | 🌐 Go | 📅 2023-05-01 - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [newsapi-go](https://github.com/jellydator/newsapi-go) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2025-06-17 - Go client for [NewsAPI](https://newsapi.org/).
* [openaigo](https://github.com/otiai10/openaigo) ⭐ 295 | 🐛 2 | 🌐 Go | 📅 2024-05-14 - OpenAI GPT3/GPT3.5 ChatGPT API client library for Go.
* [patreon-go](https://github.com/mxpv/patreon-go) ⭐ 44 | 🐛 1 | 🌐 Go | 📅 2022-09-01 - Go library for Patreon API.
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) ⭐ 738 | 🐛 2 | 🌐 Go | 📅 2025-06-30 - Wrapper for PayPal payment API.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2016-03-06 - The Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) ⭐ 146 | 🐛 1 | 🌐 Go | 📅 2024-04-29 - Go wrapper for the Pushover API.
* [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2022-05-28 - Go library for the [RAWG Video Games Database](https://rawg.io/) API
* [shopify](https://github.com/rapito/go-shopify) ⭐ 24 | 🐛 2 | 🌐 Go | 📅 2020-12-03 - Go Library to make CRUD request to the Shopify API.
* [simples3](https://github.com/rhnvrm/simples3) ⭐ 165 | 🐛 2 | 🌐 Go | 📅 2025-06-04 - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
* [slack](https://github.com/slack-go/slack) ⭐ 4,806 | 🐛 104 | 🌐 Go | 📅 2025-06-29 - Slack API in Go.
* [smite](https://github.com/sergiotapia/smitego) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2014-07-18 - Go package to wraps access to the Smite game API.
* [spotify](https://github.com/rapito/go-spotify) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2024-09-09 - Go Library to access Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) ⭐ 33 | 🐛 2 | 🌐 Go | 📅 2024-06-08 - Go Library to interact with Steam game servers.
* [stripe](https://github.com/stripe/stripe-go) ⭐ 2,341 | 🐛 9 | 🌐 Go | 📅 2025-07-02 - Go client for the Stripe API.
* [swag](https://github.com/zc2638/swag) ⭐ 48 | 🐛 1 | 🌐 Go | 📅 2024-05-01 - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more.
* [textbelt](https://github.com/dietsche/textbelt) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2015-09-04 - Go client for the textbelt.com txt messaging API.
* [Trello](https://github.com/adlio/trello) ⭐ 225 | 🐛 8 | 🌐 Go | 📅 2024-04-15 - Go wrapper for the Trello API.
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2019-10-23 - Go wrapper for the TripAdvisor API.
* [tumblr](https://github.com/mattcunningham/gumblr) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2016-10-30 - Go wrapper for the Tumblr v2 API.
* [uptimerobot](https://github.com/bitfield/uptimerobot) ⭐ 57 | 🐛 13 | 🌐 Go | 📅 2023-04-22 - Go wrapper and command-line client for the Uptime Robot v2 API.
* [vl-go](https://github.com/verifid/vl-go) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2021-05-30 - Go client library around the VerifID identity verification layer API.
* [webhooks](https://github.com/go-playground/webhooks) ⭐ 992 | 🐛 37 | 🌐 Go | 📅 2024-08-06 - Webhook receiver for GitHub and Bitbucket.
* [wit-go](https://github.com/wit-ai/wit-go) ⭐ 167 | 🐛 0 | 🌐 Go | 📅 2025-02-28 - Go client for wit.ai HTTP API.
* [ynab](https://github.com/brunomvsouza/ynab.go) ⭐ 72 | 🐛 2 | 🌐 Go | 📅 2025-02-09 - Go wrapper for the YNAB API.
* [zooz](https://github.com/gojuno/go-zooz) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2024-03-06 - Go client for the Zooz API.

**[⬆ back to top](#contents)**

## Utilities

*General utilities and tools to make your life easier.*

* [apm](https://github.com/topfreegames/apm) ⭐ 167 | 🐛 9 | 🌐 Go | 📅 2016-11-24 - Process manager for Golang applications with an HTTP API.
* [backscanner](https://github.com/icza/backscanner) ⭐ 67 | 🐛 0 | 🌐 Go | 📅 2024-11-24 - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
* [bed](https://github.com/itchyny/bed) ⭐ 1,304 | 🐛 1 | 🌐 Go | 📅 2024-12-01 - A Vim-like binary editor written in Go.
* [blank](https://github.com/Henry-Sarabia/blank) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2019-07-31 - Verify or remove blanks and whitespace from strings.
* [bleep](https://github.com/sinhashubham95/bleep) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-01-06 - Perform any number of actions on any set of OS signals in Go.
* [boilr](https://github.com/tmrts/boilr) ⭐ 1,738 | 🐛 44 | 🌐 Go | 📅 2023-03-07 - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [changie](https://github.com/miniscruff/changie) ⭐ 777 | 🐛 8 | 🌐 Go | 📅 2025-07-01 - Automated changelog tool for preparing releases with lots of customization options.
* [chyle](https://github.com/antham/chyle) ⭐ 158 | 🐛 1 | 🌐 Go | 📅 2025-06-09 - Changelog generator using a git repository with multiple configuration possibilities.
* [circuit](https://github.com/cep21/circuit) ⭐ 785 | 🐛 3 | 🌐 Go | 📅 2025-05-06 - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) ⭐ 1,146 | 🐛 23 | 🌐 Go | 📅 2024-05-15 - Circuit Breakers in Go.
* [clipboard](https://github.com/golang-design/clipboard) ⭐ 696 | 🐛 24 | 🌐 Go | 📅 2025-06-14 - 📋 cross-platform clipboard package in Go.
* [clockwork](https://github.com/jonboulle/clockwork) ⭐ 709 | 🐛 8 | 🌐 Go | 📅 2025-01-02 - A simple fake clock for golang.
* [cmd](https://github.com/SimonBaeumer/cmd) ⭐ 159 | 🐛 1 | 🌐 Go | 📅 2025-02-14 - Library for executing shell commands on osx, windows and linux.
* [command](https://github.com/txgruppi/command) ⚠️ Archived - Command pattern for Go with thread safe serial and parallel dispatcher.
* [config-file-validator](https://github.com/Boeing/config-file-validator) ⭐ 379 | 🐛 36 | 🌐 Go | 📅 2025-07-01 - Cross Platform tool to validate configuration files.
* [cookie](https://github.com/syntaqx/cookie) ⭐ 111 | 🐛 2 | 🌐 Go | 📅 2025-05-16 - Cookie struct parsing and helper package.
* [copy-pasta](https://github.com/jutkko/copy-pasta) ⭐ 54 | 🐛 10 | 🌐 Go | 📅 2020-06-20 - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [countries](https://github.com/biter777/countries) ⭐ 457 | 🐛 17 | 🌐 Go | 📅 2024-05-30 - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standards.
* [countries](https://github.com/pioz/countries) ⭐ 91 | 🐛 1 | 🌐 Go | 📅 2023-10-06 - All you need when you are working with countries in Go.
* [create-go-app](https://github.com/create-go-app/cli) ⭐ 2,705 | 🐛 7 | 🌐 Go | 📅 2025-06-09 - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
* [cryptgo](https://github.com/Gituser143/cryptgo) ⭐ 155 | 🐛 6 | 🌐 Go | 📅 2021-10-17 - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time!
* [ctop](https://github.com/bcicen/ctop) ⭐ 16,228 | 🐛 112 | 🌐 Go | 📅 2024-07-08 - [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics.
* [ctxutil](https://github.com/posener/ctxutil) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2020-03-01 - A collection of utility functions for contexts.
* [cvt](https://github.com/shockerli/cvt) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2024-11-30 - Easy and safe convert any value to another type.
* [dbt](https://github.com/nikogura/dbt) ⭐ 68 | 🐛 6 | 🌐 Go | 📅 2024-06-20 - A framework for running self-updating signed binaries from a central, trusted repository.
* [Death](https://github.com/vrecan/death) ⭐ 198 | 🐛 0 | 🌐 Go | 📅 2024-12-16 - Managing go application shutdown with signals.
* [debounce](https://github.com/floatdrop/debounce) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2025-06-21 - A zero-allocation debouncer written in Go.
* [delve](https://github.com/derekparker/delve) ⭐ 653 | 🐛 2 | 🌐 Go | 📅 2025-06-29 - Go debugger.
* [dive](https://github.com/wagoodman/dive) ⭐ 51,279 | 🐛 167 | 🌐 Go | 📅 2025-06-30 - A tool for exploring each layer in a Docker image.
* [dlog](https://github.com/kirillDanshin/dlog) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2017-07-28 - Compile-time controlled logger to make your release smaller without removing debug calls.
* [EaseProbe](https://github.com/megaease/easeprobe) ⭐ 2,252 | 🐛 6 | 🌐 Go | 📅 2025-07-01 - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification.
* [equalizer](https://github.com/reugn/equalizer) ⭐ 91 | 🐛 0 | 🌐 Go | 📅 2024-03-14 - Quota manager and rate limiter collection for Go.
* [ergo](https://github.com/cristianoliveira/ergo) ⭐ 635 | 🐛 8 | 🌐 Go | 📅 2025-02-02 - The management of multiple local services running over different ports made easy.
* [evaluator](https://github.com/nullne/evaluator) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2023-04-14 - Evaluate an expression dynamically based on s-expression. It's simple and easy to extend.
* [Failsafe-go](https://github.com/failsafe-go/failsafe-go) ⭐ 1,804 | 🐛 27 | 🌐 Go | 📅 2025-06-24 - Fault tolerance and resilience patterns for Go.
* [filetype](https://github.com/h2non/filetype) ⭐ 2,206 | 🐛 46 | 🌐 Go | 📅 2025-06-27 - Small package to infer the file type checking the magic numbers signature.
* [filler](https://github.com/yaronsumel/filler) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2017-04-10 - small utility to fill structs using "fill" tag.
* [filter](https://github.com/gookit/filter) ⭐ 151 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - provide filtering, sanitizing, and conversion of Go data.
* [fzf](https://github.com/junegunn/fzf) ⭐ 71,464 | 🐛 289 | 🌐 Go | 📅 2025-07-02 - Command-line fuzzy finder written in Go.
* [generate](https://github.com/go-playground/generate) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2017-01-10 - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [ghokin](https://github.com/antham/ghokin) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2025-06-30 - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
* [git-time-metric](https://github.com/git-time-metric/gtm) ⭐ 994 | 🐛 52 | 🌐 Go | 📅 2022-01-31 - Simple, seamless, lightweight time tracking for Git.
* [git-tools](https://github.com/kazhuravlev/git-tools) ⭐ 33 | 🐛 3 | 🌐 Go | 📅 2025-06-08 - Tool to help manage git tags.
* [gitbatch](https://github.com/isacikgoz/gitbatch) ⭐ 1,557 | 🐛 20 | 🌐 Go | 📅 2023-05-11 - manage your git repositories in one place.
* [gitcs](https://github.com/knbr13/gitcs/) ⭐ 122 | 🐛 0 | 🌐 Go | 📅 2025-06-06 - Git Commits Visualizer, CLI tool to visualize your Git commits on your local machine.
* [go-actuator](https://github.com/sinhashubham95/go-actuator) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-03-19 - Production ready features for Go based web frameworks.
* [go-astitodo](https://github.com/asticode/go-astitodo) ⭐ 66 | 🐛 2 | 🌐 Go | 📅 2024-04-22 - Parse TODOs in your GO code.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) ⭐ 181 | 🐛 0 | 🌐 Go | 📅 2019-08-29 - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) ⭐ 166 | 🐛 1 | 🌐 Go | 📅 2019-03-21 - Pure Go bsdiff and bspatch libraries and CLI tools.
* [go-clip](https://github.com/prashantgupta24/go-clip) ⭐ 14 | 🐛 2 | 🌐 Go | 📅 2021-02-05 - A minimalistic clipboard manager for Mac.
* [go-convert](https://github.com/Eun/go-convert) ⭐ 23 | 🐛 2 | 🌐 Go | 📅 2024-05-08 - Package go-convert enables you to convert a value into another type.
* [go-countries](https://github.com/mikekonan/go-countries) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2020-12-17 - Lightweight lookup over ISO-3166 codes.
* [go-dry](https://github.com/ungerik/go-dry) ⭐ 487 | 🐛 0 | 🌐 Go | 📅 2025-01-14 - DRY (don't repeat yourself) package for Go.
* [go-events](https://github.com/deatil/go-events) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2024-12-04 - A go event and event'subscribe package, like wordpress hook functions.
* [go-funk](https://github.com/thoas/go-funk) ⭐ 4,908 | 🐛 8 | 🌐 Go | 📅 2024-07-24 - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-health](https://github.com/Talento90/go-health) ⭐ 96 | 🐛 0 | 🌐 Go | 📅 2022-01-19 - Health package simplifies the way you add health check to your services.
* [go-httpheader](https://github.com/mozillazg/go-httpheader) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2023-07-15 - Go library for encoding structs into Header fields.
* [go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) ⭐ 95 | 🐛 4 | 🌐 Go | 📅 2025-07-01 - A CLI for removing unused or previous versions of AWS Lambdas.
* [go-lock](https://github.com/viney-shih/go-lock) ⭐ 120 | 🐛 0 | 🌐 Go | 📅 2022-06-18 - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
* [go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) ⭐ 93 | 🐛 0 | 🌐 Go | 📅 2023-08-26 - A Pattern matching library inspired by ts-pattern.
* [go-pkg](https://github.com/chenquan/go-pkg) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2022-06-29 - A go toolkit.
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2020-02-17 - Go package for working with Problem Details.
* [go-qr](https://github.com/piglig/go-qr) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2024-12-16 - A native, high-quality and minimalistic QR code generator.
* [go-rate](https://github.com/beefsack/go-rate) ⭐ 399 | 🐛 0 | 🌐 Go | 📅 2022-02-14 - Timed rate limiter for Go.
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) ⭐ 225 | 🐛 29 | 🌐 Go | 📅 2024-07-10 - XML Sitemap generator written in Go.
* [go-trigger](https://github.com/sadlil/go-trigger) ⭐ 249 | 🐛 1 | 🌐 Go | 📅 2017-03-28 - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [go-tripper](https://github.com/rajnandan1/go-tripper) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2024-04-21 - Tripper is a circuit breaker package for Go that allows you to circuit and control the status of circuits.
* [go-type](https://github.com/mikekonan/go-types) ⭐ 21 | 🐛 1 | 🌐 Go | 📅 2025-03-14 - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
* [goback](https://github.com/carlescere/goback) ⭐ 50 | 🐛 6 | 🌐 Go | 📅 2021-03-09 - Go simple exponential backoff package.
* [goctx](https://github.com/zerosnake0/goctx) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-11-24 - Get your context value with high performance.
* [godaemon](https://github.com/VividCortex/godaemon) ⭐ 495 | 🐛 9 | 🌐 Go | 📅 2021-06-29 - Utility to write daemons.
* [godropbox](https://github.com/dropbox/godropbox) ⭐ 4,198 | 🐛 6 | 🌐 Go | 📅 2023-12-24 - Common libraries for writing Go services/applications from Dropbox.
* [gofn](https://github.com/tiendc/gofn) ⭐ 52 | 🐛 0 | 🌐 Go | 📅 2025-02-13 - High performance utility functions written using Generics for Go 1.18+.
* [golarm](https://github.com/msempere/golarm) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2015-08-24 - Fire alarms with system events.
* [golog](https://github.com/mlimaloureiro/golog) ⭐ 63 | 🐛 15 | 🌐 Go | 📅 2019-01-22 - Easy and lightweight CLI tool to time track your tasks.
* [gopencils](https://github.com/bndr/gopencils) ⭐ 453 | 🐛 7 | 🌐 Go | 📅 2019-02-18 - Small and simple package to easily consume REST APIs.
* [goplaceholder](https://github.com/michiwend/goplaceholder) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2016-01-17 - a small golang lib to generate placeholder images.
* [goreadability](https://github.com/philipjkim/goreadability) ⭐ 69 | 🐛 2 | 🌐 Go | 📅 2019-04-22 - Webpage summary extractor using Facebook Open Graph and arc90's readability.
* [goreleaser](https://github.com/goreleaser/goreleaser) ⭐ 14,803 | 🐛 22 | 🌐 Go | 📅 2025-07-03 - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) ⭐ 3,134 | 🐛 30 | 🌐 Go | 📅 2018-10-27 - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) ⭐ 116 | 🐛 2 | 🌐 Go | 📅 2022-11-11 - SeaweedFS client library with almost full features.
* [gostrutils](https://github.com/ik5/gostrutils) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2024-06-30 - Collections of string manipulation and conversion functions.
* [gotenv](https://github.com/subosito/gotenv) ⭐ 306 | 🐛 2 | 🌐 Go | 📅 2025-05-05 - Load environment variables from `.env` or any `io.Reader` in Go.
* [goval](https://github.com/maja42/goval) ⭐ 170 | 🐛 1 | 🌐 Go | 📅 2025-02-19 - Evaluate arbitrary expressions in Go.
* [graterm](https://github.com/skovtunenko/graterm) ⭐ 28 | 🐛 3 | 🌐 Go | 📅 2025-02-23 - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application.
* [grofer](https://github.com/pesos/grofer) ⭐ 374 | 🐛 18 | 🌐 Go | 📅 2023-04-04 - A system and resource monitoring tool written in Golang!
* [gubrak](https://github.com/novalagung/gubrak) ⭐ 499 | 🐛 0 | 🌐 Go | 📅 2023-03-08 - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* [handy](https://github.com/miguelpragier/handy) ⭐ 82 | 🐛 0 | 🌐 Go | 📅 2020-09-30 - Many utilities and helpers like string handlers/formatters and validators.
* [healthcheck](https://github.com/kazhuravlev/healthcheck) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2025-06-08 - A simple yet powerful readiness test for Kubernetes.
* [hostctl](https://github.com/guumaster/hostctl) ⭐ 1,163 | 🐛 19 | 🌐 Go | 📅 2024-01-26 - A CLI tool to manage /etc/hosts with easy commands.
* [htcat](https://github.com/htcat/htcat) ⭐ 556 | 🐛 4 | 🌐 Go | 📅 2025-05-30 - Parallel and Pipelined HTTP GET Utility.
* [hub](https://github.com/github/hub) ⭐ 22,914 | 🐛 294 | 🌐 Go | 📅 2024-02-02 - wrap git commands with additional functionality to interact with github from the terminal.
* [immortal](https://github.com/immortal/immortal) ⭐ 819 | 🐛 2 | 🌐 Go | 📅 2024-07-21 - \*nix cross-platform (OS agnostic) supervisor.
* [jet](https://github.com/NicoNex/jet) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-03-24 - Just Edit Text: a fast and powerful tool for finding and replacing file content and names using regular expressions.
* [jsend](https://github.com/clevergo/jsend) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2021-06-29 - JSend's implementation written in Go.
* [json-log-viewer](https://github.com/hedhyw/json-log-viewer) ⭐ 159 | 🐛 10 | 🌐 Go | 📅 2025-06-25 - Interactive viewer for JSON logs.
* [jump](https://github.com/gsamokovarov/jump) ⭐ 1,859 | 🐛 2 | 🌐 Go | 📅 2025-06-20 - Jump helps you navigate faster by learning your habits.
* [just](https://github.com/kazhuravlev/just) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2025-05-25 - Just a collection of useful functions for working with generic data structures.
* [koazee](https://github.com/wesovilabs/koazee) ⭐ 531 | 🐛 14 | 🌐 Go | 📅 2020-11-18 - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
* [lancet](https://github.com/duke-git/lancet) ⭐ 5,097 | 🐛 8 | 🌐 Go | 📅 2025-06-25 - A comprehensive, efficient, and reusable util function library of go.
* [lets-go](https://github.com/aplescia-chwy/lets-go) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2021-04-24 - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
* [limiters](https://github.com/mennanov/limiters) ⭐ 568 | 🐛 6 | 🌐 Go | 📅 2025-07-01 - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
* [lo](https://github.com/samber/lo) ⭐ 19,689 | 🐛 210 | 🌐 Go | 📅 2025-07-02 - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...)
* [loncha](https://github.com/kazu/loncha) ⭐ 11 | 🐛 1 | 🌐 Go | 📅 2022-07-21 - A high-performance slice Utilities.
* [lrserver](https://github.com/jaschaephraim/lrserver) ⭐ 128 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-06 - LiveReload server for Go.
* [mani](https://github.com/alajmo/mani) ⭐ 558 | 🐛 20 | 🌐 Go | 📅 2025-05-26 - CLI tool to help you manage multiple repositories.
* [mc](https://github.com/minio/mc) ⭐ 3,080 | 🐛 41 | 🌐 Go | 📅 2025-07-02 - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo](https://github.com/imdario/mergo) ⭐ 3,017 | 🐛 15 | 🌐 Go | 📅 2025-07-01 - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [mimemagic](https://github.com/zRedShift/mimemagic) ⭐ 100 | 🐛 6 | 🌐 Go | 📅 2023-10-11 - Pure Go ultra performant MIME sniffing library/utility.
* [mimesniffer](https://github.com/aofei/mimesniffer) ⚠️ Archived - A MIME type sniffer for Go.
* [mimetype](https://github.com/gabriel-vasile/mimetype) ⭐ 1,820 | 🐛 43 | 🌐 Go | 📅 2025-07-01 - Package for MIME type detection based on magic numbers.
* [minify](https://github.com/tdewolff/minify) ⭐ 3,902 | 🐛 34 | 🌐 Go | 📅 2025-06-11 - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [minquery](https://github.com/icza/minquery) ⭐ 62 | 🐛 4 | 🌐 Go | 📅 2023-03-31 - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
* [moldova](https://github.com/StabbyCutyou/moldova) ⭐ 169 | 🐛 0 | 🌐 Go | 📅 2017-09-04 - Utility for generating random data based on an input template.
* [mole](https://github.com/davrodpin/mole) ⭐ 1,715 | 🐛 29 | 🌐 Go | 📅 2024-05-13 - cli app to easily create ssh tunnels.
* [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) ⭐ 131 | 🐛 4 | 🌐 Go | 📅 2023-03-07 - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines.
* [mssqlx](https://github.com/linxGnu/mssqlx) ⭐ 102 | 🐛 3 | 🌐 Go | 📅 2024-04-29 - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [multitick](https://github.com/VividCortex/multitick) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2023-12-12 - Multiplexor for aligned tickers.
* [netbug](https://github.com/e-dard/netbug) ⭐ 72 | 🐛 0 | 🌐 Go | 📅 2015-10-29 - Easy remote profiling of your services.
* [nfdump](https://github.com/chrispassas/nfdump) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-10-24 - Read nfdump netflow files.
* [nostromo](https://github.com/pokanop/nostromo) ⭐ 146 | 🐛 13 | 🌐 Go | 📅 2024-06-25 - CLI for building powerful aliases.
* [okrun](https://github.com/xta/okrun) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2014-10-06 - go run error steamroller.
* [olaf](https://github.com/btnguyen2k/olaf) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2019-04-10 - Twitter Snowflake implemented in Go.
* [onecache](https://github.com/adelowo/onecache) ⭐ 136 | 🐛 0 | 🌐 Go | 📅 2020-05-25 - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [optional](https://github.com/kazhuravlev/optional) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2025-06-07 - Optional struct fields and vars.
* [panicparse](https://github.com/maruel/panicparse) ⭐ 3,670 | 🐛 3 | 🌐 Go | 📅 2025-03-13 - Groups similar goroutines and colorizes stack dump.
* [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) ⭐ 248 | 🐛 2 | 🌐 Go | 📅 2023-03-01 - Pattern matching library.
* [peco](https://github.com/peco/peco) ⭐ 7,764 | 🐛 52 | 🌐 Go | 📅 2025-06-21 - Simplistic interactive filtering tool.
* [pgo](https://github.com/arthurkushman/pgo) ⭐ 88 | 🐛 1 | 🌐 Go | 📅 2024-04-08 - Convenient functions for PHP community.
* [pm](https://github.com/VividCortex/pm) ⭐ 79 | 🐛 2 | 🌐 Go | 📅 2023-12-12 - Process (i.e. goroutine) manager with an HTTP API.
* [pointer](https://github.com/xorcare/pointer) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2024-12-02 - Package pointer contains helper routines for simplifying the creation of optional fields of basic type.
* [ptr](https://github.com/gotidy/ptr) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2023-06-06 - Package that provide functions for simplified creation of pointers from constants of basic types.
* [rclient](https://github.com/zpatrick/rclient) ⭐ 35 | 🐛 2 | 🌐 Go | 📅 2019-11-28 - Readable, flexible, simple-to-use client for REST APIs.
* [remote-touchpad](https://github.com/Unrud/remote-touchpad) ⭐ 607 | 🐛 13 | 🌐 Go | 📅 2025-03-18 - Control mouse and keyboard from a smartphone.
* [repeat](https://github.com/ssgreg/repeat) ⭐ 85 | 🐛 0 | 🌐 Go | 📅 2020-07-24 - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* [request](https://github.com/mozillazg/request) ⭐ 425 | 🐛 6 | 🌐 Go | 📅 2019-12-05 - Go HTTP Requests for Humans™.
* [rerun](https://github.com/ivpusic/rerun) ⭐ 166 | 🐛 0 | 🌐 Go | 📅 2018-03-22 - Recompiling and rerunning go apps when source changes.
* [rest-go](https://github.com/edermanoel94/rest-go) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2020-08-16 - A package that provide many helpful methods for working with rest api.
* [retry](https://github.com/kamilsk/retry) ⭐ 343 | 🐛 10 | 🌐 Go | 📅 2024-06-10 - The most advanced functional mechanism to perform actions repetitively until successful.
* [retry](https://github.com/percolate/retry) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2023-03-16 - A simple but highly configurable retry package for Go.
* [retry](https://github.com/thedevsaddam/retry) ⭐ 66 | 🐛 0 | 🌐 Go | 📅 2022-01-04 - Simple and easy retry mechanism package for Go.
* [retry](https://github.com/shafreeck/retry) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2020-02-11 - A pretty simple library to ensure your work to be done.
* [retry-go](https://github.com/avast/retry-go) ⭐ 2,716 | 🐛 14 | 🌐 Go | 📅 2025-03-21 - Simple library for retry mechanism.
* [retry-go](https://github.com/rafaeljesus/retry-go) ⭐ 50 | 🐛 2 | 🌐 Go | 📅 2018-10-25 - Retrying made simple and easy for golang.
* [robustly](https://github.com/VividCortex/robustly) ⭐ 159 | 🐛 1 | 🌐 Go | 📅 2023-12-12 - Runs functions resiliently, catching and restarting panics.
* [rospo](https://github.com/ferama/rospo) ⭐ 336 | 🐛 7 | 🌐 Go | 📅 2025-06-22 - Simple and reliable ssh tunnels with embedded ssh server in Golang.
* [scan](https://github.com/blockloop/scan) ⭐ 596 | 🐛 1 | 🌐 Go | 📅 2025-06-06 - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
* [scan](https://github.com/wroge/scan) ⭐ 65 | 🐛 0 | 🌐 Go | 📅 2024-03-08 - Scan sql rows into any type powered by generics.
* [scany](https://github.com/georgysavva/scany) ⭐ 1,438 | 🐛 6 | 🌐 Go | 📅 2025-03-19 - Library for scanning data from a database into Go structs and more.
* [serve](https://github.com/syntaqx/serve) ⭐ 344 | 🐛 2 | 🌐 Go | 📅 2025-05-05 - A static http server anywhere you need.
* [sesh](https://github.com/joshmedeski/sesh) ⭐ 1,115 | 🐛 56 | 🌐 Go | 📅 2025-06-23 - Sesh is a CLI that helps you create and manage tmux sessions quickly and easily using zoxide.
* [set](https://github.com/nofeaturesonlybugs/set) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2022-06-12 - Performant and flexible struct mapping and loose type conversion.
* [shutdown](https://github.com/ztrue/shutdown) ⭐ 60 | 🐛 0 | 🌐 Go | 📅 2022-01-15 - App shutdown hooks for `os.Signal` handling.
* [silk](https://github.com/chrispassas/silk) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2022-03-09 - Read silk netflow files.
* [slice](https://github.com/psampaz/slice) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2020-04-09 - Type-safe functions for common Go slice operations.
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2020-02-03 - Slice conversion between primitive types.
* [slicer](https://github.com/leaanthony/slicer) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2021-08-08 - Makes working with slices easier.
* [sorty](https://github.com/jfcg/sorty) ⭐ 137 | 🐛 0 | 🌐 Go | 📅 2024-05-11 - Fast Concurrent / Parallel Sorting.
* [sqlx](https://github.com/jmoiron/sqlx) ⭐ 17,020 | 🐛 381 | 🌐 Go | 📅 2024-08-15 - provides a set of extensions on top of the excellent built-in database/sql package.
* [sshman](https://github.com/shoobyban/sshman) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2022-11-03 - SSH Manager for authorized\_keys files on multiple remote servers.
* [statiks](https://github.com/janiltonmaciel/statiks) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2025-04-16 - Fast, zero-configuration, static HTTP filer server.
* [Storm](https://github.com/asdine/storm) ⭐ 2,082 | 🐛 64 | 🌐 Go | 📅 2024-01-07 - Simple and powerful toolkit for BoltDB.
* [structs](https://github.com/PumpkinSeed/structs) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2017-10-23 - Implement simple functions to manipulate structs.
* [throttle](https://github.com/yudppp/throttle) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2021-08-24 - Throttle is an object that will perform exactly one action per duration.
* [tik](https://github.com/andy2046/tik) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2020-10-17 - Simple and easy timing wheel package for Go.
* [tome](https://github.com/cyruzin/tome) ⭐ 35 | 🐛 1 | 🌐 Go | 📅 2022-04-20 - Tome was designed to paginate simple RESTful APIs.
* [toolbox](https://github.com/viant/toolbox) ⭐ 219 | 🐛 5 | 🌐 Go | 📅 2024-12-10 - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [UNIS](https://github.com/esemplastic/unis) ⭐ 70 | 🐛 2 | 🌐 Go | 📅 2017-05-09 - Common Architecture™ for String Utilities in Go.
* [upterm](https://github.com/owenthereal/upterm) ⭐ 934 | 🐛 51 | 🌐 Go | 📅 2025-06-30 - A tool for developers to share terminal/tmux sessions securely over the web. It’s perfect for remote pair programming, accessing computers behind NATs/firewalls, remote debugging, and more.
* [usql](https://github.com/knq/usql) ⭐ 9,411 | 🐛 94 | 🌐 Go | 📅 2025-05-19 - usql is a universal command-line interface for SQL databases.
* [util](https://github.com/shomali11/util) ⭐ 299 | 🐛 1 | 🌐 Go | 📅 2022-07-17 - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [watchhttp](https://github.com/nikolaydubina/watchhttp) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2024-08-22 - Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint.
* [wifiqr](https://github.com/reugn/wifiqr) ⭐ 272 | 🐛 0 | 🌐 Go | 📅 2024-05-19 - Wi-Fi QR Code Generator.
* [wuzz](https://github.com/asciimoo/wuzz) ⭐ 10,662 | 🐛 46 | 🌐 Go | 📅 2025-05-06 - Interactive cli tool for HTTP inspection.
* [xferspdy](https://github.com/monmohan/xferspdy) ⭐ 102 | 🐛 3 | 🌐 Go | 📅 2021-04-04 - Xferspdy provides binary diff and patch library in golang.
* [xpool](https://github.com/peczenyj/xpool) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2025-05-05 - Yet another golang type safe object pool using generics.
* [yogo](https://github.com/antham/yogo) ⭐ 45 | 🐛 0 | 🌐 HTML | 📅 2025-06-06 - Check yopmail mails from command line.

**[⬆ back to top](#contents)**

## UUID

*Libraries for working with UUIDs.*

* [fastuuid](https://github.com/rekby/fastuuid) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2023-02-28 - Fast generate UUIDv4 as string or bytes.
* [goid](https://github.com/jakehl/goid) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2019-02-18 - Generate and Parse RFC4122 compliant V4 UUIDs.
* [gouid](https://github.com/twharmon/gouid) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2024-12-03 - Generate cryptographically secure random string IDs with just one allocation.
* [nanoid](https://github.com/aidarkhanov/nanoid) ⚠️ Archived - A tiny and efficient Go unique string ID generator.
* [sno](https://github.com/muyo/sno) ⭐ 91 | 🐛 1 | 🌐 Go | 📅 2021-11-12 - Compact, sortable and fast unique IDs with embedded metadata.
* [ulid](https://github.com/oklog/ulid) ⭐ 4,750 | 🐛 5 | 🌐 Go | 📅 2025-06-09 - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
* [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
* [uuid](https://github.com/agext/uuid) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2020-03-12 - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* [uuid](https://github.com/gofrs/uuid) ⭐ 1,701 | 🐛 4 | 🌐 Go | 📅 2025-07-01 - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
* [uuid](https://github.com/google/uuid) ⭐ 5,711 | 🐛 45 | 🌐 Go | 📅 2024-11-14 - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
* [uuidcheck](https://github.com/ashwingopalsamy/uuidcheck) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2024-12-08 - A tiny, dependency-free Go library that validates UUIDs against standard RFC 4122 formatting, converts UUIDv7() into UTC timestamps.
* [wuid](https://github.com/edwingeng/wuid) ⭐ 540 | 🐛 2 | 🌐 Go | 📅 2024-01-26 - An extremely fast globally unique number generator.
* [xid](https://github.com/rs/xid) ⭐ 4,146 | 🐛 17 | 🌐 Go | 📅 2025-05-12 - Xid is a globally unique id generator library, ready to be safely used directly in your server code.

**[⬆ back to top](#contents)**

## Validation

*Libraries for validation.*

* [checkdigit](https://github.com/osamingo/checkdigit) ⭐ 111 | 🐛 1 | 🌐 Go | 📅 2025-03-28 - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
* [go-validator](https://github.com/tiendc/go-validator) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2024-11-27 - Validation library using Generics.
* [gody](https://github.com/guiferpa/gody) ⭐ 156 | 🐛 1 | 🌐 Go | 📅 2025-05-30 - :balloon: A lightweight struct validator for Go.
* [govalid](https://github.com/twharmon/govalid) ⭐ 96 | 🐛 0 | 🌐 Go | 📅 2025-05-20 - Fast, tag-based validation for structs.
* [govalidator](https://github.com/asaskevich/govalidator) ⭐ 6,167 | 🐛 167 | 🌐 Go | 📅 2025-01-22 - Validators and sanitizers for strings, numerics, slices and structs.
* [govalidator](https://github.com/thedevsaddam/govalidator) ⭐ 1,335 | 🐛 43 | 🌐 Go | 📅 2024-05-12 - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [hvalid](https://github.com/lyonnee/hvalid) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2025-06-05 hvalid is a lightweight validation library written in Go language. It provides a custom validator interface and a series of common validation functions to help developers quickly implement data validation.
* [jio](https://github.com/faceair/jio) ⭐ 118 | 🐛 2 | 🌐 Go | 📅 2024-07-04 - jio is a json schema validator similar to [joi](https://github.com/hapijs/joi) ⭐ 21,113 | 🐛 192 | 🌐 JavaScript | 📅 2025-06-18.
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) ⭐ 3,937 | 🐛 58 | 🌐 Go | 📅 2024-03-23 - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [validate](https://github.com/gookit/validate) ⭐ 1,096 | 🐛 27 | 🌐 Go | 📅 2025-06-30 - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
* [validate](https://github.com/gobuffalo/validate) ⭐ 93 | 🐛 0 | 🌐 Go | 📅 2022-09-26 - This package provides a framework for writing validations for Go applications.
* [validator](https://github.com/go-playground/validator) ⭐ 18,591 | 🐛 323 | 🌐 Go | 📅 2025-07-02 - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
* [Validator](https://github.com/go-the-way/validator) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2024-08-16 - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex.
* [valix](https://github.com/marrow16/valix) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2025-04-03 Go package for validating requests
* [Zog](https://github.com/Oudwins/zog) ⭐ 892 | 🐛 10 | 🌐 Go | 📅 2025-07-02 - A [Zod](https://github.com/colinhacks/zod) ⭐ 38,837 | 🐛 535 | 🌐 TypeScript | 📅 2025-07-03 inspired schema builder for runtime value parsing and validation.
  **[⬆ back to top](#contents)**

## Version Control

*Libraries for version control.*

* [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
* [froggit-go](https://github.com/jfrog/froggit-go) ⭐ 47 | 🐛 17 | 🌐 Go | 📅 2025-06-25 - Froggit-Go is a Go library, allowing to perform actions on VCS providers.
* [git2go](https://github.com/libgit2/git2go) ⭐ 1,973 | 🐛 84 | 🌐 Go | 📅 2024-03-04 - Go bindings for libgit2.
* [githooks](https://github.com/gabyx/githooks) ⭐ 110 | 🐛 14 | 🌐 Go | 📅 2025-04-14 - Per-repo and shared Git hooks with version control and auto update.
* [go-git](https://github.com/go-git/go-git) ⭐ 6,682 | 🐛 167 | 🌐 Go | 📅 2025-07-01 - highly extensible Git implementation in pure Go.
* [go-vcs](https://github.com/sourcegraph/go-vcs) ⭐ 80 | 🐛 22 | 🌐 Go | 📅 2023-07-17 - manipulate and inspect VCS repositories in Go.
* [hercules](https://github.com/src-d/hercules) ⭐ 2,716 | 🐛 52 | 🌐 Go | 📅 2023-02-07 - gaining advanced insights from Git repository history.
* [hgo](https://github.com/beyang/hgo) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2015-08-25 - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

**[⬆ back to top](#contents)**

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) ⭐ 912 | 🐛 49 | 🌐 Go | 📅 2022-09-06 - Go bindings for FFmpeg av\* libraries.
* [go-astiav](https://github.com/asticode/go-astiav) ⭐ 518 | 🐛 1 | 🌐 Go | 📅 2025-05-23 - Better C bindings for ffmpeg in GO.
* [go-astisub](https://github.com/asticode/go-astisub) ⭐ 643 | 🐛 6 | 🌐 Go | 📅 2025-03-01 - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [go-astits](https://github.com/asticode/go-astits) ⭐ 571 | 🐛 8 | 🌐 Go | 📅 2024-12-22 - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* [go-m3u8](https://github.com/etherlabsio/go-m3u8) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2022-09-20 - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility.
* [go-mpd](https://github.com/unki2aut/go-mpd) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2025-06-10 - Parser and generator library for MPEG-DASH manifest files.
* [goav](https://github.com/giorgisio/goav) ⭐ 2,118 | 🐛 48 | 🌐 Go | 📅 2022-05-19 - Comprehensive Go bindings for FFmpeg.
* [gortsplib](https://github.com/aler9/gortsplib) ⭐ 801 | 🐛 25 | 🌐 Go | 📅 2025-07-02 - Pure Go RTSP server and client library.
* [libvlc-go](https://github.com/adrg/libvlc-go) ⭐ 471 | 🐛 10 | 🌐 Go | 📅 2025-06-03 - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
* [m3u8](https://github.com/grafov/m3u8) ⚠️ Archived - Parser and generator library of M3U8 playlists for Apple HLS.
* [mp4ff](https://github.com/Eyevinn/mp4ff) ⭐ 528 | 🐛 2 | 🌐 Go | 📅 2025-07-02 - Library and tools for working with MP4 files containing video, audio, subtitles, or metadata.
* [v4l](https://github.com/korandiz/v4l) ⭐ 85 | 🐛 2 | 🌐 Go | 📅 2024-03-22 - Video capture library for Linux, written in Go.

**[⬆ back to top](#contents)**

## Web Frameworks

*Full stack web frameworks.*

* [Atreugo](https://github.com/savsgio/atreugo) ⭐ 1,282 | 🐛 5 | 🌐 Go | 📅 2025-01-01 - High performance and extensible micro web framework with zero memory allocations in hot paths.
* [Beego](https://github.com/beego/beego) ⭐ 32,132 | 🐛 16 | 🌐 Go | 📅 2025-06-25 - beego is an open-source, high-performance web framework for the Go programming language.
* [Confetti Framework](https://confetti-framework.github.io/docs/) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
* [Don](https://github.com/abemedia/go-don) ⭐ 54 | 🐛 13 | 🌐 Go | 📅 2025-05-05 - A highly performant and simple to use API framework.
* [Echo](https://github.com/labstack/echo) ⭐ 31,228 | 🐛 105 | 🌐 Go | 📅 2025-05-22 - High performance, minimalist Go web framework.
* [Fastschema](https://github.com/fastschema/fastschema) ⭐ 467 | 🐛 16 | 🌐 Go | 📅 2025-06-04 - A flexible Go web framework and Headless CMS.
* [Fiber](https://github.com/gofiber/fiber) ⭐ 37,021 | 🐛 101 | 🌐 Go | 📅 2025-07-02 - An Express.js inspired web framework build on Fasthttp.
* [Flamingo](https://github.com/i-love-flamingo/flamingo) ⭐ 533 | 🐛 30 | 🌐 Go | 📅 2025-07-02 - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
* [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) ⭐ 565 | 🐛 28 | 🌐 Go | 📅 2025-07-02 - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
* [Fuego](https://github.com/go-fuego/fuego) ⭐ 1,430 | 🐛 37 | 🌐 Go | 📅 2025-06-30 - The framework for busy Go developers! Web framework generating OpenAPI 3 spec from source code.
* [Gin](https://github.com/gin-gonic/gin) ⭐ 82,969 | 🐛 855 | 🌐 Go | 📅 2025-07-01 - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Ginrpc](https://github.com/xxjwxc/ginrpc) ⭐ 297 | 🐛 13 | 🌐 Go | 📅 2025-04-16 - Gin parameter automatic binding tool,gin rpc tools.
* [Goa](https://github.com/goadesign/goa) ⭐ 5,888 | 🐛 26 | 🌐 Go | 📅 2025-07-02 - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* [GoFr](https://github.com/gofr-dev/gofr) ⭐ 11,742 | 🐛 86 | 🌐 Go | 📅 2025-07-02 - Gofr is an opinionated microservice development framework.
* [GoFrame](https://github.com/gogf/gf) ⭐ 12,500 | 🐛 205 | 🌐 Go | 📅 2025-06-24 - GoFrame is a modular, powerful, high-performance and enterprise-class application development framework of Golang.
* [golamb](https://github.com/twharmon/golamb) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2024-05-30 - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway.
* [Gone](https://github.com/gone-io/gone) ⭐ 131 | 🐛 0 | 🌐 Go | 📅 2025-06-10 - A lightweight dependency injection and web framework inspired by Spring.
* [goravel](https://github.com/goravel/goravel) ⭐ 3,896 | 🐛 57 | 🌐 Go | 📅 2025-07-02 - A Laravel-inspired web framework with ORM, authentication, queue, task scheduling, and more built-in features.
* [Goyave](https://github.com/go-goyave/goyave) ⭐ 1,711 | 🐛 11 | 🌐 Go | 📅 2025-07-01 - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
* [Hertz](https://github.com/cloudwego/hertz) ⭐ 6,349 | 🐛 45 | 🌐 Go | 📅 2025-07-02 - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices.
* [hiboot](https://github.com/hidevopsio/hiboot) ⭐ 181 | 🐛 2 | 🌐 Go | 📅 2025-06-19 - hiboot is a high performance web application framework with auto configuration and dependency injection support.
* [Huma](https://github.com/danielgtaylor/huma/) ⭐ 3,206 | 🐛 118 | 🌐 Go | 📅 2025-07-02 - Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI.
* [iWF](https://github.com/indeedeng/iwf) ⭐ 579 | 🐛 72 | 🌐 Go | 📅 2025-07-02 - iWF is an all-in-one platform for developing long-running business processes. It offers a convenient abstraction for utilizing databases, ElasticSearch, message queues, durable timers, and more, with a clean, simple, and user-friendly interface.
* [Lit](https://github.com/jvcoutinho/lit) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2024-02-27 - Highly performant declarative web framework for Golang, aiming for simplicity and quality of life.
* [Microservice](https://github.com/claygod/microservice) ⭐ 118 | 🐛 0 | 🌐 Go | 📅 2025-04-14 - The framework for the creation of microservices, written in Golang.
* [patron](https://github.com/beatlabs/patron) ⭐ 125 | 🐛 26 | 🌐 Go | 📅 2025-07-01 - Patron is a microservice framework following best cloud practices with a focus on productivity.
* [Pnutmux](https://gitlab.com/fruitygo/pnutmux) - Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting.
* [Revel](https://github.com/revel/revel) ⭐ 13,197 | 🐛 99 | 🌐 Go | 📅 2023-10-28 - High-productivity web framework for the Go language.
* [rk-boot](https://github.com/rookie-ninja/rk-boot) ⭐ 543 | 🐛 14 | 🌐 Go | 📅 2024-10-04 - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily.
* [Ronykit](https://github.com/clubpay/ronykit) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2025-06-28 - Web framework with pluggable architecture and very performant.
* [rux](https://github.com/gookit/rux) ⭐ 97 | 🐛 2 | 🌐 Go | 📅 2025-06-21 - Simple and fast web framework for build golang HTTP applications.
* [templui](https://github.com/axzilla/templui) ⭐ 743 | 🐛 2 | 🌐 JavaScript | 📅 2025-07-02 - Modern UI Components for Go & Templ.
* [uAdmin](https://github.com/uadmin/uadmin) ⭐ 352 | 🐛 25 | 🌐 Go | 📅 2024-10-10 - Fully featured web framework for Golang, inspired by Django.
* [WebGo](https://github.com/naughtygopher/webgo) ⭐ 306 | 🐛 2 | 🌐 Go | 📅 2025-01-25 - A micro-framework to build web apps with handler chaining, middleware, and context injection. With standard library-compliant HTTP handlers (i.e., `http.HandlerFunc`)..
* [Yokai](https://github.com/ankorstore/yokai) ⭐ 732 | 🐛 1 | 🌐 Go | 📅 2025-06-17 - Simple, modular, and observable Go framework for backend applications.

**[⬆ back to top](#contents)**

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) ⭐ 24 | 🐛 1 | 🌐 Go | 📅 2020-03-13 - An HTTP client for Server-Timing header.
* [CORS](https://github.com/rs/cors) ⭐ 2,794 | 🐛 7 | 🌐 Go | 📅 2024-12-12 - Easily add CORS capabilities to your API.
* [echo-middleware](https://github.com/faabiosr/echo-middleware) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2024-12-11 - Middleware for Echo framework with logging and metrics.
* [formjson](https://github.com/rs/formjson) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2015-12-17 - Transparently handle JSON input as a standard form POST.
* [go-fault](https://github.com/github/go-fault) ⭐ 509 | 🐛 0 | 🌐 Go | 📅 2025-06-19 - Fault injection middleware for Go.
* [go-server-timing](https://github.com/mitchellh/go-server-timing) ⚠️ Archived - Add/parse Server-Timing header.
* [Limiter](https://github.com/ulule/limiter) ⭐ 2,232 | 🐛 14 | 🌐 Go | 📅 2024-12-10 - Dead simple rate limit middleware for Go.
* [ln-paywall](https://github.com/philippgille/ln-paywall) ⭐ 155 | 🐛 18 | 🌐 Go | 📅 2019-02-24 - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
* [mid](https://github.com/bobg/mid) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2025-03-22 - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more.
* [rk-gin](https://github.com/rookie-ninja/rk-gin) ⭐ 50 | 🐛 2 | 🌐 Go | 📅 2024-04-09 - Middleware for Gin framework with logging, metrics, auth, tracing etc.
* [rk-grpc](https://github.com/rookie-ninja/rk-grpc) ⭐ 77 | 🐛 4 | 🌐 Go | 📅 2023-10-31 - Middleware for gRPC with logging, metrics, auth, tracing etc.
* [Tollbooth](https://github.com/didip/tollbooth) ⭐ 2,805 | 🐛 7 | 🌐 Go | 📅 2025-01-12 - Rate limit HTTP request handler.
* [XFF](https://github.com/sebest/xff) ⭐ 100 | 🐛 8 | 🌐 Go | 📅 2022-01-18 - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) ⭐ 3,264 | 🐛 11 | 🌐 Go | 📅 2024-06-06 - Painless middleware chaining for Go.
* [catena](https://github.com/codemodus/catena) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2018-08-25 - http.Handler wrapper catenation (same API as "chain").
* [chain](https://github.com/codemodus/chain) ⭐ 61 | 🐛 0 | 🌐 Go | 📅 2018-08-25 - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [gores](https://github.com/alioygur/gores) ⭐ 106 | 🐛 0 | 🌐 Go | 📅 2021-01-01 - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [interpose](https://github.com/carbocation/interpose) ⭐ 293 | 🐛 1 | 🌐 Go | 📅 2016-12-06 - Minimalist net/http middleware for golang.
* [mediary](https://github.com/HereMobilityDevelopers/mediary) ⭐ 88 | 🐛 0 | 🌐 Go | 📅 2020-06-24 - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
* [muxchain](https://github.com/stephens2424/muxchain) ⭐ 206 | 🐛 1 | 🌐 Go | 📅 2019-03-19 - Lightweight middleware for net/http.
* [negroni](https://github.com/urfave/negroni) ⭐ 7,530 | 🐛 9 | 🌐 Go | 📅 2025-05-03 - Idiomatic HTTP middleware for Golang.
* [render](https://github.com/unrolled/render) ⭐ 1,967 | 🐛 1 | 🌐 Go | 📅 2024-10-15 - Go package for easily rendering JSON, XML, and HTML template responses.
* [renderer](https://github.com/thedevsaddam/renderer) ⭐ 262 | 🐛 0 | 🌐 Go | 📅 2021-01-18 - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* [rye](https://github.com/InVisionApp/rye) ⚠️ Archived - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [stats](https://github.com/thoas/stats) ⭐ 593 | 🐛 8 | 🌐 Go | 📅 2022-12-12 - Go middleware that stores various information about your web application.

**[⬆ back to top](#contents)**

### Routers

* [alien](https://github.com/gernest/alien) ⭐ 134 | 🐛 3 | 🌐 Go | 📅 2024-03-24 - Lightweight and fast http router from outer space.
* [bellt](https://github.com/GuilhermeCaruso/bellt) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2022-07-18 - A simple Go HTTP router.
* [Bone](https://github.com/go-zoo/bone) ⭐ 1,287 | 🐛 3 | 🌐 Go | 📅 2019-05-06 - Lightning Fast HTTP Multiplexer.
* [Bxog](https://github.com/claygod/Bxog) ⭐ 101 | 🐛 0 | 🌐 Go | 📅 2022-09-07 - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [chi](https://github.com/go-chi/chi) ⭐ 20,055 | 🐛 82 | 🌐 Go | 📅 2025-06-20 - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) ⭐ 871 | 🐛 19 | 🌐 Go | 📅 2019-04-25 - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [FastRouter](https://github.com/razonyang/fastrouter) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2017-11-03 - a fast, flexible HTTP router written in Go.
* [goblin](https://github.com/bmf-san/goblin) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2024-12-26 - A golang http router based on trie tree.
* [gocraft/web](https://github.com/gocraft/web) ⭐ 1,512 | 🐛 24 | 🌐 Go | 📅 2020-10-01 - Mux and middleware package in Go.
* [Goji](https://github.com/goji/goji) ⭐ 970 | 🐛 6 | 🌐 Go | 📅 2022-07-26 - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [GoLobby/Router](https://github.com/golobby/router) ⭐ 22 | 🐛 2 | 🌐 Go | 📅 2022-03-30 - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language.
* [goroute](https://github.com/goroute/route) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2019-12-23 - Simple yet powerful HTTP request multiplexer.
* [GoRouter](https://github.com/vardius/gorouter) ⭐ 153 | 🐛 9 | 🌐 Go | 📅 2024-09-05 - GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [gowww/router](https://github.com/gowww/router) ⭐ 185 | 🐛 0 | 🌐 Go | 📅 2023-09-11 - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [httprouter](https://github.com/julienschmidt/httprouter) ⭐ 16,911 | 🐛 82 | 🌐 Go | 📅 2024-07-22 - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [httptreemux](https://github.com/dimfeld/httptreemux) ⭐ 618 | 🐛 8 | 🌐 Go | 📅 2024-07-10 - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [lars](https://github.com/go-playground/lars) ⭐ 384 | 🐛 1 | 🌐 Go | 📅 2019-05-15 - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [mux](https://github.com/gorilla/mux) ⭐ 21,452 | 🐛 35 | 🌐 Go | 📅 2024-08-15 - Powerful URL router and dispatcher for golang.
* [nchi](https://github.com/muir/nchi) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2025-07-01 - chi-like router built on httprouter with dependency injection based middleware wrappers
* [ngamux](https://github.com/ngamux/ngamux) ⭐ 71 | 🐛 0 | 🌐 Go | 📅 2025-01-27 - Simple HTTP router for Go.
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) ⭐ 456 | 🐛 12 | 🌐 Go | 📅 2022-05-08 - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [pure](https://github.com/go-playground/pure) ⭐ 150 | 🐛 0 | 🌐 Go | 📅 2023-07-13 - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [Siesta](https://github.com/VividCortex/siesta) ⭐ 348 | 🐛 0 | 🌐 Go | 📅 2023-12-12 - Composable framework to write middleware and handlers.
* [vestigo](https://github.com/husobee/vestigo) ⭐ 267 | 🐛 13 | 🌐 Go | 📅 2020-10-08 - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [violetear](https://github.com/nbari/violetear) ⭐ 107 | 🐛 1 | 🌐 Go | 📅 2022-09-27 - Go HTTP router.
* [xmux](https://github.com/rs/xmux) ⭐ 99 | 🐛 2 | 🌐 Go | 📅 2017-06-09 - High performance muxer based on `httprouter` with `net/context` support.
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) ⭐ 530 | 🐛 0 | 🌐 Go | 📅 2019-09-27 - A simple and fast HTTP router for Go.

**[⬆ back to top](#contents)**

## WebAssembly

* [dom](https://github.com/dennwc/dom) ⭐ 499 | 🐛 10 | 🌐 Go | 📅 2019-09-26 - DOM library.
* [Extism Go SDK](https://github.com/extism/go-sdk) ⭐ 125 | 🐛 5 | 🌐 Go | 📅 2025-05-14 - Universal, cross-language WebAssembly framework for building plug-in systems and polyglot apps.
* [go-canvas](https://github.com/markfarnan/go-canvas) ⭐ 263 | 🐛 4 | 🌐 Go | 📅 2020-12-09 - Library to use HTML5 Canvas, with all drawing within go code.
* [tinygo](https://github.com/tinygo-org/tinygo) ⭐ 16,415 | 🐛 499 | 🌐 Go | 📅 2025-06-30 - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
* [vert](https://github.com/norunners/vert) ⭐ 103 | 🐛 2 | 🌐 Go | 📅 2022-12-03 - Interop between Go and JS values.
* [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) ⭐ 199 | 🐛 5 | 🌐 Go | 📅 2025-03-23 - Run Go WASM tests in your browser.
* [webapi](https://github.com/gowebapi/webapi) ⭐ 179 | 🐛 3 | 🌐 Go | 📅 2022-12-21 - Bindings for DOM and HTML generated from WebIDL.

**[⬆ back to top](#contents)**

## Webhooks Server

* [webhook](https://github.com/adnanh/webhook) ⭐ 11,016 | 🐛 116 | 🌐 Go | 📅 2025-01-12 - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [webhooked](https://github.com/42Atomys/webhooked) ⭐ 40 | 🐛 7 | 🌐 Go | 📅 2024-11-24 - A webhook receiver on steroids: handle, secure, format and store a Webhook payload has never been easier.
* [WebhookX](https://github.com/webhookx-io/webhookx) ⭐ 233 | 🐛 13 | 🌐 Go | 📅 2025-07-02 - A webhooks gateway for message receiving, processing, and reliable delivering.

**[⬆ back to top](#contents)**

## Windows

* [d3d9](https://github.com/gonutz/d3d9) ⭐ 161 | 🐛 0 | 🌐 Go | 📅 2025-06-28 - Go bindings for Direct3D9.
* [go-ole](https://github.com/go-ole/go-ole) ⭐ 1,249 | 🐛 6 | 🌐 Go | 📅 2025-04-21 - Win32 OLE implementation for golang.
* [gosddl](https://github.com/MonaxGT/gosddl) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-04-30 - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

**[⬆ back to top](#contents)**

## Workflow Frameworks

*Libraries for creating Workflows.*

* [Cadence-client](https://github.com/uber-go/cadence-client) ⭐ 359 | 🐛 74 | 🌐 Go | 📅 2025-07-02 - A framework for authoring workflows and activities running on top of the Cadence orchestration engine made by Uber.
* [Dagu](https://github.com/dagu-go/dagu) ⭐ 2,358 | 🐛 113 | 🌐 Go | 📅 2025-07-01 - No-code workflow executor. it executes DAGs defined in a simple YAML format.
* [go-dag](https://github.com/rhosocial/go-dag) ⭐ 29 | 🐛 2 | 🌐 Go | 📅 2024-08-17 - A framework developed in Go that manages the execution of workflows described by directed acyclic graphs.
* [go-taskflow](https://github.com/noneback/go-taskflow) ⭐ 560 | 🐛 3 | 🌐 Go | 📅 2025-05-14 - A taskflow-like General-purpose Task-parallel Programming Framework with integrated visualizer and profiler.
* [workflow](https://github.com/luno/workflow) ⭐ 174 | 🐛 4 | 🌐 Go | 📅 2025-07-02 - A tech stack agnostic Event Driven Workflow framework.

**[⬆ back to top](#contents)**

## XML

*Libraries and tools for manipulating XML.*

* [XML-Comp](https://github.com/xml-comp/xml-comp) ⭐ 21 | 🐛 8 | 🌐 Go | 📅 2018-07-19 - Simple command line XML comparer that generates diffs of folders, files and tags.
* [xml2map](https://github.com/sbabiv/xml2map) ⭐ 63 | 🐛 3 | 🌐 Go | 📅 2021-12-07 - XML to MAP converter written Golang.
* [xmlquery](https://github.com/antchfx/xmlquery) ⭐ 470 | 🐛 18 | 🌐 Go | 📅 2025-04-16 - xmlquery is Golang XPath package for XML query.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) ⭐ 28 | 🐛 1 | 🌐 Go | 📅 2023-05-25 - Procedural XML generation API based on libxml2's xmlwriter module.
* [xpath](https://github.com/antchfx/xpath) ⭐ 719 | 🐛 17 | 🌐 Go | 📅 2025-04-21 - XPath package for Go.
* [zek](https://github.com/miku/zek) ⭐ 770 | 🐛 9 | 🌐 Go | 📅 2025-05-19 - Generate a Go struct from XML.

## Zero Trust

*Libraries and tools to implement Zero Trust architectures.*

* [Cosign](https://github.com/sigstore/cosign) ⭐ 5,033 | 🐛 261 | 🌐 Go | 📅 2025-07-01 - Container Signing, Verification and Storage in an OCI registry.
* [in-toto](https://github.com/in-toto/in-toto-golang) ⭐ 139 | 🐛 34 | 🌐 Go | 📅 2025-06-22 - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation.
* [OpenZiti](https://github.com/openziti/ziti) ⭐ 3,409 | 🐛 245 | 🌐 Go | 📅 2025-07-02 - A full, open source zero trust overlay network. Including numerous SDKs for numerous languages such as [golang](https://github.com/openziti/sdk-golang) ⭐ 107 | 🐛 19 | 🌐 Go | 📅 2025-07-02 allowing you to embed zero trust principles directly into your applications. The [OpenZiti Test Kitchen](https://github.com/openziti-test-kitchen) has numerous examples to draw inspiration from including a [zero trust ssh client - zssh](https://github.com/openziti-test-kitchen/zssh) ⭐ 39 | 🐛 0 | 🌐 Go | 📅 2025-06-25
* [Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) ⭐ 89 | 🐛 1 | 🌐 Go | 📅 2025-06-30 - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication.
* [Spire](https://github.com/spiffe/spire) ⭐ 1,980 | 🐛 157 | 🌐 Go | 📅 2025-07-02 - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms.

## Code Analysis

*Source code analysis tools, also known as Static Application Security Testing (SAST) Tools.*

* [apicompat](https://github.com/bradleyfalzon/apicompat) ⭐ 180 | 🐛 7 | 🌐 Go | 📅 2017-02-05 - Checks recent changes to a Go project for backwards incompatible changes.
* [asty](https://github.com/asty-org/asty) ⭐ 88 | 🐛 1 | 🌐 Go | 📅 2023-05-22 - Converts golang AST to JSON and JSON to AST.
* [blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) - blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages.
* [ChainJacking](https://github.com/Checkmarx/chainjacking) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2022-05-29 - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
* [Chronos](https://github.com/amit-davidson/Chronos) ⭐ 435 | 🐛 6 | 🌐 Go | 📅 2022-04-22 - Detects race conditions statically
* [dupl](https://github.com/mibk/dupl) ⭐ 351 | 🐛 4 | 🌐 Go | 📅 2024-03-20 - Tool for code clone detection.
* [errcheck](https://github.com/kisielk/errcheck) ⭐ 2,423 | 🐛 13 | 🌐 Go | 📅 2025-06-30 - Errcheck is a program for checking for unchecked errors in Go programs.
* [fatcontext](https://github.com/Crocmagnon/fatcontext) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2025-07-02 - Fatcontext detects nested contexts in loops or function literals.
* [go-checkstyle](https://github.com/qiniu/checkstyle) ⭐ 131 | 🐛 5 | 🌐 Go | 📅 2021-03-10 - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) ⭐ 946 | 🐛 4 | 🌐 Go | 📅 2021-11-08 - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [go-critic](https://github.com/go-critic/go-critic) ⭐ 1,971 | 🐛 135 | 🌐 Go | 📅 2025-06-15 - source code linter that brings checks that are currently not implemented in other linters.
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) ⭐ 661 | 🐛 6 | 🌐 Go | 📅 2023-02-19 - An easy way to find outdated dependencies of your Go projects.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) ⭐ 782 | 🐛 2 | 🌐 JavaScript | 📅 2023-11-30 - Web based Golang AST visualizer.
* [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2022-09-06 - iFood API SDK.
* [golangci-lint](https://github.com/golangci/golangci-lint) ⭐ 17,266 | 🐛 115 | 🌐 Go | 📅 2025-07-01 – A fast Go linters runner. It runs linters in parallel, uses caching, supports `yaml` config, has integrations with all major IDE and has dozens of linters included.
* [golines](https://github.com/segmentio/golines) ⭐ 1,074 | 🐛 72 | 🌐 Go | 📅 2025-04-14 - Formatter that automatically shortens long lines in Go code.
* [GoPlantUML](https://github.com/jfeliu007/goplantuml) ⭐ 2,020 | 🐛 41 | 🌐 Go | 📅 2025-06-11 - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
* [goreturns](https://github.com/sqs/goreturns) ⭐ 533 | 🐛 27 | 🌐 Go | 📅 2023-10-30 - Adds zero-value return statements to match the func return types.
* [gostatus](https://github.com/shurcooL/gostatus) ⭐ 244 | 🐛 1 | 🌐 Go | 📅 2025-05-18 - Command line tool, shows the status of repositories that contain Go packages.
* [lint](https://github.com/surullabs/lint) ⭐ 65 | 🐛 2 | 🌐 Go | 📅 2018-10-28 - Run linters as part of go test.
* [php-parser](https://github.com/z7zmey/php-parser) ⭐ 955 | 🐛 18 | 🌐 Go | 📅 2021-04-28 - A Parser for PHP written in Go.
* [revive](https://github.com/mgechev/revive) ⭐ 5,220 | 🐛 47 | 🌐 Go | 📅 2025-06-25 – \~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for `golint`.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) ⭐ 6,488 | 🐛 579 | 🌐 Go | 📅 2025-06-11 - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [testifylint](https://github.com/Antonboom/testifylint) ⭐ 141 | 🐛 35 | 🌐 Go | 📅 2025-07-01 – A linter that checks usage of [github.com/stretchr/testify](https://github.com/stretchr/testify) ⭐ 24,862 | 🐛 370 | 🌐 Go | 📅 2025-07-01.
* [tickgit](https://github.com/augmentable-dev/tickgit) ⭐ 324 | 🐛 14 | 🌐 Go | 📅 2023-12-18 - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
* [todocheck](https://github.com/preslavmihaylov/todocheck) ⭐ 433 | 🐛 12 | 🌐 Go | 📅 2025-03-09 - Static code analyser which links TODO comments in code with issues in your issue tracker.
* [unconvert](https://github.com/mdempsky/unconvert) ⭐ 383 | 🐛 7 | 🌐 Go | 📅 2025-02-16 - Remove unnecessary type conversions from Go source.
* [usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) ⭐ 45 | 🐛 1 | 🌐 Go | 📅 2025-05-24 - A linter that detect the possibility to use variables/constants from the Go standard library.
* [vacuum](https://github.com/daveshanley/vacuum) ⭐ 791 | 🐛 75 | 🌐 Go | 📅 2025-07-02 - An ultra-super-fast, lightweight OpenAPI linter and quality checking tool.
* [validate](https://github.com/mccoyst/validate) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2023-08-18 - Automatically validates struct fields with tags.
* [wrapcheck](https://github.com/tomarrell/wrapcheck) ⭐ 339 | 🐛 9 | 🌐 Go | 📅 2025-03-26 - A linter to check that errors from external packages are wrapped.

**[⬆ back to top](#contents)**

## Editor Plugins

*Plugin for text editors and IDEs.*

* [coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) ⭐ 575 | 🐛 13 | 🌐 TypeScript | 📅 2024-10-22 - This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) ⭐ 7,747 | 🐛 95 | 🌐 Go | 📅 2025-07-01 features to Vim/Neovim.
* [Go Doc](https://github.com/msyrus/vscode-go-doc) ⭐ 8 | 🐛 5 | 🌐 TypeScript | 📅 2024-02-08 - A Visual Studio Code extension for showing definition in output and generating go doc.
* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-mode](https://github.com/dominikh/go-mode.el) ⭐ 1,421 | 🐛 51 | 🌐 Emacs Lisp | 📅 2025-03-11 - Go mode for GNU/Emacs.
* [gocode](https://github.com/nsf/gocode) ⭐ 5,005 | 🐛 66 | 🌐 Go | 📅 2024-04-09 - Autocompletion daemon for the Go programming language.
* [goimports-reviser](https://github.com/incu6us/goimports-reviser) ⭐ 673 | 🐛 24 | 🌐 Go | 📅 2025-04-16 - Formatting tool for imports.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) ⭐ 3,418 | 🐛 82 | 🌐 Go | 📅 2020-07-21 - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* [gounit-vim](https://github.com/hexdigest/gounit-vim) ⭐ 25 | 🐛 0 | 🌐 Vim script | 📅 2018-10-29 - Vim plugin for generating Go tests based on the function's or method's signature.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) ⭐ 90 | 🐛 0 | 🌐 VimL | 📅 2016-06-28 - Vim plugin to highlight syntax errors on save.
* [vim-go](https://github.com/fatih/vim-go) ⭐ 16,153 | 🐛 39 | 🌐 Vim Script | 📅 2025-06-21 - Go development plugin for Vim.
* [vscode-go](https://github.com/golang/vscode-go) ⭐ 4,079 | 🐛 416 | 🌐 TypeScript | 📅 2025-07-02 - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch](https://github.com/eaburns/Watch) ⭐ 202 | 🐛 8 | 🌐 Go | 📅 2023-03-18 - Runs a command in an acme win on file changes.

**[⬆ back to top](#contents)**

## Go Generate Tools

* [envdoc](https://github.com/g4s8/envdoc) ⭐ 86 | 🐛 5 | 🌐 Go | 📅 2025-06-19 -  generate documentation for environment variables from Go source files.
* [generic](https://github.com/usk81/generic) ⭐ 49 | 🐛 2 | 🌐 Go | 📅 2021-01-13 - flexible data type for Go.
* [gocontracts](https://github.com/Parquery/gocontracts) ⭐ 113 | 🐛 1 | 🌐 Go | 📅 2019-01-26 - brings design-by-contract to Go by synchronizing the code with the documentation.
* [godal](https://github.com/mafulong/godal) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2021-10-23 - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm.
* [gonerics](https://github.com/bouk/gonerics) ⭐ 113 | 🐛 0 | 🌐 Go | 📅 2014-09-29 - Idiomatic Generics in Go.
* [gotests](https://github.com/cweill/gotests) ⭐ 5,083 | 🐛 63 | 🌐 Go | 📅 2023-09-12 - Generate Go tests from your source code.
* [gounit](https://github.com/hexdigest/gounit) ⭐ 85 | 🐛 1 | 🌐 Go | 📅 2018-08-17 - Generate Go tests using your own templates.
* [hasgo](https://github.com/DylanMeeus/hasgo) ⭐ 143 | 🐛 16 | 🌐 Go | 📅 2021-04-29 - Generate Haskell inspired functions for your slices.
* [options-gen](https://github.com/kazhuravlev/options-gen) ⭐ 95 | 🐛 8 | 🌐 Go | 📅 2025-05-25 - Functional options described by Dave Cheney's post "Functional options for friendly APIs".
* [re2dfa](https://gitlab.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
* [sqlgen](https://github.com/anqiansong/sqlgen) ⭐ 85 | 🐛 1 | 🌐 Go | 📅 2023-06-29 - Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN.
* [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
* [xgen](https://github.com/xuri/xgen) ⭐ 371 | 🐛 30 | 🌐 Go | 📅 2025-06-20 - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.

**[⬆ back to top](#contents)**

## Go Tools

* [decouple](https://github.com/bobg/decouple) ⭐ 30 | 🐛 3 | 🌐 Go | 📅 2025-02-12 - Find “overspecified” function parameters that could be generalized with interface types.
* [docs](https://github.com/go-oas/docs) ⭐ 46 | 🐛 9 | 🌐 Go | 📅 2023-05-05 - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.
* [go-callvis](https://github.com/TrueFurby/go-callvis) ⭐ 6,304 | 🐛 70 | 🌐 Go | 📅 2025-01-04 - Visualize call graph of your Go program using dot format.
* [go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) ⭐ 1,620 | 🐛 7 | 🌐 Go | 📅 2025-07-01 - Analyze and visualize the size of dependencies in compiled Golang binaries, providing insight into their impact on the final build.
* [go-swagger](https://github.com/go-swagger/go-swagger) ⭐ 9,794 | 🐛 606 | 🌐 Go | 📅 2025-06-27 - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [go-template-playground](https://bartventer.github.io/go-template-playground/) - An interactive environment to create and test Go templates.
* [godbg](https://github.com/tylerwince/godbg) ⭐ 206 | 🐛 2 | 🌐 Go | 📅 2019-04-20 - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
* [gomodrun](https://github.com/dustinblackman/gomodrun/) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2024-05-17 - Go tool that executes and caches binaries included in go.mod files.
* [gotemplate.io](https://gotemplate.io/) - Online tool to preview `text/template` templates live.
* [gotestdox](https://github.com/bitfield/gotestdox) ⭐ 143 | 🐛 3 | 🌐 Go | 📅 2024-06-08 - Show Go test results as readable sentences.
* [gothanks](https://github.com/psampaz/gothanks) ⭐ 127 | 🐛 1 | 🌐 Go | 📅 2023-02-18 - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
* [gotutor](https://github.com/ahmedakef/gotutor) ⭐ 34 | 🐛 0 | 🌐 Elm | 📅 2025-06-24 - Online Go Debugger & Visualizer.
* [igo](https://github.com/rocketlaunchr/igo) ⭐ 68 | 🐛 0 | 🌐 Go | 📅 2020-04-06 - An igo to go transpiler (new language features for Go language!)
* [modver](https://github.com/bobg/modver) ⭐ 20 | 🐛 9 | 🌐 Go | 📅 2025-04-16 - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules.
* [MoniGO](https://github.com/iyashjayesh/monigo) ⭐ 273 | 🐛 3 | 🌐 CSS | 📅 2025-01-09 - A performance monitoring library for Go applications. It provides real-time insights into application performance! 🚀
* [OctoLinker](https://github.com/OctoLinker/browser-extension) ⭐ 5,321 | 🐛 62 | 🌐 HTML | 📅 2023-10-02 - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [richgo](https://github.com/kyoh86/richgo) ⭐ 860 | 🐛 7 | 🌐 Go | 📅 2024-07-25 - Enrich `go test` outputs with text decorations.
* [roumon](https://github.com/becheran/roumon) ⭐ 217 | 🐛 1 | 🌐 Go | 📅 2025-02-12 - Monitor current state of all active goroutines via a command line interface.
* [rts](https://github.com/galeone/rts) ⭐ 251 | 🐛 0 | 🌐 Go | 📅 2022-10-29 - RTS: response to struct. Generates Go structs from server responses.
* [textra](https://github.com/ravsii/textra) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2023-05-01 - Extract Go struct field names, types and tags for filtering and exporting.
* [typex](https://github.com/dtgorski/typex) ⭐ 206 | 🐛 0 | 🌐 Go | 📅 2023-09-15 - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.

**[⬆ back to top](#contents)**

## Software Packages

*Software written in Go.*

**[⬆ back to top](#contents)**

### DevOps Tools

* [abbreviate](https://github.com/dnnrly/abbreviate) ⭐ 222 | 🐛 6 | 🌐 Go | 📅 2024-07-11 - abbreviate is a tool turning long strings in to shorter ones with configurable separators, for example to embed branch names in to deployment stack IDs.
* [alaz](https://github.com/ddosify/alaz) ⭐ 688 | 🐛 7 | 🌐 C | 📅 2024-10-02 - Effortless, Low-Overhead, eBPF-based Kubernetes Monitoring.
* [aptly](https://github.com/aptly-dev/aptly) ⭐ 2,671 | 🐛 200 | 🌐 Go | 📅 2025-06-21 - aptly is a Debian repository management tool.
* [aurora](https://github.com/xuri/aurora) ⭐ 601 | 🐛 7 | 🌐 JavaScript | 📅 2021-08-19 - Cross-platform web-based Beanstalkd queue server console.
* [awsenv](https://github.com/soniah/awsenv) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2018-07-17 - Small binary that loads Amazon (AWS) environment variables for a profile.
* [Balerter](https://github.com/balerter/balerter) ⭐ 306 | 🐛 5 | 🌐 Go | 📅 2024-07-22 - A self-hosted script-based alerting manager.
* [Blast](https://github.com/dave/blast) ⭐ 220 | 🐛 1 | 🌐 Go | 📅 2018-03-01 - A simple tool for API load testing and batch jobs.
* [bombardier](https://github.com/codesenberg/bombardier) ⭐ 6,409 | 🐛 18 | 🌐 Go | 📅 2025-03-25 - Fast cross-platform HTTP benchmarking tool.
* [bosun](https://github.com/bosun-monitor/bosun) ⚠️ Archived - Time Series Alerting Framework.
* [cassowary](https://github.com/rogerwelin/cassowary) ⭐ 802 | 🐛 6 | 🌐 Go | 📅 2025-06-10 - Modern cross-platform HTTP load-testing tool written in Go.
* [Ddosify](https://github.com/ddosify/ddosify) ⭐ 8,478 | 🐛 16 | 🌐 Go | 📅 2025-03-13 - High-performance load testing tool, written in Golang.
* [decompose](https://github.com/s0rg/decompose) ⭐ 104 | 🐛 3 | 🌐 Go | 📅 2024-12-13 - tool to generate and process Docker containers connections graphs.
* [DepCharge](https://github.com/centerorbit/depcharge) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2021-12-23 - Helps orchestrating the execution of commands across the many dependencies in larger projects.
* [dish](https://github.com/thevxn/dish) ⭐ 239 | 🐛 6 | 🌐 Go | 📅 2025-07-01 - A lightweight, remotely configurable monitoring service.
* [Docker](https://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) ⭐ 51 | 🐛 0 | 🌐 Shell | 📅 2025-04-02 - Docker image for building Go binaries for Windows with MinGW toolchain.
* [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) ⭐ 177 | 🐛 0 | 🌐 Go | 📅 2022-05-23 - A go library and an executable that produces valid Dockerfiles using various input channels.
* [dogo](https://github.com/liudng/dogo) ⭐ 272 | 🐛 5 | 🌐 Go | 📅 2019-03-15 - Monitoring changes in the source file and automatically compile and run (restart).
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) ⭐ 38 | 🐛 4 | 🌐 Go | 📅 2024-11-25 - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [drone-scp](https://github.com/appleboy/drone-scp) ⭐ 155 | 🐛 20 | 🌐 Go | 📅 2025-05-02 - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [Dropship](https://github.com/chrismckenzie/dropship) ⭐ 66 | 🐛 10 | 🌐 Go | 📅 2018-07-25 - Tool for deploying code via cdn.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) ⭐ 331 | 🐛 13 | 🌐 Go | 📅 2024-12-07 - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [fac](https://github.com/mkchoi212/fac) ⭐ 1,853 | 🐛 9 | 🌐 Go | 📅 2023-12-29 - Command-line user interface to fix git merge conflicts.
* [Flannel](https://github.com/flannel-io/flannel) ⭐ 9,172 | 🐛 29 | 🌐 Go | 📅 2025-06-30 - Flannel is a network fabric for containers, designed for Kubernetes.
* [Fleet device management](https://github.com/fleetdm/fleet) ⭐ 5,174 | 🐛 2,515 | 🌐 Go | 📅 2025-07-03 - Lightweight, programmable telemetry for servers and workstations.
* [gaia](https://github.com/gaia-pipeline/gaia) ⭐ 5,226 | 🐛 55 | 🌐 Go | 📅 2023-08-22 - Build powerful pipelines in any programming language.
* [ghorg](https://github.com/gabrie30/ghorg) ⭐ 1,769 | 🐛 14 | 🌐 Go | 📅 2025-07-02 - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket.
* [Gitea](https://github.com/go-gitea/gitea) ⭐ 49,348 | 🐛 2,704 | 🌐 Go | 📅 2025-07-03 - Fork of Gogs, entirely community driven.
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* [go-furnace](https://github.com/go-furnace/go-furnace) ⭐ 99 | 🐛 12 | 🌐 Go | 📅 2021-10-28 - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
* [go-rocket-update](https://github.com/mouuff/go-rocket-update) ⭐ 107 | 🐛 4 | 🌐 Go | 📅 2025-05-25 - A simple way to make self updating Go applications - Supports Github and Gitlab.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) ⭐ 1,618 | 🐛 16 | 🌐 Go | 📅 2024-08-17 - Enable your Go applications to self update.
* [gobrew](https://github.com/cryptojuice/gobrew) ⭐ 191 | 🐛 4 | 🌐 Shell | 📅 2020-05-21 - gobrew lets you easily switch between multiple versions of go.
* [gobrew](https://github.com/kevincobain2000/gobrew) ⭐ 395 | 🐛 1 | 🌐 Go | 📅 2025-06-11 - Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash.
* [godbg](https://github.com/sirnewton01/godbg) ⭐ 228 | 🐛 5 | 🌐 JavaScript | 📅 2018-07-09 - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) ⭐ 338 | 🐛 7 | 🌐 Go | 📅 2016-07-21 - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [govvv](https://github.com/ahmetalpbalkan/govvv) ⭐ 538 | 🐛 1 | 🌐 Go | 📅 2023-03-24 - “go build” wrapper to easily add version information into Go binaries.
* [grapes](https://github.com/yaronsumel/grapes) ⭐ 170 | 🐛 2 | 🌐 Go | 📅 2025-06-05 - Lightweight tool designed to distribute commands over ssh with ease.
* [GVM](https://github.com/moovweb/gvm) ⭐ 11,039 | 🐛 216 | 🌐 Shell | 📅 2024-08-08 - GVM provides an interface to manage Go versions.
* [Hey](https://github.com/rakyll/hey) ⭐ 19,023 | 🐛 182 | 🌐 Go | 📅 2024-08-20 - Hey is a tiny program that sends some load to a web application.
* [httpref](https://github.com/dnnrly/httpref) ⭐ 40 | 🐛 4 | 🌐 Go | 📅 2024-11-12 - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
* [jcli](https://github.com/jenkins-zh/jenkins-cli) ⭐ 405 | 🐛 82 | 🌐 Go | 📅 2025-03-28 - Jenkins CLI allows you manage your Jenkins as an easy way.
* [k3d](https://github.com/k3d-io/k3d) ⭐ 5,882 | 🐛 246 | 🌐 Go | 📅 2025-06-28 - Little helper to run CNCF's k3s in Docker.
* [k3s](https://github.com/k3s-io/k3s) ⭐ 30,105 | 🐛 126 | 🌐 Go | 📅 2025-07-02 - Lightweight Kubernetes.
* [k6](https://github.com/grafana/k6) ⭐ 28,164 | 🐛 794 | 🌐 Go | 📅 2025-06-30 - A modern load testing tool, using Go and JavaScript.
* [kala](https://github.com/ajvb/kala) ⭐ 2,154 | 🐛 14 | 🌐 Go | 📅 2024-02-19 - Simplistic, modern, and performant job scheduler.
* [kcli](https://github.com/cswank/kcli) ⭐ 220 | 🐛 1 | 🌐 Go | 📅 2020-01-04 - Command line tool for inspecting kafka topics/partitions/messages.
* [kind](https://github.com/kubernetes-sigs/kind) ⭐ 14,260 | 🐛 207 | 🌐 Go | 📅 2025-07-01 - Kubernetes IN Docker - local clusters for testing Kubernetes.
* [ko](https://github.com/google/ko) ⭐ 8,052 | 🐛 51 | 🌐 Go | 📅 2025-07-03 - Command line tool for building and deploying Go applications on Kubernetes
* [kool](https://github.com/kool-dev/kool) ⭐ 689 | 🐛 6 | 🌐 Go | 📅 2025-05-23 - Command line tool for managing Docker environments as an easy way.
* [kubeblocks](https://github.com/apecloud/kubeblocks) ⭐ 2,751 | 🐛 151 | 🌐 Go | 📅 2025-07-03 - KubeBlocks is an open-source control plane that runs and manages databases, message queues and other data infrastructure on K8s.
* [kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 116,092 | 🐛 2,613 | 🌐 Go | 📅 2025-07-03 - Container Cluster Manager from Google.
* [kubeshark](https://github.com/kubeshark/kubeshark) ⭐ 11,413 | 🐛 138 | 🌐 Go | 📅 2025-07-01 - API traffic analyzer for Kubernetes, inspired by Wireshark, purposely built for Kubernetes.
* [KubeVela](https://github.com/kubevela/kubevela) ⭐ 6,747 | 🐛 543 | 🌐 Go | 📅 2025-06-30 - Cloud native application delivery.
* [KubeVPN](https://github.com/kubenetworks/kubevpn) ⭐ 1,181 | 🐛 2 | 🌐 Go | 📅 2025-06-26 - KubeVPN offers a Cloud-Native Dev Environment that seamlessly connects to your Kubernetes cluster network.
* [KusionStack](https://github.com/KusionStack/kusion) ⭐ 1,140 | 🐛 48 | 🌐 Go | 📅 2025-06-30 - A unified programmable configuration techstack to deliver modern app in 'platform as code' and 'infra as code' approach.
* [kwatch](https://github.com/abahmed/kwatch) ⭐ 982 | 🐛 25 | 🌐 Go | 📅 2025-06-30 - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly.
* [lstags](https://github.com/ivanilves/lstags) ⭐ 338 | 🐛 10 | 🌐 Go | 📅 2023-05-11 - Tool and API to sync Docker images across different registries.
* [lwc](https://github.com/timdp/lwc) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2022-07-26 - A live-updating version of the UNIX wc command.
* [manssh](https://github.com/xwjdsh/manssh) ⭐ 300 | 🐛 2 | 🌐 Go | 📅 2022-02-11 - manssh is a command line tool for managing your ssh alias config easily.
* [Mantil](https://github.com/mantil-io/mantil) ⭐ 112 | 🐛 4 | 🌐 Go | 📅 2022-11-07 - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure.
* [minikube](https://github.com/kubernetes/minikube) ⭐ 30,626 | 🐛 532 | 🌐 Go | 📅 2025-07-02 - Run Kubernetes locally.
* [Moby](https://github.com/moby/moby) ⭐ 70,026 | 🐛 3,605 | 🌐 Go | 📅 2025-07-03 - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora](https://github.com/emicklei/mora) ⭐ 316 | 🐛 9 | 🌐 Go | 📅 2024-04-23 - REST server for accessing MongoDB documents and meta data.
* [ostent](https://github.com/ostrost/ostent) ⭐ 180 | 🐛 0 | 🌐 Go | 📅 2022-12-12 - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [Packer](https://github.com/mitchellh/packer) ⭐ 15,405 | 🐛 304 | 🌐 Go | 📅 2025-07-02 - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Pewpew](https://github.com/bengadbois/pewpew) ⭐ 435 | 🐛 1 | 🌐 Go | 📅 2024-06-19 - Flexible HTTP command line stress tester.
* [PipeCD](https://github.com/pipe-cd/pipecd) ⭐ 1,181 | 🐛 109 | 🌐 Go | 📅 2025-07-03 - A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications.
* [podinfo](https://github.com/stefanprodan/podinfo) ⭐ 5,638 | 🐛 30 | 🌐 Go | 📅 2025-06-27 - Podinfo is a tiny web application made with Go that showcases best practices of running microservices in Kubernetes. Podinfo is used by CNCF projects like Flux and Flagger for end-to-end testing and workshops.
* [Pomerium](https://github.com/pomerium/pomerium) ⭐ 4,329 | 🐛 136 | 🌐 Go | 📅 2025-07-03 - Pomerium is an identity-aware access proxy.
* [Rodent](https://github.com/alouche/rodent) ⭐ 33 | 🐛 6 | 🌐 Shell | 📅 2017-04-22 - Rodent helps you manage Go versions, projects and track dependencies.
* [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) ⭐ 364 | 🐛 20 | 🌐 Go | 📅 2025-06-30 - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) ⭐ 1,143 | 🐛 53 | 🌐 Go | 📅 2021-08-28 - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [s5cmd](https://github.com/peak/s5cmd) ⭐ 3,386 | 🐛 140 | 🌐 Go | 📅 2025-06-13 - Blazing fast S3 and local filesystem execution tool.
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) ⭐ 923 | 🐛 198 | 🌐 Go | 📅 2025-07-02 - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [script](https://github.com/bitfield/script) ⭐ 6,770 | 🐛 42 | 🌐 Go | 📅 2025-03-22 - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
* [sg](https://github.com/ChristopherRabotin/sg) ⭐ 8 | 🐛 2 | 🌐 Go | 📅 2016-10-28 - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
* [skm](https://github.com/TimothyYe/skm) ⭐ 977 | 🐛 4 | 🌐 Go | 📅 2025-06-21 - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* [StatusOK](https://github.com/sanathp/statusok) ⭐ 1,629 | 🐛 39 | 🌐 Go | 📅 2021-08-11 - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [tau](https://github.com/taubyte/tau) ⭐ 4,042 | 🐛 28 | 🌐 Go | 📅 2025-06-23 - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging.
* [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) ⭐ 278 | 🐛 31 | 🌐 Go | 📅 2023-11-10 - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
* [tf-profile](https://github.com/datarootsio/tf-profile) ⭐ 158 | 🐛 5 | 🌐 Go | 📅 2025-03-15 - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
* [tlm](https://github.com/yusufcanb/tlm) ⭐ 1,434 | 🐛 6 | 🌐 Go | 📅 2025-03-28 - Local cli copilot, powered by CodeLLaMa
* [traefik](https://github.com/containous/traefik) ⭐ 55,381 | 🐛 652 | 🌐 Go | 📅 2025-07-02 - Reverse proxy and load balancer with support for multiple backends.
* [trubka](https://github.com/xitonix/trubka) ⭐ 333 | 🐛 4 | 🌐 Go | 📅 2025-04-18 - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
* [uTask](https://github.com/ovh/utask) ⭐ 1,290 | 🐛 54 | 🌐 Go | 📅 2025-06-30 - Automation engine that models and executes business processes declared in yaml.
* [Vegeta](https://github.com/tsenart/vegeta) ⭐ 24,333 | 🐛 94 | 🌐 Go | 📅 2024-10-28 - HTTP load testing tool and library. It's over 9000!
* [wait-for](https://github.com/dnnrly/wait-for) ⭐ 17 | 🐛 1 | 🌐 Go | 📅 2023-02-02 - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) ⭐ 168 | 🐛 1 | 🌐 Go | 📅 2021-12-30 - Cli tool to remotely execute commands on Windows machines.

**[⬆ back to top](#contents)**

### Other Software

* [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
* [blocky](https://github.com/0xERR0R/blocky) ⭐ 5,434 | 🐛 67 | 🌐 Go | 📅 2025-07-02 - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
* [borg](https://github.com/crufter/borg) ⚠️ Archived - Terminal based search engine for bash snippets.
* [boxed](https://github.com/tejo/boxed) ⭐ 78 | 🐛 0 | 🌐 Go | 📅 2018-08-09 - Dropbox based blog engine.
* [Chapar](https://github.com/chapar-rest/chapar) ⭐ 581 | 🐛 7 | 🌐 Go | 📅 2025-06-28 - Chapar is a a cross-platform Postman alternative built with go, aims to help developers to test their api endpoints. it support http and grpc protocols.
* [Cherry](https://github.com/rafael-santiago/cherry) ⭐ 301 | 🐛 0 | 🌐 Go | 📅 2017-06-24 - Tiny webchat server in Go.
* [Circuit](https://github.com/gocircuit/circuit) ⭐ 1,988 | 🐛 13 | 🌐 Go | 📅 2023-10-18 - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) ⭐ 10,409 | 🐛 26 | 🌐 Go | 📅 2025-03-20 - Simulate bad network connections.
* [confd](https://github.com/kelseyhightower/confd) ⭐ 8,399 | 🐛 179 | 🌐 Go | 📅 2024-07-16 - Manage local application configuration files using templates and data from etcd or consul.
* [crawley](https://github.com/s0rg/crawley) ⭐ 302 | 🐛 3 | 🌐 Go | 📅 2025-06-18 - Web scraper/crawler for cli.
* [croc](https://github.com/schollz/croc) ⭐ 30,493 | 🐛 11 | 🌐 Go | 📅 2025-06-23 - Easily and securely send files or folders from one computer to another.
* [Documize](https://github.com/documize/community) ⭐ 2,265 | 🐛 46 | 🌐 JavaScript | 📅 2024-12-31 - Modern wiki software that integrates data from SaaS tools.
* [dp](https://github.com/scryinfo/dp) ⭐ 80 | 🐛 67 | 🌐 Go | 📅 2023-01-07 - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
* [drive](https://github.com/odeke-em/drive) ⭐ 6,721 | 🐛 287 | 🌐 Go | 📅 2024-02-09 - Google Drive client for the commandline.
* [Duplicacy](https://github.com/gilbertchen/duplicacy) ⭐ 5,470 | 🐛 322 | 🌐 Go | 📅 2025-05-03 - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
* [fjira](https://github.com/mk-5/fjira) ⭐ 181 | 🐛 21 | 🌐 Go | 📅 2024-11-13 - A fuzzy-search based terminal UI application for Attlasian Jira
* [Gebug](https://github.com/moshebe/gebug) ⭐ 632 | 🐛 18 | 🌐 Go | 📅 2024-04-24 - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
* [gfile](https://github.com/Antonito/gfile) ⭐ 752 | 🐛 7 | 🌐 Go | 📅 2023-02-25 - Securely transfer files between two computers, without any third party, over WebRTC.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) ⭐ 897 | 🐛 7 | 🌐 Go | 📅 2023-11-26 - App that displays updates for the Go packages in your GOPATH.
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) ⭐ 473 | 🐛 11 | 🌐 Go | 📅 2023-03-23 - Video streaming torrent client.
* [goblin](https://goblin.run) - Cloud builder for CLI's written in go lang
* [GoBoy](https://github.com/Humpheh/goboy) ⭐ 2,632 | 🐛 10 | 🌐 Go | 📅 2023-03-06 - Nintendo Game Boy Color emulator written in Go.
* [gocc](https://github.com/goccmack/gocc) ⭐ 642 | 🐛 25 | 🌐 Go | 📅 2025-04-21 - Gocc is a compiler kit for Go written in Go.
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2022-12-03 - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
* [Gokapi](https://github.com/Forceu/gokapi) ⭐ 1,991 | 🐛 18 | 🌐 Go | 📅 2025-06-26 - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload.
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [GoNB](https://github.com/janpfeifer/gonb) ⭐ 878 | 🐛 10 | 🌐 Go | 📅 2025-06-01 - Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab).
* [Gor](https://github.com/buger/gor) ⭐ 18,992 | 🐛 338 | 🌐 Go | 📅 2025-04-05 - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [Guora](https://github.com/meloalright/guora) ⭐ 674 | 🐛 7 | 🌐 Go | 📅 2023-01-31 - A self-hosted Quora like web application written in Go.
* [hoofli](https://github.com/dnnrly/hoofli) ⭐ 9 | 🐛 7 | 🌐 Go | 📅 2024-08-07 - Generate PlantUML diagrams from Chrome or Firefox network inspections.
* [hotswap](https://github.com/edwingeng/hotswap) ⭐ 397 | 🐛 0 | 🌐 Go | 📅 2024-05-24 - A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure.
* [hugo](https://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) ⭐ 360 | 🐛 0 | 🌐 Go | 📅 2022-11-24 - Browser accessible IDE. Designed for Go with Go.
* [joincap](https://github.com/assafmo/joincap) ⭐ 217 | 🐛 4 | 🌐 Go | 📅 2025-06-06 - Command-line utility for merging multiple pcap files together.
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 11,818 | 🐛 121 | 🌐 Go | 📅 2025-07-03 - Distributed POSIX file system built on top of Redis and AWS S3.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Layli](https://layli.app) - Draw pretty layout diagrams as code.
* [Leaps](https://github.com/jeffail/leaps) ⭐ 756 | 🐛 14 | 🌐 Go | 📅 2023-03-07 - Pair programming service using Operational Transforms.
* [lgo](https://github.com/yunabe/lgo) ⭐ 2,456 | 🐛 24 | 🌐 Go | 📅 2020-11-20 - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
* [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) ⭐ 7,692 | 🐛 405 | 🌐 C++ | 📅 2025-05-19 - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server) ⭐ 564 | 🐛 9 | 🌐 Go | 📅 2022-05-26 - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [myLG](https://github.com/mehrdadrad/mylg) ⭐ 2,715 | 🐛 14 | 🌐 Go | 📅 2020-02-26 - Command Line Network Diagnostic tool written in Go.
* [naclpipe](https://github.com/unix4fun/naclpipe) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2018-11-18 - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) ⭐ 328 | 🐛 9 | 🌐 Go | 📅 2023-12-27 - 🐮 cowsay is reborn. for a New Era.
* [nes](https://github.com/fogleman/nes) ⭐ 5,572 | 🐛 12 | 🌐 Go | 📅 2024-08-17 - Nintendo Entertainment System (NES) emulator written in Go.
* [Orbit](https://github.com/gulien/orbit) ⭐ 185 | 🐛 3 | 🌐 Go | 📅 2021-01-18 - A simple tool for running commands and generating files from templates.
* [peg](https://github.com/pointlander/peg) ⭐ 1,062 | 🐛 36 | 🌐 Go | 📅 2025-05-28 - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [Plik](https://github.com/root-gg/plik) ⭐ 1,580 | 🐛 46 | 🌐 Go | 📅 2025-06-14 - Plik is a temporary file upload system (Wetransfer like) in Go.
* [portal](https://github.com/SpatiumPortae/portal) ⭐ 1,655 | 🐛 28 | 🌐 Go | 📅 2024-08-20 - Portal is a quick and easy command-line file transfer utility from any computer to another.
* [restic](https://github.com/restic/restic) ⭐ 29,186 | 🐛 471 | 🌐 Go | 📅 2025-07-01 - De-duplicating backup program.
* [sake](https://github.com/alajmo/sake) ⭐ 700 | 🐛 13 | 🌐 Go | 📅 2025-04-18 - sake is a command runner for local and remote hosts.
* [scc](https://github.com/boyter/scc) ⭐ 7,441 | 🐛 53 | 🌐 Go | 📅 2025-06-29 - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) ⭐ 24,994 | 🐛 591 | 🌐 Go | 📅 2025-07-03 - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http](https://github.com/msoap/shell2http) ⭐ 1,415 | 🐛 5 | 🌐 Go | 📅 2025-06-18 - Executing shell commands via http server (for prototyping or remote control).
* [Snitch](https://github.com/lucasgomide/snitch) ⭐ 16 | 🐛 5 | 🌐 Go | 📅 2018-07-23 - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* [sonic](https://github.com/go-sonic/sonic) ⭐ 2,093 | 🐛 3 | 🌐 Go | 📅 2024-05-10 - Sonic is a Go Blogging Platform. Simple and Powerful.
* [Stack Up](https://github.com/pressly/sup) ⭐ 2,503 | 🐛 56 | 🌐 Go | 📅 2023-12-24 - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [stew](https://github.com/marwanhawari/stew) ⭐ 275 | 🐛 10 | 🌐 Go | 📅 2025-05-06 - An independent package manager for compiled binaries.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [tcpdog](https://github.com/mehrdadrad/tcpdog) ⭐ 260 | 🐛 1 | 🌐 Go | 📅 2021-07-21 - eBPF based TCP observability.
* [tinycare-tui](https://github.com/DMcP89/tinycare-tui) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-07-01 - Small terminal app that shows git commits from the last 24 hours and week, current weather, some self care advice, a joke, and you current todo list tasks.
* [toxiproxy](https://github.com/shopify/toxiproxy) ⭐ 11,338 | 🐛 91 | 🌐 Go | 📅 2025-06-30 - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vaku](https://github.com/lingrino/vaku) ⭐ 155 | 🐛 0 | 🌐 Go | 📅 2025-06-16 - CLI & API for folder-based functions in Vault like copy, move, and search.
* [vFlow](https://github.com/VerizonDigital/vflow) ⭐ 1,131 | 🐛 70 | 🌐 Go | 📅 2024-08-22 - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [Wave Terminal](https://waveterm.dev) - Wave is an open-source, AI-native terminal built for seamless developer workflows with inline rendering, a modern UI, and persistent sessions.
* [wellington](https://github.com/wellington/wellington) ⭐ 302 | 🐛 28 | 🌐 Go | 📅 2023-02-25 - Sass project management tool, extends the language with sprite functions (like Compass).
* [woke](https://github.com/get-woke/woke) ⭐ 489 | 🐛 41 | 🌐 Go | 📅 2024-05-07 - Detect non-inclusive language in your source code.
* [yai](https://github.com/ekkinox/yai) ⭐ 802 | 🐛 29 | 🌐 Go | 📅 2024-07-31 - AI powered terminal assistant.
* [zs](https://git.mills.io/prologic/zs) - an extremely minimal static site generator.

**[⬆ back to top](#contents)**

# Resources

*Where to discover new Go libraries.*

**[⬆ back to top](#contents)**

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) ⭐ 99 | 🐛 2 | 🌐 Go | 📅 2014-07-28 - Framework to compare the performance between different Go versions.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2017-03-17 - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) ⭐ 148 | 🐛 2 | 🌐 Go | 📅 2016-02-25 - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) ⭐ 1,656 | 🐛 23 | 🌐 Go | 📅 2023-09-12 - Go HTTP request router benchmark and comparison.
* [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-10-08 - Go JSON benchmark.
* [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) ⭐ 32 | 🐛 6 | 🌐 Go | 📅 2024-05-09 - benchmarks for machine learning inference in Go.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) ⭐ 2,124 | 🐛 4 | 🌐 Go | 📅 2025-01-17 - Go web framework benchmark.
* [go\_serialization\_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) ⭐ 1,593 | 🐛 6 | 🌐 Go | 📅 2025-06-12 - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) ⭐ 61 | 🐛 0 | 🌐 Go | 📅 2021-05-19 - Benchmarks of common basic operations for the Go language.
* [golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) ⭐ 136 | 🐛 0 | 🌐 Go | 📅 2025-05-08 - a collection of golang benchmarks.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed](https://github.com/feyeleanor/GoSpeed) ⭐ 126 | 🐛 1 | 🌐 Go | 📅 2024-03-25 - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench](https://github.com/jimrobinson/kvbench) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2019-09-28 - Key/Value database benchmark.
* [skynet](https://github.com/atemerev/skynet) ⭐ 1,059 | 🐛 32 | 🌐 C# | 📅 2023-11-10 - Skynet 1M threads microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) ⭐ 243 | 🐛 1 | 🌐 Go | 📅 2020-10-28 - Compare various Image resize algorithms for the Go language.

**[⬆ back to top](#contents)**

## Conferences

* [GoCon](https://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](https://golab.io/) - Florence, Italy.
* [GopherChina](https://gopherchina.org) - Shanghai, China.
* [GopherCon](https://www.gophercon.com/) - Varied Locations Each Year, USA.
* [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, Brazil.
* [GopherCon Europe](https://gophercon.eu/) - Berlin, Germany.
* [GopherCon India](https://gopherconindia.org/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GopherCon UK](https://www.gophercon.co.uk/) - London, UK.
* [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
* [GoWest Conference](https://www.gowestconf.com/) - Lehi, USA.

**[⬆ back to top](#contents)**

## E-Books

### E-books for purchase

* [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
* [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
* [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
* [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
* [Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) - An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly.
* [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
* [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
* [Go in Practice, Second Edition](https://www.manning.com/books/go-in-practice-second-edition)  - Your practical guide on the ins-and-outs of Go development, covering the standard library and the most important tools from Go’s powerful ecosystem.
* [Know Go: Generics](https://bitfieldconsulting.com/books/generics) - A guide to understanding and using generics in Go.
* [Lets-Go](https://lets-go.alexedwards.net) - A step-by-step guide to creating fast, secure and maintanable web applications with Go.
* [Lets-Go-Further](https://lets-go-further.alexedwards.net) - Advanced patterns for building APIs and web applications in Go.
* [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
* [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.

### Free e-books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build a blockchain from scratch in Go with gRPC](https://github.com/volodymyrprokopyuk/go-blockchain) ⭐ 430 | 🐛 0 | 🌐 Go | 📅 2025-03-14 - The foundational and practical guide for effectively learning and progressively building a blockchain from scratch in Go with gRPC.
* [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
* [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go AST Book (Chinese)](https://github.com/chai2010/go-ast-book) ⭐ 5,459 | 🐛 8 | 🌐 Go | 📅 2024-09-26 - A book focusing on Go `go/*` packages.
* [Go Faster](https://leanpub.com/gofaster) - This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster.
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2018-10-03 - in Persian.
* [Go with the domain](https://threedots.tech/go-with-the-domain/) - A book showing how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
* [GoBooks](https://github.com/dariubs/GoBooks) ⭐ 18,159 | 🐛 2 | 📅 2025-04-05 - A curated list of Go books.
* [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/golang/)
* [Practical Go Lessons](https://www.practical-go-lessons.com/)
* [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
* [The Go Programming Language](https://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) ⭐ 9,547 | 🐛 35 | 🌐 Go | 📅 2023-04-25
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) ⭐ 3,209 | 🐛 10 | 🌐 Go | 📅 2023-10-23

**[⬆ back to top](#contents)**

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) ⭐ 3,767 | 🐛 2 | 🌐 Go | 📅 2024-12-22 - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) ⭐ 73 | 🐛 0 | 📅 2018-03-04 - Go gopher Vector Data \[.ai, .svg].
* [gopher-logos](https://github.com/GolangUA/gopher-logos) ⭐ 130 | 🐛 1 | 📅 2021-06-24 - adorable gopher logos.
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers) ⭐ 600 | 🐛 8 | 🌐 Shell | 📅 2019-12-03
* [gophericons](https://github.com/shalakhin/gophericons) ⭐ 625 | 🐛 2 | 📅 2018-03-23
* [gopherize.me](https://github.com/matryer/gopherize.me) ⭐ 735 | 🐛 20 | 🌐 JavaScript | 📅 2021-08-23 - Gopherize yourself.
* [gophers](https://github.com/ashleymcnamara/gophers) ⭐ 3,019 | 🐛 1 | 🌐 Go | 📅 2025-01-23 - Gopher artworks by Ashley McNamara.
* [gophers](https://github.com/egonelbre/gophers) ⭐ 3,675 | 🐛 5 | 🌐 Go | 📅 2022-07-06 - Free gophers.
* [gophers](https://github.com/rogeralsing/gophers) ⭐ 58 | 🐛 2 | 📅 2020-08-06 - random gopher graphics.
* [gophers](https://github.com/sillecelik/go-gopher) ⭐ 153 | 🐛 0 | 📅 2025-01-28 - Gopher amigurumi toy pattern.
* [gophers](https://github.com/scraly/gophers) ⭐ 36 | 🐛 0 | 📅 2024-03-24 - Gophers by Aurélie Vache.

**[⬆ back to top](#contents)**

## Meetups

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
* [Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/)
* [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Bärner Go Meetup - Berne, Switzerland](https://www.meetup.com/berner-go-meetup/)
* [Go Ireland - Dublin](https://www.meetup.com/goireland/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBandung](https://www.meetup.com/GoBandung/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Athens](https://www.meetup.com/Athens-Gophers/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
* [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Milano](https://www.meetup.com/golang-milano/)
* [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Poland](https://www.meetup.com/Golang-Poland/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Roma](https://www.meetup.com/golangroma/)
* [Golang Rotterdam](https://www.meetup.com/golang-rotterdam/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/)
* [Golang Torino](https://www.meetup.com/golang-torino/)
* [Golang Turkey](https://kommunity.com/goturkiye)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Vienna, Austria](https://www.meetup.com/viennago/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Lagos Gophers](https://www.meetup.com/GolangNigeria/)
* [Nairobi Gophers](https://www.meetup.com/nairobi-gophers/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)
* [Zürich Gophers - Zurich, Switzerland](https://www.meetup.com/zurich-gophers/)

*Add the group of your city/country here (send **PR**)*

**[⬆ back to top](#contents)**

## Style Guides

* [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) ⭐ 1,509 | 🐛 0 | 📅 2024-08-02
* [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md) ⭐ 31,040 | 🐛 7,282 | 🌐 Go | 📅 2025-07-03
* [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
* [Google](https://google.github.io/styleguide/go/)
* [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst) ⭐ 16,177 | 🐛 181 | 🌐 Go | 📅 2025-06-30
* [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification) ⚠️ Archived
* [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
* [Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md) ⭐ 308 | 🐛 0 | 📅 2022-02-03
* [Uber](https://github.com/uber-go/guide/blob/master/style.md) ⭐ 16,615 | 🐛 24 | 🌐 Makefile | 📅 2025-06-16

**[⬆ back to top](#contents)**

## Social Media

### Twitter

* [@GoDiscussions](https://twitter.com/GoDiscussions)
* [@golang](https://twitter.com/golang)
* [@golang\_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangweekly](https://twitter.com/golangweekly)

**[⬆ back to top](#contents)**

### Reddit

* [r/golang](https://www.reddit.com/r/golang/)

**[⬆ back to top](#contents)**

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) ⭐ 519 | 🐛 0 | 📅 2021-07-13 - A curated list of awesome golang workshops.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) ⭐ 38,558 | 🐛 4 | 📅 2025-05-11 - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 32,682 | 🐛 41 | 🌐 Ruby | 📅 2024-06-02 - List of other amazingly awesome lists.
* [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2022-08-25 - Parse awesome-go README file and generate a new README file with repo info.
* [Code with Mukesh](https://codewithmukesh.com/categories/golang) - Software Engineer and Blogs @ codewithmukesh.com.
* [Coding Mystery](https://codingmystery.com) - Solve exciting escape-room-inspired programming challenges using Go.
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Go Blog](https://blog.golang.org) - The official Go blog.
* [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g\&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go Projects](https://github.com/golang/go/wiki/Projects) ⭐ 128,668 | 🐛 9,362 | 🌐 Go | 📅 2025-07-02 - List of projects on the Go community wiki.
* [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [go.dev](https://go.dev/) - A hub for Go developers.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) ⭐ 40 | 🐛 0 | 📅 2017-09-23 - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusively for Golang related Roles.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [Golang Nugget](https://golangnugget.com) - A weekly roundup of the best Go content, delivered to your inbox every Monday.
* [Golang Weekly](https://discu.eu/weekly/golang/) - Each monday projects, tutorials and articles about Go.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
* [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
* [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
* [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
* [pkg.go.dev](https://pkg.go.dev/) - Documentation for open source Go packages.
* [studygolang](https://studygolang.com) - The community of studygolang in China.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

**[⬆ back to top](#contents)**

### Tutorials

* [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) - Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
* [Build a Database in 1000 lines of code](https://link.medium.com/O9YQlx89Htb) - Build a NoSQL Database From Zero in 1000 Lines of Code.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) ⭐ 43,667 | 🐛 133 | 🌐 Go | 📅 2024-05-12 - Golang ebook intro how to build a web app with golang.
* [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
* [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) ⭐ 128 | 🐛 1 | 🌐 Go | 📅 2023-03-12 - Collection of programming design patterns implemented in Go.
* [Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8\&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) ⭐ 8,655 | 🐛 24 | 📅 2023-11-08 - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go in 7 days](https://github.com/harrytran103/7_days_of_go) ⭐ 153 | 🐛 0 | 🌐 Go | 📅 2025-05-04 - Learn everything about Go in 7 days (from a Nodejs developer).
* [Go Language Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go language Tutorial.
* [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [go-clean-template](https://github.com/evrone/go-clean-template) ⭐ 6,920 | 🐛 9 | 🌐 Go | 📅 2025-07-03 - Clean Architecture template for Golang services.
* [go-patterns](https://github.com/tmrts/go-patterns) ⭐ 26,629 | 🐛 65 | 🌐 Go | 📅 2024-05-14 - Curated list of Go design patterns, recipes and idioms.
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) ⭐ 4,736 | 🐛 1 | 🌐 Go | 📅 2023-02-02 - Examples of Golang compared to Node.js for learning.
* [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
* [golang-examples](https://github.com/SimonWaldherr/golang-examples) ⭐ 1,629 | 🐛 6 | 🌐 Go | 📅 2025-04-19 - Many examples to learn Golang.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
* [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
* [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
* [GraphQL with Go](https://hasura.io/learn/graphql/backend-stack/languages/go/) - Learn how to create a Go GraphQL server and client with code generation. Also includes creating REST endpoints.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [Hex Monscape](https://github.com/Haraj-backend/hex-monscape) ⭐ 79 | 🐛 2 | 🌐 Go | 📅 2024-07-18 - Getting started guidelines in writing maintainable code using Hexagonal Architecture.
* [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
* [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
* [How to Implement Role-Based Access Control (RBAC) Authorization in Golang](https://www.permit.io/blog/role-based-access-control-rbac-authorization-in-golang) - A guide to implementing Role-Based Access Control (RBAC) in Golang, including code examples, covering various methods to secure app endpoints with role-based authorization.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) ⭐ 19,367 | 🐛 40 | 🌐 Go | 📅 2025-06-24 - Learn Go with thousands of examples, exercises, and quizzes.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) ⭐ 22,946 | 🐛 65 | 🌐 Go | 📅 2025-06-17 - Learn Go with test-driven development.
* [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Series of articles in order to learn Golang language by concrete applications as example.
* [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
* [Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) - Everything about building, deploying and scaling Go applications in production.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Understanding Go in a visual way](https://dev.to/aurelievache/series/26234) - Learn Go visually
* [W3basic Go Tutorials](https://www.w3basic.com/golang/) - W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming.
* [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

**[⬆ back to top](#contents)**

### Guided Learning

* [The Go Developer Roadmap](https://roadmap.sh/golang) - A visual roadmap that new Go developers can follow through to help them learn Go.
* [The Go Learning Path](https://tutorialedge.net/paths/golang/) - A guided learning path containing a mix of free and premium resources.
* [The Go Skill Tree](https://labex.io/skilltrees/go) - A structured learning path that combines both free and premium resources.

**[⬆ back to top](#contents)**
