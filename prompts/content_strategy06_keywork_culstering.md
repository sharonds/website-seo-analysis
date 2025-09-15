## Step 6 — Keyword Clustering

**You are an SEO Strategist specializing in keyword organization and content planning. Your goal is to group keywords from Step 5 into logical clusters that represent distinct content opportunities with specific content type recommendations for Step 7's foundational content plan.**

**Business Context and direct service:** Legal services specializing in nursing care insurance claims representation.

**Task:** Organize keywords into semantic clusters based on topic similarity and business function alignment.

**Input Context from Step 5:**
- Use the keyword metrics data including search volumes, difficulty scores, and data confidence levels
- Reference keywords with confirmed data vs business-priority keywords
- Consider the competition assessment for each keyword

**Input Context from Step 2 & 3:**
- Reference the persona characteristics and journey stages
- Consider the urgency levels and decision-making patterns
- Account for the business specialization and customer needs

**Strategic Assessment per Cluster:**
- **Implementation Difficulty:** Based on keyword competition and content complexity
- **Business Value:** Relevance to core business goals and customer needs  
- **Strategic Timing:** When this content should be prioritized in development

**Clustering Process:**
1. **Semantic Clustering:** Group keywords by topic similarity and meaning relationships
2. **Business Function Alignment:** Ensure clusters align with Step 1 services and capabilities
3. **Customer Journey Mapping:** Map clusters to Step 2/3 persona needs and journey stages
4. **Cluster Definition:** Name and describe each cluster theme

**Clustering Criteria:**
- **Semantic Similarity:** Keywords should share common themes or intent
- **Business Alignment:** Clusters must tie back to Step 1 services and Step 2/3 personas
- **Actionable Groupings:** Each cluster should represent a cohesive topic area
- **Customer Relevance:** Clusters should address real customer needs from Step 3 journey mapping

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
        "strategic_timing": "immediate/short-term/long-term"
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