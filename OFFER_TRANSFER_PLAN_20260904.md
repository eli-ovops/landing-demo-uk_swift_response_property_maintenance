# Offer / Transfer Plan — Swift Response Property Maintenance

**Purpose:** internal prerequisite for quoting the current UK `£99 AS-SHOWN HANDOVER` / `£199 ONE PERSONALISED UPDATE` offer in a first email. This plan does not authorize source transfer, deployment, customer contact, payment, or any change to the visible Demo.

**Current display baseline:** `https://long-firefly-73a4.uumit-200ut-agents.workers.dev/` — a public independent concept preview, observed by the user in a browser on 2026-09-04. It is not described as private or as a final production website.

## Code and dependency disposition

| Component | Current source / role | Disposition for a future source handover | Reason / required action |
| --- | --- | --- | --- |
| `index.html`, inline browser logic | User-directed original static presentation code | `TRANSFERABLE SUBJECT TO FINAL PACKAGE CHECK` | No backend, account, secret, tracking code or third-party runtime library is present. Recheck the final file set before any actual transfer. |
| `styles.css` | User-directed original static styling | `TRANSFERABLE SUBJECT TO FINAL PACKAGE CHECK` | Uses a system-font stack and an embedded SVG grain only; no font file or licensed bundle is included. |
| Local static runtime structure | Relative HTML/CSS/asset paths | `TRANSFERABLE SUBJECT TO FINAL PACKAGE CHECK` | Confirm final archive runs locally after any customer-approved asset disposition. |
| `.media/`, QA screenshots, ledgers, manifests and package notes | Internal provenance / QA material | `EXCLUDE BY AGREEMENT` | Not customer-facing site runtime assets and not part of a final source handover. |

## Customer material and copy disposition

| Material group | Current Demo use | Disposition for a future source handover | Reason / required action |
| --- | --- | --- | --- |
| Complete Swift Response wordmark (`OFFICIAL-09`) | Header, contact close, footer, favicon | `CUSTOMER RECONFIRMATION REQUIRED` | It is a faithful local raster of the official Header Logo, suitable for the current concept preview but not represented as a transferable Logo source file. Ask the customer to provide or confirm their final Logo asset. |
| Official-site service visuals (`OFFICIAL-01` to `OFFICIAL-06`, `OFFICIAL-10` to `OFFICIAL-14`) | Hero and service/standards sections | `CUSTOMER RECONFIRMATION REQUIRED` | Sources and hashes are recorded in `IMAGE_LEDGER.md`; the current permission boundary is local / independent concept use only. Customer must confirm which final images may remain or supply replacements. |
| Website-published testimonials, business claims, contact details and service wording | Page copy and contact CTA | `CUSTOMER RECONFIRMATION REQUIRED` | Confirm current accuracy and continued use at the handover stage; replace only with customer-approved wording or assets if required. |
| SafeContractor mark and unverified project/team/vehicle material | Not used | `EXCLUDE BY AGREEMENT` | No final right/verification basis is currently recorded; do not add it by default. |

## Customer-visible difference safeguard

If a customer-reconfirmation item cannot remain in a final `SOURCE_TRANSFER_PACKAGE`, agree the replacement with the customer before delivery, regenerate the affected final static files, and provide an updated preview. Do not silently hand over a materially different version from the concept preview.

## Gate result

`OFFER / TRANSFER PLAN = PASS` for a £99 / £199 first-email quotation only: the static code boundary is clear and every item not yet known to be transferable has one explicit disposition above.

`FINAL SOURCE / ASSET TRANSFER ELIGIBILITY = NOT RUN` — this must be re-evaluated only before any actual file handover, after customer confirmation of final assets and copy.
