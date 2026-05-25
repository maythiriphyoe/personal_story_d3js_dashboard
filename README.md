# personal_story_d3js_dashboard

### Introduction
This project is meant to build an interactive personal story dashboard for the Data Communications Class for Sping 2026 semester. This project is built by D3.js and uses the personal behaviour data collected for 20 days. The variables include sleep hours, screen time, learning duration, productivity scores, social energy reserves, stress levels, daily highlight categories, and proactive mental health habits (such as journaling).

### Key Insights and Findings
- A strong positive correlation (0.59) exists between intensive learning intervals and high stress levels. There is a weak positive relationship (0.33) between stress and productivity too, indicating that high stress drives productivity temporarily and cause the mood crash later with negative correlation later between stress and mood (-0.40).
- There is a strong negative relationship between intensive learning hours and my social reserve. The longer study hours drain my social energy.
- For wellness habits such as journaling, it is found that stress scores are higher on days featuring journaling. That indicates that journaling is used to respond to stress spikes. 
- Creative activities: `Hobby` (cooking) highlights an average a peak mood of 8.0. On the other hand, `Relaxation` (Going to cafes) is tightly coupled with absolute lowest mood states (2.0). This indicates that relaxation activies or going out are used almost exclusively as an emergency coping mechanism after severe burnout.

### Decision Making 

After tracking my habits for 20 days, I noticed a few patterns that may help improve my routine and well-being:
- Balance study time: Long study hours often increased stress and reduced social energy. Taking breaks and avoiding long study sprints may help prevent burnout.
- Journal regularly: Journaling mostly happened on stressful days. Turning it into a regular habit may help manage stress earlier.
- Make time for hobbies: Creative and enjoyable activities were linked to better mood scores. Scheduling hobby time during busy weeks may help improve emotional well-being.

### Limitations and Ethical Considerations

Privacy: This dashboard only uses general self-tracked data such as mood, stress, sleep, and productivity. Personal journal details were removed and grouped into broad categories like Hobby, Entertainment, and Achievement.
Limitations:
- The dataset only covers 20 days, so it may not fully represent long-term patterns.
- Mood and stress scores were self-reported and may change depending on emotions or memory.
- Some entries were logged later, so a few details may not be perfectly accurate.
Visualization Choices:
- Mood vs. Stress Timeline (Line Chart): to clearly show how mood and stress changed over time across the 20 days.
- Mood vs. Social Energy & Sleep (Scatter Plots): to show relationships between mood, sleep, and social energy through individual daily data points.
- Average Mood by Daily Highlight (Horizontal Bar Chart): to compare mood scores across activity categories while keeping labels easy to read.
- Stress Profiles & Journaling Impact (Bar Charts): for simple comparisons between groups such as weekdays vs. weekends and journaling vs. non-journaling days.
- Variable Correlation Matrix (Heatmap): to summarize relationships between all tracked variables.
AI use: Gemini AI was used to help with D3.js coding, debugging, correlation calculations, and improving the dashboard layout and styling.
Additional Context: The insights in this dashboard are based only on the collected data and may not include other factors such as physical health, diet, or outside events.
