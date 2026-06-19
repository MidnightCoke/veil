# Veil — Privacy Policy

**Last updated: June 19, 2026**

Veil ("the extension") is a browser extension that visually blurs your AI chat
history on ChatGPT, Claude, and Gemini. This policy explains exactly what it does
and does not do with your information.

## The short version

**Veil collects no data.** It has no servers, no accounts, and no analytics. It does
not track you and transmits nothing. Everything happens locally, in your browser.

## What Veil stores

Veil saves your **preferences** locally using the browser's storage
(`chrome.storage.local`):

- blur on/off state
- blur strength
- the "show pinned chats" option
- language
- theme

This information stays on your device and is never sent anywhere. Uninstalling the
extension removes it.

## What Veil accesses

- Veil runs **only** on the supported AI chat sites — `chatgpt.com`,
  `chat.openai.com`, `claude.ai`, and `gemini.google.com` — to apply the visual blur
  to the page you are viewing.
- It does **not** read, store, or transmit the content of your conversations. The
  blur is a purely visual CSS effect applied locally.

### Permissions

| Permission | Why |
| --- | --- |
| `storage` | Save your settings (above) locally on your device. |
| `activeTab` | Apply or update the blur on the AI chat page in your current tab when you toggle Veil. |

Veil requests no broad host permissions beyond the content scripts needed to render
the blur on the supported sites.

## Data sharing and selling

Veil does **not** sell or transfer user data to third parties. It does not use or
transfer data for advertising, for determining creditworthiness, for lending, or for
any purpose unrelated to its single purpose (visually blurring your AI chat history).

## Remote code

Veil contains **no remote code**. All code ships inside the extension package; nothing
is loaded or executed from external sources.

## Children

Veil collects no data from anyone, including children.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised.

## Contact

Questions about privacy? [Open an issue](https://github.com/MidnightCoke/veil/issues).
