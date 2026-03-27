---

## 🔬 The Science: Analysis Logic

ASLAB uses standard psychometric formulas to evaluate test quality. Here is how the "Smarter Insights" are calculated:

### 1. Difficulty Index ($P$)
This measures how easy or hard a question is by calculating the percentage of students who got it right.
*   **Formula:** $P = \frac{R}{N}$ (Right answers / Total students)
*   **Interpretation:** 
    *   **> 0.70:** Very Easy (Consider moving to the start of the test)
    *   **0.30 – 0.70:** Ideal Difficulty (The "Sweet Spot")
    *   **< 0.30:** Very Hard (Check for confusing wording or untaught topics)

### 2. Discrimination Index ($D$)
This determines if the question can distinguish between high-performing and low-performing students. ASLAB uses the **Kelley's 27% Rule**.
*   **Method:** We compare the number of correct hits in the **Upper 27%** of the class vs. the **Lower 27%**.
*   **Formula:** $D = \frac{U - L}{n}$
*   **Interpretation:**
    *   **> 0.40:** Excellent (Keep)
    *   **0.20 – 0.39:** Good/Fair (Revise)
    *   **< 0.19:** Poor (Remove)
    *   **Negative Value:** Alert! This means struggling students got it right while top students got it wrong (likely a "trick" question or a keying error).

### 3. Smart Action Labels
Based on the intersection of $P$ and $D$, ASLAB automatically flags items:
*   ✅ **KEEP:** High discrimination and balanced difficulty.
*   ⚠️ **REVISE:** Low discrimination or extreme difficulty; needs wording tweaks.
*   🚫 **REMOVE:** Negative discrimination or 0% success rate.
