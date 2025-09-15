# All SEO Analysis Prompts

This file contains all the user prompts from the SEO analysis process for https://www.moshetabo.co.il.

## Step 1: Website Data Collection → Site Intelligence
**Role:** Technical Crawler
**Target Website:** https://www.moshetabo.co.il
**Goal:** Extract complete on-page data for analysis
**Task:** Perform systematic data collection:
1. Scrape homepage + identify 3-5 key service/product pages
2. Extract from each page:
   - Page title and meta description
   - All heading tags (H1, H2, H3)
   - First 200 words of body content
   - All internal links with anchor text
   - Image count and alt text presence/absence
   - Page URL structure
3. Document site hierarchy and navigation flow
4. Note primary language mix (Hebrew/English)

**Input:** Target website URL only
**Output Format:** Structured data table with:
- Page URLs
- SEO elements (titles, meta descriptions, headings)
- Content snippets
- Link inventory
- Image optimization status

**Business Logic:** This foundational step gathers raw data needed for all subsequent analysis. Without complete data extraction, we cannot identify what's broken vs. working, making this the critical first building block.

**Success Criteria:** Complete data collection from 4-6 pages maximum with all required elements documented for Step 2 analysis.



## Step 2: SEO Health Check → Problem Identification
**Role:** SEO Auditor
**Input:** Structured data from Step 1
**Task:** Complete on-page SEO assessment:

1. **Title Tag Analysis:** Length (30-60 chars), uniqueness across pages, service keyword presence
2. **Meta Description Review:** Presence/absence, optimal length (150-160 chars), compelling copy quality
3. **Heading Structure:** H1 uniqueness per page, logical hierarchy (H1→H2→H3), keyword usage
4. **Content Quality:** Hebrew readability, appropriate length (300+ words), keyword density, topic relevance
5. **Internal Linking:** Navigation logic, descriptive anchor text, link distribution between pages
6. **Image Optimization:** Alt text coverage percentage, descriptive file naming conventions
7. **Keyword Consistency:** Same service terms appearing across titles, H1s, content, and meta descriptions

**Flag Critical Issues:**
- Missing or duplicate titles/meta descriptions
- Multiple H1s or poor heading hierarchy
- Thin content (under 300 words)
- Missing alt text on images
- Weak/generic anchor text ("click here", "read more")
- Keyword gaps (service terms missing from SEO elements)

**Output:** Complete issue checklist with severity ranking (High/Medium/Low) and working elements identification.

## Step 3: Technical Foundation → Infrastructure Assessment
**Role:** Technical SEO Specialist
**Goal:** Verify core technical elements that impact search visibility
**Target:** https://www.moshetabo.co.il
**Input:** Website URL for direct technical testing
**Task:** Pass/fail assessment of foundational elements:

**Core Infrastructure:**
1. **Sitemap Accessibility:** Check /sitemap.xml and /sitemap_index.xml existence and validity
2. **Robots.txt Configuration:** Verify /robots.txt exists and doesn't block critical pages
3. **HTTPS Security:** Confirm SSL certificate and no mixed content warnings
4. **Mobile Responsiveness:** Test viewport configuration and responsive design functionality
5. **Page Speed Basics:** Identify obvious blockers (oversized images, slow server response)
6. **URL Structure:** Evaluate clean, descriptive URLs vs. parameter-heavy structures

**Functionality Tests:**
- Site loads properly on mobile/desktop devices
- Internal links from Step 1 data work correctly
- Canonical tags implementation (if present)
- Basic loading time assessment

**Output:** 
- Technical scorecard: ✅/❌ for each element
- Critical blockers identification (issues preventing indexing)
- Performance bottlenecks summary
- Foundation readiness score for optimization work

**Business Logic:** Technical issues can completely block SEO success regardless of content quality. This pass/fail assessment identifies infrastructure problems that must be fixed before optimizing content elements.

**Success Criteria:** Binary assessment complete - clear identification of what works vs. what's broken, with critical blockers flagged for immediate attention.

## Step 4: Keyword Analyst
**Role:** Keyword Analyst  
**Input:** Content from Steps 1-2  

**Task:** Basic keyword alignment check:  
1. Identify 2-3 primary Hebrew service keywords from content  
2. Check keyword presence in:  
   - Page titles  
   - H1 tags  
   - First paragraph of main pages  
   - Meta descriptions  
3. Evaluate keyword natural integration vs over-optimization  
4. Note missing keywords that should be present for business type  

**Analysis Points:**  
- Are main services clearly reflected in SEO elements?  
- Do Hebrew keywords appear naturally in content?  
- Are there obvious keyword gaps for the business type?  

**Output:** Keyword map showing alignment between business services and on-page optimization.

## Step 5: SEO Strategist
**Role:** SEO Strategist  
**Input:** Findings from Steps 1-4  

**Task:** Synthesize all findings into business-friendly summary:  
1. Calculate overall SEO health score: Low/Medium/High  
2. Identify top 5-7 critical issues impacting search visibility  
3. Explain each issue in simple business terms (why it hurts traffic/customers)  
4. Estimate potential impact: "Quick wins" vs "Long-term improvements"  

**Scoring Logic:**  
- High: 8+ green flags, 0-1 red flags  
- Medium: 5-7 green flags, 2-3 red flags  
- Low: <5 green flags, 4+ red flags  

**Output:** Executive summary with clear SEO health rating and priority issues.

## Step 6: Content & SEO Advisor
**Role:** Content & SEO Advisor  
**Input:** All previous analysis  

**Task:** Create actionable Hebrew recommendations:  
For each major issue found, structure as:  
**בעיה:** [Describe problem in Hebrew]  
**למה זה חשוב:** [Impact on business in Hebrew]  
**פתרון פשוט:** [Step-by-step fix in Hebrew]  

**Prioritization:**  
1. Quick wins (can fix in 1-2 hours)  
2. Medium effort (needs few days/weeks)  
3. Long-term improvements (ongoing work)  

Focus on:  
- Missing meta descriptions  
- Weak title tags  
- Poor mobile experience  
- Slow loading pages  
- Missing alt text  

**Output:** Hebrew action plan with timeline and business impact for each recommendation.
