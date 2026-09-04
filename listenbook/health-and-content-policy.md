# Talefall — Audiobook Player: Consumer Health Data Privacy Policy and AI Safety and Content Policy

**Effective Date: September 4, 2026**

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
(contact@ownplace.net; telephone +1 (213) 524-8012) — developer of Talefall —
Audiobook Player (the "App"; bundle identifier com.anisimov.audiobooks) and
operator of its optional AI Studio service (the "Service").

This page has two parts. **Part A** is our **Consumer Health Data Privacy
Policy**, required by Washington's My Health My Data Act, Nevada SB 370, the
Connecticut Data Privacy Act, and similar laws. **Part B** is our AI Safety
and Content Policy for AI Studio. Both are part of our [Privacy
Policy](privacy-policy.html) and [Terms of Use](terms-of-use.html); if this
page conflicts with those documents on a point they cover, this page controls
for consumer health data and AI safety. A direct link to this page appears on our home page and in the App at
Settings → Privacy.

---

# Part A — Consumer Health Data Privacy Policy

## A1. Why this policy exists

AI Studio is not a health service. Its **writing mode** is intended solely to
generate fictional entertainment from a description you type. Its
**server-based narration mode** reads aloud a text book you already own. We
do not ask for health information, and our rules — stated before every
order — require you to confirm that the order contains none.

Nevertheless, AI Studio accepts free text. Information you type into a book
request, or contained in a text you submit for narration, **may constitute
"consumer health data"** under the Washington My Health My Data Act (Chapter
19.373 RCW), Nevada SB 370, the Connecticut Data Privacy Act, and similar
laws if it reveals the past, present, or future physical or mental health
status of an identifiable person — for example, a request written around
your own diagnosis, medication, pregnancy, reproductive or sexual health,
gender-affirming care, or a mental-health condition. Such information does
not stop being consumer health data because you labelled it fiction or
because entering it breaks our rules. **This policy contains the information
those laws require** about how such data would be handled if it were
present. It applies to everyone who uses AI Studio, wherever they live.

We do not use submitted text to identify, infer, or determine any
consumer's health status; we process it only to generate or narrate the
work the user requested. Wherever you live — including Washington, Nevada,
and Connecticut — you may exercise the access, correction, and deletion
rights described in A7 and A8.

## A2. What consumer health data we may collect, and from whom

We collect consumer health data only if **you** put it in the text you send
to AI Studio, contrary to the confirmation you give before every order. There
is no other source. Specifically:

| Category | How it could arise | Linked to |
|---|---|---|
| Health information contained in a **book request** ("prompt") | You type it into the description of the book you want written | The order record and the subscription's Apple original transaction identifier |
| Health information contained in **text you submit for narration** | It is in the EPUB, FB2, PDF, or TXT you chose to have narrated in our voice | The order record and the same identifier |
| Health information contained in a **passage read aloud** on demand | It is in the passage you selected | Nothing — the passage is processed in memory and not stored |
| Health information you include in a **content report or an email** to us | You write it in a report, a support message, or a rights request | The report record or your email address |

Because these are free-text fields, the same text could in principle contain
biometric, genetic, or other sensitive information about a person; we do not
solicit it, do not look for it, and treat it exactly as described here. We do
**not** collect precise location, health data from other apps or devices
(including HealthKit), or any health information from third parties. We do
not establish geofences around health-care facilities and do not use
location data to identify or infer visits to health-care facilities.
Country- and region-level GeoIP checks are used solely for territorial and
sanctions compliance. We do **not** infer health status from your requests, your library,
your purchases, your language, or anything else, and we do **not** use
automated tools to detect or extract health information from content. The
safety controls evaluate submitted text for prohibited content categories,
including self-harm instructions. They are not used to infer or create a
record of any person's health status or to build a profile; only the
enforcement metadata described in this Policy is retained.

## A3. How we use it (purposes)

If consumer health data is present in what you send, it is used **only**:

1. to write or narrate the specific book you requested and deliver it to
   your device;
2. to operate the automated safety controls described in Part B, which
   process the text but do not extract health information;
3. to respond to you if you contact us; and
4. where the law requires it, to comply with a legal obligation or to
   establish, exercise, or defend legal claims.

The necessity on which we rely covers only the text that is objectively
needed to produce the book you ordered; it does not extend to any other use.
We do **not** use it for advertising, marketing, profiling, product
recommendations, research, model training, or any purpose unrelated to the
book you ordered. We do not sell consumer health data and never will without
the separate, signed authorization the law requires.

## A4. Who processes it (processors) and whether we "share" it

We have no affiliates. Content that could contain consumer health data is
handled by the service providers ("processors") that do the work of writing
and narrating your book, only for that purpose, on our documented
instructions. Under Washington law, disclosure to a processor bound by a
compliant contract for the purpose stated in this policy is **not "sharing"**
of consumer health data; we describe it here so that you know exactly who
receives it.

**Processors**

| Recipient | Role | Location | What it receives |
|---|---|---|---|
| **Modal Labs, Inc.** (modal.com) | Hosting; runs our service and our own narrator model in our private container; holds the temporary working storage used to produce and deliver the order | United States | The full order (request or narration text, generated chapters, audio) |
| **OpenRouter, Inc.** (openrouter.ai) | Gateway to the language model that writes fiction (writing mode only) | United States | The book request and the working text our writer program generates; no identifier added by us. Our service keeps with the order the request identifiers OpenRouter returns, so that a deletion request can be actioned; they do not directly identify you but remain linked to the order until the order is deleted |
| **The model provider reached through OpenRouter** (currently Meta Platforms, Inc.), acting as OpenRouter's subprocessor | Generates the text | United States | The same content. |

OpenRouter and Meta process writing-mode content to generate the
requested text. Requests are sent using a setting that restricts routing to
providers that state they do not use content for training or routine
retention. This is not a zero-retention guarantee; limited retention may
occur for abuse prevention, security, billing, or legal compliance. The
setting operates fail-closed: if no provider with that stated policy is
available, the order is not sent.

Writing mode currently requests `meta/muse-spark-1.2` (Muse Spark 1.2 by
Meta) through OpenRouter with `provider.data_collection="deny"`.
Server-based narration uses `VoxCPM2`, operated by OWN PLACE LLC in its
private container hosted by Modal.

Modal and OpenRouter are bound by written data-processing terms covering
confidentiality, security, documented instructions, subprocessors, rights
requests, deletion, and incident notification. Meta acts as OpenRouter's
subprocessor under OpenRouter's applicable flow-down obligations. The
narrator model is operated by OWN PLACE LLC in a private container hosted by
Modal. Narration text is processed by Modal as our infrastructure provider
but is not sent to OpenRouter, Meta, or another model provider. Passages
read aloud on demand go to our narrator only and are not stored.

**No processor is authorized by us to collect consumer health data across
unrelated websites, applications, or services.**

**Statutory "sharing."** We do **not** share consumer health data with any
third party for that party's own purposes, with affiliates (we have none),
with advertisers, or with data brokers, and we have not done so. If that ever
changed, we would first obtain the separate opt-in consent the law requires
and would list here the name and active contact details of every third party
with whom the data was shared.

**Other disclosures.** We may disclose data where legally required (for
example, in response to a valid subpoena) or as part of a merger,
acquisition, or sale of assets, subject to the notice and purpose-limitation
requirements of applicable law.

## A5. Our rule: no real people, no sensitive data — confirmed before every order

We do not ask for consent to process consumer health data, and we do not
treat any tap in the App as such consent. Our approach is prevention and
refusal:

- **The rule.** AI Studio's writing mode is intended solely to generate
  fictional entertainment. The server-based narration mode may process only
  text that you are legally entitled to submit and that does not contain
  personal or consumer health data about an identifiable real person,
  including you. Use the on-device voice for text containing such data.
- **The confirmation, before every order.** Each time you place an order the
  App shows the statement *"I confirm that this order does not contain
  information about an identifiable real person, including me, and does not
  contain health, biometric, genetic, precise-location, financial-account, or
  other sensitive personal data"* and the button **"Confirm and Continue."**
  If you instead indicate that the order does contain such information, the
  App **refuses the order**; nothing is sent to our server, and the App
  suggests the on-device voice for narration. There is no option to consent
  to processing it instead.
- **The necessity basis, if you confirm wrongly.** If, despite your
  confirmation, consumer health data is present, the only thing we do with it
  is the processing you requested: write or narrate the book and deliver it
  to you. Where inadvertently submitted consumer health data relates only to
  the person placing the order, we rely on the requested-service exception
  solely to the objectively necessary extent. We do not rely on that
  exception for consumer health data about another person. Third-party
  consumer health data is prohibited; when detected, processing stops and
  the data is deleted. When we become aware that an order contains consumer
  health data of any kind, we delete it under A7 and may refuse further
  orders.
- **The AI-provider permission is separate, mode-specific, and is not
  health-data consent.** Before your first writing-mode order, and again if
  the provider changes, the App asks you to allow content from your
  writing-mode orders to be sent to OpenRouter and Meta in the United States
  (A4, and Privacy Policy Section 6.6). Server-based narration does not
  require permission to send content to OpenRouter or Meta because it is not
  sent to them; before every narration order the App instead shows the
  upload confirmation naming our service hosted by Modal. Neither permission
  describes anything but where content goes; neither is, or is treated by us
  as, consent to process health or other sensitive data. None of these
  confirmations is a condition of using the player.

## A6. How long it is kept

The same retention rules as for every AI Studio order apply (Privacy Policy,
Section 6.4). We operate **no post-delivery server retention**:

AI Studio temporarily processes submitted text only as necessary to
generate, narrate, and deliver the order you requested, does not use it to
identify or infer anyone's health status, and deletes OWN PLACE LLC's
working copies immediately after confirmed delivery or, if delivery is not
completed, no later than seven days after the Service accepts the order.

| What | How long we keep it |
|---|---|
| Order text, generated chapters, title, and audio | Held in **temporary working storage** on Modal only while the order is being produced and delivered: encrypted, subject to an application-level time-to-live, and excluded from OWN PLACE LLC's application logs and crash reports; we do not create separate content backups. Deleted immediately after confirmed delivery of the final chapter. |
| Content of an order that is never fully delivered | Deleted no later than **seven days** after the Service accepts the order |
| Passages read aloud on demand | **Not stored** |
| Content you submit in a content report or support request | Retained separately under the report-retention period below |
| Content reports and enforcement notes | Up to 24 months after resolution |
| Emails | No longer than 24 months after the last message, deleted earlier on request |

- Delivery is confirmed only after the App has durably saved every chapter
  on the device. A successful network download is not, by itself, delivery.
- If full delivery is not confirmed within seven days after the Service
  accepts the order, we treat the order as failed, stop further processing,
  delete all server-side order content, and automatically restore all hours
  reserved or charged for that order. Chapters already saved on your device
  remain available.
- We do not retain order content after confirmed delivery, except content
  you separately submit in a report or support request and content that law
  requires us to preserve.
- OWN PLACE LLC cannot recover or re-deliver the book from its server after
  deletion; the App may still restore the user's own saved iCloud copy.
- OpenRouter and Meta: see A4; limited retention may occur there, and the
  routing setting is not a zero-retention guarantee.
- We do not create separate content backups. Processor backup copies, if
  any, expire on that processor's next
  scheduled expiration cycle and, for Washington consumer health data,
  no later than six months after an authenticated request.

## A7. Your rights

Regardless of where you live, you may:

- **Confirm and access** — ask whether we hold information associated with
  your subscription and receive a copy of the information that still exists,
  together with the processors (A4) that received order content, with their
  contact details. Because ordinary order content is deleted after delivery,
  we cannot provide content or order records that have already been deleted.
- **Correct or review** — ask us to correct inaccurate consumer health data
  we still hold or to review how it was used. Because order content is free
  text you wrote and we do not alter it, correction normally takes the form of
  deleting the order or replacing it with a new one at your request. We cannot
  correct records that have already been deleted; we will tell you what we
  did.
- **Withdraw the AI-provider permission** — in Settings → Privacy, withdraw
  the permission to send writing-mode content to our AI providers; new
  writing-mode orders stop until you grant permission again. Withdrawing
  AI-provider permission disables writing mode only. Server-based narration
  remains available subject to its separate upload confirmation. Withdrawal
  does not undo processing that already happened, but you can then delete
  the resulting books.
- **Delete** — delete a single book in the App (the App offers to delete the
  copy on this device and the copy stored through Apple's iCloud service), or use
  **Settings → Privacy → Request Data Deletion** to delete every order and
  permission record linked to your subscription. If you request deletion while an order is active, we stop further processing as soon as technically possible, delete OWN PLACE LLC's server-side working content, and restore the affected hours under Terms Section 4.2.
  We also notify OpenRouter where it may still hold a limited copy. If the order has
  already been delivered, we confirm that our server copy was deleted at
  delivery. A privacy deletion request does not delete the copy of the book
  on your device or the copy the App stores through Apple's iCloud service
  under your Apple account; OWN PLACE LLC does not access or control that
  copy. We instruct our processors to delete their
  copies and let backup copies expire as described in A6. We keep only a minimal record that the deletion
  was done (a keyed hash of the subscription identifier, the date, and what
  was deleted — no content) and any billing evidence the law requires.
  **Deleting content or consumer health data does not forfeit purchased
  extra hours.** We retain only the minimum entitlement record needed to
  preserve that balance. If you request deletion of every identifier-linked
  record and preservation is technically impossible, we will first offer a
  refund path for unused purchased extra hours or obtain your separate
  confirmation that you choose deletion and forfeiture.
- **Not be discriminated against** for exercising these rights. Exercising a
  right does not affect your player license or your subscription. Deleting
  content or consumer health data does not affect purchased extra hours. A
  separate request to erase the minimum entitlement record may make
  preservation technically impossible; before erasing it, we provide a
  refund path and obtain separate confirmation.
- **Appeal** — if we decline a request, reply to our response within 45
  days; we answer appeals in writing within 45 days and tell you how to
  contact the Washington Attorney General (or your state's) if you are not
  satisfied.

## A8. How to exercise your rights, how we verify you, and how fast we act

- **In the App (preferred):** Settings → Privacy → Request Data Deletion (or
  the access option next to it). The App authenticates the request with your
  current Apple-signed subscription transaction; nothing else is needed and no
  email is involved.
- **By email:** contact@ownplace.net, subject "Talefall: consumer health data
  request". Because we hold no name or account, email alone is not enough to
  delete or hand over content; we will ask for proof proportionate to the
  request (for example, an Apple receipt for the subscription or a signed
  transaction obtained through the App) so that a leaked identifier cannot be
  used by someone else against you.
- **By telephone:** +1 (213) 524-8012.
- **Authorized agents** may act for you with your written permission.

**Timing.** We respond to verified requests within 45 days, extendable once
by 45 days where the law allows and we tell you why. Because we operate no
post-delivery server retention, in most cases there is no server copy left
to delete. Where a copy still exists, we delete our own copies immediately
and send the processor deletion instruction the same day, for every
deletion request, wherever you live. Modal request logs expire after one
day. For Washington consumer health data, backup copies held by a processor
are deleted no later than six months after authentication.

## A9. Processors' obligations and our assessment

Modal and OpenRouter are bound by written data-processing terms covering
confidentiality, security, documented instructions, subprocessors, rights
requests, deletion, and incident notification (Modal: the Data Processing
Addendum at modal.com/legal/dpa, subprocessors at
trust.modal.com/subprocessors; OpenRouter: the data processing addendum
incorporated in its terms, subprocessors at trust.openrouter.ai). Meta acts
as OpenRouter's subprocessor under OpenRouter's applicable flow-down
obligations. OWN PLACE LLC remains responsible for its choice and use of
these processors.

Because free-text orders could contain sensitive data, we conduct and keep a
data-protection assessment of AI Studio's processing, including the
Connecticut Data Privacy Act assessment required for processing of sensitive
data, and update it when we change a processor or model provider.

## A10. Changes to this policy

We will update the Effective Date and post a new version at this address.
If a change would expand how consumer health data is collected, used, or
shared, the App will ask for your affirmative consent before the next order.

---

# Part B — AI Safety and Content Policy

## B1. Scope

This Policy governs every request submitted to AI Studio and every book it
produces. It is part of the Terms of Use (Section 5). It applies in addition
to the App's 18+ rating and the age confirmation required before the first
order.

## B2. Writing mode: fiction only. Narration mode: your own text, no personal data

AI Studio's writing mode is intended solely to generate fictional
entertainment. The server-based narration mode may process only text that
you are legally entitled to submit and that does not contain personal or
consumer health data about an identifiable real person, including you. Use
the on-device voice for text containing such data.

In writing mode your request must not describe, depict, or be about a real,
identifiable person — including you. In both modes you confirm before every
order that the order contains no information about an identifiable real
person and no health, biometric, genetic, precise-location,
financial-account, or other sensitive personal data; an order you flag as
containing such data is refused. These rules exist to protect you and
others. Because we do not routinely review submitted content, we rely on
your confirmation that it contains no prohibited personal or consumer
health data.

## B3. Prohibited uses

You may not use AI Studio to request, produce, or narrate content that:

1. **sexualizes minors** in any form, including fictional characters
   presented as minors, or that otherwise exploits or endangers children;
2. is **pornographic or graphically explicit sexual content, sexual
   services, sexual exploitation, non-consensual sexual content, or fetish
   content intended primarily for sexual arousal** — all of which are
   prohibited;
3. **threatens, incites, or glorifies violence** against real people or
   groups, or constitutes a credible threat;
4. **promotes, recruits for, or provides support to terrorism or violent
   extremism**, including extremist recruitment material;
5. **facilitates human trafficking, forced labour, or sexual exploitation**;
6. **provides instructions for or encourages self-harm, suicide, or eating
   disorders**;
7. **provides instructions that facilitate serious wrongdoing**, including
   the creation of weapons capable of mass harm, malware, or serious crimes
   against persons;
8. **harasses, bullies, or demeans** a real person, or targets people on the
   basis of a protected characteristic;
9. **impersonates or defames** a real person or organization, or presents
   invented statements as things a real person said or did;
10. **profiles, tracks, or compiles personal data** about other people, or
    contains personal or health information about identifiable people;
11. is intended to be presented as **medical, legal, financial, psychological,
    or other professional advice** without the involvement of a licensed
    professional, or as a substitute for emergency services;
12. **infringes copyright, trademark, privacy, or publicity rights**,
    including requests to reproduce or continue a specific protected work or
    to closely imitate a living author's identifiable style with intent to
    pass the result off;
13. contains **prompt-injection, malware**, or attempts to extract our system
    instructions, provider keys, or other users' content;
14. **circumvents** hours, limits, the territorial or sanctions restrictions
    in the Terms (Sections 4.9 and 7), or these safety controls; or
15. is otherwise **unlawful** where you are located or where we operate.

Ordinary adult fiction — including violence, crime, horror, strong language,
and mature themes handled as part of a story — is not prohibited by this
Policy; the App is rated 18+ for that reason. Sexual content is limited to
what item 2 allows: it may be part of a narrative, but pornographic or
graphically explicit material is prohibited. The model provider may apply its
own safeguards under its current service configuration; we do not rely on
those safeguards as a substitute for our controls, and a request may still
be declined by the provider.

## B4. Safety controls

- **Automated input controls** examine each request before it is sent to the
  language model and decline requests that match the prohibited categories
  above. A declined request consumes no hours.
- **Automated output controls** examine generated text before narration and
  stop an order whose output matches the prohibited categories; a stopped
  order is not charged.
- **Provider safeguards.** The model provider may apply its own safeguards
  under its current service configuration; we do not rely on those
  safeguards as a substitute for our controls.
- **No human pre-review.** Nobody at OWN PLACE LLC reads requests or books
  before they reach you. Authorized personnel may review specific content
  only when you request support, report content, submit a legal complaint,
  or when reasonably necessary to investigate abuse, security incidents, or
  comply with law.
- **No profiling.** Safety controls make a decision about a request; they do
  not build a record of you. Only the enforcement notes in B6 are kept.

These controls are imperfect. They can decline a harmless request and can
miss a harmful one; that is why you must review generated content before
relying on it or sharing it, and why the report path below exists.

## B5. Reporting content

If a generated book contains something unsafe or unlawful:

- open the book menu in the App and tap **Report content**. Report content
  submits the report directly through the App to our service, with the book
  identifier, the App version, the category you choose, and what you add. If
  submission fails, the App offers email to contact@ownplace.net as a
  fallback method. A content report may include the excerpt or chapter you choose to
  submit for review; reported content is retained separately under the
  report-retention period.
- Anyone may also report — including people who are not users — by email to
  contact@ownplace.net with the subject "Talefall: content report" and,
  where known, the book identifier.

We acknowledge reports through the available reporting channel and promptly
prioritize reports alleging child exploitation, credible threats, or imminent
harm. Other reports are reviewed as resources permit.
We tell the reporter the outcome where we lawfully can. Where a report shows
that content still held on our servers is unlawful, we restrict access to
that content immediately — delivery is withheld and the order is stopped if
still running — pending review.

**Child sexual exploitation.** When we obtain actual knowledge of apparent
child sexual abuse material or child sexual exploitation involving the
Service, we report it to the National Center for Missing & Exploited Children
(NCMEC) CyberTipline as soon as reasonably possible, preserve the material
and related records as required by 18 U.S.C. § 2258A, and cooperate with law
enforcement. Such reports are handled before any other report.

## B6. Enforcement

Depending on severity and history, we may:

- refuse or cancel the order and remove or withhold the server copy of the
  book, immediately where the content appears unlawful;
- restrict the subscription identifier to a lower daily limit;
- **block the subscription identifier** from placing further AI Studio orders,
  for serious or repeated violations; or
- report the matter to law enforcement or NCMEC where required.

Enforcement applies to the AI Studio subscription only. Your separately
purchased player license and the books already on your device are not
affected, and a deletion request under the Privacy Policy is still honoured.
For each enforcement action we keep a note (book identifier, date, reason
category, restriction) for up to 24 months, or longer only for legal claims.
Blocking for a violation does not entitle you to a refund from us for hours
already used, without prejudice to any refund Apple grants or that applicable
law requires.

## B7. Appeals

If your order was declined by a safety control, or your subscription
identifier was restricted or blocked, and you believe this was wrong, email
contact@ownplace.net with the subject "Talefall: appeal" within **30 days**,
including the book identifier or the date of the restriction and why you
think the decision was mistaken. A person will review the decision and answer
in writing within **30 days**. If a decision was mistaken, we restore access
and any hours affected.

## B8. Accuracy and reliance

Writing-mode output is intended as fictional entertainment and may be
inaccurate or fabricated. Server-based narration reproduces the text you
submit and may be fiction or non-fiction. Writing-mode text is produced by a
statistical model and may be inaccurate, invented, or biased even when it
sounds confident. Do not rely on it for factual accuracy and never as medical, legal, financial, or other
professional advice. If you are in crisis, contact local emergency services
or a crisis line; AI Studio cannot help you.

## B9. Contact

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net · Telephone: +1 (213) 524-8012
