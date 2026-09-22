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

> ### 🆕 A major UI & Android experience update is now available.
>
> **Latest update:** `22 September 2026`
>
> **Release:** Android User + Android Admin
>
> **Status:** 🟡 **Public Testing / Active Development**
>
> Today's update focused on making Sky Sense feel more like a polished real-world messaging application while improving Android usability and account security.

### ⚡ What's New

#### 💬 Modern VIP Chat

* ✅ Instagram/WhatsApp-inspired chat layout
* ✅ Unified chat header
* ✅ Removed unnecessary extra banner/header
* ✅ Refresh button moved to the top-right
* ✅ Permanent SKY/Admin circular avatars
* ✅ Cleaner message grouping and presentation
* ✅ Removed distracting blue focus outlines
* ✅ Enter now creates a new line instead of immediately sending
* ✅ Keyboard no longer automatically opens when a reply arrives
* ✅ Improved Android back-swipe navigation

#### 📨 Message Interaction

Messages now support richer interaction:

* ⭐ **Star** messages
* ✏️ **Edit** messages
* 🗑️ **Delete** messages
* Edited messages display an **Edited** indicator
* Deleted messages display:

> 🚫 This message was deleted

Long-press a message to access the available actions.

#### ℹ️ Chat Information

Both **SKY Chat** and **VIP Chat** now include an **Info (i)** panel.

It provides information such as:

* Chat identity
* Build information
* Chat-related controls
* Reset Chat action

#### 🤖 SKY Reliability

* ✅ Fixed the SKY Chat infinite-loading issue
* ✅ Restored the AI streaming connection
* ✅ Improved the experience when SKY is generating a response

#### 🔐 Account Security

Security & Privacy now includes:

* ✅ **Change Password**
* Existing password-reset/recovery flow
* Firebase Authentication-based password handling

Password changes are performed through the authenticated account system rather than storing passwords inside the application.

#### 📱 Android Improvements

* ✅ Updated Android launcher icons
* ✅ Improved Android back navigation
* ✅ Improved chat keyboard behavior
* ✅ Improved mobile chat layout
* ✅ Continued real-device testing on iQOO Neo 6

---

## 🔔 Intelligent Notifications

Sky Sense notifications are designed to tell you **what happened and who caused it** rather than displaying generic messages.

Examples:

> **Rahul sent a message**
> *Hey, are you available?*

> **Admin sent a message**
> *Your request has been updated.*

> **SKY replied**
> *Here's what I think about that...*

Notifications can cover:

* VIP messages
* Admin messages
* Support messages
* Support replies
* SKY responses
* Important account events

### 📲 Notification Interaction

```text
Message
   ↓
Notification
   ↓
Tap
   ↓
Sky Sense
   ↓
Relevant Conversation
```

Notification taps are designed to open the relevant conversation instead of simply dropping the user at the application home screen.

---

## 🧪 Current Testing Status

Sky Sense remains in **public testing**.

### ✅ Verified

| Area                          | Status     |
| ----------------------------- | ---------- |
| User/Admin Logout             | 🟢 Working |
| Native FCM                    | 🟢 Working |
| Push Notifications            | 🟢 Working |
| Closed-App Notifications      | 🟢 Working |
| Notification Tap Routing      | 🟢 Working |
| Guest Support Persistence     | 🟢 Working |
| Support Conversation Recovery | 🟢 Working |
| VIP Messaging                 | 🟢 Working |
| SKY Chat                      | 🟢 Working |
| SKY Streaming                 | 🟢 Working |
| Password Change               | 🟢 Working |
| Android Back Navigation       | 🟢 Working |
| Firebase Authentication       | 🟢 Working |

### 🟡 Still Being Improved

* Fine UI/UX polish
* Android edge cases
* Messaging edge cases
* Performance optimization
* Final release QA

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

### 💬 Talk with SKY

Have contextual conversations with SKY and continue discussions without treating every message as an isolated question.

### 🧠 Conversation Context

Relevant conversational context is preserved so follow-up questions can feel like part of the same conversation.

### 📝 Quick Notes

Capture thoughts, ideas, reminders, or information you don't want to lose.

### 🎯 Goal Tracker

Create and manage personal goals alongside your AI experience.

### 📰 What's New

Stay updated with announcements and platform updates.

### 💭 Opinion Box

Share feedback, opinions, and ideas that can help shape the platform.

### 🆘 Support

Support is available for both authenticated users and guests.

Guest support conversations can persist across application restarts so users can continue their support conversations.

### ⭐ VIP Experience

Sky Sense includes a controlled VIP membership system with additional interaction capabilities.

VIP access is handled through an approval and access-code system rather than a conventional paid subscription.

### 🔔 Intelligent Notifications

Receive contextual notifications for:

* VIP conversations
* Support
* Admin messages
* SKY replies
* Important account activity

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
* Firebase-based password management

Support functionality is **not made publicly readable** simply to make guest support easier.

---

## 📱 Platforms

### Web

Sky Sense is available as a web application and supports PWA installation.

### Android

Separate Android applications are available for:

* **Sky Sense** — User application
* **Sky Sense Admin** — Administrative application

Both Android applications are currently in public testing.

---

## 🧪 Real-Device Testing

A major part of development is testing the Android applications on physical hardware rather than relying only on successful builds.

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
* Android back navigation
* Chat UI
* Android-specific behavior

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

Or:

> Long-press a message → test Star/Edit/Delete.

Real-world testing helps identify problems that normal development builds can miss.

---

## 🗺️ Development Direction

Sky Sense is being developed around a simple principle:

> **The goal isn't to make another AI chatbot.**
>
> **The goal is to build a useful personal AI experience around SKY.**

Current development focuses on:

* Better contextual memory
* More useful personal workflows
* Improved SKY reasoning
* Smarter notifications
* Better messaging experiences
* Stronger Android experience
* Better account security
* UI/UX refinement
* Stability and edge-case handling
* Real-world user feedback

---

## 📌 Current Release

**Status:** 🟡 Public Testing

**Latest update:** `22 September 2026`

**Current focus:**

> **Polish → Test → Improve → Repeat**

The core platform is functional and being actively tested on real devices.

---

## 🌱 Open Development

Sky Sense is being built step by step.

The project provides an opportunity to experiment with:

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
