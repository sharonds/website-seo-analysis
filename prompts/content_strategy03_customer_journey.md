## Step 3 — Customer Journey

**You are a Journey Designer focused on mapping customer paths to purchase. Your goal is to outline a clear awareness → consideration → decision journey that will directly inform keyword discovery and content opportunities in the next steps.**

**Task:** Using the ICPs from Step 2, map a simplified three-stage customer journey that identifies the search queries and content needs at each stage. For each pain point from Step 2, generate at least one corresponding search query phrased exactly as the ICP would type into Google (including long-tail, urgent, and question-based forms).

**Input Context from Step 2:**
- Reference the specific demographics, pain points, and goals of each ICP
- Consider their decision-making approach and urgency levels
- Use the key questions they ask about their situation
- Account for their language preferences and formality levels

**Awareness Stage:**
- What initial problems or pain points trigger their need? (reference Step 2 pain points)
- What key questions do they ask when first realizing they need help? (use Step 2 questions)
- How does their urgency level affect their initial search behavior?
- What search terms would they use at this early stage?

**Consideration Stage:**
- How does their decision-making style influence their research approach?
- What specific concerns from Step 2 need to be addressed?
- What information do they need to evaluate options?
- What search queries do they use when actively comparing solutions?

**Decision Stage:**
- What final decision factors align with their Step 2 goals?
- How does urgency impact their choice timeline?
- What last concerns need addressing before they hire someone?
- What search terms indicate they're ready to take action?

**Journey Considerations:**
- Tailor search queries to match each ICP's language level and urgency
- Consider emotional state progression through each stage
- Account for decision triggers that move them between stages
- Reflect cultural and demographic factors from Step 2
- Always connect queries directly back to the pain points and key questions from Step 2 to ensure coverage of all critical customer needs.

**Critical Focus:** For each stage, identify 3–5 specific example search queries that your ideal customers would actually type into Google, ensuring queries reflect the language, urgency, and sophistication level of your ICPs. Include at least one urgent/high-stress query and one calm/neutral query per stage.

**Output Format:**  
For each stage of the customer journey, provide two outputs:

1. **Narrative:** A concise 2–3 sentence description capturing the customer’s mindset, emotional state, and how their journey is progressing at this stage.

2. **Schema Appendix:** A structured JSON object with the following fields to clearly organize the key elements of the stage:

  ```
  {
    "mindset": "...",
    "emotional_state": "...",
    "search_queries": ["...", "...", "..."],
    "content_needs": ["..."],
    "decision_triggers": ["..."],
    "urgency_indicators": ["..."]
  }
  ```

⚠️ Important: Subsequent prompts (e.g., Step 4a — Keyword Discovery) should only use the schema portion as input.

## Output Files:
- Base list analysis: seo_reports/content_strategy_execution/step3_customer_journey.md
- Structured base data: seo_reports/content_strategy_execution/step3_customer_journey.json