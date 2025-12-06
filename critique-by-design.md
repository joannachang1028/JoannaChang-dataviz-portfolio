| [Home Page](https://joannachang1028.github.io/JoannaChang-dataviz-portfolio/) | [Visualizing Government Debt](visualizing-government-debt) | [Critique by Design](critique-by-design) | [Final project I](final-project-part-one) | [Final project II](final-project-part-two) | [Final project III](final-project-part-three) |

# HPV Vaccination: Visualization Critique and Redesign Plan

## Step 1: The Visualization

For this assignment, I selected the visualization series from **“HPV vaccination: How the world can eliminate cervical cancer”** published by *Our World in Data*.  

🔗 **Source:** [Our World in Data – HPV vaccination](https://ourworldindata.org/hpv-vaccination-world-can-eliminate-cervical-cancer)

### **Why I Chose This Visualization**
I chose this set of visualizations because HPV vaccination is a highly consequential global health issue, and this article includes multiple charts exploring different aspects of cervical cancer prevention—from historical cervical cancer incidence in the UK, to global HPV vaccination policies, to cross-country differences in vaccination coverage.

The **first graphic**, showing *cervical cancer incidence by birth cohort in the UK*, particularly stood out to me. It clearly illustrates how dramatically cancer rates dropped among women who received the HPV vaccine as teenagers. The visualization isolates birth cohorts in a way that makes the impact of vaccination policies easy to grasp at a glance.

However, as the article progresses, the visualizations—while individually strong—begin to feel fragmented in their messaging. One chart shows incidence across different countries, another shows which countries have national HPV programs, and others show global vaccination coverage. Although each chart tells its own clear story, it’s harder for viewers to synthesize how policy adoption, vaccination rates, and cancer outcomes interrelate.  
➡️ This **lack of narrative cohesion** is what I plan to address in my redesign.

---

## Step 2: The Critique

### **Rubric Ratings**

| Category        | Score | Comments                                                                 |
|-----------------|:-----:|--------------------------------------------------------------------------|
| **Usefulness**  | 8/10  | Informative and insightful, especially the UK birth-cohort chart.       |
| **Completeness**| 8/10  | Strong individually, but lack a cohesive overarching narrative.          |
| **Perceptibility** | 7/10 | Clear visuals, but users must navigate multiple charts for full context.|
| **Truthfulness** | 9/10 | Accurate, transparent, and well-sourced data.                           |
| **Intuitiveness**| 8/10 | Good interactivity; some charts require prior context.                  |
| **Aesthetics**  | 7/10  | Clean OWID style; minor color contrast issues.                          |
| **Engagement**  | 7/10  | Interesting visuals, but fragmented structure limits immersion.          |

### **Overall Observations**
The visualizations are effective when viewed individually—each highlights a different aspect of HPV vaccination’s impact or global policy adoption.  
The **UK cohort chart** is especially impactful in showing how early vaccination prevents cervical cancer later in life.  
Interactive **world maps** also enhance engagement, allowing users to explore geographic variations and trends.

### **What Works Well**
- Strong interactivity (hovering, filtering, time series).
- Clear color coding and readable layouts.
- Effective storytelling within each individual visualization.
- Reliable and transparent data sources.

### **What Could Be Improved**
- Lack of **unified narrative** across charts.  
- Requires switching between graphs to see relationships among *policy*, *coverage*, and *incidence*.  
- Missing **integrated contextual layers** combining vaccination and outcome data.  
- Slight **color inconsistencies** reduce cohesiveness.

### **Redesign Focus**
For my redesign, I plan to:
- Improve **narrative cohesion** by integrating key dimensions (policy adoption, vaccination rates, and cancer outcomes).  
- Use **consistent color schemes** and **visual hierarchy** to tie the story together.  
- Explore **multi-layered visuals** to enhance intuitiveness and insight.

---

## Step 3: Sketch a solution

![Sketch for Redesign](https://raw.githubusercontent.com/joannachang1028/JoannaChang-dataviz-portfolio/b1a521c215660e15a8d52f6c43723b381b3e3b50/Critique%20And%20Redesign.jpg)

---
## Step 4: Test the solution

### Questions Asked
- Tell me what you think upon seeing the chart.  
- Can you describe what this is telling you?  
- Is there anything surprising or confusing?  
- Who do you think is the intended audience?  
- What recommendations would you make to improve the design?

### Results

| Question / Theme | Interview 1 - MISM classmate | Interview 2 - MISM classmate |
|---|---|---|
| Clarity of cancer case numbers | Asked whether the cancer case numbers shown below the chart directly correspond to the years above it. The alignment between values and years wasn't immediately clear. | Shared the same confusion. She wasn't sure if the numbers matched the correct years due to how they were displayed. |
| Chart type preference | Suggested using a line graph for cancer cases instead of bar-style annotations, noting it would make trends more intuitive. | Agreed that a separate line on the secondary (right) y-axis would improve readability. |
| Comparing countries | Mentioned that showing all countries' vaccination coverage and cancer incidence on one graph is overwhelming. | Recommended using filters, pages, or country-by-country toggles to let users view changes for each country individually after they implemented national HPV vaccination. |

### Synthesis
Across both interviews, the feedback revealed **three consistent themes**:
#### 1. Ambiguity in value–year alignment  
Viewers were unsure whether the numerical labels below the chart corresponded cleanly to the timeline above. This suggests that labeling, positioning, or axis relationships need to be clarified.

#### 2. Cancer incidence should be visualized as a trend line  
Both classmates independently recommended using a line graph—paired with a secondary y-axis—to better show how cancer cases change over time. This strengthens the argument that the current representation feels unintuitive.

#### 3. Comparing all countries at once is overwhelming  
Showing every country’s vaccination coverage and cancer incidence on a single graph creates visual clutter and makes interpretation difficult. Filters, country selectors, or paginated views would make the narrative more digestible and allow users to see how each country’s HPV policy affected outcomes over time.

### Design Changes Inspired by the Feedback

Based on these patterns, the following improvements will be implemented in the final redesign:

- Replace **numeric annotations** with a **trend line** for cancer incidence, displayed on a secondary y-axis.  
- Improve **alignment and labeling** so that years and cancer values clearly correspond.  
- Introduce **interactivity** with toggles or filters to select countries individually.  
- Apply a **storytelling structure**, presenting each country’s *“before vs. after HPV policy adoption”* in a clear, focused layout.

---

## Step 4.5 — Before Moving on to Redesign  
### Datasets Preparation & EDA on Change of Policy on HPV Schedule

#### 4.5.1 Datasets I Used in Redesign

To build a cohesive, data-driven redesign that connects **HPV vaccination policy**, **coverage**, and **cancer outcomes**, I integrated the following datasets from *Our World in Data (OWID)* and WHO sources:

##### **1. HPV Vaccination Coverage Rate (%)**
- **Source:** [Our World in Data – HPV vaccination coverage](https://ourworldindata.org/hpv-vaccination-world-can-eliminate-cervical-cancer)
- **Description:** Annual data showing the **percentage of females** vaccinated against HPV by country and year.
- **Purpose in Redesign:** To visualize the **uptake trajectory** of HPV vaccines over time and assess whether policy adoption led to measurable increases in coverage.

##### **2. Cervical Cancer Incidence / Cases / Accumulative Risk**
- **Source:** [Our World in Data – Cervical cancer incidence](https://ourworldindata.org/cervical-cancer)
- **Description:** WHO-compiled time-series data showing **new cervical cancer cases per 100,000 women** by country and year.
- **Purpose in Redesign:** To examine **long-term health outcomes** associated with HPV vaccination coverage, and visualize **pre- vs. post-policy** trends in cervical cancer incidence.

##### **3. HPV Immunization Schedule (Policy Adoption Dataset)**
- **Source:** [Our World in Data – HPV immunization schedule (WHO policy dataset)](https://ourworldindata.org/explorers/which-countries-include-hpv-vaccines)
- **Description:** Historical record of **which countries include the HPV vaccine in their national immunization programs**, with yearly status values:  
  - “Not routinely administered”  
  - “Subnational”  
  - “Entire country”  
- **Purpose in Redesign:** Serves as the **policy timeline backbone**, identifying **the year each country transitioned** to national HPV vaccination—used to align coverage and cancer trends for comparative analysis.

##### **Integration Objective**
By combining these datasets, the redesigned visualization connects **policy action → coverage increase → cancer risk reduction**, creating a unified narrative that was missing from the original fragmented charts.

---

#### 4.5.2 EDA on HPV _immunization_schedule (Detailed analysis is in the ipynb. file)
##### 1. Load and Clean the Data

Renamed key columns for clarity: "Entity" → "Country"
Long policy column → "Status for Vaccination"
Performed sanity checks using .shape and .head().

##### **2. Identify First Policy Change**

Found all countries that ever left **"Not routinely administered"**, capturing each country’s **first change year** and **new status**.

##### **3. Focus on National Coverage Adoption**

Filtered to countries moving specifically to "Entire country", summarized counts, and visualized the timing distribution.

##### **4. Filter to Cancer Data Window (2006–2014)**

Selected the subset matching the available cancer data.

##### **5. Extract First 8 Adopters**

Saved the first eight early-adopting countries for further analysis.
Note: Since the other two datasets do not include data for Monaco, it is excluded from the analysis and comparison.
As a result, we only have seven countries available for the redesign.

---

## Step 5: Build the Solution

### Overview of the Final Redesign

<iframe 
  src="https://public.tableau.com/views/HPVNationalProgramPolicyEffect/HPVNatioalProgramPolicyEffect?:embed=y&:showVizHome=no"
  width="100%" 
  height="700"
  frameborder="0">
</iframe>

The redesigned visualization is a **country-level small-multiple dashboard** that illustrates how national HPV vaccination programs relate to:

- **Cervical cancer cumulative risk** (left y-axis, shaded area)
- **HPV vaccination coverage among girls (%)** (right y-axis, line with data labels)

Seven early-adopting countries with complete data were included:
- United States  
- Australia  
- Denmark  
- France (metropolitan)  
- Germany  
- Spain  
- Switzerland  

Each country appears as an independent panel following a consistent visual structure.

Original designs in the article:[Our World in Data – HPV vaccination](https://ourworldindata.org/hpv-vaccination-world-can-eliminate-cervical-cancer)

#### **Dashboard Structure (Per-Country Panel)**

Each country panel follows a consistent structure:
- **Title:** HPV National Program Policy Effect – *[Country]*
- **X-axis:** 2003–2016  
- **Left Y-axis:** Cumulative cervical cancer risk  
- **Right Y-axis:** HPV vaccination coverage (%)  
- **Policy Marker:** Vertical dotted line indicating the year of national vaccine adoption  
- **Background:** White before policy; lightly tinted after  
- **Visuals:** Area chart for cancer risk, line chart for coverage, unified color theme across countries 

In Tableau, these sheets are combined into a **scrollable small-multiple dashboard** that avoids clutter from overlapping multi-country line charts.

---

### How This Design Addresses Earlier Critiques

#### **1. Clearer Relationship Between Years and Cancer Cases**
- Cancer risk displayed as a **continuous area chart**, leveraging position & shape.
- Removed isolated numeric labels under the chart.
- Cleaner year-to-value alignment.

#### **2. Cancer Incidence Displayed as a Trend**
- Shaded area communicates overall risk trends.
- Coverage line added using a **secondary axis**:
  - Example: USA shows **23%, 26%, 36%**.
- This enables visual comparison of **coverage trajectory vs. cancer trajectory**.

#### **3. Avoiding Clutter From Multi-Country Overlays**
- Each country gets its **own panel** → no visual chaos.
- Incorporates feedback: “use a filter or page for each country.”
- Comparison becomes intuitive and uncluttered.

### Design Choices

#### **Color & Encoding**
- Each panel uses a **soft, distinct color** for both area & line.
- Pre-policy shading lightly tinted; post-policy shading subtly shifted.
- Coverage rates labeled for easier cross-country comparison:
  - e.g., Australia: **65–71%**
  - USA: **<40%**

#### **Policy Annotation**
- Vertical dotted line labeled **“HPV National Program Start”**.
- Helps viewers quickly interpret pre- vs. post-policy regions.

#### **Consistency Across Panels**
All panels share:

- Same year range (**2003–2016**)  
- Similar axis scaling  
- Uniform colors, typography, and layout  

This standardization enhances comparability across countries.

### Key Comparisons and Insights (7-Country Analysis)

Although descriptive rather than causal, several qualitative insights emerge:

#### **1. High and Sustained Coverage — Australia & Spain**
- Australia: **~65–71% coverage**
- Spain: **>80% by 2016**
- Cancer risk remains stable or declines slightly  
- Strong future outcomes expected as vaccinated cohorts age

#### **2. Moderate Coverage Growth — Germany & Switzerland**
- Germany: **30–40%**
- Switzerland: **50–60%**
- Minimal improvement in cancer risk  
- Suggests sustained high coverage is necessary for stronger impact

#### **3. Low or Unstable Coverage — USA, France, Denmark**
- USA & France: **<40% coverage**, mostly flat cancer risk
- Denmark:
  - Early high uptake → collapse to **16%** by 2016 (likely vaccine hesitancy)
  - Cervical cancer risk fluctuates and remains high
  - Highlights the importance of **consistent vaccination uptake**

#### **4. Timing Matters**
- Early adopters with sustained high coverage (Australia, Spain) show the **most promising trajectories**.
- Small-multiple layout makes differences in timing and uptake visually obvious.

---
### Limitations

One important limitation of the redesign is the **availability of vaccination coverage data**.  
Coverage rate data for most countries only begins in **2010**, while many national HPV vaccination programs were introduced around **2006–2007**.

#### **As a result:**
- The dashboard cannot fully show the **immediate change in uptake** right after policy adoption.  
- The first few post-policy years are **missing**, creating a gap between policy introduction and the earliest available coverage data.  
- This limits the ability to observe **early adoption patterns** or **short-term behavioral responses** during the initial rollout phase.

Despite this constraint, the visualization still effectively shows **medium-term trajectories (2010–2016)** and highlights how differences in uptake levels relate to **later cancer risk patterns** across countries.

---
## References
I used AI tools to proofread my grammar and wording throughout the descriptions.
