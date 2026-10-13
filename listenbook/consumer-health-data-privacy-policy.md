# Talefall — Audiobook Player: Consumer Health Data Privacy Policy

**Effective Date: October 13, 2026**

<!-- ДАТА РЕДАКЦИИ: 13 октября 2026 — черновик; при публикации заменить на фактический день публикации (во всех 9 файлах). -->

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
(contact@ownplace.net; telephone +1 (213) 524-8012) — developer of Talefall —
Audiobook Player (the "App"; bundle identifier com.anisimov.audiobooks) and
operator of the server features that come with the Talefall Subscription (the
"Service"): **Book from an Idea** and **narration of your own text in the
Talefall voice**.

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
| Health information in a **book idea** | Typed into the idea, against the rule | The person placing the order | The order and the subscription's Apple original transaction identifier |
| Health information in a **text sent for narration** | Contained in a text book you chose to narrate in the Talefall voice | The person placing the order | The same |
| Health information in a **generated chapter** | Written by the AI model while producing the book | Generated from the order | The same |
| Health information in a **content report or email** | Written in a report, support message, or request | The reporter or sender, who may write about someone else | The report or your email address |

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
Section 4.2 of the Terms of Use, and notify every AI
recipient that may have received it to delete it — OpenRouter, which we ask
to pass the request on to the model provider that processed the order (such
as Microsoft or a GLM hosting provider), and any other AI provider listed in
the Privacy Policy, Section 6.3.3, that received it — giving the dates and any
identifiers we still hold. We
do this also after delivery.

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
6.3.2 and 6.3.3). For example, Microsoft may store content its abuse
monitoring flags and have authorized Microsoft employees review it. We treat a
recipient as a processor for consumer health data — so that disclosure to it
is not "sharing" under Washington law — only to the extent a binding contract
with it covers that processing. **We do not rely on any contract with the AI
providers to cover sensitive data (see "Contract limits" below), so we make no
such claim for OpenRouter, the model providers OpenRouter routes to (including
Microsoft), or any other AI provider;** for them, our protection is prevention
(A5) and deletion on discovery (A3).

Book writing goes to AI providers on the conditions of the permission version
under which the order was placed (Privacy Policy, Section 6.3). The current
permission (version 2026-10-13.1) names these recipients: OpenRouter and the
model providers it routes to, Amazon Web Services (Amazon Bedrock), Microsoft
(Azure), Google (Google Cloud, Vertex AI), Anthropic, and OpenAI. **Today, books under permission 2026-10-13.1 are written by the GLM model through OpenRouter; the Microsoft Azure route and Amazon Bedrock meet that permission's conditions but are switched off. Earlier permissions continue on the routes they named.** Orders under the current permission go to the GLM-5.3 model through OpenRouter, as described below; processing and access by authorized provider staff may occur outside the United States (Privacy Policy, Section 6.3.2). Orders placed under the
earlier permissions (2026-10-08 and 2026-10-10.2) go only to the routes those
permissions named; that is also the GLM-5.3 model, developed by Z.ai,
reached through OpenRouter and restricted to hosting providers that OpenRouter
lists as headquartered in the United States and as zero data retention
(Privacy Policy, Section 6.3.5). Each order keeps the route assigned when it
was accepted; within the GLM route, requests for the same order may be
processed by different listed hosting providers.

| Recipient | Role | What it receives |
|---|---|---|
| **Modal Labs, Inc.** (modal.com), United States | Hosting; runs our service, our narrator model, and our moderation model; holds temporary working storage | The full order: idea or narration text, generated chapters, audio |
| **OpenRouter, Inc.** (openrouter.ai) | Passes book-writing requests to the model providers below; does not store prompts or responses for our requests, but may categorize sampled prompts anonymously for its reporting and model rankings (Privacy Policy, Section 6.3.3) | The idea and the working text our writer program produces, with no identifier added by us |
| **Microsoft Corporation (Microsoft Azure)** (microsoft.com) — route switched off today | While switched on, runs the GPT-6 Luna model that writes the text, on the endpoint OpenRouter labels as United States. Under Microsoft's standard abuse-monitoring process, authorized Microsoft employees may review prompts and responses flagged for suspected abuse or identified as part of a potentially abusive pattern. Microsoft does not publish the reviewer countries for the US route we use; access may occur outside the United States, including from countries where Microsoft operates. Microsoft's published documentation does not specify a maximum retention period for content stored for this review. Under the earlier permission 2026-10-10.2 this route is used only if switched on, which it currently is not | The same content OpenRouter forwards |
| **Hosting providers of the GLM model** (all permission versions), reached through OpenRouter: Baseten, Crusoe, Decart, DeepInfra, Fireworks AI, Inference.net, Modal, Morph, Novita AI, Parasail, Phala, Sail Research, Together AI, Venice, and Wafer | Run the model that writes the text; listed by OpenRouter as headquartered in the United States and zero data retention; server locations not published | The same content OpenRouter forwards |
| **Other AI providers named in the current permission**: Amazon Web Services, Inc. (Amazon Bedrock), Google LLC (Google Cloud, Vertex AI), Anthropic, PBC, and OpenAI OpCo, LLC | Named on the permission screen. Amazon Bedrock meets the conditions of the current permission but is not enabled; Google, Anthropic and OpenAI have no route. **None of them receives anything today.** Before any of them receives an order, the Privacy Policy registry lists its verified conditions and we update the assessment in A9 | Nothing today |
| **Apple Inc.** (iCloud Mail) | Delivers and stores mail sent to contact@ownplace.net | What you write to us, and your email address |

Narration and moderation run on our own models at Modal; that text is not
sent to any AI provider. Under every permission version, processing by
OpenRouter and the providers it routes to, and access by their authorized
staff, may take place outside the United States (Privacy Policy, Sections
6.3.2 and 6.3.3). Neither OpenAI, the
developer of GPT-6 Luna, nor Z.ai, the developer of GLM, receives orders.

**Contract limits.** Our data processing addendum with OpenRouter is its
standard one, which excludes sensitive data; Microsoft and the GLM hosting
providers process requests as OpenRouter's providers, and we have no contract
of our own with them. Amazon Web Services processes
content under its standard AWS Data Processing Addendum, which is
incorporated into the AWS Service Terms; we do not rely on it to authorize
the processing of sensitive data. We therefore prohibit sending health and
other sensitive data and filter for it before anything reaches an AI provider
(A5). We do not claim contractual protection for sensitive data
that we do not have.

**No advertising disclosures and no sale.** We do not intentionally disclose
consumer health data to anyone, do not give it to advertisers or data brokers,
and do not sell it. Incidental disclosures may occur through the recipients
and processing described above; for example, if someone includes consumer health data in a
book idea against our rule and our filters miss it, it is transmitted to the
AI recipients on the route used — OpenRouter and the model provider it routes
to (today a GLM hosting provider; Microsoft while its route is switched on) — to write the book, and that provider may keep it for abuse,
security or legal checks as described above. Because we do not rely on a contract
with these providers that covers sensitive data, such a transmission may count
as "sharing" under Washington law. Our rule and filters do not create an
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
  AI provider; English, Russian, and Spanish): it refuses an idea containing,
  among other patterns, statements about the requester's own or a named close
  person's health, sexual orientation, gender identity, or criminal record, as
  well as contact details and identification numbers. A refused request is
  not sent on, uses no hours, and the App asks for a rewrite. Our log records
  only the category of the refusal, not the text. Text sent for narration is
  not scanned for personal data; the per-book confirmation and the rule apply
  to it, and it goes only to our own narrator model.
- **Output moderation.** Each generated chapter is checked by our own
  moderation model at Modal for personal data about real people and other
  prohibited content before narration and delivery; a failing chapter is not
  delivered and the order is stopped.
- **The filters are imperfect.** They do not recognize every case, and the
  rule applies to anything they miss.
- **No consent option.** We do not ask for consent to process consumer health
  data, and no tap in the App is treated as such consent. The AI-provider
  permission only authorizes where book-order content goes, and its screen
  repeats the rule: *"Fiction only, 18+: no real personal or health
  information."* If consumer health
  data reaches us despite the rule, we process it only as described in A3 and
  delete it as described in A6; where we learn that an order contains it, we
  delete it and may refuse further orders.

## A6. How long it is kept

| What | How long |
|---|---|
| Order content (idea or narration text, generated chapters, audio) | Encrypted temporary working storage on Modal, deleted as soon as the App confirms it has saved every chapter; if the App has not confirmed saving every chapter, the order expires 7 days after it was accepted and is deleted at the next scheduled cleanup, normally within 15 minutes (a failed cleanup is retried). Deleted sooner when we learn it contains consumer health data |
| A refused request | Not stored; only the refusal category is logged |
| Order receipt | Kept 7 years after the last related financial event; contains a SHA-256 fingerprint of the idea text, never the text |
| Content reports (may include a passage) | 12 months |
| Materials preserved under 18 U.S.C. § 2258A | 1 year after submission, or longer where the law requires |
| Email | Up to 24 months after the last message, deleted earlier on request |
| Copies kept by service providers | Modal may keep function inputs and outputs up to 7 days; OpenRouter keeps request metadata without content; the AI provider that processed an order may keep content only as the Privacy Policy registry (Section 6.3.3) states — for Microsoft, content flagged by its abuse monitoring, kept for human review for a period Microsoft does not publish, which we cannot access directly; for the GLM hosting providers used for earlier permissions, zero-data-retention endpoints; backup copies held by a processor are deleted no later than 6 months after an authenticated Washington request |

We keep consumer health data beyond an applicable deletion deadline only
where a specific legal obligation or statutory exception requires it.

## A7. Your rights

Wherever you live, you may:

- **Confirm and access** whether we hold your consumer health data, get a copy
  of what still exists, and get a list of every recipient that received it —
  processors, contractors, and any other third parties, including recipients
  of incidental transmissions such as OpenRouter, the model provider it
  routed the order to (such as Microsoft or a GLM hosting provider), and any
  other listed AI provider that received the data —
  with their contact details (A4). We have no affiliates;
- **Delete** your consumer health data. We notify every recipient that
  received it — processors, contractors, and other third parties — to delete
  it, using the identifiers we still hold;
- **Withdraw** the AI-provider permission in Settings, which stops further
  transfers to AI providers, including for orders in progress, and new book
  orders, and **ask us to stop collecting** your consumer health data, which
  we treat as a deletion request plus a block on further processing for your
  subscription if you ask;
- **Correct** inaccurate data we still hold;
- **Appeal** a refusal (A8); and
- **Not be discriminated against** for exercising these rights.

People who do not use Talefall but believe their data was submitted by
someone else have the same rights. Our working copy of order content is deleted as described in Section 6.4 of
the Privacy Policy; we can provide or delete only content we still hold.

## A8. How to make a request, verification, and timing

- **Email** contact@ownplace.net with the subject "Talefall: consumer health
  data request," or **call** +1 (213) 524-8012. Include your subscription's
  original transaction identifier if you have it; the "Request data deletion"
  button in the App's Settings prepares an email with it. People without a subscription should give
  information that helps us find the data.
- **Verification.** We use commercially reasonable, proportionate
  verification (for example, an Apple receipt for the subscription). The
  identifier alone is not proof of authority. Authorized agents may act with
  your written permission.
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
conditions-based permission 2026-10-13.1 and its Microsoft Azure route, and
any later route to another listed AI provider — we update the assessment and resolve findings
that require changes to our processing or safeguards. Updating the Privacy
Policy does not replace this assessment.

## A10. Changes

We will update the Effective Date and post the new version here. Our current
Service does not offer a sensitive-data consent option; any change that would
permit such processing will require updated disclosures, the consent the law
requires, and suitable processor contracts before it takes effect.

## A11. Contact

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net · Telephone: +1 (213) 524-8012
