---
layout: default
title: Privacy Policy
lang: en
---

# Privacy Policy — TimerGym

**Last updated: October 23, 2026**

> This is an English translation provided for convenience. In case of any
> discrepancy, the **French version** of this policy prevails:
> [Politique de confidentialité](../politique-de-confidentialite.html).

This privacy policy ("the Policy") is solely intended to explain which personal data
is collected when you use the **TimerGym** mobile application ("the App"), why it is
collected, who it is shared with, how long it is kept, and which rights you can
exercise. It is drawn up in accordance with Regulation (EU) 2016/679 of 27 April 2016
("GDPR") and the amended French Data Protection Act no. 78-17 of 6 January 1978
("Informatique et Libertés").

It applies to the App regardless of the app store from which you obtained it.

> **This document only covers personal data protection.** The contractual rules for
> using the service (account, Premium subscription, termination, liability) are set
> out in the **[Terms of Use and Sale](./terms.html)**, and legal information about the
> publisher is in the **Legal Notice** (`mentions-legales.html`, in French). These
> documents are separate and should be read together, but none replaces another.

---

## 1. Data controller

- **Publisher / data controller:** Marwin Verin (sole proprietorship) — trading
  name: **Mrw Co**
- **Status:** Sole trader — SIRET 10924536500019
- **Address:** 53 rue Montmailler, 87000 Limoges, France
- **Contact / exercising your rights:** contact@mrwco.fr
- **Data Protection Officer (DPO):** not appointed — given the size of the business
  and the nature of the processing (art. 37 GDPR), appointing a DPO is not mandatory at
  this stage. The data controller is the point of contact for any question about
  personal data (see section 11 "Contact").

## 2. Data we collect

| Category | Data | Source | Required? |
|----------|------|--------|-----------|
| Account | Email address, sign-in username, password (stored **hashed**, never in plain text) | You, at sign-up | Yes, to create an account |
| Profile | Display name, weight, height, age, sex, goal, available equipment, maximum loads (1RM) | You, optional | No — the app also works without an account, locally |
| Workout history | Completed workouts: date, program, location (gym/home/bodyweight), duration, exercises performed, weights used, sets and reps, total volume | You, when finishing a workout | No — without an account, only your last workout stays on your phone, to be added to the account you create within 24 hours; otherwise it is never sent |
| Weight tracking | Dated weigh-ins that you enter yourself | You, optional | No |
| Custom workouts | Name you give the workout and the ordered list of exercises you put in it | You, optional (Premium feature) | No |
| Subscription | Plan type (free/Premium/Pro), status, transaction identifiers provided by the app store | You + Apple/Google and RevenueCat (see 4.2) | No, unless you subscribe |
| Consents | Accepted version of the Terms, date, email opt-in, IP address at the time of consent | System | Yes, to create an account |
| Technical / security | IP address, sign-in dates, audit log (sign-up, sign-in, password reset…) | System | Yes, for security purposes |
| Usage measurement and diagnostics | App usage events (e.g. workout started/finished, timer, equipment updated, sign-in), screens viewed — **without account identifier or email address, and without the content you enter** —, technical information (app/OS version, device model), errors and crashes | System, via **PostHog** (see 4.1) | No — see 4.1 to object |
| Contact messages | The content of the message you write from Profile → Help & contact, the chosen type (feedback, problem, question), the email address you leave for a reply (optional), and attached technical information: app version, operating system and its version, as well as your account and subscription type if you are signed in | You, optional | No |
| Biometric sign-in | **No biometric data is sent to us.** Face ID / Touch ID / fingerprint are checked **locally by your phone's operating system**; once local unlocking succeeds, the app only reuses a sign-in token already issued and stored in the device's secure storage (Keychain/Keystore) | Your device (100% local processing) | No, optional feature that can be enabled in Profile → Account |

**Health / fitness data.** Weight (including dated weigh-ins), height, age, sex,
maximum loads (1RM) and workout history are fitness-related data. We only collect them
if you choose to enter them, for the sole purpose of providing the service (suggested
weight calculation, progress tracking). They are **never** sold or used for
advertising.

We **do not collect**: geolocation, address book contacts, medical health data in the
strict sense (diagnoses, medical records), advertising identifiers, or any bank card
data (see section 4.2).

## 3. Purposes and legal bases

| Purpose | Legal basis (GDPR) |
|---------|--------------------|
| Create and manage your account, provide the service | Performance of the contract (art. 6.1.b) |
| Sync your profile and workout history across devices | Performance of the contract (art. 6.1.b) |
| Manage the Premium subscription and in-app purchases | Performance of the contract (art. 6.1.b) |
| Account security, fraud prevention, audit log | Legitimate interest (art. 6.1.f) |
| Email verification and password reset | Performance of the contract (art. 6.1.b) |
| Technical diagnostics (crashes, errors) to keep the service working | Legitimate interest (art. 6.1.f), limited to what is strictly necessary |
| App audience measurement (usage statistics without direct identification) | Legitimate interest (art. 6.1.f) — improving the app, see 4.1; you can object at any time |
| News emails (optional) | Consent (art. 6.1.a), which can be withdrawn at any time |
| Answering messages sent from "Help & contact" and fixing reported problems | Performance of the contract (art. 6.1.b) and legitimate interest (art. 6.1.f) |
| Compliance with legal obligations (accounting, tax) | Legal obligation (art. 6.1.c) |

## 4. Recipients and processors

Your data is accessible to us and to the following **processors**, each bound by a
data processing agreement (DPA) compliant with article 28 GDPR:

- **Application backend hosting:** Render (Render Services, Inc., a US company),
  server hosted in the **Frankfurt (Germany, European Union)** region.
- **Database:** Neon (Lakebase Postgres) — data hosted in the AWS Europe region
  (`eu-west-2`, London, United Kingdom), covered by the European Commission's
  **adequacy decision** for the United Kingdom.
- **Sending transactional emails** (account verification, password reset): Brevo
  (formerly Sendinblue), a French company, Paris.
- **Receiving emails sent to `contact@mrwco.fr`** (including your requests to exercise
  your rights): OVH — OVH SAS, 2 rue Kellermann, 59100 Roubaix, France, email service
  hosted in France.
- **Payment / subscriptions:** Apple (App Store) and Google (Google Play), which
  process payment data under their own privacy policies. **We do not store any bank
  card data**; we only receive a transaction confirmation (purchase identifier, status,
  plan subscribed to).
- **Subscription management:** RevenueCat (RevenueCat, Inc., a US company), which
  receives your account identifier, the transaction identifier and your subscription
  status so that we can unlock Premium on all your devices (see 4.2). **No bank card
  data is sent to it.**
- **Stores:** Apple and Google, when you download the App and make in-app purchases.

We do not **sell** your data and do not share it for advertising purposes.

### 4.1 Usage measurement and diagnostics (PostHog)

The App uses **PostHog** (PostHog Inc.) as its only audience measurement and technical
diagnostics tool. In practice, PostHog may receive:

- **feature usage events** (e.g. workout start/end, 1RM or equipment update, end of
  onboarding, simulated subscription) and the **names of screens viewed**;
- **technical information** (app and operating system version, device model,
  language, time zone, app opening/backgrounding);
- **error and crash reports** (uncaught exceptions, rejected promises).

However, PostHog **receives neither your account identifier, nor your email address,
nor the content you enter** (username, names of your workouts, weight, messages…):
PostHog's identification feature is not used, screen taps are not recorded, and events
are **not linked to your account**, even when you are signed in. They are associated
with a **random technical identifier, generated at installation** of the app and
**reset at each sign-out**. Approximate location derived from the IP address is
disabled.

**Legal basis:** the publisher's legitimate interest (art. 6.1.f GDPR) in
understanding how the app is used and fixing its crashes, without directly
identifying anyone. **You can object at any time** by writing to contact@mrwco.fr (see
section 7).

### 4.2 Subscription management (RevenueCat)

The Premium subscription is managed by **RevenueCat** (RevenueCat, Inc., a US
company), which lets us manage subscriptions on Apple and Google with a single
integration.

RevenueCat receives your **account identifier** (a number internal to our service,
never your email address), the **transaction identifier** and your **subscription
status**. This information comes back to us to unlock Premium features on all the
devices where you are signed in, and to remove them when the subscription expires.

RevenueCat **never receives bank card data**: it is processed exclusively by Apple and
Google, who do not share it with us either.

The transfer to the United States is governed as described in section 5.

### 4.3 Storage on your device and trackers

The App uses **no cookies** and **no advertising identifier**. It stores on your
device: your settings and workout data (the app's local storage, erased when the app
is uninstalled), your sign-in token (Keychain/Keystore secure storage, only if you
have an account) and the PostHog technical identifier described in 4.1.

## 5. Transfers outside the European Union

When a processor handles data outside the EU, the transfer is governed by a European
Commission **adequacy decision** or by contractual safeguards:

- **Neon** (database): data hosted in the United Kingdom (London), covered by the
  EU–UK adequacy decision, renewed until 27 December 2031. As Neon Inc. is a US
  company, any access from the United States is governed by its data processing
  agreement (DPA).
- **PostHog** (audience measurement): the App is configured on PostHog's **"EU Cloud"**
  infrastructure (`eu.i.posthog.com`) — data is **hosted in the European Union**. As
  PostHog Inc. is a US company, any access from the United States falls under its
  participation in the **EU-US Data Privacy Framework**.
- **Render** (application server hosting): Render Services, Inc. is a US company, but
  the server is located in Frankfurt (EU); it is **certified under the EU-US Data
  Privacy Framework**.
- **RevenueCat** (subscription management): RevenueCat, Inc. is a US company; the
  transfer is governed by the data processing agreement concluded with RevenueCat,
  which relies on the European Commission's **standard contractual clauses**.
- **Brevo** (emails) and **OVH** (email service): French companies, data processed in
  the European Union.

## 6. Retention periods

- **Account and profile:** kept as long as the account is active. Deleting the
  account (Profile → Account) **immediately** erases all your data from our servers
  (profile, 1RMs, workouts, weigh-ins, messages, consents). Technical backup copies of
  the database disappear on their own when our host's restore window expires.
- **Deactivated (paused) account:** from Profile → Account, you can **deactivate**
  your account instead of deleting it: all your sessions are immediately revoked but
  your data is **kept** until you sign in again (automatic reactivation) or request
  permanent deletion.
- **Contact messages:** kept for a maximum of 24 months from receipt, to keep track of
  reported problems and their fixes, then deleted automatically. If you were signed in
  when sending them, they are **deleted with your account**. Note: if we replied to
  you by email, that exchange remains in our respective mailboxes, like any email.
- **Security / audit logs:** 12 months maximum, then deleted automatically. If you
  delete your account, your IP address and any entered detail are erased from them
  immediately: only the type of action and the date remain.
- **Billing data:** kept for 10 years (French accounting obligation).
- **Verification / reset codes:** valid for 15 minutes, deleted automatically within
  24 hours of their use or expiry.
- **Usage measurement and diagnostics events (PostHog):** 12 months maximum from
  collection, after which they are deleted or anonymized.

## 7. Your rights

Under articles 12 to 22 GDPR, you have the following rights over your personal data:

- **Right of access** (art. 15): obtain a copy of the data concerning you.
- **Right to rectification** (art. 16): correct inaccurate or incomplete data.
- **Right to erasure** or "right to be forgotten" (art. 17): request deletion of your
  data, in particular by deleting your account.
- **Right to restriction of processing** (art. 18).
- **Right to data portability** (art. 20): receive your data in a structured, commonly
  used and machine-readable format.
- **Right to object** (art. 21), in particular to processing based on legitimate
  interest (security, diagnostics) or to detailed usage measurement.
- **Right to withdraw your consent** at any time (art. 7.3), without affecting the
  lawfulness of processing carried out before the withdrawal.
- **Right to set instructions regarding the fate of your data after your death**
  (art. 85 of the French Data Protection Act).

**How to exercise these rights:**

- **Directly in the App:** Profile → Account → "Export my data" (portability),
  "Deactivate my account" (reversible pause, no data loss) or "Delete my account"
  (permanent erasure). A "Sign out of all devices" button also lets you immediately
  revoke all your active sessions.
- **By email:** contact@mrwco.fr, stating the right you are exercising. We will respond within
  one month (which may be extended by two months for complex requests).
- **Right to lodge a complaint:** if you believe your rights are not being respected,
  you can contact the **Commission Nationale de l'Informatique et des Libertés
  (CNIL)** — www.cnil.fr — 3 place de Fontenoy, 75007 Paris, France — or the data
  protection authority of your country of residence.

## 8. Security

We implement appropriate technical and organizational measures: hashed passwords
(bcrypt), encrypted communications (HTTPS/TLS), session token stored in the device's
secure storage (Keychain/Keystore), limited sign-in attempts, session revocation when
the password is changed, HTTP security headers, restricted access to data, audit log.
As no method is infallible, we cannot guarantee absolute security, but we undertake to
fix any identified vulnerability without delay.

## 9. Minors

The App is not intended for children under **15**, the age of autonomous digital
consent set by article 45 of the French Data Protection Act for information society
services. We do not knowingly collect data about users under 15. If you are the parent
or legal guardian of a minor who created an account without your permission, contact
us at contact@mrwco.fr so that we can delete the account.

## 10. Changes to the Policy

We may change this Policy, in particular to reflect the addition of new third-party
tools. In the event of a substantial change, you will be informed in the App or by
email before it takes effect. The date of the last update appears at the top of the
document.

## 11. Contact

For any question about this Policy or your personal data: **contact@mrwco.fr**.
