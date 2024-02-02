# top-go

[top-go](https://github.com/zhufuyi/top-go) is a page showing go language related github repositories and learning materials, data from [awesome-go](https://github.com/avelino/awesome-go), in awesome-go is hard to see those github repositories use more people, not very friendly to repository selection, so add the number of stars to each github repository, and by the number of stars descending display, mainly to make repository selection easier, **top-go** update data once every half month.

Click here to see [top 500 repositories](https://github.com/zhufuyi/top-go/blob/main/top500-repos.md).

Click here to see [top 100 active repositories](https://github.com/zhufuyi/top-go/blob/main/top100-active-repos.md).

<br>

---

## Catalogue list

- [Audio and Music](#audio-and-music)
- [Authentication and OAuth](#authentication-and-oauth)
- [Blockchain](#blockchain)
- [Bot Building](#bot-building)
- [Build Automation](#build-automation)
- [Command Line](#command-line)
  - [Advanced Console UIs](#advanced-console-uis)
  - [Standard CLI](#standard-cli)
- [Configuration](#configuration)
- [Continuous Integration](#continuous-integration)
- [CSS Preprocessors](#css-preprocessors)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Bit-packing and Compression](#bit-packing-and-compression)
  - [Bit Sets](#bit-sets)
  - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
  - [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
  - [Iterators](#iterators)
  - [Maps](#maps)
  - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
  - [Nullable Types](#nullable-types)
  - [Queues](#queues)
  - [Sets](#sets)
  - [Text Analysis](#text-analysis)
  - [Trees](#trees)
  - [Pipes](#pipes)
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
- [Distributed Systems](#distributed-systems)
- [Dynamic DNS](#dynamic-dns)
- [Email](#email)
- [Embeddable Scripting Languages](#embeddable-scripting-languages)
- [Error Handling](#error-handling)
- [File Handling](#file-handling)
- [Financial](#financial)
- [Forms](#forms)
- [Functional](#functional)
- [Game Development](#game-development)
- [Generators](#generators)
- [Geographic](#geographic)
- [Go Compilers](#go-compilers)
- [Goroutines](#goroutines)
- [GUI](#gui)
- [Hardware](#hardware)
- [Images](#images)
- [IoT (Internet of Things)](#iot-internet-of-things)
- [Job Scheduler](#job-scheduler)
- [JSON](#json)
- [Logging](#logging)
- [Machine Learning](#machine-learning)
- [Messaging](#messaging)
- [Microsoft Office](#microsoft-office)
  - [Microsoft Excel](#microsoft-excel)
- [Miscellaneous](#miscellaneous)
  - [Dependency Injection](#dependency-injection)
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
  - [HTTP Clients](#http-clients)
- [OpenGL](#opengl)
- [ORM](#orm)
- [Package Management](#package-management)
- [Performance](#performance)
- [Query Language](#query-language)
- [Resource Embedding](#resource-embedding)
- [Science and Data Analysis](#science-and-data-analysis)
- [Security](#security)
- [Serialization](#serialization)
- [Server Applications](#server-applications)
- [Stream Processing](#stream-processing)
- [Template Engines](#template-engines)
- [Testing](#testing)
  - [Testing Frameworks](#testing-frameworks)
  - [Mock](#mock)
  - [Fuzzing and delta-debugging/reducing/shrinking.](#fuzzing-and-delta-debuggingreducingshrinking.)
  - [Selenium and browser control tools.](#selenium-and-browser-control-tools.)
  - [Fail injection](#fail-injection)
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
- [Web Frameworks](#web-frameworks)
  - [Middlewares](#middlewares)
    - [Actual middlewares](#actual-middlewares)
    - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
  - [Routers](#routers)
- [WebAssembly](#webassembly)
- [Windows](#windows)
- [XML](#xml)
- [Zero Trust](#zero-trust)
- [Code Analysis](#code-analysis)
- [Editor Plugins](#editor-plugins)
- [Go Generate Tools](#go-generate-tools)
- [Go Tools](#go-tools)
- [Software Packages](#software-packages)
  - [DevOps Tools](#devops-tools)
  - [Other Software](#other-software)
- [Benchmarks](#benchmarks)
- [Conferences](#conferences)
- [E-Books](#e-books)
  - [E-books for purchase](#e-books-for-purchase)
  - [Free e-books](#free-e-books)
- [Gophers](#gophers)
- [Meetups](#meetups)
- [Style Guides](#style-guides)
- [Social Media](#social-media)
  - [Twitter](#twitter)
  - [Reddit](#reddit)
- [Websites](#websites)
  - [Tutorials](#tutorials)
- [Websites](#websites)


<br><br>

---

<br><br>

## Audio and Music

_Libraries for manipulating audio._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Oto](https://github.com/hajimehoshi/oto) | 1.4k | A low-level library to play sound on multiple platforms. |
| <b>[PortAudio](https://github.com/gordonklaus/portaudio) | 649 | Go bindings for the PortAudio audio I/O library. |
| <b>[music-theory](https://github.com/go-music-theory/music-theory) | 421 | Music theory models in Go. |
| <b>[id3v2](https://github.com/bogem/id3v2) | 318 | ID3 decoding and encoding library for Go. |
| <b>[GoAudio](https://github.com/DylanMeeus/GoAudio) | 317 | Native Go Audio Processing Library. |
| <b>[flac](https://github.com/mewkiz/flac) | 278 | Native Go FLAC encoder/decoder with support for FLAC streams. |
| <b>[malgo](https://github.com/gen2brain/malgo) | 251 | Mini audio library. |
| <b>[gaad](https://github.com/Comcast/gaad) | 118 | Native Go AAC bitstream parser. |
| <b>[minimp3](https://github.com/tosone/minimp3) | 117 | Lightweight MP3 decoder library. |
| <b>[gosamplerate](https://github.com/dh1tw/gosamplerate) | 31 | libsamplerate bindings for go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Authentication and OAuth

_Libraries for implementing authentications schemes._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[casbin](https://github.com/hsluoyz/casbin) | 16.0k | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| <b>[jwt-go](https://github.com/golang-jwt/jwt) | 6.0k | A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs. |
| <b>[oauth2](https://github.com/golang/oauth2) | 5.0k | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| <b>[goth](https://github.com/markbates/goth) | 4.7k | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| <b>[keto](https://github.com/ory/keto) | 4.4k | Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models. |
| <b>[authboss](https://github.com/volatiletech/authboss) | 3.6k | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| <b>[go-jose](https://github.com/square/go-jose) | 2.0k | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| <b>[loginsrv](https://github.com/tarent/loginsrv) | 1.9k | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| <b>[osin](https://github.com/openshift/osin) | 1.9k | Golang OAuth2 server library. |
| <b>[scs](https://github.com/alexedwards/scs) | 1.8k | Session Manager for HTTP servers. |
| <b>[gologin](https://github.com/dghubble/gologin) | 1.7k | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| <b>[gorbac](https://github.com/mikespook/gorbac) | 1.5k | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| <b>[oidc](https://github.com/zitadel/oidc) | 1.1k | Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation |
| <b>[paseto](https://github.com/o1egl/paseto) | 779 | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| <b>[jwt](https://github.com/cristalhq/jwt) | 635 | Safe, simple and fast JSON Web Tokens for Go. |
| <b>[go-guardian](https://github.com/shaj13/go-guardian) | 513 | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| <b>[permissions2](https://github.com/xyproto/permissions2) | 498 | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| <b>[jwt](https://github.com/pascaldekloe/jwt) | 345 | Lightweight JSON Web Token (JWT) library. |
| <b>[jeff](https://github.com/abraithwaite/jeff) | 259 | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| <b>[jwt-auth](https://github.com/adam-hanna/jwt-auth) | 231 | JWT middleware for Golang http servers with many configuration options. |
| <b>[go-jose](https://github.com/go-jose/go-jose) | 210 | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| <b>[otpgen](https://github.com/grijul/otpgen) | 133 | Library to generate TOTP/HOTP codes. |
| <b>[sessionup](https://github.com/swithek/sessionup) | 123 | Simple, yet effective HTTP session management and identification package. |
| <b>[session](https://github.com/icza/session) | 114 | Go session management for web servers (including support for Google App Engine - GAE). |
| <b>[sjwt](https://github.com/brianvoe/sjwt) | 114 | Simple jwt generator and parser. |
| <b>[rbac](https://github.com/zpatrick/rbac) | 107 | Minimalistic RBAC package for Go applications. |
| <b>[sessions](https://github.com/adam-hanna/sessions) | 75 | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| <b>[securecookie](https://github.com/chmike/securecookie) | 74 | Efficient secure cookie encoding/decoding. |
| <b>[branca](https://github.com/essentialkaos/branca) | 71 | branca token [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+. |
| <b>[otpgo](https://github.com/jltorresm/otpgo) | 65 | Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. |
| <b>[go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) | 60 | Golang library for providing a canonical representation of email address. |
| <b>[scope](https://github.com/SonicRoshan/scope) | 33 | Easily Manage OAuth2 Scopes In Go. |
| <b>[cookiestxt](https://github.com/mengzhuo/cookiestxt) | 12 | provides parser of cookies.txt file format. |
| <b>[gosession](http://github.com/Kwynto/gosession) | 0 | This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, at least it tries to become one. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Blockchain

_Tools for building blockchains._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-ethereum](https://github.com/ethereum/go-ethereum) | 45.0k | Official Go implementation of the Ethereum protocol. |
| <b>[kubo](https://github.com/ipfs/kubo) | 16.0k | A blockchain framework implemented in Go. It provides content-addressable storage which can be used for decentralized storage in DApps. It is based on the IPFS protocol. |
| <b>[cosmos-sdk](https://github.com/cosmos/cosmos-sdk) | 5.7k | A Framework for Building Public Blockchains in the Cosmos Ecosystem. |
| <b>[tendermint](https://github.com/tendermint/tendermint) | 5.6k | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| <b>[solana-go](https://github.com/gagliardetto/solana-go) | 503 | Go library to interface with Solana JSON RPC and WebSocket interfaces. |
| <b>[cometbft](https://github.com/cometbft/cometbft) | 454 | A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm. |
| <b>[gossamer](https://github.com/ChainSafe/gossamer) | 404 | A Go implementation of the Polkadot Host. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Bot Building

_Libraries for building and working with bots._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) | 5.2k | Simple and clean Telegram bot client. |
| <b>[olivia](https://github.com/olivia-ai/olivia) | 3.6k | A chatbot built with an artificial neural network. |
| <b>[telebot](https://github.com/tucnak/telebot) | 3.5k | Telegram bot framework written in Go. |
| <b>[wayback](https://github.com/wabarc/wayback) | 1.6k | A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages. |
| <b>[Kelp](https://github.com/stellar/kelp) | 1.1k | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| <b>[Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) | 977 | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| <b>[go-chat-bot](https://github.com/go-chat-bot/bot) | 811 | IRC, Slack & Telegram bot written in Go. |
| <b>[slacker](https://github.com/shomali11/slacker) | 808 | Easy to use framework to create Slack bots. |
| <b>[tbot](https://github.com/yanzay/tbot) | 347 | Telegram bot server with API similar to net/http. |
| <b>[go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 322 | Library to write bots for twitch.tv chat |
| <b>[telego](https://github.com/mymmrac/telego) | 318 | Telegram Bot API library for Golang with full one-to-one API implementation. |
| <b>[echotron](https://github.com/NicoNex/echotron) | 303 | An elegant and concurrent library for Telegram Bots in Go. |
| <b>[bot](https://github.com/go-telegram/bot) | 279 | Zero-dependencies Telegram Bot library with additional UI components |
| <b>[go-sarah](https://github.com/oklahomer/go-sarah) | 260 | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| <b>[Tenyks](https://github.com/kyleterry/tenyks) | 176 | Service oriented IRC bot using Redis and JSON for messaging. |
| <b>[slack-bot](https://github.com/innogames/slack-bot) | 158 | Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github... |
| <b>[larry](https://github.com/ezeoleaf/larry) | 155 | Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go. |
| <b>[hanu](https://github.com/sbstjn/hanu) | 152 | Framework for writing Slack bots. |
| <b>[go-tgbot](https://github.com/olebedev/go-tgbot) | 117 | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| <b>[ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 84 | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| <b>[margelet](https://github.com/zhulik/margelet) | 82 | Framework for building Telegram bots. |
| <b>[slackscot](https://github.com/alexandre-normand/slackscot) | 56 | Another framework for building Slack bots. |
| <b>[govkbot](https://github.com/nikepan/govkbot) | 46 | Simple Go [VK](https://vk.com) bot library. |
| <b>[teleterm](https://github.com/alfiankan/teleterm) | 33 | Telegram Bot Exec Terminal Command. |
| <b>[micha](https://github.com/onrik/micha) | 26 | Go Library for Telegram bot api. |
| <b>[go-joe](https://joe-bot.net) | - | A general-purpose bot library inspired by Hubot but written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Build Automation

_Libraries and tools helping with build automation._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Task](https://github.com/go-task/task) | 9.4k | simple "Make" alternative. |
| <b>[realize](https://github.com/tockins/realize) | 4.4k | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| <b>[mage](https://github.com/magefile/mage) | 3.8k | Mage is a make/rake-like build tool using Go. |
| <b>[mmake](https://github.com/tj/mmake) | 1.7k | Modern Make. |
| <b>[xc](https://github.com/joerdav/xc) | 947 | Task runner with README.md defined tasks, executable markdown. |
| <b>[goyek](https://github.com/goyek/goyek) | 477 | Create build pipelines in Go. |
| <b>[taskctl](https://github.com/taskctl/taskctl) | 272 | Concurrent task runner. |
| <b>[1build](https://github.com/gopinath-langote/1build) | 219 | Command line tool to frictionlessly manage project-specific commands. |
| <b>[gaper](https://github.com/maxcnunes/gaper) | 79 | Builds and restarts a Go project when it crashes or some watched file changes. |
| <b>[anko](https://github.com/GuilhermeCaruso/anko) | 36 | Simple application watcher for multiple programming languages. |
| <b>[gilbert](https://go-gilbert.github.io) | - | Build system and task runner for Go projects. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Command Line


<br>

### Advanced Console UIs

_Libraries for building Console Applications and Console User Interfaces._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bubbletea](https://github.com/charmbracelet/bubbletea) | 22.0k | Go framework to build terminal apps, based on The Elm Architecture. |
| <b>[termui](https://github.com/gizak/termui) | 13.0k | Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). |
| <b>[gocui](https://github.com/jroimartin/gocui) | 9.6k | Minimalist Go library aimed at creating Console User Interfaces. |
| <b>[lipgloss](https://github.com/charmbracelet/lipgloss) | 6.9k | Declaratively define styles for color, format and layout in the terminal. |
| <b>[go-prompt](https://github.com/c-bata/go-prompt) | 5.1k | Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). |
| <b>[termbox-go](https://github.com/nsf/termbox-go) | 4.6k | Termbox is a library for creating cross-platform text-based interfaces. |
| <b>[pterm](https://github.com/pterm/pterm) | 4.4k | A library to beautify console output on every platform with many combinable components. |
| <b>[bubbles](https://github.com/charmbracelet/bubbles) | 4.3k | TUI components for bubbletea. |
| <b>[progressbar](https://github.com/schollz/progressbar) | 3.7k | Basic thread-safe progress bar that works in every OS. |
| <b>[asciigraph](https://github.com/guptarohit/asciigraph) | 2.4k | Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. |
| <b>[termdash](https://github.com/mum4k/termdash) | 2.4k | Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). |
| <b>[mpb](https://github.com/vbauerster/mpb) | 2.2k | Multi progress bar for terminal applications. |
| <b>[spinner](https://github.com/briandowns/spinner) | 2.2k | Go package to easily provide a terminal spinner with options. |
| <b>[uiprogress](https://github.com/gosuri/uiprogress) | 2.1k | Flexible library to render progress bars in terminal applications. |
| <b>[termenv](https://github.com/muesli/termenv) | 1.6k | Advanced ANSI style & color support for your terminal applications. |
| <b>[uilive](https://github.com/gosuri/uilive) | 1.6k | Library for updating terminal output in realtime. |
| <b>[aurora](https://github.com/logrusorgru/aurora) | 1.4k | ANSI terminal colors that supports fmt.Printf/Sprintf. |
| <b>[gookit/color](https://github.com/gookit/color) | 1.4k | Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. |
| <b>[go-isatty](https://github.com/mattn/go-isatty) | 774 | isatty for golang. |
| <b>[go-colorable](https://github.com/mattn/go-colorable) | 730 | Colorable writer for windows. |
| <b>[uitable](https://github.com/gosuri/uitable) | 717 | Library to improve readability in terminal apps using tabular data. |
| <b>[gommon/color](https://github.com/labstack/gommon/tree/master/color) | 516 | Style terminal text. |
| <b>[simpletable](https://github.com/alexeyco/simpletable) | 499 | Simple tables in terminal with Go. |
| <b>[chalk](https://github.com/ttacon/chalk) | 442 | Intuitive package for prettifying terminal/console output. |
| <b>[box-cli-maker](https://github.com/Delta456/box-cli-maker) | 439 | Make Highly Customized Boxes for your CLI. |
| <b>[yacspin](https://github.com/theckman/yacspin) | 426 | Yet Another CLi Spinner package, for working with terminal spinners. |
| <b>[tabby](https://github.com/cheynewallace/tabby) | 344 | A tiny library for super simple Golang tables. |
| <b>[bubble-table](https://github.com/Evertras/bubble-table) | 287 | An interactive table component for bubbletea. |
| <b>[go-colortext](https://github.com/daviddengcn/go-colortext) | 214 | Go library for color output in terminals. |
| <b>[cfmt](https://github.com/mingrammer/cfmt) | 100 | Contextual fmt inspired by bootstrap color classes. |
| <b>[tabular](https://github.com/InVisionApp/tabular) | 76 | Print ASCII tables from command line utilities without the need to pass large sets of data to the API. |
| <b>[cfmt](https://github.com/i582/cfmt) | 62 | Simple and convenient formatted stylized output fully compatible with fmt library. |
| <b>[table](https://github.com/tomlazar/table) | 49 | Small library for terminal color based tables . |
| <b>[ctc](https://github.com/wzshiming/ctc) | 46 | The non-invasive cross-platform terminal color library does not need to modify the Print method. |
| <b>[marker](https://github.com/cyucelen/marker) | 45 | Easiest way to match and mark strings for colorful terminal outputs. |
| <b>[colourize](https://github.com/TreyBastian/colourize) | 26 | Go library for ANSI colour text in terminals. |
| <b>[go-ataman](https://github.com/workanator/go-ataman) | 16 | Go library for rendering ANSI colored text templates in terminals. |
| <b>[go-palette](https://github.com/abusomani/go-palette) | 14 | Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts. |
| <b>[crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) | 7 | Dynamic configuration file templating tool for kubernetes manifest or general configuration files. |


<br>

[👆back to top](#catalogue-list)


<br>

### Standard CLI

_Libraries for building standard or basic Command Line applications._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cobra](https://github.com/spf13/cobra) | 35.0k | Commander for modern Go CLI interactions. |
| <b>[urfave/cli](https://github.com/urfave/cli) | 21.0k | Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). |
| <b>[elvish](https://github.com/elves/elvish) | 5.2k | An expressive programming language and a versatile interactive shell. |
| <b>[survey](https://github.com/go-survey/survey) | 4.0k | Build interactive and accessible prompts with full support for windows and posix terminals. |
| <b>[kingpin](https://github.com/alecthomas/kingpin) | 3.4k | Command line and flag parser supporting sub commands (superseded by `kong`; see below). |
| <b>[Dnote](https://github.com/dnote/dnote) | 2.6k | A simple command line notebook with multi-device sync. |
| <b>[go-flags](https://github.com/jessevdk/go-flags) | 2.5k | go command line option parser. |
| <b>[pflag](https://github.com/spf13/pflag) | 2.3k | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. |
| <b>[go-arg](https://github.com/alexflint/go-arg) | 1.8k | Struct-based argument parsing in Go. |
| <b>[mitchellh/cli](https://github.com/mitchellh/cli) | 1.7k | Go library for implementing command-line interfaces. |
| <b>[ops](https://github.com/nanovms/ops) | 1.2k | Unikernel Builder/Orchestrator. |
| <b>[liner](https://github.com/peterh/liner) | 1000 | Go readline-like library for command-line interfaces. |
| <b>[complete](https://github.com/posener/complete) | 906 | Write bash completions in Go + Go command bash completion. |
| <b>[mow.cli](https://github.com/jawher/mow.cli) | 869 | Go library for building CLI applications with sophisticated flag and argument parsing and validation. |
| <b>[flaggy](https://github.com/integrii/flaggy) | 842 | A robust and idiomatic flags package with excellent subcommand support. |
| <b>[cli](https://github.com/mkideal/cli) | 713 | Feature-rich and easy to use command-line package based on golang struct tags. |
| <b>[argparse](https://github.com/akamensky/argparse) | 580 | Command line argument parser inspired by Python's argparse module. |
| <b>[carapace-bin](https://github.com/rsteube/carapace-bin) | 532 | Multi-shell multi-command argument completer. |
| <b>[climax](https://github.com/tucnak/climax) | 214 | Alternative CLI with "human face", in spirit of Go command. |
| <b>[wmenu](https://github.com/dixonwille/wmenu) | 208 | Easy to use menu structure for cli applications that prompts users to make choices. |
| <b>[hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) | 180 | cli application framework with auto configuration and dependency injection. |
| <b>[commandeer](https://github.com/jaffee/commandeer) | 172 | Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. |
| <b>[clîr](https://github.com/leaanthony/clir) | 163 | A Simple and Clear CLI library. Dependency free. |
| <b>[carapace](https://github.com/rsteube/carapace) | 156 | Command argument completion generator for spf13/cobra. |
| <b>[sflags](https://github.com/octago/sflags) | 148 | Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. |
| <b>[job](https://github.com/liujianping/job) | 137 | JOB, make your short-term command as a long-term job. |
| <b>[flag](https://github.com/cosiner/flag) | 129 | Simple but powerful command line option parsing library for Go supporting subcommand. |
| <b>[ukautz/clif](https://github.com/ukautz/clif) | 125 | Small command line interface framework. |
| <b>[cli](https://github.com/teris-io/cli) | 124 | Simple and complete API for building command line interfaces in Go. |
| <b>[cmdr](https://github.com/hedzr/cmdr) | 122 | A POSIX/GNU style, getopt-like command-line UI Go library. |
| <b>[env](https://github.com/codingconcepts/env) | 107 | Tag-based environment configuration for structs. |
| <b>[acmd](https://github.com/cristalhq/acmd) | 105 | Simple, useful and opinionated CLI package in Go. |
| <b>[version](https://github.com/mszostok/version) | 81 | Collects and displays CLI version information in multiple formats along with upgrade notice. |
| <b>[gocmd](https://github.com/devfacet/gocmd) | 67 | Go library for building command line applications. |
| <b>[wlog](https://github.com/dixonwille/wlog) | 65 | Simple logging interface that supports cross-platform color and concurrency. |
| <b>[readline](https://github.com/reeflective/readline) | 59 | Shell library with modern and easy to use UI features. |
| <b>[strumt](https://github.com/antham/strumt) | 57 | Library to create prompt chain. |
| <b>[command-chain](https://github.com/rainu/go-command-chain) | 53 | A go library for configure and run command chains - such like pipelining in unix shells. |
| <b>[go-getoptions](https://github.com/DavidGamba/go-getoptions) | 53 | Go option parser inspired on the flexibility of Perl’s GetOpt::Long. |
| <b>[flagvar](https://github.com/sgreben/flagvar) | 43 | A collection of flag argument types for Go's standard `flag` package. |
| <b>[cmd](https://github.com/posener/cmd) | 41 | Extends the standard `flag` package to support sub commands and more in idiomatic way. |
| <b>[argv](https://github.com/cosiner/argv) | 39 | Go library to split command line string as arguments array using the bash syntax. |
| <b>[go-commander](https://github.com/yitsushi/go-commander) | 35 | Go library to simplify CLI workflow. |
| <b>[go-andotp](https://github.com/grijul/go-andotp) | 25 | A CLI program to encrypt/decrypt [andOTP](https://github.com/andOTP/andOTP) files. Can be used as library as well. |
| <b>[mcli](https://github.com/jxskiss/mcli) | 24 | A minimal but very powerful cli library for Go. |
| <b>[sand](https://github.com/Zaba505/sand) | 24 | Simple API for creating interpreters and so much more. |
| <b>[ts](https://github.com/liujianping/ts) | 20 | Timestamp convert & compare tool. |
| <b>[carapace-spec](https://github.com/rsteube/carapace-spec) | 13 | Define simple completions using a spec file. |
| <b>[subcmd](https://github.com/bobg/subcmd) | 6 | Another approach to parsing and running subcommands. Works alongside the standard `flag` package. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Configuration

_Libraries for configuration parsing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[viper](https://github.com/spf13/viper) | 25.0k | Go configuration with fangs. |
| <b>[godotenv](https://github.com/joho/godotenv) | 7.2k | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| <b>[kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) | 4.8k | Go library for managing configuration data from environment variables. |
| <b>[env](https://github.com/caarlos0/env) | 4.2k | Parse environment variables to Go structs (with defaults). |
| <b>[ini](https://github.com/go-ini/ini) | 3.4k | Go package to read and write INI files. |
| <b>[koanf](https://github.com/knadh/koanf) | 2.2k | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| <b>[kong](https://github.com/alecthomas/kong) | 1.7k | Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (succesor to `kingpin`). |
| <b>[cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 1.3k | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| <b>[konfig](https://github.com/lalamove/konfig) | 644 | Composable, observable and performant config handling for Go for the distributed processing era. |
| <b>[xdg](https://github.com/adrg/xdg) | 527 | Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). |
| <b>[gookit/config](https://github.com/gookit/config) | 513 | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| <b>[aconfig](https://github.com/cristalhq/aconfig) | 507 | Simple, useful and opinionated config loader. |
| <b>[confita](https://github.com/heetch/confita) | 483 | Load configuration in cascade from multiple backends into a struct. |
| <b>[GoLobby/Config](https://github.com/golobby/config) | 352 | GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language. |
| <b>[config](https://github.com/JeremyLoy/config) | 334 | Cloud native application configuration. Bind ENV to structs in only two lines. |
| <b>[fig](https://github.com/kkyr/fig) | 318 | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| <b>[hjson](https://github.com/hjson/hjson-go) | 312 | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| <b>[store](https://github.com/tucnak/store) | 275 | Lightweight configuration manager for Go. |
| <b>[config](https://github.com/olebedev/config) | 268 | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| <b>[envconfig](https://github.com/vrischmann/envconfig) | 236 | Read your configuration from environment variables. |
| <b>[joshbetz/config](https://github.com/joshbetz/config) | 216 | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| <b>[gcfg](https://github.com/go-gcfg/gcfg) | 165 | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| <b>[harvester](https://github.com/beatlabs/harvester) | 129 | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| <b>[onion](https://github.com/goraz/onion) | 114 | Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP. |
| <b>[envcfg](https://github.com/tomazk/envcfg) | 102 | Un-marshaling environment variables to Go structs. |
| <b>[envh](https://github.com/antham/envh) | 98 | Helpers to manage environment variables. |
| <b>[configuro](https://github.com/sherifabdlnaby/configuro) | 91 | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| <b>[configuration](https://github.com/BoRuDar/configuration) | 88 | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| <b>[xdg](https://github.com/OpenPeeDeeP/xdg) | 80 | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| <b>[uConfig](https://github.com/omeid/uconfig) | 69 | Lightweight, zero-dependency, and extendable configuration management. |
| <b>[hocon](https://github.com/gurkankaymak/hocon) | 68 | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| <b>[gofigure](https://github.com/ian-kent/gofigure) | 67 | Go application configuration made easy. |
| <b>[configure](https://github.com/paked/configure) | 56 | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| <b>[go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 54 | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| <b>[gone/jconf](https://github.com/One-com/gone/tree/master/jconf) | 47 | Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization. |
| <b>[env](https://github.com/junk1tm/env) | 46 | A lightweight package for loading environment variables into structs. |
| <b>[config](https://github.com/num30/config) | 44 | configure you app using file, environment variables, or flags in two lines of code |
| <b>[go-up](https://github.com/ufoscout/go-up) | 43 | A simple configuration library with recursive placeholders resolution and no magic. |
| <b>[ingo](https://github.com/schachmat/ingo) | 36 | Flags persisted in an ini-like config file. |
| <b>[genv](https://github.com/sakirsensoy/genv) | 35 | Read environment variables easily with dotenv support. |
| <b>[mini](https://github.com/sasbury/mini) | 35 | Golang package for parsing ini-style configuration files. |
| <b>[conflate](https://github.com/the4thamigo-uk/conflate) | 31 | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| <b>[go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 18 | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| <b>[ini](https://github.com/wlevene/ini) | 15 | INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file. |
| <b>[envconf](https://github.com/ian-kent/envconf) | 11 | Configuration from environment. |
| <b>[go-conf](https://github.com/ThomasObenaus/go-conf) | 11 | Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters. |
| <b>[go-ini](https://github.com/subpop/go-ini) | 11 | A Go package that marshals and unmarshals INI-files. |
| <b>[nasermirzaei89/env](https://github.com/nasermirzaei89/env) | 10 | Simple useful package for read environment variables. |
| <b>[typenv](https://github.com/diegomarangoni/typenv) | 9 | Minimalistic, zero dependency, typed environment variables library. |
| <b>[swap](https://github.com/oblq/swap) | 8 | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| <b>[gonfig](https://github.com/milad-abbasi/gonfig) | 7 | Tag-based configuration parser which loads values from different providers into typesafe struct. |
| <b>[nfigure](https://github.com/muir/nfigure) | 7 | Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML |
| <b>[piper](https://github.com/Yiling-J/piper) | 7 | Viper wrapper with config inheritance and key generation. |
| <b>[goConfig](https://github.com/crgimenes/goConfig) | 3 | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Continuous Integration

_Tools for help with continuous integration._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[drone](https://github.com/drone/drone) | 31.0k | Drone is a Continuous Integration platform built on Docker, written in Go. |
| <b>[CDS](https://github.com/ovh/cds) | 4.4k | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| <b>[woodpecker](https://github.com/woodpecker-ci/woodpecker) | 3.4k | Woodpecker is a community fork of the Drone CI system. |
| <b>[goveralls](https://github.com/mattn/goveralls) | 772 | Go integration for Coveralls.io continuous code coverage tracking system. |
| <b>[gotestfmt](https://github.com/GoTestTools/gotestfmt) | 448 | go test output for humans. |
| <b>[gotestfmt](https://github.com/haveyoudebuggedit/gotestfmt) | 448 | go test output for humans. |
| <b>[overalls](https://github.com/go-playground/overalls) | 114 | Multi-Package go project coverprofile for tools like goveralls. |
| <b>[duci](https://github.com/duck8823/duci) | 74 | A simple ci server no needs domain specific languages. |
| <b>[gomason](https://github.com/nikogura/gomason) | 60 | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| <b>[go-test-coverage](https://github.com/vladopajic/go-test-coverage) | 36 | Tool and GitHub action which reports issues when test coverage is below set threshold. |
| <b>[roveralls](https://github.com/LawrenceWoodman/roveralls) | 19 | Recursive coverage testing tool. |
| <b>[go-fuzz-action](https://github.com/jidicula/go-fuzz-action) | 11 | Use Go 1.18's built-in fuzz testing in GitHub Actions. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## CSS Preprocessors

_Libraries for preprocessing CSS files._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gcss](https://github.com/yosssi/gcss) | 487 | Pure Go CSS Preprocessor. |
| <b>[go-libsass](https://github.com/wellington/go-libsass) | 201 | Go wrapper to the 100% Sass compatible libsass project. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Data Structures and Algorithms


<br>

### Bit-packing and Compression


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[roaring](https://github.com/RoaringBitmap/roaring) | 2.3k | Go package implementing compressed bitsets. |
| <b>[binpacker](https://github.com/zhuangsirui/binpacker) | 217 | Binary packer and unpacker helps user build custom binary stream. |
| <b>[bit](https://github.com/yourbasic/bit) | 154 | Golang set data structure with bonus bit-twiddling functions. |
| <b>[crunch](https://github.com/superwhiskers/crunch) | 91 | Go package implementing buffers for handling various datatypes easily. |
| <b>[go-ef](https://github.com/amallia/go-ef) | 31 | A Go implementation of the Elias-Fano encoding. |
| <b>[bingo](https://github.com/iancmcc/bingo) | 28 | Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes. |


<br>

[👆back to top](#catalogue-list)


<br>

### Bit Sets


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bitset](https://github.com/bits-and-blooms/bitset) | 1.2k | Go package implementing bitsets. |
| <b>[bitmap](https://github.com/kelindar/bitmap) | 259 | Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Bloom and Cuckoo Filters


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bloom](https://github.com/bits-and-blooms/bloom) | 2.2k | Go package implementing Bloom filters. |
| <b>[boomfilters](https://github.com/tylertreat/BoomFilters) | 1.6k | Probabilistic data structures for processing continuous, unbounded streams. |
| <b>[cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 1000 | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| <b>[cuckoo-filter](https://github.com/linvon/cuckoo-filter) | 276 | Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available. |
| <b>[bloom](https://github.com/zhenjl/bloom) | 147 | Bloom filters implemented in Go. |
| <b>[ring](https://github.com/TheTannerRyan/ring) | 135 | Go implementation of a high performance, thread safe bloom filter. |
| <b>[bloom](https://github.com/yourbasic/bloom) | 83 | Golang Bloom filter implementation. |
| <b>[bloomfilter](https://github.com/OldPanda/bloomfilter) | 16 | Yet another Bloomfilter implementation in Go, compatible with Java's Guava library. |


<br>

[👆back to top](#catalogue-list)


<br>

### Data Structure and Algorithm Collections


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gods](https://github.com/emirpasic/gods) | 15.0k | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| <b>[go-datastructures](https://github.com/Workiva/go-datastructures) | 7.3k | Collection of useful, performant, and thread-safe data structures. |
| <b>[gostl](https://github.com/liyue201/gostl) | 970 | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| <b>[algorithms](https://github.com/shady831213/algorithms) | 755 | Algorithms and data structures.CLRS study. |


<br>

[👆back to top](#catalogue-list)


<br>

### Iterators


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[iter](https://github.com/disksing/iter) | 186 | Go implementation of C++ STL iterators and algorithms. |
| <b>[goterator](https://github.com/yaa110/goterator) | 17 | Iterator implementation to provide map and reduce functionalities. |


<br>

[👆back to top](#catalogue-list)


<br>

### Maps


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cmap](https://github.com/lrita/cmap) | 82 | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| <b>[dict](https://github.com/srfrog/dict) | 43 | Python-like dictionaries (dict) for Go. |
| <b>[goradd/maps](https://github.com/goradd/maps) | 31 | Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc. |


<br>

[👆back to top](#catalogue-list)


<br>

### Miscellaneous Data Structures and Algorithms


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gota](https://github.com/kniren/gota) | 2.8k | Implementation of dataframes, series, and data wrangling methods for Go. |
| <b>[hyperloglog](https://github.com/axiomhq/hyperloglog) | 896 | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| <b>[go-geoindex](https://github.com/hailocab/go-geoindex) | 354 | In-memory geo index. |
| <b>[hilbert](https://github.com/google/hilbert) | 275 | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| <b>[plinko](https://github.com/shipt/plinko) | 165 | A finite state machine and workflow orchestrator that compiles for fast execution, easy debugging, auto-generated documentation. Includes advanced features such as side-effect hooks. |
| <b>[go-rquad](https://github.com/aurelien-rainone/go-rquad) | 129 | Region quadtrees with efficient point location and neighbour finding. |
| <b>[conjungo](https://github.com/InVisionApp/conjungo) | 122 | A small, powerful and flexible merge library. |
| <b>[go-rampart](https://github.com/francesconi/go-rampart) | 94 | Determine how intervals relate to each other. |
| <b>[gogu](https://github.com/esimov/gogu) | 90 | A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library. |
| <b>[go-tuple](https://github.com/barweiss/go-tuple) | 72 | Generic tuple implementation for Go 1.18+. |
| <b>[count-min-log](https://github.com/seiflotfy/count-min-log) | 66 | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| <b>[hide](https://github.com/emvi/hide) | 59 | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| <b>[fsm](https://github.com/cocoonspace/fsm) | 56 | Finite-State Machine package. |
| <b>[concurrent-writer](https://github.com/free/concurrent-writer) | 54 | Highly concurrent drop-in replacement for `bufio.Writer`. |
| <b>[genfuncs](https://github.com/nwillc/genfuncs) | 46 | Go 1.18+ generics package inspired by Kotlin's Sequence and Map. |
| <b>[go-generics](https://github.com/bobg/go-generics) | 46 | Generic slice, map, set, iterator, and goroutine utilities. |
| <b>[go18ds](https://github.com/daichi-m/go18ds) | 41 | Go Data Structures using Go 1.18 generics. |
| <b>[quadtree](https://github.com/s0rg/quadtree) | 31 | Generic, zero-alloc, 100%-test covered quadtree. |
| <b>[gofal](https://github.com/xxjwxc/gofal) | 18 | fractional api for Go. |
| <b>[slices](https://github.com/srfrog/slices) | 16 | Functions that operate on slices; like `package strings` but adapted to work with slices. |
| <b>[slices](https://github.com/twharmon/slices) | 15 | Pure, generic functions for slices. |


<br>

[👆back to top](#catalogue-list)


<br>

### Nullable Types


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[nan](https://github.com/kak-tus/nan) | 81 | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| <b>[typ](https://github.com/gurukami/typ) | 44 | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| <b>[null](https://github.com/emvi/null) | 32 | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |


<br>

[👆back to top](#catalogue-list)


<br>

### Queues


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[deque](https://github.com/gammazero/deque) | 521 | Fast ring-buffer deque (double-ended queue). |
| <b>[goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 340 | Concurrent FIFO queue. |
| <b>[queue](https://github.com/adrianbrad/queue) | 233 | Multiple thread-safe, generic queue implementations for Go. |
| <b>[deque](https://github.com/edwingeng/deque) | 169 | A highly optimized double-ended queue. |
| <b>[memlog](https://github.com/embano1/memlog) | 110 | An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka. |


<br>

[👆back to top](#catalogue-list)


<br>

### Sets


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golang-set](https://github.com/deckarep/golang-set) | 3.8k | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| <b>[goset](https://github.com/zoumo/goset) | 52 | A useful Set collection implementation for Go. |
| <b>[set](https://github.com/StudioSol/set) | 26 | Simple set data structure implementation in Go using LinkedHashMap. |
| <b>[dsu](https://github.com/ihebu/dsu) | 13 | Disjoint Set data structure implementation in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Text Analysis


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bleve](https://github.com/blevesearch/bleve) | 9.5k | Modern text indexing library for go. |
| <b>[trie](https://github.com/derekparker/trie) | 721 | Trie implementation in Go. |
| <b>[go-edlib](https://github.com/hbollon/go-edlib) | 437 | Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. |
| <b>[go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 327 | Go implementation of Adaptive Radix Tree. |
| <b>[levenshtein](https://github.com/agnivade/levenshtein) | 319 | Implementation to calculate levenshtein distance in Go. |
| <b>[levenshtein](https://github.com/agext/levenshtein) | 82 | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| <b>[ptrie](https://github.com/viant/ptrie) | 37 | An implementation of prefix tree. |
| <b>[mspm](https://github.com/BlackRabbitt/mspm) | 24 | Multi-String Pattern Matching Algorithm for information retrieval. |
| <b>[parsefields](https://github.com/MonaxGT/parsefields) | 8 | Tools for parse JSON-like logs for collecting unique fields and events. |


<br>

[👆back to top](#catalogue-list)


<br>

### Trees


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[skiplist](https://github.com/MauriceGit/skiplist) | 266 | Very fast Go Skiplist implementation. |
| <b>[skiplist](https://github.com/gansidui/skiplist) | 83 | Skiplist implementation in Go. |
| <b>[treemap](https://github.com/igrmk/treemap) | 53 | Generic key-sorted map using a red-black tree under the hood. |
| <b>[treap](https://github.com/perdata/treap) | 24 | Persistent, fast ordered map using tree heaps. |
| <b>[merkle](https://github.com/bobg/merkle) | 13 | Space-efficient computation of Merkle root hashes and inclusion proofs. |
| <b>[hashsplit](http://github.com/bobg/hashsplit) | 8 | Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position. |


<br>

[👆back to top](#catalogue-list)


<br>

### Pipes


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[pipeline](https://github.com/hyfather/pipeline) | 52 | An implementation of pipelines with fan-in and fan-out. |
| <b>[ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) | 29 | Go module that processes work concurrently and returns output in a channel in the order of input. |
| <b>[parapipe](https://github.com/nazar256/parapipe) | 25 | FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Database


<br>

### Caches

_Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[groupcache](https://github.com/golang/groupcache) | 13.0k | Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. |
| <b>[BigCache](https://github.com/allegro/bigcache) | 7.0k | Efficient key/value cache for gigabytes of data. |
| <b>[GCache](https://github.com/bluele/gcache) | 2.5k | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| <b>[gocache](https://github.com/eko/gocache) | 2.1k | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| <b>[cache2go](https://github.com/muesli/cache2go) | 2.0k | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| <b>[fastcache](https://github.com/VictoriaMetrics/fastcache) | 1.9k | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| <b>[otter](https://github.com/maypok86/otter) | 971 | A high performance lockless cache for Go. Many times faster than Ristretto and friends. |
| <b>[ttlcache](https://github.com/jellydator/ttlcache) | 801 | An in-memory cache with item expiration and generics. |
| <b>[cachego](https://github.com/fabiorphp/cachego) | 342 | Golang Cache component for multiple drivers. |
| <b>[cachego](https://github.com/faabiosr/cachego) | 342 | Golang Cache component for multiple drivers. |
| <b>[theine](https://github.com/Yiling-J/theine-go) | 200 | High performance, near optimal in-memory cache with proactive TTL expiration and generics. |
| <b>[cache](https://github.com/akyoto/cache) | 167 | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| <b>[bcache](https://github.com/iwanbk/bcache) | 144 | Eventually consistent distributed in-memory  cache Go library. |
| <b>[remember-go](https://github.com/rocketlaunchr/remember-go) | 137 | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| <b>[go-cache](https://github.com/viney-shih/go-cache) | 119 | A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern. |
| <b>[imcache](https://github.com/erni27/imcache) | 106 | A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding. |
| <b>[go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 91 | Fast in-memory key:value store/cache library. Pointer caches. |
| <b>[go-freelru](https://github.com/elastic/go-freelru) | 73 | A GC-less, fast and generic LRU hashmap library with optional locking, sharding, eviction and expiration. |
| <b>[timedmap](https://github.com/zekroTJA/timedmap) | 69 | Map with expiring key-value pairs. |
| <b>[couchcache](https://github.com/codingsince1985/couchcache) | 60 | RESTful caching micro-service backed by Couchbase server. |
| <b>[clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 44 | BigCache with clustering support and individual item expiration. |
| <b>[2q](https://github.com/floatdrop/2q) | 33 | 2Q in-memory cache implementation. |
| <b>[gdcache](https://github.com/ulovecode/gdcache) | 12 | A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache. |
| <b>[ttlcache](https://github.com/cheshir/ttlcache) | 9 | In-memory key value storage with TTL for each record. |
| <b>[nscache](https://github.com/no-src/nscache) | 7 | A Go caching framework that supports multiple data source drivers. |
| <b>[coherence-go-client](https://github.com/oracle/coherence-go-client) | 7 | Full implementation of Oracle Coherence cache API for Go applications using gRPC as network transport. |
| <b>[gocache](https://github.com/yuseferi/gocache) | 5 | A data race free Go ache library with high performance and auto pruge functionality |


<br>

[👆back to top](#catalogue-list)


<br>

### Databases Implemented in Go


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[prometheus](https://github.com/prometheus/prometheus) | 52.0k | Monitoring system and time series database. |
| <b>[tidb](https://github.com/pingcap/tidb) | 36.0k | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| <b>[cockroach](https://github.com/cockroachdb/cockroach) | 29.0k | Scalable, Geo-Replicated, Transactional Datastore. |
| <b>[influxdb](https://github.com/influxdb/influxdb) | 27.0k | Scalable datastore for metrics, events, and real-time analytics. |
| <b>[Milvus](https://github.com/milvus-io/milvus) | 25.0k | Milvus is a vector database for embedding management, analytics and search. |
| <b>[dgraph](https://github.com/dgraph-io/dgraph) | 20.0k | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| <b>[dolt](https://github.com/dolthub/dolt) | 16.0k | Dolt – It's Git for Data. |
| <b>[rqlite](https://github.com/rqlite/rqlite) | 15.0k | The lightweight, distributed, relational database built on SQLite. |
| <b>[badger](https://github.com/dgraph-io/badger) | 13.0k | Fast key-value store in Go. |
| <b>[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 10.0k | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| <b>[immudb](https://github.com/codenotary/immudb) | 8.4k | immudb is a lightweight, high-speed immutable database for systems and applications written in Go. |
| <b>[bbolt](https://github.com/etcd-io/bbolt) | 7.3k | An embedded key/value database for Go. |
| <b>[goleveldb](https://github.com/syndtr/goleveldb) | 5.9k | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| <b>[buntdb](https://github.com/tidwall/buntdb) | 4.3k | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| <b>[rosedb](https://github.com/roseduan/rosedb) | 4.2k | An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset. |
| <b>[ledisdb](https://github.com/siddontang/ledisdb) | 4.0k | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| <b>[godis](https://github.com/hdt3213/godis) | 3.2k | A Golang implemented high-performance Redis server and cluster. |
| <b>[nutsdb](https://github.com/xujiajun/nutsdb) | 3.2k | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| <b>[LinDB](https://github.com/lindb/lindb) | 2.8k | LinDB is a scalable, high performance, high availability distributed time series database. |
| <b>[tiedot](https://github.com/HouzuoGuo/tiedot) | 2.7k | Your NoSQL database powered by Golang. |
| <b>[lotusdb](https://github.com/flower-corp/lotusdb) | 1.9k | Fast k/v database compatible with lsm and b+tree. |
| <b>[CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1.5k | CovenantSQL is a SQL database on blockchain. |
| <b>[column](https://github.com/kelindar/column) | 1.3k | High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions. |
| <b>[diskv](https://github.com/peterbourgon/diskv) | 1.3k | Home-grown disk-backed key-value store. |
| <b>[Databunker](https://github.com/paranoidguy/databunker) | 1.2k | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| <b>[pogreb](https://github.com/akrylysov/pogreb) | 1.2k | Embedded key-value store for read-heavy workloads. |
| <b>[eliasdb](https://github.com/krotik/eliasdb) | 984 | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| <b>[moss](https://github.com/couchbase/moss) | 940 | Moss is a simple LSM key-value storage engine written in 100% Go. |
| <b>[objectbox-go](https://github.com/objectbox/objectbox-go) | 939 | High-performance embedded Object Database (NoSQL) with Go API. |
| <b>[clover](https://github.com/ostafen/clover) | 541 | A lightweight document-oriented NoSQL database written in pure Golang. |
| <b>[levigo](https://github.com/jmhodges/levigo) | 418 | Levigo is a Go wrapper for LevelDB. |
| <b>[pudge](https://github.com/recoilme/pudge) | 355 | Fast and simple key/value store written using Go's standard library. |
| <b>[Vasto](https://github.com/chrislusf/vasto) | 254 | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| <b>[dtf](https://github.com/dtm-labs/dtf) | 215 | A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages. |
| <b>[piladb](https://github.com/fern4lvarez/piladb) | 202 | Lightweight RESTful database engine based on stack data structures. |
| <b>[libradb](https://github.com/amit-davidson/LibraDB) | 135 | LibraDB is a simple database with less then 1000 lines of code for learning. |
| <b>[unitdb](https://github.com/unit-io/unitdb) | 115 | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| <b>[hare](https://github.com/jameycribbs/hare) | 85 | A simple database management system that stores each table as a text file of line-delimited JSON. |
| <b>[regatta](https://github.com/jamf/regatta) | 59 | Fast, simple, geo-distributed KV store built for cloud native era. |
| <b>[Coffer](https://github.com/claygod/coffer) | 36 | Simple ACID key-value database that supports transactions. |
| <b>[tempdb](https://github.com/rafaeljesus/tempdb) | 17 | Key-value store for temporary items. |
| <b>[Bitcask](https://git.mills.io/prologic/bitcask) | - | Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). |


<br>

[👆back to top](#catalogue-list)


<br>

### Database Schema Migration


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[migrate](https://github.com/golang-migrate/migrate) | 13.0k | Database migrations. CLI and Golang library. |
| <b>[bytebase](https://github.com/bytebase/bytebase) | 9.3k | Safe database schema change and version control for DevOps teams. |
| <b>[goose](https://github.com/pressly/goose) | 5.0k | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| <b>[atlas](https://github.com/ariga/atlas) | 4.5k | A Database Toolkit. A CLI designed to help companies better work with their data. |
| <b>[dbmate](https://github.com/amacneil/dbmate) | 4.1k | A lightweight, framework-agnostic database migration tool. |
| <b>[sql-migrate](https://github.com/rubenv/sql-migrate) | 3.0k | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| <b>[soda](https://github.com/gobuffalo/pop/tree/master/soda) | 1.4k | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| <b>[skeema](https://github.com/skeema/skeema) | 1.2k | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| <b>[gormigrate](https://github.com/go-gormigrate/gormigrate) | 960 | Database schema migration helper for Gorm ORM. |
| <b>[goavro](https://github.com/linkedin/goavro) | 935 | A Go package that encodes and decodes Avro data. |
| <b>[migrator](https://github.com/lopezator/migrator) | 158 | Dead simple Go database migration library. |
| <b>[darwin](https://github.com/GuiaBolso/darwin) | 141 | Database schema evolution library for Go. |
| <b>[go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 84 | A Go package to help write migrations with go-pg/pg. |
| <b>[sqlize](https://github.com/sunary/sqlize) | 75 | Database migration generator. Allows generate sql migration from model and existing sql by differ them. |
| <b>[avro](https://github.com/khezen/avro) | 45 | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| <b>[schema](https://github.com/adlio/schema) | 30 | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| <b>[go-fixtures](https://github.com/RichardKnop/go-fixtures) | 28 | Django style fixtures for Golang's excellent built-in database/sql library. |
| <b>[pravasan](https://github.com/pravasan/pravasan) | 28 | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| <b>[migrator](https://github.com/larapulse/migrator) | 24 | MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code. |
| <b>[libschema](https://github.com/muir/libschema) | 14 | Define your migrations separately in each libary.  Migrations for open source libraries.  MySQL & PostgreSQL. |
| <b>[gorm-seeder](https://github.com/Kachit/gorm-seeder) | 13 | Simple database seeder for Gorm ORM. |
| <b>[go-pg-migrate](https://github.com/lawzava/go-pg-migrate) | 10 | CLI-friendly package for go-pg migrations management. |
| <b>[godfish](https://github.com/rafaelespinoza/godfish) | 6 | Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3. |


<br>

[👆back to top](#catalogue-list)


<br>

### Database Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[vitess](https://github.com/youtube/vitess) | 17.0k | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| <b>[pgweb](https://github.com/sosedoff/pgweb) | 8.2k | Web-based PostgreSQL database browser. |
| <b>[kingshard](https://github.com/flike/kingshard) | 6.3k | kingshard is a high performance proxy for MySQL powered by Golang. |
| <b>[orchestrator](https://github.com/github/orchestrator) | 5.4k | MySQL replication topology manager & visualizer. |
| <b>[go-mysql](https://github.com/siddontang/go-mysql) | 4.3k | Go toolset to handle MySQL protocol and replication. |
| <b>[go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) | 4.0k | Sync your MySQL data into Elasticsearch automatically. |
| <b>[pREST](https://github.com/prest/prest) | 4.0k | Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. |
| <b>[chproxy](https://github.com/Vertamedia/chproxy) | 1.2k | HTTP proxy for ClickHouse database. |
| <b>[pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | 989 | Advanced scheduling for PostgreSQL. |
| <b>[clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 452 | Collects small inserts and sends big requests to ClickHouse servers. |
| <b>[rdb](https://github.com/HDT3213/rdb) | 327 | Redis RDB file parser for secondary development and memory analysis. |
| <b>[myreplication](https://github.com/2tvenom/myreplication) | 191 | MySql binary log replication listener. Supports statement and row based replication. |
| <b>[octillery](https://github.com/knocknote/octillery) | 185 | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| <b>[dbbench](https://github.com/sj14/dbbench) | 96 | Database benchmarking tool with support for several databases and scripts. |
| <b>[datagen](https://github.com/codingconcepts/datagen) | 56 | A fast data generator that's multi-table aware and supports multi-row DML. |
| <b>[onedump](https://github.com/liweiyi88/onedump) | 38 | Database backup from different drivers to different destinations with one command and configuration. |
| <b>[prep](https://github.com/hexdigest/prep) | 33 | Use prepared SQL statements without changing your code. |
| <b>[rwdb](https://github.com/andizzle/rwdb) | 18 | rwdb provides read replica capability for multiple database servers setup. |
| <b>[dg](https://github.com/codingconcepts/dg) | 18 | A fast data generator that produces CSV files from generated relational data. |
| <b>[dynago](https://github.com/twharmon/dynago) | 10 | Simplify working with AWS DynamoDB. |


<br>

[👆back to top](#catalogue-list)


<br>

### SQL Query Builders

_Libraries for building and using SQL._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sqlc](https://github.com/kyleconroy/sqlc) | 9.9k | Generate type-safe code from SQL. |
| <b>[Squirrel](https://github.com/Masterminds/squirrel) | 6.3k | Go library that helps you build SQL queries. |
| <b>[xo](https://github.com/knq/xo) | 3.5k | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| <b>[goqu](https://github.com/doug-martin/goqu) | 2.1k | Idiomatic SQL builder and query library. |
| <b>[jet](https://github.com/go-jet/jet) | 1.8k | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| <b>[gendry](https://github.com/didi/gendry) | 1.6k | Non-invasive SQL builder and powerful data binder. |
| <b>[Dotsql](https://github.com/gchaincl/dotsql) | 704 | Go library that helps you keep sql files in one place and use them with ease. |
| <b>[ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 614 | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| <b>[dbq](https://github.com/rocketlaunchr/dbq) | 390 | Zero boilerplate database operations for Go. |
| <b>[sqlingo](https://github.com/lqs/sqlingo) | 357 | A lightweight DSL to build SQL in Go. |
| <b>[sqrl](https://github.com/elgris/sqrl) | 266 | SQL query builder, fork of Squirrel with improved performance. |
| <b>[sq](https://github.com/bokwoon95/go-structured-query) | 195 | Type-safe SQL builder and struct mapper for Go. |
| <b>[buildsqlx](https://github.com/arthurkushman/buildsqlx) | 139 | Go database query builder library for PostgreSQL. |
| <b>[sqlf](https://github.com/leporo/sqlf) | 137 | Fast SQL query builder. |
| <b>[bqb](https://github.com/nullism/bqb) | 118 | Lightweight and easy to learn query builder. |
| <b>[igor](https://github.com/galeone/igor) | 115 | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| <b>[builq](https://github.com/cristalhq/builq) | 76 | Easily build SQL queries in Go. |
| <b>[godbal](https://github.com/xujiajun/godbal) | 59 | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| <b>[qry](https://github.com/HnH/qry) | 31 | Tool that generates constants from files with raw SQL queries. |
| <b>[gosql](https://github.com/twharmon/gosql) | 29 | SQL Query builder with better null values support. |
| <b>[mpath](https://github.com/spacetab-io/mpath-go) | 13 | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| <b>[ormlite](https://github.com/pupizoid/ormlite) | 12 | Lightweight package containing some ORM-like features and helpers for sqlite databases. |
| <b>[Hotcoal](https://github.com/motrboat/hotcoal) | 12 | Secure your handcrafted SQL against injection. |
| <b>[sg](https://github.com/go-the-way/sg) | 4 | A SQL Gen for generating standard SQLs(supports: CRUD) written in Go. |
| <b>[hasql](https://golang.yandex/hasql) | - | Library for accessing multi-host SQL database installations. |
| <b>[Squalus](https://gitlab.com/qosenergy/squalus) | - | Thin layer over the Go SQL package that makes it easier to perform queries. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Database Drivers


<br>

### Interfaces to Multiple Backends


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cayley](https://github.com/google/cayley) | 15.0k | Graph database with support for multiple backends. |
| <b>[gokv](https://github.com/philippgille/gokv) | 628 | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| <b>[go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) | 123 | Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries. |
| <b>[dsc](https://github.com/viant/dsc) | 28 | Datastore connectivity for SQL, NoSQL, structured files. |


<br>

[👆back to top](#catalogue-list)


<br>

### Relational Database Drivers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) | 14.0k | MySQL driver for Go. |
| <b>[pgx](https://github.com/jackc/pgx) | 8.9k | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| <b>[pq](https://github.com/lib/pq) | 8.6k | Pure Go Postgres driver for database/sql. |
| <b>[go-sqlite3](https://github.com/mattn/go-sqlite3) | 7.2k | SQLite3 driver for go that uses database/sql. |
| <b>[go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1.8k | Microsoft MSSQL driver for Go. |
| <b>[sqlhooks](https://github.com/qustavo/sqlhooks) | 624 | Attach hooks to any database/sql driver. |
| <b>[go-oci8](https://github.com/mattn/go-oci8) | 622 | Oracle driver for go that uses database/sql. |
| <b>[godror](https://github.com/godror/godror) | 484 | Oracle driver for Go, using the ODPI-C driver. |
| <b>[Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) | 386 | SQLite with pure Go. |
| <b>[Kivik](https://github.com/go-kivik/kivik) | 291 | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| <b>[KSQL](https://github.com/VinGarcia/ksql) | 258 | A Simple and Powerful Golang SQL Library |
| <b>[firebirdsql](https://github.com/nakagami/firebirdsql) | 212 | Firebird RDBMS SQL driver for Go. |
| <b>[surrealdb.go](https://github.com/surrealdb/surrealdb.go) | 199 | SurrealDB Driver for Go. |
| <b>[go-adodb](https://github.com/mattn/go-adodb) | 135 | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| <b>[ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) | 117 | native and database/sql driver YDB (Yandex Database) |
| <b>[avatica](https://github.com/apache/calcite-avatica-go) | 113 | Apache Avatica/Phoenix SQL driver for database/sql. |
| <b>[gofreetds](https://github.com/minus5/gofreetds) | 110 | Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org). |
| <b>[bgc](https://github.com/viant/bgc) | 21 | Datastore Connectivity for BigQuery for go. |
| <b>[pig](https://github.com/alexeyco/pig) | 15 | Simple [pgx](https://github.com/jackc/pgx) wrapper to execute and [scan](https://github.com/georgysavva/scany) query results easily. |


<br>

[👆back to top](#catalogue-list)


<br>

### NoSQL Database Drivers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[redis](https://github.com/redis/go-redis) | 19.0k | Redis client for Golang. |
| <b>[redis](https://github.com/go-redis/redis) | 19.0k | Redis client for Golang. |
| <b>[redigo](https://github.com/gomodule/redigo) | 9.7k | Redigo is a Go client for the Redis database. |
| <b>[mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 7.8k | Official MongoDB driver for the Go language. |
| <b>[mgo](https://github.com/globalsign/mgo) | 2.0k | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| <b>[gomemcache](https://github.com/bradfitz/gomemcache/) | 1.7k | memcache client library for the Go programming language. |
| <b>[gorethink](https://github.com/dancannon/gorethink) | 1.6k | Go language driver for RethinkDB. |
| <b>[qmgo](https://github.com/qiniu/qmgo) | 1.2k | The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| <b>[mgm](https://github.com/kamva/mgm) | 717 | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| <b>[redeo](https://github.com/bsm/redeo) | 430 | Redis-protocol compatible TCP servers/services. |
| <b>[aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 416 | Aerospike client in Go language. |
| <b>[neoism](https://github.com/jmcvetta/neoism) | 390 | Neo4j client for Golang. |
| <b>[rueidis](http://github.com/rueian/rueidis) | 368 | Fast Redis RESP3 client with auto pipelining and server-assisted client side caching. |
| <b>[gocb](https://github.com/couchbase/gocb) | 356 | Official Couchbase Go SDK. |
| <b>[go-rejson](https://github.com/nitishm/go-rejson) | 333 | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| <b>[go-couchbase](https://github.com/couchbase/go-couchbase) | 321 | Couchbase client in Go. |
| <b>[godis](https://github.com/piaohao/godis) | 109 | redis client implement by golang, inspired by jedis. |
| <b>[Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 77 | Neo4j REST Client in golang. |
| <b>[arangolite](https://github.com/solher/arangolite) | 73 | Lightweight golang driver for ArangoDB. |
| <b>[go-pilosa](https://github.com/pilosa/go-pilosa) | 58 | Go client library for Pilosa. |
| <b>[forestdb](https://github.com/couchbase/goforestdb) | 35 | Go bindings for ForestDB. |
| <b>[goriak](https://github.com/zegl/goriak) | 30 | Go language driver for Riak KV. |
| <b>[neo4j](https://github.com/cihangir/neo4j) | 27 | Neo4j Rest API Bindings for Golang. |
| <b>[xredis](https://github.com/shomali11/xredis) | 19 | Typesafe, customizable, clean & easy to use Redis client. |
| <b>[gocosmos](https://github.com/btnguyen2k/gocosmos) | 19 | REST client and standard `database/sql` driver for Azure Cosmos DB. |
| <b>[godscache](https://github.com/defcronyke/godscache) | 11 | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| <b>[asc](https://github.com/viant/asc) | 9 | Datastore Connectivity for Aerospike for go. |
| <b>[gocql](https://gocql.github.io) | - | Go language driver for Apache Cassandra. |


<br>

[👆back to top](#catalogue-list)


<br>

### Search and Analytic Databases


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[elastic](https://github.com/olivere/elastic) | 7.3k | Elasticsearch client for Go. |
| <b>[go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 5.4k | Official Elasticsearch client for Go. |
| <b>[clickhouse-go](https://github.com/ClickHouse/clickhouse-go/) | 2.7k | ClickHouse SQL client for Go with a `database/sql` compatibility. |
| <b>[elasticsql](https://github.com/cch123/elasticsql) | 1.1k | Convert sql to elasticsearch dsl in Go. |
| <b>[elastigo](https://github.com/mattbaird/elastigo) | 948 | Elasticsearch client library. |
| <b>[skizze](https://github.com/seiflotfy/skizze) | 88 | probabilistic data-structures service and storage. |
| <b>[goes](https://github.com/OwnLocal/goes) | 30 | Library to interact with Elasticsearch. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Date and Time

_Libraries for working with dates and times._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[carbon](https://github.com/golang-module/carbon) | 4.3k | A simple, semantic and developer-friendly golang package for datetime. |
| <b>[now](https://github.com/jinzhu/now) | 4.3k | Now is a time toolkit for golang. |
| <b>[dateparse](https://github.com/araddon/dateparse) | 2.0k | Parse date's without knowing format in advance. |
| <b>[carbon](https://github.com/uniplaces/carbon) | 767 | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| <b>[durafmt](https://github.com/hako/durafmt) | 481 | Time duration formatting library for Go. |
| <b>[gostradamus](https://github.com/bykof/gostradamus) | 193 | A Go package for working with dates. |
| <b>[timeutil](https://github.com/leekchan/timeutil) | 193 | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| <b>[go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 183 | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| <b>[iso8601](https://github.com/relvacode/iso8601) | 133 | Efficiently parse ISO8601 date-times without regex. |
| <b>[date](https://github.com/rickb777/date) | 120 | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| <b>[go-str2duration](https://github.com/xhit/go-str2duration) | 87 | Convert string to duration. Support time.Duration returned string and more. |
| <b>[timespan](https://github.com/SaidinWoT/timespan) | 83 | For interacting with intervals of time, defined as a start time and a duration. |
| <b>[go-sunrise](https://github.com/nathan-osman/go-sunrise) | 79 | Calculate the sunrise and sunset times for a given location. |
| <b>[feiertage](https://github.com/wlbr/feiertage) | 45 | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| <b>[kair](https://github.com/GuilhermeCaruso/kair) | 25 | Date and Time - Golang Formatting Library. |
| <b>[cronrange](https://github.com/1set/cronrange) | 18 | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| <b>[NullTime](https://github.com/kirillDanshin/nulltime) | 14 | Nullable `time.Time`. |
| <b>[go-anytime](https://github.com/ijt/go-anytime) | 13 | Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance. |
| <b>[strftime](https://github.com/awoodbeck/strftime) | 12 | C99-compatible strftime formatter. |
| <b>[tuesday](https://github.com/osteele/tuesday) | 12 | Ruby-compatible Strftime function. |
| <b>[go-week](https://github.com/stoewer/go-week) | 9 | An efficient package to work with ISO8601 week dates. |
| <b>[approx](https://github.com/goschtalt/approx) | 6 | A Duration extension supporting parsing/printing durations in days, weeks and years. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Distributed Systems

_Packages that help with building Distributed Systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[raft](https://github.com/coreos/etcd/tree/master/raft) | 46.0k | Go implementation of the Raft consensus protocol, by CoreOS. |
| <b>[go-zero](https://github.com/tal-tech/go-zero) | 27.0k | A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity. |
| <b>[go-kit](https://github.com/go-kit/kit) | 26.0k | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| <b>[Kratos](https://github.com/go-kratos/kratos) | 22.0k | A modular-designed and easy-to-use microservices framework in Go. |
| <b>[go-micro](https://github.com/micro/go-micro) | 21.0k | A distributed systems development framework. |
| <b>[grpc-go](https://github.com/grpc/grpc-go) | 19.0k | The Go language implementation of gRPC. HTTP/2 based RPC. |
| <b>[NATS](https://github.com/nats-io/gnatsd) | 14.0k | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| <b>[micro](https://github.com/micro/micro) | 12.0k | A distributed systems runtime for the cloud and beyond. |
| <b>[rpcx](https://github.com/smallnest/rpcx) | 7.9k | Distributed pluggable RPC service framework like alibaba Dubbo. |
| <b>[raft](https://github.com/hashicorp/raft) | 7.7k | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| <b>[Kitex](https://github.com/cloudwego/kitex) | 6.5k | A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice. |
| <b>[lura](https://github.com/luraproject/lura) | 6.0k | Ultra performant API Gateway framework with middlewares. |
| <b>[torrent](https://github.com/anacrolix/torrent) | 5.1k | BitTorrent client package. |
| <b>[dragonboat](https://github.com/lni/dragonboat) | 4.8k | A feature complete and high performance multi-group Raft library in Go. |
| <b>[emitter-io](https://github.com/emitter-io/emitter) | 3.7k | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| <b>[gleam](https://github.com/chrislusf/gleam) | 3.3k | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| <b>[glow](https://github.com/chrislusf/glow) | 3.2k | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| <b>[liftbridge](https://github.com/liftbridge-io/liftbridge) | 2.5k | Lightweight, fault-tolerant message streams for NATS. |
| <b>[Dragonfly](https://github.com/dragonflyoss/Dragonfly2) | 1.8k | Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures. |
| <b>[go-doudou](https://github.com/unionj-cloud/go-doudou) | 1.3k | A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity. |
| <b>[hprose](https://github.com/hprose/hprose-golang) | 1.2k | Very newbility RPC Library, support 25+ languages now. |
| <b>[redis-lock](https://github.com/bsm/redislock) | 1.2k | Simplified distributed locking implementation using Redis. |
| <b>[rain](https://github.com/cenkalti/rain) | 906 | BitTorrent client and library. |
| <b>[arpc](https://github.com/lesismal/arpc) | 850 | More effective network communication, support two-way-calling, notify, broadcast. |
| <b>[ringpop-go](https://github.com/uber/ringpop-go) | 810 | Scalable, fault-tolerant application-layer sharding for Go applications. |
| <b>[go-health](https://github.com/InVisionApp/go-health) | 730 | Library for enabling asynchronous dependency health checks in your service. |
| <b>[gorpc](https://github.com/valyala/gorpc) | 684 | Simple, fast and scalable RPC library for high load. |
| <b>[consistent](https://github.com/buraksezer/consistent) | 641 | Consistent hashing with bounded loads. |
| <b>[sponge](https://github.com/zhufuyi/sponge) | 623 | A distributed development framework that integrates automatic code generation, gin and grpc frameworks, base development frameworks. |
| <b>[trpc-go](https://github.com/trpc-group/trpc-go) | 589 | The Go language implementation of tRPC, which is a pluggable, high-performance RPC framework. |
| <b>[go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 519 | A library built to provide support for defining async service health checks for golang services. |
| <b>[digota](https://github.com/digota/digota) | 496 | grpc ecommerce microservice. |
| <b>[raft](https://github.com/etcd-io/raft) | 456 | Go implementation of the Raft consensus protocol, by CoreOS. |
| <b>[Temporal](https://github.com/temporalio/sdk-go) | 423 | Durable execution system for making code fault-tolerant and simple. |
| <b>[go-jump](https://github.com/dgryski/go-jump) | 374 | Port of Google's "Jump" Consistent Hash function. |
| <b>[sleuth](https://github.com/ursiform/sleuth) | 370 | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| <b>[jsonrpc](https://github.com/ybbus/jsonrpc) | 301 | JSON-RPC 2.0 HTTP client implementation. |
| <b>[dht](https://github.com/anacrolix/dht) | 288 | BitTorrent Kademlia DHT implementation. |
| <b>[jsonrpc](https://github.com/osamingo/jsonrpc) | 185 | The jsonrpc package helps implement of JSON-RPC 2.0. |
| <b>[outboxer](https://github.com/italolelis/outboxer) | 149 | Outboxer is a go library that implements the outbox pattern. |
| <b>[doublejump](https://github.com/edwingeng/doublejump) | 95 | A revamped Google's jump consistent hash. |
| <b>[Semaphore](https://github.com/jexia/semaphore) | 89 | A straightforward (micro) service orchestrator. |
| <b>[dot](https://github.com/dotchain/dot/) | 82 | distributed sync using operational transformation/OT. |
| <b>[celeriac](https://github.com/svcavallar/celeriac.v1) | 72 | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| <b>[go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 58 | MySQL based distributed lock. |
| <b>[flowgraph](https://github.com/vectaport/flowgraph) | 54 | flow-based programming package. |
| <b>[drmaa](https://github.com/dgruber/drmaa) | 47 | Job submission library for cluster schedulers based on the DRMAA standard. |
| <b>[go-pdu](https://github.com/pdupub/go-pdu) | 46 | A decentralized identity-based social network. |
| <b>[gmsec](https://github.com/gmsec/micro) | 24 | A Go distributed systems development framework. |
| <b>[consistenthash](https://github.com/mbrostami/consistenthash) | 23 | Consistent hashing with configurable replicas. |
| <b>[dynatomic](https://github.com/tylfin/dynatomic) | 16 | A library for using DynamoDB as an atomic counter. |
| <b>[failured](https://github.com/andy2046/failured) | 11 | adaptive accrual failure detector for distributed systems. |
| <b>[bedrock](https://github.com/z5labs/bedrock) | 2 | Provides a minimal, modular and composable foundation for quickly developing services and more use case specific frameworks in Go. |
| <b>[dynamolock](https://cirello.io/dynamolock) | - | DynamoDB-backed distributed locking implementation. |
| <b>[pglock](https://cirello.io/pglock) | - | PostgreSQL-backed distributed locking implementation. |
| <b>[pjrpc](https://gitlab.com/pjrpc/pjrpc) | - | Golang JSON-RPC Server-Client with Protobuf spec. |
| <b>[resgate](https://resgate.io/) | - | Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Dynamic DNS

_Tools for updating dynamic DNS records._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GoDNS](https://github.com/timothyye/godns) | 1.4k | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| <b>[DDNS](https://github.com/skibish/ddns) | 241 | Personal DDNS client with Digital Ocean Networking DNS as backend. |
| <b>[dyndns](https://gitlab.com/alcastle/dyndns) | - | Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Email

_Libraries and tools that implement email creation and sending._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[MailHog](https://github.com/mailhog/MailHog) | 13.0k | Email and SMTP testing with web and API interface. |
| <b>[Maddy](https://github.com/foxcpp/maddy) | 4.5k | All-in-one (SMTP, IMAP, DKIM, DMARC, MTA-STS, DANE) email server |
| <b>[Mailpit](https://github.com/axllent/mailpit) | 3.9k | Email and SMTP testing tool for developers. |
| <b>[hermes](https://github.com/matcornic/hermes) | 2.7k | Golang package that generates clean, responsive HTML e-mails. |
| <b>[email](https://github.com/jordan-wright/email) | 2.5k | A robust and flexible email library for Go. |
| <b>[go-imap](https://github.com/emersion/go-imap) | 1.9k | IMAP library for clients and servers. |
| <b>[email-verifier](https://github.com/AfterShip/email-verifier) | 1000 | A Go library for email verification without sending any emails. |
| <b>[SendGrid](https://github.com/sendgrid/sendgrid-go) | 941 | SendGrid's Go library for sending email. |
| <b>[mailgun-go](https://github.com/mailgun/mailgun-go) | 673 | Go library for sending mail with the Mailgun API. |
| <b>[go-simple-mail](https://github.com/xhit/go-simple-mail) | 570 | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |
| <b>[go-mail](https://github.com/wneessen/go-mail) | 396 | A simple Go library for sending mails in Go. |
| <b>[go-message](https://github.com/emersion/go-message) | 347 | Streaming library for the Internet Message Format and mail messages. |
| <b>[douceur](https://github.com/aymerick/douceur) | 238 | CSS inliner for your HTML emails. |
| <b>[Hectane](https://github.com/hectane/hectane) | 218 | Lightweight SMTP client providing an HTTP API. |
| <b>[mailchain](https://github.com/mailchain/mailchain) | 141 | Send encrypted emails to blockchain addresses written in Go. |
| <b>[go-premailer](https://github.com/vanng822/go-premailer) | 129 | Inline styling for HTML mail in Go. |
| <b>[smtpmock](https://github.com/mocktools/go-smtp-mock) | 103 | Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment. |
| <b>[go-dkim](https://github.com/toorop/go-dkim) | 94 | DKIM library, to sign & verify email. |
| <b>[smtp](https://github.com/mailhog/smtp) | 74 | SMTP server protocol state machine. |
| <b>[truemail-go](https://github.com/truemail-rb/truemail-go) | 73 | Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more. |
| <b>[go-email-validator](https://github.com/go-email-validator/go-email-validator) | 52 | Modular email validator for syntax, disposable, smtp, etc... checking. |
| <b>[mailx](https://github.com/valord577/mailx) | 9 | Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`. |
| <b>[chasquid](https://blitiri.com.ar/p/chasquid) | - | SMTP server written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Embeddable Scripting Languages

_Embedding other languages inside your go code._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopher-lua](https://github.com/yuin/gopher-lua) | 5.9k | Lua 5.1 VM and compiler written in Go. |
| <b>[expr](https://github.com/antonmedv/expr) | 5.2k | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| <b>[goja](https://github.com/dop251/goja) | 4.6k | ECMAScript 5.1(+) implementation in Go. |
| <b>[tengo](https://github.com/d5/tengo) | 3.4k | Bytecode compiled script language for Go. |
| <b>[go-lua](https://github.com/Shopify/go-lua) | 2.9k | Port of the Lua 5.2 VM to pure Go. |
| <b>[starlark-go](https://github.com/google/starlark-go) | 2.2k | Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution. |
| <b>[cel-go](https://github.com/google/cel-go) | 2.0k | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| <b>[go-python](https://github.com/sbinet/go-python) | 1.5k | naive go bindings to the CPython C-API. |
| <b>[anko](https://github.com/mattn/anko) | 1.4k | Scriptable interpreter written in Go. |
| <b>[metacall](https://github.com/metacall/core) | 1.4k | Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more. |
| <b>[go-php](https://github.com/deuill/go-php) | 919 | PHP bindings for Go. |
| <b>[go-duktape](https://github.com/olebedev/go-duktape) | 779 | Duktape JavaScript engine bindings for Go. |
| <b>[gval](https://github.com/PaesslerAG/gval) | 689 | A highly customizable expression language written in Go. |
| <b>[golua](https://github.com/aarzilli/golua) | 633 | Go bindings for Lua C API. |
| <b>[prolog](https://github.com/ichiban/prolog) | 525 | Embeddable Prolog. |
| <b>[gisp](https://github.com/jcla1/gisp) | 509 | Simple LISP in Go. |
| <b>[gentee](https://github.com/gentee/gentee) | 124 | Embeddable scripting programming language. |
| <b>[binder](https://github.com/alexeyco/binder) | 69 | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| <b>[purl](https://github.com/ian-kent/purl) | 39 | Perl 5.18.2 embedded in Go. |
| <b>[ecal](https://github.com/krotik/ecal) | 37 | A simple embeddable scripting language which supports concurrent event processing. |
| <b>[ngaro](https://github.com/db47h/ngaro) | 26 | Embeddable Ngaro VM implementation enabling scripting in Retro. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Error Handling

_Libraries for handling errors._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[errors](https://github.com/pkg/errors) | 8.1k | Package that provides simple error handling primitives. |
| <b>[go-multierror](https://github.com/hashicorp/go-multierror) | 2.1k | Go (golang) package for representing a list of errors as a single error. |
| <b>[errors](https://github.com/cockroachdb/errors) | 1.9k | Go error library with error portability over the network. |
| <b>[eris](https://github.com/rotisserie/eris) | 1.4k | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| <b>[errorx](https://github.com/joomcode/errorx) | 1.1k | A feature rich error package with stack traces, composition of errors and more. |
| <b>[tracerr](https://github.com/ztrue/tracerr) | 880 | Golang errors with stack trace and source fragments. |
| <b>[errlog](https://github.com/snwfdhmp/errlog) | 456 | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| <b>[emperror](https://github.com/emperror/emperror) | 322 | Error handling tools and best practices for Go libraries and applications. |
| <b>[errors](https://github.com/emperror/errors) | 190 | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| <b>[Fault](https://github.com/Southclaws/fault) | 146 | An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values. |
| <b>[oops](https://github.com/samber/oops) | 140 | Error handling with context, stack trace and source fragments. |
| <b>[errors](https://github.com/bnkamalesh/errors) | 60 | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| <b>[exception](https://github.com/rbrahul/exception) | 26 | A simple utility package for exception handling with try-catch in Golang. |
| <b>[Falcon](https://github.com/SonicRoshan/falcon) | 10 | A Simple Yet Highly Powerful Package For Error Handling. |
| <b>[errors](https://github.com/PumpkinSeed/errors) | 7 | The most simple error wrapper with awesome performance and minimal memory overhead. |
| <b>[errors](https://github.com/neuronlabs/errors) | 6 | Simple golang error handling with classification primitives. |
| <b>[errors](https://gitlab.com/tozd/go/errors) | - | Providing errors with a stack trace and optional structured details. Compatible with github.com/pkg/errors API but does not use it internally. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## File Handling

_Libraries for handling files and file systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[pdfcpu](https://github.com/pdfcpu/pdfcpu) | 5.9k | PDF processor. |
| <b>[afero](https://github.com/spf13/afero) | 5.6k | FileSystem Abstraction System for Go. |
| <b>[gdu](https://github.com/dundee/gdu) | 3.0k | Disk usage analyzer with console interface. |
| <b>[notify](https://github.com/rjeczalik/notify) | 871 | File system event notification library with simple API, similar to os/signal. |
| <b>[copy](https://github.com/otiai10/copy) | 647 | Copy directory recursively. |
| <b>[gofs](https://github.com/no-src/gofs) | 391 | A file synchronization tool out of the box. |
| <b>[afs](https://github.com/viant/afs) | 274 | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| <b>[vfs](https://github.com/C2FO/vfs) | 264 | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| <b>[iso9660](https://github.com/kdomanski/iso9660) | 248 | A package for reading and creating ISO9660 disk images |
| <b>[bigfile](https://github.com/bigfile/bigfile) | 247 | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| <b>[go-exiftool](https://github.com/barasher/go-exiftool) | 210 | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| <b>[go-csv-tag](https://github.com/artonge/go-csv-tag) | 112 | Load csv file using tag. |
| <b>[checksum](https://github.com/codingsince1985/checksum) | 97 | Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files. |
| <b>[skywalker](https://github.com/dixonwille/skywalker) | 96 | Package to allow one to concurrently go through a filesystem with ease. |
| <b>[parquet](https://github.com/parsyl/parquet) | 88 | Read and write [parquet](https://parquet.apache.org) files. |
| <b>[opc](https://github.com/qmuntal/opc) | 75 | Load Open Packaging Conventions (OPC) files for Go. |
| <b>[tarfs](https://github.com/posener/tarfs) | 59 | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| <b>[baraka](https://github.com/xis/baraka) | 52 | A library to process http file uploads easily. |
| <b>[go-gtfs](https://github.com/artonge/go-gtfs) | 38 | Load gtfs files in go. |
| <b>[flop](https://github.com/homedepot/flop) | 34 | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| <b>[gut/yos](https://github.com/1set/gut) | 27 | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| <b>[go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 21 | Copy files for humans. |
| <b>[todotxt](https://github.com/1set/todotxt) | 20 | Go library for Gina Trapani's [_todo.txt_](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [_todo.txt_ format](https://github.com/todotxt/todo.txt). |
| <b>[higgs](https://github.com/dastoori/higgs) | 18 | A tiny cross-platform Go library to hide/unhide files and directories. |
| <b>[pathtype](https://github.com/jonchun/pathtype) | 13 | Treat paths as their own type instead of using strings. |
| <b>[stl](https://gitlab.com/russoj88/stl) | - | Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Financial

_Packages for accounting and finance._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[decimal](https://github.com/shopspring/decimal) | 5.7k | Arbitrary-precision fixed-point decimal numbers. |
| <b>[ticker](https://github.com/achannarasappa/ticker) | 4.8k | Terminal stock watcher and stock position tracker. |
| <b>[go-money](https://github.com/rhymond/go-money) | 1.4k | Implementation of Fowler's Money pattern. |
| <b>[bbgo](https://github.com/c9s/bbgo) | 1000 | A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies. |
| <b>[accounting](https://github.com/leekchan/accounting) | 848 | money and currency formatting for golang. |
| <b>[techan](https://github.com/sdcoffey/techan) | 772 | Technical analysis library with advanced market analysis and trading strategies. |
| <b>[go-finance](https://github.com/FlashBoys/go-finance) | 536 | Comprehensive financial markets data in Go. |
| <b>[currency](https://github.com/bojanz/currency) | 469 | Handles currency amounts, provides currency information and formatting. |
| <b>[ach](https://github.com/moov-io/ach) | 417 | A reader, writer, and valdiator for Automated Clearing House (ACH) files. |
| <b>[orderbook](https://github.com/i25959341/orderbook) | 380 | Matching Engine for Limit Order Book in Golang. |
| <b>[go-finance](https://github.com/alpeb/go-finance) | 160 | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| <b>[sleet](https://github.com/BoltApp/sleet) | 131 | One unified interface for multiple Payment Service Providers (PsP) to process online payment. |
| <b>[ofxgo](https://github.com/aclindsa/ofxgo) | 127 | Query OFX servers and/or parse the responses (with example command-line client). |
| <b>[transaction](https://github.com/claygod/transaction) | 127 | Embedded transactional database of accounts, running in multithreaded mode. |
| <b>[vat](https://github.com/dannyvankooten/vat) | 110 | VAT number validation & EU VAT rates. |
| <b>[go-finnhub](https://github.com/m1/go-finnhub) | 84 | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| <b>[currency](https://github.com/bnkamalesh/currency) | 57 | High performant & accurate currency computation package. |
| <b>[fastme](https://github.com/newity/fastme) | 37 | Fast extensible matching engine Go implementation. |
| <b>[payme](https://github.com/jovandeginste/payme) | 27 | QR code generator (ASCII & PNG) for SEPA payments. |
| <b>[fpdecimal](https://github.com/nikolaydubina/fpdecimal) | 26 | Fast and precise serialization and arithmetic for small fixed-point decimals |
| <b>[go-finance](https://github.com/pieterclaerhout/go-finance) | 24 | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |
| <b>[fpmoney](https://github.com/nikolaydubina/fpmoney) | 23 | Fast and simple ISO4217 fixed-point decimal money. |
| <b>[decimal](https://github.com/govalues/decimal) | 16 | Immutable decimal numbers with panic-free arithmetic. |
| <b>[money](https://github.com/govalues/money) | 10 | Immutable monetary amounts and exchange rates with panic-free arithmetic. |
| <b>[go-nowpayments](https://github.com/matm/go-nowpayments) | 2 | Library for the crypto NOWPayments API. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Forms

_Libraries for working with forms._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[nosurf](https://github.com/justinas/nosurf) | 1.5k | CSRF protection middleware for Go. |
| <b>[gorilla/csrf](https://github.com/gorilla/csrf) | 973 | CSRF protection for Go web applications & services. |
| <b>[binding](https://github.com/mholt/binding) | 795 | Binds form and JSON data from net/http Request to struct. |
| <b>[form](https://github.com/go-playground/form) | 671 | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| <b>[conform](https://github.com/leebenson/conform) | 315 | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| <b>[httpin](https://github.com/ggicci/httpin) | 231 | Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc. |
| <b>[formam](https://github.com/monoculum/formam) | 182 | decode form's values into a struct. |
| <b>[forms](https://github.com/albrow/forms) | 135 | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| <b>[qs](https://github.com/sonh/qs) | 69 | Go module for encoding structs into URL query parameters. |
| <b>[bind](https://github.com/robfig/bind) | 30 | Bind form data to any Go values. |
| <b>[queryparam](https://github.com/tomwright/queryparam) | 19 | Decode `url.Values` into usable struct values of standard or custom types. |
| <b>[gbind](https://github.com/bdjimmy/gbind) | 8 | Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation |
| <b>[checker](https://github.com/cinar/checker) | 6 | Checker helps validating user input through rules defined in struct tags or directly through functions. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Functional

_Packages to support functional programming in Go._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[mo](https://github.com/samber/mo) | 2.1k | Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...). |
| <b>[go-underscore](https://github.com/tobyhede/go-underscore) | 1.3k | Useful collection of helpfully functional Go collection utilities. |
| <b>[fpGo](https://github.com/TeaEntityLab/fpGo) | 333 | Monad, Functional Programming features for Golang. |
| <b>[fp-go](https://github.com/repeale/fp-go) | 275 | Collection of Functional Programming helpers powered by Golang 1.18+ generics. |
| <b>[go-functional](https://github.com/BooleanCat/go-functional) | 254 | Functional programming in Go using generics |
| <b>[gofp](https://github.com/rbrahul/gofp) | 143 | A lodash like powerful utility library for Golang. |
| <b>[fuego](https://github.com/seborama/fuego) | 142 | Functional Experiment in Go. |
| <b>[underscore](https://github.com/rjNemo/underscore) | 102 | Functional programming helpers for Go 1.18 and beyond. |
| <b>[valor](https://github.com/phelmkamp/valor) | 16 | Generic option and result types that optionally contain a value. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Game Development

_Awesome game development libraries._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Ebiten](https://github.com/hajimehoshi/ebiten) | 9.4k | dead simple 2D game library in Go. |
| <b>[Leaf](https://github.com/name5566/leaf) | 5.1k | Lightweight game server framework. |
| <b>[Pixel](https://github.com/faiface/pixel) | 4.4k | Hand-crafted 2D game library in Go. |
| <b>[g3n](https://github.com/g3n/engine) | 2.6k | Go 3D Game Engine. |
| <b>[nano](https://github.com/lonng/nano) | 2.6k | Lightweight, facility, high performance golang based game server framework. |
| <b>[goworld](https://github.com/xiaonanln/goworld) | 2.5k | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| <b>[go-sdl2](https://github.com/veandco/go-sdl2) | 2.1k | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| <b>[Pitaya](https://github.com/topfreegames/pitaya) | 2.1k | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| <b>[engo](https://github.com/EngoEngine/engo) | 1.7k | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| <b>[Oak](https://github.com/oakmound/oak) | 1.5k | Pure Go game engine. |
| <b>[termloop](https://github.com/JoelOtter/termloop) | 1.4k | Terminal-based game engine for Go, built on top of Termbox. |
| <b>[gonet](https://github.com/xtaci/gonet) | 1.2k | Game server skeleton implemented with golang. |
| <b>[raylib-go](https://github.com/gen2brain/raylib-go) | 1.2k | Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| <b>[Azul3D](https://github.com/azul3d/engine) | 597 | 3D game engine written in Go. |
| <b>[go-astar](https://github.com/beefsack/go-astar) | 575 | Go implementation of the A\* path finding algorithm. |
| <b>[Harfang3D](https://github.com/harfang3d/harfang3d) | 442 | 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev](github.com/harfang3d/harfang-go)). |
| <b>[go3d](https://github.com/ungerik/go3d) | 284 | Performance oriented 2D/3D math package for Go. |
| <b>[tile](https://github.com/kelindar/tile) | 134 | Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. |
| <b>[prototype](https://github.com/gonutz/prototype) | 83 | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| <b>[fantasyname](https://github.com/s0rg/fantasyname) | 29 | Fantasy names generator. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Generators

_Tools that generate Go code._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[oapi-codegen](https://github.com/deepmap/oapi-codegen) | 4.8k | This package contains a set of utilities for generating Go boilerplate code for services based on OpenAPI 3.0 API definitions. |
| <b>[go-linq](https://github.com/ahmetalpbalkan/go-linq) | 3.4k | .NET LINQ-like query methods for Go. |
| <b>[jennifer](https://github.com/dave/jennifer) | 3.1k | Generate arbitrary Go code without templates. |
| <b>[goderive](https://github.com/awalterschulze/goderive) | 1.2k | Derives functions from input types. |
| <b>[GoWrap](https://github.com/hexdigest/gowrap) | 847 | Generate decorators for Go interfaces using simple templates. |
| <b>[go-enum](https://github.com/abice/go-enum) | 611 | Code generation for enums from code comments. |
| <b>[interfaces](https://github.com/rjeczalik/interfaces) | 409 | Command line tool for generating interface definitions. |
| <b>[goverter](https://github.com/jmattheis/goverter) | 398 | Generate converters by defining an interface. |
| <b>[copygen](https://github.com/switchupcb/copygen) | 311 | Generate type-to-type code without reflection. |
| <b>[gotype](https://github.com/wzshiming/gotype) | 58 | Golang source code parsing, usage like reflect package. |
| <b>[generis](https://github.com/senselogic/GENERIS) | 43 | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| <b>[go-xray](https://github.com/pieterclaerhout/go-xray) | 27 | Helpers for making the use of reflection easier. |
| <b>[typeregistry](https://github.com/xiaoxin01/typeregistry) | 23 | A library to create type dynamically. |
| <b>[convergen](https://github.com/reedom/convergen) | 20 | Feature rich type-to-type copy code generator. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Geographic

_Geographic tools and servers_


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Tile38](https://github.com/tidwall/tile38) | 8.8k | Geolocation DB with spatial index and realtime geofencing. |
| <b>[S2 geometry](https://github.com/golang/geo) | 1.6k | S2 geometry library in Go. |
| <b>[mbtileserver](https://github.com/consbio/mbtileserver) | 571 | A simple Go-based server for map tiles stored in mbtiles format. |
| <b>[osm](https://github.com/paulmach/osm) | 321 | Library for reading, writing and working with OpenStreetMap data and APIs. |
| <b>[H3](https://github.com/uber/h3-go) | 263 | Go bindings for H3, a hierarchical hexagonal geospatial indexing system. |
| <b>[godal](https://github.com/airbusgeo/godal) | 112 | Go wrapper for GDAL. |
| <b>[simplefeatures](https://github.com/peterstace/simplefeatures) | 112 | simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them. |
| <b>[WGS84](https://github.com/wroge/wgs84) | 109 | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| <b>[geoserver](https://github.com/hishamkaram/geoserver) | 85 | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| <b>[gismanager](https://github.com/hishamkaram/gismanager) | 50 | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| <b>[pbf](https://github.com/maguro/pbf) | 47 | OpenStreetMap PBF golang encoder/decoder. |
| <b>[S2 geojson](https://github.com/pantrif/s2-geojson) | 26 | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |
| <b>[Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) | 5 | A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection. |
| <b>[H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) | 3 | Conversion utilities between H3 indexes and GeoJSON. |
| <b>[H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) | 2 | Distribution of Uber H3geo cells by virtual nodes. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Compilers

_Tools for compiling Go to other languages._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopherjs](https://github.com/gopherjs/gopherjs) | 12.0k | Compiler from Go to JavaScript. |
| <b>[tardisgo](https://github.com/tardisgo/tardisgo) | 429 | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| <b>[c4go](https://github.com/Konstantin8105/c4go) | 349 | Transpile C code to Go code. |
| <b>[c2go](https://github.com/goplus/c2go) | 298 | Convert C code to Go code. |
| <b>[esp32](https://github.com/andygeiss/esp32-transpiler) | 79 | Transpile Go into Arduino code. |
| <b>[f4go](https://github.com/Konstantin8105/f4go) | 41 | Transpile FORTRAN 77 code to Go code. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Goroutines

_Tools for managing and working with Goroutines._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[ants](https://github.com/panjf2000/ants) | 12.0k | A high-performance and low-cost goroutine pool in Go. |
| <b>[conc](https://github.com/sourcegraph/conc) | 8.1k | `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer. |
| <b>[tunny](https://github.com/Jeffail/tunny) | 3.8k | Goroutine pool for golang. |
| <b>[goworker](https://github.com/benmanns/goworker) | 2.8k | goworker is a Go-based background worker. |
| <b>[workerpool](https://github.com/gammazero/workerpool) | 1.2k | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| <b>[pond](https://github.com/alitto/pond) | 1.1k | Minimalistic and High-performance goroutine worker pool written in Go. |
| <b>[grpool](https://github.com/ivpusic/grpool) | 737 | Lightweight Goroutine pool. |
| <b>[pool](https://github.com/go-playground/pool) | 722 | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| <b>[gowp](https://github.com/xxjwxc/gowp) | 487 | gowp is concurrency limiting goroutine pool. |
| <b>[go-floc](https://github.com/workanator/go-floc) | 264 | Orchestrate goroutines with ease. |
| <b>[flowmatic](https://github.com/carlmjohnson/flowmatic) | 224 | Structured concurrency made easy. |
| <b>[go-flow](https://github.com/kamildrazkiewicz/go-flow) | 218 | Control goroutines execution order. |
| <b>[artifex](https://github.com/borderstech/artifex) | 182 | Simple in-memory job queue for Golang using worker-based dispatching. |
| <b>[routine](https://github.com/timandy/routine) | 174 | `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully. |
| <b>[async](https://github.com/reugn/async) | 169 | An alternative sync library for Go (Future, Promise, Locks). |
| <b>[semaphore](https://github.com/marusama/semaphore) | 165 | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| <b>[go-workers](https://github.com/catmullet/go-workers) | 162 | Easily and safely run workers for large data processing pipelines. |
| <b>[neilotoole/errgroup](https://github.com/neilotoole/errgroup) | 156 | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| <b>[cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 136 | CyclicBarrier for golang. |
| <b>[async](https://github.com/studiosol/async) | 130 | A safe way to execute functions asynchronously, recovering them in case of panic. |
| <b>[gollback](https://github.com/vardius/gollback) | 116 | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| <b>[go-actor](https://github.com/vladopajic/go-actor) | 97 | A tiny library for writing concurrent programs using actor model. |
| <b>[Hunch](https://github.com/AaronJan/Hunch) | 97 | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| <b>[semaphore](https://github.com/kamilsk/semaphore) | 96 | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| <b>[threadpool](https://github.com/shettyh/threadpool) | 96 | Golang threadpool implementation. |
| <b>[worker-pool](https://github.com/vardius/worker-pool) | 90 | goworker is a Go simple async worker pool. |
| <b>[gpool](https://github.com/Sherifabdlnaby/gpool) | 89 | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| <b>[goccm](https://github.com/zenthangplus/goccm) | 66 | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| <b>[gowl](https://github.com/hamed-yousefi/gowl) | 62 | Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status. |
| <b>[nursery](https://github.com/arunsworld/nursery) | 62 | Structured concurrency in Go. |
| <b>[routine](https://github.com/x-mod/routine) | 60 | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| <b>[gohive](https://github.com/loveleshsharma/gohive) | 48 | A highly performant and easy to use Goroutine pool for Go. |
| <b>[kyoo](https://github.com/dirkaholic/kyoo) | 45 | Provides an unlimited job queue and concurrent worker pools. |
| <b>[go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 44 | Like `sync.WaitGroup` with error handling and concurrency control. |
| <b>[parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 35 | Run functions in parallel. |
| <b>[go-trylock](https://github.com/subchen/go-trylock) | 33 | TryLock support on read-write lock for Golang. |
| <b>[stl](https://github.com/ssgreg/stl) | 28 | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| <b>[channelify](https://github.com/ddelizia/channelify) | 27 | Transform your function to return channels for easy and powerful parallel processing. |
| <b>[concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) | 17 | Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines. |
| <b>[execpool](https://github.com/hexdigest/execpool) | 17 | A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command. |
| <b>[breaker](https://github.com/kamilsk/breaker) | 16 | Flexible mechanism to make execution flow interruptible. |
| <b>[queue](https://github.com/AnikHasibul/queue) | 15 | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| <b>[conexec](https://github.com/ITcathyh/conexec) | 14 | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| <b>[go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) | 14 | Manage a pool of goroutines using this lightweight library with a simple API. |
| <b>[go-workerpool](https://github.com/zenthangplus/go-workerpool) | 10 | Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines. |
| <b>[hands](https://github.com/duanckham/hands) | 10 | A process controller used to control the execution and return strategies of multiple goroutines. |
| <b>[async-job](https://github.com/lab210-dev/async-job) | 8 | AsyncJob is an asynchronous queue job manager with light code, clear and speed. |
| <b>[go-accumulator](https://github.com/nar10z/go-accumulator) | 6 | Solution for accumulation of events and their subsequent processing. |
| <b>[oversight](https://pkg.go.dev/cirello.io/oversight) | - | Oversight is a complete implementation of the Erlang supervision trees. |
| <b>[oversight](https://cirello.io/oversight) | - | Oversight is a complete implementation of the Erlang supervision trees. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## GUI

_Interaction_


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fyne](https://github.com/fyne-io/fyne) | 22.0k | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| <b>[webview](https://github.com/zserge/webview) | 12.0k | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| <b>[qt](https://github.com/therecipe/qt) | 10.0k | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| <b>[robotgo](https://github.com/go-vgo/robotgo) | 9.0k | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| <b>[ui](https://github.com/andlabs/ui) | 8.3k | Platform-native GUI library for Go. Cross platform. |
| <b>[app](https://github.com/murlokswarm/app) | 7.6k | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| <b>[walk](https://github.com/lxn/walk) | 6.7k | Windows application library kit for Go. |
| <b>[go-astilectron](https://github.com/asticode/go-astilectron) | 4.9k | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| <b>[systray](https://github.com/getlantern/systray) | 3.0k | Cross platform Go library to place an icon and menu in the notification area. |
| <b>[go-sciter](https://github.com/sciter-sdk/go-sciter) | 2.6k | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| <b>[gotk3](https://github.com/gotk3/gotk3) | 2.0k | Go bindings for GTK3. |
| <b>[zenity](https://github.com/ncruces/zenity) | 596 | Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user. |
| <b>[gosx-notifier](https://github.com/deckarep/gosx-notifier) | 584 | OSX Desktop Notifications library for Go. |
| <b>[gowd](https://github.com/dtylman/gowd) | 417 | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| <b>[trayhost](https://github.com/shurcooL/trayhost) | 246 | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| <b>[energy](https://github.com/energye/energy) | 218 | Cross-platform based on LCL(Native System UI Control Library) and CEF(Chromium Embedded Framework) (Windows/ macOS / Linux) |
| <b>[unison](https://github.com/richardwilkes/unison) | 126 | A unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported. |
| <b>[mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 30 | OSX Sleep/Wake notifications in golang. |
| <b>[mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 26 | OSX library to notify about any (pluggable) activity on your machine. |
| <b>[go-appindicator](https://github.com/dawidd6/go-appindicator) | 19 | Go bindings for libappindicator3 C library. |
| <b>[goradd/html5tag](https://github.com/goradd/html5tag) | 6 | Library for outputting HTML5 tags. |
| <b>[AppIndicator Go](https://github.com/gopherlibs/appindicator) | 4 | Go bindings for libappindicator3 C library. |
| <b>[Wails](https://wails.io) | - | Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer. |
| <b>[Goey](https://bitbucket.org/rj/goey/src/master/) | - | Cross platform UI toolkit aggregator for Windows / Linux / Mac. GTK, Cocoa, Windows API |
| <b>[gio](https://gioui.org) | - | Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly. |
| <b>[go-gtk](https://mattn.github.io/go-gtk/) | - | Go bindings for GTK. |
| <b>[Wails](https://wails.app) | - | Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Hardware

_Libraries, tools, and tutorials for interacting with hardware._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[arduino-cli](https://github.com/arduino/arduino-cli) | 4.1k | Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects. |
| <b>[go-rpio](https://github.com/stianeikeland/go-rpio) | 2.1k | GPIO for Go, doesn't require cgo. |
| <b>[ghw](https://github.com/jaypipes/ghw) | 1.5k | Golang hardware discovery/inspection library. |
| <b>[emgo](https://github.com/ziutek/emgo) | 1000 | Go-like language for programming embedded systems (e.g. STM32 MCU). |
| <b>[sysinfo](https://github.com/zcalusic/sysinfo) | 474 | A pure Go library providing Linux OS / kernel / hardware system information. |
| <b>[goroslib](https://github.com/aler9/goroslib) | 292 | Robot Operating System (ROS) library for Go. |
| <b>[go-osc](https://github.com/hypebeast/go-osc) | 183 | Open Sound Control (OSC) bindings for Go. |
| <b>[joystick](https://github.com/0xcafed00d/joystick) | 52 | a polled API to read the state of an attached joystick. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Images

_Libraries for manipulating images._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gocv](https://github.com/hybridgroup/gocv) | 6.0k | Go package for computer vision using OpenCV 3.3+. |
| <b>[imaginary](https://github.com/h2non/imaginary) | 5.2k | Fast and simple HTTP microservice for image resizing. |
| <b>[imaging](https://github.com/disintegration/imaging) | 5.0k | Simple Go image processing package. |
| <b>[gg](https://github.com/fogleman/gg) | 4.2k | 2D rendering in pure Go. |
| <b>[bild](https://github.com/anthonynsimon/bild) | 3.9k | Collection of image processing algorithms in pure Go. |
| <b>[ln](https://github.com/fogleman/ln) | 3.2k | 3D line art rendering in Go. |
| <b>[resize](https://github.com/nfnt/resize) | 3.0k | Image resizing for Go with common interpolation methods. |
| <b>[gowitness](https://github.com/sensepost/gowitness) | 2.6k | Screenshoting webpages using go and headless chrome on command line. |
| <b>[bimg](https://github.com/h2non/bimg) | 2.5k | Small package for fast and efficient image processing using libvips. |
| <b>[pt](https://github.com/fogleman/pt) | 2.1k | Path tracing engine written in Go. |
| <b>[svgo](https://github.com/ajstarks/svgo) | 2.1k | Go Language Library for SVG generation. |
| <b>[picfit](https://github.com/thoas/picfit) | 2.0k | An image resizing server written in Go. |
| <b>[smartcrop](https://github.com/muesli/smartcrop) | 1.8k | Finds good crops for arbitrary images and crop sizes. |
| <b>[gift](https://github.com/disintegration/gift) | 1.7k | Package of image processing filters. |
| <b>[imagick](https://github.com/gographics/imagick) | 1.7k | Go binding to ImageMagick's MagickWand C API. |
| <b>[canvas](https://github.com/tdewolff/canvas) | 1.4k | Vector graphics to PDF, SVG or rasterized image. |
| <b>[geopattern](https://github.com/pravj/geopattern) | 1.3k | Create beautiful generative image patterns from a string. |
| <b>[go-opencv](https://github.com/lazywei/go-opencv) | 1.3k | Go bindings for OpenCV. |
| <b>[govips](https://github.com/davidbyttow/govips) | 1.1k | A lightning fast image processing and resizing library for Go. |
| <b>[stegify](https://github.com/DimitarPetrov/stegify) | 1.1k | Go tool for LSB steganography, capable of hiding any file within an image. |
| <b>[image2ascii](https://github.com/qeesung/image2ascii) | 820 | Convert image to ASCII. |
| <b>[goimagehash](https://github.com/corona10/goimagehash) | 676 | Go Perceptual image hashing package. |
| <b>[govatar](https://github.com/o1egl/govatar) | 576 | Library and CMD tool for generating funny avatars. |
| <b>[draft](https://github.com/lucasepe/draft) | 574 | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| <b>[mort](https://github.com/aldor007/mort) | 496 | Storage and image processing server written in Go. |
| <b>[go-nude](https://github.com/koyachi/go-nude) | 395 | Nudity detection with Go. |
| <b>[steganography](https://github.com/auyer/steganography) | 284 | Pure Go Library for LSB steganography. |
| <b>[darkroom](https://github.com/gojek/darkroom) | 224 | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| <b>[gltf](https://github.com/qmuntal/gltf) | 223 | Efficient and robust glTF 2.0 reader, writer and validator. |
| <b>[mergi](https://github.com/noelyahan/mergi) | 217 | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| <b>[rez](https://github.com/bamiaux/rez) | 209 | Image resizing in pure Go and SIMD. |
| <b>[go-webp](https://github.com/kolesa-team/go-webp) | 182 | Library for encode and decode webp pictures, using libwebp. |
| <b>[transformimgs](https://github.com/Pixboost/transformimgs) | 171 | Transformimgs resizes and optimises images for Web using next-generation formats. |
| <b>[img](https://github.com/hawx/img) | 151 | Selection of image manipulation tools. |
| <b>[go-cairo](https://github.com/ungerik/go-cairo) | 136 | Go binding for the cairo graphics library. |
| <b>[cameron](https://github.com/aofei/cameron) | 110 | An avatar generator for Go. |
| <b>[color-extractor](https://github.com/marekm4/color-extractor) | 74 | Dominant color extractor with no external dependencies. |
| <b>[gridder](https://github.com/shomali11/gridder) | 72 | A Grid based 2D Graphics library. |
| <b>[webp-server](https://github.com/mehdipourfar/webp-server) | 68 | Simple and minimal image server capable of storing, resizing, converting and caching images. |
| <b>[go-gd](https://github.com/bolknote/go-gd) | 59 | Go binding for GD library. |
| <b>[goimghdr](https://github.com/corona10/goimghdr) | 40 | The imghdr module determines the type of image contained in a file for Go. |
| <b>[tga](https://github.com/ftrvxmtrx/tga) | 34 | Package tga is a TARGA image format decoder/encoder. |
| <b>[go-webcolors](https://github.com/jyotiska/go-webcolors) | 27 | Port of webcolors library from Python to Go. |
| <b>[mpo](https://github.com/donatj/mpo) | 13 | Decoder and conversion tool for MPO 3D Photos. |
| <b>[scout](https://github.com/jonoton/scout) | 12 | Scout is a standalone open source software solution for DIY video security. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## IoT (Internet of Things)

_Libraries for programming devices of the IoT._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gobot](https://github.com/hybridgroup/gobot/) | 8.6k | Gobot is a framework for robotics, physical computing, and the Internet of Things. |
| <b>[flogo](https://github.com/tibcosoftware/flogo) | 2.3k | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| <b>[ekuiper](https://github.com/lf-edge/ekuiper) | 1.3k | Lightweight data stream processing engine for IoT edge. |
| <b>[gatt](https://github.com/paypal/gatt) | 1.1k | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| <b>[connectordb](https://github.com/connectordb/connectordb) | 386 | Open-Source Platform for Quantified Self & IoT. |
| <b>[devices](https://github.com/goiot/devices) | 263 | Suite of libraries for IoT devices, experimental for x/exp/io. |
| <b>[huego](https://github.com/amimof/huego) | 245 | An extensive Philips Hue client library for Go. |
| <b>[sensorbee](https://github.com/sensorbee/sensorbee) | 227 | Lightweight stream processing engine for IoT. |
| <b>[iot](https://github.com/vaelen/iot/) | 64 | IoT is a simple framework for implementing a Google IoT Core device. |
| <b>[eywa](https://github.com/xcodersun/eywa) | 61 | Project Eywa is essentially a connection manager that keeps track of connected devices. |
| <b>[mainflux](https://github.com/Mainflux/mainflux) | 19 | Industrial IoT Messaging and Device Management Server. |
| <b>[periph](https://periph.io/) | - | Peripherals I/O to interface with low-level board facilities. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Job Scheduler

_Libraries for scheduling jobs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gocron](https://github.com/go-co-op/gocron) | 4.6k | Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). |
| <b>[go-quartz](https://github.com/reugn/go-quartz) | 1.6k | Simple, zero-dependency scheduling library for Go. |
| <b>[Dagu](https://github.com/dagu-go/dagu) | 1000 | No-code workflow executor. it executes DAGs defined in a simple YAML format. |
| <b>[gron](https://github.com/roylee0704/gron) | 1000 | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| <b>[JobRunner](https://github.com/bamzi/jobrunner) | 998 | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| <b>[jobs](https://github.com/albrow/jobs) | 494 | Persistent and flexible background jobs library. |
| <b>[scheduler](https://github.com/carlescere/scheduler) | 437 | Cronjobs scheduling made easy. |
| <b>[gronx](https://github.com/adhocore/gronx) | 332 | Cron expression parser, task runner and daemon consuming crontab like task list. |
| <b>[goflow](https://github.com/fieldryand/goflow) | 236 | A workflow orchestrator and scheduler for rapid prototyping of ETL/ML/AI pipelines. |
| <b>[go-cron](https://github.com/rk/go-cron) | 223 | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| <b>[tasks](https://github.com/madflojo/tasks) | 222 | An easy to use in-process scheduler for recurring tasks in Go. |
| <b>[clockwerk](https://github.com/onatm/clockwerk) | 141 | Go package to schedule periodic jobs using a simple, fluent syntax. |
| <b>[cheek](https://github.com/datarootsio/cheek) | 114 | A simple crontab like scheduler that aims to offer a KISS approach to job scheduling. |
| <b>[leprechaun](https://github.com/kilgaloon/leprechaun) | 101 | Job scheduler that supports webhooks, crons and classic scheduling. |
| <b>[cdule](https://github.com/deepaksinghvi/cdule) | 45 | Job scheduler library with database support |
| <b>[sched](https://github.com/romshark/sched) | 27 | A job scheduler with the ability to fast-forward time. |
| <b>[cronticker](https://github.com/krayzpipes/cronticker) | 11 | A ticker implementation to support cron schedules. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## JSON

_Libraries for working with JSON._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GJSON](https://github.com/tidwall/gjson) | 13.0k | Get a JSON value with one line of code. |
| <b>[gojson](https://github.com/ChimeraCoder/gojson) | 2.6k | Automatically generate Go (golang) struct definitions from example JSON. |
| <b>[fastjson](https://github.com/valyala/fastjson) | 2.1k | Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. |
| <b>[OjG](https://github.com/ohler55/ojg) | 764 | Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath. |
| <b>[jsondiff](https://github.com/wI2L/jsondiff) | 370 | JSON diff library for Go based on RFC6902 (JSON Patch). |
| <b>[marshmallow](https://github.com/PerimeterX/marshmallow) | 337 | Performant JSON unmarshaling for flexible use cases. |
| <b>[kazaam](https://github.com/Qntfy/kazaam) | 272 | API for arbitrary transformation of JSON documents. |
| <b>[ajson](https://github.com/spyzhov/ajson) | 203 | Abstract JSON for golang with JSONPath support. |
| <b>[gojq](https://github.com/elgs/gojq) | 191 | JSON query in Golang. |
| <b>[jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) | 168 | A fast and convinient library for unstructured JSON data, replacing `encoding/json`. |
| <b>[jettison](https://github.com/wI2L/jettison) | 167 | Fast and flexible JSON encoder for Go. |
| <b>[json2go](https://github.com/m-zajac/json2go) | 125 | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| <b>[gjo](https://github.com/skanehira/gjo) | 122 | Small utility to create JSON objects. |
| <b>[jsongo](https://github.com/ricardolonga/jsongo) | 109 | Fluent API to make it easier to create Json objects. |
| <b>[JayDiff](https://github.com/yazgazan/jaydiff) | 103 | JSON diff utility written in Go. |
| <b>[jscan](https://github.com/romshark/jscan) | 80 | High performance zero-allocation JSON iterator. |
| <b>[ujson](https://github.com/olvrng/ujson) | 72 | Fast and minimal JSON parser and transformer that works on unstructured JSON. |
| <b>[jsonf](https://github.com/miolini/jsonf) | 65 | Console tool for highlighted formatting and struct query fetching JSON. |
| <b>[go-respond](https://github.com/nicklaw5/go-respond) | 53 | Go package for handling common HTTP JSON responses. |
| <b>[mp](https://github.com/sanbornm/mp) | 47 | Simple cli email parser. It currently takes stdin and outputs JSON. |
| <b>[jsoncolor](https://github.com/neilotoole/jsoncolor) | 41 | Drop-in replacement for `encoding/json` that outputs colorized JSON. |
| <b>[vjson](https://github.com/miladibra10/vjson) | 38 | Go package for validating JSON objects with declaring a JSON schema with fluent API. |
| <b>[ask](https://github.com/simonnilsson/ask) | 33 | Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types. |
| <b>[gojmapr](https://github.com/limiu82214/gojmapr) | 22 | Get simple struct from complex json by json path. |
| <b>[dynjson](https://github.com/cocoonspace/dynjson) | 16 | Client-customizable JSON formats for dynamic APIs. |
| <b>[mapslice-json](https://github.com/mickep76/mapslice-json) | 16 | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| <b>[go-jsonerror](https://github.com/ddymko/go-jsonerror) | 14 | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| <b>[jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 14 | Go bindings based on the JSON API errors reference. |
| <b>[jsonhal](https://github.com/RichardKnop/jsonhal) | 14 | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| <b>[epoch](https://github.com/vtopc/epoch) | 13 | Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON. |
| <b>[jzon](https://github.com/zerosnake0/jzon) | 12 | JSON library with standard compatible API/behavior. |
| <b>[jsonic](https://github.com/sinhashubham95/jsonic) | 11 | Utilities to handle and query JSON without defining structs in a type safe manner. |
| <b>[ej](https://github.com/lucassscaravelli/ej) | 10 | Write and read JSON from different sources succinctly. |
| <b>[omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) | 5 | Simple JSON parser with validation by condition via golang struct fields tags. |
| <b>[htmljson](https://github.com/nikolaydubina/htmljson) | 5 | Rich rendering of JSON as HTML in Go. |
| <b>[jsonhandlers](https://github.com/abusomani/jsonhandlers) | 2 | JSON library to expose simple handlers that lets you easily read and write json from various sources. |
| <b>[JSON-to-Go](https://mholt.github.io/json-to-go/) | - | Convert JSON to Go struct. |
| <b>[JSON-to-Proto](https://json-to-proto.github.io/) | - | Convert JSON to Protobuf online. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Logging

_Libraries for generating and working with log files._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[logrus](https://github.com/Sirupsen/logrus) | 24.0k | Structured logger for Go. |
| <b>[zap](https://github.com/uber-go/zap) | 20.0k | Fast, structured, leveled logging in Go. |
| <b>[zerolog](https://github.com/rs/zerolog) | 9.4k | Zero-allocation JSON logger. |
| <b>[spew](https://github.com/davecgh/go-spew) | 5.8k | Implements a deep pretty printer for Go data structures to aid in debugging. |
| <b>[lumberjack](https://github.com/natefinch/lumberjack) | 4.5k | Simple rolling logger, implements io.WriteCloser. |
| <b>[glog](https://github.com/golang/glog) | 3.5k | Leveled execution logs for Go. |
| <b>[tail](https://github.com/hpcloud/tail) | 2.6k | Go package striving to emulate the features of the BSD tail program. |
| <b>[pp](https://github.com/k0kubun/pp) | 1.7k | Colored pretty printer for Go language. |
| <b>[seelog](https://github.com/cihub/seelog) | 1.6k | Logging functionality with flexible dispatching, filtering, and formatting. |
| <b>[log](https://github.com/apex/log) | 1.3k | Structured logging package for Go. |
| <b>[log15](https://github.com/inconshreveable/log15) | 1.1k | Simple, powerful logging for Go. |
| <b>[phuslu/log](https://github.com/phuslu/log) | 537 | Structured Logging Made Easy. |
| <b>[tint](https://github.com/lmittmann/tint) | 531 | A slog.Handler that writes tinted logs. |
| <b>[onelog](https://github.com/francoispqt/onelog) | 415 | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. |
| <b>[httpretty](https://github.com/henvic/httpretty) | 381 | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| <b>[logutils](https://github.com/hashicorp/logutils) | 362 | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| <b>[logxi](https://github.com/mgutz/logxi) | 352 | 12-factor app logger that is fast and makes you happy. |
| <b>[sqldb-logger](https://github.com/simukti/sqldb-logger) | 333 | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| <b>[slog](https://github.com/gookit/slog) | 321 | Lightweight, configurable, extensible logger for Go. |
| <b>[rollingwriter](https://github.com/arthurkiller/rollingWriter) | 290 | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| <b>[log](https://github.com/go-playground/log) | 289 | Simple, configurable and scalable Structured Logging for Go. |
| <b>[go-logger](https://github.com/apsdehal/go-logger) | 286 | Simple logger of Go Programs, with level handlers. |
| <b>[slog-multi](https://github.com/samber/slog-multi) | 211 | Chain of slog.Handler (pipeline, fanout...). |
| <b>[logur](https://github.com/logur/logur) | 197 | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| <b>[glg](https://github.com/kpango/glg) | 188 | glg is simple and fast leveled logging library for Go. |
| <b>[logger](https://github.com/azer/logger) | 158 | Minimalistic logging library for Go. |
| <b>[xlog](https://github.com/rs/xlog) | 138 | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| <b>[ozzo-log](https://github.com/go-ozzo/ozzo-log) | 122 | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| <b>[log-voyage](https://github.com/firstrow/logvoyage) | 94 | Full-featured logging saas written in golang. |
| <b>[slog-formatter](https://github.com/samber/slog-formatter) | 67 | Common formatters for slog and helpers to build your own. |
| <b>[go-cronowriter](https://github.com/utahta/go-cronowriter) | 56 | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| <b>[gone/log](https://github.com/One-com/gone/tree/master/log) | 47 | Fast, extendable, full-featured, std-lib source compatible log library. |
| <b>[stdlog](https://github.com/alexcesaro/log) | 47 | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| <b>[noodlog](https://github.com/gyozatech/noodlog) | 44 | Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings. |
| <b>[logex](https://github.com/chzyer/logex) | 43 | Golang log lib, supports tracking and level, wrap by standard log lib. |
| <b>[go-log](https://github.com/ian-kent/go-log) | 42 | Log4j implementation in Go. |
| <b>[gologger](https://github.com/sadlil/gologger) | 40 | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| <b>[journald](https://github.com/ssgreg/journald) | 38 | Go implementation of systemd Journal's native API for logging. |
| <b>[go-log](https://github.com/siddontang/go-log) | 33 | Log lib supports level and multi handlers. |
| <b>[mlog](https://github.com/jbrodriguez/mlog) | 33 | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| <b>[distillog](https://github.com/amoghe/distillog) | 32 | distilled levelled logging (think of it as stdlib + log levels). |
| <b>[logrusly](https://github.com/sebest/logrusly) | 28 | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| <b>[log](https://github.com/teris-io/log) | 26 | Structured log interface for Go cleanly separates logging facade from its implementation. |
| <b>[zkits-logger](https://github.com/edoger/zkits-logger) | 25 | A powerful zero-dependency JSON logger. |
| <b>[gomol](https://github.com/aphistic/gomol) | 19 | Multiple-output, structured logging for Go with extensible logging outputs. |
| <b>[logmatic](https://github.com/borderstech/logmatic) | 16 | Colorized logger for Golang with dynamic log level configuration. |
| <b>[logrusiowriter](https://github.com/cabify/logrusiowriter) | 16 | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| <b>[xylog](https://github.com/xybor-x/xylog) | 15 | Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax. |
| <b>[glo](https://github.com/lajosbencz/glo) | 15 | PHP Monolog inspired logging facility with identical severity levels. |
| <b>[zax](https://github.com/yuseferi/zax) | 14 | Integrate Context with Zap logger, which leads to more flexibility in Go logging. |
| <b>[go-log](https://github.com/subchen/go-log) | 14 | Simple and configurable Logging in Go, with level, formatters and writers. |
| <b>[log](https://github.com/heartwilltell/log) | 14 | Simple leveled logging wrapper around standard log package. |
| <b>[kemba](https://github.com/clok/kemba) | 11 | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |
| <b>[logdump](https://github.com/ewwwwwqm/logdump) | 11 | Package for multi-level logging. |
| <b>[logo](https://github.com/mbndr/logo) | 11 | Golang logger to different configurable writers. |
| <b>[go-log](https://github.com/pieterclaerhout/go-log) | 10 | A logging library with strack traces, object dumping and optional timestamps. |
| <b>[log](https://github.com/aerogo/log) | 10 | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| <b>[xlog](https://github.com/xfxdev/xlog) | 8 | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| <b>[structy/log](https://github.com/structy/log) | 5 | A simple to use log system, minimalist but with features for debugging and differentiation of messages. |
| <b>[zl](https://github.com/nkmr-jp/zl) | 4 | High Developer Experience, zap based logger. It offers rich functionality but is easy to configure. |
| <b>[slf4g](https://github.com/echocat/slf4g) | 3 | Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks. |
| <b>[log](https://github.com/no-src/log) | 3 | A simple logging framework out of the box. |
| <b>[yell](https://github.com/jfcg/yell) | 1 | Yet another minimalistic logging library. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Machine Learning

_Libraries for Machine Learning._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GoLearn](https://github.com/sjwhitworth/golearn) | 9.1k | General Machine Learning library for Go. |
| <b>[gorse](https://github.com/zhenghaoz/gorse) | 7.9k | An offline recommender system backend based on collaborative filtering written in Go. |
| <b>[gorgonia](https://github.com/gorgonia/gorgonia) | 5.2k | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| <b>[m2cgen](https://github.com/BayesWitnesses/m2cgen) | 2.7k | A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support. |
| <b>[gosseract](https://github.com/otiai10/gosseract) | 2.4k | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| <b>[tfgo](https://github.com/galeone/tfgo) | 2.3k | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| <b>[goml](https://github.com/cdipaolo/goml) | 1.5k | On-line Machine Learning in Go. |
| <b>[eaopt](https://github.com/MaxHalford/eaopt) | 869 | An evolutionary optimization library. |
| <b>[bayesian](https://github.com/jbrukh/bayesian) | 781 | Naive Bayesian Classification for Golang. |
| <b>[CloudForest](https://github.com/ryanbressler/CloudForest) | 735 | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| <b>[ocrserver](https://github.com/otiai10/ocrserver) | 631 | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| <b>[onnx-go](https://github.com/owulveryck/onnx-go) | 590 | Go Interface to Open Neural Network Exchange (ONNX). |
| <b>[gobrain](https://github.com/goml/gobrain) | 549 | Neural Networks written in go. |
| <b>[go-deep](https://github.com/patrikeh/go-deep) | 494 | A feature-rich neural network library in Go. |
| <b>[regommend](https://github.com/muesli/regommend) | 306 | Recommendation & collaborative filtering engine. |
| <b>[Goptuna](https://github.com/c-bata/goptuna) | 249 | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| <b>[goga](https://github.com/tomcraven/goga) | 205 | Genetic algorithm library for Go. |
| <b>[goRecommend](https://github.com/timkaye11/goRecommend) | 199 | Recommendation Algorithms library written in Go. |
| <b>[go-galib](https://github.com/thoj/go-galib) | 195 | Genetic Algorithms library written in Go / golang. |
| <b>[shield](https://github.com/eaigner/shield) | 155 | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| <b>[go-fann](https://github.com/white-pony/go-fann) | 115 | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| <b>[go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) | 107 | Fast and convenient feature processing for low latency machine learning in Go. |
| <b>[goscore](https://github.com/asafschers/goscore) | 93 | Go Scoring API for PMML. |
| <b>[gonet](https://github.com/dathoangnd/gonet) | 80 | Neural Network for Go. |
| <b>[fonet](https://github.com/Fontinalis/fonet) | 79 | A Deep Neural Network library written in Go. |
| <b>[libsvm](https://github.com/datastream/libsvm) | 73 | libsvm golang version derived work based on LIBSVM 3.14. |
| <b>[GoMind](https://github.com/surenderthakran/gomind) | 72 | A simplistic Neural Network Library in Go. |
| <b>[neat](https://github.com/jinyeom/neat) | 69 | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| <b>[neural-go](https://github.com/schuyler/neural-go) | 67 | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| <b>[go-pr](https://github.com/daviddengcn/go-pr) | 62 | Pattern recognition package in Go lang. |
| <b>[Varis](https://github.com/Xamber/Varis) | 53 | Golang Neural Network. |
| <b>[golinear](https://github.com/danieldk/golinear) | 44 | liblinear bindings for Go. |
| <b>[go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 40 | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| <b>[randomforest](https://github.com/malaschitz/randomForest) | 39 | Easy to use Random Forest library for Go. |
| <b>[godist](https://github.com/e-dard/godist) | 36 | Various probability distributions, and associated methods. |
| <b>[ddt](https://github.com/sgrodriguez/ddt) | 33 | Dynamic decision tree, create trees defining customizable rules. |
| <b>[evoli](https://github.com/khezen/evoli) | 28 | Genetic Algorithm and Particle Swarm Optimization library. |
| <b>[probab](https://github.com/ThePaw/probab) | 19 | Probability distribution functions. Bayesian inference. Written in pure Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Messaging

_Libraries that implement messaging systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sarama](https://github.com/Shopify/sarama) | 11.0k | Go library for Apache Kafka. |
| <b>[Asynq](https://github.com/hibiken/asynq) | 8.1k | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| <b>[Centrifugo](https://github.com/centrifugal/centrifugo) | 7.7k | Real-time messaging (Websockets or SockJS) server in Go. |
| <b>[gorush](https://github.com/appleboy/gorush) | 7.5k | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| <b>[machinery](https://github.com/RichardKnop/machinery) | 7.2k | Asynchronous task queue/job queue based on distributed message passing. |
| <b>[Benthos](https://github.com/Jeffail/benthos) | 7.1k | A message streaming bridge between a range of protocols. |
| <b>[Watermill](https://github.com/ThreeDotsLabs/watermill) | 6.5k | Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog. |
| <b>[go-socket.io](https://github.com/googollee/go-socket.io) | 5.5k | socket.io library for golang, a realtime application framework. |
| <b>[NATS Go Client](https://github.com/nats-io/nats) | 5.0k | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| <b>[Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) | 4.3k | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| <b>[Mercure](https://github.com/dunglas/mercure) | 3.7k | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| <b>[melody](https://github.com/olahol/melody) | 3.4k | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| <b>[APNs2](https://github.com/sideshow/apns2) | 2.9k | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| <b>[go-nsq](https://github.com/nsqio/go-nsq) | 2.5k | the official Go package for NSQ. |
| <b>[gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 2.1k | gopush-cluster is a go push server cluster. |
| <b>[EventBus](https://github.com/asaskevich/EventBus) | 1.6k | The lightweight event bus with async compatibility. |
| <b>[Beaver](https://github.com/Clivern/Beaver) | 1.5k | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| <b>[Uniqush-Push](https://github.com/uniqush/uniqush-push) | 1.5k | Redis backed unified push service for server-side notifications to mobile devices. |
| <b>[amqp](https://github.com/rabbitmq/amqp091-go) | 1.2k | Go RabbitMQ Client Library. |
| <b>[Chanify](https://github.com/chanify/chanify) | 1.2k | A push notification server send message to your iOS devices. |
| <b>[zmq4](https://github.com/pebbe/zmq4) | 1.1k | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| <b>[Gollum](https://github.com/trivago/gollum) | 934 | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| <b>[dbus](https://github.com/godbus/dbus) | 920 | Native Go bindings for D-Bus. |
| <b>[golongpoll](https://github.com/jcuga/golongpoll) | 644 | HTTP longpoll server library that makes web pub-sub simple. |
| <b>[mangos](https://github.com/nanomsg/mangos) | 624 | Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. |
| <b>[emitter](https://github.com/olebedev/emitter) | 489 | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| <b>[Glue](https://github.com/desertbit/glue) | 410 | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| <b>[pubsub](https://github.com/tuxychandru/pubsub) | 393 | Simple pubsub package for go. |
| <b>[Quamina](https://github.com/timbray/quamina) | 355 | Fast pattern-matching for filtering messages and events. |
| <b>[Bus](https://github.com/mustafaturan/bus) | 323 | Minimalist message bus implementation for internal communication. |
| <b>[messagebus](https://github.com/vardius/message-bus) | 262 | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| <b>[rabtap](https://github.com/jandelgado/rabtap) | 249 | RabbitMQ swiss army knife cli app. |
| <b>[guble](https://github.com/smancke/guble) | 155 | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| <b>[hub](https://github.com/leandro-lugaresi/hub) | 139 | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| <b>[redisqueue](https://github.com/robinjoseph08/redisqueue) | 118 | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| <b>[oplog](https://github.com/dailymotion/oplog) | 113 | Generic oplog/replication system for REST APIs. |
| <b>[rabbus](https://github.com/rafaeljesus/rabbus) | 97 | A tiny wrapper over amqp exchanges and queues. |
| <b>[Ratus](https://github.com/hyperonym/ratus) | 95 | Ratus is a RESTful asynchronous task queue server. |
| <b>[go-mq](https://github.com/cheshir/go-mq) | 89 | RabbitMQ client with declarative configuration. |
| <b>[drone-line](https://github.com/appleboy/drone-line) | 79 | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| <b>[nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 77 | A tiny wrapper around NSQ topic and channel. |
| <b>[go-notify](https://github.com/TheCreeper/go-notify) | 67 | Native implementation of the freedesktop notification spec. |
| <b>[RapidMQ](https://github.com/sybrexsys/RapidMQ) | 67 | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| <b>[Commander](https://github.com/jeroenrinzema/commander) | 65 | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| <b>[go-res](https://github.com/jirenius/go-res) | 62 | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| <b>[event](https://github.com/agoalofalife/event) | 54 | Implementation of the pattern observer. |
| <b>[hare](https://github.com/leozz37/hare) | 51 | A user friendly library for sending messages and listening to TCP sockets. |
| <b>[ami](https://github.com/kak-tus/ami) | 28 | Go client to reliable queues based on Redis Cluster Streams. |
| <b>[go-vitotrol](https://github.com/maxatome/go-vitotrol) | 23 | Client library to Viessmann Vitotrol web service. |
| <b>[gosd](https://github.com/alexsniffin/gosd) | 23 | A library for scheduling when to dispatch a message to a channel. |
| <b>[rmqconn](https://github.com/sbabiv/rmqconn) | 22 | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| <b>[jazz](https://github.com/socifi/jazz) | 18 | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| <b>[mob](https://github.com/erni27/mob) | 11 | mob is a generic-based, simple mediator / event aggregator library. It supports in-process requests / events processing. |
| <b>[gaurun-client](https://github.com/osamingo/gaurun-client) | 11 | Gaurun Client written in Go. |
| <b>[go-eventbus](https://github.com/stanipetrosyan/go-eventbus) | 1 | Simple Event Bus package for Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Microsoft Office


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[unioffice](https://github.com/unidoc/unioffice) | 4.1k | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |


<br>

[👆back to top](#catalogue-list)


<br>

### Microsoft Excel

_Libraries for working with Microsoft Excel._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[excelize](https://github.com/xuri/excelize) | 17.0k | Golang library for reading and writing Microsoft Excel&trade; (XLSX) files. |
| <b>[xlsx](https://github.com/tealeg/xlsx) | 5.7k | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| <b>[go-excel](https://github.com/szyhf/go-excel) | 182 | A simple and light reader to read a relate-db-like excel as a table. |
| <b>[xlsx](https://github.com/plandem/xlsx) | 171 | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| <b>[exl](https://github.com/go-the-way/exl) | 24 | Excel binding to struct written in Go.(Only supports Go1.18+) |
| <b>[goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 21 | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Miscellaneous


<br>

### Dependency Injection

_Libraries for working with dependency injection._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[google/wire](https://github.com/google/wire) | 12.0k | Automated Initialization in Go. |
| <b>[fx](https://github.com/uber-go/fx) | 4.9k | A dependency injection based application framework for Go (built on top of dig). |
| <b>[dig](https://github.com/uber-go/dig) | 3.6k | A reflection based dependency injection toolkit for Go. |
| <b>[do](https://github.com/samber/do) | 1.5k | A dependency injection framework based on Generics. |
| <b>[GoLobby/Container](https://github.com/golobby/container) | 519 | GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language. |
| <b>[goioc/di](https://github.com/goioc/di) | 315 | Spring-inspired Dependency Injection Container. |
| <b>[di](https://github.com/goava/di) | 218 | A dependency injection container for go programming language. |
| <b>[dingo](https://github.com/i-love-flamingo/dingo) | 171 | A dependency injection toolkit for Go, based on Guice. |
| <b>[alice](https://github.com/magic003/alice) | 51 | Additive dependency injection container for Golang. |
| <b>[wire](https://github.com/Fs02/wire) | 38 | Strict Runtime Dependency Injection for Golang. |
| <b>[linker](https://github.com/logrange/linker) | 35 | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| <b>[nject](https://github.com/muir/nject) | 28 | A type safe, reflective framework for libraries, tests, http endpoints, and service startup. |
| <b>[gocontainer](https://github.com/vardius/gocontainer) | 19 | Simple Dependency Injection Container. |
| <b>[gontainer](https://github.com/NVIDIA/gontainer) | 18 | A dependency injection service container for Go projects. |
| <b>[gontainer/gontainer](https://github.com/gontainer/gontainer) | 12 | A YAML-based Dependency Injection container for GO. It supports dependencies' scopes, and auto-detection of circular dependencies. Gontainer is concurrent-safe. |
| <b>[kinit](https://github.com/go-kata/kinit) | 9 | Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization. |
| <b>[HnH/di](https://github.com/HnH/di) | 7 | DI container library that is focused on clean API and flexibility. |
| <b>[boot-go](http://github.com/boot-go/boot) | 0 | Component-based development with dependency injection using reflections for Go developers. |


<br>

[👆back to top](#catalogue-list)


<br>

### Project Layout

_**Unofficial** set of patterns for structuring projects._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golang-standards/project-layout](https://github.com/golang-standards/project-layout) | 44.0k | Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful. |
| <b>[ardanlabs/service](https://github.com/ardanlabs/service) | 3.3k | A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications. |
| <b>[modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 1.7k | Go application boilerplate and example applying modern practices. |
| <b>[pagoda](https://github.com/mikestefanello/pagoda) | 1.2k | Rapid, easy full-stack web development starter kit built in Go. |
| <b>[nunu](https://github.com/go-nunu/nunu) | 972 | Nunu is a scaffolding tool for building Go applications. |
| <b>[cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 654 | A Go application boilerplate template for quick starting projects following production best practices. |
| <b>[golang-templates/seed](https://github.com/golang-templates/seed) | 427 | Go application GitHub repository template. |
| <b>[go-starter](https://github.com/allaboutapps/go-starter) | 407 | An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers. |
| <b>[go-todo-backend](https://github.com/Fs02/go-todo-backend) | 289 | Go Todo Backend example using modular project layout for product microservice. |
| <b>[scaffold](https://github.com/catchplay/scaffold) | 146 | Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. |
| <b>[go-sample](https://github.com/zitryss/go-sample) | 126 | A sample layout for Go application projects with the real code. |
| <b>[gobase](https://github.com/wajox/gobase) | 52 | A simple skeleton for golang application with basic setup for real golang application. |
| <b>[wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) | 23 | Set of practices and discussions on how to structure Go project layout. |
| <b>[go-module](https://github.com/octomation/go-module) | 22 | Template for a typical module written on Go. |
| <b>[insidieux/inizio](https://github.com/insidieux/inizio) | 17 | Golang project layout generator with plugins. |


<br>

[👆back to top](#catalogue-list)


<br>

### Strings

_Libraries for working with strings._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[xstrings](https://github.com/huandu/xstrings) | 1.3k | Collection of useful string functions ported from other languages. |
| <b>[sttr](https://github.com/abhimanyu003/sttr) | 774 | cross-platform, cli app to perform various operations on string. |
| <b>[strutil](https://github.com/ozgio/strutil) | 199 | String utilities. |
| <b>[gobeam/Stringy](https://github.com/gobeam/Stringy) | 196 | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| <b>[caps](https://github.com/chanced/caps) | 50 | A case conversion library. |
| <b>[bexp](https://github.com/happy-sdk/happy-go/tree/main/strings/bexp) | 17 | Go implementation of Brace Expansion mechanism to generate arbitrary strings. |
| <b>[bexp](https://github.com/mkungla/bexp) | 0 | Go implementation of Brace Expansion mechanism to generate arbitrary strings. |
| <b>[go-formatter](https://gitlab.com/tymonx/go-formatter) | - | Implements **replacement fields** surrounded by curly braces `{}` format strings. |


<br>

[👆back to top](#catalogue-list)


<br>

### Uncategorized

_These libraries were placed here because none of the other categories seemed to fit._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopsutil](https://github.com/shirou/gopsutil) | 9.8k | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| <b>[gatus](https://github.com/TwinProduction/gatus) | 4.4k | Automated service health dashboard. |
| <b>[archiver](https://github.com/mholt/archiver) | 4.2k | Library and command for making and extracting .zip and .tar.gz archives. |
| <b>[gofakeit](https://github.com/brianvoe/gofakeit) | 4.0k | Random data generator written in go. |
| <b>[base64Captcha](https://github.com/mojocn/base64Captcha) | 1.9k | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| <b>[go-resiliency](https://github.com/eapache/go-resiliency) | 1.9k | Resiliency patterns for golang. |
| <b>[gosms](https://github.com/haxpax/gosms) | 1.4k | Your own local SMS gateway in Go that can be used to send SMS. |
| <b>[go-commons-pool](https://github.com/jolestar/go-commons-pool) | 1.2k | Generic object pool for Golang. |
| <b>[llvm](https://github.com/llir/llvm) | 1.1k | Library for interacting with LLVM IR in pure Go. |
| <b>[shortid](https://github.com/teris-io/shortid) | 907 | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| <b>[shoutrrr](https://github.com/containrrr/shoutrrr) | 806 | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| <b>[stateless](https://github.com/qmuntal/stateless) | 746 | A fluent library for creating state machines. |
| <b>[health](https://github.com/alexliesenfeld/health) | 730 | A simple and flexible health check library for Go. |
| <b>[health](https://github.com/dimiro1/health) | 448 | Easy to use, extensible health check library. |
| <b>[banner](https://github.com/dimiro1/banner) | 443 | Add beautiful banners into your Go applications. |
| <b>[xz](https://github.com/ulikunitz/xz) | 439 | Pure golang package for reading and writing xz-compressed files. |
| <b>[gountries](https://github.com/pariz/gountries) | 401 | Package that exposes country and subdivision data. |
| <b>[conv](https://github.com/cstockton/go-conv) | 385 | Package conv provides fast and intuitive conversions across Go types. |
| <b>[lk](https://github.com/hyperboloide/lk) | 338 | A simple licensing library for golang. |
| <b>[ffmt](https://github.com/go-ffmt/ffmt) | 302 | Beautify data display for Humans. |
| <b>[go-unarr](https://github.com/gen2brain/go-unarr) | 266 | Decompression library for RAR, TAR, ZIP and 7z archives. |
| <b>[healthcheck](https://github.com/etherlabsio/healthcheck) | 258 | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| <b>[antch](https://github.com/antchfx/antch) | 255 | A fast, powerful and extensible web crawling & scraping framework. |
| <b>[battery](https://github.com/distatus/battery) | 235 | Cross-platform, normalized battery information library. |
| <b>[bitio](https://github.com/icza/bitio) | 228 | Highly optimized bit-level Reader and Writer for Go. |
| <b>[gtree](https://github.com/ddddddO/gtree) | 179 | Provide CLI and Package for tree output and directories creation from Markdown or programmatically. |
| <b>[stats](https://github.com/go-playground/stats) | 170 | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| <b>[turtle](https://github.com/hackebrot/turtle) | 155 | Emojis for Go. |
| <b>[captcha](https://github.com/steambap/captcha) | 139 | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| <b>[gotoprom](https://github.com/cabify/gotoprom) | 109 | Type-safe metrics builder wrapper library for the official Prometheus client. |
| <b>[gommit](https://github.com/antham/gommit) | 108 | Analyze git commit messages to ensure they follow defined patterns. |
| <b>[indigo](https://github.com/osamingo/indigo) | 107 | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| <b>[faker](https://github.com/pioz/faker) | 87 | Random fake data and struct generator for Go. |
| <b>[morse](https://github.com/alwindoss/morse) | 79 | Library to convert to and from morse code. |
| <b>[persian](https://github.com/mavihq/persian) | 79 | Some utilities for Persian language in go. |
| <b>[pdfgen](https://github.com/hyperboloide/pdfgen) | 67 | HTTP service to generate PDF from Json requests. |
| <b>[xkg](https://github.com/go-xkg/xkg) | 56 | X Keyboard Grabber. |
| <b>[datacounter](https://github.com/miolini/datacounter) | 47 | Go counters for readers/writer/http.ResponseWriter. |
| <b>[browscap_go](https://github.com/digitalcrab/browscap_go) | 46 | GoLang Library for [Browser Capabilities Project](https://browscap.org/). |
| <b>[url-shortener](https://github.com/pantrif/url-shortener) | 44 | A modern, powerful, and robust URL shortener microservice with mysql support. |
| <b>[sandid](https://github.com/aofei/sandid) | 42 | Every grain of sand on earth has its own ID. |
| <b>[autoflags](https://github.com/artyom/autoflags) | 39 | Go package to automatically define command line flags from struct fields. |
| <b>[xdg](https://github.com/rkoesters/xdg) | 37 | FreeDesktop.org (xdg) Specs implemented in Go. |
| <b>[gosh](https://github.com/osamingo/gosh) | 35 | Provide Go Statistics Handler, Struct, Measure Method. |
| <b>[metrics](https://github.com/pascaldekloe/metrics) | 27 | Library for metrics instrumentation and Prometheus exposition. |
| <b>[shellwords](https://github.com/Wing924/shellwords) | 21 | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| <b>[numa](https://github.com/lrita/numa) | 19 | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |
| <b>[avgRating](https://github.com/kirillDanshin/avgRating) | 16 | Calculate average score and rating based on Wilson Score Equation. |
| <b>[anagent](https://github.com/mudler/anagent) | 15 | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| <b>[hostutils](https://github.com/Wing924/hostutils) | 12 | A golang library for packing and unpacking FQDNs list. |
| <b>[go-commandbus](https://github.com/lana/go-commandbus) | 11 | A slight and pluggable command-bus for Go. |
| <b>[varint](https://github.com/chmike/varint) | 11 | A faster varying length integer encoder/decoder than the one provided in the standard library. |
| <b>[faker](https://github.com/neotoolkit/faker) | 10 | Fake data generator. |
| <b>[openapi](https://github.com/neotoolkit/openapi) | 10 | OpenAPI 3.x parser. |
| <b>[basexx](https://github.com/bobg/basexx) | 5 | Convert to, from, and between digit strings in various number bases. |
| <b>[VarHandler](https://github.com/azr/generators/tree/master/varhandler) | 5 | Generate boilerplate http input and output handling. |
| <b>[common](https://github.com/kubeservice-stack/common) | 4 | A library for server framework. |
| <b>[sitemap-format](https://github.com/mingard/sitemap-format) | 4 | A simple sitemap generator, with a little syntactic sugar. |
| <b>[go-openapi](https://github.com/go-openapi) | - | Collection of packages to parse and utilize open-api schemas. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Natural Language Processing

_Libraries for working with human languages._


<br>

### Language Detection


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[whatlanggo](https://github.com/abadojack/whatlanggo) | 612 | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| <b>[getlang](https://github.com/rylans/getlang) | 163 | Fast natural language detection package. |
| <b>[guesslanguage](https://github.com/endeveit/guesslanguage) | 57 | Functions to determine the natural language of a unicode text. |
| <b>[detectlanguage](https://github.com/detectlanguage/detectlanguage-go) | 24 | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |


<br>

[👆back to top](#catalogue-list)


<br>

### Morphological Analyzers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[spaGO](https://github.com/nlpodyssey/spago) | 1.7k | Self-contained Machine Learning and Natural Language Processing library in Go. |
| <b>[kagome](https://github.com/ikawaha/kagome) | 770 | JP morphological analyzer written in pure Go. |
| <b>[nlp](https://github.com/james-bowman/nlp) | 428 | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| <b>[nlp](https://github.com/Shixzie/nlp) | 385 | Extract values from strings and fill your structs with nlp. |
| <b>[RAKE.go](https://github.com/afjoseph/RAKE.Go) | 107 | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| <b>[go-stem](https://github.com/agonopol/go-stem) | 76 | Implementation of the porter stemming algorithm. |
| <b>[go2vec](https://github.com/danieldk/go2vec) | 50 | Reader and utility functions for word2vec embeddings. |
| <b>[porter2](https://github.com/zhenjl/porter2) | 46 | Really fast Porter 2 stemmer. |
| <b>[govader](https://github.com/jonreiter/govader) | 38 | Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). |
| <b>[snowball](https://github.com/goodsign/snowball) | 36 | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| <b>[paicehusk](https://github.com/rookii/paicehusk) | 29 | Golang implementation of the Paice/Husk Stemming Algorithm. |
| <b>[golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 20 | Go bindings for the snowball libstemmer library including porter 2. |
| <b>[libtextcat](https://github.com/goodsign/libtextcat) | 13 | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| <b>[porter](https://github.com/a2800276/porter) | 12 | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| <b>[gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) | 10 | Sentiment analyzer using sentiwordnet lexicon in Go. |
| <b>[govader-backend](https://github.com/PIMPfiction/govader_backend) | 6 | Microservice implementation of [GoVader](https://github.com/jonreiter/govader). |
| <b>[spelling-corrector](https://github.com/jorelosorio/spellingcorrector) | 2 | A spelling corrector for the Spanish language or create your own. |


<br>

[👆back to top](#catalogue-list)


<br>

### Slugifiers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[slug](https://github.com/gosimple/slug) | 1.1k | URL-friendly slugify with multiple languages support. |
| <b>[go-slugify](https://github.com/mozillazg/go-slugify) | 88 | Make pretty slug with multiple languages support. |
| <b>[Slugify](https://github.com/avelino/slugify) | 32 | Go slugify application that handles string. |


<br>

[👆back to top](#catalogue-list)


<br>

### Tokenizers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[prose](https://github.com/jdkato/prose) | 3.0k | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| <b>[gse](https://github.com/go-ego/gse) | 2.4k | Go efficient text segmentation; support english, chinese, japanese and other. |
| <b>[gojieba](https://github.com/yanyiwu/gojieba) | 2.3k | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| <b>[sentences](https://github.com/neurosnap/sentences) | 401 | Sentence tokenizer:  converts text into a list of sentences. |
| <b>[segment](https://github.com/blevesearch/segment) | 84 | Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/) |
| <b>[textcat](https://github.com/pebbe/textcat) | 71 | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| <b>[MMSEGO](https://github.com/awsong/MMSEGO) | 62 | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| <b>[stemmer](https://github.com/dchest/stemmer) | 50 | Stemmer packages for Go programming language. Includes English and German stemmers. |
| <b>[gotokenizer](https://github.com/xujiajun/gotokenizer) | 18 | A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) |
| <b>[shamoji](https://github.com/osamingo/shamoji) | 13 | The shamoji is word filtering package written in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Translation


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-i18n](https://github.com/nicksnyder/go-i18n/) | 2.7k | Package and an accompanying tool to work with localized text. |
| <b>[go-pinyin](https://github.com/mozillazg/go-pinyin) | 1.5k | CN Hanzi to Hanyu Pinyin converter. |
| <b>[gotext](https://github.com/leonelquinteros/gotext) | 413 | GNU gettext utilities for Go. |
| <b>[go-localize](https://github.com/m1/go-localize) | 58 | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| <b>[iuliia-go](https://github.com/mehanizm/iuliia-go) | 43 | Transliterate Cyrillic → Latin in every possible way. |
| <b>[go-mystem](https://github.com/dveselov/mystem) | 32 | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| <b>[spreak](https://github.com/vorlif/spreak) | 30 | Flexible translation and humanization library for Go, based on the concepts behind gettext. |
| <b>[icu](https://github.com/goodsign/icu) | 21 | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| <b>[t](https://github.com/youthlin/t) | 17 | Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template. |


<br>

[👆back to top](#catalogue-list)


<br>

### Transliteration


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-unidecode](https://github.com/mozillazg/go-unidecode) | 118 | ASCII transliterations of Unicode text. |
| <b>[gounidecode](https://github.com/fiam/gounidecode) | 79 | Unicode transliterator (also known as unidecode) for Go. |
| <b>[transliterator](https://github.com/alexsergivan/transliterator) | 38 | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| <b>[enca](https://github.com/endeveit/enca) | 16 | Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Networking

_Libraries for working with various layers of the network._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fasthttp](https://github.com/valyala/fasthttp) | 21.0k | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| <b>[kcptun](https://github.com/xtaci/kcptun) | 14.0k | Extremely simple & fast udp tunnel based on KCP protocol. |
| <b>[webrtc](https://github.com/pions/webrtc) | 12.0k | A pure Go implementation of the WebRTC API. |
| <b>[quic-go](https://github.com/lucas-clemente/quic-go) | 9.2k | An implementation of the QUIC protocol in pure Go. |
| <b>[gnet](https://github.com/panjf2000/gnet) | 8.4k | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| <b>[dns](https://github.com/miekg/dns) | 7.6k | Go library for working with DNS. |
| <b>[gopacket](https://github.com/google/gopacket) | 6.0k | Go library for packet processing with libpcap bindings. |
| <b>[HTTPLab](https://github.com/gchaincl/httplab) | 4.0k | HTTPLabs let you inspect HTTP requests and forge responses. |
| <b>[kcp-go](https://github.com/xtaci/kcp-go) | 3.9k | KCP - Fast and Reliable ARQ Protocol. |
| <b>[netpoll](https://github.com/cloudwego/netpoll) | 3.8k | A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance. |
| <b>[gobgp](https://github.com/osrg/gobgp) | 3.4k | BGP implemented in the Go Programming Language. |
| <b>[ssh](https://github.com/gliderlabs/ssh) | 3.3k | Higher-level API for building SSH servers (wraps crypto/ssh). |
| <b>[fortio](https://github.com/fortio/fortio) | 3.1k | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| <b>[nbio](https://github.com/lesismal/nbio) | 1.9k | Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. |
| <b>[water](https://github.com/songgao/water) | 1.8k | Simple TUN/TAP library. |
| <b>[gev](https://github.com/Allenxuxu/gev) | 1.7k | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| <b>[go-getter](https://github.com/hashicorp/go-getter) | 1.5k | Go library for downloading files or directories from various sources using a URL. |
| <b>[sftp](https://github.com/pkg/sftp) | 1.4k | Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>. |
| <b>[grab](https://github.com/cavaliercoder/grab) | 1.3k | Go package for managing file downloads. |
| <b>[NFF-Go](https://github.com/intel-go/nff-go) | 1.3k | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| <b>[ftp](https://github.com/jlaffaye/ftp) | 1.2k | Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959). |
| <b>[mdns](https://github.com/hashicorp/mdns) | 1.1k | Simple mDNS (Multicast DNS) client/server library in Golang. |
| <b>[gosnmp](https://github.com/soniah/gosnmp) | 1000 | Native Go library for performing SNMP actions. |
| <b>[gmqtt](https://github.com/DrmagicE/gmqtt) | 944 | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| <b>[vssh](https://github.com/yahoo/vssh) | 926 | Go library for building network and server automation over SSH protocol. |
| <b>[gws](https://github.com/lxzan/gws) | 886 | High-Performance WebSocket Server & Client With AsyncIO Supporting . |
| <b>[cidranger](https://github.com/yl2chen/cidranger) | 871 | Fast IP to CIDR lookup for Go. |
| <b>[easytcp](https://github.com/DarthPestilane/easytcp) | 781 | A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful. |
| <b>[lhttp](https://github.com/fanux/lhttp) | 690 | Powerful websocket framework, build your IM server more easily. |
| <b>[go-stun](https://github.com/ccding/go-stun) | 618 | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| <b>[peerdiscovery](https://github.com/schollz/peerdiscovery) | 617 | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| <b>[gaio](https://github.com/xtaci/gaio) | 541 | High performance async-io networking for Golang in proactor mode. |
| <b>[gotcp](https://github.com/gansidui/gotcp) | 509 | Go package for quickly writing tcp applications. |
| <b>[stun](https://github.com/go-rtc/stun) | 487 | Go implementation of RFC 5389 STUN protocol. |
| <b>[gopcap](https://github.com/akrennmair/gopcap) | 481 | Go wrapper for libpcap. |
| <b>[tcp_server](https://github.com/firstrow/tcp_server) | 424 | Go library for building tcp servers faster. |
| <b>[raw](https://github.com/mdlayher/raw) | 422 | Package raw enables reading and writing data at the device driver level for a network interface. |
| <b>[winrm](https://github.com/masterzen/winrm) | 411 | Go WinRM client to remotely execute commands on Windows machines. |
| <b>[ftpserverlib](https://github.com/fclairamb/ftpserverlib) | 384 | Fully featured FTP server library. |
| <b>[arp](https://github.com/mdlayher/arp) | 348 | Package arp implements the ARP protocol, as described in RFC 826. |
| <b>[dnsmonster](https://github.com/mosajjal/dnsmonster) | 292 | Passive DNS Capture/Monitoring Framework. |
| <b>[ethernet](https://github.com/mdlayher/ethernet) | 270 | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| <b>[buffstreams](https://github.com/stabbycutyou/buffstreams) | 254 | Streaming protocolbuffer data over TCP made easy. |
| <b>[gNxI](https://github.com/google/gnxi) | 247 | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| <b>[jazigo](https://github.com/udhos/jazigo) | 205 | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| <b>[tcpack](https://github.com/lim-yoona/tcpack) | 175 | tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program. |
| <b>[utp](https://github.com/anacrolix/utp) | 172 | Go uTP micro transport protocol implementation. |
| <b>[event](https://github.com/cheng-zhongliang/event) | 153 | Simple I/O event notification library written in Golang. |
| <b>[canopus](https://github.com/zubairhamed/canopus) | 153 | CoAP Client/Server implementation (RFC 7252). |
| <b>[xtcp](https://github.com/xfxdev/xtcp) | 148 | TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. |
| <b>[sslb](https://github.com/eduardonunesp/sslb) | 145 | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| <b>[iplib](https://github.com/c-robinson/iplib) | 128 | Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html) |
| <b>[gldap](https://github.com/jimlambrt/gldap) | 105 | gldap provides an ldap server implementation and you provide handlers for its ldap operations. |
| <b>[ether](https://github.com/songgao/ether) | 80 | Cross-platform Go package for sending and receiving ethernet frames. |
| <b>[packet](https://github.com/aerogo/packet) | 77 | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| <b>[dhcp6](https://github.com/mdlayher/dhcp6) | 76 | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| <b>[go-powerdns](https://github.com/joeig/go-powerdns) | 76 | PowerDNS API bindings for Golang. |
| <b>[fullproxy](https://github.com/shoriwe/fullproxy) | 68 | A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols. |
| <b>[portproxy](https://github.com/aybabtme/portproxy) | 53 | Simple TCP proxy which adds CORS support to API's which don't support it. |
| <b>[linkio](https://github.com/ian-kent/linkio) | 52 | Network link speed simulation for Reader/Writer interfaces. |
| <b>[panoptes-stream](https://github.com/yahoo/panoptes-stream) | 40 | A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT). |
| <b>[golibwireshark](https://github.com/sunwxg/golibwireshark) | 29 | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| <b>[graval](https://github.com/koofr/graval) | 28 | Experimental FTP server framework. |
| <b>[publicip](https://github.com/polera/publicip) | 27 | Package publicip returns your public facing IPv4 address (internet egress). |
| <b>[gohooks](https://github.com/averageflow/gohooks) | 23 | GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server. |
| <b>[httpproxy](https://github.com/wzshiming/httpproxy) | 22 | HTTP proxy handler and dialer. |
| <b>[goshark](https://github.com/sunwxg/goshark) | 18 | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| <b>[llb](https://github.com/kirillDanshin/llb) | 14 | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| <b>[tspool](https://github.com/two/tspool) | 14 | A TCP Library use worker pool to improve performance and protect your server. |
| <b>[gnet](https://github.com/fish-tennis/gnet) | 12 | `gnet` is a high-performance networking framework,especially for game servers. |
| <b>[go-sse](https://github.com/lampctl/go-sse) | 6 | Go client and server implementation of HTML server-sent events. |
| <b>[mqttPaho](https://eclipse.org/paho/clients/golang/) | - | The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets. |


<br>

[👆back to top](#catalogue-list)


<br>

### HTTP Clients

_Libraries for making HTTP requests._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[resty](https://github.com/go-resty/resty) | 9.0k | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| <b>[req](https://github.com/imroc/req) | 3.9k | Simple Go HTTP client with Black Magic (Less code and More efficiency). |
| <b>[heimdall](https://github.com/gojektech/heimdall) | 2.5k | An enhanced http client with retry and hystrix capabilities. |
| <b>[grequests](https://github.com/levigross/grequests) | 2.0k | A Go "clone" of the great and famous Requests library. |
| <b>[go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) | 1.8k | Retryable HTTP client in Go. |
| <b>[sling](https://github.com/dghubble/sling) | 1.6k | Sling is a Go HTTP client library for creating and sending API requests. |
| <b>[requests](https://github.com/carlmjohnson/requests) | 1.3k | HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools. |
| <b>[gentleman](https://github.com/h2non/gentleman) | 1000 | Full-featured plugin-driven HTTP client library. |
| <b>[pester](https://github.com/sethgrid/pester) | 628 | Go HTTP client calls with retries, backoff, and concurrency. |
| <b>[go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) | 354 | Get easily stdlib HTTP client, which does not share any state with other clients. |
| <b>[request](https://github.com/monaco-io/request) | 272 | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| <b>[go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) | 75 | Go http.RoundTripper that emits open telemetry metrics for HTTP requests. |
| <b>[go-http-client](https://github.com/bozd4g/go-http-client) | 68 | Make http calls simply and easily. |
| <b>[go-zoox/fetch](https://github.com/go-zoox/fetch) | 63 | A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API. |
| <b>[rq](https://github.com/ddo/rq) | 51 | A nicer interface for golang stdlib HTTP client. |
| <b>[httpretry](https://github.com/ybbus/httpretry) | 40 | Enriches the default go HTTP client with retry functionality. |
| <b>[fast-shot](https://github.com/opus-domini/fast-shot) | 24 | Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client. |
| <b>[go-req](https://github.com/wenerme/go-req) | 22 | Declarative golang HTTP client. |
| <b>[httpc](https://github.com/valord577/httpc) | 5 | A customizable and simple HTTP client library. Only depend on the stdlib HTTP client. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## OpenGL

_Libraries for using OpenGL in Go._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[glfw](https://github.com/go-gl/glfw) | 1.5k | Go bindings for GLFW 3. |
| <b>[gl](https://github.com/go-gl/gl) | 1000 | Go bindings for OpenGL (generated via glow). |
| <b>[mathgl](https://github.com/go-gl/mathgl) | 521 | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| <b>[goxjs/gl](https://github.com/goxjs/gl) | 169 | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| <b>[goxjs/glfw](https://github.com/goxjs/glfw) | 80 | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| <b>[go-glmatrix](https://github.com/technohippy/go-glmatrix) | 8 | Go port of [glMatrix](https://glmatrix.net/) library. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## ORM

_Libraries that implement Object-Relational Mapping or datamapping techniques._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GORM](https://github.com/go-gorm/gorm) | 35.0k | The fantastic ORM library for Golang, aims to be developer friendly. |
| <b>[ent](https://github.com/facebook/ent) | 15.0k | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| <b>[SQLBoiler](https://github.com/volatiletech/sqlboiler) | 6.3k | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| <b>[go-pg](https://github.com/go-pg/pg) | 5.5k | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| <b>[gorp](https://github.com/go-gorp/gorp) | 3.7k | Go Relational Persistence, ORM-ish library for Go. |
| <b>[upper.io/db](https://github.com/upper/db) | 3.4k | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| <b>[bun](https://github.com/uptrace/bun) | 2.7k | SQL-first Golang ORM. Successor of go-pg. |
| <b>[gormt](https://github.com/xxjwxc/gormt) | 2.3k | Mysql database to golang gorm struct. |
| <b>[Prisma](https://github.com/prisma/prisma-client-go) | 1.8k | Prisma Client Go, Typesafe database access for Go. |
| <b>[pop/soda](https://github.com/gobuffalo/pop) | 1.4k | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| <b>[reform](https://github.com/go-reform/reform) | 1.4k | Better ORM for Go, based on non-empty interfaces and code generation. |
| <b>[go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 1.2k | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| <b>[go-queryset](https://github.com/jirfag/go-queryset) | 717 | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| <b>[rel](https://github.com/go-rel/rel) | 713 | Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. |
| <b>[Zoom](https://github.com/albrow/zoom) | 304 | Blazing-fast datastore and querying engine built on Redis. |
| <b>[go-sql](https://github.com/rushteam/gosql) | 176 | A easy ORM for mysql. |
| <b>[grimoire](https://github.com/Fs02/grimoire) | 160 | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| <b>[golobby/orm](https://github.com/golobby/orm) | 151 | Simple, fast, type-safe, generic orm for developer happiness. |
| <b>[go-store](https://github.com/gosuri/go-store) | 112 | Simple and fast Redis backed key-value store library for Go. |
| <b>[go-firestorm](https://github.com/jschoedt/go-firestorm) | 47 | A simple ORM for Google/Firebase Cloud Firestore. |
| <b>[cacheme](https://github.com/Yiling-J/cacheme-go) | 24 | Schema based, typed Redis caching/memoize framework for Go. |
| <b>[lore](https://github.com/abrahambotros/lore) | 14 | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
| <b>[marlow](https://github.com/marlow/marlow) | 14 | Generated ORM from project structs for compile time safety assurances. |
| <b>[go-dbw](https://github.com/hashicorp/go-dbw) | 12 | A simple package that encapsulates database operations. |
| <b>[XORM](https://gitea.com/xorm/xorm) | - | Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle). |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Package Management

_Unofficial libraries for package and dependency management._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[dep](https://github.com/golang/dep) | 13.0k | Go dependency tool. |
| <b>[glide](https://github.com/Masterminds/glide) | 8.2k | Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. |
| <b>[godep](https://github.com/tools/godep) | 5.6k | dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. |
| <b>[govendor](https://github.com/kardianos/govendor) | 4.9k | Go Package Manager. Go vendor tool that works with the standard vendor file. |
| <b>[gopm](https://github.com/gpmgo/gopm) | 2.5k | Go Package Manager. |
| <b>[gom](https://github.com/mattn/gom) | 1.4k | Go Manager - bundle for go. |
| <b>[gpm](https://github.com/pote/gpm) | 1.2k | Barebones dependency manager for Go. |
| <b>[goop](https://github.com/nitrous-io/goop) | 780 | Simple dependency manager for Go (golang), inspired by Bundler. |
| <b>[modgv](https://github.com/lucasepe/modgv) | 475 | Converts 'go mod graph' output into Graphviz's DOT language. |
| <b>[gup](https://github.com/nao1215/gup) | 251 | Update binaries installed by "go install". |
| <b>[nut](https://github.com/jingweno/nut) | 234 | Vendor Go dependencies. |
| <b>[johnny-deps](https://github.com/VividCortex/johnny-deps) | 214 | Minimal dependency version using Git. |
| <b>[mvn-golang](https://github.com/raydac/mvn-golang) | 159 | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| <b>[VenGO](https://github.com/DamnWidget/VenGO) | 125 | create and manage exportable isolated go virtual environments. |
| <b>[gop](https://github.com/lunny/gop) | 50 | Build and manage your Go applications out of GOPATH. |
| <b>[go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) | - | Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules. |
| <b>[vgo](https://go.googlesource.com/vgo/) | - | Versioned Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Performance


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[jaeger](https://github.com/jaegertracing/jaeger) | 19.0k | A distributed tracing system. |
| <b>[pixie](https://github.com/pixie-labs/pixie) | 5.1k | No instrumentation tracing for Golang applications via eBPF. |
| <b>[statsviz](https://github.com/arl/statsviz) | 3.0k | Live visualization of your Go application runtime statistics. |
| <b>[profile](https://github.com/pkg/profile) | 1.9k | Simple profiling support package for Go. |
| <b>[go-instrument](https://github.com/nikolaydubina/go-instrument) | 116 | Automatically add spans to all methods and functions. |
| <b>[tracer](https://github.com/kamilsk/tracer) | 83 | Simple, lightweight tracing. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Query Language


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[graphql-go](https://github.com/graphql-go/graphql) | 9.6k | Implementation of GraphQL for Go. |
| <b>[gqlgen](https://github.com/99designs/gqlgen) | 9.4k | go generate based graphql server library. |
| <b>[dasel](https://github.com/tomwright/dasel) | 4.7k | Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. |
| <b>[graphql](https://github.com/neelance/graphql-go) | 4.6k | GraphQL server with a focus on ease of use. |
| <b>[gojsonq](https://github.com/thedevsaddam/gojsonq) | 2.1k | A simple Go package to Query over JSON Data. |
| <b>[rql](https://github.com/a8m/rql) | 321 | Resource Query Language for REST API. |
| <b>[jsonql](https://github.com/elgs/jsonql) | 272 | JSON query expression library in Golang. |
| <b>[jsonslice](https://github.com/bhmj/jsonslice) | 79 | Jsonpath queries with advanced filters. |
| <b>[rqp](https://github.com/timsolov/rest-query-parser) | 65 | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| <b>[goven](https://github.com/SeldonIO/goven) | 57 | A drop-in query language for any database schema. |
| <b>[graphql](https://github.com/tmc/graphql) | 57 | graphql parser + utilities. |
| <b>[api-fu](https://github.com/ccbrown/api-fu) | 53 | Comprehensive GraphQL implementation. |
| <b>[straf](https://github.com/SonicRoshan/straf) | 36 | Easily Convert Golang structs to GraphQL objects. |
| <b>[mql](https://github.com/hashicorp/mql) | 29 | Model Query Language (mql) is a query language for your database models. |
| <b>[jsonpath](https://github.com/AsaiYusuke/jsonpath) | 20 | A query library for retrieving part of JSON based on JSONPath syntax. |
| <b>[gws](https://github.com/Zaba505/gws) | 7 | Apollos' "GraphQL over Websocket" client and server implementation. |
| <b>[grapher](https://github.com/reaganiwadha/grapher) | 3 | A GraphQL field builder utilizing Go generics with extra utilities and features. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Resource Embedding


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[statik](https://github.com/rakyll/statik) | 3.7k | Embeds static files into a Go executable. |
| <b>[packr](https://github.com/gobuffalo/packr) | 3.4k | The simple and easy way to embed static files into Go binaries. |
| <b>[go.rice](https://github.com/GeertJohan/go.rice) | 2.4k | go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. |
| <b>[vfsgen](https://github.com/shurcooL/vfsgen) | 981 | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| <b>[esc](https://github.com/mjibson/esc) | 638 | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| <b>[fileb0x](https://github.com/UnnoTed/fileb0x) | 632 | Simple tool to embed files in go with focus on "customization" and ease to use. |
| <b>[go-resources](https://github.com/omeid/go-resources) | 176 | Unfancy resources embedding with Go. |
| <b>[statics](https://github.com/go-playground/statics) | 67 | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| <b>[templify](https://github.com/wlbr/templify) | 30 | Embed external template files into Go code to create single file binaries. |
| <b>[rebed](https://github.com/soypat/rebed) | 29 | Recreate folder structures and files from Go 1.16's `embed.FS` type |
| <b>[debme](https://github.com/leaanthony/debme) | 28 | Create an `embed.FS` from an existing `embed.FS` subdirectory. |
| <b>[mule](https://github.com/wlbr/mule) | 14 | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Science and Data Analysis

_Libraries for scientific computing and data analyzing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gonum](https://github.com/gonum/gonum) | 7.1k | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| <b>[stats](https://github.com/montanaflynn/stats) | 2.9k | Statistics package with common functions missing from the Golang standard library. |
| <b>[gonum/plot](https://github.com/gonum/plot) | 2.6k | gonum/plot provides an API for building and drawing plots in Go. |
| <b>[gosl](https://github.com/cpmech/gosl) | 1.8k | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| <b>[streamtools](https://github.com/nytlabs/streamtools) | 1.3k | general purpose, graphical tool for dealing with streams of data. |
| <b>[dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 1.1k | Dataframes for machine-learning and statistics (similar to pandas). |
| <b>[go-dsp](https://github.com/mjibson/go-dsp) | 835 | Digital Signal Processing for Go. |
| <b>[orb](https://github.com/paulmach/orb) | 787 | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| <b>[chart](https://github.com/vdobler/chart) | 763 | Simple Chart Plotting library for Go. Supports many graphs types. |
| <b>[goraph](https://github.com/gyuho/goraph) | 728 | Pure Go graph theory library(data structure, algorithm visualization). |
| <b>[graph](https://github.com/yourbasic/graph) | 672 | Library of basic graph algorithms. |
| <b>[ewma](https://github.com/VividCortex/ewma) | 424 | Exponentially-weighted moving averages. |
| <b>[calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 382 | Calendar heatmap in plain Go inspired by Github contribution activity. |
| <b>[TextRank](https://github.com/DavidBelicza/TextRank) | 191 | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| <b>[gohistogram](https://github.com/VividCortex/gohistogram) | 172 | Approximate histograms for data streams. |
| <b>[sparse](https://github.com/james-bowman/sparse) | 150 | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| <b>[go-estimate](https://github.com/milosgajdos/go-estimate) | 106 | State estimation and filtering algorithms in Go. |
| <b>[pagerank](https://github.com/alixaxel/pagerank) | 79 | Weighted PageRank algorithm implemented in Go. |
| <b>[jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) | 69 | Tool to manipulate JSONL graphs with graphviz support. |
| <b>[geom](https://github.com/skelterjohn/geom) | 55 | 2D geometry for golang. |
| <b>[evaler](https://github.com/soniah/evaler) | 52 | Simple floating point arithmetic expression evaluator. |
| <b>[gograph](https://github.com/hmdsefi/gograph) | 42 | A golang generic graph library that provides mathematical graph-theory and algorithms. |
| <b>[decimal](https://github.com/db47h/decimal) | 38 | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| <b>[triangolatte](https://github.com/tchayen/triangolatte) | 36 | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| <b>[goent](https://github.com/kzahedi/goent) | 34 | GO Implementation of Entropy Measures. |
| <b>[piecewiselinear](https://github.com/sgreben/piecewiselinear) | 26 | Tiny linear interpolation library. |
| <b>[godesim](https://github.com/soypat/godesim) | 23 | Extended/multivariable ODE solver framework for event-based simulations with simple API. |
| <b>[ode](https://github.com/ChristopherRabotin/ode) | 22 | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| <b>[GoStats](https://github.com/OGFris/GoStats) | 20 | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| <b>[PiHex](https://github.com/claygod/PiHex) | 20 | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| <b>[assocentity](https://github.com/ndabAP/assocentity) | 14 | Package assocentity returns the average distance from words to a given entity. |
| <b>[rootfinding](https://github.com/khezen/rootfinding) | 11 | root-finding algorithms library for finding roots of quadratic functions. |
| <b>[go-gt](https://github.com/ThePaw/go-gt) | 10 | Graph theory algorithms written in "Go" language. |
| <b>[bradleyterry](https://github.com/seanhagen/bradleyterry) | 9 | Provides a Bradley-Terry Model for pairwise comparisons. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Security

_Libraries that are used to help make your application more secure._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[age](https://github.com/FiloSottile/age) | 15.0k | A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. |
| <b>[lego](https://github.com/go-acme/lego) | 6.7k | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| <b>[CertMagic](https://github.com/caddyserver/certmagic) | 4.7k | Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal. |
| <b>[Cameradar](https://github.com/Ullaakut/cameradar) | 3.8k | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| <b>[memguard](https://github.com/awnumar/memguard) | 2.5k | A pure Go library for handling sensitive values in memory. |
| <b>[secure](https://github.com/unrolled/secure) | 2.2k | HTTP middleware for Go that facilitates some quick security wins. |
| <b>[acmetool](https://github.com/hlandau/acme) | 2.0k | ACME (Let's Encrypt) client tool with automatic renewal. |
| <b>[themis](https://github.com/cossacklabs/themis) | 1.8k | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| <b>[Coraza](https://github.com/corazawaf/coraza) | 1.6k | Enterprise-ready, modsecurity and OWASP CRS compatible WAF library. |
| <b>[acra](https://github.com/cossacklabs/acra) | 1.3k | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| <b>[dongle](https://github.com/golang-module/dongle) | 823 | A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption. |
| <b>[nacl](https://github.com/kevinburke/nacl) | 540 | Go implementation of the NaCL set of API's. |
| <b>[beelzebub](https://github.com/mariocandela/beelzebub) | 496 | A secure low code honeypot framework, leveraging AI for System Virtualization. |
| <b>[go-password-validator](https://github.com/lane-c-wagner/go-password-validator) | 459 | Password validator based on raw cryptographic entropy values. |
| <b>[booster](https://github.com/anatol/booster) | 425 | Fast initramfs generator with full-disk encryption support. |
| <b>[ssh-vault](https://github.com/ssh-vault/ssh-vault) | 414 | encrypt/decrypt using ssh keys. |
| <b>[optimus-go](https://github.com/pjebs/optimus-go) | 353 | ID hashing and Obfuscation using Knuth's Algorithm. |
| <b>[go-yara](https://github.com/hillu/go-yara) | 336 | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| <b>[firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 334 | A rest application to dynamically update firewalld rules on a linux server. |
| <b>[BadActor](https://github.com/jaredfolkins/badactor) | 319 | In-memory, application-driven jailer built in the spirit of fail2ban. |
| <b>[passlib](https://github.com/hlandau/passlib) | 287 | Futureproof password hashing library. |
| <b>[teler-waf](https://github.com/kitabisa/teler-waf) | 229 | teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications. |
| <b>[simple-scrypt](https://github.com/elithrar/simple-scrypt) | 191 | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| <b>[go-peer](https://github.com/number571/go-peer) | 152 | A software library for creating secure and anonymous decentralized systems. |
| <b>[argon2pw](https://github.com/raja/argon2pw) | 90 | Argon2 password hash generation with constant-time password comparison. |
| <b>[goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 58 | A probably paranoid package for securely hashing and encrypting passwords. |
| <b>[go-generate-password](https://github.com/m1/go-generate-password) | 51 | Password generator that can be used on the cli or as a library. |
| <b>[certificates](https://github.com/mvmaasakkers/certificates) | 36 | An opinionated tool for generating tls certificates. |
| <b>[go-htpasswd](https://github.com/tg123/go-htpasswd) | 33 | Apache htpasswd Parser for Go. |
| <b>[secureio](https://github.com/xaionaro-go/secureio) | 31 | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| <b>[secret](https://github.com/rsjethani/secret) | 24 | Prevent your secrets from leaking into logs, std* etc. |
| <b>[sslmgr](https://github.com/adrianosela/sslmgr) | 22 | SSL certificates made easy with a high level wrapper around acme/autocert. |
| <b>[argon2-hashing](https://github.com/andskur/argon2-hashing) | 20 | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| <b>[goArgonPass](https://github.com/dwin/goArgonPass) | 16 | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
| <b>[passwap](https://github.com/zitadel/passwap) | 14 | Provides a unified implementation between different password hashing algorithms |
| <b>[Interpol](https://github.com/avahidi/interpol) | 2 | Rule-based data generator for fuzzing and penetration testing. |
| <b>[autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) | - | Auto provision Let's Encrypt certificates and start a TLS server. |
| <b>[Interpol](https://bitbucket.org/vahidi/interpol) | - | Rule-based data generator for fuzzing and penetration testing. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Serialization

_Libraries and tools for binary serialization._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[jsoniter](https://github.com/json-iterator/go) | 13.0k | High-performance 100% compatible drop-in replacement of "encoding/json". |
| <b>[goprotobuf](https://github.com/golang/protobuf) | 9.4k | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| <b>[mapstructure](https://github.com/mitchellh/mapstructure) | 7.5k | Go library for decoding generic map values into native Go structures. |
| <b>[gogoprotobuf](https://github.com/gogo/protobuf) | 5.6k | Protocol Buffers for Go with Gadgets. |
| <b>[go-codec](https://github.com/ugorji/go) | 1.8k | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| <b>[csvutil](https://github.com/jszwec/csvutil) | 863 | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| <b>[colfer](https://github.com/pascaldekloe/colfer) | 728 | Code generation for the Colfer binary format. |
| <b>[cbor](https://github.com/fxamacker/cbor) | 641 | Small, safe, and easy CBOR encoding and decoding library. |
| <b>[go-capnproto](https://github.com/glycerine/go-capnproto) | 288 | Cap'n Proto library and parser for go. |
| <b>[php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 160 | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| <b>[structomap](https://github.com/tuvistavie/structomap) | 144 | Library to easily and dynamically generate maps from static structures. |
| <b>[binstruct](https://github.com/ghostiam/binstruct) | 82 | Golang binary decoder for mapping data into the structure. |
| <b>[bambam](https://github.com/glycerine/bambam) | 67 | generator for Cap'n Proto schemas from go. |
| <b>[asn1](https://github.com/PromonLogicalis/asn1) | 53 | Asn.1 BER and DER encoding library for golang. |
| <b>[bel](https://github.com/32leaves/bel) | 35 | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| <b>[fwencoder](https://github.com/o1egl/fwencoder) | 26 | Fixed width file parser (encoding and decoding library) for Go. |
| <b>[elastic](https://github.com/epiclabs-io/elastic) | 24 | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| <b>[pletter](https://github.com/vimeda/pletter) | 19 | A standard way to wrap a proto message for message brokers. |
| <b>[gotiny](https://github.com/raszia/gotiny) | 15 | Efficient Go serialization library, gotiny is almost as fast as serialization libraries that generate code. |
| <b>[fixedwidth](https://github.com/huydang284/fixedwidth) | 9 | Fixed-width text formatting (UTF-8 supported). |
| <b>[unitpacking](https://github.com/recolude/unitpacking) | 6 | Library to pack unit vectors into as fewest bytes as possible. |
| <b>[go-lctree](https://github.com/sbourlon/go-lctree) | 4 | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Server Applications


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Caddy](https://github.com/caddyserver/caddy) | 52.0k | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| <b>[etcd](https://github.com/etcd-io/etcd) | 46.0k | Highly-available key value store for shared configuration and service discovery. |
| <b>[etcd](https://github.com/coreos/etcd) | 46.0k | Highly-available key value store for shared configuration and service discovery. |
| <b>[minio](https://github.com/minio/minio) | 43.0k | Minio is a distributed object storage server. |
| <b>[RoadRunner](https://github.com/spiral/roadrunner) | 7.6k | High-performance PHP application server, load-balancer and process manager. |
| <b>[SFTPGo](https://github.com/drakkan/sftpgo) | 7.6k | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| <b>[Easegress](https://github.com/megaease/easegress) | 5.7k | A cloud native high availability/performance traffic orchestration system with observability and extensibility. |
| <b>[devd](https://github.com/cortesi/devd) | 3.4k | Local webserver for developers. |
| <b>[flipt](https://github.com/markphelps/flipt) | 3.1k | A self contained feature flag solution written in Go and Vue.js |
| <b>[algernon](https://github.com/xyproto/algernon) | 2.6k | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| <b>[Wish](https://github.com/charmbracelet/wish) | 2.6k | Make SSH apps, just like that! |
| <b>[Fider](https://github.com/getfider/fider) | 2.5k | Fider is an open platform to collect and organize customer feedback. |
| <b>[Flagr](https://github.com/checkr/flagr) | 2.3k | Flagr is an open-source feature flagging and A/B testing service. |
| <b>[Trickster](https://github.com/tricksterproxy/trickster) | 1.9k | HTTP reverse proxy cache and time series accelerator. |
| <b>[discovery](https://github.com/Bilibili/discovery) | 1.8k | A registry for resilient mid-tier load balancing and failover. |
| <b>[jackal](https://github.com/ortuman/jackal) | 1.4k | An XMPP server written in Go. |
| <b>[go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) | 990 | A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it. |
| <b>[Euterpe](https://github.com/ironsmile/euterpe) | 511 | Self-hosted music streaming server with built-in web UI and REST API. |
| <b>[dummy](https://github.com/neotoolkit/dummy) | 177 | Run mock server based off an API contract with one command. |
| <b>[dudeldu](https://github.com/krotik/dudeldu) | 144 | A simple SHOUTcast server. |
| <b>[go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) | 110 | Simple Reverse Proxy with Caching, written in Go, using Redis. |
| <b>[cortex-tenant](https://github.com/blind-oracle/cortex-tenant) | 86 | Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels. |
| <b>[lets-proxy2](https://github.com/rekby/lets-proxy2) | 84 | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| <b>[psql-streamer](https://github.com/blind-oracle/psql-streamer) | 56 | Stream database events from PostgreSQL to Kafka. |
| <b>[nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 39 | Nginx log parser and exporter to Prometheus. |
| <b>[simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) | 37 | Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management. |
| <b>[protoxy](https://github.com/camgraff/protoxy) | 34 | A proxy server that converts JSON request bodies to Protocol Buffers. |
| <b>[Moxy](https://github.com/sinhashubham95/moxy) | 12 | Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint. |
| <b>[riemann-relay](https://github.com/blind-oracle/riemann-relay) | 2 | Relay to load-balance Riemann events and/or convert them to Carbon. |
| <b>[consul](https://www.consul.io/) | - | Consul is a tool for service discovery, monitoring and configuration. |
| <b>[nsq](https://nsq.io/) | - | A realtime distributed messaging platform. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Stream Processing

_Libraries and tools for stream processing and reactive programming._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-streams](https://github.com/reugn/go-streams) | 1.7k | Go stream processing library. |
| <b>[machine](https://github.com/whitaker-io/machine) | 142 | Go library for writing and generating stream workers with built in metrics and traceability. |
| <b>[stream](https://github.com/youthlin/stream) | 84 | Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... |
| <b>[goio](https://github.com/primetalk/goio) | 77 | An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Template Engines

_Libraries and tools for templating and lexing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[templ](https://github.com/a-h/templ) | 5.2k | A HTML templating language that has great developer tooling. |
| <b>[sprig](https://github.com/Masterminds/sprig) | 3.9k | Useful template functions for Go templates. |
| <b>[quicktemplate](https://github.com/valyala/quicktemplate) | 3.0k | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| <b>[pongo2](https://github.com/flosch/pongo2) | 2.7k | Django-like template-engine for Go. |
| <b>[maroto](https://github.com/johnfercher/maroto) | 1.4k | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| <b>[jet](https://github.com/CloudyKit/jet) | 1.1k | Jet template engine. |
| <b>[Razor](https://github.com/sipin/gorazor) | 837 | Razor view engine for Golang. |
| <b>[fasttemplate](https://github.com/valyala/fasttemplate) | 788 | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/). |
| <b>[ego](https://github.com/benbjohnson/ego) | 576 | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| <b>[raymond](https://github.com/aymerick/raymond) | 573 | Complete handlebars implementation in Go. |
| <b>[goview](https://github.com/foolin/goview) | 394 | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| <b>[liquid](https://github.com/osteele/liquid) | 252 | Go implementation of Shopify Liquid templates. |
| <b>[Soy](https://github.com/robfig/soy) | 173 | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| <b>[extemplate](https://github.com/dannyvankooten/extemplate) | 56 | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| <b>[gospin](https://github.com/m1/gospin) | 53 | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |
| <b>[got](https://github.com/goradd/got) | 25 | A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more. |
| <b>[tbd](https://github.com/lucasepe/tbd) | 25 | A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Testing

_Libraries for testing codebases and generating test data._


<br>

### Testing Frameworks


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Testify](https://github.com/stretchr/testify) | 21.0k | Sacred extension to the standard go testing package. |
| <b>[GoConvey](https://github.com/smartystreets/goconvey/) | 8.0k | BDD-style framework with web UI and live reload. |
| <b>[go-cmp](https://github.com/google/go-cmp) | 3.9k | Package for comparing Go values in tests. |
| <b>[httpexpect](https://github.com/gavv/httpexpect) | 2.4k | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| <b>[godog](https://github.com/DATA-DOG/godog) | 2.1k | Cucumber or Behat like BDD framework for Go. |
| <b>[is](https://github.com/matryer/is) | 1.7k | Professional lightweight testing mini-framework for Go. |
| <b>[gnomock](https://github.com/orlangure/gnomock) | 1.3k | integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. |
| <b>[go-vcr](https://github.com/dnaeon/go-vcr) | 1.1k | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| <b>[testfixtures](https://github.com/go-testfixtures/testfixtures) | 1000 | A helper for Rails' like test fixtures to test database applications. |
| <b>[goblin](https://github.com/franela/goblin) | 887 | Mocha like testing framework fo Go. |
| <b>[baloo](https://github.com/h2non/baloo) | 770 | Expressive and versatile end-to-end HTTP API testing made easy. |
| <b>[goc](https://github.com/qiniu/goc) | 746 | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| <b>[embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 695 | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| <b>[go-mutesting](https://github.com/zimmski/go-mutesting) | 615 | Mutation testing for Go source code. |
| <b>[gotest.tools](https://github.com/gotestyourself/gotest.tools) | 478 | A collection of packages to augment the go testing package and support common patterns. |
| <b>[gofight](https://github.com/appleboy/gofight) | 437 | API Handler Testing for Golang Router framework. |
| <b>[testza](https://github.com/MarvinJWendt/testza) | 416 | Full-featured test framework with nice colorized output. |
| <b>[go-testdeep](https://github.com/maxatome/go-testdeep) | 411 | Extremely flexible golang deep comparison, extends the go testing package. |
| <b>[cupaloy](https://github.com/bradleyjkemp/cupaloy) | 283 | Simple snapshot testing addon for your test framework. |
| <b>[frisby](https://github.com/verdverm/frisby) | 276 | REST API testing framework. |
| <b>[got](https://github.com/ysmood/got) | 263 | An enjoyable golang test framework. |
| <b>[endly](https://github.com/viant/endly) | 250 | Declarative end to end functional testing. |
| <b>[go-hit](https://github.com/Eun/go-hit) | 242 | Hit is an http integration test framework written in golang. |
| <b>[go-carpet](https://github.com/msoap/go-carpet) | 240 | Tool for viewing test coverage in terminal. |
| <b>[commander](https://github.com/SimonBaeumer/commander) | 217 | Tool for testing cli applications on windows, linux and osx. |
| <b>[charlatan](https://github.com/percolate/charlatan) | 200 | Tool to generate fake interface implementations for tests. |
| <b>[dbcleaner](https://github.com/khaiql/dbcleaner) | 157 | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| <b>[jsonassert](https://github.com/kinbiko/jsonassert) | 116 | Package for verifying that your JSON payloads are serialized correctly. |
| <b>[GoSpec](https://github.com/orfjackal/gospec) | 114 | BDD-style testing framework for the Go programming language. |
| <b>[testcase](https://github.com/adamluzsi/testcase) | 114 | Idiomatic testing framework for Behavior Driven Development. |
| <b>[wstest](https://github.com/posener/wstest) | 101 | Websocket client for unit-testing a websocket http.Handler. |
| <b>[gocrest](https://github.com/corbym/gocrest) | 97 | Composable hamcrest-like matchers for Go assertions. |
| <b>[be](https://github.com/carlmjohnson/be) | 88 | The minimalist generic test assertion library. |
| <b>[gherkingen](https://github.com/hedhyw/gherkingen) | 66 | BDD boilerplate generator and framework. |
| <b>[assert](https://github.com/go-playground/assert) | 62 | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| <b>[covergates](https://github.com/covergates/covergates) | 60 | Self-hosted code coverage report review and management service. |
| <b>[restit](https://github.com/yookoala/restit) | 55 | Go micro framework to help writing RESTful API integration test. |
| <b>[gospecify](https://github.com/stesla/gospecify) | 53 | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| <b>[gomatch](https://github.com/jfilipczyk/gomatch) | 45 | library created for testing JSON against patterns. |
| <b>[dsunit](https://github.com/viant/dsunit) | 43 | Datastore testing for SQL, NoSQL, structured files. |
| <b>[Hamcrest](https://github.com/rdrdr/hamcrest) | 29 | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| <b>[fixenv](https://github.com/rekby/fixenv) | 27 | Fixture manage engine, inspired by pytest fixtures. |
| <b>[schema](https://github.com/jgroeneveld/schema) | 20 | Quick and easy expression matching for JSON schemas used in requests and responses. |
| <b>[flute](https://github.com/suzuki-shunsuke/flute) | 18 | HTTP client testing framework. |
| <b>[testsql](https://github.com/zhulongcheng/testsql) | 17 | Generate test data from SQL files before testing and clear it after finished. |
| <b>[gogiven](https://github.com/corbym/gogiven) | 14 | YATSPEC-like BDD testing framework for Go. |
| <b>[biff](https://github.com/fulldump/biff) | 13 | Bifurcation testing framework, BDD compatible. |
| <b>[gosuite](https://github.com/pavlo/gosuite) | 12 | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| <b>[badio](https://github.com/cavaliercoder/badio) | 11 | Extensions to Go's `testing/iotest` package. |
| <b>[stop-and-go](https://github.com/elgohr/stop-and-go) | 10 | Testing helper for concurrency. |
| <b>[trial](https://github.com/jgroeneveld/trial) | 6 | Quick and easy extendable assertions without introducing much boilerplate. |
| <b>[Tt](https://github.com/vcaesar/tt) | 6 | Simple and colorful test tools. |
| <b>[go-testpredicate](https://github.com/maargenton/go-testpredicate) | 5 | Test predicate style assertions library with extensive diagnostics output. |
| <b>[omg.testingtools](https://github.com/dedalqq/omg.testingtools) | 1 | The simple library for change a values of private fields for testing. |
| <b>[gomega](https://onsi.github.io/gomega/) | - | Rspec like matcher/assertion library. |
| <b>[testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) | - | Convert markdown snippets into testable go code. |
| <b>[apitest](https://apitest.dev) | - | Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams. |
| <b>[ginkgo](https://onsi.github.io/ginkgo/) | - | BDD Testing Framework for Go. |
| <b>[gocheck](https://labix.org/gocheck) | - | More advanced testing framework alternative to gotest. |


<br>

[👆back to top](#catalogue-list)


<br>

### Mock


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gomock](https://github.com/golang/mock) | 9.2k | Mocking framework for the Go programming language. |
| <b>[go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 5.7k | Mock SQL driver for testing database interactions. |
| <b>[mockery](https://github.com/vektra/mockery) | 5.4k | Tool to generate Go interfaces. |
| <b>[hoverfly](https://github.com/SpectoLabs/hoverfly) | 2.3k | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| <b>[gock](https://github.com/h2non/gock) | 2.0k | Versatile HTTP mocking made easy. |
| <b>[httpmock](https://github.com/jarcoal/httpmock) | 1.8k | Easy mocking of HTTP responses from external resources. |
| <b>[counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 903 | Tool for generating self-contained mock objects. |
| <b>[go-txdb](https://github.com/DATA-DOG/go-txdb) | 602 | Single transaction based database driver mainly for testing purposes. |
| <b>[minimock](https://github.com/gojuno/minimock) | 534 | Mock generator for Go interfaces. |
| <b>[govcr](https://github.com/seborama/govcr) | 162 | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| <b>[go-localstack](https://github.com/elgohr/go-localstack) | 73 | Tool for using localstack in AWS testing. |
| <b>[timex](https://github.com/cabify/timex) | 70 | A test-friendly replacement for the native `time` package. |
| <b>[mockhttp](https://github.com/tv42/mockhttp) | 23 | Mock object for Go http.ResponseWriter. |
| <b>[mockit](https://github.com/pasdam/mockit) | 16 | Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java. |
| <b>[genmock](https://gitlab.com/so_literate/genmock) | - | Go mocking system with code generator for building calls of the interface methods. |


<br>

[👆back to top](#catalogue-list)


<br>

### Fuzzing and delta-debugging/reducing/shrinking.


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-fuzz](https://github.com/dvyukov/go-fuzz) | 4.7k | Randomized testing system. |
| <b>[gofuzz](https://github.com/google/gofuzz) | 1.5k | Library for populating go objects with random values. |
| <b>[Tavor](https://github.com/zimmski/tavor) | 241 | Generic fuzzing and delta-debugging framework. |


<br>

[👆back to top](#catalogue-list)


<br>

### Selenium and browser control tools.


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[chromedp](https://github.com/knq/chromedp) | 10.0k | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| <b>[rod](https://github.com/go-rod/rod) | 4.5k | A Devtools driver to make web automation and scraping easy. |
| <b>[selenoid](https://github.com/aerokube/selenoid) | 2.4k | alternative Selenium hub server that launches browsers within containers. |
| <b>[playwright-go](https://github.com/mxschmitt/playwright-go) | 1.6k | browser automation library to control Chromium, Firefox and WebKit with a single API. |
| <b>[cdp](https://github.com/mafredri/cdp) | 707 | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| <b>[ggr](https://github.com/aerokube/ggr) | 305 | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |


<br>

[👆back to top](#catalogue-list)


<br>

### Fail injection


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[failpoint](https://github.com/pingcap/failpoint) | 795 | An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Text Processing

_Libraries for parsing and manipulating texts._


<br>

### Formatters


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-humanize](https://github.com/dustin/go-humanize) | 3.9k | Formatters for time, numbers, and memory size to human readable format. |
| <b>[bytes](https://github.com/labstack/gommon/tree/master/bytes) | 516 | Formats and parses numeric byte values (10K, 2M, 3G, etc.). |
| <b>[gotabulate](https://github.com/bndr/gotabulate) | 308 | Easily pretty-print your tabular data with Go. |
| <b>[align](https://github.com/Guitarbum722/align) | 83 | A general purpose application that aligns text. |
| <b>[go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 79 | Fixed-width text formatting (encoder/decoder with reflection). |
| <b>[address](https://github.com/bojanz/address) | 69 | Handles address representation, validation and formatting. |
| <b>[textwrap](https://github.com/isbm/textwrap) | 5 | Wraps text at end of lines. Implementation of `textwrap` module from Python. |


<br>

[👆back to top](#catalogue-list)


<br>

### Markup Languages


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[blackfriday](https://github.com/russross/blackfriday) | 5.3k | Markdown processor in Go. |
| <b>[toml](https://github.com/BurntSushi/toml) | 4.4k | TOML configuration format (encoder/decoder with reflection). |
| <b>[goldmark](https://github.com/yuin/goldmark) | 3.1k | A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured. |
| <b>[go-toml](https://github.com/pelletier/go-toml) | 1.6k | Go library for the TOML format with query support and handy cli tools. |
| <b>[htmlquery](https://github.com/antchfx/htmlquery) | 671 | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| <b>[html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 669 | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| <b>[mxj](https://github.com/clbanning/mxj) | 592 | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| <b>[goq](https://github.com/andrewstuart/goq) | 250 | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| <b>[bafi](https://github.com/mmalcek/bafi) | 92 | Universal JSON, BSON, YAML, XML translator to ANY format using templates. |
| <b>[go-output-format](https://github.com/drewstinnett/go-output-format) | 13 | Output go structures into multiple formats (YAML/JSON/etc) in your command line app. |
| <b>[bbConvert](https://github.com/CalebQ42/bbConvert) | 7 | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| <b>[htmlyaml](https://github.com/nikolaydubina/htmlyaml) | 3 | Rich rendering of YAML as HTML in Go |
| <b>[htree](https://github.com/bobg/htree) | 2 | Traverse, navigate, filter, and otherwise process trees of [html.Node](https://pkg.go.dev/golang.org/x/net/html#Node) objects. |
| <b>[github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) | - | GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links. |


<br>

[👆back to top](#catalogue-list)


<br>

### Parsers/Encoders/Decoders


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sh](https://github.com/mvdan/sh) | 6.5k | Shell parser and formatter. |
| <b>[gofeed](https://github.com/mmcdole/gofeed) | 2.3k | Parse RSS and Atom feeds in Go. |
| <b>[when](https://github.com/olebedev/when) | 1.3k | Natural EN and RU language date/time parser with pluggable rules. |
| <b>[commonregex](https://github.com/mingrammer/commonregex) | 877 | A collection of common regular expressions for Go. |
| <b>[omniparser](https://github.com/jf-tech/omniparser) | 607 | A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. |
| <b>[gographviz](https://github.com/awalterschulze/gographviz) | 537 | Parses the Graphviz DOT language. |
| <b>[go-nmea](https://github.com/adrianmo/go-nmea) | 202 | NMEA parser library for the Go language. |
| <b>[editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 125 | Editorconfig file parser and manipulator for Go. |
| <b>[sdp](https://github.com/gortc/sdp) | 112 | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| <b>[go-vcard](https://github.com/emersion/go-vcard) | 96 | Parse and format vCard. |
| <b>[did](https://github.com/ockam-network/did) | 81 | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| <b>[tokenizer](https://github.com/bzick/tokenizer) | 73 | — Parse any string, slice or infinite buffer to any tokens. |
| <b>[allot](https://github.com/sbstjn/allot) | 58 | Placeholder and wildcard text parsing for CLI tools and bots. |
| <b>[parth](https://github.com/codemodus/parth) | 46 | URL path segmentation parsing. |
| <b>[gonameparts](https://github.com/polera/gonameparts) | 39 | Parses human names into individual name parts. |
| <b>[normalize](https://github.com/avito-tech/normalize) | 39 | Sanitize, normalize and compare fuzzy text. |
| <b>[xj2go](https://github.com/stackerzzq/xj2go) | 34 | Convert xml or json to go struct. |
| <b>[go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) | 29 | High performance top level domains (TLD) extraction module. |
| <b>[codetree](https://github.com/aerogo/codetree) | 23 | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| <b>[parseargs-go](https://github.com/nproc/parseargs-go) | 10 | string argument parser that understands quotes and backslashes. |
| <b>[doi](https://github.com/hscells/doi) | 8 | Document object identifier (doi) parser in Go. |
| <b>[encdec](https://github.com/mickep76/encdec) | 8 | Package provides a generic interface to encoders and decoders. |
| <b>[ltsv](https://github.com/Wing924/ltsv) | 8 | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Regular Expressions


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[rex](https://github.com/hedhyw/rex) | 176 | Regular expressions builder. |
| <b>[regroup](https://github.com/oriser/regroup) | 139 | Match regex expression named groups into go struct using struct tags and automatic parsing. |
| <b>[goregen](https://github.com/zach-klippenstein/goregen) | 89 | Library for generating random strings from regular expressions. |
| <b>[genex](https://github.com/alixaxel/genex) | 76 | Count and expand Regular Expressions into all matching Strings. |
| <b>[go-wildcard](https://github.com/IGLOU-EU/go-wildcard) | 64 | Simple and lightweight wildcard pattern matching. |


<br>

[👆back to top](#catalogue-list)


<br>

### Sanitation


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bluemonday](https://github.com/microcosm-cc/bluemonday) | 2.9k | HTML Sanitizer. |
| <b>[gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 59 | A sanitization-based swear filter for Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Scrapers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[colly](https://github.com/asciimoo/colly) | 22.0k | Fast and Elegant Scraping Framework for Gophers. |
| <b>[GoQuery](https://github.com/PuerkitoBio/goquery) | 13.0k | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| <b>[xurls](https://github.com/mvdan/xurls) | 1.1k | Extract urls from text. |
| <b>[dataflowkit](https://github.com/slotix/dataflowkit) | 636 | Web scraping Framework to turn websites into structured data. |
| <b>[gospider](https://github.com/zhshch2002/gospider) | 203 | A simple golang spider/scraping framework,build a spider in 3 lines. migrated from [goribot](https://github.com/zhshch2002/goribot) |
| <b>[pagser](https://github.com/foolin/pagser) | 93 | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| <b>[Tagify](https://github.com/zoomio/tagify) | 35 | Produces a set of tags from given source. |
| <b>[go-recipe](https://github.com/kkyr/go-recipe) | 25 | A package for scraping recipes from websites. |
| <b>[walker](https://github.com/cyucelen/walker) | 7 | Seamlessly fetch paginated data from any source. Simple and high performance API scraping included. |


<br>

[👆back to top](#catalogue-list)


<br>

### RSS


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[podcast](https://github.com/eduncan911/podcast) | 126 | iTunes Compliant and RSS 2.0 Podcast Generator in Golang |
| <b>[syndfeed](https://github.com/zhengchun/syndfeed) | 11 | A syndication feed for Atom 1.0 and RSS 2.0. |


<br>

[👆back to top](#catalogue-list)


<br>

### Utility/Miscellaneous


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-runewidth](https://github.com/mattn/go-runewidth) | 570 | Functions to get fixed width of the character or string. |
| <b>[radix](https://github.com/yourbasic/radix) | 188 | Fast string sorting algorithm. |
| <b>[go-zero-width](https://github.com/trubitsyn/go-zero-width) | 111 | Zero-width character detection and removal for Go. |
| <b>[petrovich](https://github.com/striker2000/petrovich) | 45 | Petrovich is the library which inflects Russian names to given grammatical case. |
| <b>[kace](https://github.com/codemodus/kace) | 20 | Common case conversions covering common initialisms. |
| <b>[TySug](https://github.com/Dynom/TySug) | 17 | Alternative suggestions with respect to keyboard layouts. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Third-party APIs

_Libraries for accessing third party APIs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[github](https://github.com/google/go-github) | 9.9k | Go library for accessing the GitHub REST API v3. |
| <b>[aws-sdk-go](https://github.com/aws/aws-sdk-go) | 8.5k | The official AWS SDK for the Go programming language. |
| <b>[go-openai](https://github.com/sashabaranov/go-openai) | 7.6k | OpenAI ChatGPT, DALL·E, Whisper API library for Go. |
| <b>[discordgo](https://github.com/bwmarrin/discordgo) | 4.5k | Go bindings for the Discord Chat API. |
| <b>[slack](https://github.com/slack-go/slack) | 4.5k | Slack API in Go. |
| <b>[google](https://github.com/google/google-api-go-client) | 3.7k | Auto-generated Google APIs for Go. |
| <b>[google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) | 3.5k | Google Cloud APIs Go Client Library. |
| <b>[aws-sdk-go](https://github.com/aws/aws-sdk-go-v2) | 2.3k | The official AWS SDK for the Go programming language. |
| <b>[minio-go](https://github.com/minio/minio-go) | 2.2k | Minio Go Library for Amazon S3 compatible cloud storage. |
| <b>[stripe](https://github.com/stripe/stripe-go) | 1.9k | Go client for the Stripe API. |
| <b>[go-twitter](https://github.com/dghubble/go-twitter) | 1.6k | Go client library for the Twitter v1.1 APIs. |
| <b>[go-jira](https://github.com/andygrunwald/go-jira) | 1.4k | Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) |
| <b>[facebook](https://github.com/huandu/facebook) | 1.2k | Go Library that supports the Facebook Graph API. |
| <b>[anaconda](https://github.com/ChimeraCoder/anaconda) | 1.1k | Go client library for the Twitter 1.1 API. |
| <b>[githubql](https://github.com/shurcooL/githubql) | 1.1k | Go library for accessing the GitHub GraphQL API v4. |
| <b>[webhooks](https://github.com/go-playground/webhooks) | 905 | Webhook receiver for GitHub and Bitbucket. |
| <b>[twitter-scraper](https://github.com/n0madic/twitter-scraper) | 823 | Scrape the Twitter Frontend API without authentication and limits. |
| <b>[paypal](https://github.com/logpacker/PayPal-Go-SDK) | 626 | Wrapper for PayPal payment API. |
| <b>[geo-golang](https://github.com/codingsince1985/geo-golang) | 492 | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| <b>[lark](https://github.com/chyroc/lark) | 370 | [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback. |
| <b>[openaigo](https://github.com/otiai10/openaigo) | 281 | OpenAI GPT3/GPT3.5 ChatGPT API client library for Go. |
| <b>[ethrpc](https://github.com/onrik/ethrpc) | 260 | Go bindings for Ethereum JSON RPC API. |
| <b>[Trello](https://github.com/adlio/trello) | 215 | Go wrapper for the Trello API. |
| <b>[go-marathon](https://github.com/gambol99/go-marathon) | 199 | Go library for interacting with Mesosphere's Marathon PAAS. |
| <b>[go-lark](https://github.com/go-lark/lark) | 174 | An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform. |
| <b>[wit-go](https://github.com/wit-ai/wit-go) | 148 | Go client for wit.ai HTTP API. |
| <b>[go-trending](https://github.com/andygrunwald/go-trending) | 139 | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| <b>[Medium](https://github.com/Medium/medium-sdk-go) | 139 | Golang SDK for Medium's OAuth2 API. |
| <b>[pushover](https://github.com/gregdel/pushover) | 139 | Go wrapper for the Pushover API. |
| <b>[gostorm](https://github.com/jsgilmore/gostorm) | 129 | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| <b>[gosip](https://github.com/koltyakov/gosip) | 126 | Go client library SharePoint API. |
| <b>[simples3](https://github.com/rhnvrm/simples3) | 119 | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| <b>[hipchat (xmpp)](https://github.com/daneharrigan/hipchat) | 111 | A golang package to communicate with HipChat over XMPP. |
| <b>[hipchat](https://github.com/andybons/hipchat) | 105 | This project implements a golang client library for the Hipchat API. |
| <b>[go-atlassian](https://github.com/ctreminiom/go-atlassian) | 102 | Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud) |
| <b>[cachet](https://github.com/andygrunwald/cachet) | 91 | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| <b>[golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 90 | Golang wrapper for The Movie Database API v3. |
| <b>[igdb](https://github.com/Henry-Sarabia/igdb) | 79 | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| <b>[gogtrends](https://github.com/groovili/gogtrends) | 78 | Google Trends Unofficial API. |
| <b>[google-play-scraper](https://github.com/n0madic/google-play-scraper) | 78 | Get data from Google Play Store. |
| <b>[go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 72 | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| <b>[go-unsplash](https://github.com/hbagdi/go-unsplash) | 72 | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| <b>[airtable](https://github.com/mehanizm/airtable) | 69 | Go client library for the [Airtable API](https://airtable.com/api). |
| <b>[circleci](https://github.com/jszwedko/go-circleci) | 67 | Go client library for interacting with CircleCI's API. |
| <b>[ynab](https://github.com/brunomvsouza/ynab.go) | 64 | Go wrapper for the YNAB API. |
| <b>[mixpanel](https://github.com/dukex/mixpanel) | 60 | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| <b>[amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 57 | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| <b>[uptimerobot](https://github.com/bitfield/uptimerobot) | 57 | Go wrapper and command-line client for the Uptime Robot v2 API. |
| <b>[go-redoc](https://github.com/mvrilo/go-redoc) | 56 | Embedded OpenAPI/Swagger documentation ui for Go using [ReDoc](https://redocly.com/). |
| <b>[clarifai](https://github.com/samuelcouch/clarifai) | 55 | Go client library for interfacing with the Clarifai API. |
| <b>[megos](https://github.com/andygrunwald/megos) | 54 | Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster. |
| <b>[GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) | 53 | Go MusicBrainz WS2 client library. |
| <b>[go-xkcd](https://github.com/nishanths/go-xkcd) | 52 | Go client for the xkcd API. |
| <b>[fcm](https://github.com/maddevsio/fcm) | 51 | Go library for Firebase Cloud Messaging. |
| <b>[gads](https://github.com/emiddleton/gads) | 50 | Google Adwords Unofficial API. |
| <b>[spotify](https://github.com/rapito/go-spotify) | 48 | Go Library to access Spotify WEB API. |
| <b>[swag](https://github.com/zc2638/swag) | 43 | No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more. |
| <b>[golyrics](https://github.com/mamal72/golyrics) | 40 | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| <b>[go-myanimelist](https://github.com/nstratos/go-myanimelist) | 38 | Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2). |
| <b>[patreon-go](https://github.com/mxpv/patreon-go) | 38 | Go library for Patreon API. |
| <b>[lastpass-go](https://github.com/ansd/lastpass-go) | 33 | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| <b>[translate](https://github.com/poorny/translate) | 33 | Go online translation package. |
| <b>[gami](https://github.com/bit4bit/gami) | 32 | Go library for Asterisk Manager Interface. |
| <b>[gcm](https://github.com/Aorioli/gcm) | 31 | Go library for Google Cloud Messaging. |
| <b>[steam](https://github.com/sostronk/go-steam) | 31 | Go Library to interact with Steam game servers. |
| <b>[GoFreeDB](https://github.com/FreeLeh/GoFreeDB) | 31 | Golang library providing common and simple database abstractions on top of Google Sheets. |
| <b>[go-imgur](https://github.com/koffeinsource/go-imgur) | 25 | Go client library for [imgur](https://imgur.com) |
| <b>[shopify](https://github.com/rapito/go-shopify) | 25 | Go Library to make CRUD request to the Shopify API. |
| <b>[device-check-go](https://github.com/rinchsan/device-check-go) | 24 | Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. |
| <b>[coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) | 23 | Go client library for interacting with Coinpaprika's API. |
| <b>[go-twitch](https://github.com/knspriggs/go-twitch) | 22 | Go client for interacting with the Twitch v3 API. |
| <b>[jokeapi-go](https://github.com/icelain/jokeapi) | 22 | Go client for [JokeAPI](https://sv443.net/jokeapi/v2/). |
| <b>[brewerydb](https://github.com/naegelejd/brewerydb) | 19 | Go library for accessing the BreweryDB API. |
| <b>[textbelt](https://github.com/dietsche/textbelt) | 19 | Go client for the textbelt.com txt messaging API. |
| <b>[codeship-go](https://github.com/codeship/codeship-go) | 18 | Go client library for interacting with Codeship's API v2. |
| <b>[go-aws-news](https://github.com/circa10a/go-aws-news) | 18 | Go application and library to fetch what's new from AWS. |
| <b>[go-hacknews](https://github.com/PaulRosset/go-hacknews) | 17 | Tiny Go client for HackerNews API. |
| <b>[google-analytics](https://github.com/chonthu/go-google-analytics) | 15 | Simple wrapper for easy google analytics reporting. |
| <b>[gopaapi5](https://github.com/utekaravinash/gopaapi5) | 15 | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| <b>[bqwriter](https://github.com/OTA-Insight/bqwriter) | 14 | High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout. |
| <b>[go-openproject](https://github.com/manuelbcd/go-openproject) | 14 | Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API. |
| <b>[goami2](https://github.com/staskobzar/goami2) | 14 | AMI v2 library for Asterisk PBX. |
| <b>[go-here](https://github.com/abdullahselek/go-here) | 13 | Go client library around the HERE location based APIs. |
| <b>[gomalshare](https://github.com/MonaxGT/gomalshare) | 13 | Go library MalShare API [malshare.com](https://www.malshare.com/) |
| <b>[go-sophos](https://github.com/esurdam/go-sophos) | 12 | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| <b>[go-swagger-ui](https://github.com/esurdam/go-swagger-ui) | 11 | Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json. |
| <b>[smite](https://github.com/sergiotapia/smitego) | 11 | Go package to wraps access to the Smite game API. |
| <b>[rrdaclient](https://github.com/Omie/rrdaclient) | 10 | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| <b>[go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 9 | Go client library for the SPTrans Olho Vivo API. |
| <b>[libgoffi](https://github.com/clevabit/libgoffi) | 9 | Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration |
| <b>[rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) | 9 | Go library for the [RAWG Video Games Database](https://rawg.io/) API |
| <b>[tumblr](https://github.com/mattcunningham/gumblr) | 9 | Go wrapper for the Tumblr v2 API. |
| <b>[goagi](https://github.com/staskobzar/goagi) | 9 | Go library to build Asterisk PBX agi/fastagi applications. |
| <b>[go-chronos](https://github.com/axelspringer/go-chronos) | 8 | Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler |
| <b>[go-hibp](https://github.com/wneessen/go-hibp) | 8 | Simple Go binding to the "Have I Been Pwned" APIs. |
| <b>[google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 8 | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| <b>[zooz](https://github.com/gojuno/go-zooz) | 7 | Go client for the Zooz API. |
| <b>[newsapi-go](https://github.com/jellydator/newsapi-go) | 6 | Go client for [NewsAPI](https://newsapi.org/). |
| <b>[appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) | 5 | Unofficial Golang SDK for AppStore Connect API. |
| <b>[go-restcountries](https://github.com/chriscross0/go-restcountries) | 4 | Go library for the [REST Countries API](https://restcountries.eu/). |
| <b>[dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) | 3 | Unofficial Dusupay payment gateway API Client for Go |
| <b>[kanka](https://github.com/Henry-Sarabia/kanka) | 3 | Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0). |
| <b>[fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) | 2 | Unofficial Fasapay payment gateway XML API Client for Golang. |
| <b>[playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) | 2 | The Playlyfe Rest API Go SDK. |
| <b>[TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) | 2 | Go wrapper for the TripAdvisor API. |
| <b>[vl-go](https://github.com/verifid/vl-go) | 2 | Go client library around the VerifID identity verification layer API. |
| <b>[go-telegraph](https://gitlab.com/toby3d/telegraph) | - | Telegraph publishing platform API client. |
| <b>[go-yapla](https://git.iglou.eu/Production/go-yapla) | - | Go client library for the Yapla v2.0 API. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Utilities

_General utilities and tools to make your life easier._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fzf](https://github.com/junegunn/fzf) | 57.0k | Command-line fuzzy finder written in Go. |
| <b>[dive](https://github.com/wagoodman/dive) | 42.0k | A tool for exploring each layer in a Docker image. |
| <b>[hub](https://github.com/github/hub) | 23.0k | wrap git commands with additional functionality to interact with github from the terminal. |
| <b>[ctop](https://github.com/bcicen/ctop) | 15.0k | [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics. |
| <b>[lo](https://github.com/samber/lo) | 15.0k | A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...) |
| <b>[sqlx](https://github.com/jmoiron/sqlx) | 15.0k | provides a set of extensions on top of the excellent built-in database/sql package. |
| <b>[air](https://github.com/cosmtrek/air) | 14.0k | Air - Live reload for Go apps. |
| <b>[goreleaser](https://github.com/goreleaser/goreleaser) | 13.0k | Deliver Go binaries as fast and easily as possible. |
| <b>[wuzz](https://github.com/asciimoo/wuzz) | 10.0k | Interactive cli tool for HTTP inspection. |
| <b>[usql](https://github.com/knq/usql) | 8.4k | usql is a universal command-line interface for SQL databases. |
| <b>[peco](https://github.com/peco/peco) | 7.5k | Simplistic interactive filtering tool. |
| <b>[go-funk](https://github.com/thoas/go-funk) | 4.5k | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| <b>[godropbox](https://github.com/dropbox/godropbox) | 4.2k | Common libraries for writing Go services/applications from Dropbox. |
| <b>[hystrix-go](https://github.com/afex/hystrix-go) | 4.1k | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| <b>[minify](https://github.com/tdewolff/minify) | 3.5k | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| <b>[panicparse](https://github.com/maruel/panicparse) | 3.5k | Groups similar goroutines and colorizes stack dump. |
| <b>[lancet](https://github.com/duke-git/lancet) | 3.5k | A comprehensive, efficient, and reusable util function library of go. |
| <b>[goreporter](https://github.com/wgliang/goreporter) | 3.1k | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| <b>[mc](https://github.com/minio/mc) | 2.6k | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| <b>[mergo](https://github.com/imdario/mergo) | 2.6k | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| <b>[create-go-app](https://github.com/create-go-app/cli) | 2.3k | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| <b>[retry-go](https://github.com/avast/retry-go) | 2.1k | Simple library for retry mechanism. |
| <b>[filetype](https://github.com/h2non/filetype) | 2.0k | Small package to infer the file type checking the magic numbers signature. |
| <b>[Storm](https://github.com/asdine/storm) | 2.0k | Simple and powerful toolkit for BoltDB. |
| <b>[EaseProbe](https://github.com/megaease/easeprobe) | 2.0k | A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification. |
| <b>[boilr](https://github.com/tmrts/boilr) | 1.7k | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| <b>[jump](https://github.com/gsamokovarov/jump) | 1.7k | Jump helps you navigate faster by learning your habits. |
| <b>[mole](https://github.com/davrodpin/mole) | 1.7k | cli app to easily create ssh tunnels. |
| <b>[gitbatch](https://github.com/isacikgoz/gitbatch) | 1.5k | manage your git repositories in one place. |
| <b>[mimetype](https://github.com/gabriel-vasile/mimetype) | 1.3k | Package for MIME type detection based on magic numbers. |
| <b>[circuitbreaker](https://github.com/rubyist/circuitbreaker) | 1.1k | Circuit Breakers in Go. |
| <b>[scany](https://github.com/georgysavva/scany) | 1.1k | Library for scanning data from a database into Go structs and more. |
| <b>[hostctl](https://github.com/guumaster/hostctl) | 979 | A CLI tool to manage /etc/hosts with easy commands. |
| <b>[git-time-metric](https://github.com/git-time-metric/gtm) | 956 | Simple, seamless, lightweight time tracking for Git. |
| <b>[immortal](https://github.com/immortal/immortal) | 785 | \*nix cross-platform (OS agnostic) supervisor. |
| <b>[upterm](https://github.com/owenthereal/upterm) | 725 | A tool for developers to share terminal/tmux sessions securely over the web. It’s perfect for remote pair programming, accessing computers behind NATs/firewalls, remote debugging, and more. |
| <b>[circuit](https://github.com/cep21/circuit) | 724 | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| <b>[delve](https://github.com/derekparker/delve) | 614 | Go debugger. |
| <b>[ergo](https://github.com/cristianoliveira/ergo) | 599 | The management of multiple local services running over different ports made easy. |
| <b>[clockwork](https://github.com/jonboulle/clockwork) | 579 | A simple fake clock for golang. |
| <b>[changie](https://github.com/miniscruff/changie) | 561 | Automated changelog tool for preparing releases with lots of customization options. |
| <b>[htcat](https://github.com/htcat/htcat) | 552 | Parallel and Pipelined HTTP GET Utility. |
| <b>[koazee](https://github.com/wesovilabs/koazee) | 519 | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| <b>[clipboard](https://github.com/golang-design/clipboard) | 499 | 📋 cross-platform clipboard package in Go. |
| <b>[scan](https://github.com/blockloop/scan) | 495 | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| <b>[godaemon](https://github.com/VividCortex/godaemon) | 493 | Utility to write daemons. |
| <b>[go-dry](https://github.com/ungerik/go-dry) | 488 | DRY (don't repeat yourself) package for Go. |
| <b>[gubrak](https://github.com/novalagung/gubrak) | 472 | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| <b>[remote-touchpad](https://github.com/Unrud/remote-touchpad) | 459 | Control mouse and keyboard from a smartphone. |
| <b>[gopencils](https://github.com/bndr/gopencils) | 451 | Small and simple package to easily consume REST APIs. |
| <b>[Deepcopier](https://github.com/ulule/deepcopier) | 433 | Simple struct copying for Go. |
| <b>[request](https://github.com/mozillazg/request) | 426 | Go HTTP Requests for Humans™. |
| <b>[mani](https://github.com/alajmo/mani) | 405 | CLI tool to help you manage multiple repositories. |
| <b>[go-rate](https://github.com/beefsack/go-rate) | 393 | Timed rate limiter for Go. |
| <b>[countries](https://github.com/biter777/countries) | 335 | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| <b>[retry](https://github.com/kamilsk/retry) | 334 | The most advanced functional mechanism to perform actions repetitively until successful. |
| <b>[grofer](https://github.com/pesos/grofer) | 320 | A system and resource monitoring tool written in Golang! |
| <b>[serve](https://github.com/syntaqx/serve) | 320 | A static http server anywhere you need. |
| <b>[util](https://github.com/shomali11/util) | 283 | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| <b>[gotenv](https://github.com/subosito/gotenv) | 279 | Load environment variables from `.env` or any `io.Reader` in Go. |
| <b>[limiters](https://github.com/mennanov/limiters) | 275 | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| <b>[rospo](https://github.com/ferama/rospo) | 260 | Simple and reliable ssh tunnels with embedded ssh server in Golang. |
| <b>[gohper](https://github.com/cosiner/gohper) | 256 | Various tools/modules help for development. |
| <b>[wifiqr](https://github.com/reugn/wifiqr) | 247 | Wi-Fi QR Code Generator. |
| <b>[go-trigger](https://github.com/sadlil/go-trigger) | 241 | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| <b>[pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 235 | Pattern matching libray. |
| <b>[go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 213 | XML Sitemap generator written in Go. |
| <b>[toolbox](https://github.com/viant/toolbox) | 195 | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| <b>[Death](https://github.com/vrecan/death) | 192 | Managing go application shutdown with signals. |
| <b>[go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 185 | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| <b>[moldova](https://github.com/StabbyCutyou/moldova) | 167 | Utility for generating random data based on an input template. |
| <b>[rerun](https://github.com/ivpusic/rerun) | 167 | Recompiling and rerunning go apps when source changes. |
| <b>[apm](https://github.com/topfreegames/apm) | 165 | Process manager for Golang applications with an HTTP API. |
| <b>[robustly](https://github.com/VividCortex/robustly) | 157 | Runs functions resiliently, catching and restarting panics. |
| <b>[chyle](https://github.com/antham/chyle) | 154 | Changelog generator using a git repository with multiple configuration possibilities. |
| <b>[go-bsdiff](https://github.com/gabstv/go-bsdiff) | 151 | Pure Go bsdiff and bspatch libraries and CLI tools. |
| <b>[cmd](https://github.com/SimonBaeumer/cmd) | 143 | Library for executing shell commands on osx, windows and linux. |
| <b>[cryptgo](https://github.com/Gituser143/cryptgo) | 143 | Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time! |
| <b>[filter](https://github.com/gookit/filter) | 143 | provide filtering, sanitizing, and conversion of Go data. |
| <b>[nostromo](https://github.com/pokanop/nostromo) | 140 | CLI for building powerful aliases. |
| <b>[goval](https://github.com/maja42/goval) | 136 | Evaluate arbitrary expressions in Go. |
| <b>[onecache](https://github.com/adelowo/onecache) | 134 | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| <b>[mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 128 | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| <b>[sorty](https://github.com/jfcg/sorty) | 125 | Fast Concurrent / Parallel Sorting. |
| <b>[lrserver](https://github.com/jaschaephraim/lrserver) | 124 | LiveReload server for Go. |
| <b>[goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 112 | SeaweedFS client library with almost full features. |
| <b>[go-lock](https://github.com/viney-shih/go-lock) | 105 | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| <b>[mssqlx](https://github.com/linxGnu/mssqlx) | 101 | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| <b>[xferspdy](https://github.com/monmohan/xferspdy) | 100 | Xferspdy provides binary diff and patch library in golang. |
| <b>[mimemagic](https://github.com/zRedShift/mimemagic) | 97 | Pure Go ultra performant MIME sniffing library/utility. |
| <b>[go-health](https://github.com/Talento90/go-health) | 94 | Health package simplifies the way you add health check to your services. |
| <b>[pgo](https://github.com/arthurkushman/pgo) | 85 | Convenient functions for PHP community. |
| <b>[countries](https://github.com/pioz/countries) | 85 | All you need when you are working with countries in Go. |
| <b>[repeat](https://github.com/ssgreg/repeat) | 84 | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| <b>[go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) | 84 | A Pattern matching library inspired by ts-pattern. |
| <b>[pm](https://github.com/VividCortex/pm) | 80 | Process (i.e. goroutine) manager with an HTTP API. |
| <b>[handy](https://github.com/miguelpragier/handy) | 77 | Many utilities and helpers like string handlers/formatters and validators. |
| <b>[netbug](https://github.com/e-dard/netbug) | 73 | Easy remote profiling of your services. |
| <b>[multitick](https://github.com/VividCortex/multitick) | 70 | Multiplexor for aligned tickers. |
| <b>[UNIS](https://github.com/esemplastic/unis) | 70 | Common Architecture™ for String Utilities in Go. |
| <b>[goreadability](https://github.com/philipjkim/goreadability) | 69 | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| <b>[retry](https://github.com/thedevsaddam/retry) | 65 | Simple and easy retry mechanism package for Go. |
| <b>[minquery](https://github.com/icza/minquery) | 62 | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| <b>[go-astitodo](https://github.com/asticode/go-astitodo) | 61 | Parse TODOs in your GO code. |
| <b>[golog](https://github.com/mlimaloureiro/golog) | 60 | Easy and lightweight CLI tool to time track your tasks. |
| <b>[dbt](https://github.com/nikogura/dbt) | 58 | A framework for running self-updating signed binaries from a central, trusted repository. |
| <b>[backscanner](https://github.com/icza/backscanner) | 57 | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| <b>[shutdown](https://github.com/ztrue/shutdown) | 57 | App shutdown hooks for `os.Signal` handling. |
| <b>[beyond](https://github.com/wesovilabs/beyond) | 56 | The Go tool that will drive you to the AOP world! |
| <b>[scan](https://github.com/wroge/scan) | 56 | Scan sql rows into any type powered by generics. |
| <b>[golarm](https://github.com/msempere/golarm) | 52 | Fire alarms with system events. |
| <b>[slice](https://github.com/psampaz/slice) | 51 | Type-safe functions for common Go slice operations. |
| <b>[copy-pasta](https://github.com/jutkko/copy-pasta) | 50 | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| <b>[goback](https://github.com/carlescere/goback) | 48 | Go simple exponential backoff package. |
| <b>[retry-go](https://github.com/rafaeljesus/retry-go) | 47 | Retrying made simple and easy for golang. |
| <b>[go-httpheader](https://github.com/mozillazg/go-httpheader) | 46 | Go library for encoding structs into Header fields. |
| <b>[intrinsic](https://github.com/mengzhuo/intrinsic) | 46 | Use x86 SIMD without writing any assembly code. |
| <b>[set](https://github.com/nofeaturesonlybugs/set) | 46 | Performant and flexible struct mapping and loose type conversion. |
| <b>[sshman](https://github.com/shoobyban/sshman) | 45 | SSH Manager for authorized_keys files on multiple remote servers. |
| <b>[cvt](https://github.com/shockerli/cvt) | 44 | Easy and safe convert any value to another type. |
| <b>[slicer](https://github.com/leaanthony/slicer) | 44 | Makes working with slices easier. |
| <b>[equalizer](https://github.com/reugn/equalizer) | 43 | Quota manager and rate limiter collection for Go. |
| <b>[gostrutils](https://github.com/ik5/gostrutils) | 43 | Collections of string manipulation and conversion functions. |
| <b>[pointer](https://github.com/xorcare/pointer) | 41 | Package pointer contains helper routines for simplifying the creation of optional fields of basic type. |
| <b>[ghokin](https://github.com/antham/ghokin) | 40 | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| <b>[gpath](https://github.com/tenntenn/gpath) | 40 | Library to simplify access struct fields with Go's expression in reflection. |
| <b>[copy](https://github.com/gotidy/copy) | 39 | Package for fast copying structs of different types. |
| <b>[evaluator](https://github.com/nullne/evaluator) | 38 | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| <b>[rclient](https://github.com/zpatrick/rclient) | 35 | Readable, flexible, simple-to-use client for REST APIs. |
| <b>[tome](https://github.com/cyruzin/tome) | 35 | Tome was designed to paginate simple RESTful APIs. |
| <b>[yogo](https://github.com/antham/yogo) | 35 | Check yopmail mails from command line. |
| <b>[myhttp](https://github.com/inancgumus/myhttp) | 34 | Simple API to make HTTP GET requests with timeout support. |
| <b>[throttle](https://github.com/yudppp/throttle) | 34 | Throttle is an object that will perform exactly one action per duration. |
| <b>[mimesniffer](https://github.com/aofei/mimesniffer) | 32 | A MIME type sniffer for Go. |
| <b>[generate](https://github.com/go-playground/generate) | 30 | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| <b>[goplaceholder](https://github.com/michiwend/goplaceholder) | 28 | a small golang lib to generate placeholder images. |
| <b>[watchhttp](https://github.com/nikolaydubina/watchhttp) | 28 | Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint. |
| <b>[gofn](https://github.com/tiendc/gofn) | 28 | High performance utility functions written using Generics for Go 1.18+. |
| <b>[ugo](https://github.com/alxrm/ugo) | 27 | ugo is slice toolbox with concise syntax for Go. |
| <b>[graterm](https://github.com/skovtunenko/graterm) | 27 | Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application. |
| <b>[rerate](https://github.com/abo/rerate) | 26 | Redis-based rate counter and rate limiter for Go. |
| <b>[ctxutil](https://github.com/posener/ctxutil) | 25 | A collection of utility functions for contexts. |
| <b>[structs](https://github.com/PumpkinSeed/structs) | 24 | Implement simple functions to manipulate structs. |
| <b>[ptr](https://github.com/gotidy/ptr) | 23 | Package that provide functions for simplified creation of pointers from constants of basic types. |
| <b>[go-convert](https://github.com/Eun/go-convert) | 22 | Package go-convert enables you to convert a value into another type. |
| <b>[jsend](https://github.com/clevergo/jsend) | 21 | JSend's implementation writen in Go. |
| <b>[just](https://github.com/kazhuravlev/just) | 18 | Just a collection of useful functions for working with generic data structures. |
| <b>[dlog](https://github.com/kirillDanshin/dlog) | 17 | Compile-time controlled logger to make your release smaller without removing debug calls. |
| <b>[filler](https://github.com/yaronsumel/filler) | 17 | small utility to fill structs using "fill" tag. |
| <b>[go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 17 | Go package for working with Problem Details. |
| <b>[go-type](https://github.com/mikekonan/go-types) | 17 | Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. |
| <b>[contextplus](https://github.com/contextplus/contextplus) | 17 | Package contextplus provide more easy to use functions for contexts. |
| <b>[okrun](https://github.com/xta/okrun) | 16 | go run error steamroller. |
| <b>[rest-go](https://github.com/edermanoel94/rest-go) | 16 | A package that provide many helpful methods for working with rest api. |
| <b>[command](https://github.com/txgruppi/command) | 14 | Command pattern for Go with thread safe serial and parallel dispatcher. |
| <b>[go-actuator](https://github.com/sinhashubham95/go-actuator) | 14 | Production ready features for Go based web frameworks. |
| <b>[go-countries](https://github.com/mikekonan/go-countries) | 13 | Lightweight lookup over ISO-3166 codes. |
| <b>[silk](https://github.com/chrispassas/silk) | 13 | Read silk netflow files. |
| <b>[blank](https://github.com/Henry-Sarabia/blank) | 12 | Verify or remove blanks and whitespace from strings. |
| <b>[go-clip](https://github.com/prashantgupta24/go-clip) | 12 | A minimalistic clipboard manager for Mac. |
| <b>[retry](https://github.com/shafreeck/retry) | 12 | A pretty simple library to ensure your work to be done. |
| <b>[go-qr](https://github.com/piglig/go-qr) | 12 | A native, high-quality and minimalistic QR code generator. |
| <b>[bleep](https://github.com/sinhashubham95/bleep) | 11 | Perform any number of actions on any set of OS signals in Go. |
| <b>[retry](https://github.com/percolate/retry) | 10 | A simple but highly configurable retry package for Go. |
| <b>[statiks](https://github.com/janiltonmaciel/statiks) | 10 | Fast, zero-configuration, static HTTP filer server. |
| <b>[nfdump](https://github.com/chrispassas/nfdump) | 8 | Read nfdump netflow files. |
| <b>[sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 8 | Slice conversion between primitive types. |
| <b>[goctx](https://github.com/zerosnake0/goctx) | 7 | Get your context value with high performance. |
| <b>[reflectutils](https://github.com/muir/reflectutils) | 7 | Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string. |
| <b>[loncha](https://github.com/kazu/loncha) | 7 | A high-performance slice Utilities. |
| <b>[go-pkg](https://github.com/chenquan/go-pkg) | 6 | A go toolkit. |
| <b>[go-safe](https://github.com/kenkyu392/go-safe) | 6 | Panic-safe sandbox. |
| <b>[lets-go](https://github.com/aplescia-chwy/lets-go) | 6 | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| <b>[olaf](https://github.com/btnguyen2k/olaf) | 6 | Twitter Snowflake implemented in Go. |
| <b>[tik](https://github.com/andy2046/tik) | 5 | Simple and easy timing wheel package for Go. |
| <b>[objwalker](https://github.com/rekby/objwalker) | 2 | Walk by go objects with reflection. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## UUID

_Libraries for working with UUIDs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[uuid](https://github.com/google/uuid) | 4.8k | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| <b>[ulid](https://github.com/oklog/ulid) | 4.0k | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| <b>[xid](https://github.com/rs/xid) | 3.6k | Xid is a globally unique id generator library, ready to be safely used directly in your server code. |
| <b>[uuid](https://github.com/gofrs/uuid) | 1.5k | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| <b>[wuid](https://github.com/edwingeng/wuid) | 509 | An extremely fast unique number generator, 10-135 times faster than UUID. |
| <b>[sno](https://github.com/muyo/sno) | 89 | Compact, sortable and fast unique IDs with embedded metadata. |
| <b>[nanoid](https://github.com/aidarkhanov/nanoid) | 59 | A tiny and efficient Go unique string ID generator. |
| <b>[goid](https://github.com/jakehl/goid) | 40 | Generate and Parse RFC4122 compliant V4 UUIDs. |
| <b>[gouid](https://github.com/twharmon/gouid) | 22 | Generate cryptographically secure random string IDs with just one allocation. |
| <b>[uuid](https://github.com/agext/uuid) | 18 | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |
| <b>[goflake](https://github.com/hart87/GoFlake) | 12 | A small, scalable, & serverless unique ID generator for use in distributed systems. Inspired by Twitters Snowflake. |
| <b>[uniq](https://gitlab.com/skilstak/code/go/uniq) | - | No hassle safe, fast unique identifiers with commands. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Validation

_Libraries for validation._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[validator](https://github.com/go-playground/validator) | 15.0k | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| <b>[govalidator](https://github.com/asaskevich/govalidator) | 5.9k | Validators and sanitizers for strings, numerics, slices and structs. |
| <b>[ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 3.5k | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| <b>[govalidator](https://github.com/thedevsaddam/govalidator) | 1.3k | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| <b>[validate](https://github.com/gookit/validate) | 985 | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| <b>[checkdigit](https://github.com/osamingo/checkdigit) | 107 | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| <b>[jio](https://github.com/faceair/jio) | 96 | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| <b>[validate](https://github.com/gobuffalo/validate) | 92 | This package provides a framework for writing validations for Go applications. |
| <b>[terraform-validator](https://github.com/thazelart/terraform-validator) | 80 | A norms and conventions validator for Terraform. |
| <b>[gody](https://github.com/guiferpa/gody) | 66 | :balloon: A lightweight struct validator for Go. |
| <b>[govalid](https://github.com/twharmon/govalid) | 36 | Fast, tag-based validation for structs. |
| <b>[valix](https://github.com/marrow16/valix) | 23 | Go package for validating requests |
| <b>[Validator](https://github.com/go-the-way/validator) | 7 | A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Version Control

_Libraries for version control._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-git](https://github.com/go-git/go-git) | 5.3k | highly extensible Git implementation in pure Go. |
| <b>[glab](https://github.com/profclems/glab) | 2.1k | An open-source GitLab command line tool bringing GitLab's cool features to your command line. |
| <b>[hercules](https://github.com/src-d/hercules) | 2.0k | gaining advanced insights from Git repository history. |
| <b>[git2go](https://github.com/libgit2/git2go) | 1.9k | Go bindings for libgit2. |
| <b>[githooks](https://github.com/gabyx/githooks) | 87 | Per-repo and shared Git hooks with version control and auto update. |
| <b>[gh](https://github.com/rjeczalik/gh) | 82 | Scriptable server and net/http middleware for GitHub Webhooks. |
| <b>[go-vcs](https://github.com/sourcegraph/go-vcs) | 77 | manipulate and inspect VCS repositories in Go. |
| <b>[froggit-go](https://github.com/jfrog/froggit-go) | 41 | Froggit-Go is a Go library, allowing to perform actions on VCS providers. |
| <b>[hgo](https://github.com/beyang/hgo) | 17 | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |
| <b>[cli](https://gitlab.com/gitlab-org/cli) | - | An open-source GitLab command line tool bringing GitLab's cool features to your command line. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Video

_Libraries for manipulating video._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[goav](https://github.com/giorgisio/goav) | 2.1k | Comprehensive Go bindings for FFmpeg. |
| <b>[m3u8](https://github.com/grafov/m3u8) | 1.1k | Parser and generator library of M3U8 playlists for Apple HLS. |
| <b>[gmf](https://github.com/3d0c/gmf) | 869 | Go bindings for FFmpeg av\* libraries. |
| <b>[gortsplib](https://github.com/aler9/gortsplib) | 564 | Pure Go RTSP server and client library. |
| <b>[go-astisub](https://github.com/asticode/go-astisub) | 539 | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| <b>[go-astits](https://github.com/asticode/go-astits) | 513 | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| <b>[libvlc-go](https://github.com/adrg/libvlc-go) | 393 | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| <b>[gst](https://github.com/ziutek/gst) | 168 | Go bindings for GStreamer. |
| <b>[go-m3u8](https://github.com/quangngotan95/go-m3u8) | 109 | Parser and generator library for Apple m3u8 playlists. |
| <b>[v4l](https://github.com/korandiz/v4l) | 77 | Video capture library for Linux, written in Go. |
| <b>[libgosubs](https://github.com/wargarblgarbl/libgosubs) | 24 | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| <b>[go-m3u8](https://github.com/etherlabsio/go-m3u8) | 24 | Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility. |
| <b>[go-mpd](https://github.com/unki2aut/go-mpd) | 21 | Parser and generator library for MPEG-DASH manifest files. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Web Frameworks

_Full stack web frameworks._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Gin](https://github.com/gin-gonic/gin) | 74.0k | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| <b>[Beego](https://github.com/beego/beego) | 31.0k | beego is an open-source, high-performance web framework for the Go programming language. |
| <b>[Fiber](https://github.com/gofiber/fiber) | 30.0k | An Express.js inspired web framework build on Fasthttp. |
| <b>[Echo](https://github.com/labstack/echo) | 28.0k | High performance, minimalist Go web framework. |
| <b>[Revel](https://github.com/revel/revel) | 13.0k | High-productivity web framework for the Go language. |
| <b>[GoFrame](https://github.com/gogf/gf) | 11.0k | GoFrame is a modular, full-featured and production-ready application development framework of golang. |
| <b>[Goa](https://github.com/goadesign/goa) | 5.4k | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| <b>[Hertz](https://github.com/cloudwego/hertz) | 4.5k | A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices. |
| <b>[Gizmo](https://github.com/NYTimes/gizmo) | 3.7k | Microservice toolkit used by the New York Times. |
| <b>[go-json-rest](https://github.com/ant0ine/go-json-rest) | 3.5k | Quick and easy way to setup a RESTful JSON API. |
| <b>[Macaron](https://github.com/go-macaron/macaron) | 3.5k | Macaron is a high productive and modular design web framework in Go. |
| <b>[utron](https://github.com/gernest/utron) | 2.2k | Lightweight MVC framework for Go(Golang). |
| <b>[Goyave](https://github.com/go-goyave/goyave) | 1.4k | Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities. |
| <b>[REST Layer](https://github.com/rs/rest-layer) | 1.2k | Framework to build REST/GraphQL API on top of databases with mostly configuration over code. |
| <b>[Atreugo](https://github.com/savsgio/atreugo) | 1.2k | High performance and extensible micro web framework with zero memory allocations in hot paths. |
| <b>[tigertonic](https://github.com/rcrowley/go-tigertonic) | 996 | Go framework for building JSON web services inspired by Dropwizard. |
| <b>[tango](https://github.com/lunny/tango) | 835 | Micro & pluggable web framework for Go. |
| <b>[Gearbox](https://github.com/abahmed/gearbox) | 734 | A web framework written in Go with a focus on high performance and memory optimization. |
| <b>[GoFr](https://github.com/gofr-dev/gofr) | 695 | Gofr is an opinionated microservice development framework. |
| <b>[Aero](https://github.com/aerogo/aero) | 555 | High-performance web framework for Go, reaches top scores in Lighthouse. |
| <b>[gongular](https://github.com/mustafaakin/gongular) | 502 | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| <b>[rk-boot](https://github.com/rookie-ninja/rk-boot) | 471 | A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily. |
| <b>[Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 469 | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| <b>[Air](https://github.com/aofei/air) | 436 | An ideally refined web framework for Go. |
| <b>[Flamingo](https://github.com/i-love-flamingo/flamingo) | 419 | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| <b>[neo](https://github.com/ivpusic/neo) | 418 | Neo is minimal and fast Go Web Framework with extremely simple API. |
| <b>[Huma](https://github.com/danielgtaylor/huma/) | 401 | Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI. |
| <b>[mango](https://github.com/paulbellamy/mango) | 373 | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| <b>[Gondola](https://github.com/rainycape/gondola) | 311 | The web framework for writing faster sites, faster. |
| <b>[uAdmin](https://github.com/uadmin/uadmin) | 311 | Fully featured web framework for Golang, inspired by Django. |
| <b>[WebGo](https://github.com/bnkamalesh/webgo) | 293 | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| <b>[Ginrpc](https://github.com/xxjwxc/ginrpc) | 286 | Gin parameter automatic binding tool,gin rpc tools. |
| <b>[Golf](https://github.com/dinever/golf) | 270 | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| <b>[hiboot](https://github.com/hidevopsio/hiboot) | 180 | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| <b>[appy](https://github.com/appist/appy) | 130 | An opinionated productive web framework that helps scaling business easier. |
| <b>[go-rest](https://github.com/ungerik/go-rest) | 128 | Small and evil REST framework for Go. |
| <b>[patron](https://github.com/beatlabs/patron) | 124 | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| <b>[Microservice](https://github.com/claygod/microservice) | 114 | The framework for the creation of microservices, written in Golang. |
| <b>[rux](https://github.com/gookit/rux) | 96 | Simple and fast web framework for build golang HTTP applications. |
| <b>[vox](https://github.com/aisk/vox) | 83 | A golang web framework for humans, inspired by Koa heavily. |
| <b>[Golax](https://github.com/fulldump/golax) | 75 | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| <b>[YARF](https://github.com/yarf-framework/yarf) | 67 | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| <b>[Fireball](https://github.com/zpatrick/fireball) | 59 | More "natural" feeling web framework. |
| <b>[goa](https://github.com/goa-go/goa) | 49 | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| <b>[GoTuna](https://github.com/gotuna/gotuna) | 47 | Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embedded views and static files. |
| <b>[Pulse](https://github.com/gopulse/pulse) | 37 | Pulse is an HTTP web framework written in Go (Golang) |
| <b>[goweb](https://github.com/twharmon/goweb) | 37 | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |
| <b>[Resoursea](https://github.com/resoursea/api) | 34 | REST framework for quickly writing resource based services. |
| <b>[rex](https://github.com/goanywhere/rex) | 33 | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| <b>[Don](https://github.com/abemedia/go-don) | 33 | A highly performant and simple to use API framework. |
| <b>[Lit](https://github.com/jvcoutinho/lit) | 23 | Highly performant declarative web framework for Golang, aiming for simplicity and quality of life. |
| <b>[Banjo](https://github.com/nsheremet/banjo) | 22 | Very simple and fast web framework for Go. |
| <b>[golamb](https://github.com/twharmon/golamb) | 6 | Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway. |
| <b>[anoweb](https://github.com/go-the-way/anoweb) | 5 | The lightweight and powerful web framework using the new way for Go.Another go the way. |
| <b>[Pnutmux](https://gitlab.com/fruitygo/pnutmux) | - | Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting. |
| <b>[aah](https://aahframework.org) | - | Scalable, performant, rapid development Web framework for Go. |
| <b>[Buffalo](https://gobuffalo.io) | - | Bringing the productivity of Rails to Go! |
| <b>[Confetti Framework](https://confetti-framework.github.io/docs/) | - | Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go. |
| <b>[REST Layer](https://rest-layer.io) | - | Framework to build REST/GraphQL API on top of databases with mostly configuration over code. |


<br>

[👆back to top](#catalogue-list)


<br>

### Middlewares


<br>

#### Actual middlewares


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Tollbooth](https://github.com/didip/tollbooth) | 2.6k | Rate limit HTTP request handler. |
| <b>[CORS](https://github.com/rs/cors) | 2.5k | Easily add CORS capabilities to your API. |
| <b>[Limiter](https://github.com/ulule/limiter) | 1.9k | Dead simple rate limit middleware for Go. |
| <b>[go-server-timing](https://github.com/mitchellh/go-server-timing) | 857 | Add/parse Server-Timing header. |
| <b>[go-fault](https://github.com/github/go-fault) | 485 | Fault injection middleware for Go. |
| <b>[ln-paywall](https://github.com/philippgille/ln-paywall) | 138 | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| <b>[XFF](https://github.com/sebest/xff) | 98 | Handle `X-Forwarded-For` header and friends. |
| <b>[rk-grpc](https://github.com/rookie-ninja/rk-grpc) | 69 | Middleware for gRPC with logging, metrics, auth, tracing etc. |
| <b>[rk-gin](https://github.com/rookie-ninja/rk-gin) | 42 | Middleware for Gin framework with logging, metrics, auth, tracing etc. |
| <b>[formjson](https://github.com/rs/formjson) | 38 | Transparently handle JSON input as a standard form POST. |
| <b>[client-timing](https://github.com/posener/client-timing) | 24 | An HTTP client for Server-Timing header. |
| <b>[echo-middleware](https://github.com/faabiosr/echo-middleware) | 13 | Middleware for Echo framework with logging and metrics. |
| <b>[mid](https://github.com/bobg/mid) | 7 | Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more. |


<br>

[👆back to top](#catalogue-list)


<br>

#### Libraries for creating HTTP middlewares


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[negroni](https://github.com/urfave/negroni) | 7.4k | Idiomatic HTTP middleware for Golang. |
| <b>[alice](https://github.com/justinas/alice) | 2.9k | Painless middleware chaining for Go. |
| <b>[render](https://github.com/unrolled/render) | 1.9k | Go package for easily rendering JSON, XML, and HTML template responses. |
| <b>[stats](https://github.com/thoas/stats) | 593 | Go middleware that stores various information about your web application. |
| <b>[interpose](https://github.com/carbocation/interpose) | 293 | Minimalist net/http middleware for golang. |
| <b>[renderer](https://github.com/thedevsaddam/renderer) | 261 | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| <b>[muxchain](https://github.com/stephens2424/muxchain) | 208 | Lightweight middleware for net/http. |
| <b>[gores](https://github.com/alioygur/gores) | 102 | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| <b>[rye](https://github.com/InVisionApp/rye) | 102 | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| <b>[mediary](https://github.com/HereMobilityDevelopers/mediary) | 89 | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| <b>[chain](https://github.com/codemodus/chain) | 63 | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| <b>[go-wrap](https://github.com/go-on/wrap) | 59 | Small middlewares package for net/http. |
| <b>[catena](https://github.com/codemodus/catena) | 9 | http.Handler wrapper catenation (same API as "chain"). |


<br>

[👆back to top](#catalogue-list)


<br>

### Routers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[mux](https://github.com/gorilla/mux) | 20.0k | Powerful URL router and dispatcher for golang. |
| <b>[chi](https://github.com/go-chi/chi) | 16.0k | Small, fast and expressive HTTP router built on net/context. |
| <b>[httprouter](https://github.com/julienschmidt/httprouter) | 16.0k | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| <b>[gocraft/web](https://github.com/gocraft/web) | 1.5k | Mux and middleware package in Go. |
| <b>[Bone](https://github.com/go-zoo/bone) | 1.3k | Lightning Fast HTTP Multiplexer. |
| <b>[Goji](https://github.com/goji/goji) | 951 | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| <b>[fasthttprouter](https://github.com/buaazp/fasthttprouter) | 875 | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| <b>[httptreemux](https://github.com/dimfeld/httptreemux) | 614 | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| <b>[xujiajun/gorouter](https://github.com/xujiajun/gorouter) | 530 | A simple and fast HTTP router for Go. |
| <b>[ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 447 | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| <b>[lars](https://github.com/go-playground/lars) | 389 | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| <b>[Siesta](https://github.com/VividCortex/siesta) | 350 | Composable framework to write middleware and handlers. |
| <b>[vestigo](https://github.com/husobee/vestigo) | 268 | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| <b>[gowww/router](https://github.com/gowww/router) | 187 | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| <b>[GoRouter](https://github.com/vardius/gorouter) | 150 | GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| <b>[pure](https://github.com/go-playground/pure) | 148 | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| <b>[alien](https://github.com/gernest/alien) | 129 | Lightweight and fast http router from outer space. |
| <b>[violetear](https://github.com/nbari/violetear) | 107 | Go HTTP router. |
| <b>[Bxog](https://github.com/claygod/Bxog) | 103 | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| <b>[xmux](https://github.com/rs/xmux) | 98 | High performance muxer based on `httprouter` with `net/context` support. |
| <b>[goblin](https://github.com/bmf-san/goblin) | 72 | A golang http router based on trie tree. |
| <b>[ngamux](https://github.com/ngamux/ngamux) | 62 | Simple HTTP router for Go. |
| <b>[bellt](https://github.com/GuilhermeCaruso/bellt) | 54 | A simple Go HTTP router. |
| <b>[FastRouter](https://github.com/razonyang/fastrouter) | 23 | a fast, flexible HTTP router written in Go. |
| <b>[GoLobby/Router](https://github.com/golobby/router) | 22 | GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language. |
| <b>[nchi](https://github.com/muir/nchi) | 13 | chi-like router built on httprouter with dependency injection based middleware wrappers |
| <b>[goroute](https://github.com/goroute/route) | 9 | Simple yet powerful HTTP request multiplexer. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## WebAssembly


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[tinygo](https://github.com/tinygo-org/tinygo) | 14.0k | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| <b>[dom](https://github.com/dennwc/dom) | 483 | DOM library. |
| <b>[go-canvas](https://github.com/markfarnan/go-canvas) | 220 | Library to use HTML5 Canvas, with all drawing within go code. |
| <b>[wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 167 | Run Go WASM tests in your browser. |
| <b>[webapi](https://github.com/gowebapi/webapi) | 159 | Bindings for DOM and HTML generated from WebIDL. |
| <b>[vert](https://github.com/norunners/vert) | 96 | Interop between Go and JS values. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Windows


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-ole](https://github.com/go-ole/go-ole) | 1.1k | Win32 OLE implementation for golang. |
| <b>[d3d9](https://github.com/gonutz/d3d9) | 153 | Go bindings for Direct3D9. |
| <b>[gosddl](https://github.com/MonaxGT/gosddl) | 11 | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## XML

_Libraries and tools for manipulating XML._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[zek](https://github.com/miku/zek) | 719 | Generate a Go struct from XML. |
| <b>[xpath](https://github.com/antchfx/xpath) | 635 | XPath package for Go. |
| <b>[xquery](https://github.com/antchfx/xquery) | 157 | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| <b>[xml2map](https://github.com/sbabiv/xml2map) | 59 | XML to MAP converter written Golang. |
| <b>[xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 26 | Procedural XML generation API based on libxml2's xmlwriter module. |
| <b>[XML-Comp](https://github.com/xml-comp/xml-comp) | 21 | Simple command line XML comparer that generates diffs of folders, files and tags. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Zero Trust

_Libraries and tools to implement Zero Trust architectures._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Cosign](https://github.com/sigstore/cosign) | 3.9k | Container Signing, Verification and Storage in an OCI registry. |
| <b>[Spire](https://github.com/spiffe/spire) | 1.6k | SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms. |
| <b>[in-toto](https://github.com/in-toto/in-toto-golang) | 113 | Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation. |
| <b>[Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) | 71 | Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Code Analysis

_Source code analysis tools, also known as Static Application Security Testing (SAST) Tools._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golangci-lint](https://github.com/golangci/golangci-lint) | 14.0k | – A fast Go linters runner. It runs linters in parallel, uses caching, supports `yaml` config, has integrations with all major IDE and has dozens of linters included. |
| <b>[gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) | 5.8k | gosimple is a linter for Go source code that specialises on simplifying code. |
| <b>[staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) | 5.8k | staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#. |
| <b>[unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) | 5.8k | unused checks Go code for unused constants, variables, functions and types. |
| <b>[revive](https://github.com/mgechev/revive) | 4.5k | – ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for `golint`. |
| <b>[GoLint](https://github.com/golang/lint) | 4.0k | Golint is a linter for Go source code. |
| <b>[errcheck](https://github.com/kisielk/errcheck) | 2.2k | Errcheck is a program for checking for unchecked errors in Go programs. |
| <b>[go-critic](https://github.com/go-critic/go-critic) | 1.7k | source code linter that brings checks that are currently not implemented in other linters. |
| <b>[GoPlantUML](https://github.com/jfeliu007/goplantuml) | 1.6k | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| <b>[gcvis](https://github.com/davecheney/gcvis) | 1.1k | Visualise Go program GC trace data in real time. |
| <b>[php-parser](https://github.com/z7zmey/php-parser) | 935 | A Parser for PHP written in Go. |
| <b>[go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 804 | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| <b>[golines](https://github.com/segmentio/golines) | 768 | Formatter that automatically shortens long lines in Go code. |
| <b>[goast-viewer](https://github.com/yuroyoro/goast-viewer) | 743 | Web based Golang AST visualizer. |
| <b>[go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 642 | An easy way to find outdated dependencies of your Go projects. |
| <b>[Chronos](https://github.com/amit-davidson/Chronos) | 415 | Detects race conditions statically |
| <b>[todocheck](https://github.com/preslavmihaylov/todocheck) | 406 | Static code analyser which links TODO comments in code with issues in your issue tracker. |
| <b>[unconvert](https://github.com/mdempsky/unconvert) | 370 | Remove unnecessary type conversions from Go source. |
| <b>[vaccum](https://github.com/daveshanley/vacuum) | 355 | An ultra-super-fast, lightweight OpenAPI linter and quality checking tool. |
| <b>[dupl](https://github.com/mibk/dupl) | 323 | Tool for code clone detection. |
| <b>[tickgit](https://github.com/augmentable-dev/tickgit) | 316 | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| <b>[gostatus](https://github.com/shurcooL/gostatus) | 242 | Command line tool, shows the status of repositories that contain Go packages. |
| <b>[apicompat](https://github.com/bradleyfalzon/apicompat) | 177 | Checks recent changes to a Go project for backwards incompatible changes. |
| <b>[go-checkstyle](https://github.com/qiniu/checkstyle) | 128 | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| <b>[asty](https://github.com/asty-org/asty) | 68 | Converts golang AST to JSON and JSON to AST. |
| <b>[lint](https://github.com/surullabs/lint) | 66 | Run linters as part of go test. |
| <b>[validate](https://github.com/mccoyst/validate) | 61 | Automatically validates struct fields with tags. |
| <b>[ChainJacking](https://github.com/Checkmarx/chainjacking) | 53 | Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack. |
| <b>[testifylint](https://github.com/Antonboom/testifylint) | 48 | – A linter that checks usage of [github.com/stretchr/testify](https://github.com/stretchr/testify). |
| <b>[go-outdated](https://github.com/firstrow/go-outdated) | 44 | Console application that displays outdated packages. |
| <b>[usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) | 42 | A linter that detect the possibility to use variables/constants from the Go standard library. |
| <b>[tarp](https://github.com/verygoodsoftwarenotvirus/tarp) | 18 | tarp finds functions and methods without direct unit tests in Go source code. |
| <b>[golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) | 11 | iFood API SDK. |
| <b>[GoCover.io](https://gocover.io/) | - | GoCover.io offers the code coverage of any golang package as a service. |
| <b>[goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) | - | Tool to fix (add, remove) your Go imports automatically. |
| <b>[Golint online](http://go-lint.appspot.com/) | - | Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package. |
| <b>[goreturns](https://sourcegraph.com/github.com/sqs/goreturns) | - | Adds zero-value return statements to match the func return types. |
| <b>[blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) | - | blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Editor Plugins

_Plugin for text editors and IDEs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[vim-go](https://github.com/fatih/vim-go) | 16.0k | Go development plugin for Vim. |
| <b>[gocode](https://github.com/nsf/gocode) | 5.0k | Autocompletion daemon for the Go programming language. |
| <b>[vscode-go](https://github.com/golang/vscode-go) | 3.7k | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| <b>[GoSublime](https://github.com/DisposaBoy/GoSublime) | 3.4k | Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. |
| <b>[go-plus](https://github.com/joefitzgerald/go-plus) | 1.5k | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| <b>[go-mode](https://github.com/dominikh/go-mode.el) | 1.4k | Go mode for GNU/Emacs. |
| <b>[coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) | 558 | This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim. |
| <b>[goimports-reviser](https://github.com/incu6us/goimports-reviser) | 502 | Formatting tool for imports. |
| <b>[Watch](https://github.com/eaburns/Watch) | 201 | Runs a command in an acme win on file changes. |
| <b>[vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 87 | Vim plugin to highlight syntax errors on save. |
| <b>[go-language-server](https://github.com/theia-ide/go-language-server) | 32 | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| <b>[gounit-vim](https://github.com/hexdigest/gounit-vim) | 22 | Vim plugin for generating Go tests based on the function's or method's signature. |
| <b>[theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 15 | Go language support for the Theia IDE. |
| <b>[Go Doc](https://github.com/msyrus/vscode-go-doc) | 7 | A Visual Studio Code extension for showing definition in output and generating go doc. |
| <b>[Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) | - | Go plugin for JetBrains IDEs. |
| <b>[goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) | - | This extension adds benchmark profiling support for the Go language to VS Code. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Generate Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gotests](https://github.com/cweill/gotests) | 4.8k | Generate Go tests from your source code. |
| <b>[genny](https://github.com/cheekybits/genny) | 1.7k | Elegant generics for Go. |
| <b>[xgen](https://github.com/xuri/xgen) | 282 | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| <b>[re2dfa](https://github.com/opennota/re2dfa) | 193 | Transform regular expressions into finite state machines and output Go source code. |
| <b>[hasgo](https://github.com/DylanMeeus/hasgo) | 132 | Generate Haskell inspired functions for your slices. |
| <b>[gonerics](https://github.com/bouk/gonerics) | 114 | Idiomatic Generics in Go. |
| <b>[gocontracts](https://github.com/Parquery/gocontracts) | 104 | brings design-by-contract to Go by synchronizing the code with the documentation. |
| <b>[gounit](https://github.com/hexdigest/gounit) | 75 | Generate Go tests using your own templates. |
| <b>[sqlgen](https://github.com/anqiansong/sqlgen) | 73 | Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN. |
| <b>[options-gen](https://github.com/kazhuravlev/options-gen) | 49 | Functional options described by Dave Cheney's post "Functional options for friendly APIs". |
| <b>[generic](https://github.com/usk81/generic) | 48 | flexible data type for Go. |
| <b>[envdoc](https://github.com/g4s8/envdoc) | 20 | generate documentation for environment variables from Go source files. |
| <b>[godal](https://github.com/mafulong/godal) | 18 | Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm. |
| <b>[re2dfa](https://gitlab.com/opennota/re2dfa) | - | Transform regular expressions into finite state machines and output Go source code. |
| <b>[TOML-to-Go](https://xuri.me/toml-to-go) | - | Translates TOML into a Go type in the browser instantly. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-swagger](https://github.com/go-swagger/go-swagger) | 9.1k | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| <b>[go-callvis](https://github.com/TrueFurby/go-callvis) | 5.6k | Visualize call graph of your Go program using dot format. |
| <b>[OctoLinker](https://github.com/OctoLinker/browser-extension) | 5.2k | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| <b>[depth](https://github.com/KyleBanks/depth) | 868 | Visualize dependency trees of any package by analyzing imports. |
| <b>[richgo](https://github.com/kyoh86/richgo) | 825 | Enrich `go test` outputs with text decorations. |
| <b>[rts](https://github.com/galeone/rts) | 248 | RTS: response to struct. Generates Go structs from server responses. |
| <b>[godbg](https://github.com/tylerwince/godbg) | 199 | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| <b>[typex](https://github.com/dtgorski/typex) | 191 | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| <b>[roumon](https://github.com/becheran/roumon) | 160 | Monitor current state of all active goroutines via a command line interface. |
| <b>[gothanks](https://github.com/psampaz/gothanks) | 119 | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| <b>[colorgo](https://github.com/songgao/colorgo) | 113 | Wrapper around `go` command for colorized `go build` output. |
| <b>[gotestdox](https://github.com/bitfield/gotestdox) | 78 | Show Go test results as readable sentences. |
| <b>[igo](https://github.com/rocketlaunchr/igo) | 64 | An igo to go transpiler (new language features for Go language!) |
| <b>[go-james](https://github.com/pieterclaerhout/go-james) | 61 | Go project skeleton creator, builds and tests your projects without the manual setup. |
| <b>[go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 43 | Bash completion for go and wgo. |
| <b>[docs](https://github.com/go-oas/docs) | 32 | Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard. |
| <b>[gomodrun](https://github.com/dustinblackman/gomodrun/) | 31 | Go tool that executes and caches binaries included in go.mod files. |
| <b>[generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 25 | A [Yeoman](https://yeoman.io) generator to get new Go projects started. |
| <b>[modver](https://github.com/bobg/modver) | 12 | Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules. |
| <b>[textra](https://github.com/ravsii/textra) | 4 | Extract Go struct field names, types and tags for filtering and exporting. |
| <b>[decouple](https://github.com/bobg/decouple) | 1 | Find “overspecified” function parameters that could be generalized with interface types. |
| <b>[gotemplate.io](https://gotemplate.io/) | - | Online tool to preview `text/template` templates live. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Software Packages

_Software written in Go._


<br>

### DevOps Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[kubernetes](https://github.com/kubernetes/kubernetes) | 105.0k | Container Cluster Manager from Google. |
| <b>[Moby](https://github.com/moby/moby) | 67.0k | Collaborative project for the container ecosystem to assemble container-based systems. |
| <b>[traefik](https://github.com/containous/traefik) | 47.0k | Reverse proxy and load balancer with support for multiple backends. |
| <b>[Gitea](https://github.com/go-gitea/gitea) | 40.0k | Fork of Gogs, entirely community driven. |
| <b>[minikube](https://github.com/kubernetes/minikube) | 28.0k | Run Kubernetes locally. |
| <b>[k3s](https://github.com/k3s-io/k3s) | 26.0k | Lightweight Kubernetes. |
| <b>[k6](https://github.com/grafana/k6) | 23.0k | A modern load testing tool, using Go and JavaScript. |
| <b>[Vegeta](https://github.com/tsenart/vegeta) | 22.0k | HTTP load testing tool and library. It's over 9000! |
| <b>[Hey](https://github.com/rakyll/hey) | 17.0k | Hey is a tiny program that sends some load to a web application. |
| <b>[Packer](https://github.com/mitchellh/packer) | 15.0k | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| <b>[kind](https://github.com/kubernetes-sigs/kind) | 12.0k | Kubernetes IN Docker - local clusters for testing Kubernetes. |
| <b>[kubeshark](https://github.com/kubeshark/kubeshark) | 10.0k | API traffic analyzer for Kubernetes, inspired by Wireshark, purposely built for Kubernetes. |
| <b>[Mizu](https://github.com/up9inc/mizu) | 10.0k | API traffic viewer for Kubernetes enabling you to view all API communication between microservices, multiprotocol support: HTTP1.1, HTTP/2, AMQP, Kafka, Redis. |
| <b>[webhook](https://github.com/adnanh/webhook) | 9.6k | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| <b>[GVM](https://github.com/moovweb/gvm) | 9.3k | GVM provides an interface to manage Go versions. |
| <b>[Flannel](https://github.com/flannel-io/flannel) | 8.4k | Flannel is a network fabric for containers, designed for Kubernetes. |
| <b>[Ddosify](https://github.com/ddosify/ddosify) | 8.1k | High-performance load testing tool, written in Golang. |
| <b>[ko](https://github.com/google/ko) | 6.9k | Command line tool for building and deploying Go applications on Kubernetes |
| <b>[KubeVela](https://github.com/kubevela/kubevela) | 5.9k | Cloud native application delivery. |
| <b>[bombardier](https://github.com/codesenberg/bombardier) | 5.1k | Fast cross-platform HTTP benchmarking tool. |
| <b>[gaia](https://github.com/gaia-pipeline/gaia) | 5.1k | Build powerful pipelines in any programming language. |
| <b>[k3d](https://github.com/k3d-io/k3d) | 4.9k | Little helper to run CNCF's k3s in Docker. |
| <b>[script](https://github.com/bitfield/script) | 4.8k | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| <b>[gox](https://github.com/mitchellh/gox) | 4.6k | Dead simple, no frills Go cross compile tool. |
| <b>[Pomerium](https://github.com/pomerium/pomerium) | 3.8k | Pomerium is an identity-aware access proxy. |
| <b>[bosun](https://github.com/bosun-monitor/bosun) | 3.4k | Time Series Alerting Framework. |
| <b>[s5cmd](https://github.com/peak/s5cmd) | 2.2k | Blazing fast S3 and local filesystem execution tool. |
| <b>[kala](https://github.com/ajvb/kala) | 2.1k | Simplistic, modern, and performant job scheduler. |
| <b>[Fleet device management](https://github.com/fleetdm/fleet) | 1.9k | Lightweight, programmable telemetry for servers and workstations. |
| <b>[fac](https://github.com/mkchoi212/fac) | 1.8k | Command-line user interface to fix git merge conflicts. |
| <b>[goxc](https://github.com/laher/goxc) | 1.7k | build tool for Go, with a focus on cross-compiling and packaging. |
| <b>[StatusOK](https://github.com/sanathp/statusok) | 1.6k | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| <b>[ghorg](https://github.com/gabrie30/ghorg) | 1.4k | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket. |
| <b>[go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 1.4k | Enable your Go applications to self update. |
| <b>[s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1.1k | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| <b>[uTask](https://github.com/ovh/utask) | 1.1k | Automation engine that models and executes business processes declared in yaml. |
| <b>[PipeCD](https://github.com/pipe-cd/pipecd) | 925 | A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications. |
| <b>[skm](https://github.com/TimothyYe/skm) | 918 | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| <b>[kwatch](https://github.com/abahmed/kwatch) | 878 | Monitor & detect crashes in your Kubernetes(K8s) cluster instantly. |
| <b>[Scaleway-cli](https://github.com/scaleway/scaleway-cli) | 860 | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| <b>[cassowary](https://github.com/rogerwelin/cassowary) | 704 | Modern cross-platform HTTP load-testing tool written in Go. |
| <b>[kool](https://github.com/kool-dev/kool) | 654 | Command line tool for managing Docker environments as an easy way. |
| <b>[aurora](https://github.com/xuri/aurora) | 589 | Cross-platform web-based Beanstalkd queue server console. |
| <b>[govvv](https://github.com/ahmetalpbalkan/govvv) | 535 | “go build” wrapper to easily add version information into Go binaries. |
| <b>[Pewpew](https://github.com/bengadbois/pewpew) | 398 | Flexible HTTP command line stress tester. |
| <b>[jcli](https://github.com/jenkins-zh/jenkins-cli) | 372 | Jenkins CLI allows you manage your Jenkins as an easy way. |
| <b>[gonative](https://github.com/inconshreveable/gonative) | 338 | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| <b>[trubka](https://github.com/xitonix/trubka) | 331 | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| <b>[gobrew](https://github.com/kevincobain2000/gobrew) | 319 | Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash. |
| <b>[lstags](https://github.com/ivanilves/lstags) | 315 | Tool and API to sync Docker images across different registries. |
| <b>[Mora](https://github.com/emicklei/mora) | 314 | REST server for accessing MongoDB documents and meta data. |
| <b>[easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 299 | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| <b>[Balerter](https://github.com/balerter/balerter) | 296 | A self-hosted script-based alerting manager. |
| <b>[manssh](https://github.com/xwjdsh/manssh) | 291 | manssh is a command line tool for managing your ssh alias config easily. |
| <b>[terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 267 | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| <b>[dogo](https://github.com/liudng/dogo) | 259 | Monitoring changes in the source file and automatically compile and run (restart). |
| <b>[s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 247 | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| <b>[godbg](https://github.com/sirnewton01/godbg) | 227 | Web-based gdb front-end application. |
| <b>[Blast](https://github.com/dave/blast) | 214 | A simple tool for API load testing and batch jobs. |
| <b>[abbreviate](https://github.com/dnnrly/abbreviate) | 208 | abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs. |
| <b>[kcli](https://github.com/cswank/kcli) | 205 | Command line tool for inspecting kafka topics/partitions/messages. |
| <b>[gobrew](https://github.com/cryptojuice/gobrew) | 194 | gobrew lets you easily switch between multiple versions of go. |
| <b>[ostent](https://github.com/ostrost/ostent) | 178 | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| <b>[grapes](https://github.com/yaronsumel/grapes) | 166 | Lightweight tool designed to distribute commands over ssh with ease. |
| <b>[Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) | 161 | A go library and an executable that produces valid Dockerfiles using various input channels. |
| <b>[winrm-cli](https://github.com/masterzen/winrm-cli) | 161 | Cli tool to remotely execute commands on Windows machines. |
| <b>[tf-profile](https://github.com/datarootsio/tf-profile) | 135 | Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations. |
| <b>[drone-scp](https://github.com/appleboy/drone-scp) | 131 | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| <b>[Mantil](https://github.com/mantil-io/mantil) | 108 | Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure. |
| <b>[go-furnace](https://github.com/go-furnace/go-furnace) | 97 | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| <b>[go-rocket-update](https://github.com/mouuff/go-rocket-update) | 90 | A simple way to make self updating Go applications - Supports Github and Gitlab. |
| <b>[Dropship](https://github.com/chrismckenzie/dropship) | 64 | Tool for deploying code via cdn. |
| <b>[decompose](https://github.com/s0rg/decompose) | 61 | tool to generate and process Docker containers connections graphs. |
| <b>[docker-go-mingw](https://github.com/x1unix/docker-go-mingw) | 41 | Docker image for building Go binaries for Windows with MinGW toolchain. |
| <b>[drone-jenkins](https://github.com/appleboy/drone-jenkins) | 38 | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| <b>[httpref](https://github.com/dnnrly/httpref) | 35 | httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. |
| <b>[awsenv](https://github.com/soniah/awsenv) | 34 | Small binary that loads Amazon (AWS) environment variables for a profile. |
| <b>[Rodent](https://github.com/alouche/rodent) | 33 | Rodent helps you manage Go versions, projects and track dependencies. |
| <b>[lwc](https://github.com/timdp/lwc) | 32 | A live-updating version of the UNIX wc command. |
| <b>[DepCharge](https://github.com/centerorbit/depcharge) | 23 | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| <b>[wait-for](https://github.com/dnnrly/wait-for) | 18 | Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things. |
| <b>[aptly](https://github.com/smira/aptly) | 11 | aptly is a Debian repository management tool. |
| <b>[sg](https://github.com/ChristopherRabotin/sg) | 8 | Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. |
| <b>[gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) | - | Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance. |
| <b>[Gogs](https://gogs.io/) | - | A Self Hosted Git Service in the Go Programming Language. |
| <b>[Wide](https://wide.b3log.org/login) | - | Web-based IDE for Teams using Golang. |


<br>

[👆back to top](#catalogue-list)


<br>

### Other Software

_Where to discover new Go libraries._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[croc](https://github.com/schollz/croc) | 26.0k | Easily and securely send files or folders from one computer to another. |
| <b>[restic](https://github.com/restic/restic) | 23.0k | De-duplicating backup program. |
| <b>[Seaweed File System](https://github.com/chrislusf/seaweedfs) | 19.0k | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| <b>[Gor](https://github.com/buger/gor) | 18.0k | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| <b>[toxiproxy](https://github.com/shopify/toxiproxy) | 10.0k | Proxy to simulate network and system conditions for automated tests. |
| <b>[Comcast](https://github.com/tylertreat/Comcast) | 10.0k | Simulate bad network connections. |
| <b>[confd](https://github.com/kelseyhightower/confd) | 8.2k | Manage local application configuration files using templates and data from etcd or consul. |
| <b>[LiteIDE](https://github.com/visualfc/liteide) | 7.4k | LiteIDE is a simple, open source, cross-platform Go IDE. |
| <b>[drive](https://github.com/odeke-em/drive) | 6.6k | Google Drive client for the commandline. |
| <b>[scc](https://github.com/boyter/scc) | 5.6k | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| <b>[nes](https://github.com/fogleman/nes) | 5.3k | Nintendo Entertainment System (NES) emulator written in Go. |
| <b>[Duplicacy](https://github.com/gilbertchen/duplicacy) | 4.9k | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| <b>[blocky](https://github.com/0xERR0R/blocky) | 3.4k | Fast and lightweight DNS proxy as ad-blocker for local network with many features. |
| <b>[myLG](https://github.com/mehrdadrad/mylg) | 2.7k | Command Line Network Diagnostic tool written in Go. |
| <b>[GoBoy](https://github.com/Humpheh/goboy) | 2.6k | Nintendo Game Boy Color emulator written in Go. |
| <b>[Stack Up](https://github.com/pressly/sup) | 2.5k | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| <b>[lgo](https://github.com/yunabe/lgo) | 2.3k | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| <b>[Circuit](https://github.com/gocircuit/circuit) | 2.0k | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| <b>[Documize](https://github.com/documize/community) | 2.0k | Modern wiki software that integrates data from SaaS tools. |
| <b>[snap](https://github.com/intelsdi-x/snap) | 1.8k | Powerful telemetry framework. |
| <b>[borg](https://github.com/crufter/borg) | 1.6k | Terminal based search engine for bash snippets. |
| <b>[Plik](https://github.com/root-gg/plik) | 1.3k | Plik is a temporary file upload system (Wetransfer like) in Go. |
| <b>[shell2http](https://github.com/msoap/shell2http) | 1.2k | Executing shell commands via http server (for prototyping or remote control). |
| <b>[portal](https://github.com/SpatiumPortae/portal) | 1.1k | Portal is a quick and easy command-line file transfer utility from any computer to another. |
| <b>[vFlow](https://github.com/VerizonDigital/vflow) | 1000 | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| <b>[peg](https://github.com/pointlander/peg) | 957 | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| <b>[Go Package Store](https://github.com/shurcooL/Go-Package-Store) | 897 | App that displays updates for the Go packages in your GOPATH. |
| <b>[Gokapi](https://github.com/Forceu/gokapi) | 879 | Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload. |
| <b>[Leaps](https://github.com/jeffail/leaps) | 742 | Pair programming service using Operational Transforms. |
| <b>[gfile](https://github.com/Antonito/gfile) | 720 | Securely transfer files between two computers, without any third party, over WebRTC. |
| <b>[Guora](https://github.com/meloalright/guora) | 660 | A self-hosted Quora like web application written in Go. |
| <b>[sake](https://github.com/alajmo/sake) | 633 | sake is a command runner for local and remote hosts. |
| <b>[Gebug](https://github.com/moshebe/gebug) | 628 | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| <b>[gocc](https://github.com/goccmack/gocc) | 586 | Gocc is a compiler kit for Go written in Go. |
| <b>[mockingjay](https://github.com/quii/mockingjay-server) | 547 | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| <b>[yai](https://github.com/ekkinox/yai) | 478 | AI powered terminal assistant. |
| <b>[go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 464 | Video streaming torrent client. |
| <b>[woke](https://github.com/get-woke/woke) | 416 | Detect non-inclusive language in your source code. |
| <b>[ipe](https://github.com/dimiro1/ipe) | 366 | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| <b>[ide](https://github.com/thestrukture/ide) | 357 | Browser accessible IDE. Designed for Go with Go. |
| <b>[GoNB](https://github.com/janpfeifer/gonb) | 356 | Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab). |
| <b>[tcpprobe](https://github.com/mehrdadrad/tcpprobe) | 351 | TCP tool for network performance and path monitoring, including socket statistics. |
| <b>[wellington](https://github.com/wellington/wellington) | 305 | Sass project management tool, extends the language with sprite functions (like Compass). |
| <b>[Cherry](https://github.com/rafael-santiago/cherry) | 298 | Tiny webchat server in Go. |
| <b>[hotswap](https://github.com/edwingeng/hotswap) | 280 | A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure. |
| <b>[Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) | 278 | 🐮 cowsay is reborn. for a New Era. |
| <b>[tcpdog](https://github.com/mehrdadrad/tcpdog) | 248 | eBPF based TCP observability. |
| <b>[crawley](https://github.com/s0rg/crawley) | 214 | Web scraper/crawler for cli. |
| <b>[joincap](https://github.com/assafmo/joincap) | 200 | Command-line utility for merging multiple pcap files together. |
| <b>[Orbit](https://github.com/gulien/orbit) | 178 | A simple tool for running commands and generating files from templates. |
| <b>[vaku](https://github.com/lingrino/vaku) | 150 | CLI & API for folder-based functions in Vault like copy, move, and search. |
| <b>[stew](https://github.com/marwanhawari/stew) | 123 | An independent package manager for compiled binaries. |
| <b>[dp](https://github.com/scryinfo/dp) | 82 | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| <b>[boxed](https://github.com/tejo/boxed) | 80 | Dropbox based blog engine. |
| <b>[fjira](https://github.com/mk-5/fjira) | 68 | A fuzzy-search based terminal UI application for Attlasian Jira |
| <b>[term-quiz](https://github.com/crazcalm/term-quiz) | 26 | Quizzes for your terminal. |
| <b>[naclpipe](https://github.com/unix4fun/naclpipe) | 24 | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| <b>[Snitch](https://github.com/lucasgomide/snitch) | 17 | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| <b>[GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 13 | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |
| <b>[hoofli](https://github.com/dnnrly/hoofli) | 8 | Generate PlantUML diagrams from Chrome or Firefox network inspections. |
| <b>[protoncheck](https://github.com/servusdei2018/protoncheck) | 5 | ProtonMail module for waybar/polybar/yabar/i3blocks. |
| <b>[Juju](https://jujucharms.com/) | - | Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more. |
| <b>[limetext](https://limetext.github.io) | - | Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text. |
| <b>[syncthing](https://syncthing.net/) | - | Open, decentralized file synchronization tool and protocol. |
| <b>[tsuru](https://tsuru.io/) | - | Extensible and open source Platform as a Service software. |
| <b>[zs](https://git.mills.io/prologic/zs) | - | an extremely minimal static site generator. |
| <b>[Better Go Playground](https://goplay.tools) | - | Go playground with syntax highlight, code completion and other features. |
| <b>[Docker](https://www.docker.com/) | - | Open platform for distributed applications for developers and sysadmins. |
| <b>[goblin](https://goblin.reaper.im) | - | Golang binaries in a curl, built by goblins. |
| <b>[GoLand](https://jetbrains.com/go) | - | Full featured cross-platform Go IDE. |
| <b>[hugo](https://gohugo.io/) | - | Fast and Modern Static Website Engine. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Benchmarks


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 2.0k | Go web framework benchmark. |
| <b>[go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1.6k | Go HTTP request router benchmark and comparison. |
| <b>[go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1.5k | Benchmarks of Go serialization methods. |
| <b>[skynet](https://github.com/atemerev/skynet) | 1000 | Skynet 1M threads microbenchmark. |
| <b>[speedtest-resize](https://github.com/fawick/speedtest-resize) | 237 | Compare various Image resize algorithms for the Go language. |
| <b>[go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 145 | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| <b>[gospeed](https://github.com/feyeleanor/GoSpeed) | 115 | Go micro-benchmarks for calculating the speed of language constructs. |
| <b>[autobench](https://github.com/davecheney/autobench) | 98 | Framework to compare the performance between different Go versions. |
| <b>[golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 65 | Collection of benchmarks for popular Go database/SQL utilities. |
| <b>[gocostmodel](https://github.com/PuerkitoBio/gocostmodel) | 61 | Benchmarks of common basic operations for the Go language. |
| <b>[go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) | 29 | benchmarks for machine learning inference in Go. |
| <b>[go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 27 | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| <b>[kvbench](https://github.com/jimrobinson/kvbench) | 26 | Key/Value database benchmark. |
| <b>[go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) | 9 | Go JSON benchmark. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Conferences


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Capital Go](http://www.capitalgolang.com) | - | Washington, D.C., USA. |
| <b>[dotGo](https://www.dotgo.eu) | - | Paris, France. |
| <b>[GoCon](https://gocon.connpass.com/) | - | Tokyo, Japan. |
| <b>[GoDays](https://www.godays.io/) | - | Berlin, Germany. |
| <b>[GoLab](https://golab.io/) | - | Florence, Italy. |
| <b>[GopherChina](https://gopherchina.org) | - | Shanghai, China. |
| <b>[GopherCon](https://www.gophercon.com/) | - | Denver, USA. |
| <b>[GopherCon Australia](https://gophercon.com.au/) | - | Sydney, Australia. |
| <b>[GopherCon Brazil](https://gopherconbr.org) | - | Florianópolis, Brazil. |
| <b>[GopherCon Europe](https://gophercon.is/) | - | Berlin, Germany. |
| <b>[GopherCon India](https://www.gophercon.in/) | - | Pune, India. |
| <b>[GopherCon Israel](https://www.gophercon.org.il/) | - | Tel Aviv, Israel. |
| <b>[GopherCon Russia](https://www.gophercon-russia.ru) | - | Moscow, Russia. |
| <b>[GopherCon Singapore](https://gophercon.sg) | - | Mapletree Business City, Singapore. |
| <b>[GopherCon UK](https://www.gophercon.co.uk/) | - | London, UK. |
| <b>[GopherCon Vietnam](https://gophercon.vn/) | - | Ho Chi Minh City, Vietnam. |
| <b>[GoWayFest](https://goway.io/) | - | Minsk, Belarus. |
| <b>[GoWest Conference](https://www.gowestconf.com/) | - | Lehi, USA. |
| <b>[GopherCon Europe](https://gophercon.eu/) | - | Berlin, Germany. |
| <b>[GopherCon India](https://gopherconindia.org/) | - | Pune, India. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## E-Books


<br>

### E-books for purchase


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them) | - |  |
| <b>[Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go) | - |  |
| <b>[Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) | - | This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product. |
| <b>[For the Love of Go](https://bitfieldconsulting.com/books/love) | - | An introductory book for Go beginners. |
| <b>[Know Go: Generics](https://bitfieldconsulting.com/books/generics) | - | A guide to understanding and using generics in Go. |
| <b>[The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) | - | A guide to writing command-line tools in Go. |
| <b>[Writing A Compiler In Go](https://compilerbook.com) | - |  |
| <b>[Writing An Interpreter In Go](https://interpreterbook.com) | - | Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls. |
| <b>[The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) | - | A guide to testing in Go. |
| <b>[Black Hat Go](https://nostarch.com/blackhatgo) | - | Go programming for hackers and pentesters. |
| <b>[Go Faster](https://leanpub.com/gofaster) | - | This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster. |
| <b>[Lets-Go](https://lets-go.alexedwards.net) | - | A step-by-step guide to creating fast, secure and maintanable web applications with Go. |
| <b>[Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) | - | An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly. |
| <b>[Lets-Go-Further](https://lets-go-further.alexedwards.net) | - | Advanced patterns for building APIs and web applications in Go. |
| <b>[Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) | - | Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code. |


<br>

[👆back to top](#catalogue-list)


<br>

### Free e-books


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GoBooks](https://github.com/dariubs/GoBooks) | 16.0k | A curated list of Go books. |
| <b>[The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 9.4k | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| <b>[Go AST Book (Chinese)](https://github.com/chai2010/go-ast-book) | 5.2k | A book focusing on Go `go/*` packages. |
| <b>[Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) | 3.1k | Learn how to write webapps without a framework in Go. |
| <b>[Go Succinctly](https://github.com/thedevsir/gosuccinctly) | 22 | in Persian. |
| <b>[Go with the domain](https://threedots.tech/go-with-the-domain/) | - | A book showing how to apply DDD, Clean Architecture, and CQRS by practical refactoring. |
| <b>[A Go Developer's Notebook](https://leanpub.com/GoNotebook/read) | - |  |
| <b>[An Introduction to Programming in Go](http://www.golang-book.com/) | - |  |
| <b>[Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/) | - |  |
| <b>[Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/) | - |  |
| <b>[Go 101](https://go101.org) | - | A book focusing on Go syntax/semantics and all kinds of details. |
| <b>[Go Bootcamp](http://golangbootcamp.com) | - |  |
| <b>[How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) | - | A 600 page introduction to Go aimed at first time developers. |
| <b>[Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf) | - |  |
| <b>[Network Programming With Go](https://jan.newmarch.name/go/) | - |  |
| <b>[Practical Go Lessons](https://www.practical-go-lessons.com/) | - |  |
| <b>[Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/) | - |  |
| <b>[The Go Programming Language](https://www.gopl.io/) | - |  |
| <b>[Network Programming With Go](https://jan.newmarch.name/golang/) | - |  |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Gophers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gophers](https://github.com/egonelbre/gophers) | 3.3k | Free gophers. |
| <b>[Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) | 3.2k | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| <b>[gophers](https://github.com/ashleymcnamara/gophers) | 2.9k | Gopher artworks by Ashley McNamara. |
| <b>[gopherize.me](https://github.com/matryer/gopherize.me) | 664 | Gopherize yourself. |
| <b>[gophericons](https://github.com/shalakhin/gophericons) | 608 | 34 gopher images for Go developers community |
| <b>[gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 574 | gopher stickers |
| <b>[gophers](https://github.com/sillecelik/go-gopher) | 132 | Gopher amigurumi toy pattern. |
| <b>[gopher-logos](https://github.com/GolangUA/gopher-logos) | 118 | adorable gopher logos. |
| <b>[Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 67 | Go gopher Vector Data [.ai, .svg]. |
| <b>[gophers](https://github.com/rogeralsing/gophers) | 58 | random gopher graphics. |
| <b>[gophers](https://github.com/scraly/gophers) | 29 | Gophers by Aurélie Vache. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Meetups


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Bärner Go Meetup - Berne, Switzerland](https://www.meetup.com/berner-go-meetup/) | - |  |
| <b>[Zürich Gophers - Zurich, Switzerland](https://www.meetup.com/zurich-gophers/) | - |  |
| <b>[Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/) | - |  |
| <b>[Belfast Gophers](https://www.meetup.com/Belfast-Gophers/) | - |  |
| <b>[Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/) | - |  |
| <b>[Berlin Golang](https://www.meetup.com/golang-users-berlin/) | - |  |
| <b>[Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/) | - |  |
| <b>[Canberra Gophers](https://www.meetup.com/Canberra-Gophers/) | - |  |
| <b>[Go Language NYC](https://www.meetup.com/golanguagenewyork/) | - |  |
| <b>[Go London User Group](https://www.meetup.com/Go-London-User-Group/) | - |  |
| <b>[Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/) | - |  |
| <b>[Go Toronto](https://www.meetup.com/go-toronto/) | - |  |
| <b>[Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/) | - |  |
| <b>[GoBandung](https://www.meetup.com/GoBandung/) | - |  |
| <b>[GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/) | - |  |
| <b>[GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/) | - |  |
| <b>[GoJakarta](https://www.meetup.com/GoJakarta/) | - |  |
| <b>[Golang Amsterdam](https://www.meetup.com/golang-amsterdam/) | - |  |
| <b>[Golang Argentina](https://www.meetup.com/Golang-Argentina/) | - |  |
| <b>[Golang Athens](https://www.meetup.com/Athens-Gophers/) | - |  |
| <b>[Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/) | - |  |
| <b>[Golang Bangalore](https://www.meetup.com/Golang-Bangalore/) | - |  |
| <b>[Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/) | - |  |
| <b>[Golang Boston](https://www.meetup.com/bostongo/) | - |  |
| <b>[Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/) | - |  |
| <b>[Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/) | - |  |
| <b>[Golang Copenhagen](https://www.meetup.com/Go-Cph/) | - |  |
| <b>[Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/) | - |  |
| <b>[Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/) | - |  |
| <b>[Golang Dorset, UK](https://www.meetup.com/golang-dorset/) | - |  |
| <b>[Golang Estonia](https://www.meetup.com/Golang-Estonia/) | - |  |
| <b>[Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/) | - |  |
| <b>[Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/) | - |  |
| <b>[Golang Israel](https://www.meetup.com/Go-Israel/) | - |  |
| <b>[Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/) | - |  |
| <b>[Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/) | - |  |
| <b>[Golang Korea](https://www.meetup.com/GDG-Golang-Korea/) | - |  |
| <b>[Golang Lima - Peru](https://www.meetup.com/Golang-Peru/) | - |  |
| <b>[Golang Lyon](https://www.meetup.com/Golang-Lyon/) | - |  |
| <b>[Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/) | - |  |
| <b>[Golang Melbourne](https://www.meetup.com/golang-mel/) | - |  |
| <b>[Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/) | - |  |
| <b>[Golang New York](https://www.meetup.com/nycgolang/) | - |  |
| <b>[Golang North East](https://www.meetup.com/en-AU/Golang-North-East/) | - |  |
| <b>[Golang Paris](https://www.meetup.com/Golang-Paris/) | - |  |
| <b>[Golang Poland](https://www.meetup.com/Golang-Poland/) | - |  |
| <b>[Golang Pune](https://www.meetup.com/Golang-Pune/) | - |  |
| <b>[Golang Singapore](https://www.meetup.com/golangsg/) | - |  |
| <b>[Golang Stockholm](https://www.meetup.com/Go-Stockholm/) | - |  |
| <b>[Golang Sydney, AU](https://www.meetup.com/golang-syd/) | - |  |
| <b>[Golang São Paulo - Brazil](https://www.meetup.com/golangbr/) | - |  |
| <b>[Golang Taipei](https://www.meetup.com/golang-taipei-meetup/) | - |  |
| <b>[Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/) | - |  |
| <b>[Golang Turkey](https://kommunity.com/goturkiye) | - |  |
| <b>[Golang Vancouver, BC](https://www.meetup.com/golangvan/) | - |  |
| <b>[Golang Vienna, Austria](https://www.meetup.com/viennago/) | - |  |
| <b>[Golang Казань](https://www.meetup.com/GolangKazan/) | - |  |
| <b>[Golang Москва](https://www.meetup.com/Golang-Moscow/) | - |  |
| <b>[Golang Питер](https://www.meetup.com/Golang-Peter/) | - |  |
| <b>[GoSF - San Francisco, CA](https://www.meetup.com/golangsf) | - |  |
| <b>[Istanbul Golang](https://www.meetup.com/Istanbul-Golang/) | - |  |
| <b>[Seattle Go Programmers](https://www.meetup.com/golang/) | - |  |
| <b>[Ukrainian Golang User Groups](https://www.meetup.com/uagolang/) | - |  |
| <b>[Utah Go User Group](https://www.meetup.com/utahgophers/) | - |  |
| <b>[Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/) | - |  |
| <b>[Golang Rotterdam](https://www.meetup.com/golang-rotterdam/) | - |  |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Style Guides


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md) | 29.0k | CockroachDB - the open source, cloud-native distributed SQL database. |
| <b>[Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst) | 15.0k | Hyperledger Fabric is an enterprise-grade permissioned distributed ledger framework for developing solutions and applications. Its modular and versatile design satisfies a broad range of industry use cases. It offers a unique approach to consensus that enables performance at scale while preserving privacy. |
| <b>[Uber](https://github.com/uber-go/guide/blob/master/style.md) | 15.0k | The Uber Go Style Guide. |
| <b>[Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification) | 3.0k | Autonomous (self-hosted) BitTorrent DHT search engine suite. |
| <b>[bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) | 1.5k | 🏆 Opinionated Styleguide for the Go language |
| <b>[Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md) | 313 | Playbook da linguagem Go |
| <b>[GitLab](https://docs.gitlab.com/ee/development/go_guide/) | - |  |
| <b>[Sourcegraph](https://about.sourcegraph.com/handbook/engineering/go_style_guide) | - |  |
| <b>[Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/) | - |  |
| <b>[Google](https://google.github.io/styleguide/go/) | - |  |
| <b>[Sourcegraph](https://docs.sourcegraph.com/dev/background-information/languages/go) | - |  |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Social Media


<br>

### Twitter


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[@golang](https://twitter.com/golang) | - |  |
| <b>[@golang_news](https://twitter.com/golang_news) | - |  |
| <b>[@golangch](https://twitter.com/golangch) | - |  |
| <b>[@golangflow](https://twitter.com/golangflow) | - |  |
| <b>[@golangweekly](https://twitter.com/golangweekly) | - |  |
| <b>[@GoDiscussions](https://twitter.com/GoDiscussions) | - |  |


<br>

[👆back to top](#catalogue-list)


<br>

### Reddit


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[r/golang](https://www.reddit.com/r/golang/) | - |  |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Websites


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Go Projects](https://github.com/golang/go/wiki/Projects) | 117.0k | List of projects on the Go community wiki. |
| <b>[awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 31.0k | List of other amazingly awesome lists. |
| <b>[Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) | 27.0k | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| <b>[Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) | 490 | A curated list of awesome golang workshops. |
| <b>[golang-graphics](https://github.com/mholt/golang-graphics) | 139 | Collection of Go images, graphics, and art. |
| <b>[gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 41 | Collection of Go projects that needs help. Good place to start your open-source way in Go. |
| <b>[awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) | 22 | Parse awesome-go README file and generate a new README file with repo info. |
| <b>[Explore Go Libraries & Projects](https://kandi.openweaver.com/explore/go) | - | Discover & find a curated list of popular & new Go libraries, top authors, trending project kits, discussions, tutorials & learning resources on kandi. |
| <b>[Golang Weekly](https://discu.eu/weekly/golang/) | - | Each monday projects, tutorials and articles about Go. |
| <b>[Awesome Go @LibHunt](https://go.libhunt.com) | - | Your go-to Go Toolbox. |
| <b>[Code with Mukesh](https://codewithmukesh.com/blog/category/golang) | - | Software Engineer and Blogs @ codewithmukesh.com. |
| <b>[Coding Mystery](https://codingmystery.com) | - | Solve exciting escape-room-inspired programming challenges using Go. |
| <b>[CodinGame](https://www.codingame.com/) | - | Learn Go by solving interactive tasks using small games as practical examples. |
| <b>[Go Blog](https://blog.golang.org) | - | The official Go blog. |
| <b>[Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) | - | A group of Gophers read and discuss a different Go project every week. |
| <b>[Go Community on Hashnode](https://hashnode.com/n/go) | - | Community of Gophers on Hashnode. |
| <b>[Go Forum](https://forum.golangbridge.org) | - | Forum to discuss Go. |
| <b>[Go In 5 Minutes](https://www.goin5minutes.com/) | - | 5 minute screencasts focused on getting one thing done. |
| <b>[Go Proverbs](https://go-proverbs.github.io/) | - | Go Proverbs by Rob Pike. |
| <b>[Go Report Card](https://goreportcard.com) | - | A report card for your Go package. |
| <b>[go.dev](https://go.dev/) | - | A hub for Go developers. |
| <b>[godoc.org](https://godoc.org/) | - | Documentation for open source Go packages. |
| <b>[Golang Developer Jobs](https://golangjob.xyz) | - | Developer Jobs exclusivly for Golang related Roles. |
| <b>[Golang Flow](https://golangflow.io) | - | Post Updates, News, Packages and more. |
| <b>[Golang News](https://golangnews.com) | - | Links and news about Go programming. |
| <b>[Golang Resources](https://golangresources.com) | - | A curation of the best articles, exercises, talks and videos to learn Go. |
| <b>[golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) | - | Go mailing list. |
| <b>[Google Plus Community](https://plus.google.com/communities/114112804251407510571) | - | The Google+ community for #golang enthusiasts. |
| <b>[Gopher Community Chat](https://invite.slack.golangbridge.org) | - | Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)). |
| <b>[Gophercises](https://gophercises.com/) | - | Free coding exercises for budding gophers. |
| <b>[gowalker.org](https://gowalker.org) | - | Go Project API documentation. |
| <b>[json2go](https://m-zajac.github.io/json2go) | - | Advanced JSON to Go struct conversion - online tool. |
| <b>[justforfunc](https://www.youtube.com/c/justforfunc) | - | Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc). |
| <b>[Learn Go Programming](https://blog.learngoprogramming.com) | - | Learn Go concepts with illustrations. |
| <b>[Lille Gophers](https://lille-gophers.loscrackitos.codes/) | - | Golang talks community in Lille, France ([@LilleGophers](https://twitter.com/LilleGophers)). |
| <b>[Made with Golang](https://madewithgolang.com/?ref=awesome-go) | - |  |
| <b>[r/Golang](https://www.reddit.com/r/golang) | - | News about Go. |
| <b>[studygolang](https://studygolang.com) | - | The community of studygolang in China. |
| <b>[Trending Go repositories on GitHub today](https://github.com/trending?l=go) | - | Good place to find new Go libraries. |
| <b>[TutorialEdge - Golang](https://tutorialedge.net/course/golang/) | - |  |


<br>

[👆back to top](#catalogue-list)


<br>

### Tutorials


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) | 43.0k | Golang ebook intro how to build a web app with golang. |
| <b>[go-patterns](https://github.com/tmrts/go-patterns) | 24.0k | Curated list of Go design patterns, recipes and idioms. |
| <b>[Learn Go with TDD](https://github.com/quii/learn-go-with-tests) | 21.0k | Learn Go with test-driven development. |
| <b>[Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) | 18.0k | Learn Go with thousands of examples, exercises, and quizzes. |
| <b>[Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) | 8.0k | Go's reference card. |
| <b>[go-clean-template](https://github.com/evrone/go-clean-template) | 5.8k | Clean Architecture template for Golang services. |
| <b>[Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 4.4k | Examples of Golang compared to Node.js for learning. |
| <b>[Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) | 1.7k | A little e-book on Ethereum Development with Go. |
| <b>[Working with Go](https://github.com/mkaz/working-with-go) | 1.2k | Intro to go for experienced programmers. |
| <b>[goapp](https://github.com/bnkamalesh/goapp) | 707 | An opinionated guideline to structure & develop a Go web application/service. |
| <b>[Go in 7 days](https://github.com/harrytran103/7_days_of_go) | 134 | Learn everything about Go in 7 days (from a Nodejs developer). |
| <b>[Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) | 108 | Collection of programming design patterns implemented in Go. |
| <b>[Hex Monscape](https://github.com/Haraj-backend/hex-monscape) | 49 | Getting started guidelines in writing maintainable code using Hexagonal Architecture. |
| <b>[Debugged.it Go patterns](https://github.com/haveyoudebuggedit/go-patterns) | 10 | Advanced Go patterns with ready-to-run examples. |
| <b>[Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) | - | A List of Free Courses to Learn the Go Programming Language. |
| <b>[Golangbot](https://golangbot.com/learn-golang-series/) | - | Tutorials to get started with programming in Go. |
| <b>[GolangCode](https://golangcode.com/) | - | Collection of code snippets and tutorials to help tackle every day issues. |
| <b>[GopherSnippets](https://gophersnippets.com/) | - | Code snippets with tests and testable examples for the Go programming language. |
| <b>[Gosamples](https://gosamples.dev/) | - | Collection of code snippets that let you solve everyday code problems. |
| <b>[Hackr.io](https://hackr.io/tutorials/learn-golang) | - | Learn Go from the best online golang tutorials submitted & voted by the golang programming community. |
| <b>[How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) | - | Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM. |
| <b>[CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) | - | — Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more. |
| <b>[How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) | - | Learn how to use Docker for Go development and how to build production Docker images. |
| <b>[How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) | - | Get started with Godog — a Behavior-driven development framework for building and testing Go applications. |
| <b>[Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) | - | Serie of article in order to learn Golang language by concrete applications as example. |
| <b>[Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) | - | Getting started with golang for beginner. |
| <b>[package main](https://www.youtube.com/packagemain) | - | YouTube channel about Programming in Go. |
| <b>[Programming with Google Go](https://www.coursera.org/specializations/google-golang) | - | Coursera Specialization to learn about Go from scratch. |
| <b>[Saving a Third of Our Memory by Re-ordering Go Struct Fields](https://qvault.io/golang/struct-field-ordering-memory/) | - | How inefficient field ordering in Go structs. |
| <b>[The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02) | - |  |
| <b>[Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) | - | A video series teaching programming and game development. |
| <b>[Your basic Go](https://yourbasic.org/golang) | - | Huge collection of tutorials and how to's. |
| <b>[GopherCoding](https://gophercoding.com/) | - | Collection of code snippets and tutorials to help tackle every day issues. |
| <b>[A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) | - | Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library. |
| <b>[Build a Database in 1000 lines of code](https://link.medium.com/O9YQlx89Htb) | - | Build a NoSQL Database From Zero in 1000 Lines of Code. |
| <b>[Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) | - | Dive deep into building microservices using Go, including gRPC. |
| <b>[Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) | - | Everything about building, deploying and scaling Go applications in production. |
| <b>[W3basic Go Tutorials](https://www.w3basic.com/golang/) | - | W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming. |
| <b>[50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) | - | Traps, Gotchas, and Common Mistakes for New Golang Devs. |
| <b>[A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) | - | Building a Golang site for e-commerce (demo included). |
| <b>[A Tour of Go](https://tour.golang.org/) | - | Interactive tour of Go. |
| <b>[Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) | - | We’ll write an API with the help of the powerful Gorilla Mux. |
| <b>[Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) | - | Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline. |
| <b>[Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) | - | How to cache slow database queries. |
| <b>[Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) | - | How to cancel MySQL queries. |
| <b>[Games With Go](https://gameswithgo.org/) | - | A video series teaching programming and game development. |
| <b>[Go By Example](https://gobyexample.com/) | - | Hands-on introduction to Go using annotated example programs. |
| <b>[Go database/sql tutorial](http://go-database-sql.org/) | - | Introduction to database/sql. |
| <b>[Go Language Tutorial](https://www.javatpoint.com/go-tutorial) | - | Learn Go language Tutorial. |
| <b>[Go Playground for iOS](https://codeplayground.app) | - | Interactively edit & play Go snippets on your mobile device. |
| <b>[Go Tutorial](https://www.tutorialspoint.com/go/index.htm) | - | Learn Go programming. |
| <b>[Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/) | - |  |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Websites

