# Terms of Use for Talefall — Audiobook Player

**Effective Date: October 14, 2026**

<!-- ДАТА РЕДАКЦИИ: 14 октября 2026 — черновик; при публикации заменить на фактический день публикации (во всех 9 файлах). -->

These Terms of Use ("Terms") form a legal agreement between you ("you") and
OWN PLACE LLC ("we," "us," or "our"), a Washington limited liability company,
7707 NE 141st St, Kirkland, WA 98034-5321, USA (contact@ownplace.net;
telephone +1 (213) 524-8012). They govern your use of the Talefall — Audiobook
Player application (the "App"; bundle identifier com.anisimov.audiobooks) and
of the server features that come with the **Talefall Subscription** (the
"Service"), described in Section 1.

**How you accept these Terms.** By downloading, installing, or using the App
you agree to these Terms as they apply to the player. Before you first use the
Service, the App shows a screen titled "Before You Create" with the switch
"I'm 18 or older and agree to the Terms of Use and Privacy Policy"; the App
does not send a book order or a narration request to the Service until you
have turned that switch on and tapped "Continue." If you do not agree, do not
use the App or the Service.

Related documents, which form part of these Terms: our [Privacy
Policy](privacy-policy.html), our [Consumer Health Data Privacy
Policy](consumer-health-data-privacy-policy.html), our [AI Safety and Content
Policy](ai-safety-and-content-policy.html), and the list of [Supported
Territories](ai-studio-territories.html).

## 1. The App and the Service

**The App** is an iOS audiobook player and reader. You can import your own
audio files and text books, listen and read with saved positions, speed
control, a sleep timer, bookmarks, highlights and notes, turn an audiobook
into text with on-device speech recognition, read a text aloud with an
on-device Apple voice, and browse built-in catalogs of works identified by
their providers as public-domain or otherwise lawfully available. The App has
no user accounts and does not upload your library. A short sample audiobook
is bundled with the App and plays without a network connection; its text was
written with the help of an AI model.

**The Service** requires an active Talefall Subscription for new orders and new requests that use hours. Expiry does not prevent delivery or management of an existing paid order, as described in Section 8. The territorial restrictions in Section 4.9 continue to apply. It has two server features,
reached from the App's **Create** tab:

- **Book from an Idea** — you describe an idea and choose a book type (Story,
  Explainer, or How-to), a language, and a length. Our service writes the text
  with a third-party large language model and narrates it with our own
  narrator model.
- **Narrate My Text in the Talefall voice** — our narrator model reads aloud a
  text book you already have, either as a whole book or passage by passage
  while you listen.

The finished book is delivered to the App. Narrating with the on-device Apple
voice and on-device transcription do not use the Service.

## 2. License; Age Requirement

Subject to these Terms, we grant you a limited, personal, non-exclusive,
non-transferable, revocable license to use the App on Apple-branded devices
you own or control, as permitted by the Apple Media Services Terms and
Conditions. Your use of the App is also governed by **Apple's standard
Licensed Application End User License Agreement** ("Apple Standard EULA"),
https://www.apple.com/legal/internet-services/itunes/dev/stdeula/. If these
Terms conflict with Apple's required minimum terms, the Apple Standard EULA
controls.

**Age.** The App is rated **18+** on the App Store because the Service can
produce text and narration that no person reviews before it reaches you. You
must be at least **18 years old, or the age of majority where you live if
that is higher**, to use the App and the Service. The "Before You Create"
screen asks you to state that you are 18 or older; this is a self-declaration,
not age verification, and we do not collect proof of age. If you are under
that age, do not use the App.

## 3. The Player: Trial, One-Time Purchase, or Subscription

- The App is free to download and includes a **3-day free trial** of the
  player. You are **not charged automatically** when the trial ends. Earlier
  versions of the App offered a 14-day trial; from version 1.3, a trial in
  progress ends 3 days after it started. This does not limit any right you
  have under applicable law.
- After the trial, listening and reading in the player require either the
  **one-time player purchase** (non-consumable, product
  `com.anisimov.audiobooks.pro`) or an **active Talefall Subscription**,
  which includes the player while it is active. Without either, your
  library, your book orders, and Export to Files remain available, and the
  App offers the purchase when you start listening or reading.
- The one-time purchase is not a subscription and has no recurring charge.
  If you bought it, the player stays available to you whether or not you
  subscribe, subject to technical compatibility, the Apple Standard EULA, and
  applicable law.
- The trial start date is stored in the iOS Keychain and the iCloud
  Key-Value Store so that reinstalling does not restart the trial.
- Prices are the localized prices Apple shows immediately before purchase;
  any price on our website is an example and may be out of date.

## 4. The Talefall Subscription: Hours, Extra Hours, and Cancellation

**4.1 Subscription.** Placing new orders and making new requests that use hours requires an **auto-renewable monthly
subscription** bought through Apple (product
`com.anisimov.audiobooks.generation.monthly`, shown in the App as "Talefall
Subscription"). Payment is charged to your Apple Account when you confirm the
purchase. The subscription **renews automatically** each month at the same
price unless you turn off auto-renewal at least 24 hours before the end of the
current period; renewal is charged within 24 hours before the period ends.
Manage or cancel it in iOS Settings → Apple Account → Subscriptions.
Cancellation takes effect at the end of the current paid period. Except where
required by law, cancellation does not give a prorated refund for a period in
which the Service was available as promised; this does not limit remedies for
a non-conforming or undelivered service.

**4.2 Monthly hours and how they are used.** Each subscription month includes
**5 hours of new audio** ("hours"). Listening never uses hours; only creating
new audio does. Before an order starts, the Service checks that the length you
selected fits your remaining hours; if it does not, the order is refused
before any work is done. **Hours are deducted after narration for the actual
length of the finished audio**, which may be somewhat shorter or longer than
the length you selected, but never by more than the balance you had when the
order was accepted. Unused monthly hours **expire at renewal**
and do not carry over. The month follows your subscription's renewal date.

**Delivery and restoration of hours.** A chapter is *delivered* when the App
confirms to our server that it has saved the chapter, or when our server has
sent the chapter's complete audio file (every byte of the size our server
declared for that file) in response to a request made with the subscription
that placed the order. If any chapter of an order has not been delivered when
the order ends — whether it failed, was stopped (for example, by our output
moderation, Section 5.4), was cancelled or deleted by you, or expired (Section
8) — all hours reserved or charged for the order are restored automatically,
including the hours for chapters that were delivered. If every chapter was
delivered, cancelling or deleting the order, its expiry, or the end of your
subscription does not by itself restore any hours. Automatic restoration depends only on whether every chapter was delivered
under this rule; a complete transfer or a saved confirmation does not by
itself show that the file is playable or materially what you ordered. If a
delivered file cannot be played or is materially not what you ordered, write
to contact@ownplace.net with the book number shown in the App, and we will
restore the hours after checking. Hours restored after the month from which
they were taken has ended are credited to your extra-hours balance (Section
4.3). Restoring hours is a credit to your hours balance, not a refund of money
by Apple, and it does not limit any refund or remedy you may have under
Section 4.5 or applicable law.

**4.3 Extra hours.** With an active subscription you may buy an **extra-hours
pack** (consumable product `com.anisimov.audiobooks.hours5`, **5 hours**).
Extra hours are used after the monthly hours and **do not expire at renewal**.
Apple may charge your Apple Account when it approves the purchase; we credit
the hours after our server verifies the signed Apple transaction, never twice
for the same transaction. If verification is temporarily unavailable, the App
retries automatically. If the hours are not credited within 24 hours, contact
contact@ownplace.net and we will restore the credit or help you request a
refund from Apple. If your subscription lapses, unused extra hours become
unavailable but stay recorded and return if the same subscription is
reactivated. Extra hours cannot be transferred to another subscription or
Apple Account. If we permanently discontinue the Service, Section 8 applies.
Deleting your content or data does not forfeit unused purchased extra hours
without your confirmation. We retain records needed to preserve that balance
and other records described in Sections 6.2, 6.4, and 10 of the Privacy
Policy, subject to the retention periods and deletion rights stated there. If
you ask us to delete records needed to preserve that balance, we will first
offer a refund path or ask you to confirm the forfeiture.

**4.4 Service limits.** To protect the Service from abuse and runaway costs we
apply technical limits in addition to your hours: book length from 15 minutes
to 5 hours, size limits on submitted text, and daily ceilings on the number of
orders and the total audio the Service produces across all users. A request
refused because of a limit uses no hours.

**4.5 Refunds and billing.** **All purchases are processed by Apple.** We do
not receive your payment details or Apple Account credentials. For charges,
receipts, and refunds, contact Apple (https://support.apple.com/billing,
https://reportaproblem.apple.com); Apple decides refunds under its policies.
Nothing in these Terms limits a refund or remedy you are entitled to under
applicable law. If Apple refunds or revokes a subscription, Apple notifies our
server and the Service stops accepting new requests under it. Books already on
your device are not removed.

**4.6 Restore Purchases.** "Restore Purchases" uses the Apple Account of the
original purchase. If a completed purchase is still not recognized, contact
contact@ownplace.net.

**4.7 Price changes.** Apple notifies you of a subscription price increase in
advance and, where required, asks for your consent.

**4.8 Test purchases.** Purchases in Apple's sandbox or in TestFlight builds
are for testing only and give no rights to the production Service.

**4.9 Where the Service is available.** The App is not distributed on App
Store storefronts in the European Economic Area, the United Kingdom, or
Switzerland. The Service, its subscription, and extra-hours purchases are
offered only to persons physically located in a country or region listed at
https://ownplace.net/talefall/ai-studio-territories (a "Supported
Territory"). Our server checks the country of each Service request from the
request's IP address and refuses requests from outside the Supported
Territories, from countries and regions subject to comprehensive U.S.
sanctions, and when the country cannot be determined. Purchases also depend
on the App Store storefront offering the product. A refused request uses no
hours. Do not use a VPN, another person's Apple Account, or any other means
to get around this check. An existing subscription may continue to renew
while you are outside a Supported Territory unless you cancel it; unused
monthly hours still expire, while extra hours stay recorded. The player and
the books already on your device keep working everywhere. If we remove the
territory in which you bought and normally use the subscription, we will
explain how to cancel and help you request an Apple refund for a materially
unusable paid period. The list may change when required by law, a provider
restriction, or an App Store requirement; we will give advance notice where
reasonably practicable. Requests to exercise privacy rights, withdrawals of
permission, and content reports are accepted from anywhere.

**4.10 No reduction of what you already paid for.** We will not reduce the
hours or other material benefits already purchased for the current period.
Material adverse changes apply only to later periods after reasonable advance
notice.

## 5. AI-Generated Content

**5.1 How book creation works.** When you order a book, your idea, the book
type, language, and length are sent to our service on Modal. Our server first
checks the idea with automated filters (Section 5.4). It then writes the
book with third-party large language models.

Book writing uses third-party AI models from the AI providers named in your
AI-provider permission. The current recipients, routes, countries, retention,
caching and human access are listed in the registry in Privacy Policy Section
6.3.3.

Under the current permission (version 2026-10-14.1), models, and the
selection among the providers on its closed list, may change within the
safeguards that permission states (Privacy Policy, Section 6.3.2) without
asking you again. Sending content to an unlisted recipient, or broadening its
purposes, human access or retention, requires renewed explicit permission
(Privacy Policy, Section 6.6). Changes to a provider's terms do not
automatically expand your permission. Availability of a model in
a provider's catalogue does not by itself make it authorized. Accepting these
Terms does not replace that permission and does not authorize processing of
consumer health data or other sensitive personal data.

**Earlier permissions keep their promises.** For orders placed under the
earlier permission versions, the earlier promises continue to apply
unchanged: under 2026-10-08, only the GLM model through OpenRouter; under
2026-10-10.2, only OpenRouter routes to zero-data-retention endpoints of
hosting providers that OpenRouter lists as headquartered in the United States
(including Microsoft Azure only while that route is switched on and
classified as zero data retention), or Amazon Bedrock in AWS Regions in the
United States with flagged content kept for no more than 30 days, if that
route is enabled; under 2026-10-13.1, only routes that met that permission's
conditions, today GPT-6.1 Sol and GPT-6 Luna on Microsoft Azure (Privacy
Policy, Section 6.3.5). The conditions of permission 2026-10-14.1 apply only if you accept
that permission in the App.

Providers' own abuse-monitoring and acceptable-use rules apply to the
requests (AI Safety and Content Policy, B4). Each chapter is then
checked by our output moderation (Section 5.4), narrated by our own narrator
model running on Modal, and delivered to the App. OWN PLACE LLC does not
routinely conduct human pre-review of orders or books. Under the current
permission, authorized staff or contractors of an AI provider may access
content only for the service, support, security, abuse prevention and legal
compliance. OpenRouter also permits access by personnel performing its routing service in accordance with its agreement, as described in Privacy Policy Sections 6.3.2–6.3.3.
Limited human access and provider safeguards are described in Privacy Policy
Section 6.3.

**5.2 What you confirm before using the Service.**

1. *Terms and age* — once, before your first book order or server narration:
   the "Before You Create" screen described above. The App records on your
   device the version of the Terms you accepted (currently 2026-10-14.1,
   this edition of October 14, 2026), the time, and your 18+ statement.
   Updated versions of the App ask you to accept this edition before your
   next use of the Service. Older versions that hold the acceptance of an
   earlier edition and an earlier permission send book orders only on the
   routes that permission named (Privacy Policy, Section 6.3.5); this edition
   does not change them.
2. *Permission to send book orders to the AI providers* — before your first
   book order, and again when renewed permission is required (Privacy Policy,
   Section 6.6). The screen asks **"Allow AI processing of your book
   orders?"** and states: **"Send your ideas, settings and text to the AI providers below to create books? No model training, no sale, no advertising. Only for the service, support, security, abuse prevention and law, including OpenRouter's anonymous topic classification. Processing and authorized staff or contractor access may occur in several countries; we don't choose recipients or routes in China or other countries of concern under US law; provider information we checked names none there but is incomplete. Retention varies; no single maximum. Fiction only: no real personal or health data. Withdraw in Settings."**
   Under the heading **"AI providers"** it lists: **"OpenRouter (AI request routing)"**, **"Amazon Web Services (Amazon Bedrock)"**, **"Microsoft (Azure, Foundry)"**, **"Google (Vertex AI, Gemini API)"**, **"OpenAI"**, **"Anthropic"**, **"Mistral AI"**, **"xAI"**, **"Independent model hosts: Sail Research, Together AI, Fireworks AI, DeepInfra, Baseten"**. The link **"AI providers, countries &
   retention"** opens the recipients registry in Privacy Policy Section 6.3
   before you decide. The buttons are **"Allow AI Processing"** and **"Not
   Now"**. Below the buttons the screen states: **"“Not Now” sends no order content to AI providers. The player and server-based narration remain available."**
   In Settings, the permission switch is explained: **"Your ideas, book settings and working text are sent to the AI providers listed in the Privacy Policy to write your books. No model training. You can turn this permission off."**
   This is permission version 2026-10-14.1. Permissions of the earlier
   versions 2026-10-08, 2026-10-10.2 and 2026-10-13.1 are used only for the
   routes those versions named (Privacy Policy, Section 6.3.5). Updated versions of the
   App ask again with the current text before your next book order; until
   then, older versions use only those earlier routes.
   You can withdraw it at any time in Settings; further transfers to the AI
   providers then stop, including further AI calls for orders in progress,
   and new book orders stop until you allow it again.
3. *No personal data — before every book order.* The order form shows the
   switch **"My idea contains no personal data about real people"**; the
   order cannot be sent until it is on, and it covers the exact text of your
   idea, so editing the idea requires confirming again.
4. *Narration in the Talefall voice.* For a book created from your idea, the
   App reuses the confirmation given when you placed that order for narration
   of the resulting book; it does not ask you to confirm again. For another
   book without that confirmation, before its first narration in the Talefall
   voice you confirm "This text has no real person's information." With the
   on-device Apple voice, the text never leaves your device.

None of these screens is, or is treated by us as, consent to process health
or other sensitive data (see the Consumer Health Data Privacy Policy).

**5.3 Your requests.** You are responsible for what you submit. **Do not
include personal data about real people — including yourself — in an idea or
in a text you send for narration:** no real person's name together with their
circumstances, no contact details, addresses, or account numbers, and no
health, sexual orientation, gender identity, beliefs, finances, criminal
record, or other sensitive details about you or anyone else. Calling a request
"fiction" or changing a name does not make such details anonymous. Stories
must be fiction. Explainers and How-to guides may cover general topics, such
as science, history, or a skill, but not a private individual. In addition,
you must not submit requests or text that:

(a) sexualize minors, or are pornographic or graphically explicit sexual
content (mature themes within adult fiction are allowed within the limits of
the AI Safety and Content Policy);
(b) make credible threats, incite or glorify violence against real people or
groups, promote terrorism or violent extremism, or attack people for a
protected characteristic;
(c) seek instructions for weapons capable of mass harm, for self-harm or
suicide, or for other serious wrongdoing;
(d) harass, defame, or impersonate a real person or organization;
(e) infringe copyright, trademark, privacy, or publicity rights, including
requests to reproduce or continue a specific protected work;
(f) seek medical, legal, financial, or other professional advice, or are
meant to be presented as such advice;
(g) contain malware or prompt-injection, or try to extract our instructions,
keys, or other users' data; or
(h) try to get around hours, limits, territorial restrictions, or safety
controls.

The full rules are in the [AI Safety and Content
Policy](ai-safety-and-content-policy.html).

**5.4 Safety controls.** Our server applies automated controls; they reduce
risk but are not perfect, and the prohibitions apply equally to anything they
miss.

- **Personal-data check (book ideas).** Before a book idea is sent to an AI
  provider, our server checks it for personal and sensitive data patterns,
  such as email addresses, phone numbers, government or payment-card numbers,
  passwords, or a statement about your own or a named close person's health,
  sexuality, gender identity, or criminal record. A match is refused, uses no
  hours, and the App asks you to rewrite the idea. In versions of the App
  using permission 2026-10-14.1, text you send for narration in the Talefall
  voice is checked by the same filter before it is narrated; in every version
  your per-book confirmation (Section 5.2) and the rule in Section 5.3 apply
  to it.
- **Prohibited-content check (ideas and narration text).** Before anything is
  sent to an AI provider or the narrator, our server refuses requests that
  clearly seek sexual content involving minors, instructions for weapons of
  mass destruction, or encouragement of suicide. A refused request uses no
  hours.
- **Output moderation.** Before narration and delivery, each generated chapter
  is checked by an open-source safety classifier model that we run on our own
  infrastructure at Modal (it does not send the text to anyone else), for
  sexual content (especially involving minors), hate, dangerous instructions,
  and personal data about real people. A chapter that fails is not narrated or
  delivered; the order is stopped and the hours for it are restored.
- **No human pre-review.** Nobody at OWN PLACE LLC reads orders or books before
  they reach you. Specific content may be read only when you contact support,
  report content, or submit a legal complaint, or when reasonably necessary to
  investigate abuse or a security incident or to comply with law.

**5.5 Reporting and enforcement.** Use **Report content** in the book's menu
to report a generated book. The report is sent from the App to our service; if
sending fails, the App offers to email the report to contact@ownplace.net
instead. Anyone, including non-users, may report by email. We review reports
promptly and give priority to child safety, credible threats, and imminent
harm. When we obtain actual knowledge of apparent child sexual exploitation
that triggers 18 U.S.C. § 2258A, we report it to NCMEC as required. For
serious or repeated violations we may refuse orders and **block the
subscription** from the Service. A blocked subscriber may ask for review by
emailing contact@ownplace.net within 30 days; a person will review the
decision and answer within 30 days. A block affects only the Service, not the
player or books already on your device. A block for a violation does not
entitle you to a refund from us for hours already used, without prejudice to
a refund Apple grants or the law requires. This does not affect restoration of
hours under Section 4.2. Details are in the AI Safety and
Content Policy.

**5.6 No guarantees about the output.** AI-generated text may be
**inaccurate, incomplete, repetitive, biased, offensive, or otherwise
unsuitable**, may differ from what you asked for, and may resemble existing
works; narration may mispronounce words. Explainers and How-to guides are
AI-generated overviews without source checking. **Do not rely on generated
content for facts, and never as medical, legal, financial, or other
professional advice.** Review content before relying on it or sharing it.

**5.7 Ownership.** As between you and us, we assign to you whatever rights we
may lawfully hold in the generated text and the delivered narration of your
book, excluding our software, models, prompts, narrator voice, trademarks, and
other underlying technology, and you may use the book for any lawful purpose.
We claim no ownership of your requests. **We do not promise that the output is
copyrightable, unique, or non-infringing**; similar text may be generated for
others. You may not use delivered narration to train or clone a voice model.

**5.8 Our license to your content.** You grant us a non-exclusive, worldwide,
royalty-free license to store, copy, process, transmit, and narrate your
requests, the text you submit for narration, and the generated book, solely
to provide the Service to you, to run the safety controls, to handle reports,
to enforce these Terms, and as required by law. For book-writing requests
routed through OpenRouter, and only where your applicable AI-provider
permission expressly covers it (permission 2026-10-14.1 does), this license
includes allowing OpenRouter to use your requests in anonymized form solely
to classify them by topic for its usage reporting and model rankings, as
OpenRouter's terms (Section 6.5) describe; you confirm that you have the
rights needed for that use (compare OpenRouter's terms, Section 6.6). We do
not grant OpenRouter any other license to your content (Privacy Policy,
Section 6.3). We do not use your content
to train models or for advertising.

**5.9 Text you submit for narration.** You represent that you own the text or
have the right to have it narrated for your personal use and that it contains
no personal data about real people (Section 5.3). The text is processed by our
own narrator model on Modal and is not sent to OpenRouter, its hosting
providers (including Microsoft), Amazon Web Services, or any other model
provider.

## 6. User Content, Copyright, and Complaints

You are responsible for the files and text you import, upload, submit, and
play, and for having the right to do so. Do not use the App or the Service
for pirated or otherwise unlawful material. Catalog works are identified as
public-domain or lawfully available by their providers (LibriVox, the
Internet Archive, Project Gutenberg); we do not guarantee their status in
every country, and you are responsible for confirming that your use is
lawful where you are.

**Copyright complaints.** If you believe material processed by the Service or
accessible through the App infringes your copyright, write to: Pavel Anisimov,
Member, OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA;
contact@ownplace.net; +1 (213) 524-8012. Identify the work, the material at
issue and how to locate it, your contact details, and why you believe the use
is unauthorized. We may stop an order, remove material we still hold, or
restrict the subscription of repeat infringers. Because the Service deletes a
book from our server once the App confirms that it has saved every chapter,
the material may no longer be held by us. This is a voluntary channel; we have not designated an agent with the
U.S. Copyright Office under 17 U.S.C. § 512(c)(2). Complaints about a
catalog work should normally go to the service that hosts it.

## 7. Acceptable Use; Export and Sanctions

You agree not to: use the App or the Service unlawfully or against these
Terms; reverse-engineer the App except as the law permits; extract the App's
service token, forge or replay Apple transactions, or access the Service other
than through the unmodified App; interfere with the App or the Service;
misuse the local Wi-Fi upload feature; resell or share your subscription or
its hours, or place orders by automation; or get around the territorial
restrictions in Section 4.9.

**Export and sanctions.** You may not use the Service in violation of U.S.
export-control or sanctions laws. You may not buy or use the Service if you
are a blocked or sanctioned person, are acting for one, or are located in a
country or region subject to comprehensive U.S. sanctions (including Cuba,
Iran, North Korea, and the Crimea, so-called Donetsk People's Republic, and
so-called Luhansk People's Republic regions of Ukraine). Other countries and
regions, such as Syria and Russia, are also outside the Supported Territories
as a service restriction, and targeted sanctions and export controls apply
everywhere. Our
country check (Section 4.9) is a territorial control and does not by itself
establish that you are eligible under sanctions law.

**Wi-Fi upload.** The Wi-Fi upload feature runs a temporary web server on
your device that uses a session token over unencrypted HTTP on your local
network. Use it only on a trusted private network and turn it off when done.

## 8. Availability, Server Storage, and Termination of the Service

The Service is provided on a **best-effort** basis and depends on third-party
providers and cloud infrastructure we do not control. We do not guarantee that
it is always available or that an order completes within a particular time.

**Server storage.** While an order is being produced and delivered, its text
and audio are held on Modal as temporary, encrypted working storage.
**We delete our server copy of the text and audio as soon as the App confirms
that it has saved every chapter on your device.** Cancellation, a deletion
request, and expiry also cause that copy to be deleted without this
confirmation. Once our server copy is deleted, **we cannot restore or
re-deliver the book.** Restoration of hours follows Section 4.2: a chapter can
count as delivered through a complete transfer from our server even without
the App's saved confirmation.
An order for which the App has not confirmed saving every chapter within
**seven days** after the Service accepted it expires: at the next scheduled
cleanup, normally within 15 minutes, we stop processing and delete all order
content from our working storage (a cleanup that fails is retried). Hours for
an expired order are restored only as Section 4.2 provides, that is, if any
chapter was not delivered; chapters already saved on your device remain. We keep a receipt for each order
(times, length, hours charged, and the records described in the Privacy
Policy) but not its content. Exceptions: content you submit in a report or support request, and content the law requires us to preserve. Copies kept by our service providers (for example, Modal's infrastructure copies for up to seven days, or content flagged by a provider's abuse monitoring) follow the periods described in the Privacy Policy.

**Subscription expiry and existing orders.** A book ordered and paid for with
hours while your subscription was active remains available for delivery after
the subscription expires, provided the subscription has not been refunded or
revoked. You can still view the order list, download the book, confirm
delivery, and delete or cancel the order using the same subscription. Expiry
alone does not cancel the order or restore its hours. New orders and new
requests that use hours require an active subscription. The existing seven-day
delivery deadline and the rules for deletion and restoration of hours continue
to apply; expiry does not restart that deadline. Listening and reading in the
App remain subject to the player access requirements.

**Your copy.** As chapters arrive, the App saves them on your device and, if
iCloud is available and the save succeeds, also in your private iCloud storage,
which we cannot access. If iCloud is unavailable or full, use Export to Files
before deleting the App. Your saved copy and Export to Files do not depend on
an active subscription; listening to or reading it in the App requires the
player purchase or an active subscription (Section 3).

**Availability of book writing.** Under permission 2026-10-14.1 we write
books only through AI providers whose published terms meet that permission's
conditions (Privacy Policy, Section 6.3.2). When no such provider is open,
book writing may be temporarily unavailable: the App says so, the order is not
accepted, no hours are used, and the order is not sent to another provider
instead. If the route of an accepted order closes while the book is being
written, or you withdraw the permission, the order is stopped and its hours
are restored under Section 4.2. Narration and the player are not affected.
Today, books under permission 2026-10-14.1 are written by the GPT-6.1 Sol model (developed by OpenAI) reached through OpenRouter, run by OpenAI; when that route is unavailable or switched off, the same model on Microsoft Azure (United States endpoint) or on Amazon Bedrock (United States endpoint used by OpenRouter), or the GPT-6 Luna model on Microsoft Azure — each order keeps the route assigned when it was accepted. The GLM route is not used under it. Earlier permissions continue on the routes they named.

**Changes and discontinuation.** We may change the Service — including the
models, providers, narrator voice, length limits, and the hours included in
future periods — subject to Section 4.10. If we discontinue the Service, we
will give notice in the App and on our website at least 30 days in advance
where practicable, stop charging renewals, give a reasonable period to use
remaining hours, and, where that is impossible, help affected users request an
appropriate refund through Apple. Books already on your device stay there
(Section 3 governs playback in the App).

**Suspension and termination.** We may suspend or end your access to the
Service if we reasonably believe you violated Sections 4.9, 5, 6, or 7. This
does not end your separately purchased player license. Sections 4.2–4.3 (as to
recorded hours), 5.6–5.8, 6, and 10–15 survive termination.

## 9. Third-Party Services

The App connects to third-party services you choose to use (Apple, LibriVox,
the Internet Archive, Project Gutenberg). The Service relies on Modal Labs,
Inc. (hosting) and the AI providers named in your AI-provider permission:
OpenRouter, Inc. and the model providers it routes to (today Microsoft
Corporation through Microsoft Azure for the current permission, and GLM
hosting providers for earlier permissions), Amazon Web Services, Inc. (Amazon
Bedrock), Google LLC (Google Cloud, Vertex AI), Anthropic, PBC, and OpenAI
OpCo, LLC, of which only those marked as used in the registry in Privacy
Policy Section 6.3.3 receive orders.
Those services operate under their own terms; we remain responsible for our
choice and use of them but do not guarantee their availability.

## 10. Disclaimer of Warranties

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE APP, THE SERVICE, AND
ALL GENERATED CONTENT ARE PROVIDED "AS IS" AND "AS AVAILABLE," WITHOUT
WARRANTY OF ANY KIND, AND WE DISCLAIM ALL IMPLIED WARRANTIES, INCLUDING
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, NON-INFRINGEMENT,
AND ACCURACY. WE DO NOT WARRANT THAT THE APP OR THE SERVICE WILL BE
UNINTERRUPTED OR ERROR-FREE, OR THAT GENERATED CONTENT WILL BE ACCURATE,
ORIGINAL, OR SUITABLE FOR ANY PURPOSE. THIS SECTION DOES NOT LIMIT THE
STATUTORY REMEDIES REFERRED TO IN SECTIONS 4.1, 4.5, AND 11.

## 11. Limitation of Liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, OWN PLACE LLC AND ITS
MEMBERS AND CONTRACTORS WILL NOT BE LIABLE FOR ANY INDIRECT, INCIDENTAL,
SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES, OR FOR LOSS OF DATA, PROFITS, OR
CONTENT (INCLUDING GENERATED BOOKS), ARISING OUT OF THE APP, THE SERVICE, OR
GENERATED CONTENT. OUR TOTAL LIABILITY FOR ALL CLAIMS WILL NOT EXCEED THE
GREATER OF (A) THE AMOUNTS YOU PAID THROUGH APPLE FOR THE APP AND THE SERVICE
IN THE TWELVE MONTHS BEFORE THE EVENT GIVING RISE TO THE CLAIM, OR (B) USD $50.

**These limits do not apply to liability that cannot lawfully be limited,
including for fraud, willful misconduct, gross negligence where non-waivable,
death or personal injury caused by negligence, or violation of non-waivable
privacy or consumer rights.** Some jurisdictions do not allow certain
limitations, so some of the above may not apply to you. We cannot restore
deleted local files; keep your own backups.

## 12. Indemnification

To the extent permitted by law, you will indemnify OWN PLACE LLC against a
third-party claim directly caused by your knowing unlawful commercial use of
submitted or generated content or your material breach of Sections 5–7. We
will promptly notify you and allow reasonable participation in the defense.
This does not require you to indemnify us for our own negligence, misconduct,
or legal violations.

## 13. Governing Law and Venue

These Terms are governed by the laws of the **State of Washington, USA**,
without regard to conflict-of-laws rules. Disputes go to the state and federal
courts located in Washington, except where consumer-protection law lets you
bring a claim where you live. Before filing a claim, please email
contact@ownplace.net; most issues can be resolved informally within 30 days.

## 14. Apple as Third-Party Beneficiary

These Terms are between you and OWN PLACE LLC only, not Apple. OWN PLACE LLC,
not Apple, is solely responsible for the App, the Service, and their content,
maintenance, support, and any claims relating to them (including
product-liability, consumer-protection, and intellectual-property claims).
Apple has no obligation to provide maintenance or support. Apple and its
subsidiaries are **third-party beneficiaries** of these Terms and may enforce
them against you. If the App fails to conform to an applicable warranty, you
may notify Apple, and Apple will refund the App's purchase price; to the
maximum extent permitted by law, Apple has no other warranty obligation for
the App.

## 15. Changes to These Terms; General

**Changes.** We may update these Terms. We will change the Effective Date and
post the new version at its public address; earlier versions are available on
request. Where a change materially expands data processing or your
obligations, or where the law requires it, the App asks you to accept the new
version before your next use of the Service; this edition (version
2026-10-14.1) is such a change. A new edition of these Terms does not by
itself expand your AI-provider permission: a recipient not named in it, or a
wider scope of processing, requires renewed explicit permission (Section
5.2; Privacy Policy, Section 6.6). The conditions of permission
2026-10-14.1 apply only if you accept that permission in the App and only to
orders placed under it; orders placed under an earlier permission keep its
promises, and nothing applies retroactively. Material changes do not reduce
benefits already purchased for the current period.

**Notices.** We may give notices in the App or on our website; notices to us
go to contact@ownplace.net or 7707 NE 141st St, Kirkland, WA 98034-5321, USA.

**Assignment; waiver; force majeure.** We may assign these Terms in a merger,
reorganization, or sale of the Service, subject to applicable law. You may not
assign them. Not enforcing a provision is not a waiver. Neither party is
liable for delay caused by events beyond its reasonable control; this does
not excuse refunds or other non-waivable consumer remedies.

**Language.** These Terms are written in English. If a translation conflicts
with the English version, the English version controls, without limiting
mandatory consumer rights where you live.

**Entire agreement.** These Terms, the Privacy Policy, the Consumer Health
Data Privacy Policy, the AI Safety and Content Policy, and the Apple Standard
EULA are the entire agreement between you and us about the App and the
Service. If any provision is unenforceable, the rest remain in effect.

## 16. Contact

OWN PLACE LLC
7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net
Telephone: +1 (213) 524-8012
