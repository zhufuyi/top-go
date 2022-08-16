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


<br><br>

---

<br><br>

## Audio and Music

_Libraries for manipulating audio._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Oto](https://github.com/hajimehoshi/oto) | 1000 | A low-level library to play sound on multiple platforms. |
| <b>[PortAudio](https://github.com/gordonklaus/portaudio) | 525 | Go bindings for the PortAudio audio I/O library. |
| <b>[music-theory](https://github.com/go-music-theory/music-theory) | 404 | Music theory models in Go. |
| <b>[id3v2](https://github.com/bogem/id3v2) | 256 | ID3 decoding and encoding library for Go. |
| <b>[GoAudio](https://github.com/DylanMeeus/GoAudio) | 242 | Native Go Audio Processing Library. |
| <b>[flac](https://github.com/mewkiz/flac) | 218 | Native Go FLAC encoder/decoder with support for FLAC streams. |
| <b>[malgo](https://github.com/gen2brain/malgo) | 187 | Mini audio library. |
| <b>[gaad](https://github.com/Comcast/gaad) | 104 | Native Go AAC bitstream parser. |
| <b>[minimp3](https://github.com/tosone/minimp3) | 85 | Lightweight MP3 decoder library. |
| <b>[gosamplerate](https://github.com/dh1tw/gosamplerate) | 18 | libsamplerate bindings for go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Authentication and OAuth

_Libraries for implementing authentications schemes._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[casbin](https://github.com/hsluoyz/casbin) | 13.0k | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| <b>[oauth2](https://github.com/golang/oauth2) | 4.3k | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| <b>[goth](https://github.com/markbates/goth) | 3.8k | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| <b>[keto](https://github.com/ory/keto) | 3.5k | Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models. |
| <b>[authboss](https://github.com/volatiletech/authboss) | 3.1k | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| <b>[go-jose](https://github.com/square/go-jose) | 1.9k | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| <b>[loginsrv](https://github.com/tarent/loginsrv) | 1.9k | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| <b>[osin](https://github.com/openshift/osin) | 1.8k | Golang OAuth2 server library. |
| <b>[gologin](https://github.com/dghubble/gologin) | 1.5k | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| <b>[gorbac](https://github.com/mikespook/gorbac) | 1.3k | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| <b>[scs](https://github.com/alexedwards/scs) | 1.2k | Session Manager for HTTP servers. |
| <b>[paseto](https://github.com/o1egl/paseto) | 621 | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| <b>[jwt](https://github.com/cristalhq/jwt) | 560 | Safe, simple and fast JSON Web Tokens for Go. |
| <b>[permissions2](https://github.com/xyproto/permissions2) | 462 | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| <b>[go-guardian](https://github.com/shaj13/go-guardian) | 388 | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| <b>[jwt](https://github.com/pascaldekloe/jwt) | 291 | Lightweight JSON Web Token (JWT) library. |
| <b>[jeff](https://github.com/abraithwaite/jeff) | 240 | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| <b>[jwt-auth](https://github.com/adam-hanna/jwt-auth) | 218 | JWT middleware for Golang http servers with many configuration options. |
| <b>[otpgen](https://github.com/grijul/otpgen) | 121 | Library to generate TOTP/HOTP codes. |
| <b>[sessionup](https://github.com/swithek/sessionup) | 118 | Simple, yet effective HTTP session management and identification package. |
| <b>[session](https://github.com/icza/session) | 107 | Go session management for web servers (including support for Google App Engine - GAE). |
| <b>[sjwt](https://github.com/brianvoe/sjwt) | 99 | Simple jwt generator and parser. |
| <b>[rbac](https://github.com/zpatrick/rbac) | 98 | Minimalistic RBAC package for Go applications. |
| <b>[sessions](https://github.com/adam-hanna/sessions) | 66 | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| <b>[securecookie](https://github.com/chmike/securecookie) | 60 | Efficient secure cookie encoding/decoding. |
| <b>[go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) | 51 | Golang library for providing a canonical representation of email address. |
| <b>[branca](https://github.com/essentialkaos/branca) | 42 | branca token [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+. |
| <b>[otpgo](https://github.com/jltorresm/otpgo) | 39 | Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. |
| <b>[scope](https://github.com/SonicRoshan/scope) | 21 | Easily Manage OAuth2 Scopes In Go. |
| <b>[cookiestxt](https://github.com/mengzhuo/cookiestxt) | 13 | provides parser of cookies.txt file format. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Blockchain

_Tools for building blockchains._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-ethereum](https://github.com/ethereum/go-ethereum) | 39.0k | Official Go implementation of the Ethereum protocol. |
| <b>[tendermint](https://github.com/tendermint/tendermint) | 5.1k | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| <b>[cosmos-sdk](https://github.com/cosmos/cosmos-sdk) | 4.3k | A Framework for Building Public Blockchains in the Cosmos Ecosystem. |
| <b>[solana-go](https://github.com/gagliardetto/solana-go) | 353 | Go library to interface with Solana JSON RPC and WebSocket interfaces. |
| <b>[gossamer](https://github.com/ChainSafe/gossamer) | 346 | A Go implementation of the Polkadot Host. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Bot Building

_Libraries for building and working with bots._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) | 3.9k | Simple and clean Telegram bot client. |
| <b>[olivia](https://github.com/olivia-ai/olivia) | 3.3k | A chatbot built with an artificial neural network. |
| <b>[telebot](https://github.com/tucnak/telebot) | 2.7k | Telegram bot framework written in Go. |
| <b>[Kelp](https://github.com/stellar/kelp) | 913 | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| <b>[Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) | 811 | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| <b>[go-chat-bot](https://github.com/go-chat-bot/bot) | 754 | IRC, Slack & Telegram bot written in Go. |
| <b>[slacker](https://github.com/shomali11/slacker) | 682 | Easy to use framework to create Slack bots. |
| <b>[tbot](https://github.com/yanzay/tbot) | 328 | Telegram bot server with API similar to net/http. |
| <b>[wayback](https://github.com/wabarc/wayback) | 300 | A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages. |
| <b>[go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 250 | Library to write bots for twitch.tv chat |
| <b>[go-sarah](https://github.com/oklahomer/go-sarah) | 245 | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| <b>[Tenyks](https://github.com/kyleterry/tenyks) | 173 | Service oriented IRC bot using Redis and JSON for messaging. |
| <b>[echotron](https://github.com/NicoNex/echotron) | 167 | An elegant and concurrent library for Telegram Bots in Go. |
| <b>[hanu](https://github.com/sbstjn/hanu) | 140 | Framework for writing Slack bots. |
| <b>[go-tgbot](https://github.com/olebedev/go-tgbot) | 113 | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| <b>[slack-bot](https://github.com/innogames/slack-bot) | 107 | Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github... |
| <b>[telego](https://github.com/mymmrac/telego) | 90 | Telegram Bot API library for Golang with full one-to-one API implementation. |
| <b>[margelet](https://github.com/zhulik/margelet) | 74 | Framework for building Telegram bots. |
| <b>[larry](https://github.com/ezeoleaf/larry) | 71 | Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go. |
| <b>[ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 66 | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| <b>[slackscot](https://github.com/alexandre-normand/slackscot) | 52 | Another framework for building Slack bots. |
| <b>[govkbot](https://github.com/nikepan/govkbot) | 39 | Simple Go [VK](https://vk.com) bot library. |
| <b>[micha](https://github.com/onrik/micha) | 21 | Go Library for Telegram bot api. |
| <b>[teleterm](https://github.com/alfiankan/teleterm) | 11 | Telegram Bot Exec Terminal Command. |
| <b>[go-joe](https://joe-bot.net) | - | A general-purpose bot library inspired by Hubot but written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Build Automation

_Libraries and tools helping with build automation._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Task](https://github.com/go-task/task) | 5.6k | simple "Make" alternative. |
| <b>[realize](https://github.com/tockins/realize) | 4.3k | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| <b>[mage](https://github.com/magefile/mage) | 3.1k | Mage is a make/rake-like build tool using Go. |
| <b>[mmake](https://github.com/tj/mmake) | 1.6k | Modern Make. |
| <b>[goyek](https://github.com/goyek/goyek) | 303 | Create build pipelines in Go. |
| <b>[taskctl](https://github.com/taskctl/taskctl) | 206 | Concurrent task runner. |
| <b>[1build](https://github.com/gopinath-langote/1build) | 176 | Command line tool to frictionlessly manage project-specific commands. |
| <b>[gaper](https://github.com/maxcnunes/gaper) | 55 | Builds and restarts a Go project when it crashes or some watched file changes. |
| <b>[anko](https://github.com/GuilhermeCaruso/anko) | 26 | Simple application watcher for multiple programming languages. |
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
| <b>[termui](https://github.com/gizak/termui) | 12.0k | Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). |
| <b>[gocui](https://github.com/jroimartin/gocui) | 8.4k | Minimalist Go library aimed at creating Console User Interfaces. |
| <b>[go-prompt](https://github.com/c-bata/go-prompt) | 4.6k | Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). |
| <b>[termbox-go](https://github.com/nsf/termbox-go) | 4.4k | Termbox is a library for creating cross-platform text-based interfaces. |
| <b>[pterm](https://github.com/pterm/pterm) | 2.9k | A library to beautify console output on every platform with many combinable components. |
| <b>[progressbar](https://github.com/schollz/progressbar) | 2.7k | Basic thread-safe progress bar that works in every OS. |
| <b>[asciigraph](https://github.com/guptarohit/asciigraph) | 2.0k | Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. |
| <b>[termdash](https://github.com/mum4k/termdash) | 2.0k | Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). |
| <b>[spinner](https://github.com/briandowns/spinner) | 1.9k | Go package to easily provide a terminal spinner with options. |
| <b>[uiprogress](https://github.com/gosuri/uiprogress) | 1.9k | Flexible library to render progress bars in terminal applications. |
| <b>[mpb](https://github.com/vbauerster/mpb) | 1.8k | Multi progress bar for terminal applications. |
| <b>[uilive](https://github.com/gosuri/uilive) | 1.5k | Library for updating terminal output in realtime. |
| <b>[aurora](https://github.com/logrusorgru/aurora) | 1.2k | ANSI terminal colors that supports fmt.Printf/Sprintf. |
| <b>[gookit/color](https://github.com/gookit/color) | 1.2k | Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. |
| <b>[termenv](https://github.com/muesli/termenv) | 1.1k | Advanced ANSI style & color support for your terminal applications. |
| <b>[uitable](https://github.com/gosuri/uitable) | 652 | Library to improve readability in terminal apps using tabular data. |
| <b>[go-isatty](https://github.com/mattn/go-isatty) | 633 | isatty for golang. |
| <b>[go-colorable](https://github.com/mattn/go-colorable) | 630 | Colorable writer for windows. |
| <b>[gommon/color](https://github.com/labstack/gommon/tree/master/color) | 459 | Style terminal text. |
| <b>[chalk](https://github.com/ttacon/chalk) | 404 | Intuitive package for prettifying terminal/console output. |
| <b>[simpletable](https://github.com/alexeyco/simpletable) | 378 | Simple tables in terminal with Go. |
| <b>[yacspin](https://github.com/theckman/yacspin) | 357 | Yet Another CLi Spinner package, for working with terminal spinners. |
| <b>[tabby](https://github.com/cheynewallace/tabby) | 320 | A tiny library for super simple Golang tables. |
| <b>[box-cli-maker](https://github.com/Delta456/box-cli-maker) | 228 | Make Highly Customized Boxes for your CLI. |
| <b>[go-colortext](https://github.com/daviddengcn/go-colortext) | 211 | Go library for color output in terminals. |
| <b>[cfmt](https://github.com/mingrammer/cfmt) | 84 | Contextual fmt inspired by bootstrap color classes. |
| <b>[tabular](https://github.com/InVisionApp/tabular) | 64 | Print ASCII tables from command line utilities without the need to pass large sets of data to the API. |
| <b>[cfmt](https://github.com/i582/cfmt) | 46 | Simple and convenient formatted stylized output fully compatible with fmt library. |
| <b>[ctc](https://github.com/wzshiming/ctc) | 39 | The non-invasive cross-platform terminal color library does not need to modify the Print method. |
| <b>[table](https://github.com/tomlazar/table) | 32 | Small library for terminal color based tables . |
| <b>[marker](https://github.com/cyucelen/marker) | 31 | Easiest way to match and mark strings for colorful terminal outputs. |
| <b>[colourize](https://github.com/TreyBastian/colourize) | 25 | Go library for ANSI colour text in terminals. |
| <b>[go-ataman](https://github.com/workanator/go-ataman) | 11 | Go library for rendering ANSI colored text templates in terminals. |
| <b>[crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) | 3 | Dynamic configuration file templating tool for kubernetes manifest or general configuration files. |


<br>

[👆back to top](#catalogue-list)


<br>

### Standard CLI

_Libraries for building standard or basic Command Line applications._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cobra](https://github.com/spf13/cobra) | 28.0k | Commander for modern Go CLI interactions. |
| <b>[urfave/cli](https://github.com/urfave/cli) | 19.0k | Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). |
| <b>[elvish](https://github.com/elves/elvish) | 4.8k | An expressive programming language and a versatile interactive shell. |
| <b>[kingpin](https://github.com/alecthomas/kingpin) | 3.2k | Command line and flag parser supporting sub commands (superseded by `kong`; see below). |
| <b>[Dnote](https://github.com/dnote/dnote) | 2.3k | A simple command line notebook with multi-device sync. |
| <b>[go-flags](https://github.com/jessevdk/go-flags) | 2.3k | go command line option parser. |
| <b>[pflag](https://github.com/spf13/pflag) | 1.9k | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. |
| <b>[mitchellh/cli](https://github.com/mitchellh/cli) | 1.6k | Go library for implementing command-line interfaces. |
| <b>[go-arg](https://github.com/alexflint/go-arg) | 1.4k | Struct-based argument parsing in Go. |
| <b>[ops](https://github.com/nanovms/ops) | 1000 | Unikernel Builder/Orchestrator. |
| <b>[liner](https://github.com/peterh/liner) | 909 | Go readline-like library for command-line interfaces. |
| <b>[complete](https://github.com/posener/complete) | 837 | Write bash completions in Go + Go command bash completion. |
| <b>[mow.cli](https://github.com/jawher/mow.cli) | 820 | Go library for building CLI applications with sophisticated flag and argument parsing and validation. |
| <b>[flaggy](https://github.com/integrii/flaggy) | 805 | A robust and idiomatic flags package with excellent subcommand support. |
| <b>[cli](https://github.com/mkideal/cli) | 665 | Feature-rich and easy to use command-line package based on golang struct tags. |
| <b>[argparse](https://github.com/akamensky/argparse) | 443 | Command line argument parser inspired by Python's argparse module. |
| <b>[climax](https://github.com/tucnak/climax) | 198 | Alternative CLI with "human face", in spirit of Go command. |
| <b>[hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) | 175 | cli application framework with auto configuration and dependency injection. |
| <b>[wmenu](https://github.com/dixonwille/wmenu) | 168 | Easy to use menu structure for cli applications that prompts users to make choices. |
| <b>[commandeer](https://github.com/jaffee/commandeer) | 158 | Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. |
| <b>[sflags](https://github.com/octago/sflags) | 140 | Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. |
| <b>[flag](https://github.com/cosiner/flag) | 121 | Simple but powerful command line option parsing library for Go supporting subcommand. |
| <b>[clîr](https://github.com/leaanthony/clir) | 120 | A Simple and Clear CLI library. Dependency free. |
| <b>[job](https://github.com/liujianping/job) | 118 | JOB, make your short-term command as a long-term job. |
| <b>[ukautz/clif](https://github.com/ukautz/clif) | 115 | Small command line interface framework. |
| <b>[cli](https://github.com/teris-io/cli) | 113 | Simple and complete API for building command line interfaces in Go. |
| <b>[cmdr](https://github.com/hedzr/cmdr) | 112 | A POSIX/GNU style, getopt-like command-line UI Go library. |
| <b>[env](https://github.com/codingconcepts/env) | 92 | Tag-based environment configuration for structs. |
| <b>[carapace-bin](https://github.com/rsteube/carapace-bin) | 67 | Multi-shell multi-command argument completer. |
| <b>[gocmd](https://github.com/devfacet/gocmd) | 57 | Go library for building command line applications. |
| <b>[wlog](https://github.com/dixonwille/wlog) | 57 | Simple logging interface that supports cross-platform color and concurrency. |
| <b>[acmd](https://github.com/cristalhq/acmd) | 48 | Simple, useful and opinionated CLI package in Go. |
| <b>[strumt](https://github.com/antham/strumt) | 46 | Library to create prompt chain. |
| <b>[carapace](https://github.com/rsteube/carapace) | 44 | Command argument completion generator for spf13/cobra. |
| <b>[go-getoptions](https://github.com/DavidGamba/go-getoptions) | 43 | Go option parser inspired on the flexibility of Perl’s GetOpt::Long. |
| <b>[flagvar](https://github.com/sgreben/flagvar) | 39 | A collection of flag argument types for Go's standard `flag` package. |
| <b>[argv](https://github.com/cosiner/argv) | 33 | Go library to split command line string as arguments array using the bash syntax. |
| <b>[cmd](https://github.com/posener/cmd) | 33 | Extends the standard `flag` package to support sub commands and more in idiomatic way. |
| <b>[go-commander](https://github.com/yitsushi/go-commander) | 29 | Go library to simplify CLI workflow. |
| <b>[command-chain](https://github.com/rainu/go-command-chain) | 25 | A go library for configure and run command chains - such like pipelining in unix shells. |
| <b>[sand](https://github.com/Zaba505/sand) | 18 | Simple API for creating interpreters and so much more. |
| <b>[go-andotp](https://github.com/grijul/go-andotp) | 17 | A CLI program to encrypt/decrypt [andOTP](https://github.com/andOTP/andOTP) files. Can be used as library as well. |
| <b>[ts](https://github.com/liujianping/ts) | 14 | Timestamp convert & compare tool. |
| <b>[carapace-spec](https://github.com/rsteube/carapace-spec) | 2 | Define simple completions using a spec file. |
| <b>[subcmd](https://github.com/bobg/subcmd) | 2 | Another approach to parsing and running subcommands. Works alongside the standard `flag` package. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Configuration

_Libraries for configuration parsing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[viper](https://github.com/spf13/viper) | 20.0k | Go configuration with fangs. |
| <b>[godotenv](https://github.com/joho/godotenv) | 5.2k | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| <b>[kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) | 4.2k | Go library for managing configuration data from environment variables. |
| <b>[ini](https://github.com/go-ini/ini) | 3.0k | Go package to read and write INI files. |
| <b>[env](https://github.com/caarlos0/env) | 2.6k | Parse environment variables to Go structs (with defaults). |
| <b>[koanf](https://github.com/knadh/koanf) | 1.1k | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| <b>[kong](https://github.com/alecthomas/kong) | 1000 | Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (succesor to `kingpin`). |
| <b>[cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 696 | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| <b>[konfig](https://github.com/lalamove/konfig) | 626 | Composable, observable and performant config handling for Go for the distributed processing era. |
| <b>[confita](https://github.com/heetch/confita) | 451 | Load configuration in cascade from multiple backends into a struct. |
| <b>[aconfig](https://github.com/cristalhq/aconfig) | 386 | Simple, useful and opinionated config loader. |
| <b>[gookit/config](https://github.com/gookit/config) | 377 | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| <b>[config](https://github.com/JeremyLoy/config) | 314 | Cloud native application configuration. Bind ENV to structs in only two lines. |
| <b>[GoLobby/Config](https://github.com/golobby/config) | 288 | GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language. |
| <b>[hjson](https://github.com/hjson/hjson-go) | 274 | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| <b>[store](https://github.com/tucnak/store) | 261 | Lightweight configuration manager for Go. |
| <b>[xdg](https://github.com/adrg/xdg) | 252 | Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). |
| <b>[config](https://github.com/olebedev/config) | 250 | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| <b>[fig](https://github.com/kkyr/fig) | 224 | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| <b>[envconfig](https://github.com/vrischmann/envconfig) | 222 | Read your configuration from environment variables. |
| <b>[joshbetz/config](https://github.com/joshbetz/config) | 212 | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| <b>[gcfg](https://github.com/go-gcfg/gcfg) | 160 | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| <b>[harvester](https://github.com/beatlabs/harvester) | 113 | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| <b>[onion](https://github.com/goraz/onion) | 106 | Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP. |
| <b>[envcfg](https://github.com/tomazk/envcfg) | 98 | Un-marshaling environment variables to Go structs. |
| <b>[envh](https://github.com/antham/envh) | 95 | Helpers to manage environment variables. |
| <b>[configuro](https://github.com/sherifabdlnaby/configuro) | 82 | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| <b>[configuration](https://github.com/BoRuDar/configuration) | 76 | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| <b>[xdg](https://github.com/OpenPeeDeeP/xdg) | 69 | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| <b>[gofigure](https://github.com/ian-kent/gofigure) | 64 | Go application configuration made easy. |
| <b>[configure](https://github.com/paked/configure) | 56 | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| <b>[go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 50 | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| <b>[uConfig](https://github.com/omeid/uconfig) | 50 | Lightweight, zero-dependency, and extendable configuration management. |
| <b>[hocon](https://github.com/gurkankaymak/hocon) | 45 | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| <b>[gone/jconf](https://github.com/One-com/gone/tree/master/jconf) | 40 | Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization. |
| <b>[go-up](https://github.com/ufoscout/go-up) | 37 | A simple configuration library with recursive placeholders resolution and no magic. |
| <b>[ingo](https://github.com/schachmat/ingo) | 36 | Flags persisted in an ini-like config file. |
| <b>[mini](https://github.com/sasbury/mini) | 31 | Golang package for parsing ini-style configuration files. |
| <b>[genv](https://github.com/sakirsensoy/genv) | 28 | Read environment variables easily with dotenv support. |
| <b>[conflate](https://github.com/the4thamigo-uk/conflate) | 25 | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| <b>[config](https://github.com/num30/config) | 23 | configure you app using file, environment variables, or flags in two lines of code |
| <b>[env](https://github.com/junk1tm/env) | 22 | A lightweight package for loading environment variables into structs. |
| <b>[go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 14 | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| <b>[envconf](https://github.com/ian-kent/envconf) | 10 | Configuration from environment. |
| <b>[ini](https://github.com/wlevene/ini) | 9 | INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file. |
| <b>[nasermirzaei89/env](https://github.com/nasermirzaei89/env) | 8 | Simple useful package for read environment variables. |
| <b>[go-ini](https://github.com/subpop/go-ini) | 7 | A Go package that marshals and unmarshals INI-files. |
| <b>[typenv](https://github.com/diegomarangoni/typenv) | 7 | Minimalistic, zero dependency, typed environment variables library. |
| <b>[swap](https://github.com/oblq/swap) | 6 | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| <b>[piper](https://github.com/Yiling-J/piper) | 5 | Viper wrapper with config inheritance and key generation. |
| <b>[go-conf](https://github.com/ThomasObenaus/go-conf) | 4 | Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters. |
| <b>[gonfig](https://github.com/milad-abbasi/gonfig) | 4 | Tag-based configuration parser which loads values from different providers into typesafe struct. |
| <b>[nfigure](https://github.com/muir/nfigure) | 1 | Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML |
| <b>[goConfig](https://github.com/crgimenes/goConfig) | 0 | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Continuous Integration

_Tools for help with continuous integration._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[drone](https://github.com/drone/drone) | 26.0k | Drone is a Continuous Integration platform built on Docker, written in Go. |
| <b>[CDS](https://github.com/ovh/cds) | 3.9k | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| <b>[goveralls](https://github.com/mattn/goveralls) | 735 | Go integration for Coveralls.io continuous code coverage tracking system. |
| <b>[gotestfmt](https://github.com/haveyoudebuggedit/gotestfmt) | 230 | go test output for humans. |
| <b>[overalls](https://github.com/go-playground/overalls) | 111 | Multi-Package go project coverprofile for tools like goveralls. |
| <b>[duci](https://github.com/duck8823/duci) | 74 | A simple ci server no needs domain specific languages. |
| <b>[gomason](https://github.com/nikogura/gomason) | 53 | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| <b>[roveralls](https://github.com/LawrenceWoodman/roveralls) | 17 | Recursive coverage testing tool. |
| <b>[go-fuzz-action](https://github.com/jidicula/go-fuzz-action) | 2 | Use Go 1.18's built-in fuzz testing in GitHub Actions. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## CSS Preprocessors

_Libraries for preprocessing CSS files._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gcss](https://github.com/yosssi/gcss) | 457 | Pure Go CSS Preprocessor. |
| <b>[go-libsass](https://github.com/wellington/go-libsass) | 188 | Go wrapper to the 100% Sass compatible libsass project. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Data Structures and Algorithms


<br>

### Bit-packing and Compression


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[roaring](https://github.com/RoaringBitmap/roaring) | 1.7k | Go package implementing compressed bitsets. |
| <b>[binpacker](https://github.com/zhuangsirui/binpacker) | 190 | Binary packer and unpacker helps user build custom binary stream. |
| <b>[bit](https://github.com/yourbasic/bit) | 127 | Golang set data structure with bonus bit-twiddling functions. |
| <b>[crunch](https://github.com/superwhiskers/crunch) | 59 | Go package implementing buffers for handling various datatypes easily. |
| <b>[go-ef](https://github.com/amallia/go-ef) | 21 | A Go implementation of the Elias-Fano encoding. |
| <b>[bingo](https://github.com/iancmcc/bingo) | 8 | Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes. |


<br>

[👆back to top](#catalogue-list)


<br>

### Bit Sets


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bitset](https://github.com/bits-and-blooms/bitset) | 958 | Go package implementing bitsets. |
| <b>[bitmap](https://github.com/kelindar/bitmap) | 163 | Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Bloom and Cuckoo Filters


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bloom](https://github.com/bits-and-blooms/bloom) | 1.6k | Go package implementing Bloom filters. |
| <b>[boomfilters](https://github.com/tylertreat/BoomFilters) | 1.5k | Probabilistic data structures for processing continuous, unbounded streams. |
| <b>[cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 917 | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| <b>[cuckoo-filter](https://github.com/linvon/cuckoo-filter) | 222 | Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available. |
| <b>[bloom](https://github.com/zhenjl/bloom) | 147 | Bloom filters implemented in Go. |
| <b>[ring](https://github.com/TheTannerRyan/ring) | 127 | Go implementation of a high performance, thread safe bloom filter. |
| <b>[bloom](https://github.com/yourbasic/bloom) | 73 | Golang Bloom filter implementation. |
| <b>[bloomfilter](https://github.com/OldPanda/bloomfilter) | 9 | Yet another Bloomfilter implementation in Go, compatible with Java's Guava library. |


<br>

[👆back to top](#catalogue-list)


<br>

### Data Structure and Algorithm Collections


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gods](https://github.com/emirpasic/gods) | 12.0k | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| <b>[go-datastructures](https://github.com/Workiva/go-datastructures) | 6.6k | Collection of useful, performant, and thread-safe data structures. |
| <b>[gostl](https://github.com/liyue201/gostl) | 697 | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| <b>[algorithms](https://github.com/shady831213/algorithms) | 658 | Algorithms and data structures.CLRS study. |


<br>

[👆back to top](#catalogue-list)


<br>

### Iterators


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[iter](https://github.com/disksing/iter) | 160 | Go implementation of C++ STL iterators and algorithms. |
| <b>[goterator](https://github.com/yaa110/goterator) | 9 | Iterator implementation to provide map and reduce functionalities. |


<br>

[👆back to top](#catalogue-list)


<br>

### Maps


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[cmap](https://github.com/lrita/cmap) | 34 | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| <b>[dict](https://github.com/srfrog/dict) | 29 | Python-like dictionaries (dict) for Go. |
| <b>[goradd/maps](https://github.com/goradd/maps) | 10 | Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc. |


<br>

[👆back to top](#catalogue-list)


<br>

### Miscellaneous Data Structures and Algorithms


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gota](https://github.com/kniren/gota) | 2.3k | Implementation of dataframes, series, and data wrangling methods for Go. |
| <b>[hyperloglog](https://github.com/axiomhq/hyperloglog) | 792 | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| <b>[go-geoindex](https://github.com/hailocab/go-geoindex) | 342 | In-memory geo index. |
| <b>[hilbert](https://github.com/google/hilbert) | 253 | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| <b>[go-rquad](https://github.com/aurelien-rainone/go-rquad) | 120 | Region quadtrees with efficient point location and neighbour finding. |
| <b>[conjungo](https://github.com/InVisionApp/conjungo) | 106 | A small, powerful and flexible merge library. |
| <b>[go-rampart](https://github.com/francesconi/go-rampart) | 81 | Determine how intervals relate to each other. |
| <b>[count-min-log](https://github.com/seiflotfy/count-min-log) | 57 | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| <b>[hide](https://github.com/emvi/hide) | 49 | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| <b>[concurrent-writer](https://github.com/free/concurrent-writer) | 45 | Highly concurrent drop-in replacement for `bufio.Writer`. |
| <b>[go-tuple](https://github.com/barweiss/go-tuple) | 32 | Generic tuple implementation for Go 1.18+. |
| <b>[fsm](https://github.com/cocoonspace/fsm) | 26 | Finite-State Machine package. |
| <b>[genfuncs](https://github.com/nwillc/genfuncs) | 24 | Go 1.18+ generics package inspired by Kotlin's Sequence and Map. |
| <b>[go18ds](https://github.com/daichi-m/go18ds) | 21 | Go Data Structures using Go 1.18 generics. |
| <b>[gofal](https://github.com/xxjwxc/gofal) | 15 | fractional api for Go. |
| <b>[slices](https://github.com/srfrog/slices) | 7 | Functions that operate on slices; like `package strings` but adapted to work with slices. |
| <b>[slices](https://github.com/twharmon/slices) | 6 | Pure, generic functions for slices. |


<br>

[👆back to top](#catalogue-list)


<br>

### Nullable Types


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[nan](https://github.com/kak-tus/nan) | 54 | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| <b>[typ](https://github.com/gurukami/typ) | 32 | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| <b>[null](https://github.com/emvi/null) | 27 | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |


<br>

[👆back to top](#catalogue-list)


<br>

### Queues


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[deque](https://github.com/gammazero/deque) | 363 | Fast ring-buffer deque (double-ended queue). |
| <b>[goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 202 | Concurrent FIFO queue. |
| <b>[deque](https://github.com/edwingeng/deque) | 60 | A highly optimized double-ended queue. |
| <b>[memlog](https://github.com/embano1/memlog) | 59 | An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka. |


<br>

[👆back to top](#catalogue-list)


<br>

### Sets


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golang-set](https://github.com/deckarep/golang-set) | 2.6k | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| <b>[goset](https://github.com/zoumo/goset) | 49 | A useful Set collection implementation for Go. |
| <b>[set](https://github.com/StudioSol/set) | 21 | Simple set data structure implementation in Go using LinkedHashMap. |
| <b>[dsu](https://github.com/ihebu/dsu) | 7 | Disjoint Set data structure implementation in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Text Analysis


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bleve](https://github.com/blevesearch/bleve) | 8.6k | Modern text indexing library for go. |
| <b>[trie](https://github.com/derekparker/trie) | 600 | Trie implementation in Go. |
| <b>[go-edlib](https://github.com/hbollon/go-edlib) | 336 | Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. |
| <b>[go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 241 | Go implementation of Adaptive Radix Tree. |
| <b>[levenshtein](https://github.com/agnivade/levenshtein) | 228 | Implementation to calculate levenshtein distance in Go. |
| <b>[levenshtein](https://github.com/agext/levenshtein) | 68 | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| <b>[ptrie](https://github.com/viant/ptrie) | 29 | An implementation of prefix tree. |
| <b>[mspm](https://github.com/BlackRabbitt/mspm) | 17 | Multi-String Pattern Matching Algorithm for information retrieval. |
| <b>[parsefields](https://github.com/MonaxGT/parsefields) | 6 | Tools for parse JSON-like logs for collecting unique fields and events. |


<br>

[👆back to top](#catalogue-list)


<br>

### Trees


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[skiplist](https://github.com/MauriceGit/skiplist) | 213 | Very fast Go Skiplist implementation. |
| <b>[skiplist](https://github.com/gansidui/skiplist) | 79 | Skiplist implementation in Go. |
| <b>[treemap](https://github.com/igrmk/treemap) | 24 | Generic key-sorted map using a red-black tree under the hood. |
| <b>[treap](https://github.com/perdata/treap) | 19 | Persistent, fast ordered map using tree heaps. |
| <b>[hashsplit](http://github.com/bobg/hashsplit) | 8 | Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position. |
| <b>[merkle](https://github.com/bobg/merkle) | 4 | Space-efficient computation of Merkle root hashes and inclusion proofs. |


<br>

[👆back to top](#catalogue-list)


<br>

### Pipes


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[pipeline](https://github.com/hyfather/pipeline) | 41 | An implementation of pipelines with fan-in and fan-out. |
| <b>[parapipe](https://github.com/nazar256/parapipe) | 19 | FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results. |
| <b>[ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) | 14 | Go module that processes work concurrently and returns output in a channel in the order of input. |


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
| <b>[BigCache](https://github.com/allegro/bigcache) | 5.9k | Efficient key/value cache for gigabytes of data. |
| <b>[GCache](https://github.com/bluele/gcache) | 2.1k | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| <b>[cache2go](https://github.com/muesli/cache2go) | 1.8k | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| <b>[fastcache](https://github.com/VictoriaMetrics/fastcache) | 1.5k | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| <b>[gocache](https://github.com/eko/gocache) | 1.4k | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| <b>[ttlcache](https://github.com/jellydator/ttlcache) | 471 | An in-memory cache with item expiration and generics. |
| <b>[cachego](https://github.com/fabiorphp/cachego) | 178 | Golang Cache component for multiple drivers. |
| <b>[cachego](https://github.com/faabiosr/cachego) | 178 | Golang Cache component for multiple drivers. |
| <b>[remember-go](https://github.com/rocketlaunchr/remember-go) | 115 | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| <b>[cache](https://github.com/akyoto/cache) | 111 | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| <b>[bcache](https://github.com/iwanbk/bcache) | 89 | Eventually consistent distributed in-memory  cache Go library. |
| <b>[go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 83 | Fast in-memory key:value store/cache library. Pointer caches. |
| <b>[go-cache](https://github.com/viney-shih/go-cache) | 69 | A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern. |
| <b>[couchcache](https://github.com/codingsince1985/couchcache) | 57 | RESTful caching micro-service backed by Couchbase server. |
| <b>[timedmap](https://github.com/zekroTJA/timedmap) | 46 | Map with expiring key-value pairs. |
| <b>[clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 41 | BigCache with clustering support and individual item expiration. |
| <b>[2q](https://github.com/floatdrop/2q) | 11 | 2Q in-memory cache implementation. |
| <b>[gdcache](https://github.com/ulovecode/gdcache) | 9 | A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache. |
| <b>[ttlcache](https://github.com/cheshir/ttlcache) | 6 | In-memory key value storage with TTL for each record. |


<br>

[👆back to top](#catalogue-list)


<br>

### Databases Implemented in Go


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[prometheus](https://github.com/prometheus/prometheus) | 44.0k | Monitoring system and time series database. |
| <b>[tidb](https://github.com/pingcap/tidb) | 32.0k | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| <b>[cockroach](https://github.com/cockroachdb/cockroach) | 25.0k | Scalable, Geo-Replicated, Transactional Datastore. |
| <b>[influxdb](https://github.com/influxdb/influxdb) | 24.0k | Scalable datastore for metrics, events, and real-time analytics. |
| <b>[dgraph](https://github.com/dgraph-io/dgraph) | 18.0k | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| <b>[Milvus](https://github.com/milvus-io/milvus) | 12.0k | Milvus is a vector database for embedding management, analytics and search. |
| <b>[badger](https://github.com/dgraph-io/badger) | 11.0k | Fast key-value store in Go. |
| <b>[rqlite](https://github.com/rqlite/rqlite) | 11.0k | The lightweight, distributed, relational database built on SQLite. |
| <b>[immudb](https://github.com/codenotary/immudb) | 7.8k | immudb is a lightweight, high-speed immutable database for systems and applications written in Go. |
| <b>[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 6.9k | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| <b>[bbolt](https://github.com/etcd-io/bbolt) | 5.8k | An embedded key/value database for Go. |
| <b>[goleveldb](https://github.com/syndtr/goleveldb) | 5.3k | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| <b>[ledisdb](https://github.com/siddontang/ledisdb) | 3.9k | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| <b>[buntdb](https://github.com/tidwall/buntdb) | 3.8k | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| <b>[rosedb](https://github.com/roseduan/rosedb) | 3.1k | An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset. |
| <b>[tiedot](https://github.com/HouzuoGuo/tiedot) | 2.7k | Your NoSQL database powered by Golang. |
| <b>[nutsdb](https://github.com/xujiajun/nutsdb) | 2.4k | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| <b>[godis](https://github.com/hdt3213/godis) | 2.1k | A Golang implemented high-performance Redis server and cluster. |
| <b>[CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1.4k | CovenantSQL is a SQL database on blockchain. |
| <b>[diskv](https://github.com/peterbourgon/diskv) | 1.2k | Home-grown disk-backed key-value store. |
| <b>[Databunker](https://github.com/paranoidguy/databunker) | 1000 | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| <b>[column](https://github.com/kelindar/column) | 965 | High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions. |
| <b>[eliasdb](https://github.com/krotik/eliasdb) | 937 | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| <b>[lotusdb](https://github.com/flower-corp/lotusdb) | 924 | Fast k/v database compatible with lsm and b+tree. |
| <b>[pogreb](https://github.com/akrylysov/pogreb) | 915 | Embedded key-value store for read-heavy workloads. |
| <b>[moss](https://github.com/couchbase/moss) | 880 | Moss is a simple LSM key-value storage engine written in 100% Go. |
| <b>[levigo](https://github.com/jmhodges/levigo) | 405 | Levigo is a Go wrapper for LevelDB. |
| <b>[pudge](https://github.com/recoilme/pudge) | 328 | Fast and simple key/value store written using Go's standard library. |
| <b>[clover](https://github.com/ostafen/clover) | 245 | A lightweight document-oriented NoSQL database written in pure Golang. |
| <b>[Vasto](https://github.com/chrislusf/vasto) | 238 | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| <b>[dtf](https://github.com/dtm-labs/dtf) | 237 | A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages. |
| <b>[piladb](https://github.com/fern4lvarez/piladb) | 195 | Lightweight RESTful database engine based on stack data structures. |
| <b>[unitdb](https://github.com/unit-io/unitdb) | 95 | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| <b>[hare](https://github.com/jameycribbs/hare) | 59 | A simple database management system that stores each table as a text file of line-delimited JSON. |
| <b>[Coffer](https://github.com/claygod/coffer) | 30 | Simple ACID key-value database that supports transactions. |
| <b>[tempdb](https://github.com/rafaeljesus/tempdb) | 16 | Key-value store for temporary items. |
| <b>[Bitcask](https://git.mills.io/prologic/bitcask) | - | Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). |


<br>

[👆back to top](#catalogue-list)


<br>

### Database Schema Migration


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[migrate](https://github.com/golang-migrate/migrate) | 9.4k | Database migrations. CLI and Golang library. |
| <b>[goose](https://github.com/pressly/goose) | 2.9k | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| <b>[sql-migrate](https://github.com/rubenv/sql-migrate) | 2.5k | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| <b>[atlas](https://github.com/ariga/atlas) | 1.7k | A Database Toolkit. A CLI designed to help companies better work with their data. |
| <b>[soda](https://github.com/gobuffalo/pop/tree/master/soda) | 1.2k | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| <b>[skeema](https://github.com/skeema/skeema) | 1000 | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| <b>[goavro](https://github.com/linkedin/goavro) | 822 | A Go package that encodes and decodes Avro data. |
| <b>[gormigrate](https://github.com/go-gormigrate/gormigrate) | 803 | Database schema migration helper for Gorm ORM. |
| <b>[darwin](https://github.com/GuiaBolso/darwin) | 132 | Database schema evolution library for Go. |
| <b>[migrator](https://github.com/lopezator/migrator) | 127 | Dead simple Go database migration library. |
| <b>[go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 80 | A Go package to help write migrations with go-pg/pg. |
| <b>[avro](https://github.com/khezen/avro) | 38 | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| <b>[sqlize](https://github.com/sunary/sqlize) | 37 | Database migration generator. Allows generate sql migration from model and existing sql by differ them. |
| <b>[go-fixtures](https://github.com/RichardKnop/go-fixtures) | 28 | Django style fixtures for Golang's excellent built-in database/sql library. |
| <b>[pravasan](https://github.com/pravasan/pravasan) | 28 | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| <b>[schema](https://github.com/adlio/schema) | 24 | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| <b>[migrator](https://github.com/larapulse/migrator) | 19 | MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code. |
| <b>[go-pg-migrate](https://github.com/lawzava/go-pg-migrate) | 7 | CLI-friendly package for go-pg migrations management. |
| <b>[libschema](https://github.com/muir/libschema) | 3 | Define your migrations separately in each libary.  Migrations for open source libraries.  MySQL & PostgreSQL. |
| <b>[gorm-seeder](https://github.com/Kachit/gorm-seeder) | 2 | Simple database seeder for Gorm ORM. |
| <b>[godfish](https://github.com/rafaelespinoza/godfish) | 1 | Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3. |


<br>

[👆back to top](#catalogue-list)


<br>

### Database Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[vitess](https://github.com/youtube/vitess) | 15.0k | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| <b>[pgweb](https://github.com/sosedoff/pgweb) | 7.4k | Web-based PostgreSQL database browser. |
| <b>[kingshard](https://github.com/flike/kingshard) | 6.1k | kingshard is a high performance proxy for MySQL powered by Golang. |
| <b>[orchestrator](https://github.com/github/orchestrator) | 4.6k | MySQL replication topology manager & visualizer. |
| <b>[go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) | 3.8k | Sync your MySQL data into Elasticsearch automatically. |
| <b>[go-mysql](https://github.com/siddontang/go-mysql) | 3.7k | Go toolset to handle MySQL protocol and replication. |
| <b>[pREST](https://github.com/prest/prest) | 3.3k | Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. |
| <b>[chproxy](https://github.com/Vertamedia/chproxy) | 955 | HTTP proxy for ClickHouse database. |
| <b>[pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | 764 | Advanced scheduling for PostgreSQL. |
| <b>[clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 376 | Collects small inserts and sends big requests to ClickHouse servers. |
| <b>[myreplication](https://github.com/2tvenom/myreplication) | 187 | MySql binary log replication listener. Supports statement and row based replication. |
| <b>[octillery](https://github.com/knocknote/octillery) | 168 | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| <b>[rdb](https://github.com/HDT3213/rdb) | 166 | Redis RDB file parser for secondary development and memory analysis. |
| <b>[dbbench](https://github.com/sj14/dbbench) | 72 | Database benchmarking tool with support for several databases and scripts. |
| <b>[datagen](https://github.com/codingconcepts/datagen) | 49 | A fast data generator that's multi-table aware and supports multi-row DML. |
| <b>[prep](https://github.com/hexdigest/prep) | 31 | Use prepared SQL statements without changing your code. |
| <b>[rwdb](https://github.com/andizzle/rwdb) | 15 | rwdb provides read replica capability for multiple database servers setup. |
| <b>[dynago](https://github.com/twharmon/dynago) | 2 | Simplify working with AWS DynamoDB. |


<br>

[👆back to top](#catalogue-list)


<br>

### SQL Query Builders

_Libraries for building and using SQL._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sqlc](https://github.com/kyleconroy/sqlc) | 6.1k | Generate type-safe code from SQL. |
| <b>[Squirrel](https://github.com/Masterminds/squirrel) | 5.1k | Go library that helps you build SQL queries. |
| <b>[xo](https://github.com/knq/xo) | 3.2k | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| <b>[goqu](https://github.com/doug-martin/goqu) | 1.6k | Idiomatic SQL builder and query library. |
| <b>[gendry](https://github.com/didi/gendry) | 1.4k | Non-invasive SQL builder and powerful data binder. |
| <b>[jet](https://github.com/go-jet/jet) | 772 | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| <b>[Dotsql](https://github.com/gchaincl/dotsql) | 643 | Go library that helps you keep sql files in one place and use them with ease. |
| <b>[ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 566 | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| <b>[dbq](https://github.com/rocketlaunchr/dbq) | 350 | Zero boilerplate database operations for Go. |
| <b>[sqlingo](https://github.com/lqs/sqlingo) | 257 | A lightweight DSL to build SQL in Go. |
| <b>[sqrl](https://github.com/elgris/sqrl) | 242 | SQL query builder, fork of Squirrel with improved performance. |
| <b>[sq](https://github.com/bokwoon95/go-structured-query) | 170 | Type-safe SQL builder and struct mapper for Go. |
| <b>[igor](https://github.com/galeone/igor) | 86 | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| <b>[sqlf](https://github.com/leporo/sqlf) | 81 | Fast SQL query builder. |
| <b>[buildsqlx](https://github.com/arthurkushman/buildsqlx) | 69 | Go database query builder library for PostgreSQL. |
| <b>[godbal](https://github.com/xujiajun/godbal) | 53 | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| <b>[bqb](https://github.com/nullism/bqb) | 40 | Lightweight and easy to learn query builder. |
| <b>[gosql](https://github.com/twharmon/gosql) | 23 | SQL Query builder with better null values support. |
| <b>[qry](https://github.com/HnH/qry) | 22 | Tool that generates constants from files with raw SQL queries. |
| <b>[mpath](https://github.com/spacetab-io/mpath-go) | 11 | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| <b>[ormlite](https://github.com/pupizoid/ormlite) | 3 | Lightweight package containing some ORM-like features and helpers for sqlite databases. |
| <b>[sg](https://github.com/go-the-way/sg) | 1 | A SQL Gen for generating standard SQLs(supports: CRUD) written in Go. |
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
| <b>[cayley](https://github.com/google/cayley) | 14.0k | Graph database with support for multiple backends. |
| <b>[gokv](https://github.com/philippgille/gokv) | 458 | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| <b>[dsc](https://github.com/viant/dsc) | 25 | Datastore connectivity for SQL, NoSQL, structured files. |


<br>

[👆back to top](#catalogue-list)


<br>

### Relational Database Drivers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) | 13.0k | MySQL driver for Go. |
| <b>[pq](https://github.com/lib/pq) | 7.5k | Pure Go Postgres driver for database/sql. |
| <b>[go-sqlite3](https://github.com/mattn/go-sqlite3) | 5.9k | SQLite3 driver for go that uses database/sql. |
| <b>[pgx](https://github.com/jackc/pgx) | 5.8k | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| <b>[go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1.6k | Microsoft MSSQL driver for Go. |
| <b>[go-oci8](https://github.com/mattn/go-oci8) | 592 | Oracle driver for go that uses database/sql. |
| <b>[sqlhooks](https://github.com/qustavo/sqlhooks) | 571 | Attach hooks to any database/sql driver. |
| <b>[godror](https://github.com/godror/godror) | 382 | Oracle driver for Go, using the ODPI-C driver. |
| <b>[Kivik](https://github.com/go-kivik/kivik) | 239 | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| <b>[firebirdsql](https://github.com/nakagami/firebirdsql) | 173 | Firebird RDBMS SQL driver for Go. |
| <b>[go-adodb](https://github.com/mattn/go-adodb) | 127 | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| <b>[Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) | 124 | SQLite with pure Go. |
| <b>[gofreetds](https://github.com/minus5/gofreetds) | 106 | Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org). |
| <b>[avatica](https://github.com/apache/calcite-avatica-go) | 98 | Apache Avatica/Phoenix SQL driver for database/sql. |
| <b>[bgc](https://github.com/viant/bgc) | 16 | Datastore Connectivity for BigQuery for go. |
| <b>[pig](https://github.com/alexeyco/pig) | 9 | Simple [pgx](https://github.com/jackc/pgx) wrapper to execute and [scan](https://github.com/georgysavva/scany) query results easily. |


<br>

[👆back to top](#catalogue-list)


<br>

### NoSQL Database Drivers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[redis](https://github.com/go-redis/redis) | 15.0k | Redis client for Golang. |
| <b>[redigo](https://github.com/gomodule/redigo) | 9.2k | Redigo is a Go client for the Redis database. |
| <b>[mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 6.9k | Official MongoDB driver for the Go language. |
| <b>[mgo](https://github.com/globalsign/mgo) | 1.9k | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| <b>[gorethink](https://github.com/dancannon/gorethink) | 1.6k | Go language driver for RethinkDB. |
| <b>[gomemcache](https://github.com/bradfitz/gomemcache/) | 1.5k | memcache client library for the Go programming language. |
| <b>[qmgo](https://github.com/qiniu/qmgo) | 948 | The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| <b>[mgm](https://github.com/kamva/mgm) | 542 | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| <b>[redeo](https://github.com/bsm/redeo) | 416 | Redis-protocol compatible TCP servers/services. |
| <b>[aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 394 | Aerospike client in Go language. |
| <b>[neoism](https://github.com/jmcvetta/neoism) | 388 | Neo4j client for Golang. |
| <b>[rueidis](http://github.com/rueian/rueidis) | 368 | Fast Redis RESP3 client with auto pipelining and server-assisted client side caching. |
| <b>[gocb](https://github.com/couchbase/gocb) | 337 | Official Couchbase Go SDK. |
| <b>[go-couchbase](https://github.com/couchbase/go-couchbase) | 316 | Couchbase client in Go. |
| <b>[go-rejson](https://github.com/nitishm/go-rejson) | 276 | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| <b>[godis](https://github.com/piaohao/godis) | 105 | redis client implement by golang, inspired by jedis. |
| <b>[Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 76 | Neo4j REST Client in golang. |
| <b>[arangolite](https://github.com/solher/arangolite) | 72 | Lightweight golang driver for ArangoDB. |
| <b>[go-pilosa](https://github.com/pilosa/go-pilosa) | 54 | Go client library for Pilosa. |
| <b>[forestdb](https://github.com/couchbase/goforestdb) | 32 | Go bindings for ForestDB. |
| <b>[goriak](https://github.com/zegl/goriak) | 27 | Go language driver for Riak KV. |
| <b>[neo4j](https://github.com/cihangir/neo4j) | 27 | Neo4j Rest API Bindings for Golang. |
| <b>[xredis](https://github.com/shomali11/xredis) | 18 | Typesafe, customizable, clean & easy to use Redis client. |
| <b>[godscache](https://github.com/defcronyke/godscache) | 10 | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| <b>[gocosmos](https://github.com/btnguyen2k/gocosmos) | 9 | REST client and standard `database/sql` driver for Azure Cosmos DB. |
| <b>[asc](https://github.com/viant/asc) | 8 | Datastore Connectivity for Aerospike for go. |
| <b>[gocql](https://gocql.github.io) | - | Go language driver for Apache Cassandra. |


<br>

[👆back to top](#catalogue-list)


<br>

### Search and Analytic Databases


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[elastic](https://github.com/olivere/elastic) | 7.0k | Elasticsearch client for Go. |
| <b>[go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 4.3k | Official Elasticsearch client for Go. |
| <b>[elasticsql](https://github.com/cch123/elasticsql) | 948 | Convert sql to elasticsearch dsl in Go. |
| <b>[elastigo](https://github.com/mattbaird/elastigo) | 947 | Elasticsearch client library. |
| <b>[skizze](https://github.com/seiflotfy/skizze) | 86 | probabilistic data-structures service and storage. |
| <b>[goes](https://github.com/OwnLocal/goes) | 28 | Library to interact with Elasticsearch. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Date and Time

_Libraries for working with dates and times._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[now](https://github.com/jinzhu/now) | 3.8k | Now is a time toolkit for golang. |
| <b>[carbon](https://github.com/golang-module/carbon) | 2.2k | A simple, semantic and developer-friendly golang package for datetime. |
| <b>[dateparse](https://github.com/araddon/dateparse) | 1.8k | Parse date's without knowing format in advance. |
| <b>[carbon](https://github.com/uniplaces/carbon) | 723 | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| <b>[durafmt](https://github.com/hako/durafmt) | 443 | Time duration formatting library for Go. |
| <b>[timeutil](https://github.com/leekchan/timeutil) | 189 | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| <b>[gostradamus](https://github.com/bykof/gostradamus) | 169 | A Go package for working with dates. |
| <b>[go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 126 | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| <b>[iso8601](https://github.com/relvacode/iso8601) | 105 | Efficiently parse ISO8601 date-times without regex. |
| <b>[date](https://github.com/rickb777/date) | 91 | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| <b>[timespan](https://github.com/SaidinWoT/timespan) | 82 | For interacting with intervals of time, defined as a start time and a duration. |
| <b>[go-sunrise](https://github.com/nathan-osman/go-sunrise) | 55 | Calculate the sunrise and sunset times for a given location. |
| <b>[go-str2duration](https://github.com/xhit/go-str2duration) | 43 | Convert string to duration. Support time.Duration returned string and more. |
| <b>[feiertage](https://github.com/wlbr/feiertage) | 42 | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| <b>[kair](https://github.com/GuilhermeCaruso/kair) | 23 | Date and Time - Golang Formatting Library. |
| <b>[cronrange](https://github.com/1set/cronrange) | 17 | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| <b>[NullTime](https://github.com/kirillDanshin/nulltime) | 12 | Nullable `time.Time`. |
| <b>[tuesday](https://github.com/osteele/tuesday) | 11 | Ruby-compatible Strftime function. |
| <b>[strftime](https://github.com/awoodbeck/strftime) | 10 | C99-compatible strftime formatter. |
| <b>[go-week](https://github.com/stoewer/go-week) | 7 | An efficient package to work with ISO8601 week dates. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Distributed Systems

_Packages that help with building Distributed Systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[raft](https://github.com/coreos/etcd/tree/master/raft) | 41.0k | Go implementation of the Raft consensus protocol, by CoreOS. |
| <b>[go-kit](https://github.com/go-kit/kit) | 24.0k | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| <b>[go-zero](https://github.com/tal-tech/go-zero) | 20.0k | A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity. |
| <b>[go-micro](https://github.com/micro/go-micro) | 19.0k | A distributed systems development framework. |
| <b>[Kratos](https://github.com/go-kratos/kratos) | 19.0k | A modular-designed and easy-to-use microservices framework in Go. |
| <b>[grpc-go](https://github.com/grpc/grpc-go) | 17.0k | The Go language implementation of gRPC. HTTP/2 based RPC. |
| <b>[micro](https://github.com/micro/micro) | 11.0k | A distributed systems runtime for the cloud and beyond. |
| <b>[NATS](https://github.com/nats-io/gnatsd) | 11.0k | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| <b>[rpcx](https://github.com/smallnest/rpcx) | 7.2k | Distributed pluggable RPC service framework like alibaba Dubbo. |
| <b>[raft](https://github.com/hashicorp/raft) | 6.3k | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| <b>[lura](https://github.com/luraproject/lura) | 5.2k | Ultra performant API Gateway framework with middlewares. |
| <b>[torrent](https://github.com/anacrolix/torrent) | 4.5k | BitTorrent client package. |
| <b>[dragonboat](https://github.com/lni/dragonboat) | 4.3k | A feature complete and high performance multi-group Raft library in Go. |
| <b>[emitter-io](https://github.com/emitter-io/emitter) | 3.3k | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| <b>[gleam](https://github.com/chrislusf/gleam) | 3.1k | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| <b>[glow](https://github.com/chrislusf/glow) | 3.1k | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| <b>[liftbridge](https://github.com/liftbridge-io/liftbridge) | 2.3k | Lightweight, fault-tolerant message streams for NATS. |
| <b>[hprose](https://github.com/hprose/hprose-golang) | 1.2k | Very newbility RPC Library, support 25+ languages now. |
| <b>[go-doudou](https://github.com/unionj-cloud/go-doudou) | 840 | A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity. |
| <b>[redis-lock](https://github.com/bsm/redislock) | 768 | Simplified distributed locking implementation using Redis. |
| <b>[rain](https://github.com/cenkalti/rain) | 751 | BitTorrent client and library. |
| <b>[ringpop-go](https://github.com/uber/ringpop-go) | 743 | Scalable, fault-tolerant application-layer sharding for Go applications. |
| <b>[gorpc](https://github.com/valyala/gorpc) | 652 | Simple, fast and scalable RPC library for high load. |
| <b>[go-health](https://github.com/InVisionApp/go-health) | 628 | Library for enabling asynchronous dependency health checks in your service. |
| <b>[arpc](https://github.com/lesismal/arpc) | 582 | More effective network communication, support two-way-calling, notify, broadcast. |
| <b>[consistent](https://github.com/buraksezer/consistent) | 496 | Consistent hashing with bounded loads. |
| <b>[go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 486 | A library built to provide support for defining async service health checks for golang services. |
| <b>[digota](https://github.com/digota/digota) | 456 | grpc ecommerce microservice. |
| <b>[sleuth](https://github.com/ursiform/sleuth) | 355 | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| <b>[go-jump](https://github.com/dgryski/go-jump) | 348 | Port of Google's "Jump" Consistent Hash function. |
| <b>[dht](https://github.com/anacrolix/dht) | 241 | BitTorrent Kademlia DHT implementation. |
| <b>[jsonrpc](https://github.com/ybbus/jsonrpc) | 236 | JSON-RPC 2.0 HTTP client implementation. |
| <b>[jsonrpc](https://github.com/osamingo/jsonrpc) | 168 | The jsonrpc package helps implement of JSON-RPC 2.0. |
| <b>[outboxer](https://github.com/italolelis/outboxer) | 87 | Outboxer is a go library that implements the outbox pattern. |
| <b>[doublejump](https://github.com/edwingeng/doublejump) | 76 | A revamped Google's jump consistent hash. |
| <b>[Semaphore](https://github.com/jexia/semaphore) | 74 | A straightforward (micro) service orchestrator. |
| <b>[celeriac](https://github.com/svcavallar/celeriac.v1) | 73 | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| <b>[dot](https://github.com/dotchain/dot/) | 72 | distributed sync using operational transformation/OT. |
| <b>[flowgraph](https://github.com/vectaport/flowgraph) | 51 | flow-based programming package. |
| <b>[go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 46 | MySQL based distributed lock. |
| <b>[drmaa](https://github.com/dgruber/drmaa) | 40 | Job submission library for cluster schedulers based on the DRMAA standard. |
| <b>[go-pdu](https://github.com/pdupub/go-pdu) | 39 | A decentralized identity-based social network. |
| <b>[gmsec](https://github.com/gmsec/micro) | 20 | A Go distributed systems development framework. |
| <b>[dynatomic](https://github.com/tylfin/dynatomic) | 14 | A library for using DynamoDB as an atomic counter. |
| <b>[consistenthash](https://github.com/mbrostami/consistenthash) | 11 | Consistent hashing with configurable replicas. |
| <b>[failured](https://github.com/andy2046/failured) | 6 | adaptive accrual failure detector for distributed systems. |
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
| <b>[GoDNS](https://github.com/timothyye/godns) | 1.1k | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| <b>[DDNS](https://github.com/skibish/ddns) | 216 | Personal DDNS client with Digital Ocean Networking DNS as backend. |
| <b>[dyndns](https://gitlab.com/alcastle/dyndns) | - | Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Email

_Libraries and tools that implement email creation and sending._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[MailHog](https://github.com/mailhog/MailHog) | 11.0k | Email and SMTP testing with web and API interface. |
| <b>[hermes](https://github.com/matcornic/hermes) | 2.5k | Golang package that generates clean, responsive HTML e-mails. |
| <b>[email](https://github.com/jordan-wright/email) | 2.1k | A robust and flexible email library for Go. |
| <b>[go-imap](https://github.com/emersion/go-imap) | 1.6k | IMAP library for clients and servers. |
| <b>[SendGrid](https://github.com/sendgrid/sendgrid-go) | 837 | SendGrid's Go library for sending email. |
| <b>[mailgun-go](https://github.com/mailgun/mailgun-go) | 615 | Go library for sending mail with the Mailgun API. |
| <b>[email-verifier](https://github.com/AfterShip/email-verifier) | 497 | A Go library for email verification without sending any emails. |
| <b>[go-simple-mail](https://github.com/xhit/go-simple-mail) | 364 | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |
| <b>[go-message](https://github.com/emersion/go-message) | 260 | Streaming library for the Internet Message Format and mail messages. |
| <b>[Hectane](https://github.com/hectane/hectane) | 220 | Lightweight SMTP client providing an HTTP API. |
| <b>[douceur](https://github.com/aymerick/douceur) | 219 | CSS inliner for your HTML emails. |
| <b>[mailchain](https://github.com/mailchain/mailchain) | 121 | Send encrypted emails to blockchain addresses written in Go. |
| <b>[go-premailer](https://github.com/vanng822/go-premailer) | 90 | Inline styling for HTML mail in Go. |
| <b>[go-dkim](https://github.com/toorop/go-dkim) | 80 | DKIM library, to sign & verify email. |
| <b>[smtp](https://github.com/mailhog/smtp) | 72 | SMTP server protocol state machine. |
| <b>[smtpmock](https://github.com/mocktools/go-smtp-mock) | 51 | Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment. |
| <b>[go-email-validator](https://github.com/go-email-validator/go-email-validator) | 38 | Modular email validator for syntax, disposable, smtp, etc... checking. |
| <b>[go-mail](https://github.com/wneessen/go-mail) | 31 | A simple Go library for sending mails in Go. |
| <b>[truemail-go](https://github.com/truemail-rb/truemail-go) | 19 | Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more. |
| <b>[mailx](https://github.com/valord577/mailx) | 3 | Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`. |
| <b>[chasquid](https://blitiri.com.ar/p/chasquid) | - | SMTP server written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Embeddable Scripting Languages

_Embedding other languages inside your go code._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopher-lua](https://github.com/yuin/gopher-lua) | 4.9k | Lua 5.1 VM and compiler written in Go. |
| <b>[goja](https://github.com/dop251/goja) | 3.2k | ECMAScript 5.1(+) implementation in Go. |
| <b>[tengo](https://github.com/d5/tengo) | 2.9k | Bytecode compiled script language for Go. |
| <b>[expr](https://github.com/antonmedv/expr) | 2.8k | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| <b>[go-lua](https://github.com/Shopify/go-lua) | 2.5k | Port of the Lua 5.2 VM to pure Go. |
| <b>[go-python](https://github.com/sbinet/go-python) | 1.4k | naive go bindings to the CPython C-API. |
| <b>[anko](https://github.com/mattn/anko) | 1.3k | Scriptable interpreter written in Go. |
| <b>[cel-go](https://github.com/google/cel-go) | 1.3k | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| <b>[metacall](https://github.com/metacall/core) | 1000 | Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more. |
| <b>[go-php](https://github.com/deuill/go-php) | 868 | PHP bindings for Go. |
| <b>[go-duktape](https://github.com/olebedev/go-duktape) | 781 | Duktape JavaScript engine bindings for Go. |
| <b>[golua](https://github.com/aarzilli/golua) | 589 | Go bindings for Lua C API. |
| <b>[gval](https://github.com/PaesslerAG/gval) | 523 | A highly customizable expression language written in Go. |
| <b>[gisp](https://github.com/jcla1/gisp) | 486 | Simple LISP in Go. |
| <b>[prolog](https://github.com/ichiban/prolog) | 408 | Embeddable Prolog. |
| <b>[gentee](https://github.com/gentee/gentee) | 95 | Embeddable scripting programming language. |
| <b>[binder](https://github.com/alexeyco/binder) | 59 | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| <b>[purl](https://github.com/ian-kent/purl) | 34 | Perl 5.18.2 embedded in Go. |
| <b>[ecal](https://github.com/krotik/ecal) | 26 | A simple embeddable scripting language which supports concurrent event processing. |
| <b>[ngaro](https://github.com/db47h/ngaro) | 22 | Embeddable Ngaro VM implementation enabling scripting in Retro. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Error Handling

_Libraries for handling errors._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[errors](https://github.com/pkg/errors) | 7.9k | Package that provides simple error handling primitives. |
| <b>[go-multierror](https://github.com/hashicorp/go-multierror) | 1.7k | Go (golang) package for representing a list of errors as a single error. |
| <b>[errors](https://github.com/cockroachdb/errors) | 1.4k | Go error library with error portability over the network. |
| <b>[eris](https://github.com/rotisserie/eris) | 1000 | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| <b>[errorx](https://github.com/joomcode/errorx) | 881 | A feature rich error package with stack traces, composition of errors and more. |
| <b>[tracerr](https://github.com/ztrue/tracerr) | 730 | Golang errors with stack trace and source fragments. |
| <b>[errlog](https://github.com/snwfdhmp/errlog) | 407 | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| <b>[emperror](https://github.com/emperror/emperror) | 251 | Error handling tools and best practices for Go libraries and applications. |
| <b>[errors](https://github.com/emperror/errors) | 152 | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| <b>[errors](https://github.com/bnkamalesh/errors) | 42 | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| <b>[exception](https://github.com/rbrahul/exception) | 16 | A simple utility package for exception handling with try-catch in Golang. |
| <b>[Falcon](https://github.com/SonicRoshan/falcon) | 7 | A Simple Yet Highly Powerful Package For Error Handling. |
| <b>[errors](https://github.com/PumpkinSeed/errors) | 5 | The most simple error wrapper with awesome performance and minimal memory overhead. |
| <b>[errors](https://github.com/neuronlabs/errors) | 3 | Simple golang error handling with classification primitives. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## File Handling

_Libraries for handling files and file systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[afero](https://github.com/spf13/afero) | 4.7k | FileSystem Abstraction System for Go. |
| <b>[pdfcpu](https://github.com/pdfcpu/pdfcpu) | 3.3k | PDF processor. |
| <b>[gdu](https://github.com/dundee/gdu) | 1.9k | Disk usage analyzer with console interface. |
| <b>[notify](https://github.com/rjeczalik/notify) | 753 | File system event notification library with simple API, similar to os/signal. |
| <b>[copy](https://github.com/otiai10/copy) | 456 | Copy directory recursively. |
| <b>[bigfile](https://github.com/bigfile/bigfile) | 229 | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| <b>[afs](https://github.com/viant/afs) | 192 | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| <b>[vfs](https://github.com/C2FO/vfs) | 185 | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| <b>[go-exiftool](https://github.com/barasher/go-exiftool) | 132 | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| <b>[go-csv-tag](https://github.com/artonge/go-csv-tag) | 96 | Load csv file using tag. |
| <b>[gofs](https://github.com/no-src/gofs) | 84 | A file synchronization tool out of the box. |
| <b>[skywalker](https://github.com/dixonwille/skywalker) | 82 | Package to allow one to concurrently go through a filesystem with ease. |
| <b>[opc](https://github.com/qmuntal/opc) | 72 | Load Open Packaging Conventions (OPC) files for Go. |
| <b>[checksum](https://github.com/codingsince1985/checksum) | 67 | Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files. |
| <b>[parquet](https://github.com/parsyl/parquet) | 56 | Read and write [parquet](https://parquet.apache.org) files. |
| <b>[tarfs](https://github.com/posener/tarfs) | 50 | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| <b>[baraka](https://github.com/xis/baraka) | 45 | A library to process http file uploads easily. |
| <b>[go-gtfs](https://github.com/artonge/go-gtfs) | 32 | Load gtfs files in go. |
| <b>[flop](https://github.com/homedepot/flop) | 31 | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| <b>[gut/yos](https://github.com/1set/gut) | 24 | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| <b>[go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 16 | Copy files for humans. |
| <b>[todotxt](https://github.com/1set/todotxt) | 13 | Go library for Gina Trapani's [_todo.txt_](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [_todo.txt_ format](https://github.com/todotxt/todo.txt). |
| <b>[pathtype](https://github.com/jonchun/pathtype) | 11 | Treat paths as their own type instead of using strings. |
| <b>[higgs](https://github.com/dastoori/higgs) | 10 | A tiny cross-platform Go library to hide/unhide files and directories. |
| <b>[stl](https://gitlab.com/russoj88/stl) | - | Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Financial

_Packages for accounting and finance._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[decimal](https://github.com/shopspring/decimal) | 4.3k | Arbitrary-precision fixed-point decimal numbers. |
| <b>[ticker](https://github.com/achannarasappa/ticker) | 4.3k | Terminal stock watcher and stock position tracker. |
| <b>[go-money](https://github.com/rhymond/go-money) | 1.1k | Implementation of Fowler's Money pattern. |
| <b>[accounting](https://github.com/leekchan/accounting) | 761 | money and currency formatting for golang. |
| <b>[techan](https://github.com/sdcoffey/techan) | 660 | Technical analysis library with advanced market analysis and trading strategies. |
| <b>[go-finance](https://github.com/FlashBoys/go-finance) | 537 | Comprehensive financial markets data in Go. |
| <b>[currency](https://github.com/bojanz/currency) | 329 | Handles currency amounts, provides currency information and formatting. |
| <b>[ach](https://github.com/moov-io/ach) | 325 | A reader, writer, and valdiator for Automated Clearing House (ACH) files. |
| <b>[orderbook](https://github.com/i25959341/orderbook) | 282 | Matching Engine for Limit Order Book in Golang. |
| <b>[go-finance](https://github.com/alpeb/go-finance) | 141 | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| <b>[transaction](https://github.com/claygod/transaction) | 113 | Embedded transactional database of accounts, running in multithreaded mode. |
| <b>[ofxgo](https://github.com/aclindsa/ofxgo) | 103 | Query OFX servers and/or parse the responses (with example command-line client). |
| <b>[sleet](https://github.com/BoltApp/sleet) | 97 | One unified interface for multiple Payment Service Providers (PsP) to process online payment. |
| <b>[vat](https://github.com/dannyvankooten/vat) | 95 | VAT number validation & EU VAT rates. |
| <b>[go-finnhub](https://github.com/m1/go-finnhub) | 74 | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| <b>[currency](https://github.com/bnkamalesh/currency) | 47 | High performant & accurate currency computation package. |
| <b>[fastme](https://github.com/newity/fastme) | 36 | Fast extensible matching engine Go implementation. |
| <b>[fpdecimal](https://github.com/nikolaydubina/fpdecimal) | 12 | Fast and precise serialization and arithmetic for small fixed-point decimals |
| <b>[payme](https://github.com/jovandeginste/payme) | 10 | QR code generator (ASCII & PNG) for SEPA payments. |
| <b>[go-finance](https://github.com/pieterclaerhout/go-finance) | 9 | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |
| <b>[fpmoney](https://github.com/nikolaydubina/fpmoney) | 6 | Fast and simple ISO4217 fixed-point decimal money. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Forms

_Libraries for working with forms._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[nosurf](https://github.com/justinas/nosurf) | 1.3k | CSRF protection middleware for Go. |
| <b>[gorilla/csrf](https://github.com/gorilla/csrf) | 819 | CSRF protection for Go web applications & services. |
| <b>[binding](https://github.com/mholt/binding) | 792 | Binds form and JSON data from net/http Request to struct. |
| <b>[form](https://github.com/go-playground/form) | 548 | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| <b>[conform](https://github.com/leebenson/conform) | 264 | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| <b>[formam](https://github.com/monoculum/formam) | 172 | decode form's values into a struct. |
| <b>[forms](https://github.com/albrow/forms) | 132 | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| <b>[httpin](https://github.com/ggicci/httpin) | 101 | Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc. |
| <b>[qs](https://github.com/sonh/qs) | 63 | Go module for encoding structs into URL query parameters. |
| <b>[bind](https://github.com/robfig/bind) | 27 | Bind form data to any Go values. |
| <b>[queryparam](https://github.com/tomwright/queryparam) | 13 | Decode `url.Values` into usable struct values of standard or custom types. |
| <b>[gbind](https://github.com/bdjimmy/gbind) | 7 | Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Functional

_Packages to support functional programming in Go._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-underscore](https://github.com/tobyhede/go-underscore) | 1.3k | Useful collection of helpfully functional Go collection utilities. |
| <b>[mo](https://github.com/samber/mo) | 775 | Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...). |
| <b>[fpGo](https://github.com/TeaEntityLab/fpGo) | 283 | Monad, Functional Programming features for Golang. |
| <b>[gofp](https://github.com/rbrahul/gofp) | 128 | A lodash like powerful utility library for Golang. |
| <b>[fuego](https://github.com/seborama/fuego) | 120 | Functional Experiment in Go. |
| <b>[fp-go](https://github.com/repeale/fp-go) | 90 | Collection of Functional Programming helpers powered by Golang 1.18+ generics. |
| <b>[underscore](https://github.com/rjNemo/underscore) | 65 | Functional programming helpers for Go 1.18 and beyond. |
| <b>[valor](https://github.com/phelmkamp/valor) | 5 | Generic option and result types that optionally contain a value. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Game Development

_Awesome game development libraries._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Ebiten](https://github.com/hajimehoshi/ebiten) | 6.9k | dead simple 2D game library in Go. |
| <b>[Leaf](https://github.com/name5566/leaf) | 4.5k | Lightweight game server framework. |
| <b>[Pixel](https://github.com/faiface/pixel) | 4.0k | Hand-crafted 2D game library in Go. |
| <b>[goworld](https://github.com/xiaonanln/goworld) | 2.2k | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| <b>[g3n](https://github.com/g3n/engine) | 2.1k | Go 3D Game Engine. |
| <b>[nano](https://github.com/lonng/nano) | 2.1k | Lightweight, facility, high performance golang based game server framework. |
| <b>[go-sdl2](https://github.com/veandco/go-sdl2) | 1.8k | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| <b>[engo](https://github.com/EngoEngine/engo) | 1.5k | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| <b>[Pitaya](https://github.com/topfreegames/pitaya) | 1.5k | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| <b>[Oak](https://github.com/oakmound/oak) | 1.3k | Pure Go game engine. |
| <b>[termloop](https://github.com/JoelOtter/termloop) | 1.3k | Terminal-based game engine for Go, built on top of Termbox. |
| <b>[gonet](https://github.com/xtaci/gonet) | 1.2k | Game server skeleton implemented with golang. |
| <b>[raylib-go](https://github.com/gen2brain/raylib-go) | 849 | Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| <b>[Azul3D](https://github.com/azul3d/engine) | 553 | 3D game engine written in Go. |
| <b>[go-astar](https://github.com/beefsack/go-astar) | 510 | Go implementation of the A\* path finding algorithm. |
| <b>[go3d](https://github.com/ungerik/go3d) | 266 | Performance oriented 2D/3D math package for Go. |
| <b>[prototype](https://github.com/gonutz/prototype) | 74 | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| <b>[tile](https://github.com/kelindar/tile) | 62 | Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Generators

_Tools that generate Go code._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-linq](https://github.com/ahmetalpbalkan/go-linq) | 3.1k | .NET LINQ-like query methods for Go. |
| <b>[jennifer](https://github.com/dave/jennifer) | 2.5k | Generate arbitrary Go code without templates. |
| <b>[goderive](https://github.com/awalterschulze/goderive) | 999 | Derives functions from input types. |
| <b>[GoWrap](https://github.com/hexdigest/gowrap) | 643 | Generate decorators for Go interfaces using simple templates. |
| <b>[go-enum](https://github.com/abice/go-enum) | 363 | Code generation for enums from code comments. |
| <b>[interfaces](https://github.com/rjeczalik/interfaces) | 350 | Command line tool for generating interface definitions. |
| <b>[copygen](https://github.com/switchupcb/copygen) | 165 | Generate type-to-type code without reflection. |
| <b>[goverter](https://github.com/jmattheis/goverter) | 139 | Generate converters by defining an interface. |
| <b>[gotype](https://github.com/wzshiming/gotype) | 45 | Golang source code parsing, usage like reflect package. |
| <b>[generis](https://github.com/senselogic/GENERIS) | 34 | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| <b>[go-xray](https://github.com/pieterclaerhout/go-xray) | 23 | Helpers for making the use of reflection easier. |
| <b>[typeregistry](https://github.com/xiaoxin01/typeregistry) | 14 | A library to create type dynamically. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Geographic

_Geographic tools and servers_


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Tile38](https://github.com/tidwall/tile38) | 8.2k | Geolocation DB with spatial index and realtime geofencing. |
| <b>[S2 geometry](https://github.com/golang/geo) | 1.4k | S2 geometry library in Go. |
| <b>[mbtileserver](https://github.com/consbio/mbtileserver) | 369 | A simple Go-based server for map tiles stored in mbtiles format. |
| <b>[osm](https://github.com/paulmach/osm) | 223 | Library for reading, writing and working with OpenStreetMap data and APIs. |
| <b>[WGS84](https://github.com/wroge/wgs84) | 85 | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| <b>[godal](https://github.com/airbusgeo/godal) | 80 | Go wrapper for GDAL. |
| <b>[geoserver](https://github.com/hishamkaram/geoserver) | 74 | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| <b>[simplefeatures](https://github.com/peterstace/simplefeatures) | 59 | simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them. |
| <b>[gismanager](https://github.com/hishamkaram/gismanager) | 47 | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| <b>[pbf](https://github.com/maguro/pbf) | 37 | OpenStreetMap PBF golang encoder/decoder. |
| <b>[S2 geojson](https://github.com/pantrif/s2-geojson) | 17 | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |
| <b>[H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) | 2 | Conversion utilities between H3 indexes and GeoJSON. |
| <b>[Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) | 1 | A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection. |
| <b>[H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) | 0 | Distribution of Uber H3geo cells by virtual nodes. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Compilers

_Tools for compiling Go to other languages._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopherjs](https://github.com/gopherjs/gopherjs) | 11.0k | Compiler from Go to JavaScript. |
| <b>[tardisgo](https://github.com/tardisgo/tardisgo) | 418 | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| <b>[c4go](https://github.com/Konstantin8105/c4go) | 323 | Transpile C code to Go code. |
| <b>[c2go](https://github.com/goplus/c2go) | 192 | Convert C code to Go code. |
| <b>[esp32](https://github.com/andygeiss/esp32-transpiler) | 50 | Transpile Go into Arduino code. |
| <b>[f4go](https://github.com/Konstantin8105/f4go) | 32 | Transpile FORTRAN 77 code to Go code. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Goroutines

_Tools for managing and working with Goroutines._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[ants](https://github.com/panjf2000/ants) | 8.9k | A high-performance and low-cost goroutine pool in Go. |
| <b>[tunny](https://github.com/Jeffail/tunny) | 3.2k | Goroutine pool for golang. |
| <b>[goworker](https://github.com/benmanns/goworker) | 2.7k | goworker is a Go-based background worker. |
| <b>[workerpool](https://github.com/gammazero/workerpool) | 888 | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| <b>[grpool](https://github.com/ivpusic/grpool) | 700 | Lightweight Goroutine pool. |
| <b>[pool](https://github.com/go-playground/pool) | 693 | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| <b>[pond](https://github.com/alitto/pond) | 600 | Minimalistic and High-performance goroutine worker pool written in Go. |
| <b>[gowp](https://github.com/xxjwxc/gowp) | 407 | gowp is concurrency limiting goroutine pool. |
| <b>[go-floc](https://github.com/workanator/go-floc) | 256 | Orchestrate goroutines with ease. |
| <b>[go-flow](https://github.com/kamildrazkiewicz/go-flow) | 194 | Control goroutines execution order. |
| <b>[semaphore](https://github.com/marusama/semaphore) | 149 | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| <b>[go-workers](https://github.com/catmullet/go-workers) | 143 | Easily and safely run workers for large data processing pipelines. |
| <b>[artifex](https://github.com/borderstech/artifex) | 134 | Simple in-memory job queue for Golang using worker-based dispatching. |
| <b>[neilotoole/errgroup](https://github.com/neilotoole/errgroup) | 131 | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| <b>[async](https://github.com/studiosol/async) | 109 | A safe way to execute functions asynchronously, recovering them in case of panic. |
| <b>[cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 98 | CyclicBarrier for golang. |
| <b>[gollback](https://github.com/vardius/gollback) | 94 | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| <b>[semaphore](https://github.com/kamilsk/semaphore) | 89 | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| <b>[async](https://github.com/reugn/async) | 86 | An alternative sync library for Go (Future, Promise, Locks). |
| <b>[Hunch](https://github.com/AaronJan/Hunch) | 85 | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| <b>[gpool](https://github.com/Sherifabdlnaby/gpool) | 84 | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| <b>[worker-pool](https://github.com/vardius/worker-pool) | 83 | goworker is a Go simple async worker pool. |
| <b>[threadpool](https://github.com/shettyh/threadpool) | 75 | Golang threadpool implementation. |
| <b>[goccm](https://github.com/zenthangplus/goccm) | 54 | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| <b>[routine](https://github.com/x-mod/routine) | 52 | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| <b>[nursery](https://github.com/arunsworld/nursery) | 49 | Structured concurrency in Go. |
| <b>[gohive](https://github.com/loveleshsharma/gohive) | 41 | A highly performant and easy to use Goroutine pool for Go. |
| <b>[kyoo](https://github.com/dirkaholic/kyoo) | 38 | Provides an unlimited job queue and concurrent worker pools. |
| <b>[gowl](https://github.com/hamed-yousefi/gowl) | 34 | Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status. |
| <b>[parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 33 | Run functions in parallel. |
| <b>[go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 31 | Like `sync.WaitGroup` with error handling and concurrency control. |
| <b>[go-trylock](https://github.com/subchen/go-trylock) | 30 | TryLock support on read-write lock for Golang. |
| <b>[channelify](https://github.com/ddelizia/channelify) | 23 | Transform your function to return channels for easy and powerful parallel processing. |
| <b>[stl](https://github.com/ssgreg/stl) | 23 | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| <b>[conexec](https://github.com/ITcathyh/conexec) | 12 | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| <b>[execpool](https://github.com/hexdigest/execpool) | 12 | A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command. |
| <b>[queue](https://github.com/AnikHasibul/queue) | 12 | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| <b>[hands](https://github.com/duanckham/hands) | 9 | A process controller used to control the execution and return strategies of multiple goroutines. |
| <b>[concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) | 7 | Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines. |
| <b>[go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) | 7 | Manage a pool of goroutines using this lightweight library with a simple API. |
| <b>[breaker](https://github.com/kamilsk/breaker) | 5 | Flexible mechanism to make execution flow interruptible. |
| <b>[async-job](https://github.com/lab210-dev/async-job) | 2 | AsyncJob is an asynchronous queue job manager with light code, clear and speed. |
| <b>[oversight](https://cirello.io/oversight) | - | Oversight is a complete implementation of the Erlang supervision trees. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## GUI

_Interaction_


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fyne](https://github.com/fyne-io/fyne) | 18.0k | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| <b>[webview](https://github.com/zserge/webview) | 10.0k | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| <b>[qt](https://github.com/therecipe/qt) | 9.4k | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| <b>[ui](https://github.com/andlabs/ui) | 8.2k | Platform-native GUI library for Go. Cross platform. |
| <b>[robotgo](https://github.com/go-vgo/robotgo) | 7.8k | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| <b>[app](https://github.com/murlokswarm/app) | 6.4k | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| <b>[walk](https://github.com/lxn/walk) | 6.1k | Windows application library kit for Go. |
| <b>[go-astilectron](https://github.com/asticode/go-astilectron) | 4.5k | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| <b>[systray](https://github.com/getlantern/systray) | 2.5k | Cross platform Go library to place an icon and menu in the notification area. |
| <b>[go-sciter](https://github.com/sciter-sdk/go-sciter) | 2.4k | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| <b>[gotk3](https://github.com/gotk3/gotk3) | 1.8k | Go bindings for GTK3. |
| <b>[gosx-notifier](https://github.com/deckarep/gosx-notifier) | 574 | OSX Desktop Notifications library for Go. |
| <b>[gowd](https://github.com/dtylman/gowd) | 374 | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| <b>[zenity](https://github.com/ncruces/zenity) | 313 | Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user. |
| <b>[trayhost](https://github.com/shurcooL/trayhost) | 231 | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| <b>[go-appindicator](https://github.com/dawidd6/go-appindicator) | 20 | Go bindings for libappindicator3 C library. |
| <b>[mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 18 | OSX library to notify about any (pluggable) activity on your machine. |
| <b>[mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 18 | OSX Sleep/Wake notifications in golang. |
| <b>[goradd/html5tag](https://github.com/goradd/html5tag) | 3 | Library for outputting HTML5 tags. |
| <b>[AppIndicator Go](https://github.com/gopherlibs/appindicator) | 2 | Go bindings for libappindicator3 C library. |
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
| <b>[arduino-cli](https://github.com/arduino/arduino-cli) | 3.5k | Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects. |
| <b>[go-rpio](https://github.com/stianeikeland/go-rpio) | 1.9k | GPIO for Go, doesn't require cgo. |
| <b>[ghw](https://github.com/jaypipes/ghw) | 1.2k | Golang hardware discovery/inspection library. |
| <b>[emgo](https://github.com/ziutek/emgo) | 985 | Go-like language for programming embedded systems (e.g. STM32 MCU). |
| <b>[sysinfo](https://github.com/zcalusic/sysinfo) | 367 | A pure Go library providing Linux OS / kernel / hardware system information. |
| <b>[goroslib](https://github.com/aler9/goroslib) | 211 | Robot Operating System (ROS) library for Go. |
| <b>[go-osc](https://github.com/hypebeast/go-osc) | 156 | Open Sound Control (OSC) bindings for Go. |
| <b>[joystick](https://github.com/0xcafed00d/joystick) | 31 | a polled API to read the state of an attached joystick. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Images

_Libraries for manipulating images._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gocv](https://github.com/hybridgroup/gocv) | 4.9k | Go package for computer vision using OpenCV 3.3+. |
| <b>[imaginary](https://github.com/h2non/imaginary) | 4.5k | Fast and simple HTTP microservice for image resizing. |
| <b>[imaging](https://github.com/disintegration/imaging) | 4.3k | Simple Go image processing package. |
| <b>[bild](https://github.com/anthonynsimon/bild) | 3.6k | Collection of image processing algorithms in pure Go. |
| <b>[gg](https://github.com/fogleman/gg) | 3.5k | 2D rendering in pure Go. |
| <b>[ln](https://github.com/fogleman/ln) | 3.1k | 3D line art rendering in Go. |
| <b>[resize](https://github.com/nfnt/resize) | 2.9k | Image resizing for Go with common interpolation methods. |
| <b>[bimg](https://github.com/h2non/bimg) | 2.0k | Small package for fast and efficient image processing using libvips. |
| <b>[pt](https://github.com/fogleman/pt) | 2.0k | Path tracing engine written in Go. |
| <b>[svgo](https://github.com/ajstarks/svgo) | 1.9k | Go Language Library for SVG generation. |
| <b>[gowitness](https://github.com/sensepost/gowitness) | 1.7k | Screenshoting webpages using go and headless chrome on command line. |
| <b>[picfit](https://github.com/thoas/picfit) | 1.7k | An image resizing server written in Go. |
| <b>[smartcrop](https://github.com/muesli/smartcrop) | 1.7k | Finds good crops for arbitrary images and crop sizes. |
| <b>[gift](https://github.com/disintegration/gift) | 1.6k | Package of image processing filters. |
| <b>[imagick](https://github.com/gographics/imagick) | 1.5k | Go binding to ImageMagick's MagickWand C API. |
| <b>[go-opencv](https://github.com/lazywei/go-opencv) | 1.3k | Go bindings for OpenCV. |
| <b>[geopattern](https://github.com/pravj/geopattern) | 1.2k | Create beautiful generative image patterns from a string. |
| <b>[canvas](https://github.com/tdewolff/canvas) | 1000 | Vector graphics to PDF, SVG or rasterized image. |
| <b>[stegify](https://github.com/DimitarPetrov/stegify) | 1000 | Go tool for LSB steganography, capable of hiding any file within an image. |
| <b>[govips](https://github.com/davidbyttow/govips) | 738 | A lightning fast image processing and resizing library for Go. |
| <b>[image2ascii](https://github.com/qeesung/image2ascii) | 684 | Convert image to ASCII. |
| <b>[draft](https://github.com/lucasepe/draft) | 542 | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| <b>[goimagehash](https://github.com/corona10/goimagehash) | 524 | Go Perceptual image hashing package. |
| <b>[govatar](https://github.com/o1egl/govatar) | 512 | Library and CMD tool for generating funny avatars. |
| <b>[mort](https://github.com/aldor007/mort) | 459 | Storage and image processing server written in Go. |
| <b>[go-nude](https://github.com/koyachi/go-nude) | 349 | Nudity detection with Go. |
| <b>[rez](https://github.com/bamiaux/rez) | 207 | Image resizing in pure Go and SIMD. |
| <b>[darkroom](https://github.com/gojek/darkroom) | 195 | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| <b>[mergi](https://github.com/noelyahan/mergi) | 178 | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| <b>[gltf](https://github.com/qmuntal/gltf) | 172 | Efficient and robust glTF 2.0 reader, writer and validator. |
| <b>[steganography](https://github.com/auyer/steganography) | 149 | Pure Go Library for LSB steganography. |
| <b>[img](https://github.com/hawx/img) | 140 | Selection of image manipulation tools. |
| <b>[go-cairo](https://github.com/ungerik/go-cairo) | 121 | Go binding for the cairo graphics library. |
| <b>[cameron](https://github.com/aofei/cameron) | 87 | An avatar generator for Go. |
| <b>[go-webp](https://github.com/kolesa-team/go-webp) | 63 | Library for encode and decode webp pictures, using libwebp. |
| <b>[go-gd](https://github.com/bolknote/go-gd) | 54 | Go binding for GD library. |
| <b>[gridder](https://github.com/shomali11/gridder) | 54 | A Grid based 2D Graphics library. |
| <b>[webp-server](https://github.com/mehdipourfar/webp-server) | 46 | Simple and minimal image server capable of storing, resizing, converting and caching images. |
| <b>[goimghdr](https://github.com/corona10/goimghdr) | 38 | The imghdr module determines the type of image contained in a file for Go. |
| <b>[tga](https://github.com/ftrvxmtrx/tga) | 31 | Package tga is a TARGA image format decoder/encoder. |
| <b>[go-webcolors](https://github.com/jyotiska/go-webcolors) | 26 | Port of webcolors library from Python to Go. |
| <b>[mpo](https://github.com/donatj/mpo) | 9 | Decoder and conversion tool for MPO 3D Photos. |
| <b>[scout](https://github.com/jonoton/scout) | 4 | Scout is a standalone open source software solution for DIY video security. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## IoT (Internet of Things)

_Libraries for programming devices of the IoT._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gobot](https://github.com/hybridgroup/gobot/) | 7.9k | Gobot is a framework for robotics, physical computing, and the Internet of Things. |
| <b>[flogo](https://github.com/tibcosoftware/flogo) | 2.1k | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| <b>[mainflux](https://github.com/Mainflux/mainflux) | 1.8k | Industrial IoT Messaging and Device Management Server. |
| <b>[gatt](https://github.com/paypal/gatt) | 1000 | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| <b>[connectordb](https://github.com/connectordb/connectordb) | 344 | Open-Source Platform for Quantified Self & IoT. |
| <b>[devices](https://github.com/goiot/devices) | 254 | Suite of libraries for IoT devices, experimental for x/exp/io. |
| <b>[sensorbee](https://github.com/sensorbee/sensorbee) | 213 | Lightweight stream processing engine for IoT. |
| <b>[huego](https://github.com/amimof/huego) | 212 | An extensive Philips Hue client library for Go. |
| <b>[iot](https://github.com/vaelen/iot/) | 59 | IoT is a simple framework for implementing a Google IoT Core device. |
| <b>[eywa](https://github.com/xcodersun/eywa) | 55 | Project Eywa is essentially a connection manager that keeps track of connected devices. |
| <b>[periph](https://periph.io/) | - | Peripherals I/O to interface with low-level board facilities. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Job Scheduler

_Libraries for scheduling jobs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gocron](https://github.com/go-co-op/gocron) | 2.2k | Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). |
| <b>[JobRunner](https://github.com/bamzi/jobrunner) | 932 | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| <b>[go-quartz](https://github.com/reugn/go-quartz) | 928 | Simple, zero-dependency scheduling library for Go. |
| <b>[gron](https://github.com/roylee0704/gron) | 904 | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| <b>[jobs](https://github.com/albrow/jobs) | 489 | Persistent and flexible background jobs library. |
| <b>[scheduler](https://github.com/carlescere/scheduler) | 392 | Cronjobs scheduling made easy. |
| <b>[Dagu](https://github.com/dagu-go/dagu) | 272 | No-code workflow executor. it executes DAGs defined in a simple YAML format. |
| <b>[go-cron](https://github.com/rk/go-cron) | 211 | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| <b>[gronx](https://github.com/adhocore/gronx) | 208 | Cron expression parser, task runner and daemon consuming crontab like task list. |
| <b>[clockwerk](https://github.com/onatm/clockwerk) | 121 | Go package to schedule periodic jobs using a simple, fluent syntax. |
| <b>[tasks](https://github.com/madflojo/tasks) | 103 | An easy to use in-process scheduler for recurring tasks in Go. |
| <b>[leprechaun](https://github.com/kilgaloon/leprechaun) | 87 | Job scheduler that supports webhooks, crons and classic scheduling. |
| <b>[goflow](https://github.com/fieldryand/goflow) | 54 | A workflow orchestrator and scheduler for rapid prototyping of ETL/ML/AI pipelines. |
| <b>[cheek](https://github.com/datarootsio/cheek) | 45 | A simple crontab like scheduler that aims to offer a KISS approach to job scheduling. |
| <b>[sched](https://github.com/romshark/sched) | 25 | A job scheduler with the ability to fast-forward time. |
| <b>[cdule](https://github.com/deepaksinghvi/cdule) | 9 | Job scheduler library with database support |
| <b>[cronticker](https://github.com/krayzpipes/cronticker) | 3 | A ticker implementation to support cron schedules. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## JSON

_Libraries for working with JSON._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GJSON](https://github.com/tidwall/gjson) | 11.0k | Get a JSON value with one line of code. |
| <b>[gojson](https://github.com/ChimeraCoder/gojson) | 2.5k | Automatically generate Go (golang) struct definitions from example JSON. |
| <b>[fastjson](https://github.com/valyala/fastjson) | 1.6k | Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. |
| <b>[OjG](https://github.com/ohler55/ojg) | 497 | Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath. |
| <b>[kazaam](https://github.com/Qntfy/kazaam) | 234 | API for arbitrary transformation of JSON documents. |
| <b>[marshmallow](https://github.com/PerimeterX/marshmallow) | 188 | Performant JSON unmarshaling for flexible use cases. |
| <b>[gojq](https://github.com/elgs/gojq) | 182 | JSON query in Golang. |
| <b>[jsondiff](https://github.com/wI2L/jsondiff) | 181 | JSON diff library for Go based on RFC6902 (JSON Patch). |
| <b>[jettison](https://github.com/wI2L/jettison) | 129 | Fast and flexible JSON encoder for Go. |
| <b>[ajson](https://github.com/spyzhov/ajson) | 124 | Abstract JSON for golang with JSONPath support. |
| <b>[gjo](https://github.com/skanehira/gjo) | 110 | Small utility to create JSON objects. |
| <b>[json2go](https://github.com/m-zajac/json2go) | 105 | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| <b>[jsongo](https://github.com/ricardolonga/jsongo) | 103 | Fluent API to make it easier to create Json objects. |
| <b>[JayDiff](https://github.com/yazgazan/jaydiff) | 88 | JSON diff utility written in Go. |
| <b>[jsonf](https://github.com/miolini/jsonf) | 63 | Console tool for highlighted formatting and struct query fetching JSON. |
| <b>[ujson](https://github.com/olvrng/ujson) | 59 | Fast and minimal JSON parser and transformer that works on unstructured JSON. |
| <b>[go-respond](https://github.com/nicklaw5/go-respond) | 48 | Go package for handling common HTTP JSON responses. |
| <b>[mp](https://github.com/sanbornm/mp) | 45 | Simple cli email parser. It currently takes stdin and outputs JSON. |
| <b>[vjson](https://github.com/miladibra10/vjson) | 30 | Go package for validating JSON objects with declaring a JSON schema with fluent API. |
| <b>[jsoncolor](https://github.com/neilotoole/jsoncolor) | 28 | Drop-in replacement for `encoding/json` that outputs colorized JSON. |
| <b>[ask](https://github.com/simonnilsson/ask) | 17 | Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types. |
| <b>[jscan](https://github.com/romshark/jscan) | 14 | High performance zero-allocation JSON iterator. |
| <b>[mapslice-json](https://github.com/mickep76/mapslice-json) | 13 | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| <b>[dynjson](https://github.com/cocoonspace/dynjson) | 12 | Client-customizable JSON formats for dynamic APIs. |
| <b>[go-jsonerror](https://github.com/ddymko/go-jsonerror) | 12 | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| <b>[jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 12 | Go bindings based on the JSON API errors reference. |
| <b>[jsonhal](https://github.com/RichardKnop/jsonhal) | 10 | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| <b>[jzon](https://github.com/zerosnake0/jzon) | 10 | JSON library with standard compatible API/behavior. |
| <b>[epoch](https://github.com/vtopc/epoch) | 9 | Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON. |
| <b>[ej](https://github.com/lucassscaravelli/ej) | 8 | Write and read JSON from different sources succinctly. |
| <b>[jsonic](https://github.com/sinhashubham95/jsonic) | 7 | Utilities to handle and query JSON without defining structs in a type safe manner. |
| <b>[omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) | 4 | Simple JSON parser with validation by condition via golang struct fields tags. |
| <b>[JSON-to-Go](https://mholt.github.io/json-to-go/) | - | Convert JSON to Go struct. |
| <b>[JSON-to-Proto](https://json-to-proto.github.io/) | - | Convert JSON to Protobuf online. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Logging

_Libraries for generating and working with log files._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[logrus](https://github.com/Sirupsen/logrus) | 21.0k | Structured logger for Go. |
| <b>[zap](https://github.com/uber-go/zap) | 17.0k | Fast, structured, leveled logging in Go. |
| <b>[zerolog](https://github.com/rs/zerolog) | 6.7k | Zero-allocation JSON logger. |
| <b>[spew](https://github.com/davecgh/go-spew) | 5.2k | Implements a deep pretty printer for Go data structures to aid in debugging. |
| <b>[lumberjack](https://github.com/natefinch/lumberjack) | 3.5k | Simple rolling logger, implements io.WriteCloser. |
| <b>[glog](https://github.com/golang/glog) | 3.2k | Leveled execution logs for Go. |
| <b>[tail](https://github.com/hpcloud/tail) | 2.4k | Go package striving to emulate the features of the BSD tail program. |
| <b>[seelog](https://github.com/cihub/seelog) | 1.6k | Logging functionality with flexible dispatching, filtering, and formatting. |
| <b>[log](https://github.com/apex/log) | 1.2k | Structured logging package for Go. |
| <b>[log15](https://github.com/inconshreveable/log15) | 1.1k | Simple, powerful logging for Go. |
| <b>[phuslu/log](https://github.com/phuslu/log) | 443 | Structured Logging Made Easy. |
| <b>[onelog](https://github.com/francoispqt/onelog) | 399 | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. |
| <b>[logxi](https://github.com/mgutz/logxi) | 348 | 12-factor app logger that is fast and makes you happy. |
| <b>[logutils](https://github.com/hashicorp/logutils) | 324 | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| <b>[log](https://github.com/go-playground/log) | 280 | Simple, configurable and scalable Structured Logging for Go. |
| <b>[go-logger](https://github.com/apsdehal/go-logger) | 276 | Simple logger of Go Programs, with level handlers. |
| <b>[httpretty](https://github.com/henvic/httpretty) | 270 | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| <b>[sqldb-logger](https://github.com/simukti/sqldb-logger) | 257 | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| <b>[rollingwriter](https://github.com/arthurkiller/rollingWriter) | 239 | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| <b>[glg](https://github.com/kpango/glg) | 168 | glg is simple and fast leveled logging library for Go. |
| <b>[logur](https://github.com/logur/logur) | 166 | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| <b>[logger](https://github.com/azer/logger) | 155 | Minimalistic logging library for Go. |
| <b>[xlog](https://github.com/rs/xlog) | 135 | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| <b>[ozzo-log](https://github.com/go-ozzo/ozzo-log) | 119 | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| <b>[slog](https://github.com/gookit/slog) | 113 | Lightweight, configurable, extensible logger for Go. |
| <b>[log-voyage](https://github.com/firstrow/logvoyage) | 91 | Full-featured logging saas written in golang. |
| <b>[go-cronowriter](https://github.com/utahta/go-cronowriter) | 48 | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| <b>[stdlog](https://github.com/alexcesaro/log) | 44 | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| <b>[gologger](https://github.com/sadlil/gologger) | 40 | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| <b>[gone/log](https://github.com/One-com/gone/tree/master/log) | 40 | Fast, extendable, full-featured, std-lib source compatible log library. |
| <b>[logex](https://github.com/chzyer/logex) | 39 | Golang log lib, supports tracking and level, wrap by standard log lib. |
| <b>[go-log](https://github.com/ian-kent/go-log) | 38 | Log4j implementation in Go. |
| <b>[noodlog](https://github.com/gyozatech/noodlog) | 37 | Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings. |
| <b>[go-log](https://github.com/siddontang/go-log) | 31 | Log lib supports level and multi handlers. |
| <b>[journald](https://github.com/ssgreg/journald) | 31 | Go implementation of systemd Journal's native API for logging. |
| <b>[distillog](https://github.com/amoghe/distillog) | 28 | distilled levelled logging (think of it as stdlib + log levels). |
| <b>[logrusly](https://github.com/sebest/logrusly) | 27 | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| <b>[log](https://github.com/teris-io/log) | 25 | Structured log interface for Go cleanly separates logging facade from its implementation. |
| <b>[mlog](https://github.com/jbrodriguez/mlog) | 25 | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| <b>[gomol](https://github.com/aphistic/gomol) | 18 | Multiple-output, structured logging for Go with extensible logging outputs. |
| <b>[zkits-logger](https://github.com/edoger/zkits-logger) | 18 | A powerful zero-dependency JSON logger. |
| <b>[glo](https://github.com/lajosbencz/glo) | 14 | PHP Monolog inspired logging facility with identical severity levels. |
| <b>[logmatic](https://github.com/borderstech/logmatic) | 14 | Colorized logger for Golang with dynamic log level configuration. |
| <b>[logrusiowriter](https://github.com/cabify/logrusiowriter) | 13 | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| <b>[go-log](https://github.com/subchen/go-log) | 12 | Simple and configurable Logging in Go, with level, formatters and writers. |
| <b>[go-log](https://github.com/pieterclaerhout/go-log) | 9 | A logging library with strack traces, object dumping and optional timestamps. |
| <b>[log](https://github.com/aerogo/log) | 9 | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| <b>[logdump](https://github.com/ewwwwwqm/logdump) | 9 | Package for multi-level logging. |
| <b>[logo](https://github.com/mbndr/logo) | 9 | Golang logger to different configurable writers. |
| <b>[kemba](https://github.com/clok/kemba) | 8 | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |
| <b>[xlog](https://github.com/xfxdev/xlog) | 7 | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| <b>[structy/log](https://github.com/structy/log) | 4 | A simple to use log system, minimalist but with features for debugging and differentiation of messages. |
| <b>[slf4g](https://github.com/echocat/slf4g) | 1 | Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks. |
| <b>[yell](https://github.com/jfcg/yell) | 0 | Yet another minimalistic logging library. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Machine Learning

_Libraries for Machine Learning._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GoLearn](https://github.com/sjwhitworth/golearn) | 8.5k | General Machine Learning library for Go. |
| <b>[gorse](https://github.com/zhenghaoz/gorse) | 6.1k | An offline recommender system backend based on collaborative filtering written in Go. |
| <b>[gorgonia](https://github.com/gorgonia/gorgonia) | 4.6k | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| <b>[m2cgen](https://github.com/BayesWitnesses/m2cgen) | 2.2k | A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support. |
| <b>[tfgo](https://github.com/galeone/tfgo) | 2.0k | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| <b>[gosseract](https://github.com/otiai10/gosseract) | 1.8k | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| <b>[goml](https://github.com/cdipaolo/goml) | 1.4k | On-line Machine Learning in Go. |
| <b>[eaopt](https://github.com/MaxHalford/eaopt) | 808 | An evolutionary optimization library. |
| <b>[bayesian](https://github.com/jbrukh/bayesian) | 739 | Naive Bayesian Classification for Golang. |
| <b>[CloudForest](https://github.com/ryanbressler/CloudForest) | 715 | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| <b>[gobrain](https://github.com/goml/gobrain) | 525 | Neural Networks written in go. |
| <b>[ocrserver](https://github.com/otiai10/ocrserver) | 523 | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| <b>[onnx-go](https://github.com/owulveryck/onnx-go) | 408 | Go Interface to Open Neural Network Exchange (ONNX). |
| <b>[go-deep](https://github.com/patrikeh/go-deep) | 381 | A feature-rich neural network library in Go. |
| <b>[regommend](https://github.com/muesli/regommend) | 299 | Recommendation & collaborative filtering engine. |
| <b>[Goptuna](https://github.com/c-bata/goptuna) | 222 | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| <b>[go-galib](https://github.com/thoj/go-galib) | 192 | Genetic Algorithms library written in Go / golang. |
| <b>[goRecommend](https://github.com/timkaye11/goRecommend) | 189 | Recommendation Algorithms library written in Go. |
| <b>[goga](https://github.com/tomcraven/goga) | 164 | Genetic algorithm library for Go. |
| <b>[shield](https://github.com/eaigner/shield) | 152 | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| <b>[go-fann](https://github.com/white-pony/go-fann) | 110 | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| <b>[goscore](https://github.com/asafschers/goscore) | 82 | Go Scoring API for PMML. |
| <b>[go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) | 81 | Fast and convenient feature processing for low latency machine learning in Go. |
| <b>[gonet](https://github.com/dathoangnd/gonet) | 75 | Neural Network for Go. |
| <b>[libsvm](https://github.com/datastream/libsvm) | 71 | libsvm golang version derived work based on LIBSVM 3.14. |
| <b>[fonet](https://github.com/Fontinalis/fonet) | 69 | A Deep Neural Network library written in Go. |
| <b>[neat](https://github.com/jinyeom/neat) | 65 | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| <b>[neural-go](https://github.com/schuyler/neural-go) | 63 | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| <b>[go-pr](https://github.com/daviddengcn/go-pr) | 61 | Pattern recognition package in Go lang. |
| <b>[Varis](https://github.com/Xamber/Varis) | 48 | Golang Neural Network. |
| <b>[golinear](https://github.com/danieldk/golinear) | 44 | liblinear bindings for Go. |
| <b>[go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 34 | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| <b>[godist](https://github.com/e-dard/godist) | 33 | Various probability distributions, and associated methods. |
| <b>[GoMind](https://github.com/surenderthakran/gomind) | 32 | A simplistic Neural Network Library in Go. |
| <b>[evoli](https://github.com/khezen/evoli) | 24 | Genetic Algorithm and Particle Swarm Optimization library. |
| <b>[randomforest](https://github.com/malaschitz/randomForest) | 23 | Easy to use Random Forest library for Go. |
| <b>[ddt](https://github.com/sgrodriguez/ddt) | 19 | Dynamic decision tree, create trees defining customizable rules. |
| <b>[probab](https://github.com/ThePaw/probab) | 17 | Probability distribution functions. Bayesian inference. Written in pure Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Messaging

_Libraries that implement messaging systems._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sarama](https://github.com/Shopify/sarama) | 9.1k | Go library for Apache Kafka. |
| <b>[gorush](https://github.com/appleboy/gorush) | 6.5k | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| <b>[machinery](https://github.com/RichardKnop/machinery) | 6.4k | Asynchronous task queue/job queue based on distributed message passing. |
| <b>[Centrifugo](https://github.com/centrifugal/centrifugo) | 6.3k | Real-time messaging (Websockets or SockJS) server in Go. |
| <b>[go-socket.io](https://github.com/googollee/go-socket.io) | 4.8k | socket.io library for golang, a realtime application framework. |
| <b>[Benthos](https://github.com/Jeffail/benthos) | 4.7k | A message streaming bridge between a range of protocols. |
| <b>[NATS Go Client](https://github.com/nats-io/nats) | 4.1k | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| <b>[Asynq](https://github.com/hibiken/asynq) | 3.9k | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| <b>[Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) | 3.5k | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| <b>[Mercure](https://github.com/dunglas/mercure) | 3.0k | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| <b>[APNs2](https://github.com/sideshow/apns2) | 2.7k | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| <b>[melody](https://github.com/olahol/melody) | 2.5k | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| <b>[go-nsq](https://github.com/nsqio/go-nsq) | 2.3k | the official Go package for NSQ. |
| <b>[gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 2.0k | gopush-cluster is a go push server cluster. |
| <b>[Beaver](https://github.com/Clivern/Beaver) | 1.4k | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| <b>[Uniqush-Push](https://github.com/uniqush/uniqush-push) | 1.4k | Redis backed unified push service for server-side notifications to mobile devices. |
| <b>[EventBus](https://github.com/asaskevich/EventBus) | 1.2k | The lightweight event bus with async compatibility. |
| <b>[zmq4](https://github.com/pebbe/zmq4) | 1000 | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| <b>[Gollum](https://github.com/trivago/gollum) | 920 | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| <b>[Chanify](https://github.com/chanify/chanify) | 904 | A push notification server send message to your iOS devices. |
| <b>[dbus](https://github.com/godbus/dbus) | 742 | Native Go bindings for D-Bus. |
| <b>[golongpoll](https://github.com/jcuga/golongpoll) | 605 | HTTP longpoll server library that makes web pub-sub simple. |
| <b>[mangos](https://github.com/nanomsg/mangos) | 536 | Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. |
| <b>[amqp](https://github.com/rabbitmq/amqp091-go) | 463 | Go RabbitMQ Client Library. |
| <b>[emitter](https://github.com/olebedev/emitter) | 431 | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| <b>[Glue](https://github.com/desertbit/glue) | 402 | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| <b>[pubsub](https://github.com/tuxychandru/pubsub) | 378 | Simple pubsub package for go. |
| <b>[Bus](https://github.com/mustafaturan/bus) | 272 | Minimalist message bus implementation for internal communication. |
| <b>[Quamina](https://github.com/timbray/quamina) | 238 | Fast pattern-matching for filtering messages and events. |
| <b>[messagebus](https://github.com/vardius/message-bus) | 225 | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| <b>[rabtap](https://github.com/jandelgado/rabtap) | 216 | RabbitMQ swiss army knife cli app. |
| <b>[guble](https://github.com/smancke/guble) | 152 | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| <b>[hub](https://github.com/leandro-lugaresi/hub) | 118 | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| <b>[oplog](https://github.com/dailymotion/oplog) | 112 | Generic oplog/replication system for REST APIs. |
| <b>[rabbus](https://github.com/rafaeljesus/rabbus) | 93 | A tiny wrapper over amqp exchanges and queues. |
| <b>[redisqueue](https://github.com/robinjoseph08/redisqueue) | 86 | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| <b>[drone-line](https://github.com/appleboy/drone-line) | 77 | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| <b>[go-mq](https://github.com/cheshir/go-mq) | 75 | RabbitMQ client with declarative configuration. |
| <b>[nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 74 | A tiny wrapper around NSQ topic and channel. |
| <b>[RapidMQ](https://github.com/sybrexsys/RapidMQ) | 64 | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| <b>[go-notify](https://github.com/TheCreeper/go-notify) | 61 | Native implementation of the freedesktop notification spec. |
| <b>[Commander](https://github.com/jeroenrinzema/commander) | 60 | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| <b>[go-res](https://github.com/jirenius/go-res) | 59 | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| <b>[hare](https://github.com/leozz37/hare) | 49 | A user friendly library for sending messages and listening to TCP sockets. |
| <b>[event](https://github.com/agoalofalife/event) | 47 | Implementation of the pattern observer. |
| <b>[ami](https://github.com/kak-tus/ami) | 23 | Go client to reliable queues based on Redis Cluster Streams. |
| <b>[gosd](https://github.com/alexsniffin/gosd) | 20 | A library for scheduling when to dispatch a message to a channel. |
| <b>[go-vitotrol](https://github.com/maxatome/go-vitotrol) | 19 | Client library to Viessmann Vitotrol web service. |
| <b>[rmqconn](https://github.com/sbabiv/rmqconn) | 19 | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| <b>[jazz](https://github.com/socifi/jazz) | 15 | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| <b>[gaurun-client](https://github.com/osamingo/gaurun-client) | 10 | Gaurun Client written in Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Microsoft Office


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[unioffice](https://github.com/unidoc/unioffice) | 3.5k | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |


<br>

[👆back to top](#catalogue-list)


<br>

### Microsoft Excel

_Libraries for working with Microsoft Excel._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[excelize](https://github.com/xuri/excelize) | 12.0k | Golang library for reading and writing Microsoft Excel&trade; (XLSX) files. |
| <b>[xlsx](https://github.com/tealeg/xlsx) | 5.4k | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| <b>[go-excel](https://github.com/szyhf/go-excel) | 152 | A simple and light reader to read a relate-db-like excel as a table. |
| <b>[xlsx](https://github.com/plandem/xlsx) | 152 | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| <b>[goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 18 | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |
| <b>[exl](https://github.com/go-the-way/exl) | 10 | Excel binding to struct written in Go.(Only supports Go1.18+) |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Miscellaneous


<br>

### Dependency Injection

_Libraries for working with dependency injection._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[google/wire](https://github.com/google/wire) | 8.9k | Automated Initialization in Go. |
| <b>[fx](https://github.com/uber-go/fx) | 3.0k | A dependency injection based application framework for Go (built on top of dig). |
| <b>[dig](https://github.com/uber-go/dig) | 2.7k | A reflection based dependency injection toolkit for Go. |
| <b>[do](https://github.com/samber/do) | 483 | A dependency injection framework based on Generics. |
| <b>[GoLobby/Container](https://github.com/golobby/container) | 373 | GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language. |
| <b>[goioc/di](https://github.com/goioc/di) | 198 | Spring-inspired Dependency Injection Container. |
| <b>[di](https://github.com/goava/di) | 156 | A dependency injection container for go programming language. |
| <b>[dingo](https://github.com/i-love-flamingo/dingo) | 134 | A dependency injection toolkit for Go, based on Guice. |
| <b>[alice](https://github.com/magic003/alice) | 46 | Additive dependency injection container for Golang. |
| <b>[linker](https://github.com/logrange/linker) | 35 | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| <b>[wire](https://github.com/Fs02/wire) | 35 | Strict Runtime Dependency Injection for Golang. |
| <b>[nject](https://github.com/muir/nject) | 18 | A type safe, reflective framework for libraries, tests, http endpoints, and service startup. |
| <b>[gocontainer](https://github.com/vardius/gocontainer) | 15 | Simple Dependency Injection Container. |
| <b>[kinit](https://github.com/go-kata/kinit) | 8 | Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization. |
| <b>[HnH/di](https://github.com/HnH/di) | 4 | DI container library that is focused on clean API and flexibility. |


<br>

[👆back to top](#catalogue-list)


<br>

### Project Layout

_**Unofficial** set of patterns for structuring projects._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[golang-standards/project-layout](https://github.com/golang-standards/project-layout) | 34.0k | Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful. |
| <b>[ardanlabs/service](https://github.com/ardanlabs/service) | 2.4k | A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications. |
| <b>[modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 1.3k | Go application boilerplate and example applying modern practices. |
| <b>[cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 537 | A Go application boilerplate template for quick starting projects following production best practices. |
| <b>[pagoda](https://github.com/mikestefanello/pagoda) | 394 | Rapid, easy full-stack web development starter kit built in Go. |
| <b>[golang-templates/seed](https://github.com/golang-templates/seed) | 281 | Go application GitHub repository template. |
| <b>[go-starter](https://github.com/allaboutapps/go-starter) | 177 | An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers. |
| <b>[go-todo-backend](https://github.com/Fs02/go-todo-backend) | 165 | Go Todo Backend example using modular project layout for product microservice. |
| <b>[scaffold](https://github.com/catchplay/scaffold) | 117 | Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. |
| <b>[go-sample](https://github.com/zitryss/go-sample) | 105 | A sample layout for Go application projects with the real code. |
| <b>[gobase](https://github.com/wajox/gobase) | 30 | A simple skeleton for golang application with basic setup for real golang application. |
| <b>[wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) | 17 | Set of practices and discussions on how to structure Go project layout. |
| <b>[insidieux/inizio](https://github.com/insidieux/inizio) | 11 | Golang project layout generator with plugins. |


<br>

[👆back to top](#catalogue-list)


<br>

### Strings

_Libraries for working with strings._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[xstrings](https://github.com/huandu/xstrings) | 1.1k | Collection of useful string functions ported from other languages. |
| <b>[sttr](https://github.com/abhimanyu003/sttr) | 408 | cross-platform, cli app to perform various operations on string. |
| <b>[strutil](https://github.com/ozgio/strutil) | 180 | String utilities. |
| <b>[gobeam/Stringy](https://github.com/gobeam/Stringy) | 137 | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| <b>[bexp](https://github.com/mkungla/bexp) | 8 | Go implementation of Brace Expansion mechanism to generate arbitrary strings. |
| <b>[go-formatter](https://gitlab.com/tymonx/go-formatter) | - | Implements **replacement fields** surrounded by curly braces `{}` format strings. |


<br>

[👆back to top](#catalogue-list)


<br>

### Uncategorized

_These libraries were placed here because none of the other categories seemed to fit._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gopsutil](https://github.com/shirou/gopsutil) | 8.1k | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| <b>[archiver](https://github.com/mholt/archiver) | 3.6k | Library and command for making and extracting .zip and .tar.gz archives. |
| <b>[gatus](https://github.com/TwinProduction/gatus) | 2.8k | Automated service health dashboard. |
| <b>[gofakeit](https://github.com/brianvoe/gofakeit) | 2.6k | Random data generator written in go. |
| <b>[go-resiliency](https://github.com/eapache/go-resiliency) | 1.6k | Resiliency patterns for golang. |
| <b>[base64Captcha](https://github.com/mojocn/base64Captcha) | 1.5k | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| <b>[gosms](https://github.com/haxpax/gosms) | 1.4k | Your own local SMS gateway in Go that can be used to send SMS. |
| <b>[go-commons-pool](https://github.com/jolestar/go-commons-pool) | 1.1k | Generic object pool for Golang. |
| <b>[llvm](https://github.com/llir/llvm) | 931 | Library for interacting with LLVM IR in pure Go. |
| <b>[shortid](https://github.com/teris-io/shortid) | 787 | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| <b>[health](https://github.com/alexliesenfeld/health) | 520 | A simple and flexible health check library for Go. |
| <b>[stateless](https://github.com/qmuntal/stateless) | 470 | A fluent library for creating state machines. |
| <b>[health](https://github.com/dimiro1/health) | 431 | Easy to use, extensible health check library. |
| <b>[shoutrrr](https://github.com/containrrr/shoutrrr) | 408 | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| <b>[banner](https://github.com/dimiro1/banner) | 403 | Add beautiful banners into your Go applications. |
| <b>[xz](https://github.com/ulikunitz/xz) | 383 | Pure golang package for reading and writing xz-compressed files. |
| <b>[conv](https://github.com/cstockton/go-conv) | 381 | Package conv provides fast and intuitive conversions across Go types. |
| <b>[gountries](https://github.com/pariz/gountries) | 350 | Package that exposes country and subdivision data. |
| <b>[ffmt](https://github.com/go-ffmt/ffmt) | 276 | Beautify data display for Humans. |
| <b>[lk](https://github.com/hyperboloide/lk) | 252 | A simple licensing library for golang. |
| <b>[antch](https://github.com/antchfx/antch) | 234 | A fast, powerful and extensible web crawling & scraping framework. |
| <b>[healthcheck](https://github.com/etherlabsio/healthcheck) | 225 | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| <b>[battery](https://github.com/distatus/battery) | 208 | Cross-platform, normalized battery information library. |
| <b>[go-unarr](https://github.com/gen2brain/go-unarr) | 197 | Decompression library for RAR, TAR, ZIP and 7z archives. |
| <b>[bitio](https://github.com/icza/bitio) | 192 | Highly optimized bit-level Reader and Writer for Go. |
| <b>[stats](https://github.com/go-playground/stats) | 162 | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| <b>[turtle](https://github.com/hackebrot/turtle) | 136 | Emojis for Go. |
| <b>[captcha](https://github.com/steambap/captcha) | 113 | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| <b>[gommit](https://github.com/antham/gommit) | 95 | Analyze git commit messages to ensure they follow defined patterns. |
| <b>[indigo](https://github.com/osamingo/indigo) | 95 | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| <b>[gotoprom](https://github.com/cabify/gotoprom) | 93 | Type-safe metrics builder wrapper library for the official Prometheus client. |
| <b>[morse](https://github.com/alwindoss/morse) | 75 | Library to convert to and from morse code. |
| <b>[persian](https://github.com/mavihq/persian) | 65 | Some utilities for Persian language in go. |
| <b>[faker](https://github.com/pioz/faker) | 63 | Random fake data and struct generator for Go. |
| <b>[pdfgen](https://github.com/hyperboloide/pdfgen) | 57 | HTTP service to generate PDF from Json requests. |
| <b>[gtree](https://github.com/ddddddO/gtree) | 55 | Provide CLI and Package for tree output and directories creation from Markdown or programmatically. |
| <b>[xkg](https://github.com/go-xkg/xkg) | 53 | X Keyboard Grabber. |
| <b>[browscap_go](https://github.com/digitalcrab/browscap_go) | 41 | GoLang Library for [Browser Capabilities Project](https://browscap.org/). |
| <b>[datacounter](https://github.com/miolini/datacounter) | 40 | Go counters for readers/writer/http.ResponseWriter. |
| <b>[sandid](https://github.com/aofei/sandid) | 37 | Every grain of sand on earth has its own ID. |
| <b>[autoflags](https://github.com/artyom/autoflags) | 36 | Go package to automatically define command line flags from struct fields. |
| <b>[url-shortener](https://github.com/pantrif/url-shortener) | 36 | A modern, powerful, and robust URL shortener microservice with mysql support. |
| <b>[gosh](https://github.com/osamingo/gosh) | 29 | Provide Go Statistics Handler, Struct, Measure Method. |
| <b>[xdg](https://github.com/rkoesters/xdg) | 28 | FreeDesktop.org (xdg) Specs implemented in Go. |
| <b>[metrics](https://github.com/pascaldekloe/metrics) | 22 | Library for metrics instrumentation and Prometheus exposition. |
| <b>[shellwords](https://github.com/Wing924/shellwords) | 17 | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| <b>[anagent](https://github.com/mudler/anagent) | 14 | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| <b>[avgRating](https://github.com/kirillDanshin/avgRating) | 11 | Calculate average score and rating based on Wilson Score Equation. |
| <b>[hostutils](https://github.com/Wing924/hostutils) | 10 | A golang library for packing and unpacking FQDNs list. |
| <b>[numa](https://github.com/lrita/numa) | 10 | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |
| <b>[faker](https://github.com/neotoolkit/faker) | 7 | Fake data generator. |
| <b>[openapi](https://github.com/neotoolkit/openapi) | 7 | OpenAPI 3.x parser. |
| <b>[go-commandbus](https://github.com/lana/go-commandbus) | 5 | A slight and pluggable command-bus for Go. |
| <b>[VarHandler](https://github.com/azr/generators/tree/master/varhandler) | 4 | Generate boilerplate http input and output handling. |
| <b>[basexx](https://github.com/bobg/basexx) | 2 | Convert to, from, and between digit strings in various number bases. |
| <b>[varint](https://github.com/chmike/varint) | 2 | A faster varying length integer encoder/decoder than the one provided in the standard library. |
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
| <b>[whatlanggo](https://github.com/abadojack/whatlanggo) | 548 | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| <b>[getlang](https://github.com/rylans/getlang) | 138 | Fast natural language detection package. |
| <b>[guesslanguage](https://github.com/endeveit/guesslanguage) | 55 | Functions to determine the natural language of a unicode text. |
| <b>[detectlanguage](https://github.com/detectlanguage/detectlanguage-go) | 15 | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |


<br>

[👆back to top](#catalogue-list)


<br>

### Morphological Analyzers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[spaGO](https://github.com/nlpodyssey/spago) | 1.2k | Self-contained Machine Learning and Natural Language Processing library in Go. |
| <b>[kagome](https://github.com/ikawaha/kagome) | 664 | JP morphological analyzer written in pure Go. |
| <b>[nlp](https://github.com/Shixzie/nlp) | 379 | Extract values from strings and fill your structs with nlp. |
| <b>[nlp](https://github.com/james-bowman/nlp) | 371 | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| <b>[RAKE.go](https://github.com/afjoseph/RAKE.Go) | 94 | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| <b>[go-stem](https://github.com/agonopol/go-stem) | 68 | Implementation of the porter stemming algorithm. |
| <b>[go2vec](https://github.com/danieldk/go2vec) | 48 | Reader and utility functions for word2vec embeddings. |
| <b>[porter2](https://github.com/zhenjl/porter2) | 45 | Really fast Porter 2 stemmer. |
| <b>[snowball](https://github.com/goodsign/snowball) | 32 | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| <b>[paicehusk](https://github.com/rookii/paicehusk) | 28 | Golang implementation of the Paice/Husk Stemming Algorithm. |
| <b>[govader](https://github.com/jonreiter/govader) | 25 | Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). |
| <b>[golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 19 | Go bindings for the snowball libstemmer library including porter 2. |
| <b>[libtextcat](https://github.com/goodsign/libtextcat) | 11 | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| <b>[porter](https://github.com/a2800276/porter) | 9 | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| <b>[gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) | 8 | Sentiment analyzer using sentiwordnet lexicon in Go. |
| <b>[govader-backend](https://github.com/PIMPfiction/govader_backend) | 2 | Microservice implementation of [GoVader](https://github.com/jonreiter/govader). |
| <b>[spelling-corrector](https://github.com/jorelosorio/spellingcorrector) | 0 | A spelling corrector for the Spanish language or create your own. |


<br>

[👆back to top](#catalogue-list)


<br>

### Slugifiers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[slug](https://github.com/gosimple/slug) | 845 | URL-friendly slugify with multiple languages support. |
| <b>[go-slugify](https://github.com/mozillazg/go-slugify) | 79 | Make pretty slug with multiple languages support. |
| <b>[Slugify](https://github.com/avelino/slugify) | 31 | Go slugify application that handles string. |


<br>

[👆back to top](#catalogue-list)


<br>

### Tokenizers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[prose](https://github.com/jdkato/prose) | 2.9k | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| <b>[gse](https://github.com/go-ego/gse) | 2.0k | Go efficient text segmentation; support english, chinese, japanese and other. |
| <b>[gojieba](https://github.com/yanyiwu/gojieba) | 1.9k | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| <b>[sentences](https://github.com/neurosnap/sentences) | 327 | Sentence tokenizer:  converts text into a list of sentences. |
| <b>[segment](https://github.com/blevesearch/segment) | 70 | Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/) |
| <b>[textcat](https://github.com/pebbe/textcat) | 67 | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| <b>[MMSEGO](https://github.com/awsong/MMSEGO) | 61 | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| <b>[stemmer](https://github.com/dchest/stemmer) | 51 | Stemmer packages for Go programming language. Includes English and German stemmers. |
| <b>[gotokenizer](https://github.com/xujiajun/gotokenizer) | 14 | A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) |
| <b>[shamoji](https://github.com/osamingo/shamoji) | 12 | The shamoji is word filtering package written in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Translation


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-i18n](https://github.com/nicksnyder/go-i18n/) | 2.1k | Package and an accompanying tool to work with localized text. |
| <b>[go-pinyin](https://github.com/mozillazg/go-pinyin) | 1.2k | CN Hanzi to Hanyu Pinyin converter. |
| <b>[gotext](https://github.com/leonelquinteros/gotext) | 348 | GNU gettext utilities for Go. |
| <b>[go-localize](https://github.com/m1/go-localize) | 40 | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| <b>[iuliia-go](https://github.com/mehanizm/iuliia-go) | 30 | Transliterate Cyrillic → Latin in every possible way. |
| <b>[go-mystem](https://github.com/dveselov/mystem) | 28 | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| <b>[icu](https://github.com/goodsign/icu) | 20 | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| <b>[t](https://github.com/youthlin/t) | 11 | Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template. |
| <b>[spreak](https://github.com/vorlif/spreak) | 7 | Flexible translation and humanization library for Go, based on the concepts behind gettext. |


<br>

[👆back to top](#catalogue-list)


<br>

### Transliteration


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-unidecode](https://github.com/mozillazg/go-unidecode) | 94 | ASCII transliterations of Unicode text. |
| <b>[gounidecode](https://github.com/fiam/gounidecode) | 75 | Unicode transliterator (also known as unidecode) for Go. |
| <b>[transliterator](https://github.com/alexsergivan/transliterator) | 24 | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| <b>[enca](https://github.com/endeveit/enca) | 11 | Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Networking

_Libraries for working with various layers of the network._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fasthttp](https://github.com/valyala/fasthttp) | 18.0k | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| <b>[kcptun](https://github.com/xtaci/kcptun) | 13.0k | Extremely simple & fast udp tunnel based on KCP protocol. |
| <b>[webrtc](https://github.com/pions/webrtc) | 9.7k | A pure Go implementation of the WebRTC API. |
| <b>[quic-go](https://github.com/lucas-clemente/quic-go) | 7.1k | An implementation of the QUIC protocol in pure Go. |
| <b>[gnet](https://github.com/panjf2000/gnet) | 6.8k | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| <b>[dns](https://github.com/miekg/dns) | 6.5k | Go library for working with DNS. |
| <b>[gopacket](https://github.com/google/gopacket) | 5.0k | Go library for packet processing with libpcap bindings. |
| <b>[HTTPLab](https://github.com/gchaincl/httplab) | 3.8k | HTTPLabs let you inspect HTTP requests and forge responses. |
| <b>[kcp-go](https://github.com/xtaci/kcp-go) | 3.4k | KCP - Fast and Reliable ARQ Protocol. |
| <b>[gobgp](https://github.com/osrg/gobgp) | 2.9k | BGP implemented in the Go Programming Language. |
| <b>[netpoll](https://github.com/cloudwego/netpoll) | 2.9k | A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance. |
| <b>[ssh](https://github.com/gliderlabs/ssh) | 2.7k | Higher-level API for building SSH servers (wraps crypto/ssh). |
| <b>[fortio](https://github.com/fortio/fortio) | 2.6k | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| <b>[gev](https://github.com/Allenxuxu/gev) | 1.5k | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| <b>[water](https://github.com/songgao/water) | 1.5k | Simple TUN/TAP library. |
| <b>[go-getter](https://github.com/hashicorp/go-getter) | 1.4k | Go library for downloading files or directories from various sources using a URL. |
| <b>[NFF-Go](https://github.com/intel-go/nff-go) | 1.2k | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| <b>[sftp](https://github.com/pkg/sftp) | 1.2k | Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>. |
| <b>[grab](https://github.com/cavaliercoder/grab) | 1.1k | Go package for managing file downloads. |
| <b>[ftp](https://github.com/jlaffaye/ftp) | 975 | Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959). |
| <b>[mdns](https://github.com/hashicorp/mdns) | 896 | Simple mDNS (Multicast DNS) client/server library in Golang. |
| <b>[gosnmp](https://github.com/soniah/gosnmp) | 879 | Native Go library for performing SNMP actions. |
| <b>[vssh](https://github.com/yahoo/vssh) | 857 | Go library for building network and server automation over SSH protocol. |
| <b>[nbio](https://github.com/lesismal/nbio) | 743 | Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. |
| <b>[cidranger](https://github.com/yl2chen/cidranger) | 735 | Fast IP to CIDR lookup for Go. |
| <b>[gmqtt](https://github.com/DrmagicE/gmqtt) | 712 | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| <b>[lhttp](https://github.com/fanux/lhttp) | 676 | Powerful websocket framework, build your IM server more easily. |
| <b>[peerdiscovery](https://github.com/schollz/peerdiscovery) | 554 | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| <b>[go-stun](https://github.com/ccding/go-stun) | 511 | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| <b>[gotcp](https://github.com/gansidui/gotcp) | 495 | Go package for quickly writing tcp applications. |
| <b>[stun](https://github.com/go-rtc/stun) | 488 | Go implementation of RFC 5389 STUN protocol. |
| <b>[gaio](https://github.com/xtaci/gaio) | 449 | High performance async-io networking for Golang in proactor mode. |
| <b>[gopcap](https://github.com/akrennmair/gopcap) | 448 | Go wrapper for libpcap. |
| <b>[easytcp](https://github.com/DarthPestilane/easytcp) | 447 | A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful. |
| <b>[raw](https://github.com/mdlayher/raw) | 423 | Package raw enables reading and writing data at the device driver level for a network interface. |
| <b>[tcp_server](https://github.com/firstrow/tcp_server) | 417 | Go library for building tcp servers faster. |
| <b>[winrm](https://github.com/masterzen/winrm) | 371 | Go WinRM client to remotely execute commands on Windows machines. |
| <b>[ftpserverlib](https://github.com/fclairamb/ftpserverlib) | 325 | Fully featured FTP server library. |
| <b>[arp](https://github.com/mdlayher/arp) | 292 | Package arp implements the ARP protocol, as described in RFC 826. |
| <b>[buffstreams](https://github.com/stabbycutyou/buffstreams) | 249 | Streaming protocolbuffer data over TCP made easy. |
| <b>[ethernet](https://github.com/mdlayher/ethernet) | 242 | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| <b>[gNxI](https://github.com/google/gnxi) | 219 | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| <b>[dnsmonster](https://github.com/mosajjal/dnsmonster) | 206 | Passive DNS Capture/Monitoring Framework. |
| <b>[jazigo](https://github.com/udhos/jazigo) | 181 | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| <b>[utp](https://github.com/anacrolix/utp) | 162 | Go uTP micro transport protocol implementation. |
| <b>[canopus](https://github.com/zubairhamed/canopus) | 148 | CoAP Client/Server implementation (RFC 7252). |
| <b>[sslb](https://github.com/eduardonunesp/sslb) | 141 | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| <b>[xtcp](https://github.com/xfxdev/xtcp) | 136 | TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. |
| <b>[iplib](https://github.com/c-robinson/iplib) | 88 | Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html) |
| <b>[ether](https://github.com/songgao/ether) | 77 | Cross-platform Go package for sending and receiving ethernet frames. |
| <b>[dhcp6](https://github.com/mdlayher/dhcp6) | 75 | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| <b>[packet](https://github.com/aerogo/packet) | 73 | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| <b>[gldap](https://github.com/jimlambrt/gldap) | 71 | gldap provides an ldap server implementation and you provide handlers for its ldap operations. |
| <b>[go-powerdns](https://github.com/joeig/go-powerdns) | 60 | PowerDNS API bindings for Golang. |
| <b>[linkio](https://github.com/ian-kent/linkio) | 52 | Network link speed simulation for Reader/Writer interfaces. |
| <b>[portproxy](https://github.com/aybabtme/portproxy) | 50 | Simple TCP proxy which adds CORS support to API's which don't support it. |
| <b>[panoptes-stream](https://github.com/yahoo/panoptes-stream) | 36 | A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT). |
| <b>[fullproxy](https://github.com/shoriwe/fullproxy) | 30 | A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols. |
| <b>[graval](https://github.com/koofr/graval) | 27 | Experimental FTP server framework. |
| <b>[golibwireshark](https://github.com/sunwxg/golibwireshark) | 25 | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| <b>[publicip](https://github.com/polera/publicip) | 25 | Package publicip returns your public facing IPv4 address (internet egress). |
| <b>[gohooks](https://github.com/averageflow/gohooks) | 17 | GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server. |
| <b>[httpproxy](https://github.com/wzshiming/httpproxy) | 15 | HTTP proxy handler and dialer. |
| <b>[goshark](https://github.com/sunwxg/goshark) | 14 | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| <b>[tspool](https://github.com/two/tspool) | 13 | A TCP Library use worker pool to improve performance and protect your server. |
| <b>[llb](https://github.com/kirillDanshin/llb) | 12 | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| <b>[mqttPaho](https://eclipse.org/paho/clients/golang/) | - | The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets. |


<br>

[👆back to top](#catalogue-list)


<br>

### HTTP Clients

_Libraries for making HTTP requests._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[resty](https://github.com/go-resty/resty) | 6.5k | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| <b>[req](https://github.com/imroc/req) | 2.5k | Simple Go HTTP client with Black Magic (Less code and More efficiency). |
| <b>[heimdall](https://github.com/gojektech/heimdall) | 2.3k | An enhanced http client with retry and hystrix capabilities. |
| <b>[grequests](https://github.com/levigross/grequests) | 1.9k | A Go "clone" of the great and famous Requests library. |
| <b>[sling](https://github.com/dghubble/sling) | 1.5k | Sling is a Go HTTP client library for creating and sending API requests. |
| <b>[go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) | 1.3k | Retryable HTTP client in Go. |
| <b>[gentleman](https://github.com/h2non/gentleman) | 962 | Full-featured plugin-driven HTTP client library. |
| <b>[pester](https://github.com/sethgrid/pester) | 596 | Go HTTP client calls with retries, backoff, and concurrency. |
| <b>[requests](https://github.com/carlmjohnson/requests) | 400 | HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools. |
| <b>[go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) | 256 | Get easily stdlib HTTP client, which does not share any state with other clients. |
| <b>[request](https://github.com/monaco-io/request) | 210 | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| <b>[go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) | 60 | Go http.RoundTripper that emits open telemetry metrics for HTTP requests. |
| <b>[go-http-client](https://github.com/bozd4g/go-http-client) | 41 | Make http calls simply and easily. |
| <b>[rq](https://github.com/ddo/rq) | 40 | A nicer interface for golang stdlib HTTP client. |
| <b>[httpretry](https://github.com/ybbus/httpretry) | 21 | Enriches the default go HTTP client with retry functionality. |
| <b>[go-req](https://github.com/wenerme/go-req) | 15 | Declarative golang HTTP client. |
| <b>[httpc](https://github.com/valord577/httpc) | 4 | A customizable and simple HTTP client library. Only depend on the stdlib HTTP client. |
| <b>[go-zoox/fetch](https://github.com/go-zoox/fetch) | 2 | A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## OpenGL

_Libraries for using OpenGL in Go._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[glfw](https://github.com/go-gl/glfw) | 1.3k | Go bindings for GLFW 3. |
| <b>[gl](https://github.com/go-gl/gl) | 917 | Go bindings for OpenGL (generated via glow). |
| <b>[mathgl](https://github.com/go-gl/mathgl) | 448 | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| <b>[goxjs/gl](https://github.com/goxjs/gl) | 158 | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| <b>[goxjs/glfw](https://github.com/goxjs/glfw) | 76 | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| <b>[go-glmatrix](https://github.com/technohippy/go-glmatrix) | 4 | Go port of [glMatrix](https://glmatrix.net/) library. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## ORM

_Libraries that implement Object-Relational Mapping or datamapping techniques._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GORM](https://github.com/go-gorm/gorm) | 29.0k | The fantastic ORM library for Golang, aims to be developer friendly. |
| <b>[ent](https://github.com/facebook/ent) | 11.0k | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| <b>[go-pg](https://github.com/go-pg/pg) | 5.2k | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| <b>[SQLBoiler](https://github.com/volatiletech/sqlboiler) | 5.1k | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| <b>[gorp](https://github.com/go-gorp/gorp) | 3.6k | Go Relational Persistence, ORM-ish library for Go. |
| <b>[upper.io/db](https://github.com/upper/db) | 3.1k | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| <b>[gormt](https://github.com/xxjwxc/gormt) | 2.0k | Mysql database to golang gorm struct. |
| <b>[Prisma](https://github.com/prisma/prisma-client-go) | 1.3k | Prisma Client Go, Typesafe database access for Go. |
| <b>[reform](https://github.com/go-reform/reform) | 1.3k | Better ORM for Go, based on non-empty interfaces and code generation. |
| <b>[pop/soda](https://github.com/gobuffalo/pop) | 1.2k | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| <b>[go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 823 | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| <b>[go-queryset](https://github.com/jirfag/go-queryset) | 671 | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| <b>[rel](https://github.com/go-rel/rel) | 556 | Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. |
| <b>[Zoom](https://github.com/albrow/zoom) | 291 | Blazing-fast datastore and querying engine built on Redis. |
| <b>[go-sql](https://github.com/rushteam/gosql) | 163 | A easy ORM for mysql. |
| <b>[grimoire](https://github.com/Fs02/grimoire) | 157 | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| <b>[go-store](https://github.com/gosuri/go-store) | 108 | Simple and fast Redis backed key-value store library for Go. |
| <b>[golobby/orm](https://github.com/golobby/orm) | 104 | Simple, fast, type-safe, generic orm for developer happiness. |
| <b>[go-firestorm](https://github.com/jschoedt/go-firestorm) | 35 | A simple ORM for Google/Firebase Cloud Firestore. |
| <b>[cacheme](https://github.com/Yiling-J/cacheme-go) | 21 | Schema based, typed Redis caching/memoize framework for Go. |
| <b>[marlow](https://github.com/marlow/marlow) | 11 | Generated ORM from project structs for compile time safety assurances. |
| <b>[lore](https://github.com/abrahambotros/lore) | 10 | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
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
| <b>[goop](https://github.com/nitrous-io/goop) | 776 | Simple dependency manager for Go (golang), inspired by Bundler. |
| <b>[modgv](https://github.com/lucasepe/modgv) | 410 | Converts 'go mod graph' output into Graphviz's DOT language. |
| <b>[nut](https://github.com/jingweno/nut) | 236 | Vendor Go dependencies. |
| <b>[johnny-deps](https://github.com/VividCortex/johnny-deps) | 212 | Minimal dependency version using Git. |
| <b>[mvn-golang](https://github.com/raydac/mvn-golang) | 143 | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| <b>[VenGO](https://github.com/DamnWidget/VenGO) | 123 | create and manage exportable isolated go virtual environments. |
| <b>[gop](https://github.com/lunny/gop) | 48 | Build and manage your Go applications out of GOPATH. |
| <b>[go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) | - | Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules. |
| <b>[vgo](https://go.googlesource.com/vgo/) | - | Versioned Go. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Performance


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[jaeger](https://github.com/jaegertracing/jaeger) | 16.0k | A distributed tracing system. |
| <b>[pixie](https://github.com/pixie-labs/pixie) | 3.7k | No instrumentation tracing for Golang applications via eBPF. |
| <b>[statsviz](https://github.com/arl/statsviz) | 1.9k | Live visualization of your Go application runtime statistics. |
| <b>[profile](https://github.com/pkg/profile) | 1.8k | Simple profiling support package for Go. |
| <b>[tracer](https://github.com/kamilsk/tracer) | 65 | Simple, lightweight tracing. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Query Language


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[graphql-go](https://github.com/graphql-go/graphql) | 8.7k | Implementation of GraphQL for Go. |
| <b>[gqlgen](https://github.com/99designs/gqlgen) | 8.0k | go generate based graphql server library. |
| <b>[graphql](https://github.com/neelance/graphql-go) | 4.2k | GraphQL server with a focus on ease of use. |
| <b>[dasel](https://github.com/tomwright/dasel) | 3.6k | Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. |
| <b>[gojsonq](https://github.com/thedevsaddam/gojsonq) | 1.9k | A simple Go package to Query over JSON Data. |
| <b>[rql](https://github.com/a8m/rql) | 261 | Resource Query Language for REST API. |
| <b>[jsonql](https://github.com/elgs/jsonql) | 254 | JSON query expression library in Golang. |
| <b>[jsonslice](https://github.com/bhmj/jsonslice) | 68 | Jsonpath queries with advanced filters. |
| <b>[graphql](https://github.com/tmc/graphql) | 55 | graphql parser + utilities. |
| <b>[api-fu](https://github.com/ccbrown/api-fu) | 43 | Comprehensive GraphQL implementation. |
| <b>[rqp](https://github.com/timsolov/rest-query-parser) | 43 | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| <b>[goven](https://github.com/SeldonIO/goven) | 36 | A drop-in query language for any database schema. |
| <b>[straf](https://github.com/SonicRoshan/straf) | 32 | Easily Convert Golang structs to GraphQL objects. |
| <b>[jsonpath](https://github.com/AsaiYusuke/jsonpath) | 10 | A query library for retrieving part of JSON based on JSONPath syntax. |
| <b>[gws](https://github.com/Zaba505/gws) | 4 | Apollos' "GraphQL over Websocket" client and server implementation. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Resource Embedding


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[statik](https://github.com/rakyll/statik) | 3.5k | Embeds static files into a Go executable. |
| <b>[packr](https://github.com/gobuffalo/packr) | 3.4k | The simple and easy way to embed static files into Go binaries. |
| <b>[go.rice](https://github.com/GeertJohan/go.rice) | 2.3k | go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. |
| <b>[vfsgen](https://github.com/shurcooL/vfsgen) | 947 | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| <b>[esc](https://github.com/mjibson/esc) | 622 | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| <b>[fileb0x](https://github.com/UnnoTed/fileb0x) | 613 | Simple tool to embed files in go with focus on "customization" and ease to use. |
| <b>[go-resources](https://github.com/omeid/go-resources) | 175 | Unfancy resources embedding with Go. |
| <b>[statics](https://github.com/go-playground/statics) | 64 | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| <b>[templify](https://github.com/wlbr/templify) | 27 | Embed external template files into Go code to create single file binaries. |
| <b>[rebed](https://github.com/soypat/rebed) | 22 | Recreate folder structures and files from Go 1.16's `embed.FS` type |
| <b>[debme](https://github.com/leaanthony/debme) | 20 | Create an `embed.FS` from an existing `embed.FS` subdirectory. |
| <b>[mule](https://github.com/wlbr/mule) | 11 | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Science and Data Analysis

_Libraries for scientific computing and data analyzing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gonum](https://github.com/gonum/gonum) | 6.0k | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| <b>[stats](https://github.com/montanaflynn/stats) | 2.5k | Statistics package with common functions missing from the Golang standard library. |
| <b>[gonum/plot](https://github.com/gonum/plot) | 2.2k | gonum/plot provides an API for building and drawing plots in Go. |
| <b>[gosl](https://github.com/cpmech/gosl) | 1.7k | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| <b>[streamtools](https://github.com/nytlabs/streamtools) | 1.3k | general purpose, graphical tool for dealing with streams of data. |
| <b>[dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 864 | Dataframes for machine-learning and statistics (similar to pandas). |
| <b>[go-dsp](https://github.com/mjibson/go-dsp) | 785 | Digital Signal Processing for Go. |
| <b>[chart](https://github.com/vdobler/chart) | 734 | Simple Chart Plotting library for Go. Supports many graphs types. |
| <b>[goraph](https://github.com/gyuho/goraph) | 692 | Pure Go graph theory library(data structure, algorithm visualization). |
| <b>[graph](https://github.com/yourbasic/graph) | 570 | Library of basic graph algorithms. |
| <b>[orb](https://github.com/paulmach/orb) | 561 | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| <b>[ewma](https://github.com/VividCortex/ewma) | 389 | Exponentially-weighted moving averages. |
| <b>[calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 354 | Calendar heatmap in plain Go inspired by Github contribution activity. |
| <b>[gohistogram](https://github.com/VividCortex/gohistogram) | 166 | Approximate histograms for data streams. |
| <b>[TextRank](https://github.com/DavidBelicza/TextRank) | 161 | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| <b>[sparse](https://github.com/james-bowman/sparse) | 132 | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| <b>[go-estimate](https://github.com/milosgajdos/go-estimate) | 97 | State estimation and filtering algorithms in Go. |
| <b>[pagerank](https://github.com/alixaxel/pagerank) | 75 | Weighted PageRank algorithm implemented in Go. |
| <b>[jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) | 58 | Tool to manipulate JSONL graphs with graphviz support. |
| <b>[geom](https://github.com/skelterjohn/geom) | 51 | 2D geometry for golang. |
| <b>[evaler](https://github.com/soniah/evaler) | 49 | Simple floating point arithmetic expression evaluator. |
| <b>[triangolatte](https://github.com/tchayen/triangolatte) | 29 | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| <b>[decimal](https://github.com/db47h/decimal) | 27 | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| <b>[goent](https://github.com/kzahedi/goent) | 27 | GO Implementation of Entropy Measures. |
| <b>[piecewiselinear](https://github.com/sgreben/piecewiselinear) | 22 | Tiny linear interpolation library. |
| <b>[GoStats](https://github.com/OGFris/GoStats) | 20 | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| <b>[godesim](https://github.com/soypat/godesim) | 19 | Extended/multivariable ODE solver framework for event-based simulations with simple API. |
| <b>[ode](https://github.com/ChristopherRabotin/ode) | 17 | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| <b>[PiHex](https://github.com/claygod/PiHex) | 17 | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| <b>[assocentity](https://github.com/ndabAP/assocentity) | 8 | Package assocentity returns the average distance from words to a given entity. |
| <b>[rootfinding](https://github.com/khezen/rootfinding) | 7 | root-finding algorithms library for finding roots of quadratic functions. |
| <b>[go-gt](https://github.com/ThePaw/go-gt) | 6 | Graph theory algorithms written in "Go" language. |
| <b>[bradleyterry](https://github.com/seanhagen/bradleyterry) | 5 | Provides a Bradley-Terry Model for pairwise comparisons. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Security

_Libraries that are used to help make your application more secure._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[age](https://github.com/FiloSottile/age) | 11.0k | A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. |
| <b>[lego](https://github.com/go-acme/lego) | 5.5k | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| <b>[CertMagic](https://github.com/caddyserver/certmagic) | 4.1k | Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal. |
| <b>[Cameradar](https://github.com/Ullaakut/cameradar) | 3.0k | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| <b>[memguard](https://github.com/awnumar/memguard) | 2.2k | A pure Go library for handling sensitive values in memory. |
| <b>[secure](https://github.com/unrolled/secure) | 2.0k | HTTP middleware for Go that facilitates some quick security wins. |
| <b>[acmetool](https://github.com/hlandau/acme) | 1.9k | ACME (Let's Encrypt) client tool with automatic renewal. |
| <b>[themis](https://github.com/cossacklabs/themis) | 1.6k | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| <b>[acra](https://github.com/cossacklabs/acra) | 1000 | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| <b>[Coraza](https://github.com/corazawaf/coraza) | 627 | Enterprise-ready, modsecurity and OWASP CRS compatible WAF library. |
| <b>[nacl](https://github.com/kevinburke/nacl) | 527 | Go implementation of the NaCL set of API's. |
| <b>[ssh-vault](https://github.com/ssh-vault/ssh-vault) | 355 | encrypt/decrypt using ssh keys. |
| <b>[go-password-validator](https://github.com/lane-c-wagner/go-password-validator) | 349 | Password validator based on raw cryptographic entropy values. |
| <b>[optimus-go](https://github.com/pjebs/optimus-go) | 318 | ID hashing and Obfuscation using Knuth's Algorithm. |
| <b>[firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 317 | A rest application to dynamically update firewalld rules on a linux server. |
| <b>[BadActor](https://github.com/jaredfolkins/badactor) | 309 | In-memory, application-driven jailer built in the spirit of fail2ban. |
| <b>[dongle](https://github.com/golang-module/dongle) | 276 | A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption. |
| <b>[go-yara](https://github.com/hillu/go-yara) | 268 | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| <b>[passlib](https://github.com/hlandau/passlib) | 268 | Futureproof password hashing library. |
| <b>[simple-scrypt](https://github.com/elithrar/simple-scrypt) | 180 | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| <b>[argon2pw](https://github.com/raja/argon2pw) | 88 | Argon2 password hash generation with constant-time password comparison. |
| <b>[goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 51 | A probably paranoid package for securely hashing and encrypting passwords. |
| <b>[go-generate-password](https://github.com/m1/go-generate-password) | 44 | Password generator that can be used on the cli or as a library. |
| <b>[go-htpasswd](https://github.com/tg123/go-htpasswd) | 26 | Apache htpasswd Parser for Go. |
| <b>[secureio](https://github.com/xaionaro-go/secureio) | 25 | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| <b>[certificates](https://github.com/mvmaasakkers/certificates) | 23 | An opinionated tool for generating tls certificates. |
| <b>[argon2-hashing](https://github.com/andskur/argon2-hashing) | 17 | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| <b>[goArgonPass](https://github.com/dwin/goArgonPass) | 15 | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
| <b>[sslmgr](https://github.com/adrianosela/sslmgr) | 14 | SSL certificates made easy with a high level wrapper around acme/autocert. |
| <b>[secret](https://github.com/rsjethani/secret) | 12 | Prevent your secrets from leaking into logs, std* etc. |
| <b>[autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) | - | Auto provision Let's Encrypt certificates and start a TLS server. |
| <b>[Interpol](https://bitbucket.org/vahidi/interpol) | - | Rule-based data generator for fuzzing and penetration testing. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Serialization

_Libraries and tools for binary serialization._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[jsoniter](https://github.com/json-iterator/go) | 11.0k | High-performance 100% compatible drop-in replacement of "encoding/json". |
| <b>[goprotobuf](https://github.com/golang/protobuf) | 8.6k | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| <b>[mapstructure](https://github.com/mitchellh/mapstructure) | 6.0k | Go library for decoding generic map values into native Go structures. |
| <b>[gogoprotobuf](https://github.com/gogo/protobuf) | 5.4k | Protocol Buffers for Go with Gadgets. |
| <b>[go-codec](https://github.com/ugorji/go) | 1.7k | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| <b>[csvutil](https://github.com/jszwec/csvutil) | 738 | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| <b>[colfer](https://github.com/pascaldekloe/colfer) | 673 | Code generation for the Colfer binary format. |
| <b>[cbor](https://github.com/fxamacker/cbor) | 474 | Small, safe, and easy CBOR encoding and decoding library. |
| <b>[go-capnproto](https://github.com/glycerine/go-capnproto) | 282 | Cap'n Proto library and parser for go. |
| <b>[php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 154 | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| <b>[structomap](https://github.com/tuvistavie/structomap) | 134 | Library to easily and dynamically generate maps from static structures. |
| <b>[bambam](https://github.com/glycerine/bambam) | 64 | generator for Cap'n Proto schemas from go. |
| <b>[binstruct](https://github.com/ghostiam/binstruct) | 57 | Golang binary decoder for mapping data into the structure. |
| <b>[asn1](https://github.com/PromonLogicalis/asn1) | 51 | Asn.1 BER and DER encoding library for golang. |
| <b>[bel](https://github.com/32leaves/bel) | 26 | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| <b>[fwencoder](https://github.com/o1egl/fwencoder) | 20 | Fixed width file parser (encoding and decoding library) for Go. |
| <b>[pletter](https://github.com/vimeda/pletter) | 18 | A standard way to wrap a proto message for message brokers. |
| <b>[elastic](https://github.com/epiclabs-io/elastic) | 16 | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| <b>[fixedwidth](https://github.com/huydang284/fixedwidth) | 6 | Fixed-width text formatting (UTF-8 supported). |
| <b>[unitpacking](https://github.com/recolude/unitpacking) | 4 | Library to pack unit vectors into as fewest bytes as possible. |
| <b>[go-lctree](https://github.com/sbourlon/go-lctree) | 3 | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Server Applications


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Caddy](https://github.com/caddyserver/caddy) | 42.0k | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| <b>[etcd](https://github.com/coreos/etcd) | 41.0k | Highly-available key value store for shared configuration and service discovery. |
| <b>[minio](https://github.com/minio/minio) | 35.0k | Minio is a distributed object storage server. |
| <b>[RoadRunner](https://github.com/spiral/roadrunner) | 6.7k | High-performance PHP application server, load-balancer and process manager. |
| <b>[Easegress](https://github.com/megaease/easegress) | 4.6k | A cloud native high availability/performance traffic orchestration system with observability and extensibility. |
| <b>[SFTPGo](https://github.com/drakkan/sftpgo) | 4.6k | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| <b>[devd](https://github.com/cortesi/devd) | 3.3k | Local webserver for developers. |
| <b>[algernon](https://github.com/xyproto/algernon) | 2.1k | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| <b>[Fider](https://github.com/getfider/fider) | 2.0k | Fider is an open platform to collect and organize customer feedback. |
| <b>[Flagr](https://github.com/checkr/flagr) | 2.0k | Flagr is an open-source feature flagging and A/B testing service. |
| <b>[flipt](https://github.com/markphelps/flipt) | 1.9k | A self contained feature flag solution written in Go and Vue.js |
| <b>[discovery](https://github.com/Bilibili/discovery) | 1.7k | A registry for resilient mid-tier load balancing and failover. |
| <b>[Trickster](https://github.com/tricksterproxy/trickster) | 1.7k | HTTP reverse proxy cache and time series accelerator. |
| <b>[Wish](https://github.com/charmbracelet/wish) | 1.5k | Make SSH apps, just like that! |
| <b>[jackal](https://github.com/ortuman/jackal) | 1.3k | An XMPP server written in Go. |
| <b>[go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) | 492 | A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it. |
| <b>[Euterpe](https://github.com/ironsmile/euterpe) | 420 | Self-hosted music streaming server with built-in web UI and REST API. |
| <b>[dummy](https://github.com/neotoolkit/dummy) | 158 | Run mock server based off an API contract with one command. |
| <b>[dudeldu](https://github.com/krotik/dudeldu) | 136 | A simple SHOUTcast server. |
| <b>[lets-proxy2](https://github.com/rekby/lets-proxy2) | 64 | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| <b>[go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) | 61 | Simple Reverse Proxy with Caching, written in Go, using Redis. |
| <b>[cortex-tenant](https://github.com/blind-oracle/cortex-tenant) | 52 | Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels. |
| <b>[psql-streamer](https://github.com/blind-oracle/psql-streamer) | 41 | Stream database events from PostgreSQL to Kafka. |
| <b>[nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 32 | Nginx log parser and exporter to Prometheus. |
| <b>[simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) | 27 | Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management. |
| <b>[protoxy](https://github.com/camgraff/protoxy) | 24 | A proxy server that converts JSON request bodies to Protocol Buffers. |
| <b>[Moxy](https://github.com/sinhashubham95/moxy) | 7 | Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint. |
| <b>[riemann-relay](https://github.com/blind-oracle/riemann-relay) | 1 | Relay to load-balance Riemann events and/or convert them to Carbon. |
| <b>[consul](https://www.consul.io/) | - | Consul is a tool for service discovery, monitoring and configuration. |
| <b>[nsq](https://nsq.io/) | - | A realtime distributed messaging platform. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Stream Processing

_Libraries and tools for stream processing and reactive programming._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-streams](https://github.com/reugn/go-streams) | 1000 | Go stream processing library. |
| <b>[machine](https://github.com/whitaker-io/machine) | 113 | Go library for writing and generating stream workers with built in metrics and traceability. |
| <b>[stream](https://github.com/youthlin/stream) | 64 | Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... |
| <b>[goio](https://github.com/primetalk/goio) | 41 | An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Template Engines

_Libraries and tools for templating and lexing._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sprig](https://github.com/Masterminds/sprig) | 3.1k | Useful template functions for Go templates. |
| <b>[quicktemplate](https://github.com/valyala/quicktemplate) | 2.5k | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| <b>[pongo2](https://github.com/flosch/pongo2) | 2.3k | Django-like template-engine for Go. |
| <b>[jet](https://github.com/CloudyKit/jet) | 947 | Jet template engine. |
| <b>[Razor](https://github.com/sipin/gorazor) | 799 | Razor view engine for Golang. |
| <b>[maroto](https://github.com/johnfercher/maroto) | 716 | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| <b>[fasttemplate](https://github.com/valyala/fasttemplate) | 625 | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/). |
| <b>[ego](https://github.com/benbjohnson/ego) | 529 | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| <b>[raymond](https://github.com/aymerick/raymond) | 489 | Complete handlebars implementation in Go. |
| <b>[goview](https://github.com/foolin/goview) | 292 | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| <b>[liquid](https://github.com/osteele/liquid) | 167 | Go implementation of Shopify Liquid templates. |
| <b>[Soy](https://github.com/robfig/soy) | 166 | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| <b>[extemplate](https://github.com/dannyvankooten/extemplate) | 50 | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| <b>[gospin](https://github.com/m1/gospin) | 39 | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |
| <b>[tbd](https://github.com/lucasepe/tbd) | 20 | A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata. |
| <b>[got](https://github.com/goradd/got) | 2 | A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Testing

_Libraries for testing codebases and generating test data._


<br>

### Testing Frameworks


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Testify](https://github.com/stretchr/testify) | 17.0k | Sacred extension to the standard go testing package. |
| <b>[GoConvey](https://github.com/smartystreets/goconvey/) | 7.4k | BDD-style framework with web UI and live reload. |
| <b>[go-cmp](https://github.com/google/go-cmp) | 3.1k | Package for comparing Go values in tests. |
| <b>[httpexpect](https://github.com/gavv/httpexpect) | 2.0k | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| <b>[godog](https://github.com/DATA-DOG/godog) | 1.7k | Cucumber or Behat like BDD framework for Go. |
| <b>[is](https://github.com/matryer/is) | 1.5k | Professional lightweight testing mini-framework for Go. |
| <b>[gnomock](https://github.com/orlangure/gnomock) | 911 | integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. |
| <b>[go-vcr](https://github.com/dnaeon/go-vcr) | 903 | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| <b>[goblin](https://github.com/franela/goblin) | 861 | Mocha like testing framework fo Go. |
| <b>[testfixtures](https://github.com/go-testfixtures/testfixtures) | 830 | A helper for Rails' like test fixtures to test database applications. |
| <b>[baloo](https://github.com/h2non/baloo) | 732 | Expressive and versatile end-to-end HTTP API testing made easy. |
| <b>[goc](https://github.com/qiniu/goc) | 557 | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| <b>[go-mutesting](https://github.com/zimmski/go-mutesting) | 544 | Mutation testing for Go source code. |
| <b>[gofight](https://github.com/appleboy/gofight) | 423 | API Handler Testing for Golang Router framework. |
| <b>[embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 416 | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| <b>[testza](https://github.com/MarvinJWendt/testza) | 393 | Full-featured test framework with nice colorized output. |
| <b>[gotest.tools](https://github.com/gotestyourself/gotest.tools) | 338 | A collection of packages to augment the go testing package and support common patterns. |
| <b>[go-testdeep](https://github.com/maxatome/go-testdeep) | 313 | Extremely flexible golang deep comparison, extends the go testing package. |
| <b>[frisby](https://github.com/verdverm/frisby) | 272 | REST API testing framework. |
| <b>[got](https://github.com/ysmood/got) | 233 | An enjoyable golang test framework. |
| <b>[go-carpet](https://github.com/msoap/go-carpet) | 227 | Tool for viewing test coverage in terminal. |
| <b>[cupaloy](https://github.com/bradleyjkemp/cupaloy) | 221 | Simple snapshot testing addon for your test framework. |
| <b>[endly](https://github.com/viant/endly) | 215 | Declarative end to end functional testing. |
| <b>[commander](https://github.com/SimonBaeumer/commander) | 202 | Tool for testing cli applications on windows, linux and osx. |
| <b>[charlatan](https://github.com/percolate/charlatan) | 195 | Tool to generate fake interface implementations for tests. |
| <b>[dbcleaner](https://github.com/khaiql/dbcleaner) | 139 | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| <b>[go-hit](https://github.com/Eun/go-hit) | 121 | Hit is an http integration test framework written in golang. |
| <b>[GoSpec](https://github.com/orfjackal/gospec) | 112 | BDD-style testing framework for the Go programming language. |
| <b>[testcase](https://github.com/adamluzsi/testcase) | 94 | Idiomatic testing framework for Behavior Driven Development. |
| <b>[wstest](https://github.com/posener/wstest) | 92 | Websocket client for unit-testing a websocket http.Handler. |
| <b>[jsonassert](https://github.com/kinbiko/jsonassert) | 88 | Package for verifying that your JSON payloads are serialized correctly. |
| <b>[gocrest](https://github.com/corbym/gocrest) | 83 | Composable hamcrest-like matchers for Go assertions. |
| <b>[restit](https://github.com/yookoala/restit) | 55 | Go micro framework to help writing RESTful API integration test. |
| <b>[gospecify](https://github.com/stesla/gospecify) | 52 | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| <b>[covergates](https://github.com/covergates/covergates) | 50 | Self-hosted code coverage report review and management service. |
| <b>[gherkingen](https://github.com/hedhyw/gherkingen) | 49 | BDD boilerplate generator and framework. |
| <b>[gomatch](https://github.com/jfilipczyk/gomatch) | 42 | library created for testing JSON against patterns. |
| <b>[assert](https://github.com/go-playground/assert) | 41 | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| <b>[dsunit](https://github.com/viant/dsunit) | 41 | Datastore testing for SQL, NoSQL, structured files. |
| <b>[Hamcrest](https://github.com/rdrdr/hamcrest) | 27 | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| <b>[schema](https://github.com/jgroeneveld/schema) | 17 | Quick and easy expression matching for JSON schemas used in requests and responses. |
| <b>[flute](https://github.com/suzuki-shunsuke/flute) | 17 | HTTP client testing framework. |
| <b>[be](https://github.com/carlmjohnson/be) | 16 | The minimalist generic test assertion library. |
| <b>[gogiven](https://github.com/corbym/gogiven) | 13 | YATSPEC-like BDD testing framework for Go. |
| <b>[testsql](https://github.com/zhulongcheng/testsql) | 13 | Generate test data from SQL files before testing and clear it after finished. |
| <b>[gosuite](https://github.com/pavlo/gosuite) | 11 | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| <b>[biff](https://github.com/fulldump/biff) | 10 | Bifurcation testing framework, BDD compatible. |
| <b>[badio](https://github.com/cavaliercoder/badio) | 9 | Extensions to Go's `testing/iotest` package. |
| <b>[fixenv](https://github.com/rekby/fixenv) | 6 | Fixture manage engine, inspired by pytest fixtures. |
| <b>[stop-and-go](https://github.com/elgohr/stop-and-go) | 5 | Testing helper for concurrency. |
| <b>[trial](https://github.com/jgroeneveld/trial) | 5 | Quick and easy extendable assertions without introducing much boilerplate. |
| <b>[Tt](https://github.com/vcaesar/tt) | 4 | Simple and colorful test tools. |
| <b>[go-testpredicate](https://github.com/maargenton/go-testpredicate) | 4 | Test predicate style assertions library with extensive diagnostics output. |
| <b>[gomega](https://onsi.github.io/gomega/) | - | Rspec like matcher/assertion library. |
| <b>[omg.testingtools](https://github.com/dedalqq/omg.testingtools) | 0 | The simple library for change a values of private fields for testing. |
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
| <b>[gomock](https://github.com/golang/mock) | 7.8k | Mocking framework for the Go programming language. |
| <b>[go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 4.6k | Mock SQL driver for testing database interactions. |
| <b>[mockery](https://github.com/vektra/mockery) | 3.8k | Tool to generate Go interfaces. |
| <b>[hoverfly](https://github.com/SpectoLabs/hoverfly) | 1.9k | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| <b>[gock](https://github.com/h2non/gock) | 1.7k | Versatile HTTP mocking made easy. |
| <b>[httpmock](https://github.com/jarcoal/httpmock) | 1.5k | Easy mocking of HTTP responses from external resources. |
| <b>[counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 711 | Tool for generating self-contained mock objects. |
| <b>[go-txdb](https://github.com/DATA-DOG/go-txdb) | 470 | Single transaction based database driver mainly for testing purposes. |
| <b>[minimock](https://github.com/gojuno/minimock) | 460 | Mock generator for Go interfaces. |
| <b>[govcr](https://github.com/seborama/govcr) | 108 | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| <b>[timex](https://github.com/cabify/timex) | 63 | A test-friendly replacement for the native `time` package. |
| <b>[go-localstack](https://github.com/elgohr/go-localstack) | 53 | Tool for using localstack in AWS testing. |
| <b>[mockhttp](https://github.com/tv42/mockhttp) | 21 | Mock object for Go http.ResponseWriter. |
| <b>[mockit](https://github.com/pasdam/mockit) | 9 | Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java. |
| <b>[genmock](https://gitlab.com/so_literate/genmock) | - | Go mocking system with code generator for building calls of the interface methods. |


<br>

[👆back to top](#catalogue-list)


<br>

### Fuzzing and delta-debugging/reducing/shrinking.


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-fuzz](https://github.com/dvyukov/go-fuzz) | 4.4k | Randomized testing system. |
| <b>[gofuzz](https://github.com/google/gofuzz) | 1.3k | Library for populating go objects with random values. |
| <b>[Tavor](https://github.com/zimmski/tavor) | 235 | Generic fuzzing and delta-debugging framework. |


<br>

[👆back to top](#catalogue-list)


<br>

### Selenium and browser control tools.


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[chromedp](https://github.com/knq/chromedp) | 8.0k | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| <b>[rod](https://github.com/go-rod/rod) | 2.7k | A Devtools driver to make web automation and scraping easy. |
| <b>[selenoid](https://github.com/aerokube/selenoid) | 2.2k | alternative Selenium hub server that launches browsers within containers. |
| <b>[playwright-go](https://github.com/mxschmitt/playwright-go) | 889 | browser automation library to control Chromium, Firefox and WebKit with a single API. |
| <b>[cdp](https://github.com/mafredri/cdp) | 623 | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| <b>[ggr](https://github.com/aerokube/ggr) | 288 | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |


<br>

[👆back to top](#catalogue-list)


<br>

### Fail injection


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[failpoint](https://github.com/pingcap/failpoint) | 713 | An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Text Processing

_Libraries for parsing and manipulating texts._


<br>

### Formatters


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-humanize](https://github.com/dustin/go-humanize) | 3.3k | Formatters for time, numbers, and memory size to human readable format. |
| <b>[bytes](https://github.com/labstack/gommon/tree/master/bytes) | 459 | Formats and parses numeric byte values (10K, 2M, 3G, etc.). |
| <b>[gotabulate](https://github.com/bndr/gotabulate) | 286 | Easily pretty-print your tabular data with Go. |
| <b>[align](https://github.com/Guitarbum722/align) | 76 | A general purpose application that aligns text. |
| <b>[go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 64 | Fixed-width text formatting (encoder/decoder with reflection). |
| <b>[address](https://github.com/bojanz/address) | 52 | Handles address representation, validation and formatting. |
| <b>[textwrap](https://github.com/isbm/textwrap) | 2 | Wraps text at end of lines. Implementation of `textwrap` module from Python. |


<br>

[👆back to top](#catalogue-list)


<br>

### Markup Languages


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[blackfriday](https://github.com/russross/blackfriday) | 5.0k | Markdown processor in Go. |
| <b>[toml](https://github.com/BurntSushi/toml) | 4.0k | TOML configuration format (encoder/decoder with reflection). |
| <b>[goldmark](https://github.com/yuin/goldmark) | 2.3k | A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured. |
| <b>[go-toml](https://github.com/pelletier/go-toml) | 1.3k | Go library for the TOML format with query support and handy cli tools. |
| <b>[mxj](https://github.com/clbanning/mxj) | 525 | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| <b>[htmlquery](https://github.com/antchfx/htmlquery) | 505 | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| <b>[html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 378 | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| <b>[goq](https://github.com/andrewstuart/goq) | 217 | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| <b>[bafi](https://github.com/mmalcek/bafi) | 60 | Universal JSON, BSON, YAML, XML translator to ANY format using templates. |
| <b>[go-output-format](https://github.com/drewstinnett/go-output-format) | 7 | Output go structures into multiple formats (YAML/JSON/etc) in your command line app. |
| <b>[bbConvert](https://github.com/CalebQ42/bbConvert) | 6 | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| <b>[github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) | - | GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links. |


<br>

[👆back to top](#catalogue-list)


<br>

### Parsers/Encoders/Decoders


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[sh](https://github.com/mvdan/sh) | 5.0k | Shell parser and formatter. |
| <b>[gofeed](https://github.com/mmcdole/gofeed) | 1.9k | Parse RSS and Atom feeds in Go. |
| <b>[when](https://github.com/olebedev/when) | 1.2k | Natural EN and RU language date/time parser with pluggable rules. |
| <b>[commonregex](https://github.com/mingrammer/commonregex) | 823 | A collection of common regular expressions for Go. |
| <b>[gographviz](https://github.com/awalterschulze/gographviz) | 490 | Parses the Graphviz DOT language. |
| <b>[omniparser](https://github.com/jf-tech/omniparser) | 484 | A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. |
| <b>[go-nmea](https://github.com/adrianmo/go-nmea) | 181 | NMEA parser library for the Go language. |
| <b>[sdp](https://github.com/gortc/sdp) | 114 | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| <b>[editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 102 | Editorconfig file parser and manipulator for Go. |
| <b>[go-vcard](https://github.com/emersion/go-vcard) | 74 | Parse and format vCard. |
| <b>[did](https://github.com/ockam-network/did) | 64 | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| <b>[allot](https://github.com/sbstjn/allot) | 55 | Placeholder and wildcard text parsing for CLI tools and bots. |
| <b>[parth](https://github.com/codemodus/parth) | 41 | URL path segmentation parsing. |
| <b>[gonameparts](https://github.com/polera/gonameparts) | 36 | Parses human names into individual name parts. |
| <b>[normalize](https://github.com/avito-tech/normalize) | 30 | Sanitize, normalize and compare fuzzy text. |
| <b>[xj2go](https://github.com/stackerzzq/xj2go) | 26 | Convert xml or json to go struct. |
| <b>[codetree](https://github.com/aerogo/codetree) | 21 | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| <b>[tokenizer](https://github.com/bzick/tokenizer) | 17 | — Parse any string, slice or infinite buffer to any tokens. |
| <b>[go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) | 9 | High performance top level domains (TLD) extraction module. |
| <b>[parseargs-go](https://github.com/nproc/parseargs-go) | 9 | string argument parser that understands quotes and backslashes. |
| <b>[encdec](https://github.com/mickep76/encdec) | 7 | Package provides a generic interface to encoders and decoders. |
| <b>[ltsv](https://github.com/Wing924/ltsv) | 7 | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |
| <b>[doi](https://github.com/hscells/doi) | 6 | Document object identifier (doi) parser in Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Regular Expressions


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[regroup](https://github.com/oriser/regroup) | 116 | Match regex expression named groups into go struct using struct tags and automatic parsing. |
| <b>[rex](https://github.com/hedhyw/rex) | 112 | Regular expressions builder. |
| <b>[goregen](https://github.com/zach-klippenstein/goregen) | 73 | Library for generating random strings from regular expressions. |
| <b>[genex](https://github.com/alixaxel/genex) | 66 | Count and expand Regular Expressions into all matching Strings. |
| <b>[go-wildcard](https://github.com/IGLOU-EU/go-wildcard) | 16 | Simple and lightweight wildcard pattern matching. |


<br>

[👆back to top](#catalogue-list)


<br>

### Sanitation


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[bluemonday](https://github.com/microcosm-cc/bluemonday) | 2.4k | HTML Sanitizer. |
| <b>[gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 48 | A sanitization-based swear filter for Go. |


<br>

[👆back to top](#catalogue-list)


<br>

### Scrapers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[colly](https://github.com/asciimoo/colly) | 17.0k | Fast and Elegant Scraping Framework for Gophers. |
| <b>[GoQuery](https://github.com/PuerkitoBio/goquery) | 12.0k | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| <b>[xurls](https://github.com/mvdan/xurls) | 943 | Extract urls from text. |
| <b>[dataflowkit](https://github.com/slotix/dataflowkit) | 539 | Web scraping Framework to turn websites into structured data. |
| <b>[gospider](https://github.com/zhshch2002/gospider) | 170 | A simple golang spider/scraping framework,build a spider in 3 lines. migrated from [goribot](https://github.com/zhshch2002/goribot) |
| <b>[pagser](https://github.com/foolin/pagser) | 68 | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| <b>[Tagify](https://github.com/zoomio/tagify) | 23 | Produces a set of tags from given source. |


<br>

[👆back to top](#catalogue-list)


<br>

### RSS


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[podcast](https://github.com/eduncan911/podcast) | 110 | iTunes Compliant and RSS 2.0 Podcast Generator in Golang |
| <b>[syndfeed](https://github.com/zhengchun/syndfeed) | 8 | A syndication feed for Atom 1.0 and RSS 2.0. |


<br>

[👆back to top](#catalogue-list)


<br>

### Utility/Miscellaneous


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-runewidth](https://github.com/mattn/go-runewidth) | 474 | Functions to get fixed width of the character or string. |
| <b>[radix](https://github.com/yourbasic/radix) | 177 | Fast string sorting algorithm. |
| <b>[go-zero-width](https://github.com/trubitsyn/go-zero-width) | 103 | Zero-width character detection and removal for Go. |
| <b>[petrovich](https://github.com/striker2000/petrovich) | 39 | Petrovich is the library which inflects Russian names to given grammatical case. |
| <b>[kace](https://github.com/codemodus/kace) | 18 | Common case conversions covering common initialisms. |
| <b>[TySug](https://github.com/Dynom/TySug) | 12 | Alternative suggestions with respect to keyboard layouts. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Third-party APIs

_Libraries for accessing third party APIs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[github](https://github.com/google/go-github) | 8.7k | Go library for accessing the GitHub REST API v3. |
| <b>[aws-sdk-go](https://github.com/aws/aws-sdk-go) | 7.8k | The official AWS SDK for the Go programming language. |
| <b>[slack](https://github.com/slack-go/slack) | 4.0k | Slack API in Go. |
| <b>[discordgo](https://github.com/bwmarrin/discordgo) | 3.3k | Go bindings for the Discord Chat API. |
| <b>[google](https://github.com/google/google-api-go-client) | 3.1k | Auto-generated Google APIs for Go. |
| <b>[google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) | 3.0k | Google Cloud APIs Go Client Library. |
| <b>[minio-go](https://github.com/minio/minio-go) | 1.7k | Minio Go Library for Amazon S3 compatible cloud storage. |
| <b>[stripe](https://github.com/stripe/stripe-go) | 1.6k | Go client for the Stripe API. |
| <b>[go-twitter](https://github.com/dghubble/go-twitter) | 1.5k | Go client library for the Twitter v1.1 APIs. |
| <b>[go-jira](https://github.com/andygrunwald/go-jira) | 1.2k | Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) |
| <b>[anaconda](https://github.com/ChimeraCoder/anaconda) | 1.1k | Go client library for the Twitter 1.1 API. |
| <b>[facebook](https://github.com/huandu/facebook) | 1.1k | Go Library that supports the Facebook Graph API. |
| <b>[githubql](https://github.com/shurcooL/githubql) | 910 | Go library for accessing the GitHub GraphQL API v4. |
| <b>[webhooks](https://github.com/go-playground/webhooks) | 769 | Webhook receiver for GitHub and Bitbucket. |
| <b>[paypal](https://github.com/logpacker/PayPal-Go-SDK) | 514 | Wrapper for PayPal payment API. |
| <b>[geo-golang](https://github.com/codingsince1985/geo-golang) | 439 | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| <b>[twitter-scraper](https://github.com/n0madic/twitter-scraper) | 244 | Scrape the Twitter Frontend API without authentication and limits. |
| <b>[ethrpc](https://github.com/onrik/ethrpc) | 240 | Go bindings for Ethereum JSON RPC API. |
| <b>[lark](https://github.com/chyroc/lark) | 217 | [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback. |
| <b>[Trello](https://github.com/adlio/trello) | 201 | Go wrapper for the Trello API. |
| <b>[go-marathon](https://github.com/gambol99/go-marathon) | 195 | Go library for interacting with Mesosphere's Marathon PAAS. |
| <b>[Medium](https://github.com/Medium/medium-sdk-go) | 132 | Golang SDK for Medium's OAuth2 API. |
| <b>[gostorm](https://github.com/jsgilmore/gostorm) | 128 | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| <b>[wit-go](https://github.com/wit-ai/wit-go) | 125 | Go client for wit.ai HTTP API. |
| <b>[pushover](https://github.com/gregdel/pushover) | 124 | Go wrapper for the Pushover API. |
| <b>[go-trending](https://github.com/andygrunwald/go-trending) | 121 | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| <b>[hipchat (xmpp)](https://github.com/daneharrigan/hipchat) | 110 | A golang package to communicate with HipChat over XMPP. |
| <b>[go-lark](https://github.com/go-lark/lark) | 106 | An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform. |
| <b>[hipchat](https://github.com/andybons/hipchat) | 104 | This project implements a golang client library for the Hipchat API. |
| <b>[cachet](https://github.com/andygrunwald/cachet) | 90 | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| <b>[simples3](https://github.com/rhnvrm/simples3) | 89 | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| <b>[gosip](https://github.com/koltyakov/gosip) | 79 | Go client library SharePoint API. |
| <b>[igdb](https://github.com/Henry-Sarabia/igdb) | 75 | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| <b>[go-unsplash](https://github.com/hbagdi/go-unsplash) | 66 | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| <b>[gogtrends](https://github.com/groovili/gogtrends) | 65 | Google Trends Unofficial API. |
| <b>[circleci](https://github.com/jszwedko/go-circleci) | 64 | Go client library for interacting with CircleCI's API. |
| <b>[clarifai](https://github.com/samuelcouch/clarifai) | 56 | Go client library for interfacing with the Clarifai API. |
| <b>[golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 54 | Golang wrapper for The Movie Database API v3. |
| <b>[megos](https://github.com/andygrunwald/megos) | 54 | Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster. |
| <b>[amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 53 | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| <b>[ynab](https://github.com/brunomvsouza/ynab.go) | 52 | Go wrapper for the YNAB API. |
| <b>[gads](https://github.com/emiddleton/gads) | 49 | Google Adwords Unofficial API. |
| <b>[go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 49 | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| <b>[uptimerobot](https://github.com/bitfield/uptimerobot) | 49 | Go wrapper and command-line client for the Uptime Robot v2 API. |
| <b>[go-atlassian](https://github.com/ctreminiom/go-atlassian) | 48 | Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud) |
| <b>[fcm](https://github.com/maddevsio/fcm) | 47 | Go library for Firebase Cloud Messaging. |
| <b>[mixpanel](https://github.com/dukex/mixpanel) | 46 | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| <b>[go-xkcd](https://github.com/nishanths/go-xkcd) | 45 | Go client for the xkcd API. |
| <b>[GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) | 45 | Go MusicBrainz WS2 client library. |
| <b>[airtable](https://github.com/mehanizm/airtable) | 43 | Go client library for the [Airtable API](https://airtable.com/api). |
| <b>[spotify](https://github.com/rapito/go-spotify) | 43 | Go Library to access Spotify WEB API. |
| <b>[golyrics](https://github.com/mamal72/golyrics) | 38 | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| <b>[google-play-scraper](https://github.com/n0madic/google-play-scraper) | 38 | Get data from Google Play Store. |
| <b>[go-myanimelist](https://github.com/nstratos/go-myanimelist) | 31 | Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2). |
| <b>[patreon-go](https://github.com/mxpv/patreon-go) | 31 | Go library for Patreon API. |
| <b>[translate](https://github.com/poorny/translate) | 31 | Go online translation package. |
| <b>[gami](https://github.com/bit4bit/gami) | 30 | Go library for Asterisk Manager Interface. |
| <b>[gcm](https://github.com/Aorioli/gcm) | 30 | Go library for Google Cloud Messaging. |
| <b>[lastpass-go](https://github.com/ansd/lastpass-go) | 29 | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| <b>[steam](https://github.com/sostronk/go-steam) | 27 | Go Library to interact with Steam game servers. |
| <b>[go-imgur](https://github.com/koffeinsource/go-imgur) | 23 | Go client library for [imgur](https://imgur.com) |
| <b>[shopify](https://github.com/rapito/go-shopify) | 23 | Go Library to make CRUD request to the Shopify API. |
| <b>[go-twitch](https://github.com/knspriggs/go-twitch) | 21 | Go client for interacting with the Twitch v3 API. |
| <b>[brewerydb](https://github.com/naegelejd/brewerydb) | 18 | Go library for accessing the BreweryDB API. |
| <b>[codeship-go](https://github.com/codeship/codeship-go) | 18 | Go client library for interacting with Codeship's API v2. |
| <b>[jokeapi-go](https://github.com/icelain/jokeapi) | 18 | Go client for [JokeAPI](https://sv443.net/jokeapi/v2/). |
| <b>[textbelt](https://github.com/dietsche/textbelt) | 17 | Go client for the textbelt.com txt messaging API. |
| <b>[go-hacknews](https://github.com/PaulRosset/go-hacknews) | 16 | Tiny Go client for HackerNews API. |
| <b>[coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) | 15 | Go client library for interacting with Coinpaprika's API. |
| <b>[device-check-go](https://github.com/rinchsan/device-check-go) | 14 | Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. |
| <b>[go-aws-news](https://github.com/circa10a/go-aws-news) | 14 | Go application and library to fetch what's new from AWS. |
| <b>[google-analytics](https://github.com/chonthu/go-google-analytics) | 12 | Simple wrapper for easy google analytics reporting. |
| <b>[gopaapi5](https://github.com/utekaravinash/gopaapi5) | 12 | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| <b>[go-openproject](https://github.com/manuelbcd/go-openproject) | 11 | Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API. |
| <b>[go-here](https://github.com/abdullahselek/go-here) | 10 | Go client library around the HERE location based APIs. |
| <b>[go-sophos](https://github.com/esurdam/go-sophos) | 10 | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| <b>[smite](https://github.com/sergiotapia/smitego) | 10 | Go package to wraps access to the Smite game API. |
| <b>[bqwriter](https://github.com/OTA-Insight/bqwriter) | 9 | High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout. |
| <b>[gomalshare](https://github.com/MonaxGT/gomalshare) | 9 | Go library MalShare API [malshare.com](https://www.malshare.com/) |
| <b>[rrdaclient](https://github.com/Omie/rrdaclient) | 8 | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| <b>[google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 7 | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| <b>[libgoffi](https://github.com/clevabit/libgoffi) | 7 | Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration |
| <b>[rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) | 7 | Go library for the [RAWG Video Games Database](https://rawg.io/) API |
| <b>[tumblr](https://github.com/mattcunningham/gumblr) | 7 | Go wrapper for the Tumblr v2 API. |
| <b>[goami2](https://github.com/staskobzar/goami2) | 7 | AMI v2 library for Asterisk PBX. |
| <b>[go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 6 | Go client library for the SPTrans Olho Vivo API. |
| <b>[zooz](https://github.com/gojuno/go-zooz) | 6 | Go client for the Zooz API. |
| <b>[go-swagger-ui](https://github.com/esurdam/go-swagger-ui) | 5 | Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json. |
| <b>[go-chronos](https://github.com/axelspringer/go-chronos) | 4 | Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler |
| <b>[go-hibp](https://github.com/wneessen/go-hibp) | 4 | Simple Go binding to the "Have I Been Pwned" APIs. |
| <b>[goagi](https://github.com/staskobzar/goagi) | 4 | Go library to build Asterisk PBX agi/fastagi applications. |
| <b>[kanka](https://github.com/Henry-Sarabia/kanka) | 3 | Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0). |
| <b>[appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) | 2 | Unofficial Golang SDK for AppStore Connect API. |
| <b>[go-restcountries](https://github.com/chriscross0/go-restcountries) | 2 | Go library for the [REST Countries API](https://restcountries.eu/). |
| <b>[newsapi-go](https://github.com/jellydator/newsapi-go) | 2 | Go client for [NewsAPI](https://newsapi.org/). |
| <b>[dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) | 1 | Unofficial Dusupay payment gateway API Client for Go |
| <b>[playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) | 1 | The Playlyfe Rest API Go SDK. |
| <b>[TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) | 1 | Go wrapper for the TripAdvisor API. |
| <b>[vl-go](https://github.com/verifid/vl-go) | 1 | Go client library around the VerifID identity verification layer API. |
| <b>[fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) | 0 | Unofficial Fasapay payment gateway XML API Client for Golang. |
| <b>[go-telegraph](https://gitlab.com/toby3d/telegraph) | - | Telegraph publishing platform API client. |
| <b>[go-yapla](https://git.iglou.eu/Production/go-yapla) | - | Go client library for the Yapla v2.0 API. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Utilities

_General utilities and tools to make your life easier._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[fzf](https://github.com/junegunn/fzf) | 46.0k | Command-line fuzzy finder written in Go. |
| <b>[hub](https://github.com/github/hub) | 22.0k | wrap git commands with additional functionality to interact with github from the terminal. |
| <b>[ctop](https://github.com/bcicen/ctop) | 13.0k | [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics. |
| <b>[sqlx](https://github.com/jmoiron/sqlx) | 12.0k | provides a set of extensions on top of the excellent built-in database/sql package. |
| <b>[goreleaser](https://github.com/goreleaser/goreleaser) | 10.0k | Deliver Go binaries as fast and easily as possible. |
| <b>[wuzz](https://github.com/asciimoo/wuzz) | 10.0k | Interactive cli tool for HTTP inspection. |
| <b>[usql](https://github.com/knq/usql) | 7.5k | usql is a universal command-line interface for SQL databases. |
| <b>[lo](https://github.com/samber/lo) | 7.3k | A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...) |
| <b>[peco](https://github.com/peco/peco) | 7.1k | Simplistic interactive filtering tool. |
| <b>[godropbox](https://github.com/dropbox/godropbox) | 4.0k | Common libraries for writing Go services/applications from Dropbox. |
| <b>[go-funk](https://github.com/thoas/go-funk) | 3.7k | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| <b>[hystrix-go](https://github.com/afex/hystrix-go) | 3.7k | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| <b>[panicparse](https://github.com/maruel/panicparse) | 3.2k | Groups similar goroutines and colorizes stack dump. |
| <b>[minify](https://github.com/tdewolff/minify) | 3.1k | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| <b>[goreporter](https://github.com/wgliang/goreporter) | 3.0k | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| <b>[mc](https://github.com/minio/mc) | 2.2k | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| <b>[mergo](https://github.com/imdario/mergo) | 2.0k | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| <b>[Storm](https://github.com/asdine/storm) | 1.9k | Simple and powerful toolkit for BoltDB. |
| <b>[filetype](https://github.com/h2non/filetype) | 1.6k | Small package to infer the file type checking the magic numbers signature. |
| <b>[mole](https://github.com/davrodpin/mole) | 1.6k | cli app to easily create ssh tunnels. |
| <b>[lancet](https://github.com/duke-git/lancet) | 1.6k | A comprehensive, efficient, and reusable util function library of go. |
| <b>[boilr](https://github.com/tmrts/boilr) | 1.5k | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| <b>[create-go-app](https://github.com/create-go-app/cli) | 1.5k | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| <b>[gitbatch](https://github.com/isacikgoz/gitbatch) | 1.5k | manage your git repositories in one place. |
| <b>[jump](https://github.com/gsamokovarov/jump) | 1.4k | Jump helps you navigate faster by learning your habits. |
| <b>[EaseProbe](https://github.com/megaease/easeprobe) | 1.1k | A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification. |
| <b>[circuitbreaker](https://github.com/rubyist/circuitbreaker) | 1000 | Circuit Breakers in Go. |
| <b>[git-time-metric](https://github.com/git-time-metric/gtm) | 900 | Simple, seamless, lightweight time tracking for Git. |
| <b>[hostctl](https://github.com/guumaster/hostctl) | 796 | A CLI tool to manage /etc/hosts with easy commands. |
| <b>[mimetype](https://github.com/gabriel-vasile/mimetype) | 789 | Package for MIME type detection based on magic numbers. |
| <b>[immortal](https://github.com/immortal/immortal) | 747 | \*nix cross-platform (OS agnostic) supervisor. |
| <b>[circuit](https://github.com/cep21/circuit) | 655 | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| <b>[scany](https://github.com/georgysavva/scany) | 633 | Library for scanning data from a database into Go structs and more. |
| <b>[htcat](https://github.com/htcat/htcat) | 548 | Parallel and Pipelined HTTP GET Utility. |
| <b>[ergo](https://github.com/cristianoliveira/ergo) | 530 | The management of multiple local services running over different ports made easy. |
| <b>[delve](https://github.com/derekparker/delve) | 513 | Go debugger. |
| <b>[koazee](https://github.com/wesovilabs/koazee) | 505 | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| <b>[godaemon](https://github.com/VividCortex/godaemon) | 488 | Utility to write daemons. |
| <b>[go-dry](https://github.com/ungerik/go-dry) | 478 | DRY (don't repeat yourself) package for Go. |
| <b>[gopencils](https://github.com/bndr/gopencils) | 438 | Small and simple package to easily consume REST APIs. |
| <b>[request](https://github.com/mozillazg/request) | 418 | Go HTTP Requests for Humans™. |
| <b>[gubrak](https://github.com/novalagung/gubrak) | 410 | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| <b>[clockwork](https://github.com/jonboulle/clockwork) | 408 | A simple fake clock for golang. |
| <b>[Deepcopier](https://github.com/ulule/deepcopier) | 392 | Simple struct copying for Go. |
| <b>[changie](https://github.com/miniscruff/changie) | 375 | Automated changelog tool for preparing releases with lots of customization options. |
| <b>[go-rate](https://github.com/beefsack/go-rate) | 366 | Timed rate limiter for Go. |
| <b>[retry](https://github.com/kamilsk/retry) | 322 | The most advanced functional mechanism to perform actions repetitively until successful. |
| <b>[mani](https://github.com/alajmo/mani) | 301 | CLI tool to help you manage multiple repositories. |
| <b>[scan](https://github.com/blockloop/scan) | 297 | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| <b>[serve](https://github.com/syntaqx/serve) | 275 | A static http server anywhere you need. |
| <b>[gohper](https://github.com/cosiner/gohper) | 256 | Various tools/modules help for development. |
| <b>[util](https://github.com/shomali11/util) | 251 | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| <b>[clipboard](https://github.com/golang-design/clipboard) | 243 | 📋 cross-platform clipboard package in Go. |
| <b>[go-trigger](https://github.com/sadlil/go-trigger) | 228 | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| <b>[gotenv](https://github.com/subosito/gotenv) | 228 | Load environment variables from `.env` or any `io.Reader` in Go. |
| <b>[grofer](https://github.com/pesos/grofer) | 216 | A system and resource monitoring tool written in Golang! |
| <b>[wifiqr](https://github.com/reugn/wifiqr) | 212 | Wi-Fi QR Code Generator. |
| <b>[pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 183 | Pattern matching libray. |
| <b>[Death](https://github.com/vrecan/death) | 181 | Managing go application shutdown with signals. |
| <b>[go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 180 | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| <b>[toolbox](https://github.com/viant/toolbox) | 180 | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| <b>[go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 179 | XML Sitemap generator written in Go. |
| <b>[rospo](https://github.com/ferama/rospo) | 178 | Simple and reliable ssh tunnels with embedded ssh server in Golang. |
| <b>[countries](https://github.com/biter777/countries) | 173 | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| <b>[rerun](https://github.com/ivpusic/rerun) | 164 | Recompiling and rerunning go apps when source changes. |
| <b>[moldova](https://github.com/StabbyCutyou/moldova) | 162 | Utility for generating random data based on an input template. |
| <b>[apm](https://github.com/topfreegames/apm) | 159 | Process manager for Golang applications with an HTTP API. |
| <b>[robustly](https://github.com/VividCortex/robustly) | 153 | Runs functions resiliently, catching and restarting panics. |
| <b>[chyle](https://github.com/antham/chyle) | 145 | Changelog generator using a git repository with multiple configuration possibilities. |
| <b>[go-bsdiff](https://github.com/gabstv/go-bsdiff) | 132 | Pure Go bsdiff and bspatch libraries and CLI tools. |
| <b>[onecache](https://github.com/adelowo/onecache) | 128 | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| <b>[lrserver](https://github.com/jaschaephraim/lrserver) | 121 | LiveReload server for Go. |
| <b>[nostromo](https://github.com/pokanop/nostromo) | 117 | CLI for building powerful aliases. |
| <b>[cryptgo](https://github.com/Gituser143/cryptgo) | 116 | Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time! |
| <b>[sorty](https://github.com/jfcg/sorty) | 107 | Fast Concurrent / Parallel Sorting. |
| <b>[mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 103 | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| <b>[cmd](https://github.com/SimonBaeumer/cmd) | 100 | Library for executing shell commands on osx, windows and linux. |
| <b>[limiters](https://github.com/mennanov/limiters) | 100 | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| <b>[mssqlx](https://github.com/linxGnu/mssqlx) | 100 | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| <b>[goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 95 | SeaweedFS client library with almost full features. |
| <b>[xferspdy](https://github.com/monmohan/xferspdy) | 93 | Xferspdy provides binary diff and patch library in golang. |
| <b>[go-health](https://github.com/Talento90/go-health) | 90 | Health package simplifies the way you add health check to your services. |
| <b>[filter](https://github.com/gookit/filter) | 89 | provide filtering, sanitizing, and conversion of Go data. |
| <b>[goval](https://github.com/maja42/goval) | 83 | Evaluate arbitrary expressions in Go. |
| <b>[repeat](https://github.com/ssgreg/repeat) | 80 | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| <b>[pm](https://github.com/VividCortex/pm) | 77 | Process (i.e. goroutine) manager with an HTTP API. |
| <b>[mimemagic](https://github.com/zRedShift/mimemagic) | 76 | Pure Go ultra performant MIME sniffing library/utility. |
| <b>[go-lock](https://github.com/viney-shih/go-lock) | 75 | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| <b>[netbug](https://github.com/e-dard/netbug) | 70 | Easy remote profiling of your services. |
| <b>[pgo](https://github.com/arthurkushman/pgo) | 69 | Convenient functions for PHP community. |
| <b>[UNIS](https://github.com/esemplastic/unis) | 69 | Common Architecture™ for String Utilities in Go. |
| <b>[handy](https://github.com/miguelpragier/handy) | 68 | Many utilities and helpers like string handlers/formatters and validators. |
| <b>[goreadability](https://github.com/philipjkim/goreadability) | 65 | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| <b>[multitick](https://github.com/VividCortex/multitick) | 63 | Multiplexor for aligned tickers. |
| <b>[minquery](https://github.com/icza/minquery) | 59 | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| <b>[go-astitodo](https://github.com/asticode/go-astitodo) | 58 | Parse TODOs in your GO code. |
| <b>[golog](https://github.com/mlimaloureiro/golog) | 57 | Easy and lightweight CLI tool to time track your tasks. |
| <b>[retry](https://github.com/thedevsaddam/retry) | 55 | Simple and easy retry mechanism package for Go. |
| <b>[slice](https://github.com/psampaz/slice) | 50 | Type-safe functions for common Go slice operations. |
| <b>[copy-pasta](https://github.com/jutkko/copy-pasta) | 49 | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| <b>[dbt](https://github.com/nikogura/dbt) | 48 | A framework for running self-updating signed binaries from a central, trusted repository. |
| <b>[golarm](https://github.com/msempere/golarm) | 48 | Fire alarms with system events. |
| <b>[beyond](https://github.com/wesovilabs/beyond) | 47 | The Go tool that will drive you to the AOP world! |
| <b>[goback](https://github.com/carlescere/goback) | 45 | Go simple exponential backoff package. |
| <b>[intrinsic](https://github.com/mengzhuo/intrinsic) | 44 | Use x86 SIMD without writing any assembly code. |
| <b>[retry-go](https://github.com/rafaeljesus/retry-go) | 43 | Retrying made simple and easy for golang. |
| <b>[go-httpheader](https://github.com/mozillazg/go-httpheader) | 39 | Go library for encoding structs into Header fields. |
| <b>[gpath](https://github.com/tenntenn/gpath) | 39 | Library to simplify access struct fields with Go's expression in reflection. |
| <b>[slicer](https://github.com/leaanthony/slicer) | 39 | Makes working with slices easier. |
| <b>[equalizer](https://github.com/reugn/equalizer) | 38 | Quota manager and rate limiter collection for Go. |
| <b>[backscanner](https://github.com/icza/backscanner) | 37 | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| <b>[set](https://github.com/nofeaturesonlybugs/set) | 37 | Performant and flexible struct mapping and loose type conversion. |
| <b>[gostrutils](https://github.com/ik5/gostrutils) | 36 | Collections of string manipulation and conversion functions. |
| <b>[evaluator](https://github.com/nullne/evaluator) | 35 | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| <b>[shutdown](https://github.com/ztrue/shutdown) | 35 | App shutdown hooks for `os.Signal` handling. |
| <b>[myhttp](https://github.com/inancgumus/myhttp) | 34 | Simple API to make HTTP GET requests with timeout support. |
| <b>[rclient](https://github.com/zpatrick/rclient) | 32 | Readable, flexible, simple-to-use client for REST APIs. |
| <b>[sshman](https://github.com/shoobyban/sshman) | 32 | SSH Manager for authorized_keys files on multiple remote servers. |
| <b>[pointer](https://github.com/xorcare/pointer) | 30 | Package pointer contains helper routines for simplifying the creation of optional fields of basic type. |
| <b>[tome](https://github.com/cyruzin/tome) | 30 | Tome was designed to paginate simple RESTful APIs. |
| <b>[throttle](https://github.com/yudppp/throttle) | 28 | Throttle is an object that will perform exactly one action per duration. |
| <b>[generate](https://github.com/go-playground/generate) | 27 | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| <b>[ghokin](https://github.com/antham/ghokin) | 27 | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| <b>[ugo](https://github.com/alxrm/ugo) | 26 | ugo is slice toolbox with concise syntax for Go. |
| <b>[copy](https://github.com/gotidy/copy) | 25 | Package for fast copying structs of different types. |
| <b>[goplaceholder](https://github.com/michiwend/goplaceholder) | 24 | a small golang lib to generate placeholder images. |
| <b>[rerate](https://github.com/abo/rerate) | 24 | Redis-based rate counter and rate limiter for Go. |
| <b>[mimesniffer](https://github.com/aofei/mimesniffer) | 23 | A MIME type sniffer for Go. |
| <b>[structs](https://github.com/PumpkinSeed/structs) | 20 | Implement simple functions to manipulate structs. |
| <b>[ctxutil](https://github.com/posener/ctxutil) | 19 | A collection of utility functions for contexts. |
| <b>[cvt](https://github.com/shockerli/cvt) | 17 | Easy and safe convert any value to another type. |
| <b>[dlog](https://github.com/kirillDanshin/dlog) | 16 | Compile-time controlled logger to make your release smaller without removing debug calls. |
| <b>[filler](https://github.com/yaronsumel/filler) | 16 | small utility to fill structs using "fill" tag. |
| <b>[jsend](https://github.com/clevergo/jsend) | 16 | JSend's implementation writen in Go. |
| <b>[go-convert](https://github.com/Eun/go-convert) | 15 | Package go-convert enables you to convert a value into another type. |
| <b>[okrun](https://github.com/xta/okrun) | 15 | go run error steamroller. |
| <b>[ptr](https://github.com/gotidy/ptr) | 15 | Package that provide functions for simplified creation of pointers from constants of basic types. |
| <b>[rest-go](https://github.com/edermanoel94/rest-go) | 15 | A package that provide many helpful methods for working with rest api. |
| <b>[command](https://github.com/txgruppi/command) | 13 | Command pattern for Go with thread safe serial and parallel dispatcher. |
| <b>[go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 13 | Go package for working with Problem Details. |
| <b>[go-type](https://github.com/mikekonan/go-types) | 13 | Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. |
| <b>[retry](https://github.com/shafreeck/retry) | 11 | A pretty simple library to ensure your work to be done. |
| <b>[silk](https://github.com/chrispassas/silk) | 11 | Read silk netflow files. |
| <b>[go-actuator](https://github.com/sinhashubham95/go-actuator) | 9 | Production ready features for Go based web frameworks. |
| <b>[go-countries](https://github.com/mikekonan/go-countries) | 9 | Lightweight lookup over ISO-3166 codes. |
| <b>[statiks](https://github.com/janiltonmaciel/statiks) | 9 | Fast, zero-configuration, static HTTP filer server. |
| <b>[bleep](https://github.com/sinhashubham95/bleep) | 8 | Perform any number of actions on any set of OS signals in Go. |
| <b>[go-clip](https://github.com/prashantgupta24/go-clip) | 8 | A minimalistic clipboard manager for Mac. |
| <b>[retry](https://github.com/percolate/retry) | 8 | A simple but highly configurable retry package for Go. |
| <b>[sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 8 | Slice conversion between primitive types. |
| <b>[blank](https://github.com/Henry-Sarabia/blank) | 7 | Verify or remove blanks and whitespace from strings. |
| <b>[go-pkg](https://github.com/chenquan/go-pkg) | 6 | A go toolkit. |
| <b>[nfdump](https://github.com/chrispassas/nfdump) | 6 | Read nfdump netflow files. |
| <b>[go-safe](https://github.com/kenkyu392/go-safe) | 5 | Panic-safe sandbox. |
| <b>[lets-go](https://github.com/aplescia-chwy/lets-go) | 4 | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| <b>[loncha](https://github.com/kazu/loncha) | 4 | A high-performance slice Utilities. |
| <b>[olaf](https://github.com/btnguyen2k/olaf) | 3 | Twitter Snowflake implemented in Go. |
| <b>[reflectutils](https://github.com/muir/reflectutils) | 3 | Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string. |
| <b>[tik](https://github.com/andy2046/tik) | 3 | Simple and easy timing wheel package for Go. |
| <b>[goctx](https://github.com/zerosnake0/goctx) | 2 | Get your context value with high performance. |
| <b>[objwalker](https://github.com/rekby/objwalker) | 1 | Walk by go objects with reflection. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## UUID

_Libraries for working with UUIDs._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[uuid](https://github.com/google/uuid) | 3.8k | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| <b>[xid](https://github.com/rs/xid) | 2.9k | Xid is a globally unique id generator library, ready to be safely used directly in your server code. |
| <b>[ulid](https://github.com/oklog/ulid) | 2.8k | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| <b>[uuid](https://github.com/gofrs/uuid) | 1.2k | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| <b>[wuid](https://github.com/edwingeng/wuid) | 468 | An extremely fast unique number generator, 10-135 times faster than UUID. |
| <b>[sno](https://github.com/muyo/sno) | 69 | Compact, sortable and fast unique IDs with embedded metadata. |
| <b>[nanoid](https://github.com/aidarkhanov/nanoid) | 52 | A tiny and efficient Go unique string ID generator. |
| <b>[goid](https://github.com/jakehl/goid) | 33 | Generate and Parse RFC4122 compliant V4 UUIDs. |
| <b>[gouid](https://github.com/twharmon/gouid) | 16 | Generate cryptographically secure random string IDs with just one allocation. |
| <b>[uuid](https://github.com/agext/uuid) | 14 | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |
| <b>[goflake](https://github.com/hart87/GoFlake) | 12 | A small, scalable, & serverless unique ID generator for use in distributed systems. Inspired by Twitters Snowflake. |
| <b>[uniq](https://gitlab.com/skilstak/code/go/uniq) | - | No hassle safe, fast unique identifiers with commands. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Validation

_Libraries for validation._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[validator](https://github.com/go-playground/validator) | 11.0k | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| <b>[govalidator](https://github.com/asaskevich/govalidator) | 5.4k | Validators and sanitizers for strings, numerics, slices and structs. |
| <b>[ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 2.8k | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| <b>[govalidator](https://github.com/thedevsaddam/govalidator) | 1.1k | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| <b>[validate](https://github.com/gookit/validate) | 763 | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| <b>[checkdigit](https://github.com/osamingo/checkdigit) | 93 | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| <b>[terraform-validator](https://github.com/thazelart/terraform-validator) | 78 | A norms and conventions validator for Terraform. |
| <b>[validate](https://github.com/gobuffalo/validate) | 69 | This package provides a framework for writing validations for Go applications. |
| <b>[jio](https://github.com/faceair/jio) | 68 | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| <b>[gody](https://github.com/guiferpa/gody) | 61 | :balloon: A lightweight struct validator for Go. |
| <b>[govalid](https://github.com/twharmon/govalid) | 28 | Fast, tag-based validation for structs. |
| <b>[Validator](https://github.com/go-the-way/validator) | 2 | A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Version Control

_Libraries for version control._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-git](https://github.com/go-git/go-git) | 3.8k | highly extensible Git implementation in pure Go. |
| <b>[glab](https://github.com/profclems/glab) | 2.1k | An open-source GitLab command line tool bringing GitLab's cool features to your command line. |
| <b>[git2go](https://github.com/libgit2/git2go) | 1.8k | Go bindings for libgit2. |
| <b>[hercules](https://github.com/src-d/hercules) | 1.8k | gaining advanced insights from Git repository history. |
| <b>[gh](https://github.com/rjeczalik/gh) | 78 | Scriptable server and net/http middleware for GitHub Webhooks. |
| <b>[go-vcs](https://github.com/sourcegraph/go-vcs) | 73 | manipulate and inspect VCS repositories in Go. |
| <b>[githooks](https://github.com/gabyx/githooks) | 47 | Per-repo and shared Git hooks with version control and auto update. |
| <b>[froggit-go](https://github.com/jfrog/froggit-go) | 19 | Froggit-Go is a Go library, allowing to perform actions on VCS providers. |
| <b>[hgo](https://github.com/beyang/hgo) | 13 | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Video

_Libraries for manipulating video._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[goav](https://github.com/giorgisio/goav) | 1.9k | Comprehensive Go bindings for FFmpeg. |
| <b>[m3u8](https://github.com/grafov/m3u8) | 950 | Parser and generator library of M3U8 playlists for Apple HLS. |
| <b>[gmf](https://github.com/3d0c/gmf) | 778 | Go bindings for FFmpeg av\* libraries. |
| <b>[go-astits](https://github.com/asticode/go-astits) | 430 | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| <b>[go-astisub](https://github.com/asticode/go-astisub) | 403 | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| <b>[libvlc-go](https://github.com/adrg/libvlc-go) | 310 | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| <b>[gortsplib](https://github.com/aler9/gortsplib) | 284 | Pure Go RTSP server and client library. |
| <b>[gst](https://github.com/ziutek/gst) | 165 | Go bindings for GStreamer. |
| <b>[go-m3u8](https://github.com/quangngotan95/go-m3u8) | 97 | Parser and generator library for Apple m3u8 playlists. |
| <b>[v4l](https://github.com/korandiz/v4l) | 68 | Video capture library for Linux, written in Go. |
| <b>[libgosubs](https://github.com/wargarblgarbl/libgosubs) | 19 | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| <b>[go-mpd](https://github.com/unki2aut/go-mpd) | 13 | Parser and generator library for MPEG-DASH manifest files. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Web Frameworks

_Full stack web frameworks._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Gin](https://github.com/gin-gonic/gin) | 62.0k | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| <b>[Beego](https://github.com/beego/beego) | 29.0k | beego is an open-source, high-performance web framework for the Go programming language. |
| <b>[Echo](https://github.com/labstack/echo) | 23.0k | High performance, minimalist Go web framework. |
| <b>[Fiber](https://github.com/gofiber/fiber) | 22.0k | An Express.js inspired web framework build on Fasthttp. |
| <b>[Revel](https://github.com/revel/revel) | 13.0k | High-productivity web framework for the Go language. |
| <b>[Goa](https://github.com/goadesign/goa) | 4.8k | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| <b>[Gizmo](https://github.com/NYTimes/gizmo) | 3.6k | Microservice toolkit used by the New York Times. |
| <b>[go-json-rest](https://github.com/ant0ine/go-json-rest) | 3.5k | Quick and easy way to setup a RESTful JSON API. |
| <b>[Macaron](https://github.com/go-macaron/macaron) | 3.3k | Macaron is a high productive and modular design web framework in Go. |
| <b>[utron](https://github.com/gernest/utron) | 2.2k | Lightweight MVC framework for Go(Golang). |
| <b>[Goyave](https://github.com/go-goyave/goyave) | 1.1k | Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities. |
| <b>[tigertonic](https://github.com/rcrowley/go-tigertonic) | 1000 | Go framework for building JSON web services inspired by Dropwizard. |
| <b>[tango](https://github.com/lunny/tango) | 835 | Micro & pluggable web framework for Go. |
| <b>[Gearbox](https://github.com/abahmed/gearbox) | 654 | A web framework written in Go with a focus on high performance and memory optimization. |
| <b>[Aero](https://github.com/aerogo/aero) | 487 | High-performance web framework for Go, reaches top scores in Lighthouse. |
| <b>[gongular](https://github.com/mustafaakin/gongular) | 449 | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| <b>[Air](https://github.com/aofei/air) | 417 | An ideally refined web framework for Go. |
| <b>[neo](https://github.com/ivpusic/neo) | 417 | Neo is minimal and fast Go Web Framework with extremely simple API. |
| <b>[mango](https://github.com/paulbellamy/mango) | 368 | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| <b>[Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 343 | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| <b>[Gondola](https://github.com/rainycape/gondola) | 309 | The web framework for writing faster sites, faster. |
| <b>[Flamingo](https://github.com/i-love-flamingo/flamingo) | 307 | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| <b>[rk-boot](https://github.com/rookie-ninja/rk-boot) | 268 | A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily. |
| <b>[Golf](https://github.com/dinever/golf) | 259 | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| <b>[WebGo](https://github.com/bnkamalesh/webgo) | 255 | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| <b>[Ginrpc](https://github.com/xxjwxc/ginrpc) | 231 | Gin parameter automatic binding tool,gin rpc tools. |
| <b>[uAdmin](https://github.com/uadmin/uadmin) | 198 | Fully featured web framework for Golang, inspired by Django. |
| <b>[hiboot](https://github.com/hidevopsio/hiboot) | 175 | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| <b>[appy](https://github.com/appist/appy) | 127 | An opinionated productive web framework that helps scaling business easier. |
| <b>[Huma](https://github.com/danielgtaylor/huma/) | 126 | Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI. |
| <b>[go-rest](https://github.com/ungerik/go-rest) | 125 | Small and evil REST framework for Go. |
| <b>[Microservice](https://github.com/claygod/microservice) | 101 | The framework for the creation of microservices, written in Golang. |
| <b>[patron](https://github.com/beatlabs/patron) | 97 | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| <b>[rux](https://github.com/gookit/rux) | 81 | Simple and fast web framework for build golang HTTP applications. |
| <b>[vox](https://github.com/aisk/vox) | 78 | A golang web framework for humans, inspired by Koa heavily. |
| <b>[Golax](https://github.com/fulldump/golax) | 74 | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| <b>[YARF](https://github.com/yarf-framework/yarf) | 65 | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| <b>[Fireball](https://github.com/zpatrick/fireball) | 58 | More "natural" feeling web framework. |
| <b>[goa](https://github.com/goa-go/goa) | 46 | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| <b>[GoTuna](https://github.com/gotuna/gotuna) | 40 | Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embedded views and static files. |
| <b>[Resoursea](https://github.com/resoursea/api) | 32 | REST framework for quickly writing resource based services. |
| <b>[rex](https://github.com/goanywhere/rex) | 32 | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| <b>[goweb](https://github.com/twharmon/goweb) | 31 | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |
| <b>[Banjo](https://github.com/nsheremet/banjo) | 19 | Very simple and fast web framework for Go. |
| <b>[anoweb](https://github.com/go-the-way/anoweb) | 3 | The lightweight and powerful web framework using the new way for Go.Another go the way. |
| <b>[golamb](https://github.com/twharmon/golamb) | 2 | Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway. |
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
| <b>[Tollbooth](https://github.com/didip/tollbooth) | 2.3k | Rate limit HTTP request handler. |
| <b>[CORS](https://github.com/rs/cors) | 2.2k | Easily add CORS capabilities to your API. |
| <b>[Limiter](https://github.com/ulule/limiter) | 1.6k | Dead simple rate limit middleware for Go. |
| <b>[go-server-timing](https://github.com/mitchellh/go-server-timing) | 839 | Add/parse Server-Timing header. |
| <b>[go-fault](https://github.com/github/go-fault) | 462 | Fault injection middleware for Go. |
| <b>[ln-paywall](https://github.com/philippgille/ln-paywall) | 127 | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| <b>[XFF](https://github.com/sebest/xff) | 90 | Handle `X-Forwarded-For` header and friends. |
| <b>[rk-grpc](https://github.com/rookie-ninja/rk-grpc) | 44 | Middleware for gRPC with logging, metrics, auth, tracing etc. |
| <b>[formjson](https://github.com/rs/formjson) | 36 | Transparently handle JSON input as a standard form POST. |
| <b>[rk-gin](https://github.com/rookie-ninja/rk-gin) | 35 | Middleware for Gin framework with logging, metrics, auth, tracing etc. |
| <b>[client-timing](https://github.com/posener/client-timing) | 20 | An HTTP client for Server-Timing header. |
| <b>[echo-middleware](https://github.com/faabiosr/echo-middleware) | 10 | Middleware for Echo framework with logging and metrics. |
| <b>[mid](https://github.com/bobg/mid) | 4 | Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more. |


<br>

[👆back to top](#catalogue-list)


<br>

#### Libraries for creating HTTP middlewares


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[negroni](https://github.com/urfave/negroni) | 7.2k | Idiomatic HTTP middleware for Golang. |
| <b>[alice](https://github.com/justinas/alice) | 2.6k | Painless middleware chaining for Go. |
| <b>[render](https://github.com/unrolled/render) | 1.7k | Go package for easily rendering JSON, XML, and HTML template responses. |
| <b>[stats](https://github.com/thoas/stats) | 586 | Go middleware that stores various information about your web application. |
| <b>[interpose](https://github.com/carbocation/interpose) | 295 | Minimalist net/http middleware for golang. |
| <b>[renderer](https://github.com/thedevsaddam/renderer) | 241 | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| <b>[muxchain](https://github.com/stephens2424/muxchain) | 209 | Lightweight middleware for net/http. |
| <b>[gores](https://github.com/alioygur/gores) | 99 | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| <b>[rye](https://github.com/InVisionApp/rye) | 97 | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| <b>[mediary](https://github.com/HereMobilityDevelopers/mediary) | 79 | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| <b>[chain](https://github.com/codemodus/chain) | 64 | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| <b>[go-wrap](https://github.com/go-on/wrap) | 59 | Small middlewares package for net/http. |
| <b>[catena](https://github.com/codemodus/catena) | 8 | http.Handler wrapper catenation (same API as "chain"). |


<br>

[👆back to top](#catalogue-list)


<br>

### Routers


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[mux](https://github.com/gorilla/mux) | 17.0k | Powerful URL router and dispatcher for golang. |
| <b>[httprouter](https://github.com/julienschmidt/httprouter) | 14.0k | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| <b>[chi](https://github.com/go-chi/chi) | 12.0k | Small, fast and expressive HTTP router built on net/context. |
| <b>[gocraft/web](https://github.com/gocraft/web) | 1.5k | Mux and middleware package in Go. |
| <b>[Bone](https://github.com/go-zoo/bone) | 1.3k | Lightning Fast HTTP Multiplexer. |
| <b>[Goji](https://github.com/goji/goji) | 904 | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| <b>[fasthttprouter](https://github.com/buaazp/fasthttprouter) | 866 | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| <b>[httptreemux](https://github.com/dimfeld/httptreemux) | 551 | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| <b>[xujiajun/gorouter](https://github.com/xujiajun/gorouter) | 527 | A simple and fast HTTP router for Go. |
| <b>[ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 441 | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| <b>[lars](https://github.com/go-playground/lars) | 389 | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| <b>[Siesta](https://github.com/VividCortex/siesta) | 352 | Composable framework to write middleware and handlers. |
| <b>[vestigo](https://github.com/husobee/vestigo) | 269 | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| <b>[gowww/router](https://github.com/gowww/router) | 164 | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| <b>[GoRouter](https://github.com/vardius/gorouter) | 130 | GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| <b>[pure](https://github.com/go-playground/pure) | 128 | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| <b>[alien](https://github.com/gernest/alien) | 122 | Lightweight and fast http router from outer space. |
| <b>[violetear](https://github.com/nbari/violetear) | 104 | Go HTTP router. |
| <b>[Bxog](https://github.com/claygod/Bxog) | 103 | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| <b>[xmux](https://github.com/rs/xmux) | 96 | High performance muxer based on `httprouter` with `net/context` support. |
| <b>[bellt](https://github.com/GuilhermeCaruso/bellt) | 54 | A simple Go HTTP router. |
| <b>[ngamux](https://github.com/ngamux/ngamux) | 51 | Simple HTTP router for Go. |
| <b>[goblin](https://github.com/bmf-san/goblin) | 35 | A golang http router based on trie tree. |
| <b>[FastRouter](https://github.com/razonyang/fastrouter) | 21 | a fast, flexible HTTP router written in Go. |
| <b>[GoLobby/Router](https://github.com/golobby/router) | 18 | GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language. |
| <b>[goroute](https://github.com/goroute/route) | 8 | Simple yet powerful HTTP request multiplexer. |
| <b>[nchi](https://github.com/muir/nchi) | 3 | chi-like router built on httprouter with dependency injection based middleware wrappers |


<br>

[👆back to top](#catalogue-list)


<br><br>

## WebAssembly


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[tinygo](https://github.com/tinygo-org/tinygo) | 11.0k | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| <b>[dom](https://github.com/dennwc/dom) | 460 | DOM library. |
| <b>[go-canvas](https://github.com/markfarnan/go-canvas) | 172 | Library to use HTML5 Canvas, with all drawing within go code. |
| <b>[wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 128 | Run Go WASM tests in your browser. |
| <b>[webapi](https://github.com/gowebapi/webapi) | 117 | Bindings for DOM and HTML generated from WebIDL. |
| <b>[vert](https://github.com/norunners/vert) | 77 | Interop between Go and JS values. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Windows


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-ole](https://github.com/go-ole/go-ole) | 893 | Win32 OLE implementation for golang. |
| <b>[d3d9](https://github.com/gonutz/d3d9) | 132 | Go bindings for Direct3D9. |
| <b>[gosddl](https://github.com/MonaxGT/gosddl) | 8 | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## XML

_Libraries and tools for manipulating XML._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[zek](https://github.com/miku/zek) | 584 | Generate a Go struct from XML. |
| <b>[xpath](https://github.com/antchfx/xpath) | 504 | XPath package for Go. |
| <b>[xquery](https://github.com/antchfx/xquery) | 155 | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| <b>[xml2map](https://github.com/sbabiv/xml2map) | 42 | XML to MAP converter written Golang. |
| <b>[xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 21 | Procedural XML generation API based on libxml2's xmlwriter module. |
| <b>[XML-Comp](https://github.com/xml-comp/xml-comp) | 17 | Simple command line XML comparer that generates diffs of folders, files and tags. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Zero Trust

_Libraries and tools to implement Zero Trust architectures._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[Cosign](https://github.com/sigstore/cosign) | 2.3k | Container Signing, Verification and Storage in an OCI registry. |
| <b>[Spire](https://github.com/spiffe/spire) | 1.2k | SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms. |
| <b>[in-toto](https://github.com/in-toto/in-toto-golang) | 62 | Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation. |
| <b>[Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) | 42 | Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Code Analysis

_Source code analysis tools, also known as Static Application Security Testing (SAST) Tools._


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) | 4.9k | gosimple is a linter for Go source code that specialises on simplifying code. |
| <b>[staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) | 4.9k | staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#. |
| <b>[unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) | 4.9k | unused checks Go code for unused constants, variables, functions and types. |
| <b>[GoLint](https://github.com/golang/lint) | 4.0k | Golint is a linter for Go source code. |
| <b>[errcheck](https://github.com/kisielk/errcheck) | 1.9k | Errcheck is a program for checking for unchecked errors in Go programs. |
| <b>[go-critic](https://github.com/go-critic/go-critic) | 1.4k | source code linter that brings checks that are currently not implemented in other linters. |
| <b>[gcvis](https://github.com/davecheney/gcvis) | 1.1k | Visualise Go program GC trace data in real time. |
| <b>[GoPlantUML](https://github.com/jfeliu007/goplantuml) | 1.1k | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| <b>[php-parser](https://github.com/z7zmey/php-parser) | 886 | A Parser for PHP written in Go. |
| <b>[goast-viewer](https://github.com/yuroyoro/goast-viewer) | 636 | Web based Golang AST visualizer. |
| <b>[go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 610 | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| <b>[go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 592 | An easy way to find outdated dependencies of your Go projects. |
| <b>[golines](https://github.com/segmentio/golines) | 446 | Formatter that automatically shortens long lines in Go code. |
| <b>[todocheck](https://github.com/preslavmihaylov/todocheck) | 387 | Static code analyser which links TODO comments in code with issues in your issue tracker. |
| <b>[unconvert](https://github.com/mdempsky/unconvert) | 323 | Remove unnecessary type conversions from Go source. |
| <b>[dupl](https://github.com/mibk/dupl) | 286 | Tool for code clone detection. |
| <b>[tickgit](https://github.com/augmentable-dev/tickgit) | 278 | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| <b>[gostatus](https://github.com/shurcooL/gostatus) | 243 | Command line tool, shows the status of repositories that contain Go packages. |
| <b>[apicompat](https://github.com/bradleyfalzon/apicompat) | 175 | Checks recent changes to a Go project for backwards incompatible changes. |
| <b>[go-checkstyle](https://github.com/qiniu/checkstyle) | 121 | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| <b>[lint](https://github.com/surullabs/lint) | 66 | Run linters as part of go test. |
| <b>[validate](https://github.com/mccoyst/validate) | 59 | Automatically validates struct fields with tags. |
| <b>[go-outdated](https://github.com/firstrow/go-outdated) | 42 | Console application that displays outdated packages. |
| <b>[ChainJacking](https://github.com/Checkmarx/chainjacking) | 27 | Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack. |
| <b>[usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) | 16 | A linter that detect the possibility to use variables/constants from the Go standard library. |
| <b>[tarp](https://github.com/verygoodsoftwarenotvirus/tarp) | 14 | tarp finds functions and methods without direct unit tests in Go source code. |
| <b>[golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) | 8 | iFood API SDK. |
| <b>[GoCover.io](https://gocover.io/) | - | GoCover.io offers the code coverage of any golang package as a service. |
| <b>[goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) | - | Tool to fix (add, remove) your Go imports automatically. |
| <b>[Golint online](http://go-lint.appspot.com/) | - | Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package. |
| <b>[goreturns](https://sourcegraph.com/github.com/sqs/goreturns) | - | Adds zero-value return statements to match the func return types. |


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
| <b>[vscode-go](https://github.com/golang/vscode-go) | 2.9k | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| <b>[go-plus](https://github.com/joefitzgerald/go-plus) | 1.5k | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| <b>[go-mode](https://github.com/dominikh/go-mode.el) | 1.3k | Go mode for GNU/Emacs. |
| <b>[coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) | 479 | This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim. |
| <b>[Watch](https://github.com/eaburns/Watch) | 192 | Runs a command in an acme win on file changes. |
| <b>[goimports-reviser](https://github.com/incu6us/goimports-reviser) | 168 | Formatting tool for imports. |
| <b>[vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 87 | Vim plugin to highlight syntax errors on save. |
| <b>[go-language-server](https://github.com/theia-ide/go-language-server) | 31 | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| <b>[gounit-vim](https://github.com/hexdigest/gounit-vim) | 23 | Vim plugin for generating Go tests based on the function's or method's signature. |
| <b>[theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 16 | Go language support for the Theia IDE. |
| <b>[Go Doc](https://github.com/msyrus/vscode-go-doc) | 4 | A Visual Studio Code extension for showing definition in output and generating go doc. |
| <b>[Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) | - | Go plugin for JetBrains IDEs. |
| <b>[goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) | - | This extension adds benchmark profiling support for the Go language to VS Code. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Generate Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[gotests](https://github.com/cweill/gotests) | 4.1k | Generate Go tests from your source code. |
| <b>[genny](https://github.com/cheekybits/genny) | 1.6k | Elegant generics for Go. |
| <b>[re2dfa](https://github.com/opennota/re2dfa) | 193 | Transform regular expressions into finite state machines and output Go source code. |
| <b>[xgen](https://github.com/xuri/xgen) | 174 | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| <b>[hasgo](https://github.com/DylanMeeus/hasgo) | 119 | Generate Haskell inspired functions for your slices. |
| <b>[gonerics](https://github.com/bouk/gonerics) | 114 | Idiomatic Generics in Go. |
| <b>[gocontracts](https://github.com/Parquery/gocontracts) | 85 | brings design-by-contract to Go by synchronizing the code with the documentation. |
| <b>[gounit](https://github.com/hexdigest/gounit) | 63 | Generate Go tests using your own templates. |
| <b>[generic](https://github.com/usk81/generic) | 43 | flexible data type for Go. |
| <b>[godal](https://github.com/mafulong/godal) | 13 | Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm. |
| <b>[TOML-to-Go](https://xuri.me/toml-to-go) | - | Translates TOML into a Go type in the browser instantly. |


<br>

[👆back to top](#catalogue-list)


<br><br>

## Go Tools


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[go-swagger](https://github.com/go-swagger/go-swagger) | 7.9k | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| <b>[OctoLinker](https://github.com/OctoLinker/browser-extension) | 5.0k | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| <b>[go-callvis](https://github.com/TrueFurby/go-callvis) | 4.3k | Visualize call graph of your Go program using dot format. |
| <b>[depth](https://github.com/KyleBanks/depth) | 774 | Visualize dependency trees of any package by analyzing imports. |
| <b>[richgo](https://github.com/kyoh86/richgo) | 720 | Enrich `go test` outputs with text decorations. |
| <b>[rts](https://github.com/galeone/rts) | 232 | RTS: response to struct. Generates Go structs from server responses. |
| <b>[godbg](https://github.com/tylerwince/godbg) | 185 | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| <b>[typex](https://github.com/dtgorski/typex) | 151 | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| <b>[gothanks](https://github.com/psampaz/gothanks) | 113 | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| <b>[colorgo](https://github.com/songgao/colorgo) | 110 | Wrapper around `go` command for colorized `go build` output. |
| <b>[roumon](https://github.com/becheran/roumon) | 84 | Monitor current state of all active goroutines via a command line interface. |
| <b>[go-james](https://github.com/pieterclaerhout/go-james) | 53 | Go project skeleton creator, builds and tests your projects without the manual setup. |
| <b>[igo](https://github.com/rocketlaunchr/igo) | 51 | An igo to go transpiler (new language features for Go language!) |
| <b>[go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 39 | Bash completion for go and wgo. |
| <b>[generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 24 | A [Yeoman](https://yeoman.io) generator to get new Go projects started. |
| <b>[gomodrun](https://github.com/dustinblackman/gomodrun/) | 23 | Go tool that executes and caches binaries included in go.mod files. |
| <b>[gotestdox](https://github.com/bitfield/gotestdox) | 12 | Show Go test results as readable sentences. |
| <b>[docs](https://github.com/go-oas/docs) | 11 | Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard. |
| <b>[modver](https://github.com/bobg/modver) | 2 | Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules. |
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
| <b>[kubernetes](https://github.com/kubernetes/kubernetes) | 91.0k | Container Cluster Manager from Google. |
| <b>[Moby](https://github.com/moby/moby) | 64.0k | Collaborative project for the container ecosystem to assemble container-based systems. |
| <b>[traefik](https://github.com/containous/traefik) | 39.0k | Reverse proxy and load balancer with support for multiple backends. |
| <b>[Gitea](https://github.com/go-gitea/gitea) | 32.0k | Fork of Gogs, entirely community driven. |
| <b>[Vegeta](https://github.com/tsenart/vegeta) | 20.0k | HTTP load testing tool and library. It's over 9000! |
| <b>[Hey](https://github.com/rakyll/hey) | 14.0k | Hey is a tiny program that sends some load to a web application. |
| <b>[Packer](https://github.com/mitchellh/packer) | 14.0k | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| <b>[webhook](https://github.com/adnanh/webhook) | 8.1k | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| <b>[GVM](https://github.com/moovweb/gvm) | 7.7k | GVM provides an interface to manage Go versions. |
| <b>[gaia](https://github.com/gaia-pipeline/gaia) | 4.8k | Build powerful pipelines in any programming language. |
| <b>[ko](https://github.com/google/ko) | 4.8k | Command line tool for building and deploying Go applications on Kubernetes |
| <b>[Ddosify](https://github.com/ddosify/ddosify) | 4.7k | High-performance load testing tool, written in Golang. |
| <b>[gox](https://github.com/mitchellh/gox) | 4.3k | Dead simple, no frills Go cross compile tool. |
| <b>[Mizu](https://github.com/up9inc/mizu) | 3.8k | API traffic viewer for Kubernetes enabling you to view all API communication between microservices, multiprotocol support: HTTP1.1, HTTP/2, AMQP, Kafka, Redis. |
| <b>[bombardier](https://github.com/codesenberg/bombardier) | 3.7k | Fast cross-platform HTTP benchmarking tool. |
| <b>[bosun](https://github.com/bosun-monitor/bosun) | 3.3k | Time Series Alerting Framework. |
| <b>[Pomerium](https://github.com/pomerium/pomerium) | 3.2k | Pomerium is an identity-aware access proxy. |
| <b>[script](https://github.com/bitfield/script) | 2.9k | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| <b>[fac](https://github.com/mkchoi212/fac) | 1.8k | Command-line user interface to fix git merge conflicts. |
| <b>[kala](https://github.com/ajvb/kala) | 1.8k | Simplistic, modern, and performant job scheduler. |
| <b>[goxc](https://github.com/laher/goxc) | 1.7k | build tool for Go, with a focus on cross-compiling and packaging. |
| <b>[StatusOK](https://github.com/sanathp/statusok) | 1.6k | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| <b>[s5cmd](https://github.com/peak/s5cmd) | 1.2k | Blazing fast S3 and local filesystem execution tool. |
| <b>[go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 1.1k | Enable your Go applications to self update. |
| <b>[s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1.1k | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| <b>[ghorg](https://github.com/gabrie30/ghorg) | 1000 | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket. |
| <b>[Fleet device management](https://github.com/fleetdm/fleet) | 888 | Lightweight, programmable telemetry for servers and workstations. |
| <b>[skm](https://github.com/TimothyYe/skm) | 791 | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| <b>[Scaleway-cli](https://github.com/scaleway/scaleway-cli) | 761 | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| <b>[uTask](https://github.com/ovh/utask) | 708 | Automation engine that models and executes business processes declared in yaml. |
| <b>[kwatch](https://github.com/abahmed/kwatch) | 667 | Monitor & detect crashes in your Kubernetes(K8s) cluster instantly. |
| <b>[kool](https://github.com/kool-dev/kool) | 605 | Command line tool for managing Docker environments as an easy way. |
| <b>[cassowary](https://github.com/rogerwelin/cassowary) | 604 | Modern cross-platform HTTP load-testing tool written in Go. |
| <b>[aurora](https://github.com/xuri/aurora) | 564 | Cross-platform web-based Beanstalkd queue server console. |
| <b>[govvv](https://github.com/ahmetalpbalkan/govvv) | 527 | “go build” wrapper to easily add version information into Go binaries. |
| <b>[Pewpew](https://github.com/bengadbois/pewpew) | 344 | Flexible HTTP command line stress tester. |
| <b>[jcli](https://github.com/jenkins-zh/jenkins-cli) | 332 | Jenkins CLI allows you manage your Jenkins as an easy way. |
| <b>[gonative](https://github.com/inconshreveable/gonative) | 331 | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| <b>[trubka](https://github.com/xitonix/trubka) | 322 | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| <b>[Mora](https://github.com/emicklei/mora) | 303 | REST server for accessing MongoDB documents and meta data. |
| <b>[lstags](https://github.com/ivanilves/lstags) | 289 | Tool and API to sync Docker images across different registries. |
| <b>[Balerter](https://github.com/balerter/balerter) | 273 | A self-hosted script-based alerting manager. |
| <b>[manssh](https://github.com/xwjdsh/manssh) | 268 | manssh is a command line tool for managing your ssh alias config easily. |
| <b>[easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 252 | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| <b>[dogo](https://github.com/liudng/dogo) | 248 | Monitoring changes in the source file and automatically compile and run (restart). |
| <b>[godbg](https://github.com/sirnewton01/godbg) | 225 | Web-based gdb front-end application. |
| <b>[terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 213 | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| <b>[Blast](https://github.com/dave/blast) | 207 | A simple tool for API load testing and batch jobs. |
| <b>[gobrew](https://github.com/cryptojuice/gobrew) | 190 | gobrew lets you easily switch between multiple versions of go. |
| <b>[abbreviate](https://github.com/dnnrly/abbreviate) | 183 | abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs. |
| <b>[kcli](https://github.com/cswank/kcli) | 180 | Command line tool for inspecting kafka topics/partitions/messages. |
| <b>[ostent](https://github.com/ostrost/ostent) | 173 | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| <b>[grapes](https://github.com/yaronsumel/grapes) | 156 | Lightweight tool designed to distribute commands over ssh with ease. |
| <b>[winrm-cli](https://github.com/masterzen/winrm-cli) | 143 | Cli tool to remotely execute commands on Windows machines. |
| <b>[Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) | 132 | A go library and an executable that produces valid Dockerfiles using various input channels. |
| <b>[s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 121 | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| <b>[drone-scp](https://github.com/appleboy/drone-scp) | 109 | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| <b>[go-furnace](https://github.com/go-furnace/go-furnace) | 90 | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| <b>[Mantil](https://github.com/mantil-io/mantil) | 75 | Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure. |
| <b>[go-rocket-update](https://github.com/mouuff/go-rocket-update) | 68 | A simple way to make self updating Go applications - Supports Github and Gitlab. |
| <b>[Dropship](https://github.com/chrismckenzie/dropship) | 60 | Tool for deploying code via cdn. |
| <b>[drone-jenkins](https://github.com/appleboy/drone-jenkins) | 34 | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| <b>[docker-go-mingw](https://github.com/x1unix/docker-go-mingw) | 33 | Docker image for building Go binaries for Windows with MinGW toolchain. |
| <b>[Rodent](https://github.com/alouche/rodent) | 32 | Rodent helps you manage Go versions, projects and track dependencies. |
| <b>[awsenv](https://github.com/soniah/awsenv) | 29 | Small binary that loads Amazon (AWS) environment variables for a profile. |
| <b>[lwc](https://github.com/timdp/lwc) | 27 | A live-updating version of the UNIX wc command. |
| <b>[DepCharge](https://github.com/centerorbit/depcharge) | 22 | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| <b>[httpref](https://github.com/dnnrly/httpref) | 22 | httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. |
| <b>[sg](https://github.com/ChristopherRabotin/sg) | 7 | Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. |
| <b>[aptly](https://github.com/smira/aptly) | 5 | aptly is a Debian repository management tool. |
| <b>[wait-for](https://github.com/dnnrly/wait-for) | 3 | Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things. |
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
| <b>[croc](https://github.com/schollz/croc) | 20.0k | Easily and securely send files or folders from one computer to another. |
| <b>[restic](https://github.com/restic/restic) | 18.0k | De-duplicating backup program. |
| <b>[Gor](https://github.com/buger/gor) | 16.0k | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| <b>[Seaweed File System](https://github.com/chrislusf/seaweedfs) | 15.0k | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| <b>[Comcast](https://github.com/tylertreat/Comcast) | 9.6k | Simulate bad network connections. |
| <b>[toxiproxy](https://github.com/shopify/toxiproxy) | 8.4k | Proxy to simulate network and system conditions for automated tests. |
| <b>[confd](https://github.com/kelseyhightower/confd) | 7.9k | Manage local application configuration files using templates and data from etcd or consul. |
| <b>[LiteIDE](https://github.com/visualfc/liteide) | 6.9k | LiteIDE is a simple, open source, cross-platform Go IDE. |
| <b>[drive](https://github.com/odeke-em/drive) | 6.4k | Google Drive client for the commandline. |
| <b>[nes](https://github.com/fogleman/nes) | 5.1k | Nintendo Entertainment System (NES) emulator written in Go. |
| <b>[Duplicacy](https://github.com/gilbertchen/duplicacy) | 4.2k | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| <b>[scc](https://github.com/boyter/scc) | 3.7k | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| <b>[myLG](https://github.com/mehrdadrad/mylg) | 2.6k | Command Line Network Diagnostic tool written in Go. |
| <b>[GoBoy](https://github.com/Humpheh/goboy) | 2.5k | Nintendo Game Boy Color emulator written in Go. |
| <b>[Stack Up](https://github.com/pressly/sup) | 2.4k | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| <b>[lgo](https://github.com/yunabe/lgo) | 2.2k | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| <b>[Circuit](https://github.com/gocircuit/circuit) | 2.0k | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| <b>[snap](https://github.com/intelsdi-x/snap) | 1.8k | Powerful telemetry framework. |
| <b>[blocky](https://github.com/0xERR0R/blocky) | 1.7k | Fast and lightweight DNS proxy as ad-blocker for local network with many features. |
| <b>[borg](https://github.com/crufter/borg) | 1.6k | Terminal based search engine for bash snippets. |
| <b>[Documize](https://github.com/documize/community) | 1.6k | Modern wiki software that integrates data from SaaS tools. |
| <b>[Plik](https://github.com/root-gg/plik) | 1000 | Plik is a temporary file upload system (Wetransfer like) in Go. |
| <b>[shell2http](https://github.com/msoap/shell2http) | 965 | Executing shell commands via http server (for prototyping or remote control). |
| <b>[vFlow](https://github.com/VerizonDigital/vflow) | 913 | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| <b>[Go Package Store](https://github.com/shurcooL/Go-Package-Store) | 888 | App that displays updates for the Go packages in your GOPATH. |
| <b>[peg](https://github.com/pointlander/peg) | 863 | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| <b>[Leaps](https://github.com/jeffail/leaps) | 725 | Pair programming service using Operational Transforms. |
| <b>[gfile](https://github.com/Antonito/gfile) | 675 | Securely transfer files between two computers, without any third party, over WebRTC. |
| <b>[Guora](https://github.com/meloalright/guora) | 599 | A self-hosted Quora like web application written in Go. |
| <b>[Gebug](https://github.com/moshebe/gebug) | 595 | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| <b>[gocc](https://github.com/goccmack/gocc) | 535 | Gocc is a compiler kit for Go written in Go. |
| <b>[mockingjay](https://github.com/quii/mockingjay-server) | 519 | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| <b>[sake](https://github.com/alajmo/sake) | 458 | sake is a command runner for local and remote hosts. |
| <b>[go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 452 | Video streaming torrent client. |
| <b>[Gokapi](https://github.com/Forceu/gokapi) | 361 | Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload. |
| <b>[ipe](https://github.com/dimiro1/ipe) | 355 | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| <b>[ide](https://github.com/thestrukture/ide) | 349 | Browser accessible IDE. Designed for Go with Go. |
| <b>[woke](https://github.com/get-woke/woke) | 338 | Detect non-inclusive language in your source code. |
| <b>[tcpprobe](https://github.com/mehrdadrad/tcpprobe) | 324 | TCP tool for network performance and path monitoring, including socket statistics. |
| <b>[wellington](https://github.com/wellington/wellington) | 298 | Sass project management tool, extends the language with sprite functions (like Compass). |
| <b>[Cherry](https://github.com/rafael-santiago/cherry) | 281 | Tiny webchat server in Go. |
| <b>[Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) | 218 | 🐮 cowsay is reborn. for a New Era. |
| <b>[tcpdog](https://github.com/mehrdadrad/tcpdog) | 196 | eBPF based TCP observability. |
| <b>[joincap](https://github.com/assafmo/joincap) | 175 | Command-line utility for merging multiple pcap files together. |
| <b>[Orbit](https://github.com/gulien/orbit) | 169 | A simple tool for running commands and generating files from templates. |
| <b>[vaku](https://github.com/lingrino/vaku) | 138 | CLI & API for folder-based functions in Vault like copy, move, and search. |
| <b>[stew](https://github.com/marwanhawari/stew) | 100 | An independent package manager for compiled binaries. |
| <b>[dp](https://github.com/scryinfo/dp) | 85 | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| <b>[boxed](https://github.com/tejo/boxed) | 77 | Dropbox based blog engine. |
| <b>[crawley](https://github.com/s0rg/crawley) | 63 | Web scraper/crawler for cli. |
| <b>[naclpipe](https://github.com/unix4fun/naclpipe) | 22 | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| <b>[term-quiz](https://github.com/crazcalm/term-quiz) | 22 | Quizzes for your terminal. |
| <b>[Snitch](https://github.com/lucasgomide/snitch) | 15 | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| <b>[GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 12 | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |
| <b>[protoncheck](https://github.com/servusdei2018/protoncheck) | 3 | ProtonMail module for waybar/polybar/yabar/i3blocks. |
| <b>[hoofli](https://github.com/dnnrly/hoofli) | 3 | Generate PlantUML diagrams from Chrome or Firefox network inspections. |
| <b>[Juju](https://jujucharms.com/) | - | Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more. |
| <b>[limetext](https://limetext.github.io) | - | Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text. |
| <b>[syncthing](https://syncthing.net/) | - | Open, decentralized file synchronization tool and protocol. |
| <b>[tsuru](https://tsuru.io/) | - | Extensible and open source Platform as a Service software. |
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
| <b>[go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 1.7k | Go web framework benchmark. |
| <b>[go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1.6k | Go HTTP request router benchmark and comparison. |
| <b>[go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1.3k | Benchmarks of Go serialization methods. |
| <b>[skynet](https://github.com/atemerev/skynet) | 1000 | Skynet 1M threads microbenchmark. |
| <b>[speedtest-resize](https://github.com/fawick/speedtest-resize) | 218 | Compare various Image resize algorithms for the Go language. |
| <b>[go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 144 | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| <b>[gospeed](https://github.com/feyeleanor/GoSpeed) | 110 | Go micro-benchmarks for calculating the speed of language constructs. |
| <b>[autobench](https://github.com/davecheney/autobench) | 93 | Framework to compare the performance between different Go versions. |
| <b>[golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 61 | Collection of benchmarks for popular Go database/SQL utilities. |
| <b>[gocostmodel](https://github.com/PuerkitoBio/gocostmodel) | 57 | Benchmarks of common basic operations for the Go language. |
| <b>[kvbench](https://github.com/jimrobinson/kvbench) | 24 | Key/Value database benchmark. |
| <b>[go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 23 | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| <b>[go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) | 23 | benchmarks for machine learning inference in Go. |
| <b>[go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) | 6 | Go JSON benchmark. |


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


<br>

[👆back to top](#catalogue-list)


<br>

### Free e-books


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[GoBooks](https://github.com/dariubs/GoBooks) | 13.0k | A curated list of Go books. |
| <b>[The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 8.8k | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| <b>[Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) | 3.0k | Learn how to write webapps without a framework in Go. |
| <b>[Go Succinctly](https://github.com/thedevsir/gosuccinctly) | 22 | in Persian. |
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
| <b>[gophers](https://github.com/egonelbre/gophers) | 2.8k | Free gophers. |
| <b>[gophers](https://github.com/ashleymcnamara/gophers) | 2.7k | Gopher artworks by Ashley McNamara. |
| <b>[Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) | 2.5k | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| <b>[gophericons](https://github.com/shalakhin/gophericons) | 606 | 34 gopher images for Go developers community |
| <b>[gopherize.me](https://github.com/matryer/gopherize.me) | 590 | Gopherize yourself. |
| <b>[gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 538 | gopher stickers |
| <b>[gopher-logos](https://github.com/GolangUA/gopher-logos) | 106 | adorable gopher logos. |
| <b>[gophers](https://github.com/sillecelik/go-gopher) | 103 | Gopher amigurumi toy pattern. |
| <b>[gophers](https://github.com/rogeralsing/gophers) | 57 | random gopher graphics. |
| <b>[Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 56 | Go gopher Vector Data [.ai, .svg]. |
| <b>[gophers](https://github.com/scraly/gophers) | 18 | Gophers by Aurélie Vache. |


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


<br>

[👆back to top](#catalogue-list)


<br><br>

## Style Guides


| Repo | Stars | Description |
| :------ | :------ | :------ |
| <b>[CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md) | 25.0k | CockroachDB - the open source, cloud-native distributed SQL database. |
| <b>[Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst) | 14.0k | Hyperledger Fabric is an enterprise-grade permissioned distributed ledger framework for developing solutions and applications. Its modular and versatile design satisfies a broad range of industry use cases. It offers a unique approach to consensus that enables performance at scale while preserving privacy. |
| <b>[Uber](https://github.com/uber-go/guide/blob/master/style.md) | 12.0k | The Uber Go Style Guide. |
| <b>[Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification) | 2.8k | Autonomous (self-hosted) BitTorrent DHT search engine suite. |
| <b>[bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) | 1.3k | 🏆 Opinionated Styleguide for the Go language |
| <b>[Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md) | 309 | Playbook da linguagem Go |
| <b>[GitLab](https://docs.gitlab.com/ee/development/go_guide/) | - |  |
| <b>[Sourcegraph](https://about.sourcegraph.com/handbook/engineering/go_style_guide) | - |  |
| <b>[Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/) | - |  |


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
| <b>[Go Projects](https://github.com/golang/go/wiki/Projects) | 103.0k | List of projects on the Go community wiki. |
| <b>[awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 29.0k | List of other amazingly awesome lists. |
| <b>[Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) | 23.0k | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| <b>[Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) | 468 | A curated list of awesome golang workshops. |
| <b>[golang-graphics](https://github.com/mholt/golang-graphics) | 138 | Collection of Go images, graphics, and art. |
| <b>[gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 40 | Collection of Go projects that needs help. Good place to start your open-source way in Go. |
| <b>[awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) | 19 | Parse awesome-go README file and generate a new README file with repo info. |
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
| <b>[Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) | 41.0k | Golang ebook intro how to build a web app with golang. |
| <b>[go-patterns](https://github.com/tmrts/go-patterns) | 20.0k | Curated list of Go design patterns, recipes and idioms. |
| <b>[Learn Go with TDD](https://github.com/quii/learn-go-with-tests) | 18.0k | Learn Go with test-driven development. |
| <b>[Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) | 14.0k | Learn Go with thousands of examples, exercises, and quizzes. |
| <b>[Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) | 6.8k | Go's reference card. |
| <b>[go-clean-template](https://github.com/evrone/go-clean-template) | 3.4k | Clean Architecture template for Golang services. |
| <b>[Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 3.1k | Examples of Golang compared to Node.js for learning. |
| <b>[Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) | 1.4k | A little e-book on Ethereum Development with Go. |
| <b>[Working with Go](https://github.com/mkaz/working-with-go) | 1.2k | Intro to go for experienced programmers. |
| <b>[goapp](https://github.com/bnkamalesh/goapp) | 502 | An opinionated guideline to structure & develop a Go web application/service. |
| <b>[Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) | 83 | Collection of programming design patterns implemented in Go. |
| <b>[Debugged.it Go patterns](https://github.com/haveyoudebuggedit/go-patterns) | 5 | Advanced Go patterns with ready-to-run examples. |
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
| <b>[Your basic Go](https://yourbasic.org/golang) | - | Huge collection of tutorials and how to's. |
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

