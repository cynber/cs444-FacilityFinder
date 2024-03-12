---
authors:
  - felicia
  - kae
  - justin
  - rafi

categories:
 - Project Update
 - CPSC 444

date: 2024-03-11

draft: true

slug: project-update-4

---

# CPSC 444 L2B FacilityFinder - Blog Update #4

This blog post will be about the experiment design for our project. It will include the revised goal(s) of the experiment, the experiment method, and supplementary experiment materials.

<!-- more -->

## 4a. Revised goal(s) of experiment

??? quote "Original Goals (from Blog Update #3) - click to expand"

    You can also click [here](project-update-3.md#3e-proposed-goals-of-experiment) to view the original goals from Blog Update #3.

    ---

    For our experiment, there are a few goals that we would like to focus on. We have ranked these goals by importance and our ability to test them within the scope of CPSC 444. Our two most important goals are as follows.

    1. **Do participants feel motivated to add/update washroom data?** 
        - This is the most important goal for our experiment. We want to ensure that the app is sustainable and that the information in the app is up to date. As such, we want to investigate whether or not participants feel motivated to add and update washroom data. 
        - While this currently exists in a limited form in our low-fidelity prototype, we will need to expand on this for our evaluation. In particular, we want to explore different ways of motivating participants to add and update washroom data. 
            - In particular, we are exploring the use of gamification and social incentives, such as a points system, a leaderboard, and achievements.

    2. **Do participants prefer a visual or text-based interface?** 
        - This is the second most important goal for our experiment. We want to ensure that the app is accessible and useful for a diverse set of participants. As such, we want to investigate the best way to convey the information.
        - This is easy to test since it is already partially implemented in our low-fidelity prototype. For our evaluation, we will ask participants to complete tasks using both the visual and text-based interfaces, and then ask them which one they prefer.

    We also considered a few other goals, but we are unlikely to pursue them in our experiment. Those goals are as follows.

    3. **Do participants value the option to switch between text-based and visual-based GUIs?** 
        - This may be helpful if we find that there are groups of participants that prefer one interface over the other. While this is partially implemented in our low-fidelity prototype, it can be covered by the goals above.

    4. **Do participants see themselves continuing to use this app over time/once the novelty wears off?**
        - This is important for the long-term sustainability of the app. However, within the scope of CPSC 444, we may not be able to test this goal effectively. This is something that would need to be tested over a long period of time, especially because individual participants may only use the app every so often.

    5. **Do participants prefer a more playful and juvenile design, or a more serious design?**
        - This is a low priority goal to explore different design and theme options. In particular, we want to see if participants will enjoy a funny and playful design, or if they might find it inappropriate for the context.

!!! info "Updated Goal"
    What is the most effective gamification method for motivating participants to add/update washroom data?

**Reasoning:** 

The main reason for the change was to narrow the scope of the goals to make them more specific and testable, within the scope of CPSC 444. The original goal was too broad and would have been difficult to test effectively. We also wanted to focus on the most important goal for our experiment.

<br>

## 4b. Experiment Method

Please see the sidebar to jump to the section you are interested in.

<br>

### 4b.1. Participants

Participants: **People who physically visit the UBC Vancouver campus**.

The participants will be recruited through a combination of **quota sampling** and **snowball sampling**. 

We will aim to recruit **8-12 participants**, where there will be a balance of participants who are familiar and unfamiliar with the UBC Vancouver campus, able-bodied and disabled, and those who are cisgender and gender diverse.

Our recruiting approach will be to post on the [UBC subreddit](https://reddit.com/r/ubc), and to ask participants to either contact us directly or to refer others who may be interested in participating in our experiment.





<br>

### 4b.2. Conditions

There will be **3 conditions** in our experiment. Each condition will represent a different level of gamification. These conditions differ in what happens when a participant adds or updates washroom data.

1. `Baseline`: This will be the control condition. No points or achievements will be awarded.
2. `Points-Only`: There will be a points system, and participants will see a notification popup to inform them when they earn points for adding or updating data.
3. `Points-and-Achievements`: There will be a points system as above, but participants can also earn special achievements for adding or updating a certain type of data.






<br>

### 4b.3. Experimental Tasks

Participants will be asked to complete the following:

1. **Add information to a listing**
2. **Explore washrooms in building X. Go to washroom Y.** 
3. **You’re at fountain, navigate to a washroom. Feel free to explore the prototype as much or little as you want.** 

For task #2, the participants will not be prompted to add info to washroom listings, but we will note if they do so. For task #3, we will note any interesting behaviors.





<br>

### 4b.4. Design

This experiment will be a **within-subject design**. Each participant will complete the tasks in each of the 3 conditions.

Thus there will be one independent variable (IV) with 3 conditions.




<br>

### 4b.5. Procedure

1. **Recruitment:** Participants will first respond to a **demographic survey**. This will include questions about age, status (student, staff, etc.), gender identity, physical ability, and familiarity with the UBC Vancouver campus.
2. **Prep Task:** Participants will be asked to physically visit a washroom before the experiment begins. They will need to be cricital, and remember anything that is interesting, unique, or desirable about the washroom.
3. **Prototype:** Participants will then explore the prototype and complete the tasks in one of the 3 conditions. They will be asked to think aloud to the researcher in person. The researcher will take notes and write down relevant time stamps.
4. **Survey:** Participants will complete a self-report survey on their experience with the prototype.
5. Steps 3 and 4 will be repeated for the other 2 conditions.
6. **Debriefing:** The Participants will go through a closing survey, be debriefed, and thanked for their time.




<br>

### 4b.6. Apparatus

The apparatus will include:

- A laptop or tablet equipped with screensharing capabilities
- Digital access to the prototype
- Access to the survey/questionnaire
- Access to task instructions




<br>

### 4b.7. Independent and Dependent Variables

**Independent Variable (IV):** 

The method of gamification used to motivate participants to add/update washroom data.

**Dependent Variables (DV):**

- Participant condition preference (self-reported selection)
- Effectiveness of condition (observed)
    - Number of times participants add/update washroom
- Time spent per condition
- Participant frustration/discomfort (both observed & self-reported)
    - Erroneous clicks (observed)
    - Amount of effort to use (from scale)




<br>

### 4b.8. Hypotheses

- **H1:** The `Points-and-Achievements` condition will be the most preferred condition, over the `Baseline` and `Points-Only` conditions.
- **Null:** There is no preference for the `Points-and-Achievements` condition over the other conditions.

---

- **H2:** Participants spend the least amount of time exploring in the `No-Points` condition prototype.
**Null:** Participants do not spend the least amount of time exploring in the `No-Points` condition prototype, compared to the other conditions.

---

- **H3:** Participants will be most motivated to add information to washroom listings in the `Points-and-Achievements` condition.
- **Null:** There is no significant difference in participant motivation to add washrooms across different conditions.




<br>

### 4b.9. Planned Statistical Analysis

Given the within-subject design, we will use a **Repeated Measures Analysis of Variance (ANOVA)** to test our hypotheses. This should allow us to compare the means of the different conditions, while accounting for the fact that the same participants are being tested in each condition. 

Since we will have multiple comparisons, we will use the **Bonferroni correction** if the ANOVA results are significant. This will help us to avoid Type I errors, ensuring that the observed differences are not due to chance.




<br>

### 4b.10. Expected Limitations of the Planned Experiment

There are a few limitations that we expect to encounter in our experiment. These include:

- **Small sample size:** We are aiming to recruit 8-12 participants, which is a small sample size. This may limit the generalizability of our results.
- **Private Setting:** As this experiment is about behaviour in a traditionally private setting, participant behaviour may be slightly different from the natural behaviour.
- **Participant Fatigue:** Since there are 3 conditions, the participants may become tired over the course of the experiment.
- **Learning Effects:** While we are counterbalancing the order of the conditions, learning effects may still be a problem.





<br>

## 4c. Supplementary Experiment Materials

See below for links to the supplementary materials for our experiment.