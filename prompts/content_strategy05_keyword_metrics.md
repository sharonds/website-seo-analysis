## Step 5 — Keyword Metrics (Optional)

**Business Context:** [Insert business context from Step 1]

**You are an SEO Analyst focused on keyword prioritization through data analysis. Your goal is to add quantitative context to keyword opportunities from Step 4D using DataForSEO MCP tools for strategic decision-making in Step 6 clustering.**

**Input Context from Step 4D:**
- Use the filtered keyword list with business relevance and intent classifications
- Reference the source phase attribution for each keyword
- Consider the inclusion reasons documented for context

**Task:** For the keyword list from Step 4D, gather and analyze available metrics using DataForSEO MCP tools:

**Primary Metrics to Collect:**
- Monthly search volume data
- Keyword difficulty/competition scores
- Search trends data
- SERP feature presence (featured snippets, local pack, etc.)

**DataForSEO MCP Tools:**
- `dataforseo:dataforseo_labs_google_keyword_overview`
- `dataforseo:dataforseo_labs_bulk_keyword_difficulty`
- `dataforseo:serp_organic_live_advanced`

**No Data Strategy:**
- **Preserve High-Relevance Keywords:** Keep keywords with strong business relevance even if no search data
- **Document Data Confidence:** Mark each keyword's data reliability level
- **Prioritize Business Value:** For niche markets, business relevance overrides search volume
- **Unknown Volume Handling:** Document when volume data is unavailable without making assumptions

**Assessment Framework:**
- **High Priority:** Any business relevance + any measurable volume
- **Strategic Value:** High business relevance + no volume data
- **Medium Priority:** Lower relevance + confirmed volume
- **Quick Wins:** Low competition + any relevance

**Output Format - JSON Structure:**
```json
{
  "metrics_summary": {
    "keywords_analyzed": 0,
    "keywords_with_data": 0,
    "keywords_no_data": 0,
    "analysis_date": "YYYY-MM-DD"
  },
  "keyword_metrics": [
    {
      "keyword": "keyword_term",
      "monthly_searches": 0,
      "difficulty": "high/medium/low",
      "competition": "high/medium/low",
      "data_confidence": "confirmed/estimated/unknown",
      "business_priority": "high/medium/low",
      "strategic_rationale": "why_this_keyword_matters"
    }
  ]
}```

Output Files:

Metrics analysis: seo_reports/step05_keyword_metrics.md
Keyword metrics data: seo_reports/step05_metrics.json

Purpose: This metrics analysis provides data context for Step 6 clustering while acknowledging niche market realities and preserving business-relevant keywords regardless of search volume.