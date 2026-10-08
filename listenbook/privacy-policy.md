# Privacy Policy for Talefall — Audiobook Player

**Effective Date: October 8, 2026**

**Controller:** OWN PLACE LLC, a Washington limited liability company, 7707 NE
141st St, Kirkland, WA 98034-5321, USA. Email: contact@ownplace.net.
Telephone: +1 (213) 524-8012.
**App:** Talefall — Audiobook Player (the "App"), bundle identifier
com.anisimov.audiobooks, for iPhone.

Talefall is first of all an audiobook player and reader that works with your
own files on your own device. **The player does not upload your library.** The
optional, paid **Talefall Subscription** adds two server features, both in the
App's Create tab (together, the "Service"):

- **Book from an Idea:** you describe an idea; our service writes a book (a
  Story, an Explainer, or a How-to guide) with a third-party AI model and
  narrates it with our own narrator model.
- **Narrate My Text in the Talefall voice:** our narrator model reads aloud a
  text book you already have.

This Policy explains what leaves your device when you use those features,
where it goes, why, and how long it is kept, and what never leaves your
device. Companion documents that are part of our privacy disclosures:

- **Consumer Health Data Privacy Policy:**
  https://ownplace.net/talefall/health-data (also linked from the home page
  of ownplace.net)
- **AI Safety and Content Policy:** https://ownplace.net/talefall/ai-safety
- **Supported Territories:** https://ownplace.net/talefall/ai-studio-territories

This Policy is published in English, Russian, and Spanish, the languages of
the App. If a translation conflicts with the English version, the English
version controls, without limiting mandatory rights under the law where you
live.

---

## 1. Who We Are and How to Contact Us

- **Controller:** OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321,
  USA. We have no affiliates.
- **Privacy questions and requests:** contact@ownplace.net or
  +1 (213) 524-8012 (Section 10).

## 2. Summary

- **No accounts.** No registration, login, or password. We do not know your
  name, email, or Apple ID unless you write to us.
- **The player is local.** Your audio files, text books, library, positions,
  bookmarks, notes, statistics, and settings stay on your device and in your
  own iCloud or device backups.
- **If you do not use the Service, none of your library content is sent to
  us.** The App still contacts Apple and, when you open them, the catalog
  providers (Section 5).
- **The Service is optional.** When you order a book, your idea goes to our
  service on Modal (USA). Our server first checks it for personal and
  sensitive data and for prohibited content. It is then sent to **OpenRouter,
  Inc.**, which passes it to independent hosting providers of the **GLM**
  model that OpenRouter lists as headquartered in the United States and as
  zero data retention. We may switch this route to **Amazon Web Services
  (Amazon Bedrock)**; the permission you give names both (Section 6.6).
  Processing is not guaranteed to take place only in the United States.
  Narration runs on our own narrator model on Modal, and every chapter is
  checked by our own moderation model on Modal; neither sends the text to
  another company.
- **The rule: no personal data about real people, including you.** You
  confirm it before every book order and before a book is first sent for
  narration in the Talefall voice. Our server refuses book ideas in which it
  detects personal or sensitive data (Section 6.5). We do not read your
  requests or books.
- **We keep no copy after delivery.** The server copy of a book is deleted as
  soon as the App confirms it has saved every chapter; an undelivered order
  expires after seven days and is deleted, with its hours restored, at the
  next scheduled cleanup. We keep a receipt
  (times, hours, confirmation records) but not the content (Section 6.4).
- **Your subscription is identified by Apple's signed transaction, not by
  you** (Section 6.1).
- **Usage counters only if you say yes**; the default is no (Section 8).
- **No tracking, no ads, no advertising identifier, no third-party analytics
  SDKs.** We do not sell or share personal information.

## 3. Information We Do Not Collect

Through the App we do not ask for, and the App does not send us, your name,
email address, phone number, contacts, photos, precise location, browsing
history, device identifiers, or advertising identifier. We do not collect
your playback history, bookmarks, notes, or highlights, or titles or text from
your library unless you deliberately send a text for narration in the
Talefall voice. We do not request health information and do not infer
anything about your health or other characteristics from what you submit.

**If you contact us.** If you email contact@ownplace.net, we receive your
email address and what you write. We use it only to respond, to handle
support, privacy, content, and copyright requests, and to comply with law. We
keep correspondence for no longer than **24 months after the last message**,
and delete it earlier on request, except where we must keep it to document a
refund dispute, a content report, a legal claim, or a legal obligation. For
consumer health data, we keep it beyond an applicable deletion deadline only
where a specific legal obligation or statutory exception requires it. Our
email provider, Apple (iCloud Mail), processes this mail to deliver and
secure it.

**Apple analytics.** If you enabled "Share With App Developers" in iOS, Apple
may give us aggregated App Store Connect analytics and crash reports through
Apple's developer services. There is no analytics SDK in the App.

**On-device technical log.** The App keeps a small, size-limited technical
log on your device (App version, internal book numbers, step names, error
codes, and crash reports from Apple's MetricKit). It contains no book content
and is not sent anywhere.

## 4. Information Stored Only on Your Device or in Your iCloud

- Your imported audio files and text books, your library, covers, titles,
  progress, playback and reading positions, bookmarks, highlights, notes,
  listening statistics, and settings.
- **On-device transcription:** turning an audiobook into text uses Apple's
  speech recognition on the device; the audio and text stay there.
- **On-device voice:** reading a text aloud with an Apple voice happens on
  the device and does not use the Service.
- **On-device format conversion** of audio formats.
- The **bundled sample audiobook**, which plays without a network connection.
- The **trial start date**, stored in the iOS Keychain and the iCloud
  Key-Value Store so that reinstalling does not restart the trial. It contains
  only a date and may survive deleting the App.
- Your **usage-counters answer**, and a local copy of your Terms acceptance
  and AI-provider permission so the App does not ask again unnecessarily.
- Books delivered by the Service, on the device and, if iCloud is available
  and the save succeeds, in your private iCloud storage, which we cannot
  access.

## 5. What Leaves Your Device

Each connection necessarily exposes your IP address and ordinary connection
data to the service that receives it. Optional features send nothing until
you use them.

| Feature | What is sent | To whom | Why | How long |
|---|---|---|---|---|
| **Cover lookup** (Settings → "Find covers online", off until you turn it on) | Title and author of a book without a cover | Apple iTunes Search API | To find a cover image | Not received by us |
| **Catalogs** (only when you open them) | Your search text and download requests | LibriVox, the Internet Archive, Project Gutenberg / Gutendex | To browse and download public-domain books | Not received by us |
| **Wi-Fi Upload** (only when you turn it on) | The files you choose | From your computer's browser to your iPhone over your local network | To copy files to the phone | Not received by us |
| **Purchases** | Purchase and restore requests | Apple (StoreKit) | To buy the player, subscribe, or buy extra hours | Apple's policy; Section 7 |
| **Trial date** | The trial start date | Apple iCloud Key-Value Store | So reinstalling does not restart the trial | Your iCloud account |
| **AI-provider permission** | Whether you allowed or withdrew it, its version, and the time, with the signed subscription transaction (your Terms acceptance stays on the device) | Our service on Modal (USA) | So the Service writes books only with your permission | Section 6.4 |
| **Book from an Idea** | Your idea, book type, language, length, the signed subscription transaction, the App's shared service token, a random order key, and the version and time of your per-order confirmation | Our service on Modal (USA); the idea and the working text are sent on to the AI provider (Section 6.3) | To write and narrate the book you ordered | Content: until delivery; an undelivered order expires after 7 days (Section 6.4). Receipt: Section 6.4 |
| **Narration in the Talefall voice** (only for a book you confirmed) | The book's title, language, and chapter text, with the signed transaction and token | Our service on Modal (USA); our own narrator model only | To narrate that book | As above |
| **Passage narration** (Talefall voice, while you listen to a confirmed book) | The passage text and language, with the signed transaction and token | Our service on Modal (USA); our own narrator model only | To return audio of that passage | Not stored by our application; only the character count and audio length are logged. Modal may keep function inputs and outputs up to 7 days |
| **Collecting books** | Book numbers, per-chapter "saved" confirmations, delete or cancel requests, the signed transaction | Our service on Modal (USA) | To download your books and let the server delete its copy | Section 6.4 |
| **Report content** (only when you use it) | Book number, chapter, the passage shown on the report screen (up to 4,000 characters), the reason, your note, the signed transaction if you have a subscription | Our service on Modal (USA); if sending fails, an email you send to contact@ownplace.net (without the passage) | To review and act on a report | 12 months (Section 6.4) |
| **Usage counters** (only if you said yes) | Step names with seconds since launch, file type of a failed import, App version, device language, a random per-session number | Our service on Modal (USA) | To learn where new users get stuck | 90 days |
| **App Store Server Notifications** (not from your device) | Apple's signed notice of a renewal, expiry, refund, or revocation | From Apple to our service | So the Service knows the subscription status | Section 6.4 |

**Third-party policies.** Apple: https://www.apple.com/legal/privacy/ ·
Internet Archive: https://archive.org/about/terms · LibriVox:
https://librivox.org/pages/privacy/ · Project Gutenberg:
https://www.gutenberg.org/policy/privacy_policy.html · Modal:
https://modal.com/legal/privacy-policy · OpenRouter:
https://openrouter.ai/privacy · Amazon Web Services:
https://aws.amazon.com/privacy/.

## 6. The Talefall Subscription's Server Features

This section applies only if you subscribe and use the Service.

### 6.1 No account — an Apple-signed transaction instead

When you subscribe, Apple gives the App a transaction record signed by Apple.
The App attaches it to every Service request. Our server verifies Apple's
signature and reads only the subscription's **original transaction
identifier** (a number assigned by Apple that stays the same across renewals),
the product, the environment, and the expiry and revocation dates. We store
the original transaction identifier with your orders, receipts, permission
record, reports, and hours balance, and it appears in our logs of hours
charged and restored. It contains no name, email, or Apple ID, and Apple
does not give us your identity with it, but it is a persistent identifier, so
we treat it as personal information. We may associate it with contact details
you give us in correspondence.

The App also sends a **shared service token**, the same in every copy of the
App; it is an abuse-control signal, not authentication. Access to your books
depends on the Apple-signed transaction. A **random order key** lets the
server recognize a repeated request as the same order.

### 6.2 What our server stores about an order

While an order is in progress: your idea (or, for narration, the text you
supplied), book type, language and length, the generated title and chapters,
the audio, technical state and times, the original transaction identifier,
and the request identifiers returned by the AI provider. Content is held in
Modal's storage as **temporary, encrypted working storage** and is kept out of
our application logs.

For every order we also keep a **receipt** that outlives the content: book
number, original transaction identifier, times, ordered and delivered
length, hours charged or restored, and the outcome. For a book order the
receipt also records your per-order confirmation: the version of the
confirmation text, the time, and a cryptographic fingerprint (SHA-256) of the
idea text — not the text itself.

### 6.3 Who processes the content

| Recipient | Role | Location | What it receives | Commitments |
|---|---|---|---|---|
| **Modal Labs, Inc.** | Hosting: runs our service, our writer program, our narrator model, and our moderation model; stores working content, receipts, and logs | United States | Everything in 6.2 | Processor under Modal's Data Processing Addendum (modal.com/legal/dpa): processes on our instructions, lists its subprocessors, notifies breaches, does not train on customer data. Modal may keep function inputs and outputs for up to seven days under its infrastructure retention policy, independently of our deletion |
| **OpenRouter, Inc.** (current route) | Gateway that passes book-writing requests to the model's hosting providers | United States company; processing not guaranteed to be only in the United States | Your idea, length, language, and the instructions, plans, and draft chapters our writer program produces. **We add no account, device, or subscription identifier** | Processor under OpenRouter's data processing addendum (signed September 11, 2026). Requests are sent with `data_collection: deny`, zero-data-retention routing, and a fixed list of hosting providers; if none of them is available, the request is not sent elsewhere. OpenRouter may keep limited request metadata for billing, security, abuse prevention, or legal compliance |
| **Hosting providers of the GLM model** (current route), reached through OpenRouter: Baseten, Crusoe, Decart, DeepInfra, Fireworks AI, Inference.net, Modal, Morph, Novita AI, Parasail, Phala, Sail Research, Together AI, Venice, and Wafer | Run the GLM model that writes the text | Providers that OpenRouter lists as headquartered in the United States and as zero data retention; server locations not guaranteed | The same content OpenRouter forwards | Bound through OpenRouter. Zero data retention is the providers' stated commitment, not a guarantee from us. **Z.ai, the developer of GLM, does not receive your orders** |
| **Amazon Web Services, Inc. (Amazon Bedrock)** — possible future route | Would run the model that writes the text, instead of OpenRouter and its hosts | United States company; processing not guaranteed to be only in the United States | The same content | Not in use as of the Effective Date. If we switch, we will update this table before the switch; your existing permission already names AWS |
| **Our narrator model** (VoxCPM2) | Reads text aloud | Our own container on Modal (USA) | The text to be narrated | Operated by us; nothing is sent to another company |
| **Our moderation model** | Checks each generated chapter (Section 6.5) | Our own container on Modal (USA) | Each generated chapter | Operated by us; nothing is sent to another company |
| **Apple** | Payments, subscription status, email delivery for contact@ownplace.net | Apple's infrastructure | Purchases; notices about renewals and refunds; your email if you write to us | Apple's policy |

**Contract limits on sensitive data.** Our agreement with OpenRouter is its
standard data processing addendum, which excludes sensitive data. We therefore
prohibit sending personal or sensitive data in requests and filter for it
(Section 6.5); we do not claim any contractual protection for sensitive data
that we do not have. Narration and moderation run on our own models at Modal.

We never use your requests or books to train models, never sell them, and
share them with no one other than the recipients above, except as required by
law (for example, a valid court order or a mandatory report) or in a merger
or sale of the business, subject to applicable law. Where the law allows, we
will tell you about a legal demand for your data.

**Human access.** Nobody routinely reads requests or books. Specific content
may be reviewed when you contact support, report content, or submit a legal
complaint, or when reasonably necessary to investigate abuse or a security
incident or to comply with law.

### 6.4 Retention and deletion — no copy after delivery

- **Working content** (idea or narration text, generated chapters, title,
  audio, AI-provider request identifiers) is held only while the order is
  produced and delivered.
- **Delivery is confirmed only after the App has saved every chapter on your
  device.** Immediately after that, we delete our server copy of the text and
  audio. We cannot restore or re-deliver the book after that.
- **If delivery is not confirmed within seven days** after the Service
  accepted the order, the order expires: at the next scheduled cleanup,
  normally within 15 minutes, we delete all server-side order content and
  restore all hours reserved or charged for it; a cleanup that fails is
  retried.
- **Deleting or cancelling a book in the App** sends a delete request to the
  service (retried later if you are offline); a running order is stopped and
  its hours restored.
- **Receipts, permission records, and the hours balance** (Sections 6.2 and
  6.6) are kept for **seven years after the last related financial event**,
  because they document paid work and charges, then deleted or irreversibly
  aggregated. They contain no book content.
- **Content reports** are kept for **12 months** after submission, separately
  from books. **Blocks** of a subscription, with the reason category and
  related book number, are kept while the block lasts and for 12 months after
  it ends.
- **Materials preserved for a report under 18 U.S.C. § 2258A** are kept one
  year after submission, or longer where the law requires, under a legal hold.
- **Deletion-request records** (date, a keyed hash of the transaction
  identifier, and what was deleted; no content) are kept for two years as
  evidence that we complied.
- **Processor copies.** Modal may keep function inputs and outputs for up to
  seven days under its infrastructure retention policy. OpenRouter and the
  hosting providers may keep limited metadata as described in 6.3. After
  delivery we no longer hold identifiers that would let us locate any residual
  provider copy; while an order is active, a deletion request cancels it.
- For Washington consumer health data, backup copies held by a processor are
  deleted no later than six months after an authenticated request.

**Your own copy.** The copy on your device and in your private iCloud storage
is yours; we cannot access it, and a deletion request to us does not delete
it. Deleting a book in the App offers to remove both. If iCloud is unavailable
or full, use Export to Files before deleting the App.

### 6.5 Safety controls

The AI model has no access to your library or device; it sees only your idea
and what it generated for that order.

- **Input check for personal and sensitive data in book ideas** (on our
  server, before anything is sent to an AI provider; English, Russian, and
  Spanish): email addresses, phone numbers, U.S. Social Security numbers,
  payment-card numbers, IBANs, passwords and API keys, and statements about
  your own or a named close person's health, sexual orientation, gender
  identity, or criminal record. A match is refused, nothing is sent on, no
  hours are used, and the App asks you to rewrite the request. Text you send
  for narration is not scanned for personal data; your per-book confirmation
  and the rule apply to it.
- **Input check for prohibited content** (book ideas, narration text, and
  passages): clear requests for sexual content involving minors, weapons of
  mass destruction, or encouragement of suicide are refused the same way.
- **Output moderation:** every generated chapter is checked before narration
  and delivery by an open-source safety classifier model running in our own
  container on Modal, for sexual content (especially involving minors), hate,
  dangerous instructions, and personal data about real people. A failing
  chapter is not narrated or delivered; the order is stopped and its hours
  restored.
- Our logs record only the category of a refusal or moderation decision,
  never the text. These checks are not used to infer anyone's health or other
  characteristics, and they create no profile of you.
- These controls are pattern- and model-based and imperfect; they do not
  recognize every real person, and the rule applies equally to anything they
  miss.
- **Reports and blocks.** Reports (Section 5) are reviewed promptly. We may
  block a subscription for serious or repeated violations; a blocked
  subscriber may ask for review by email. Details and the appeal process are
  in the [AI Safety and Content Policy](ai-safety-and-content-policy.html).

### 6.6 Screens before using the Service, and what we record

1. **"Before You Create"** (once, before the first book order or narration in
   the Talefall voice; the App does not send either until you accept): *"Creating books from ideas and narrating your text on
   our service are covered by the Terms of Use and the Privacy Policy. These
   features are for adults only."* with the switch *"I'm 18 or older and agree
   to the Terms of Use and Privacy Policy"* and the button "Continue." This is
   a self-declaration of age, not age verification. The App stores the Terms
   version (currently 2026-10-08), the time, and your statement on your
   device; it is not sent to our server.
2. **AI-provider permission** (before the first book order; again if the
   permission text changes). Title: *"Send your order to OpenRouter or Amazon
   Bedrock?"* Text: *"Allow content from my book orders to be sent to
   OpenRouter, which passes it to independent hosting providers running the
   GLM model (developed by Z.ai), to generate the requested text. Z.ai itself
   does not receive my orders. Requests are restricted to hosting providers
   that OpenRouter lists as headquartered in the United States and as zero
   data retention, which means they state that they do not store or train on
   the content. Talefall may instead send the same content to Amazon Web
   Services (Amazon Bedrock) for the same purpose; the Privacy Policy names
   the route in use. I understand that processing is not guaranteed to take
   place only in the United States. This permission remains in effect until I
   withdraw it or Talefall uses a provider not named here. Zero data retention
   is the providers' commitment, not a guarantee from us; OpenRouter or Amazon
   Web Services may keep limited request metadata for billing, security,
   abuse prevention, or legal compliance."* Buttons: "Allow and Continue" and
   "Not Now"; "Not Now" sends nothing to these providers. Our server keeps
   your latest decision (allowed or withdrawn), the permission version
   (2026-10-08), and the time, with the original transaction identifier, and
   refuses book orders without a current permission. You can withdraw it in Settings; book orders then stop until
   you allow it again. Narration does not need this permission because the
   text is not sent to these providers.
3. **Before every book order:** the switch *"My idea contains no personal data
   about real people"*; it covers the exact text, so editing the idea requires
   confirming again. Recorded in the receipt as described in 6.2.
4. **Before a book is first narrated in the Talefall voice:** the switch or
   question *"This text has no real person's information"* / *"Send this text
   for narration?"*. This confirmation stays in the App and is not recorded by
   our server. With the on-device Apple voice the text never leaves your
   device.

**None of these screens asks for, and no tap is treated as, consent to process
health or other sensitive data.** Neither a confirmation nor the fact that a
request passed our filters authorizes processing such data. If it reaches us
despite the rule, that is a residual risk we work to prevent, not a service
we offer: it may be processed automatically before anyone notices, but we
rely on a "requested service" exception only where the applicable law allows
it and the processing is necessary and proportionate, and never because one
person submitted another person's data. When we learn that an order contains
such data, we stop the order, delete the data, restore the hours, notify
OpenRouter of the identifiers we still hold if the order is active, and may
refuse further orders. See the Consumer Health Data Privacy Policy.

### 6.7 Territory and sanctions check

The Service is offered only in the Supported Territories (Terms of Use,
Section 4.9). For each Service request our server derives the **country** from
the request's IP address and refuses requests from outside the Supported
Territories, from countries and regions subject to comprehensive U.S.
sanctions or otherwise excluded (including the Crimea, so-called Donetsk
People's Republic, so-called Luhansk People's Republic, Kherson, and
Zaporizhzhia regions of Ukraine), and when the country
cannot be determined. Privacy requests, permission withdrawals, and content
reports are not blocked by this check. We record the country code and the
decision in our logs, not the IP address; the IP address is used only for this check. We do
not derive the U.S. state, do not collect precise location, and do not use
location to infer visits to any place. This check is a territorial control
and does not by itself establish eligibility under sanctions law.

## 7. Purchases and What We Receive from Apple

All payments are processed by Apple. We never receive your card details,
billing address, or Apple Account credentials. Apple gives us aggregated
sales reports.

- **One-time player purchase:** checked on the device with StoreKit; nothing
  about it is sent to our server.
- **Talefall Subscription and extra hours:** in addition to the signed
  transaction (Section 6.1), Apple's App Store Server Notifications tell our
  server when a subscription renews, expires, or is refunded or revoked. We
  store the original transaction identifier, the event type, and the dates,
  to open each month's hours and to stop accepting a refunded or revoked
  subscription. For an extra-hours purchase our server verifies the signed
  transaction and stores its identifier so it is credited only once.

## 8. Usage Counters (optional, off unless you allow them)

On first launch the App asks whether it may send a few anonymous counters;
the default is no, and you can change your answer in Settings. If you allow
it, the App sends step names (for example: the App opened, the library was
shown, playback started, an import failed), the seconds since launch, the file
type of a failed import (never the file name), the App version, your device
language, and a random number that groups one session's counters and is not
stored. The counters never contain book titles, text, file names, or any
identifier of you or your device. Our server accepts only these fields and
deletes the counters after **90 days**. They are not shared with anyone and
not used for tracking.

## 9. Server Logs

Our service on Modal writes technical logs: request paths with book numbers,
status codes, times, the original transaction identifier on hours and order
events, character and duration counts, refusal and moderation categories, and
the country code from the territory check. Our application does not write the
IP address or any request or book text to these logs. Modal's infrastructure
processes IP addresses to route and secure traffic under its own policies.
Our application logs are kept for about **one day**. We also keep daily counts
of refused requests by reason, without identifiers, for 30 days.

## 10. Your Choices, Rights, and How to Make a Request

- **Use the player only.** If you do not use the Service and do not allow
  counters, no library content is sent to us. Cover lookup and the counters
  are off unless you turn them on in Settings.
- **Delete a book.** Deleting a book in the App deletes our server copy if one
  still exists, stops a running order, and restores its hours.
- **Withdraw the AI-provider permission** in Settings. New book orders stop
  until you allow it again; processing already done is not undone.
- **Make a privacy request** — access, a copy, correction, deletion, or a
  request that we stop collecting, sharing, or selling your consumer health
  data: email contact@ownplace.net with the subject "Talefall: privacy
  request" (the "Request data deletion" button in the App's Settings, under
  Privacy, prepares a deletion email with the subject "Talefall: data deletion
  request" and your subscription's original transaction identifier). Include
  that identifier if you have it; it helps us find your records. The identifier alone is not proof of authority, so
  before disclosing or deleting data we may ask for proof proportionate to the
  request, such as an Apple receipt for the subscription. People who do not
  use Talefall may also make requests; we verify them by an appropriate
  alternative method.
- **What deletion covers.** We delete any remaining order content, receipts,
  permission records, reports linked to you, and other records eligible for
  deletion, and instruct processors that can still locate a copy to delete it.
  We keep only the minimal deletion-request record (Section 6.4), records the
  law requires us to keep, and — unless you confirm that you give them up —
  the minimum record needed to preserve unused purchased extra hours. Where
  Nevada law (NRS 603A.515) applies, we delete covered data within 30 days
  after authentication and notify recipients.
- **Access and correction.** We provide a copy of what still exists and the
  list of recipients that received order content. Because content is deleted
  after delivery, we cannot provide or correct what no longer exists.
- **Authorized agents** may act for you with your written permission.
- **Cancel the subscription** in iOS Settings → Apple Account →
  Subscriptions. Cancelling does not by itself delete records; make a request
  for that.

**Timing.** We respond without undue delay and within **45 days** of receiving
your request; verification does not restart this period. We may extend it
once by 45 days where the law allows, telling you why within the first period.
Shorter legal deadlines apply where they exist. **Appeals:** if we decline a
request, reply to our answer within 45 days; we answer the appeal in writing
within 45 days and, where the law provides, tell you how to contact your
state's Attorney General. We will not discriminate against you for exercising
your rights. If you ask us to stop processing your data for the Service, we
cannot write or narrate new books for your subscription while that request
is in effect; your player and the books on your device are not affected.

## 11. Children and Age

The App is rated **18+** on the App Store, and the Service is for adults only.
Before first using the Service you state that you are 18 or older; we do not
verify age. The App is not directed to children, and we do not knowingly
collect personal information from children under 13. If we learn that we
have, we delete it. Parents may contact contact@ownplace.net.

## 12. California (CCPA/CPRA)

To the extent the CCPA applies to us, California residents have the rights to
**know/access**, **delete**, and **correct** personal information and to
**non-discrimination**; we honor these requests even where the law may not
require it. We do **not** sell or "share" personal information, do not use it
for cross-context behavioral advertising, and do not use sensitive personal
information for purposes that would require a right to limit. In the past 12
months we collected: identifiers (the original transaction identifier and the
country derived from IP); commercial information (subscription status and
hours); user-generated content (book ideas and narration text, held
temporarily, and content reports); limited internet activity (optional
anonymous counters); and contact details and correspondence if you wrote to
us — for the purposes in Sections 5–9, disclosed only to the recipients in
Section 6.3. Make requests as described in Section 10; we acknowledge them
within 10 business days.

## 13. Washington, Nevada, Connecticut, and Other U.S. States; Consumer Health Data

The Service is not a health service, and our rule prohibits personal and
sensitive data about real people in requests. A request may nevertheless
contain **consumer health data** under Washington's My Health My Data Act,
Nevada SB 370, or the Connecticut Data Privacy Act if someone includes it
against the rule. Our separate **Consumer Health Data Privacy Policy**
(https://ownplace.net/talefall/health-data), linked from the ownplace.net
home page, explains what we may collect, why, who receives it, how long it is
kept, and your rights. We do not use geofences and do not infer health status.

Residents of other states with privacy laws (for example Colorado,
Connecticut, Oregon, Texas, and Virginia) may access, correct, delete, or
obtain a copy of their personal information, and opt out of targeted
advertising, sale, or profiling; we do none of those three. Make requests as
described in Section 10.

## 14. European Economic Area, United Kingdom, and Switzerland

The App is not distributed on App Store storefronts in the European Economic
Area, the United Kingdom, or Switzerland, and the Service is not offered to
people located there (Section 6.7). If you contact us from there for
support, we process your email and message to respond, on the basis of your
request, our legitimate interest in providing support, and our legal
obligations; you may ask for access, correction, deletion, restriction, or
portability, object, and complain to your supervisory authority.

## 15. Security

- All connections between the App and our service, and between our service
  and its processors, use TLS. Working content is stored encrypted.
- Service requests must carry an Apple-signed transaction, which our server
  verifies before doing paid work; books are shown, cancelled, and deleted
  only for the subscription that ordered them.
- On your device, keys and the trial date are kept in the Keychain; local
  files have the protection iOS provides, which a device passcode improves.
- Wi-Fi Upload uses a session token over plain HTTP on your local network;
  use it only on a trusted private network.

We are a small company without a dedicated security team; the shared service
token in the App could be extracted, though it does not give access to anyone
else's books. No Internet service is perfectly secure. We notify affected
people and authorities of a breach as and when the law requires.

## 16. No Tracking, No Cookies, No Advertising

We do not track you across apps or websites, do not use the advertising
identifier, do not show the App Tracking Transparency prompt, and include no
analytics, advertising, or tracking SDKs. The App sets no browser cookies;
websites you open from it follow their own policies.

## 17. Retention Summary

| Data | Where | Kept |
|---|---|---|
| Library, reading and playback data, settings | Your device and backups | Until you delete it |
| Trial start date | Keychain and iCloud Key-Value Store | Persistent by design |
| Order content (idea or narration text, chapters, title, audio, AI-provider request identifiers) | Modal (USA), encrypted working storage | Until delivery is confirmed; if never delivered, the order expires after 7 days and is deleted at the next scheduled cleanup (normally within 15 minutes); sooner if you delete the book or ask us |
| Processor copies | Modal; OpenRouter and its hosts | Modal up to 7 days; OpenRouter and hosts as described in 6.3 |
| Your delivered book | Your device and private iCloud | Until you delete it |
| Receipts, permission records, hours balance, subscription notices | Modal (USA) | 7 years after the last related financial event |
| Content reports (reason, note, passage, book number, chapter, subscription identifier) | Modal (USA); our mailbox if emailed | 12 months |
| Block records | Modal (USA) | While the block lasts plus 12 months |
| Materials preserved under 18 U.S.C. § 2258A | Modal (USA) / our mailbox | 1 year after submission, or longer where the law requires |
| Deletion-request record (no content) | Modal (USA) | 2 years |
| Usage counters (anonymous) | Modal (USA) | 90 days |
| Application logs (no IP, no content) | Modal (USA) | About 1 day |
| Refusal counts (numbers only) | Modal (USA) | 30 days |
| Email correspondence | Our mailbox | Up to 24 months after the last message |

## 18. App Privacy Label

For version 1.3 our App Store privacy label and the privacy manifest in the
App disclose:

- **Data linked to you:** Identifiers — **User ID** (the subscription's
  original transaction identifier); **Purchases — Purchase History**
  (subscription status, extra hours, hours used); **User Content — Other User
  Content** (book ideas, narration text, content reports); **Location —
  Coarse Location** (the country derived from the IP address of a Service
  request, logged as a country code with the request for about one day);
  all for App Functionality.
- **Data not linked to you:** Usage Data — **Product Interaction** (the
  optional anonymous counters), for Analytics.
- **No tracking.**

The country is used only to decide each request under Section 6.7 and for
security; it is not stored with your orders or used for any other purpose.

## 19. Changes to This Policy

We will update the Effective Date and post the new version at its public
address; earlier versions are available on request. Before a material change
to how Service data is processed takes effect — for example, a new kind of
recipient not named in the permission you gave — we will show a notice in the
App and ask for your permission again where required. A switch to Amazon Web
Services, which your permission already names, will be reflected in Section
6.3 before it happens.

## 20. Contact

OWN PLACE LLC
7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net
Telephone: +1 (213) 524-8012
