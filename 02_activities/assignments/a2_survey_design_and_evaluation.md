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

The number of your chosen topic: `3`

Describe the purpose of your survey:
```
This survey investigates how age influences music taste, particularly regarding perceptions of popular music. The research aims to understand both cross-sectional differences (comparing people of different ages) and longitudinal patterns (how individual preferences change over time) to contribute to sociological understanding of cultural consumption and aging.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target Population: All residents of Toronto aged 15 and above who can complete a survey in English.

Sampling Frame: University of Toronto student database combined with a stratified random sample from Toronto census data to ensure adequate representation across age groups (15-24, 25-34, 35-49, 50-64, 65+).

Sampling Units: Individual persons selected from the sampling frame.

Sampling Strategy: Stratified random sampling with oversampling of older age groups (50+) to ensure sufficient sample sizes for comparison. Target sample size of 1,500 respondents (300 per age stratum) to allow for robust statistical analysis and published academic findings.
```

Your 5-10 question survey:
```
1. What is your age? _____ years
2. On a scale of 1-5 (1=Strongly Disagree, 5=Strongly Agree): "I enjoy listening to current popular music (top 40 hits)."
3. How many hours per week do you typically spend listening to music? 
   □ 0-2 hours  □ 3-7 hours  □ 8-14 hours  □ 15+ hours
4. What genres of music do you primarily listen to? (Select all that apply)
   □ Pop  □ Rock  □ Hip-Hop/Rap  □ Country  □ Classical  □ Jazz  □ Electronic/EDM  □ Other: _____
5. Thinking back 10 years ago (if applicable), how would you describe your music preferences compared to now?
   □ Very different  □ Somewhat different  □ About the same  □ N/A (I'm under 25)
6. On a scale of 1-5: "Music that was popular when I was a teenager/young adult (ages 15-25) is the best music."
7. How often do you actively seek out new music or artists you haven't heard before?
   □ Daily  □ Weekly  □ Monthly  □ Rarely  □ Never
8. Which statement best describes your attitude toward current popular music?
   □ I enjoy it and listen regularly
   □ I'm neutral about it
   □ I prefer music from earlier eras
   □ I don't listen to popular music at all
9. What is your highest level of education completed?
   □ High school or less  □ Some college/university  □ Bachelor's degree  □ Graduate degree
10. Gender: □ Male  □ Female  □ Non-binary  □ Prefer not to say
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. SAMPLE TYPE:
Stratified random sampling using a complex multi-stage design. The sampling frame was created from multiple linked sources including Census data, administrative data, and billing files (telephone numbers and addresses).

2. SAMPLE SIZE:
Target sample size of approximately 25,000 respondents across Canada's 10 provinces. The PUMF (Public Use Microdata File) contains a subset of this for confidentiality protection.

3. TARGET POPULATION:
Non-institutionalized persons aged 15 years and older living in private households in the 10 provinces of Canada. Excluded: residents of Yukon, Northwest Territories, and Nunavut; full-time residents of institutions; persons without telephones or internet access.

4. SAMPLING FRAME:
An integrated frame combining multiple sources: Census of Population data, Address Register (AR), administrative files, and telephone number databases (both landline and cellular). This approach improved coverage compared to traditional random digit dialing, including cell-phone-only households.

5. SURVEY MODE(S):
For the first time in 2018, the GSS offered two collection modes:
- Internet/online questionnaire (rEQ - respondent-completed electronic questionnaire)
- Telephone interview (iEQ - interviewer-assisted electronic questionnaire using CATI)
This dual-mode approach was implemented to adapt to changing technology use and respondent preferences.

6. TIMELINE:
Collection period: September to December 2018 (4 months)
Data release: Planned for 2020, with the PUMF released in January 2021

7. RESPONSE RATE:
While the exact response rate for Cycle 33 (2018 GVP) is not explicitly stated in available documentation, comparable 2018 GSS cycles showed response rates around 50-53%. The 2013 GSS GVP had a response rate near 50%, suggesting the 2018 rate is likely in this range. The introduction of online response options may have affected response patterns.

8. WEIGHTS:
Bootstrap weights are provided with the dataset for variance estimation. Survey weights adjust for:
- Unequal probabilities of selection
- Non-response (including adjustments using administrative data on non-responding household characteristics such as income and composition)
- Post-stratification to known population totals from Census data
The bootstrap method (with multiple replicate weights) is used to calculate proper standard errors and confidence intervals.

9. DATA PROCESSING:
- Computer-assisted interviewing (CATI for telephone, web-based for online) with built-in edit checks during collection
- Post-collection editing and validation
- Coding of open-ended responses
- Imputation for missing data
- Derivation of analytical variables
- Application of survey weights

10. CLEANING, IMPUTATION, ETC:
- Rigorous quality assurance applied across all statistical process steps
- Validation measures included: analysis of changes over time, verification through cross-tabulations, comparison with similar data sources
- For the PUMF, additional disclosure control measures: some variables suppressed, top-coded, or had categories collapsed to prevent identification
- Imputation procedures used for item non-response (specific methods not detailed in available documentation)

11. SOURCES OF ERROR:
SAMPLING ERROR: Present due to sample-based (vs. census) design; bootstrap weights enable estimation of sampling variability.

NON-SAMPLING ERROR sources:
- Coverage error: Despite improved frame, some over-coverage and under-coverage remains; households without telephones or internet excluded
- Non-response error: Some selected households/individuals did not participate; addressed through weighting adjustments using administrative data
- Measurement error: Possible from questionnaire design, respondent misunderstanding, or mode effects
- Processing error: Potential errors in data entry, coding, editing (minimized through quality control)

12. LIMITATIONS, KNOWN BIASES, ETC:
- COMPARABILITY ISSUE: The 2018 GSS GVP results are NOT directly comparable to previous iterations (2013, 2010, 2007, 2004) due to the introduction of online data collection. The mode effect (online vs. telephone) likely impacted estimates, making trend analysis problematic.
- Self-reported data subject to recall bias, social desirability bias
- The online mode may attract different types of respondents than telephone interviews
- Four-month collection period may not capture seasonal variation in volunteering/donating behavior
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 19/10/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
