# Step 10: LLM Monitoring & Measurement

> **Purpose:** Know whether the strategy is working. Track whether ChatGPT, Perplexity, Gemini, and Claude are citing IHTC — and what they say when they do.

---

## The Core Measurement Question

For each major LLM, the goal is to appear — and appear accurately — when a potential patient asks:

1. "What is the best hair transplant clinic in Tijuana?"
2. "How much does a hair transplant in Tijuana cost?"
3. "Is it safe to get a hair transplant in Mexico?"
4. "Hair transplant Tijuana vs USA"
5. "FUE+DHI hair transplant Tijuana"
6. "Hair transplant clinic near San Diego"
7. "Dr. Erik Yáñez Tijuana"

---

## Manual LLM Testing Protocol

### Run monthly (first week of each month)

Query each of the 7 questions above in:
- **ChatGPT** (GPT-4 or latest available)
- **Perplexity** (use the web search mode)
- **Google Gemini**
- **Claude**
- **Microsoft Copilot** (Bing-backed; good for local business queries)

**For each response, record:**
1. Is IHTC mentioned by name? (Y/N)
2. Is "International Hair Transplant Clinic" mentioned? (Y/N)
3. Is Dr. Erik Yáñez mentioned? (Y/N)
4. Is the $2,345 price mentioned? And is it labeled as "promotional" or "current"?
5. Is FUE+DHI mentioned as a combined procedure?
6. What sources does the LLM cite? (Perplexity and some GPT responses show citations)
7. Are any factual errors present?

---

## Tracking Spreadsheet Structure

Create a Google Sheet with:

| Column | Contents |
|--------|----------|
| Date | Month tested |
| LLM | ChatGPT / Perplexity / Gemini / Claude / Copilot |
| Query | Which of the 7 queries |
| IHTC Named? | Y/N |
| Dr. Yáñez Named? | Y/N |
| Price Mentioned? | Y/N — and exact wording |
| Price Labeled Correctly? | "current promotional" Y/N |
| FUE+DHI Combined? | Y/N |
| Sources Cited | List any URLs |
| Errors/Issues | Any wrong information |
| Screenshot | Link to screenshot |

**Target state:** IHTC named in at least 3 of 5 LLMs for query #1 ("best hair transplant clinic Tijuana") within 12 months.

---

## Screenshot Archiving

Save a screenshot for every LLM response to the 7 queries. Store in Google Drive folder:  
`IHTC / LLM Monitoring / YYYY-MM`

This creates a visual record of progress — comparing October 2026 to October 2027 shows clearly whether the strategy is working.

---

## What to Do When an LLM Gets Something Wrong

### If IHTC is not mentioned at all:
- Check whether the queried topic has a corresponding page on tijuanahair.com
- If no page exists, that query is a content gap → add to content calendar (Step 9)
- Check whether llms.txt includes the relevant page
- Check whether the comparison page (best-hair-transplant-clinic-tijuana.html) targets that query in its FAQ schema

### If the price is mentioned but not labeled as promotional:
- Verify the homepage and cost page still use "current promotional price" language
- Check llms.txt for the correct promotional price framing
- The fix propagates slowly (LLMs re-index over weeks/months)

### If FUE and DHI are presented as separate options:
- Identify which page is likely being indexed (check Perplexity citations)
- Review that page for any language presenting them as distinct procedures
- Update the page and the FAQ schema

### If factual errors appear (wrong address, wrong surgeon name, etc.):
- Submit a correction to Google Business Profile (usually propagates to Gemini fastest)
- Update all directory listings (Step 6 NAP audit)
- If Perplexity cites a specific URL with wrong info, check and correct that page

### If a competitor clinic is mentioned instead of IHTC:
- Run the competitor comparison: what does that clinic's web presence look like?
- Identify the gap — are they mentioned in more forums? More directories?
- Prioritize the Step 8 backlink/authority actions for the missing source type

---

## Automated Monitoring (Optional, Low Cost)

### Google Alerts
Set up alerts that email you when these are mentioned online:
- "International Hair Transplant Clinic"
- "IHTC Tijuana"
- "Dr. Erik Yáñez"
- "tijuanahair.com"

This catches organic mentions you didn't create — forum posts, news articles, patient shares.

### Perplexity Monitoring
Perplexity shows its sources. For the 7 queries, note every URL that Perplexity cites. Those URLs are your competitors' most valuable pages — study them and identify what they're doing that IHTC isn't.

### Brand24 or Mention.com (Paid)
Tools that monitor brand mentions across the web in near-real-time. Useful at scale once the clinic has significant review volume. Optional at early stages.

---

## Success Milestones

| Milestone | Target Date | Metric |
|-----------|-------------|--------|
| First IHTC citation by any LLM for query #1 | Q1 2027 | Named in ≥1 LLM |
| Cited by 3 of 5 LLMs for query #1 | Q3 2027 | Named in ≥3 LLMs |
| Price labeled correctly when cited | Ongoing | "current promotional" in citation |
| FUE+DHI always described as combined | Ongoing | No LLM separates them as options |
| Zero factual errors in any LLM response | Q4 2027 | Errors: 0 |
| Cited for all 7 queries by at least 1 LLM | Q4 2027 | 7/7 queries covered |

---

## Quarterly Review Ritual

At the start of each quarter:

1. Run all 7 queries in all 5 LLMs (35 total tests)
2. Fill in the tracking spreadsheet
3. Screenshot archive
4. Identify: which queries are unmet, which LLMs are lagging, which content gaps exist
5. Adjust content calendar (Step 9) to address gaps
6. Review and update llms.txt if any new pages were added since last quarter
7. Check NAP consistency on top-5 directories (Step 6)

---

## What Takes Time vs What Is Immediate

**Immediate (within days of publishing):**
- New pages indexed by Google
- Schema markup parsed
- llms.txt updated

**Takes 1–3 months:**
- LLM training data updated with new pages (some models update more frequently)
- Review accumulation
- Directory listings verified and propagating

**Takes 6–12 months:**
- Forum discussions generating organic IHTC mentions
- Backlinks from medical tourism sites building
- LLMs consistently citing IHTC for competitive queries

**The compound effect:** Each piece — a review, a forum mention, a new page, a directory listing, a media mention — adds incrementally. None of them alone produces the result. All of them together do.

---

## Summary: The Full 10-Step System

| Step | Action | Status |
|------|--------|--------|
| 1 | llms.txt — AI-readable site summary | ✅ Complete |
| 2 | robots.txt — allow all LLM crawlers | ✅ Complete |
| 3 | Schema markup across all pages | ✅ Complete |
| 4 | Resources/Blog section on homepage | ✅ Complete |
| 5 | Comparison page (IHTC vs others) | ✅ Complete |
| 6 | NAP/Directories audit | ✅ Strategy documented |
| 7 | Reviews strategy | ✅ Strategy documented |
| 8 | Authority & backlinks | ✅ Strategy documented + patient-stories.html live |
| 9 | Content calendar | ✅ 12-month plan documented |
| 10 | LLM monitoring & measurement | ✅ Protocol documented |

**Next actions:**
1. Implement Step 6 (NAP audit) — start with Google Business Profile
2. Begin Step 7 (reviews) — send Day 10 WhatsApp to next patient post-procedure
3. Publish Step 9 content — start with hair-transplant-recovery-guide.html (October)
4. Run Step 10 baseline measurement — test all 7 queries in all 5 LLMs now, record baseline
