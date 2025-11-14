| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

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

---
## Step 4: Test the solution

### Questions Asked
- Tell me what you think upon seeing the chart.  
- Can you describe what this is telling you?  
- Is there anything surprising or confusing?  
- Who do you think is the intended audience?  
- What recommendations would you make to improve the design?

### Results
| **Question / Theme** | **Interview 1 - MISM classmate** | **Interview 2 - MISM classmate** |
|------------------------|-----------------|-----------------|
| **Clarity of cancer case numbers** | Asked whether the cancer case numbers shown below the chart directly correspond to the years above it. The alignment between values and years wasn't immediately clear. | Shared the same confusion. She wasn’t sure if the numbers matched the correct years due to how they were displayed. |
| **Chart type preference** | Suggested using a line graph for cancer cases instead of bar-style annotations, noting it would make trends more intuitive. | Agreed that a separate line on the secondary (right) y-axis would improve readability. |
| **Comparing countries** | Mentioned that showing all countries’ vaccination coverage and cancer incidence on one graph is overwhelming. | Recommended using filters, pages, or country-by-country toggles to let users view changes for each country individually after they implemented national HPV vaccination. |


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

Final Redesigned Visualization – Overview

For the final redesign, I built a country-level small-multiple dashboard that shows how HPV national vaccination programs relate to:

Cervical cancer cumulative risk (left y-axis, shaded area), and

HPV vaccination coverage among girls (%) (right y-axis, line with data labels)

for the first seven early-adopting countries with complete data:

United States, Australia, Denmark, France (metropolitan), Germany, Spain, and Switzerland

Each country has its own panel (as shown in the figures above), all following the same structure:

Title: HPV National Program Policy Effect – [Country]

X-axis: Year (2003–2016)

Left y-axis: Cumulative risk of cervical cancer

Right y-axis: Vaccination coverage rate (%)

Vertical dotted line marking the year each country introduced HPV vaccination into its national immunization schedule

White background before policy adoption, lightly tinted background after

Color-coded area + line chart for each country for easy cross-panel comparison

In Tableau, these individual sheets are combined into a dashboard. Users can select a country or scroll panel-by-panel to compare trajectories without the clutter of overlapping multi-country lines.

How This Design Addresses the Earlier Critique
1. Clearer relationship between years and cancer cases

Cancer risk is now shown as a continuous area chart, using position and shape to represent change over time.

No more isolated numeric labels under the chart — reducing confusion regarding year–value alignment.

2. Cancer incidence as a trend (not just labels)

The shaded area clearly communicates overall cervical cancer risk trends.

Vaccination coverage is displayed as a secondary-axis line with selected data labels (e.g., 23%, 26%, 36% for the USA).

This dual-axis approach lets viewers compare coverage trajectories vs. cancer risk trajectories without conflating scales.

3. Avoiding clutter from all countries on one graph

Each country is shown in its own panel with a consistent layout and color theme.

This applies classmates’ feedback to “use a filter or page for each country,” allowing insight without line chaos or visual overload.

Design Choices
Color & Encoding

Each panel uses a distinct but soft color (red, blue, green, teal, etc.) for both area and line to maintain identity and readability.

The pre-policy area is slightly tinted; the post-policy area shifts subtly to highlight the intervention period.

Vaccination coverage includes data labels to aid country-to-country comparison (e.g., Australia reaching 65–71%, while the USA remains under 40%).

Policy Annotation

A clear vertical dotted line labeled “HPV National Program Start” marks when each country introduced the vaccine nationally.

This milestone helps viewers interpret whether changes occur before or after the policy.

Consistency Across Panels

All charts share:

Same year range (2003–2016)

Similar axis scaling

Unified typography and layout

This makes comparisons valid and visually intuitive.

Key Comparisons and Insights From the 7-Country Analysis

Although the redesign is descriptive rather than causal, several qualitative insights emerge:

1. High and sustained coverage: Australia & Spain

Both countries achieved rapid and high vaccination uptake:

Australia: ~65–71%

Spain: >80% by 2016

Cancer risk appears stable or slightly declining, suggesting strong future benefits as vaccinated cohorts age.

2. Moderate coverage growth: Germany & Switzerland

Germany: ~30–40%

Switzerland: ~50–60%

Cancer risk shows minimal improvement, indicating that policy adoption alone isn’t enough — coverage level matters.

3. Low or unstable coverage: USA, France, Denmark

USA and France remain below 40% coverage; cancer risk is mostly flat.

Denmark is an outlier: after high uptake in the early 2010s, coverage plunges to 16% by 2016 (likely tied to vaccine hesitancy).

Cumulative cancer risk in Denmark remains high and fluctuating, underscoring the importance of sustained uptake.

4. Timing matters

Countries that adopted HPV vaccination earlier and maintained high coverage (Australia, Spain) show more promising trajectories than those with delayed or inconsistent uptake.

The small-multiple layout makes these timing differences visually explicit.

---
## References
I used AI to proofread my grammar and wordings in desciption. 
