# Talefall — Audiobook Player: Consumer Health Data Privacy Policy

**Effective Date: September 4, 2026**

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
(contact@ownplace.net; telephone +1 (213) 524-8012) — developer of Talefall —
Audiobook Player (the "App"; bundle identifier com.anisimov.audiobooks) and
operator of its optional AI Studio service (the "Service").

This page is our **Consumer Health Data Privacy Policy**, required by
Washington's My Health My Data Act, Nevada SB 370, the Connecticut Data
Privacy Act, and similar laws. It is part of our [Privacy
Policy](privacy-policy.html) and [Terms of Use](terms-of-use.html); if this
page conflicts with those documents on a point they cover, this page controls
for consumer health data. Our rules for what may be submitted to AI Studio,
our safety controls, reporting, and appeals are in a separate document, the
[AI Safety and Content Policy](ai-safety-and-content-policy.html). A direct
link to this page appears on our home page and in the App at
Settings → Privacy.

---

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

These rights are also available to individuals whose personal data we process
even if they do not use Talefall or hold a subscription. Contact
contact@ownplace.net with information reasonably sufficient to locate the
data. We verify your identity and authority using an appropriate alternative
method and do not require another person's Apple transaction.

We do not use submitted text to identify, infer, or determine any
consumer's health status; we process it only to generate or narrate the
work the user requested. Wherever you live — including Washington, Nevada,
and Connecticut — you may exercise the access, correction, and deletion
rights described in A7 and A8.

## A2. What consumer health data we may collect, and from whom

We collect consumer health data only if it is put in the text sent to AI
Studio, contrary to the confirmation given before every order, or included in
a message sent to us. Sources include the individual concerned, users
submitting orders or reports, and other persons contacting us. A submission
may concern someone other than its sender. Specifically:

| Category | How it could arise | Linked to |
|---|---|---|
| Health information contained in a **book request** ("prompt") | You type it into the description of the book you want written | The order record and the subscription's Apple original transaction identifier |
| Health information contained in **text you submit for narration** | It is in the EPUB, FB2, PDF, or TXT you chose to have narrated in our voice | The order record and the same identifier |
| Health information contained in a **passage read aloud** on demand | It is in the passage you selected | The authenticated subscription during processing; passage content is not retained in our application storage. Technical logs follow Privacy Policy Section 9 |
| Health information you include in a **content report or an email** to us | You write it in a report, a support message, or a rights request | The report record or your email address |

Because these are free-text fields, the same text could in principle contain
biometric, genetic, or other sensitive information about a person; we do not
solicit it, do not look for it, and treat it exactly as described here. We do
**not** collect precise location, or health data from other apps or devices
(including HealthKit). We do
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
2. to operate the automated safety controls described in the [AI Safety and
   Content Policy](ai-safety-and-content-policy.html), which process the text
   but do not extract health information;
3. to respond to you if you contact us; and
4. where the law requires it, to comply with a legal obligation.

For consumer health data, retention beyond an applicable deletion deadline is
permitted only where a specific applicable legal obligation or statutory
exception authorizes it. A general interest in defending possible claims does
not by itself override that deadline. This applies equally to excerpts
contained in content reports and in email correspondence.

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
| **OpenRouter, Inc.** (openrouter.ai) | Gateway to the language model that writes fiction (writing mode only) | United States | The book request and the working text our writer program generates; no identifier added by us. While the order exists, our service keeps with it the request identifiers OpenRouter returns; they do not directly identify you and are deleted together with the order |
| **The model provider reached through OpenRouter** (currently Meta Platforms, Inc.), acting as OpenRouter's subprocessor | Generates the text | United States | The same content. |
| **Our business email provider** | Delivery, storage, and security of mail sent to and from contact@ownplace.net | United States | Whatever you include in a support, privacy, or content-report message, and your email address |

OpenRouter and Meta process writing-mode content to generate the
requested text. Requests are sent using a setting that restricts routing to
providers that state they do not use content for training or routine
retention. This is not a zero-retention guarantee; limited retention may
occur for abuse prevention, security, billing, or legal compliance. The
setting operates fail-closed: if no provider with that stated policy is
available, the order is not sent.

**OpenRouter's standard DPA does not contemplate processing Sensitive Data
without the agreement or amendment it specifies. Our prohibition on
submitting such data is not a substitute for those contractual
requirements.**

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
read aloud on demand go to our narrator only and are not retained in our
application storage.

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
- **What your confirmation does and does not do.** **A user's confirmation
  does not authorize processing of personal or consumer health data. We rely
  on a requested-service exception only where the applicable law permits it
  and the specific processing is objectively necessary and proportionate.
  Otherwise, processing requires a valid legal basis; our current service
  does not offer a sensitive-data consent option.** We do not rely on that
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

**Modal may retain Function inputs and outputs for up to seven days under its
infrastructure retention policy, independently of deletion from our
application storage. The one-day period applies to application and container
logs only.**

| What | How long we keep it |
|---|---|
| Order text, generated chapters, title, and audio | Held in **temporary working storage** on Modal only while the order is being produced and delivered: encrypted, subject to an application-level time-to-live, and excluded from OWN PLACE LLC's application logs and crash reports; we do not create separate content backups. Deleted immediately after confirmed delivery of the final chapter. |
| Content of an order that is never fully delivered | Deleted no later than **seven days** after the Service accepts the order |
| Passages read aloud on demand | **Not retained in our application storage** |
| Content you submit in a content report or support request | Retained separately under the report-retention period below |
| Content reports and enforcement notes | Up to 24 months after resolution |
| Materials preserved for a report under 18 U.S.C. § 2258A | One year after submission, and longer where legally required |
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
  requires us to preserve. **For consumer health data, retention beyond an
  applicable deletion deadline is permitted only where a specific applicable
  legal obligation or statutory exception authorizes it. A general interest
  in defending possible claims does not by itself override that deadline.**
- OWN PLACE LLC cannot recover or re-deliver the book from its server after
  deletion; the App may still restore the user's own saved iCloud copy.
- OpenRouter and Meta: see A4; limited retention may occur there, and the
  routing setting is not a zero-retention guarantee.
- **Where NRS 603A.515 applies, we delete covered data within 30 calendar
  days after authentication and notify the relevant recipients. Recipients
  must delete covered data within 30 calendar days after notification,
  subject to the statute's backup exception.**
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
- **Ask us to stop collecting your consumer health data** — **you may
  separately request that we cease collecting, sharing, or selling your
  consumer health data. This request is not limited to writing mode.
  Withdrawing AI-provider permission also stops further transfers under that
  permission for active writing orders as soon as technically possible;
  processing already completed cannot be undone.**
- **Delete** — delete a single book in the App (the App offers to delete the
  copy on this device and the copy stored through Apple's iCloud service), or
  ask us to delete every order and permission record linked to your
  subscription. **To request access, correction, or deletion, email
  contact@ownplace.net and include your subscription's original transaction
  identifier, if available. We use it to locate records and verify your
  authority proportionately before disclosing or deleting data. The
  identifier alone is not proof of authority.** Settings → Privacy →
  **Request Data Deletion** in the App prepares that email for you with the
  identifier filled in. If you request deletion while an order is queued,
  being written, or being narrated, we stop further processing as soon as
  technically possible, delete our working content, and restore the affected
  hours under Terms Section 4.2. **After confirmed delivery we no longer hold
  identifiers that would let us locate any residual processor copy of your
  order. Requests are sent with a routing setting that excludes providers
  that retain or train on content; any limited retention by OpenRouter or the
  model provider for abuse prevention, security, billing, or legal compliance
  ends under their own retention periods. If you request deletion while an
  order is active, we cancel the order and notify OpenRouter with the
  identifiers we still hold.** If the order has
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
  refund path or obtain your separate confirmation of deletion and
  forfeiture.
- **Not be discriminated against** for exercising these rights. Exercising a
  right does not affect your player license or your subscription. Deleting
  content or consumer health data does not affect purchased extra hours. A
  separate request to erase the minimum entitlement record may make
  preservation technically impossible; before erasing it, we will first offer
  a refund path or obtain your separate confirmation of deletion and
  forfeiture.
- **Appeal** — if we decline a request, reply to our response within 45
  days; we answer appeals in writing within 45 days and tell you how to
  contact the Washington Attorney General (or your state's) if you are not
  satisfied.

**These rights are also available to individuals whose personal data we
process even if they do not use Talefall or hold a subscription. Contact
contact@ownplace.net with information reasonably sufficient to locate the
data. We verify your identity and authority using an appropriate alternative
method and do not require another person's Apple transaction.**

## A8. How to exercise your rights, how we verify you, and how fast we act

- **By email (the way requests are made):** **To request access, correction,
  or deletion, email contact@ownplace.net and include your subscription's
  original transaction identifier, if available. We use it to locate records
  and verify your authority proportionately before disclosing or deleting
  data. The identifier alone is not proof of authority.** Use the subject
  "Talefall: consumer health data request". Because we hold no name or
  account, we may ask for proof proportionate to the request (for example, an
  Apple receipt for the subscription) so that a leaked identifier cannot be
  used by someone else against you.
- **From the App:** Settings → Privacy → **Request Data Deletion** opens that
  email with your subscription's original transaction identifier filled in.
  The App does not send a deletion request to our service by itself.
- **By telephone:** +1 (213) 524-8012.
- **Authorized agents** may act for you with your written permission.
- **If you do not use Talefall or hold a subscription:** **these rights are
  also available to individuals whose personal data we process even if they
  do not use Talefall or hold a subscription. Contact contact@ownplace.net
  with information reasonably sufficient to locate the data. We verify your
  identity and authority using an appropriate alternative method and do not
  require another person's Apple transaction.**

**Timing.** **We respond without undue delay and within 45 calendar days
after receiving your request. Verification does not restart this period. We
may extend it once by 45 days where permitted, explaining the extension
within the initial period. Where the CCPA applies, we acknowledge receipt
within 10 business days. Shorter statutory deletion deadlines remain
applicable.** **Where NRS 603A.515 applies, we delete covered data within 30
calendar days after authentication and notify the relevant recipients.
Recipients must delete covered data within 30 calendar days after
notification, subject to the statute's backup exception.** Because we operate
no post-delivery server retention, in most cases there is no server copy left
to delete. Where a copy still exists, we delete our own copies and send any
processor deletion instruction we are still able to address, as described in
A7. Modal application and container logs expire after one day; Modal may
retain Function inputs and outputs for up to seven days under its
infrastructure retention policy. For Washington consumer health data, backup
copies held by a processor are deleted no later than six months after
authentication.

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

**OpenRouter's standard DPA does not contemplate processing Sensitive Data
without the agreement or amendment it specifies. Our prohibition on
submitting such data is not a substitute for those contractual
requirements.**

Because free-text orders could contain sensitive data, we conduct and keep a
data-protection assessment of AI Studio's processing, including the
Connecticut Data Privacy Act assessment required for processing of sensitive
data, and update it when we change a processor or model provider.

## A10. Changes to this policy

We will update the Effective Date and post a new version at this address.
**Our current service does not accept sensitive-data consent. Any future
change permitting such processing will require updated disclosures, a
separate legally valid consent mechanism where required, and appropriate
processor arrangements before the change is enabled.**

## A11. Contact

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net · Telephone: +1 (213) 524-8012
