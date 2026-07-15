# Privacy Policy for ListenBook

**Effective Date: July 15, 2026**

OWN PLACE LLC ("we," "us," or "our"), a limited liability company organized
under the laws of the State of Washington, USA, is the developer of the
ListenBook application, listed on the Apple App Store as "ListenBook
Audiobooks" (the "App"). Bundle identifier: com.anisimov.audiobooks.

We built ListenBook to be **private by design**. The App does not
automatically transmit your personal data to OWN PLACE LLC, and we do not
operate a developer server or backend. This Privacy Policy explains what
remains on your device and the limited situations in which information you
request is sent directly to third-party services such as Apple, LibriVox,
the Internet Archive, or — only if you turn on the optional cloud voice —
Microsoft Azure.

This Policy is available in English (primary). The App interface is available
in English, Russian, and Spanish. If a translation of this Policy is provided
and conflicts with the English version, the English version controls.

---

## 1. Who We Are and How to Contact Us

- **Developer / data controller (to the extent any applies):** OWN PLACE LLC, State of Washington, USA.
- **App:** ListenBook ("ListenBook Audiobooks"), iOS 26 or later, iPhone.
- **Contact for privacy questions:** contact@ownplace.net

## 2. Plain-Language Summary

- We have **no user accounts** — no registration, no login.
- We operate **no developer server or backend**. The App does not automatically send your audio files, listening activity, library information, or device identifiers to OWN PLACE LLC.
- We do **not operate our own analytics system** and do not include
  analytics, advertising, or tracking SDKs. Any functional third-party
  libraries included in the App are used solely to provide App features (such
  as ZIP extraction and the local Wi-Fi upload server) and are not configured
  to transmit personal information to OWN PLACE LLC. Apple may separately
  provide privacy-protected App Store Connect analytics or diagnostics from
  users who choose to share them, as described below.
- We use **no cookies**, request **no App Tracking Transparency (ATT)** permission, and use **no advertising identifiers (IDFA)**.

## 3. Information We Do NOT Collect Automatically

Because the App has no developer server and no account system, the App does
not automatically transmit user-level personal information, audio files,
listening activity, or device identifiers to OWN PLACE LLC. We do not
receive, store, sell, or share your name, phone number, contacts, photos,
location, health data, browsing history, or advertising identifiers through
the App. Apple may separately provide privacy-protected app analytics, crash
reports, and diagnostic information from users who choose to share analytics
with app developers, as explained below.

**If you contact us voluntarily.** The App does not automatically collect
personal information. If you voluntarily contact us at contact@ownplace.net,
we may receive your email address and any information you include in your
message. We use this information only to respond to your request, provide
support, protect our legal rights, and comply with applicable legal
obligations; we do not sell or share it. We retain support correspondence
only for as long as reasonably necessary to respond to your request,
maintain appropriate business records, resolve disputes, and comply with
applicable legal obligations. You may request deletion of your support
correspondence by contacting us at contact@ownplace.net, subject to any
information that we are required or permitted to retain by law. Support
correspondence may be processed and stored by our email service provider
solely to deliver, secure, and maintain our business email. We do not sell
support correspondence or use it for advertising.

**Apple analytics and diagnostics.** If you have enabled "Share With App
Developers" in your device settings, Apple may provide us with
privacy-protected App Store Connect analytics, crash reports, and diagnostic
information. We receive this information through Apple's developer services,
not through an analytics SDK embedded in the App, and use it only to
diagnose technical problems and improve the App. You can control this
sharing in iOS Settings under Privacy & Security → Analytics & Improvements.

Separately and independently of the above, the App may record an on-device
crash call stack (received from Apple's MetricKit framework) into its own
**local** diagnostics log described in Section 4. That local log stays on your
device; it is **not** sent to OWN PLACE LLC automatically, and reaches us only
if you deliberately export and send it. A crash call stack Apple may provide to
us through App Store Connect (above) is a different, Apple-controlled mechanism;
recording a crash stack locally does not mean we automatically receive it.

## 4. Information Stored Locally on Your Device or in Your Own iCloud

The following is created and stored **on your device**, or synced through
**your own Apple iCloud account** (controlled by you and by Apple, never by
us). It does not reach OWN PLACE LLC:

- Your imported audio files and book library (covers, titles, progress).
- Playback positions, bookmarks, playback history, and listening statistics.
- App settings (skip step, playback behavior, theme, language, etc.).
- Your **evaluation-period start date**, stored in the iOS **Keychain** and
  in the **iCloud Key-Value Store**. This value is synced through your Apple
  iCloud account so that reinstalling the App does not restart the evaluation
  period. It contains only a date and is never transmitted to us.
- Any **Microsoft Azure Speech key** you choose to enter for the optional cloud
  voice, stored in the iOS **Keychain** on your device and never transmitted to us.

The App also maintains a small, size-limited **technical diagnostics log** in
its local cache (not in the Files-visible Documents area). It may contain the
App version, pseudonymous book identifiers, source type, chapter numbers,
technical error information, and crash call stacks. It is **not intended to
contain book titles, book text, audio content, Azure keys, or file paths**. The
log remains on your device and is **not automatically transmitted** to OWN PLACE
LLC. You can optionally export it yourself with "Share diagnostics" in Settings
(see Section 5).

You can remove an Azure key from the App's Cloud Voice settings. Deleting the
App removes its local container, but may not remove Keychain items or values
already synchronized through the iCloud Key-Value Store. The evaluation-period
start date is intentionally designed to survive reinstallation.

## 5. Information That Leaves Your Device When You Use Certain Features

Some optional features send limited requests **directly to third parties**.
Except when you deliberately use "Share diagnostics" and select OWN PLACE LLC as
the recipient, these requests do not pass through, and are not received or
stored by, OWN PLACE LLC. Like any Internet communication, such requests
necessarily expose to the receiving service your IP address, the content of the
request (for example, a search query), and technical connection data; those
services process this information under their own policies:

| Feature (optional features are marked; cover-art lookup is on by default) | What is sent | Where it goes |
|---|---|---|
| LibriVox catalog search/download | Search text (title/author); download requests | librivox.org (feed API) and archive.org (file hosting) |
| Internet Archive catalog (scope `collection:librivoxaudio`) | Search text; download requests | archive.org |
| Cover-art lookup (**automatic by default**: runs after an import and at launch for books without a cover; can be turned off in Settings → Covers) | Book title/author | Apple iTunes Search API |
| One-time purchase / restore purchase | Purchase and restore requests | Apple (StoreKit) |
| Evaluation-period date sync | Evaluation-period start date only | Apple iCloud Key-Value Store |
| Wi-Fi upload (local web server, port 8080) | Your selected files | **Directly from your computer's browser to your iPhone over your local Wi-Fi network (computer-to-phone).** Not via the cloud and not via any developer server. |
| Optional cloud voice (text-to-speech), only if you enable it and enter your own key | The text of the book chapter being converted to audio, plus the Azure key you entered | Microsoft Azure Speech, using **your own Azure account and key** |
| "Share diagnostics" (only if you tap it) | A copy of the local technical diagnostics log | Whatever destination you pick in the iOS share sheet (for example Mail, Messages, or Files) |

**About purchases.** Purchase and restore requests are processed by Apple.
The App receives on-device entitlement information necessary to unlock
purchased functionality. OWN PLACE LLC does not receive your payment card
details or Apple Account credentials and does not maintain a user-level
database of purchases. Apple may provide aggregated sales and financial
reports through App Store Connect.

**About Wi-Fi upload:** When enabled, the App runs a temporary local web
server on your device and displays a local network address that includes a
one-time access token generated for that session. You open that address in a
browser on a computer connected to the same Wi-Fi network and upload files.
The transfer is strictly computer-to-phone over your local Wi-Fi network.
Upload requests that do not contain the current session token are rejected.
The token protects against casual or unauthorized connections, but because the
local transfer uses HTTP rather than HTTPS, a party capable of observing
traffic on the local network could potentially obtain it. Use this feature
only on a trusted private network, keep the displayed address private, and stop
the server when finished.

**About the optional cloud voice.** ListenBook can turn a text book (EPUB,
FB2, or TXT) into audio. By default this uses an **on-device Apple voice**, and
the text never leaves your device. As an option, you can choose a **cloud
voice** and enter your own Microsoft Azure Speech key (stored only in your
device Keychain). When the cloud voice is selected, the text of each chapter
being converted is sent **directly from your device to Microsoft Azure**, using
**your own Azure account and key**, to generate the speech audio. OWN PLACE LLC
never receives, stores, or processes this text, and operates no server in this
path. Per Microsoft's documentation, real-time text-to-speech input and output
for prebuilt voices is not retained in the service logs; Microsoft processes
the request under its own terms. This feature is **off unless you deliberately
add a key and select the cloud voice**; if you prefer that no text leaves your
device, use the on-device Apple voice.

**About the diagnostics log.** If you choose "Share diagnostics" in Settings,
iOS displays its standard sharing interface and sends a copy of the technical
diagnostics log only to the destination you select. OWN PLACE LLC receives the
log only if you deliberately choose to send it to us. The selected recipient or
service processes the shared file under its own terms and privacy policy. The
App does not send this log anywhere on its own.

**Third-party privacy policies.** These providers operate under their own
terms and privacy policies, which we encourage you to review:

- Apple (StoreKit, iCloud, iTunes Search API): https://www.apple.com/legal/privacy/
- Internet Archive (archive.org): https://archive.org/about/terms
- LibriVox (librivox.org): https://librivox.org/pages/privacy/
- Microsoft (Azure Speech, only if you enable the cloud voice): https://privacy.microsoft.com/privacystatement

We do not control these third parties and are not responsible for their
practices.

## 6. Children's Privacy (COPPA)

The App is a general-audience audiobook player. It is **not directed to
children under 13**, and we do **not knowingly collect any personal
information from children**. The App does not automatically collect personal
information from any user. We do not use the App to target children or to
serve advertising.
If you believe that a child has provided personal information to us, please
contact us at contact@ownplace.net so that we can review and, where
appropriate, delete the information.

## 7. Your Rights — California (CCPA/CPRA)

We do **not** sell or "share" (as those terms are defined under the
California Consumer Privacy Act, as amended by the California Privacy Rights
Act) any personal information, and we do not use personal information for
cross-context behavioral advertising. California residents generally have
the rights to: **know/access** the personal information collected;
**delete** it; **correct** it; **opt out** of its sale or sharing; and
**limit** the use of sensitive personal information, with a right to
**non-discrimination** for exercising these rights.

Because the App does not automatically collect personal information, and the
only personal information we may hold is support correspondence or technical
diagnostic information that you deliberately choose to send us, in most cases
there is little or no personal information for us to disclose, delete, correct,
sell, share, or limit. You may exercise any applicable rights — including
requesting access to or deletion of your support correspondence or diagnostic
information — by contacting
contact@ownplace.net, and we will respond consistent with applicable law
without discrimination.

## 8. Washington State

This Policy and the App are governed by the laws of the State of Washington.
The App is **not designed to collect consumer health data** and does not use
geofencing. We do not collect, process, store, or share consumer health data
as defined by Washington's My Health My Data Act (Chapter 19.373 RCW).

## 9. Your Rights — Other US States

Depending on where you live, applicable US state privacy laws may give you
rights to access, correct, delete, or obtain a copy of personal information,
and to opt out of certain uses of personal information (such as targeted
advertising, the sale of personal data, or certain profiling). Because the
App does not automatically collect personal information, the only
information OWN PLACE LLC is generally able to act upon is support
correspondence or technical diagnostic information that you deliberately choose
to send us. To make an inquiry or request deletion of your support
correspondence or diagnostic information, contact contact@ownplace.net.

## 10. EU / UK (GDPR and UK GDPR)

If the App is available in the European Union, the European Economic Area,
or the United Kingdom, please note that the App does not automatically
collect or process personal data. The personal data OWN PLACE LLC may process
is generally limited to support correspondence and technical diagnostic
information that you **deliberately choose to send to us** (for example, by
emailing contact@ownplace.net or by using "Share diagnostics" and selecting us
as the recipient). We process that information only to respond to your request,
diagnose the reported problem, protect our legal rights, and comply with
applicable legal obligations. We keep it only as long as needed for support and
investigation and to meet legal obligations; we do **not** use it for
advertising and do **not** sell it. You may request deletion of information you
have sent us, subject to anything we are required or permitted to retain by law.
For this limited processing the legal bases are our legitimate interests in
responding to your inquiry and providing support (Art. 6(1)(f) GDPR) and, where
applicable, compliance with legal obligations (Art. 6(1)(c) GDPR). We perform no
special-category processing (Art. 9 GDPR).

- You may exercise your data-subject rights (access, rectification, erasure,
  restriction, portability, objection under Arts. 15–22 GDPR / UK GDPR) with
  respect to any support correspondence or diagnostic information we hold by contacting
  contact@ownplace.net. You also have the right to lodge a complaint with
  your supervisory authority.
- Beyond information you deliberately send us, we carry out **no international
  transfers** of personal data ourselves. If you email us from outside the
  United States, your message will be received and processed in the United
  States. Any data you exchange directly with third parties — Apple (including
  the iTunes Search API used for cover art), archive.org, librivox.org, and
  Microsoft Azure (only if you enable the cloud voice) — is governed by those
  parties' own policies and may be processed by them outside your country.

If you are in the EU/UK and have questions, contact contact@ownplace.net.

## 11. Local Data, Deletion, and Backups

Audiobooks, covers, playback data, bookmarks, history, and statistics are
stored **locally in the App's container on your device**. Depending on your
Apple device and backup settings, some local App data may also be included in an
Apple-managed device backup. ListenBook does **not operate its own cloud
synchronization service** for your audiobook library; the only value it places
in iCloud is the evaluation-period start date, stored separately in the Keychain
and the iCloud Key-Value Store. OWN PLACE LLC does not keep copies of your files
or data and **cannot restore** anything that is deleted. Deleting the App may
permanently delete your imported audiobooks, bookmarks, and listening history
stored on the device.
You are solely responsible for maintaining your own backups (for example,
device backups via iCloud or your computer); the availability and behavior of
iCloud backups depend on your device settings and on Apple.

## 12. Security

Because your data stays on your device or in your own iCloud, its security
depends primarily on your device passcode and your Apple Account security. The
evaluation-period start date, and any Azure Speech key you choose to enter, are
stored using the iOS Keychain.

When Wi-Fi Upload is enabled, the App generates a fresh one-time access token
for that server session and rejects upload requests that do not present the
valid token. The transfer takes place over local HTTP and is not end-to-end
encrypted. You should use Wi-Fi Upload only on a trusted private network, keep
the displayed address and token private, and stop the server when the transfer
is complete. No security measure is perfect.

## 13. No Tracking, No Cookies, No Advertising

To be direct about tracking:

- **We do not track you.** The App performs no user tracking across apps,
  websites, or services.
- **We do not use cookies.** The App is a native iOS application and does not
  set or read cookies.
- **We do not show the App Tracking Transparency (ATT) prompt**, because we
  do not track you and do not access the device's advertising identifier.
- **We do not use advertising identifiers (IDFA)** or any device fingerprint
  for advertising or measurement.
- **We do not include analytics, advertising, or tracking SDKs.** Any
  functional third-party libraries in the App are used solely to provide App
  features and are not configured to transmit personal information to OWN
  PLACE LLC.

## 14. International Transfers

The App does not send personal data to OWN PLACE LLC automatically. When you
deliberately use an optional third-party feature — such as the Azure cloud
voice, catalog search, book download, cover-art lookup, StoreKit, or iCloud
synchronization — the resulting request may be processed by that provider in
the United States or another country under the provider's own privacy policy.
If you contact us by email or send us a diagnostics file, that information is
received and processed in the United States.

## 15. Changes to This Policy

We may update this Policy to reflect changes to the App or to applicable law.
When we do, we will revise the "Effective Date" above and post the updated
Policy at its public URL. The updated Policy will apply from the revised
Effective Date. Where required by applicable law, we will provide additional
notice or obtain consent before materially changing how personal information
is processed.

## 16. Contact

OWN PLACE LLC — contact@ownplace.net
