# Talefall — Audiobook Player: Consumer Health Data Privacy Policy

**Effective Date: October 10, 2026**

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
law requires us to preserve them), restore the hours, and notify every AI
provider that may have received it — Amazon Web Services and OpenRouter — to
delete it, giving the dates and any identifiers we still hold. We do this
also after delivery.

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
process it to provide the Service for the purposes in A3; in addition,
Amazon Web Services may keep content its abuse classifiers flag for its
automated abuse detection (A6). We treat a recipient
as a processor for consumer health data — so that disclosure to it is not
"sharing" under Washington law — only to the extent a binding contract with
it covers that processing. **We do not rely on any contract with the AI
providers to cover sensitive data (see "Contract limits" below), so we make no
such claim for Amazon Web Services, OpenRouter, or the hosting providers
OpenRouter routes to;** for them, our protection is prevention (A5) and
deletion on discovery (A3).

Book writing uses one of two routes. **Main route:** the GPT-6 Luna model,
developed by OpenAI, run by Amazon Web Services in Amazon Bedrock in AWS
Regions in the United States. **Backup route:** the GLM-5.3 model, developed
by Z.ai, accessed through OpenRouter using the model identifier
`z-ai/glm-5.3` and restricted to the hosting providers listed in the Privacy
Policy; it is used when the main route is unavailable or fails for an order,
and for orders made under an earlier permission version. One book may be
written partly on each route.

| Recipient | Role | What it receives |
|---|---|---|
| **Modal Labs, Inc.** (modal.com), United States | Hosting; runs our service, our narrator model, and our moderation model; holds temporary working storage | The full order: idea or narration text, generated chapters, audio |
| **Amazon Web Services, Inc. (Amazon Bedrock)** (aws.amazon.com) — main route for book writing | Runs the GPT-6 Luna model that writes the text, in AWS Regions in the United States. By default it does not store the content, but it keeps traffic flagged by its abuse classifiers for up to 30 days for automated abuse detection | The idea and the working text our writer program produces, with no identifier added by us |
| **OpenRouter, Inc.** (openrouter.ai) — backup route for book writing | Passes book-writing requests to the model's hosting providers | The idea and the working text our writer program produces, with no identifier added by us |
| **Hosting providers of the GLM model** (backup route), reached through OpenRouter: Baseten, Crusoe, Decart, DeepInfra, Fireworks AI, Inference.net, Modal, Morph, Novita AI, Parasail, Phala, Sail Research, Together AI, Venice, and Wafer | Run the model that writes the text; listed by OpenRouter as headquartered in the United States and zero data retention | The same content |
| **Apple Inc.** (iCloud Mail) | Delivers and stores mail sent to contact@ownplace.net | What you write to us, and your email address |

Narration and moderation run on our own models at Modal; that text is not
sent to Amazon Web Services, OpenRouter, or its hosts. On the backup route,
processing is not guaranteed to take place only in the United States. Neither
OpenAI, the developer of GPT-6 Luna, nor Z.ai, the developer of GLM, receives
orders.

**Contract limits.** Our data processing addendum with OpenRouter is its
standard one, which excludes sensitive data. Amazon Web Services processes
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
AI provider on the route used — Amazon Web Services, or OpenRouter and its
hosting providers — to write the book. Because we do not rely on a contract
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
  permission only authorizes where book-order content goes. If consumer health
  data reaches us despite the rule, we process it only as described in A3 and
  delete it as described in A6; where we learn that an order contains it, we
  delete it and may refuse further orders.

## A6. How long it is kept

| What | How long |
|---|---|
| Order content (idea or narration text, generated chapters, audio) | Encrypted temporary working storage on Modal, deleted as soon as the App confirms it has saved every chapter; if delivery is not confirmed, the order expires 7 days after it was accepted and is deleted at the next scheduled cleanup, normally within 15 minutes (a failed cleanup is retried). Deleted sooner when we learn it contains consumer health data |
| A refused request | Not stored; only the refusal category is logged |
| Order receipt | Kept 7 years after the last related financial event; contains a SHA-256 fingerprint of the idea text, never the text |
| Content reports (may include a passage) | 12 months |
| Materials preserved under 18 U.S.C. § 2258A | 1 year after submission, or longer where the law requires |
| Email | Up to 24 months after the last message, deleted earlier on request |
| Copies kept by service providers | Modal may keep function inputs and outputs up to 7 days; Amazon Web Services keeps no content by default but keeps content flagged by its abuse classifiers up to 30 days, which we cannot access directly, and may keep limited metadata; OpenRouter and hosting providers keep no content under zero-data-retention routing but may keep limited metadata; backup copies held by a processor are deleted no later than 6 months after an authenticated Washington request |

We keep consumer health data beyond an applicable deletion deadline only
where a specific legal obligation or statutory exception requires it.

## A7. Your rights

Wherever you live, you may:

- **Confirm and access** whether we hold your consumer health data, get a copy
  of what still exists, and get a list of every recipient that received it —
  processors, contractors, and any other third parties, including recipients
  of incidental transmissions such as Amazon Web Services, OpenRouter, and
  OpenRouter's hosting providers —
  with their contact details (A4). We have no affiliates;
- **Delete** your consumer health data. We notify every recipient that
  received it — processors, contractors, and other third parties — to delete
  it, using the identifiers we still hold;
- **Withdraw** the AI-provider permission in Settings, which stops new book
  orders, and **ask us to stop collecting** your consumer health data, which
  we treat as a deletion request plus a block on further processing for your
  subscription if you ask;
- **Correct** inaccurate data we still hold;
- **Appeal** a refusal (A8); and
- **Not be discriminated against** for exercising these rights.

People who do not use Talefall but believe their data was submitted by
someone else have the same rights. Because order content is deleted after
delivery, in most cases no content remains to provide or delete.

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
enabling a new AI route or materially changing its processing, we update the
assessment and resolve findings that require changes to our processing or
safeguards.

## A10. Changes

We will update the Effective Date and post the new version here. Our current
Service does not offer a sensitive-data consent option; any change that would
permit such processing will require updated disclosures, the consent the law
requires, and suitable processor contracts before it takes effect.

## A11. Contact

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net · Telephone: +1 (213) 524-8012
