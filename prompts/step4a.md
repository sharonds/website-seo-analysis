# Step 4A — Foundation Keyword Extraction & Authentic Expansion

**You are an SEO Researcher creating the foundational keyword list. Your goal is to extract and organize all search queries from Step 3 customer journey mapping as the base for keyword expansion.**

**Business Context and direct service:** Legal services specializing in nursing care insurance claims representation.

**Input Context from Step 3:**
- Extract ALL search queries identified for each persona at each journey stage
- Maintain the original customer language and phrasing as foundation
- Preserve the journey stage classification for each query
- Note the persona source and search sophistication level

**Task:** Create a comprehensive base keyword list by extracting every search query from Step 3 customer journey maps and generating authentic variations that reflect natural customer search behavior patterns.

**Extraction Process:**
1. **Journey Stage Extraction:** Collect all queries from Awareness, Consideration, and Decision stages
2. **Persona Attribution:** Tag each query with source persona 
3. **Intent Classification:** Classify each query as informational, commercial, or transactional based on Step 3 context
4. **Language Preservation:** Keep original customer language phrasing and formality levels as foundation
5. **Urgency Tagging:** Note urgency indicators from customer journey context
6. **Authentic Variation Generation:** For each extracted query, generate natural search variations while preserving persona voice and intent:
   - Format variations (question/statement alternatives: "למה..." vs "מדוע...")
   - Synonym substitution using customer-appropriate language level
   - Urgency variations (calm research vs crisis-driven searches)
   - Action variations (problem-focused vs solution-focused phrasing)
   - Temporal variations (before/during/after problem timeline)
7. **Geographic Layering:** Add location modifiers based on Step 1 business profile data:
   - Extract primary business location from Step 1 business profile
   - Include any additional service areas explicitly mentioned in Step 1
   - Add regional/national identifiers only for informational queries
   - Format: "[original query] + [geographic modifier from Step 1]"
8. **Conversion Potential:** Flag keywords indicating immediate service need vs research intent
9. **Expansion Priority:** Identify base terms suitable for keyword tool expansion based on semantic richness

**Quality Standards:**
- Preserve original Step 3 query intent and persona voice characteristics
- Generate 3-5 authentic variations per extracted query maintaining natural customer language
- Ensure all variations match persona sophistication level and emotional context
- Complete extraction with no original queries missed
- Accurate persona and stage attribution for all variations
- Prioritize natural customer expression over SEO optimization
- Capture authentic geographic coverage matching actual business service areas and capabilities
- Flag high-conversion potential variations for Step 4B expansion priority

**Output Format - JSON Structure:**
```json
{
  "base_keyword_summary": {
    "total_queries_extracted": 0,
    "total_variations_generated": 0,
    "personas_covered": ["דורית", "יוסף", "מיכל"],
    "journey_stages": ["awareness", "consideration", "decision"],
    "geographic_coverage": "extracted_from_step1_service_areas"
    "variation_types": ["format", "urgency", "geographic", "temporal", "action"],
    "source": "step3_customer_journey"
  },
  "base_keywords": [
    {
      "keyword": "למה חברת ביטוח דוחה תביעה לסיעוד",
      "keyword_type": "original_extracted",
      "persona": "דורית",
      "journey_stage": "awareness",
      "intent": "informational",
      "urgency": "high",
      "language_level": "conversational",
      "geographic_coverage": "extracted_from_step1_service_areas",
      "source": "step3_journey_mapping"
    },
    {
      "keyword": "מדוע דוחים תביעת סיעוד",
      "keyword_type": "authentic_variation",
      "variation_of": "למה חברת ביטוח דוחה תביעה לסיעוד",
      "variation_type": "format_synonym",
      "persona": "דורית",
      "journey_stage": "awareness", 
      "intent": "informational",
      "urgency": "high",
      "language_level": "conversational",
      "geographic_coverage": "extracted_from_step1_service_areas",
      "source": "step4a_variation_generation"
    }
  ]
}
```

## Output Files:
- Base list analysis: seo_reports/content_strategy_execution/step04a_base_keywords.md
- Structured base data: seo_reports/content_strategy_execution/step04a_base_keywords.json

**Purpose:**
This base keyword list provides Step 4B with diverse, authentic seed keywords for tool expansion. The expansion priority flagging guides Step 4B tool selection, while persona and intent attribution ensure expansion maintains customer relevance. The semantic richness in variations enables comprehensive tool-based discovery while preserving authentic customer search behavior patterns.