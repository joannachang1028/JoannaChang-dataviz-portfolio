| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

For this assignment, I selected the visualization series from “HPV vaccination: How the world can eliminate cervical cancer” published by Our World in Data. The article and all visualizations can be accessed at the following link:
https://ourworldindata.org/hpv-vaccination-world-can-eliminate-cervical-cancer

I chose this set of visualizations because HPV vaccination is a highly consequential global health issue, and this article includes multiple charts exploring different aspects of cervical cancer prevention—from historical cervical cancer incidence in the UK, to global HPV vaccination policies, to cross-country differences in vaccination coverage.

The first graphic, which shows cervical cancer incidence by birth cohort in the UK, particularly stood out to me. It clearly illustrates how dramatically cancer rates dropped among women who received the HPV vaccine as teenagers. The visualization isolates birth cohorts in a way that makes the impact of vaccination policies easy to grasp at a glance.

However, as the article progresses, the visualizations—while individually strong—begin to feel fragmented in their messaging. One chart shows incidence across different countries, another shows which countries have national HPV programs, and others show global vaccination coverage. Although each chart tells its own clear story, it’s harder for viewers to synthesize how policy adoption, vaccination rates, and cancer outcomes interrelate. This gap in narrative cohesion is what I plan to focus on in my redesign.

## Step two: the critique
Below are the ratings I provided in the critique rubric:

Usefulness: 8/10
The visualizations are informative and communicate valuable insights, especially the UK birth-cohort chart.

Completeness: 8/10
Each chart includes relevant information, but collectively they lack a cohesive storyline that ties all components together.

Perceptibility: 7/10
Most visuals are clear, but viewers must navigate across multiple graphs to understand the full picture.

Truthfulness: 9/10
The visualizations are accurate, well-sourced, and do not appear to misrepresent the data.

Intuitiveness: 8/10
Interactivity helps users explore the data, though some charts may require prior context to fully appreciate.

Aesthetics: 7/10
Clean and consistent with the Our World in Data style, but some color contrasts could be improved.

Engagement: 7/10
The visuals draw interest, but the fragmented structure limits how deeply users can follow the overall narrative.

Overall observations:
The visualizations work well individually—each one highlights a specific aspect of HPV vaccination impact or global policy adoption. The UK cohort chart is especially impactful in showing how early vaccination prevents cervical cancer later in life. Interactive world maps also effectively display geographic differences and allow users to explore patterns at their own pace.

What works well:

Strong interactivity (hover, filtering, time series).

Clear color coding and readable layouts.

Strong storytelling within each standalone visualization.

Reliable and trustworthy data sources.

What doesn’t work well:

The different charts do not build a unified narrative as a whole.

Readers must jump between multiple graphs to understand the relationship between policy adoption, vaccination coverage, and cancer incidence.

Additional contextual layers—such as showing incidence and vaccination rates together—could deepen understanding.

Color schemes vary slightly across charts, reducing cohesiveness.

These insights will guide my redesign, where I aim to improve narrative cohesion and integrate multiple data dimensions into a single, intuitive story.

## Step three: Sketch a solution


## Step four: Test the solution

Questions asked

Tell me what you think upon seeing the chart.

Can you describe what this is telling you?

Is there anything surprising or confusing?

Who do you think is the intended audience?

What recommendations would you make to improve the design?

Results
Question / Theme	Interview 1	Interview 2
Clarity of cancer case numbers	Asked whether the cancer case numbers shown below the chart directly correspond to the years above it. The alignment between values and years wasn't immediately clear.	Shared the same confusion—wasn’t sure if the numbers matched the correct years due to how they were displayed.
Chart type preference	Suggested using a line graph for cancer cases instead of bar-style annotations, noting it would make trends more intuitive.	Agreed that a separate line on the secondary (right) y-axis would improve readability.
Comparing countries	Mentioned that showing all countries’ vaccination coverage and cancer incidence on one graph is overwhelming.	Recommended using filters, pages, or country-by-country toggles to let users view changes for each country individually after they implemented national HPV vaccination.
Synthesis

Across both interviews, the feedback revealed three consistent themes:

Ambiguity in value–year alignment:
Viewers were unsure whether the numerical labels below the chart corresponded cleanly to the timeline above. This suggests that labeling, positioning, or axis relationships need to be clarified.

Cancer incidence should be visualized as a trend line:
Both classmates independently recommended using a line graph—paired with a secondary y-axis—to better show how cancer cases change over time. This strengthens the argument that the current representation feels unintuitive.

Comparing all countries at once is overwhelming:
Showing every country’s vaccination coverage and cancer incidence on a single graph creates visual clutter and makes interpretation difficult. Filters, country selectors, or paginated views would make the narrative more digestible and allow users to see how each country’s HPV policy affected outcomes over time.

Design changes inspired by the feedback

Based on these patterns, here are the design improvements I plan to implement in the final redesign:

Replace numeric annotations with a clear trend line for cancer incidence, displayed on its own y-axis.

Improve alignment and labeling so that years and cancer values clearly match.

Introduce interactivity, allowing users to toggle or filter by country instead of displaying all lines at once.

Use storytelling structure, showing each country’s “before vs. after HPV policy adoption” in a clean, focused view.

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

