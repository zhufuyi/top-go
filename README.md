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
| <b>[Oto](https://github.com/hajimehoshi/oto) | 1.3k | A low-level library to play sound on multiple platforms. |
| <b>[PortAudio](https://github.com/gordonklaus/portaudio) | 599 | Go bindings for the PortAudio audio I/O library. |
| <b>[music-theory](https://github.com/go-music-theory/music-theory) | 417 | Music theory models in Go. |
| <b>[id3v2](https://github.com/bogem/id3v2) | 290 | ID3 decoding and encoding library for Go. |
| <b>[GoAudio](https://github.com/DylanMeeus/GoAudio) | 283 | Native Go Audio Processing Library. |
| <b>[flac](https://github.com/mewkiz/flac) | 249 | Native Go FLAC encoder/decoder with support for FLAC streams. |
| <b>[malgo](https://github.com/gen2brain/malgo) | 220 | Mini audio library. |
| <b>[gaad](https://github.com/Comcast/gaad) | 111 | Native Go AAC bitstream parser. |
| <b>[minimp3](https://github.com/tosone/minimp3) | 103 | Lightweight MP3 decoder library. |
| <b>[gosamplerate](https://github.com/dh1tw/gosamplerate) | 27 | libsamplerate bindings for go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Authentication and OAuth

_Libraries for implementing authentications schemes._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[casbin](https://github.com/hsluoyz/casbin) | 15.0k | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| <b>[jwt-go](https://github.com/golang-jwt/jwt) | 4.8k | A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs. |
| <b>[oauth2](https://github.com/golang/oauth2) | 4.7k | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| <b>[goth](https://github.com/markbates/goth) | 4.2k | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| <b>[keto](https://github.com/ory/keto) | 4.1k | Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models. |
| <b>[authboss](https://github.com/volatiletech/authboss) | 3.4k | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| <b>[go-jose](https://github.com/square/go-jose) | 2.0k | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| <b>[loginsrv](https://github.com/tarent/loginsrv) | 1.9k | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| <b>[osin](https://github.com/openshift/osin) | 1.8k | Golang OAuth2 server library. |
| <b>[gologin](https://github.com/dghubble/gologin) | 1.6k | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| <b>[gorbac](https://github.com/mikespook/gorbac) | 1.5k | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| <b>[scs](https://github.com/alexedwards/scs) | 1.5k | Session Manager for HTTP servers. |
| <b>[paseto](https://github.com/o1egl/paseto) | 716 | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| <b>[jwt](https://github.com/cristalhq/jwt) | 602 | Safe, simple and fast JSON Web Tokens for Go. |
| <b>[permissions2](https://github.com/xyproto/permissions2) | 482 | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| <b>[go-guardian](https://github.com/shaj13/go-guardian) | 469 | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| <b>[jwt](https://github.com/pascaldekloe/jwt) | 334 | Lightweight JSON Web Token (JWT) library. |
| <b>[jeff](https://github.com/abraithwaite/jeff) | 256 | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| <b>[jwt-auth](https://github.com/adam-hanna/jwt-auth) | 226 | JWT middleware for Golang http servers with many configuration options. |
| <b>[go-jose](https://github.com/go-jose/go-jose) | 131 | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| <b>[otpgen](https://github.com/grijul/otpgen) | 130 | Library to generate TOTP/HOTP codes. |
| <b>[sessionup](https://github.com/swithek/sessionup) | 119 | Simple, yet effective HTTP session management and identification package. |
| <b>[sjwt](https://github.com/brianvoe/sjwt) | 112 | Simple jwt generator and parser. |
| <b>[session](https://github.com/icza/session) | 111 | Go session management for web servers (including support for Google App Engine - GAE). |
| <b>[rbac](https://github.com/zpatrick/rbac) | 106 | Minimalistic RBAC package for Go applications. |
| <b>[sessions](https://github.com/adam-hanna/sessions) | 74 | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| <b>[securecookie](https://github.com/chmike/securecookie) | 72 | Efficient secure cookie encoding/decoding. |
| <b>[branca](https://github.com/essentialkaos/branca) | 58 | branca token [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+. |
| <b>[otpgo](https://github.com/jltorresm/otpgo) | 57 | Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. |
| <b>[go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) | 56 | Golang library for providing a canonical representation of email address. |
| <b>[scope](https://github.com/SonicRoshan/scope) | 30 | Easily Manage OAuth2 Scopes In Go. |
| <b>[cookiestxt](https://github.com/mengzhuo/cookiestxt) | 12 | provides parser of cookies.txt file format. |
| <b>[gosession](http://github.com/Kwynto/gosession) | 0 | This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, at least it tries to become one. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Blockchain

_Tools for building blockchains._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-ethereum](https://github.com/ethereum/go-ethereum) | 43.0k | Official Go implementation of the Ethereum protocol. |
| <b>[tendermint](https://github.com/tendermint/tendermint) | 5.5k | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| <b>[cosmos-sdk](https://github.com/cosmos/cosmos-sdk) | 5.2k | A Framework for Building Public Blockchains in the Cosmos Ecosystem. |
| <b>[solana-go](https://github.com/gagliardetto/solana-go) | 428 | Go library to interface with Solana JSON RPC and WebSocket interfaces. |
| <b>[gossamer](https://github.com/ChainSafe/gossamer) | 388 | A Go implementation of the Polkadot Host. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Bot Building

_Libraries for building and working with bots._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) | 4.7k | Simple and clean Telegram bot client. |
| <b>[olivia](https://github.com/olivia-ai/olivia) | 3.5k | A chatbot built with an artificial neural network. |
| <b>[telebot](https://github.com/tucnak/telebot) | 3.1k | Telegram bot framework written in Go. |
| <b>[wayback](https://github.com/wabarc/wayback) | 1.3k | A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages. |
| <b>[Kelp](https://github.com/stellar/kelp) | 991 | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| <b>[Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) | 910 | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| <b>[go-chat-bot](https://github.com/go-chat-bot/bot) | 782 | IRC, Slack & Telegram bot written in Go. |
| <b>[slacker](https://github.com/shomali11/slacker) | 765 | Easy to use framework to create Slack bots. |
| <b>[tbot](https://github.com/yanzay/tbot) | 336 | Telegram bot server with API similar to net/http. |
| <b>[go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 295 | Library to write bots for twitch.tv chat |
| <b>[echotron](https://github.com/NicoNex/echotron) | 260 | An elegant and concurrent library for Telegram Bots in Go. |
| <b>[go-sarah](https://github.com/oklahomer/go-sarah) | 258 | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| <b>[telego](https://github.com/mymmrac/telego) | 212 | Telegram Bot API library for Golang with full one-to-one API implementation. |
| <b>[Tenyks](https://github.com/kyleterry/tenyks) | 175 | Service oriented IRC bot using Redis and JSON for messaging. |
| <b>[hanu](https://github.com/sbstjn/hanu) | 143 | Framework for writing Slack bots. |
| <b>[larry](https://github.com/ezeoleaf/larry) | 143 | Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go. |
| <b>[slack-bot](https://github.com/innogames/slack-bot) | 139 | Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github... |
| <b>[go-tgbot](https://github.com/olebedev/go-tgbot) | 118 | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| <b>[bot](https://github.com/go-telegram/bot) | 114 | Zero-dependencies Telegram Bot library with additional UI components |
| <b>[ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 79 | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| <b>[margelet](https://github.com/zhulik/margelet) | 79 | Framework for building Telegram bots. |
| <b>[slackscot](https://github.com/alexandre-normand/slackscot) | 54 | Another framework for building Slack bots. |
| <b>[govkbot](https://github.com/nikepan/govkbot) | 43 | Simple Go [VK](https://vk.com) bot library. |
| <b>[micha](https://github.com/onrik/micha) | 25 | Go Library for Telegram bot api. |
| <b>[teleterm](https://github.com/alfiankan/teleterm) | 21 | Telegram Bot Exec Terminal Command. |
| <b>[go-joe](https://joe-bot.net) | - | A general-purpose bot library inspired by Hubot but written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Build Automation

_Libraries and tools helping with build automation._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Task](https://github.com/go-task/task) | 7.7k | simple "Make" alternative. |
| <b>[realize](https://github.com/tockins/realize) | 4.4k | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| <b>[mage](https://github.com/magefile/mage) | 3.6k | Mage is a make/rake-like build tool using Go. |
| <b>[mmake](https://github.com/tj/mmake) | 1.7k | Modern Make. |
| <b>[xc](https://github.com/joerdav/xc) | 848 | Task runner with README.md defined tasks, executable markdown. |
| <b>[goyek](https://github.com/goyek/goyek) | 384 | Create build pipelines in Go. |
| <b>[taskctl](https://github.com/taskctl/taskctl) | 253 | Concurrent task runner. |
| <b>[1build](https://github.com/gopinath-langote/1build) | 211 | Command line tool to frictionlessly manage project-specific commands. |
| <b>[gaper](https://github.com/maxcnunes/gaper) | 71 | Builds and restarts a Go project when it crashes or some watched file changes. |
| <b>[anko](https://github.com/GuilhermeCaruso/anko) | 28 | Simple application watcher for multiple programming languages. |
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
| <b>[bubbletea](https://github.com/charmbracelet/bubbletea) | 19.0k | Go framework to build terminal apps, based on The Elm Architecture. |
| <b>[termui](https://github.com/gizak/termui) | 13.0k | Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). |
| <b>[gocui](https://github.com/jroimartin/gocui) | 9.1k | Minimalist Go library aimed at creating Console User Interfaces. |
| <b>[lipgloss](https://github.com/charmbracelet/lipgloss) | 5.9k | Declaratively define styles for color, format and layout in the terminal. |
| <b>[go-prompt](https://github.com/c-bata/go-prompt) | 4.9k | Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). |
| <b>[termbox-go](https://github.com/nsf/termbox-go) | 4.5k | Termbox is a library for creating cross-platform text-based interfaces. |
| <b>[pterm](https://github.com/pterm/pterm) | 3.8k | A library to beautify console output on every platform with many combinable components. |
| <b>[bubbles](https://github.com/charmbracelet/bubbles) | 3.4k | TUI components for bubbletea. |
| <b>[progressbar](https://github.com/schollz/progressbar) | 3.3k | Basic thread-safe progress bar that works in every OS. |
| <b>[termdash](https://github.com/mum4k/termdash) | 2.3k | Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). |
| <b>[asciigraph](https://github.com/guptarohit/asciigraph) | 2.2k | Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. |
| <b>[mpb](https://github.com/vbauerster/mpb) | 2.1k | Multi progress bar for terminal applications. |
| <b>[spinner](https://github.com/briandowns/spinner) | 2.1k | Go package to easily provide a terminal spinner with options. |
| <b>[uiprogress](https://github.com/gosuri/uiprogress) | 2.0k | Flexible library to render progress bars in terminal applications. |
| <b>[uilive](https://github.com/gosuri/uilive) | 1.6k | Library for updating terminal output in realtime. |
| <b>[termenv](https://github.com/muesli/termenv) | 1.4k | Advanced ANSI style & color support for your terminal applications. |
| <b>[aurora](https://github.com/logrusorgru/aurora) | 1.3k | ANSI terminal colors that supports fmt.Printf/Sprintf. |
| <b>[gookit/color](https://github.com/gookit/color) | 1.3k | Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. |
| <b>[go-isatty](https://github.com/mattn/go-isatty) | 710 | isatty for golang. |
| <b>[uitable](https://github.com/gosuri/uitable) | 708 | Library to improve readability in terminal apps using tabular data. |
| <b>[go-colorable](https://github.com/mattn/go-colorable) | 695 | Colorable writer for windows. |
| <b>[gommon/color](https://github.com/labstack/gommon/tree/master/color) | 489 | Style terminal text. |
| <b>[simpletable](https://github.com/alexeyco/simpletable) | 455 | Simple tables in terminal with Go. |
| <b>[chalk](https://github.com/ttacon/chalk) | 424 | Intuitive package for prettifying terminal/console output. |
| <b>[yacspin](https://github.com/theckman/yacspin) | 398 | Yet Another CLi Spinner package, for working with terminal spinners. |
| <b>[box-cli-maker](https://github.com/Delta456/box-cli-maker) | 359 | Make Highly Customized Boxes for your CLI. |
| <b>[tabby](https://github.com/cheynewallace/tabby) | 329 | A tiny library for super simple Golang tables. |
| <b>[go-colortext](https://github.com/daviddengcn/go-colortext) | 215 | Go library for color output in terminals. |
| <b>[cfmt](https://github.com/mingrammer/cfmt) | 94 | Contextual fmt inspired by bootstrap color classes. |
| <b>[tabular](https://github.com/InVisionApp/tabular) | 69 | Print ASCII tables from command line utilities without the need to pass large sets of data to the API. |
| <b>[cfmt](https://github.com/i582/cfmt) | 57 | Simple and convenient formatted stylized output fully compatible with fmt library. |
| <b>[table](https://github.com/tomlazar/table) | 44 | Small library for terminal color based tables . |
| <b>[ctc](https://github.com/wzshiming/ctc) | 42 | The non-invasive cross-platform terminal color library does not need to modify the Print method. |
| <b>[marker](https://github.com/cyucelen/marker) | 40 | Easiest way to match and mark strings for colorful terminal outputs. |
| <b>[colourize](https://github.com/TreyBastian/colourize) | 26 | Go library for ANSI colour text in terminals. |
| <b>[go-ataman](https://github.com/workanator/go-ataman) | 14 | Go library for rendering ANSI colored text templates in terminals. |
| <b>[go-palette](https://github.com/abusomani/go-palette) | 9 | Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts. |
| <b>[crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) | 6 | Dynamic configuration file templating tool for kubernetes manifest or general configuration files. |


<br>

[👆back to top](#catalogue-list)


<br>

### Standard CLI

_Libraries for building standard or basic Command Line applications._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cobra](https://github.com/spf13/cobra) | 32.0k | Commander for modern Go CLI interactions. |
| <b>[urfave/cli](https://github.com/urfave/cli) | 20.0k | Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). |
| <b>[elvish](https://github.com/elves/elvish) | 5.1k | An expressive programming language and a versatile interactive shell. |
| <b>[survey](https://github.com/go-survey/survey) | 3.8k | Build interactive and accessible prompts with full support for windows and posix terminals. |
| <b>[kingpin](https://github.com/alecthomas/kingpin) | 3.3k | Command line and flag parser supporting sub commands (superseded by `kong`; see below). |
| <b>[Dnote](https://github.com/dnote/dnote) | 2.5k | A simple command line notebook with multi-device sync. |
| <b>[go-flags](https://github.com/jessevdk/go-flags) | 2.4k | go command line option parser. |
| <b>[pflag](https://github.com/spf13/pflag) | 2.1k | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. |
| <b>[mitchellh/cli](https://github.com/mitchellh/cli) | 1.7k | Go library for implementing command-line interfaces. |
| <b>[go-arg](https://github.com/alexflint/go-arg) | 1.6k | Struct-based argument parsing in Go. |
| <b>[ops](https://github.com/nanovms/ops) | 1.1k | Unikernel Builder/Orchestrator. |
| <b>[liner](https://github.com/peterh/liner) | 968 | Go readline-like library for command-line interfaces. |
| <b>[complete](https://github.com/posener/complete) | 884 | Write bash completions in Go + Go command bash completion. |
| <b>[mow.cli](https://github.com/jawher/mow.cli) | 850 | Go library for building CLI applications with sophisticated flag and argument parsing and validation. |
| <b>[flaggy](https://github.com/integrii/flaggy) | 831 | A robust and idiomatic flags package with excellent subcommand support. |
| <b>[cli](https://github.com/mkideal/cli) | 685 | Feature-rich and easy to use command-line package based on golang struct tags. |
| <b>[argparse](https://github.com/akamensky/argparse) | 528 | Command line argument parser inspired by Python's argparse module. |
| <b>[carapace-bin](https://github.com/rsteube/carapace-bin) | 229 | Multi-shell multi-command argument completer. |
| <b>[climax](https://github.com/tucnak/climax) | 209 | Alternative CLI with "human face", in spirit of Go command. |
| <b>[wmenu](https://github.com/dixonwille/wmenu) | 189 | Easy to use menu structure for cli applications that prompts users to make choices. |
| <b>[hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) | 179 | cli application framework with auto configuration and dependency injection. |
| <b>[commandeer](https://github.com/jaffee/commandeer) | 166 | Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. |
| <b>[clîr](https://github.com/leaanthony/clir) | 153 | A Simple and Clear CLI library. Dependency free. |
| <b>[sflags](https://github.com/octago/sflags) | 148 | Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. |
| <b>[job](https://github.com/liujianping/job) | 127 | JOB, make your short-term command as a long-term job. |
| <b>[flag](https://github.com/cosiner/flag) | 126 | Simple but powerful command line option parsing library for Go supporting subcommand. |
| <b>[cmdr](https://github.com/hedzr/cmdr) | 122 | A POSIX/GNU style, getopt-like command-line UI Go library. |
| <b>[ukautz/clif](https://github.com/ukautz/clif) | 122 | Small command line interface framework. |
| <b>[cli](https://github.com/teris-io/cli) | 120 | Simple and complete API for building command line interfaces in Go. |
| <b>[carapace](https://github.com/rsteube/carapace) | 108 | Command argument completion generator for spf13/cobra. |
| <b>[env](https://github.com/codingconcepts/env) | 106 | Tag-based environment configuration for structs. |
| <b>[acmd](https://github.com/cristalhq/acmd) | 86 | Simple, useful and opinionated CLI package in Go. |
| <b>[version](https://github.com/mszostok/version) | 68 | Collects and displays CLI version information in multiple formats along with upgrade notice. |
| <b>[gocmd](https://github.com/devfacet/gocmd) | 64 | Go library for building command line applications. |
| <b>[wlog](https://github.com/dixonwille/wlog) | 59 | Simple logging interface that supports cross-platform color and concurrency. |
| <b>[strumt](https://github.com/antham/strumt) | 55 | Library to create prompt chain. |
| <b>[go-getoptions](https://github.com/DavidGamba/go-getoptions) | 46 | Go option parser inspired on the flexibility of Perl’s GetOpt::Long. |
| <b>[command-chain](https://github.com/rainu/go-command-chain) | 43 | A go library for configure and run command chains - such like pipelining in unix shells. |
| <b>[flagvar](https://github.com/sgreben/flagvar) | 42 | A collection of flag argument types for Go's standard `flag` package. |
| <b>[argv](https://github.com/cosiner/argv) | 38 | Go library to split command line string as arguments array using the bash syntax. |
| <b>[cmd](https://github.com/posener/cmd) | 36 | Extends the standard `flag` package to support sub commands and more in idiomatic way. |
| <b>[readline](https://github.com/reeflective/readline) | 34 | Shell library with modern and easy to use UI features. |
| <b>[go-commander](https://github.com/yitsushi/go-commander) | 33 | Go library to simplify CLI workflow. |
| <b>[go-andotp](https://github.com/grijul/go-andotp) | 22 | A CLI program to encrypt/decrypt [andOTP](https://github.com/andOTP/andOTP) files. Can be used as library as well. |
| <b>[sand](https://github.com/Zaba505/sand) | 19 | Simple API for creating interpreters and so much more. |
| <b>[ts](https://github.com/liujianping/ts) | 17 | Timestamp convert & compare tool. |
| <b>[mcli](https://github.com/jxskiss/mcli) | 12 | A minimal but very powerful cli library for Go. |
| <b>[carapace-spec](https://github.com/rsteube/carapace-spec) | 6 | Define simple completions using a spec file. |
| <b>[subcmd](https://github.com/bobg/subcmd) | 4 | Another approach to parsing and running subcommands. Works alongside the standard `flag` package. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Configuration

_Libraries for configuration parsing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[viper](https://github.com/spf13/viper) | 23.0k | Go configuration with fangs. |
| <b>[godotenv](https://github.com/joho/godotenv) | 6.2k | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| <b>[kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) | 4.6k | Go library for managing configuration data from environment variables. |
| <b>[env](https://github.com/caarlos0/env) | 3.6k | Parse environment variables to Go structs (with defaults). |
| <b>[ini](https://github.com/go-ini/ini) | 3.2k | Go package to read and write INI files. |
| <b>[koanf](https://github.com/knadh/koanf) | 1.8k | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| <b>[kong](https://github.com/alecthomas/kong) | 1.4k | Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (succesor to `kingpin`). |
| <b>[cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 1000 | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| <b>[konfig](https://github.com/lalamove/konfig) | 637 | Composable, observable and performant config handling for Go for the distributed processing era. |
| <b>[confita](https://github.com/heetch/confita) | 464 | Load configuration in cascade from multiple backends into a struct. |
| <b>[gookit/config](https://github.com/gookit/config) | 464 | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| <b>[aconfig](https://github.com/cristalhq/aconfig) | 452 | Simple, useful and opinionated config loader. |
| <b>[xdg](https://github.com/adrg/xdg) | 393 | Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). |
| <b>[GoLobby/Config](https://github.com/golobby/config) | 330 | GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language. |
| <b>[config](https://github.com/JeremyLoy/config) | 329 | Cloud native application configuration. Bind ENV to structs in only two lines. |
| <b>[hjson](https://github.com/hjson/hjson-go) | 298 | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| <b>[fig](https://github.com/kkyr/fig) | 269 | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| <b>[store](https://github.com/tucnak/store) | 269 | Lightweight configuration manager for Go. |
| <b>[config](https://github.com/olebedev/config) | 263 | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| <b>[envconfig](https://github.com/vrischmann/envconfig) | 233 | Read your configuration from environment variables. |
| <b>[joshbetz/config](https://github.com/joshbetz/config) | 213 | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| <b>[gcfg](https://github.com/go-gcfg/gcfg) | 163 | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| <b>[harvester](https://github.com/beatlabs/harvester) | 127 | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| <b>[onion](https://github.com/goraz/onion) | 112 | Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP. |
| <b>[envcfg](https://github.com/tomazk/envcfg) | 100 | Un-marshaling environment variables to Go structs. |
| <b>[envh](https://github.com/antham/envh) | 96 | Helpers to manage environment variables. |
| <b>[configuro](https://github.com/sherifabdlnaby/configuro) | 87 | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| <b>[configuration](https://github.com/BoRuDar/configuration) | 83 | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| <b>[xdg](https://github.com/OpenPeeDeeP/xdg) | 74 | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| <b>[gofigure](https://github.com/ian-kent/gofigure) | 65 | Go application configuration made easy. |
| <b>[uConfig](https://github.com/omeid/uconfig) | 62 | Lightweight, zero-dependency, and extendable configuration management. |
| <b>[hocon](https://github.com/gurkankaymak/hocon) | 59 | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| <b>[configure](https://github.com/paked/configure) | 57 | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| <b>[go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 54 | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| <b>[gone/jconf](https://github.com/One-com/gone/tree/master/jconf) | 45 | Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization. |
| <b>[env](https://github.com/junk1tm/env) | 39 | A lightweight package for loading environment variables into structs. |
| <b>[go-up](https://github.com/ufoscout/go-up) | 39 | A simple configuration library with recursive placeholders resolution and no magic. |
| <b>[ingo](https://github.com/schachmat/ingo) | 36 | Flags persisted in an ini-like config file. |
| <b>[mini](https://github.com/sasbury/mini) | 34 | Golang package for parsing ini-style configuration files. |
| <b>[config](https://github.com/num30/config) | 33 | configure you app using file, environment variables, or flags in two lines of code |
| <b>[genv](https://github.com/sakirsensoy/genv) | 33 | Read environment variables easily with dotenv support. |
| <b>[conflate](https://github.com/the4thamigo-uk/conflate) | 27 | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| <b>[go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 17 | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| <b>[ini](https://github.com/wlevene/ini) | 12 | INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file. |
| <b>[envconf](https://github.com/ian-kent/envconf) | 11 | Configuration from environment. |
| <b>[nasermirzaei89/env](https://github.com/nasermirzaei89/env) | 10 | Simple useful package for read environment variables. |
| <b>[go-ini](https://github.com/subpop/go-ini) | 9 | A Go package that marshals and unmarshals INI-files. |
| <b>[typenv](https://github.com/diegomarangoni/typenv) | 9 | Minimalistic, zero dependency, typed environment variables library. |
| <b>[go-conf](https://github.com/ThomasObenaus/go-conf) | 8 | Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters. |
| <b>[swap](https://github.com/oblq/swap) | 8 | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| <b>[piper](https://github.com/Yiling-J/piper) | 7 | Viper wrapper with config inheritance and key generation. |
| <b>[gonfig](https://github.com/milad-abbasi/gonfig) | 6 | Tag-based configuration parser which loads values from different providers into typesafe struct. |
| <b>[nfigure](https://github.com/muir/nfigure) | 6 | Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML |
| <b>[goConfig](https://github.com/crgimenes/goConfig) | 3 | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Continuous Integration

_Tools for help with continuous integration._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[drone](https://github.com/drone/drone) | 27.0k | Drone is a Continuous Integration platform built on Docker, written in Go. |
| <b>[CDS](https://github.com/ovh/cds) | 4.2k | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| <b>[woodpecker](https://github.com/woodpecker-ci/woodpecker) | 2.7k | Woodpecker is a community fork of the Drone CI system. |
| <b>[goveralls](https://github.com/mattn/goveralls) | 762 | Go integration for Coveralls.io continuous code coverage tracking system. |
| <b>[gotestfmt](https://github.com/GoTestTools/gotestfmt) | 384 | go test output for humans. |
| <b>[gotestfmt](https://github.com/haveyoudebuggedit/gotestfmt) | 384 | go test output for humans. |
| <b>[overalls](https://github.com/go-playground/overalls) | 112 | Multi-Package go project coverprofile for tools like goveralls. |
| <b>[duci](https://github.com/duck8823/duci) | 74 | A simple ci server no needs domain specific languages. |
| <b>[gomason](https://github.com/nikogura/gomason) | 57 | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| <b>[roveralls](https://github.com/LawrenceWoodman/roveralls) | 19 | Recursive coverage testing tool. |
| <b>[go-fuzz-action](https://github.com/jidicula/go-fuzz-action) | 9 | Use Go 1.18's built-in fuzz testing in GitHub Actions. |
| <b>[go-test-coverage](https://github.com/vladopajic/go-test-coverage) | 9 | Tool and GitHub action which reports issues when test coverage is below set threshold. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## CSS Preprocessors

_Libraries for preprocessing CSS files._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gcss](https://github.com/yosssi/gcss) | 479 | Pure Go CSS Preprocessor. |
| <b>[go-libsass](https://github.com/wellington/go-libsass) | 193 | Go wrapper to the 100% Sass compatible libsass project. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Data Structures and Algorithms


<br>

### Bit-packing and Compression


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[roaring](https://github.com/RoaringBitmap/roaring) | 2.0k | Go package implementing compressed bitsets. |
| <b>[binpacker](https://github.com/zhuangsirui/binpacker) | 206 | Binary packer and unpacker helps user build custom binary stream. |
| <b>[bit](https://github.com/yourbasic/bit) | 149 | Golang set data structure with bonus bit-twiddling functions. |
| <b>[crunch](https://github.com/superwhiskers/crunch) | 85 | Go package implementing buffers for handling various datatypes easily. |
| <b>[go-ef](https://github.com/amallia/go-ef) | 28 | A Go implementation of the Elias-Fano encoding. |
| <b>[bingo](https://github.com/iancmcc/bingo) | 21 | Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes. |


<br>

[👆back to top](#catalogue-list)


<br>

### Bit Sets


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bitset](https://github.com/bits-and-blooms/bitset) | 1.1k | Go package implementing bitsets. |
| <b>[bitmap](https://github.com/kelindar/bitmap) | 216 | Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Bloom and Cuckoo Filters


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bloom](https://github.com/bits-and-blooms/bloom) | 1.9k | Go package implementing Bloom filters. |
| <b>[boomfilters](https://github.com/tylertreat/BoomFilters) | 1.5k | Probabilistic data structures for processing continuous, unbounded streams. |
| <b>[cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 990 | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| <b>[cuckoo-filter](https://github.com/linvon/cuckoo-filter) | 253 | Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available. |
| <b>[bloom](https://github.com/zhenjl/bloom) | 147 | Bloom filters implemented in Go. |
| <b>[ring](https://github.com/TheTannerRyan/ring) | 129 | Go implementation of a high performance, thread safe bloom filter. |
| <b>[bloom](https://github.com/yourbasic/bloom) | 78 | Golang Bloom filter implementation. |
| <b>[bloomfilter](https://github.com/OldPanda/bloomfilter) | 13 | Yet another Bloomfilter implementation in Go, compatible with Java's Guava library. |


<br>

[👆back to top](#catalogue-list)


<br>

### Data Structure and Algorithm Collections


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gods](https://github.com/emirpasic/gods) | 14.0k | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| <b>[go-datastructures](https://github.com/Workiva/go-datastructures) | 7.1k | Collection of useful, performant, and thread-safe data structures. |
| <b>[gostl](https://github.com/liyue201/gostl) | 869 | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| <b>[algorithms](https://github.com/shady831213/algorithms) | 717 | Algorithms and data structures.CLRS study. |


<br>

[👆back to top](#catalogue-list)


<br>

### Iterators


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[iter](https://github.com/disksing/iter) | 177 | Go implementation of C++ STL iterators and algorithms. |
| <b>[goterator](https://github.com/yaa110/goterator) | 14 | Iterator implementation to provide map and reduce functionalities. |


<br>

[👆back to top](#catalogue-list)


<br>

### Maps


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cmap](https://github.com/lrita/cmap) | 56 | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| <b>[dict](https://github.com/srfrog/dict) | 39 | Python-like dictionaries (dict) for Go. |
| <b>[goradd/maps](https://github.com/goradd/maps) | 22 | Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc. |


<br>

[👆back to top](#catalogue-list)


<br>

### Miscellaneous Data Structures and Algorithms


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gota](https://github.com/kniren/gota) | 2.7k | Implementation of dataframes, series, and data wrangling methods for Go. |
| <b>[hyperloglog](https://github.com/axiomhq/hyperloglog) | 854 | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| <b>[go-geoindex](https://github.com/hailocab/go-geoindex) | 350 | In-memory geo index. |
| <b>[hilbert](https://github.com/google/hilbert) | 263 | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| <b>[go-rquad](https://github.com/aurelien-rainone/go-rquad) | 126 | Region quadtrees with efficient point location and neighbour finding. |
| <b>[conjungo](https://github.com/InVisionApp/conjungo) | 114 | A small, powerful and flexible merge library. |
| <b>[go-rampart](https://github.com/francesconi/go-rampart) | 89 | Determine how intervals relate to each other. |
| <b>[gogu](https://github.com/esimov/gogu) | 75 | A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library. |
| <b>[count-min-log](https://github.com/seiflotfy/count-min-log) | 62 | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| <b>[go-tuple](https://github.com/barweiss/go-tuple) | 57 | Generic tuple implementation for Go 1.18+. |
| <b>[hide](https://github.com/emvi/hide) | 53 | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| <b>[concurrent-writer](https://github.com/free/concurrent-writer) | 49 | Highly concurrent drop-in replacement for `bufio.Writer`. |
| <b>[fsm](https://github.com/cocoonspace/fsm) | 45 | Finite-State Machine package. |
| <b>[genfuncs](https://github.com/nwillc/genfuncs) | 44 | Go 1.18+ generics package inspired by Kotlin's Sequence and Map. |
| <b>[go18ds](https://github.com/daichi-m/go18ds) | 32 | Go Data Structures using Go 1.18 generics. |
| <b>[go-generics](https://github.com/bobg/go-generics) | 23 | Generic slice, map, set, iterator, and goroutine utilities. |
| <b>[quadtree](https://github.com/s0rg/quadtree) | 23 | Generic, zero-alloc, 100%-test covered quadtree. |
| <b>[gofal](https://github.com/xxjwxc/gofal) | 17 | fractional api for Go. |
| <b>[slices](https://github.com/srfrog/slices) | 13 | Functions that operate on slices; like `package strings` but adapted to work with slices. |
| <b>[slices](https://github.com/twharmon/slices) | 13 | Pure, generic functions for slices. |


<br>

[👆back to top](#catalogue-list)


<br>

### Nullable Types


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[nan](https://github.com/kak-tus/nan) | 74 | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| <b>[typ](https://github.com/gurukami/typ) | 33 | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| <b>[null](https://github.com/emvi/null) | 31 | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |


<br>

[👆back to top](#catalogue-list)


<br>

### Queues


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[deque](https://github.com/gammazero/deque) | 459 | Fast ring-buffer deque (double-ended queue). |
| <b>[goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 277 | Concurrent FIFO queue. |
| <b>[queue](https://github.com/adrianbrad/queue) | 169 | Multiple thread-safe, generic queue implementations for Go. |
| <b>[deque](https://github.com/edwingeng/deque) | 127 | A highly optimized double-ended queue. |
| <b>[memlog](https://github.com/embano1/memlog) | 87 | An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka. |


<br>

[👆back to top](#catalogue-list)


<br>

### Sets


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golang-set](https://github.com/deckarep/golang-set) | 3.3k | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| <b>[goset](https://github.com/zoumo/goset) | 51 | A useful Set collection implementation for Go. |
| <b>[set](https://github.com/StudioSol/set) | 23 | Simple set data structure implementation in Go using LinkedHashMap. |
| <b>[dsu](https://github.com/ihebu/dsu) | 11 | Disjoint Set data structure implementation in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Text Analysis


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bleve](https://github.com/blevesearch/bleve) | 9.1k | Modern text indexing library for go. |
| <b>[trie](https://github.com/derekparker/trie) | 648 | Trie implementation in Go. |
| <b>[go-edlib](https://github.com/hbollon/go-edlib) | 390 | Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. |
| <b>[go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 287 | Go implementation of Adaptive Radix Tree. |
| <b>[levenshtein](https://github.com/agnivade/levenshtein) | 285 | Implementation to calculate levenshtein distance in Go. |
| <b>[levenshtein](https://github.com/agext/levenshtein) | 76 | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| <b>[ptrie](https://github.com/viant/ptrie) | 32 | An implementation of prefix tree. |
| <b>[mspm](https://github.com/BlackRabbitt/mspm) | 22 | Multi-String Pattern Matching Algorithm for information retrieval. |
| <b>[parsefields](https://github.com/MonaxGT/parsefields) | 7 | Tools for parse JSON-like logs for collecting unique fields and events. |


<br>

[👆back to top](#catalogue-list)


<br>

### Trees


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[skiplist](https://github.com/MauriceGit/skiplist) | 251 | Very fast Go Skiplist implementation. |
| <b>[skiplist](https://github.com/gansidui/skiplist) | 82 | Skiplist implementation in Go. |
| <b>[treemap](https://github.com/igrmk/treemap) | 31 | Generic key-sorted map using a red-black tree under the hood. |
| <b>[treap](https://github.com/perdata/treap) | 21 | Persistent, fast ordered map using tree heaps. |
| <b>[merkle](https://github.com/bobg/merkle) | 10 | Space-efficient computation of Merkle root hashes and inclusion proofs. |
| <b>[hashsplit](http://github.com/bobg/hashsplit) | 8 | Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position. |


<br>

[👆back to top](#catalogue-list)


<br>

### Pipes


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[pipeline](https://github.com/hyfather/pipeline) | 47 | An implementation of pipelines with fan-in and fan-out. |
| <b>[parapipe](https://github.com/nazar256/parapipe) | 23 | FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results. |
| <b>[ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) | 22 | Go module that processes work concurrently and returns output in a channel in the order of input. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Database


<br>

### Caches

_Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[groupcache](https://github.com/golang/groupcache) | 12.0k | Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. |
| <b>[BigCache](https://github.com/allegro/bigcache) | 6.6k | Efficient key/value cache for gigabytes of data. |
| <b>[GCache](https://github.com/bluele/gcache) | 2.4k | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| <b>[cache2go](https://github.com/muesli/cache2go) | 2.0k | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| <b>[gocache](https://github.com/eko/gocache) | 1.8k | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| <b>[fastcache](https://github.com/VictoriaMetrics/fastcache) | 1.7k | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| <b>[ttlcache](https://github.com/jellydator/ttlcache) | 661 | An in-memory cache with item expiration and generics. |
| <b>[cachego](https://github.com/fabiorphp/cachego) | 272 | Golang Cache component for multiple drivers. |
| <b>[cachego](https://github.com/faabiosr/cachego) | 272 | Golang Cache component for multiple drivers. |
| <b>[cache](https://github.com/akyoto/cache) | 132 | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| <b>[remember-go](https://github.com/rocketlaunchr/remember-go) | 126 | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| <b>[bcache](https://github.com/iwanbk/bcache) | 121 | Eventually consistent distributed in-memory  cache Go library. |
| <b>[go-cache](https://github.com/viney-shih/go-cache) | 106 | A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern. |
| <b>[theine](https://github.com/Yiling-J/theine-go) | 92 | High performance, near optimal in-memory cache with proactive TTL expiration and generics. |
| <b>[go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 87 | Fast in-memory key:value store/cache library. Pointer caches. |
| <b>[imcache](https://github.com/erni27/imcache) | 64 | A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding. |
| <b>[couchcache](https://github.com/codingsince1985/couchcache) | 60 | RESTful caching micro-service backed by Couchbase server. |
| <b>[timedmap](https://github.com/zekroTJA/timedmap) | 60 | Map with expiring key-value pairs. |
| <b>[clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 43 | BigCache with clustering support and individual item expiration. |
| <b>[2q](https://github.com/floatdrop/2q) | 25 | 2Q in-memory cache implementation. |
| <b>[gdcache](https://github.com/ulovecode/gdcache) | 10 | A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache. |
| <b>[ttlcache](https://github.com/cheshir/ttlcache) | 9 | In-memory key value storage with TTL for each record. |
| <b>[nscache](https://github.com/no-src/nscache) | 3 | A Go caching framework that supports multiple data source drivers. |


<br>

[👆back to top](#catalogue-list)


<br>

### Databases Implemented in Go


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[prometheus](https://github.com/prometheus/prometheus) | 49.0k | Monitoring system and time series database. |
| <b>[tidb](https://github.com/pingcap/tidb) | 34.0k | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| <b>[cockroach](https://github.com/cockroachdb/cockroach) | 27.0k | Scalable, Geo-Replicated, Transactional Datastore. |
| <b>[influxdb](https://github.com/influxdb/influxdb) | 26.0k | Scalable datastore for metrics, events, and real-time analytics. |
| <b>[Milvus](https://github.com/milvus-io/milvus) | 20.0k | Milvus is a vector database for embedding management, analytics and search. |
| <b>[dgraph](https://github.com/dgraph-io/dgraph) | 19.0k | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| <b>[dolt](https://github.com/dolthub/dolt) | 15.0k | Dolt – It's Git for Data. |
| <b>[rqlite](https://github.com/rqlite/rqlite) | 14.0k | The lightweight, distributed, relational database built on SQLite. |
| <b>[badger](https://github.com/dgraph-io/badger) | 12.0k | Fast key-value store in Go. |
| <b>[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 8.6k | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| <b>[immudb](https://github.com/codenotary/immudb) | 8.2k | immudb is a lightweight, high-speed immutable database for systems and applications written in Go. |
| <b>[bbolt](https://github.com/etcd-io/bbolt) | 6.6k | An embedded key/value database for Go. |
| <b>[goleveldb](https://github.com/syndtr/goleveldb) | 5.7k | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| <b>[buntdb](https://github.com/tidwall/buntdb) | 4.1k | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| <b>[ledisdb](https://github.com/siddontang/ledisdb) | 4.0k | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| <b>[rosedb](https://github.com/roseduan/rosedb) | 3.7k | An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset. |
| <b>[nutsdb](https://github.com/xujiajun/nutsdb) | 2.9k | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| <b>[godis](https://github.com/hdt3213/godis) | 2.8k | A Golang implemented high-performance Redis server and cluster. |
| <b>[tiedot](https://github.com/HouzuoGuo/tiedot) | 2.7k | Your NoSQL database powered by Golang. |
| <b>[CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1.4k | CovenantSQL is a SQL database on blockchain. |
| <b>[diskv](https://github.com/peterbourgon/diskv) | 1.3k | Home-grown disk-backed key-value store. |
| <b>[column](https://github.com/kelindar/column) | 1.1k | High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions. |
| <b>[Databunker](https://github.com/paranoidguy/databunker) | 1.1k | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| <b>[lotusdb](https://github.com/flower-corp/lotusdb) | 1.1k | Fast k/v database compatible with lsm and b+tree. |
| <b>[pogreb](https://github.com/akrylysov/pogreb) | 1.1k | Embedded key-value store for read-heavy workloads. |
| <b>[eliasdb](https://github.com/krotik/eliasdb) | 968 | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| <b>[moss](https://github.com/couchbase/moss) | 924 | Moss is a simple LSM key-value storage engine written in 100% Go. |
| <b>[objectbox-go](https://github.com/objectbox/objectbox-go) | 827 | High-performance embedded Object Database (NoSQL) with Go API. |
| <b>[levigo](https://github.com/jmhodges/levigo) | 416 | Levigo is a Go wrapper for LevelDB. |
| <b>[clover](https://github.com/ostafen/clover) | 405 | A lightweight document-oriented NoSQL database written in pure Golang. |
| <b>[pudge](https://github.com/recoilme/pudge) | 342 | Fast and simple key/value store written using Go's standard library. |
| <b>[Vasto](https://github.com/chrislusf/vasto) | 250 | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| <b>[dtf](https://github.com/dtm-labs/dtf) | 217 | A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages. |
| <b>[piladb](https://github.com/fern4lvarez/piladb) | 201 | Lightweight RESTful database engine based on stack data structures. |
| <b>[unitdb](https://github.com/unit-io/unitdb) | 107 | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| <b>[libradb](https://github.com/amit-davidson/LibraDB) | 94 | LibraDB is a simple database with less then 1000 lines of code for learning. |
| <b>[hare](https://github.com/jameycribbs/hare) | 74 | A simple database management system that stores each table as a text file of line-delimited JSON. |
| <b>[Coffer](https://github.com/claygod/coffer) | 32 | Simple ACID key-value database that supports transactions. |
| <b>[tempdb](https://github.com/rafaeljesus/tempdb) | 17 | Key-value store for temporary items. |
| <b>[Bitcask](https://git.mills.io/prologic/bitcask) | - | Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). |


<br>

[👆back to top](#catalogue-list)


<br>

### Database Schema Migration


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[migrate](https://github.com/golang-migrate/migrate) | 12.0k | Database migrations. CLI and Golang library. |
| <b>[bytebase](https://github.com/bytebase/bytebase) | 6.0k | Safe database schema change and version control for DevOps teams. |
| <b>[goose](https://github.com/pressly/goose) | 4.0k | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| <b>[dbmate](https://github.com/amacneil/dbmate) | 3.5k | A lightweight, framework-agnostic database migration tool. |
| <b>[atlas](https://github.com/ariga/atlas) | 3.1k | A Database Toolkit. A CLI designed to help companies better work with their data. |
| <b>[sql-migrate](https://github.com/rubenv/sql-migrate) | 2.9k | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| <b>[soda](https://github.com/gobuffalo/pop/tree/master/soda) | 1.3k | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| <b>[skeema](https://github.com/skeema/skeema) | 1.2k | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| <b>[gormigrate](https://github.com/go-gormigrate/gormigrate) | 896 | Database schema migration helper for Gorm ORM. |
| <b>[goavro](https://github.com/linkedin/goavro) | 885 | A Go package that encodes and decodes Avro data. |
| <b>[migrator](https://github.com/lopezator/migrator) | 151 | Dead simple Go database migration library. |
| <b>[darwin](https://github.com/GuiaBolso/darwin) | 133 | Database schema evolution library for Go. |
| <b>[go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 83 | A Go package to help write migrations with go-pg/pg. |
| <b>[sqlize](https://github.com/sunary/sqlize) | 57 | Database migration generator. Allows generate sql migration from model and existing sql by differ them. |
| <b>[avro](https://github.com/khezen/avro) | 42 | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| <b>[go-fixtures](https://github.com/RichardKnop/go-fixtures) | 29 | Django style fixtures for Golang's excellent built-in database/sql library. |
| <b>[pravasan](https://github.com/pravasan/pravasan) | 29 | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| <b>[schema](https://github.com/adlio/schema) | 28 | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| <b>[migrator](https://github.com/larapulse/migrator) | 24 | MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code. |
| <b>[libschema](https://github.com/muir/libschema) | 13 | Define your migrations separately in each libary.  Migrations for open source libraries.  MySQL & PostgreSQL. |
| <b>[go-pg-migrate](https://github.com/lawzava/go-pg-migrate) | 10 | CLI-friendly package for go-pg migrations management. |
| <b>[gorm-seeder](https://github.com/Kachit/gorm-seeder) | 8 | Simple database seeder for Gorm ORM. |
| <b>[godfish](https://github.com/rafaelespinoza/godfish) | 4 | Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3. |


<br>

[👆back to top](#catalogue-list)


<br>

### Database Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[vitess](https://github.com/youtube/vitess) | 16.0k | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| <b>[pgweb](https://github.com/sosedoff/pgweb) | 7.9k | Web-based PostgreSQL database browser. |
| <b>[kingshard](https://github.com/flike/kingshard) | 6.2k | kingshard is a high performance proxy for MySQL powered by Golang. |
| <b>[orchestrator](https://github.com/github/orchestrator) | 4.9k | MySQL replication topology manager & visualizer. |
| <b>[go-mysql](https://github.com/siddontang/go-mysql) | 4.1k | Go toolset to handle MySQL protocol and replication. |
| <b>[go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) | 4.0k | Sync your MySQL data into Elasticsearch automatically. |
| <b>[pREST](https://github.com/prest/prest) | 3.8k | Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. |
| <b>[chproxy](https://github.com/Vertamedia/chproxy) | 1.1k | HTTP proxy for ClickHouse database. |
| <b>[pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | 884 | Advanced scheduling for PostgreSQL. |
| <b>[clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 420 | Collects small inserts and sends big requests to ClickHouse servers. |
| <b>[rdb](https://github.com/HDT3213/rdb) | 261 | Redis RDB file parser for secondary development and memory analysis. |
| <b>[myreplication](https://github.com/2tvenom/myreplication) | 191 | MySql binary log replication listener. Supports statement and row based replication. |
| <b>[octillery](https://github.com/knocknote/octillery) | 183 | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| <b>[dbbench](https://github.com/sj14/dbbench) | 86 | Database benchmarking tool with support for several databases and scripts. |
| <b>[datagen](https://github.com/codingconcepts/datagen) | 56 | A fast data generator that's multi-table aware and supports multi-row DML. |
| <b>[prep](https://github.com/hexdigest/prep) | 33 | Use prepared SQL statements without changing your code. |
| <b>[onedump](https://github.com/liweiyi88/onedump) | 18 | Database backup from different drivers to different destinations with one command and configuration. |
| <b>[rwdb](https://github.com/andizzle/rwdb) | 18 | rwdb provides read replica capability for multiple database servers setup. |
| <b>[dynago](https://github.com/twharmon/dynago) | 8 | Simplify working with AWS DynamoDB. |


<br>

[👆back to top](#catalogue-list)


<br>

### SQL Query Builders

_Libraries for building and using SQL._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sqlc](https://github.com/kyleconroy/sqlc) | 8.2k | Generate type-safe code from SQL. |
| <b>[Squirrel](https://github.com/Masterminds/squirrel) | 5.8k | Go library that helps you build SQL queries. |
| <b>[xo](https://github.com/knq/xo) | 3.4k | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| <b>[goqu](https://github.com/doug-martin/goqu) | 1.9k | Idiomatic SQL builder and query library. |
| <b>[gendry](https://github.com/didi/gendry) | 1.5k | Non-invasive SQL builder and powerful data binder. |
| <b>[jet](https://github.com/go-jet/jet) | 1.3k | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| <b>[Dotsql](https://github.com/gchaincl/dotsql) | 674 | Go library that helps you keep sql files in one place and use them with ease. |
| <b>[ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 596 | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| <b>[dbq](https://github.com/rocketlaunchr/dbq) | 376 | Zero boilerplate database operations for Go. |
| <b>[sqlingo](https://github.com/lqs/sqlingo) | 315 | A lightweight DSL to build SQL in Go. |
| <b>[sqrl](https://github.com/elgris/sqrl) | 253 | SQL query builder, fork of Squirrel with improved performance. |
| <b>[sq](https://github.com/bokwoon95/go-structured-query) | 192 | Type-safe SQL builder and struct mapper for Go. |
| <b>[sqlf](https://github.com/leporo/sqlf) | 118 | Fast SQL query builder. |
| <b>[igor](https://github.com/galeone/igor) | 107 | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| <b>[buildsqlx](https://github.com/arthurkushman/buildsqlx) | 106 | Go database query builder library for PostgreSQL. |
| <b>[bqb](https://github.com/nullism/bqb) | 79 | Lightweight and easy to learn query builder. |
| <b>[builq](https://github.com/cristalhq/builq) | 64 | Easily build SQL queries in Go. |
| <b>[godbal](https://github.com/xujiajun/godbal) | 58 | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| <b>[gosql](https://github.com/twharmon/gosql) | 29 | SQL Query builder with better null values support. |
| <b>[qry](https://github.com/HnH/qry) | 29 | Tool that generates constants from files with raw SQL queries. |
| <b>[mpath](https://github.com/spacetab-io/mpath-go) | 12 | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| <b>[ormlite](https://github.com/pupizoid/ormlite) | 8 | Lightweight package containing some ORM-like features and helpers for sqlite databases. |
| <b>[sg](https://github.com/go-the-way/sg) | 3 | A SQL Gen for generating standard SQLs(supports: CRUD) written in Go. |
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
| <b>[gokv](https://github.com/philippgille/gokv) | 553 | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| <b>[go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) | 49 | Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries. |
| <b>[dsc](https://github.com/viant/dsc) | 26 | Datastore connectivity for SQL, NoSQL, structured files. |


<br>

[👆back to top](#catalogue-list)


<br>

### Relational Database Drivers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) | 13.0k | MySQL driver for Go. |
| <b>[pq](https://github.com/lib/pq) | 8.1k | Pure Go Postgres driver for database/sql. |
| <b>[pgx](https://github.com/jackc/pgx) | 7.2k | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| <b>[go-sqlite3](https://github.com/mattn/go-sqlite3) | 6.7k | SQLite3 driver for go that uses database/sql. |
| <b>[go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1.7k | Microsoft MSSQL driver for Go. |
| <b>[sqlhooks](https://github.com/qustavo/sqlhooks) | 605 | Attach hooks to any database/sql driver. |
| <b>[go-oci8](https://github.com/mattn/go-oci8) | 603 | Oracle driver for go that uses database/sql. |
| <b>[godror](https://github.com/godror/godror) | 444 | Oracle driver for Go, using the ODPI-C driver. |
| <b>[Kivik](https://github.com/go-kivik/kivik) | 269 | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| <b>[KSQL](https://github.com/VinGarcia/ksql) | 225 | A Simple and Powerful Golang SQL Library |
| <b>[firebirdsql](https://github.com/nakagami/firebirdsql) | 198 | Firebird RDBMS SQL driver for Go. |
| <b>[surrealdb.go](https://github.com/surrealdb/surrealdb.go) | 157 | SurrealDB Driver for Go. |
| <b>[Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) | 136 | SQLite with pure Go. |
| <b>[go-adodb](https://github.com/mattn/go-adodb) | 132 | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| <b>[avatica](https://github.com/apache/calcite-avatica-go) | 110 | Apache Avatica/Phoenix SQL driver for database/sql. |
| <b>[gofreetds](https://github.com/minus5/gofreetds) | 109 | Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org). |
| <b>[ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) | 95 | native and database/sql driver YDB (Yandex Database) |
| <b>[bgc](https://github.com/viant/bgc) | 20 | Datastore Connectivity for BigQuery for go. |
| <b>[pig](https://github.com/alexeyco/pig) | 13 | Simple [pgx](https://github.com/jackc/pgx) wrapper to execute and [scan](https://github.com/georgysavva/scany) query results easily. |


<br>

[👆back to top](#catalogue-list)


<br>

### NoSQL Database Drivers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[redis](https://github.com/redis/go-redis) | 17.0k | Redis client for Golang. |
| <b>[redis](https://github.com/go-redis/redis) | 17.0k | Redis client for Golang. |
| <b>[redigo](https://github.com/gomodule/redigo) | 9.5k | Redigo is a Go client for the Redis database. |
| <b>[mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 7.4k | Official MongoDB driver for the Go language. |
| <b>[mgo](https://github.com/globalsign/mgo) | 2.0k | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| <b>[gomemcache](https://github.com/bradfitz/gomemcache/) | 1.6k | memcache client library for the Go programming language. |
| <b>[gorethink](https://github.com/dancannon/gorethink) | 1.6k | Go language driver for RethinkDB. |
| <b>[qmgo](https://github.com/qiniu/qmgo) | 1.1k | The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| <b>[mgm](https://github.com/kamva/mgm) | 662 | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| <b>[redeo](https://github.com/bsm/redeo) | 423 | Redis-protocol compatible TCP servers/services. |
| <b>[aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 411 | Aerospike client in Go language. |
| <b>[neoism](https://github.com/jmcvetta/neoism) | 390 | Neo4j client for Golang. |
| <b>[rueidis](http://github.com/rueian/rueidis) | 368 | Fast Redis RESP3 client with auto pipelining and server-assisted client side caching. |
| <b>[gocb](https://github.com/couchbase/gocb) | 342 | Official Couchbase Go SDK. |
| <b>[go-couchbase](https://github.com/couchbase/go-couchbase) | 314 | Couchbase client in Go. |
| <b>[go-rejson](https://github.com/nitishm/go-rejson) | 313 | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| <b>[godis](https://github.com/piaohao/godis) | 109 | redis client implement by golang, inspired by jedis. |
| <b>[Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 76 | Neo4j REST Client in golang. |
| <b>[arangolite](https://github.com/solher/arangolite) | 73 | Lightweight golang driver for ArangoDB. |
| <b>[go-pilosa](https://github.com/pilosa/go-pilosa) | 58 | Go client library for Pilosa. |
| <b>[forestdb](https://github.com/couchbase/goforestdb) | 33 | Go bindings for ForestDB. |
| <b>[goriak](https://github.com/zegl/goriak) | 30 | Go language driver for Riak KV. |
| <b>[neo4j](https://github.com/cihangir/neo4j) | 27 | Neo4j Rest API Bindings for Golang. |
| <b>[xredis](https://github.com/shomali11/xredis) | 19 | Typesafe, customizable, clean & easy to use Redis client. |
| <b>[gocosmos](https://github.com/btnguyen2k/gocosmos) | 15 | REST client and standard `database/sql` driver for Azure Cosmos DB. |
| <b>[godscache](https://github.com/defcronyke/godscache) | 11 | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| <b>[asc](https://github.com/viant/asc) | 9 | Datastore Connectivity for Aerospike for go. |
| <b>[gocql](https://gocql.github.io) | - | Go language driver for Apache Cassandra. |


<br>

[👆back to top](#catalogue-list)


<br>

### Search and Analytic Databases


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[elastic](https://github.com/olivere/elastic) | 7.2k | Elasticsearch client for Go. |
| <b>[go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 5.0k | Official Elasticsearch client for Go. |
| <b>[elasticsql](https://github.com/cch123/elasticsql) | 1.1k | Convert sql to elasticsearch dsl in Go. |
| <b>[elastigo](https://github.com/mattbaird/elastigo) | 950 | Elasticsearch client library. |
| <b>[skizze](https://github.com/seiflotfy/skizze) | 88 | probabilistic data-structures service and storage. |
| <b>[goes](https://github.com/OwnLocal/goes) | 29 | Library to interact with Elasticsearch. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Date and Time

_Libraries for working with dates and times._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[now](https://github.com/jinzhu/now) | 4.2k | Now is a time toolkit for golang. |
| <b>[carbon](https://github.com/golang-module/carbon) | 3.3k | A simple, semantic and developer-friendly golang package for datetime. |
| <b>[dateparse](https://github.com/araddon/dateparse) | 1.9k | Parse date's without knowing format in advance. |
| <b>[carbon](https://github.com/uniplaces/carbon) | 756 | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| <b>[durafmt](https://github.com/hako/durafmt) | 461 | Time duration formatting library for Go. |
| <b>[timeutil](https://github.com/leekchan/timeutil) | 192 | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| <b>[gostradamus](https://github.com/bykof/gostradamus) | 180 | A Go package for working with dates. |
| <b>[go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 156 | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| <b>[iso8601](https://github.com/relvacode/iso8601) | 124 | Efficiently parse ISO8601 date-times without regex. |
| <b>[date](https://github.com/rickb777/date) | 110 | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| <b>[timespan](https://github.com/SaidinWoT/timespan) | 82 | For interacting with intervals of time, defined as a start time and a duration. |
| <b>[go-str2duration](https://github.com/xhit/go-str2duration) | 72 | Convert string to duration. Support time.Duration returned string and more. |
| <b>[go-sunrise](https://github.com/nathan-osman/go-sunrise) | 72 | Calculate the sunrise and sunset times for a given location. |
| <b>[feiertage](https://github.com/wlbr/feiertage) | 43 | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| <b>[kair](https://github.com/GuilhermeCaruso/kair) | 25 | Date and Time - Golang Formatting Library. |
| <b>[cronrange](https://github.com/1set/cronrange) | 18 | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| <b>[NullTime](https://github.com/kirillDanshin/nulltime) | 14 | Nullable `time.Time`. |
| <b>[strftime](https://github.com/awoodbeck/strftime) | 12 | C99-compatible strftime formatter. |
| <b>[tuesday](https://github.com/osteele/tuesday) | 12 | Ruby-compatible Strftime function. |
| <b>[go-anytime](https://github.com/ijt/go-anytime) | 9 | Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance. |
| <b>[go-week](https://github.com/stoewer/go-week) | 8 | An efficient package to work with ISO8601 week dates. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Distributed Systems

_Packages that help with building Distributed Systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[raft](https://github.com/coreos/etcd/tree/master/raft) | 44.0k | Go implementation of the Raft consensus protocol, by CoreOS. |
| <b>[go-kit](https://github.com/go-kit/kit) | 25.0k | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| <b>[go-zero](https://github.com/tal-tech/go-zero) | 25.0k | A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity. |
| <b>[go-micro](https://github.com/micro/go-micro) | 21.0k | A distributed systems development framework. |
| <b>[Kratos](https://github.com/go-kratos/kratos) | 21.0k | A modular-designed and easy-to-use microservices framework in Go. |
| <b>[grpc-go](https://github.com/grpc/grpc-go) | 18.0k | The Go language implementation of gRPC. HTTP/2 based RPC. |
| <b>[NATS](https://github.com/nats-io/gnatsd) | 13.0k | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| <b>[micro](https://github.com/micro/micro) | 12.0k | A distributed systems runtime for the cloud and beyond. |
| <b>[rpcx](https://github.com/smallnest/rpcx) | 7.6k | Distributed pluggable RPC service framework like alibaba Dubbo. |
| <b>[raft](https://github.com/hashicorp/raft) | 7.2k | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| <b>[Kitex](https://github.com/cloudwego/kitex) | 6.0k | A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice. |
| <b>[lura](https://github.com/luraproject/lura) | 5.6k | Ultra performant API Gateway framework with middlewares. |
| <b>[torrent](https://github.com/anacrolix/torrent) | 4.8k | BitTorrent client package. |
| <b>[dragonboat](https://github.com/lni/dragonboat) | 4.6k | A feature complete and high performance multi-group Raft library in Go. |
| <b>[emitter-io](https://github.com/emitter-io/emitter) | 3.6k | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| <b>[gleam](https://github.com/chrislusf/gleam) | 3.2k | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| <b>[glow](https://github.com/chrislusf/glow) | 3.1k | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| <b>[liftbridge](https://github.com/liftbridge-io/liftbridge) | 2.4k | Lightweight, fault-tolerant message streams for NATS. |
| <b>[Dragonfly](https://github.com/dragonflyoss/Dragonfly2) | 1.4k | Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures. |
| <b>[go-doudou](https://github.com/unionj-cloud/go-doudou) | 1.2k | A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity. |
| <b>[hprose](https://github.com/hprose/hprose-golang) | 1.2k | Very newbility RPC Library, support 25+ languages now. |
| <b>[redis-lock](https://github.com/bsm/redislock) | 1000 | Simplified distributed locking implementation using Redis. |
| <b>[rain](https://github.com/cenkalti/rain) | 838 | BitTorrent client and library. |
| <b>[ringpop-go](https://github.com/uber/ringpop-go) | 784 | Scalable, fault-tolerant application-layer sharding for Go applications. |
| <b>[arpc](https://github.com/lesismal/arpc) | 761 | More effective network communication, support two-way-calling, notify, broadcast. |
| <b>[go-health](https://github.com/InVisionApp/go-health) | 684 | Library for enabling asynchronous dependency health checks in your service. |
| <b>[gorpc](https://github.com/valyala/gorpc) | 679 | Simple, fast and scalable RPC library for high load. |
| <b>[consistent](https://github.com/buraksezer/consistent) | 594 | Consistent hashing with bounded loads. |
| <b>[go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 514 | A library built to provide support for defining async service health checks for golang services. |
| <b>[digota](https://github.com/digota/digota) | 476 | grpc ecommerce microservice. |
| <b>[sleuth](https://github.com/ursiform/sleuth) | 366 | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| <b>[go-jump](https://github.com/dgryski/go-jump) | 361 | Port of Google's "Jump" Consistent Hash function. |
| <b>[Temporal](https://github.com/temporalio/sdk-go) | 325 | Durable execution system for making code fault-tolerant and simple. |
| <b>[jsonrpc](https://github.com/ybbus/jsonrpc) | 276 | JSON-RPC 2.0 HTTP client implementation. |
| <b>[dht](https://github.com/anacrolix/dht) | 264 | BitTorrent Kademlia DHT implementation. |
| <b>[raft](https://github.com/etcd-io/raft) | 247 | Go implementation of the Raft consensus protocol, by CoreOS. |
| <b>[jsonrpc](https://github.com/osamingo/jsonrpc) | 179 | The jsonrpc package helps implement of JSON-RPC 2.0. |
| <b>[outboxer](https://github.com/italolelis/outboxer) | 136 | Outboxer is a go library that implements the outbox pattern. |
| <b>[doublejump](https://github.com/edwingeng/doublejump) | 87 | A revamped Google's jump consistent hash. |
| <b>[Semaphore](https://github.com/jexia/semaphore) | 84 | A straightforward (micro) service orchestrator. |
| <b>[dot](https://github.com/dotchain/dot/) | 79 | distributed sync using operational transformation/OT. |
| <b>[celeriac](https://github.com/svcavallar/celeriac.v1) | 72 | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| <b>[flowgraph](https://github.com/vectaport/flowgraph) | 52 | flow-based programming package. |
| <b>[go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 52 | MySQL based distributed lock. |
| <b>[go-pdu](https://github.com/pdupub/go-pdu) | 46 | A decentralized identity-based social network. |
| <b>[drmaa](https://github.com/dgruber/drmaa) | 44 | Job submission library for cluster schedulers based on the DRMAA standard. |
| <b>[gmsec](https://github.com/gmsec/micro) | 22 | A Go distributed systems development framework. |
| <b>[consistenthash](https://github.com/mbrostami/consistenthash) | 19 | Consistent hashing with configurable replicas. |
| <b>[dynatomic](https://github.com/tylfin/dynatomic) | 15 | A library for using DynamoDB as an atomic counter. |
| <b>[failured](https://github.com/andy2046/failured) | 10 | adaptive accrual failure detector for distributed systems. |
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
| <b>[GoDNS](https://github.com/timothyye/godns) | 1.3k | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| <b>[DDNS](https://github.com/skibish/ddns) | 234 | Personal DDNS client with Digital Ocean Networking DNS as backend. |
| <b>[dyndns](https://gitlab.com/alcastle/dyndns) | - | Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Email

_Libraries and tools that implement email creation and sending._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[MailHog](https://github.com/mailhog/MailHog) | 12.0k | Email and SMTP testing with web and API interface. |
| <b>[hermes](https://github.com/matcornic/hermes) | 2.6k | Golang package that generates clean, responsive HTML e-mails. |
| <b>[email](https://github.com/jordan-wright/email) | 2.3k | A robust and flexible email library for Go. |
| <b>[go-imap](https://github.com/emersion/go-imap) | 1.8k | IMAP library for clients and servers. |
| <b>[Mailpit](https://github.com/axllent/mailpit) | 1.2k | Email and SMTP testing tool for developers. |
| <b>[SendGrid](https://github.com/sendgrid/sendgrid-go) | 900 | SendGrid's Go library for sending email. |
| <b>[email-verifier](https://github.com/AfterShip/email-verifier) | 808 | A Go library for email verification without sending any emails. |
| <b>[mailgun-go](https://github.com/mailgun/mailgun-go) | 647 | Go library for sending mail with the Mailgun API. |
| <b>[go-simple-mail](https://github.com/xhit/go-simple-mail) | 472 | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |
| <b>[go-message](https://github.com/emersion/go-message) | 313 | Streaming library for the Internet Message Format and mail messages. |
| <b>[go-mail](https://github.com/wneessen/go-mail) | 284 | A simple Go library for sending mails in Go. |
| <b>[douceur](https://github.com/aymerick/douceur) | 230 | CSS inliner for your HTML emails. |
| <b>[Hectane](https://github.com/hectane/hectane) | 220 | Lightweight SMTP client providing an HTTP API. |
| <b>[mailchain](https://github.com/mailchain/mailchain) | 137 | Send encrypted emails to blockchain addresses written in Go. |
| <b>[go-premailer](https://github.com/vanng822/go-premailer) | 112 | Inline styling for HTML mail in Go. |
| <b>[go-dkim](https://github.com/toorop/go-dkim) | 89 | DKIM library, to sign & verify email. |
| <b>[smtpmock](https://github.com/mocktools/go-smtp-mock) | 82 | Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment. |
| <b>[smtp](https://github.com/mailhog/smtp) | 77 | SMTP server protocol state machine. |
| <b>[go-email-validator](https://github.com/go-email-validator/go-email-validator) | 50 | Modular email validator for syntax, disposable, smtp, etc... checking. |
| <b>[truemail-go](https://github.com/truemail-rb/truemail-go) | 47 | Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more. |
| <b>[mailx](https://github.com/valord577/mailx) | 6 | Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`. |
| <b>[chasquid](https://blitiri.com.ar/p/chasquid) | - | SMTP server written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Embeddable Scripting Languages

_Embedding other languages inside your go code._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopher-lua](https://github.com/yuin/gopher-lua) | 5.5k | Lua 5.1 VM and compiler written in Go. |
| <b>[goja](https://github.com/dop251/goja) | 3.9k | ECMAScript 5.1(+) implementation in Go. |
| <b>[expr](https://github.com/antonmedv/expr) | 3.8k | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| <b>[tengo](https://github.com/d5/tengo) | 3.2k | Bytecode compiled script language for Go. |
| <b>[go-lua](https://github.com/Shopify/go-lua) | 2.7k | Port of the Lua 5.2 VM to pure Go. |
| <b>[starlark-go](https://github.com/google/starlark-go) | 2.0k | Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution. |
| <b>[cel-go](https://github.com/google/cel-go) | 1.6k | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| <b>[go-python](https://github.com/sbinet/go-python) | 1.5k | naive go bindings to the CPython C-API. |
| <b>[anko](https://github.com/mattn/anko) | 1.3k | Scriptable interpreter written in Go. |
| <b>[metacall](https://github.com/metacall/core) | 1.3k | Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more. |
| <b>[go-php](https://github.com/deuill/go-php) | 896 | PHP bindings for Go. |
| <b>[go-duktape](https://github.com/olebedev/go-duktape) | 777 | Duktape JavaScript engine bindings for Go. |
| <b>[gval](https://github.com/PaesslerAG/gval) | 623 | A highly customizable expression language written in Go. |
| <b>[golua](https://github.com/aarzilli/golua) | 612 | Go bindings for Lua C API. |
| <b>[gisp](https://github.com/jcla1/gisp) | 499 | Simple LISP in Go. |
| <b>[prolog](https://github.com/ichiban/prolog) | 488 | Embeddable Prolog. |
| <b>[gentee](https://github.com/gentee/gentee) | 109 | Embeddable scripting programming language. |
| <b>[binder](https://github.com/alexeyco/binder) | 67 | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| <b>[purl](https://github.com/ian-kent/purl) | 38 | Perl 5.18.2 embedded in Go. |
| <b>[ecal](https://github.com/krotik/ecal) | 33 | A simple embeddable scripting language which supports concurrent event processing. |
| <b>[ngaro](https://github.com/db47h/ngaro) | 25 | Embeddable Ngaro VM implementation enabling scripting in Retro. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Error Handling

_Libraries for handling errors._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[errors](https://github.com/pkg/errors) | 8.0k | Package that provides simple error handling primitives. |
| <b>[go-multierror](https://github.com/hashicorp/go-multierror) | 2.0k | Go (golang) package for representing a list of errors as a single error. |
| <b>[errors](https://github.com/cockroachdb/errors) | 1.6k | Go error library with error portability over the network. |
| <b>[eris](https://github.com/rotisserie/eris) | 1.3k | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| <b>[errorx](https://github.com/joomcode/errorx) | 975 | A feature rich error package with stack traces, composition of errors and more. |
| <b>[tracerr](https://github.com/ztrue/tracerr) | 790 | Golang errors with stack trace and source fragments. |
| <b>[errlog](https://github.com/snwfdhmp/errlog) | 450 | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| <b>[emperror](https://github.com/emperror/emperror) | 301 | Error handling tools and best practices for Go libraries and applications. |
| <b>[errors](https://github.com/emperror/errors) | 177 | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| <b>[Fault](https://github.com/Southclaws/fault) | 133 | An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values. |
| <b>[errors](https://github.com/bnkamalesh/errors) | 51 | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| <b>[oops](https://github.com/samber/oops) | 26 | Error handling with context, stack trace and source fragments. |
| <b>[exception](https://github.com/rbrahul/exception) | 25 | A simple utility package for exception handling with try-catch in Golang. |
| <b>[Falcon](https://github.com/SonicRoshan/falcon) | 9 | A Simple Yet Highly Powerful Package For Error Handling. |
| <b>[errors](https://github.com/PumpkinSeed/errors) | 8 | The most simple error wrapper with awesome performance and minimal memory overhead. |
| <b>[errors](https://github.com/neuronlabs/errors) | 5 | Simple golang error handling with classification primitives. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## File Handling

_Libraries for handling files and file systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[afero](https://github.com/spf13/afero) | 5.2k | FileSystem Abstraction System for Go. |
| <b>[pdfcpu](https://github.com/pdfcpu/pdfcpu) | 5.0k | PDF processor. |
| <b>[gdu](https://github.com/dundee/gdu) | 2.5k | Disk usage analyzer with console interface. |
| <b>[notify](https://github.com/rjeczalik/notify) | 824 | File system event notification library with simple API, similar to os/signal. |
| <b>[copy](https://github.com/otiai10/copy) | 562 | Copy directory recursively. |
| <b>[afs](https://github.com/viant/afs) | 246 | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| <b>[bigfile](https://github.com/bigfile/bigfile) | 241 | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| <b>[vfs](https://github.com/C2FO/vfs) | 236 | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| <b>[gofs](https://github.com/no-src/gofs) | 232 | A file synchronization tool out of the box. |
| <b>[go-exiftool](https://github.com/barasher/go-exiftool) | 175 | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| <b>[go-csv-tag](https://github.com/artonge/go-csv-tag) | 108 | Load csv file using tag. |
| <b>[skywalker](https://github.com/dixonwille/skywalker) | 89 | Package to allow one to concurrently go through a filesystem with ease. |
| <b>[checksum](https://github.com/codingsince1985/checksum) | 87 | Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files. |
| <b>[opc](https://github.com/qmuntal/opc) | 74 | Load Open Packaging Conventions (OPC) files for Go. |
| <b>[parquet](https://github.com/parsyl/parquet) | 71 | Read and write [parquet](https://parquet.apache.org) files. |
| <b>[tarfs](https://github.com/posener/tarfs) | 51 | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| <b>[baraka](https://github.com/xis/baraka) | 49 | A library to process http file uploads easily. |
| <b>[go-gtfs](https://github.com/artonge/go-gtfs) | 35 | Load gtfs files in go. |
| <b>[flop](https://github.com/homedepot/flop) | 34 | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| <b>[gut/yos](https://github.com/1set/gut) | 26 | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| <b>[go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 19 | Copy files for humans. |
| <b>[todotxt](https://github.com/1set/todotxt) | 19 | Go library for Gina Trapani's [_todo.txt_](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [_todo.txt_ format](https://github.com/todotxt/todo.txt). |
| <b>[higgs](https://github.com/dastoori/higgs) | 17 | A tiny cross-platform Go library to hide/unhide files and directories. |
| <b>[pathtype](https://github.com/jonchun/pathtype) | 12 | Treat paths as their own type instead of using strings. |
| <b>[stl](https://gitlab.com/russoj88/stl) | - | Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Financial

_Packages for accounting and finance._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[decimal](https://github.com/shopspring/decimal) | 5.1k | Arbitrary-precision fixed-point decimal numbers. |
| <b>[ticker](https://github.com/achannarasappa/ticker) | 4.6k | Terminal stock watcher and stock position tracker. |
| <b>[go-money](https://github.com/rhymond/go-money) | 1.3k | Implementation of Fowler's Money pattern. |
| <b>[bbgo](https://github.com/c9s/bbgo) | 878 | A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies. |
| <b>[accounting](https://github.com/leekchan/accounting) | 807 | money and currency formatting for golang. |
| <b>[techan](https://github.com/sdcoffey/techan) | 728 | Technical analysis library with advanced market analysis and trading strategies. |
| <b>[go-finance](https://github.com/FlashBoys/go-finance) | 536 | Comprehensive financial markets data in Go. |
| <b>[currency](https://github.com/bojanz/currency) | 395 | Handles currency amounts, provides currency information and formatting. |
| <b>[ach](https://github.com/moov-io/ach) | 375 | A reader, writer, and valdiator for Automated Clearing House (ACH) files. |
| <b>[orderbook](https://github.com/i25959341/orderbook) | 337 | Matching Engine for Limit Order Book in Golang. |
| <b>[go-finance](https://github.com/alpeb/go-finance) | 149 | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| <b>[transaction](https://github.com/claygod/transaction) | 122 | Embedded transactional database of accounts, running in multithreaded mode. |
| <b>[ofxgo](https://github.com/aclindsa/ofxgo) | 117 | Query OFX servers and/or parse the responses (with example command-line client). |
| <b>[sleet](https://github.com/BoltApp/sleet) | 116 | One unified interface for multiple Payment Service Providers (PsP) to process online payment. |
| <b>[vat](https://github.com/dannyvankooten/vat) | 101 | VAT number validation & EU VAT rates. |
| <b>[go-finnhub](https://github.com/m1/go-finnhub) | 78 | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| <b>[currency](https://github.com/bnkamalesh/currency) | 52 | High performant & accurate currency computation package. |
| <b>[fastme](https://github.com/newity/fastme) | 37 | Fast extensible matching engine Go implementation. |
| <b>[fpdecimal](https://github.com/nikolaydubina/fpdecimal) | 22 | Fast and precise serialization and arithmetic for small fixed-point decimals |
| <b>[payme](https://github.com/jovandeginste/payme) | 20 | QR code generator (ASCII & PNG) for SEPA payments. |
| <b>[fpmoney](https://github.com/nikolaydubina/fpmoney) | 18 | Fast and simple ISO4217 fixed-point decimal money. |
| <b>[go-finance](https://github.com/pieterclaerhout/go-finance) | 12 | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Forms

_Libraries for working with forms._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[nosurf](https://github.com/justinas/nosurf) | 1.4k | CSRF protection middleware for Go. |
| <b>[gorilla/csrf](https://github.com/gorilla/csrf) | 883 | CSRF protection for Go web applications & services. |
| <b>[binding](https://github.com/mholt/binding) | 794 | Binds form and JSON data from net/http Request to struct. |
| <b>[form](https://github.com/go-playground/form) | 603 | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| <b>[conform](https://github.com/leebenson/conform) | 299 | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| <b>[formam](https://github.com/monoculum/formam) | 178 | decode form's values into a struct. |
| <b>[httpin](https://github.com/ggicci/httpin) | 171 | Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc. |
| <b>[forms](https://github.com/albrow/forms) | 131 | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| <b>[qs](https://github.com/sonh/qs) | 67 | Go module for encoding structs into URL query parameters. |
| <b>[bind](https://github.com/robfig/bind) | 28 | Bind form data to any Go values. |
| <b>[queryparam](https://github.com/tomwright/queryparam) | 15 | Decode `url.Values` into usable struct values of standard or custom types. |
| <b>[gbind](https://github.com/bdjimmy/gbind) | 8 | Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Functional

_Packages to support functional programming in Go._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[mo](https://github.com/samber/mo) | 1.6k | Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...). |
| <b>[go-underscore](https://github.com/tobyhede/go-underscore) | 1.3k | Useful collection of helpfully functional Go collection utilities. |
| <b>[fpGo](https://github.com/TeaEntityLab/fpGo) | 322 | Monad, Functional Programming features for Golang. |
| <b>[fp-go](https://github.com/repeale/fp-go) | 224 | Collection of Functional Programming helpers powered by Golang 1.18+ generics. |
| <b>[fuego](https://github.com/seborama/fuego) | 139 | Functional Experiment in Go. |
| <b>[gofp](https://github.com/rbrahul/gofp) | 136 | A lodash like powerful utility library for Golang. |
| <b>[underscore](https://github.com/rjNemo/underscore) | 87 | Functional programming helpers for Go 1.18 and beyond. |
| <b>[valor](https://github.com/phelmkamp/valor) | 13 | Generic option and result types that optionally contain a value. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Game Development

_Awesome game development libraries._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Ebiten](https://github.com/hajimehoshi/ebiten) | 8.3k | dead simple 2D game library in Go. |
| <b>[Leaf](https://github.com/name5566/leaf) | 4.9k | Lightweight game server framework. |
| <b>[Pixel](https://github.com/faiface/pixel) | 4.2k | Hand-crafted 2D game library in Go. |
| <b>[g3n](https://github.com/g3n/engine) | 2.4k | Go 3D Game Engine. |
| <b>[nano](https://github.com/lonng/nano) | 2.4k | Lightweight, facility, high performance golang based game server framework. |
| <b>[goworld](https://github.com/xiaonanln/goworld) | 2.3k | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| <b>[go-sdl2](https://github.com/veandco/go-sdl2) | 2.0k | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| <b>[Pitaya](https://github.com/topfreegames/pitaya) | 1.8k | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| <b>[engo](https://github.com/EngoEngine/engo) | 1.6k | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| <b>[Oak](https://github.com/oakmound/oak) | 1.4k | Pure Go game engine. |
| <b>[termloop](https://github.com/JoelOtter/termloop) | 1.4k | Terminal-based game engine for Go, built on top of Termbox. |
| <b>[gonet](https://github.com/xtaci/gonet) | 1.2k | Game server skeleton implemented with golang. |
| <b>[raylib-go](https://github.com/gen2brain/raylib-go) | 998 | Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| <b>[Azul3D](https://github.com/azul3d/engine) | 580 | 3D game engine written in Go. |
| <b>[go-astar](https://github.com/beefsack/go-astar) | 552 | Go implementation of the A\* path finding algorithm. |
| <b>[Harfang3D](https://github.com/harfang3d/harfang3d) | 342 | 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev](github.com/harfang3d/harfang-go)). |
| <b>[go3d](https://github.com/ungerik/go3d) | 282 | Performance oriented 2D/3D math package for Go. |
| <b>[tile](https://github.com/kelindar/tile) | 105 | Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. |
| <b>[prototype](https://github.com/gonutz/prototype) | 81 | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| <b>[fantasyname](https://github.com/s0rg/fantasyname) | 19 | Fantasy names generator. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Generators

_Tools that generate Go code._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-linq](https://github.com/ahmetalpbalkan/go-linq) | 3.3k | .NET LINQ-like query methods for Go. |
| <b>[jennifer](https://github.com/dave/jennifer) | 2.9k | Generate arbitrary Go code without templates. |
| <b>[goderive](https://github.com/awalterschulze/goderive) | 1.1k | Derives functions from input types. |
| <b>[GoWrap](https://github.com/hexdigest/gowrap) | 764 | Generate decorators for Go interfaces using simple templates. |
| <b>[go-enum](https://github.com/abice/go-enum) | 505 | Code generation for enums from code comments. |
| <b>[interfaces](https://github.com/rjeczalik/interfaces) | 378 | Command line tool for generating interface definitions. |
| <b>[copygen](https://github.com/switchupcb/copygen) | 264 | Generate type-to-type code without reflection. |
| <b>[goverter](https://github.com/jmattheis/goverter) | 260 | Generate converters by defining an interface. |
| <b>[gotype](https://github.com/wzshiming/gotype) | 53 | Golang source code parsing, usage like reflect package. |
| <b>[generis](https://github.com/senselogic/GENERIS) | 39 | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| <b>[go-xray](https://github.com/pieterclaerhout/go-xray) | 26 | Helpers for making the use of reflection easier. |
| <b>[typeregistry](https://github.com/xiaoxin01/typeregistry) | 17 | A library to create type dynamically. |
| <b>[convergen](https://github.com/reedom/convergen) | 4 | Feature rich type-to-type copy code generator. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Geographic

_Geographic tools and servers_


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Tile38](https://github.com/tidwall/tile38) | 8.6k | Geolocation DB with spatial index and realtime geofencing. |
| <b>[S2 geometry](https://github.com/golang/geo) | 1.5k | S2 geometry library in Go. |
| <b>[mbtileserver](https://github.com/consbio/mbtileserver) | 499 | A simple Go-based server for map tiles stored in mbtiles format. |
| <b>[osm](https://github.com/paulmach/osm) | 276 | Library for reading, writing and working with OpenStreetMap data and APIs. |
| <b>[H3](https://github.com/uber/h3-go) | 228 | Go bindings for H3, a hierarchical hexagonal geospatial indexing system. |
| <b>[WGS84](https://github.com/wroge/wgs84) | 98 | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| <b>[godal](https://github.com/airbusgeo/godal) | 97 | Go wrapper for GDAL. |
| <b>[simplefeatures](https://github.com/peterstace/simplefeatures) | 83 | simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them. |
| <b>[geoserver](https://github.com/hishamkaram/geoserver) | 82 | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| <b>[gismanager](https://github.com/hishamkaram/gismanager) | 50 | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| <b>[pbf](https://github.com/maguro/pbf) | 44 | OpenStreetMap PBF golang encoder/decoder. |
| <b>[S2 geojson](https://github.com/pantrif/s2-geojson) | 23 | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |
| <b>[H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) | 3 | Conversion utilities between H3 indexes and GeoJSON. |
| <b>[Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) | 3 | A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection. |
| <b>[H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) | 1 | Distribution of Uber H3geo cells by virtual nodes. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Compilers

_Tools for compiling Go to other languages._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopherjs](https://github.com/gopherjs/gopherjs) | 12.0k | Compiler from Go to JavaScript. |
| <b>[tardisgo](https://github.com/tardisgo/tardisgo) | 424 | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| <b>[c4go](https://github.com/Konstantin8105/c4go) | 335 | Transpile C code to Go code. |
| <b>[c2go](https://github.com/goplus/c2go) | 262 | Convert C code to Go code. |
| <b>[esp32](https://github.com/andygeiss/esp32-transpiler) | 68 | Transpile Go into Arduino code. |
| <b>[f4go](https://github.com/Konstantin8105/f4go) | 36 | Transpile FORTRAN 77 code to Go code. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Goroutines

_Tools for managing and working with Goroutines._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[ants](https://github.com/panjf2000/ants) | 10.0k | A high-performance and low-cost goroutine pool in Go. |
| <b>[conc](https://github.com/sourcegraph/conc) | 6.8k | `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer. |
| <b>[tunny](https://github.com/Jeffail/tunny) | 3.6k | Goroutine pool for golang. |
| <b>[goworker](https://github.com/benmanns/goworker) | 2.7k | goworker is a Go-based background worker. |
| <b>[workerpool](https://github.com/gammazero/workerpool) | 1.1k | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| <b>[pond](https://github.com/alitto/pond) | 901 | Minimalistic and High-performance goroutine worker pool written in Go. |
| <b>[grpool](https://github.com/ivpusic/grpool) | 729 | Lightweight Goroutine pool. |
| <b>[pool](https://github.com/go-playground/pool) | 714 | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| <b>[gowp](https://github.com/xxjwxc/gowp) | 449 | gowp is concurrency limiting goroutine pool. |
| <b>[go-floc](https://github.com/workanator/go-floc) | 262 | Orchestrate goroutines with ease. |
| <b>[go-flow](https://github.com/kamildrazkiewicz/go-flow) | 211 | Control goroutines execution order. |
| <b>[artifex](https://github.com/borderstech/artifex) | 172 | Simple in-memory job queue for Golang using worker-based dispatching. |
| <b>[semaphore](https://github.com/marusama/semaphore) | 160 | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| <b>[go-workers](https://github.com/catmullet/go-workers) | 159 | Easily and safely run workers for large data processing pipelines. |
| <b>[neilotoole/errgroup](https://github.com/neilotoole/errgroup) | 148 | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| <b>[routine](https://github.com/timandy/routine) | 131 | `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully. |
| <b>[cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 125 | CyclicBarrier for golang. |
| <b>[async](https://github.com/studiosol/async) | 119 | A safe way to execute functions asynchronously, recovering them in case of panic. |
| <b>[async](https://github.com/reugn/async) | 118 | An alternative sync library for Go (Future, Promise, Locks). |
| <b>[gollback](https://github.com/vardius/gollback) | 109 | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| <b>[Hunch](https://github.com/AaronJan/Hunch) | 95 | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| <b>[semaphore](https://github.com/kamilsk/semaphore) | 95 | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| <b>[threadpool](https://github.com/shettyh/threadpool) | 91 | Golang threadpool implementation. |
| <b>[worker-pool](https://github.com/vardius/worker-pool) | 86 | goworker is a Go simple async worker pool. |
| <b>[gpool](https://github.com/Sherifabdlnaby/gpool) | 85 | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| <b>[goccm](https://github.com/zenthangplus/goccm) | 65 | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| <b>[nursery](https://github.com/arunsworld/nursery) | 63 | Structured concurrency in Go. |
| <b>[routine](https://github.com/x-mod/routine) | 56 | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| <b>[go-actor](https://github.com/vladopajic/go-actor) | 53 | A tiny library for writing concurrent programs using actor model. |
| <b>[gowl](https://github.com/hamed-yousefi/gowl) | 53 | Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status. |
| <b>[gohive](https://github.com/loveleshsharma/gohive) | 45 | A highly performant and easy to use Goroutine pool for Go. |
| <b>[go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 41 | Like `sync.WaitGroup` with error handling and concurrency control. |
| <b>[kyoo](https://github.com/dirkaholic/kyoo) | 41 | Provides an unlimited job queue and concurrent worker pools. |
| <b>[parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 35 | Run functions in parallel. |
| <b>[go-trylock](https://github.com/subchen/go-trylock) | 33 | TryLock support on read-write lock for Golang. |
| <b>[channelify](https://github.com/ddelizia/channelify) | 27 | Transform your function to return channels for easy and powerful parallel processing. |
| <b>[stl](https://github.com/ssgreg/stl) | 26 | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| <b>[execpool](https://github.com/hexdigest/execpool) | 15 | A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command. |
| <b>[breaker](https://github.com/kamilsk/breaker) | 14 | Flexible mechanism to make execution flow interruptible. |
| <b>[concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) | 14 | Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines. |
| <b>[queue](https://github.com/AnikHasibul/queue) | 14 | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| <b>[conexec](https://github.com/ITcathyh/conexec) | 13 | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| <b>[go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) | 11 | Manage a pool of goroutines using this lightweight library with a simple API. |
| <b>[hands](https://github.com/duanckham/hands) | 10 | A process controller used to control the execution and return strategies of multiple goroutines. |
| <b>[go-workerpool](https://github.com/zenthangplus/go-workerpool) | 7 | Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines. |
| <b>[async-job](https://github.com/lab210-dev/async-job) | 6 | AsyncJob is an asynchronous queue job manager with light code, clear and speed. |
| <b>[oversight](https://cirello.io/oversight) | - | Oversight is a complete implementation of the Erlang supervision trees. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## GUI

_Interaction_


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fyne](https://github.com/fyne-io/fyne) | 20.0k | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| <b>[webview](https://github.com/zserge/webview) | 11.0k | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| <b>[qt](https://github.com/therecipe/qt) | 9.8k | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| <b>[robotgo](https://github.com/go-vgo/robotgo) | 8.4k | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| <b>[ui](https://github.com/andlabs/ui) | 8.3k | Platform-native GUI library for Go. Cross platform. |
| <b>[app](https://github.com/murlokswarm/app) | 7.1k | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| <b>[walk](https://github.com/lxn/walk) | 6.4k | Windows application library kit for Go. |
| <b>[go-astilectron](https://github.com/asticode/go-astilectron) | 4.7k | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| <b>[systray](https://github.com/getlantern/systray) | 2.8k | Cross platform Go library to place an icon and menu in the notification area. |
| <b>[go-sciter](https://github.com/sciter-sdk/go-sciter) | 2.5k | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| <b>[gotk3](https://github.com/gotk3/gotk3) | 1.9k | Go bindings for GTK3. |
| <b>[gosx-notifier](https://github.com/deckarep/gosx-notifier) | 579 | OSX Desktop Notifications library for Go. |
| <b>[zenity](https://github.com/ncruces/zenity) | 491 | Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user. |
| <b>[gowd](https://github.com/dtylman/gowd) | 398 | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| <b>[trayhost](https://github.com/shurcooL/trayhost) | 238 | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| <b>[mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 28 | OSX Sleep/Wake notifications in golang. |
| <b>[mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 25 | OSX library to notify about any (pluggable) activity on your machine. |
| <b>[go-appindicator](https://github.com/dawidd6/go-appindicator) | 19 | Go bindings for libappindicator3 C library. |
| <b>[goradd/html5tag](https://github.com/goradd/html5tag) | 4 | Library for outputting HTML5 tags. |
| <b>[AppIndicator Go](https://github.com/gopherlibs/appindicator) | 3 | Go bindings for libappindicator3 C library. |
| <b>[Wails](https://wails.io) | - | Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer. |
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
| <b>[arduino-cli](https://github.com/arduino/arduino-cli) | 3.9k | Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects. |
| <b>[go-rpio](https://github.com/stianeikeland/go-rpio) | 2.0k | GPIO for Go, doesn't require cgo. |
| <b>[ghw](https://github.com/jaypipes/ghw) | 1.3k | Golang hardware discovery/inspection library. |
| <b>[emgo](https://github.com/ziutek/emgo) | 1000 | Go-like language for programming embedded systems (e.g. STM32 MCU). |
| <b>[sysinfo](https://github.com/zcalusic/sysinfo) | 428 | A pure Go library providing Linux OS / kernel / hardware system information. |
| <b>[goroslib](https://github.com/aler9/goroslib) | 265 | Robot Operating System (ROS) library for Go. |
| <b>[go-osc](https://github.com/hypebeast/go-osc) | 171 | Open Sound Control (OSC) bindings for Go. |
| <b>[joystick](https://github.com/0xcafed00d/joystick) | 46 | a polled API to read the state of an attached joystick. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Images

_Libraries for manipulating images._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gocv](https://github.com/hybridgroup/gocv) | 5.5k | Go package for computer vision using OpenCV 3.3+. |
| <b>[imaginary](https://github.com/h2non/imaginary) | 4.8k | Fast and simple HTTP microservice for image resizing. |
| <b>[imaging](https://github.com/disintegration/imaging) | 4.7k | Simple Go image processing package. |
| <b>[gg](https://github.com/fogleman/gg) | 3.9k | 2D rendering in pure Go. |
| <b>[bild](https://github.com/anthonynsimon/bild) | 3.8k | Collection of image processing algorithms in pure Go. |
| <b>[ln](https://github.com/fogleman/ln) | 3.2k | 3D line art rendering in Go. |
| <b>[resize](https://github.com/nfnt/resize) | 2.9k | Image resizing for Go with common interpolation methods. |
| <b>[bimg](https://github.com/h2non/bimg) | 2.3k | Small package for fast and efficient image processing using libvips. |
| <b>[gowitness](https://github.com/sensepost/gowitness) | 2.2k | Screenshoting webpages using go and headless chrome on command line. |
| <b>[pt](https://github.com/fogleman/pt) | 2.1k | Path tracing engine written in Go. |
| <b>[svgo](https://github.com/ajstarks/svgo) | 2.0k | Go Language Library for SVG generation. |
| <b>[picfit](https://github.com/thoas/picfit) | 1.8k | An image resizing server written in Go. |
| <b>[gift](https://github.com/disintegration/gift) | 1.7k | Package of image processing filters. |
| <b>[smartcrop](https://github.com/muesli/smartcrop) | 1.7k | Finds good crops for arbitrary images and crop sizes. |
| <b>[imagick](https://github.com/gographics/imagick) | 1.6k | Go binding to ImageMagick's MagickWand C API. |
| <b>[canvas](https://github.com/tdewolff/canvas) | 1.3k | Vector graphics to PDF, SVG or rasterized image. |
| <b>[go-opencv](https://github.com/lazywei/go-opencv) | 1.3k | Go bindings for OpenCV. |
| <b>[geopattern](https://github.com/pravj/geopattern) | 1.2k | Create beautiful generative image patterns from a string. |
| <b>[stegify](https://github.com/DimitarPetrov/stegify) | 1.1k | Go tool for LSB steganography, capable of hiding any file within an image. |
| <b>[govips](https://github.com/davidbyttow/govips) | 914 | A lightning fast image processing and resizing library for Go. |
| <b>[image2ascii](https://github.com/qeesung/image2ascii) | 768 | Convert image to ASCII. |
| <b>[goimagehash](https://github.com/corona10/goimagehash) | 610 | Go Perceptual image hashing package. |
| <b>[draft](https://github.com/lucasepe/draft) | 566 | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| <b>[govatar](https://github.com/o1egl/govatar) | 563 | Library and CMD tool for generating funny avatars. |
| <b>[mort](https://github.com/aldor007/mort) | 482 | Storage and image processing server written in Go. |
| <b>[go-nude](https://github.com/koyachi/go-nude) | 375 | Nudity detection with Go. |
| <b>[steganography](https://github.com/auyer/steganography) | 240 | Pure Go Library for LSB steganography. |
| <b>[darkroom](https://github.com/gojek/darkroom) | 211 | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| <b>[rez](https://github.com/bamiaux/rez) | 209 | Image resizing in pure Go and SIMD. |
| <b>[mergi](https://github.com/noelyahan/mergi) | 204 | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| <b>[gltf](https://github.com/qmuntal/gltf) | 201 | Efficient and robust glTF 2.0 reader, writer and validator. |
| <b>[img](https://github.com/hawx/img) | 148 | Selection of image manipulation tools. |
| <b>[go-cairo](https://github.com/ungerik/go-cairo) | 134 | Go binding for the cairo graphics library. |
| <b>[go-webp](https://github.com/kolesa-team/go-webp) | 134 | Library for encode and decode webp pictures, using libwebp. |
| <b>[cameron](https://github.com/aofei/cameron) | 102 | An avatar generator for Go. |
| <b>[gridder](https://github.com/shomali11/gridder) | 65 | A Grid based 2D Graphics library. |
| <b>[webp-server](https://github.com/mehdipourfar/webp-server) | 59 | Simple and minimal image server capable of storing, resizing, converting and caching images. |
| <b>[color-extractor](https://github.com/marekm4/color-extractor) | 58 | Dominant color extractor with no external dependencies. |
| <b>[go-gd](https://github.com/bolknote/go-gd) | 57 | Go binding for GD library. |
| <b>[goimghdr](https://github.com/corona10/goimghdr) | 40 | The imghdr module determines the type of image contained in a file for Go. |
| <b>[tga](https://github.com/ftrvxmtrx/tga) | 32 | Package tga is a TARGA image format decoder/encoder. |
| <b>[go-webcolors](https://github.com/jyotiska/go-webcolors) | 27 | Port of webcolors library from Python to Go. |
| <b>[mpo](https://github.com/donatj/mpo) | 11 | Decoder and conversion tool for MPO 3D Photos. |
| <b>[scout](https://github.com/jonoton/scout) | 9 | Scout is a standalone open source software solution for DIY video security. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## IoT (Internet of Things)

_Libraries for programming devices of the IoT._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gobot](https://github.com/hybridgroup/gobot/) | 8.3k | Gobot is a framework for robotics, physical computing, and the Internet of Things. |
| <b>[flogo](https://github.com/tibcosoftware/flogo) | 2.3k | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| <b>[mainflux](https://github.com/Mainflux/mainflux) | 2.1k | Industrial IoT Messaging and Device Management Server. |
| <b>[gatt](https://github.com/paypal/gatt) | 1.1k | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| <b>[ekuiper](https://github.com/lf-edge/ekuiper) | 1000 | Lightweight data stream processing engine for IoT edge. |
| <b>[connectordb](https://github.com/connectordb/connectordb) | 367 | Open-Source Platform for Quantified Self & IoT. |
| <b>[devices](https://github.com/goiot/devices) | 260 | Suite of libraries for IoT devices, experimental for x/exp/io. |
| <b>[huego](https://github.com/amimof/huego) | 231 | An extensive Philips Hue client library for Go. |
| <b>[sensorbee](https://github.com/sensorbee/sensorbee) | 220 | Lightweight stream processing engine for IoT. |
| <b>[iot](https://github.com/vaelen/iot/) | 63 | IoT is a simple framework for implementing a Google IoT Core device. |
| <b>[eywa](https://github.com/xcodersun/eywa) | 60 | Project Eywa is essentially a connection manager that keeps track of connected devices. |
| <b>[periph](https://periph.io/) | - | Peripherals I/O to interface with low-level board facilities. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Job Scheduler

_Libraries for scheduling jobs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gocron](https://github.com/go-co-op/gocron) | 3.4k | Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). |
| <b>[go-quartz](https://github.com/reugn/go-quartz) | 1.3k | Simple, zero-dependency scheduling library for Go. |
| <b>[gron](https://github.com/roylee0704/gron) | 973 | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| <b>[JobRunner](https://github.com/bamzi/jobrunner) | 969 | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| <b>[Dagu](https://github.com/dagu-go/dagu) | 780 | No-code workflow executor. it executes DAGs defined in a simple YAML format. |
| <b>[jobs](https://github.com/albrow/jobs) | 495 | Persistent and flexible background jobs library. |
| <b>[scheduler](https://github.com/carlescere/scheduler) | 428 | Cronjobs scheduling made easy. |
| <b>[gronx](https://github.com/adhocore/gronx) | 271 | Cron expression parser, task runner and daemon consuming crontab like task list. |
| <b>[go-cron](https://github.com/rk/go-cron) | 216 | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| <b>[tasks](https://github.com/madflojo/tasks) | 154 | An easy to use in-process scheduler for recurring tasks in Go. |
| <b>[clockwerk](https://github.com/onatm/clockwerk) | 136 | Go package to schedule periodic jobs using a simple, fluent syntax. |
| <b>[goflow](https://github.com/fieldryand/goflow) | 118 | A workflow orchestrator and scheduler for rapid prototyping of ETL/ML/AI pipelines. |
| <b>[leprechaun](https://github.com/kilgaloon/leprechaun) | 97 | Job scheduler that supports webhooks, crons and classic scheduling. |
| <b>[cheek](https://github.com/datarootsio/cheek) | 77 | A simple crontab like scheduler that aims to offer a KISS approach to job scheduling. |
| <b>[cdule](https://github.com/deepaksinghvi/cdule) | 35 | Job scheduler library with database support |
| <b>[sched](https://github.com/romshark/sched) | 26 | A job scheduler with the ability to fast-forward time. |
| <b>[cronticker](https://github.com/krayzpipes/cronticker) | 10 | A ticker implementation to support cron schedules. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## JSON

_Libraries for working with JSON._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GJSON](https://github.com/tidwall/gjson) | 12.0k | Get a JSON value with one line of code. |
| <b>[gojson](https://github.com/ChimeraCoder/gojson) | 2.6k | Automatically generate Go (golang) struct definitions from example JSON. |
| <b>[fastjson](https://github.com/valyala/fastjson) | 1.9k | Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. |
| <b>[OjG](https://github.com/ohler55/ojg) | 610 | Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath. |
| <b>[marshmallow](https://github.com/PerimeterX/marshmallow) | 299 | Performant JSON unmarshaling for flexible use cases. |
| <b>[kazaam](https://github.com/Qntfy/kazaam) | 256 | API for arbitrary transformation of JSON documents. |
| <b>[jsondiff](https://github.com/wI2L/jsondiff) | 253 | JSON diff library for Go based on RFC6902 (JSON Patch). |
| <b>[gojq](https://github.com/elgs/gojq) | 187 | JSON query in Golang. |
| <b>[ajson](https://github.com/spyzhov/ajson) | 165 | Abstract JSON for golang with JSONPath support. |
| <b>[jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) | 153 | A fast and convinient library for unstructured JSON data, replacing `encoding/json`. |
| <b>[jettison](https://github.com/wI2L/jettison) | 148 | Fast and flexible JSON encoder for Go. |
| <b>[gjo](https://github.com/skanehira/gjo) | 120 | Small utility to create JSON objects. |
| <b>[json2go](https://github.com/m-zajac/json2go) | 118 | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| <b>[jsongo](https://github.com/ricardolonga/jsongo) | 109 | Fluent API to make it easier to create Json objects. |
| <b>[JayDiff](https://github.com/yazgazan/jaydiff) | 96 | JSON diff utility written in Go. |
| <b>[jsonf](https://github.com/miolini/jsonf) | 64 | Console tool for highlighted formatting and struct query fetching JSON. |
| <b>[ujson](https://github.com/olvrng/ujson) | 64 | Fast and minimal JSON parser and transformer that works on unstructured JSON. |
| <b>[go-respond](https://github.com/nicklaw5/go-respond) | 51 | Go package for handling common HTTP JSON responses. |
| <b>[mp](https://github.com/sanbornm/mp) | 46 | Simple cli email parser. It currently takes stdin and outputs JSON. |
| <b>[vjson](https://github.com/miladibra10/vjson) | 34 | Go package for validating JSON objects with declaring a JSON schema with fluent API. |
| <b>[jsoncolor](https://github.com/neilotoole/jsoncolor) | 33 | Drop-in replacement for `encoding/json` that outputs colorized JSON. |
| <b>[jscan](https://github.com/romshark/jscan) | 30 | High performance zero-allocation JSON iterator. |
| <b>[ask](https://github.com/simonnilsson/ask) | 25 | Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types. |
| <b>[gojmapr](https://github.com/limiu82214/gojmapr) | 19 | Get simple struct from complex json by json path. |
| <b>[dynjson](https://github.com/cocoonspace/dynjson) | 15 | Client-customizable JSON formats for dynamic APIs. |
| <b>[mapslice-json](https://github.com/mickep76/mapslice-json) | 15 | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| <b>[go-jsonerror](https://github.com/ddymko/go-jsonerror) | 13 | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| <b>[jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 13 | Go bindings based on the JSON API errors reference. |
| <b>[jsonhal](https://github.com/RichardKnop/jsonhal) | 13 | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| <b>[epoch](https://github.com/vtopc/epoch) | 12 | Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON. |
| <b>[jzon](https://github.com/zerosnake0/jzon) | 11 | JSON library with standard compatible API/behavior. |
| <b>[ej](https://github.com/lucassscaravelli/ej) | 9 | Write and read JSON from different sources succinctly. |
| <b>[jsonic](https://github.com/sinhashubham95/jsonic) | 9 | Utilities to handle and query JSON without defining structs in a type safe manner. |
| <b>[omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) | 4 | Simple JSON parser with validation by condition via golang struct fields tags. |
| <b>[htmljson](https://github.com/nikolaydubina/htmljson) | 3 | Rich rendering of JSON as HTML in Go. |
| <b>[jsonhandlers](https://github.com/abusomani/jsonhandlers) | 1 | JSON library to expose simple handlers that lets you easily read and write json from various sources. |
| <b>[JSON-to-Go](https://mholt.github.io/json-to-go/) | - | Convert JSON to Go struct. |
| <b>[JSON-to-Proto](https://json-to-proto.github.io/) | - | Convert JSON to Protobuf online. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Logging

_Libraries for generating and working with log files._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[logrus](https://github.com/Sirupsen/logrus) | 23.0k | Structured logger for Go. |
| <b>[zap](https://github.com/uber-go/zap) | 19.0k | Fast, structured, leveled logging in Go. |
| <b>[zerolog](https://github.com/rs/zerolog) | 8.3k | Zero-allocation JSON logger. |
| <b>[spew](https://github.com/davecgh/go-spew) | 5.6k | Implements a deep pretty printer for Go data structures to aid in debugging. |
| <b>[lumberjack](https://github.com/natefinch/lumberjack) | 4.1k | Simple rolling logger, implements io.WriteCloser. |
| <b>[glog](https://github.com/golang/glog) | 3.4k | Leveled execution logs for Go. |
| <b>[tail](https://github.com/hpcloud/tail) | 2.6k | Go package striving to emulate the features of the BSD tail program. |
| <b>[pp](https://github.com/k0kubun/pp) | 1.6k | Colored pretty printer for Go language. |
| <b>[seelog](https://github.com/cihub/seelog) | 1.6k | Logging functionality with flexible dispatching, filtering, and formatting. |
| <b>[log](https://github.com/apex/log) | 1.3k | Structured logging package for Go. |
| <b>[log15](https://github.com/inconshreveable/log15) | 1.1k | Simple, powerful logging for Go. |
| <b>[phuslu/log](https://github.com/phuslu/log) | 498 | Structured Logging Made Easy. |
| <b>[onelog](https://github.com/francoispqt/onelog) | 409 | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. |
| <b>[logutils](https://github.com/hashicorp/logutils) | 354 | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| <b>[logxi](https://github.com/mgutz/logxi) | 349 | 12-factor app logger that is fast and makes you happy. |
| <b>[sqldb-logger](https://github.com/simukti/sqldb-logger) | 304 | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| <b>[httpretty](https://github.com/henvic/httpretty) | 300 | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| <b>[go-logger](https://github.com/apsdehal/go-logger) | 286 | Simple logger of Go Programs, with level handlers. |
| <b>[log](https://github.com/go-playground/log) | 285 | Simple, configurable and scalable Structured Logging for Go. |
| <b>[rollingwriter](https://github.com/arthurkiller/rollingWriter) | 279 | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| <b>[slog](https://github.com/gookit/slog) | 232 | Lightweight, configurable, extensible logger for Go. |
| <b>[logur](https://github.com/logur/logur) | 193 | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| <b>[glg](https://github.com/kpango/glg) | 183 | glg is simple and fast leveled logging library for Go. |
| <b>[tint](https://github.com/lmittmann/tint) | 183 | A slog.Handler that writes tinted logs. |
| <b>[logger](https://github.com/azer/logger) | 157 | Minimalistic logging library for Go. |
| <b>[xlog](https://github.com/rs/xlog) | 137 | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| <b>[ozzo-log](https://github.com/go-ozzo/ozzo-log) | 122 | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| <b>[log-voyage](https://github.com/firstrow/logvoyage) | 94 | Full-featured logging saas written in golang. |
| <b>[go-cronowriter](https://github.com/utahta/go-cronowriter) | 55 | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| <b>[stdlog](https://github.com/alexcesaro/log) | 47 | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| <b>[slog-multi](https://github.com/samber/slog-multi) | 47 | Chain of slog.Handler (pipeline, fanout...). |
| <b>[gone/log](https://github.com/One-com/gone/tree/master/log) | 45 | Fast, extendable, full-featured, std-lib source compatible log library. |
| <b>[noodlog](https://github.com/gyozatech/noodlog) | 44 | Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings. |
| <b>[go-log](https://github.com/ian-kent/go-log) | 41 | Log4j implementation in Go. |
| <b>[gologger](https://github.com/sadlil/gologger) | 41 | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| <b>[logex](https://github.com/chzyer/logex) | 41 | Golang log lib, supports tracking and level, wrap by standard log lib. |
| <b>[journald](https://github.com/ssgreg/journald) | 36 | Go implementation of systemd Journal's native API for logging. |
| <b>[go-log](https://github.com/siddontang/go-log) | 33 | Log lib supports level and multi handlers. |
| <b>[mlog](https://github.com/jbrodriguez/mlog) | 32 | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| <b>[distillog](https://github.com/amoghe/distillog) | 31 | distilled levelled logging (think of it as stdlib + log levels). |
| <b>[logrusly](https://github.com/sebest/logrusly) | 28 | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| <b>[log](https://github.com/teris-io/log) | 26 | Structured log interface for Go cleanly separates logging facade from its implementation. |
| <b>[zkits-logger](https://github.com/edoger/zkits-logger) | 24 | A powerful zero-dependency JSON logger. |
| <b>[gomol](https://github.com/aphistic/gomol) | 19 | Multiple-output, structured logging for Go with extensible logging outputs. |
| <b>[logmatic](https://github.com/borderstech/logmatic) | 16 | Colorized logger for Golang with dynamic log level configuration. |
| <b>[slog-formatter](https://github.com/samber/slog-formatter) | 16 | Common formatters for slog and helpers to build your own. |
| <b>[glo](https://github.com/lajosbencz/glo) | 15 | PHP Monolog inspired logging facility with identical severity levels. |
| <b>[xylog](https://github.com/xybor-x/xylog) | 14 | Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax. |
| <b>[go-log](https://github.com/subchen/go-log) | 14 | Simple and configurable Logging in Go, with level, formatters and writers. |
| <b>[logrusiowriter](https://github.com/cabify/logrusiowriter) | 14 | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| <b>[log](https://github.com/heartwilltell/log) | 14 | Simple leveled logging wrapper around standard log package. |
| <b>[logdump](https://github.com/ewwwwwqm/logdump) | 11 | Package for multi-level logging. |
| <b>[logo](https://github.com/mbndr/logo) | 11 | Golang logger to different configurable writers. |
| <b>[go-log](https://github.com/pieterclaerhout/go-log) | 10 | A logging library with strack traces, object dumping and optional timestamps. |
| <b>[kemba](https://github.com/clok/kemba) | 10 | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |
| <b>[log](https://github.com/aerogo/log) | 10 | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| <b>[xlog](https://github.com/xfxdev/xlog) | 8 | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| <b>[structy/log](https://github.com/structy/log) | 5 | A simple to use log system, minimalist but with features for debugging and differentiation of messages. |
| <b>[slf4g](https://github.com/echocat/slf4g) | 3 | Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks. |
| <b>[yell](https://github.com/jfcg/yell) | 1 | Yet another minimalistic logging library. |
| <b>[log](https://github.com/no-src/log) | 0 | A simple logging framework out of the box. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Machine Learning

_Libraries for Machine Learning._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GoLearn](https://github.com/sjwhitworth/golearn) | 8.9k | General Machine Learning library for Go. |
| <b>[gorse](https://github.com/zhenghaoz/gorse) | 6.9k | An offline recommender system backend based on collaborative filtering written in Go. |
| <b>[gorgonia](https://github.com/gorgonia/gorgonia) | 5.0k | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| <b>[m2cgen](https://github.com/BayesWitnesses/m2cgen) | 2.5k | A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support. |
| <b>[tfgo](https://github.com/galeone/tfgo) | 2.2k | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| <b>[gosseract](https://github.com/otiai10/gosseract) | 2.1k | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| <b>[goml](https://github.com/cdipaolo/goml) | 1.5k | On-line Machine Learning in Go. |
| <b>[eaopt](https://github.com/MaxHalford/eaopt) | 841 | An evolutionary optimization library. |
| <b>[bayesian](https://github.com/jbrukh/bayesian) | 762 | Naive Bayesian Classification for Golang. |
| <b>[CloudForest](https://github.com/ryanbressler/CloudForest) | 727 | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| <b>[ocrserver](https://github.com/otiai10/ocrserver) | 575 | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| <b>[gobrain](https://github.com/goml/gobrain) | 543 | Neural Networks written in go. |
| <b>[onnx-go](https://github.com/owulveryck/onnx-go) | 502 | Go Interface to Open Neural Network Exchange (ONNX). |
| <b>[go-deep](https://github.com/patrikeh/go-deep) | 447 | A feature-rich neural network library in Go. |
| <b>[regommend](https://github.com/muesli/regommend) | 302 | Recommendation & collaborative filtering engine. |
| <b>[Goptuna](https://github.com/c-bata/goptuna) | 238 | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| <b>[go-galib](https://github.com/thoj/go-galib) | 195 | Genetic Algorithms library written in Go / golang. |
| <b>[goRecommend](https://github.com/timkaye11/goRecommend) | 194 | Recommendation Algorithms library written in Go. |
| <b>[goga](https://github.com/tomcraven/goga) | 191 | Genetic algorithm library for Go. |
| <b>[shield](https://github.com/eaigner/shield) | 154 | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| <b>[go-fann](https://github.com/white-pony/go-fann) | 114 | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| <b>[go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) | 97 | Fast and convenient feature processing for low latency machine learning in Go. |
| <b>[goscore](https://github.com/asafschers/goscore) | 88 | Go Scoring API for PMML. |
| <b>[gonet](https://github.com/dathoangnd/gonet) | 79 | Neural Network for Go. |
| <b>[fonet](https://github.com/Fontinalis/fonet) | 77 | A Deep Neural Network library written in Go. |
| <b>[libsvm](https://github.com/datastream/libsvm) | 73 | libsvm golang version derived work based on LIBSVM 3.14. |
| <b>[neat](https://github.com/jinyeom/neat) | 67 | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| <b>[neural-go](https://github.com/schuyler/neural-go) | 65 | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| <b>[go-pr](https://github.com/daviddengcn/go-pr) | 62 | Pattern recognition package in Go lang. |
| <b>[GoMind](https://github.com/surenderthakran/gomind) | 55 | A simplistic Neural Network Library in Go. |
| <b>[Varis](https://github.com/Xamber/Varis) | 52 | Golang Neural Network. |
| <b>[golinear](https://github.com/danieldk/golinear) | 45 | liblinear bindings for Go. |
| <b>[go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 39 | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| <b>[godist](https://github.com/e-dard/godist) | 35 | Various probability distributions, and associated methods. |
| <b>[randomforest](https://github.com/malaschitz/randomForest) | 30 | Easy to use Random Forest library for Go. |
| <b>[ddt](https://github.com/sgrodriguez/ddt) | 28 | Dynamic decision tree, create trees defining customizable rules. |
| <b>[evoli](https://github.com/khezen/evoli) | 26 | Genetic Algorithm and Particle Swarm Optimization library. |
| <b>[probab](https://github.com/ThePaw/probab) | 18 | Probability distribution functions. Bayesian inference. Written in pure Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Messaging

_Libraries that implement messaging systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sarama](https://github.com/Shopify/sarama) | 10.0k | Go library for Apache Kafka. |
| <b>[Centrifugo](https://github.com/centrifugal/centrifugo) | 7.1k | Real-time messaging (Websockets or SockJS) server in Go. |
| <b>[gorush](https://github.com/appleboy/gorush) | 7.1k | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| <b>[machinery](https://github.com/RichardKnop/machinery) | 6.9k | Asynchronous task queue/job queue based on distributed message passing. |
| <b>[Asynq](https://github.com/hibiken/asynq) | 6.2k | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| <b>[Benthos](https://github.com/Jeffail/benthos) | 6.2k | A message streaming bridge between a range of protocols. |
| <b>[Watermill](https://github.com/ThreeDotsLabs/watermill) | 5.6k | Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog. |
| <b>[go-socket.io](https://github.com/googollee/go-socket.io) | 5.2k | socket.io library for golang, a realtime application framework. |
| <b>[NATS Go Client](https://github.com/nats-io/nats) | 4.6k | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| <b>[Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) | 4.0k | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| <b>[Mercure](https://github.com/dunglas/mercure) | 3.4k | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| <b>[melody](https://github.com/olahol/melody) | 3.1k | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| <b>[APNs2](https://github.com/sideshow/apns2) | 2.8k | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| <b>[go-nsq](https://github.com/nsqio/go-nsq) | 2.4k | the official Go package for NSQ. |
| <b>[gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 2.1k | gopush-cluster is a go push server cluster. |
| <b>[Uniqush-Push](https://github.com/uniqush/uniqush-push) | 1.5k | Redis backed unified push service for server-side notifications to mobile devices. |
| <b>[Beaver](https://github.com/Clivern/Beaver) | 1.4k | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| <b>[EventBus](https://github.com/asaskevich/EventBus) | 1.4k | The lightweight event bus with async compatibility. |
| <b>[Chanify](https://github.com/chanify/chanify) | 1.1k | A push notification server send message to your iOS devices. |
| <b>[zmq4](https://github.com/pebbe/zmq4) | 1.1k | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| <b>[Gollum](https://github.com/trivago/gollum) | 931 | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| <b>[amqp](https://github.com/rabbitmq/amqp091-go) | 868 | Go RabbitMQ Client Library. |
| <b>[dbus](https://github.com/godbus/dbus) | 853 | Native Go bindings for D-Bus. |
| <b>[golongpoll](https://github.com/jcuga/golongpoll) | 634 | HTTP longpoll server library that makes web pub-sub simple. |
| <b>[mangos](https://github.com/nanomsg/mangos) | 594 | Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. |
| <b>[emitter](https://github.com/olebedev/emitter) | 464 | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| <b>[Glue](https://github.com/desertbit/glue) | 408 | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| <b>[pubsub](https://github.com/tuxychandru/pubsub) | 390 | Simple pubsub package for go. |
| <b>[Quamina](https://github.com/timbray/quamina) | 345 | Fast pattern-matching for filtering messages and events. |
| <b>[Bus](https://github.com/mustafaturan/bus) | 301 | Minimalist message bus implementation for internal communication. |
| <b>[messagebus](https://github.com/vardius/message-bus) | 247 | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| <b>[rabtap](https://github.com/jandelgado/rabtap) | 240 | RabbitMQ swiss army knife cli app. |
| <b>[guble](https://github.com/smancke/guble) | 155 | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| <b>[hub](https://github.com/leandro-lugaresi/hub) | 130 | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| <b>[oplog](https://github.com/dailymotion/oplog) | 114 | Generic oplog/replication system for REST APIs. |
| <b>[redisqueue](https://github.com/robinjoseph08/redisqueue) | 112 | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| <b>[rabbus](https://github.com/rafaeljesus/rabbus) | 97 | A tiny wrapper over amqp exchanges and queues. |
| <b>[go-mq](https://github.com/cheshir/go-mq) | 86 | RabbitMQ client with declarative configuration. |
| <b>[Ratus](https://github.com/hyperonym/ratus) | 84 | Ratus is a RESTful asynchronous task queue server. |
| <b>[drone-line](https://github.com/appleboy/drone-line) | 79 | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| <b>[nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 76 | A tiny wrapper around NSQ topic and channel. |
| <b>[go-notify](https://github.com/TheCreeper/go-notify) | 66 | Native implementation of the freedesktop notification spec. |
| <b>[Commander](https://github.com/jeroenrinzema/commander) | 65 | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| <b>[RapidMQ](https://github.com/sybrexsys/RapidMQ) | 65 | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| <b>[go-res](https://github.com/jirenius/go-res) | 62 | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| <b>[event](https://github.com/agoalofalife/event) | 53 | Implementation of the pattern observer. |
| <b>[hare](https://github.com/leozz37/hare) | 53 | A user friendly library for sending messages and listening to TCP sockets. |
| <b>[ami](https://github.com/kak-tus/ami) | 26 | Go client to reliable queues based on Redis Cluster Streams. |
| <b>[go-vitotrol](https://github.com/maxatome/go-vitotrol) | 22 | Client library to Viessmann Vitotrol web service. |
| <b>[gosd](https://github.com/alexsniffin/gosd) | 22 | A library for scheduling when to dispatch a message to a channel. |
| <b>[rmqconn](https://github.com/sbabiv/rmqconn) | 20 | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| <b>[jazz](https://github.com/socifi/jazz) | 17 | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| <b>[mob](https://github.com/erni27/mob) | 11 | mob is a generic-based, simple mediator / event aggregator library. It supports in-process requests / events processing. |
| <b>[gaurun-client](https://github.com/osamingo/gaurun-client) | 11 | Gaurun Client written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Microsoft Office


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[unioffice](https://github.com/unidoc/unioffice) | 3.8k | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |


<br>

[👆back to top](#catalogue-list)


<br>

### Microsoft Excel

_Libraries for working with Microsoft Excel._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[excelize](https://github.com/xuri/excelize) | 15.0k | Golang library for reading and writing Microsoft Excel&trade; (XLSX) files. |
| <b>[xlsx](https://github.com/tealeg/xlsx) | 5.5k | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| <b>[go-excel](https://github.com/szyhf/go-excel) | 175 | A simple and light reader to read a relate-db-like excel as a table. |
| <b>[xlsx](https://github.com/plandem/xlsx) | 162 | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| <b>[goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 20 | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |
| <b>[exl](https://github.com/go-the-way/exl) | 17 | Excel binding to struct written in Go.(Only supports Go1.18+) |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Miscellaneous


<br>

### Dependency Injection

_Libraries for working with dependency injection._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[google/wire](https://github.com/google/wire) | 11.0k | Automated Initialization in Go. |
| <b>[fx](https://github.com/uber-go/fx) | 4.0k | A dependency injection based application framework for Go (built on top of dig). |
| <b>[dig](https://github.com/uber-go/dig) | 3.2k | A reflection based dependency injection toolkit for Go. |
| <b>[do](https://github.com/samber/do) | 1.1k | A dependency injection framework based on Generics. |
| <b>[GoLobby/Container](https://github.com/golobby/container) | 465 | GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language. |
| <b>[goioc/di](https://github.com/goioc/di) | 271 | Spring-inspired Dependency Injection Container. |
| <b>[di](https://github.com/goava/di) | 192 | A dependency injection container for go programming language. |
| <b>[dingo](https://github.com/i-love-flamingo/dingo) | 161 | A dependency injection toolkit for Go, based on Guice. |
| <b>[alice](https://github.com/magic003/alice) | 51 | Additive dependency injection container for Golang. |
| <b>[wire](https://github.com/Fs02/wire) | 38 | Strict Runtime Dependency Injection for Golang. |
| <b>[linker](https://github.com/logrange/linker) | 35 | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| <b>[nject](https://github.com/muir/nject) | 25 | A type safe, reflective framework for libraries, tests, http endpoints, and service startup. |
| <b>[gocontainer](https://github.com/vardius/gocontainer) | 18 | Simple Dependency Injection Container. |
| <b>[kinit](https://github.com/go-kata/kinit) | 8 | Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization. |
| <b>[HnH/di](https://github.com/HnH/di) | 6 | DI container library that is focused on clean API and flexibility. |


<br>

[👆back to top](#catalogue-list)


<br>

### Project Layout

_**Unofficial** set of patterns for structuring projects._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golang-standards/project-layout](https://github.com/golang-standards/project-layout) | 40.0k | Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful. |
| <b>[ardanlabs/service](https://github.com/ardanlabs/service) | 2.8k | A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications. |
| <b>[modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 1.6k | Go application boilerplate and example applying modern practices. |
| <b>[pagoda](https://github.com/mikestefanello/pagoda) | 800 | Rapid, easy full-stack web development starter kit built in Go. |
| <b>[cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 615 | A Go application boilerplate template for quick starting projects following production best practices. |
| <b>[golang-templates/seed](https://github.com/golang-templates/seed) | 382 | Go application GitHub repository template. |
| <b>[go-starter](https://github.com/allaboutapps/go-starter) | 342 | An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers. |
| <b>[go-todo-backend](https://github.com/Fs02/go-todo-backend) | 224 | Go Todo Backend example using modular project layout for product microservice. |
| <b>[scaffold](https://github.com/catchplay/scaffold) | 140 | Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. |
| <b>[go-sample](https://github.com/zitryss/go-sample) | 123 | A sample layout for Go application projects with the real code. |
| <b>[gobase](https://github.com/wajox/gobase) | 47 | A simple skeleton for golang application with basic setup for real golang application. |
| <b>[wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) | 20 | Set of practices and discussions on how to structure Go project layout. |
| <b>[insidieux/inizio](https://github.com/insidieux/inizio) | 15 | Golang project layout generator with plugins. |
| <b>[go-module](https://github.com/octomation/go-module) | 11 | Template for a typical module written on Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Strings

_Libraries for working with strings._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[xstrings](https://github.com/huandu/xstrings) | 1.2k | Collection of useful string functions ported from other languages. |
| <b>[sttr](https://github.com/abhimanyu003/sttr) | 717 | cross-platform, cli app to perform various operations on string. |
| <b>[strutil](https://github.com/ozgio/strutil) | 194 | String utilities. |
| <b>[gobeam/Stringy](https://github.com/gobeam/Stringy) | 179 | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| <b>[caps](https://github.com/chanced/caps) | 47 | A case conversion library. |
| <b>[bexp](https://github.com/mkungla/bexp) | 0 | Go implementation of Brace Expansion mechanism to generate arbitrary strings. |
| <b>[go-formatter](https://gitlab.com/tymonx/go-formatter) | - | Implements **replacement fields** surrounded by curly braces `{}` format strings. |


<br>

[👆back to top](#catalogue-list)


<br>

### Uncategorized

_These libraries were placed here because none of the other categories seemed to fit._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopsutil](https://github.com/shirou/gopsutil) | 9.1k | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| <b>[archiver](https://github.com/mholt/archiver) | 4.0k | Library and command for making and extracting .zip and .tar.gz archives. |
| <b>[gatus](https://github.com/TwinProduction/gatus) | 3.7k | Automated service health dashboard. |
| <b>[gofakeit](https://github.com/brianvoe/gofakeit) | 3.1k | Random data generator written in go. |
| <b>[base64Captcha](https://github.com/mojocn/base64Captcha) | 1.8k | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| <b>[go-resiliency](https://github.com/eapache/go-resiliency) | 1.8k | Resiliency patterns for golang. |
| <b>[gosms](https://github.com/haxpax/gosms) | 1.4k | Your own local SMS gateway in Go that can be used to send SMS. |
| <b>[go-commons-pool](https://github.com/jolestar/go-commons-pool) | 1.2k | Generic object pool for Golang. |
| <b>[llvm](https://github.com/llir/llvm) | 1.1k | Library for interacting with LLVM IR in pure Go. |
| <b>[shortid](https://github.com/teris-io/shortid) | 852 | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| <b>[health](https://github.com/alexliesenfeld/health) | 677 | A simple and flexible health check library for Go. |
| <b>[shoutrrr](https://github.com/containrrr/shoutrrr) | 647 | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| <b>[stateless](https://github.com/qmuntal/stateless) | 617 | A fluent library for creating state machines. |
| <b>[health](https://github.com/dimiro1/health) | 443 | Easy to use, extensible health check library. |
| <b>[banner](https://github.com/dimiro1/banner) | 434 | Add beautiful banners into your Go applications. |
| <b>[xz](https://github.com/ulikunitz/xz) | 416 | Pure golang package for reading and writing xz-compressed files. |
| <b>[conv](https://github.com/cstockton/go-conv) | 386 | Package conv provides fast and intuitive conversions across Go types. |
| <b>[gountries](https://github.com/pariz/gountries) | 382 | Package that exposes country and subdivision data. |
| <b>[ffmt](https://github.com/go-ffmt/ffmt) | 292 | Beautify data display for Humans. |
| <b>[lk](https://github.com/hyperboloide/lk) | 291 | A simple licensing library for golang. |
| <b>[healthcheck](https://github.com/etherlabsio/healthcheck) | 255 | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| <b>[antch](https://github.com/antchfx/antch) | 249 | A fast, powerful and extensible web crawling & scraping framework. |
| <b>[go-unarr](https://github.com/gen2brain/go-unarr) | 238 | Decompression library for RAR, TAR, ZIP and 7z archives. |
| <b>[battery](https://github.com/distatus/battery) | 222 | Cross-platform, normalized battery information library. |
| <b>[bitio](https://github.com/icza/bitio) | 219 | Highly optimized bit-level Reader and Writer for Go. |
| <b>[stats](https://github.com/go-playground/stats) | 164 | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| <b>[turtle](https://github.com/hackebrot/turtle) | 150 | Emojis for Go. |
| <b>[captcha](https://github.com/steambap/captcha) | 131 | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| <b>[gotoprom](https://github.com/cabify/gotoprom) | 106 | Type-safe metrics builder wrapper library for the official Prometheus client. |
| <b>[gommit](https://github.com/antham/gommit) | 103 | Analyze git commit messages to ensure they follow defined patterns. |
| <b>[indigo](https://github.com/osamingo/indigo) | 101 | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| <b>[gtree](https://github.com/ddddddO/gtree) | 99 | Provide CLI and Package for tree output and directories creation from Markdown or programmatically. |
| <b>[morse](https://github.com/alwindoss/morse) | 77 | Library to convert to and from morse code. |
| <b>[faker](https://github.com/pioz/faker) | 76 | Random fake data and struct generator for Go. |
| <b>[persian](https://github.com/mavihq/persian) | 72 | Some utilities for Persian language in go. |
| <b>[pdfgen](https://github.com/hyperboloide/pdfgen) | 60 | HTTP service to generate PDF from Json requests. |
| <b>[xkg](https://github.com/go-xkg/xkg) | 55 | X Keyboard Grabber. |
| <b>[datacounter](https://github.com/miolini/datacounter) | 45 | Go counters for readers/writer/http.ResponseWriter. |
| <b>[browscap_go](https://github.com/digitalcrab/browscap_go) | 44 | GoLang Library for [Browser Capabilities Project](https://browscap.org/). |
| <b>[url-shortener](https://github.com/pantrif/url-shortener) | 42 | A modern, powerful, and robust URL shortener microservice with mysql support. |
| <b>[sandid](https://github.com/aofei/sandid) | 40 | Every grain of sand on earth has its own ID. |
| <b>[autoflags](https://github.com/artyom/autoflags) | 38 | Go package to automatically define command line flags from struct fields. |
| <b>[gosh](https://github.com/osamingo/gosh) | 34 | Provide Go Statistics Handler, Struct, Measure Method. |
| <b>[xdg](https://github.com/rkoesters/xdg) | 31 | FreeDesktop.org (xdg) Specs implemented in Go. |
| <b>[metrics](https://github.com/pascaldekloe/metrics) | 25 | Library for metrics instrumentation and Prometheus exposition. |
| <b>[shellwords](https://github.com/Wing924/shellwords) | 19 | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| <b>[numa](https://github.com/lrita/numa) | 16 | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |
| <b>[anagent](https://github.com/mudler/anagent) | 14 | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| <b>[avgRating](https://github.com/kirillDanshin/avgRating) | 14 | Calculate average score and rating based on Wilson Score Equation. |
| <b>[hostutils](https://github.com/Wing924/hostutils) | 12 | A golang library for packing and unpacking FQDNs list. |
| <b>[go-commandbus](https://github.com/lana/go-commandbus) | 10 | A slight and pluggable command-bus for Go. |
| <b>[faker](https://github.com/neotoolkit/faker) | 9 | Fake data generator. |
| <b>[openapi](https://github.com/neotoolkit/openapi) | 9 | OpenAPI 3.x parser. |
| <b>[varint](https://github.com/chmike/varint) | 7 | A faster varying length integer encoder/decoder than the one provided in the standard library. |
| <b>[VarHandler](https://github.com/azr/generators/tree/master/varhandler) | 5 | Generate boilerplate http input and output handling. |
| <b>[basexx](https://github.com/bobg/basexx) | 4 | Convert to, from, and between digit strings in various number bases. |
| <b>[common](https://github.com/kubeservice-stack/common) | 3 | A library for server framework. |
| <b>[sitemap-format](https://github.com/mingard/sitemap-format) | 3 | A simple sitemap generator, with a little syntactic sugar. |
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
| <b>[whatlanggo](https://github.com/abadojack/whatlanggo) | 589 | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| <b>[getlang](https://github.com/rylans/getlang) | 153 | Fast natural language detection package. |
| <b>[guesslanguage](https://github.com/endeveit/guesslanguage) | 58 | Functions to determine the natural language of a unicode text. |
| <b>[detectlanguage](https://github.com/detectlanguage/detectlanguage-go) | 22 | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |


<br>

[👆back to top](#catalogue-list)


<br>

### Morphological Analyzers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[spaGO](https://github.com/nlpodyssey/spago) | 1.5k | Self-contained Machine Learning and Natural Language Processing library in Go. |
| <b>[kagome](https://github.com/ikawaha/kagome) | 727 | JP morphological analyzer written in pure Go. |
| <b>[nlp](https://github.com/james-bowman/nlp) | 408 | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| <b>[nlp](https://github.com/Shixzie/nlp) | 379 | Extract values from strings and fill your structs with nlp. |
| <b>[RAKE.go](https://github.com/afjoseph/RAKE.Go) | 99 | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| <b>[go-stem](https://github.com/agonopol/go-stem) | 75 | Implementation of the porter stemming algorithm. |
| <b>[go2vec](https://github.com/danieldk/go2vec) | 51 | Reader and utility functions for word2vec embeddings. |
| <b>[porter2](https://github.com/zhenjl/porter2) | 46 | Really fast Porter 2 stemmer. |
| <b>[snowball](https://github.com/goodsign/snowball) | 35 | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| <b>[govader](https://github.com/jonreiter/govader) | 34 | Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). |
| <b>[paicehusk](https://github.com/rookii/paicehusk) | 29 | Golang implementation of the Paice/Husk Stemming Algorithm. |
| <b>[golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 20 | Go bindings for the snowball libstemmer library including porter 2. |
| <b>[libtextcat](https://github.com/goodsign/libtextcat) | 12 | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| <b>[porter](https://github.com/a2800276/porter) | 12 | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| <b>[gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) | 10 | Sentiment analyzer using sentiwordnet lexicon in Go. |
| <b>[govader-backend](https://github.com/PIMPfiction/govader_backend) | 5 | Microservice implementation of [GoVader](https://github.com/jonreiter/govader). |
| <b>[spelling-corrector](https://github.com/jorelosorio/spellingcorrector) | 2 | A spelling corrector for the Spanish language or create your own. |


<br>

[👆back to top](#catalogue-list)


<br>

### Slugifiers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[slug](https://github.com/gosimple/slug) | 960 | URL-friendly slugify with multiple languages support. |
| <b>[go-slugify](https://github.com/mozillazg/go-slugify) | 84 | Make pretty slug with multiple languages support. |
| <b>[Slugify](https://github.com/avelino/slugify) | 32 | Go slugify application that handles string. |


<br>

[👆back to top](#catalogue-list)


<br>

### Tokenizers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[prose](https://github.com/jdkato/prose) | 3.0k | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| <b>[gse](https://github.com/go-ego/gse) | 2.2k | Go efficient text segmentation; support english, chinese, japanese and other. |
| <b>[gojieba](https://github.com/yanyiwu/gojieba) | 2.1k | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| <b>[sentences](https://github.com/neurosnap/sentences) | 365 | Sentence tokenizer:  converts text into a list of sentences. |
| <b>[segment](https://github.com/blevesearch/segment) | 77 | Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/) |
| <b>[textcat](https://github.com/pebbe/textcat) | 70 | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| <b>[MMSEGO](https://github.com/awsong/MMSEGO) | 62 | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| <b>[stemmer](https://github.com/dchest/stemmer) | 52 | Stemmer packages for Go programming language. Includes English and German stemmers. |
| <b>[gotokenizer](https://github.com/xujiajun/gotokenizer) | 17 | A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) |
| <b>[shamoji](https://github.com/osamingo/shamoji) | 13 | The shamoji is word filtering package written in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Translation


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-i18n](https://github.com/nicksnyder/go-i18n/) | 2.4k | Package and an accompanying tool to work with localized text. |
| <b>[go-pinyin](https://github.com/mozillazg/go-pinyin) | 1.4k | CN Hanzi to Hanyu Pinyin converter. |
| <b>[gotext](https://github.com/leonelquinteros/gotext) | 382 | GNU gettext utilities for Go. |
| <b>[go-localize](https://github.com/m1/go-localize) | 55 | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| <b>[iuliia-go](https://github.com/mehanizm/iuliia-go) | 38 | Transliterate Cyrillic → Latin in every possible way. |
| <b>[go-mystem](https://github.com/dveselov/mystem) | 30 | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| <b>[icu](https://github.com/goodsign/icu) | 21 | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| <b>[spreak](https://github.com/vorlif/spreak) | 21 | Flexible translation and humanization library for Go, based on the concepts behind gettext. |
| <b>[t](https://github.com/youthlin/t) | 14 | Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template. |


<br>

[👆back to top](#catalogue-list)


<br>

### Transliteration


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-unidecode](https://github.com/mozillazg/go-unidecode) | 108 | ASCII transliterations of Unicode text. |
| <b>[gounidecode](https://github.com/fiam/gounidecode) | 78 | Unicode transliterator (also known as unidecode) for Go. |
| <b>[transliterator](https://github.com/alexsergivan/transliterator) | 35 | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| <b>[enca](https://github.com/endeveit/enca) | 15 | Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Networking

_Libraries for working with various layers of the network._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fasthttp](https://github.com/valyala/fasthttp) | 20.0k | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| <b>[kcptun](https://github.com/xtaci/kcptun) | 13.0k | Extremely simple & fast udp tunnel based on KCP protocol. |
| <b>[webrtc](https://github.com/pions/webrtc) | 11.0k | A pure Go implementation of the WebRTC API. |
| <b>[quic-go](https://github.com/lucas-clemente/quic-go) | 8.3k | An implementation of the QUIC protocol in pure Go. |
| <b>[gnet](https://github.com/panjf2000/gnet) | 7.7k | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| <b>[dns](https://github.com/miekg/dns) | 7.0k | Go library for working with DNS. |
| <b>[gopacket](https://github.com/google/gopacket) | 5.7k | Go library for packet processing with libpcap bindings. |
| <b>[HTTPLab](https://github.com/gchaincl/httplab) | 3.9k | HTTPLabs let you inspect HTTP requests and forge responses. |
| <b>[kcp-go](https://github.com/xtaci/kcp-go) | 3.7k | KCP - Fast and Reliable ARQ Protocol. |
| <b>[netpoll](https://github.com/cloudwego/netpoll) | 3.6k | A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance. |
| <b>[gobgp](https://github.com/osrg/gobgp) | 3.2k | BGP implemented in the Go Programming Language. |
| <b>[ssh](https://github.com/gliderlabs/ssh) | 3.0k | Higher-level API for building SSH servers (wraps crypto/ssh). |
| <b>[fortio](https://github.com/fortio/fortio) | 2.9k | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| <b>[water](https://github.com/songgao/water) | 1.7k | Simple TUN/TAP library. |
| <b>[gev](https://github.com/Allenxuxu/gev) | 1.6k | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| <b>[nbio](https://github.com/lesismal/nbio) | 1.6k | Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. |
| <b>[go-getter](https://github.com/hashicorp/go-getter) | 1.5k | Go library for downloading files or directories from various sources using a URL. |
| <b>[sftp](https://github.com/pkg/sftp) | 1.4k | Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>. |
| <b>[grab](https://github.com/cavaliercoder/grab) | 1.3k | Go package for managing file downloads. |
| <b>[NFF-Go](https://github.com/intel-go/nff-go) | 1.3k | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| <b>[ftp](https://github.com/jlaffaye/ftp) | 1.1k | Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959). |
| <b>[mdns](https://github.com/hashicorp/mdns) | 980 | Simple mDNS (Multicast DNS) client/server library in Golang. |
| <b>[gosnmp](https://github.com/soniah/gosnmp) | 971 | Native Go library for performing SNMP actions. |
| <b>[vssh](https://github.com/yahoo/vssh) | 905 | Go library for building network and server automation over SSH protocol. |
| <b>[gmqtt](https://github.com/DrmagicE/gmqtt) | 873 | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| <b>[cidranger](https://github.com/yl2chen/cidranger) | 834 | Fast IP to CIDR lookup for Go. |
| <b>[lhttp](https://github.com/fanux/lhttp) | 684 | Powerful websocket framework, build your IM server more easily. |
| <b>[easytcp](https://github.com/DarthPestilane/easytcp) | 678 | A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful. |
| <b>[peerdiscovery](https://github.com/schollz/peerdiscovery) | 593 | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| <b>[go-stun](https://github.com/ccding/go-stun) | 580 | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| <b>[gotcp](https://github.com/gansidui/gotcp) | 506 | Go package for quickly writing tcp applications. |
| <b>[gaio](https://github.com/xtaci/gaio) | 497 | High performance async-io networking for Golang in proactor mode. |
| <b>[stun](https://github.com/go-rtc/stun) | 486 | Go implementation of RFC 5389 STUN protocol. |
| <b>[gopcap](https://github.com/akrennmair/gopcap) | 472 | Go wrapper for libpcap. |
| <b>[raw](https://github.com/mdlayher/raw) | 422 | Package raw enables reading and writing data at the device driver level for a network interface. |
| <b>[tcp_server](https://github.com/firstrow/tcp_server) | 422 | Go library for building tcp servers faster. |
| <b>[winrm](https://github.com/masterzen/winrm) | 405 | Go WinRM client to remotely execute commands on Windows machines. |
| <b>[ftpserverlib](https://github.com/fclairamb/ftpserverlib) | 363 | Fully featured FTP server library. |
| <b>[gws](https://github.com/lxzan/gws) | 331 | High-Performance WebSocket Server & Client With AsyncIO Supporting . |
| <b>[arp](https://github.com/mdlayher/arp) | 324 | Package arp implements the ARP protocol, as described in RFC 826. |
| <b>[ethernet](https://github.com/mdlayher/ethernet) | 264 | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| <b>[dnsmonster](https://github.com/mosajjal/dnsmonster) | 262 | Passive DNS Capture/Monitoring Framework. |
| <b>[buffstreams](https://github.com/stabbycutyou/buffstreams) | 253 | Streaming protocolbuffer data over TCP made easy. |
| <b>[gNxI](https://github.com/google/gnxi) | 238 | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| <b>[jazigo](https://github.com/udhos/jazigo) | 191 | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| <b>[utp](https://github.com/anacrolix/utp) | 168 | Go uTP micro transport protocol implementation. |
| <b>[canopus](https://github.com/zubairhamed/canopus) | 152 | CoAP Client/Server implementation (RFC 7252). |
| <b>[sslb](https://github.com/eduardonunesp/sslb) | 143 | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| <b>[xtcp](https://github.com/xfxdev/xtcp) | 143 | TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. |
| <b>[iplib](https://github.com/c-robinson/iplib) | 113 | Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html) |
| <b>[gldap](https://github.com/jimlambrt/gldap) | 87 | gldap provides an ldap server implementation and you provide handlers for its ldap operations. |
| <b>[ether](https://github.com/songgao/ether) | 79 | Cross-platform Go package for sending and receiving ethernet frames. |
| <b>[dhcp6](https://github.com/mdlayher/dhcp6) | 76 | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| <b>[packet](https://github.com/aerogo/packet) | 72 | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| <b>[go-powerdns](https://github.com/joeig/go-powerdns) | 70 | PowerDNS API bindings for Golang. |
| <b>[fullproxy](https://github.com/shoriwe/fullproxy) | 54 | A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols. |
| <b>[portproxy](https://github.com/aybabtme/portproxy) | 53 | Simple TCP proxy which adds CORS support to API's which don't support it. |
| <b>[linkio](https://github.com/ian-kent/linkio) | 52 | Network link speed simulation for Reader/Writer interfaces. |
| <b>[panoptes-stream](https://github.com/yahoo/panoptes-stream) | 39 | A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT). |
| <b>[golibwireshark](https://github.com/sunwxg/golibwireshark) | 29 | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| <b>[graval](https://github.com/koofr/graval) | 28 | Experimental FTP server framework. |
| <b>[publicip](https://github.com/polera/publicip) | 26 | Package publicip returns your public facing IPv4 address (internet egress). |
| <b>[gohooks](https://github.com/averageflow/gohooks) | 23 | GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server. |
| <b>[httpproxy](https://github.com/wzshiming/httpproxy) | 20 | HTTP proxy handler and dialer. |
| <b>[goshark](https://github.com/sunwxg/goshark) | 16 | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| <b>[llb](https://github.com/kirillDanshin/llb) | 14 | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| <b>[tspool](https://github.com/two/tspool) | 14 | A TCP Library use worker pool to improve performance and protect your server. |
| <b>[go-sse](https://github.com/lampctl/go-sse) | 1 | Go client and server implementation of HTML server-sent events. |
| <b>[mqttPaho](https://eclipse.org/paho/clients/golang/) | - | The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets. |


<br>

[👆back to top](#catalogue-list)


<br>

### HTTP Clients

_Libraries for making HTTP requests._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[resty](https://github.com/go-resty/resty) | 7.9k | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| <b>[req](https://github.com/imroc/req) | 3.4k | Simple Go HTTP client with Black Magic (Less code and More efficiency). |
| <b>[heimdall](https://github.com/gojektech/heimdall) | 2.4k | An enhanced http client with retry and hystrix capabilities. |
| <b>[grequests](https://github.com/levigross/grequests) | 2.0k | A Go "clone" of the great and famous Requests library. |
| <b>[go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) | 1.6k | Retryable HTTP client in Go. |
| <b>[sling](https://github.com/dghubble/sling) | 1.6k | Sling is a Go HTTP client library for creating and sending API requests. |
| <b>[gentleman](https://github.com/h2non/gentleman) | 1000 | Full-featured plugin-driven HTTP client library. |
| <b>[requests](https://github.com/carlmjohnson/requests) | 980 | HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools. |
| <b>[pester](https://github.com/sethgrid/pester) | 616 | Go HTTP client calls with retries, backoff, and concurrency. |
| <b>[go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) | 298 | Get easily stdlib HTTP client, which does not share any state with other clients. |
| <b>[request](https://github.com/monaco-io/request) | 241 | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| <b>[go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) | 72 | Go http.RoundTripper that emits open telemetry metrics for HTTP requests. |
| <b>[go-http-client](https://github.com/bozd4g/go-http-client) | 55 | Make http calls simply and easily. |
| <b>[rq](https://github.com/ddo/rq) | 48 | A nicer interface for golang stdlib HTTP client. |
| <b>[go-zoox/fetch](https://github.com/go-zoox/fetch) | 42 | A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API. |
| <b>[httpretry](https://github.com/ybbus/httpretry) | 35 | Enriches the default go HTTP client with retry functionality. |
| <b>[go-req](https://github.com/wenerme/go-req) | 20 | Declarative golang HTTP client. |
| <b>[httpc](https://github.com/valord577/httpc) | 5 | A customizable and simple HTTP client library. Only depend on the stdlib HTTP client. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## OpenGL

_Libraries for using OpenGL in Go._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[glfw](https://github.com/go-gl/glfw) | 1.4k | Go bindings for GLFW 3. |
| <b>[gl](https://github.com/go-gl/gl) | 975 | Go bindings for OpenGL (generated via glow). |
| <b>[mathgl](https://github.com/go-gl/mathgl) | 497 | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| <b>[goxjs/gl](https://github.com/goxjs/gl) | 164 | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| <b>[goxjs/glfw](https://github.com/goxjs/glfw) | 76 | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| <b>[go-glmatrix](https://github.com/technohippy/go-glmatrix) | 7 | Go port of [glMatrix](https://glmatrix.net/) library. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## ORM

_Libraries that implement Object-Relational Mapping or datamapping techniques._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GORM](https://github.com/go-gorm/gorm) | 33.0k | The fantastic ORM library for Golang, aims to be developer friendly. |
| <b>[ent](https://github.com/facebook/ent) | 14.0k | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| <b>[SQLBoiler](https://github.com/volatiletech/sqlboiler) | 5.8k | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| <b>[go-pg](https://github.com/go-pg/pg) | 5.4k | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| <b>[gorp](https://github.com/go-gorp/gorp) | 3.7k | Go Relational Persistence, ORM-ish library for Go. |
| <b>[upper.io/db](https://github.com/upper/db) | 3.3k | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| <b>[gormt](https://github.com/xxjwxc/gormt) | 2.2k | Mysql database to golang gorm struct. |
| <b>[bun](https://github.com/uptrace/bun) | 2.1k | SQL-first Golang ORM. Successor of go-pg. |
| <b>[Prisma](https://github.com/prisma/prisma-client-go) | 1.5k | Prisma Client Go, Typesafe database access for Go. |
| <b>[reform](https://github.com/go-reform/reform) | 1.4k | Better ORM for Go, based on non-empty interfaces and code generation. |
| <b>[pop/soda](https://github.com/gobuffalo/pop) | 1.3k | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| <b>[go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 1000 | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| <b>[go-queryset](https://github.com/jirfag/go-queryset) | 696 | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| <b>[rel](https://github.com/go-rel/rel) | 643 | Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. |
| <b>[Zoom](https://github.com/albrow/zoom) | 300 | Blazing-fast datastore and querying engine built on Redis. |
| <b>[go-sql](https://github.com/rushteam/gosql) | 172 | A easy ORM for mysql. |
| <b>[grimoire](https://github.com/Fs02/grimoire) | 159 | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| <b>[golobby/orm](https://github.com/golobby/orm) | 131 | Simple, fast, type-safe, generic orm for developer happiness. |
| <b>[go-store](https://github.com/gosuri/go-store) | 110 | Simple and fast Redis backed key-value store library for Go. |
| <b>[go-firestorm](https://github.com/jschoedt/go-firestorm) | 43 | A simple ORM for Google/Firebase Cloud Firestore. |
| <b>[cacheme](https://github.com/Yiling-J/cacheme-go) | 22 | Schema based, typed Redis caching/memoize framework for Go. |
| <b>[marlow](https://github.com/marlow/marlow) | 13 | Generated ORM from project structs for compile time safety assurances. |
| <b>[lore](https://github.com/abrahambotros/lore) | 12 | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
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
| <b>[govendor](https://github.com/kardianos/govendor) | 5.0k | Go Package Manager. Go vendor tool that works with the standard vendor file. |
| <b>[gopm](https://github.com/gpmgo/gopm) | 2.5k | Go Package Manager. |
| <b>[gom](https://github.com/mattn/gom) | 1.4k | Go Manager - bundle for go. |
| <b>[gpm](https://github.com/pote/gpm) | 1.2k | Barebones dependency manager for Go. |
| <b>[goop](https://github.com/nitrous-io/goop) | 779 | Simple dependency manager for Go (golang), inspired by Bundler. |
| <b>[modgv](https://github.com/lucasepe/modgv) | 463 | Converts 'go mod graph' output into Graphviz's DOT language. |
| <b>[nut](https://github.com/jingweno/nut) | 237 | Vendor Go dependencies. |
| <b>[johnny-deps](https://github.com/VividCortex/johnny-deps) | 214 | Minimal dependency version using Git. |
| <b>[gup](https://github.com/nao1215/gup) | 186 | Update binaries installed by "go install". |
| <b>[mvn-golang](https://github.com/raydac/mvn-golang) | 155 | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| <b>[VenGO](https://github.com/DamnWidget/VenGO) | 123 | create and manage exportable isolated go virtual environments. |
| <b>[gop](https://github.com/lunny/gop) | 50 | Build and manage your Go applications out of GOPATH. |
| <b>[go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) | - | Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules. |
| <b>[vgo](https://go.googlesource.com/vgo/) | - | Versioned Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Performance


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[jaeger](https://github.com/jaegertracing/jaeger) | 18.0k | A distributed tracing system. |
| <b>[pixie](https://github.com/pixie-labs/pixie) | 4.6k | No instrumentation tracing for Golang applications via eBPF. |
| <b>[statsviz](https://github.com/arl/statsviz) | 2.9k | Live visualization of your Go application runtime statistics. |
| <b>[profile](https://github.com/pkg/profile) | 1.9k | Simple profiling support package for Go. |
| <b>[go-instrument](https://github.com/nikolaydubina/go-instrument) | 85 | Automatically add spans to all methods and functions. |
| <b>[tracer](https://github.com/kamilsk/tracer) | 77 | Simple, lightweight tracing. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Query Language


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[graphql-go](https://github.com/graphql-go/graphql) | 9.3k | Implementation of GraphQL for Go. |
| <b>[gqlgen](https://github.com/99designs/gqlgen) | 8.9k | go generate based graphql server library. |
| <b>[graphql](https://github.com/neelance/graphql-go) | 4.5k | GraphQL server with a focus on ease of use. |
| <b>[dasel](https://github.com/tomwright/dasel) | 4.3k | Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. |
| <b>[gojsonq](https://github.com/thedevsaddam/gojsonq) | 2.1k | A simple Go package to Query over JSON Data. |
| <b>[rql](https://github.com/a8m/rql) | 289 | Resource Query Language for REST API. |
| <b>[jsonql](https://github.com/elgs/jsonql) | 266 | JSON query expression library in Golang. |
| <b>[jsonslice](https://github.com/bhmj/jsonslice) | 78 | Jsonpath queries with advanced filters. |
| <b>[graphql](https://github.com/tmc/graphql) | 58 | graphql parser + utilities. |
| <b>[rqp](https://github.com/timsolov/rest-query-parser) | 53 | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| <b>[goven](https://github.com/SeldonIO/goven) | 51 | A drop-in query language for any database schema. |
| <b>[api-fu](https://github.com/ccbrown/api-fu) | 49 | Comprehensive GraphQL implementation. |
| <b>[straf](https://github.com/SonicRoshan/straf) | 34 | Easily Convert Golang structs to GraphQL objects. |
| <b>[jsonpath](https://github.com/AsaiYusuke/jsonpath) | 18 | A query library for retrieving part of JSON based on JSONPath syntax. |
| <b>[gws](https://github.com/Zaba505/gws) | 7 | Apollos' "GraphQL over Websocket" client and server implementation. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Resource Embedding


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[statik](https://github.com/rakyll/statik) | 3.6k | Embeds static files into a Go executable. |
| <b>[packr](https://github.com/gobuffalo/packr) | 3.4k | The simple and easy way to embed static files into Go binaries. |
| <b>[go.rice](https://github.com/GeertJohan/go.rice) | 2.4k | go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. |
| <b>[vfsgen](https://github.com/shurcooL/vfsgen) | 972 | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| <b>[esc](https://github.com/mjibson/esc) | 632 | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| <b>[fileb0x](https://github.com/UnnoTed/fileb0x) | 628 | Simple tool to embed files in go with focus on "customization" and ease to use. |
| <b>[go-resources](https://github.com/omeid/go-resources) | 176 | Unfancy resources embedding with Go. |
| <b>[statics](https://github.com/go-playground/statics) | 66 | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| <b>[templify](https://github.com/wlbr/templify) | 29 | Embed external template files into Go code to create single file binaries. |
| <b>[rebed](https://github.com/soypat/rebed) | 26 | Recreate folder structures and files from Go 1.16's `embed.FS` type |
| <b>[debme](https://github.com/leaanthony/debme) | 23 | Create an `embed.FS` from an existing `embed.FS` subdirectory. |
| <b>[mule](https://github.com/wlbr/mule) | 12 | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Science and Data Analysis

_Libraries for scientific computing and data analyzing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gonum](https://github.com/gonum/gonum) | 6.6k | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| <b>[stats](https://github.com/montanaflynn/stats) | 2.8k | Statistics package with common functions missing from the Golang standard library. |
| <b>[gonum/plot](https://github.com/gonum/plot) | 2.5k | gonum/plot provides an API for building and drawing plots in Go. |
| <b>[gosl](https://github.com/cpmech/gosl) | 1.8k | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| <b>[streamtools](https://github.com/nytlabs/streamtools) | 1.3k | general purpose, graphical tool for dealing with streams of data. |
| <b>[dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 1000 | Dataframes for machine-learning and statistics (similar to pandas). |
| <b>[go-dsp](https://github.com/mjibson/go-dsp) | 817 | Digital Signal Processing for Go. |
| <b>[chart](https://github.com/vdobler/chart) | 754 | Simple Chart Plotting library for Go. Supports many graphs types. |
| <b>[goraph](https://github.com/gyuho/goraph) | 718 | Pure Go graph theory library(data structure, algorithm visualization). |
| <b>[orb](https://github.com/paulmach/orb) | 670 | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| <b>[graph](https://github.com/yourbasic/graph) | 644 | Library of basic graph algorithms. |
| <b>[ewma](https://github.com/VividCortex/ewma) | 408 | Exponentially-weighted moving averages. |
| <b>[calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 375 | Calendar heatmap in plain Go inspired by Github contribution activity. |
| <b>[TextRank](https://github.com/DavidBelicza/TextRank) | 182 | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| <b>[gohistogram](https://github.com/VividCortex/gohistogram) | 171 | Approximate histograms for data streams. |
| <b>[sparse](https://github.com/james-bowman/sparse) | 140 | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| <b>[go-estimate](https://github.com/milosgajdos/go-estimate) | 104 | State estimation and filtering algorithms in Go. |
| <b>[pagerank](https://github.com/alixaxel/pagerank) | 77 | Weighted PageRank algorithm implemented in Go. |
| <b>[jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) | 65 | Tool to manipulate JSONL graphs with graphviz support. |
| <b>[geom](https://github.com/skelterjohn/geom) | 55 | 2D geometry for golang. |
| <b>[evaler](https://github.com/soniah/evaler) | 52 | Simple floating point arithmetic expression evaluator. |
| <b>[decimal](https://github.com/db47h/decimal) | 35 | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| <b>[triangolatte](https://github.com/tchayen/triangolatte) | 35 | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| <b>[goent](https://github.com/kzahedi/goent) | 33 | GO Implementation of Entropy Measures. |
| <b>[piecewiselinear](https://github.com/sgreben/piecewiselinear) | 26 | Tiny linear interpolation library. |
| <b>[gograph](https://github.com/hmdsefi/gograph) | 25 | A golang generic graph library that provides mathematical graph-theory and algorithms. |
| <b>[godesim](https://github.com/soypat/godesim) | 21 | Extended/multivariable ODE solver framework for event-based simulations with simple API. |
| <b>[ode](https://github.com/ChristopherRabotin/ode) | 21 | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| <b>[PiHex](https://github.com/claygod/PiHex) | 20 | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| <b>[GoStats](https://github.com/OGFris/GoStats) | 19 | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| <b>[assocentity](https://github.com/ndabAP/assocentity) | 11 | Package assocentity returns the average distance from words to a given entity. |
| <b>[go-gt](https://github.com/ThePaw/go-gt) | 10 | Graph theory algorithms written in "Go" language. |
| <b>[rootfinding](https://github.com/khezen/rootfinding) | 10 | root-finding algorithms library for finding roots of quadratic functions. |
| <b>[bradleyterry](https://github.com/seanhagen/bradleyterry) | 8 | Provides a Bradley-Terry Model for pairwise comparisons. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Security

_Libraries that are used to help make your application more secure._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[age](https://github.com/FiloSottile/age) | 14.0k | A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. |
| <b>[lego](https://github.com/go-acme/lego) | 6.2k | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| <b>[CertMagic](https://github.com/caddyserver/certmagic) | 4.5k | Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal. |
| <b>[Cameradar](https://github.com/Ullaakut/cameradar) | 3.4k | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| <b>[memguard](https://github.com/awnumar/memguard) | 2.3k | A pure Go library for handling sensitive values in memory. |
| <b>[secure](https://github.com/unrolled/secure) | 2.1k | HTTP middleware for Go that facilitates some quick security wins. |
| <b>[acmetool](https://github.com/hlandau/acme) | 2.0k | ACME (Let's Encrypt) client tool with automatic renewal. |
| <b>[themis](https://github.com/cossacklabs/themis) | 1.7k | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| <b>[acra](https://github.com/cossacklabs/acra) | 1.2k | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| <b>[Coraza](https://github.com/corazawaf/coraza) | 1.1k | Enterprise-ready, modsecurity and OWASP CRS compatible WAF library. |
| <b>[dongle](https://github.com/golang-module/dongle) | 716 | A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption. |
| <b>[nacl](https://github.com/kevinburke/nacl) | 535 | Go implementation of the NaCL set of API's. |
| <b>[go-password-validator](https://github.com/lane-c-wagner/go-password-validator) | 404 | Password validator based on raw cryptographic entropy values. |
| <b>[ssh-vault](https://github.com/ssh-vault/ssh-vault) | 384 | encrypt/decrypt using ssh keys. |
| <b>[booster](https://github.com/anatol/booster) | 357 | Fast initramfs generator with full-disk encryption support. |
| <b>[optimus-go](https://github.com/pjebs/optimus-go) | 346 | ID hashing and Obfuscation using Knuth's Algorithm. |
| <b>[firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 329 | A rest application to dynamically update firewalld rules on a linux server. |
| <b>[BadActor](https://github.com/jaredfolkins/badactor) | 314 | In-memory, application-driven jailer built in the spirit of fail2ban. |
| <b>[go-yara](https://github.com/hillu/go-yara) | 307 | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| <b>[passlib](https://github.com/hlandau/passlib) | 283 | Futureproof password hashing library. |
| <b>[simple-scrypt](https://github.com/elithrar/simple-scrypt) | 185 | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| <b>[teler-waf](https://github.com/kitabisa/teler-waf) | 164 | teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications. |
| <b>[argon2pw](https://github.com/raja/argon2pw) | 89 | Argon2 password hash generation with constant-time password comparison. |
| <b>[goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 55 | A probably paranoid package for securely hashing and encrypting passwords. |
| <b>[go-generate-password](https://github.com/m1/go-generate-password) | 48 | Password generator that can be used on the cli or as a library. |
| <b>[certificates](https://github.com/mvmaasakkers/certificates) | 37 | An opinionated tool for generating tls certificates. |
| <b>[go-htpasswd](https://github.com/tg123/go-htpasswd) | 32 | Apache htpasswd Parser for Go. |
| <b>[secureio](https://github.com/xaionaro-go/secureio) | 30 | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| <b>[secret](https://github.com/rsjethani/secret) | 22 | Prevent your secrets from leaking into logs, std* etc. |
| <b>[argon2-hashing](https://github.com/andskur/argon2-hashing) | 19 | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| <b>[sslmgr](https://github.com/adrianosela/sslmgr) | 18 | SSL certificates made easy with a high level wrapper around acme/autocert. |
| <b>[goArgonPass](https://github.com/dwin/goArgonPass) | 16 | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
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
| <b>[jsoniter](https://github.com/json-iterator/go) | 12.0k | High-performance 100% compatible drop-in replacement of "encoding/json". |
| <b>[goprotobuf](https://github.com/golang/protobuf) | 9.1k | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| <b>[mapstructure](https://github.com/mitchellh/mapstructure) | 6.9k | Go library for decoding generic map values into native Go structures. |
| <b>[gogoprotobuf](https://github.com/gogo/protobuf) | 5.6k | Protocol Buffers for Go with Gadgets. |
| <b>[go-codec](https://github.com/ugorji/go) | 1.7k | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| <b>[csvutil](https://github.com/jszwec/csvutil) | 804 | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| <b>[colfer](https://github.com/pascaldekloe/colfer) | 708 | Code generation for the Colfer binary format. |
| <b>[cbor](https://github.com/fxamacker/cbor) | 570 | Small, safe, and easy CBOR encoding and decoding library. |
| <b>[go-capnproto](https://github.com/glycerine/go-capnproto) | 287 | Cap'n Proto library and parser for go. |
| <b>[php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 158 | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| <b>[structomap](https://github.com/tuvistavie/structomap) | 139 | Library to easily and dynamically generate maps from static structures. |
| <b>[binstruct](https://github.com/ghostiam/binstruct) | 73 | Golang binary decoder for mapping data into the structure. |
| <b>[bambam](https://github.com/glycerine/bambam) | 66 | generator for Cap'n Proto schemas from go. |
| <b>[asn1](https://github.com/PromonLogicalis/asn1) | 53 | Asn.1 BER and DER encoding library for golang. |
| <b>[bel](https://github.com/32leaves/bel) | 35 | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| <b>[elastic](https://github.com/epiclabs-io/elastic) | 24 | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| <b>[fwencoder](https://github.com/o1egl/fwencoder) | 24 | Fixed width file parser (encoding and decoding library) for Go. |
| <b>[pletter](https://github.com/vimeda/pletter) | 20 | A standard way to wrap a proto message for message brokers. |
| <b>[fixedwidth](https://github.com/huydang284/fixedwidth) | 8 | Fixed-width text formatting (UTF-8 supported). |
| <b>[unitpacking](https://github.com/recolude/unitpacking) | 6 | Library to pack unit vectors into as fewest bytes as possible. |
| <b>[go-lctree](https://github.com/sbourlon/go-lctree) | 4 | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Server Applications


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Caddy](https://github.com/caddyserver/caddy) | 48.0k | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| <b>[etcd](https://github.com/coreos/etcd) | 44.0k | Highly-available key value store for shared configuration and service discovery. |
| <b>[minio](https://github.com/minio/minio) | 39.0k | Minio is a distributed object storage server. |
| <b>[RoadRunner](https://github.com/spiral/roadrunner) | 7.2k | High-performance PHP application server, load-balancer and process manager. |
| <b>[SFTPGo](https://github.com/drakkan/sftpgo) | 6.3k | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| <b>[Easegress](https://github.com/megaease/easegress) | 5.4k | A cloud native high availability/performance traffic orchestration system with observability and extensibility. |
| <b>[devd](https://github.com/cortesi/devd) | 3.3k | Local webserver for developers. |
| <b>[flipt](https://github.com/markphelps/flipt) | 2.4k | A self contained feature flag solution written in Go and Vue.js |
| <b>[Fider](https://github.com/getfider/fider) | 2.3k | Fider is an open platform to collect and organize customer feedback. |
| <b>[algernon](https://github.com/xyproto/algernon) | 2.2k | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| <b>[Flagr](https://github.com/checkr/flagr) | 2.2k | Flagr is an open-source feature flagging and A/B testing service. |
| <b>[Wish](https://github.com/charmbracelet/wish) | 2.1k | Make SSH apps, just like that! |
| <b>[Trickster](https://github.com/tricksterproxy/trickster) | 1.9k | HTTP reverse proxy cache and time series accelerator. |
| <b>[discovery](https://github.com/Bilibili/discovery) | 1.7k | A registry for resilient mid-tier load balancing and failover. |
| <b>[jackal](https://github.com/ortuman/jackal) | 1.4k | An XMPP server written in Go. |
| <b>[go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) | 722 | A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it. |
| <b>[Euterpe](https://github.com/ironsmile/euterpe) | 483 | Self-hosted music streaming server with built-in web UI and REST API. |
| <b>[dummy](https://github.com/neotoolkit/dummy) | 173 | Run mock server based off an API contract with one command. |
| <b>[dudeldu](https://github.com/krotik/dudeldu) | 141 | A simple SHOUTcast server. |
| <b>[go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) | 93 | Simple Reverse Proxy with Caching, written in Go, using Redis. |
| <b>[lets-proxy2](https://github.com/rekby/lets-proxy2) | 76 | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| <b>[cortex-tenant](https://github.com/blind-oracle/cortex-tenant) | 70 | Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels. |
| <b>[psql-streamer](https://github.com/blind-oracle/psql-streamer) | 51 | Stream database events from PostgreSQL to Kafka. |
| <b>[nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 37 | Nginx log parser and exporter to Prometheus. |
| <b>[simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) | 33 | Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management. |
| <b>[protoxy](https://github.com/camgraff/protoxy) | 30 | A proxy server that converts JSON request bodies to Protocol Buffers. |
| <b>[Moxy](https://github.com/sinhashubham95/moxy) | 9 | Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint. |
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
| <b>[go-streams](https://github.com/reugn/go-streams) | 1.5k | Go stream processing library. |
| <b>[machine](https://github.com/whitaker-io/machine) | 129 | Go library for writing and generating stream workers with built in metrics and traceability. |
| <b>[stream](https://github.com/youthlin/stream) | 79 | Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... |
| <b>[goio](https://github.com/primetalk/goio) | 68 | An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Template Engines

_Libraries and tools for templating and lexing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sprig](https://github.com/Masterminds/sprig) | 3.6k | Useful template functions for Go templates. |
| <b>[quicktemplate](https://github.com/valyala/quicktemplate) | 2.8k | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| <b>[pongo2](https://github.com/flosch/pongo2) | 2.5k | Django-like template-engine for Go. |
| <b>[jet](https://github.com/CloudyKit/jet) | 1.1k | Jet template engine. |
| <b>[maroto](https://github.com/johnfercher/maroto) | 1000 | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| <b>[Razor](https://github.com/sipin/gorazor) | 816 | Razor view engine for Golang. |
| <b>[fasttemplate](https://github.com/valyala/fasttemplate) | 715 | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/). |
| <b>[ego](https://github.com/benbjohnson/ego) | 556 | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| <b>[raymond](https://github.com/aymerick/raymond) | 534 | Complete handlebars implementation in Go. |
| <b>[goview](https://github.com/foolin/goview) | 344 | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| <b>[liquid](https://github.com/osteele/liquid) | 210 | Go implementation of Shopify Liquid templates. |
| <b>[Soy](https://github.com/robfig/soy) | 168 | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| <b>[extemplate](https://github.com/dannyvankooten/extemplate) | 54 | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| <b>[gospin](https://github.com/m1/gospin) | 45 | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |
| <b>[tbd](https://github.com/lucasepe/tbd) | 23 | A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata. |
| <b>[got](https://github.com/goradd/got) | 12 | A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Testing

_Libraries for testing codebases and generating test data._


<br>

### Testing Frameworks


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Testify](https://github.com/stretchr/testify) | 20.0k | Sacred extension to the standard go testing package. |
| <b>[GoConvey](https://github.com/smartystreets/goconvey/) | 7.8k | BDD-style framework with web UI and live reload. |
| <b>[go-cmp](https://github.com/google/go-cmp) | 3.6k | Package for comparing Go values in tests. |
| <b>[httpexpect](https://github.com/gavv/httpexpect) | 2.2k | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| <b>[godog](https://github.com/DATA-DOG/godog) | 2.0k | Cucumber or Behat like BDD framework for Go. |
| <b>[is](https://github.com/matryer/is) | 1.6k | Professional lightweight testing mini-framework for Go. |
| <b>[gnomock](https://github.com/orlangure/gnomock) | 1.2k | integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. |
| <b>[go-vcr](https://github.com/dnaeon/go-vcr) | 1000 | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| <b>[testfixtures](https://github.com/go-testfixtures/testfixtures) | 947 | A helper for Rails' like test fixtures to test database applications. |
| <b>[goblin](https://github.com/franela/goblin) | 890 | Mocha like testing framework fo Go. |
| <b>[baloo](https://github.com/h2non/baloo) | 758 | Expressive and versatile end-to-end HTTP API testing made easy. |
| <b>[goc](https://github.com/qiniu/goc) | 679 | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| <b>[embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 606 | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| <b>[go-mutesting](https://github.com/zimmski/go-mutesting) | 587 | Mutation testing for Go source code. |
| <b>[gofight](https://github.com/appleboy/gofight) | 436 | API Handler Testing for Golang Router framework. |
| <b>[gotest.tools](https://github.com/gotestyourself/gotest.tools) | 431 | A collection of packages to augment the go testing package and support common patterns. |
| <b>[testza](https://github.com/MarvinJWendt/testza) | 409 | Full-featured test framework with nice colorized output. |
| <b>[go-testdeep](https://github.com/maxatome/go-testdeep) | 386 | Extremely flexible golang deep comparison, extends the go testing package. |
| <b>[frisby](https://github.com/verdverm/frisby) | 274 | REST API testing framework. |
| <b>[cupaloy](https://github.com/bradleyjkemp/cupaloy) | 264 | Simple snapshot testing addon for your test framework. |
| <b>[got](https://github.com/ysmood/got) | 263 | An enjoyable golang test framework. |
| <b>[endly](https://github.com/viant/endly) | 241 | Declarative end to end functional testing. |
| <b>[go-carpet](https://github.com/msoap/go-carpet) | 239 | Tool for viewing test coverage in terminal. |
| <b>[go-hit](https://github.com/Eun/go-hit) | 224 | Hit is an http integration test framework written in golang. |
| <b>[commander](https://github.com/SimonBaeumer/commander) | 214 | Tool for testing cli applications on windows, linux and osx. |
| <b>[charlatan](https://github.com/percolate/charlatan) | 199 | Tool to generate fake interface implementations for tests. |
| <b>[dbcleaner](https://github.com/khaiql/dbcleaner) | 155 | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| <b>[GoSpec](https://github.com/orfjackal/gospec) | 113 | BDD-style testing framework for the Go programming language. |
| <b>[jsonassert](https://github.com/kinbiko/jsonassert) | 110 | Package for verifying that your JSON payloads are serialized correctly. |
| <b>[testcase](https://github.com/adamluzsi/testcase) | 108 | Idiomatic testing framework for Behavior Driven Development. |
| <b>[wstest](https://github.com/posener/wstest) | 99 | Websocket client for unit-testing a websocket http.Handler. |
| <b>[gocrest](https://github.com/corbym/gocrest) | 94 | Composable hamcrest-like matchers for Go assertions. |
| <b>[be](https://github.com/carlmjohnson/be) | 69 | The minimalist generic test assertion library. |
| <b>[gherkingen](https://github.com/hedhyw/gherkingen) | 58 | BDD boilerplate generator and framework. |
| <b>[covergates](https://github.com/covergates/covergates) | 57 | Self-hosted code coverage report review and management service. |
| <b>[restit](https://github.com/yookoala/restit) | 56 | Go micro framework to help writing RESTful API integration test. |
| <b>[assert](https://github.com/go-playground/assert) | 56 | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| <b>[gospecify](https://github.com/stesla/gospecify) | 53 | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| <b>[gomatch](https://github.com/jfilipczyk/gomatch) | 45 | library created for testing JSON against patterns. |
| <b>[dsunit](https://github.com/viant/dsunit) | 42 | Datastore testing for SQL, NoSQL, structured files. |
| <b>[Hamcrest](https://github.com/rdrdr/hamcrest) | 28 | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| <b>[schema](https://github.com/jgroeneveld/schema) | 20 | Quick and easy expression matching for JSON schemas used in requests and responses. |
| <b>[flute](https://github.com/suzuki-shunsuke/flute) | 17 | HTTP client testing framework. |
| <b>[gogiven](https://github.com/corbym/gogiven) | 16 | YATSPEC-like BDD testing framework for Go. |
| <b>[testsql](https://github.com/zhulongcheng/testsql) | 16 | Generate test data from SQL files before testing and clear it after finished. |
| <b>[gosuite](https://github.com/pavlo/gosuite) | 12 | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| <b>[biff](https://github.com/fulldump/biff) | 12 | Bifurcation testing framework, BDD compatible. |
| <b>[badio](https://github.com/cavaliercoder/badio) | 10 | Extensions to Go's `testing/iotest` package. |
| <b>[fixenv](https://github.com/rekby/fixenv) | 10 | Fixture manage engine, inspired by pytest fixtures. |
| <b>[stop-and-go](https://github.com/elgohr/stop-and-go) | 9 | Testing helper for concurrency. |
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
| <b>[gomock](https://github.com/golang/mock) | 8.9k | Mocking framework for the Go programming language. |
| <b>[go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 5.3k | Mock SQL driver for testing database interactions. |
| <b>[mockery](https://github.com/vektra/mockery) | 4.7k | Tool to generate Go interfaces. |
| <b>[hoverfly](https://github.com/SpectoLabs/hoverfly) | 2.2k | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| <b>[gock](https://github.com/h2non/gock) | 1.9k | Versatile HTTP mocking made easy. |
| <b>[httpmock](https://github.com/jarcoal/httpmock) | 1.7k | Easy mocking of HTTP responses from external resources. |
| <b>[counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 836 | Tool for generating self-contained mock objects. |
| <b>[go-txdb](https://github.com/DATA-DOG/go-txdb) | 543 | Single transaction based database driver mainly for testing purposes. |
| <b>[minimock](https://github.com/gojuno/minimock) | 503 | Mock generator for Go interfaces. |
| <b>[govcr](https://github.com/seborama/govcr) | 149 | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| <b>[go-localstack](https://github.com/elgohr/go-localstack) | 70 | Tool for using localstack in AWS testing. |
| <b>[timex](https://github.com/cabify/timex) | 69 | A test-friendly replacement for the native `time` package. |
| <b>[mockhttp](https://github.com/tv42/mockhttp) | 22 | Mock object for Go http.ResponseWriter. |
| <b>[mockit](https://github.com/pasdam/mockit) | 16 | Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java. |
| <b>[genmock](https://gitlab.com/so_literate/genmock) | - | Go mocking system with code generator for building calls of the interface methods. |


<br>

[👆back to top](#catalogue-list)


<br>

### Fuzzing and delta-debugging/reducing/shrinking.


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-fuzz](https://github.com/dvyukov/go-fuzz) | 4.6k | Randomized testing system. |
| <b>[gofuzz](https://github.com/google/gofuzz) | 1.4k | Library for populating go objects with random values. |
| <b>[Tavor](https://github.com/zimmski/tavor) | 242 | Generic fuzzing and delta-debugging framework. |


<br>

[👆back to top](#catalogue-list)


<br>

### Selenium and browser control tools.


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[chromedp](https://github.com/knq/chromedp) | 9.1k | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| <b>[rod](https://github.com/go-rod/rod) | 3.9k | A Devtools driver to make web automation and scraping easy. |
| <b>[selenoid](https://github.com/aerokube/selenoid) | 2.4k | alternative Selenium hub server that launches browsers within containers. |
| <b>[playwright-go](https://github.com/mxschmitt/playwright-go) | 1.3k | browser automation library to control Chromium, Firefox and WebKit with a single API. |
| <b>[cdp](https://github.com/mafredri/cdp) | 675 | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| <b>[ggr](https://github.com/aerokube/ggr) | 301 | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |


<br>

[👆back to top](#catalogue-list)


<br>

### Fail injection


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[failpoint](https://github.com/pingcap/failpoint) | 773 | An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Text Processing

_Libraries for parsing and manipulating texts._


<br>

### Formatters


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-humanize](https://github.com/dustin/go-humanize) | 3.6k | Formatters for time, numbers, and memory size to human readable format. |
| <b>[bytes](https://github.com/labstack/gommon/tree/master/bytes) | 489 | Formats and parses numeric byte values (10K, 2M, 3G, etc.). |
| <b>[gotabulate](https://github.com/bndr/gotabulate) | 296 | Easily pretty-print your tabular data with Go. |
| <b>[align](https://github.com/Guitarbum722/align) | 80 | A general purpose application that aligns text. |
| <b>[go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 73 | Fixed-width text formatting (encoder/decoder with reflection). |
| <b>[address](https://github.com/bojanz/address) | 63 | Handles address representation, validation and formatting. |
| <b>[textwrap](https://github.com/isbm/textwrap) | 4 | Wraps text at end of lines. Implementation of `textwrap` module from Python. |


<br>

[👆back to top](#catalogue-list)


<br>

### Markup Languages


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[blackfriday](https://github.com/russross/blackfriday) | 5.2k | Markdown processor in Go. |
| <b>[toml](https://github.com/BurntSushi/toml) | 4.2k | TOML configuration format (encoder/decoder with reflection). |
| <b>[goldmark](https://github.com/yuin/goldmark) | 2.7k | A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured. |
| <b>[go-toml](https://github.com/pelletier/go-toml) | 1.5k | Go library for the TOML format with query support and handy cli tools. |
| <b>[htmlquery](https://github.com/antchfx/htmlquery) | 609 | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| <b>[mxj](https://github.com/clbanning/mxj) | 561 | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| <b>[html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 552 | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| <b>[goq](https://github.com/andrewstuart/goq) | 240 | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| <b>[bafi](https://github.com/mmalcek/bafi) | 76 | Universal JSON, BSON, YAML, XML translator to ANY format using templates. |
| <b>[go-output-format](https://github.com/drewstinnett/go-output-format) | 9 | Output go structures into multiple formats (YAML/JSON/etc) in your command line app. |
| <b>[bbConvert](https://github.com/CalebQ42/bbConvert) | 7 | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| <b>[htmlyaml](https://github.com/nikolaydubina/htmlyaml) | 2 | Rich rendering of YAML as HTML in Go |
| <b>[github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) | - | GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links. |


<br>

[👆back to top](#catalogue-list)


<br>

### Parsers/Encoders/Decoders


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sh](https://github.com/mvdan/sh) | 5.9k | Shell parser and formatter. |
| <b>[gofeed](https://github.com/mmcdole/gofeed) | 2.2k | Parse RSS and Atom feeds in Go. |
| <b>[when](https://github.com/olebedev/when) | 1.3k | Natural EN and RU language date/time parser with pluggable rules. |
| <b>[commonregex](https://github.com/mingrammer/commonregex) | 861 | A collection of common regular expressions for Go. |
| <b>[omniparser](https://github.com/jf-tech/omniparser) | 577 | A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. |
| <b>[gographviz](https://github.com/awalterschulze/gographviz) | 521 | Parses the Graphviz DOT language. |
| <b>[go-nmea](https://github.com/adrianmo/go-nmea) | 194 | NMEA parser library for the Go language. |
| <b>[editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 118 | Editorconfig file parser and manipulator for Go. |
| <b>[sdp](https://github.com/gortc/sdp) | 112 | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| <b>[go-vcard](https://github.com/emersion/go-vcard) | 88 | Parse and format vCard. |
| <b>[did](https://github.com/ockam-network/did) | 77 | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| <b>[allot](https://github.com/sbstjn/allot) | 56 | Placeholder and wildcard text parsing for CLI tools and bots. |
| <b>[tokenizer](https://github.com/bzick/tokenizer) | 46 | — Parse any string, slice or infinite buffer to any tokens. |
| <b>[parth](https://github.com/codemodus/parth) | 43 | URL path segmentation parsing. |
| <b>[gonameparts](https://github.com/polera/gonameparts) | 38 | Parses human names into individual name parts. |
| <b>[normalize](https://github.com/avito-tech/normalize) | 35 | Sanitize, normalize and compare fuzzy text. |
| <b>[xj2go](https://github.com/stackerzzq/xj2go) | 31 | Convert xml or json to go struct. |
| <b>[codetree](https://github.com/aerogo/codetree) | 22 | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| <b>[go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) | 17 | High performance top level domains (TLD) extraction module. |
| <b>[parseargs-go](https://github.com/nproc/parseargs-go) | 10 | string argument parser that understands quotes and backslashes. |
| <b>[encdec](https://github.com/mickep76/encdec) | 8 | Package provides a generic interface to encoders and decoders. |
| <b>[ltsv](https://github.com/Wing924/ltsv) | 8 | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |
| <b>[doi](https://github.com/hscells/doi) | 7 | Document object identifier (doi) parser in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Regular Expressions


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[rex](https://github.com/hedhyw/rex) | 154 | Regular expressions builder. |
| <b>[regroup](https://github.com/oriser/regroup) | 131 | Match regex expression named groups into go struct using struct tags and automatic parsing. |
| <b>[goregen](https://github.com/zach-klippenstein/goregen) | 85 | Library for generating random strings from regular expressions. |
| <b>[genex](https://github.com/alixaxel/genex) | 74 | Count and expand Regular Expressions into all matching Strings. |
| <b>[go-wildcard](https://github.com/IGLOU-EU/go-wildcard) | 46 | Simple and lightweight wildcard pattern matching. |


<br>

[👆back to top](#catalogue-list)


<br>

### Sanitation


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bluemonday](https://github.com/microcosm-cc/bluemonday) | 2.7k | HTML Sanitizer. |
| <b>[gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 55 | A sanitization-based swear filter for Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Scrapers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[colly](https://github.com/asciimoo/colly) | 20.0k | Fast and Elegant Scraping Framework for Gophers. |
| <b>[GoQuery](https://github.com/PuerkitoBio/goquery) | 13.0k | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| <b>[xurls](https://github.com/mvdan/xurls) | 1.1k | Extract urls from text. |
| <b>[dataflowkit](https://github.com/slotix/dataflowkit) | 593 | Web scraping Framework to turn websites into structured data. |
| <b>[gospider](https://github.com/zhshch2002/gospider) | 193 | A simple golang spider/scraping framework,build a spider in 3 lines. migrated from [goribot](https://github.com/zhshch2002/goribot) |
| <b>[pagser](https://github.com/foolin/pagser) | 85 | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| <b>[Tagify](https://github.com/zoomio/tagify) | 30 | Produces a set of tags from given source. |
| <b>[go-recipe](https://github.com/kkyr/go-recipe) | 20 | A package for scraping recipes from websites. |
| <b>[walker](https://github.com/cyucelen/walker) | 4 | Seamlessly fetch paginated data from any source. Simple and high performance API scraping included. |


<br>

[👆back to top](#catalogue-list)


<br>

### RSS


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[podcast](https://github.com/eduncan911/podcast) | 123 | iTunes Compliant and RSS 2.0 Podcast Generator in Golang |
| <b>[syndfeed](https://github.com/zhengchun/syndfeed) | 11 | A syndication feed for Atom 1.0 and RSS 2.0. |


<br>

[👆back to top](#catalogue-list)


<br>

### Utility/Miscellaneous


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-runewidth](https://github.com/mattn/go-runewidth) | 528 | Functions to get fixed width of the character or string. |
| <b>[radix](https://github.com/yourbasic/radix) | 184 | Fast string sorting algorithm. |
| <b>[go-zero-width](https://github.com/trubitsyn/go-zero-width) | 109 | Zero-width character detection and removal for Go. |
| <b>[petrovich](https://github.com/striker2000/petrovich) | 43 | Petrovich is the library which inflects Russian names to given grammatical case. |
| <b>[kace](https://github.com/codemodus/kace) | 19 | Common case conversions covering common initialisms. |
| <b>[TySug](https://github.com/Dynom/TySug) | 15 | Alternative suggestions with respect to keyboard layouts. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Third-party APIs

_Libraries for accessing third party APIs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[github](https://github.com/google/go-github) | 9.4k | Go library for accessing the GitHub REST API v3. |
| <b>[aws-sdk-go](https://github.com/aws/aws-sdk-go) | 8.3k | The official AWS SDK for the Go programming language. |
| <b>[go-openai](https://github.com/sashabaranov/go-openai) | 5.4k | OpenAI ChatGPT, DALL·E, Whisper API library for Go. |
| <b>[slack](https://github.com/slack-go/slack) | 4.3k | Slack API in Go. |
| <b>[discordgo](https://github.com/bwmarrin/discordgo) | 4.0k | Go bindings for the Discord Chat API. |
| <b>[google](https://github.com/google/google-api-go-client) | 3.5k | Auto-generated Google APIs for Go. |
| <b>[google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) | 3.3k | Google Cloud APIs Go Client Library. |
| <b>[minio-go](https://github.com/minio/minio-go) | 2.0k | Minio Go Library for Amazon S3 compatible cloud storage. |
| <b>[stripe](https://github.com/stripe/stripe-go) | 1.8k | Go client for the Stripe API. |
| <b>[go-twitter](https://github.com/dghubble/go-twitter) | 1.6k | Go client library for the Twitter v1.1 APIs. |
| <b>[go-jira](https://github.com/andygrunwald/go-jira) | 1.3k | Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) |
| <b>[anaconda](https://github.com/ChimeraCoder/anaconda) | 1.1k | Go client library for the Twitter 1.1 API. |
| <b>[facebook](https://github.com/huandu/facebook) | 1.1k | Go Library that supports the Facebook Graph API. |
| <b>[githubql](https://github.com/shurcooL/githubql) | 1000 | Go library for accessing the GitHub GraphQL API v4. |
| <b>[webhooks](https://github.com/go-playground/webhooks) | 838 | Webhook receiver for GitHub and Bitbucket. |
| <b>[paypal](https://github.com/logpacker/PayPal-Go-SDK) | 582 | Wrapper for PayPal payment API. |
| <b>[twitter-scraper](https://github.com/n0madic/twitter-scraper) | 498 | Scrape the Twitter Frontend API without authentication and limits. |
| <b>[geo-golang](https://github.com/codingsince1985/geo-golang) | 467 | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| <b>[lark](https://github.com/chyroc/lark) | 327 | [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback. |
| <b>[ethrpc](https://github.com/onrik/ethrpc) | 255 | Go bindings for Ethereum JSON RPC API. |
| <b>[openaigo](https://github.com/otiai10/openaigo) | 245 | OpenAI GPT3/GPT3.5 ChatGPT API client library for Go. |
| <b>[Trello](https://github.com/adlio/trello) | 209 | Go wrapper for the Trello API. |
| <b>[go-marathon](https://github.com/gambol99/go-marathon) | 199 | Go library for interacting with Mesosphere's Marathon PAAS. |
| <b>[go-lark](https://github.com/go-lark/lark) | 148 | An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform. |
| <b>[wit-go](https://github.com/wit-ai/wit-go) | 141 | Go client for wit.ai HTTP API. |
| <b>[Medium](https://github.com/Medium/medium-sdk-go) | 137 | Golang SDK for Medium's OAuth2 API. |
| <b>[pushover](https://github.com/gregdel/pushover) | 134 | Go wrapper for the Pushover API. |
| <b>[gostorm](https://github.com/jsgilmore/gostorm) | 130 | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| <b>[go-trending](https://github.com/andygrunwald/go-trending) | 128 | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| <b>[simples3](https://github.com/rhnvrm/simples3) | 115 | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| <b>[hipchat (xmpp)](https://github.com/daneharrigan/hipchat) | 110 | A golang package to communicate with HipChat over XMPP. |
| <b>[gosip](https://github.com/koltyakov/gosip) | 106 | Go client library SharePoint API. |
| <b>[hipchat](https://github.com/andybons/hipchat) | 104 | This project implements a golang client library for the Hipchat API. |
| <b>[cachet](https://github.com/andygrunwald/cachet) | 91 | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| <b>[go-atlassian](https://github.com/ctreminiom/go-atlassian) | 80 | Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud) |
| <b>[golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 79 | Golang wrapper for The Movie Database API v3. |
| <b>[igdb](https://github.com/Henry-Sarabia/igdb) | 77 | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| <b>[go-unsplash](https://github.com/hbagdi/go-unsplash) | 72 | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| <b>[gogtrends](https://github.com/groovili/gogtrends) | 72 | Google Trends Unofficial API. |
| <b>[go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 67 | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| <b>[google-play-scraper](https://github.com/n0madic/google-play-scraper) | 66 | Get data from Google Play Store. |
| <b>[circleci](https://github.com/jszwedko/go-circleci) | 64 | Go client library for interacting with CircleCI's API. |
| <b>[airtable](https://github.com/mehanizm/airtable) | 59 | Go client library for the [Airtable API](https://airtable.com/api). |
| <b>[mixpanel](https://github.com/dukex/mixpanel) | 59 | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| <b>[ynab](https://github.com/brunomvsouza/ynab.go) | 58 | Go wrapper for the YNAB API. |
| <b>[clarifai](https://github.com/samuelcouch/clarifai) | 56 | Go client library for interfacing with the Clarifai API. |
| <b>[amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 55 | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| <b>[megos](https://github.com/andygrunwald/megos) | 55 | Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster. |
| <b>[uptimerobot](https://github.com/bitfield/uptimerobot) | 55 | Go wrapper and command-line client for the Uptime Robot v2 API. |
| <b>[go-xkcd](https://github.com/nishanths/go-xkcd) | 51 | Go client for the xkcd API. |
| <b>[fcm](https://github.com/maddevsio/fcm) | 50 | Go library for Firebase Cloud Messaging. |
| <b>[gads](https://github.com/emiddleton/gads) | 50 | Google Adwords Unofficial API. |
| <b>[GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) | 49 | Go MusicBrainz WS2 client library. |
| <b>[spotify](https://github.com/rapito/go-spotify) | 47 | Go Library to access Spotify WEB API. |
| <b>[golyrics](https://github.com/mamal72/golyrics) | 40 | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| <b>[go-myanimelist](https://github.com/nstratos/go-myanimelist) | 36 | Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2). |
| <b>[patreon-go](https://github.com/mxpv/patreon-go) | 36 | Go library for Patreon API. |
| <b>[swag](https://github.com/zc2638/swag) | 36 | No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more. |
| <b>[translate](https://github.com/poorny/translate) | 33 | Go online translation package. |
| <b>[gami](https://github.com/bit4bit/gami) | 31 | Go library for Asterisk Manager Interface. |
| <b>[gcm](https://github.com/Aorioli/gcm) | 31 | Go library for Google Cloud Messaging. |
| <b>[lastpass-go](https://github.com/ansd/lastpass-go) | 31 | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| <b>[steam](https://github.com/sostronk/go-steam) | 30 | Go Library to interact with Steam game servers. |
| <b>[go-imgur](https://github.com/koffeinsource/go-imgur) | 25 | Go client library for [imgur](https://imgur.com) |
| <b>[shopify](https://github.com/rapito/go-shopify) | 25 | Go Library to make CRUD request to the Shopify API. |
| <b>[GoFreeDB](https://github.com/FreeLeh/GoFreeDB) | 25 | Golang library providing common and simple database abstractions on top of Google Sheets. |
| <b>[go-twitch](https://github.com/knspriggs/go-twitch) | 22 | Go client for interacting with the Twitch v3 API. |
| <b>[jokeapi-go](https://github.com/icelain/jokeapi) | 21 | Go client for [JokeAPI](https://sv443.net/jokeapi/v2/). |
| <b>[coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) | 20 | Go client library for interacting with Coinpaprika's API. |
| <b>[brewerydb](https://github.com/naegelejd/brewerydb) | 19 | Go library for accessing the BreweryDB API. |
| <b>[codeship-go](https://github.com/codeship/codeship-go) | 19 | Go client library for interacting with Codeship's API v2. |
| <b>[textbelt](https://github.com/dietsche/textbelt) | 19 | Go client for the textbelt.com txt messaging API. |
| <b>[device-check-go](https://github.com/rinchsan/device-check-go) | 18 | Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. |
| <b>[go-aws-news](https://github.com/circa10a/go-aws-news) | 17 | Go application and library to fetch what's new from AWS. |
| <b>[go-hacknews](https://github.com/PaulRosset/go-hacknews) | 16 | Tiny Go client for HackerNews API. |
| <b>[gopaapi5](https://github.com/utekaravinash/gopaapi5) | 14 | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| <b>[go-openproject](https://github.com/manuelbcd/go-openproject) | 13 | Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API. |
| <b>[go-sophos](https://github.com/esurdam/go-sophos) | 13 | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| <b>[google-analytics](https://github.com/chonthu/go-google-analytics) | 13 | Simple wrapper for easy google analytics reporting. |
| <b>[bqwriter](https://github.com/OTA-Insight/bqwriter) | 12 | High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout. |
| <b>[go-here](https://github.com/abdullahselek/go-here) | 12 | Go client library around the HERE location based APIs. |
| <b>[smite](https://github.com/sergiotapia/smitego) | 12 | Go package to wraps access to the Smite game API. |
| <b>[goami2](https://github.com/staskobzar/goami2) | 11 | AMI v2 library for Asterisk PBX. |
| <b>[go-swagger-ui](https://github.com/esurdam/go-swagger-ui) | 10 | Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json. |
| <b>[gomalshare](https://github.com/MonaxGT/gomalshare) | 10 | Go library MalShare API [malshare.com](https://www.malshare.com/) |
| <b>[libgoffi](https://github.com/clevabit/libgoffi) | 9 | Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration |
| <b>[rrdaclient](https://github.com/Omie/rrdaclient) | 9 | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| <b>[go-chronos](https://github.com/axelspringer/go-chronos) | 8 | Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler |
| <b>[go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 8 | Go client library for the SPTrans Olho Vivo API. |
| <b>[google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 8 | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| <b>[rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) | 8 | Go library for the [RAWG Video Games Database](https://rawg.io/) API |
| <b>[tumblr](https://github.com/mattcunningham/gumblr) | 8 | Go wrapper for the Tumblr v2 API. |
| <b>[go-hibp](https://github.com/wneessen/go-hibp) | 7 | Simple Go binding to the "Have I Been Pwned" APIs. |
| <b>[zooz](https://github.com/gojuno/go-zooz) | 7 | Go client for the Zooz API. |
| <b>[newsapi-go](https://github.com/jellydator/newsapi-go) | 6 | Go client for [NewsAPI](https://newsapi.org/). |
| <b>[goagi](https://github.com/staskobzar/goagi) | 6 | Go library to build Asterisk PBX agi/fastagi applications. |
| <b>[appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) | 3 | Unofficial Golang SDK for AppStore Connect API. |
| <b>[dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) | 3 | Unofficial Dusupay payment gateway API Client for Go |
| <b>[go-restcountries](https://github.com/chriscross0/go-restcountries) | 3 | Go library for the [REST Countries API](https://restcountries.eu/). |
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
| <b>[fzf](https://github.com/junegunn/fzf) | 53.0k | Command-line fuzzy finder written in Go. |
| <b>[hub](https://github.com/github/hub) | 22.0k | wrap git commands with additional functionality to interact with github from the terminal. |
| <b>[ctop](https://github.com/bcicen/ctop) | 14.0k | [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics. |
| <b>[sqlx](https://github.com/jmoiron/sqlx) | 14.0k | provides a set of extensions on top of the excellent built-in database/sql package. |
| <b>[goreleaser](https://github.com/goreleaser/goreleaser) | 12.0k | Deliver Go binaries as fast and easily as possible. |
| <b>[lo](https://github.com/samber/lo) | 12.0k | A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...) |
| <b>[wuzz](https://github.com/asciimoo/wuzz) | 10.0k | Interactive cli tool for HTTP inspection. |
| <b>[usql](https://github.com/knq/usql) | 8.1k | usql is a universal command-line interface for SQL databases. |
| <b>[peco](https://github.com/peco/peco) | 7.4k | Simplistic interactive filtering tool. |
| <b>[go-funk](https://github.com/thoas/go-funk) | 4.3k | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| <b>[godropbox](https://github.com/dropbox/godropbox) | 4.1k | Common libraries for writing Go services/applications from Dropbox. |
| <b>[hystrix-go](https://github.com/afex/hystrix-go) | 4.0k | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| <b>[panicparse](https://github.com/maruel/panicparse) | 3.4k | Groups similar goroutines and colorizes stack dump. |
| <b>[minify](https://github.com/tdewolff/minify) | 3.3k | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| <b>[goreporter](https://github.com/wgliang/goreporter) | 3.1k | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| <b>[mc](https://github.com/minio/mc) | 2.5k | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| <b>[lancet](https://github.com/duke-git/lancet) | 2.5k | A comprehensive, efficient, and reusable util function library of go. |
| <b>[mergo](https://github.com/imdario/mergo) | 2.4k | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| <b>[create-go-app](https://github.com/create-go-app/cli) | 2.0k | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| <b>[Storm](https://github.com/asdine/storm) | 2.0k | Simple and powerful toolkit for BoltDB. |
| <b>[filetype](https://github.com/h2non/filetype) | 1.8k | Small package to infer the file type checking the magic numbers signature. |
| <b>[EaseProbe](https://github.com/megaease/easeprobe) | 1.8k | A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification. |
| <b>[retry-go](https://github.com/avast/retry-go) | 1.7k | Simple library for retry mechanism. |
| <b>[boilr](https://github.com/tmrts/boilr) | 1.6k | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| <b>[jump](https://github.com/gsamokovarov/jump) | 1.6k | Jump helps you navigate faster by learning your habits. |
| <b>[mole](https://github.com/davrodpin/mole) | 1.6k | cli app to easily create ssh tunnels. |
| <b>[gitbatch](https://github.com/isacikgoz/gitbatch) | 1.5k | manage your git repositories in one place. |
| <b>[circuitbreaker](https://github.com/rubyist/circuitbreaker) | 1.1k | Circuit Breakers in Go. |
| <b>[mimetype](https://github.com/gabriel-vasile/mimetype) | 1.1k | Package for MIME type detection based on magic numbers. |
| <b>[git-time-metric](https://github.com/git-time-metric/gtm) | 937 | Simple, seamless, lightweight time tracking for Git. |
| <b>[scany](https://github.com/georgysavva/scany) | 937 | Library for scanning data from a database into Go structs and more. |
| <b>[hostctl](https://github.com/guumaster/hostctl) | 899 | A CLI tool to manage /etc/hosts with easy commands. |
| <b>[immortal](https://github.com/immortal/immortal) | 766 | \*nix cross-platform (OS agnostic) supervisor. |
| <b>[circuit](https://github.com/cep21/circuit) | 697 | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| <b>[delve](https://github.com/derekparker/delve) | 584 | Go debugger. |
| <b>[ergo](https://github.com/cristianoliveira/ergo) | 568 | The management of multiple local services running over different ports made easy. |
| <b>[htcat](https://github.com/htcat/htcat) | 552 | Parallel and Pipelined HTTP GET Utility. |
| <b>[koazee](https://github.com/wesovilabs/koazee) | 515 | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| <b>[godaemon](https://github.com/VividCortex/godaemon) | 491 | Utility to write daemons. |
| <b>[go-dry](https://github.com/ungerik/go-dry) | 487 | DRY (don't repeat yourself) package for Go. |
| <b>[clockwork](https://github.com/jonboulle/clockwork) | 485 | A simple fake clock for golang. |
| <b>[changie](https://github.com/miniscruff/changie) | 461 | Automated changelog tool for preparing releases with lots of customization options. |
| <b>[gopencils](https://github.com/bndr/gopencils) | 443 | Small and simple package to easily consume REST APIs. |
| <b>[gubrak](https://github.com/novalagung/gubrak) | 439 | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| <b>[request](https://github.com/mozillazg/request) | 424 | Go HTTP Requests for Humans™. |
| <b>[Deepcopier](https://github.com/ulule/deepcopier) | 410 | Simple struct copying for Go. |
| <b>[clipboard](https://github.com/golang-design/clipboard) | 403 | 📋 cross-platform clipboard package in Go. |
| <b>[scan](https://github.com/blockloop/scan) | 399 | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| <b>[remote-touchpad](https://github.com/Unrud/remote-touchpad) | 396 | Control mouse and keyboard from a smartphone. |
| <b>[go-rate](https://github.com/beefsack/go-rate) | 386 | Timed rate limiter for Go. |
| <b>[mani](https://github.com/alajmo/mani) | 365 | CLI tool to help you manage multiple repositories. |
| <b>[retry](https://github.com/kamilsk/retry) | 336 | The most advanced functional mechanism to perform actions repetitively until successful. |
| <b>[serve](https://github.com/syntaqx/serve) | 297 | A static http server anywhere you need. |
| <b>[util](https://github.com/shomali11/util) | 274 | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| <b>[grofer](https://github.com/pesos/grofer) | 272 | A system and resource monitoring tool written in Golang! |
| <b>[gotenv](https://github.com/subosito/gotenv) | 259 | Load environment variables from `.env` or any `io.Reader` in Go. |
| <b>[gohper](https://github.com/cosiner/gohper) | 255 | Various tools/modules help for development. |
| <b>[countries](https://github.com/biter777/countries) | 249 | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| <b>[go-trigger](https://github.com/sadlil/go-trigger) | 233 | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| <b>[wifiqr](https://github.com/reugn/wifiqr) | 231 | Wi-Fi QR Code Generator. |
| <b>[rospo](https://github.com/ferama/rospo) | 224 | Simple and reliable ssh tunnels with embedded ssh server in Golang. |
| <b>[pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 222 | Pattern matching libray. |
| <b>[go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 202 | XML Sitemap generator written in Go. |
| <b>[toolbox](https://github.com/viant/toolbox) | 192 | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| <b>[Death](https://github.com/vrecan/death) | 189 | Managing go application shutdown with signals. |
| <b>[go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 183 | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| <b>[moldova](https://github.com/StabbyCutyou/moldova) | 166 | Utility for generating random data based on an input template. |
| <b>[rerun](https://github.com/ivpusic/rerun) | 165 | Recompiling and rerunning go apps when source changes. |
| <b>[apm](https://github.com/topfreegames/apm) | 163 | Process manager for Golang applications with an HTTP API. |
| <b>[limiters](https://github.com/mennanov/limiters) | 158 | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| <b>[robustly](https://github.com/VividCortex/robustly) | 156 | Runs functions resiliently, catching and restarting panics. |
| <b>[chyle](https://github.com/antham/chyle) | 150 | Changelog generator using a git repository with multiple configuration possibilities. |
| <b>[go-bsdiff](https://github.com/gabstv/go-bsdiff) | 143 | Pure Go bsdiff and bspatch libraries and CLI tools. |
| <b>[nostromo](https://github.com/pokanop/nostromo) | 135 | CLI for building powerful aliases. |
| <b>[cryptgo](https://github.com/Gituser143/cryptgo) | 133 | Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time! |
| <b>[onecache](https://github.com/adelowo/onecache) | 132 | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| <b>[cmd](https://github.com/SimonBaeumer/cmd) | 131 | Library for executing shell commands on osx, windows and linux. |
| <b>[filter](https://github.com/gookit/filter) | 131 | provide filtering, sanitizing, and conversion of Go data. |
| <b>[lrserver](https://github.com/jaschaephraim/lrserver) | 124 | LiveReload server for Go. |
| <b>[sorty](https://github.com/jfcg/sorty) | 120 | Fast Concurrent / Parallel Sorting. |
| <b>[goval](https://github.com/maja42/goval) | 117 | Evaluate arbitrary expressions in Go. |
| <b>[mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 113 | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| <b>[mssqlx](https://github.com/linxGnu/mssqlx) | 101 | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| <b>[goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 100 | SeaweedFS client library with almost full features. |
| <b>[xferspdy](https://github.com/monmohan/xferspdy) | 96 | Xferspdy provides binary diff and patch library in golang. |
| <b>[go-health](https://github.com/Talento90/go-health) | 92 | Health package simplifies the way you add health check to your services. |
| <b>[mimemagic](https://github.com/zRedShift/mimemagic) | 90 | Pure Go ultra performant MIME sniffing library/utility. |
| <b>[go-lock](https://github.com/viney-shih/go-lock) | 88 | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| <b>[repeat](https://github.com/ssgreg/repeat) | 81 | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| <b>[pgo](https://github.com/arthurkushman/pgo) | 79 | Convenient functions for PHP community. |
| <b>[pm](https://github.com/VividCortex/pm) | 78 | Process (i.e. goroutine) manager with an HTTP API. |
| <b>[countries](https://github.com/pioz/countries) | 76 | All you need when you are working with countries in Go. |
| <b>[handy](https://github.com/miguelpragier/handy) | 73 | Many utilities and helpers like string handlers/formatters and validators. |
| <b>[netbug](https://github.com/e-dard/netbug) | 72 | Easy remote profiling of your services. |
| <b>[UNIS](https://github.com/esemplastic/unis) | 70 | Common Architecture™ for String Utilities in Go. |
| <b>[multitick](https://github.com/VividCortex/multitick) | 67 | Multiplexor for aligned tickers. |
| <b>[goreadability](https://github.com/philipjkim/goreadability) | 66 | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| <b>[retry](https://github.com/thedevsaddam/retry) | 63 | Simple and easy retry mechanism package for Go. |
| <b>[go-astitodo](https://github.com/asticode/go-astitodo) | 60 | Parse TODOs in your GO code. |
| <b>[minquery](https://github.com/icza/minquery) | 60 | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| <b>[golog](https://github.com/mlimaloureiro/golog) | 59 | Easy and lightweight CLI tool to time track your tasks. |
| <b>[dbt](https://github.com/nikogura/dbt) | 57 | A framework for running self-updating signed binaries from a central, trusted repository. |
| <b>[beyond](https://github.com/wesovilabs/beyond) | 53 | The Go tool that will drive you to the AOP world! |
| <b>[shutdown](https://github.com/ztrue/shutdown) | 51 | App shutdown hooks for `os.Signal` handling. |
| <b>[slice](https://github.com/psampaz/slice) | 51 | Type-safe functions for common Go slice operations. |
| <b>[copy-pasta](https://github.com/jutkko/copy-pasta) | 50 | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| <b>[golarm](https://github.com/msempere/golarm) | 50 | Fire alarms with system events. |
| <b>[scan](https://github.com/wroge/scan) | 49 | Scan sql rows into any type powered by generics. |
| <b>[goback](https://github.com/carlescere/goback) | 48 | Go simple exponential backoff package. |
| <b>[retry-go](https://github.com/rafaeljesus/retry-go) | 47 | Retrying made simple and easy for golang. |
| <b>[intrinsic](https://github.com/mengzhuo/intrinsic) | 46 | Use x86 SIMD without writing any assembly code. |
| <b>[backscanner](https://github.com/icza/backscanner) | 45 | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| <b>[go-httpheader](https://github.com/mozillazg/go-httpheader) | 44 | Go library for encoding structs into Header fields. |
| <b>[set](https://github.com/nofeaturesonlybugs/set) | 44 | Performant and flexible struct mapping and loose type conversion. |
| <b>[slicer](https://github.com/leaanthony/slicer) | 43 | Makes working with slices easier. |
| <b>[sshman](https://github.com/shoobyban/sshman) | 43 | SSH Manager for authorized_keys files on multiple remote servers. |
| <b>[equalizer](https://github.com/reugn/equalizer) | 42 | Quota manager and rate limiter collection for Go. |
| <b>[gostrutils](https://github.com/ik5/gostrutils) | 40 | Collections of string manipulation and conversion functions. |
| <b>[gpath](https://github.com/tenntenn/gpath) | 40 | Library to simplify access struct fields with Go's expression in reflection. |
| <b>[evaluator](https://github.com/nullne/evaluator) | 37 | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| <b>[pointer](https://github.com/xorcare/pointer) | 36 | Package pointer contains helper routines for simplifying the creation of optional fields of basic type. |
| <b>[cvt](https://github.com/shockerli/cvt) | 35 | Easy and safe convert any value to another type. |
| <b>[ghokin](https://github.com/antham/ghokin) | 35 | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| <b>[myhttp](https://github.com/inancgumus/myhttp) | 35 | Simple API to make HTTP GET requests with timeout support. |
| <b>[rclient](https://github.com/zpatrick/rclient) | 35 | Readable, flexible, simple-to-use client for REST APIs. |
| <b>[tome](https://github.com/cyruzin/tome) | 34 | Tome was designed to paginate simple RESTful APIs. |
| <b>[throttle](https://github.com/yudppp/throttle) | 33 | Throttle is an object that will perform exactly one action per duration. |
| <b>[copy](https://github.com/gotidy/copy) | 31 | Package for fast copying structs of different types. |
| <b>[generate](https://github.com/go-playground/generate) | 29 | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| <b>[mimesniffer](https://github.com/aofei/mimesniffer) | 28 | A MIME type sniffer for Go. |
| <b>[ugo](https://github.com/alxrm/ugo) | 27 | ugo is slice toolbox with concise syntax for Go. |
| <b>[goplaceholder](https://github.com/michiwend/goplaceholder) | 26 | a small golang lib to generate placeholder images. |
| <b>[rerate](https://github.com/abo/rerate) | 24 | Redis-based rate counter and rate limiter for Go. |
| <b>[graterm](https://github.com/skovtunenko/graterm) | 24 | Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application. |
| <b>[watchhttp](https://github.com/nikolaydubina/watchhttp) | 23 | Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint. |
| <b>[ctxutil](https://github.com/posener/ctxutil) | 22 | A collection of utility functions for contexts. |
| <b>[structs](https://github.com/PumpkinSeed/structs) | 22 | Implement simple functions to manipulate structs. |
| <b>[ptr](https://github.com/gotidy/ptr) | 21 | Package that provide functions for simplified creation of pointers from constants of basic types. |
| <b>[go-convert](https://github.com/Eun/go-convert) | 20 | Package go-convert enables you to convert a value into another type. |
| <b>[just](https://github.com/kazhuravlev/just) | 20 | Just a collection of useful functions for working with generic data structures. |
| <b>[jsend](https://github.com/clevergo/jsend) | 19 | JSend's implementation writen in Go. |
| <b>[dlog](https://github.com/kirillDanshin/dlog) | 17 | Compile-time controlled logger to make your release smaller without removing debug calls. |
| <b>[filler](https://github.com/yaronsumel/filler) | 17 | small utility to fill structs using "fill" tag. |
| <b>[go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 17 | Go package for working with Problem Details. |
| <b>[contextplus](https://github.com/contextplus/contextplus) | 17 | Package contextplus provide more easy to use functions for contexts. |
| <b>[okrun](https://github.com/xta/okrun) | 16 | go run error steamroller. |
| <b>[rest-go](https://github.com/edermanoel94/rest-go) | 16 | A package that provide many helpful methods for working with rest api. |
| <b>[go-type](https://github.com/mikekonan/go-types) | 15 | Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. |
| <b>[command](https://github.com/txgruppi/command) | 14 | Command pattern for Go with thread safe serial and parallel dispatcher. |
| <b>[go-actuator](https://github.com/sinhashubham95/go-actuator) | 14 | Production ready features for Go based web frameworks. |
| <b>[go-clip](https://github.com/prashantgupta24/go-clip) | 12 | A minimalistic clipboard manager for Mac. |
| <b>[silk](https://github.com/chrispassas/silk) | 12 | Read silk netflow files. |
| <b>[retry](https://github.com/shafreeck/retry) | 11 | A pretty simple library to ensure your work to be done. |
| <b>[blank](https://github.com/Henry-Sarabia/blank) | 10 | Verify or remove blanks and whitespace from strings. |
| <b>[go-countries](https://github.com/mikekonan/go-countries) | 10 | Lightweight lookup over ISO-3166 codes. |
| <b>[statiks](https://github.com/janiltonmaciel/statiks) | 10 | Fast, zero-configuration, static HTTP filer server. |
| <b>[bleep](https://github.com/sinhashubham95/bleep) | 9 | Perform any number of actions on any set of OS signals in Go. |
| <b>[retry](https://github.com/percolate/retry) | 9 | A simple but highly configurable retry package for Go. |
| <b>[nfdump](https://github.com/chrispassas/nfdump) | 8 | Read nfdump netflow files. |
| <b>[sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 8 | Slice conversion between primitive types. |
| <b>[go-pkg](https://github.com/chenquan/go-pkg) | 6 | A go toolkit. |
| <b>[go-safe](https://github.com/kenkyu392/go-safe) | 6 | Panic-safe sandbox. |
| <b>[loncha](https://github.com/kazu/loncha) | 6 | A high-performance slice Utilities. |
| <b>[lets-go](https://github.com/aplescia-chwy/lets-go) | 5 | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| <b>[olaf](https://github.com/btnguyen2k/olaf) | 5 | Twitter Snowflake implemented in Go. |
| <b>[reflectutils](https://github.com/muir/reflectutils) | 5 | Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string. |
| <b>[tik](https://github.com/andy2046/tik) | 5 | Simple and easy timing wheel package for Go. |
| <b>[goctx](https://github.com/zerosnake0/goctx) | 4 | Get your context value with high performance. |
| <b>[objwalker](https://github.com/rekby/objwalker) | 2 | Walk by go objects with reflection. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## UUID

_Libraries for working with UUIDs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[uuid](https://github.com/google/uuid) | 4.4k | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| <b>[ulid](https://github.com/oklog/ulid) | 3.5k | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| <b>[xid](https://github.com/rs/xid) | 3.4k | Xid is a globally unique id generator library, ready to be safely used directly in your server code. |
| <b>[uuid](https://github.com/gofrs/uuid) | 1.4k | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| <b>[wuid](https://github.com/edwingeng/wuid) | 494 | An extremely fast unique number generator, 10-135 times faster than UUID. |
| <b>[sno](https://github.com/muyo/sno) | 83 | Compact, sortable and fast unique IDs with embedded metadata. |
| <b>[nanoid](https://github.com/aidarkhanov/nanoid) | 59 | A tiny and efficient Go unique string ID generator. |
| <b>[goid](https://github.com/jakehl/goid) | 38 | Generate and Parse RFC4122 compliant V4 UUIDs. |
| <b>[gouid](https://github.com/twharmon/gouid) | 20 | Generate cryptographically secure random string IDs with just one allocation. |
| <b>[uuid](https://github.com/agext/uuid) | 15 | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |
| <b>[goflake](https://github.com/hart87/GoFlake) | 12 | A small, scalable, & serverless unique ID generator for use in distributed systems. Inspired by Twitters Snowflake. |
| <b>[uniq](https://gitlab.com/skilstak/code/go/uniq) | - | No hassle safe, fast unique identifiers with commands. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Validation

_Libraries for validation._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[validator](https://github.com/go-playground/validator) | 13.0k | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| <b>[govalidator](https://github.com/asaskevich/govalidator) | 5.7k | Validators and sanitizers for strings, numerics, slices and structs. |
| <b>[ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 3.2k | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| <b>[govalidator](https://github.com/thedevsaddam/govalidator) | 1.2k | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| <b>[validate](https://github.com/gookit/validate) | 890 | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| <b>[checkdigit](https://github.com/osamingo/checkdigit) | 99 | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| <b>[validate](https://github.com/gobuffalo/validate) | 82 | This package provides a framework for writing validations for Go applications. |
| <b>[terraform-validator](https://github.com/thazelart/terraform-validator) | 79 | A norms and conventions validator for Terraform. |
| <b>[jio](https://github.com/faceair/jio) | 76 | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| <b>[gody](https://github.com/guiferpa/gody) | 63 | :balloon: A lightweight struct validator for Go. |
| <b>[govalid](https://github.com/twharmon/govalid) | 33 | Fast, tag-based validation for structs. |
| <b>[valix](https://github.com/marrow16/valix) | 9 | Go package for validating requests |
| <b>[Validator](https://github.com/go-the-way/validator) | 5 | A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Version Control

_Libraries for version control._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-git](https://github.com/go-git/go-git) | 4.7k | highly extensible Git implementation in pure Go. |
| <b>[glab](https://github.com/profclems/glab) | 2.1k | An open-source GitLab command line tool bringing GitLab's cool features to your command line. |
| <b>[git2go](https://github.com/libgit2/git2go) | 1.9k | Go bindings for libgit2. |
| <b>[hercules](https://github.com/src-d/hercules) | 1.9k | gaining advanced insights from Git repository history. |
| <b>[gh](https://github.com/rjeczalik/gh) | 79 | Scriptable server and net/http middleware for GitHub Webhooks. |
| <b>[go-vcs](https://github.com/sourcegraph/go-vcs) | 74 | manipulate and inspect VCS repositories in Go. |
| <b>[githooks](https://github.com/gabyx/githooks) | 68 | Per-repo and shared Git hooks with version control and auto update. |
| <b>[froggit-go](https://github.com/jfrog/froggit-go) | 38 | Froggit-Go is a Go library, allowing to perform actions on VCS providers. |
| <b>[hgo](https://github.com/beyang/hgo) | 15 | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |
| <b>[cli](https://gitlab.com/gitlab-org/cli) | - | An open-source GitLab command line tool bringing GitLab's cool features to your command line. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Video

_Libraries for manipulating video._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[goav](https://github.com/giorgisio/goav) | 2.0k | Comprehensive Go bindings for FFmpeg. |
| <b>[m3u8](https://github.com/grafov/m3u8) | 1000 | Parser and generator library of M3U8 playlists for Apple HLS. |
| <b>[gmf](https://github.com/3d0c/gmf) | 841 | Go bindings for FFmpeg av\* libraries. |
| <b>[go-astits](https://github.com/asticode/go-astits) | 478 | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| <b>[go-astisub](https://github.com/asticode/go-astisub) | 463 | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| <b>[gortsplib](https://github.com/aler9/gortsplib) | 428 | Pure Go RTSP server and client library. |
| <b>[libvlc-go](https://github.com/adrg/libvlc-go) | 355 | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| <b>[gst](https://github.com/ziutek/gst) | 166 | Go bindings for GStreamer. |
| <b>[go-m3u8](https://github.com/quangngotan95/go-m3u8) | 104 | Parser and generator library for Apple m3u8 playlists. |
| <b>[v4l](https://github.com/korandiz/v4l) | 75 | Video capture library for Linux, written in Go. |
| <b>[libgosubs](https://github.com/wargarblgarbl/libgosubs) | 23 | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| <b>[go-m3u8](https://github.com/etherlabsio/go-m3u8) | 17 | Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility. |
| <b>[go-mpd](https://github.com/unki2aut/go-mpd) | 16 | Parser and generator library for MPEG-DASH manifest files. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Web Frameworks

_Full stack web frameworks._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Gin](https://github.com/gin-gonic/gin) | 69.0k | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| <b>[Beego](https://github.com/beego/beego) | 30.0k | beego is an open-source, high-performance web framework for the Go programming language. |
| <b>[Fiber](https://github.com/gofiber/fiber) | 27.0k | An Express.js inspired web framework build on Fasthttp. |
| <b>[Echo](https://github.com/labstack/echo) | 26.0k | High performance, minimalist Go web framework. |
| <b>[Revel](https://github.com/revel/revel) | 13.0k | High-productivity web framework for the Go language. |
| <b>[GoFrame](https://github.com/gogf/gf) | 9.4k | GoFrame is a modular, full-featured and production-ready application development framework of golang. |
| <b>[Goa](https://github.com/goadesign/goa) | 5.2k | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| <b>[Hertz](https://github.com/cloudwego/hertz) | 3.8k | A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices. |
| <b>[Gizmo](https://github.com/NYTimes/gizmo) | 3.7k | Microservice toolkit used by the New York Times. |
| <b>[go-json-rest](https://github.com/ant0ine/go-json-rest) | 3.5k | Quick and easy way to setup a RESTful JSON API. |
| <b>[Macaron](https://github.com/go-macaron/macaron) | 3.4k | Macaron is a high productive and modular design web framework in Go. |
| <b>[utron](https://github.com/gernest/utron) | 2.2k | Lightweight MVC framework for Go(Golang). |
| <b>[Goyave](https://github.com/go-goyave/goyave) | 1.3k | Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities. |
| <b>[REST Layer](https://github.com/rs/rest-layer) | 1.2k | Framework to build REST/GraphQL API on top of databases with mostly configuration over code. |
| <b>[Atreugo](https://github.com/savsgio/atreugo) | 1.1k | High performance and extensible micro web framework with zero memory allocations in hot paths. |
| <b>[tigertonic](https://github.com/rcrowley/go-tigertonic) | 998 | Go framework for building JSON web services inspired by Dropwizard. |
| <b>[tango](https://github.com/lunny/tango) | 834 | Micro & pluggable web framework for Go. |
| <b>[Gearbox](https://github.com/abahmed/gearbox) | 712 | A web framework written in Go with a focus on high performance and memory optimization. |
| <b>[Aero](https://github.com/aerogo/aero) | 525 | High-performance web framework for Go, reaches top scores in Lighthouse. |
| <b>[gongular](https://github.com/mustafaakin/gongular) | 495 | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| <b>[Air](https://github.com/aofei/air) | 429 | An ideally refined web framework for Go. |
| <b>[Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 429 | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| <b>[neo](https://github.com/ivpusic/neo) | 418 | Neo is minimal and fast Go Web Framework with extremely simple API. |
| <b>[rk-boot](https://github.com/rookie-ninja/rk-boot) | 408 | A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily. |
| <b>[Flamingo](https://github.com/i-love-flamingo/flamingo) | 382 | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| <b>[mango](https://github.com/paulbellamy/mango) | 372 | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| <b>[Gondola](https://github.com/rainycape/gondola) | 310 | The web framework for writing faster sites, faster. |
| <b>[WebGo](https://github.com/bnkamalesh/webgo) | 280 | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| <b>[uAdmin](https://github.com/uadmin/uadmin) | 274 | Fully featured web framework for Golang, inspired by Django. |
| <b>[Ginrpc](https://github.com/xxjwxc/ginrpc) | 270 | Gin parameter automatic binding tool,gin rpc tools. |
| <b>[Golf](https://github.com/dinever/golf) | 265 | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| <b>[Huma](https://github.com/danielgtaylor/huma/) | 203 | Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI. |
| <b>[hiboot](https://github.com/hidevopsio/hiboot) | 179 | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| <b>[appy](https://github.com/appist/appy) | 129 | An opinionated productive web framework that helps scaling business easier. |
| <b>[go-rest](https://github.com/ungerik/go-rest) | 127 | Small and evil REST framework for Go. |
| <b>[patron](https://github.com/beatlabs/patron) | 125 | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| <b>[Microservice](https://github.com/claygod/microservice) | 111 | The framework for the creation of microservices, written in Golang. |
| <b>[rux](https://github.com/gookit/rux) | 89 | Simple and fast web framework for build golang HTTP applications. |
| <b>[vox](https://github.com/aisk/vox) | 80 | A golang web framework for humans, inspired by Koa heavily. |
| <b>[Golax](https://github.com/fulldump/golax) | 76 | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| <b>[YARF](https://github.com/yarf-framework/yarf) | 65 | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| <b>[Fireball](https://github.com/zpatrick/fireball) | 59 | More "natural" feeling web framework. |
| <b>[goa](https://github.com/goa-go/goa) | 49 | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| <b>[GoTuna](https://github.com/gotuna/gotuna) | 43 | Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embedded views and static files. |
| <b>[Pulse](https://github.com/gopulse/pulse) | 36 | Pulse is an HTTP web framework written in Go (Golang) |
| <b>[goweb](https://github.com/twharmon/goweb) | 35 | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |
| <b>[Resoursea](https://github.com/resoursea/api) | 33 | REST framework for quickly writing resource based services. |
| <b>[rex](https://github.com/goanywhere/rex) | 33 | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| <b>[Banjo](https://github.com/nsheremet/banjo) | 21 | Very simple and fast web framework for Go. |
| <b>[Don](https://github.com/abemedia/go-don) | 20 | A highly performant and simple to use API framework. |
| <b>[anoweb](https://github.com/go-the-way/anoweb) | 5 | The lightweight and powerful web framework using the new way for Go.Another go the way. |
| <b>[golamb](https://github.com/twharmon/golamb) | 5 | Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway. |
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
| <b>[CORS](https://github.com/rs/cors) | 2.4k | Easily add CORS capabilities to your API. |
| <b>[Tollbooth](https://github.com/didip/tollbooth) | 2.4k | Rate limit HTTP request handler. |
| <b>[Limiter](https://github.com/ulule/limiter) | 1.8k | Dead simple rate limit middleware for Go. |
| <b>[go-server-timing](https://github.com/mitchellh/go-server-timing) | 852 | Add/parse Server-Timing header. |
| <b>[go-fault](https://github.com/github/go-fault) | 480 | Fault injection middleware for Go. |
| <b>[ln-paywall](https://github.com/philippgille/ln-paywall) | 135 | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| <b>[XFF](https://github.com/sebest/xff) | 97 | Handle `X-Forwarded-For` header and friends. |
| <b>[rk-grpc](https://github.com/rookie-ninja/rk-grpc) | 65 | Middleware for gRPC with logging, metrics, auth, tracing etc. |
| <b>[rk-gin](https://github.com/rookie-ninja/rk-gin) | 40 | Middleware for Gin framework with logging, metrics, auth, tracing etc. |
| <b>[formjson](https://github.com/rs/formjson) | 38 | Transparently handle JSON input as a standard form POST. |
| <b>[client-timing](https://github.com/posener/client-timing) | 24 | An HTTP client for Server-Timing header. |
| <b>[echo-middleware](https://github.com/faabiosr/echo-middleware) | 14 | Middleware for Echo framework with logging and metrics. |
| <b>[mid](https://github.com/bobg/mid) | 7 | Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more. |


<br>

[👆back to top](#catalogue-list)


<br>

#### Libraries for creating HTTP middlewares


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[negroni](https://github.com/urfave/negroni) | 7.3k | Idiomatic HTTP middleware for Golang. |
| <b>[alice](https://github.com/justinas/alice) | 2.8k | Painless middleware chaining for Go. |
| <b>[render](https://github.com/unrolled/render) | 1.8k | Go package for easily rendering JSON, XML, and HTML template responses. |
| <b>[stats](https://github.com/thoas/stats) | 590 | Go middleware that stores various information about your web application. |
| <b>[interpose](https://github.com/carbocation/interpose) | 295 | Minimalist net/http middleware for golang. |
| <b>[renderer](https://github.com/thedevsaddam/renderer) | 256 | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| <b>[muxchain](https://github.com/stephens2424/muxchain) | 208 | Lightweight middleware for net/http. |
| <b>[rye](https://github.com/InVisionApp/rye) | 101 | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| <b>[gores](https://github.com/alioygur/gores) | 100 | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| <b>[mediary](https://github.com/HereMobilityDevelopers/mediary) | 85 | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| <b>[chain](https://github.com/codemodus/chain) | 65 | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| <b>[go-wrap](https://github.com/go-on/wrap) | 59 | Small middlewares package for net/http. |
| <b>[catena](https://github.com/codemodus/catena) | 9 | http.Handler wrapper catenation (same API as "chain"). |


<br>

[👆back to top](#catalogue-list)


<br>

### Routers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[mux](https://github.com/gorilla/mux) | 18.0k | Powerful URL router and dispatcher for golang. |
| <b>[httprouter](https://github.com/julienschmidt/httprouter) | 15.0k | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| <b>[chi](https://github.com/go-chi/chi) | 14.0k | Small, fast and expressive HTTP router built on net/context. |
| <b>[gocraft/web](https://github.com/gocraft/web) | 1.5k | Mux and middleware package in Go. |
| <b>[Bone](https://github.com/go-zoo/bone) | 1.3k | Lightning Fast HTTP Multiplexer. |
| <b>[Goji](https://github.com/goji/goji) | 940 | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| <b>[fasthttprouter](https://github.com/buaazp/fasthttprouter) | 874 | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| <b>[httptreemux](https://github.com/dimfeld/httptreemux) | 594 | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| <b>[xujiajun/gorouter](https://github.com/xujiajun/gorouter) | 531 | A simple and fast HTTP router for Go. |
| <b>[ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 449 | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| <b>[lars](https://github.com/go-playground/lars) | 389 | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| <b>[Siesta](https://github.com/VividCortex/siesta) | 351 | Composable framework to write middleware and handlers. |
| <b>[vestigo](https://github.com/husobee/vestigo) | 268 | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| <b>[gowww/router](https://github.com/gowww/router) | 166 | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| <b>[GoRouter](https://github.com/vardius/gorouter) | 148 | GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| <b>[pure](https://github.com/go-playground/pure) | 139 | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| <b>[alien](https://github.com/gernest/alien) | 127 | Lightweight and fast http router from outer space. |
| <b>[violetear](https://github.com/nbari/violetear) | 106 | Go HTTP router. |
| <b>[Bxog](https://github.com/claygod/Bxog) | 105 | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| <b>[xmux](https://github.com/rs/xmux) | 95 | High performance muxer based on `httprouter` with `net/context` support. |
| <b>[goblin](https://github.com/bmf-san/goblin) | 59 | A golang http router based on trie tree. |
| <b>[ngamux](https://github.com/ngamux/ngamux) | 58 | Simple HTTP router for Go. |
| <b>[bellt](https://github.com/GuilhermeCaruso/bellt) | 54 | A simple Go HTTP router. |
| <b>[FastRouter](https://github.com/razonyang/fastrouter) | 22 | a fast, flexible HTTP router written in Go. |
| <b>[GoLobby/Router](https://github.com/golobby/router) | 21 | GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language. |
| <b>[nchi](https://github.com/muir/nchi) | 13 | chi-like router built on httprouter with dependency injection based middleware wrappers |
| <b>[goroute](https://github.com/goroute/route) | 8 | Simple yet powerful HTTP request multiplexer. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## WebAssembly


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[tinygo](https://github.com/tinygo-org/tinygo) | 13.0k | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| <b>[dom](https://github.com/dennwc/dom) | 475 | DOM library. |
| <b>[go-canvas](https://github.com/markfarnan/go-canvas) | 208 | Library to use HTML5 Canvas, with all drawing within go code. |
| <b>[wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 146 | Run Go WASM tests in your browser. |
| <b>[webapi](https://github.com/gowebapi/webapi) | 142 | Bindings for DOM and HTML generated from WebIDL. |
| <b>[vert](https://github.com/norunners/vert) | 84 | Interop between Go and JS values. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Windows


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-ole](https://github.com/go-ole/go-ole) | 986 | Win32 OLE implementation for golang. |
| <b>[d3d9](https://github.com/gonutz/d3d9) | 142 | Go bindings for Direct3D9. |
| <b>[gosddl](https://github.com/MonaxGT/gosddl) | 10 | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## XML

_Libraries and tools for manipulating XML._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[zek](https://github.com/miku/zek) | 669 | Generate a Go struct from XML. |
| <b>[xpath](https://github.com/antchfx/xpath) | 580 | XPath package for Go. |
| <b>[xquery](https://github.com/antchfx/xquery) | 156 | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| <b>[xml2map](https://github.com/sbabiv/xml2map) | 49 | XML to MAP converter written Golang. |
| <b>[xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 24 | Procedural XML generation API based on libxml2's xmlwriter module. |
| <b>[XML-Comp](https://github.com/xml-comp/xml-comp) | 20 | Simple command line XML comparer that generates diffs of folders, files and tags. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Zero Trust

_Libraries and tools to implement Zero Trust architectures._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Cosign](https://github.com/sigstore/cosign) | 3.4k | Container Signing, Verification and Storage in an OCI registry. |
| <b>[Spire](https://github.com/spiffe/spire) | 1.4k | SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms. |
| <b>[in-toto](https://github.com/in-toto/in-toto-golang) | 92 | Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation. |
| <b>[Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) | 58 | Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Code Analysis

_Source code analysis tools, also known as Static Application Security Testing (SAST) Tools._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) | 5.4k | gosimple is a linter for Go source code that specialises on simplifying code. |
| <b>[staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) | 5.4k | staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#. |
| <b>[unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) | 5.4k | unused checks Go code for unused constants, variables, functions and types. |
| <b>[GoLint](https://github.com/golang/lint) | 4.0k | Golint is a linter for Go source code. |
| <b>[errcheck](https://github.com/kisielk/errcheck) | 2.1k | Errcheck is a program for checking for unchecked errors in Go programs. |
| <b>[go-critic](https://github.com/go-critic/go-critic) | 1.6k | source code linter that brings checks that are currently not implemented in other linters. |
| <b>[GoPlantUML](https://github.com/jfeliu007/goplantuml) | 1.4k | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| <b>[gcvis](https://github.com/davecheney/gcvis) | 1.1k | Visualise Go program GC trace data in real time. |
| <b>[php-parser](https://github.com/z7zmey/php-parser) | 916 | A Parser for PHP written in Go. |
| <b>[go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 734 | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| <b>[goast-viewer](https://github.com/yuroyoro/goast-viewer) | 702 | Web based Golang AST visualizer. |
| <b>[go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 637 | An easy way to find outdated dependencies of your Go projects. |
| <b>[golines](https://github.com/segmentio/golines) | 619 | Formatter that automatically shortens long lines in Go code. |
| <b>[Chronos](https://github.com/amit-davidson/Chronos) | 404 | Detects race conditions statically |
| <b>[todocheck](https://github.com/preslavmihaylov/todocheck) | 398 | Static code analyser which links TODO comments in code with issues in your issue tracker. |
| <b>[unconvert](https://github.com/mdempsky/unconvert) | 352 | Remove unnecessary type conversions from Go source. |
| <b>[dupl](https://github.com/mibk/dupl) | 313 | Tool for code clone detection. |
| <b>[tickgit](https://github.com/augmentable-dev/tickgit) | 304 | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| <b>[gostatus](https://github.com/shurcooL/gostatus) | 244 | Command line tool, shows the status of repositories that contain Go packages. |
| <b>[vaccum](https://github.com/daveshanley/vacuum) | 210 | An ultra-super-fast, lightweight OpenAPI linter and quality checking tool. |
| <b>[apicompat](https://github.com/bradleyfalzon/apicompat) | 177 | Checks recent changes to a Go project for backwards incompatible changes. |
| <b>[go-checkstyle](https://github.com/qiniu/checkstyle) | 128 | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| <b>[lint](https://github.com/surullabs/lint) | 67 | Run linters as part of go test. |
| <b>[validate](https://github.com/mccoyst/validate) | 60 | Automatically validates struct fields with tags. |
| <b>[asty](https://github.com/asty-org/asty) | 46 | Converts golang AST to JSON and JSON to AST. |
| <b>[go-outdated](https://github.com/firstrow/go-outdated) | 44 | Console application that displays outdated packages. |
| <b>[usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) | 39 | A linter that detect the possibility to use variables/constants from the Go standard library. |
| <b>[ChainJacking](https://github.com/Checkmarx/chainjacking) | 37 | Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack. |
| <b>[tarp](https://github.com/verygoodsoftwarenotvirus/tarp) | 17 | tarp finds functions and methods without direct unit tests in Go source code. |
| <b>[golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) | 10 | iFood API SDK. |
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
| <b>[vim-go](https://github.com/fatih/vim-go) | 15.0k | Go development plugin for Vim. |
| <b>[gocode](https://github.com/nsf/gocode) | 5.0k | Autocompletion daemon for the Go programming language. |
| <b>[GoSublime](https://github.com/DisposaBoy/GoSublime) | 3.4k | Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. |
| <b>[vscode-go](https://github.com/golang/vscode-go) | 3.4k | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| <b>[go-plus](https://github.com/joefitzgerald/go-plus) | 1.5k | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| <b>[go-mode](https://github.com/dominikh/go-mode.el) | 1.3k | Go mode for GNU/Emacs. |
| <b>[coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) | 539 | This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim. |
| <b>[goimports-reviser](https://github.com/incu6us/goimports-reviser) | 343 | Formatting tool for imports. |
| <b>[Watch](https://github.com/eaburns/Watch) | 199 | Runs a command in an acme win on file changes. |
| <b>[vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 87 | Vim plugin to highlight syntax errors on save. |
| <b>[go-language-server](https://github.com/theia-ide/go-language-server) | 31 | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| <b>[gounit-vim](https://github.com/hexdigest/gounit-vim) | 23 | Vim plugin for generating Go tests based on the function's or method's signature. |
| <b>[theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 15 | Go language support for the Theia IDE. |
| <b>[Go Doc](https://github.com/msyrus/vscode-go-doc) | 6 | A Visual Studio Code extension for showing definition in output and generating go doc. |
| <b>[Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) | - | Go plugin for JetBrains IDEs. |
| <b>[goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) | - | This extension adds benchmark profiling support for the Go language to VS Code. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Generate Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gotests](https://github.com/cweill/gotests) | 4.6k | Generate Go tests from your source code. |
| <b>[genny](https://github.com/cheekybits/genny) | 1.7k | Elegant generics for Go. |
| <b>[xgen](https://github.com/xuri/xgen) | 242 | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| <b>[re2dfa](https://github.com/opennota/re2dfa) | 193 | Transform regular expressions into finite state machines and output Go source code. |
| <b>[hasgo](https://github.com/DylanMeeus/hasgo) | 128 | Generate Haskell inspired functions for your slices. |
| <b>[gonerics](https://github.com/bouk/gonerics) | 114 | Idiomatic Generics in Go. |
| <b>[gocontracts](https://github.com/Parquery/gocontracts) | 98 | brings design-by-contract to Go by synchronizing the code with the documentation. |
| <b>[gounit](https://github.com/hexdigest/gounit) | 70 | Generate Go tests using your own templates. |
| <b>[sqlgen](https://github.com/anqiansong/sqlgen) | 61 | Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN. |
| <b>[generic](https://github.com/usk81/generic) | 47 | flexible data type for Go. |
| <b>[options-gen](https://github.com/kazhuravlev/options-gen) | 41 | Functional options described by Dave Cheney's post "Functional options for friendly APIs". |
| <b>[godal](https://github.com/mafulong/godal) | 17 | Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm. |
| <b>[TOML-to-Go](https://xuri.me/toml-to-go) | - | Translates TOML into a Go type in the browser instantly. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-swagger](https://github.com/go-swagger/go-swagger) | 8.7k | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| <b>[go-callvis](https://github.com/TrueFurby/go-callvis) | 5.2k | Visualize call graph of your Go program using dot format. |
| <b>[OctoLinker](https://github.com/OctoLinker/browser-extension) | 5.2k | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| <b>[depth](https://github.com/KyleBanks/depth) | 828 | Visualize dependency trees of any package by analyzing imports. |
| <b>[richgo](https://github.com/kyoh86/richgo) | 795 | Enrich `go test` outputs with text decorations. |
| <b>[rts](https://github.com/galeone/rts) | 242 | RTS: response to struct. Generates Go structs from server responses. |
| <b>[godbg](https://github.com/tylerwince/godbg) | 196 | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| <b>[typex](https://github.com/dtgorski/typex) | 179 | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| <b>[roumon](https://github.com/becheran/roumon) | 144 | Monitor current state of all active goroutines via a command line interface. |
| <b>[gothanks](https://github.com/psampaz/gothanks) | 118 | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| <b>[colorgo](https://github.com/songgao/colorgo) | 112 | Wrapper around `go` command for colorized `go build` output. |
| <b>[go-james](https://github.com/pieterclaerhout/go-james) | 59 | Go project skeleton creator, builds and tests your projects without the manual setup. |
| <b>[igo](https://github.com/rocketlaunchr/igo) | 58 | An igo to go transpiler (new language features for Go language!) |
| <b>[go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 42 | Bash completion for go and wgo. |
| <b>[gotestdox](https://github.com/bitfield/gotestdox) | 40 | Show Go test results as readable sentences. |
| <b>[gomodrun](https://github.com/dustinblackman/gomodrun/) | 26 | Go tool that executes and caches binaries included in go.mod files. |
| <b>[generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 25 | A [Yeoman](https://yeoman.io) generator to get new Go projects started. |
| <b>[docs](https://github.com/go-oas/docs) | 22 | Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard. |
| <b>[modver](https://github.com/bobg/modver) | 8 | Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules. |
| <b>[textra](https://github.com/ravsii/textra) | 4 | Extract Go struct field names, types and tags for filtering and exporting. |
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
| <b>[kubernetes](https://github.com/kubernetes/kubernetes) | 99.0k | Container Cluster Manager from Google. |
| <b>[Moby](https://github.com/moby/moby) | 66.0k | Collaborative project for the container ecosystem to assemble container-based systems. |
| <b>[traefik](https://github.com/containous/traefik) | 43.0k | Reverse proxy and load balancer with support for multiple backends. |
| <b>[Gitea](https://github.com/go-gitea/gitea) | 37.0k | Fork of Gogs, entirely community driven. |
| <b>[Vegeta](https://github.com/tsenart/vegeta) | 21.0k | HTTP load testing tool and library. It's over 9000! |
| <b>[Hey](https://github.com/rakyll/hey) | 16.0k | Hey is a tiny program that sends some load to a web application. |
| <b>[Packer](https://github.com/mitchellh/packer) | 14.0k | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| <b>[Mizu](https://github.com/up9inc/mizu) | 9.2k | API traffic viewer for Kubernetes enabling you to view all API communication between microservices, multiprotocol support: HTTP1.1, HTTP/2, AMQP, Kafka, Redis. |
| <b>[webhook](https://github.com/adnanh/webhook) | 9.0k | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| <b>[GVM](https://github.com/moovweb/gvm) | 8.5k | GVM provides an interface to manage Go versions. |
| <b>[Ddosify](https://github.com/ddosify/ddosify) | 7.3k | High-performance load testing tool, written in Golang. |
| <b>[ko](https://github.com/google/ko) | 6.1k | Command line tool for building and deploying Go applications on Kubernetes |
| <b>[KubeVela](https://github.com/kubevela/kubevela) | 5.3k | Cloud native application delivery. |
| <b>[gaia](https://github.com/gaia-pipeline/gaia) | 5.1k | Build powerful pipelines in any programming language. |
| <b>[gox](https://github.com/mitchellh/gox) | 4.5k | Dead simple, no frills Go cross compile tool. |
| <b>[bombardier](https://github.com/codesenberg/bombardier) | 4.3k | Fast cross-platform HTTP benchmarking tool. |
| <b>[script](https://github.com/bitfield/script) | 4.1k | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| <b>[Pomerium](https://github.com/pomerium/pomerium) | 3.6k | Pomerium is an identity-aware access proxy. |
| <b>[bosun](https://github.com/bosun-monitor/bosun) | 3.4k | Time Series Alerting Framework. |
| <b>[kala](https://github.com/ajvb/kala) | 2.0k | Simplistic, modern, and performant job scheduler. |
| <b>[fac](https://github.com/mkchoi212/fac) | 1.8k | Command-line user interface to fix git merge conflicts. |
| <b>[goxc](https://github.com/laher/goxc) | 1.7k | build tool for Go, with a focus on cross-compiling and packaging. |
| <b>[s5cmd](https://github.com/peak/s5cmd) | 1.7k | Blazing fast S3 and local filesystem execution tool. |
| <b>[StatusOK](https://github.com/sanathp/statusok) | 1.6k | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| <b>[Fleet device management](https://github.com/fleetdm/fleet) | 1.4k | Lightweight, programmable telemetry for servers and workstations. |
| <b>[ghorg](https://github.com/gabrie30/ghorg) | 1.3k | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket. |
| <b>[go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 1.2k | Enable your Go applications to self update. |
| <b>[s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1.1k | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| <b>[uTask](https://github.com/ovh/utask) | 908 | Automation engine that models and executes business processes declared in yaml. |
| <b>[skm](https://github.com/TimothyYe/skm) | 868 | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| <b>[Scaleway-cli](https://github.com/scaleway/scaleway-cli) | 823 | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| <b>[kwatch](https://github.com/abahmed/kwatch) | 761 | Monitor & detect crashes in your Kubernetes(K8s) cluster instantly. |
| <b>[cassowary](https://github.com/rogerwelin/cassowary) | 671 | Modern cross-platform HTTP load-testing tool written in Go. |
| <b>[kool](https://github.com/kool-dev/kool) | 626 | Command line tool for managing Docker environments as an easy way. |
| <b>[aurora](https://github.com/xuri/aurora) | 577 | Cross-platform web-based Beanstalkd queue server console. |
| <b>[govvv](https://github.com/ahmetalpbalkan/govvv) | 536 | “go build” wrapper to easily add version information into Go binaries. |
| <b>[Pewpew](https://github.com/bengadbois/pewpew) | 379 | Flexible HTTP command line stress tester. |
| <b>[jcli](https://github.com/jenkins-zh/jenkins-cli) | 358 | Jenkins CLI allows you manage your Jenkins as an easy way. |
| <b>[gonative](https://github.com/inconshreveable/gonative) | 334 | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| <b>[trubka](https://github.com/xitonix/trubka) | 330 | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| <b>[Mora](https://github.com/emicklei/mora) | 311 | REST server for accessing MongoDB documents and meta data. |
| <b>[lstags](https://github.com/ivanilves/lstags) | 307 | Tool and API to sync Docker images across different registries. |
| <b>[Balerter](https://github.com/balerter/balerter) | 287 | A self-hosted script-based alerting manager. |
| <b>[easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 285 | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| <b>[manssh](https://github.com/xwjdsh/manssh) | 283 | manssh is a command line tool for managing your ssh alias config easily. |
| <b>[dogo](https://github.com/liudng/dogo) | 257 | Monitoring changes in the source file and automatically compile and run (restart). |
| <b>[terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 249 | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| <b>[gobrew](https://github.com/kevincobain2000/gobrew) | 245 | Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash. |
| <b>[godbg](https://github.com/sirnewton01/godbg) | 226 | Web-based gdb front-end application. |
| <b>[Blast](https://github.com/dave/blast) | 210 | A simple tool for API load testing and batch jobs. |
| <b>[abbreviate](https://github.com/dnnrly/abbreviate) | 200 | abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs. |
| <b>[kcli](https://github.com/cswank/kcli) | 194 | Command line tool for inspecting kafka topics/partitions/messages. |
| <b>[gobrew](https://github.com/cryptojuice/gobrew) | 193 | gobrew lets you easily switch between multiple versions of go. |
| <b>[s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 182 | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| <b>[ostent](https://github.com/ostrost/ostent) | 178 | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| <b>[grapes](https://github.com/yaronsumel/grapes) | 161 | Lightweight tool designed to distribute commands over ssh with ease. |
| <b>[winrm-cli](https://github.com/masterzen/winrm-cli) | 154 | Cli tool to remotely execute commands on Windows machines. |
| <b>[Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) | 148 | A go library and an executable that produces valid Dockerfiles using various input channels. |
| <b>[drone-scp](https://github.com/appleboy/drone-scp) | 120 | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| <b>[Mantil](https://github.com/mantil-io/mantil) | 102 | Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure. |
| <b>[go-furnace](https://github.com/go-furnace/go-furnace) | 97 | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| <b>[tf-profile](https://github.com/datarootsio/tf-profile) | 87 | Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations. |
| <b>[go-rocket-update](https://github.com/mouuff/go-rocket-update) | 82 | A simple way to make self updating Go applications - Supports Github and Gitlab. |
| <b>[Dropship](https://github.com/chrismckenzie/dropship) | 63 | Tool for deploying code via cdn. |
| <b>[drone-jenkins](https://github.com/appleboy/drone-jenkins) | 37 | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| <b>[docker-go-mingw](https://github.com/x1unix/docker-go-mingw) | 36 | Docker image for building Go binaries for Windows with MinGW toolchain. |
| <b>[Rodent](https://github.com/alouche/rodent) | 34 | Rodent helps you manage Go versions, projects and track dependencies. |
| <b>[awsenv](https://github.com/soniah/awsenv) | 33 | Small binary that loads Amazon (AWS) environment variables for a profile. |
| <b>[httpref](https://github.com/dnnrly/httpref) | 29 | httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. |
| <b>[lwc](https://github.com/timdp/lwc) | 28 | A live-updating version of the UNIX wc command. |
| <b>[DepCharge](https://github.com/centerorbit/depcharge) | 23 | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| <b>[wait-for](https://github.com/dnnrly/wait-for) | 14 | Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things. |
| <b>[aptly](https://github.com/smira/aptly) | 9 | aptly is a Debian repository management tool. |
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
| <b>[croc](https://github.com/schollz/croc) | 23.0k | Easily and securely send files or folders from one computer to another. |
| <b>[restic](https://github.com/restic/restic) | 20.0k | De-duplicating backup program. |
| <b>[Seaweed File System](https://github.com/chrislusf/seaweedfs) | 18.0k | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| <b>[Gor](https://github.com/buger/gor) | 17.0k | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| <b>[Comcast](https://github.com/tylertreat/Comcast) | 9.9k | Simulate bad network connections. |
| <b>[toxiproxy](https://github.com/shopify/toxiproxy) | 9.2k | Proxy to simulate network and system conditions for automated tests. |
| <b>[confd](https://github.com/kelseyhightower/confd) | 8.1k | Manage local application configuration files using templates and data from etcd or consul. |
| <b>[LiteIDE](https://github.com/visualfc/liteide) | 7.2k | LiteIDE is a simple, open source, cross-platform Go IDE. |
| <b>[drive](https://github.com/odeke-em/drive) | 6.5k | Google Drive client for the commandline. |
| <b>[nes](https://github.com/fogleman/nes) | 5.2k | Nintendo Entertainment System (NES) emulator written in Go. |
| <b>[scc](https://github.com/boyter/scc) | 4.8k | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| <b>[Duplicacy](https://github.com/gilbertchen/duplicacy) | 4.7k | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| <b>[blocky](https://github.com/0xERR0R/blocky) | 2.7k | Fast and lightweight DNS proxy as ad-blocker for local network with many features. |
| <b>[myLG](https://github.com/mehrdadrad/mylg) | 2.6k | Command Line Network Diagnostic tool written in Go. |
| <b>[GoBoy](https://github.com/Humpheh/goboy) | 2.5k | Nintendo Game Boy Color emulator written in Go. |
| <b>[Stack Up](https://github.com/pressly/sup) | 2.4k | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| <b>[lgo](https://github.com/yunabe/lgo) | 2.3k | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| <b>[Circuit](https://github.com/gocircuit/circuit) | 2.0k | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| <b>[Documize](https://github.com/documize/community) | 1.9k | Modern wiki software that integrates data from SaaS tools. |
| <b>[snap](https://github.com/intelsdi-x/snap) | 1.8k | Powerful telemetry framework. |
| <b>[borg](https://github.com/crufter/borg) | 1.6k | Terminal based search engine for bash snippets. |
| <b>[Plik](https://github.com/root-gg/plik) | 1.2k | Plik is a temporary file upload system (Wetransfer like) in Go. |
| <b>[shell2http](https://github.com/msoap/shell2http) | 1.1k | Executing shell commands via http server (for prototyping or remote control). |
| <b>[vFlow](https://github.com/VerizonDigital/vflow) | 989 | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| <b>[peg](https://github.com/pointlander/peg) | 915 | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| <b>[Go Package Store](https://github.com/shurcooL/Go-Package-Store) | 896 | App that displays updates for the Go packages in your GOPATH. |
| <b>[portal](https://github.com/SpatiumPortae/portal) | 867 | Portal is a quick and easy command-line file transfer utility from any computer to another. |
| <b>[Leaps](https://github.com/jeffail/leaps) | 735 | Pair programming service using Operational Transforms. |
| <b>[gfile](https://github.com/Antonito/gfile) | 704 | Securely transfer files between two computers, without any third party, over WebRTC. |
| <b>[Gokapi](https://github.com/Forceu/gokapi) | 688 | Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload. |
| <b>[Guora](https://github.com/meloalright/guora) | 653 | A self-hosted Quora like web application written in Go. |
| <b>[Gebug](https://github.com/moshebe/gebug) | 619 | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| <b>[sake](https://github.com/alajmo/sake) | 601 | sake is a command runner for local and remote hosts. |
| <b>[gocc](https://github.com/goccmack/gocc) | 569 | Gocc is a compiler kit for Go written in Go. |
| <b>[mockingjay](https://github.com/quii/mockingjay-server) | 541 | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| <b>[go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 455 | Video streaming torrent client. |
| <b>[woke](https://github.com/get-woke/woke) | 376 | Detect non-inclusive language in your source code. |
| <b>[ipe](https://github.com/dimiro1/ipe) | 366 | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| <b>[ide](https://github.com/thestrukture/ide) | 352 | Browser accessible IDE. Designed for Go with Go. |
| <b>[tcpprobe](https://github.com/mehrdadrad/tcpprobe) | 336 | TCP tool for network performance and path monitoring, including socket statistics. |
| <b>[wellington](https://github.com/wellington/wellington) | 302 | Sass project management tool, extends the language with sprite functions (like Compass). |
| <b>[Cherry](https://github.com/rafael-santiago/cherry) | 288 | Tiny webchat server in Go. |
| <b>[Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) | 252 | 🐮 cowsay is reborn. for a New Era. |
| <b>[hotswap](https://github.com/edwingeng/hotswap) | 232 | A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure. |
| <b>[tcpdog](https://github.com/mehrdadrad/tcpdog) | 227 | eBPF based TCP observability. |
| <b>[joincap](https://github.com/assafmo/joincap) | 188 | Command-line utility for merging multiple pcap files together. |
| <b>[Orbit](https://github.com/gulien/orbit) | 175 | A simple tool for running commands and generating files from templates. |
| <b>[vaku](https://github.com/lingrino/vaku) | 148 | CLI & API for folder-based functions in Vault like copy, move, and search. |
| <b>[crawley](https://github.com/s0rg/crawley) | 143 | Web scraper/crawler for cli. |
| <b>[stew](https://github.com/marwanhawari/stew) | 115 | An independent package manager for compiled binaries. |
| <b>[dp](https://github.com/scryinfo/dp) | 84 | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| <b>[boxed](https://github.com/tejo/boxed) | 78 | Dropbox based blog engine. |
| <b>[term-quiz](https://github.com/crazcalm/term-quiz) | 24 | Quizzes for your terminal. |
| <b>[naclpipe](https://github.com/unix4fun/naclpipe) | 23 | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| <b>[Snitch](https://github.com/lucasgomide/snitch) | 16 | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| <b>[GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 13 | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |
| <b>[hoofli](https://github.com/dnnrly/hoofli) | 6 | Generate PlantUML diagrams from Chrome or Firefox network inspections. |
| <b>[protoncheck](https://github.com/servusdei2018/protoncheck) | 4 | ProtonMail module for waybar/polybar/yabar/i3blocks. |
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
| <b>[go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 1.9k | Go web framework benchmark. |
| <b>[go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1.6k | Go HTTP request router benchmark and comparison. |
| <b>[go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1.4k | Benchmarks of Go serialization methods. |
| <b>[skynet](https://github.com/atemerev/skynet) | 1000 | Skynet 1M threads microbenchmark. |
| <b>[speedtest-resize](https://github.com/fawick/speedtest-resize) | 232 | Compare various Image resize algorithms for the Go language. |
| <b>[go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 147 | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| <b>[gospeed](https://github.com/feyeleanor/GoSpeed) | 111 | Go micro-benchmarks for calculating the speed of language constructs. |
| <b>[autobench](https://github.com/davecheney/autobench) | 96 | Framework to compare the performance between different Go versions. |
| <b>[golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 64 | Collection of benchmarks for popular Go database/SQL utilities. |
| <b>[gocostmodel](https://github.com/PuerkitoBio/gocostmodel) | 60 | Benchmarks of common basic operations for the Go language. |
| <b>[go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) | 27 | benchmarks for machine learning inference in Go. |
| <b>[go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 26 | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| <b>[kvbench](https://github.com/jimrobinson/kvbench) | 25 | Key/Value database benchmark. |
| <b>[go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) | 8 | Go JSON benchmark. |


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
| <b>[GoBooks](https://github.com/dariubs/GoBooks) | 14.0k | A curated list of Go books. |
| <b>[The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 9.2k | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| <b>[Go AST Book (Chinese)](https://github.com/chai2010/go-ast-book) | 5.0k | A book focusing on Go `go/*` packages. |
| <b>[Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) | 3.1k | Learn how to write webapps without a framework in Go. |
| <b>[Go Succinctly](https://github.com/thedevsir/gosuccinctly) | 23 | in Persian. |
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
| <b>[gophers](https://github.com/egonelbre/gophers) | 3.2k | Free gophers. |
| <b>[Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) | 3.0k | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| <b>[gophers](https://github.com/ashleymcnamara/gophers) | 2.8k | Gopher artworks by Ashley McNamara. |
| <b>[gopherize.me](https://github.com/matryer/gopherize.me) | 642 | Gopherize yourself. |
| <b>[gophericons](https://github.com/shalakhin/gophericons) | 609 | 34 gopher images for Go developers community |
| <b>[gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 558 | gopher stickers |
| <b>[gophers](https://github.com/sillecelik/go-gopher) | 118 | Gopher amigurumi toy pattern. |
| <b>[gopher-logos](https://github.com/GolangUA/gopher-logos) | 112 | adorable gopher logos. |
| <b>[Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 64 | Go gopher Vector Data [.ai, .svg]. |
| <b>[gophers](https://github.com/rogeralsing/gophers) | 58 | random gopher graphics. |
| <b>[gophers](https://github.com/scraly/gophers) | 22 | Gophers by Aurélie Vache. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Meetups


| Repo | Stars | Description |
| :------ | :------ | :------ |
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
| <b>[CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md) | 27.0k | CockroachDB - the open source, cloud-native distributed SQL database. |
| <b>[Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst) | 15.0k | Hyperledger Fabric is an enterprise-grade permissioned distributed ledger framework for developing solutions and applications. Its modular and versatile design satisfies a broad range of industry use cases. It offers a unique approach to consensus that enables performance at scale while preserving privacy. |
| <b>[Uber](https://github.com/uber-go/guide/blob/master/style.md) | 14.0k | The Uber Go Style Guide. |
| <b>[Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification) | 2.9k | Autonomous (self-hosted) BitTorrent DHT search engine suite. |
| <b>[bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) | 1.4k | 🏆 Opinionated Styleguide for the Go language |
| <b>[Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md) | 315 | Playbook da linguagem Go |
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
| <b>[Go Projects](https://github.com/golang/go/wiki/Projects) | 112.0k | List of projects on the Go community wiki. |
| <b>[awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 30.0k | List of other amazingly awesome lists. |
| <b>[Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) | 26.0k | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| <b>[Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) | 486 | A curated list of awesome golang workshops. |
| <b>[golang-graphics](https://github.com/mholt/golang-graphics) | 139 | Collection of Go images, graphics, and art. |
| <b>[gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 40 | Collection of Go projects that needs help. Good place to start your open-source way in Go. |
| <b>[awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) | 21 | Parse awesome-go README file and generate a new README file with repo info. |
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
| <b>[Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) | 42.0k | Golang ebook intro how to build a web app with golang. |
| <b>[go-patterns](https://github.com/tmrts/go-patterns) | 22.0k | Curated list of Go design patterns, recipes and idioms. |
| <b>[Learn Go with TDD](https://github.com/quii/learn-go-with-tests) | 20.0k | Learn Go with test-driven development. |
| <b>[Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) | 17.0k | Learn Go with thousands of examples, exercises, and quizzes. |
| <b>[Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) | 7.6k | Go's reference card. |
| <b>[go-clean-template](https://github.com/evrone/go-clean-template) | 5.2k | Clean Architecture template for Golang services. |
| <b>[Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 3.8k | Examples of Golang compared to Node.js for learning. |
| <b>[Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) | 1.6k | A little e-book on Ethereum Development with Go. |
| <b>[Working with Go](https://github.com/mkaz/working-with-go) | 1.2k | Intro to go for experienced programmers. |
| <b>[goapp](https://github.com/bnkamalesh/goapp) | 623 | An opinionated guideline to structure & develop a Go web application/service. |
| <b>[Go in 7 days](https://github.com/harrytran103/7_days_of_go) | 121 | Learn everything about Go in 7 days (from a Nodejs developer). |
| <b>[Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) | 102 | Collection of programming design patterns implemented in Go. |
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

