---
layout: page
title: Privacy policy
permalink: /privacy/
---

**Effective 15 November 2026**

Notae is built so that your words stay yours. The developer runs no servers and collects no data. This policy explains what Notae does with your audio, your text and your settings.

## Your audio

- Notae listens only while you are recording: between your taps in the app, or between your taps on the Notae Keyboard's dictation button during a keyboard session.
- Audio is kept in memory while it is transcribed and is never written to storage.
- By default, transcription runs on your device with Apple's speech recognition.
- If you choose **ElevenLabs Scribe** or **OpenAI** under Settings › Transcription and add your own key for that service, the audio of each recording is sent directly from your device to that provider when you stop, together with your custom vocabulary and a list of common work terms to help it spell them right. Notae doesn't keep the audio.

## Your text

- By default, Notae writes text and prompts on your device with Apple Intelligence, where available, or produces a clean transcript with no AI model.
- If you add your own Anthropic (Claude) or OpenAI key, Notae can send the transcript of a dictation, the instructions for the mode you chose, and your custom vocabulary and snippets, directly from your device to that provider. Audio is never sent for this.
- Before the first request to a provider, Notae shows what will be sent and asks for your permission. You can turn cloud providers off in Settings at any time.
- What you send to a provider is covered by your agreement with that provider: see the [Anthropic privacy policy](https://www.anthropic.com/legal/privacy), the [OpenAI privacy policy](https://openai.com/policies/privacy-policy) and the [ElevenLabs privacy policy](https://elevenlabs.io/privacy-policy). Notae asks OpenAI not to store responses.
- API keys are stored in your device's Keychain and are only sent to the provider they belong to.

## The Notae Keyboard

- The keyboard never logs, stores or sends what you type.
- It needs **Full Access** only to talk to the Notae app on the same device: to start and stop a dictation and to receive the finished text. Without Full Access, typing still works.
- When you use voice editing on selected text, the keyboard passes that selection to the Notae app on your device so the edit can be applied. It goes to a cloud provider only if you have chosen one, as described above.
- The keyboard has no network access of its own and contains no AI models.

## History and settings

- Your dictations (transcript, result, mode, engine and duration) are saved on your device in the Notae app, so you can find them again.
- You choose how long they are kept (forever, 30 days or 7 days), can delete any of them, and can export them as a text file.
- Settings, vocabulary and snippets are stored on your device.
- An on-device timing log (how long each step took, never any text) helps diagnose slowness. It never leaves your device.

## What Notae does not do

- No accounts, no sign-in.
- No analytics, advertising or tracking SDKs, and no tracking across apps or websites.
- No selling or sharing of data. The developer receives none.
- If you choose to share analytics with app developers in iOS Settings, Apple may provide crash and performance reports through MetricKit. Notae shows these on the device only and does not send them anywhere.

## Children

Notae is not directed at children under 13 and collects no personal information from anyone.

## Changes

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions or requests: [open an issue](https://github.com/mathivetharaj/notae-site/issues/new).
