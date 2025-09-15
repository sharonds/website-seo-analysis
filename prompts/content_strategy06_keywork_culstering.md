## Step 6 — Keyword Clustering

**You are an SEO Strategist specializing in keyword organization and content planning. Your goal is to group keywords from Step 5 into logical clusters that represent distinct content opportunities with specific content type recommendations for Step 7's foundational content plan.**

**Business Context and direct service:** Legal services specializing in nursing care insurance claims representation.

**Task:** Organize the keyword list from Step 5 into strategic clusters using these criteria:

**Input Context from Step 5:**
- Use the keyword metrics data including search volumes, difficulty scores, and data confidence levels
- Reference keywords with confirmed data vs business-priority keywords
- Consider the competition assessment for each keyword

**Input Context from Step 2 & 3:**
- Reference the persona characteristics and journey stages
- Consider the urgency levels and decision-making patterns
- Account for the business specialization and customer needs

**Task:** Organize keywords into semantic clusters based on topic similarity and business function alignment.

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
  "clustering_summary": {
    "total_keywords_clustered": 0,
    "total_clusters_created": 0,
    "clustering_date": "YYYY-MM-DD"
  },
  "keyword_clusters": [
    {
      "cluster_name": "descriptive_cluster_name",
      "cluster_theme": "main_topic_focus",
      "target_personas": ["דורית", "יוסף", "ד״ר רחל"],
      "journey_stages": ["awareness", "consideration", "decision"],
      "business_alignment": "how_this_serves_step1_services",
      "keywords": [
        {
          "keyword": "keyword_term",
          "role_in_cluster": "primary/supporting/related"
        }
      ]
    }
  ]
}
```

**Output Files:**
- Metrics analysis: seo_reports/content_strategy_execution/step06_clustering.md
- Keyword metrics data: seo_reports/content_strategy_execution/step06_clustering.json

**Purpose:** These clusters with content type recommendations will directly translate into the structured content plan in Step 7, ensuring each piece has the optimal format for its keyword intent and user needs.