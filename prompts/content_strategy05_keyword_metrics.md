# Content Strategy 05: Keyword Metrics Analysis Prompt

**מועד:** 12 ספטמבר 2025  
**שלב:** Step 5 - Keyword Metrics & Prioritization  
**כלי:** DataForSEO MCP Tools

---

## המטלה המקורית

**You are an SEO Analyst focused on keyword prioritization through data analysis. Your goal is to add quantitative context to keyword opportunities from Step 4 using DataForSEO MCP tools for strategic decision-making in Step 6 clustering.**

**Task:** For the keyword list from Step 4, gather and analyze available metrics using DataForSEO MCP tool:

**Primary Metrics to Collect:**
- Monthly search volume data
- Keyword difficulty/competition scores  
- Search trends data
- SERP feature presence (featured snippets, local pack, etc.)

**DataForSEO MCP Research Process:**
1. **Bulk Keyword Analysis:** Use DataForSEO tools to process the keyword list efficiently
2. Note data gaps for low-volume niche terms
3. Document data confidence levels
4. **Intent Validation:** Analyze SERP results to confirm search intent classification
5. **Geographic Relevance:** Focus on location-specific data for local keywords
6. **USE**: dataforseo:dataforseo_labs_google_keyword_overview, dataforseo:dataforseo_labs_bulk_keyword_difficulty, dataforseo:serp_organic_live_advanced

**Assessment Framework:**
- **High Priority:** Good volume + manageable difficulty + clear business relevance
- **Medium Priority:** Lower volume but high relevance OR higher volume but more challenging  
- **Long-term Targets:** High volume + high difficulty but strategically important
- **Quick Wins:** Low competition + decent relevance for early content wins
- **Unknown:** Mark clearly when data is unavailable rather than estimating

---

## התהליך שבוצע

### כלי DataForSEO שנוצלו:
1. **`mcp_dataforseo_dataforseo_labs_google_keyword_overview`** - נפח חיפוש, CPC, תחרות
2. **`mcp_dataforseo_dataforseo_labs_bulk_keyword_difficulty`** - ציוני קושי
3. **`mcp_dataforseo_serp_organic_live_advanced`** - ניתוח SERP ופיצ׳רים

### מתודולוגיה:
1. **הכנת נתונים:** עיבוד 124 מילות מפתח מ-Step 4
2. **איסוף מטריקות:** שליפת נתונים עבור מילות מפתח ליבה
3. **ניתוח SERP:** בדיקת תחרות ופיצ׳רים (Local Pack, Video, etc.)
4. **חישוב עדיפויות:** אלגוריתם ציונים (נפח + קושי + רלוונטיות עסקית)
5. **יצירת מאגר:** JSON מובנה עם כל הנתונים

### תוצאות מרכזיות:
- **📈 מילת מפתח ראשית:** "ביטוח סיעודי" (3,600 חיפושים/חודש)
- **🎯 הזדמנות מסחרית:** "תביעת ביטוח סיעודי" (260 חיפושים, KD=1)
- **🥇 Quick Win:** "מה זה ביטוח סיעודי" (140 חיפושים, KD=9)
- **🌍 Local Pack:** דומיננטי בתחום, דורש אסטרטגיית Local SEO

---

## קבצי פלט

### קבצים שנוצרו:
1. **`seo_reports/step5_keyword_metrics.md`** - דוח מקיף עם תובנות ואסטרטגיות
2. **`seo_reports/keyword_metrics_export.json`** - מאגר נתונים מובנה לעבודה
3. **`keyword_metrics_database.json`** - מאגר פעילות עם ציוני עדיפות
4. **`keywords_for_analysis.txt`** - רשימת מילות מפתח גולמית

### מבנה הנתונים:
```json
{
  "keyword": {
    "stage": "Awareness/Consideration/Decision/Local/Core",
    "category": "core service/question-based/problem-solving/etc",
    "intent": "Informational/Commercial/Transactional", 
    "search_volume": number,
    "keyword_difficulty": number,
    "cpc": number,
    "competition": number,
    "priority_score": calculated_score,
    "confidence": "high/medium/no_data"
  }
}
```

---

## תובנות למשך

### הצלחות:
- זיהוי מילת מפתח ראשית עם נפח גבוה
- גילוי פערי CPC משמעותיים בין אינפורמטיבי למסחרי
- ניתוח מעמיק של SERP המקומי
- יצירת מערכת דירוג אובייקטיבית

### אתגרים:
- 122 מילות מפתח ללא נתונים כמותיים  
- נדרש איסוף נתונים נוסף עבור Long-tail keywords
- חשיבות Local SEO לא הוערכה במלואה בתחילה

### המלצות לStep 6:
1. **קלסטרינג סמנטי:** קיבוץ מילות מפתח דומות לנושאים
2. **מיפוי תוכן:** התאמת מילות מפתח לדפי אתר ספציפיים
3. **אסטרטגיית Local SEO:** פיתוח דפים מקומיים ו-GMB
4. **לוח זמנים ליצירה:** עדיפויות ברורות ליצירת תוכן

---

## פרמטרים טכניים

**DataForSEO Configuration:**
- `language_code`: "he"
- `location_name`: "Israel"  
- `search_engine`: "google"
- `depth`: 10 (for SERP analysis)

**Priority Scoring Algorithm:**
- Volume Score: 0-50 points (weighted by search volume)
- Difficulty Score: 0-30 points (inverse of keyword difficulty)
- Business Score: 0-20 points (based on stage and intent)
- Total: 0-100 point scale

**Quality Control:**
- Cross-reference metrics across different endpoints
- Document data confidence levels 
- Flag unusual metrics for manual review
- Ensure geographic data alignment with target market