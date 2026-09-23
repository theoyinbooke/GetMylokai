# Mylokai — Privacy Policy, Terms & Conditions, and Legal Disclaimers

**Effective Date:** March 5, 2026
**Last Updated:** September 22, 2026
**App Name:** Mylokai (MyLokAI)
**Developer:** Olanrewaju Oyinbooke ("Developer", "we", "us", "our")
**Contact:** oyinbookeola@outlook.com

---

## Table of Contents

1. [Privacy Policy](#1-privacy-policy)
2. [Terms and Conditions](#2-terms-and-conditions)
3. [Disclaimers](#3-disclaimers)
4. [EU and International Compliance](#4-eu-and-international-compliance)
5. [Apple Platform Disclosures](#5-apple-platform-disclosures)
6. [Changes to This Document](#6-changes-to-this-document)
7. [Contact Information](#7-contact-information)

---

## 1. Privacy Policy

### 1.1 Overview

Mylokai is a privacy-first artificial intelligence chat application designed to operate entirely on your device. We are committed to protecting your privacy. **We do not collect, store, transmit, process, sell, share, or otherwise handle any personal data, usage data, analytics, telemetry, or any other information of any kind from our users.**

Mylokai does not use any cloud AI service. Every AI model runs on your device. Apart from downloading the models you choose (Section 1.5), the only features that send anything from your conversations off your device are the **optional web search** (Section 1.4) and the **optional weather lookup** (Section 1.4a), both off by default.

### 1.2 Data Collection

**We collect no data whatsoever.** Specifically:

- **No personal information** is collected (name, email, phone number, address, date of birth, or any other personally identifiable information).
- **No usage data** is collected (app usage patterns, session duration, feature usage, crash reports, or performance metrics). Crash and hang reports that Apple's MetricKit provides stay on your device; they reach us only if you choose to share one with us.
- **No analytics or telemetry** is collected, transmitted, or processed.
- **No device information** is collected (device model, operating system version, unique device identifiers, IP addresses, or hardware specifications).
- **No location data** is collected (GPS, Wi-Fi-based location, or IP-based geolocation).
- **No cookies, tracking pixels, web beacons, or similar technologies** are used.
- **No advertising identifiers** are collected or used.
- **No biometric data** is collected or processed.
- **No health or fitness data** is collected or processed.
- **No financial or payment data** is collected or processed.
- **No browsing history, search queries, or interaction data** is collected by us. If you turn on the optional web search, search queries are sent directly to Brave Search as described in Section 1.4. If you turn on the optional weather lookup, the city name you ask about is sent to Apple as described in Section 1.4a.

### 1.3 On-Device Processing

All AI inference, conversation processing, memory extraction, document analysis, speech recognition, and any other data processing performed by Mylokai occurs **exclusively on your device**. Specifically:

- **Conversations** are stored only in the local on-device database (Apple SwiftData) and are never transmitted to any server, cloud service, or third party.
- **AI model inference** using Apple's FoundationModels framework and MLX models runs entirely on-device using your device's Neural Engine and GPU.
- **Memory entries** (facts and preferences the app extracts from conversations) are stored only in the local on-device database and are never transmitted externally.
- **Documents** you upload (PDFs, images, text files) are processed on-device and are never uploaded to any server.
- **Voice input** is processed using Apple's on-device speech recognition and is never transmitted to any server. If on-device recognition is not available for your language or device, voice input is turned off rather than sent to a server.
- **Persona configurations** and **app settings** are stored only on your device.

### 1.4 Optional Web Search (Brave Search)

Mylokai does not connect to any cloud AI provider. Two **optional** features use the internet during a conversation: web search through the Brave Search API, using **your own Brave Search API key**, described here, and Weather, described in Section 1.4a. Web search is:

- **Off by default** — the app is fully functional without it.
- **User-initiated** — you must turn it on in Settings and enter your own Brave Search API key.
- **Clearly disclosed** — Settings explains what is sent before you turn it on.

**When web search is on, please be aware:**

- When the AI model decides a question needs current information, the app sends **a short search query** (a few words the model writes) to Brave Search. Your conversations, files, memories, and settings are **not** sent.
- The connection is **directly between your device and Brave**; we do not act as an intermediary and never receive the query.
- Brave receives the query, your API key, and your device's network information (such as its IP address). Brave states that it keeps a record of queries submitted through a Search API account for up to 90 days for billing and troubleshooting.
- Your API key is stored only in your device's Keychain and is sent only to Brave.
- **We are not responsible** for how Brave handles, stores, or retains data. Brave Search API privacy notice: https://api-dashboard.search.brave.com/privacy-policy

### 1.4a Optional Weather (Apple Weather)

If you turn on Weather in Settings, the assistant can look up current conditions and a short forecast for **a city you name**:

- Only the **city name** (for example "Chicago") is sent: to Apple Maps to find the place, and the resulting coordinates to Apple Weather (WeatherKit) for the forecast.
- Your device's location is **never** used or sent, and Mylokai does not request location permission.
- Weather data is provided by Apple Weather. Apple's privacy policy applies: https://www.apple.com/legal/privacy/ — data sources: https://weatherkit.apple.com/legal-attribution.html
- Weather is off by default, and you can turn it off at any time.

### 1.4b Optional Calendar (On Device)

If you turn on Calendar in Settings and allow access, the assistant can read your calendar events **on your device** to answer questions about your schedule. Calendar data is used only by the on-device AI model and is **never** sent off your device or to us. Calendar is off by default, and you can turn it off or revoke access at any time in your device's Settings.

### 1.5 Model Downloads

When you download AI models from the in-app model catalog, these models are downloaded from HuggingFace (https://huggingface.co). The download is a direct connection between your device and HuggingFace's servers. We do not operate, control, or intermediate these downloads. HuggingFace's privacy policy applies to these downloads: https://huggingface.co/privacy

### 1.6 Data Storage and Security

- All app data is stored locally on your device using Apple's SwiftData framework and iOS Keychain.
- Data is protected by iOS's built-in encryption and security features, including device passcode, Face ID, and Touch ID protections.
- We do not have access to any data stored on your device.
- If you delete the app, all locally stored data (conversations, memories, settings, and models downloaded to the app's own storage) is permanently deleted. Models stored in a folder you chose yourself (for example, a folder shared with other apps) remain there until you delete them.

### 1.7 Data Sharing

**We do not share any data with any third party for any purpose.** There are no data sharing agreements, no data partnerships, no data sales, and no data transfers of any kind initiated by us.

If you choose to contact us — for example with the in-app "Report Response" option, which opens an email you can review before sending — we receive only what you put in that email and use it only to respond and improve the app.

### 1.8 Children's Privacy

Mylokai is not directed at children under the age of 13 (or the applicable age of digital consent in your jurisdiction). We do not knowingly collect any information from children. Since we collect no data from any users, this is inherently satisfied.

### 1.9 Data Retention

Since we collect no data, there is no data retention policy applicable to us. All data created by the app exists only on your device and is under your exclusive control. You may delete any or all data at any time through the app's settings or by deleting the app.

### 1.10 Data Portability

You may export your data at any time. On iPhone and iPad, each conversation can be exported in full (Markdown or JSON) from the conversation list. The Export Data feature in Settings exports your conversation list and memories in JSON format.

---

## 2. Terms and Conditions

### 2.1 Acceptance of Terms

By downloading, installing, or using Mylokai, you acknowledge that you have read, understood, and agree to be bound by these Terms and Conditions, the Privacy Policy, and all Disclaimers contained in this document. If you do not agree to these terms, you must not use the app.

### 2.2 Description of Service

Mylokai is an application for iPhone, iPad, and Mac that provides an interface for interacting with artificial intelligence language models. All AI inference runs on your device, using Apple's on-device models or open models you download. The app offers optional web search through Brave Search. The app is provided for general informational and conversational purposes only.

### 2.3 License

We grant you a limited, non-exclusive, non-transferable, revocable license to use Mylokai for personal, non-commercial purposes, subject to these Terms and Conditions and the Apple Licensed Application End User License Agreement (EULA).

### 2.4 User Responsibilities

You are solely responsible for:

- All content you input into the app, including messages, documents, and API keys.
- Your use of the optional Brave Search web search, including compliance with Brave's terms of service.
- Ensuring that your use of the app complies with all applicable laws and regulations in your jurisdiction.
- Any consequences arising from actions taken based on AI-generated content.
- Maintaining the security of your device and any API keys stored within the app.
- Any costs, charges, or fees incurred from your Brave Search API account.
- Complying with the license and acceptable use terms of any AI model you download (shown in the app under Licenses).

### 2.5 Prohibited Uses

You agree not to use Mylokai to:

- Generate content that is illegal, harmful, threatening, abusive, harassing, defamatory, or otherwise objectionable.
- Violate any applicable local, national, or international law or regulation.
- Infringe upon the intellectual property rights of any third party.
- Attempt to reverse engineer, decompile, or disassemble the app beyond what is permitted by applicable law.
- Use the app for any purpose that is fraudulent, deceptive, or misleading.
- Generate content intended to cause harm to individuals, groups, or organizations.

### 2.6 Intellectual Property

The Mylokai app, including its design, code, graphics, and user interface, is the intellectual property of the Developer. Third-party AI models downloaded through the app are subject to their respective licenses as specified by their publishers (for example Apache 2.0, MIT, the Llama 3.2 Community License, or the LFM Open License). The app lists each model's license under Settings > Licenses.

### 2.7 Termination

We reserve the right to terminate or suspend your access to the app at any time, for any reason, without prior notice or liability. You may terminate your use of the app at any time by deleting it from your device.

### 2.8 Modifications to Terms

We reserve the right to modify these Terms and Conditions at any time. Changes will be indicated by updating the "Last Updated" date at the top of this document. Your continued use of the app after any changes constitutes acceptance of the modified terms.

---

## 3. Disclaimers

### 3.1 AI-Generated Content Disclaimer

**IMPORTANT: ALL CONTENT GENERATED BY MYLOKAI IS PRODUCED BY ARTIFICIAL INTELLIGENCE LANGUAGE MODELS AND SHOULD NOT BE RELIED UPON AS ACCURATE, COMPLETE, CURRENT, OR SUITABLE FOR ANY PARTICULAR PURPOSE.**

- AI-generated content may contain **errors, inaccuracies, hallucinations, fabrications, biases, or misleading information**.
- AI-generated content **does not constitute professional advice** of any kind, including but not limited to medical, legal, financial, tax, engineering, psychological, or any other professional advice.
- **You should independently verify** any information provided by the AI before relying on it or taking any action based upon it.
- The Developer **is not responsible** for any decisions, actions, or consequences resulting from the use of AI-generated content.
- The AI models used in this app have knowledge cutoff dates and **may not reflect current events, laws, regulations, or scientific understanding**.

### 3.2 No Warranty Disclaimer

**THE APP IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO:**

- IMPLIED WARRANTIES OF MERCHANTABILITY
- FITNESS FOR A PARTICULAR PURPOSE
- NON-INFRINGEMENT
- ACCURACY OR RELIABILITY OF CONTENT
- UNINTERRUPTED OR ERROR-FREE OPERATION
- FREEDOM FROM VIRUSES OR OTHER HARMFUL COMPONENTS
- COMPATIBILITY WITH ANY PARTICULAR DEVICE OR OPERATING SYSTEM VERSION

**THE DEVELOPER EXPRESSLY DISCLAIMS ALL WARRANTIES, WHETHER EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE.**

**If you turn on the optional Weather feature: YOUR USE OF THIS REAL TIME WEATHER GUIDANCE APPLICATION OR WEBSITE IS AT YOUR SOLE RISK. WEATHER DATA MAY NOT BE ACCURATE.**

### 3.3 Limitation of Liability

**TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL THE DEVELOPER BE LIABLE FOR ANY:**

- Direct, indirect, incidental, special, consequential, or punitive damages
- Loss of profits, data, use, goodwill, or other intangible losses
- Damages resulting from your access to, use of, or inability to use the app
- Damages resulting from any content obtained from or generated by the app
- Damages resulting from unauthorized access to or alteration of your data
- Damages resulting from the conduct of any third party in connection with the app
- Damages resulting from any errors, mistakes, or inaccuracies in AI-generated content
- Damages arising from the use of third-party services used by the app, such as web search
- Damages resulting from loss or corruption of locally stored data
- Any other matter relating to the app

**THIS LIMITATION APPLIES REGARDLESS OF THE LEGAL THEORY (CONTRACT, TORT, STRICT LIABILITY, OR OTHERWISE) AND EVEN IF THE DEVELOPER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.**

### 3.4 Indemnification

You agree to defend, indemnify, and hold harmless the Developer from and against any claims, liabilities, damages, losses, costs, and expenses (including reasonable attorneys' fees) arising out of or in connection with your use of the app, your violation of these terms, or your violation of any rights of a third party.

### 3.5 Third-Party Services Disclaimer

The Developer is not responsible for and makes no representations or warranties regarding any third-party services, including but not limited to:

- Brave Search, when you turn on the optional web search
- Apple Weather and Apple Maps, when you turn on the optional weather lookup
- HuggingFace model hosting and downloads
- The publishers of the open AI models listed in the app
- Apple's FoundationModels framework and on-device AI capabilities
- Any other third-party service, API, or platform

Your use of any third-party service is at your own risk and subject to that third party's terms and policies.

### 3.6 No Professional Advice Disclaimer

**Mylokai is not a substitute for professional advice.** The app and its AI-generated content should never be used as a replacement for:

- **Medical advice** — Do not use AI-generated content for medical diagnosis, treatment decisions, or health-related decisions. Always consult a qualified healthcare professional.
- **Legal advice** — Do not use AI-generated content for legal decisions, legal strategy, or understanding your legal rights. Always consult a qualified attorney.
- **Financial advice** — Do not use AI-generated content for investment decisions, tax planning, or financial strategy. Always consult a qualified financial advisor.
- **Mental health support** — The app is not a crisis resource. If you are experiencing a mental health emergency, please contact emergency services or a crisis helpline immediately.
- **Engineering or safety-critical advice** — Do not use AI-generated content for decisions that could affect physical safety, structural integrity, or critical systems.

### 3.7 Accuracy and Reliability Disclaimer

The Developer makes no representations or warranties about the accuracy, reliability, completeness, or timeliness of any content generated by the AI models or of any web search results. AI models are probabilistic systems that can and do produce incorrect, inconsistent, and fabricated information.

### 3.8 Availability Disclaimer

The Developer does not guarantee that the app will be available at all times, or that it will be compatible with future versions of iOS or future Apple devices. The app may be discontinued at any time without prior notice.

---

## 4. EU and International Compliance

### 4.1 General Data Protection Regulation (GDPR) — EU Regulation 2016/679

As Mylokai **does not collect, process, store, or transmit any personal data**, the obligations under the GDPR are inherently addressed. However, for clarity and transparency:

**Lawful Basis for Processing (Article 6):** No personal data processing occurs, therefore no lawful basis is required.

**Data Subject Rights (Articles 15-22):** Since no personal data is collected or processed:
- **Right of Access (Article 15):** There is no data held by us to access.
- **Right to Rectification (Article 16):** There is no data held by us to rectify.
- **Right to Erasure / Right to Be Forgotten (Article 17):** There is no data held by us to erase. All data exists solely on your device and can be deleted by you at any time.
- **Right to Restriction of Processing (Article 18):** No processing of personal data occurs.
- **Right to Data Portability (Article 20):** All your data is already on your device. The app provides an export feature for your convenience.
- **Right to Object (Article 21):** No processing of personal data occurs to which you could object.
- **Right Not to Be Subject to Automated Decision-Making (Article 22):** The app does not make any automated decisions that produce legal effects or similarly significantly affect you. AI-generated content is for informational and conversational purposes only.

**Data Protection Officer (Article 37):** Not required as we do not process personal data.

**Data Protection Impact Assessment (Article 35):** Not required as we do not process personal data.

**International Data Transfers (Chapter V):** No personal data is transferred internationally by us. If you turn on the optional web search, search queries are sent to Brave Search and are governed by Brave's privacy notice and data transfer mechanisms.

**Data Breach Notification (Articles 33-34):** As we hold no personal data, a data breach of user data from our systems is not possible. However, users should be aware that data stored locally on their device is subject to the security of that device.

### 4.2 EU AI Act — Regulation (EU) 2024/1689

Mylokai is classified as a **general-purpose AI application** that provides a user interface for interacting with AI language models. Under the EU AI Act:

**Risk Classification:** Mylokai is not designed for, marketed for, or intended for use in any high-risk category as defined under Annex III of the EU AI Act, including but not limited to:
- Biometric identification or categorisation
- Critical infrastructure management
- Education and vocational training (grading, admissions)
- Employment and worker management
- Essential private and public services (credit scoring, emergency services)
- Law enforcement
- Migration, asylum, and border control
- Administration of justice and democratic processes

**Transparency Obligations (Article 50):** 
- Users are clearly informed that they are interacting with an AI system.
- The app's onboarding flow and interface make it clear that responses are AI-generated.
- AI-generated content is not represented as human-generated.

**General-Purpose AI Models (Article 51-56):**
- Mylokai is not a provider of AI models — it is an application that runs AI models developed by third parties (Apple, and open models published on HuggingFace) on your device.
- The respective model providers are responsible for compliance with GPAI model obligations under the EU AI Act.

**Prohibited Practices (Article 5):** Mylokai is not designed for, and must not be used for, any prohibited AI practices, including:
- Subliminal, manipulative, or deceptive techniques
- Exploitation of vulnerabilities of specific groups
- Social scoring
- Real-time remote biometric identification in publicly accessible spaces
- Untargeted scraping of facial images
- Emotion recognition in the workplace or educational institutions
- Biometric categorisation based on sensitive attributes
- Predictive policing based solely on profiling

### 4.3 ePrivacy Directive — Directive 2002/58/EC (as amended)

Mylokai does not use cookies, tracking technologies, or any form of electronic communication surveillance. No consent under the ePrivacy Directive is required as no such technologies are employed.

### 4.4 Digital Services Act (DSA) — Regulation (EU) 2022/2065

Mylokai is a standalone application that does not host user-generated content publicly, does not operate as an online platform or intermediary service, and does not facilitate the dissemination of content to the public. The DSA obligations for online platforms and intermediaries do not apply.

### 4.5 Digital Markets Act (DMA) — Regulation (EU) 2022/1925

Mylokai is not a gatekeeper platform and the DMA obligations do not apply.

### 4.6 Consumer Rights Directive — Directive 2011/83/EU

The app is distributed through Apple's App Store. Consumer rights regarding digital content, including the right of withdrawal, are governed by Apple's App Store terms and applicable consumer protection laws in your jurisdiction.

### 4.7 UK General Data Protection Regulation (UK GDPR) and Data Protection Act 2018

For users in the United Kingdom, the same principles outlined in Section 4.1 (GDPR) apply under the UK GDPR. No personal data is collected, processed, or stored by us.

### 4.8 California Consumer Privacy Act (CCPA) / California Privacy Rights Act (CPRA)

For users in California, USA:
- **We do not sell personal information.** We do not collect personal information to sell.
- **We do not share personal information** for cross-context behavioral advertising.
- **We do not collect sensitive personal information.**
- Since no personal information is collected, the rights to know, delete, correct, and opt-out are inherently satisfied.

### 4.9 Other International Privacy Laws

Mylokai's zero-data-collection approach is designed to comply with privacy regulations worldwide, including but not limited to:
- **Brazil:** Lei Geral de Proteção de Dados (LGPD)
- **Canada:** Personal Information Protection and Electronic Documents Act (PIPEDA)
- **Australia:** Privacy Act 1988
- **Japan:** Act on the Protection of Personal Information (APPI)
- **South Korea:** Personal Information Protection Act (PIPA)
- **India:** Digital Personal Data Protection Act, 2023
- **South Africa:** Protection of Personal Information Act (POPIA)
- **Switzerland:** Federal Act on Data Protection (FADP)

Since no personal data is collected, processed, or transmitted, Mylokai inherently satisfies the core requirements of these regulations.

---

## 5. Apple Platform Disclosures

### 5.1 App Tracking Transparency

Mylokai does **not** track users across other companies' apps or websites. The app does not request App Tracking Transparency (ATT) authorization because no tracking occurs.

### 5.2 Apple Privacy Nutrition Labels

In accordance with Apple's App Privacy requirements:
- **Search History (optional web search only):** if you turn on web search, search queries are sent to Brave Search to provide results. This data is not linked to your identity and is not used to track you.
- **Weather (optional):** if you turn on Weather, the city name you ask about is sent to Apple only to answer that request. It is not your device's location, is not linked to your identity, and is not used to track you.
- **No other data is collected.**
- **Data Not Used to Track You:** No tracking occurs.

### 5.3 Required Device Permissions

Mylokai may request the following device permissions, which are used exclusively for on-device functionality:

- **Microphone Access:** Used solely for on-device speech-to-text input. Audio is processed locally and is never transmitted externally.
- **Speech Recognition:** Used solely for on-device transcription of voice input. If on-device recognition is unavailable, voice input is turned off rather than sent to a server.
- **Camera:** Used solely to capture documents and images you choose to attach in a chat. Images are processed on your device.
- **Photo Library:** Used solely to attach images you choose. Images are processed on your device.
- **Calendars:** Requested only if you turn on Calendar in Settings. Events are read on your device to answer schedule questions and are never transmitted.

These permissions are optional and the app is fully functional without them.

### 5.4 FoundationModels Framework

Mylokai uses Apple's FoundationModels framework for on-device AI inference. This framework runs entirely on your device using the Apple Neural Engine. Apple's privacy policies regarding the FoundationModels framework apply: https://www.apple.com/privacy

---

## 6. Changes to This Document

We reserve the right to update this Privacy Policy, Terms & Conditions, and Disclaimers at any time. When we make changes, we will update the "Last Updated" date at the top of this document. We encourage you to review this document periodically.

Material changes will be communicated through the app or through the App Store update notes when reasonably practicable. Your continued use of the app after any changes constitutes your acceptance of the revised terms.

---

## 7. Contact Information

If you have any questions, concerns, or requests regarding this Privacy Policy, Terms & Conditions, or Disclaimers, please contact:

**Developer:** Olanrewaju Oyinbooke
**Email:** oyinbookeola@outlook.com

For EU-specific inquiries, you may also contact your local Data Protection Authority, although we note that no personal data is processed by Mylokai.

---

## 8. Governing Law

These Terms and Conditions, and any disputes arising from or related to the use of Mylokai, shall be governed by and construed in accordance with the laws of the jurisdiction in which the Developer resides, without regard to its conflict of law provisions.

For users in the European Union, nothing in these terms affects your statutory rights under applicable EU consumer protection laws, including the right to bring proceedings in your local courts.

---

*This document was last reviewed and updated on September 22, 2026.*

*Mylokai is an independent application and is not affiliated with, endorsed by, or sponsored by Apple Inc., Brave Software, Hugging Face, or the publishers of the AI models listed in the app. Model and company names and logos are shown only to identify the source of each model. Apple Intelligence and Apple Weather are trademarks of Apple Inc.*

