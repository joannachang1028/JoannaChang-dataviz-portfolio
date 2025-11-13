| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

# HPV Vaccination: Visualization Critique and Redesign Plan

## Step 1: The Visualization

For this assignment, I selected the visualization series from  
**“HPV vaccination: How the world can eliminate cervical cancer”**  
published by *Our World in Data*.  

🔗 **Source:** [Our World in Data – HPV vaccination](https://ourworldindata.org/hpv-vaccination-world-can-eliminate-cervical-cancer)

---

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

---

### **Overall Observations**
The visualizations are effective when viewed individually—each highlights a different aspect of HPV vaccination’s impact or global policy adoption.  
The **UK cohort chart** is especially impactful in showing how early vaccination prevents cervical cancer later in life.  
Interactive **world maps** also enhance engagement, allowing users to explore geographic variations and trends.

---

### ✅ **What Works Well**
- Strong interactivity (hovering, filtering, time series).
- Clear color coding and readable layouts.
- Effective storytelling within each individual visualization.
- Reliable and transparent data sources.

---

### ⚠️ **What Could Be Improved**
- Lack of **unified narrative** across charts.  
- Requires switching between graphs to see relationships among *policy*, *coverage*, and *incidence*.  
- Missing **integrated contextual layers** combining vaccination and outcome data.  
- Slight **color inconsistencies** reduce cohesiveness.

---

### **Redesign Focus**
For my redesign, I plan to:
- Improve **narrative cohesion** by integrating key dimensions (policy adoption, vaccination rates, and cancer outcomes).  
- Use **consistent color schemes** and **visual hierarchy** to tie the story together.  
- Explore **multi-layered visuals** (e.g., combined trend + map dashboard) to enhance intuitiveness and insight.


## Step three: Sketch a solution


## Step four: Test the solution

### Questions Asked

- Tell me what you think upon seeing the chart.  
- Can you describe what this is telling you?  
- Is there anything surprising or confusing?  
- Who do you think is the intended audience?  
- What recommendations would you make to improve the design?

---

### Results

| **Question / Theme** | **Interview 1** | **Interview 2** |
|------------------------|-----------------|-----------------|
| **Clarity of cancer case numbers** | Asked whether the cancer case numbers shown below the chart directly correspond to the years above it. The alignment between values and years wasn't immediately clear. | Shared the same confusion—wasn’t sure if the numbers matched the correct years due to how they were displayed. |
| **Chart type preference** | Suggested using a line graph for cancer cases instead of bar-style annotations, noting it would make trends more intuitive. | Agreed that a separate line on the secondary (right) y-axis would improve readability. |
| **Comparing countries** | Mentioned that showing all countries’ vaccination coverage and cancer incidence on one graph is overwhelming. | Recommended using filters, pages, or country-by-country toggles to let users view changes for each country individually after they implemented national HPV vaccination. |

---

### Synthesis

Across both interviews, the feedback revealed **three consistent themes**:

#### 1. Ambiguity in value–year alignment  
Viewers were unsure whether the numerical labels below the chart corresponded cleanly to the timeline above. This suggests that labeling, positioning, or axis relationships need to be clarified.

#### 2. Cancer incidence should be visualized as a trend line  
Both classmates independently recommended using a line graph—paired with a secondary y-axis—to better show how cancer cases change over time. This strengthens the argument that the current representation feels unintuitive.

#### 3. Comparing all countries at once is overwhelming  
Showing every country’s vaccination coverage and cancer incidence on a single graph creates visual clutter and makes interpretation difficult. Filters, country selectors, or paginated views would make the narrative more digestible and allow users to see how each country’s HPV policy affected outcomes over time.

---

### Design Changes Inspired by the Feedback

Based on these patterns, the following improvements will be implemented in the final redesign:

- Replace **numeric annotations** with a **trend line** for cancer incidence, displayed on a secondary y-axis.  
- Improve **alignment and labeling** so that years and cancer values clearly correspond.  
- Introduce **interactivity** with toggles or filters to select countries individually.  
- Apply a **storytelling structure**, presenting each country’s *“before vs. after HPV policy adoption”* in a clear, focused layout.


## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

