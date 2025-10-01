# Project Milestone 2 (PM2)

Milestone 2 will comprise about 8% of your overall course grade.

## Goal

In the second project milestone, there are four goals:

1. Setup your project repository on GitHub using the template we provide.
2. As a team, select **one** of the approved datasets, do a data abstraction, and then conduct a comprehensive exploratory data analysis.
3. Write a report that includes your research questions, a Task Analysis, and preliminary sketches of your plan to answer your research questions.
4. Choose a contracted grade and submit a link to your repository (must be in the `ubc-dsci320-2024W2` GitHub organization).

## 1. Repository Setup

- One member of the group should [accept the GitHub Classroom link](https://classroom.github.com/a/llIknRnf) and name the repository: `Team_YOURTEAMNAME`; this will create a new repository for your group.
- Other members of the group should "join" that repository by clicking on the [the GitHub Classroom link](https://classroom.github.com/a/llIknRnf). All group members will have the same admin access to the repository and everyone should be pushing to this repository.
- Complete the main README.md file in the root of your project repository.
- Look around all the files and folders that currently exist in the repository
- Develop or adopt a code of conduct for how your team will work, and how issues will be resolved.
- [**OPTIONAL**] Read through the `project_vision.md` file ; I find that this has been helpful to teams in the past, but this is optional for you to do. It will not be graded, but we will read it.
- In the `analysis` directory, update the default names of the existing folders (ColdHarbour, Lucknow, Rhodes, and Wellington) to be short names that correspond to the areas each member of the group is analyzing. It doesn't actually matter too much what the folder names are, just make them unique and distinct for each person so it's easy to distinguish - each team member will work in their own folder.
- Add your data to the repository in the `data` directory (if it is less than 45mb). If it is significantly more, you will need to use [GitLFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage). Come by the instructor student hours if you need help with this, this part is not really part of the course so we'll just show you how to do it.

## 2. Data Abstraction and Comprehensive EDA

This data abstraction should appear in your report and only needs to be done once. 
The code and figures for each individual team member's EDA should be in their respective `analysisX.ipynb` file in the `analysis` directory.
The consolidation of the EDA (key visual summaries and interesting/important results) should be presented in the report - you should export the altair figures from the notebooks and embed them into the report markdown file.

More details about the data abstraction and EDA are below.

### Data Abstraction

Using the principles you were exposed to in the Data Abstraction lectures, describe the dataset and all of the attributes in your dataset.
Remember to include the semantics, the data attribute types, and the cardinality for each attribute - use the following table as a template:

| Attribute Name | Attribute Type | Data Semantics | Cardinality |
|----------------|----------------|----------------|-------------|
| .              | .              | .              | .           |
| .              | .              | .              | .           |
| .              | .              | .              | .           |
| .              | .              | .              | .           |

Only one Data Abstraction needs to be done per group/dataset.

### Exploratory Data Analysis

Using the suggested workflow for EDA that we discussed in class, apply it to your data.
Your EDA must include univariate visual summaries for all attributes (both categorical and quantitative), multivariate visual summaries does not need to be exhaustive but must include at least 4 unique representations for bi-variates.
You may do an abbreviated univariate analysis and present brief numerical summaries and focus your efforts on bi- and multivariate visual data analysis.
Each group member's EDA should be slightly different based on their interests and research questions.
As a rough guideline, at least 50% of each person's EDA should be unique.

## 3. Report: Research Questions, Task Analysis, Sketches

Your report will be a written presentation of the work you've done and will require you to synthesize discussions you've had with your group, EDA you've done, summaries you've written in other parts of the project and consolidate them into one written file. 
The format of this report is somewhat flexible, but we require the following sections and subsections to be present in the report:

1. Introduction (~500 words)
2. About the Data (no limit)
    - Data Abstraction
    - Exploratory Data Analysis
      - General
      - Person 1
      - Person 2
      - Person 3
      - Person 4
3. Research Questions (~500 words)
    - Person 1
    - Person 2
    - Person 3
    - Person 4
4. Task Analysis (~500 words)
5. Preliminary Sketches (~250 - 500 words)
6. Next Steps (~250 words)

### Introduction (~500 words)

- Add a description of your dataset
- Including the source, how/why the data was gathered/generated
- Introduce your team members, their backgrounds and their interests in the dataset
- Intended Audience: Who is your intended audience and what do you expect they will get from this project (what is the motivation)?

### About the Data

See the section on "2. Data Abstraction and Comprehensive EDA" for details on this.

### Research Questions

Project team members should develop research questions using the FINER criteria:
- Feasible
- Interesting
- Novel
- Ethical
- Relevant

The number of research questions you come up with will depend on the contracted grade your team chooses.
"Simple" research questions are ones that are less novel and less interesting and more complex, sophisticated, and deeper research questions have more layers, are more interesting and novel.

```{warning}
Note that for our purposes in DSCI 320, "novel" does not mean "never published before" - rather, it means that the questions need an element of sophistication and not trivial to answer.
```

### Task Analysis

To ensure diversity in tasks, we will use Stasko's taxonomy to label low-level tasks for the research questions you've chosen.
Here are some general guidelines for you to ensure diversity in tasks.
Each project must have:
- At least 7 distinct tasks pertaining to at least 6 distinct attributes. 
  - If your group size is 3 then you should have 5 distinct tasks, that pertain to at least 4 distinct attributes
- Sufficient overall complexity that visualizing multiple attributes using multiple views is necessary.
- All tasks must be plausible and must be addressable by the dataset(s) you are using.
- Your tasks must be complex enough that the design requirements in the Overview are met.

### Preliminary Sketches

For each of the tasks, you should create some low-fidelity sketches in anticipation of creating these visualizations and views in Milestone 3.

```{warning}
You should *not* create any Altair visualizations (that are not part of your initial EDA) as part of Milestone 2. We want to see your low- and high- fidelity sketches in Milestone 3 so we can give you feedback before you spend the time and efforts to create them.
```

Here's what you need to do **for each ~task~ research question**,
- Three low-fidelity sketches suited for ~task~ research question ; consider these three sketches different "options" that you will choose from after you critique them
- A critical analysis (critique) of all three low-fidelity sketches 
- One high-fidelity sketch of the final one that you select for this task
- An explanation of how the sketch you selected adheres to theoretical principles you have been exposed to in this course.

### Next Steps (~250 words)

At the end of the report, you should add a detailed, actionable plan with a timeline, and identified tasks for each group member.
Feel free to use tables or point form - you will be assessed on the thoughtfulness and specificity of your plans.

## 4. Choose Contracted Grade

Carefully read through the Project Description and choose your contracted grade on the PrairieLearn submission.