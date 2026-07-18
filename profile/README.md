<p align="center"><img src="https://raw.githubusercontent.com/geoseal/.github/main/brand/geoseal-mark.svg" width="180" alt="Geoseal — the seal balancing the pin"></p>

<h1 align="center">Geoseal</h1>

<p align="center"><b>Verified presence as an API.</b></p>

<p align="center">
  <a href="https://www.npmjs.com/package/@geoseal/capacitor"><img src="https://img.shields.io/npm/v/%40geoseal%2Fcapacitor?label=%40geoseal%2Fcapacitor&color=17C99A" alt="npm"></a>
  <a href="https://www.npmjs.com/package/@geoseal/react-native"><img src="https://img.shields.io/npm/v/%40geoseal%2Freact-native?label=%40geoseal%2Freact-native&color=17C99A" alt="npm"></a>
  <a href="https://www.npmjs.com/package/@geoseal/expo"><img src="https://img.shields.io/npm/v/%40geoseal%2Fexpo?label=%40geoseal%2Fexpo&color=17C99A" alt="npm"></a>
  <a href="https://github.com/geoseal/sdks/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-0A0F1A" alt="Apache-2.0"></a>
</p>

Geoseal confirms that a person or asset actually **arrived at — and left — a physical place**. Device location fixes are treated as untrusted input; the server-side double-geofence engine confirms enter/exit by M-of-N sample agreement rather than trusting a single GPS ping. Confirmed facts arrive as HMAC-SHA-256-signed webhooks, payroll-grade visit records, and an embeddable live view.

**MCP-native**: AI assistants query places, subjects, live presence, visits, and events over a live [MCP server](https://geoseal.dev/docs/mcp) — reads open, writes confirm-gated.

```bash
claude mcp add --transport http geoseal-docs \
  https://ibnwfzwekqyfozquwpff.supabase.co/functions/v1/mcp-docs   # public docs server, no key needed
```

## SDKs

| Package | Platform | Install |
|---|---|---|
| [`@geoseal/capacitor`](https://www.npmjs.com/package/@geoseal/capacitor) | Capacitor (iOS + Android) — reference SDK | `npm i @geoseal/capacitor` |
| [`@geoseal/react-native`](https://www.npmjs.com/package/@geoseal/react-native) | React Native | `npm i @geoseal/react-native` |
| [`@geoseal/expo`](https://www.npmjs.com/package/@geoseal/expo) | Expo (config plugin) | `npx expo install @geoseal/expo` |
| [`@geoseal/cordova`](https://www.npmjs.com/package/@geoseal/cordova) | Cordova | `cordova plugin add @geoseal/cordova` |
| [`@geoseal/nativescript`](https://www.npmjs.com/package/@geoseal/nativescript) | NativeScript | `npm i @geoseal/nativescript` |
| [`@geoseal/react-views`](https://www.npmjs.com/package/@geoseal/react-views) | React — embeddable live shift view | `npm i @geoseal/react-views` |
| `GeosealCore` | iOS native engine (CocoaPods) | `pod 'CheckpointCore'` — the trunk still serves the legacy name until the next native release ships `GeosealCore` |
| `geoseal_flutter` · `GeoSeal.Maui` · `dev.geoseal:geoseal-kmp` | Flutter · .NET MAUI · Kotlin Multiplatform | built + verified, registry publishes pending |

SDK source: [geoseal/sdks](https://github.com/geoseal/sdks) · every wrapper is a thin port of one small device contract — the detection brain runs server-side.

## Links

- Site: [geoseal.dev](https://geoseal.dev)
- Docs: [geoseal.dev/docs](https://geoseal.dev/docs) · [Quickstart](https://geoseal.dev/docs/quickstart)
- Pricing: [geoseal.dev/pricing](https://geoseal.dev/pricing) — free during beta
- For AI assistants: [llms.txt](https://geoseal.dev/llms.txt) · [OpenAPI 3.1](https://geoseal.dev/openapi.json) · [MCP manifest](https://geoseal.dev/server.json)

---

<p align="center"><sub>The mark: a harbor seal balancing a map pin — location, verified with a wink. 🦭📍</sub></p>
