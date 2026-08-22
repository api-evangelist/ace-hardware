# Ace Hardware (ace-hardware)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ace Hardware is a retailer-owned hardware cooperative operating thousands of independently owned stores worldwide that sell hardware, tools, paint, lawn and garden, and home improvement products. As a cooperative, Ace Hardware provides vendor integration through EDI standards and an affiliate program for digital publishers to earn commissions on online sales at acehardware.com.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/ace-hardware/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Retail, Hardware, Home Improvement, Tools, Paint, Cooperative, EDI, Affiliate

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Ace Hardware Affiliate Program
The Ace Hardware Affiliate Program allows digital publishers, bloggers, and content creators to earn commissions by referring customers to acehardware.com. The program is managed through Impact's affiliate network and provides access to product links, banners, and promotional resources.

**Human URL:** [https://www.acehardware.com/affiliates](https://www.acehardware.com/affiliates)

#### Tags:

 - Affiliate, Commission, Publisher, Impact

#### Properties

- [Documentation](https://www.acehardware.com/affiliates)
- [Affiliate Program FAQ](https://www.acehardware.com/affiliate-faq)
- [Affiliate Referral Schema](json-schema/ace-hardware-affiliate-referral-schema.json)
- [Affiliate Referral Structure](json-structure/ace-hardware-affiliate-referral-structure.json)
- [Affiliate Referral Example](examples/ace-hardware-affiliate-referral-example.json)

### Ace Hardware Vendor EDI Integration
Ace Hardware requires all vendors to exchange electronic data using X12 EDI standards (version 4010) via AS2 connection. Supported transaction sets include 850 (Purchase Order), 856 (Advanced Ship Notice), 810 (Invoice), 820 (Payment/Remittance), and 864 (Text Message).

**Human URL:** [https://www.acehardware-vendors.com/](https://www.acehardware-vendors.com/)

#### Tags:

 - EDI, Vendor, Supply Chain, X12, AS2

#### Properties

- [Documentation](https://www.acehardware-vendors.com/)
- [Ace Hardware EDI Guide (Stedi Network)](https://www.stedi.com/edi/network/ace-hardware)
- [Ace Hardware EDI via SPS Commerce](https://www.spscommerce.com/network/find-a-partner/view/ace-hardware/)
- [EDI Purchase Order Schema](json-schema/ace-hardware-edi-purchase-order-schema.json)
- [EDI Purchase Order Structure](json-structure/ace-hardware-edi-purchase-order-structure.json)
- [EDI Purchase Order Example](examples/ace-hardware-edi-purchase-order-example.json)

### Ace Hardware Retail Commerce
Ace Hardware's online retail platform at acehardware.com offers customers the ability to shop for hardware, tools, paint, lawn and garden, and home improvement products with options for online ordering, store pickup, and delivery.

**Human URL:** [https://www.acehardware.com/](https://www.acehardware.com/)

#### Tags:

 - Retail, E-Commerce, Hardware, Home Improvement

#### Properties

- [Documentation](https://www.acehardware.com/)

## Common Properties

- [Website](https://www.acehardware.com)
- [Portal](https://www.acehardware.com/)
- [Privacy Policy](https://www.acehardware.com/privacy-policy)
- [Terms of Service](https://www.acehardware.com/legal-notices)
- [Ace Hardware JSON-LD Context](json-ld/ace-hardware-context.jsonld)
- [Ace Hardware Vocabulary](vocabulary/ace-hardware-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Retailer-Owned Cooperative Model | Ace Hardware is owned by its member retailers, giving independent hardware store owners the purchasing power and brand recognition of a national chain while remaining locally owned. |
| Affiliate Commission Program | Publishers earn commissions on referrals to acehardware.com, managed through the Impact affiliate network with access to product links and promotional banners. |
| Vendor EDI Integration | Standardized X12 EDI (version 4010) via AS2 connection enables electronic purchase orders, invoices, ship notices, and payment remittance between Ace Hardware and its vendors. |
| Local Store Inventory | Online shopping integrates with real-time local store inventory allowing buy online, pick up in store across thousands of locations. |
| Vendor Scorecard | Ace Hardware maintains a vendor scorecard tracking supply chain compliance, on-time shipments, and EDI transaction accuracy. |

## Use Cases

| Name | Description |
|------|-------------|
| Affiliate Publisher Monetization | Bloggers, home improvement content creators, and comparison shopping sites earn commissions by linking to Ace Hardware product pages. |
| Vendor Supply Chain Integration | Hardware and home improvement manufacturers integrate their ERP and order management systems with Ace Hardware's EDI infrastructure. |
| Buy Online Pick Up In Store | Customers browse acehardware.com and reserve products for same-day pickup at their local independently owned Ace Hardware store. |
| Drop Ship Vendor Programs | Vendors ship products directly to Ace Hardware customers, integrated through EDI transaction sets for orders and ship notices. |

## Integrations

| Name | Description |
|------|-------------|
| Impact Affiliate Network | Ace Hardware's affiliate program runs on the Impact platform, providing tracking, reporting, and commission management for affiliates. |
| Logicbroker EDI Platform | Logicbroker serves as Ace Hardware's EDI integration platform for vendor onboarding, transaction monitoring, and compliance management. |
| SPS Commerce | SPS Commerce provides pre-built EDI connections for vendors wanting to become Ace Hardware-compliant suppliers. |
| RangeMe Vendor Discovery | Ace Hardware uses RangeMe for new vendor applications and product discovery by category buyers. |
| Tradeshift | Tradeshift provides invoice and payment processing integration for Ace Hardware's AP automation workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Ace Hardware EDI Purchase Order Schema](json-schema/ace-hardware-edi-purchase-order-schema.json)
- [Ace Hardware Affiliate Referral Schema](json-schema/ace-hardware-affiliate-referral-schema.json)

### JSON Structure

- [Ace Hardware EDI Purchase Order Structure](json-structure/ace-hardware-edi-purchase-order-structure.json)
- [Ace Hardware Affiliate Referral Structure](json-structure/ace-hardware-affiliate-referral-structure.json)

### JSON-LD

- [Ace Hardware Context](json-ld/ace-hardware-context.jsonld)

### Examples

- [Ace Hardware EDI Purchase Order Example](examples/ace-hardware-edi-purchase-order-example.json)
- [Ace Hardware Affiliate Referral Example](examples/ace-hardware-affiliate-referral-example.json)

## Vocabulary

- [Ace Hardware Vocabulary](vocabulary/ace-hardware-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 7 actions, 2 workflows, and 3 personas across Ace Hardware's retail and supply chain integration landscape

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
