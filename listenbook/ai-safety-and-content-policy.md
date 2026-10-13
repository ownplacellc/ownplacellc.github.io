# Talefall — Audiobook Player: AI Safety and Content Policy

**Effective Date: October 13, 2026**

<!-- ДАТА РЕДАКЦИИ: 13 октября 2026 — черновик; при публикации заменить на фактический день публикации (во всех 9 файлах). -->

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
(contact@ownplace.net; telephone +1 (213) 524-8012) — developer of Talefall —
Audiobook Player (the "App"; bundle identifier com.anisimov.audiobooks) and
operator of the server features that come with the Talefall Subscription (the
"Service"): **Book from an Idea** and **narration of your own text in the
Talefall voice**, both in the App's Create tab.

This Policy is part of our [Terms of Use](terms-of-use.html) and our [Privacy
Policy](privacy-policy.html). How consumer health data is handled if it
reaches us is described in our [Consumer Health Data Privacy
Policy](consumer-health-data-privacy-policy.html).

## B1. Scope

This Policy governs every request submitted to the Service and every book it
produces. It applies in addition to the App's 18+ rating and the "Before You
Create" screen, on which you state that you are 18 or older and accept the
Terms before your first use of the Service. That statement is a
self-declaration; we do not verify age.

## B2. The core rule: no personal data about real people

Do not put personal data about real people — **including yourself** — into a
book idea or into a text you send for narration in the Talefall voice. That
means no real person's name together with their circumstances, no contact
details, addresses, or account numbers, and no health, sexual orientation,
gender identity, beliefs, finances, criminal record, or other sensitive
details about you or anyone else. Changing a name or calling something
"fiction" does not make such details anonymous.

- **Stories** must be fiction: invented characters and events.
- **Explainers and How-to guides** may cover general topics — science,
  history, how things work, a skill you want to learn — but not a private
  individual.
- **Narration in the Talefall voice** is for text you are entitled to have
  narrated and that contains no personal data about real people. For any
  other text, use the on-device Apple voice: that text never leaves your
  device.

Before **every** book order you turn on the switch **"My idea contains no
personal data about real people"**; it covers the exact text of the idea, so
editing the idea requires confirming again. For a book created from your idea, the App reuses the confirmation given when you placed that order for narration of the resulting book; it does not ask you to confirm again. For another book without that confirmation, before its first narration in the Talefall voice you confirm "This text has no real person's information." These confirmations state the rule; they are not consent to
process sensitive data, and the rule applies whether or not our filters catch
a violation.

## B3. Prohibited uses

You may not use the Service to request, produce, or narrate content that:

1. **sexualizes minors** in any form, including fictional characters
   presented as minors, or otherwise exploits or endangers children;
2. is **pornographic or graphically explicit sexual content**, sexual
   services, non-consensual sexual content, or fetish content intended
   primarily for sexual arousal;
3. **threatens, incites, or glorifies violence** against real people or
   groups, or is a credible threat;
4. **promotes or supports terrorism or violent extremism**;
5. **facilitates human trafficking, forced labour, or sexual exploitation**;
6. **provides instructions for, or encourages, self-harm, suicide, or eating
   disorders**;
7. **provides instructions that facilitate serious wrongdoing**, including
   weapons capable of mass harm, malware, or serious crimes against people;
8. is **hateful**: attacks or demeans people on the basis of a protected
   characteristic, or harasses or bullies a real person;
9. **impersonates or defames** a real person or organization, or presents
   invented statements as things a real person said or did;
10. contains or compiles **personal data about real people** (B2);
11. is meant to be presented as **medical, legal, financial, psychological,
    or other professional advice**, or as a substitute for emergency
    services;
12. **infringes copyright, trademark, privacy, or publicity rights**,
    including requests to reproduce or continue a specific protected work;
13. contains **prompt-injection or malware**, or tries to extract our
    instructions, keys, or other users' content;
14. **circumvents** hours, limits, the territorial or sanctions restrictions
    in the Terms (Sections 4.9 and 7), or these safety controls; or
15. is otherwise **unlawful** where you are or where we operate.

Ordinary adult fiction — violence, crime, horror, strong language, and mature
themes handled as part of a story — is allowed; that is why the App is rated
18+. Sexual content may be part of a story but must not be pornographic or
graphically explicit.

## B4. Safety controls

Our input checks and output moderation run automatically on our service at
Modal; providers may apply additional safeguards, as described below. They
reduce risk but are
imperfect: they can refuse a harmless request and miss a harmful one, so the
rules above apply to anything they miss, and you must review generated
content before relying on it or sharing it.

- **Input check for personal and sensitive data (book ideas).** Before a
  book idea is sent to an AI provider, our server looks for personal and sensitive data patterns in English, Russian, and
  Spanish: email addresses, phone numbers, U.S. Social Security numbers,
  payment-card numbers, IBANs, passwords and API keys, and statements about
  your own health, sexuality, gender identity, or criminal record or that of a
  named close person (a relative, partner, friend, colleague, neighbor,
  patient, or client). A match is refused: nothing is sent on, no hours are
  used, and the App asks you to rewrite the request. Our log records only the
  category of the refusal, never the text. Text you send for narration is not
  scanned for personal data; your per-book confirmation and the rule in B2
  apply to it.
- **Input check for prohibited content (ideas and narration text).** Before
  anything is sent to an AI provider or to our narrator, our server refuses
  requests that clearly seek sexual content involving minors, instructions
  for weapons of mass destruction, or encouragement of or instructions for
  suicide.
- **Output moderation.** Before narration and delivery, every generated
  chapter is checked by an open-source safety classifier model that we run on
  our own infrastructure at Modal, so the text is not sent to any other
  company for this check. It looks for sexual content (especially involving
  minors), hate, dangerous instructions, and personal data about real people.
  A chapter that fails is not narrated or delivered, the order is stopped,
  and the hours reserved for it are restored. We record the category of the
  decision, not the text.
- **Provider safeguards.** AI providers may apply their own safeguards; we do
  not rely on them in place of our own controls. Under the current
  AI-provider permission, providers may run automated checks, keep content
  for abuse, security or legal checks within their published limits, and let
  authorized staff access it to investigate suspected abuse, give needed
  support, or comply with law (Privacy Policy, Section 6.3). Today, books under permission 2026-10-13.1 are written by the GPT-6 Luna model on Microsoft Azure through OpenRouter's United States domain; Amazon Bedrock meets that permission's conditions but is not enabled, and the GLM route is not used under it. Earlier permissions continue on the routes they named.
  On the Microsoft Azure route, Azure filters prompts
  and completions in real time and runs abuse monitoring, in which flagged
  content may be stored and reviewed by authorized Microsoft employees; where
  it confirms abuse, access to the model may be limited, suspended, or
  terminated. Books under earlier permissions are written by GLM hosting
  providers through OpenRouter. OpenRouter and every provider it
  routes to apply their own terms and policies, and any listed provider may
  suspend our access for violations of its terms or use policies. Requests
  that break those terms can therefore stop the Service for everyone, which
  is one more reason the rules in B3 apply.
- **No human pre-review.** Nobody at OWN PLACE LLC reads requests or books
  before they reach you. Authorized personnel review specific content only
  when you contact support, report content, or submit a legal complaint, or
  when reasonably necessary to investigate abuse or a security incident or to
  comply with law.
- **No profiling.** These controls decide about a request or a chapter. They
  are not used to infer anyone's health or other characteristics or to build a
  profile; only the records described in B6 are kept.

## B5. Reporting content

- **In the App:** open the book's menu and tap **Report content**, choose a
  reason (Child safety, About a real person, Threat or violence, Copyright,
  or Something else), and add a note if you like. The report is sent from the
  App to our service together with the book number, the chapter, the passage
  shown on the report screen, and the App version, so that we can find what
  you mean.
- **By email, if sending fails:** the App offers to email the report to
  contact@ownplace.net instead; that email contains the book number, chapter,
  reason, your note, and the App version, but not the passage.
- **Anyone, including people who do not use the App,** may report by email to
  contact@ownplace.net with the subject "Talefall: content report" and, if
  known, the book number.

We review reports promptly. Reports about child safety, credible threats, or
imminent harm are handled first. We tell the reporter the outcome where we
lawfully can. Reports are stored separately from books and are kept for
**12 months**, longer only where the law requires preservation.

**Child sexual exploitation.** When we obtain actual knowledge of facts or
circumstances that trigger 18 U.S.C. § 2258A, including apparent child sexual
abuse material, child sex trafficking, or online enticement, we report to the
NCMEC CyberTipline as soon as reasonably possible and preserve the report
materials for one year after submission, or longer where the law requires,
under the required security safeguards and outside ordinary automatic
deletion.

## B6. Enforcement

Depending on severity and history, we may:

- refuse or stop an order and remove or withhold the server copy of a book;
- **block the subscription** (identified by its Apple original transaction
  identifier) from placing further orders and narration requests, for
  serious or repeated violations; or
- report the matter to law enforcement or NCMEC where required.

A block applies to the Service only. Your separately purchased player, the
books already on your device, and your privacy rights are not affected. For
each block we keep a record of the subscription identifier, the date, the
reason category, and the related book number, for as long as the block lasts
and for 12 months after it ends, longer only where the law requires. A block
for a violation does not entitle you to a refund from us for hours already
used, without prejudice to any refund Apple grants or the law requires. This
does not affect restoration of hours under Section 4.2 of the Terms of Use.

## B7. Review of a block or refusal

If your request was refused by a safety control or your subscription was
blocked, and you believe this was a mistake, email contact@ownplace.net with
the subject "Talefall: appeal" within **30 days**, including the book number
or the date and why you think the decision was wrong. A person reviews the
decision and answers in writing within **30 days**. If the decision was
mistaken, we lift the block and restore any hours affected.

## B8. Accuracy and reliance

Generated text is produced by a statistical model and may be inaccurate,
invented, or biased even when it sounds confident. Explainers and How-to
guides are AI-generated overviews without source checking. Do not rely on
generated content for facts, and never as medical, legal, financial, or other
professional advice. If you are in crisis, contact local emergency services
or a crisis line.

## B9. Contact

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, USA
Email: contact@ownplace.net · Telephone: +1 (213) 524-8012
