**VALIDITY OF SCREENING TESTS: HIGH-YIELD EXAM NOTES**

**I. THE 2x2 CONTINGENCY TABLE FRAMEWORK** To understand the evaluation of a screening test, it is essential to set up a 2x2 contingency table comparing the screening test results against the "true" diagnosis (usually determined by a gold-standard diagnostic test).

|Screening Test Results|Diseased (True Status)|Not Diseased (True Status)|Total|
|:--|:--|:--|:--|
|**Positive**|**a** (True-Positive)|**b** (False-Positive)|**a + b**|
|**Negative**|**c** (False-Negative)|**d** (True-Negative)|**c + d**|
|**Total**|**a + c**|**b + d**|**a + b + c + d**|

- **a (True-Positive):** Individuals found positive on the test who actually have the disease.
- **b (False-Positive):** Individuals who have a positive test result but do NOT have the disease.
- **c (False-Negative):** Individuals with a negative test result who actually HAVE the disease.
- **d (True-Negative):** Individuals with a negative test result who do NOT have the disease.

---

**II. SENSITIVITY**

- **First Principles Understanding:** Sensitivity represents the ability of a test to identify correctly _all those who have the disease_. It looks only at the diseased column. It answers the question: "Of all the people who truly have the disease, what proportion tested positive?"
- **Formula:** $$\text{Sensitivity} = \frac{a}{a + c} \times 100$$ _(True Positives / Total True Diseased)_
- **High-Yield Interpretation:** A 90% sensitivity means that 90% of the diseased people screened will give a "true-positive" result, and the remaining 10% will give a "false-negative" result. A highly sensitive test has very few false-negatives.

---

**III. SPECIFICITY**

- **First Principles Understanding:** Specificity is defined as the ability of a test to identify correctly _those who do not have the disease_. It looks only at the non-diseased column. It answers the question: "Of all the people who are truly disease-free, what proportion tested negative?"
- **Formula:** $$\text{Specificity} = \frac{d}{b + d} \times 100$$ _(True Negatives / Total True Non-Diseased)_
- **High-Yield Interpretation:** A 90% specificity means that 90% of the non-diseased persons will give a "true-negative" result, and 10% will be wrongly classified as "diseased" (false-positives). A highly specific test has very few false-positives.
- _Note on Inverse Relationship:_ In tests with continuous variables (like blood sugar), sensitivity and specificity are inversely related; increasing sensitivity (by lowering the cut-off) decreases specificity, and vice versa.

---

**IV. POSITIVE PREDICTIVE VALUE (PPV)**

- **First Principles Understanding:** While sensitivity and specificity are inherent properties of the test, predictive accuracy reflects the diagnostic power of the test in the field. The PPV indicates the probability that a patient with a positive test result has, in fact, the disease in question. It looks across the positive test row. It answers: "If my test result is positive, what are the actual chances I have the disease?"
- **Formula:** $$\text{Predictive Value of a Positive Test} = \frac{a}{a + b} \times 100$$ _(True Positives / Total Test Positives)_
- **High-Yield Interpretation:** Predictive accuracy depends heavily on disease prevalence. The more prevalent a disease is in a given population, the more accurate the predictive value of a positive test will be. Conversely, if the disease is rare, the PPV drops significantly because the number of false-positives outnumbers the true-positives.

---

**V. NEGATIVE PREDICTIVE VALUE (NPV)**

- **First Principles Understanding:** This is the probability that a patient with a negative test result is truly free of the disease. It looks across the negative test row. It answers: "If my test result is negative, what are the chances I am truly disease-free?"
- **Formula:** $$\text{Predictive Value of a Negative Test} = \frac{d}{c + d} \times 100$$ _(True Negatives / Total Test Negatives)_


**VALIDITY OF SCREENING TESTS: FALSE POSITIVES AND FALSE NEGATIVES (HIGH-YIELD EXAM NOTES)**

**I. PERCENTAGE OF FALSE-NEGATIVES**

- **First Principles & Concept:** The term "false-negative" means that patients who actually have the disease are told that they do not have the disease. It amounts to giving the diseased individual a "false reassurance".
- **Formula:** Based on the standard 2x2 contingency table, the percentage of false-negatives is calculated out of the total number of individuals who truly have the disease. $$\text{Percentage of false-negatives} = \frac{c}{a + c} \times 100$$ _(Where 'c' = False-negatives, and 'a + c' = Total truly diseased individuals)_.
- **Relationship with Sensitivity:** A screening test which is very sensitive has few "false-negatives". Conversely, the lower the sensitivity of a test, the larger the number of false-negatives it will yield.
- **Clinical & Public Health Significance:** A false-negative result can be highly detrimental. The patient with a "false-negative" test result might ignore the subsequent development of signs and symptoms and may postpone seeking treatment. This is especially dangerous if the disease in question is a serious one and the screening test is unlikely to be repeated within a short period of time.

**II. PERCENTAGE OF FALSE-POSITIVES**

- **First Principles & Concept:** The term "false-positive" means that normal, healthy patients who do not have the disease are incorrectly told that they have the disease.
- **Formula:** Based on the standard 2x2 contingency table, the percentage of false-positives is calculated out of the total number of individuals who are truly disease-free. $$\text{Percentage of false-positives} = \frac{b}{b + d} \times 100$$ _(Where 'b' = False-positives, and 'b + d' = Total truly non-diseased individuals)_.
- **Relationship with Specificity:** A screening test with a high specificity will yield very few false-positives.
- **Clinical & Public Health Significance:** False-positives pose a significant administrative and psychological burden. Normal healthy people are subjected to further unnecessary diagnostic tests, causing them inconvenience, discomfort, psychological anxiety, and financial expense until their freedom from the disease is conclusively established. Furthermore, a high rate of false-positives overburdens the health system's diagnostic facilities and brings discredit to the mass screening programmes.

_(Note: In clinical and epidemiological practice, no screening test is perfect; that is, no test is 100 per cent sensitive and 100 per cent specific, meaning every test will inherently have some percentage of false-positives and false-negatives.)_