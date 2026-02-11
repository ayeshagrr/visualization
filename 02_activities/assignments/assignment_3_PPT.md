# Data Visualization

## Assignment 3: Final Project

DATASET: https://open.toronto.ca/dataset/washroom-facilities/
IMAGE: TorontoParksPPTInfographic.png
    
   
    > What software did you use to create your data visualization?
        
        Microsoft Powerpoint

    > Who is your intended audience? 

        The intended audience is the general public who use Toronto parks, eg., park visitors planning outings (families, seniors, tourists, runners, dog-walkers), people who need reliable washroom access (e.g., caregivers, people with medical needs, parents with young children), community members looking for quick, practical information without technical detail.

        A secondary audience could be City of Toronto parks staff or community organizations sharing basic park-use information.
    
    > What information or message are you trying to convey with your visualization? 

        The different types of available washroom facilities across Toronto parks.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
        
        Visual hierarchy: Large title, short subtitle, then three equal “cards” so the reader knows what to read first and can scan quickly.

        Consistency: Each washroom type uses the same structure (icon → title → short description), making comparison effortless.

        Alignment and spacing: Symmetry across the three panels; consistent margins and whitespace to reduce clutter.

        Simplicity and cognitive load: Minimal text per panel; one checkmark bullet to keep the message digestible.

        Typography: Clear, large headings for categories; simpler body text for the description.

        Color palette: A restrained green/neutral palette that matches a “parks/nature” theme and keeps attention on the content rather than decoration.

        Iconography: Simple icons (building/portable/community centre) reinforce meaning even if someone reads quickly.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

        PowerPoint is partially reproducible: it’s great for stable layouts but doesn’t automatically regenerate visuals from updated data the way code-based tools do.

        To make it as reproducible as possible, I would:
            - keep the source dataset and definitions (what counts as each washroom type) saved alongside the slide deck
            - document the steps used to create the layout (Slide Master settings, fonts, sizes, spacing rules)
            - store the infographic as a template (so future updates follow the same structure)

        Impact of limited reproducibility: If the underlying data or definitions change, PowerPoint won’t update automatically. That means updates require manual edits, increasing the risk of inconsistency unless the workflow is documented and version-controlled.
    
    > How did you ensure that your data visualization is accessible?  
        
        Readable text: Large headings and short lines of text; avoids dense paragraphs.

        High contrast: Dark text/icons on a light background to improve legibility.

        Not relying on color alone: Categories are communicated by text labels + icons, not by color coding.

        Plain language: Descriptions are short and practical (e.g., “temporary, outdoor… often during summer”).

        Export considerations: If shared as an image/PDF, I would add alt text (in PowerPoint) for each icon/panel or a text-only version of the content (e.g., in the slide notes or an accompanying webpage)
        
        Layout clarity: Three clearly separated panels help screen magnification users follow sections.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

        Toronto residents planning park visits (families, walkers, seniors).

        People who rely on predictable washroom access: parents with young children, pregnant people, older adults, people with disabilities, and people with certain health conditions.

        Visitors and commuters who use parks for recreation or as part of daily routes.

        City planners or advocacy groups interested in identifying gaps in amenities.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

         Included only the “type of toilet” field and the count of facilities because the goal was to show a straightforward overview of what kinds of washrooms are available.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

        This infographic focuses on categorical classification only. I included features that support quick orientation:
        - the three types of facilities
        - a brief descriptor of where/when each type is typically available (permanent vs temporary; indoor vs outdoor; community centre proximity)
        
        I excluded details that would complicate a high-level infographic, such as:
        - counts (how many of each type)
        - locations by park
        - hours of operation/seasonality by site
        - accessibility features (e.g., wheelchair accessible, gender-neutral, baby change tables)
        - maintenance status or closures
        
        Those exclusions keep the message simple, but they also limit how actionable it is for people needing specifics.

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
