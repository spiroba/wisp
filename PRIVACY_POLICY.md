# Privacy Policy — Wisp

**Last updated: March 29, 2026**

## Introduction

Wisp ("we", "our", "the app") is a meeting AI assistant developed by Boris Spiro. This Privacy Policy explains how we collect, use, and protect your information when you use Wisp.

## Data Collection

### Audio Recordings
- Audio is recorded and stored **locally on your device** only.
- We do **not** upload, access, or store your audio recordings on any server.
- Audio files remain in the app's sandboxed storage and are deleted when you remove a meeting.

### Speech Recognition
- Wisp uses **Apple Speech Recognition** to transcribe audio.
- When on-device recognition is available, transcription happens **entirely on your device** with no data sent externally.
- When on-device recognition is unavailable, Apple may process audio on their servers per [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

### AI-Generated Notes
- Transcription text is sent to the AI provider **you choose** (OpenAI, Anthropic, xAI, or DeepSeek) to generate meeting notes.
- This happens **only when you have entered your own API key** and initiated a recording or import.
- We do not act as an intermediary — your device communicates directly with the AI provider's API.
- We do not store, access, or process your transcriptions on our servers.

### API Keys
- API keys you enter are stored in **Apple Keychain** on your device.
- Keys are never transmitted to us or any third party other than the AI provider you selected.
- Keys are protected with `kSecAttrAccessibleWhenUnlockedThisDeviceOnly`.

### Subscription Data
- Subscription purchases are processed by **Apple** through the App Store.
- We use StoreKit 2 to verify your subscription status locally.
- We do not collect payment information.

### Analytics & Tracking
- Wisp does **not** include any analytics SDKs, advertising trackers, or third-party tracking tools.
- We do **not** collect device identifiers, usage data, or behavioral analytics.
- We do **not** use App Tracking Transparency because we do not track users.

## Data Storage

All data is stored locally on your device:
- Meeting recordings (audio files)
- Transcriptions
- AI-generated notes
- Chat messages
- App settings and preferences

**We have no servers. We cannot access your data.**

## Data Sharing

We do not share your data with anyone. The only external communication occurs when:
1. **You** send a transcription to an AI provider (OpenAI, Anthropic, xAI, or DeepSeek) using **your own API key**.
2. **Apple** processes subscription purchases through the App Store.

## Data Deletion

- You can delete any meeting (including its audio, transcription, notes, and chat history) at any time from within the app.
- Uninstalling the app removes all data permanently.
- Auto-delete settings allow automatic removal of old meetings after 30, 60, or 90 days.

## Children's Privacy

Wisp is not directed at children under 13. We do not knowingly collect personal information from children.

## Third-Party Services

Wisp communicates with third-party AI providers only at your explicit request:

| Provider | Privacy Policy |
|----------|---------------|
| OpenAI | https://openai.com/privacy |
| Anthropic | https://www.anthropic.com/privacy |
| xAI | https://x.ai/legal/privacy-policy |
| DeepSeek | https://www.deepseek.com/privacy |

Please review the respective privacy policies of the provider you choose to use.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

If you have questions about this Privacy Policy:

- GitHub: https://github.com/spiroba/Wisp/issues
- Email: spiroboris91@icloud.com
