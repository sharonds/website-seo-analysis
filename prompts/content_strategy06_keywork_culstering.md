## Step 6 — Keyword Clustering

**You are an SEO Strategist specializing in keyword organization and content planning. Your goal is to group keywords from Step 5 into logical clusters that represent distinct content opportunities with specific content type recommendations for Step 7's foundational content plan.**

**Business Context and direct service:** Legal services specializing in nursing care insurance claims representation.

**Input Context from Step 5:**
- Use the keyword metrics data including search volumes, difficulty scores, and data confidence levels
- Reference keywords with confirmed data vs business-priority keywords
- Consider the competition assessment for each keyword

**Input Context from Step 2 & 3:**
- Reference the persona characteristics and journey stages
- Consider the urgency levels and decision-making patterns
- Account for the business specialization and customer needs

**Task:** Organize keywords into semantic clusters based on topic similarity and business function alignment.

**Clustering Methodology:**
- **Semantic Similarity:** Keywords that address the same core topic or concept
- **Search Intent Alignment:** Keywords with similar user intent and expectations
- **Content Compatibility:** Keywords that would naturally fit in the same piece of content
- **Customer Journey Stage:** Group by awareness, consideration, or decision stage relevance

**Content Type Decision Framework:**
- **Service Pages:** Commercial intent keywords, direct service terms
- **Blog Posts:** Informational keywords, how-to queries, educational topics
- **FAQ Pages:** Question-based keywords, common concerns, troubleshooting
- **Guides/Resources:** Comprehensive topics, multi-step processes, detailed explanations
- **Landing Pages:** High-intent conversion terms, specific service requests

**Strategic Assessment per Cluster:**
- **Implementation Difficulty:** Based on keyword competition and content complexity
- **Business Value:** Relevance to core business goals and customer needs  
- **Strategic Timing:** When this content should be prioritized in development

**Organization Principles:**
- Each cluster should represent one potential piece of content
- Avoid keyword cannibalization by keeping similar intent terms together
- Match content type to search intent and user expectations
- Consider logical content depth for each cluster and format

**No-Data Prioritization Framework:**
When keywords lack search volume data, use these alternative signals:
- **Customer Urgency:** High-urgency persona needs from Step 3
- **Business Relevance:** Direct service keywords vs general information
- **Intent Strength:** Transactional > Commercial > Informational
- **Competitive Gaps:** Keywords competitors aren't targeting
- **Geographic Specificity:** Local modifiers indicate purchase intent

**Quality Standards:**
- Minimum 3-5 keywords per cluster (unless standalone high-value terms)
- Clear thematic connection between clustered keywords
- Content type aligns with keyword intent and business goals
- Actionable groupings with clear format recommendations

**Output Format - JSON Structure:**
```json
{
  "keyword_clusters": [
    {
      "cluster_name": "descriptive_topic_name",
      "primary_keyword": "main_target_term",
      "supporting_keywords": ["supporting_term_1", "supporting_term_2"],
      "search_intent": "informational/commercial/transactional",
      "customer_journey_stage": "awareness/consideration/decision",
      "content_type_recommendation": "service_page/blog_post/guide/faq/landing_page",
      "opportunity_assessment": {
        "implementation_difficulty": "easy/medium/hard",
        "business_value": "high/medium/low",
        "strategic_timing": "immediate/short-term/long-term",
        "data_confidence": "confirmed/estimated/business-priority"
      },
      "rationale": "why_this_clustering_and_content_type"
    }
  ]
}
```

**Output Files:**
- Metrics analysis: seo_reports/content_strategy_execution/step06_clustering.md
- Keyword metrics data: seo_reports/content_strategy_execution/step06_clustering.json

**Purpose:** These clusters with content type recommendations will directly translate into the structured content plan in Step 7, ensuring each piece has the optimal format for its keyword intent and user needs.