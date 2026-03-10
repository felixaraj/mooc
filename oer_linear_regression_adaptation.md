# OER Adaptation: Linear Regression (One-Page) for SWAYAM

## 1) Selected Open Textbook Chapter

**Provider chosen:** OpenStax

### TASL
- **Title:** *Introductory Statistics 2e* — Chapter: **Linear Regression and Correlation**
- **Author:** OpenStax (Rice University)
- **Source:** OpenStax textbook page and chapter content (publicly available online)
- **License:** **Creative Commons Attribution 4.0 International (CC BY 4.0)**

> Note: This adaptation preserves core concepts while compressing chapter-level content into a one-page bilingual teaching aid suitable for higher-education instructors.

---

## 2) Adapted One-Page Lesson Handout (English + Tamil)

**Audience:** Teachers from higher educational institutions  
**Context:** SWAYAM online course delivery  
**Format:** Lesson handout + infographic-style quick reference

## Linear Regression & Correlation — Faculty Handout (One Page)

### A. Learning Outcomes / கற்றல் விளைவுகள்
By the end, learners can:  
1. Explain correlation vs. regression.  
2. Interpret slope and intercept in context.  
3. Use and interpret \(r\) and \(R^2\).  
4. Check key assumptions and identify misuse.

பாடம் முடிவில் கற்றவர்கள்:  
1. தொடர்பு (correlation) மற்றும் பின்னூட்டம் (regression) வித்தியாசத்தை விளக்க முடியும்.  
2. slope மற்றும் intercept-ஐ சூழலில் பொருள் கூற முடியும்.  
3. \(r\), \(R^2\) மதிப்புகளை விளக்க முடியும்.  
4. முக்கிய assumptions-ஐ சரிபார்த்து தவறான பயன்பாட்டை கண்டறிய முடியும்.

---

### B. Core Ideas / மையக் கருத்துகள்
- **Correlation** measures strength and direction of linear association between two quantitative variables.
  - \(r\in[-1,1]\): sign = direction; magnitude = strength.
- **Simple linear regression** models prediction:
  - \(\hat y=b_0+b_1x\)
  - \(b_1\): expected change in \(y\) for 1-unit increase in \(x\)
  - \(b_0\): predicted \(y\) when \(x=0\) (interpret only if meaningful)
- **Goodness of fit:**
  - \(R^2\): proportion of variation in \(y\) explained by \(x\) via the model.

- **Correlation:** இரண்டு அளவியல் மாறிகள் (quantitative variables) இடையிலான நேர்க்கோட்டு தொடர்பின் திசை + வலிமையை அளவிடும்.  
- **Simple Linear Regression:** \(x\) மூலம் \(y\)-ஐ கணிக்க உதவும் மாதிரி: \(\hat y=b_0+b_1x\).  
- **\(R^2\):** மாதிரி \(y\)-இல் உள்ள மாறுபாட்டில் எவ்வளவு பகுதியை விளக்குகிறது என்பதைக் காட்டும்.

---

### C. Minimum Assumptions (LINE) / அவசிய முன்னிலை விதிகள்
Use LINE checks before interpreting model quality:
- **L — Linearity:** Scatter plot roughly linear.
- **I — Independence:** Observations independent.
- **N — Normality of residuals:** Approx. normal (for inference).
- **E — Equal variance:** Residual spread roughly constant.

LINE சரிபார்ப்புகள்:
- **L:** தரவு சுமார் நேர்க்கோட்டாக இருக்க வேண்டும்.  
- **I:** கண்காணிப்புகள் ஒன்றின் மீது ஒன்று சார்ந்திருக்கக் கூடாது.  
- **N:** residuals சுமார் normal.  
- **E:** residual spread எல்லா \(x\)-இலும் சுமார் சமமாக இருக்க வேண்டும்.

---

### D. Interpretation Template for Instructors / கற்பித்தலுக்கான விளக்க மாதிரி
**English template:**  
“For every 1-unit increase in **X**, predicted **Y** changes by **\(b_1\)** units on average. The model explains **\(R^2\times100\)%** of variance in **Y**. These results indicate association, not causation.”

**Tamil template:**  
“**X** 1 அலகு அதிகரிக்கும்போது, **Y** சராசரியாக **\(b_1\)** அலகுகள் மாறும் என மாதிரி கணிக்கிறது. **Y**-இல் உள்ள மாறுபாட்டின் **\(R^2\times100\)%** பகுதியை மாதிரி விளக்குகிறது. இது காரணம்-விளைவு என்பதை நிரூபிக்காது; தொடர்பை மட்டும் காட்டுகிறது.”

---

### E. Frequent Misconceptions / பொதுவான தவறான புரிதல்கள்
1. High \(r\) or high \(R^2\) **does not** prove causation.  
2. Regression line is not reliable for extreme extrapolation beyond observed \(x\)-range.  
3. Outliers can strongly change slope and correlation.  
4. Nonlinear data can produce misleading low/high linear metrics.

1. அதிக \(r\), \(R^2\) இருந்தாலும் அது காரணத் தொடர்பை நிரூபிக்காது.  
2. பார்த்த \(x\)-range-க்கு வெளியே கணிப்பு நம்பகமல்ல.  
3. Outliers, slope மற்றும் correlation-ஐ அதிகமாக பாதிக்கலாம்.  
4. நேரற்ற (nonlinear) தரவை நேர்க்கோட்டாக அணுகினால் தவறான முடிவுகள் கிடைக்கலாம்.

---

### F. 20-Minute SWAYAM Delivery Plan / SWAYAM குறுநேர கற்பித்தல் திட்டம்
- **Minute 0–5:** Concept intro + scatterplot intuition.
- **Minute 5–10:** Equation, slope/intercept interpretation.
- **Minute 10–15:** \(r\), \(R^2\), assumptions (LINE).
- **Minute 15–20:** One example + one misconception check quiz.

- **0–5 நிமிடம்:** scatterplot மூலம் கருத்து அறிமுகம்.  
- **5–10:** regression equation, slope/intercept விளக்கம்.  
- **10–15:** \(r\), \(R^2\), LINE assumptions.  
- **15–20:** உதாரணம் + misconception quiz.

---

## 3) Infographic-Ready Version (Text Blocks)

### Block 1: What is it?
**EN:** Linear regression predicts Y from X using a best-fit line.  
**TA:** Linear regression என்பது X மூலம் Y-ஐ சிறந்த நேர்கோட்டால் கணிக்கும் முறை.

### Block 2: Key Formula
**EN/TA:** \(\hat y=b_0+b_1x\)

### Block 3: Strength Indicators
**EN:** Correlation \(r\): direction + strength; \(R^2\): explained variance.  
**TA:** \(r\): திசை + வலிமை; \(R^2\): விளக்கப்பட்ட மாறுபாடு.

### Block 4: Caution
**EN:** Association \(\neq\) causation. Avoid blind extrapolation.  
**TA:** தொடர்பு \(\neq\) காரணம். அளவுக்கு மீறிய extrapolation தவிர்க்கவும்.

### Block 5: Teaching Tip
**EN:** Always show scatterplot + residual check before conclusion.  
**TA:** முடிவு சொல்லும் முன் scatterplot மற்றும் residual check காட்டவும்.

---

## 4) Reuse & Attribution Statement (for SWAYAM page footer)
“This material adapts content from OpenStax *Introductory Statistics 2e* (Linear Regression and Correlation chapter), licensed under CC BY 4.0. Changes include condensation, bilingual translation (English/Tamil), and reformatting into one-page handout and infographic text.”
