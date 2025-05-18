# NUML QEC AI Bot

**Version:** v0.0.1-beta  
**Status:** Beta Preview  
**Author:** [Ahmed Muneeb](https://ahmedmuneeb.com)

**NUML QEC AI Bot** is a Windows desktop tool that automatically fills QEC (Quality Enhancement Cell) forms for both **teachers** and **courses**. It uses **Gemini AI** to understand and complete the form fields intelligently without user input.

This is a **beta version built in one day**, with core features working but minimal infrastructure and UI.

---

## Key Features

- ✅ **AI-powered form understanding** using **Gemini AI**
- ✅ Automated browser control using **PTR with Chromium**
- ✅ Supports both teacher and course form types
- ✅ One-screen basic interface (no advanced UI)
- ❌ No error logs or in-app messages yet

---

## How It Works

1. The app launches a Chromium window automatically.
2. Gemini AI processes the QEC form and fills it out.
3. Once the process is complete, the window closes.
4. **Important Notes:**
   - **Do not interact with the window** while it's open.
   - If the window closes unexpectedly, it's likely due to:
     - NUML server errors or being down
     - Login or validation issues
     - An internal app error (currently handled by silently closing)

---

## Screenshots

> *Below are example screenshots of the current version of NUML QEC AI Bot.*

![Main App Screen](https://github.com/user-attachments/assets/061098da-c678-4645-ac79-5b0b6f0fa1d1)

> *Note: Screenshots are from v0.0.1-beta and subject to change.*

---

## Current Limitations

- Minimal error handling: any error will close the Chromium window
- No retry or error logging (coming in future versions)
- No public source code yet – this release includes only basic infrastructure

---

## Coming Soon

- Full source code with Gemini API logic
- Error logs and better validation messages
- Retry mechanism and form feedback
- User interface improvements

---

## Status

> This is a **preview beta release**, intended for testing only.  
> Full development and feature rollout will continue in future versions.

---

## License

MIT License

---

## Developed By

Ahmed Muneeb  
[ahmedmuneeb.com](https://ahmedmuneeb.com)  
[github.com/theahmedmuneeb](https://github.com/theahmedmuneeb)