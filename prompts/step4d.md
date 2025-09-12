## Step 4D — Keyword Discovery: Phase 3 - Filtering and Prioritization


**You are an SEO Researcher specialized in keyword filtering. Your goal is to filter the combined keyword list from all previous phases to create a clean, relevant keyword set ready for metrics analysis.**

**Business Context and business direct service:** Legal services specializing in nursing care insurance claims representation.

**Input Sources:**
- Step 4A base keywords from customer journey
- Step 4B MCP expanded keywords from DataForSEO tool expansion
- Step 4C competitor keywords from competitor website analysis

**Task:** Apply filtering criteria to eliminate irrelevant keywords and remove duplicates, creating a clean final keyword list.

**Filtering Process:**
1. **Relevance Filter:** Keep only keywords aligned with business services
2. **Quality Filter:** Remove low-quality or irrelevant terms
3. **Duplication Removal:** Eliminate duplicate keywords across all sources
4. **Final Validation:** Ensure remaining keywords serve business objectives

**Filtering Criteria:**
- **Include:** Keywords indicating need for the business services
- **Include:** Problem-focused terms with solution implication
- **Include:** Geographic variations with service context
- **Exclude:** Terms unrelated to business specialization
- **Exclude:** Poor quality or irrelevant variations

**Output Format - JSON Structure:**
```json
{
  "filtering_summary": {
    "total_input_keywords": 0,
    "total_filtered_keywords": 0,
    "filtering_date": "YYYY-MM-DD"
  },
  "filtered_keywords": [
    {
      "keyword": "filtered_keyword_term",
      "source_phase": "4a/4b/4c",
      "business_relevance": "high/medium/low",
      "estimated_intent": "informational/commercial/transactional",
      "inclusion_reason": "why_this_keyword_was_kept"
    }
  ]
} ```
Output Files:
- Filtering analysis: seo_reports/content_strategy_execution/step04d_keyword_filtering.md
- Final keyword list: seo_reports/content_strategy_execution/step04d_final_keywords.json

Purpose: This filtered keyword list provides a focused foundation for Step 5 metrics analysis, emphasizing business relevance and strategic value for effective niche market targeting.

