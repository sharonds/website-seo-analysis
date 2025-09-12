# All SEO Analysis Prompts

This file contains all the user prompts from the SEO analysis process for https://www.moshetabo.co.il.

## Step 1: Crawler / Data Collector
**Role:** Crawler / Data Collector  
**Target Website:** https://www.moshetabo.co.il  
**Task:** Perform initial website crawl and data collection:  
1. Scrape the homepage and identify 3-5 key service/product pages  
2. Extract from each page:  
   - Page title and meta description  
   - All heading tags (H1, H2, H3)  
   - First 200 words of body content  
   - All internal links  
   - Image count and alt text presence  
3. Create a site map structure showing page hierarchy  
4. Note primary language (Hebrew/English mix)  

**Output Format:** Structured data table with page URLs, titles, headings, and content snippets.

## Step 2: SEO Reviewer
**Role:** SEO Reviewer  
**Input:** Data from Step 1  

**Task:** Analyze on-page SEO elements:  
1. Title tag analysis: length, uniqueness, keyword presence  
2. Heading structure: H1 uniqueness, logical hierarchy (H1→H2→H3)  
3. Meta descriptions: presence, length (150-160 chars), compelling copy  
4. Content quality: Hebrew readability, keyword density, content length  
5. Internal linking: navigation structure, anchor text quality  
6. Image optimization: alt text coverage, file naming  

**Flag Issues:**  
- Missing or duplicate titles/meta descriptions  
- Poor heading hierarchy  
- Thin content (under 300 words)  
- Missing alt text  
- Weak internal linking  

**Output:** Issue checklist with severity (High/Medium/Low) for each finding.

## Step 3: Technical SEO Specialist
**Role:** Technical SEO Specialist  
**Target:** Same website from Step 1  

**Task:** Check foundational technical elements:  
1. Sitemap presence: Check /sitemap.xml and /sitemap_index.xml  
2. Robots.txt: Verify /robots.txt exists and isn't blocking important pages  
3. HTTPS: Confirm secure connection and no mixed content  
4. Mobile responsiveness: Test viewport and responsive design  
5. Page speed basics: Identify obvious speed blockers (large images, etc.)  
6. URL structure: Clean, descriptive URLs vs messy parameters  

**Technical Checks:**  
- Site loads properly on mobile/desktop  
- No broken internal links  
- Proper canonical tags if applicable  
- Basic site performance (loading time estimation)  

**Output:** Technical health scorecard with pass/fail for each element.

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
2. Identify top 3 critical issues impacting search visibility  
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
