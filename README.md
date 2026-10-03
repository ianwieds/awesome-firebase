<p align="center"><!-- awesome:hero --><img src=".github/assets/hero.gif" width="100%" alt="Animated isometric scene: a flame core on a hearth sends light pulses along wires to a database, a cloud, a function and a lock."><!-- /awesome:hero --></p>

<!-- awesome:title --><h1 align="center">Awesome Firebase</h1><!-- /awesome:title -->

<p align="center"><!-- awesome:tagline -->A curated list of Firebase SDKs, libraries, tools, extensions, guides and talks.<!-- /awesome:tagline --></p>

<!-- awesome:badges -->
<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="contributing.md"><img src="https://img.shields.io/badge/PRs-welcome-FFA000" alt="PRs welcome"></a>
  <a href="https://github.com/ianwieds/awesome-firebase/commits/main"><img src="https://img.shields.io/github/last-commit/ianwieds/awesome-firebase?color=FFA000" alt="Last commit"></a>
</p>
<!-- /awesome:badges -->

[Firebase](https://firebase.google.com) is Google's app platform for databases, auth, hosting, functions and AI features. This list covers the official SDKs and docs and the community projects built around them.

## Contents

- [Official Resources](#official-resources)
  - [Docs and Guides](#docs-and-guides)
  - [News and Status](#news-and-status)
- [SDKs](#sdks)
  - [Client SDKs](#client-sdks)
  - [Admin SDKs](#admin-sdks)
- [Cloud Functions](#cloud-functions)
- [Databases](#databases)
- [Authentication and Security](#authentication-and-security)
- [Hosting and App Hosting](#hosting-and-app-hosting)
- [AI](#ai)
  - [Firebase AI Logic and Agent Tools](#firebase-ai-logic-and-agent-tools)
  - [Genkit](#genkit)
- [Extensions](#extensions)
- [Framework Integrations](#framework-integrations)
- [Mobile and Games](#mobile-and-games)
- [Tools](#tools)
  - [CLI and Emulators](#cli-and-emulators)
  - [Editor Extensions](#editor-extensions)
  - [Admin Panels and Data Tools](#admin-panels-and-data-tools)
  - [Testing and CI](#testing-and-ci)
- [Samples and Starters](#samples-and-starters)
  - [Official Samples](#official-samples)
  - [Community Apps](#community-apps)
- [Guides and Articles](#guides-and-articles)
- [Talks and Videos](#talks-and-videos)
- [Community](#community)
  - [Channels](#channels)
  - [People](#people)
- [Contributing](#contributing)

## Official Resources

### Docs and Guides

- [Admin SDK Setup](https://firebase.google.com/docs/admin/setup) - Add the Admin SDK to a server or other trusted environment.
- [Android Setup](https://firebase.google.com/docs/android/setup) - Connect an Android app to a Firebase project.
- [API Reference](https://firebase.google.com/docs/reference/) - Reference pages for every Firebase SDK and REST API.
- [Apple Platforms Setup](https://firebase.google.com/docs/ios/setup) - Connect an iOS, macOS or other Apple platform app to Firebase.
- [Firebase Codelabs](https://codelabs.developers.google.com/?cat=Firebase) - Step-by-step coding tutorials from Google, filtered to Firebase.
- [Firebase Documentation](https://firebase.google.com/docs) - The official guides, references and samples for every Firebase product.
- [Firebase for Games](https://firebase.google.com/games) - Landing page that gathers Firebase resources for Unity and C++ game teams.
- [Firebase Samples](https://firebase.google.com/docs/samples) - Index of official sample apps, grouped by product and platform.
- [Flutter Setup](https://firebase.google.com/docs/flutter/setup) - Add Firebase to a Flutter app with the FlutterFire CLI.
- [Modular Web SDK](https://firebase.google.com/docs/web/learn-more#modular-version) - Why the tree-shakeable modular JavaScript API ships smaller bundles.
- [Web Setup](https://firebase.google.com/docs/web/setup) - Add the JavaScript SDK to a web app.

### News and Status

- [Firebase Blog](https://firebase.blog) - Product announcements and engineering posts from the Firebase team.
- [Firebase Release Notes](https://firebase.google.com/support/releases) - Changelog for every Firebase SDK, the CLI and the console.
- [Firebase Status Dashboard](https://status.firebase.google.com) - Live service health and incident history for each Firebase product.

## SDKs

### Client SDKs

- [Firebase Android SDK](https://github.com/firebase/firebase-android-sdk) - Source of the Firebase libraries for Android.
- [Firebase Apple SDK](https://github.com/firebase/firebase-ios-sdk) - Source of the Firebase libraries for iOS, macOS, tvOS and watchOS.
- [Firebase C++ SDK](https://github.com/firebase/firebase-cpp-sdk) - Firebase client libraries for C++ games and apps.
- [Firebase JavaScript SDK](https://github.com/firebase/firebase-js-sdk) - The Firebase client SDK for browsers and Node.js.
- [Firebase Kotlin SDK](https://github.com/GitLiveApp/firebase-kotlin-sdk) - Kotlin Multiplatform wrapper for Firebase on Android, iOS, desktop and web.
- [Firebase Unity SDK](https://github.com/firebase/firebase-unity-sdk) - Firebase client libraries for Unity projects.
- [Firestore iOS SDK Frameworks](https://github.com/invertase/firestore-ios-sdk-frameworks) - Precompiled Firestore frameworks that cut Xcode build times.
- [Firestore Lite](https://github.com/samuelgozi/firebase-firestore-lite) - Small Firestore client for the browser built on the REST API.
- [FlutterFire](https://github.com/firebase/flutterfire) - The official Firebase plugins for Flutter.
- [Pyrebase](https://github.com/thisbejim/Pyrebase) - Python wrapper around the Firebase client REST APIs.
- [QtFirebase](https://github.com/larpon/QtFirebase) - Brings the Firebase C++ SDK to Qt and QML apps.
- [React Native Firebase](https://github.com/invertase/react-native-firebase) - Native Firebase modules for React Native on Android and iOS.

### Admin SDKs

- [Firebase Admin .NET SDK](https://github.com/firebase/firebase-admin-dotnet) - Admin SDK for C# and other .NET backends.
- [Firebase Admin Dart SDK](https://github.com/firebase/firebase-admin-dart) - Admin SDK for Dart servers and command-line tools.
- [Firebase Admin Go SDK](https://github.com/firebase/firebase-admin-go) - Admin SDK for Go backends.
- [Firebase Admin Java SDK](https://github.com/firebase/firebase-admin-java) - Admin SDK for Java and other JVM backends.
- [Firebase Admin Node.js SDK](https://github.com/firebase/firebase-admin-node) - Admin SDK for Node.js servers and Cloud Functions.
- [Firebase Admin Python SDK](https://github.com/firebase/firebase-admin-python) - Admin SDK for Python backends.
- [Firebase PHP](https://github.com/beste/firebase-php) - Unofficial Admin SDK for PHP backends.
- [Laravel Firebase](https://github.com/beste/laravel-firebase) - Laravel package that wires Firebase PHP into the framework.

## Cloud Functions

- [Cloud Functions Documentation](https://firebase.google.com/docs/functions) - Guides for writing, testing and deploying Cloud Functions for Firebase.
- [Cloud Functions Version Comparison](https://firebase.google.com/docs/functions/version-comparison) - What changes between 1st gen and 2nd gen functions, and how to upgrade.
- [Compiled Code on Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/main/functions-w-parcel) - Example that compiles TypeScript or Flow before deploying functions.
- [Express on Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/main/functions-express) - Example that serves an Express app from a single HTTPS function.
- [Firebase Functions Python SDK](https://github.com/firebase/firebase-functions-python) - SDK for writing Cloud Functions for Firebase in Python.
- [Firebase Functions SDK](https://github.com/firebase/firebase-functions) - The Node.js SDK for defining Cloud Functions triggers, including 2nd gen.
- [Firestore Queuer](https://github.com/sbarbat/firestore-queuer) - Basic job queue built on Firestore documents and function triggers.
- [Functions Samples](https://github.com/firebase/functions-samples) - Official collection of Cloud Functions examples for common tasks.
- [GraphQL Server on Cloud Functions](https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0) - Article on running a GraphQL endpoint inside an HTTPS function.
- [Integrify](https://github.com/anishkny/integrify) - Ready-made Firestore triggers that keep references and copies consistent.
- [Scheduled Functions](https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html) - Launch post for cron-style scheduled triggers in Cloud Functions.

## Databases

- [Cloud Firestore](https://firebase.google.com/docs/firestore) - Docs for the Firestore document database on web, mobile, C++ and Unity.
- [Fireleaves](https://github.com/pguyson/fireleaves) - Copies Realtime Database data into MongoDB for search and reporting.
- [Firelord](https://github.com/tylim88/Firelord) - Strongly typed TypeScript wrapper for the Firestore Admin SDK.
- [FirelordJS](https://github.com/tylim88/FirelordJS) - Strongly typed TypeScript wrapper for the Firestore web SDK.
- [FireORM](https://github.com/wovalle/fireorm) - TypeScript ORM that maps classes to Firestore collections.
- [FireSageJS](https://github.com/tylim88/FireSageJS) - Strongly typed TypeScript wrapper for the Realtime Database web SDK.
- [FireSQL](https://github.com/jsayol/FireSQL) - Runs SQL-style queries against Firestore.
- [Firestore Backup Restore](https://github.com/dalenguyen/firestore-backup-restore) - npm package that exports and imports Firestore collections as JSON.
- [Firestore Data Bundles](https://firebase.google.com/docs/firestore/bundles) - Serve prebuilt query results from a CDN to speed up first loads.
- [Firestore Enterprise Edition](https://firebase.google.com/docs/firestore/enterprise/overview-enterprise-edition-modes) - Overview of the Enterprise edition and its MongoDB-compatible mode.
- [Firestore Geoqueries](https://firebase.google.com/docs/firestore/solutions/geoqueries) - Official guide to location queries in Firestore with geohashes.
- [Fuego](https://github.com/sgarciac/fuego) - Command-line client to add, update and query Firestore documents.
- [GeoFire for JavaScript](https://github.com/firebase/geofire-js) - Location queries for Realtime Database and Firestore in JavaScript.
- [GeoFire for Objective-C](https://github.com/firebase/geofire-objc) - Location queries for Firebase on Apple platforms.
- [GeoFirestore](https://github.com/MichaelSolati/geofirestore-js) - Store documents with coordinates and query Firestore by distance.
- [SQL Connect](https://firebase.google.com/docs/sql-connect) - Docs for the Cloud SQL backed service formerly named Data Connect.
- [SQL Connect Quickstart](https://firebase.google.com/docs/sql-connect/quickstart) - Build a first schema, queries and generated SDK with SQL Connect.

## Authentication and Security

- [App Check](https://firebase.google.com/docs/app-check) - Blocks traffic that does not come from your real apps.
- [Express Firebase Middleware](https://github.com/antonybudianto/express-firebase-middleware) - Express middleware that checks Firebase ID tokens on requests.
- [Firebase Authentication](https://firebase.google.com/docs/auth) - Docs for sign-in with passwords, phone numbers and identity providers.
- [FirebaseUI for Android](https://github.com/firebase/FirebaseUI-Android) - Drop-in sign-in screens and data-bound views for Android.
- [FirebaseUI for iOS](https://github.com/firebase/FirebaseUI-iOS) - Drop-in sign-in screens and data-bound views for iOS.
- [FirebaseUI for React](https://github.com/firebase/firebaseui-web-react) - React components around the FirebaseUI web sign-in widget.
- [FirebaseUI for Web](https://github.com/firebase/firebaseui-web) - Drop-in sign-in flows for web apps.
- [Fireward](https://github.com/bijoutrouvaille/fireward) - Typed language that compiles to Firestore security rules.
- [Next Firebase Auth](https://github.com/gladly-team/next-firebase-auth) - Firebase Authentication for Next.js across server and client rendering.
- [Next Firebase Auth Edge](https://github.com/awinogrodzki/next-firebase-auth-edge) - Firebase Authentication for Next.js on Edge and Node.js runtimes.

## Hosting and App Hosting

- [App Hosting](https://firebase.google.com/docs/app-hosting) - Docs for the managed hosting service for Next.js, Angular and other SSR apps.
- [App Hosting Adapters](https://github.com/firebase/apphosting-adapters) - Build adapters that let App Hosting and the CLI run web frameworks.
- [Deploy to Firebase Hosting Action](https://github.com/FirebaseExtended/action-hosting-deploy) - GitHub Action that deploys previews and live sites to Hosting.
- [Firebase Hosting](https://firebase.google.com/docs/hosting) - Docs for static and dynamic hosting on a global CDN.
- [Hosting and Cloud Run](https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html) - Post on serving dynamic content by rewriting Hosting paths to Cloud Run.
- [Hosting Releases and Versions](https://firebase.google.com/docs/hosting/manage-hosting-resources) - Manage channels, roll back releases and cap how many versions are kept.
- [Hosting Web Frameworks](https://firebase.google.com/docs/hosting/frameworks/frameworks-overview) - Preview support for deploying framework apps straight to Hosting.
- [StackBlitz Deploys to Firebase](https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879) - Announcement of one-click Hosting deploys from the StackBlitz editor.

## AI

### Firebase AI Logic and Agent Tools

- [Firebase Agent Skills](https://github.com/firebase/agent-skills) - Skill files that teach coding agents how to work with Firebase.
- [Firebase AI Logic](https://firebase.google.com/docs/ai-logic) - Call Gemini and Imagen models from client apps through Firebase.
- [Firebase MCP Server](https://firebase.google.com/docs/ai-assistance/mcp-server) - MCP server in the Firebase CLI that lets AI tools manage projects.

### Genkit

- [Awesome Genkit](https://github.com/xavidop/awesome-genkit) - Curated list of Genkit plugins, talks, samples and articles.
- [Genkit](https://github.com/genkit-ai/genkit) - Open source framework for AI features in JavaScript, Go, Dart and Python.
- [Genkit Dart](https://github.com/genkit-ai/genkit-dart) - The Dart SDK for Genkit, for Flutter and server apps.
- [Genkit Documentation](https://genkit.dev) - Guides for flows, tools, prompts, retrieval and deployment.
- [Genkit Firebase AI Plugin](https://pub.dev/packages/genkit_firebase_ai) - Genkit Dart plugin that calls models through Firebase AI Logic.
- [Genkit Java](https://github.com/genkit-ai/genkit-java) - Unofficial Java SDK for Genkit with a Firebase plugin.
- [Genkit JavaScript API Reference](https://js.api.genkit.dev) - Generated reference for the Genkit JavaScript packages.
- [Genkit on Cloud Functions](https://genkit.dev/docs/js/deployment/firebase/) - Deploy Genkit flows as callable Cloud Functions for Firebase.
- [Internal AI](https://github.com/tanabee/internal-ai) - Self-hosted AI chat app for organizations, built on Genkit and Firebase.

## Extensions

- [Algolia Search Extension](https://github.com/algolia/firestore-algolia-search) - Syncs Firestore documents to an Algolia index for full-text search.
- [Extensions Hub](https://extensions.dev) - Catalog of published Firebase Extensions from Firebase and partners.
- [Firebase Extensions](https://firebase.google.com/docs/extensions) - Docs for packaged backend features; the service shuts down in March 2027.
- [Firebase Extensions Source](https://github.com/firebase/extensions) - Source code of the official Firebase-built extensions.
- [Mailchimp Extension](https://github.com/mailchimp/Firebase) - Syncs Firebase Authentication users and events to Mailchimp audiences.
- [MessageBird Extension](https://github.com/messagebird/firestore-send-msg) - Sends messages through MessageBird when Firestore documents are written.
- [Migrate to Function Kits](https://firebase.google.com/docs/extensions/users/migrate) - Guide for moving installed extensions to npm-distributed function kits.
- [Typesense Search Extension](https://github.com/typesense/firestore-typesense-search) - Syncs Firestore documents to Typesense, an open source search engine.

## Framework Integrations

- [AngularFire](https://github.com/angular/angularfire) - The official Angular library for Firebase.
- [Firestorter](https://github.com/IjzerenHein/firestorter) - MobX-backed Firestore bindings for React and React Native.
- [Omega](https://github.com/Omega-JS-Stack/omega) - Framework that builds a site, Firebase backend, desktop app and browser extension.
- [Re-base](https://github.com/tylermcginnis/re-base) - Syncs React component state with Firebase data.
- [React Firebase Hooks](https://github.com/CSFrequency/react-firebase-hooks) - React hooks for Auth, Firestore, Realtime Database, Storage and more.
- [React Redux Firebase](https://github.com/prescottprue/react-redux-firebase) - Redux bindings and React helpers that keep Firebase data in the store.
- [ReactFire](https://github.com/FirebaseExtended/reactfire) - Hooks and providers for using Firebase in React apps.
- [SvelteFire](https://github.com/codediodeio/sveltefire) - Svelte components and stores for Firebase.
- [VueFire](https://github.com/vuejs/vuefire) - Firebase bindings for Vue, with a Nuxt module.

## Mobile and Games

- [App Distribution](https://firebase.google.com/products/app-distribution/) - Ship pre-release Android and iOS builds to trusted testers.
- [App Distribution with App Bundles](https://firebase.googleblog.com/2021/05/app-distribution-adds-support-to-android-app-bundles.html) - Post on sending Android App Bundles to testers through App Distribution.
- [Chat SDK](https://github.com/chat-sdk) - Open source messaging framework for Android and iOS on a Firebase backend.
- [Firecoil](https://github.com/thatfiredev/firecoil) - Loads Cloud Storage images on Android with the Coil image library.
- [Flamingo](https://github.com/hukusuke1007/flamingo) - Model layer for Firestore documents in Flutter apps.
- [GeoFlutterFire](https://github.com/DarshanGowda0/GeoFlutterFire) - Location queries on Firestore for Flutter apps.

## Tools

### CLI and Emulators

- [asdf-firebase](https://github.com/jthegedus/asdf-firebase) - asdf plugin that installs and pins Firebase CLI versions without npm.
- [Emulator Suite UI](https://github.com/firebase/firebase-tools-ui) - Web interface for inspecting and editing local emulator data.
- [Firebase CLI](https://github.com/firebase/firebase-tools) - The command-line tool to deploy, manage and emulate Firebase projects.
- [Firebase Local Emulator Suite](https://firebase.google.com/docs/emulator-suite) - Run Auth, Firestore, Functions, Storage and more on your own machine.
- [Firepit](https://github.com/abeisgoat/firepit) - Standalone Firebase CLI build that runs without a Node.js install.

### Editor Extensions

- [Firebase Explorer for VS Code](https://github.com/jsayol/vscode-firebase-explorer) - Browse and manage Firebase projects from the VS Code sidebar.
- [Firebase Firestore Snippets](https://github.com/PeterHdd/firebase-firestore-snippets) - VS Code snippets for common Firebase and Firestore calls.
- [Firecode for VS Code](https://github.com/ChFlick/firecode) - Syntax highlighting and completion for Firestore security rules.

### Admin Panels and Data Tools

- [Firebase Admin](https://firebaseadmin.com) - Desktop app for Windows, macOS and Linux to manage Firebase data.
- [FireCMS](https://firecms.co/docs/) - Open source headless CMS and admin panel generated from your Firestore schema.
- [Firefoo](https://www.firefoo.com/) - Desktop Firestore client with JSON and CSV export and a query shell.
- [Firestore Query Browser](https://firestore-query-browser.firebaseapp.com) - Web app to query, batch edit and export Firestore documents.
- [Flamelink](https://flamelink.io/) - Hosted CMS that stores content in Firestore, Realtime Database and Storage.
- [Refi App](https://github.com/thanhlmm/refi-app) - Desktop GUI for browsing and editing Firestore data.
- [Rowy](https://github.com/buildship-ai/rowy) - Spreadsheet-style editor for Firestore with in-browser cloud functions.

### Testing and CI

- [Firebase CI](https://github.com/prescottprue/firebase-ci) - Helpers for deploying Firebase projects from CI pipelines.
- [Firebase Functions Test](https://github.com/firebase/firebase-functions-test) - Unit testing library for Cloud Functions for Firebase.
- [Flank](https://github.com/Flank/flank) - Parallel test runner for Test Lab, which shuts down in September 2027.
- [Security Rules Unit Tests](https://firebase.google.com/docs/rules/unit-tests) - Test Firestore, Realtime Database and Storage rules against the emulators.

## Samples and Starters

### Official Samples

- [Android Quickstarts](https://github.com/firebase/quickstart-android) - Small Android apps for each Firebase product.
- [C++ Quickstarts](https://github.com/firebase/quickstart-cpp) - Small C++ apps for each Firebase product.
- [Flutter Quickstarts](https://github.com/firebase/quickstart-flutter) - Small Flutter apps for each Firebase product.
- [FriendlyEats Web](https://github.com/firebase/friendlyeats-web) - Next.js restaurant app that is the starting point for the Firestore web codelab.
- [iOS Quickstarts](https://github.com/firebase/quickstart-ios) - Small Swift and Objective-C apps for each Firebase product.
- [JavaScript Quickstarts](https://github.com/firebase/quickstart-js) - Small web apps for each Firebase product.
- [Node.js Quickstarts](https://github.com/firebase/quickstart-nodejs) - Small Node.js scripts for Firebase server-side features.
- [Unity Quickstarts](https://github.com/firebase/quickstart-unity) - Small Unity projects for each Firebase product.
- [Web Snippets](https://github.com/firebase/snippets-web) - The code snippets shown in the Firebase web documentation.

### Community Apps

- [Angular Firestarter](https://github.com/codediodeio/angular-firestarter) - Angular progressive web app starter wired to Firebase.
- [Firebase Adventures](https://github.com/how-to-firebase/firebase-adventures) - Workshop material on building cross-platform apps with Firebase.
- [Flutter Calendar](https://github.com/mattgraham1/FlutterCalendar) - Flutter calendar app that stores events in Firebase.
- [FlutterGram](https://github.com/mdanics/fluttergram) - Instagram-style Flutter app on Firestore and Cloud Functions.
- [Fwitter](https://github.com/TheAlphamerc/flutter_twitter_clone) - Twitter-style Flutter app backed by Firebase.
- [Meme Chat](https://github.com/efortuna/memechat) - Flutter chat app with Google Sign-In, camera upload and Firebase.
- [NewsBuzz](https://github.com/theankurkedia/newsbuzz) - Flutter news reader that keeps bookmarks in Firebase.
- [React Firebase Authentication](https://github.com/okstaticzero/react-firebase-authentication) - React starter with sign-in, protected routes and Realtime Database.
- [TailorMade](https://github.com/jogboms/tailor_made) - Flutter app for running a tailoring business on Firestore and Functions.

## Guides and Articles

- [Closed Funnels with BigQuery](https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1) - Build a closed conversion funnel from Analytics data exported to BigQuery.
- [First Firebase-Powered Ionic App](https://jorgevergara.co/blog/ionic-firebase-angular/) - Long tutorial that builds an Ionic and Angular app on Firestore from scratch.
- [Flutter by Example](https://flutterbyexample.com/) - Flutter tutorials that include Firebase-backed app examples.
- [Flutter Phone Authentication](https://medium.com/@gildaswise/flutter-adding-sign-in-with-google-and-phone-authentication-to-your-app-69f681518f9b) - Add Google and SMS sign-in to a Flutter app with Firebase Auth.
- [Gemini PDF Extraction with Genkit](https://firebase.blog/posts/2025/02/gemini-genkit-pdf-structured-data) - Pull typed data out of PDFs with Gemini and Genkit.
- [Gemini Slack Bot with Firebase](https://dev.to/denisvalasek/gemini-in-your-slack-workspace-using-firebase-genkit-530c) - Run a Gemini-powered Slack bot on Firebase with Genkit.
- [Genkit Architecture Patterns](https://medium.com/@nozomi-koborinai/orchestrating-firebase-and-ai-8-genkit-architecture-patterns-12e44db40345) - Eight ways to combine Genkit flows with Firebase services.
- [Genkit Architecture Slides](https://docs.google.com/presentation/d/10F2hjzJhdInSuhDQ8G_B2raGz79mzTRIcWU_59Zh5Y8/edit?usp=sharing) - DevFest Tokyo slides with a sample Genkit and Firebase architecture.
- [Genkit Flows on Firebase](https://medium.com/@nozomi-koborinai/how-to-develop-firebase-genkit-functions-2677b386a227) - Develop and test Genkit flows locally before deploying them as functions.
- [Genkit Slack Bot in 100 Lines](https://medium.com/firebase-developers/build-a-slack-bot-app-with-firebase-genkit-in-just-100-lines-71d4e49c9e08) - Short walkthrough of a Slack bot built with Genkit on Firebase.
- [Mastering Genkit: Go Edition](https://mastering-genkit.github.io/mastering-genkit-go/) - Free online book on production AI apps with Genkit for Go.
- [Product Analytics with BigQuery and Rakam](https://rakam.io/blog/free-product-analytics-with-firebase---bigquery---rakam/) - Segment and analyze Firebase event data exported to BigQuery.
- [RAG with Genkit and Firestore](https://dev.to/denisvalasek/set-up-rag-with-genkit-and-firebase-in-15-minutes-50b2) - Use Firestore as the vector store for a Genkit retrieval pipeline.
- [State of Firebase (mid 2019)](https://codeburst.io/the-state-of-firebase-mid-2019-2b002c458d70) - Roundup of Firebase launches from Cloud Next and Google I/O 2019.
- [Ultimate Guide to Flutter](https://github.com/antz22/ultimate-guide-to-flutter) - Beginner guide to Flutter that walks through Firebase setup.

## Talks and Videos

- [#AskFirebase](https://www.youtube.com/watch?v=TSzhzR4wzSE&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA) - Playlist where the Firebase team answers community questions.
- [Firebase at Cloud Next 2018](https://www.youtube.com/watch?v=OPj26MY16F8&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL) - Playlist of the Firebase sessions from Cloud Next 2018.
- [Firebase at Google I/O 2016](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlAyGS6_paVoGJ9YKC7J3NN) - Playlist of the Firebase sessions from Google I/O 2016.
- [Firebase at Google I/O 2018](https://www.youtube.com/watch?v=e-8fiv-vteQ&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd) - Playlist of the Firebase sessions from Google I/O 2018.
- [Firebase at Google I/O 2019](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlo2L4rfPds-fFLEtOWheoO) - Playlist of the Firebase sessions from Google I/O 2019.
- [Firebase Live 2020](https://www.youtube.com/playlist?list=PLl-K7zZEsYLnw0-bXz2f9zo6745VQ_2ep) - Web series of talks and tutorials from the Firebase team.
- [Firebase Papo Reto (PT-BR)](https://www.youtube.com/watch?v=3tIpOl0lLKo) - Portuguese-language introduction to Firebase.
- [Firebase Summit 2018](https://www.youtube.com/watch?v=lN0VXVXsj9k&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R) - Playlist of every Firebase Summit 2018 session.
- [Firebase Summit 2019](https://www.youtube.com/watch?v=YKZ6rP4kwV8&list=PLl-K7zZEsYLk2OolaVXVyYrFErctrZXSX) - Playlist of every Firebase Summit 2019 session.
- [Firebase Summit 2020](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlRjj-mSComCq3Vd4IJese1) - Playlist of every Firebase Summit 2020 session.
- [Firebase YouTube](https://www.youtube.com/user/Firebase) - The official Firebase channel with tutorials, launches and event talks.
- [Firecasts](https://www.youtube.com/playlist?list=PLl-K7zZEsYLnJVX_0zbKytptZGugPIbJR) - Hands-on tutorial series for Firebase developers.
- [Fireship](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA) - Fast-paced web development videos with frequent Firebase coverage.
- [Flutter and Genkit Slides](https://speakerdeck.com/coborinai/accelerating-generative-ai-app-development-with-flutter-and-firebase-genkit) - Conference slides on building generative AI apps with Flutter and Genkit.
- [Genkit at I/O Extended Bangkok](https://www.youtube.com/watch?v=eVud8llb_W0) - Community talk on adding AI features to an app with Genkit.
- [Getting Started with Genkit 1.0](https://www.youtube.com/watch?v=3p1P5grjXIQ) - Official walkthrough of Genkit 1.0 for Node.js.
- [Introducing Firebase](https://www.youtube.com/playlist?list=PLl-K7zZEsYLmOF_07IayrTntevxtbUxDL) - Short videos that introduce each Firebase product.
- [Understanding Cloud Functions](https://www.youtube.com/watch?v=2mjfI0FYP7Y&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM) - Video series on how Cloud Functions for Firebase work.

## Community

### Channels

- [Firebase Developers Discord](https://discord.gg/BN2cgc3) - Community Discord server for Firebase questions and discussion.
- [Firebase on X](https://x.com/firebase) - Official Firebase account for launches and tips.
- [Firebase Russian Telegram](https://t.me/firebase_ru) - Russian-language Telegram chat for Firebase developers.
- [Genkit Discord](https://discord.gg/qXt5zzQKpc) - Official Discord server for Genkit users.

### People

- [Andrew Lee](https://twitter.com/startupandrew) - Firebase co-founder.
- [James Tamplin](https://twitter.com/jamestamplin) - Firebase co-founder.
- [Juarez Filho](https://twitter.com/juarezpaf) - Author of the Firebase Adventures workshop.
- [Mike McDonald](https://twitter.com/asciimike) - Former Firebase product manager.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.

<!-- awesome:maintainer -->
Maintained by [Ian Wiedenman](https://github.com/ianwieds).
<!-- /awesome:maintainer -->
