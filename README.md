# Awesome Go

A curated list of awesome Go frameworks, libraries and software.

### Contents


- [Awesome Go](#awesome-go)
    - [Language](#language)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Blockchain](#blockchain)
    - [Bot Building](#bot-building)
    - [Build Automation](#build-automation)
    - [Command Line](#command-line)
        - [Standard CLI](#standard-cli)
        - [Advanced Console UIs](#advanced-console-uis)
    - [Computer vision](#computer-vision)
    - [Concurrency](#concurrency)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [Cryptography](#cryptography)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
        - [Bit-packing and Compression](#bit-packing-and-compression)
        - [Bit Sets](#bit-sets)
        - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
        - [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
        - [Iterators](#iterators)
        - [Maps](#maps)
        - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
        - [Nullable Types](#nullable-types)
        - [Pipes](#pipes)
        - [Queues](#queues)
        - [Ranges](#ranges)
        - [Sets](#sets)
        - [Text Analysis](#text-analysis)
        - [Trees](#trees)
        - [Distributed locking](#distributed-locking)
    - [Database](#database)
        - [Caches](#caches)
        - [Databases Implemented in Go](#databases-implemented-in-go)
        - [Database Schema Migration](#database-schema-migration)
        - [Database Tools](#database-tools)
        - [SQL Query Builders](#sql-query-builders)
    - [Database Drivers](#database-drivers)
        - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
        - [Relational Database Drivers](#relational-database-drivers)
        - [NoSQL Database Drivers](#nosql-database-drivers)
        - [Search and Analytic Databases](#search-and-analytic-databases)    
    - [Date and Time](#date-and-time)
    - [Debug](#debug)
    - [Distributed Systems](#distributed-systems)
    - [Documentation](#documentation)
    - [Dynamic DNS](#dynamic-dns)
    - [e-Commerce](#e-commerce)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [File Handling](#file-handling)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [QrCode](#qrcode)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Memory allocation](#memory-allocation)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
        - [Uncategorized](#uncategorized)
    - [Natural Language Processing](#natural-language-processing)
        - [Language Detection](#language-detection)
        - [Morphological Analyzers](#morphological-analyzers)
        - [Slugifiers](#slugifiers)
        - [Tokenizers](#tokenizers)
        - [Translation](#translation)
        - [Transliteration](#transliteration)
    - [Networking](#networking)
        - [Proxy & Tunnel](#proxy-&-Tunnel)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Performance](#performance)
    - [Plugin](#plugin)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server Applications](#server-applications)
    - [Stream Processing](#stream-processing)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
        - [Formatters](#formatters)
        - [Markup Languages](#markup-languages)
        - [Parsers/Encoders/Decoders](#parsersencodersdecoders)
        - [Regular Expressions](#regular-expressions)
        - [Sanitation](#sanitation)
        - [Scrapers](#scrapers)
        - [RSS](#rss)
        - [Utility/Miscellaneous](#utilitymiscellaneous)    
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Virtualization](#virtualization)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
        - [Web Utilities](#web-utilities)
    - [WebAssembly](#webassembly)
    - [Windows](#windows)
    - [XML](#xml)
    - [Zero Trust](#zero-trust)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Style Guides](#style-guides)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)
        - [Guided Learning Paths](#guided-learning)
     

## Language

* Language Stuff *
  [Gollvm](https://go.googlesource.com/gollvm/) - LLVM-based Go compiler. It incorporates “gofrontend” (a Go language front end written in C++ and shared with GCCGO), a bridge component (which translates from gofrontend IR to LLVM IR), and a driver that sends the resulting IR through the LLVM back end.


## Audio and Music

*Libraries for manipulating audio.*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF).
* [flac](https://github.com/eaburns/flac) - No-frills native Go FLAC decoder that decodes FLAC files into byte slices.
* [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go.
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go.
* [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
* [malgo](https://github.com/gen2brain/malgo) - Mini audio library.
* [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder.
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib.
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [Authelia](https://github.com/authelia/authelia) - Authentication and authorization server providing 2-factor authentication and single sign-on (SSO) for your applications via a web portal.
* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* [authorization-proxy](https://github.com/AthenZ/authorization-proxy) - Reverse proxy to control HTTP/gPRC access with Athenz policy.
* [Authorizer](https://github.com/authorizerdev/authorizer) - open-source authentication and authorization solution for your applications. Bring your database and have complete control over the user information. You can self-host authorizer instances and connect to any database (Currently supports 11+ databases including Postgres, MySQL, SQLite, SQLServer, YugaByte, MariaDB, PlanetScale, CassandraDB, ScyllaDB, MongoDB, ArangoDB).
* [branca](https://github.com/essentialkaos/branca) - branca token [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+.
* [caddy-security](https://github.com/greenpau/caddy-security) - Authentication, Authorization, and Accounting (AAA) App and Plugin for Caddy v2. gem Implements Form-Based, Basic, Local, LDAP, OpenID Connect, OAuth 2.0 (Github, Google, Facebook, Okta, etc.), SAML Authentication. MFA/2FA with App Authenticators and Yubico. gem Authorization with JWT/PASETO tokens.
* [caddy-auth-portal](https://github.com/greenpau/caddy-auth-portal) - Authentication Plugin for Caddy v2 implementing Form-Based, Basic, Local, LDAP, OpenID Connect, OAuth 2.0 (Github, Google, Facebook, Okta, etc.), SAML Authentication. MFA with App Authenticators and Yubico.
* [casbin](https://github.com/casbin/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [Casdoor](https://github.com/casdoor/casdoor) - An open-source Identity and Access Management (IAM) / Single-Sign-On (SSO) platform with web UI supporting OAuth 2.0, OIDC, SAML and CAS.
* [Cerbos](https://github.com/cerbos/cerbos) - [Cerbos](https://cerbos.dev/) is the open core, language-agnostic, scalable authorization solution that makes user permissions and authorization simple to implement and manage by writing context-aware access control policies for your application resources.
* [charon](https://github.com/piotrkowalczuk/charon) - Authorization and authentication service.
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* [dex](https://github.com/dexidp/dex) - OpenID Connect Identity (OIDC) and OAuth 2.0 Provider with Pluggable Connectors.
* [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
* [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication.
* [go-jose](https://github.com/go-jose/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* [google-authenticator](https://github.com/tilaklodha/google-authenticator) - A small go program to generate the google authenticator code.
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* [gosession](http://github.com/Kwynto/gosession) - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, at least it tries to become one.
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* [gotrue](https://github.com/supabase/gotrue) - A JWT based API for managing users and issuing JWT tokens.
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* [hydra](https://github.com/ory/hydra) - OpenID Certified™ OpenID Connect & OAuth2 Server (OP, OpenID Provider) - cloud native, security-first, open source API security for your infrastructure. Written in Go. SDKs for any language.
* [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure and idiomatic web session management with pluggable backends.
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
* [jwt](https://github.com/cristalhq/jwt) - Safe, simple and fast JSON Web Tokens for Go.
* [jwtauth](https://github.com/go-chi/jwtauth) - About JWT authentication middleware for Go HTTP services.
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
* [jwt-go-eddsa](https://github.com/textileio/jwt-go-eddsa) - EdDSA signing method for [jwt-go](https://github.com/dgrijalva/jwt-go).
* [jwt](https://github.com/golang-jwt/jwt) - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs.
* [iam](https://github.com/marmotedu/iam) - IAM = Identity and Access Management.
* [keto](https://github.com/ory/keto) - A cloud native access control server providing best-practice patterns (RBAC, ABAC, ACL, AWS IAM Policies, Kubernetes Roles, ...) via REST APIs.
* [kratos](https://github.com/ory/kratos) - ORY Kratos is the first and only cloud native Identity and User Management System in the world. Finally, it is no longer necessary to implement a User Login process for the umpteenth time.
* [ladon](https://github.com/ory/ladon) - A SDK for access control policies: authorization for the microservice and IoT age. Inspired by AWS IAM policies.
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* [oauth2c](https://github.com/cloudentity/oauth2c) - User-friendly CLI for OAuth2.
* [opa](https://github.com/open-policy-agent/opa) - An open source, general-purpose policy engine.
* [OpenFGA](https://github.com/openfga/openfga) - A high-performance and flexible authorization/permission engine built for developers and inspired by [Google Zanzibar](https://research.google/pubs/pub48190/).
* [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
* [otpgen](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes.
* [otp](https://github.com/pquerna/otp) - One Time Password utilities Go / Golang.
* [OTP Gateway](https://github.com/knadh/otpgateway) - Standalone server for user address and OTP verification flows with pluggable providers (e-mail, SMS, bank penny drops etc.)
* [otpgo](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
* [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
* [permify](https://github.com/Permify/permify) - Permify is an open-source authorization service inspired by Google Zanzibar.
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications.
* [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
* [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* [sessions](https://github.com/gorilla/sessions) - gorilla/sessions provides cookie and filesystem sessions and infrastructure for custom session backends.
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
* [signedvalue](https://github.com/sashka/signedvalue) - Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`.
* [simplejwt](https://github.com/xyproto/simplejwt) - A simple JWT package.
* [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.
* [totp](https://github.com/arcanericky/totp) - Time-Based One-Time Password Code Generator.
* [vouch-proxy](https://github.com/vouch/vouch-proxy) - an SSO and OAuth / OIDC login solution for Nginx using the auth_request module.
* [xjwt](https://github.com/pquerna/xjwt) - Go library of small extensions for working with JWTs.
* [zitadel](https://github.com/zitadel/zitadel) - ZITADEL - The best of Auth0 and Keycloak combined. Built for the serverless era.

## Blockchain

*Tools for building blockchains.*

* [Avalanche](https://github.com/ava-labs/avalanchego) - Node implementation for the [Avalanche](https://avax.network/) network - a blockchains platform with high throughput, and blazing fast transactions.
* [blockchain_guide](https://github.com/yeasy/blockchain_guide) - Introduce blockchain related technologies, from theory to practice with bitcoin, ethereum and hyperledger.
* [cometbft](https://github.com/cometbft/cometbft) - A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm.
* [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) - A Framework for Building Public Blockchains in the Cosmos Ecosystem.
* [go-algorand](https://github.com/algorand/go-algorand) - Algorand's official implementation in Go.
* [go-ethereum](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol.
* [go-ibax](https://github.com/IBAX-io/go-ibax) - An innovative Blockchain Protocol Platform, which everyone can deploy their own applications quickly and easily, such as Dapp, DeFi, DAO, Cross-Blockchain transactions, etc.
* [go-primitives](https://github.com/trustwallet/go-primitives) - Go library that contains blockchain types and functions to work with them. It also supposed to contain extension functions for basic Go types.
* [goblockchain](https://github.com/alanvivona/goblockchain) - Simple Golang Blockchain Implementation.
* [gossamer](https://github.com/ChainSafe/gossamer) - A Go implementation of the Polkadot Host.
* [lnd](https://github.com/lightningnetwork/lnd) - The Lightning Network Daemon (lnd) - is a complete implementation of a [Lightning Network](https://lightning.network/) node. lnd has several pluggable back-end chain services including [btcd](https://github.com/btcsuite/btcd) (a full-node), [bitcoind](https://github.com/bitcoin/bitcoin), and [neutrino](https://github.com/lightninglabs/neutrino) (a new experimental light client).
* [solana-go](https://github.com/gagliardetto/solana-go) - Go library to interface with Solana JSON RPC and WebSocket interfaces.
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.

## Bot Building

*Libraries for building and working with bots.*

* [bot](https://github.com/go-telegram/bot) - Zero-dependencies Telegram Bot library with additional UI components.
* [echotron](https://github.com/NicoNex/echotron) - An elegant and concurrent library for Telegram Bots in Go.
* [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence.
* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) - Libary to write bots for twitch.tv chat.
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.
* [larry](https://github.com/ezeoleaf/larry) - Larry is a really simple Twitter bot generator that tweets random repositories from Github built in Go.
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [olivia](https://github.com/olivia-ai/olivia) - A chatbot built with an artificial neural network.
* [slack-bot](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots.
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [telego](https://github.com/mymmrac/telego) - Telegram Bot API library for Golang with full one-to-one API implementation.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [teleterm](hhttps://github.com/alfiankan/teleterm) - Telegram Bot Exec Terminal Command.
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* [wayback](https://github.com/wabarc/wayback) - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages.

## Build Automation

*Libraries and tools helping with build automation.*

* [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
* [anko](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages.
* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
* [goyek](https://github.com/goyek/goyek) - Create build pipelines in Go.
* [mage](https://github.com/magefile/mage) - Mage is a make/rake-like build tool using Go.
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [Task](https://github.com/go-task/task) - simple "Make" alternative.
* [taskctl](https://github.com/taskctl/taskctl) - Concurrent task runner.
* [xc](https://github.com/joerdav/xc) - ask runner with README.md defined tasks, executable markdown.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [acmd](https://github.com/cristalhq/acmd) -  Simple, useful and opinionated CLI package in Go.
* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* [carapace](https://github.com/rsteube/carapace) - Command argument completion generator for spf13/cobra.
* [carapace-bin](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer.
* [carapace-spec](https://github.com/rsteube/carapace-spec) - Define simple completions using a spec file.
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications.
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [clir](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
* [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idomatic way.
* [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [command-chain](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such like pipelining in unix shells.
* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [Dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile.
* [elvish](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* [go-andotp](https://github.com/grijul/go-andotp) - A CLI program to encrypt/decrypt [andOTP](https://github.com/andOTP/andOTP) files. Can be used as library as well.
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long.
* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* [kong](https://github.com/alecthomas/kong) - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (succesor to kingpin).
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* [mcli](https://github.com/jxskiss/mcli) - A minimal but very powerful cli library for Go.
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license.
* [readline](https://github.com/reeflective/readline) - Shell library with modern and easy to use UI features.
* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* [subcmd](https://github.com/bobg/subcmd) - Another approach to parsing and running subcommands. Works alongside the standard flag package.
* [survey](https://github.com/go-survey/survey) - Build interactive and accessible prompts with full support for windows and posix terminals.
* [strumt](https://github.com/antham/strumt) - Library to create prompt chain.
* [tablewriter](https://github.com/olekukonko/tablewriter) - Generate ASCII table on the fly.
* [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [version](https://github.com/mszostok/version) - Collects and displays CLI version information in multiple formats along with upgrade notice.
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.
* [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [box-cli-maker](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI.
* [bubble-table](https://github.com/Evertras/bubble-table) - An interactive table component for bubbletea.
* [bubbles](https://github.com/charmbracelet/bubbles) - TUI components for bubbletea.
* [Bubble Tea](https://github.com/charmbracelet/bubbletea) - The fun, functional and stateful way to build terminal apps. A Go framework based on The Elm Architecture. Bubble Tea is well-suited for simple and complex terminal applications, either inline, full-window, or a mix of both.
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
* [cfmt](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output.
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* [crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) - Dynamic configuration file templating tool for kubernetes manifest or general configuration files.
* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
* [gum](https://github.com/charmbracelet/gum) - A tool for glamorous shell scripts.
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* [go-palette](https://github.com/abusomani/go-palette) - Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts.
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
* [lipgloss](https://github.com/charmbracelet/lipgloss) - Declaratively define styles for color, format and layout in the terminal.
* [marker](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs.
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* [pterm](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
* [sampler](https://github.com/sqshq/sampler) - Tool for shell commands execution, visualization and alerting. Configured with a simple YAML file.
* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go.
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
* [table](https://github.com/tomlazar/table) - Small library for terminal color based tables.
* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
* [tcell](https://github.com/gdamore/tcell) - Tcell is an alternate terminal package, similar in some ways to termbox, but better in others.
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui).
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output.
* [termenv](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications.
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
* [survey](https://github.com/AlecAivazis/survey) - golang library for building interactive prompts with full support for windows and posix terminals.
* [tview](https://github.com/rivo/tview) - Rich interactive widgets for terminal-based UIs written in Go
* [vhs](https://github.com/charmbracelet/vhs) - Your CLI home video recorder.
* [yacspin](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.

## Computer vision

* [pigo](https://github.com/esimov/pigo) - Pigo is a purely Go face detection library based on Pixel Intensity Comparison-based Object detection paper.

## Concurrency

* [automaxprocs](https://github.com/uber-go/automaxprocs) - Automatically set GOMAXPROCS to match Linux container CPU quota.
* [go-multilock](https://github.com/atedja/go-multilock) - Multilock allows you to obtain multiple locks without deadlock. It also uses strings as locks, which allows multiple goroutines to synchronize independently without having to share common mutex objects.

## Configuration

*Libraries for configuration parsing.*

* [aconfig](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader.
* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want).
* [cfg](https://github.com/goburrow/cfg) - Configuration loader for Go applications.
* [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines.
* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* [config](https://github.com/num30/config) -  configure you app using file, environment variables, or flags in two lines of code.
* [configor](https://github.com/jinzhu/configor) - Golang Configuration tool that support YAML, JSON, TOML, Shell Environment.
* [configuration](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* [configuro](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
* [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* [env](https://github.com/junk1tm/env) - A lightweight package for loading environment variables into structs.
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment.
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* [envh](https://github.com/antham/envh) - Helpers to manage environment variables.
* [fig](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* [genv](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support.
* [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store.
* [go-conf](https://github.com/ThomasObenaus/go-conf) - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters.
* [go-ini](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files.
* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
* [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
* [go-yaml](https://github.com/goccy/go-yaml) - YAML support for the Go language.
* [yaml](https://github.com/go-yaml/yaml) - YAML support for the Go language.
* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* [GoLobby/config](https://github.com/golobby/config) - A lightweight yet powerful config package for Go projects.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [gonfig](https://github.com/milad-abbasi/gonfig) - Tag-based configuration parser which loads values from different providers into typesafe struct.
* [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
* [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration.
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* [hocon](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
* [ini](https://github.com/wlevene/ini) - INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file.
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
* [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
* [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era.
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables.
* [nfigure](https://github.com/muir/nfigure) - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML.
* [onion](http://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
* [piper](https://github.com/Yiling-J/piper) - Viper wrapper with config inheritance and key generation.
* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars).
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* [swap](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
* [typenv](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library.
* [uConfig](https://github.com/omeid/uconfig) - Lightweight, zero-dependency, and extendable configuration management.
* [viper](https://github.com/spf13/viper) - Go configuration with fangs.
* [xdg](https://github.com/adrg/xdg) - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*Tools for help with continuous integration.*

* [abstruse](https://github.com/bleenco/abstruse) - Abstruse 2.x.x is a lightweight, yet powerful distributed CI/CD written in Golang.
* [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages.
* [go-fuzz-action](https://github.com/jidicula/go-fuzz-action) - Use Go 1.18's built-in fuzz testing in GitHub Actions.
* [go-test-coverage](https://github.com/vladopajic/go-test-coverage) - Tool and GitHub action which reports issues when test coverage is below set threshold.
* [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
* [gotestfmt](https://github.com/GoTestTools/gotestfmt) - go test output for humans.
* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.
* [woodpecker](https://github.com/woodpecker-ci/woodpecker) - Woodpecker is a community fork of the Drone CI system.

## Cryptography

*Libraries and tools for cryptography.*

* [argon2](https://github.com/matthewhartstonge/argon2) - A pure Go Argon2 implementation for secure password hashing in Go.
* [argon2id](https://github.com/alexedwards/argon2id) - Argon2id password hashing and verification for Go.
* [bank-vaults](https://github.com/bank-vaults/bank-vaults) - Bank-Vaults is an umbrella project which provides various tools for Cloud Native secret management.
* [cert-manager](https://github.com/cert-manager/cert-manager) - Automatically provision and manage TLS certificates in Kubernetes.
* [certigo](https://github.com/square/certigo) - A utility to examine and validate certificates in a variety of formats.
* [cfssl](https://github.com/cloudflare/cfssl) - CFSSL is CloudFlare's PKI/TLS swiss army knife. It is both a command line tool and an HTTP API server for signing, verifying, and bundling TLS certificates.
* [crypki](https://github.com/theparanoids/crypki) - A simple service for interacting with an HSM or other PKCS#11 device.
* [crypto11](https://github.com/ThalesIgnite/crypto11) - Implement crypto.Signer and crypto.Decrypter for HSM-protected keys via PKCS#11.
* [FPE](https://github.com/capitalone/fpe) - An implementation of the NIST approved Format Preserving Encryption (FPE) FF1 and FF3 algorithms in Go.
* [GoKey](https://github.com/f-secure-foundry/GoKey) - The GoKey application implements an OpenPGP 3.4 USB smartcard written in pure Go.
* [go-anubis](https://github.com/dgryski/go-anubis) - anubis block cipher.
* [go-pkcs12](https://github.com/SSLMate/go-pkcs12) - Package pkcs12 implements some of PKCS#12 (also known as P12 or PFX).
* [go-util](https://github.com/gbolo/go-util) - PKCS11 Test Utility.
* [gossl](https://github.com/yakuter/gossl) - Cross platform, easy to use SSL/TLS toolset.
* [Keystore](https://github.com/pavlo-v-chernykh/keystore-go) - A go (golang) implementation of Java [KeyStore](https://docs.oracle.com/javase/7/docs/technotes/guides/security/crypto/CryptoSpec.html#KeyManagement) encoder/decoder.
* [kryptology](https://github.com/coinbase/kryptology) - Coinbase's advanced cryptography library.
* [kyber](https://github.com/dedis/kyber) - Advanced crypto library for the Go language.
* [masterkey](https://github.com/avahowell/masterkey) - secure interactive password manager with xchacha20poly1305, argon2id, and Go.
* [Minica](https://github.com/jsha/minica) - Minica is a simple CA intended for use in situations where the CA operator also operates each host where a certificate will be used. It automatically generates both a key and a certificate when asked to produce a certificate. It does not offer OCSP or CRL services. Minica is appropriate, for instance, for generating certificates for RPC systems or microservices.
* [ocicrypt](https://github.com/containers/ocicrypt) - Encryption libraries for Encrypted OCI Container images.
* [payshield-rest-api](https://github.com/scalpovich/payshield-rest-api) - Simple RestAPI to Thales payShield HSM.
* [pkcs11](https://github.com/miekg/pkcs11) - pkcs11 wrapper for Go.
* [pkcs11mod](https://github.com/namecoin/pkcs11mod) - Go library for creating pkcs11 modules.
* [sops](https://github.com/mozilla/sops) - sops is an editor of encrypted files that supports YAML, JSON, ENV, INI and BINARY formats and encrypts with AWS KMS, GCP KMS, Azure Key Vault and PGP.
* [vault](https://github.com/hashicorp/vault) - A tool for secrets management, encryption as a service, and privileged access management.
* [vault-plugin-secrets-pkcs11](https://github.com/bruj0/vault-plugin-secrets-pkcs11) - This is a plugin for HashiCorp Vault that implements storing data objects into HSM devices using PKCS#11.

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*

* [algorithms](https://github.com/maximelamure/algorithms) - An implementation in GO (golang) of the basic algorithms and data structure.
* [bpool](https://github.com/oxtoacart/bpool) - Package bpool implements leaky pools of byte arrays and Buffers as bounded channels.
* [dagger](https://github.com/autom8ter/dagger) - dagger is a blazing fast, concurrency safe, mutable, in-memory directed graph implementation with zero dependencies.
* [generic](https://github.com/zyedidia/generic) - An experimental collection of generic data structures written in Go.
* [generics](https://github.com/adonovan/generics) - Experiments with Go generics.
* [go-collections](https://github.com/mikhailswift/go-collections) - Generic utility functions for dealing with collections in Go.
* [go-datastructures](https://github.com/nsnikhil/go-datastructures) - This Project aims to port/build well known and commonly used data structures to GO.
* [go-hashlru](https://github.com/saurabh0719/go-hashlru) - A simple thread-safe, fixed size LRU written in Go. Based on (dominictarr's Hashlru Algorithm)[https://github.com/dominictarr/hashlru].
* [golang-lru](https://github.com/hashicorp/golang-lru) - This provides the lru package which implements a fixed-size thread safe LRU cache. It is based on the cache in Groupcache.
* [gofp](https://github.com/rbrahul/gofp) - Go does not provide many essential built in functions when it comes to the data structure such as slice and map.
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* [hashsplit](https://github.com/bobg/hashsplit) - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
* [immutable](https://github.com/benbjohnson/immutable) - Immutable collections for Go.
* [itc](https://github.com/fgrid/itc) - This project is based on the paper [Interval Tree Clocks](http://gsd.di.uminho.pt/members/cbm/ps/itc2008.pdf): A Logical Clock for Dynamic Systems' by Paulo Sergio Almeida, Carlos Baquero and Victor Fonte.
* [LeetCode](https://github.com/kylesliu/awesome-golang-algorithm) - LeetCode of algorithms with golang solution(updating).
* [LocklessGenericRingBuffer](https://github.com/GavinClarke0/LocklessGenericRingBuffer) - Single producer and multi-reader lockless ring buffer in go using generics from the go 1.18beta release. It is significantly faster than channels with the added type safety of generics compared to ring buffers using interfaces.
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.
* [ristretto](https://github.com/dgraph-io/ristretto) - A high performance memory-bound Go cache.
* [vellum](https://github.com/couchbase/vellum) - A Go library implementing an FST (finite state transducer).
* [zeropool](https://github.com/colega/zeropool) - Zero-allocation type-safe pool for Go.

### Bit-packing and Compression

* [bingo](https://github.com/iancmcc/bingo) - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes.
* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily.
* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.

### Bit Sets

* [bitmap](https://github.com/kelindar/bitmap) - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go.
* [bitset](https://github.com/bits-and-blooms/bitset) - Go package implementing bitsets.
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets.

### Bloom and Cuckoo Filters

* [bloom](https://github.com/bits-and-blooms/bloom) - Go package implementing Bloom filters.
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* [bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters.
* [bloomfilter](https://github.com/OldPanda/bloomfilter) - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [cuckoo-filter](https://github.com/linvon/cuckoo-filter) - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available.
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.

### Data Structure and Algorithm Collections

* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [gostl](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.

### Distributed locking

* [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock.
* [mongo-lock](https://github.com/square/mongo-lock) - Distributed locking with MongoDB.
* [redsync](https://github.com/go-redsync/redsync) - Distributed mutual exclusion lock using Redis.
* [redis-lock](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis.

### Iterators

* [goterator](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities.
* [iter](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms.

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for
additional ordered map implementations.

* [cmap](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
* [cmap](https://github.com/fwhezfwhez/cmap) - Provide concurent map for golang.
* [concurrent-map](https://github.com/orcaman/concurrent-map) - Thread-safe concurrent map for Go.
* [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go.
* [go-ordered-map](https://github.com/wk8/go-ordered-map) - Same as regular maps, but also remembers the order in which keys were inserted.
* [hashmap](https://github.com/cornelk/hashmap) - Lock-free thread-safe HashMap optimized for fastest read access.
* [haxmap](https://github.com/alphadose/haxmap) - Fastest and most memory efficient golang concurrent hashmap.
* [intintmap](https://github.com/brentp/intintmap) - Fast int64 -> int64 hash in golang.
* [maps](https://github.com/goradd/maps) - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc.
* [swiss](https://github.com/dolthub/swiss) - Golang port of Abseil's flat_hash_map.
* [ttlslicemap](https://github.com/yudai/ttlslicemap) - TTL Slice Map for Caching.

### Miscellaneous Data Structures and Algorithms

* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* [DSGO](https://github.com/PeterRK/DSGO) - Data Structure in Go.
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* [fsm](https://github.com/cocoonspace/fsm) - Finite-State Machine package.
* [genfuncs](https://github.com/nwillc/genfuncs) - Go 1.18+ generics package inspired by Kotlin's Sequence and Map.
* [Go](https://github.com/TheAlgorithms/Go) - Algorithms implemented in Go (for education).
* [Golang Algorithms and Data Structures](https://github.com/TomorrowWu/golang-algorithms) - Algorithms and data structures implemented in Golang with explanations and links to further readings.
* [go-generics](https://github.com/bobg/go-generics) - Generic slice, map, set, iterator, and goroutine utilities.
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* [go-rampart](https://github.com/francesconi/go-rampart) - Determine how intervals relate to each other.
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* [go-tuple](https://github.com/barweiss/go-tuple) - Generic tuple implementation for Go 1.18+.
* [go-slices](https://github.com/tideland/go-slices) - Process typed Go slices via generics and higher-order functions.
* [gofal](https://github.com/xxjwxc/gofal) - fractional api for Go.
* [gogu](https://github.com/esimov/gogu) - A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library.
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* [graph](https://github.com/dominikbraun/graph) - A library for creating generic graph data structures and modifying, analyzing, and visualizing them.
* [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [Lock free ring buffer](https://github.com/LENSHOOD/go-lock-free-ring-buffer) - Lock-free ring buffer by golang.
* [plinko](https://github.com/shipt/plinko) - A finite state machine and workflow orchestrator that compiles for fast execution, easy debugging, auto-generated documentation. Includes advanced features such as side-effect hooks. 
* [quadtree](https://github.com/s0rg/quadtree) - Generic, zero-alloc, 100%-test covered quadtree.
* [stl4go](https://github.com/chen3feng/stl4go) - This library contains generic containers and algorithms, it is designed to be STL for Golang.
* [slices](https://github.com/srfrog/slices) - Functions that operate on slices; like `package strings` but adapted to work with slices.
* [slices](https://github.com/twharmon/slices) - Pure, generic functions for slices.
* [ttlcache](https://github.com/ReneKroon/ttlcache) - In-memory string-interface{} cache with various time-based expiration options and callbacks.
* [uint128](https://github.com/lukechampine/uint128) - uint128 for Go.

### Nullable Types

* [nan](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
* [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
* [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures.

### Pipes

* [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) - Go module that processes work concurrently and returns output in a channel in the order of input.
* [parapipe](https://github.com/nazar256/parapipe) - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
* [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.

### Queues

* [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
* [memlog](https://github.com/embano1/memlog) - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka.
* [prioritywaitqueue](https://github.com/rvagg/go-prioritywaitqueue) - A blocking queue for prioritised coordination of goroutine execution.
* [timerqueue](https://github.com/jirenius/timerqueue) - A Go package providing timer queue for a list of items that should be processed in at a fixed duration of time after being added.
* [queue](https://github.com/nayuta87/queue) - Package queue provides a lock-free queue. The underlying algorithm is one proposed by Michael and Scott.
* [queue](https://github.com/eapache/queue) - Fast golang queue using ring-buffer.
* [queue](https://github.com/adrianbrad/queue) - Multiple thread-safe, generic queue implementations for Go.

### Ranges

* [iprangetree](https://github.com/gopk/iprangetree) - Simple IP range tree collection.
* [go-range](https://github.com/apo-diod/go-range) - Lib, that implements sets, intervals and sequences in Golang.
* [Go Range Store](https://github.com/tenta-browser/go-range-store) - Range store provides a simple datastructure providing efficient storage of a single value to many (consecutive) keys.
* [gorange](https://github.com/karrick/gorange) - gorange is a small Go library for interacting with range servers.

### Sets

* [dsu](https://github.com/ihebu/dsu) - Disjoint Set data structure implementation in Go.
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.

### Text Analysis

* [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* [go-edlib](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
* [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events.
* [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree.
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go.

### Trees

* [btree](https://github.com/google/btree) - In-memory B-Tree implementation for Go, useful as an ordered, mutable data structure.
* [btree](https://github.com/tidwall/btree) - B-tree implementation for Go.
* [btree](https://github.com/Michal-Leszczynski/btree) - BTree provides a simple, ordered, in-memory data structure for Go programs.
* [go-radix](https://github.com/armon/go-radix) - Golang implementation of Radix trees.
* [Go Merkle Tree](https://github.com/txaty/go-merkletree) - High performance Golang Merkle Tree implementation (supports parallelization).
* [hashsplit](http://github.com/bobg/hashsplit) - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
* [iavl](https://github.com/cosmos/iavl) - A versioned, snapshottable (immutable) AVL+ tree for persistent data.
* [mast](https://github.com/jrhy/mast) - Immutable, versioned, diffable map implementation of the Merkle Search Tree.
* [merkle](https://github.com/bobg/merkle) - Space-efficient computation of Merkle root hashes and inclusion proofs.
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* [prtree](https://github.com/tidwall/prtree) - Just a hybrid data structure that slams my [rtree](https://github.com/tidwall/rtree) and [ptree](https://github.com/tidwall/ptree) libraries into one.
* [radix](https://github.com/OneOfOne/radix) - radix implements a [radix tree](http://en.wikipedia.org/wiki/Radix_tree). The package only provides a single Tree implementation, optimized for sparse nodes.
* [rbtree](https://github.com/HuKeping/rbtree) - This is an implementation of Red-Black tree written by Golang.
* [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
* [treemap](https://github.com/igrmk/treemap) - Generic key-sorted map using a red-black tree under the hood.

## Database

### Caches

*Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases.*

* [2q](https://github.com/floatdrop/2q) - 2Q in-memory cache implementation.
* [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory  cache Go library.
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers.
* [cachego](https://github.com/faabiosr/cachego) - Golang Cache component for multiple drivers.
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* [DiceDB](https://github.com/DiceDB/dice) - An extremely simple Golang-based in-memory KV store that speaks the Redis dialect.
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [gdcache](https://github.com/ulovecode/gdcache) - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache.
* [giostorage](https://github.com/inkeliz/giostorage) - This package was designed to save small data, like user preferences, profile pictures and related names.
* [go-cache](https://github.com/viney-shih/go-cache) - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern.
* [go-freelru](https://github.com/elastic/go-freelru) - FreeLRU - A GC-less, fast and generic LRU hashmap library for Go.
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
* [gocache](https://github.com/eko/gocache) - A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
* [gocache](https://github.com/yuseferi/gocache) - A data race free Go ache library with high performance and auto pruge functionality.
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [imcache](https://github.com/erni27/imcache) - A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding.
* [nscache](https://github.com/no-src/nscache) - A Go caching framework that supports multiple data source drivers.
* [remember-go](https://github.com/rocketlaunchr/remember-go) - A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory).
* [rockscache](https://github.com/dtm-labs/rockscache) - The First Redis Cache Library To Ensure Eventual Consistency And Strong Consistency With DB.
* [theine](https://github.com/Yiling-J/theine-go) - High performance, near optimal in-memory cache with proactive TTL expiration and generics.
* [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
* [ttlcache](https://github.com/jellydator/ttlcache) - An in-memory cache with item expiration and generics.
* [ttlcache](https://github.com/cheshir/ttlcache) - In-memory key value storage with TTL for each record.

### Databases Implemented in Go

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* [bbolt](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
* [Bitcask](https://github.com/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go.
* [bolthold](https://github.com/timshannon/bolthold) - BoltHold is an embeddable NoSQL store for Go types built on BoltDB.
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [Cete](https://github.com/mosuka/cete) - distributed key value store server written in Go built on top of BadgerDB.
* [clover](https://github.com/ostafen/clover) - A lightweight document-oriented NoSQL database written in pure Golang.
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [Coffer](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions.
* [column](https://github.com/kelindar/column) - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
* [Databunker](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
* [datatable](https://github.com/datasweet/datatable) - datatable is a Go package to manipulate tabular data, like an excel spreadsheet. datatable is inspired by the pandas python package and the data.frame R structure.
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* [Dolt](https://github.com/dolthub/dolt) - SQL database that you can fork, clone, branch, merge, push and pull just like a git repository.
* [dtf](https://github.com/dtm-labs/dtf) - A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages.
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [FerretDB](https://github.com/FerretDB/FerretDB) - A truly Open Source MongoDB alternative [https://www.ferretdb.io](https://www.ferretdb.io/)
* [FlashDB](https://github.com/arriqaaq/flashdb) - FlashDB is an embeddable, in-memory key/value database in Go (with Redis like commands and super easy to read).
* [freecache](https://github.com/coocood/freecache) - A cache library for Go with zero GC overhead.
* [FrostDb](https://github.com/polarsignals/frostdb) - Coolest database around Embeddable column database written in Go.
* [galaxycache](https://github.com/vimeo/galaxycache) - galaxycache is a caching and cache-filling library, adapted from groupcache, intended as a replacement for memcached in many cases.
* [GhostDB](https://github.com/jakekgrog/GhostDB) - GhostDB is a distributed, in-memory, general purpose key-value data store that delivers microsecond performance at any scale.
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [go-threads](https://github.com/textileio/go-threads) - Server-less p2p database built on libp2p.
* [godis](https://github.com/hdt3213/godis) - A Golang implemented high-performance Redis server and cluster.
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go.
* [go-memdb](https://github.com/hashicorp/go-memdb) - Golang in-memory database built on immutable radix trees.
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go.
* [go-storage](https://github.com/aos-dev/go-storage) - An application-oriented unified storage layer for Golang.
* [Graphik](https://github.com/graphikDB/graphik) - Graphik is an identity-aware, permissioned, persistant document/graph database & pubsub server written in Go.
* [Graviton](https://github.com/deroproject/graviton) - Graviton Database is simple, fast, versioned, authenticated, embeddable key-value store database in pure GOLANG.
Graviton Database in short is like "ZFS for key-value stores" in which every write is tracked, versioned and authenticated with cryptographic proofs.
* [hare](https://github.com/jameycribbs/hare) - A simple database management system that stores each table as a text file of line-delimited JSON.
* [imdgo](https://github.com/inelpandzic/imdgo) - In-Memory Data Grid in Go or simply - a light-weight distributed in-memory key-value store inspired primarily by Hazelcast.
* [immudb](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [iodb](https://github.com/alpineiq/iodb) - A simple filesystem-based bigfile k/v store.
* [junodb](https://github.com/paypal/junodb) - JunoDB is PayPal's home-grown secure, consistent and highly available key-value store providing low, single digit millisecond, latency at any scale.
* [Kivik](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* [libcache](https://github.com/shaj13/libcache) - A Lightweight in-memory key:value cache library for Go.
* [LinDb](https://github.com/lindb/lindb) - LinDB is a scalable, high performance, high availability distributed time series database.
* [lungo](https://github.com/256dpi/lungo) - A MongoDB compatible embeddable database and toolkit for Go.
* [libradb](https://github.com/amit-davidson/LibraDB) - LibraDB is a simple database with less then 1000 lines of code for learning.
* [LotusDB](https://github.com/lotusdblabs/lotusdb) - LotusDB is the most advanced key-value store written in Go, extremely fast, compatible with LSM tree and B+ tree, and optimization of badger and bbolt.
* [M3](https://github.com/m3db/m3) - M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform. [m3db.io](m3db.io/)
* [MarketStore](https://github.com/alpacahq/marketstore) - MarketStore is a database server optimized for financial time-series data. You can think of it as an extensible DataFrame service that is accessible from anywhere in your system, at higher scalability.
* [Milvus](https://github.com/milvus-io/milvus) - An open source vector database powered by Faiss, NMSLIB and Annoy [milvus.io](https://milvus.io/).
* [minikeyvalue](https://github.com/geohot/minikeyvalue) - minikeyvalue is a ~1000 line distributed key value store, with support for replication, multiple machines, and multiple drives per machine.
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* [mydis](https://github.com/deejross/mydis) - Distributed, reliable database and cache library, server, and client. Inspired by Redis.
* [nutsdb](https://github.com/nutsdb/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.
* [objectbox-go](https://github.com/objectbox/objectbox-go) - High-performance embedded Object Database (NoSQL) with Go API.
* [Olric](https://github.com/buraksezer/olric) - Distributed cache and in-memory key/value data store. It can be used both as an embedded Go library and as a language-independent service.
* [PranaDB](https://github.com/cashapp/pranadb) - PranaDB is a distributed streaming database, designed from the outset to be horizontally scalable.
* [Pebble](https://github.com/cockroachdb/pebble) - Pebble is a LevelDB/RocksDB inspired key-value store focused on performance and internal usage by CockroachDB.
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* [pogreb](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads.
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [pudge](https://github.com/recoilme/pudge) - Fast and simple  key/value store written using Go's standard library.
* [RadonDB](https://github.com/radondb/radon) - RadonDB is an open source, Cloud-native MySQL database for unlimited scalability and performance.
* [redcon](https://github.com/tidwall/redcon) - Redcon is a custom Redis server framework for Go that is fast and simple to use. The reason for this library it to give an efficient server front-end for the [BuntDB](https://github.com/tidwall/buntdb) and [Tile38](https://github.com/tidwall/tile38) projects.
* [RedHub](https://github.com/IceFireDB/redhub) - High-performance Redis-Server multi-threaded framework, based on RawEpoll model.
* [redix](https://github.com/alash3al/redix) - Persistent real-time key-value store, with the same redis protocol with powerful features.
* [regatta](https://github.com/jamf/regatta) - Fast, simple, geo-distributed KV store built for cloud native era.
* [rosedb](https://github.com/flower-corp/rosedb) - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence.
* [spicedb](https://github.com/authzed/spicedb) - Open source permissions database inspired by Google Zanzibar.
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [tidis](https://github.com/yongman/tidis) - Distributed transactional NoSQL database, Redis protocol compatible using tikv as backend https://xiking.win/tidis
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* [tinykv](https://github.com/tidb-incubator/tinykv) - The TinyKV course builds a key-value storage system with the Raft consensus algorithm. It is inspired by [MIT 6.824](https://pdos.csail.mit.edu/6.824/) and [TiKV Project](https://github.com/tikv/tikv).
* [Titan](https://github.com/distributedio/titan) - Distributed Redis Protocol Compatible NoSQL Database (distributed implementation of Redis compatible layer based on [TiKV](https://github.com/tikv/tikv/))
* [tstorage](https://github.com/nakabonne/tstorage) - A fast time-series data storage library.
* [unitdb](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/trace application.
* [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.
* [Weaviate](https://github.com/weaviate/weaviate) - Weaviate is an open source vector database that stores both objects and vectors, allowing for combining vector search with structured filtering with the fault-tolerance and scalability of a cloud-native database, all accessible through GraphQL, REST, and various language clients.
* [ZoneDB](https://github.com/zonedb/zonedb) - The Public Zone Database (ZoneDB) is a free, open-source database containing a list and associated metadata of public DNS zones (domain name extensions). It attempts to be exhaustive, including current, retired, and withdrawn top-level domains and subdomains.

### Database Schema Migration

* [Atlas](https://github.com/ariga/atlas) - A modern tool for managing database schemas. [atlasgo.io](https://atlasgo.io/)
* [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
* [bytebase](https://github.com/bytebase/bytebase) - Web-based, zero-config, dependency-free database schema change and version control tool for teams.
* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
* [dbmate](https://github.com/amacneil/dbmate) - A lightweight, framework-agnostic database migration tool.
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
* [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) - CLI-friendly package for go-pg migrations management.
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
* [gondolier](https://github.com/emvi/gondolier) - Database migration library using struct decorators.
* [goose](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [gorm-seeder](https://github.com/Kachit/gorm-seeder) - Simple database seeder for Gorm ORM.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* [libschema](https://github.com/muir/libschema) - Define your migrations separately in each libary. Migrations for open source libraries. MySQL & PostgreSQL.
* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library.
* [migrator](https://github.com/larapulse/migrator) - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.
* [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
* [skeema](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

### Database Tools

* [boltdbpool](https://github.com/janos/boltdbpool) - Pool of Bolt DBs.
* [bucket](https://github.com/PumpkinSeed/bucket) - Optimized data structure framework for Couchbase specialized on one bucket usage.
* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers.
* [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
* [dg](https://github.com/codingconcepts/dg) - A fast data generator that produces CSV files from generated relational data.
* [dynago](https://github.com/twharmon/dynago) - Simplify working with AWS DynamoDB.
* [Gaea](https://github.com/XiaoMi/Gaea) - Gaea is a mysql proxy, it's developed by xiaomi b2c-dev team.
* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.
* [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
* [onedump](https://github.com/liweiyi88/onedump) - Database backup from different drivers to different destinations with one command and configuration.
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
* [pREST](https://github.com/prest/prest) - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
* [rump](https://github.com/stickermule/rump) - Hot sync two Redis databases using dumps.
* [vitess](https://github.com/vitessio/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

### SQL Query Builders

*SQL query builder, libraries for building and using SQL.*

* [buildsqlx](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL.
* [builq](https://github.com/cristalhq/builq) - Easily build SQL queries in Go.
* [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go.
* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
* [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* [gosql](https://github.com/twharmon/gosql) - SQL Query builder with better null values support.
* [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
* [Hotcoal](https://github.com/motrboat/hotcoal) - Secure your handcrafted SQL against injection.
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [jet](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
* [mpath](https://github.com/spacetab-io/mpath-go) - MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation.
* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [qry](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries.
* [sg](https://github.com/go-the-way/sg) - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go.
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.
* [sq](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go.
* [sqlc](https://github.com/kyleconroy/sqlc) - Generate type safe Go from SQL.
* [sqlf](https://github.com/leporo/sqlf) - Fast SQL query builder.
* [sqlingo](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go.
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* [TinySQL](https://github.com/tidb-incubator/tinysql) - TinySQL is a course designed to teach you how to implement a distributed relational database in Go. TinySQL is also the name of the simplifed version of [TiDB](https://github.com/pingcap/tidb).
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

###  Interfaces to Multiple Backends

* [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
* [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
* [go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) - Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries.
* [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).
* [goprisma](https://github.com/jensneuse/goprisma) - A Go wrapper for prisma to turn databases into GraphQL APIs using Go.
* [valkeyrie](https://github.com/abronan/valkeyrie) - Distributed Key/Value Store Abstraction Library written in Go.

### Relational Database Drivers

* [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
* [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
* [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
* [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
* [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
* [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
* [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
* [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
* [godror](https://github.com/godror/godror) - Oracle driver for Go, using the ODPI-C driver.
* [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
* [KSQL](https://github.com/VinGarcia/ksql) - A Simple and Powerful Golang SQL Library.
* [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
* [pig](https://github.com/alexeyco/pig) - Simple [pgx](https://github.com/jackc/pgx) wrapper to execute and [scan](https://github.com/georgysavva/scany) query results easily.
* [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.
* [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go.
* [sqlhooks](https://github.com/qustavo/sqlhooks) - Attach hooks to any database/sql driver.

### NoSQL Database Drivers

* [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
* [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
* [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
* [clickhouse](https://github.com/go-gorm/clickhouse) - Clickhouse support for GORM.
* [codis](https://github.com/CodisLabs/codis) - Proxy based Redis cluster solution supporting pipeline and scaling dynamically.
* [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.
* [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
* [go-clickhouse](https://github.com/uptrace/go-clickhouse) - ClickHouse client for Go.
* [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
* [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go.
* [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
* [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
* [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
* [gocosmos](https://github.com/btnguyen2k/gocosmos) - REST client and standard `database/sql` driver for Azure Cosmos DB.
* [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
* [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis.
* [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
* [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
* [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
* [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.
* [mdbx-go](https://github.com/torquem-ch/mdbx-go) - Go bindings to the [libmdbx](https://github.com/erthink/libmdbx).
* [mgm](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver).
* [mgo](https://github.com/globalsign/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
* [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
* [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
* [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
* [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
* [qmgo](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It's based on official MongoDB driver but easier to use like Mgo.
* [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
* [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
* [redis](https://github.com/go-redis/redis) - Redis client for Golang.
* [redis-port](https://github.com/CodisLabs/redis-port) - Parse redis rdb file, sync data between redis master and slave.
* [rueidis](https://github.com/redis/rueidis) - A fast Golang Redis client that supports Client Side Caching, Auto Pipelining, Generics OM, RedisJSON, RedisBloom, RediSearch, etc.
* [surrealdb.go](https://github.com/surrealdb/surrealdb.go) - SurrealDB Driver for Go.
* [tigerbeetle-go](https://github.com/tigerbeetle/tigerbeetle-go) - [TigerBeetle][https://tigerbeetle.com/] Go client.
* [ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) - Native and database/sql driver YDB (Yandex Database).
* [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

### Search and Analytic Databases

* [clickhouse-go](https://github.com/ClickHouse/clickhouse-go/) - ClickHouse SQL client for Go with a `database/sql` compability.
* [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
* [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
* [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
* [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go.
* [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
* [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine.
* [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

## Date and Time

*Libraries for working with dates and times.*

* [approx](https://github.com/goschtalt/approx) - A Duration extension supporting parsing/printing durations in days, weeks and years.
* [carbon](https://github.com/golang-module/carbon) - A simple, semantic and developer-friendly golang package for datetime.
* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* [cronrange](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges.
* [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go.
* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
* [go-anytime](https://github.com/ijt/go-anytime) - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance.
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* [go-str2duration](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more.
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
* [go-week](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates.
* [gostradamus](https://github.com/bykof/gostradamus) - A Go package for working with dates.
* [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.
* [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
* [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

## Debug

*Debugging Libraries, Memory Leak and Resource Leak Detection*

* [cozgo](https://github.com/urjitbhatia/cozgo) - Coz profiler Golang wrapper - Coz employs a novel technique we call causal profiling that measures optimization potential.
* [debugger](https://github.com/emad-elsaid/debugger) - Golang Debugger Graphical user interface for Go programming language. Based on Delve debugger.
* [fgtrace](https://github.com/felixge/fgtrace) - fgtrace is an experimental profiler/tracer that is capturing wallclock timelines for each goroutine. It's very similar to the Chrome profiler.
* [gohook](https://github.com/brahma-adshonor/gohook) - Library to hook golang function at runtime.
* [goleak](https://github.com/uber-go/goleak) - Goroutine leak detector to help avoid Goroutine leaks.
* [gops](https://github.com/google/gops) - gops is a command to list and diagnose Go processes currently running on your system.
* [gotraceui](https://github.com/dominikh/gotraceui) - Gotraceui is a tool for visualizing and analyzing Go execution traces.
* [holmes](https://github.com/mosn/holmes) - self-aware Golang profile dumper.
* [tiny-profiler](https://github.com/kakkoyun/tiny-profiler) - A Proof-of-concept CPU profiler written in Go using eBPF.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [Argo Events](https://github.com/argoproj/argo-events) - Event-driven workflow automation framework for Kubernetes.
* [arpc](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast.
* [cadence](https://github.com/uber/cadence) - Cadence is a distributed, scalable, durable, and highly available orchestration engine to execute asynchronous long-running business logic in a scalable and resilient way.
* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [Clymene](https://github.com/Clymene-project/Clymene) - The Clymene is a time-series data and logs collection platform for distributed systems inspired by [Prometheus](https://prometheus.io/) and [Jaeger](https://www.jaegertracing.io/).
* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
* [consistenthash](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas.
* [Crossplane](https://github.com/crossplane/crossplane) - Crossplane is a framework for building cloud native control planes without needing to write code. It has a highly extensible backend that enables you to build a control plane that can orchestrate applications and infrastructure no matter where they run, and a highly configurable frontend that puts you in control of the schema of the declarative API it offers.
* [cubequeue](https://github.com/paladium/cubequeue) - A simple transaction orchestrator with a swappable database and message queue.
* [dapr](https://github.com/dapr/dapr) - Dapr is a portable, event-driven, runtime for building distributed applications across cloud and edge.
* [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice.
* [distributed](https://github.com/smallnest/distributed) - examples of etcd distributed concurrency primitives.
* [Dkron](https://github.com/distribworks/dkron) - Distributed, fault tolerant job scheduling system. [Website](https://dkron.io)
* [dolphin](https://github.com/2SE/dolphin) - Distributed API Gateway
* [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT.
* [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
* [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
* [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures.
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* [DTM](https://github.com/dtm-labs/dtm) - A cross-language distributed transaction solution. Support saga, tcc, xa, 2 phases messages. [webpage](https://en.dtm.pub/) 
    * [go-saga-example](https://github.com/3langn/go-saga-example) - Implements Orchestration saga pattern in Go with docker compose and dtm.
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
* [easegress](https://github.com/megaease/easegress) - A cloud native high availability/performance traffic orchestration system with observability and extensibility.
* [easycar](https://github.com/wuqinqiang/easycar) - A simple distributed transaction framework implemented by go.
* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
* [encore](https://github.com/encoredev/encore) - Go backend framework for rapidly creating APIs and distributed systems.
* [erpc](https://github.com/andeya/erpc) - eRPC is an efficient, extensible and easy-to-use RPC framework. Suitable for RPC, Microservice, Peer-to-Peer, IM, Game and other fields.
* [evhub](https://github.com/tencentmusic/evhub) - EvHub supports the distribution of delayed, transaction, real-time and cyclic events. It is used in scenarios such as system decoupling, asynchronous calling and distributed transactions.
* [failured](https://github.com/andy2046/failured) -  adaptive accrual failure detector for distributed systems.
* [FLAC](https://github.com/nusdbsystem/FLAC) - A distributed KV-store with FaiLure-Aware Atomic Commit protocol supported.
* [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package.
* [Frontman](https://github.com/Frontman-Labs/frontman) - Frontman is an open-source API gateway written in Go that allows you to manage your microservices and expose them as a single API endpoint. It acts as a reverse proxy and handles requests from clients, routing them to the appropriate backend service.
* [fx](https://github.com/metrue/fx) - A Function as a Service tool makes a function as a container-based service in seconds.
* [gland](https://github.com/curtiseng/gland) - Distributed transaction across multi languages.
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* [gmsec](https://github.com/gmsec/micro) - A Go distributed systems development framework.
* [go-distributed-sys](https://github.com/shijuvar/go-distributed-sys) - An example for building event-driven distributed systems and microservices in Go with NATS JetStream, gRPC and CockroachDB.
* [go-doudou](https://github.com/unionj-cloud/go-doudou) - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity.
* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [go-kratos](https://github.com/go-kratos/kratos) - A Go framework for microservices.
  * [beer-shop](https://github.com/go-kratos/beer-shop) - An online shop application, mono-repo microservices demo for kratos.
  * [kratos-transport](https://github.com/tx7do/kratos-transport) - kratos transport layer extension.
  * [kratos-blog](https://github.com/tx7do/kratos-blog) - go-kratos + antd-vue3 = cms
  * [kratos-shop](https://github.com/aliliin/kratos-shop)
* [go-jsonrpc](https://github.com/filecoin-project/go-jsonrpc) - Low Boilerplate JSON-RPC 2.0 library.
* [go-micro](https://github.com/micro/go-micro) - A distributed systems development framework.
* [go-pdu](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network.
* [go-plugin](https://github.com/hashicorp/go-plugin) - Golang plugin system over RPC.
* [go-saga](https://github.com/itimofeev/go-saga) - Saga pattern implementation in Go.
* [go-saga](https://github.com/lysu/go-saga) - Implements saga-pattern in Go, another way to distribute transaction.
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services.
* [go-zero](https://github.com/zeromicro/go-zero) - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
* [gocelery](https://github.com/gocelery/gocelery) - Celery Distributed Task Queue in Go.
* [goharvest](https://github.com/obsidiandynamics/goharvest) - Go implementation of the [Transactional Outbox](https://microservices.io/patterns/data/transactional-outbox.html) pattern for Postgres and Kafka.
* [goutube](https://github.com/Brijeshlakkad/goutube) - Streaming utility to build largely-scalable, highly available, fast, and secure distributed streaming APIs.
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway) - gRPC to JSON proxy generator following the gRPC HTTP spec.
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* [gta](https://github.com/ycydsxy/gta) - A lightweight and reliable asynchronous task and transaction message library for Golang.
* [go-grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware) - Golang gRPC Middlewares: interceptor chaining, auth, logging, retries and more.
* [grabbit](https://github.com/wework/grabbit) - A lightweight transactional message bus on top of RabbitMQ.
* [Harbor](https://github.com/goharbor/harbor) - An open source trusted cloud native registry project that stores, signs, and scans content.
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* [hptx](https://github.com/CECTC/hptx) - high-performance non-intrusive distributed transaction solution, inspired by kubernetes, only for golang language.
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* [JuiceFS](https://github.com/juicedata/juicefs) - JuiceFS is a distributed POSIX file system built on top of Redis and S3.
* [ION](https://github.com/pion/ion) - Distributed Real-time Communication System.
* [iWF](https://github.com/indeedeng/iwf) - iWF is an all-in-one platform for developing long-running business processes. It offers a convenient abstraction layer for utilizing databases, ElasticSearch, message queues, durable timers, and more, with a clean, simple, and user-friendly interface.
* [karmada](https://github.com/karmada-io/karmada) - Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration.
* [KEDA](https://github.com/kedacore/keda) - KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes.
* [Kitex](https://github.com/cloudwego/kitex) - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice.
* [KrakenD](https://github.com/krakendio/krakend-ce) - KrakenD is an extensible, ultra-high performance API Gateway that helps you effortlessly adopt microservices and secure communications. KrakenD is easy to operate and run and scales out without a single point of failure. KrakenD Community Edition (or KrakenD-CE) is the open-source distribution of [KrakenD](https://www.krakend.io/).
* [kubevela](https://github.com/oam-dev/kubevela) - Modern Application Deployment System Based on Kubernetes and OAM.
* [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
* [linkerd2](https://github.com/linkerd/linkerd2) - Ultralight, security-first service mesh for Kubernetes. Main repo for Linkerd 2.x.
* [Lotus](https://github.com/filecoin-project/lotus) - Lotus is an implementation of the Filecoin Distributed Storage Network. For more details about Filecoin, check out the [Filecoin Spec](https://spec.filecoin.io).
* [lura](https://github.com/luraproject/lura) - Ultra performant API Gateway framework with middlewares.
* [micro](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond.
* [mortar](https://github.com/go-masonry/mortar) - Mortar is a GO framework/library for building gRPC (and REST) web services. Mortar has out-of-the-box support for configuration, application metrics, logging, tracing, profiling, dependency injection and more. While it comes with predefined defaults Mortar gives you total control to fully customize it.
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* [netramesh](https://github.com/avito-tech/netramesh) - Ultra light service mesh for any orchestrator.
* [Nomad](https://github.com/hashicorp/nomad) - Nomad is an easy-to-use, flexible, and performant workload orchestrator that can deploy a mix of microservice, batch, containerized, and non-containerized applications. Nomad is easy to operate and scale and has native Consul and Vault integrations.
* [NSQ](https://github.com/nsqio/nsq) - NSQ is a realtime distributed messaging platform designed to operate at scale, handling billions of messages per day.
* [odin](https://github.com/tal-tech/odin) - Odin is a Rpcx-based rpc framework, reference [rpcx](https://rpcx.io/)
* [odin](https://github.com/theycallmemac/odin) - A programmable, observable and distributed job orchestration system.
* [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC router with Protobuf.
* [podinfo](https://github.com/stefanprodan/podinfo) - Go microservice template for Kubernetes.
* [polaris](https://github.com/polarismesh/polaris) - Service Discovery and Governance Center for Distributed and Microservice Architecture.
* [servicetmpl](https://github.com/jfeng45/servicetmpl) - Microservice template project for Go and gRPC
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* [rain](https://github.com/cenkalti/rain) - BitTorrent client and library.
* [raft](https://github.com/etcd-io/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [resgate](https://github.com/resgateio/resgate) - A Realtime API Gateway used with NATS to build REST, real time, and RPC APIs, where all your clients are synchronized seamlessly. [website](https://resgate.io/)
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* [saga-product](https://github.com/minghsu0107/saga-product) - Transaction services of the [saga pattern implementation](https://github.com/minghsu0107/saga-example).
* [sago](https://github.com/piotrpersona/sago) - Implementation of SAGA and Event Sourcing pattern in Go.
* [seata-go](https://github.com/seata/seata-go) - Go Implementation For Seata.
* [Sealos](https://github.com/labring/sealos) - Sealos is a Kubernetes distribution offering comprehensive solutions for both public and private clouds.
* [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files! Blob store has O(1) disk seek, cloud tiering. Filer supports Cloud Drive, cross-DC active-active replication, Kubernetes, POSIX FUSE mount, S3 API, S3 Gateway, Hadoop, WebDAV, encryption, Erasure Coding.
* [Service Weaver](https://github.com/ServiceWeaver/weaver) - Service Weaver is a programming framework for writing, deploying, and managing distributed applications.
* [Semaphore](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator.
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)).
* [telepresence](https://github.com/telepresenceio/telepresence) - Local development against a remote Kubernetes or OpenShift cluster [www.telepresence.io](https://www.telepresence.io/).
* [temporal](https://github.com/temporalio/temporal) - Temporal is a microservice orchestration platform which enables developers to build scalable applications without sacrificing productivity or reliability.
    * [temporal-saga-grpc](https://github.com/kevinmichaelchen/temporal-saga-grpc) - Using Temporal to orchestrate distributed transactions (sagas) across Golang microservices.
    * [tempokerja](https://github.com/harunnryd/tempokerja) - This is a example code of temporal.io (Microservice Orchestrator).
    * [temporal-ecommerce](https://github.com/temporalio/temporal-ecommerce) - This is a demo app for a blogpost series showing the process of developing a full ecommerce application.
    * [temporal-workflow-golang-example](https://github.com/alameddinc/temporal-workflow-golang-example)
    * [temporal-go-helpers](https://github.com/Courtsite/temporal-go-helpers) - Common convenience methods, and developer ergonomics for Temporal's Go SDK.
    * [sample-temporal-app](https://github.com/render-examples/sample-temporal-app) - A small app that uses the Temporal Go SDK to trigger and execute workflows.
    * [crypto](https://github.com/RTradeLtd/crypto) - Temporal's object encryption and decryption library and CLI tool.
    * [temporal-coffeeshop](https://github.com/Omar-V2/temporal-coffeeshop) - Demo application showcasing some of temporal's feature in a micro-service context.
    * [go-temporal-iwf-demo](https://github.com/leowmjw/go-temporal-iwf-demo) - Demo of Temporal + iWF for Payment, Finance, Subscription.
    * [benchmark-workers](https://github.com/temporalio/benchmark-workers) - Pre-written workflows and activities useful for benchmarking Temporal.
    * [temporal-proxy](https://github.com/robryanx/temporal-proxy) - Synchronous Proxy Sample. This sample demonstrates how to achieve synchronous interaction with a main workflow.
    * [temporal-microservice](https://github.com/esgungor/temporal-microservice) - Example project for Temporal microservice orchestarion.
    * [temporalio-cart](https://github.com/wladioh/temporalio-cart)
    * [saga-temporal](https://github.com/cv65kr/saga-temporal) - Distributed SAGA based on Temporal.io
    * [temporal_microservices](https://github.com/goltech/temporal_microservices) - Temporal workflow for orchestration, service discovery, load balancing of go microservices.
    * [temporalio-subscription-example-go](https://github.com/DJSanti/temporalio-subscription-example-go) - Temporal promises to help you build long-lasting apps. With this example, you'll learn how to integrate key Temporal concepts into an email-based subscription program.
    * [temporal-workflow-payments](https://github.com/naguigui/temporal-workflow-payments)
    * [temporal-parent-child-concurrent](https://github.com/helvellyn-io/temporal-parent-child-concurrent) - Registers and runs two child workflows and two activites.
    * [temporal-rabbit-poc](https://github.com/carmo-evan/temporal-rabbit-poc) - This is an example of how temporal can be used in tandem with a message queue such as Rabbit MQ.
* [Timecraft](https://github.com/stealthrocket/timecraft) - Timecraft is a software runtime that executes WebAssembly modules with sandboxing, task orchestration, and time travel capabilities.
* [Tork](https://github.com/runabol/tork) - Highly-scalable, general-purpose distributed workflow engine.
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.
* [transparent](https://github.com/juntaki/transparent) - Transparent cache and distributed commit to key-value store.
* [Vald](https://github.com/vdaas/vald) -  A Highly Scalable Distributed Vector Search Engine.
* [Vearch](https://github.com/vearch/vearch) - scalable distributed system for efficient similarity search of deep learning vectors.
* [VolantMQ](https://github.com/VolantMQ/volantmq) - High-Performance MQTT Server.
* [Uhaha](https://github.com/tidwall/uhaha) - Uhaha is a framework for building highly available data applications in Go.
* [xds](https://github.com/kitex-contrib/xds) - xDS is a set of discovery services that enables date-plane to discover various dynamic resources via querying from the management servers.

## Documentation

* [docuapi](https://github.com/bep/docuapi) - Beautiful multilingual API documentation theme for Hugo.
* [gomarkdoc](https://github.com/princjef/gomarkdoc) - Generate markdown documentation for Go (golang) code.
* [swag](https://github.com/swaggo/swag) - Automatically generate RESTful API documentation with Swagger 2.0 for Go.

## Dynamic DNS

*Tools for updating dynamic DNS records.*

* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.

## e-Commerce

* [ecommerce-api](https://github.com/paw1a/ecommerce-api) - Rest api of e-commerce web application
* [ecommerce](https://github.com/golang-app/ecommerce) - GoCommerce is an e-commerce application written in Go and ReactJS.
* [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
* [GoGonicEcommerceApi](https://github.com/melardev/GoGonicEcommerceApi) - Ecommerce Rest API application built in Go with Gin Gonic + Gorm.
* [go-shop-b2c](https://github.com/YangCheng0121/go-shop-b2c)
* [golang-clean-architecture-banking-transfer](https://github.com/GSabadini/golang-clean-architecture-banking-transfer) - Simple API for banking routines using a Clean Architecture in Golang.
* [Gopify](https://github.com/oussama4/gopify) - Gopify is a simple package for developing Shopify applications in Go.
* [litecart](https://github.com/shurco/litecart) - Litecart is an open source shopping-cart in 1 file of embedded database (SQLite), convenient dashboard UI and simple site.
* [mollie-api-go](https://github.com/VictorAvelar/mollie-api-go) - Golang wrapper for Mollie's REST API with full resource coverage.
* [moneygo](https://github.com/aclindsa/moneygo) - An accounting web application to track personal finances written in Go and React/Bootstrap.
* [Open-Banking](https://github.com/mimani68/openbanking) - Mega framework focused on providing rapid, well-structured and also free open banking and fintech service.
* [otel-shopping-cart](https://github.com/trstringer/otel-shopping-cart) - Sample/demo application to highlight distributed tracing and other aspects with [OpenTelemetry](https://opentelemetry.io/).
* [paymentwall-go](https://github.com/paymentwall/paymentwall-go) - Paymentwall Go API Library (create signature for requests)
* [petshop](https://github.com/ellashella24/petshop) - A RESTful API for Pet Shop App.
* [pizza-shop-microservice](https://github.com/VarthanV/pizza-shop-microservice) - A pizza shop created in Go by following Microservice architecture.
* [QIWI](https://github.com/sendtips/qiwi) - QIWI API Go library.
* [QOR](https://github.com/qor/qor) - QOR is a set of libraries written in Go that abstracts common features needed for business applications, CMSs, and E-commerce systems.
* [shop](https://github.com/foomo/shop) - Light weight shop processing library.
* [shopy-api](https://github.com/sairahul1526/shopy-api) - Shopy POS - Point of Sale System.
* [simple-mpesa](https://github.com/SirWaithaka/simple-mpesa) - A simple example of how MPESA works. Works with all 3 types of customers i.e. Agents, Merchants and Subscribers. Allows you to configure a tariff and apply it to transactions. The project follows DDD principles.
* [stripe-payments-demo](https://github.com/stripe-archive/stripe-payments-demo) - Sample store accepting universal payments on the web with Stripe Elements, Payment Request, Apple Pay, Google Pay, Microsoft Pay, and the PaymentIntents API.
* [twikey-api-go](https://github.com/twikey/twikey-api-go) - Twikey API client for Go.
* [utm5-sber-osmp](https://github.com/sir-go/utm5-sber-osmp) - Sber -- OSMP --> UTM5 & Atol POS.
* [xendit-go](https://github.com/xendit/xendit-go) - Xendit REST API Client for Go - Card, Virtual Account, Invoice, Disbursement, Recurring Payments, Payout, EWallet, Balance, Retail Outlets Services, QR Codes
* [xs2a](https://github.com/snakx/xs2a) - Open Source PSD2 XS2A Client. The current state of development is alpha.

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* [email-verifier](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* [go-email-validator](https://github.com/go-email-validator/go-email-validator) - Modular email validator for syntax, disposable, smtp, etc... checking.
* [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
* [go-mail](https://github.com/wneessen/go-mail) - A simple Go library for sending mails in Go.
* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
* [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go.
* [go-simple-mail](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
* [gluon](https://github.com/ProtonMail/gluon) - An IMAP server library written in Go.
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails.
* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* [mailchain](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go.
* [mailgun-go](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API.
* [mailpit](https://github.com/axllent/mailpit) - Email and SMTP testing tool for developers.
* [mailx](https://github.com/valord577/mailx) - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library net/smtp.
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
* [mox](https://github.com/mjl-/mox) - Modern full-featured open source secure mail server for low-maintenance self-hosted email.
* [PMail](https://github.com/Jinnrry/PMail) - Private EMail Server.
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine.
* [smtpmock](https://github.com/mocktools/go-smtp-mock) - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment.
* [truemail-go](https://github.com/truemail-rb/truemail-go) - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more.
* [yogo](https://github.com/antham/yogo) - Check yopmail mails from command line.


## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go.
* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua).
* [cel-go](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing.
* [ecal](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing.
* [expr](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
* [expression](https://github.com/neonxp/expression) - Another expression parser and executor Better version of [https://github.com/neonxp/lexpr](https://github.com/neonxp/lexpr)
* [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language.
* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go.
* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go.
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* [goja](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go.
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [govaluate](https://github.com/Knetic/govaluate) - Provides support for evaluating arbitrary C-like artithmetic/string expressions.
* [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go.
* [metacall](https://github.com/metacall/core) - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more.
* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* [otto](https://github.com/robertkrimen/otto) - Package otto is a JavaScript parser and interpreter written natively in Go.
* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.
* [prolog](https://github.com/ichiban/prolog) - Embeddable Prolog.
* [starlark-go](https://github.com/google/starlark-go) - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution.
* [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go.
* [Wasmer](https://github.com/wasmerio/go-ext-wasm) - Wasmer is a Go library for executing WebAssembly binaries.

## Error Handling

*Libraries for handling errors.*

* [emperror](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications.
* [eris](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
* [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* [errors](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives.
* [errors](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
* [errors](https://github.com/bnkamalesh/errors) - Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
* [errors](https://github.com/cockroachdb/errors) - Go error library with error portability over the network.
* [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
* [exception](https://github.com/rbrahul/exception) - A simple utility package for exception handling with try-catch in Golang.
* [Falcon](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling.
* [Fault](https://github.com/Southclaws/fault) - An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values.
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* [oops](https://github.com/samber/oops) - Error handling with context, stack trace and source fragments.
* [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.

## File Handling

*Libraries for handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* [afs](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
* [baraka](https://github.com/xis/baraka) - A library to process http file uploads easily.
* [bfile](https://github.com/tidwall/bfile) - A buffer pool file I/O library for Go.
* [bigfile](https://github.com/bigfile/bigfile) - A file transfer system, support to manage files with http api, rpc call and ftp client.
* [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5, SHA256, SHA1 or CRC, for large files.
* [copy](https://github.com/otiai10/copy) - Copy directory recursively.
* [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
* [gdu](https://github.com/dundee/gdu) - Disk usage analyzer with console interface.
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* [gofs](https://github.com/no-src/gofs) - A cross-platform real-time file synchronization tool out of the box.
* [gut/yos](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
* [higgs](https://github.com/dastoori/higgs) - A tiny cross-platform Go library to hide/unhide files and directories.
* [iso9660](https://github.com/kdomanski/iso9660) - A package for reading and creating ISO9660 disk images.
* [litefs](https://github.com/superfly/litefs) - FUSE-based file system for replicating SQLite databases across a cluster of machines.
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
* [parquet](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files.
* [pathtype](https://github.com/jonchun/pathtype) - Treat paths as their own type instead of using strings.
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) - PDF processor.
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading.
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.
* [todotxt](https://github.com/1set/todotxt) - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt).
* [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.
* [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang.
* [ach](https://github.com/moov-io/ach) - A reader, writer, and valdiator for Automated Clearing House (ACH) files.
* [achgateway](https://github.com/moov-io/achgateway) - Payment gateway enabling automated ACH operations in a distributed and fault tolerant way.
* [applecrypto](https://github.com/evdokimovn/applecrypto) - Go library for working with ApplePay tokens.
* [applepay](https://github.com/processout/applepay) - Handles the Apple Pay flow.
* [applepay](https://github.com/civet148/applepay) - Apple Pay receipt verify golang packge.
* [apple_payment_token_decoder](https://github.com/Sepuka/apple_payment_token_decoder) - Apple payment token decoder implementation.
* [applepay-session](https://github.com/davidrjonas/applepay-session) - Starts a new session with Apple Pay and outputs the response data.
* [bank-1](https://github.com/msegeya/bank-1) - Banking infrastructure built using Go.
* [bankiso](https://github.com/figassis/bankiso) - Go implementation of the ISO 20022 and 8583 standards.
* [bban_gen](https://github.com/m1ome/bban_gen) - Simple BBAN generator & validator.
* [bbgo](https://github.com/c9s/bbgo) -  A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies.
* [buyte](https://github.com/rsoury/buyte) - Apple Pay and Google Pay in a single install. Digital Wallet Payment Orchestration built on a Serverless Stack for AWS using Golang, Node.js, Serverless Framework and AWS Amplify.
* [currency](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting.
* [currency](https://github.com/bnkamalesh/currency) - High performant & accurate currency computation package.
* [creditcard](https://github.com/lfaoro/creditcard) - Credit Card structure, helpers and validation.
* [creditcard](https://github.com/retgits/creditcard) - A Go module to perform basic credit card validation.
* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
* [decimal](https://github.com/govalues/decimal) - Immutable decimal numbers with panic-free arithmetic.
* [emv-qrcode](https://github.com/dongri/emv-qrcode) - Golang Based EMV QR Code Generator and Parser: MPM (Merchant Presented Mode), CPM (Consumer Presented Mode)
* [emvutil](https://github.com/ktr0731/emvutil) - Utility tool for QR code payloads encoded according to the EMV MPM specification.
* [emvqr](https://github.com/apperto/emvqr) - Generate EMV compliant QR codes.
* [fastme](https://github.com/newity/fastme) - Fast extensible matching engine Go implementation.
* [finance-go](https://github.com/piquette/finance-go) - Financial markets data library implemented in go.
* [finance-messaging](https://github.com/fairxio/finance-messaging) - This repository contains a full set of Golang code that represents the latest ISO-20022 data elements as per the ISO-20022 specifications.
* [finance-util](https://github.com/fairxio/finance-util) - Common utility objects for use with financial systems.
* [fincrypt](https://github.com/paulcarmichael/fincrypt) - A go library which provides general purpose cryptography alongside solutions for payment industry specific requirements.
* [fpdecimal](https://github.com/nikolaydubina/fpdecimal) - Fast and precise serialization and arithmetic for small fixed-point decimals.
* [fpmoney](https://github.com/nikolaydubina/fpmoney) - Fast and simple ISO4217 fixed-point decimal money.
* [go-api](https://github.com/vvoooooo/go-api) - Organize golang apple pay ,google pay and other api.
* [go-card](https://github.com/akriventsev/go-card) - Basic credit card structure with validation.
* [go-cards-validation](https://github.com/sgumirov/go-cards-validation) - Card validation with the Luhn algorithm for golang.
* [go-credit-card](https://github.com/durango/go-credit-card) - Credit card validation with the Luhn algorithm for golang.
* [go-emv-code](https://github.com/mercari/go-emv-code) - EMV® QR Code Encoder/Decoder for Go.
* [go-financial](https://github.com/razorpay/go-financial) - A go port of numpy-financial functions and more.
* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
* [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
* [go-finance](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
* [go-finnhub](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
* [go-iso8583](https://github.com/jattento/go-iso8583) - An easy to use, yet flexible marshaler for ISO-8583.
* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
* [go-nowpayments](https://github.com/matm/go-nowpayments) - Library for the crypto NOWPayments API.
* [go-paybysquare](https://github.com/kravemir/go-paybysquare) - Go library for Pay By Square QR Code generation.
* [go-payment](https://github.com/imrenagi/go-payment) - Payment Connector for Midtrans and Xendit.
* [gopay](https://github.com/go-pay/gopay) - AliPay, WeChat, PayPal, ApplePay - payment SDK.
* [Hexagonal-Architecture](https://github.com/LordMoMA/Hexagonal-Architecture) - Distributed messaging and payment backend built around the hexagonal architecture.
* [ISO-4217-currency](https://github.com/alanvivona/ISO-4217-currency) - Manage currency in ISO 4217 format.
* [iso20022](https://github.com/yudaprama/iso20022) - This repository contains a full set of Golang parse to the ISO-20022 data catalogs ISO-20022 specifications.
* [iso20022](https://github.com/fgrid/iso20022) - ISO20022 message elements.
* [iso8583](https://github.com/mofax/iso8583) - ISO 8583 is a financial industry messaging format, when you make a purchase using your card, that transaction will probably reach you bank encoded in ISO 8583 format.
* [iso8583](https://github.com/moov-io/iso8583) - A golang implementation to marshal and unmarshal iso8583 message.
* [mimir](https://github.com/vdlbk/mimir) - Library for banking algorithms (IBAN, Payment cards, credit cards, BBAN, ABA).
* [money](https://github.com/govalues/money) - Immutable monetary amounts and exchange rates with panic-free arithmetic.
* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
* [open-payment-host](https://github.com/abishekmuthian/open-payment-host) - Open Payment Host is an easy to run self-hosted, minimalist payments host through which we can easily sell our digital items without paying double commissions while having total control over our sales and data.
* [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
* [pay-gateway](https://github.com/pjoc-team/pay-gateway) - Pay gateway. support alipay,wechatpay,unionpay,jdpay etc.
* [paygate](https://github.com/moov-io/paygate) - Moov Paygate is a RESTful HTTP API enabling Automated Clearing House (ACH) transactions and returns to be processed with an Originating Depository Financial Institution (ODFI) without a deep understanding of a full NACHA file specification.
* [payme](https://github.com/jovandeginste/payme) - QR code generator (ASCII & PNG) for SEPA payments.
* [paymentpage-sdk-go](https://github.com/ITECOMMPAY/paymentpage-sdk-go) - This is a set of libraries in the Go language to ease integration of your service with the EcommPay Payment Page.
* [payqr](https://github.com/antonlindstrom/payqr) - payqr - Payments with QR.
* [payserver](https://github.com/jiusanzhou/payserver) - A easy way to get paid.
* [paysuper](https://github.com/paysuper) - PaySuper is a unique, simple payment toolkit designed to make developers self-reliant.
* [paytokens](https://github.com/nooize/paytokens) - package for decrypt Google Pay and Apple Pay tokens.
* [pinblock](https://github.com/moov-io/pinblock) - Personal Identification Number (PIN) management and security in financial services.
* [psd2-server](https://github.com/OpenPSD/psd2-server) - PSD2 compatible API server.
* [qr-gost-56042](https://github.com/ofstudio/qr-gost-56042) - QR-код для оплаты по банковским реквизитам по [ГОСТ Р 56042-2014](https://files.stroyinf.ru/Data2/1/4293771/4293771168.htm).
* [qrpay](https://github.com/dundee/qrpay) - Golang library for creating QR codes for payments.
* [sleet](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
* [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
* [ticker](https://github.com/achannarasappa/ticker) - Terminal stock watcher and stock position tracker.
* [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
* [UBStoYNAB](https://github.com/Che4ter/UBStoYNAB) - Automatically exports transactions from the Bank UBS Switzerland into a.csv file that can be imported into YNAB.
* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.
* [go-business-creditcard](https://github.com/dsparling/go-business-creditcard) - Validate/generate credit card checksums/names.

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values.
* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* [formam](https://github.com/monoculum/formam) - decode form's values into a struct.
* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* [gbind](https://github.com/bdjimmy/gbind) - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation.
* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* [httpin](https://github.com/ggicci/httpin) - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
* [qs](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters.
* [queryparam](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types.

## Functional

*Packages to support functional programming in Go.*

* [fp-go](https://github.com/repeale/fp-go) - Collection of Functional Programming helpers powered by Golang 1.18+ generics.
* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
* [go-functional](https://github.com/BooleanCat/go-functional) - Functional programming in Go using generics.
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* [gofp](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.
* [mo](https://github.com/samber/mo) - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...).
* [underscore](https://github.com/rjNemo/underscore) - Functional programming helpers for Go 1.18 and beyond.
* [valor](https://github.com/phelmkamp/valor) - Generic option and result types that optionally contain a value.

## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go.
* [Ebitengine](https://github.com/hajimehoshi/ebiten) - dead simple 2D game engine in Go.
* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* [fantasyname](https://github.com/s0rg/fantasyname) - Fantasy names generator.
* [g3n](https://github.com/g3n/engine) - Go 3D Game Engine.
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL.
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.
* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format.
* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.
* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework.
* [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
* [Oak](https://github.com/oakmound/oak) - Pure Go game engine.
* [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
* [prototype](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.
* [tile](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [convergen](https://github.com/reedom/convergen) - Feature rich type-to-type copy code generator.
* [copygen](https://github.com/switchupcb/copygen) - Generate type-to-type code without reflection.
* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* [go-xray](https://github.com/pieterclaerhout/go-xray) - Helpers for making the use of reflection easier.
* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types.
* [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
* [goverter](https://github.com/jmattheis/goverter) - Generate converters by defining an interface.
* [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.
* [RxGo](https://github.com/ReactiveX/RxGo) - Reactive Extensions for the Go Language.
* [typeregistry](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically.

## Geographic

*Geographic tools and servers*

* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications.
* [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
* [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
* [Globe](https://github.com/mmcloughlin/globe) - Globe wireframe visualizations in Golang backed by [pinhole](https://github.com/tidwall/pinhole).
* [godal](https://github.com/airbusgeo/godal) - Go wrapper for GDAL.
* [H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) - Distribution of Uber H3geo cells by virtual nodes.
* [H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) - Conversion utilities between H3 indexes and GeoJSON.
* [mbtileserver](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format.
* [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
* [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
* [S2 geojson](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
* [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go.
* [simplefeatures](https://github.com/peterstace/simplefeatures) - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.
* [Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) - A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection.
* [WGS84](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).

## Go Compilers

*Tools for compiling Go to other languages.*

* [c2go](https://github.com/goplus/c2go) - Convert C code to Go code.
* [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
* [esp32](https://github.com/andygeiss/esp32-transpiler) - Transpile Go into Arduino code.
* [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.
* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for golang.
* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
* [async](https://github.com/Gurpartap/async) - Provides a simple parallel execution primitive that we've all come to miss from Go: async/await futures. Each future is a straightforward implementation of a single go routine and a cancellable result channel. Accessing a future's result may require type casting from interface{}.
* [async](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks).
* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
* [async](https://github.com/rafaeldias/async) - Async is a utility library for manipulating synchronous and asynchronous flows. (Concurrent, Parallel, Waterfall).
* [async-job](https://github.com/lab210-dev/async-job) - AsyncJob is an asynchronous queue job manager with light code, clear and speed.
* [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible.
* [channelify](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing.
* [chanx](https://github.com/smallnest/chanx) - Unbounded chan with ringbuffer.
* [codel](https://github.com/joshbohde/codel) - Implements the [Controlled Delay](https://queue.acm.org/detail.cfm?id=2209336) algorithm for overload detection, providing a mechanism to shed load when overloaded.
* [conc](https://github.com/sourcegraph/conc) - `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer.
* [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines.
* [conexec](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way.It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
* [coroutine](https://github.com/stealthrocket/coroutine) - durable coroutine compiler and runtime library for Go.
* [cpuworker](https://github.com/hnes/cpuworker) - A Customized Goroutine Scheduler over Golang Runtime.
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
* [execpool](https://github.com/hexdigest/execpool) - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
* [flowmatic](https://github.com/carlmjohnson/flowmatic) - Structured concurrency made easy.
* [go-actor](https://github.com/vladopajic/go-actor) - A tiny library for writing concurrent programs using actor model.
* [go-concurrency-patterns](https://github.com/lotusirous/go-concurrency-patterns) - Common concurrency patterns in Golang.
* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* [go-fork](https://github.com/kraken-hpc/go-fork) - go-fork provides fork-like behavior for go processes. go-fork can also be used to spawn functions in Linux namespaces.
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control.
* [go-workerpool](https://github.com/zenthangplus/go-workerpool) - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines.
* [go-workers](https://github.com/catmullet/go-workers) - Easily and safely run workers for large data processing pipelines.
* [goccm](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
* [gochan](https://github.com/chalvern/gochan) - pool of goroutine with buffer channel, for concurrent execution but events of individual object running sequentially
* [gohive](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go.
* [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks.
* [gool](https://github.com/txaty/gool) - A generic goroutine pool just like Python ThreadPoolExecutor.
* [goroutine](https://github.com/kortschak/goroutine) - Package for getting the runtime ID of a goroutine.
* [goroutines](https://github.com/viney-shih/goroutines) - It is an efficient, flexible, and lightweight goroutine pool. It provides an easy way to deal with concurrent tasks with limited resource.
* [gotasks](https://github.com/jiajunhuang/gotasks) - gotasks is a task/job queue framework for Golang. Currently support Redis as broker.
* [gowl](https://github.com/hamed-yousefi/gowl) - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* [goworkers](https://github.com/dpaks/goworkers) - A minimal and efficient scalable workerpool implementation in Go using goroutines.
* [gowp](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool.
* [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
* [grit](https://github.com/climech/grit) - A multitree-based personal task manager.
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* [queue](https://github.com/golang-queue/queue) - Queue is a Golang library for spawning and managing a Goroutine pool.
* [hands](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines.
* [harmony](https://github.com/butuzov/harmony) - 
* [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
* [itogami](https://github.com/alphadose/itogami) - Fastest and most efficient goroutine pool.
* [kyoo](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools.
* [limiter](https://github.com/korovkin/limiter) - go lang concurrency limiter.
* [mkill](https://github.com/changkun/mkill) - mkill limits the number of threads in a Go program.
* [neilotoole/errgroup](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
* [nursery](https://github.com/arunsworld/nursery) - Structured concurrency in Go.
* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
* [pond](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go.
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* [queue](https://github.com/AnikHasibul/queue) - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.
* [queue](https://github.com/appleboy/queue) - Queue is a Golang library for spawning and managing a Goroutine pool, Alloowing you to create multiple worker according to limit CPU number of machine.
* [rutina](https://github.com/neonxp/rutina) - Routine orchestrator for your application.
* [routine](https://github.com/timandy/routine) - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully.
* [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors.
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
* [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
* [stream](https://github.com/devnw/stream) - Stream is a generic implementation for concurrency communication patterns.
* [taskq](https://github.com/vmihailenco/taskq) - Golang asynchronous task/job queue with Redis, SQS, IronMQ, and in-memory backends.
* [thread](https://github.com/golang-design/thread) - Package thread provides threading facilities, such as scheduling calls on a specific thread, local storage, etc.
* [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
* [workgroup](https://github.com/carlmjohnson/workgroup) - Workgroup is a generic Go library that provides a structured approach to concurrent programming. It lets you easily manage concurrent tasks in a manner that is predictable and scalable, and it provides a simple, yet effective approach to structuring concurrency.
* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.
* [workerpool-go](https://github.com/cmitsakis/workerpool-go) - auto-scaling worker pool (work queue), using Go 1.18 generics.
* [ZenQ](https://github.com/alphadose/ZenQ) - A thread-safe queue faster and more resource efficient than golang's native channels.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
* [gio](https://gioui.org/) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-echarts](https://github.com/go-echarts/go-echarts) - The adorable charts library for Golang.
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* [qamel](https://github.com/go-qamel/qamel) - Simple QML binding for Go.
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [Wails](https://github.com/wailsapp/wails) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer. [Webpage](https://wails.app)
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go.
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.
* [zenity](https://github.com/ncruces/zenity) - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

* [emgo](https://github.com/ziutek/emgo) - Go-like language for programming embedded systems (e.g. STM32 MCU).
* [ghw](https://github.com/jaypipes/ghw) - Golang hardware discovery/inspection library.
* [go-osc](https://github.com/hypebeast/go-osc) - Open Sound Control (OSC) bindings for Go.
* [go-rpio](https://github.com/stianeikeland/go-rpio) - GPIO for Go, doesn't require cgo.
* [goroslib](https://github.com/aler9/goroslib) - Robot Operating System (ROS) library for Go.
* [joystick](https://github.com/0xcafed00d/joystick) - a polled API to read the state of an attached joystick.
* [sysinfo](https://github.com/zcalusic/sysinfo) - A pure Go library providing Linux OS / kernel / hardware system information.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.
* [canvas](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image.
* [color-extractor](https://github.com/marekm4/color-extractor) - Dominant color extractor with no external dependencies.
* [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
* [draft](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* [gift](https://github.com/disintegration/gift) - Package of image processing filters.
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* [go-webp](https://github.com/kolesa-team/go-webp) - Library for encode and decode webp pictures, using libwebp.
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
* [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go.
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* [gowitness](https://github.com/sensepost/gowitness) - Screenshoting webpages using go and headless chrome on command line.
* [govips](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go.
* [gridder](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library.
* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [img](https://github.com/hawx/img) - Selection of image manipulation tools.
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* [PhotoPrism](https://github.com/photoprism/photoprism) - PhotoPrism® is a server-based application for browsing, organizing and sharing your personal photo collection. It makes use of the latest technologies to automatically tag and find pictures without getting in your way.
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
* [png2svg](https://github.com/xyproto/png2svg) - Convert small PNG images to SVG Tiny 1.2
* [primitive](https://github.com/fogleman/primitive) - Reproducing images with geometric primitives.
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* [scout](https://github.com/jonoton/scout) - Scout is a standalone open source software solution for DIY video security.
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* [stackblur-go](https://github.com/esimov/stackblur-go) - A fast, almost Gaussian Blur implementation in Go.
* [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
* [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.
* [webp-server](https://github.com/mehdipourfar/webp-server) - Simple and minimal image server capable of storing, resizing, converting and caching images.

### QrCode

*Libraries for manipulating with QrCodes.*

* [go-qr](https://github.com/piglig/go-qr) - A native, high-quality and minimalistic QR code generator.
* [go-qrcode](https://github.com/skip2/go-qrcode) - Package qrcode implements a QR Code encoder.
* [txqr](https://github.com/divan/txqr) - Transfer data via animated QR codes.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* [EdgeX](https://github.com/edgexfoundry/edgex-go) - EdgeX Foundry is a vendor-neutral open source project hosted by The Linux Foundation building a common open framework for IoT edge computing.
* [ekuiper](https://github.com/if-edge/ekuiper) - Lightweight data stream processing engine for IoT edge.
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.
* [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

## Job Scheduler

*Libraries for scheduling jobs.*

* [cdule](https://github.com/deepaksinghvi/cdule) - Job scheduler library with database support.
* [cheek](https://github.com/datarootsio/cheek) - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling.
* [clockwerk](https://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go.
* [crocodile](https://github.com/labulaka521/crocodile) - A distributed task scheduling system based on Golang that supports http requests, run golang, python, python3, shell, bat
* [cron](https://github.com/robfig/cron) - cron library for go.
* [cronticker](https://github.com/krayzpipes/cronticker) - A ticker implementation to support cron schedules.
* [Dagu](https://github.com/dagu-go/dagu) -  No-code workflow executor. it executes DAGs defined in a simple YAML format.
* [gocron](https://github.com/jasonlvhit/gocron) - Golang Job Scheduling Package.
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [go-quartz](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go.
* [gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron).
* [goflow](https://github.com/fieldryand/goflow) - A simple but powerful DAG scheduler and dashboard.
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [gronx](https://github.com/adhocore/gronx) - Cron expression parser, task runner and daemon consuming crontab like task list.
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
* [sched](https://github.com/romshark/sched) - A job scheduler with the ability to fast-forward time.
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* [schedgroup](https://github.com/mdlayher/schedgroup) - Package schedgroup provides a goroutine worker pool which schedules tasks to be performed at or after a specified time.
* [tasks](https://github.com/madflojo/tasks) - An easy to use in-process scheduler for recurring tasks in Go.
* [tunasync](https://github.com/tuna/tunasync) - Mirror job management tool.

## JSON

*Libraries for working with JSON.*

* [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support.
* [ask](https://github.com/simonnilsson/ask) - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
* [dynjson](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs.
* [ej](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly.
* [epoch](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON.
* [fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
* [gabs](https://github.com/Jeffail/gabs) - For parsing, creating and editing unknown or dynamic JSON in Go.
* [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [go-json](https://github.com/goccy/go-json) - Fast JSON encoder/decoder compatible with encoding/json for Go.
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec.
* [go-jsonpointer](https://github.com/mattn/go-jsonpointer) - Go implementation of JSON Pointer (RFC6901).
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [GoJay](https://github.com/francoispqt/gojay) - fastest JSON encoder/decoder with powerful stream API for Golang
* [gojmapr](https://github.com/limiu82214/gojmapr) - Get simple struct from complex json by json path.
* [go-prettyjson](https://github.com/hokaccha/go-prettyjson) - JSON pretty print for Golang.
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [htmljson](https://github.com/nikolaydubina/htmljson) - Rich rendering of JSON as HTML in Go.
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [jettison](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go.
* [jscan](https://github.com/romshark/jscan) - High performance zero-allocation JSON iterator.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
* [json2go](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [jsoncolor](https://github.com/neilotoole/jsoncolor) - Drop-in replacement for encoding/json that outputs colorized JSON.
* [jsondiff](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch).
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [jsonhandlers](https://github.com/abusomani/jsonhandlers) - JSON library to expose simple handlers that lets you easily read and write json from various sources.
* [jsonic](https://github.com/sinhashubham95/jsonic) - Utilities to handle and query JSON without defining structs in a type safe manner.
* [jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) - A fast and convinient library for unstructured JSON data, replacing `encoding/json`.
* [jzon](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior.
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [mapslice-json](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* [marshmallow](https://github.com/PerimeterX/marshmallow) - Performant JSON unmarshaling for flexible use cases.
* [OjG](https://github.com/ohler55/ojg) - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath.
* [omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) - Simple JSON parser with validation by condition via golang struct fields tags.
* [pjson](https://github.com/tidwall/pjson) - A JSON stream parser for Go.
* [pretty](https://github.com/tidwall/pretty) - Pretty is a Go package that provides fast methods for formatting JSON for human readability, or to compact JSON for smaller payloads.
* [ujson](https://github.com/olvrng/ujson) - Fast and minimal JSON parser and transformer that works on unstructured JSON.
* [vjson](https://github.com/miladibra10/vjson) - Go package for validating JSON objects with declaring a JSON schema with fluent API.

## Logging

*Libraries for generating and working with log files.*

* [aol](https://github.com/arriqaaq/aol) - A simple immutable append only log in Go. aol is a rewrite of [wal](https://github.com/tidwall/wal) to allow only appends to a log.
* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [go-log](https://github.com/pieterclaerhout/go-log) - A logging library with strack traces, object dumping and optional timestamps.
* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [golog](https://github.com/kataras/golog) - A high-performant Logging Foundation for Go Applications. X3 faster than the rest leveled loggers.
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [GoVector](https://github.com/DistributedClocks/GoVector) - GoVector is a vector clock logging library written in Go. The [vector clock algorithm](https://en.wikipedia.org/wiki/Vector_clock) is used to order events in distributed systems in the absence of a centralized clock. GoVector implements the vector clock algorithm and provides feature-rich logging and encoding infrastructure.
* [httplog](https://github.com/MadAppGang/httplog) - Golang HTTP logger middleware with color console output and structured logs.
* [httpretty](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
* [kemba](https://github.com/clok/kemba) - A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications.
* [log](https://github.com/apex/log) - Structured logging package for Go.
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
* [log](https://github.com/cybozu-go/log) - Logging framework for Cybozu Go products.
* [log](https://github.com/heartwilltell/log) - Simple leveled logging wrapper around standard log package.
* [log](https://github.com/charmbracelet/log) - A minimal, colorful Go logging library.
* [log](https://github.com/no-src/log) - A simple logging framework out of the box.
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [logrusiowriter](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logsuck](https://github.com/JackBister/logsuck) - Logsuck is a program that makes it easier for you to deal with your logs.
* [logur](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc).
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* [loki](https://github.com/grafana/loki) - Like Prometheus, but for logs.
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [noodlog](https://github.com/gyozatech/noodlog) - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings.
* [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [pp](https://github.com/k0kubun/pp) - Colored pretty printer for Go language.
* [phuslu/log](https://github.com/phuslu/log) - Structured Logging Made Easy.
* [redlog](https://github.com/tidwall/redlog) - Redlog is a Redis style logger for Go.
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* [slf4g](https://github.com/echocat/slf4g) - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks.
* [slog](https://github.com/monzo/slog) - Structured logging.
* [slog](https://github.com/gookit/slog) - Lightweight, configurable, extensible logger for Go.
* [slog-formatter](https://github.com/samber/slog-formatter) - Common formatters for slog and helpers to build your own.
* [slog-multi](https://github.com/samber/slog-multi) - Chain of slog.Handler (pipeline, fanout...).
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [sqldb-logger](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing *sql.DB stdlib usage.
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [structy/log](https://github.com/structy/log) - A simple to use log system, minimalist but with features for debugging and differentiation of messages.
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* [tint](https://github.com/lmittmann/tint) - A slog.Handler that writes tinted logs.
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [xylog](https://github.com/xybor-x/xylog) - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax.
* [yell](https://github.com/jfcg/yell) - Yet another minimalistic logging library.
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [zax](https://github.com/yuseferi/zax) - Integrate Context with Zap logger, which leads to more flexibility in Go logging.
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.
* [zkits-logger](https://github.com/edoger/zkits-logger) - A powerful zero-dependency JSON logger.

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* [chatGPT-plugin-template](https://github.com/Pisush/chatGPT-plugin-template) - For Gophers.
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* [ddt](https://github.com/sgrodriguez/ddt) - Dynamic decision tree, create trees defining customizable rules.
* [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
* [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library.
* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine leraning in Go.
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* [go-openai](https://github.com/sashabaranov/go-openai) - OpenAI ChatGPT, GPT-3, DALL·E, Whisper API wrapper for Go.
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* [gonet](https://github.com/dathoangnd/gonet) - Neural Network for Go.
* [Goptuna](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* [gorgonia](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support.
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go.
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
* [openaigo](https://github.com/otiai10/openaigo) - OpenAI GPT3/3.5 ChatGPT API Client Library for Go, simple, less dependencies, and well-tested.
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* [randomforest](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go.
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
* [Varis](https://github.com/Xamber/Varis) - Golang Neural Network.
* [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX).

## Messaging

*Libraries that implement messaging systems.*

* [ami](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams.
* [amqp](https://github.com/rabbitmq/amqp091-go) - Go RabbitMQ Client Library.
* [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go. Send push notifications to iOS, tvOS, Safari and OSX apps.
* [asynq](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
* [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
* [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
* [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication.
* [Buz](https://github.com/silverton-io/buz) - Buz is a system for collecting events from various sources, validating data quality, and delivering them to where they need to bee.
* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* [Chanify](https://github.com/chanify/chanify) - A push notification server send message to your iOS devices.
* [cherami-server](https://github.com/uber/cherami-server) - Distributed, scalable, durable, and highly available message queue system.
* [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
* [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* [fireworq](https://github.com/fireworq/fireworq) - Fireworq is a lightweight, high-performance, language-independent job queue system.
* [fwatcher](https://github.com/ansrivas/fwatcher) - An application to watch a given directory for new files, read it and publish to Kafka ( using actors ).
* [gaurun](https://github.com/mercari/gaurun) - General push notification server in Go.
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* [go-eventbus](https://github.com/stanipetrosyan/go-eventbus) - Simple Event Bus package for Go.
* [go-mq](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration.
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* [go-res](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go.
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).
* [gosd](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel.
* [gotify](https://github.com/gotify/server) - Simple server for sending and receiving messages in real-time per WebSocket. (Includes a sleek web-ui) https://gotify.net
* [gotosocial](https://github.com/superseriousbusiness/gotosocial) - GoToSocial is an [ActivityPub](https://activitypub.rocks/) social network server, written in Golang.
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* [hare](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets.
* [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
* [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
* [jocko](https://github.com/travisjeffery/jocko) - Kafka implemented in Golang with built-in coordination (No ZK dep, single binary install, Cloud Native).
* [kafka-go](https://github.com/segmentio/kafka-go) - Kafka library in Go.
* [lmstfy](https://github.com/bitleak/lmstfy) - Implements task queue in Golang which based on Redis storage.
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* [mangos](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
* [mattermost](https://github.com/mattermost/mattermost-server) - Open source Slack-alternative in Golang and React.
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* [Memphis](https://github.com/memphisdev/memphis-broker) - Memphis is an Open-Source, Real-Time Data Processing Platform. It took three minutes to build in Memphis what took me weeks in Kafka.
* [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* [MiniQueue](https://github.com/tomarrell/miniqueue) - A stupid simple, single binary message queue using HTTP/2.
* [mob](https://github.com/erni27/mob) - mob is a generic-based, simple mediator / event aggregator library. It supports in-process requests / events processing.
* [nats-kafka](https://github.com/nats-io/nats-kafka) - This project implements a multi-connector bridge between NATS, NATS Streaming, JetStream and Kafka topics.
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* [notify](https://github.com/nikoksr/notify) - A dead simple Go library for sending notifications to various messaging services.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* [ntfy](https://github.com/binwiederhier/ntfy) - Send push notifications to your phone or desktop using PUT/POST [ntfy.sh](https://ntfy.sh/).
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* [Plumber](https://github.com/streamdal/plumber) - CLI devtool for inspecting, piping, messaging and redirecting data in message systems like Kafka, RabbitMQ , GCP PubSub and many more.
* [postee](https://github.com/aquasecurity/postee) - Simple message routing system that receives input messages through a webhook interface and can enforce actions using predefined outputs via integrations.
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* [Quamina](https://github.com/timbray/quamina) - Fast pattern-matching for filtering messages and events.
* [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
* [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [Ratus](https://github.com/hyperonym/ratus) - Ratus is a RESTful asynchronous task queue server.
* [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams.
* [rmq](https://github.com/adjust/rmq) - Message queue system written in Go and backed by Redis.
* [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
* [sarama](https://github.com/IBM/sarama) - Go library for Apache Kafka.
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* [YTask](https://github.com/gojuukaze/YTask) - Asynchronous task queue for handling distributed jobs in golang.
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2).
* [vice](https://github.com/matryer/vice) - Go channels at horizontal scale (powered by message queues).
* [watermill](https://github.com/ThreeDotsLabs/watermill) - Building event-driven applications the easy way in Go. https://watermill.io/

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents

### Microsoft Excel
*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/qax-os/excelize) - Golang library for reading and writing Microsoft Excel (XLSX) files.
* [exl](https://github.com/go-the-way/exl) - Excel binding to struct written in Go.(Only supports Go1.18+)
* [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
* [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.

## Miscellaneous

### Dependency Injection
*Libraries for working with dependency injection.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* [boot-go](http://github.com/boot-go/boot) - Component-based development with dependency injection using reflections for Go developers.
* [container](https://github.com/golobby/container) - A powerful IoC Container with fluent and easy-to-use interface.
* [di](https://github.com/HnH/di) - - DI container library that is focused on clean API and flexibility.
* [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* [dingo](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice.
* [do](https://github.com/samber/do) - A dependency injection framework based on Generics.
* [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
* [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container.
* [gontainer](https://github.com/NVIDIA/gontainer) - A dependency injection service container for Go projects.
* [google/wire](https://github.com/google/wire) - Automated Initialization in Go.
* [goioc/di](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container.
* [kinit](https://github.com/go-kata/kinit) - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
* [inject](https://github.com/defval/inject) - A reflection based dependency injection container with simple interface.
* [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
* [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support.
* [nject/npoint](https://github.com/BlueOwlOpenSource/nject) - A type safe, reflective framework based on types for libraries, tests, and endpoints.
* [nject](https://github.com/muir/nject) - A type safe, reflective framework for libraries, tests, and http endpoints, and service startup.
* [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.

### Memory allocation

* [go-slab](https://github.com/couchbase/go-slab) - A slab allocator library in the Go Programming Language.
* [mem](https://github.com/smasher164/mem) - A memory allocator for Go.
* [stealthpool](https://github.com/Link512/stealthpool) - Off heap golang memory pool.

### Project Layout

*Unofficial set of patterns for structuring projects.*

* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices.
* [go-app-template](https://github.com/mikhail-bigun/go-app-template) - Go application template.
* [go-module](https://github.com/octomation/go-module) - Template for a typical module written on Go.
* [go-rest-api](https://github.com/qiangxue/go-rest-api) - An idiomatic Go RESTful API starter kit following SOLID principles and Clean Architecture with a common project layout.
* [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code.
* [go-starter](https://github.com/allaboutapps/go-starter) - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers.
* [go-todo-backend](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice.
* [gobase](https://github.com/wajox/gobase) - A simple skeleton for golang application with basic setup for real golang application.
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem.
* [golang-templates/seed](https://github.com/golang-templates/seed) - Go application GitHub repository template.
* [Goro](https://github.com/hanagantig/goro) - A tool to generate your service layout. Goro helps to keep single approach for your code architecture.
* [inizio](https://github.com/insidieux/inizio) - Golang project layout generator with plugins.
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices.
* [nunu](https://github.com/go-nunu/nunu) - Nunu is a scaffolding tool for building Go applications.
* [pagoda](https://github.com/mikestefanello/pagoda) - Rapid, easy full-stack web development starter kit built in Go.
* [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
* [service](https://github.com/ardanlabs/service) - A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications.
* [go-project-layout](https://github.com/wangyoucao577/go-project-layout) - Set of practices and discussions on how to structure Go project layout.

### Strings
*Libraries for working with strings.*

* [bexp](https://github.com/mkungla/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
* [caps](https://github.com/chanced/caps) - A case conversion library.
* [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
* [sttr](https://github.com/abhimanyu003/sttr) - cross-platform, cli app to perform various operations on string.
* [Stringy](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
* [strutil](https://github.com/ozgio/strutil) - String utilities.
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.
* [go-strutil](https://github.com/torden/go-strutil) - Just String Processing Library for Go-lang.

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [assert](https://github.com/tidwall/assert) - This package provides an assert function for Go. It's designed to work like [assert](https://man7.org/linux/man-pages/man3/assert.3.html) in C.
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* [backoff](https://github.com/jpillora/backoff) - A simple exponential backoff counter in Go (Golang).
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
* [basexx](https://github.com/bobg/basexx) - Convert to, from, and between digit strings in various number bases.
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* [captcha](https://github.com/go-macaron/captcha) - Package captcha is a middleware that provides captcha service for Macaron.
* [common](https://github.com/kubeservice-stack/common) - A library for server framework.
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* [conv](https://github.com/tidwall/conv) - A Go package for converting various primitive types.
* [d2](https://github.com/terrastruct/d2) - D2 is a modern diagram scripting language that turns text to diagrams.
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [Extra](https://github.com/neonxp/extra) - Пакет с разными полезными функциями без дополнительных зависимостей.
* [failsafe-go](https://github.com/failsafe-go/failsafe-go) - Fault tolerance and resilience patterns for Go.
* [faker](https://github.com/pioz/faker) - Random fake data and struct generator for Go.
* [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
* [fsm](https://github.com/dyrkin/fsm) - Finite State Machine for Go inspired by Akka FSM.
* [fsm](https://github.com/looplab/fsm) - Finite State Machine for Go.
* [gatus](https://github.com/TwiN/gatus) - Automated service health dashboard.
* [gitaligned](https://github.com/soypat/gitaligned) - Get author D&D-styled alignment from repository git commit messages.
* [go-fastapi](https://github.com/sashabaranov/go-fastapi) - go-fastapi is a library to quickly build APIs. It is inspired by Python's popular [FastAPI](https://github.com/tiangolo/fastapi) library. Auto-generated OpenAPI/Swagger schema without any markup.
* [go-lodash](https://github.com/nityanandagohain/go-lodash) - Implementation of lodash library in Go 1.18 generics.
* [go-commandbus](https://github.com/lana/go-commandbus) - A slight and pluggable command-bus for Go.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* [gobreaker](https://github.com/sony/gobreaker) - [Circuit Breaker pattern](https://msdn.microsoft.com/en-us/library/dn589784.aspx) implemented in Go
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
* [gopkg](https://github.com/bytedance/gopkg) - Universal Utilities for Go.
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gorse](https://github.com/gorse-io/gorse) - An open source recommender system service written in Go.
* [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* [gostuff](https://github.com/fluhus/gostuff) - Collection of util packages.
* [gotils](https://github.com/savsgio/gotils) - Golang utlities to make your life easier.
* [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client.
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* [gov](https://github.com/256dpi/gov) - A simple prometheus metrics and pprof profile viewer.
* [grofer](https://github.com/pesos/grofer) - A system and resource monitoring tool written in Golang.
* [gtree](https://github.com/ddddddO/gtree) - Provide CLI and Package to generate tree from Markdown or programmatically, and the output is JSON/YAML/TOML/tree command.
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* [Hue exporter](https://github.com/mitchellrj/hue_exporter) - This is a Prometheus exporter for the Philips Hue system. It's written in Go. It exposes metrics about lights, groups and sensors.
* [juniper](https://github.com/bradenaw/juniper) - Juniper is an extended Go standard library using generics, including containers, iterators, and streams.
* [libstdgo](https://github.com/obsidiandynamics/libstdgo) - Standard libraries for Go.
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
* [maths](https://github.com/theriault/maths) - Maths includes mathematical functions not defined in the standard Go math package.
* [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition.
* [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
* [ogen](https://github.com/ogen-go/ogen) - OpenAPI v3 code generator for go.
* [openapi](https://github.com/neotoolkit/openapi) - OpenAPI 3.x parser.
* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* [pie](https://github.com/natefinch/pie) - toolkit for creating plugins for Go applications.
* [resenje.org](https://resenje.org) - All go packages are under domain resenje.org, but the code is hosted on GitHub.
* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
* [selfupdate](https://github.com/minio/selfupdate) - Build self-updating Go programs.
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [shoutrrr](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
* [sitemap-format](https://github.com/mingard/sitemap-format) - A simple sitemap generator, with a little syntactic sugar.
* [stateless](https://github.com/qmuntal/stateless) - A fluent library for creating state machines.
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [tableflip](https://github.com/cloudflare/tableflip) - Graceful process restarts in Go.
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
* [try](https://github.com/matryer/try) - Simple idiomatic retry package for Go.
* [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
* [varint](https://github.com/chmike/varint) - A faster varying length integer encoder/decoder than the one provided in the standard library.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
* [x](https://github.com/janos/x) - X Go packages.
* [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
* [xo](https://github.com/256dpi/xo) - A configuration, logging, reporting and tracing framework for Go applications.
* [xz](https://github.com/ulikunitz/xz) - Pure golang package for reading and writing xz-compressed files.

## Natural Language Processing

*Libraries for working with human languages.*

### Language Detection

* [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
* [getlang](https://github.com/rylans/getlang) - Fast natural language detection package.
* [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).

### Morphological Analyzers

* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.
* [govader](https://github.com/jonreiter/govader) - Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment).
* [govader_backend](https://github.com/PIMPfiction/govader_backend) - Microservice implementation of [GoVader](https://github.com/jonreiter/govader)
* [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [spaGO](https://github.com/nlpodyssey/spago) - Self-contained Machine Learning and Natural Language Processing library in Go.
* [spelling-corrector](https://github.com/jorelosorio/spellingcorrector) - A spelling corrector for the Spanish language or create your own.

### Slugifiers

* [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
* [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
* [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.

### Tokenizers

* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.

### Translation

* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* [go-localize](https://github.com/m1/go-localize) - Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings.
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
* [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* [iuliia-go](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way.
* [spreak](https://github.com/vorlif/spreak) - Flexible translation and humanization library for Go, based on the concepts behind gettext.
* [t](https://github.com/youthlin/t) - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template.

### Transliteration

* [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings.
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* [transliterator](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules.

### Uncategorized

* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.
* [govader](https://github.com/jonreiter/govader) - Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment).
* [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).

## Networking

*Libraries for working with various layers of the network.*

* [1m-go-tcp-server](https://github.com/smallnest/1m-go-tcp-server) - Benchmarks for implementation of servers which support 1 million connections.
* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* [berty](https://github.com/berty/berty) - Berty is a secure peer-to-peer messaging app that works with or without internet access, cellular data or trust in the network.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [calico](https://github.com/projectcalico/calico) - Cloud native networking and network security.
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* [cmux](https://github.com/soheilhy/cmux) - Generic Go library to multiplex connections based on their payload, serve gRPC, SSH, HTTPS, HTTP, Go RPC, and pretty much any other protocol on the same TCP listener.
* [CoreDNS](https://github.com/coredns/coredns) - CoreDNS is a DNS server that chains plugins.
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* [dnsmonster](https://github.com/mosajjal/dnsmonster) - Passive DNS Capture/Monitoring Framework.
* [easygo](https://github.com/mailru/easygo) - Tools for building go apps (epoll).
* [easytcp](https://github.com/DarthPestilane/easytcp) - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful.
* [ergo](https://github.com/halturin/ergo) - Framework for creating mesh networks using technologies and design patterns of Erlang/OTP in Golang.
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [event](https://github.com/cheng-zhongliang/event) - Simple I/O event notification library wirtten in Golang.
* [evio](https://github.com/tidwall/evio) - Fast event-loop networking for Go
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* [ftpserverlib](https://github.com/fclairamb/ftpserverlib) - Fully featured FTP server library.
* [Gain](https://github.com/pawelgaczynski/gain) - Gain is a high-performance io_uring networking framework written entirely in Go.
* [getty](https://github.com/AlexStocks/getty) - netty like asynchronous network I/O library based on tcp/udp/websocket; a bidirectional RPC framework based on JSON/Protobuf; a microservice framework based on zookeeper/etcd
* [gaio](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode.
* [gev](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
* [gldap](https://github.com/jimlambrt/gldap) - gldap provides an ldap server implementation and you provide handlers for its ldap operations.
* [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
* [gnet](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, nonblocking, event-loop networking library written in pure Go.
* [gnet](https://github.com/fish-tennis/gnet) - `gnet` is a high-performance networking framework,especially for game servers.
* [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
* [go-curl](https://github.com/golang-basic/go-curl) - libcurl(curl) binding.
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* [go-uring](https://github.com/godzie44/go-uring) - The `io_uring` library and runtime for GO
* [go-ipfs](https://github.com/ipfs/go-ipfs) - IPFS is a global, versioned, peer-to-peer filesystem.
* [go-powerdns](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang.
* [go-sse](https://github.com/lampctl/go-sse) - Go client and server implementation of HTML server-sent events.
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [gohooks](https://github.com/averageflow/gohooks) - GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server.
* [goetty](https://github.com/fagongzi/goetty) - Goetty is a framework to help you build socket application.
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* [goph](https://github.com/melbahja/goph) - Golang ssh client, execute your commands over ssh connection.
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework.
* [gws](https://github.com/lxzan/gws) - High-Performance WebSocket Server & Client With AsyncIO Supporting .
* [grpcui](https://github.com/fullstorydev/grpcui) - An interactive web UI for gRPC, along the lines of postman.
* [hmq](https://github.com/fhmq/hmq) - High performance mqtt broker.
* [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
* [httpproxy](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer.
* [httpx](https://github.com/projectdiscovery/httpx) - Fast and multi-purpose HTTP toolkit allows to run multiple probers using retryablehttp library, it is designed to maintain the result reliability with increased threads.
* [iouring-go](https://github.com/Iceber/iouring-go) - Provides easy-to-use async IO interface with io_uring.
* [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [Jupiter](https://github.com/douyu/jupiter) - Governance-oriented Microservice Framework.
* [kcp](https://github.com/skywind3000/kcp) - KCP - A Fast and Reliable ARQ Protocol.
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* [livekit-server](https://github.com/livekit/livekit-server) - Scalable, production-grade WebRTC video conferencing. SDKs for web & mobile.
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [nbio](https://github.com/lesismal/nbio) - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
* [nebula](https://github.com/slackhq/nebula) - A scalable overlay networking tool with a focus on performance, simplicity and security.
* [netaddr](https://github.com/inetaf/netaddr) - Network address types.
* [netpoll](https://github.com/cloudwego/netpoll) - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios.
* [nordvpn-linux](https://github.com/NordSecurity/nordvpn-linux) - NordVPN Linux client.
* [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* [openssl](https://github.com/spacemonkeygo/openssl) - OpenSSL bindings for Go.
* [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.
* [panoptes-stream](https://github.com/yahoo/panoptes-stream) - A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT).
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
* [pgrok](https://github.com/pgrok/pgrok) - Poor man's ngrok - a multi-tenant HTTP reverse tunnel solution through SSH remote port forwarding.
* [pool](https://github.com/go-baa/pool) - Common golang tcp connection pool, Get inspirations from sync.Pool
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [port-forward](https://github.com/tavenli/port-forward) - Port forward server with GUI admin page.
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* [qianmo](https://github.com/smallnest/qianmo) - additional network functions.
* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
* [quiwi](https://github.com/goburrow/quic) - QUIC transport protocol (https://quicwg.org/) implementation in Go. The goal is to provide low level APIs for applications or protocols using QUIC as a transport.
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* [rconn](https://github.com/jafarlihi/rconn) - (r[everse] conn[ection]) is a multiplatform program for creating reverse connections. It lets you consume services that are behind NAT and/or firewall without adding firewall rules or port-forwarding.
* [scp](https://github.com/povsister/scp) - Production-ready Secure Copy Protocol (SCP) implementation in Golang.
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [sish](https://github.com/antoniomika/sish) - HTTP(S)/WS(S)/TCP Tunnels to localhost using only SSH. An open source serveo/ngrok alternative.
* [socket](https://github.com/mdlayher/socket) - Package socket provides a low-level network connection type which integrates with Go's runtime network poller to provide asynchronous I/O and deadline support.
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* [tcpx](https://github.com/fwhezfwhez/tcpx) - A cross-language tcp framwork in golang.
* [Tinode](https://github.com/tinode/chat) - Instant messaging server.
* [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
* [uring](https://github.com/dshulyak/uring) - Golang library for io_uring framework (without CGO).
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* [vssh](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol.
* [water](https://github.com/songgao/water) - Simple TUN/TAP library.
* [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.
* [yamux](https://github.com/hashicorp/yamux) - Golang connection multiplexing library.

### Proxy & Tunnel

*Libraries for network proxy connections.*

* [brook](https://github.com/txthinking/brook) - Brook is a cross-platform proxy/vpn software.
* [chisel](https://github.com/jpillora/chisel) - Fast TCP tunnel over HTTP.
* [clash](https://github.com/Dreamacro/clash) - A rule-based tunnel in Go.
* [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta) - A rule-based tunnel in Go.
* [dae](https://github.com/daeuniverse/dae) - A Linux high-performance transparent proxy solution based on eBPF.
* [fabio](https://github.com/fabiolb/fabio) - fabio is a fast, modern, zero-conf load balancing HTTP(S) and TCP router for deploying applications managed by consul.
* [fasthttp-reverse-proxy](https://github.com/yeqown/fasthttp-reverse-proxy)- Reverse http proxy based on fasthttp.
* [fullproxy](https://github.com/shoriwe/fullproxy) - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols.
* [frp](https://github.com/fatedier/frp) - Fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet.
* [ghostunnel](https://github.com/square/ghostunnel) - A simple SSL/TLS proxy with mutual authentication for securing non-TLS services.
* [gobetween](https://github.com/yyyar/gobetween) - Modern & minimalistic load balancer and reverse-proxy.
* [goblue](https://github.com/truexf/goblue) - Tcp reverse proxy by golang.
* [goproxy](https://github.com/snail007/goproxy) - Proxy is a high performance HTTP, HTTPS, HTTPS, websocket, TCP, UDP, Socks5.
* [go_proxy_pool](https://github.com/pingc0y/go_proxy_pool)
* [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis.
* [gost](https://github.com/ginuerzh/gost) - A simple security tunnel written in Golang.
* [Hysteria](https://github.com/HyNetwork/hysteria) - Hysteria is a feature-packed proxy & relay utility optimized for lossy, unstable connections (e.g. satellite networks, congested public Wi-Fi, connecting from China to servers abroad).
* [inlets](https://github.com/inlets/inlets) - inlets is a Cloud Native Tunnel written in Go.
* [ldap_proxy](https://github.com/ant1441/ldap_proxy) - Reverse proxy and static file server that provides authentication using LDAP.
* [loadbalancer-algorithms](https://github.com/appleboy/loadbalancer-algorithms) - Load balancer Algorithms.
* [mosn](https://github.com/mosn/mosn) - MOSN is a network proxy written in Golang.
* [NPS](https://github.com/ehang-io/nps) - Lightweight, high-performance, powerful intranet penetration proxy server, with a powerful web management terminal.
* [oauth2_proxy](https://github.com/bitly/oauth2_proxy) - Reverse proxy that provides authentication with Google, Github or other provider.
* [proxify](https://github.com/projectdiscovery/proxify) - Swiss Army Knife Proxy for rapid deployments. Supports multiple operations such as request/response dump, filtering and manipulation via DSL language, upstream HTTP/Socks5 proxy. Additionally a replay utility allows to import the dumped traffic (request/responses with correct domain name) into burp or any other proxy by simply setting the upstream proxy to proxify.
* [proxym](https://github.com/wndhydrnt/proxym) - Use HAProxy, nginx or Hipache as a reverse proxy in front of Marathon, Mesos and other services.
* [proxypool](https://github.com/zu1k/proxypool) - Automatically grab the tg channel, subscription address, SS, ssr, vmess, trojan node information on the public Internet,aggregate and provide a list of nodes after deduplication.
* [proxyswap](https://github.com/gaillard/proxyswap) - Hot swappable single host reverse TCP proxy in Go.
* [pylon](https://github.com/LeonardBesson/pylon) - Go Reverse Proxy and Load balancer.
* [ReverseProxy](https://github.com/ilanyu/ReverseProxy) - ReverseProxy in golang.
* [reverseproxy](https://github.com/wybiral/reverseproxy) - Encrypted reverse proxy in Go.
* [sing-box](https://github.com/SagerNet/sing-box) - The universal proxy platform.
* [skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
* [tcp_reverse_proxy](https://github.com/yuanfengyun/tcp_reverse_proxy) - Simple TCP reverse proxy
* [tun2socks](https://github.com/xjasonlyu/tun2socks) - tun2socks - powered by gVisor TCP/IP stack.
* [tproxy](https://github.com/kevwan/tproxy) - A cli tool to proxy and analyze TCP connections.
* [traefik](https://github.com/containous/traefik) - Traefik is a modern HTTP reverse proxy and load balancer that makes deploying microservices easy.

### HTTP Clients

*Libraries for making HTTP requests.*

* [fetch](https://github.com/go-zoox/fetch) - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API.
* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) - Get easily stdlib HTTP client, which does not share any state with other clients.
* [go-http-client](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily.
* [go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) - Go http.RoundTripper that emits open telemetry metrics for HTTP requests.
* [go-req](https://github.com/wenerme/go-req) - Declarative golang HTTP client.
* [go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) - Retryable HTTP client in Go.
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.
* [httpc](https://github.com/valord577/httpc) - A customizable and simple HTTP client library. Only depend on the stdlib HTTP client.
* [httpretry](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality.
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [req](https://github.com/imroc/req) - Simple Go HTTP client with Black Magic (Less code and More efficiency).
* [Request](https://github.com/monaco-io/request) - HTTP client for golang, Inspired by Javascript-axios Python-request.
* [requests](https://github.com/carlmjohnson/requests) - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools.
* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
* [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.
* [sreq](https://github.com/winterssy/sreq) - A simple, user-friendly and concurrent safe HTTP request library for Go.

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [go-glmatrix](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](http://glmatrix.net/) library.
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [bun](https://github.com/uptrace/bun) - SQL-first Golang ORM. Successor of go-pg.
* [cacheme](https://github.com/Yiling-J/cacheme-go) - Schema based, typed Redis caching/memoize framework for Go.
* [ent](https://github.com/ent/ent) - Simple, yet powerful entity framework for Go, that makes it easy to build and maintain applications with large data-models.
* [gen](https://github.com/smallnest/gen) - Converts a database into gorm structs and RESTful api.
* [go-dbw](https://github.com/hashicorp/go-dbw) - A simple package that encapsulates database operations.
* [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* [go-sql](https://github.com/rushteam/gosql) - gosql is a easy ORM library for Golang.
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [godb](https://github.com/samonzeweb/godb) - godb is a simple Go query builder and struct mapper, not a full-featured ORM. godb does not manage relationships.
* [GORM](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [GORM Data Types](https://github.com/go-gorm/datatypes) - GORM Customized Data Types Collection.
* [gormt](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct.
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* [marlow](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances.
* [golobby/orm](https://github.com/golobby/orm) - Simple, fast, type-safe, generic orm for developer happiness.
* [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [Prisma](https://github.com/prisma/prisma-client-go) - Prisma Client Go, Typesafe database access for Go.
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* [rel](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

* [dep](https://github.com/golang/dep) - Go dependency tool.
* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go.
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager.
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [gup](https://github.com/nao1215/gup) - Update binaries installed by "go install".
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* [modgv](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language.
* [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies.
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

## Performance

* [go-instrument](https://github.com/nikolaydubina/go-instrument) - Automatically add spans to all methods and functions.
* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* [parca](https://github.com/parca-dev/parca) - Continuous profiling for analysis of CPU, memory usage over time, and down to the line number. Saving infrastructure cost, improving performance, and increasing reliability.
* [pixie](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF.
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [pyroscope](https://github.com/pyroscope-io/pyroscope) - Continuous Profiling Platform fire Debug performance issues down to a single line of code.
* [sprof](https://github.com/felixge/sprof) - sprof is the next revolution in Go profiling.
* [statsviz](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics.
* [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.
* [uptrace](https://github.com/uptrace/uptrace) - Distributed tracing using OpenTelemetry and ClickHouse.

## Plugin 

* [go-plugin](github.com/tiborvass/go-plugin) - Plugins for Go using C shared libraries

## Query Language

* [api-fu](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation.
* [bramble](https://github.com/movio/bramble) - The Movio GraphQL Gateway.
* [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
* [gqlgen](https://github.com/99designs/gqlgen) - gqlgen is a Go library for building GraphQL servers without any fuss.
* [GGql](https://github.com/UHN/ggql) - GraphQL implementation for a GraphQL API that is easy to use and understand while still providing good performance.
* [goven](https://github.com/SeldonIO/goven) - A drop-in query language for any database schema.
* [grapher](https://github.com/reaganiwadha/grapher) - A GraphQL field builder utilizing Go generics with extra utilities and features.
* [graphql](https://github.com/machinebox/graphql) - Low-level GraphQL client for Go.
* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities.
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* [graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use.
* [gws](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation.
* [jsonpath](https://github.com/AsaiYusuke/jsonpath) - A query library for retrieving part of JSON based on JSONPath syntax.
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
* [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.
* [mql](https://github.com/hashicorp/mql) - Model Query Language (mql) is a query language for your database models.
* [rql](https://github.com/a8m/rql) - Resource Query Language for REST API.
* [rqp](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
* [straf](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects.

## Resource Embedding

* [debme](https://github.com/leaanthony/debme) - Create an `embed.FS` from an existing `embed.FS` subdirectory.  
* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy.
* [mule](https://github.com/wlbr/mule) - Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity.
* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* [rebed](https://github.com/soypat/rebed) - Recreate folder structures and files from Go 1.16's `embed.FS` type
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity.
* [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.
* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity.
* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for Go for machine-learning and statistics (similar to pandas).
* [decimal](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* [float](https://github.com/jenska/float) - 80-bit IEEE 754 extended double precision floating-point library for Go.
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [go-estimate](https://github.com/milosgajdos/go-estimate) - State estimation and filtering algorithms in Go.
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.
* [godesim](https://github.com/soypat/godesim) - Extended/multivariable ODE solver framework for event-based simulations with simple API.
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
* [gograph](https://github.com/hmdsefi/gograph) -  A golang generic graph library that provides mathematical graph-theory and algorithms.
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) - Tool to manipulate JSONL graphs with graphviz support.
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
* [age](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
* [argon2-hashing](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
* [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [aws-vault](https://github.com/99designs/aws-vault) - A vault for securely storing and accessing AWS credentials in development environments.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* [booster](https://github.com/anatol/booster) - Fast initramfs generator with full-disk encryption support.
* [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
* [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates.
* [certificates](https://github.com/smallstep/certificates) - Setting up a public key infrastructure (PKI) is out of reach for many small teams.
* [CertMagic](https://github.com/caddyserver/certmagic) - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal.
* [Coraza](https://github.com/corazawaf/coraza) - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library.
* [databunker](https://github.com/securitybunker/databunker) - Secure storage for personal records built to comply with GDPR.
* [dongle](https://github.com/golang-module/dongle) - A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption.
* [ego](https://github.com/edgelesssys/ego) - EGo is an open-source SDK that enables you to develop your own confidential apps in the Go programming language.
* [etcdpasswd](https://github.com/cybozu-go/etcdpasswd) - Distributed Linux user management using etcd.
* [external-secrets](https://github.com/external-secrets/external-secrets) - External Secrets Operator reads information from a third-party service like AWS Secrets Manager and automatically injects the values as Kubernetes Secrets.
* [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server.
* [go-generate-password](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library.
* [go-htpasswd](https://github.com/tg123/go-htpasswd) - Apache htpasswd Parser for Go.
* [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values.
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
* [httpsig](https://github.com/go-fed/httpsig) - Golang implementation of the HTTP Signatures RFC draft, with SSH support.
* [Interpol](https://github.com/avahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
* [jwc](https://github.com/khezen/jwc) - JSON Web Cryptography library.
* [lego](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* [mkcert](https://github.com/FiloSottile/mkcert) - A simple zero-config tool to make locally trusted development certificates with any names you'd like. [mkcert.dev](https://mkcert.dev/)
* [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
* [obscurus](https://github.com/adamgoose/obscurus) - Obscurus is a simple web-based tool for sharing secrets via a short-lived one-time-use link.
* [optimus-go](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm.
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* [pw](https://github.com/iwpnd/pw) - Minimal password generator.
* [saml](https://github.com/crewjam/saml) - SAML library for go.
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) - Encrypt your Secret into a SealedSecret, which is safe to store - even to a public repository. The SealedSecret can be decrypted only by the controller running in the target cluster and nobody else (not even the original author) is able to obtain the original Secret from the SealedSecret.
* [secret](https://github.com/rsjethani/secret) - Prevent your secrets from leaking into logs, std* etc.
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.
* [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert.
* [teler-waf](https://github.com/kitabisa/teler-waf) - teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications.
* [tg](https://github.com/aporeto-inc/tg) - Certificate generation made easy.
* [themis](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.
* [tsip](https://github.com/dgryski/tsip) - Tiny sip-like hash. This repository has Go, amd64, C, and Rust implemtations of a small fast string
hashing function.
* [xkpasswd-go](https://github.com/vot/xkpasswd-go) - Memorable password generator in Go.

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* [bertlv](https://github.com/hexdigest/bertlv) - Go BER-TLV encoding implementation.
* [bertlv](https://github.com/skythen/bertlv) - Golang implementation of parsing and building BER-TLV.
* [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
* [bebop](https://github.com/200sc/bebop) - bebop wire format in Go.
* [buf](https://github.com/bufbuild/buf) - The buf CLI is a tool for working with Protocol Buffers.
* [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure.
* [borsh-go](https://github.com/near/borsh-go) - Implementation of the [Borsh] binary serialization format for Go projects. Borsh stands for Binary Object Representation Serializer for Hashing. It is meant to be used in security-critical projects as it prioritizes consistency, safety, speed, and comes with a strict specification.
* [cbor](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library.
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
* [elastic](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
* [fastproto](https://github.com/billyplus/fastproto) - Protocol Buffers for Go with faster Marshal and Unmarshal methods.
* [fixedwidth](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported).
* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based or code-generation support.
* [go-lctree](https://github.com/sbourlon/go-lctree) - Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation).
* [go-ltsv](https://github.com/Songmu/go-ltsv) - LTSV parser and encoder for Go with reflection.
* [go-tlv](https://github.com/pauloavelar/go-tlv) - Tag-Length-Value (TLV) is a binary encoding scheme used for data transport.
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [Karmem](https://github.com/inkeliz/karmem) - Karmem is a fast binary serialization format, faster than Google Flatbuffers and optimized for TinyGo and WASM.
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* [musgo](https://github.com/ymz-ncnk/musgo) - MusGo is an extremely fast serializer based on code generation. It supports validation, different encodings, aliases, pointers, and private fields.
* [msgpack](https://github.com/shamaton/msgpack) - Easier, faster, but extendable MessagePack Serializer for Golang.
* [msgpack](https://github.com/vmihailenco/msgpack) - MessagePack encoding for Golang.
* [fpack](https://github.com/256dpi/fpack) - A functional approach to encoding and decoding byte sequences.
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [pletter](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers.
* [Sonic](https://github.com/bytedance/sonic) - A blazingly fast JSON serializing & deserializing library, accelerated by JIT (just-in-time compiling) and SIMD (single-instruction-multiple-data).
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.
* [tlv-decoder](https://github.com/thejams/tlv-decoder) - Simple golang tlv-decoder that receive a string with a TLV format and returns a map with the content of the TLV information.
* [tlv](https://github.com/Akagi201/tlv) - [TLV](https://en.wikipedia.org/wiki/Type-length-value) is the representative of type-length-value.
* [tlvp](https://github.com/heyvito/tlvp) - tlvp is a CLI [TLV](https://en.wikipedia.org/wiki/Type-length-value) parser specially designed to handle EMV data. This may be used by payment system researchers and practitioners to read TLV data (both binary and hex-encoded) in a formatted, organised way.
* [TMC](https://github.com/bep/tmc) - Provides basic roundtrip JSON etc. encoding/decoding of a map[string]interface{} with custom type adapters.
* [unitpacking](https://github.com/recolude/unitpacking) - Library to pack unit vectors into as fewest bytes as possible.
* [vtprotobuf](https://github.com/planetscale/vtprotobuf) - A Protocol Buffers compiler that generates optimized marshaling & unmarshaling Go code for ProtoBuf APIv2.

## Server Applications

* [1Panel](https://github.com/1Panel-dev/1Panel) - Modern and Open-Source linux server operation and management panel.
* [algernon](https://github.com/xyproto/algernon) - Small self-contained pure-Go web server with Lua, Markdown, HTTP/2, QUIC, Redis and PostgreSQL support.
* [Apinto](https://github.com/eolinker/apinto) - Apinto is a microservice gateway developed based on golang. It can achieve the purposes of high-performance HTTP API forwarding, multi tenant management, API access control, etc. it has a powerful user-defined plug-in system, which can be expanded by itself, and can quickly help enterprises manage API services and improve the stability and security of API services.
* [beer-search](https://github.com/mosuka/beer-search) - Sample application using Bluge to search beers and breweries.
* [bookstore](https://github.com/Ja7ad/bookstore) - A example of a microservice API based on a clean architecture and SOLID principles implemented.
* [bookkeeper](https://github.com/tensorush/bookkeeper) - Backend for a bookkeeping service based on gRPC.
* [Caddy](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [CasaOS](https://github.com/IceWhaleTech/CasaOS) - A simple, easy-to-use, elegant open-source Personal Cloud system.
* [Cloudreve](https://github.com/cloudreve/Cloudreve) - Self-hosted file management and sharing system, supports multiple storage providers.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [cortex](https://github.com/cortexproject/cortex) - A horizontally scalable, highly available, multi-tenant, long term Prometheus.
* [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
* [corteza-server](https://github.com/cortezaproject/corteza-server) - Corteza server is the back-end of the Corteza ecosystem. The core logic is written in GO, using [go-chi](https://pkg.go.dev/github.com/go-chi/chi@v3.3.4+incompatible?utm_source=gopls) for the routing. External communication occurs via the REST API and web sockets; internal communication happens via gRPC.
* [dendrite](https://github.com/matrix-org/dendrite) - Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers.
* [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
* [dudeldu](https://github.com/krotik/dudeldu) - A simple SHOUTcast server.
* [dummy](https://github.com/neotoolkit/dummy) - Run mock server based off an API contract with one command.
* [ergo](https://github.com/ergo-services/ergo) - Actor based Framework for creating microservices using technologies and design patterns of Erlang/OTP in Golang.
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* [euterpe](https://github.com/ironsmile/euterpe) - Self-hosted music streaming server with built-in web UI and REST API.
* [Flipt](https://github.com/flipt-io/flipt) -  Self-hosted feature flag application that allows you to run experiments across services in your environment.
* [headscale](https://github.com/juanfont/headscale) - An open source, self-hosted implementation of the Tailscale control server.
* [helm-dashboard](https://github.com/komodorio/helm-dashboard) - The Helm Dashboard plugin offers a UI-driven way to view the installed Helm charts, see their revision history and corresponding k8s resources. Also, you can perform simple actions like roll back to a revision or upgrade to newer version.
* [hermes](https://github.com/hashicorp-forge/hermes) - A document management system.
* [hollywood](https://github.com/anthdm/hollywood) - Blazingly fast and light-weight Actor engine written in Golang.
* [ui-server](https://github.com/temporalio/ui-server) - ui-server serves an HTTP API analogue of [Temporal gRPC API](https://github.com/temporalio/api) as well as serves Temporal UI [https://github.com/temporalio/ui](https://github.com/temporalio/ui). It can be compiled into a binary or consumed as a Go library.
* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
* [filebrowser](https://github.com/filebrowser/filebrowser) - filebrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app or as a middleware.
* [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
* [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
* [galene](https://github.com/jech/galene) - The Galène videoconferencing server.
* [gateway-api](https://github.com/kubernetes-sigs/gateway-api) - Repository for the next iteration of composite service (e.g. Ingress) and load balancing APIs.
* [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) - A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it.
* [go-coffeeshop](https://github.com/thangchung/go-coffeeshop) - A practical event-driven microservices demo built with Golang. Nomad, Consul Connect, Vault, and Terraform for deployment.
* [go-ecommerce-microservices](https://github.com/mehdihadeli/go-ecommerce-microservices) - A practical e-commerce microservices, built with golang, domain-driven design, cqrs, event sourcing, vertical slice architecture, event-driven architecture, and the latest technologies.
* [GoTTY](https://github.com/yudai/gotty) - Share your terminal as a web application.
* [gotty](https://github.com/sorenisanerd/gotty) - GoTTY is a simple command line tool that turns your CLI tools into web applications.
* [gubernator](https://github.com/mailgun/gubernator) - High Performance Rate Limiting MicroService and Library.
* [hasura-storage](https://github.com/nhost/hasura-storage) - Storage for Hasura built on top of S3.
* [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go.
* [lets-proxy2](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
* [listmonk](https://github.com/knadh/listmonk) - High performance, self-hosted newsletter and mailing list manager with a modern dashboard. Go + VueJS.
* [Memos](https://github.com/usememos/memos) - A privacy-first, lightweight note-taking service. Easily capture and share your great thoughts.
* [Mimir](https://github.com/grafana/mimir) - Grafana Mimir provides horizontally scalable, highly available, multi-tenant, long-term storage for Prometheus.
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
* [monitoror](https://github.com/monitoror/monitoror) - Unified monitoring wallboard - Light, ergonomic and reliable monitoring for anything.
* [monolith-microservice-shop](https://github.com/ThreeDotsLabs/monolith-microservice-shop) - Source code for [https://threedots.tech/post/microservices-or-monolith-its-detail](https://threedots.tech/post/microservices-or-monolith-its-detail/) article. This shop can work both as monolith and microservices. More info you will find in the article. This repository contains only REST API.
* [moxy](https://github.com/sinhashubham95/moxy) - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint.
* [nakama](https://github.com/heroiclabs/nakama) - Distributed server for social and realtime games and apps.
* [Navidrome Music Server](https://github.com/navidrome/navidrome) - Navidrome is an open source web-based music collection server and streamer. It gives you freedom to listen to your music collection from any browser or mobile device. It's like your personal Spotify!
* [nezha](https://github.com/naiba/nezha) - Nezha Monitoring: Self-hostable, lightweight, servers and websites monitoring and O&M tool.
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
* [nightingale](https://github.com/ccfos/nightingale) - An enterprise-level cloud-native monitoring system, which can be used as drop-in replacement of Prometheus for alerting and Grafana for visualization.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform.
* [Meshery](https://github.com/meshery/meshery) - Meshery, the cloud native manager.
* [Open-IM-Server](https://github.com/OpenIMSDK/Open-IM-Server) - Instant messaging server. Backend in pure Golang, wire transport protocol is JSON over websocket.
* [Owncast](https://github.com/owncast/owncast) - Take control over your live stream video by running it yourself. Streaming + chat out of the box.
* [paopao-ce](https://github.com/rocboss/paopao-ce) - A artistic "twitter like" community built on gin+zinc+vue+ts.
* [Photos](https://github.com/charlieegan3/photos) - This is the source code for the application running at [photos.charlieegan3.com](https://photos.charlieegan3.com/).
* [pocketbase](https://github.com/pocketbase/pocketbase) - [PocketBase](https://pocketbase.io/) is an open source Go backend, consisting of: embedded database (SQLite) with realtime subscriptions, built-in files and users management, convenient Admin dashboard UI, and simple REST-ish API.
* [protoxy](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers.
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka.
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
* [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.
* [rudder-server](https://github.com/rudderlabs/rudder-server) - Privacy and Security focused Segment-alternative, in Golang and React (Customer Data Platform for Developers).
* [rtsp-simple-server](https://github.com/aler9/rtsp-simple-server) - ready-to-use RTSP / RTMP / LL-HLS server and proxy that allows to read, publish and proxy video and audio streams.
* [rttys](https://github.com/zhaojh329/rttys) - Access your device's terminal from anywhere via the web.
* [SFTPGo](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
* [simple-go-api](https://github.com/jmilagroso/simple-go-api) - Simple Go API (Go + Heroku + Postgresql + Redis + JWT).
* [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) - Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management.
* [SKMZ](https://github.com/Shpota/skmz) - A web application that allows to query programmers with their skills via a GraphQL API. The application is implemented with Go and [gqlgen](https://github.com/99designs/gqlgen) on the backend side and React on the front end side. MongoDB is used as a database.
* [sourcegraph](https://github.com/sourcegraph/sourcegraph) - Fast and featureful code search and navigation engine.
* [stash](https://github.com/stashapp/stash) - Stash is a self-hosted webapp written in Go which organizes and serves your porn.
* [Telegraf](https://github.com/influxdata/telegraf) - The plugin-driven server agent for collecting & reporting metrics.
* [Teleport](https://github.com/gravitational/teleport) - Teleport is the easiest, most secure way to access all your infrastructure. Teleport is an identity-aware, multi-protocol access proxy which understands SSH, HTTPS, RDP, Kubernetes API, MySQL, MongoDB and PostgreSQL wire protocols.
* [Tigris](https://github.com/tigrisdata/tigris) - Tigris is a modern, scalable backend for building real-time websites and apps. With a zero-ops scalable pub/sub messaging system and fault-tolerant cloud-native database, provides everything you need to get up and running quickly and efficiently.
* [Trickster](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator.
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - Small, networked, in-memory key-value store.
* [wish](https://github.com/charmbracelet/wish) - Make SSH apps, just like that.
* [WTF Dial](https://github.com/benbjohnson/wtf) - This project provides a real-time dashboard for teams to view how f-cked up they currently are.
* [zinc](https://github.com/zinclabs/zinc) - Zinc is a search engine that does full text indexing. It is a lightweight alternative to Elasticsearch and runs using a fraction of the resources. It uses [bluge](https://github.com/blugelabs/bluge) as the underlying indexing library.
* [xxim-server](https://github.com/cherish-chat/xxim-server) - Xianxian-it belongs to your social territory. Xingxian is a 100% open source social platform. Everyone can build their own server and take ownership of the data.This APP is a non-profit project.

*API server gateway*

* [bahamut](https://github.com/aporeto-inc/bahamut) - Bahamut is a Go library that provides everything needed to build an API server.
* [gateway](https://github.com/fagongzi/gateway) - Gateway is a restful API gateway based on HTTP, which can be used as a unified API access layer.
* [tyk](https://github.com/TykTechnologies/tyk) - Tyk is a lightweight, open source API Gateway and Management Platform enables you to control who accesses your API, when they access it and how they access it.

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

* [go-streams](https://github.com/reugn/go-streams) - Go stream processing library.
* [goio](https://github.com/primetalk/goio) - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2.
* [machine](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability.
* [stream](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* [gospin](https://github.com/m1/gospin) - Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations.
* [got](https://github.com/goradd/got) - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more.
* [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [jet](https://github.com/CloudyKit/jet) - Jet template engine.
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* [maroto](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* [plush](https://github.com/gobuffalo/plush) - Plush is the templating system that Go both needs and deserves. Powerful, flexible, and extendable, Plush is there to make writing your templates that much easier.
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [sprig](https://github.com/Masterminds/sprig) - Useful template functions for Go templates.
* [tbd](https://github.com/lucasepe/tbd) - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata.
* [templ](https://github.com/a-h/templ) - A language for writing HTML user interfaces in Go.
* [tmplfn](https://github.com/caltechlibrary/tmplfn) - tmplfuncs provides a set of common functions useful for working with Go's text/template and html/template packages
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
    * [buzzer](https://github.com/google/buzzer) - Buzzer is a fuzzer toolchain that allows to write eBPF fuzzing strategies.
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.
    * [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.
    * [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx.
    * [covergates](https://github.com/covergates/covergates) - Self-hosted code coverage report review and management service.
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    * [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
    * [endly](https://github.com/viant/endly) - Declarative end to end functional testing.
    * [Ensure](https://github.com/iamkoch/ensure) - A scenario-based testing framework for Go.
    * [fixenv](https://github.com/rekby/fixenv) - Fixture manage engine, inspired by pytest fixtures.
    * [fluentassert](https://github.com/fluentassert/verify) - Extensible, type-safe, fluent assertion Go library.
    * [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework.
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework.
    * [gherkingen](https://github.com/hedhyw/gherkingen) - BDD boilerplate generator and framework.
    * [ginkgo](https://github.com/onsi/ginkgo) - BDD Testing Framework for Go.
    * [gnomock](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    * [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
    * [go-hit](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang.
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    * [go-snaps](http://github.com/gkampitakis/go-snaps) - Jest-like snapshot testing in Golang.
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    * [goc](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language.
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    * [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
    * [godog](https://github.com/cucumber/godog) - Cucumber or Behat like BDD framework for Go.
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    * [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
    * [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
    * [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [Gont](https://github.com/stv0g/gont) - Go network testing toolkit for testing building complex network topologies using Linux namespaces.
    * [Gophish](https://github.com/gophish/gophish) - [Gophish](https://getgophish.com/) is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training.
    * [GoReplay](https://github.com/buger/goreplay) - open-source tool for capturing and replaying live HTTP traffic into a test environment in order to continuously test your system with real data. It can be used to increase confidence in code deployments, configuration changes and infrastructure changes.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
    * [k6](https://github.com/loadimpact/k6) - k6 is a modern load testing tool.
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [schema](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses.
    * [stop-and-go](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency.
    * [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - Convert markdown snippets into testable go code.
    * [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
    * [testza](https://github.com/MarvinJWendt/testza) - Full-featured test framework with nice colorized output.
    * [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
    * [trial](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate.
    * [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools.
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    * [go-localstack](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing.    
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
    * [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    * [mockery](https://github.com/vektra/mockery) - A mock code autogenerator for Golang.
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.
    * [mockit](https://github.com/pasdam/mockit) - Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java.
    * [monkey](https://github.com/awterman/monkey) - One line to mock functions/methods/variables in place without dependency injection or code generation.
    * [mooncake](https://github.com/GuilhermeCaruso/mooncake) - A simple way to generate mocks for multiple purposes.
    * [timex](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
    * [playwright-go](https://github.com/mxschmitt/playwright-go) - browser automation library to control Chromium, Firefox and WebKit with a single API.
    * [rod](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy.
    * [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.

* Fail injection
    * [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

## Text Processing

*Libraries for parsing and manipulating texts.*

### Formatters

* [address](https://github.com/bojanz/address) - Handles address representation, validation and formatting.
* [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
* [bytes](https://github.com/labstack/gommon/tree/master/bytes) - Formats and parses numeric byte values (10K, 2M, 3G, etc.).
* [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
* [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
* [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
* [textwrap](https://github.com/isbm/textwrap) - Wraps text at end of lines. Implementation of `textwrap` module from Python.
* [timefmt-go](https://github.com/itchyny/timefmt-go) - Efficient time formatting library (strftime, strptime) for Golang.

### Markup Languages

* [bafi](https://github.com/mmalcek/bafi) - Universal JSON, BSON, YAML, XML translator to ANY format using templates.
* [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
* [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
* [daz](https://github.com/stevelacy/daz) - Composable HTML components in Golang.
* [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
* [go-output-format](https://github.com/drewstinnett/go-output-format) - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
* [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools.
* [gohtml](https://github.com/yosssi/gohtml) - HTML formatter for Go.
* [goldmark](https://github.com/yuin/goldmark) - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured.
* [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
* [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
* [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
* [htmlyaml](https://github.com/nikolaydubina/htmlyaml) -  Rich rendering of YAML as HTML in Go.
* [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
* [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).

### Parsers/Encoders/Decoders

* [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
* [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
* [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
* [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
* [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
* [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
* [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decoders.
* [go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) - High performance effective top level domains (eTLD) extraction module.
* [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
* [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
* [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
* [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
* [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
* [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
* [normalize](https://github.com/avito-tech/normalize) - Sanitize, normalize and compare fuzzy text.
* [omniparser](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.
* [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
* [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
* [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
* [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
* [tokenizer](https://github.com/bzick/tokenizer) - Parse any string, slice or infinite buffer to any tokens.
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.
* [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.

### Regular Expressions

* [binaryregexp](https://github.com/rsc/binaryregexp) - Go regexp for binary/latin-1 data.
* [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
* [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) - Simple and lightweight wildcard pattern matching.
* [Golang-Regex-Tutorial](https://github.com/StefanSchroeder/Golang-Regex-Tutorial) - Golang - Regular Expression Tutorial.
* [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
* [regex](https://github.com/quasilyte/regex) - regular expression libraries for Go.
* [regroup](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing.
* [rex](https://github.com/hedhyw/rex) - Regular expressions builder.
* [rxscan](https://github.com/yulrizka/rxscan) - rxscan provides functionality to scan text to variables using regular expression capture group.

### Sanitation

* [bluemonday](https://github.com/microcosm-cc/bluemonday) - Fast golang HTML sanitizer (inspired by the OWASP Java HTML Sanitizer) to scrub user generated content of XSS.
* [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.

### Scrapers

* [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
* [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
* [go-recipe](https://github.com/kkyr/go-recipe) - A package for scraping recipes from websites.
* [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
* [gospider](https://github.com/zhshch2002/gospider) - A simple golang spider/scraping framework, build a spider in 3 lines. migrated from [goribot](https://github.com/zhshch2002/goribot)
* [pagser](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
* [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source.
* [walker](https://github.com/cyucelen/walker) - Seamlessly fetch paginated data from any source. Simple and high performance API scraping included.
* [xurls](https://github.com/mvdan/xurls) - Extract urls from text.

### RSS

* [podcast](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang.
* [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.

### Utility/Miscellaneous

* [Bluge](https://github.com/blugelabs/bluge) - modern text indexing in go - [blugelabs.com](blugelabs.com)
* [go-masker](https://github.com/ggwhite/go-masker) - Golang Masker is a simple utility of creating a mask for sensitive information.
* [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
* [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
* [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
* [lemonade](https://github.com/killtw/lemonade) - A sensitive word filter service based on [DFA](https://www.wikiwand.com/en/Deterministic_finite_automaton).
* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
* [radix](https://github.com/yourbasic/radix) - Fast string sorting algorithm.
* [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [airtable](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api).
* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) - Unofficial Golang SDK for AppStore Connect API.
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [bqwriter](https://github.com/OTA-Insight/bqwriter) - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout.
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
* [device-check-go](https://github.com/rinchsan/device-check-go) - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) - Unofficial Dusupay payment gateway API Client for Go.
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) - Unofficial Fasapay payment gateway XML API Client for Golang.
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [go-atlassian](https://github.com/ctreminiom/go-atlassian) - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud).
* [go-aws-news](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS.
* [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
* [go-hibp](https://github.com/wneessen/go-hibp) - Simple Go binding to the "Have I Been Pwned" APIs.
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-lark](https://github.com/go-lark/lark) - - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform.
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-openproject](https://github.com/manuelbcd/go-openproject) - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
* [go-postman-collection](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
* [go-restcountries](https://github.com/chriscross0/go-restcountries) -  Go library for the [REST Countries API](https://countrylayer.com/).
* [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [go-yapla](https://git.iglou.eu/Production/go-yapla) - Go client library for the Yapla v2.0 API.
* [goagi](https://github.com/staskobzar/goagi) - Go library to build Asterisk PBX agi/fastagi applications.
* [goami2](https://github.com/staskobzar/goami2) - AMI v2 library for Asterisk PBX.
* [GoFreeDB](https://github.com/FreeLeh/GoFreeDB) - Golang library providing common and simple database abstractions on top of Google Sheets.
* [gogtrends](https://github.com/groovili/gogtrends) - Google Trends Unofficial API.
* [golang-tmdb](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3.
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gopaapi5](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
* [gosip](https://github.com/koltyakov/gosip) - Go client library SharePoint API.
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
* [jokeapi-go](https://github.com/icelain/jokeapi) - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/).
* [kanka](https://github.com/Henry-Sarabia/kanka) - Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0).
* [lark](https://github.com/chyroc/lark) - [Feishu/Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback.
* [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
* [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](http://sourceware.org/libffi/) integration
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [newsapi-go](https://github.com/jellydator/newsapi-go) - Go client for [NewsAPI](https://newsapi.org/).
* [oapi-codegen](https://github.com/deepmap/oapi-codegen) - Generate Go client and server boilerplate from OpenAPI 3 specifications.
* [openapi3](https://github.com/go-goyave/openapi3) - An automated [OpenAPI 3](https://swagger.io/) specification generator for the [Goyave](https://github.com/go-goyave/goyave) REST API framework, using [kin-openapi/openapi3](https://pkg.go.dev/github.com/getkin/kin-openapi/openapi3) in the background.
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
* [slack](https://github.com/slack-go/slack) - Slack API in Go.
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [swag](https://github.com/zc2638/swag) - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more.
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).
* [translate](https://github.com/poorny/translate) - Go online translation package.
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [twitter-scraper](https://github.com/n0madic/twitter-scraper) - Scrape the Twitter Frontend API without authentication and limits.
* [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
* [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
* [javtube-sdk-go](https://github.com/javtube/javtube-sdk-go) - Just Another Video Tube SDK in Golang.
* [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
* [beyond](https://github.com/wesovilabs/beyond) - The Go tool that will drive you to the AOP world!
* [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
* [bleep](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go.
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clipboard](https://github.com/golang-design/clipboard) - cross-platform clipboard package in Go.
* [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
* [cmd](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux.
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [contextplus](https://github.com/contextplus/contextplus) - Package contextplus provide more easy to use functions for contexts.
* [copy](https://github.com/gotidy/copy) - Package for fast copying structs of different types.
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [countries](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts.
* [countries](https://github.com/pioz/countries) - All you need when you are working with countries in Go.
* [create-go-app](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
* [cryptgo](https://github.com/Gituser143/cryptgo) - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
* [cvt](https://github.com/shockerli/cvt) - Easy and safe convert any value to another type.
* [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository.
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [delve](https://github.com/derekparker/delve) - Go debugger.
* [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a Docker image.
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [EaseProbe](https://github.com/megaease/easeprobe) - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification.
* [ecoji](https://github.com/keith-turner/ecoji) - Encodes (and decodes) data as emojis.
* [equalizer](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go.
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [retry-go](https://github.com/avast/retry-go) - Simple library for retry mechanism.
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [gitbatch](https://github.com/isacikgoz/gitbatch) - manage your git repositories in one place.
* [goawk](https://github.com/benhoyt/goawk) - A POSIX-compliant AWK interpreter written in Go.
* [go-actuator](https://github.com/sinhashubham95/go-actuator) - Production ready features for Go based web frameworks.
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
* [go-convert](https://github.com/Eun/go-convert) - Package go-convert enbles you to convert a value into another type.
* [go-countries](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes.
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [go-lock](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
* [go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) - A Pattern matching library inspired by ts-pattern.
* [go-pkg](https://github.com/chenquan/go-pkg) - A go toolkit.
* [go-pretty](https://github.com/jedib0t/go-pretty) - Utilities to prettify console output of tables, lists, progress-bars, text, etc.
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details.
* [go-project-skeleton](https://github.com/alanchchen/go-project-skeleton) - Go project skeleton
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [go-safe](https://github.com/kenkyu392/go-safe) - Panic-safe sandbox.
* [go-reflect](https://github.com/goccy/go-reflect) - Zero-allocation reflection library for Go.
* [go-singleinstance](https://github.com/allan-simon/go-singleinstance) - Cross platform library to have only one instance of a software (based on python's [tendo](https://github.com/pycontribs/tendo/blob/master/tendo/singleton.py)).
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [go-type](https://github.com/mikekonan/go-types) - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
* [GoAdmin](https://github.com/GoAdminGroup/go-admin) - GoAdmin is a toolkit to help you build a data visualization admin panel for your golang app.
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [goctx](https://github.com/zerosnake0/goctx) - Get your context value with high performance.
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [gofn](https://github.com/tiendc/gofn) - High performance utitlity functions written using Generics for Go 1.18+.
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability.
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [gotro](https://github.com/kokizzu/gotro) - GotRo is a collection of libraries and a Golang web framework.
* [goval](https://github.com/maja42/goval) - Evaluate arbitrary expressions in Go.
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [graterm](https://github.com/skovtunenko/graterm) - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application.
* [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
* [hexd](https://github.com/tidwall/hexd) - hexd formats bytes into hex.
* [hostctl](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands.
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [ip2region](https://github.com/lionsoul2014/ip2region) - Ip2region (2.0 - xdb) is a offline IP address manager framework and locator, support billions of data segments, ten microsecond searching performance. xdb engine implementation for many programming languages.
* [jsend](https://github.com/clevergo/jsend) - JSend's implementation writen in Go.
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
* [just](https://github.com/kazhuravlev/just) - Just a collection of useful functions for working with generic data structures.
* [jqp](https://github.com/noahgorstein/jqp) - A TUI playground to experiment with jq.
* [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
* [kruise](https://github.com/openkruise/kruise) - OpenKruise, official site: [https://openkruise.io](https://openkruise.io) is a CNCF(Cloud Native Computing Foundation) incubating project. It consists of several controllers which extend and complement the Kubernetes core controllers for workload and application management.
* [lancet](https://github.com/duke-git/lancet) - Lancet is a comprehensive, efficient, and reusable util function library of go. Inspired by the java apache common package and lodash.js.
* [lets-go](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
* [limiters](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
* [lo](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...)
* [loncha](https://github.com/kazu/loncha) - A high-performance slice Utilities.
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [mani](https://github.com/alajmo/mani) - CLI tool to help you manage multiple repositories.
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
* [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
* [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
* [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines.
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [nfdump](https://github.com/chrispassas/nfdump) - Read nfdump netflow files.
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [nostromo](https://github.com/pokanop/nostromo) - CLI for building powerful aliases.
* [objwalker](https://github.com/rekby/objwalker) - Walk by go objects with reflection.
* [okrun](https://github.com/xta/okrun) - go run error steamroller.
* [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching libray.
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
* [pid](https://github.com/choleraehyq/pid) - Programatically retrieve the current goroutine's ID.
* [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) - PhoneInfoga is one of the most advanced tools to scan international phone numbers using only free resources. The goal is to first gather standard information such as country, area, carrier and line type on any international phone numbers with a very good accuracy. Then search for footprints on search engines to try to find the VoIP provider or identify the owner.
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [pointer](https://github.com/xorcare/pointer) - Package pointer contains helper routines for simplifying the creation of optional fields of basic type.
* [ptr](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types.
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [puddle](https://github.com/jackc/puddle) - Generic resource pool for Go.
* [r](https://github.com/is5/r) - Python-like `range()` experience for Go.
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [RealiTLScanner](https://github.com/XTLS/RealiTLScanner) - A TLS server scanner for Reality.
* [reflectutils](https://github.com/muir/reflectutils) - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string.
* [remote-touchpad](https://github.com/Unrud/remote-touchpad) - Control mouse and keyboard from a smartphone.
* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans.
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [rest-go](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api.
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
* [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
* [retry-go](https://github.com/avast/retry-go) - Simple library for retry mechanism.
* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [rospo](https://github.com/ferama/rospo) - Simple and reliable ssh tunnels with embedded ssh server in Golang.
* [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
* [scan](https://github.com/wroge/scan) - Scan sql rows into any type powered by generics.
* [scany](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more.
* [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need.
* [set](https://github.com/nofeaturesonlybugs/set) - Performant and flexible struct mapping and loose type conversion.
* [sshman](https://github.com/shoobyban/sshman) - SSH Manager for authorized_keys files on multiple remote servers.
* [shutdown](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling.
* [Signal Context](https://github.com/sethvargo/go-signalcontext) - Signal Context (signalcontext) is a Go library for creating Go context's that cancel on signals. This is very useful for client-side applications that want to cancel operations on user interrupts (e.g. CTRL+C).
* [silk](https://github.com/chrispassas/silk) - Read silk netflow files.
* [slice](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations.
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
* [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier.
* [sorty](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting.
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [sslice](https://github.com/yaa110/sslice) - Create a slice which is always sorted.
* [statiks](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server.
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* [Thanos](https://github.com/thanos-io/thanos) - Highly available Prometheus setup with long term storage capabilities. A CNCF Incubating project. [thanos.io](https://thanos.io/)
* [throttle](https://github.com/yudppp/throttle) - Throttle is an object that will perform exactly one action per duration.
* [tik](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go.
* [tome](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs.
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.
* [tsc](https://github.com/templexxx/tsc) - Get unix time (nanoseconds) in 8ns, 10x faster than stdlib.
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [umutex](https://github.com/yudai/umutex) - unblocking mutexes for those who don't want to write many select clauses or get confused by numerous channels.
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture for String Utilities in Go.
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [watchhttp](https://github.com/nikolaydubina/watchhttp) - Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint.
* [wifiqr](https://github.com/reugn/wifiqr) - Wi-Fi QR Code Generator.
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* [xhex](https://github.com/templexxx/xhex) - Hexadecimal encoding, 20x faster than stdlib

## UUID

*Libraries for working with UUIDs.*

* [cuid](https://github.com/lucsky/cuid) - Collision-resistant hashes for the cloud, in Go.
* [go-snowflake](https://github.com/godruoyi/go-snowflake) - An Lock Free ID Generator for Golang based on Snowflake Algorithm (Twitter announced).
* [go.uuid](https://github.com/satori/go.uuid) - UUID package for Go.
* [goflake](https://github.com/hart87/GoFlake) - A small, scalable, & serverless unique ID generator for use in distributed systems. Inspired by Twitters Snowflake.
* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* [gouid](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation.
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [ksuid](https://github.com/segmentio/ksuid) - K-Sortable Globally Unique IDs.
* [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator.
* [objectid](https://github.com/neonxp/objectid) - Генерация уникальных objectid.
* [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata.
* [snowflake](https://github.com/bwmarrin/snowflake) - A simple to use Go (golang) package to generate or parse Twitter snowflake IDs.
* [shortuuid](https://github.com/lithammer/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs.
* [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
* [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
* [uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
* [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.
* [xid](https://github.com/rs/xid) - Package xid is a globally unique id generator library, ready to safely be used directly in your server code.

## Validation

*Libraries for validation.*

* [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
* [go-tagexpr](https://github.com/bytedance/go-tagexpr) - An interesting go struct tag expression syntax for field validation, etc.
* [gody](https://github.com/guiferpa/gody) - A lightweight struct validator for Go.
* [govalid](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs.
* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to [joi](https://github.com/hapijs/joi).
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [Valgo](https://github.com/cohesivestack/valgo) - Valgo is a type-safe, expressive, and extensible validator library for Golang. Supports localization and is built with generics.
* [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
* [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
* [validator](https://github.com/go-the-way/validator) - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex.
* [valix](https://github.com/marrow16/valix) - Go package for validating requests.

## Version Control

*Libraries for version control.*

* [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
* [froggit-go](https://github.com/jfrog/froggit-go) - Froggit-Go is a Go library, allowing to perform actions on VCS providers.
* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [githooks](https://github.com/gabyx/githooks) - Per-repo and shared Git hooks with version control and auto update.
* [glab](https://github.com/profclems/glab) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
* [go-git](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go.
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history.
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists.
* [go-m3u8](https://github.com/etherlabsio/go-m3u8) - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility.
* [go-mpd](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files.
* [goav](https://github.com/giorgisio/goav) - Comprehensive Go bindings for FFmpeg.
* [gortsplib](https://github.com/aler9/gortsplib) - Pure Go RTSP server and client library.
* [go2rtc](https://github.com/AlexxIT/go2rtc) - Ultimate camera streaming application with support RTSP, RTMP, HTTP-FLV, WebRTC, MSE, HLS, MP4, MJPEG, HomeKit, FFmpeg, etc.
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
* [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Virtualization

* [kata-containers](https://github.com/kata-containers/kata-containers) - Kata Containers is an open source project and community working to build a standard implementation of lightweight Virtual Machines (VMs) that feel and perform like containers, but provide the workload isolation and security advantages of VMs.
* [lima](https://github.com/lima-vm/lima) - Linux virtual machines, typically on macOS, for running containerd.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse.
* [Air](https://github.com/aofei/air) - An ideally refined web framework for Go.
* [anoweb](https://github.com/go-the-way/anoweb) - The lightweight and powerful web framework using the new way for Go.Another go the way.
* [appy](https://github.com/appist/appy) - An opinionated productive web framework that helps scaling business easier.
* [Atreugo](https://github.com/savsgio/atreugo) - High performance and extensible micro web framework with zero memory allocations in hot paths, built on top of fasthttp.
* [Baa](https://github.com/go-baa/baa) - Express Go web framework with routing, middleware, dependency injection, http context.
* [beehive](https://github.com/kubeedge/beehive) - Pluggable module(in-process microservice) and cross-module communication Framework.
* [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go.
* [Beego](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Bud](https://github.com/livebud/bud) - The Full-Stack Web Framework for Go.
* [pulsar](https://github.com/pulsar-go/pulsar) - Pulsar - A Go Web framework for web artisans. Batteries included.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Confetti Framework](https://github.com/confetti-framework/confetti) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
* [Don](https://github.com/abemedia/go-don) - A highly performant and simple to use API framework.
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [eagle](https://github.com/go-eagle/eagle) - A microservice framework for Go. [https://go-eagle.org](https://go-eagle.org/)
* [Fiber](https://github.com/gofiber/fiber) - Fiber is an Express.js inspired web framework written in Go.
    * [cipherPayload](https://github.com/buildingwatsize/cipherPayload) - The GoFiber middleware used for Encrypting & Decrypting on payload body.
    * [gfbmb](https://github.com/SowinskiBraeden/gfbmb) - GoFiber BootStrap Message Box, an easy solution to insert BootStrap message boxes into your html page via GoFiber.
    * [go-hexagonal-architecture](https://github.com/damasdev/go-hexagonal-architecture) - A production-ready, Go boilerplate with hexagonal architecture.
    * [gofiber-gorm-sqlite-api](https://github.com/maxmin93/gofiber-gorm-sqlite-api) - Golang Boilerplate : REST API using Go-Fiber and GORM with SQLite.
    * [gofiber-skeleton](https://github.com/zercle/gofiber-skeleton) - Skeleton for Fiber web framework in Go.
    * [golang-fiber-realworld-example-app](https://github.com/alpody/golang-fiber-realworld-example-app) - Example real world backend API built with Golang + Fiber + Gorm + Swagger.
    * [fiberlogrus](https://github.com/mikhail-bigun/fiberlogrus) - Fiber logrus logger middeware.
    * [fiberprometheus](https://github.com/ansrivas/fiberprometheus) - prometheus middleware for Fiber.
    * [fiber-pongo2-pkger](https://github.com/ansrivas/fiber-pongo2-pkger) - Template-project with fiber and pongo2 as template + pkger to package static assets.
    * [mocktail](https://github.com/Huseyinnurbaki/mocktail) - Mocktail is completely free, 11mb, self-hosted, containerized mock server with a dashboard.
    * [Penguin Statistics - V3 Backend](https://github.com/penguin-statistics/backend-next) - The refactored Penguin Statistics v3 Backend. Built with Go, fiber, bun and go.uber.org/fx. Uses NATS as MQ and Redis as state synchronization.
    * [pupcloud](https://github.com/proofrock/pupcloud) - A portable web file manager and gallery.
    * [recipes](https://github.com/gofiber/recipes) - Examples for Fiber web framework.
    * [street](https://github.com/kokizzu/street) - Dummy complex example how to use Fiber, Svelte-MPA, Clickhouse, Tarantool, Gotro.
    * [sveltefiber](https://github.com/kokizzu/sveltefiber) - Example for gofiber/fiber with svelte.
    * [zlogres](https://github.com/buildingwatsize/zlogres) - middleware for Fiber that logging about api took time since request to response.
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* [Flamingo](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
* [Gearbox](https://github.com/abahmed/gearbox) - A web framework written in Go with a focus on high performance and memory optimization.
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Gin-vue-admin](https://github.com/flipped-aurora/gin-vue-admin) - Gin-vue-admin is a full-stack (frontend and backend separation) framework designed for management system. It integrates multiple functions, such as JWT authentication, dynamic routing, dynamic menu, casbin authentication, form generator, code generator, etc. So that you can focus more time on your business Requirements.
* [Ginrpc](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools.
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [go-app](https://github.com/maxence-charriere/go-app) - A package to build progressive web apps with Go programming language and WebAssembly.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* [goa](https://github.com/goa-go/goa) - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware.
* [GoFrame](https://github.com/gogf/gf) - GoFrame is a modular, full-featured and production-ready application development framework of golang.
* [golamb](https://github.com/twharmon/golamb) - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway.
* [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* [GoTuna](https://github.com/gotuna/gotuna) - Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embeded views and static files.
* [goweb](https://github.com/twharmon/goweb) - Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS.
* [Goyave](https://github.com/go-goyave/goyave) - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
* [gqlgen](https://github.com/arsmn/gqlgen) - gqlgen is a Go library for building GraphQL servers without any fuss.
* [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
* [Hertz](https://github.com/cloudwego/hertz) - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices.
* [Huma](https://github.com/danielgtaylor/huma) -  Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI.
* [Iris](https://github.com/kataras/iris) - The fastest HTTP/2 Go Web Framework. New, modern, easy to learn. Fast development with Code you control. Unbeatable cost-performance.
* [letgo](https://github.com/wjpxxx/letgo) - high-performance Lightweight web framework for the Go programming language. golang web framework.
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity.
* [patron](https://github.com/mantzas/patron) - Go microservice framework.
* [Pnutmux](https://gitlab.com/fruitygo/pnutmux) - Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting.
* [Pulse](https://github.com/gopulse/pulse) - Pulse is an HTTP web framework written in Go.
* [qor5](https://github.com/qor5/web) - Core web foundation based on Vue and htmlgo.
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* [rk-boot](https://github.com/rookie-ninja/rk-boot) - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily.
* [rux](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications.
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.
* [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily.
* [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).
* [yao](https://github.com/YaoApp/yao) - Yao A low code engine to create web services and dashboard.
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.
* [gogo](https://github.com/dolab/gogo) - Modern microservice web framework of golang
* [go-chassis](https://github.com/go-chassis/go-chassis) - microservice framework for rapid development of micro services in Go.
* [moleculer](https://github.com/moleculer-go/moleculer) - Progressive microservices framework for Go - based and compatible with https://github.com/moleculerjs/moleculer
* [spidey](https://github.com/tinrab/spidey) - Online store based on microservices and GraphQL.
* [vecty](https://github.com/gopherjs/vecty) - Vecty is a library for building responsive and dynamic web frontends in Go instead of in JavaScript, HTML & CSS.
* [zinx](https://github.com/aceld/zinx) - Zinx is a lightweight concurrent server framework based on Golang.

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.
* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [echo-middleware](https://github.com/faabiosr/echo-middleware) - Middleware for Echo framework with logging and metrics.
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* [go-limiter](https://github.com/sethvargo/go-limiter) - This package provides a rate limiter in Go (Golang), suitable for use in HTTP servers and distributed workloads. It's specifically designed for configurability and flexibility without compromising throughput.
* [gofer](https://github.com/smallnest/gofer) - Enterprise-level middleware framework, Spring framework for Go ecosystem.
* [go-fault](https://github.com/github/go-fault) - Fault injection middleware for Go.
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
* [mid](https://github.com/bobg/mid) - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more.
* [rk-grpc](https://github.com/rookie-ninja/rk-grpc) - Middleware for gRPC with logging, metrics, auth, tracing etc.
* [rk-gin](https://github.com/rookie-ninja/rk-gin) - Middleware for Gin framework with logging, metrics, auth, tracing etc.
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* [mediary](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router.
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* [goblin](https://github.com/bmf-san/goblin) - A golang http router based on trie tree.
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [goroute](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer.
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* [nchi](https://github.com/muir/nchi) - chi-like router built on httprouter with dependency injection based middleware wrappers.
* [ngamux](https://github.com/ngamux/ngamux) - Simple HTTP router for Go.
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [router](https://github.com/golobby/router) - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language.
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [violetear](https://github.com/nbari/violetear) - Go HTTP router.
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.

### Web Utilities

* [Pirsch](https://github.com/pirsch-analytics/pirsch) - Pirsch is a drop-in, server-side, no-cookie, and privacy-focused analytics solution for Go.
* [web](https://github.com/janos/web) - A collection of HTTP utilities for Go.

## WebAssembly

* [dom](https://github.com/dennwc/dom) - DOM library.
* [go-canvas](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code.
* [tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
* [vert](https://github.com/norunners/vert) - Interop between Go and JS values.
* [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser.
* [wazero](https://github.com/tetratelabs/wazero) - zero dependency WebAssembly runtime for Go developers. [wazero.io](https://wazero.io/)
* [webapi](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL.

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.
* [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

## XML

*Libraries and tools for manipulating XML.*

* [signedxml](https://github.com/ma314smith/signedxml) - Pure go library for processing signed XML documents.
* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [x2j](https://github.com/tidwall/x2j) - Convert xml to json.
* [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go.
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.
* [xml-roundtrip-validator](https://github.com/mattermost/xml-roundtrip-validator) - The Go module github.com/mattermost/xml-roundtrip-validator implements mitigations for multiple security issues in Go's 'encoding/xml'. Applications that use 'encoding/xml' for security-critical operations, such as XML signature validation and SAML, may use the 'Validate' and 'ValidateAll' functions to avoid impact from malicious XML inputs.
* [zek](https://github.com/miku/zek) - Generate a Go struct from XML.

## Zero Trust

* Libraries and tools to implement Zero Trust architectures.

* [Cosign](https://github.com/sigstore/cosign) - Container Signing, Verification and Storage in an OCI registry.
* [in-toto](https://github.com/in-toto/in-toto-golang) - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation.
* [Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication.
* [Spire](https://github.com/spiffe/spire) - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms.

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* [asty](https://github.com/asty-org/asty) - Converts golang AST to JSON and JSON to AST.
* [blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) - blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages.
* [ChainJacking](https://github.com/Checkmarx/chainjacking) - - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
* [Chronos](https://github.com/amit-davidson/Chronos) - Detects race conditions statically.
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects.
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) - iFood API SDK.
* [golines](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [GoPlantUML](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* [tickgit](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
* [todocheck](https://github.com/preslavmihaylov/todocheck) - Static code analyser which links TODO comments in code with issues in your issue tracker.
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) - A linter that detect the possibility to use variables/constants from the Go standard library.
* [vaccum](https://github.com/daveshanley/vacuum) - An ultra-super-fast, lightweight OpenAPI linter and quality checking tool.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [Go Doc](https://github.com/msyrus/vscode-go-doc) - A Visual Studio Code extension for showing definition in output and generating go doc.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [goimports-reviser](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
* [velour](https://github.com/velour/velour) - IRC client for the acme editor.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go.
* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.
* [godal](https://github.com/mafulong/godal) - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm.
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.
* [Goxygen](https://github.com/Shpota/goxygen) - Generate a Web project with Go and Angular, React or Vue.
* [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices.
* [options-gen](https://github.com/kazhuravlev/options-gen) - Functional options described by Dave Cheney's post "Functional options for friendly APIs".
* [re2dfa](https://gitlab.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
* [sqlgen](https://github.com/anqiansong/sqlgen) - Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN.
* [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
* [xgen](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.

## Go Tools

* [apikit](https://github.com/ExperienceOne/apikit) - Generates Golang client and server based on OpenAPI2 (swagger) definitions.
* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* [crawley](https://github.com/s0rg/crawley) - Web scraper/crawler for cli.
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [deptree](https://github.com/vc60er/deptree) - show golang dependence like tree.
* [docs](https://github.com/go-oas/docs) - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [go-james](https://github.com/pieterclaerhout/go-james) - Go project skeleton creator, builds and tests your projects without the manual setup.
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [goblin](https://goblin.reaper.im/) - Golang binaries in a curl, built by goblins.
* [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
* [gomodrun](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
* [gotemplate.io](https://gotemplate.io/) - Online tool to preview text/template templates live.
* [gotestdox](https://github.com/bitfield/gotestdox) - Show Go test results as readable sentences.
* [gothanks](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
* [igo](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!)
* [Local Docker DB](https://github.com/alexmacarthur/local-docker-db) - A collection of Docker Compose files I've used to quickly spin up local databases of various sorts.
* [modver](https://github.com/bobg/modver) - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [pig](https://github.com/donuts-are-good/pig) - DNS Intelligence Tool.
* [Portainer](https://github.com/portainer/portainer) - Making Docker and Kubernetes management easy. [www.portainer.io](https://www.portainer.io/)
* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* [roumon](https://github.com/becheran/roumon) - Monitor current state of all active goroutines via a command line interface.
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.
* [sake](https://github.com/alajmo/sake) - sake is a command runner for local and remote hosts.
* [textra](https://github.com/ravsii/textra) - Extract Go struct field names, types and tags for filtering and exporting.
* [typex](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.
* [wsbench](https://github.com/lxzan/wsbench) - websocket benchmark tool.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [abbreviate](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs.
* [air](https://github.com/cosmtrek/air) - Air is yet another live-reloading command line utility for Go applications in development.
* [ali](https://github.com/nakabonne/ali) - A load testing tool capable of performing real-time analysis, inspired by vegeta and [jplot](https://github.com/rs/jplot).
* [argo-workflows](https://github.com/argoproj/argo-workflows) - Workflow engine for Kubernetes.
* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* [Balerter](https://github.com/balerter/balerter) - A self-hosted script-based alerting manager.
* [Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.
* [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [buildkit](https://github.com/moby/buildkit) - Concurrent, cache-efficient, and Dockerfile-agnostic builder toolkit.
* [Buildkite](https://github.com/buildkite/agent) - The Buildkite Agent is an open-source toolkit written in Go for securely running build jobs on any device or network.
* [buildx](https://github.com/docker/buildx) - Docker CLI plugin for extended build capabilities with [BuildKit](https://github.com/moby/buildkit).
* [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go.
* [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [ddosify](https://github.com/ddosify/ddosify) - High-performance load testing tool, written in Golang.
* [DevOps](https://github.com/Pradumnasaraf/DevOps) - This repo contains all learning related to DevOps.
* [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
* [Distribution](https://github.com/distribution/distribution) - The toolset to pack, ship, store, and deliver content.
* [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) - Docker image for building Go binaries for Windows with MinGW toolchain.
* [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels.
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
* [flannel](https://github.com/flannel-io/flannel) - Flannel is a simple and easy way to configure a layer 3 network fabric designed for Kubernetes.
* [Fleet device management](https://github.com/fleetdm/fleet) - Lightweight, programmable telemetry for servers and workstations.
* [flux2](https://github.com/fluxcd/flux2) - Open and extensible continuous delivery solution for Kubernetes. Powered by GitOps Toolkit. [Website](https://fluxcd.io/)
* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
* [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket.
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.[gitness.com](https://gitness.com/)
* [Gitness](https://github.com/harness/gitness) - Gitness is an Open Source developer platform with Source Control management, Continuous Integration and Continuous Delivery.
* [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
* [go-rocket-update](https://github.com/mouuff/go-rocket-update) - A simple way to make self updating Go applications - Supports Github and Gitlab.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [gobrew](https://github.com/kevincobain2000/gobrew) - Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash.
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [govvv](https://github.com/ahmetalpbalkan/govvv) - "go build" wrapper to easily add version information into Go binaries.
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [helm](https://github.com/helm/helm) - The Kubernetes Package Manager.
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [httpref](https://github.com/dnnrly/httpref) - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
* [jcli](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way.
* [k6](https://github.com/k6io/k6) - A modern load testing tool, using Go and JavaScript - [https://k6.io](https://k6.io)
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
* [kin-openapi](https://github.com/getkin/kin-openapi) - OpenAPI 3.0 implementation for Go (parsing, converting, validation, and more).
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [KubeVela](https://github.com/kubevela/kubevela) - KubeVela is a modern application delivery platform that makes deploying and operating applications across today's hybrid, multi-cloud environments easier, faster and more reliable.
* [ko](https://github.com/google/ko) - Command line tool for building and deploying Go applications on Kubernetes.
* [kool](https://github.com/kool-dev/kool) - Command line tool for managing Docker environments as an easy way.
* [kwatch](https://github.com/abahmed/kwatch) - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly.
* [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
* [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
* [mantil](https://github.com/mantil-io/mantil) - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure.
* [minikube](https://github.com/kubernetes/minikube) - Run Kubernetes locally.
* [mizu](https://github.com/up9inc/mizu) - API traffic viewer for Kubernetes enabling you to view all API communication between microservices, multiprotocol support: HTTP1.1, HTTP/2, AMQP, Kafka, Redis.
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* [plow](https://github.com/six-ddc/plow) - A high-performance HTTP benchmarking tool with real-time web UI and terminal displaying.
* [PipeCD](https://github.com/pipe-cd/pipecd) - A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications.
* [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [reviewdog](https://github.com/reviewdog/reviewdog) - A code review dog who keeps your codebase healthy.
* [rook](https://github.com/rook/rook) - Storage Orchestration for Kubernetes.
* [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [s5cmd](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool.
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
* [tf-profile](https://github.com/datarootsio/tf-profile) - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
* [trubka](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
* [uTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml.
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [wait-for](https://github.com/dnnrly/wait-for) - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things.
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.
* [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
* [goproxy](https://github.com/goproxyio/goproxy) - global proxy for Go modules. https://goproxy.io

### Other Software

* [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
* [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [chihuahua](https://codeberg.org/momar/chihuahua) - The smallest watchdog on earth. Tiny, monitoring-plugins compatible monitoring with a status page.
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [dp](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
* [expvarmon](https://github.com/divan/expvarmon) - TermUI based Go apps monitor using [expvars](http://golang.org/pkg/expvar) variables (/debug/vars). Quickest way to monitor your Go app.
* [Gebug](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
* [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.
* [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [GoNB](https://github.com/janpfeifer/gonb) - Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab).
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [Guora](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go.
* [hoofli](https://github.com/dnnrly/hoofli) - Generate PlantUML diagrams from Chrome or Firefox network inspections.
* [httpstat](https://github.com/davecheney/httpstat) - It's like curl -v, with colours.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
* [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) - cowsay is reborn. for a New Era.
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [nexttrace](https://github.com/sjlleo/nexttrace) - An open source visual route tracking CLI tool.
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [Plik](https://github.com/root-gg/plik) - Plik is a temporary file upload system (Wetransfer like) in Go.
* [portal](https://github.com/SpatiumPortae/portal) - Portal is a quick and easy command-line file transfer utility from any computer to another.
* [protoncheck](https://github.com/servusdei2018/protoncheck) - ProtonMail module for waybar/polybar/yabar/i3blocks.
* [rancher](https://github.com/rancher/rancher) - Complete container management platform.
* [restic](https://github.com/restic/restic) - De-duplicating backup program.
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [stew](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [tcpdog](https://github.com/mehrdadrad/tcpdog) - eBPF based TCP observability.
* [tcpprobe](https://github.com/mehrdadrad/tcpprobe) - TCP tool for network performance and path monitoring, including socket statistics.
* [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal.
* [termshark](https://github.com/gcla/termshark) - A terminal user-interface for tshark, inspired by Wireshark.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vaku](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).
* [woke](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code.
* [zs](https://git.mills.io/prologic/zs) - an extremely minimal static site generator.

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [1m-go-tcp-server](https://github.com/smallnest/1m-go-tcp-server) - benchmarks for implementation of servers which support 1 million connections. 
* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark.
* [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) - benchmarks for machine learning inference in Go.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
* [dotGo](http://www.dotgo.eu) - Paris, France.
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](http://golab.io/) - Florence, Italy.
* [GolangUK](http://golanguk.com/) - London, UK.
* [GopherChina](http://gopherchina.org) - Shanghai, China.
* [GopherCon](http://www.gophercon.com/) - Denver, USA.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR.
* [GopherCon Europe](https://gophercon.is/) - Reykjavik, Iceland.
* [GopherCon India](https://www.gophercon.in/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
* [GothamGo](http://gothamgo.com/) - New York City, USA.
* [GoWayFest](https://goway.io/) - Minsk, Belarus.

## E-Books

* [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
* [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
* [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
* [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
* [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
* [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Faster](https://leanpub.com/gofaster) - This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster.
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian.
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Lets-Go](https://lets-go.alexedwards.net) - A step-by-step guide to creating fast, secure and maintanable web applications with Go.
* [Network Programming With Go](https://jan.newmarch.name/golang/)
* [Practical Go Lessons](https://www.practical-go-lessons.com/)
* [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
* [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.
* [Go-SCP](https://github.com/OWASP/Go-SCP) - Go programming language secure coding practices guide

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg].
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.
* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
* [gophers](https://github.com/egonelbre/gophers) - Free gophers.
* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics.
* [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.

## Meetups

* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBandung](https://www.meetup.com/GoBandung/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Style Guides

* [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide)
* [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
* [Edge X Foundry](https://wiki.edgexfoundry.org/display/FA/Contributor%27s+Guide+-+Go+Lang)
* [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
* [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
* [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
* [Sourcegraph](https://about.sourcegraph.com/handbook/engineering/go_style_guide)
* [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
* [Uber](https://github.com/uber-go/guide/blob/master/style.md)

## Social Media

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

### Reddit
 * [r/golang](https://www.reddit.com/r/golang/)

## Websites

* [Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) - A curated list of awesome golang workshops.
* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) - Parse awesome-go README file and generate a new README file with repo info.
* [Code with Mukesh](https://codewithmukesh.com/blog/category/golang) - Software Engineer and Blogs @ codewithmukesh.com.
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Coding Mystery](https://codingmystery.com/) - Solve exciting escape-room-inspired programming challenges using Go.
* [Go Blog](https://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusivly for Golang related Roles.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [Golang Resources](https://golangresources.com) - A curation of the best articles, exercises, talks and videos to learn Go.
* [Golang Weekly](https://discu.eu/weekly/golang) - Each monday projects, tutorials and articles about Go.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
* [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
* [Lille Gophers](https://lille-gophers.loscrackitos.codes/) - Golang talks community in Lille, France ([@LilleGophers](https://twitter.com/LilleGophers)).
* [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [100 Go Mistakes and How to Avoid Them](https://github.com/teivah/100-go-mistakes) - Source code of [100 Go Mistakes and How to Avoid Them](https://www.manning.com/books/100-go-mistakes-and-how-to-avoid-them)
* [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [7 days golang](https://github.com/geektutu/7days-golang) - 7 days golang programs from scratch (web framework Gee, distributed cache GeeCache, object relational mapping ORM framework GeeORM, rpc framework GeeRPC etc).
* [A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) - Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
* [Build a Database in 1000 lines of code]( https://link.medium.com/O9YQlx89Htb) - Build a NoSQL Database From Zero in 1000 Lines of Code.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
* [Debugged.it Go patterns](https://github.com/haveyoudebuggedit/go-patterns) - Advanced Go patterns with ready-to-run examples.
* [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go.
* [design-pattern-in-go](https://github.com/aierui/design-pattern-in-go) - Design patterns are typical solutions to commonly occurring problems in software design.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go.
* [Games With Go](https://gameswithgo.org/) - A video series teaching programming and game development.
* [Go API Boilerplate](https://github.com/zubroide/go-api-boilerplate) - Boilerplate for Golang API.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [go-clean-template](https://github.com/evrone/go-clean-template) - Clean Architecture template for Golang services.
* [go-concurrency](https://github.com/code-review-checklists/go-concurrency) - Checklist for code reviews.
* [go-concurrency-guide](https://github.com/luk4z7/go-concurrency-guide) - Practical concurrency guide in Go, communication by channels, patterns.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go in 7 days](https://github.com/harrytran103/7_days_of_go) - Learn everything about Go in 7 days (from a Nodejs developer).
* [Go generics example](https://github.com/mattn/go-generics-example) - Example code for Go generics.
* [go-misc](https://github.com/aclements/go-misc) - Miscellaneous Go hacks.
* [go-interview](https://github.com/shomali11/go-interview) - Collection of Technical Interview Questions solved with Go.
* [Go Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go programming.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - Interactively edit & play Go snippets on your mobile device.
* [go project layout](https://gist.github.com/candlerb/3cb11576b2d73800b58f3b548dc2ba4a) - Suggestions for go project layout.
* [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
* [goapp](https://github.com/bnkamalesh/goapp) - An opinionated guideline to structure & develop a Go web application/service.
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
* [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
* [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
* [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
* [GolangTraining](https://github.com/GoesToEleven/GolangTraining) - Training for Golang (go language).
* [GoRestApi](https://github.com/snowzach/gorestapi) - Golang REST API Template.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [Hex Monscape](https://github.com/Haraj-backend/hex-monscape) - Getting started guidelines in writing maintainable code using Hexagonal Architecture.
* [High performance with go](https://github.com/geektutu/high-performance-go) - High performance coding with golang.
* [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
* [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Implementing CRUD in Golang REST API with Mux & GORM](https://codewithmukesh.com/blog/implementing-crud-in-golang-rest-api/) - Building a CRUD Golang REST API from scratch using MUX, GORM, MySQL, Viper and clean folder seperation. Entire source code is also included!
* [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Serie of article in order to learn Golang language by concrete applications as example.
* [Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) - Learn Go with thousands of examples, exercises, and quizzes.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) - Getting started with golang for beginner.
* [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
* [React Components in Go](https://bepsays.com/en/2016/10/13/react-in-go) - Write React Components in Go.
* [Simple Bank](https://github.com/techschool/simplebank) - This repository contains the codes of the [Backend Master Class](https://bit.ly/backendmaster) course by [TECH SCHOOL](https://dev.to/techschoolguru) on our [Youtube channel](https://www.youtube.com/c/TECHSCHOOLGURU).
* [Saving a Third of Our Memory by Re-ordering Go Struct Fields](https://qvault.io/golang/struct-field-ordering-memory/) - How inefficient field ordering in Go structs.
* [Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) - Everything about building, deploying and scaling Go applications in production.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [ultimate-go](https://github.com/hoanhan101/ultimate-go) - Ultimate Go study guide, with heavily documented code and programs analysis all in 1 place → https://www.getrevue.co/profile/hoanhan101
* [Using Go with and C (Static and Dynamic) Libraries](https://github.com/lxwagn/using-go-with-c-libraries) - A tutorial project showing how to use C static and dynamic libraries (.a and .so) with Golang.
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
* [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

### Guided Learning 

* [The Go Developer Roadmap](https://roadmap.sh/golang) - A visual roadmap that new Go developers can follow through to help them learn Go.
* [The Go Learning Path](https://tutorialedge.net/paths/golang/) - A guided learning path containing a mix of free and premium resources.
