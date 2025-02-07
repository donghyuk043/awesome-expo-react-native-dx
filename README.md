# Awesome Expo + React Native DX [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://github.com/eyupk3/awesome-expo-react-native-dx/actions/workflows/ci.yml/badge.svg)](https://github.com/eyupk3/awesome-expo-react-native-dx/actions/workflows/ci.yml)

Curated, actively maintained resources for building high-quality Expo and React Native applications.

This repository prioritizes clear grouping, practical DX value, and verified links.

## Category Overview

| Category | Active resources |
| --- | ---: |
| [Docs & Upgrade Guides](#docs--upgrade-guides) | 8 |
| [Starter Kits & Templates](#starter-kits--templates) | 9 |
| [Navigation](#navigation) | 4 |
| [State & Data](#state--data) | 12 |
| [Backend & Auth](#backend--auth) | 8 |
| [UI & Styling](#ui--styling) | 14 |
| [Animation & Gestures](#animation--gestures) | 6 |
| [UX Libraries](#ux-libraries) | 8 |
| [Forms & Validation](#forms--validation) | 7 |
| [Media & Camera](#media--camera) | 6 |
| [Device APIs](#device-apis) | 9 |
| [Accessibility & i18n](#accessibility--i18n) | 4 |
| [Push Notifications](#push-notifications) | 4 |
| [Analytics & Monitoring](#analytics--monitoring) | 7 |
| [Monetization](#monetization) | 4 |
| [MCP Integrations](#mcp-integrations) | 4 |
| [Platform & Native Architecture](#platform--native-architecture) | 8 |
| [Build & Release](#build--release) | 5 |
| [Testing & Quality](#testing--quality) | 6 |
| [Performance & Profiling](#performance--profiling) | 6 |
| [Learning & Community](#learning--community) | 16 |

## Classification

Badges use `source_kind` from the data file directly:

- `source: official` — maintainer-authored docs and repos
- `source: community` — public OSS and community resources
- `source: commercial` — vendor services and docs

## Contribution Rules

- Explain why the resource is valuable for Expo/React Native DX.
- Keep description to 140 characters or less.
- Do not submit duplicate domain + same product entries.
- `last_verified` cannot be in the future.

Generated from `data/resources.yaml` via `npm run build:readme`.

## Docs & Upgrade Guides

### Expo Docs (5)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [EAS Documentation](https://docs.expo.dev/eas/) | Official guides for build, submit, update, metadata, and automation with EAS. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `eas` `ci-cd` `official` |
| [Expo Docs](https://docs.expo.dev/) | Official Expo documentation portal covering setup, APIs, guides, and deployment. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `official` `docs` `expo` |
| [Expo Local-First Guide](https://docs.expo.dev/guides/local-first/) | Guide for local-first app patterns in Expo, including offline data and sync strategy basics. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-09 · Tags: `local-first` `offline` `expo` |
| [Expo SDK 55 Changelog](https://expo.dev/changelog/sdk-55) | Release notes for SDK 55 with upgrade guidance and major platform changes. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `release` `upgrade` `sdk-55` |
| [Expo SDK Upgrade Walkthrough](https://docs.expo.dev/workflow/upgrading-expo-sdk-walkthrough/) | Step-by-step process to safely upgrade Expo SDK versions in existing apps. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `upgrade` `guide` `expo` |

### React Native Docs (1)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [React Native Docs](https://reactnative.dev/docs/getting-started) | Official React Native documentation for setup, core APIs, and architecture. | ![platform: react-native](https://img.shields.io/static/v1?label=platform&message=react-native&color=6366f1) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `official` `docs` `react-native` |

### Upgrade Tools (2)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [Expo Doctor Docs](https://docs.expo.dev/develop/tools/#expo-doctor) | Official Expo Doctor checks for dependency, config, and SDK compatibility issues. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `expo` `doctor` `tooling` |
| [React Native Upgrade Helper](https://react-native-community.github.io/upgrade-helper/) | Compare diffs between RN versions to perform safer upgrades with fewer regressions. | ![platform: react-native](https://img.shields.io/static/v1?label=platform&message=react-native&color=6366f1) ![type: tool](https://img.shields.io/static/v1?label=type&message=tool&color=0ea5e9) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `upgrade` `tooling` `react-native` |


## Starter Kits & Templates

### Official Starters (2)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [Create Expo App Guide](https://docs.expo.dev/more/create-expo/) | Official guide for bootstrapping Expo projects with templates and flags. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `starter` `template` `official` |
| [Expo Tabs Template](https://github.com/expo/expo/tree/main/templates/expo-template-tabs)<br>![GitHub stars](https://img.shields.io/github/stars/expo/expo?style=flat&logo=github&label=stars) | Expo starter template featuring tab navigation and common app shell patterns. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: template](https://img.shields.io/static/v1?label=type&message=template&color=16a34a) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `template` `tabs` `expo` |

### CLIs & Generators (3)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [Create Better T Stack](https://github.com/AmanVarshney01/create-better-t-stack)<br>![GitHub stars](https://img.shields.io/github/stars/amanvarshney01/create-better-t-stack?style=flat&logo=github&label=stars) | CLI for scaffolding type-safe TypeScript stacks with optional React Native frontend and backend choices. | ![platform: react-native](https://img.shields.io/static/v1?label=platform&message=react-native&color=6366f1) ![type: tool](https://img.shields.io/static/v1?label=type&message=tool&color=0ea5e9) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-07 · License: MIT · Tags: `starter` `cli` `typescript` `react-native` |
| [Create Expo Stack](https://github.com/roninoss/create-expo-stack)<br>![GitHub stars](https://img.shields.io/github/stars/roninoss/create-expo-stack?style=flat&logo=github&label=stars) | CLI to bootstrap Expo apps with routing, styling, and backend stack options. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: tool](https://img.shields.io/static/v1?label=type&message=tool&color=0ea5e9) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `starter` `cli` `expo` |
| [Ignite CLI](https://github.com/infinitered/ignite)<br>![GitHub stars](https://img.shields.io/github/stars/infinitered/ignite?style=flat&logo=github&label=stars) | Battle-tested React Native boilerplate generator focused on scalable app setup. | ![platform: react-native](https://img.shields.io/static/v1?label=platform&message=react-native&color=6366f1) ![type: tool](https://img.shields.io/static/v1?label=type&message=tool&color=0ea5e9) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `boilerplate` `cli` `react-native` |

### Community Templates (4)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [Create T3 Turbo](https://github.com/t3-oss/create-t3-turbo)<br>![GitHub stars](https://img.shields.io/github/stars/t3-oss/create-t3-turbo?style=flat&logo=github&label=stars) | Monorepo starter including Expo app and shared packages for full-stack setups. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: repo](https://img.shields.io/static/v1?label=type&message=repo&color=ea580c) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `monorepo` `starter` `turbo` |
| [Crispy (Expo Router Components)](https://github.com/EvanBacon/crispy)<br>![GitHub stars](https://img.shields.io/github/stars/evanbacon/crispy?style=flat&logo=github&label=stars) | Reusable Expo Router-first component set that accelerates new app shell development. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: repo](https://img.shields.io/static/v1?label=type&message=repo&color=ea580c) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `expo-router` `components` `starter` |
| [Expo Supabase Starter](https://github.com/flemingvincent/expo-supabase-starter)<br>![GitHub stars](https://img.shields.io/github/stars/flemingvincent/expo-supabase-starter?style=flat&logo=github&label=stars) | Expo + Supabase starter with auth and production-ready mobile architecture patterns. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: template](https://img.shields.io/static/v1?label=type&message=template&color=16a34a) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `starter` `supabase` `expo` |
| [React Native Template Obytes](https://github.com/obytes/react-native-template-obytes)<br>![GitHub stars](https://img.shields.io/github/stars/obytes/react-native-template-obytes?style=flat&logo=github&label=stars) | Production-grade Expo template with TypeScript, EAS, router, and quality tooling baked in. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: template](https://img.shields.io/static/v1?label=type&message=template&color=16a34a) ![source: community](https://img.shields.io/static/v1?label=source&message=community&color=0284c7) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · License: MIT · Tags: `template` `expo` `production` |


## Navigation

### React Navigation (3)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [React Navigation Deep Linking](https://reactnavigation.org/docs/configuring-links) | Configure deep links and universal links across iOS, Android, and web routes. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `deep-linking` `routing` `navigation` |
| [React Navigation Docs](https://reactnavigation.org/docs/getting-started) | Standard navigation solution for React Native with stack, tabs, and deep linking. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `navigation` `routing` `docs` |
| [React Navigation Native Stack](https://reactnavigation.org/docs/native-stack-navigator) | Native stack navigator docs for better performance and platform-native transitions. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `navigation` `native-stack` `performance` |

### Expo Router (1)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [Expo Linking Overview](https://docs.expo.dev/linking/overview/) | Deep linking and URL handling for Expo apps across mobile and web targets. | ![platform: expo](https://img.shields.io/static/v1?label=platform&message=expo&color=3b82f6) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `linking` `deep-linking` `expo` |


## State & Data

### Server State & Caching (2)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [TanStack Query for React Native](https://tanstack.com/query/latest/docs/framework/react/react-native) | Official guidance for using TanStack Query in React Native and Expo apps. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `data-fetching` `caching` `tanstack` |
| [TanStack Query Persist Client](https://tanstack.com/query/latest/docs/framework/react/plugins/persistQueryClient) | Persist query cache to storage for offline and fast startup experiences. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `offline` `cache` `tanstack` |

### Client State (3)

| Resource | Why it helps | Signals |
| --- | --- | --- |
| [Jotai Docs](https://github.com/pmndrs/jotai)<br>![GitHub stars](https://img.shields.io/github/stars/pmndrs/jotai?style=flat&logo=github&label=stars) | Atomic state model that scales from simple screens to complex app state graphs. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `state-management` `jotai` `atoms` |
| [Redux Toolkit Quick Start](https://github.com/reduxjs/redux-toolkit)<br>![GitHub stars](https://img.shields.io/github/stars/reduxjs/redux-toolkit?style=flat&logo=github&label=stars) | Modern Redux defaults with safer patterns and reduced setup complexity. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 2026-03-04 · Tags: `redux` `state-management` `rtk` |
| [Zustand Docs](https://github.com/pmndrs/zustand)<br>![GitHub stars](https://img.shields.io/github/stars/pmndrs/zustand?style=flat&logo=github&label=stars) | Lightweight state management with minimal boilerplate and good RN ergonomics. | ![platform: both](https://img.shields.io/static/v1?label=platform&message=both&color=0ea5e9) ![type: article](https://img.shields.io/static/v1?label=type&message=article&color=64748b) ![source: official](https://img.shields.io/static/v1?label=source&message=official&color=16a34a) ![maintained: yes](https://img.shields.io/static/v1?label=maintained&message=yes&color=16a34a)<br>Verified: 202