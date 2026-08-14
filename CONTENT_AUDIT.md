# Twinthos Landing-Page Content Audit

Audited: index.html, variant-a.html, variant-c.html (read fully). Plus a note on variant-b.html (exists on disk, out of scope).

## Core-claim checklist (required facts)
| Claim | index.html | variant-a.html | variant-c.html |
|---|---|---|---|
| £5,000/mo flat | ✅ (lines 219,226,237,302,350) | ✅ (7,275,309) | ✅ (same as index) |
| Live in ~48h | ✅ (219,225,238,275,289,301,390) | ✅ (309) | ✅ (same as index) |
| "We use Twinthos to sell Twinthos" | ✅ (240,368) | ✅ (300) | ✅ (same as index) |
| beacons.ai/humanarchitect CTA | ✅ (199,221,392,396) | ✅ (310) | ✅ (same as index) |
| **7-day no-pay guarantee** | ❌ MISSING | ❌ MISSING | ❌ MISSING |

**The 7-day guarantee is absent from all three files.** This is the single biggest content gap — it is a mandated core claim and appears nowhere. (For reference, variant-b.html, not in scope, even says "live in ~48 hours. A window, not a guarantee," which undercuts the guarantee rather than stating it.)

---

## Per-file scores & issues

### index.html — 8/10
- **Brand voice:** Confident, plain, British, on-brand. Consistent throughout.
- **AI-sounding patterns:** None of concern. No em dashes (separators are mid-dots "·"), no "here's what", no numbered "framework" spin, no engagement bait. Numbered lists (01–04 value stack, 01–05 build, 3-step path) are clean design elements, not AI padding.
- **CTA:** Strong — nav pill, hero primary, 3-step path, final primary + ghost ("Read the proof"). All point to beacons.ai/humanarchitect.
- **Funnel:** Complete — hero → value → what-it-does → capabilities → build → maths → day-in-life → proof → decision. Urgency ("limited onboarding each month") present.
- **Dead links:** None. Internal anchors #top/#path/#proof all resolve. External links structurally sound (not live-verified).
- **Social proof:** 4 testimonial cards, but all anonymized (role + sector, e.g. "Operating partner · UK SME"). No names, logos, or hard metrics — weak real proof.
- **Fixes:** Add 7-day guarantee copy near hero-meta and final CTA; add at least one named/testable testimonial or logo.

### variant-a.html — 6/10
- **Brand voice:** Diverges. More abstract/manifesto register ("An intelligence you own", "One quiet operator for the whole front of your business"). Clean and plain, but a different voice from index/c — a consistency risk if these are meant as A/B variants of one offer.
- **AI-sounding patterns:** Lowest of the three. Clean, no filler.
- **CTA:** Weak. Only ONE conversion point (bottom "Hire Twinthos"). **Hero has no CTA at all** — just headline + lede + scroll cue. Top-of-funnel capture is missing.
- **Funnel:** Incomplete at awareness — builds narrative through sections but a reader must scroll to the very bottom to act. High drop-off risk.
- **Dead links:** None structural; all external.
- **Social proof:** Only the self-referential "We use Twinthos to sell Twinthos" quote. **No customer testimonials** — weakest of the three.
- **Fixes:** Add hero CTA; add testimonial cards; add 7-day guarantee; reconcile voice with the index/c register if it is meant to be a true variant.

### variant-c.html — 8/10 (content) ⚠️ PROCESS DEFECT
- **Content is byte-for-byte identical to index.html** (both 25,685 bytes; same lines). Every strength and weakness of index.html applies, including the missing 7-day guarantee.
- **Critical issue:** It is NOT a distinct variant. As an A/B asset it adds zero test value and splits traffic to a duplicate page. This is a QA/build defect, not a content-quality issue, but it must be resolved before any test.
- **Fixes:** Either regenerate variant-c as a genuinely different layout/angle, or retire it and reallocate the slot. Add the 7-day guarantee (inherited from index content once fixed).

---

## Cross-cutting fixes (all three)
1. **Add the 7-day no-pay guarantee** — mandated claim, currently missing everywhere. Place in hero-meta, the "day in the life"/proof area, and the final CTA block.
2. **Strengthen social proof** — replace or supplement anonymized cards with named quotes, company logos, or quantified outcomes (£ saved, deals closed). Priority: variant-a.
3. **variant-a funnel** — insert a hero CTA; add testimonial cards.
4. **variant-c** — make it a real variant or drop it.
5. **Pre-launch** — live-verify the four external links (beacons.ai/humanarchitect, x.com/humanarchitect8, human-architect.substack.com, linkedin.com/in/human-architect). Content is structurally clean but links were not fetched.

## AI-pattern verdict
All three are clean of the classic LLM tells (em dash, "here's what", numbered frameworks sold as insight, engagement bait). Brand voice is the main inconsistency (variant-a vs index/c), and the missing guarantee is the main factual gap.
