# Privacy Policy – Sprechen B2 Trainer

**Last updated:** 2026-03-15

## Overview
Sprechen B2 Trainer is an Android application designed to help users prepare for the B2 German speaking exam. The app uses the OpenAI API to generate exam scenarios and evaluate spoken responses.

## Audio Recording
The app requests the `RECORD_AUDIO` permission solely to capture your spoken responses during practice sessions. Audio is:
- Streamed in real-time to the OpenAI Realtime API via WebSocket for live transcription and evaluation
- **Not stored** on any server or on the device
- **Not shared** with any third party other than OpenAI for processing
- Processed in real-time and **never persisted** after the session ends

## Data Collection
This app does **not** collect, store, or share any personal data. Specifically:
- No user accounts are required
- No analytics or tracking tools are used
- No cookies are used
- No personal information is transmitted to the developer

## Third-Party Services
The app communicates with the **OpenAI API** for:
1. Generating exam scenarios (GPT)
2. Real-time audio streaming, transcription, and conversation (OpenAI Realtime API)
3. Evaluating responses (GPT)

OpenAI's privacy policy: [https://openai.com/privacy](https://openai.com/privacy)

## Data Storage
The only data stored locally on your device:
- Generated exam scenario history (stored in SharedPreferences to avoid repetition)
- Your OpenAI API key (stored locally, never transmitted anywhere except to OpenAI)

## Children's Privacy
This app is not intended for children under 13.

## Contact
If you have questions about this privacy policy, contact:
**GitHub:** [dmazurek00](https://github.com/dmazurek00)

## Changes
Any changes to this policy will be reflected on this page with an updated date.

