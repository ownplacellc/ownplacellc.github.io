# Talefall — Audiobook Player: Consumer Health Data Privacy Policy

**Effective Date: October 22, 2026**

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
(contact@ownplace.net; telephone +1 (213) 524-8012) — developer of Talefall —
Audiobook Player (the "App"; bundle identifier com.anisimov.audiobooks) and
operator of the server features that come with the Talefall Subscription (the
"Service"): **Book from an Idea** and **narration of your own text in the
Talefall voice**. Since App version 1.3.2, the Service also writes one Book
from an Idea of about 15 minutes without a subscription (the "first book on
us"; Privacy Policy, Section 6.1A); everything in this policy applies to it in
the same way.

This is our **Consumer Health Data Privacy Policy** under Washington's My
Health My Data Act (Chapter 19.373 RCW), Nevada SB 370 (NRS 603A.400 et
seq.), the Connecticut Data Privacy Act, and similar laws. It is part of our
[Privacy Policy](privacy-policy.html); for consumer health data, this page
controls if the two differ. It is linked from the home page of ownplace.net.

## A1. Why this policy exists

The Service is not a health service, and we do not ask for health
information. **Our rule is that book ideas and texts sent for narration must
contain no personal data about real people, including you** — and in
particular no health information. You confirm this before every book order. For narration of the resulting book, the App reuses that confirmation; for another book without it, the App asks for a separate confirmation before its first narration in the Talefall voice. Our server applies the filters described in A5.

Still, the Service accepts free text. If someone types, against the rule,
information that identifies a person and reveals their past, present, or
future physical or mental health — for example a diagnosis, medication,
pregnancy, reproductive or sexual health, gender-affirming care, or a mental
health condition — that text may be **consumer health data**. It does not
stop being consumer health data because it was labelled fiction. This policy
explains what happens to it. It applies to everyone, wherever they live.

## A2. Categories we may collect, and sources

We collect consumer health data only if it is put into text sent to the
Service, or into a message sent to us.

| Category | How it could arise | Source | Linked to |
|---|---|---|---|
| Health information in a **book idea** | Typed into the idea, against the rule | The person placing the order | The order and the subscription's Apple original transaction identifier; for the first book on us, the order and the app transaction identifier (a number Apple assigns to your Apple Account's download of the App, stored with the prefix `app:`) instead of a subscription identifier (Privacy Policy, Section 6.1A) |
| Health information in a **text sent for narration** | Contained in a text book you chose to narrate in the Talefall voice (requires a subscription) | The person placing the order | The order and the subscription's Apple original transaction identifier |
| Health information in a **generated chapter** | Written by the AI model while producing the book | Generated from the order | The same identifier as the book idea of that order |
| Health information in a **content report or email** | Written in a report, support message, or request | The reporter or sender, who may write about someone else | The report (with the subscription identifier or, for the first book on us, the app transaction identifier, when sent from the App) or your email address |

The app transaction identifier and the keyed hash we keep so that the first
book on us is given only once contain no content and on their own reveal
nothing about health; but because they link an order to a download of the
App, we treat them, like the subscription identifier, as part of the data
covered by this policy whenever the linked order contains consumer health
data.

We do not collect health data from other apps or devices (including
HealthKit), do not collect precise location, do not use geofences, and do not
infer anyone's health status from requests, purchases, language, or anything
else.

## A3. Purposes

We do not offer any service that processes consumer health data, and we do
not ask anyone to provide it. If it is present despite the rule, it may be
processed automatically before anyone notices — by the checks in A5 and, if
those miss it, by the steps that write, moderate, narrate, and deliver the
requested book. **Neither a user's confirmation nor the fact that a request
passed our filters authorizes that processing.** We rely on a "requested
service" exception only where the applicable law allows it and the
processing is necessary and proportionate for a service requested by the
person the data is about — never because someone submitted another person's
data. When we learn that an order contains consumer health data, we stop the
order and any further processing, delete the copies we control (unless the
law requires us to preserve them), restore all hours for the order if any chapter was not delivered under
Section 4.2 of the Terms of Use (for the first book on us, give the offer back
under the same rule; Terms of Use, Section 4.0), and notify every AI
recipient that may have received it to delete it — for an order under
AI-provider permission 2026-10-14.1, OpenAI directly; for an order under an
earlier permission, OpenRouter, which we ask to pass the request on to the
model provider that processed the order (such as Microsoft or a GLM hosting
provider); and any other AI provider listed in the Privacy Policy, Section
6.3.3, that received it — giving the dates and the request identifiers we still hold (kept 30 days
after delivery; Privacy Policy, Section 6.4). We do this also after delivery.

**On what basis, and how we limit it.** We do not seek consent for consumer
health data and do not treat any tap as consent (A5). Our handling rests on
these grounds, each limited to what is necessary:

- **Detecting and refusing it.** Our server reads a book idea — and, for
  versions of the App using AI-provider permission 2026-10-14.1, a text sent
  for narration — only to decide whether to refuse it. A refused text is not
  stored, not sent to any AI provider and not narrated; only the refusal
  category is logged. We treat this screening as processing to prevent,
  detect and respond to the unlawful collection and sharing of consumer health
  data and to preserve the integrity of our systems (RCW 19.373.100(3)); we
  bear the burden of showing that it qualifies (RCW 19.373.100(4)).
- **A service the consumer requested.** Where consumer health data of the
  person who placed the order passes our checks, it is processed only as
  necessary to write, moderate, narrate and deliver the book that person
  requested (RCW 19.373.030(1)(a)(ii) and (1)(b)(ii)). This ground never
  covers data about someone else. Orders under the current permission
  2026-10-14.1 are sent to OpenAI directly, not through OpenRouter, and are
  not subject to OpenRouter's anonymous topic classification. For orders under earlier
  permissions, which go through OpenRouter, this ground does not cover that
  classification for reporting and model rankings, which is not necessary to
  write the book; we do not rely on any ground for that classification of
  consumer health data, and disclosing it does not make such processing
  authorized.
- **Data about someone else, or anything beyond the request.** We have no
  basis to process it. When we learn of it, we stop the order and any further
  processing at once, delete the copies we control, and ask the recipients to
  delete theirs as described above; any processing that already happened is
  handled under applicable law, and this policy does not treat it as
  authorized.
- **Reports, requests and legal duties.** We process what a report, support
  message or rights request contains to answer it, and what the law requires
  us to preserve.

Apart from that residual, unintended processing, we use consumer health data
only:

1. to run the automated checks that refuse requests containing personal or
   sensitive data, and to moderate generated chapters (A5);
2. to respond to a report, support message, or rights request; and
3. to comply with a legal obligation.

We do not use it for advertising, marketing, profiling, research, model
training, or any other purpose, and we do not sell it.

## A4. Who receives it

We have no affiliates. Content that could contain consumer health data, if
someone includes it against our rule, may reach the recipients below, which
process it to provide the Service for the purposes in A3. In addition, the AI
provider that writes the book may keep content for its own abuse, security or
legal checks within its published limits, and its authorized staff may access
it to investigate suspected abuse, give needed technical support, or comply
with law, as the AI-provider permission discloses (Privacy Policy, Sections
6.3.2 and 6.3.3). For example, under the current permission OpenAI may keep
inputs and outputs for up to 30 days to provide its services and identify
abuse, and longer only where the law requires or to protect against harm,
and its authorized employees and specialized contractors may review content
for abuse. For orders under earlier permissions, OpenRouter also permits
access by personnel performing its routing service in accordance with its
agreement, and Microsoft may store content its abuse monitoring flags for
review (Privacy Policy, Section 6.3.3). We treat a recipient as a processor for consumer health data only insofar as it processes that data on our behalf within binding contractual instructions. Washington's processor exception to "sharing" applies only where the disclosure serves the goods or services and purposes explained to the consumer when collecting the data. OpenAI engages its authorized subprocessors under the contractual safeguards required by its DPA. For OpenAI used directly under
permission 2026-10-14.1: OpenAI acts as our processor for Customer Data covered by our DPA, including sensitive data unexpectedly included in unstructured text. This contractual protection does not itself authorize collection or disclosure under consumer health data laws. We prohibit such submissions and apply the prevention and
deletion procedures in A3 and A5. **For the earlier routes we do not rely on
any contract to cover sensitive data (see "Contract limits" below), so we make
no such claim for OpenRouter, the model providers OpenRouter routes to
(including Microsoft), or any other AI provider;** for them, our protection is
prevention (A5) and deletion on discovery (A3).

Book writing goes to AI providers on the conditions of the permission version
under which the order was placed (Privacy Policy, Section 6.3). Under the
current permission (version 2026-10-14.1) **OpenAI (OpenAI OpCo, LLC) is the
only external AI model provider we use directly**, through the OpenAI API
under our own contract and OpenAI's data processing addendum. We do not route
these orders through OpenRouter or another AI gateway. OpenAI may process
content through its published affiliates and subprocessors under its DPA. Our
hosting provider Modal also processes order content (table below). **Today, books under permission 2026-10-14.1 are written
by the GPT-6.1 Sol model in the OpenAI API.** Processing and access by
authorized OpenAI staff or contractors may occur in several countries; we do not choose China (including Hong Kong and Macau), Cuba, Iran, North Korea, Russia or Venezuela — the countries of concern under the US Department of Justice Data Security Program (28 CFR 202.601, as of October 2026); the information OpenAI publishes names none of these countries, but it is not a complete list of processing locations (Privacy Policy, Section 6.3.2). Orders placed under permission 2026-10-13.1 are written by
GPT-6.1 Sol or GPT-6 Luna on Microsoft Azure through OpenRouter; orders placed under the earlier
permissions 2026-10-08 and 2026-10-10.2 go only to the routes those
permissions named; today that is the GLM-5.3 model, developed by Z.ai,
reached through OpenRouter and restricted to hosting providers that OpenRouter
lists as headquartered in the United States and as zero data retention
(Privacy Policy, Section 6.3.5). Each order keeps the route assigned when it
was accepted; within the GLM route, requests for the same order may be
processed by different listed hosting providers.

| Recipient | Role | What it receives |
|---|---|---|
| **Modal Labs, Inc.** (modal.com), United States | Hosting; runs our service, our narrator model, and our moderation model; holds temporary working storage | The full order: idea or narration text, generated chapters, audio |
| **OpenAI OpCo, LLC** (openai.com) — directly, permission 2026-10-14.1 | Our processor (service provider) under OpenAI's data processing addendum; runs the GPT-6.1 Sol model in the OpenAI API. Requests are sent with `store: false` and prompt caching off. May keep inputs and outputs for up to 30 days to provide its services and identify abuse, longer only where the law requires or where reasonably necessary to protect its services or others from harm (no published maximum; Zero Data Retention is not enabled); authorized employees (support, abuse investigation, legal compliance) and specialized contractors (abuse review only) may access it; locations of processing are those in OpenAI's published subprocessor list | The idea and the working text our writer program produces, with no identifier added by us |
| **OpenRouter, Inc.** (openrouter.ai) — earlier permissions only | Passes book-writing requests to the model providers below; does not store prompts or responses for our requests, but may categorize sampled prompts anonymously for its reporting and model rankings (Privacy Policy, Section 6.3.3) | The idea and the working text our writer program produces, with no identifier added by us |
| **Microsoft Corporation (Microsoft Azure)** (microsoft.com) — permission 2026-10-13.1 only | Runs the GPT-6.1 Sol and GPT-6 Luna models on the endpoint OpenRouter labels as United States. Under Microsoft's standard abuse-monitoring process, authorized Microsoft employees may review prompts and responses flagged for suspected abuse or identified as part of a potentially abusive pattern. Microsoft does not publish the reviewer countries for the US route we use; access may occur outside the United States. Microsoft's published documentation does not specify a maximum retention period for content stored for this review. Under the earlier permission 2026-10-10.2 this route is used only if switched on, which it currently is not | The same content OpenRouter forwards |
| **Hosting providers of the GLM model** (earlier permissions only), reached through OpenRouter: Baseten, Crusoe, Decart, DeepInfra, Fireworks AI, Inference.net, Modal, Morph, Novita AI, Parasail, Phala, Sail Research, Together AI, Venice, and Wafer | Run the model that writes the text; listed by OpenRouter as headquartered in the United States and zero data retention; server locations not published | The same content OpenRouter forwards |
| **Other AI providers named by the earlier permission 2026-10-13.1**: Amazon Web Services, Inc. (Amazon Bedrock), Google LLC (Vertex AI), Anthropic, PBC | Named on that permission's screen; not named by the current permission. Amazon Bedrock is not enabled, and the others have no route. **We do not use these AI model routes today. AWS and Google may nevertheless process content as OpenAI subprocessors.** Before any of them receives an order, the Privacy Policy registry lists its verified conditions and we update the assessment in A9 | No content through these AI model routes; possible processing through OpenAI as described above |
| **Apple Inc.** (iCloud Mail) | Delivers and stores mail sent to contact@ownplace.net | What you write to us, and your email address |

Narration and moderation run on our own models at Modal; that text is not
sent to any AI provider. Under every permission version, processing by the
AI providers, and access by their authorized staff or contractors, may take
place outside the United States (Privacy Policy, Sections 6.3.2 and 6.3.3).
We send orders to OpenAI only directly, under permission 2026-10-14.1 (OpenAI
may process them through its published affiliates and subprocessors); the
route to OpenAI through OpenRouter is not used; Z.ai, the developer of GLM,
receives no orders.

**Contract limits.** For orders under permission 2026-10-14.1 we have a
direct contract with OpenAI, including OpenAI's Data Processing Addendum,
accepted on October 14, 2026. OpenAI acts as our processor for Customer Data covered by our DPA, including sensitive data unexpectedly included in unstructured text. This contractual protection does not itself authorize collection or disclosure under consumer health data laws. We prohibit such submissions and apply the prevention
and deletion procedures in A3 and A5. For orders under earlier permissions, our data
processing addendum with OpenRouter is its standard one, which excludes
sensitive data; Microsoft and the GLM hosting providers process those requests
as OpenRouter's providers, and we have no contract of our own with them. Our
own AWS Data Processing Addendum (incorporated into the AWS Service Terms)
applies only to the direct Amazon Bedrock route, which is not enabled today.
For these earlier routes we do not rely on any of these contracts to authorize
the processing of sensitive or health data. We therefore prohibit sending health and
other sensitive data and filter for it before anything reaches an AI provider
(A5). We do not claim contractual protection for sensitive data
that we do not have.

**No advertising disclosures and no sale.** We do not intentionally disclose
consumer health data to anyone, do not give it to advertisers or data brokers,
and do not sell it. Incidental disclosures may occur through the recipients
and processing described above; for example, if someone includes consumer health data in a
book idea against our rule and our filters miss it, it is transmitted to the
AI recipients on the route used — under permission 2026-10-14.1, OpenAI
directly; under an earlier permission, OpenRouter and the model provider it
routes to (today Microsoft for permission 2026-10-13.1, or a GLM hosting
provider for 2026-10-08 and 2026-10-10.2) — to write the book, and that provider may keep it for abuse,
security or legal checks as described above. For the earlier routes, because
we do not rely on a contract with these providers that covers sensitive data,
such a transmission may count as "sharing" under Washington law. For OpenAI
used directly, our DPA's protection does not itself authorize collection or
disclosure under consumer health data laws. Our rule and filters do not create an
exemption from consumer health data laws, and the AI-provider permission does
not authorize processing consumer health data. We work to prevent such
transmissions (A5); any unintended collection or disclosure is handled under
applicable law, including stopping further processing, deletion, and
notification of recipients (A3). Any intended sharing would require the separate consent the
law requires, and a sale would require the separate, signed authorization the
law requires. We may also disclose data where the law requires it (for
example, a valid court order).

## A5. Prevention: the rule, the filters, and no consent option

- **The rule.** No personal data about real people, including you, in a book
  idea or a narration text. Stories must be fiction; Explainers and How-to
  guides may cover general topics, not a private individual.
- **Confirmations.** Before every book order: the switch *"My idea contains no
  personal data about real people"*, which covers the exact text. For a book created from your idea, the App reuses the confirmation given when you placed that order for narration of the resulting book; it does not ask you to confirm again. For another book without that confirmation, before its first narration in the Talefall voice you confirm "This text has no real person's information." With the on-device Apple voice, the text never leaves your device.
- **Input filter on our server for book ideas** (before anything is sent to an
  AI provider; English, Russian, and Spanish; for versions of the App using
  permission 2026-10-14.1, also for texts sent for narration): it refuses an idea containing,
  among other patterns, statements about the requester's own or a named close
  person's health, sexual orientation, gender identity, or criminal record, as
  well as contact details and identification numbers. A refused request is
  not sent on, uses no hours, and the App asks for a rewrite. Our log records
  only the category of the refusal, not the text. For versions of the App
  using permission 2026-10-14.1, text sent for narration in the Talefall voice
  is checked by the same filter before it is narrated; a refused text is not
  narrated and uses no hours. Earlier versions of the App are not changed:
  for them, text sent for narration is not scanned. In every version the
  per-book confirmation and the rule apply, and the text goes only to our own
  narrator model.
- **Output moderation.** Each generated chapter is checked by our own
  moderation model at Modal for personal data about real people and other
  prohibited content before narration and delivery; a failing chapter is not
  delivered and the order is stopped.
- **The filters are imperfect.** They do not recognize every case, and the
  rule applies to anything they miss.
- **No consent option.** We do not ask for consent to process consumer health
  data, and no tap in the App is treated as such consent. The AI-provider
  permission only authorizes where book-order content goes, and its screen
  repeats the rule: *"Fiction only: no real personal or health data."* If consumer health
  data reaches us despite the rule, we process it only as described in A3 and
  delete it as described in A6; where we learn that an order contains it, we
  delete it and may refuse further orders.

## A6. How long it is kept

| What | How long |
|---|---|
| Order content (idea or narration text, generated chapters, audio) | Encrypted temporary working storage on Modal, deleted as soon as the App confirms it has saved every chapter; if the App has not confirmed saving every chapter, the order expires 7 days after it was accepted and is deleted at the next scheduled cleanup, normally within 15 minutes (a failed cleanup is retried). Deleted sooner when we learn it contains consumer health data |
| A refused request | Not stored; only the refusal category is logged |
| AI-provider request identifiers (no text) | 30 days after the order's delivery or end; then deleted. A deletion request to recipients stays open until sent; identifiers in it are deleted after 30 days; the record of sending (no identifiers, no content) is kept two years |
| Paid-order receipt | Kept 7 years after the last related financial event; contains a SHA-256 fingerprint of the idea text, never the text |
| Receipt and permission records of the first book on us (app transaction identifier; no content) | Kept 7 years after the order ends (a permission record without an accepted order: after the recorded decision), then deleted at our next annual retention review unless a lawful exception applies; sooner on a deletion request (A8). The receipt contains a SHA-256 fingerprint of the idea text, never the text |
| Records of the first book on us (keyed hash of the app transaction identifier, book number, amounts, timestamps; no content) | Gift-grant and return records, related book links, per-book cost totals and budget-stop records are kept while the offer runs and deleted within 12 months after it ends, except records needed for a gift book still in progress; we review their continued necessity at least annually. Screening and detailed daily budget records normally expire about seven days after last access; a daily budget journal is normally removed about seventeen days after its day. These records are not automatically removed by the in-app deletion request; requests for earlier deletion are assessed under applicable law (Privacy Policy, Sections 6.4, 10 and 17) |
| Content reports (may include a passage) | 12 months |
| Materials preserved under 18 U.S.C. § 2258A | 1 year after submission, or longer where the law requires |
| Email | Up to 24 months after the last message, deleted earlier on request |
| Copies kept by service providers | Modal may keep function inputs and outputs up to 7 days; OpenAI (directly, permission 2026-10-14.1) may keep inputs and outputs up to 30 days, longer only where the law requires or to protect against harm, with no published maximum (requests sent with `store: false` and prompt caching off; Zero Data Retention not enabled); for orders under earlier permissions, OpenRouter keeps request metadata without content (no fixed period published; OpenRouter keeps personal information as long as reasonably necessary for its business purposes and its legal, regulatory and accounting obligations, and then deletes or de-identifies it (OpenRouter Privacy Policy, Section 7)); the model provider that processed such an order may keep content only as the Privacy Policy registry (Section 6.3.3) states — for Microsoft, content flagged by its abuse monitoring, kept for review for a period it does not publish; providers delete these copies under their own rules, subject to applicable law, and we cannot access them directly or verify their deletion; for the GLM hosting providers used for earlier permissions, zero-data-retention endpoints; backup copies held by a processor are deleted no later than 6 months after an authenticated Washington request |

We keep consumer health data beyond an applicable deletion deadline only
where a specific legal obligation or statutory exception requires it.

## A7. Your rights

Wherever you live, you may:

- **Confirm and access** whether we hold your consumer health data, get a copy
  of what still exists, and get a list of every recipient that received it —
  processors, contractors, and any other third parties, including recipients
  of incidental transmissions such as OpenAI (directly, for orders under
  permission 2026-10-14.1), or, for orders under earlier permissions,
  OpenRouter and the model provider it routed the order to (such as Microsoft
  or a GLM hosting provider), and any
  other listed AI provider that received the data —
  with their contact details (A4). We have no affiliates;
- **Delete** your consumer health data. We notify every recipient that
  received it — processors, contractors, and other third parties — to delete
  it: for orders under permission 2026-10-14.1, OpenAI directly, through its
  published privacy request or support channel, asking it to propagate the
  request to relevant subprocessors, and our hosting provider; for orders under earlier
  permissions, OpenRouter and, through it and directly, the model provider on
  the route. We record the request before deleting the order, keep it open until it
  is sent, and send it with the request identifiers we keep for 30 days after
  delivery or, after that, with our account, the route and the dates.
  Recipients delete under applicable law (RCW 19.373.040(1)(c)) and otherwise
  under their own rules; we do not receive proof of deletion (Privacy Policy,
  Section 6.4);
- **Withdraw** the AI-provider permission in Settings, which stops further
  transfers to AI providers, including for orders in progress, and new book
  orders, and **ask us to stop collecting** your consumer health data, which
  we treat as a deletion request plus a block on further processing for your
  subscription or, for the first book on us, your app transaction identifier
  if you ask;
- **Correct** inaccurate data we still hold;
- **Appeal** a refusal (A8); and
- **Not be discriminated against** for exercising these rights.

People who do not use Talefall but believe their data was submitted by
someone else have the same rights. Our working copy of order content is deleted as described in Section 6.4 of
the Privacy Policy; we can provide or delete only content we still hold.

## A8. How to make a request, verification, and timing

- **Email** contact@ownplace.net with the subject "Talefall: consumer health
  data request," or **call** +1 (213) 524-8012. Include your subscription's
  original transaction identifier and, if you ordered the first book on us,
  the app transaction identifier, if you have them. People without a
  subscription or the App should give information that helps us find the
  data.
- **Deletion from the App.** In App versions 1.3 and later, Settings →
  Privacy → "Request data deletion" asks our service directly, after you
  confirm, to delete your data. From version 1.3.2 the request carries both
  Apple-signed records the App can find — your subscription's signed
  transaction and the signed record of your download — so data kept under the
  subscription identifier and under the app transaction identifier (including
  the first book on us) is deleted. If neither can be identified or the
  request fails, the App offers an email to contact@ownplace.net (subject
  "Talefall: data deletion request") containing the identifiers it can find.
  If the App shows "Almost done", tap the button again in a few minutes to
  finish. What the deletion covers and what we retain is described in
  Section 10 of the Privacy Policy and in A6.
- **Verification.** We use commercially reasonable, proportionate
  verification (for example, an Apple receipt for the subscription, or the
  Apple-signed record of your download that the App sends). An identifier
  alone is not proof of authority. Authorized agents may act with your
  written permission.
- **Timing.** We respond within **45 days** of receiving the request, extended
  once by up to 45 more days where reasonably necessary, with notice and the
  reason within the first period. Where Nevada law applies, we delete covered
  data within 30 days after authentication and notify recipients.
- **Appeals.** If we decline a request, reply within 45 days; we answer in
  writing within 45 days, explain our decision, and tell you how to contact
  the Washington Attorney General (www.atg.wa.gov) or your state's Attorney
  General.

## A9. Assessment

Because free-text requests could contain sensitive data, we keep a
data-protection assessment of the Service, including the assessment the
Connecticut Data Privacy Act requires for processing sensitive data. Before
enabling a new AI route or materially changing its processing — including the
conditions-based permission 2026-10-13.1 and its Microsoft Azure routes, the
permission 2026-10-14.1 with its direct route to OpenAI, and any
later route to another AI provider — we update the
assessment and resolve findings
that require changes to our processing or safeguards. Updating the Privacy
Policy does not replace this assessment.

## A10. Changes

We will update the Effective Date and post the new version here.

**Changes in this edition (October 22, 2026; App version 1.3.2).**
The first book on us and its app transaction identifier (introduction, A2,
A3, A6, A7); deletion requests from the App under both Apple-signed records,
with email as a fallback (A8); retention of the first book on us records
(A6). Nothing else changes.

Our current
Service does not offer a sensitive-data consent option; any change that would
permit such processing will require updated disclosures, the consent the law
requires, and suitable processor contracts before it takes effect.

## A11. Contact

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net · Telephone: +1 (213) 524-8012
