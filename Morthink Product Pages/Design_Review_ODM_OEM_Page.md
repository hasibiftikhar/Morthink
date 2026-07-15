# Design & Content Review — ODM & OEM Solutions Page
**Reviewed against client feedback (7/10/2026, Morthink brand)**

The client's feedback maps almost entirely onto the **"ODM & OEM Solutions"** page — this is the only file in the batch containing R&D, the AEGOR platform, production capacity, IATF certification, quality tracking, and team support sections. The Homepage, About Us, and Contact Us files don't contain this content, so this review focuses on that page.

---

## 1. Global issues (apply to every image on the page)

| Client demand | Current state | Fix |
|---|---|---|
| No rounded corners on inserted images | Every photo on the page (hero, R&D shared image, factory shots, team photo) uses a soft `border-radius` | Set `border-radius: 0` on all image containers site-wide. This is a one-line CSS/Figma change but must be applied to **every** image component, not just new ones. |
| Not fully realistic photography — present key features "like a PowerPoint presentation" | Page relies on stock photography (lab shots, factory interiors, a Porsche in a showroom that has nothing to do with the brand) | Replace explanatory sections with flat, iconographic/infographic visuals — diagrams, icon sets, labelled graphics — rather than literal photos. Reserve real photography for places it's actually earning its keep: the factory/facility proof shots the client explicitly asked for (see §4). |
| Use the logo's "M" chevron mark consistently as a background pattern | Current background pattern is a generic pink checkmark/tick motif that has no connection to the Morthink logo | Replace with a repeating tile of the logo's angular "M" chevron, used at low opacity (8–10%) as section backgrounds. Sample tile delivered: `m_pattern_background.svg`. |

---

## 2. Section-by-section breakdown

### R&D Capabilities
**Client ask:** *"Each of the three aspects of R&D is described separately with accompanying illustrations."*

**Current state:** The section lists three bullet points (International Team of Experts, Advanced Testing Instruments, Three Collaborative Laboratories) but all three share **one generic 4-photo collage** on the right. There's no 1-to-1 pairing between a point and an image, so the visual doesn't reinforce any single claim.

**Fix delivered:** Three standalone flat illustrations, one per R&D aspect, each with its own icon, headline and caption, straight corners, dark card treatment consistent with the AEGOR "01/02/03" cards already on the page:
- `rd_process_illustration.svg` — Process R&D
- `rd_product_illustration.svg` — Product R&D
- `rd_material_illustration.svg` — Material R&D

Recommend swapping the current three-bullet-list-plus-one-photo layout for a 3-card row (mirroring the AEGOR card pattern below it, which is already good practice — consistency across the page is a plus).

### The AEGOR Process & Technology Platform
**Client ask:** *"The four points of the AEGOR platform are presented directly through visual content without the need for scrolling or button presses."*

**Current state:** The section only shows **three** numbered cards (01, 02, 03) at a time, with left/right arrow buttons implying a carousel — the fourth point is hidden behind a click, and on mobile all of them likely require scrolling/swiping.

**Fix delivered:** `aegor_platform_overview.svg` — a single flat infographic showing all four AEGOR points side-by-side in one view (Testing Data Bank, Scientific Evaluation, Climate Adaptation, Local Adaptation), no carousel controls needed. Note: the current copy only supports 3 distinct points from the page content — I've split "climate and environmental data" and "local adaptation" into two so there are genuinely four, but recommend confirming the fourth point's wording with the content owner (you) since the source copy on this page only described three ideas.

### Production Capacity ("Capacity Where You Need It")
**Client ask:** *"The aspects of production capacity and service efficiency are illustrated using images of factories and other facilities that demonstrate these capabilities."*

**Current state:** This section is currently just a text headline + CTA over a single wide banner photo of one facility's exterior. It doesn't visually demonstrate capacity or efficiency (e.g., scale, throughput, multiple sites).

**Fix:** This is the one section that should stay **photographic**, per the client's own request — but needs more than one banner image. Recommend a small gallery (3–4 straight-corner photos) showing: multiple manufacturing bases/exteriors, production floor in motion, packaging/shipping area, and a fast-turnaround visual cue (e.g., a shipment/logistics shot) to substantiate the "ships within 10 days" claim.

### IATF 16949 Certification
**Client ask:** *"The IATF certification pertains to quality management, and relevant visuals can be used to illustrate this aspect."*

**Current state:** Just the certification badge image plus a paragraph — no visual explains *what* quality management under IATF actually looks like operationally.

**Fix delivered:** `iatf_quality_illustration.svg` — pairs the certification badge with a flat audit/checklist icon so the graphic communicates "quality management process," not just "we have a badge."

### Real-Time Quality Tracking
**Current state:** Already implemented well — this section has individual icon + description blocks per point. ✅ No change needed here; it's the model the R&D and Team Support sections should be brought in line with.

### Team Support ("Support for Your Team, Not Just Your Order")
**Client ask:** *"The team support aspect is explained separately for each point."*

**Current state:** One banner with one paragraph covering training, marketing systems, and technical support all in a single run-on sentence — no separation.

**Fix delivered:** `team_support_points.svg` — splits this into three distinct, individually-illustrated points: Sales Training, Technical Support, Marketing Enablement. Recommend replacing the single banner with this 3-card row.

---

## 3. Content notes (writer's side)

- The hero section photo (a Porsche/generic car showroom) doesn't connect to the brand story — "We Build Your Brand" would land harder over a shot that's actually about *your* manufacturing, not a stock car detailing scene.
- "Capacity Where You Need It" copy is strong and specific (10-day turnaround) — keep it, just give it visual proof as noted in §2.
- The AEGOR section copy currently reads as three ideas dressed up as a four-step "process," which is likely *why* the current design defaulted to a hide-one-behind-a-click layout. Worth tightening the copy to four genuinely parallel points before finalizing the four-panel graphic.
- Minor: the contact form on this page has a typo — "**Tupe** Your Message" should read "**Type** Your Message."

---

## 4. Assets delivered in this package

| File | Use |
|---|---|
| `rd_process_illustration.svg/png` | R&D card 1 |
| `rd_product_illustration.svg/png` | R&D card 2 |
| `rd_material_illustration.svg/png` | R&D card 3 |
| `aegor_platform_overview.svg/png` | Replaces AEGOR carousel |
| `iatf_quality_illustration.svg/png` | Pairs with IATF badge |
| `team_support_points.svg/png` | Replaces single team-support banner |
| `m_pattern_background.svg/png` | Site-wide background pattern tile, replacing the pink checkmark motif |

All illustrations use straight corners, the brand's navy (#0B0E11) and cyan (#01B2E6) palette, and are built as scalable SVGs so your designer can recolor/resize/edit them directly in Figma or Illustrator without regenerating from scratch.
