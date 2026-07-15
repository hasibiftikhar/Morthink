# Morthink Website — Full Content & Structure Audit
**Prepared from client-supplied materials only** (website copy doc, product pages doc, design review, original content-intake brief, company deck, spec sheet, certificates/patents, and other_info.doc). No content below is invented — every finding traces back to a specific source document, and the source is named so you can verify it.

**Inputs used:**
| File | What it is |
|---|---|
| `Morthink_Website_Copy_FINAL.md` | The finished website copy, all pages |
| `Morthink_Product_Pages_FINAL_with_Specs.docx` | Product page copy reconciled against the real spec sheet |
| `Design_Review_ODM_OEM_Page.md` | Design/visual audit already done on the ODM & OEM page |
| `膜圣科技资料收集副本.docx` | Your original content-intake brief (what was requested from you) |
| `Foreign_Trade_Product_20260615_-_E.xlsx` | Source spec sheet |
| `膜法智慧公司介绍Gavin_含窗膜_EN.pptx` | Company sales deck |
| `other_info.doc` | Domain/email/contact info |
| Certificates & patents (7 PDFs) | IATF 16949, ISO 9001/14001/45001, 3 utility patents, CADCC award, China Aftermarket Top 100 |
| `xpel.com/shop` | Competitor reference site named by you |

---

## 1. Executive Summary

The website copy is well-structured and internally consistent as *copy* — but it is running noticeably behind the assets you actually have. You are sitting on IATF 16949 + three ISO certifications, three granted patents, a national industry award, and a Top 100 ranking, and the current site copy uses **one** of those seven credibility assets (IATF, mentioned twice, generically). The rest are not referenced anywhere in the copy.

There's also a naming conflict between your sales deck and your website: the deck sells window film as **Navigator / Voyage / Sail**; the website (and the reconciled spec sheet) sells it as **WOLFRA / MAGAL** (two series, not three — Sail/DS-series has no equivalent on the site). If both materials are in circulation with dealers at the same time, this is a real point of confusion, not a cosmetic one.

Beyond that, the two biggest structural gaps are (1) the **Architecture Film** product line has zero content anywhere — copy doc, product pages doc, and spec sheet all say the same thing: nothing to write from — and (2) several requirements from your own original content brief (12-language rollout, agent/distributor application fields, warranty documentation, legal pages, product SKUs/pricing) were requested from you but aren't reflected as resolved anywhere in the final copy.

---

## 2. Page-by-Page Coverage Audit

### ✅ Homepage — content present, but thin on proof
- Present: banner, mission-style intro, product application list, "New Products," "Case Studies," "Featured Blog Posts," meta tags.
- **Gap:** "Case Studies" section has no actual case studies backing it anywhere in any file you've provided — same placeholder problem as the ODM page's "Our partners" slide in the deck (Slide 11, image-only, no client names extracted).
- **Gap:** No numbers on the homepage. You have a concrete, verifiable one sitting in your own deck: **500,000 rolls/year capacity, 120 employees, two factories (Qingyuan + Zhaoqing)** (deck, Slide 3). None of this appears on the homepage or anywhere else in the website copy. This is the single easiest credibility upgrade available and it's currently unused.

### ✅ About Us — mostly complete, missing two things your own deck has
- Present: banner/mission, intro, AEGOR platform, three labs, dust-free workshop, IATF 16949.
- **Inconsistency:** copy says AEGOR combines *"70 years of Japanese coating technology"* with Chinese manufacturing experience. Your deck (Slide 3) says technology comes *"From the United States and Japan"* — the U.S. half has been dropped from the website story. Worth confirming intentional vs. lost-in-drafting.
- **Gap:** Company Values are in your deck (Slide 4: *Keep forging ahead / Strive for perfection / Innovate continuously / Take on social responsibility*) but are not on the About page at all — only Mission and Vision made it in.
- **Gap:** Only IATF 16949 is mentioned. ISO 9001 (quality), ISO 14001 (environmental), and ISO 45001 (occupational health & safety) — all three of which you hold, all four certs issued the same day (2025-06-24) — are absent from the About page and from the ODM/OEM page. That's 3 of 4 certifications currently invisible to visitors.
- **Gap:** No mention anywhere of your 3 granted utility patents (自动卷切机, 微凹涂布装置, 汽车玻璃隔热膜切割装置), your CADCC drafting-committee status for the national PPF installation standard (T/CADCC 003-2024), or your 2024 China Automotive Aftermarket Top 100 listing. These are exactly the kind of third-party validation a B2B/dealer buyer looks for before signing, and none of it is used.

### ✅ ODM & OEM — covered in detail by the separate design review
See `Design_Review_ODM_OEM_Page.md` for the full breakdown (image treatment, AEGOR 4-point carousel, R&D section pairing, team-support separation, "Tupe" typo). Content-side additions from this audit:
- **Gap:** Same missing-numbers issue as the homepage — this is the page that's supposed to sell manufacturing capability to a prospective OEM/ODM partner, and it still doesn't state annual capacity, factory count, or headcount anywhere, despite those numbers existing in your deck.
- **Gap:** Same missing-certs issue — only IATF 16949 appears; ISO 9001/14001/45001 don't.

### ⚠️ Product — All Products (MoShiEx) — consistent but entry points already outdated
- The **Paint Protection Film** overview page copy lists five series (LHOTE · CHOMO · GODEN · MALU · KANGA), but the reconciled Product Pages doc explicitly flags this is stale — there are now **six** series; CHOYU is missing from this list in the website copy file even though it has its own full page later in the same document.

### ⚠️ Individual PPF series pages — model lists don't match the verified spec sheet
This is the most consequential finding in the whole audit, because it's not a design issue — it's product data drift between two "final" documents:

| Series | Website Copy models listed | Verified Product Pages doc models | Discrepancy |
|---|---|---|---|
| LHOTE | YL75 only | YL75 · LL75 | LL75 missing from website copy |
| CHOMO | YL11 | V/YL11 | Minor code mismatch (YL11 vs V/YL11) |
| GODEN | YL10 | V/YL10 | Minor code mismatch (YL10 vs V/YL10) |
| MALU | YE75 · LE75 · SE75 · BE75 · FE75 · YE75M23 · YE75M14 · LE75M23 · LE75M14 · VE75 · **DE75 · DE75M** (12 models) | Same list but **DE75(BE75) · BE75M 23 · BE75M2** (13 models) | Website copy's last two model codes (DE75 / DE75M) don't match the verified sheet's codes (DE75(BE75) / BE75M 23 / BE75M2) — these look like an earlier, unreconciled naming pass |
| KANGA | VE85 · YE85 · LE85 · SE85 | Same | ✅ Matches |
| CHOYU | **Not listed as a series entry point anywhere in the website copy** | Full page exists in Product Pages doc (SW75, LW75M14, + 2 unspecced variants) | CHOYU is a complete blind spot in the live copy document |

Recommend treating the Product Pages doc as the source of truth going forward and re-syncing the website copy file against it before this goes to design/dev — right now the two "final" documents disagree with each other in three of five series.

### ⚠️ CHARMIST TPU Color PPF — structurally incomplete by the source material's own admission
- Copy references two series entry points: "Crystal Series · Gloss Metallic Series." The Product Pages doc's verified spec data is only broken out by **finish** (Gloss / Matte), not by series name, and explicitly flags: *"Confirm with client whether 'Crystal Series' maps to Gloss, Matte, or is a separate line entirely."* This is an open question in your own source files, not something the audit is introducing.
- No individual color names or model codes exist anywhere in any file, despite the copy promising "400+ color options."

### ⚠️ Solar Film (Window Film) — naming conflict with your sales deck
- Website copy and the verified spec sheet agree with each other: **WOLFRA** (sputtered, 3 models: WN75/WN40/WN30) and **MAGAL** (ceramic, 3 models: MV70/MV35/MV18).
- Your sales deck (Slides 30–34) sells window film under **three completely different series names**: **Navigator** (sputtered — maps to WOLFRA), **Voyage** (ceramic — maps to MAGAL), and **Sail** (a third, nano-ceramic/PET fusion tier with its own DS75/DS35/DS15 spec table) that **does not exist anywhere in the website copy or the spec sheet at all**.
- This means: (a) the deck and the website use different brand names for the same two product lines, and (b) the deck sells a third, entry-level window film tier that the website doesn't offer at all. If Sail is still an active SKU, it's missing from the website entirely; if it's been discontinued, the deck is now selling a product that doesn't exist.

### ❌ Architecture Film — confirmed empty across every source
Both the website copy doc and the Product Pages doc independently say the same thing in almost the same words: no brief, no intake content, and no spec data has ever been provided for this line. This isn't a drafting gap — there is nothing to draft from yet. Flagged here only so it's tracked as an open item, not a missed deliverable.

### ⚠️ Become a Dealer / Become an Installer — structurally present, but every "hard" field is a placeholder
- Become a Dealer, Part 4 ("Support Policies"): literally reads *"Client to provide: dealer pricing tiers, marketing support, training access, warranty backing."* None of this has been provided in any file reviewed.
- This connects directly to your own original intake brief (`膜圣科技资料收集副本.docx`), which asked you for: **product SKUs/part numbers**, **pricing tiers**, and **warranty documentation (PDF)** — all three are marked in that brief as "客户提供" (client to provide) and none appear resolved in the final website copy.
- The intake brief also specifies a full **Agent & Distributor Application Form** field set (business type, years in business, current brands carried, monthly volume estimate, etc.) and a required "form submission destination" (email/CRM). The website copy's Become a Dealer page only says *"Contact form to start a dealer application"* — it's not clear from the copy whether that detailed field set was actually implemented, or whether it collapsed into a generic contact form.

### ✅ Warranty Check / Dealer Login / Installer Login — structurally defined, contents unverifiable
- These are specified as functional pages (search box; dashboards with specific modules) but there's no warranty terms document anywhere in the file set to check the "Warranty Check" feature against, and no confirmation of the backend/CRM these dashboards are meant to pull from. The intake brief lists a "Warranty Terms Document" as a client deliverable — not present.

### ⚠️ Blog / "Source" (Resources) — structurally named, zero content
- Both sections exist as top-level nav concepts (News, product knowledge, technical insights / Case Studies, Tutorials, FAQ, Downloads, Care Instructions) but none have a single piece of actual content anywhere in the files reviewed. This mirrors XPEL's site structure closely (XPEL's footer runs Help Center, Blog, Events, Warranty Information, Shipping & Returns, Product Safety Data Sheets, Product Specifications, Dealers & Installers, Pre-Cut Kit Library) — the category names largely line up, but XPEL's are all populated and downloadable; Morthink's equivalents are currently named-but-empty.

---

## 3. Requirements From Your Own Intake Brief That Aren't Confirmed as Resolved

Your original content-request document (`膜圣科技资料收集副本.docx`) asked you for a specific list of items. Cross-checking that list against the final website copy, the following items were requested but don't show up as resolved anywhere in the copy or design review:

| Requested in intake brief | Status in final website copy |
|---|---|
| 12 languages total, starting with English / Russian / Arabic / Spanish / Traditional Chinese | Website copy provided is English-only; no indication the other 4 launch languages have been drafted |
| Two logos (brand + factory) with extra navbar space reserved for both | Not addressed in the website copy doc (this is a design-file concern, not copy — flagging so it isn't dropped) |
| Product SKUs/part numbers for the distributor section | Not present in any file |
| Pricing tiers (retail/distributor/MSRP) | Marked "client to provide" in Become a Dealer copy — not provided |
| Warranty terms document (PDF) | Not present in any file |
| Customer testimonials | Intake brief itself notes "这个自己做，或者不放相关内容" (do this ourselves, or leave it out) — website copy has no testimonials section, consistent with "leave it out," but worth confirming that's the final call |
| Privacy Policy / Terms & Conditions | Not present in any file — flagged in the intake brief as GDPR-relevant given multi-region sales |
| Analytics preference (GA/HubSpot/etc.) | Intake brief says "我们决定" (agency to decide) — no decision documented in files reviewed |
| CMS preference | Not resolved in any file reviewed |
| Social media handles | Marked "客户提供" (client to provide) in the intake brief — not present in any file |

---

## 4. Company Identity Inconsistencies

- **Legal name vs. English brand name vs. deck name** — three different English renderings of the company appear across your own documents:
  - IATF/ISO certificates: **"Guangdong Morthink Film Technology Co., Ltd"**
  - Sales deck (Slide 1): **"Guangdong Morthink Optical Material Co., Ltd."**
  - Chinese legal name on all certs/patents/awards: 广东膜法智慧光学材料有限公司 (literal translation: Guangdong MoFa Zhihui Optical Materials Co., Ltd.)
  This is very likely just an unofficial-translation drift across documents produced at different times, but it's worth locking one official English legal/trade name before it goes on a public-facing About page or a certificate download.
- **Two logos, two names** — the brand mark (MoShiEx, red/cyan) and the factory/corporate mark (Morthink, navy/cyan) are different visual identities for what the copy treats as one brand story. The intake brief itself flags this ("两个logo... 顶部导航栏设计的时候考虑把两个logo多放下" — reserve navbar space for both) as something the client is already aware needs careful handling; the website copy doesn't explain anywhere *when* a visitor sees "Morthink" vs. "MoShiEx," which could read as two companies to a first-time visitor.

---

## 5. Design/Visual Findings (Reference)

Full detail is in `Design_Review_ODM_OEM_Page.md`. Headline items, summarized:
- Rounded image corners used sitewide vs. client's straight-corner requirement.
- Literal stock photography (including an unrelated Porsche showroom shot in the hero) used where the client asked for flat/iconographic visuals — except Production Capacity, which the client explicitly wants to stay photographic and currently only has one banner image, not the gallery needed to demonstrate scale.
- Generic pink checkmark background pattern instead of the logo's "M" chevron.
- AEGOR platform shown as a 3-of-4 carousel instead of all four points visible at once — and the underlying copy only supports three genuinely distinct points, so the copy needs tightening before a fourth panel can be built honestly.
- R&D section: three claims sharing one generic photo collage instead of one visual per claim.
- Team Support: one run-on paragraph instead of three separated points.
- Contact form typo: "Tupe Your Message."

---

## 6. Structural Comparison Against Reference Site (xpel.com)

Per your reference brief, XPEL is one of your named comparison sites. Structurally:

| Area | XPEL | Morthink (per copy provided) |
|---|---|---|
| Audience model | Consumer D2C shop + dealer network | B2B only — ODM/OEM, dealer, installer (matches your intake brief's stated target market: end consumers "don't buy directly") |
| Installer discovery | "Find An Installer" locator, prominent in nav | Not present in the copy provided — worth a deliberate call on whether this is out of scope given your B2B-only model, or a gap |
| Downloadable technical docs | Product Safety Data Sheets, Product Specifications, both downloadable in the footer | No downloadable spec sheets or SDS referenced anywhere in the website copy; product pages currently say "as shown in the catalog" rather than linking a document |
| Warranty | Dedicated "Warranty Information" page | You have a page structurally planned ("Warranty Check") but no underlying warranty document exists yet in your files |
| Credibility content | Blog with regular published articles, dealer/partner case studies (Rivian, Rahal Ducati) | Blog and Case Studies are both named sections with no content yet |
| Certifications on-site | Not a major feature on XPEL's site | You have more third-party validation available (IATF + 3× ISO + patents + national award + Top 100 ranking) than XPEL surfaces, and currently use less of it |

---

## 7. Prioritized Pain Points

**Fix before anything else ships (data integrity):**
1. Reconcile the website copy's MALU/LHOTE/CHOMO/GODEN model lists against the verified Product Pages doc — they currently disagree.
2. Resolve the WOLFRA/MAGAL vs. Navigator/Voyage/Sail naming conflict between the sales deck and the website/spec sheet, including whether the "Sail" tier is still sold.
3. Add CHOYU as a listed entry point on the PPF overview page — it's currently invisible despite having a full page.

**High-value, low-effort additions (you already have the assets):**
4. Add the four numbers from your own deck (500,000 rolls/year, 2 factories, 120 employees) to the Homepage and ODM/OEM page.
5. Surface ISO 9001, 14001, and 45001 alongside IATF 16949 — currently 3 of 4 certifications are unused.
6. Add patents (3 granted), CADCC standard-drafting status, and the Top 100 ranking somewhere in About Us or a dedicated credentials section.

**Structural/legal follow-ups (need client input, not a copywriting fix):**
7. Close out the intake-brief items still marked "client to provide": SKUs, pricing tiers, warranty PDF, social handles, non-English copy for the other 4 launch languages, Privacy Policy/T&Cs.
8. Confirm the Agent & Distributor Application Form on the live Become a Dealer page actually includes the detailed field set from the intake brief, not a generic contact form.
9. Decide and document one official English company/legal name for use across the certificate downloads, About page, and footer.

**Content debt (tracked, not actionable yet):**
10. Architecture Film has no source content anywhere — needs a brief from the client before any page can be written.
11. CHARMIST "Crystal Series" vs. Gloss/Matte finish mapping is unresolved in your own source file — needs a client answer before that page is finalized.
