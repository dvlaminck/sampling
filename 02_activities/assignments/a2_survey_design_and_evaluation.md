# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#2`

Describe the purpose of your survey:
```
The purpose of this survey is to determine the major factors that Canadian voters care about leading up to the election (1 month away) and current perception of my political party. The results will then be used to reinforce major findings within campaign messaging leading up to the election in order to maintain our lead.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: Eligible Canadian voters (18+) across all federal ridings
Sampling frame: List of registered voters from federal database
Sampling units: Individual adult voter, one per stratified household
Observational units: Stratified random sampling. Household will be stratified based on geographic regions and demographics (age, gender); One individual per household.
```

Your 5-10 question survey:
```
1. How likely are you to vote in the upcoming election? (Definitely will vote, probably will vote, uncertain, probably will not vote, definitely will not vote)
2. Which party are you planning to vote for? (Our party, opposition, other, uncertain, prefer not to say)
3. Which of the following best describes where you live? (Large city centre, suburban (Midsized) city, small town, rural)
4. How satisfied with your current political party leader are you? (Very satisfied, somewhat satisfied, neutral, unsatified, very unsatisfied)
5. Please rank the following issues from most (1) to least important (5) to you when deciding your vote? (Cost of living, healthcare, housing, climate, public safety)
6. On a scale from 1-5 (least to most), please rank how much each of the following has influenced your voting decision? (Party platform & policies, party leadership, family/friends, news/media coverage)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Two-stage random stratified sampling model. First, the stratification is done at the province/census metropolitan area (CMA) level to identify househoulds of interest. Next, a random individual (over 15) is selected from each household to complete the survey.

2. Sample size: ~50,000 were contacted about the survey (40,000 invitations to the electronic survey)

3. Target population: All non-institutionalized persons 15 years of age or older, living in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions.

4. Sampling frame: Based on information from government data, combining landlines and cell numbers from Census/Statistics Canada to create list of eligible individuals.

5. Survey mode(s): Interviewed by telephone or self-completed an electronic questionnaire

6. Timeline: Data is collected every 5 years from 2018-09-04 to 2018-12-28.

7. Response rate: 41.9%

8. Weights: Estimation weighting was done at the person level. Bootstrap weights were also created for the purpose of design-based variance estimation.

9. Data processing: Processing used SSPE procesing and utilities. Error detection was done through edits programmed into the CATI system.

10. Cleaning, imputation, etc: All imputations were made using donor records selected through a score function (except in a few cases). This helped to fill incomplete responses with the experience of other respondents with similar or identical characteristics. There are quality assurance checks in statistical process and validation, and responses are subjected to scrutiny by statisticians. 

11. Sources of error: Non-sampling error (imperfect coverage and non-response), coverage error (households without telephones), response error (mistakes made while filling out the survey).

12. Limitations, known biases, etc: The survey excludes individuals living in any Canadian territories or those living at an institution. There may be limitations with the way the survey is conducted as well, such as the collection of online responses (non-response bias).

13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment-2`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
