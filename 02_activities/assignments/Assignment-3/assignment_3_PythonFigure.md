# Data Visualization

## Assignment 3: Final Project


DATASET: https://open.toronto.ca/dataset/washroom-facilities/
IMAGE: TorontoParksPythonPlot.png

    > What software did you use to create your data visualization?

    Python

    > Who is your intended audience? 

    City of Toronto Residents
    
    > What information or message are you trying to convey with your visualization? 

    The different types of available washroom facilities across Toronto parks.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

        Clarity & simplicity: Used a single line to show the count by toilet type, with clear axis labels and a descriptive title. Removed the top/right borders to reduce visual clutter.

        Visual hierarchy: Made the data line thicker and dark green so the trend is the first thing viewers notice; kept the background plain white to avoid distraction.

        Interpretability: Rotated x-axis labels to prevent overlap and make category names readable. Added a legend to clarify what the line represents.

        Annotation & engagement: Added icons above each category to help viewers quickly recognize the facility types and to make the plot more approachable for residents.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
        I used a Python script that reads the same source CSV, performs a transparent counting step (groupby/value_counts), and generates the plot using code. Anyone with the file and script can recreate the exact figure.

        To improve reproducibility, I’d keep the script in a version-controlled repo (e.g., Git), and note package versions (e.g., pandas, matplotlib, Pillow).

        One limitation: the icons are pulled from external URLs. If a link changes or disappears, the plot will still reproduce but without icons (or it may error). A fix is to download the icons once and reference local files.

    
    > How did you ensure that your data visualization is accessible?  

        Used high contrast (dark green line on a white background) and large figure size for readability.

        Included clear labels and a title so the plot is understandable without extra context.

        Avoided relying on color alone for meaning (there’s only one series and it’s labeled in the legend).

        To make it more accessible, I would also: add data labels (values) or a small table summary for screen-reader users, ensure a colorblind-safe palette if additional series are added, provide alt text describing the main takeaway.

    > Who are the individuals and communities who might be impacted by your visualization?  

        Toronto residents planning park visits (families, walkers, seniors).

        People who rely on predictable washroom access: parents with young children, pregnant people, older adults, people with disabilities, and people with certain health conditions.

        Visitors and commuters who use parks for recreation or as part of daily routes.

        City planners or advocacy groups interested in identifying gaps in amenities.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

        Included only the “type of toilet” field and the count of facilities because the goal was to show a straightforward overview of what kinds of washrooms are available.

    > What ‘underwater labour’ contributed to your final data visualization product?

        Data cleaning/standardization: handling missing toilet types (e.g., filling NAs as “Unknown”), ensuring consistent category labels.

        Data transformation: aggregating to counts per type and ordering categories for readability.

        Design iteration: testing label rotation, margins, line thickness, and icon placement so nothing overlaps or gets cut off.

        Asset preparation: sourcing icons, resizing them consistently, and positioning them relative to plotted points.

        Debugging: resolving issues like unintended second lines, default color cycles, background styling, and layout spacing.     
    

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
