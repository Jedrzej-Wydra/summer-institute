# Lesson Plan for Participants
## Summer Institutes in Computational Social Science 2020
## Day 5, Mass collaboration
## Prepared by Matt Salganik and Ian Lundberg

### Summary

In this activity, you will take part in a simulated Fragile Families Challenge. You will use the Fragile Families and Child Wellbeing Study data collected from a child's birth to age 9 to predict 6 outcomes at child age 15: 1) child grade point average (GPA), 2) child grit, 3) household eviction, 4) household material hardship, 5) caregiver layoff, and 6) caregiver participation in job training.

### Learning objectives

- Practice converting raw survey data to a suitable format
- Practice creating machine learning for predictive modeling
- Experience the common task method

### Preparation

Well in advance of the activity (we recommend at least two full days), you will need to apply for data access.

- Register for an account on the [OPR data archive](https://opr.princeton.edu/archive/restricted/Default.aspx)
- Visit your [switchboard](https://opr.princeton.edu/archive/restricted/Switchboard.aspx) and sign up for access to the Fragile Families and Child Wellbeing Study. When asked about your plans for using the data, write "I will be participating in the Fragile Families Challenge as part of SICSS." You may also include any additional plans for using the data.
- We approve these applications manually. There will be a lag before the next steps.
- Once approved, you may receive an email from the Fragile Families Study. They will direct you to the files stored on the [OPR data archive](https://opr.princeton.edu/archive/restricted/Default.aspx), but for our activity we are going to use a tailored set of files instead (see below).
- You will receive an email from Ian Lundberg with the data tailored to our activity. Ian's email will come through Princeton's Secure Send system. You will have to make an account to download; it will walk you through the steps.
- Download the zipped data folder. To open the zipped folder, you will need a password that we will post on Slack. Contact your local organizer or Ian Lundberg with questions.

Before the activity, watch the video in which Matt introduces the activity, which will be posted on the [curriculum section of the SICSS website](https://compsocialscience.github.io/summer-institute/curriculum).

### Ethics: A brief note

The Fragile Families and Child Wellbeing Study is a dataset of real people who have selflessly opened up their lives to us for the last 15 years so that their experiences can contribute to scientific research. By participating in the Fragile Families Challenge, you become a collaborator in this project. It is of the utmost importance that you respect the families in the data by using what they have told us responsibly.

You can read more about our approach to ethical data access in our [paper](https://doi.org/10.1177%2F2378023118813023) on the topic.

### Rough schedule

- 1 hour: Prepare a data file for analysis
- Break. If you are not happy with your prepared data file, we recommend using the cleaned file that we provided in the folder we emailed you. This will allow you to proceed to the next step.
- 2 hours: In groups, build predictive models and submit to the [submission site](https://codalab.fragilefamilieschallenge.org/competitions/28). Do not expect to try many different sophisticated models in the time available. A good approach would be to focus on just one outcome of interest and try models of increasing complexity after successfully submitting a basic linear model to the leaderboard.
- 15 minutes: Whole group debrief for your site

AT THE END OF THE ACTIVITY, DELETE THE DATA FILES. It is important that the data not sit on a local machine unnecessarily. If you would like access to the data for future research, you can download the data at any time from the OPR Data Archive.

### Resources

There are three sets of resources that may be helpful.

Resources about preparing data and making a submission:
- [Submission site](https://codalab.fragilefamilieschallenge.org/competitions/28)
- Here are some tips about [data preparation](https://github.com/compsocialscience/summer-institute/blob/master/2020/materials/day5-mass-collaboration/activity/SICSS_FFC_datacleaning_tips.pdf).
- To learn about the variables included in the data files, you might use: the [metadata explorer](http://metadata.fragilefamilies.princeton.edu/), use the accompanying [R](https://cran.r-project.org/web/packages/ffmetadata/index.html) and [Python](https://github.com/fragilefamilieschallenge/ffmetadata-py) packages, and/or refer to survey [questionnaires and other documentation](https://fragilefamilies.princeton.edu/data-and-documentation/public-data-documentation).
- This [blog post](https://www.fragilefamilieschallenge.org/upload-your-contribution/) shows step-by-step how to zip and upload a submission.
- If you have trouble submitting, compare the file you are attempting to submit to our [example for upload](https://github.com/compsocialscience/summer-institute/blob/master/2020/materials/day5-mass-collaboration/activity/example_for_upload.zip). Often errors occur when the numbers are in a different format, the column names are incorrect, or the directory structure of the zipped folder is incorrect. It is important that the zipped folder has no subdirectories.

Resources about the Fragile Families Challenge:
- The [published paper](https://doi.org/10.1073/pnas.1915006117)
- The [project website](http://www.fragilefamilieschallenge.org/)
- Videos from the [Fragile Families Challenge Scientific Workshop](https://www.youtube.com/channel/UCjluzrRT8fqXCx3qHjQAb5A)
- A [Special Collection of _Socius_](https://journals.sagepub.com/topic/collections-srd/srd-1-fragile_families/srd) in which participants summarize the approaches they used in the Challenge.

Resources about the broader Fragile Families and Child Wellbeing Study:
- Study [website](https://fragilefamilies.princeton.edu/)
- Database of [research papers](https://ffpubs.princeton.edu/) using the data

### Acknowledgments

This activity was designed with input from participants and TAs from SICSS 2017 - 2019, especially Yo-Yo Chen, Janet Xu, and Alex Kindel, as well as participants at many Fragile Families Challenge Getting Started Workshops. The [Fragile Families Challenge](https://doi.org/10.1073/pnas.1915006117) is a mass collaboration organized by Matt Salganik, Ian Lundberg, Alex Kindel, and Sara McLanahan involving hundreds of researchers.
