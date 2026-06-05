# Nutrition Science | Childhood Stunting Dietary Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Children and Adolescents with Stunting (2023 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Children and Adolescents with Stunting (2023 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Height assessment criteria**: complete height reference tables for ages 2–5 and 6–17, including 3rd-percentile cutoffs
- **Dietary-nutrition principles**: 6 official principles centered on growth and development needs
- **TCM dietary support**: 7 syndrome patterns plus 9 dietary formulas
- **Regional menus**: 5 regions, each with 3 days of sample menus
- **Food exchange tables**: 7 food categories for flexible meal planning
- **Growth monitoring guidance**: regular height and weight measurement and growth-curve tracking
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Stunting criterion (ages 2–5) | Height below the 3rd percentile for same age and sex | Shorter than 97% of peers |
| Stunting criterion (ages 6–17) | Height below the 3rd percentile for same age and sex | Same principle; timely intervention is needed |
| Protein (school-age children) | Adequate high-quality protein | One cup of milk plus one egg daily |
| Dairy | ≥300 mL/day | Start with one cup of milk |
| Vitamin D | 400 IU/day | Supplement if sun exposure is insufficient |
| Outdoor activity | ≥1 hour/day | Sunlight plus movement |
| Sleep (school-age children) | 9–11 hours/night | Growth hormone secretion is strongest at night |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~06 | Six dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-07~11 | Appendix knowledge: food choices, exchange tables, menus, formulas, assessment criteria | Appendices 1–5 |
| KPK-12~13 | Disease background + Q&A | Preface + disease characteristics + Q&A version |

## File Structure

```text
- SKILL.md: Main skill entry file
- system_prompt.md: System prompt with 8-module configuration
- skill.yaml: Skill metadata
- knowledge_base.md: Knowledge-base overview index
- kpk_principles.md: KPK-01~06 dietary principles
- kpk_appendix.md: KPK-07~11 appendix knowledge
- kpk_disease_qa.md: KPK-12~13 disease background + Q&A
- dietary_formulas.md: 9 dietary formulas
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medical diagnosis or medication treatment.
2. Stunting may have pathological causes; medical evaluation is recommended first.
3. Consult a physician or nutrition professional before using food-medicine substances.
4. Formula portions use an 8-year-old school-age child as an example; other ages require portion adjustment.
5. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT

<!-- Maintainer update: Runyuan Wang (9s5bz2jvd2-lang). -->
