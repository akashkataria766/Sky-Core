# ✦ Sky Sense

> **Think. Learn. Understand. Decide.**
>
> A personal AI experience built around **SKY** — a conversational companion designed to understand context, challenge ideas, and help you think more clearly.

[![Status](https://img.shields.io/badge/status-public%20testing-blue)]()
[![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Android-green)]()
[![PWA](https://img.shields.io/badge/PWA-supported-purple)]()
[![Built With](https://img.shields.io/badge/built%20with-React%20%2B%20TypeScript-61DAFB)]()

---

## 🚀 LATEST UPDATE — PUBLIC TESTING

> ### 🆕 Sky Sense is actively evolving.
>
> The latest Android builds are now being tested on a **real Android device** with USB/ADB validation.
>
> **Latest APK build:** `21 September 2026 — ~01:07 IST`
>
> **Latest README update:** `21 September 2026`
>
> **Release:** Android User + Android Admin
>
> **Status:** 🟡 **Public Testing / Active Development**

### ⚡ What's New

The latest development cycle focused heavily on reliability, Android integration, messaging and notifications.

* ✅ Logout reliability improved
* ✅ Native Android FCM registration fixed
* ✅ Push notification delivery verified on real device
* ✅ Notifications now identify the sender/action instead of using only generic messages
* ✅ Notification tap now opens the relevant Sky Sense conversation
* ✅ VIP notification routing improved
* ✅ Admin → User notification experience improved
* ✅ User → Admin notification experience improved
* ✅ SKY reply notification flow added
* ✅ Guest Support ticket persistence fixed
* ✅ Guest Support history survives app restart/process termination
* ✅ Support notification flow improved
* ✅ Android background notification behavior improved
* 🔐 Firestore security rules updated without opening Support data publicly
* 📱 Android builds tested directly on a real iQOO Neo 6

### 🔔 Smarter Notifications

Notifications are moving beyond generic messages such as:

> `New VIP Message`

toward context-aware notifications such as:

> **Rahul sent a message**
> *Hey, are you available?*

or:

> **Admin sent a message**
> *Your request has been updated.*

and:

> **SKY replied**
> *Here's what I think about that...*

The goal is simple:

> **You should know what happened before opening the app.**

### 📲 Notification Interaction

Notification interaction has also been improved.

**Notification → Tap → Sky Sense → Relevant conversation**

The system now handles notification navigation for messaging flows instead of simply opening the application without context.

---

## 🧪 Current Testing Status

Sky Sense is currently in **public testing**.

### ✅ Recently Verified

| Area                          | Status     |
| ----------------------------- | ---------- |
| User/Admin Logout             | 🟢 Working |
| Native FCM registration       | 🟢 Working |
| Push notifications            | 🟢 Working |
| Closed-app notifications      | 🟢 Tested  |
| Notification tap routing      | 🟢 Working |
| Guest Support persistence     | 🟢 Working |
| Support conversation recovery | 🟢 Working |
| VIP messaging                 | 🟢 Working |
| SKY conversations             | 🟢 Working |
| Firebase authentication       | 🟢 Working |

### 🟡 Still Being Polished

* VIP Chat visual experience
* In-app password management UI
* Additional Android UX refinements
* General reliability and edge-case testing

Features in this section are **under active development and verification**.

---

## 🌌 What is Sky Sense?

Most AI tools are built around one interaction:

**Ask → Answer → Done.**

Sky Sense explores something different.

**Talk → Remember → Understand → Think → Act.**

Sky Sense is a personal AI platform centered around **SKY**, a dedicated personality designed for natural, contextual conversations rather than functioning like a generic question-answering chatbot.

SKY can help you explore ideas, understand difficult topics, organize your thoughts, track goals, discuss decisions, and continue conversations with context.

The goal is simple:

> **Make AI feel useful beyond the chat box.**

---

## 🤖 Meet SKY

**SKY is the personality you would actually want to keep chatting with.**

SKY is designed to be:

* Practical
* Direct
* Curious
* Analytical
* Patient
* Honest
* Strategic
* Occasionally sarcastic
* Comfortable challenging weak ideas
* Able to adapt to the context of a conversation

SKY doesn't have to agree with you.

If an idea doesn't make sense, SKY can explain why.

If you're missing information, SKY can say so.

If a conversation needs depth, SKY can go deeper.

And when a simple answer is enough, SKY doesn't need to turn it into an essay.

### The idea behind SKY

> **Don't just give me an answer. Help me understand why.**

---

## ✨ What You Can Do

Sky Sense combines conversation with practical personal tools.

### 💬 Talk with SKY

Have contextual conversations with SKY and continue discussions without treating every message as an isolated question.

### 🧠 Conversation Context

Sky Sense is designed to preserve relevant conversational context so that follow-up questions feel like part of the same conversation.

### 📝 Quick Notes

Capture thoughts, ideas, reminders, or information you don't want to lose.

### 🎯 Goal Tracker

Create and manage personal goals while keeping them accessible alongside your AI experience.

### 📰 What's New

Stay updated with announcements and platform updates.

### 💭 Opinion Box

Share feedback, opinions, and ideas that can help shape the platform.

### 🆘 Support

Support is available for both authenticated users and guests.

Guest support conversations can be recovered after leaving or restarting the application, allowing users to continue an existing support conversation.

### ⭐ VIP Experience

Sky Sense includes a controlled VIP membership system with additional interaction capabilities.

VIP access is handled through an approval and access-code system rather than a conventional paid subscription.

### 🔔 Intelligent Notifications

Sky Sense can notify you about:

* VIP messages
* Admin messages
* Support replies
* Support requests
* SKY responses
* Important account events

Notifications are designed to provide useful context rather than simply saying "New Message."

---

## 🧩 Built Around a Bigger Idea

Sky Sense isn't intended to be only another chatbot.

The platform is designed around several connected experiences:

```text
                    ┌──────────────┐
                    │     SKY      │
                    │ Personal AI  │
                    └──────┬───────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
       THINK            LEARN           UNDERSTAND
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                      TAKE ACTION
```

---

## 🛠️ Technology

* React
* TypeScript
* Vite
* Firebase Authentication
* Cloud Firestore
* Firebase Cloud Messaging
* Capacitor
* Cloudflare Workers
* Cloudflare D1
* Cloudflare Workers AI
* GLM-4.7-Flash
* PWA support

---

## 🔐 Security & Privacy

Security is treated as a core part of the platform.

The application uses:

* Firebase Authentication
* Firestore security rules
* Role-based Admin access
* Approved-account controls
* VIP access-code validation
* Server-side AI request handling
* Cloudflare Worker API protection
* Controlled persona knowledge
* Protected Admin functionality
* Secure guest-support access
* Controlled notification permissions

Support functionality is **not made publicly readable** simply to make guest support easier.

---

## 📱 Platforms

### Web

Sky Sense is available as a web application and supports PWA installation.

### Android

Separate Android applications are available for:

* **Sky Sense** — User application
* **Sky Sense Admin** — Administrative application

The Android applications are currently in public testing.

---

## 🧪 Real-Device Testing

A major part of the current development process is testing the Android applications on a physical device rather than relying only on successful builds.

Current test device:

```text
Device: iQOO Neo 6
Resolution: 1080 × 2400
Platform: Android
Testing: USB / ADB
```

This helps validate:

* Firebase Authentication
* FCM registration
* Background notifications
* Closed-app notifications
* Notification tap routing
* Capacitor behavior
* Persistent guest storage
* Keyboard behavior
* Android-specific UI behavior

---

## 💬 Feedback

Found something broken?

Have an idea?

Think SKY could respond better?

Report it through the available Support and Feedback channels.

Useful reports include:

```text
Device:
Android version:
App version/build:
Feature:
What I expected:
What happened:
Steps to reproduce:
Screenshot/log:
```

### 🧪 What We're Especially Interested In

Try unusual flows.

For example:

> Close the app → receive notification → tap notification → check destination.

Or:

> Create guest support ticket → kill app → reopen → recover ticket.

Real-world testing helps identify problems that normal development builds can miss.

---

## 🗺️ Development Direction

Sky Sense is being developed around a simple principle:

> **The goal isn't to make another AI chatbot.**
>
> **The goal is to build a useful personal AI experience around SKY.**

Current development is focused on:

* Better contextual memory
* More useful personal workflows
* Improved SKY reasoning
* Smarter notifications
* Better messaging experiences
* More reliable Support
* Stronger Android experience
* Better account security
* Stability and edge-case handling
* Real-world user feedback

---

## 📌 Current Release

**Status:** 🟡 Public Testing

**Latest APK build:** `20 September 2026 — ~22:24 IST`

**README updated:** `21 September 2026`

**Current focus:**

> **Polish → Test → Improve → Repeat**

The core platform is functional and being actively tested on real devices.

---

## 🌱 Open Development

Sky Sense is being built step by step.

The project is intended to provide an opportunity to experiment with:

* AI application development
* Android application development
* Firebase architecture
* Cloudflare Workers
* Real-time messaging
* Push notifications
* Authentication
* Secure application design
* Product UI/UX
* Collaborative development

If you're interested in contributing, testing, experimenting, or simply exploring the project, feedback is welcome.

---

## ❤️ Built to Be Used

Sky Sense is not being built only to demonstrate an AI API.

It's being built as a real product experience — tested, broken, fixed, refined, and tested again.

> **Think. Learn. Understand. Decide.**
>
> **Welcome to Sky Sense.**
