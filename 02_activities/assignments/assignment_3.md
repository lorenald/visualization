# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    V1: Excel

    V2: Python

    > Who is your intended audience? 
    V1: community interested in FSL offerings

    V2: government analysts interested in identifying attrition rates of FSL education in the schools with highest overall enrollment

    > What information or message are you trying to convey with your visualization? 
    V1: FSL enrollment has a lower proportion of enrollment in secondary vs elementary at the provincial level

    V2: lower proportion of enrollment in secondary vs elementary is observed similary in schools with highest overall FSL enrollment

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    both: data trends, distribution, similarity, marks, channels

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    V1: I kept the original excel file linked to the graph made. however, this will be harder to replicate in a large scale. this makes the visualization not accessible.

    V2: I wrote a jupyter notebook with comments on what each code chunk was doing. data is publicly available and I provided a link but couldn't figure out how to add the reference on the figure itself

    > How did you ensure that your data visualization is accessible?  
    Both: implementing contrasting colours color-blind friendly, large enough font size, information is concise, added labels, titles to axis

    V1: added numbers to proportions 

    V2: bars are big enough to distinguish one from the other

    > Who are the individuals and communities who might be impacted by your visualization?  
    Both: those interested in FSL education, it can be parents, community members, investors, government, researchers

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    V1: I included provincial totals as an introduction to the topic, providing an overview of the provincial landscape

    V2: I included only the top 15 schools with the highest overall enrollment to display that even in top schools the same pattern is observed. this also helped with making the figure not too large.

    > What ‘underwater labour’ contributed to your final data visualization product?
    both: school boards reporting on their enrollment numbers, ministry of education employees connecting with data management team to share information, data analysts cleaning and preparing data for publication, managers overseeing data collection and dataset creation, developers of matplotlib library, developers who created and mantained publicy available website.

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
* Submission Due Date: `23:59 - 09/05/2025`
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
