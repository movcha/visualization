# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

Visualization 1: Python Visualization

Software Used:
- Python with libraries such as Pandas, Seaborn, and Matplotlib.

Intended Audience:
- Public health officials, environmental scientists, and the general public who are interested in the water quality of Toronto beaches.

Information or Message:
- The visualization aims to show the trends in E. Coli levels at various Toronto beach sites over the years. This information can help in understanding the long-term water quality and identifying any problematic sites that may need intervention.

Design Principles:
- The visualization focuses on meaningful data that can influence public health decisions.
- Different colors are used to represent varying levels of E. Coli to make the distinction clear and intuitive.
- The design is clean and uncluttered, with each beach site's data separated into individual small graphs for clarity.

The principles were applied by:
- Using a consistent color scheme to indicate E. Coli levels.
- Arranging the plots in a grid to facilitate easy comparison between different sites.
- Ensuring labels and titles are clear and informative.

Reproducibility:
- The code used to create the visualization is fully reproducible, as it includes all necessary steps from data loading to plotting.
- The use of standard libraries ensures that anyone with a Python environment can replicate the results.

Accessibility:
- The visualization uses color schemes that are colorblind-friendly.
- Titles and labels are used to ensure that even those with visual impairments can understand the data when using screen readers.

Impacted Individuals and Communities:
- Communities around Toronto beaches and public health stakeholders will be impacted by this visualization. It can inform them about water safety and potential health risks.

Feature Selection:
- I included the siteName, collectionDate, and eColi levels from the dataset. These features are directly relevant to assessing water quality over time at different locations.

Underwater Labour:
- Significant effort was put into data collection, cleaning, and ensuring the visualization adheres to best practices for accessibility and interpretability.

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
