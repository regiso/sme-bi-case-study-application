# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The goal of exercises in case study is for learners to apply what was learned in the previous courses to new problems or situations. This is best pedagogical practice for retaining and building skills.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4) from the Case Study: Analyzing Customer Churn in Tableau. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners in **case studies**.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

*One measurable learning objective that this exercise assesses*
Transform raw Tree Inventory data into a format that is compatible with Market Basket Analysis

#### Context

*3 - 4 sentence description of why it’s important to to do this task (linking back to the learning objective). Explain how this would be used in a real-life situation. Why is it useful, what problem does it solve?*
You can look at the same [exercise]([url](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4)) from the Case Study: Analyzing Customer Churn in Tableau on how to write a good context.

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Step 1 Examine the fields in the data set
- Step 2 Hide fields that are not necessary for the Market Basket Analysis
- Step 3 Join the transformed dataset to its original version
- Step 4 Hide fields in the joined data set to match the transformation in step 2
- ...

#### Exercise question:
*This is a question presented to learners to check if the steps above were properly completed. It can be a multiple choice question or a question with a 1-3 word answer. It is often not possible to check if all the steps are completed, in this case; the priority is to check that the learner meets the learning objective.*

Which of the 9 variables in the transformed data set were engineered from the original Buffalo Open Data Tree Inventory?
Answer - Genus
Distractors - Site ID, Total Yearly Eco Benefits

#### End goal:

*Add an image of the final visualization here.*
![vmimage1](https://user-images.githubusercontent.com/16366682/172264762-732464a5-ca7f-488f-a248-bf1861175e2f.jpg)

## Finalized Workbook

#### Files
You can upload your final workbook in the exercises folder as `ex-final-sol.twbx` or `ex-final-sol.pbix`.

#### Explanation & Description
Which answers will the learner be able to solve once building this? How does it fit in the bigger picture?

This Market Basket Analysis will contribute to the strategic planning process for the Buffalo Urban Forest.
The results will provide insights into options to maintaining the existing character and biodiversity.

#### End goal:

*Add an image of the final visualization here.*
![Dashboard](https://user-images.githubusercontent.com/16366682/172268397-2ffac4d3-4850-44f8-a2d8-c12d9d3315a0.jpg)
