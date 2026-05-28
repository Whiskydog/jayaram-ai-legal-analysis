# Privacy Policy

## 1\. Overview

This Privacy Policy explains how **Writesonic, Inc.** ("Writesonic", "we", "us", "our") collects, uses, shares, and protects personal information in connection with our products, services, and websites, including the Writesonic AI Search Visibility Platform, [writesonic.com](https://writesonic.com/), and any other Writesonic products and domains we operate (together, the "Services").

This Policy applies to:

- **Visitors** to our website, marketing pages, blog, and customer hub.
- **Account holders and end-users** of the Services, including Authorized Users on a customer account.
- **Prospects, leads, and event attendees** who interact with our marketing.
- **Job applicants** who apply through our careers pages.

This Policy does not govern personal information that our business customers ("Customers") submit to the Services as Inputs or content they manage through the Services. For that personal information, the Customer is the controller and Writesonic acts as a processor under our [Data Processing Agreement](https://writesonic.com/legal/dpa). The Customer's own privacy notice governs end-user-of-the-Customer relationships.

By using the Services, you agree to the practices described in this Policy. If you do not agree, do not use the Services.

## 2\. Personal Information We Collect

We collect personal information in three ways: (a) information you provide directly, (b) information collected automatically through your use of the Services, and (c) information from third parties.

| Category | Examples | Source | Why we collect it |
| --- | --- | --- | --- |
| **Account information** | Name, work email, password, company name, role, country | You, when you sign up or are added by an admin | Create and operate your account; authenticate; provide support |
| **Billing information** | Billing contact, billing address, last 4 of card, invoice history; full card data is held by our payment processor and not by us | You, your finance team, our payment processor | Charge fees; remit taxes; meet accounting obligations |
| **Profile and preferences** | Preferences, settings, in-product configurations, brand and competitor inputs | You and your Authorized Users | Provide and personalize the Services |
| **Inputs and Outputs** | Prompts, queries, brand configurations, agent instructions, tracked URLs, generated text, images, audio, video | You and your Authorized Users | Provide the AI Features (see §4) |
| **Usage and device data** | IP address, device identifiers, browser type and version, OS, page-view and click events, referrers, session duration, error logs | Automatic, via our Services and analytics tools | Operate, debug, and secure the Services; analytics; product improvement |
| **Cookies and similar tech** | Session cookies, preference cookies, security cookies, analytics cookies, and (with consent) advertising cookies | Automatic, see §11 | Authentication, preferences, security, analytics, and (with consent) advertising |
| **Communication content** | Support tickets, sales correspondence, recordings of meetings (where you consent), survey responses | You | Respond to inquiries; provide support; train our support team |
| **Marketing information** | Form submissions, content downloads, event registrations, newsletter subscriptions, contact data from data providers | You and from licensed B2B data providers | Send communications you've signed up for; account-based marketing |
| **Recruiting information** | CV, work history, references, interview notes | You and from recruiters or third-party tools | Evaluate applications |
| **Third-party integration data** | OAuth tokens and metadata from integrations you enable (for example, Google services, CMSs, ad platforms, AI platforms) | The third-party service, with your authorization | Provide the integration |

We do not knowingly collect or process special-category personal data such as health, biometric, racial, religious, sexual-orientation, or government-ID information through the Services. Do not submit that kind of information through the Services unless you have agreed a separate written arrangement with Writesonic.

## 3\. How We Use Information

We use personal information to:

- provide, secure, and improve the Services;
- create and authenticate accounts and provide customer support;
- bill you and process payments;
- send transactional communications (account, billing, security, product updates);
- send marketing communications you have opted into, and let you unsubscribe at any time;
- understand how the Services are used and detect abuse, fraud, or harmful behavior;
- comply with legal obligations and respond to lawful requests by public authorities;
- enforce our Terms of Service and protect our rights, property, or safety, or that of others;
- aggregate and de-identify information for analytics, benchmarking, and product development; and
- carry out the AI processing described in §4.

Where we rely on legal bases under the GDPR or UK GDPR, we rely on:

- **Performance of a contract**, to deliver the Services to you or your employer;
- **Legitimate interests**, to operate, secure, and improve the Services, prevent fraud, and conduct B2B marketing where lawful;
- **Consent**, for marketing where required, advertising cookies, and any sensitive-data processing; and
- **Compliance with legal obligations**, for tax, accounting, and lawful requests.

You may withdraw consent at any time without affecting the lawfulness of processing prior to withdrawal.

## 4\. AI Features and Your Data

The Services include AI Features that use machine-learning and generative-AI models, including (a) models developed or fine-tuned by Writesonic, and (b) third-party foundation models accessed through providers that include **OpenAI**, **Anthropic**, **Microsoft Azure OpenAI Service**, **Microsoft Azure** for Anthropic models, custom models hosted by Writesonic on **Microsoft Azure** and **Amazon Web Services**, **Stability AI**, **OpenRouter**, **Google Cloud Platform**, and other model providers selected from time to time depending on the relevant use case (collectively, "Model Providers"). The applicable Model Provider for a given AI Feature may vary based on capability, performance, cost, region, and availability. We host the Services on **Microsoft Azure**.

### 4.1 What we send to Model Providers

When you use AI Features, we send Inputs to the relevant Model Provider, receive Outputs, and return them to you in the Services. We may also send a limited amount of operational metadata (for example, a request identifier or model parameters).

### 4.2 What Model Providers do with that data

Each Model Provider has its own data-handling terms. The summary below reflects the providers' published policies and the configurations we use.

| Provider | Training on customer data | Default retention | Configuration we use |
| --- | --- | --- | --- |
| **OpenAI** (direct API) | Not used to train OpenAI models. See [OpenAI API data controls](https://developers.openai.com/api/docs/guides/your-data). | Up to 30 days for safety and abuse monitoring under the standard API. | Where eligible and approved, we use OpenAI's [Zero Data Retention (ZDR)](https://developers.openai.com/api/docs/guides/your-data) on supported endpoints. |
| **Anthropic** (direct API) | "Anthropic may not train models on Customer Content from Services." See [Anthropic Commercial Terms](https://www.anthropic.com/legal/commercial-terms) and [Anthropic DPA](https://www.anthropic.com/legal/data-processing-addendum). | Trust-and-safety logs may be retained for a limited period. | We use Anthropic's commercial API under their Commercial Terms and DPA. |
| **Microsoft Azure OpenAI Service** | Not used to train OpenAI's or Microsoft's models. See [Data, privacy, and security for Azure Direct Models in Microsoft Foundry](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy). | Up to 30 days of abuse-monitoring retention by default, with content logging. | Where we are eligible, we use Microsoft's **Modified Abuse Monitoring** to disable content logging (verifiable as `ContentLogging=FALSE`). |
| **Microsoft Azure for Anthropic models** (Microsoft Foundry) | "By default, Anthropic will not use your inputs or outputs from commercial products to train their models." See [Data, privacy, and security for use of Anthropic Claude models in Microsoft Foundry](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/claude-models/data-privacy). For these deployments, Anthropic (not Microsoft) is the processor. | Per Anthropic's terms; Anthropic Claude on Microsoft Foundry is **not** covered by the Azure OpenAI Zero Data Retention program. | We rely on Anthropic's Commercial Terms and DPA for these deployments. |
| **Custom models on Microsoft Azure or AWS** | We control these deployments; customer data is not used to train any model. | Per our internal retention schedule. | Tenant-isolated deployments under Writesonic's cloud accounts. |
| **Stability AI, OpenRouter, Google Cloud, and other providers** | We select providers and configurations that prohibit training on customer data and that meet our security and privacy requirements. | Per the relevant provider's policy. | We review provider terms before onboarding; configurations vary by use case. |

### 4.3 Use of Customer Data to train Writesonic models

We do **not** use Customer Data to train or fine-tune any general-purpose, foundation, or large-language model offered by Writesonic or by any Model Provider. We may use de-identified Inputs, Outputs, and Usage Data, that does not identify any Customer or any individual, to operate, secure, debug, evaluate, and improve the Services, including the quality and safety of AI Features.

### 4.4 Free trials and free tier

The no-training commitment in §4.3 applies equally to Inputs, Outputs, and Usage Data generated under any Trial or free tier. We do not sell that data and we do not use it to train or fine-tune any general-purpose, foundation, or large-language model. We may use de-identified Trial data for the Service-improvement purposes set out in §4.3.

### 4.5 What you should not submit

Do not submit Inputs that you do not have the right to share, or that are prohibited by the Model Provider's policies. AI Outputs may be inaccurate or biased and should be reviewed before relying on them. See our [Terms of Service](https://writesonic.com/legal/terms) §6 for more.

## 5\. How We Share Information

We share personal information in the situations below.

| Recipient category | Examples | Why |
| --- | --- | --- |
| **Sub-processors** | Cloud hosting (Microsoft Azure, AWS), Model Providers (OpenAI, Anthropic, Azure, others), CRM, helpdesk, error monitoring, analytics, billing, email | Provide and operate the Services |
| **Affiliates** | Writesonic group entities | Internal operations, support, sales, billing |
| **Integrations you enable** | Google services, CMSs, ad platforms, social platforms, third-party AI platforms | Provide the integration you authorized |
| **Professional advisers** | Lawyers, auditors, accountants | Run the business; comply with law |
| **Authorities and others** | Regulators, law enforcement, courts | Comply with valid legal process; protect rights, safety, security |
| **Buyers and successors** | In a merger, financing, acquisition, restructuring, or sale of all or part of the business | Continuation of the business |

We do not sell personal information for money. Some advertising-cookie activity may qualify as "sale" or "sharing" under specific U.S. state laws; you can opt out under §10. We do not knowingly transfer personal information of children under 18.

The current list of sub-processors used to deliver the Services is in Schedule 3 of our [Data Processing Agreement](https://writesonic.com/legal/dpa). Customers receive at least 30 days' notice of new sub-processors per the DPA.

## 6\. International Transfers

Writesonic is headquartered in the United States. When you use the Services, your personal information may be transferred to, stored in, and processed in the United States and other countries where we, our Affiliates, or our sub-processors operate.

For transfers of personal information from the European Economic Area, the United Kingdom, or Switzerland to a country that has not been deemed adequate by the relevant authority, we rely on **Standard Contractual Clauses** approved by the European Commission, the **UK International Data Transfer Addendum**, and other lawful transfer mechanisms, as set out in our [Data Processing Agreement](https://writesonic.com/legal/dpa).

## 7\. Data Retention

We retain personal information only as long as necessary for the purposes for which it was collected, and as required by applicable law.

| Type | Retention |
| --- | --- |
| Active account information | For the duration of the account, plus the period required by law |
| Customer Data after account deletion | Up to 30 days, then permanent deletion (subject to the DPA) |
| Billing and tax records | 7 years, or as required by tax law in the relevant jurisdiction |
| Support tickets | 3 years from resolution |
| Marketing-list data | Until you unsubscribe or 24 months of inactivity, whichever is sooner |
| Application server access logs | 90 days |
| Security audit logs | 1 year |
| Error and crash reports | 90 days |
| Cookies | See cookie table in §11 |

We may retain information longer where required to comply with legal obligations, defend legal claims, or address security or fraud incidents.

## 8\. Security

We implement administrative, technical, and physical safeguards designed to protect personal information. We are SOC 2 Type 2 audited and publish details about our security program at our trust center: [writesonic.trust.site](https://writesonic.trust.site/).

No system is perfectly secure. If we learn of a security incident affecting your personal information, we will notify you in line with applicable law and our contractual commitments.

## 9\. Your Privacy Rights

The rights available to you depend on where you live and the laws that apply.

### 9.1 GDPR and UK GDPR (EEA, UK, Switzerland)

You have the right to:

- access the personal information we hold about you;
- request correction of inaccurate or incomplete information;
- request deletion of your personal information ("right to be forgotten");
- restrict or object to certain processing;
- data portability, meaning to receive your information in a structured, machine-readable format;
- withdraw consent where processing is based on consent;
- not be subject to a decision based solely on automated processing that produces legal or similarly significant effects, except where permitted by law; and
- complain to your supervisory authority. A list of EEA authorities is at [edpb.europa.eu](https://edpb.europa.eu/about-edpb/about-edpb/members_en); the UK authority is at [ico.org.uk](https://ico.org.uk/).

### 9.2 California (CCPA and CPRA)

If you are a California resident, you have the right to:

- know what personal information we collect, use, disclose, and (if applicable) sell or share;
- request access to, correction of, and deletion of your personal information;
- opt out of "sale" or "sharing" of personal information for cross-context behavioral advertising. See §10;
- limit our use and disclosure of "sensitive personal information"; and
- not be subject to discrimination for exercising your rights.

We do not sell personal information for monetary consideration. Some online advertising practices qualify as "sharing" under the CPRA; you can opt out via §10.

### 9.3 Other U.S. states

If you are a resident of Virginia, Colorado, Connecticut, Utah, Texas, Oregon, Montana, Iowa, Tennessee, Indiana, New Hampshire, Delaware, New Jersey, Minnesota, Maryland, or another state with a comprehensive privacy law, you have rights similar to those above (access, correction, deletion, portability, and opt-out from targeted advertising and certain profiling). You may also appeal a denial of your request by replying to our response or contacting [support@writesonic.com](mailto:support@writesonic.com).

### 9.4 How to exercise your rights

Email [support@writesonic.com](mailto:support@writesonic.com) or use the in-product privacy controls where available. We may need to verify your identity before responding. We will respond within the time required by applicable law (generally 30 days under GDPR and 45 days under CCPA, with extensions where allowed). You may use an authorized agent where the law permits.

## 10\. Your Choices for Cookies, Advertising, and Analytics

- **Cookie banner.** Where required by law, we present a cookie banner on first visit so you can accept or decline non-essential cookies. You can clear cookies through your browser to reset your choice.
- **Browser controls.** Most browsers let you block or delete cookies and tracking. See your browser's help pages.
- **Global Privacy Control (GPC).** We honor the GPC signal as a request to opt out of "sale" and "sharing" under U.S. state laws. We do not respond to general Do Not Track headers because there is no industry-standard interpretation.
- **Marketing emails.** Use the unsubscribe link in any marketing email, or email [support@writesonic.com](mailto:support@writesonic.com).

## 11\. Cookies and Similar Technologies

We and our service providers use cookies, pixels, SDKs, and similar tracking technologies. The categories we use:

| Category | Purpose | Example tools |
| --- | --- | --- |
| **Strictly necessary** | Authentication, security, load balancing, fraud prevention | Session cookies, CSRF tokens |
| **Functional** | Remember preferences and settings | Locale, in-product UI state |
| **Analytics** | Understand how the Services are used; product improvement | Google Analytics, Plausible, Microsoft Clarity |
| **Marketing and advertising** (with consent where required) | Measure marketing campaigns; serve and measure cross-site advertising | Google Ads, Meta (Facebook), LinkedIn Ads |
| **Referral and attribution** | Track referrals and partner attribution | FirstPromoter |
| **Sales and intelligence** | Identify accounts visiting our site for B2B outreach | Unify |
| **Developer infrastructure** | Code hosting and developer-facing pages | GitHub |

You can manage cookies through your browser, the in-product cookie banner, or by following the opt-out instructions of each vendor:

- Google Analytics: [tools.google.com/dlpage/gaoptout](https://tools.google.com/dlpage/gaoptout)
- Google Ads: [google.com/settings/ads](https://www.google.com/settings/ads)
- Meta (Facebook) ads: [facebook.com/help/568137493302217](https://www.facebook.com/help/568137493302217)
- LinkedIn Ads: [linkedin.com/help/linkedin/answer/a1339724](https://www.linkedin.com/help/linkedin/answer/a1339724)
- Microsoft Clarity: [learn.microsoft.com/en-us/clarity/setup-and-installation/cookie-list](https://learn.microsoft.com/en-us/clarity/setup-and-installation/cookie-list)

Plausible is a privacy-focused analytics tool that does not set persistent cookies.

## 12\. Children

The Services are not intended for individuals under 18, and we do not knowingly collect personal information from children under 18. If you believe a child has provided us personal information, contact [support@writesonic.com](mailto:support@writesonic.com) and we will take appropriate action.

## 13\. Changes to This Policy

We may update this Policy. The "Last Updated" date at the top of this page reflects the most recent version. For material changes, we will provide additional notice (for example, in the Services or by email to the account owner) before the change takes effect. Continued use of the Services after the effective date of changes constitutes acceptance of the updated Policy.

## 14\. Contact Us

For privacy questions or to exercise your rights, contact us at [support@writesonic.com](mailto:support@writesonic.com).
