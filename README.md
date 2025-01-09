# Inato AI Engineer technical assignment

## How to Successfully Complete this Technical Assignment

1. Clone the repository provided (do **not** fork it)
2. Publish your code in a private GitHub Repo (or Gitlab, or whatever...)
3. Give us access to that repo and tell us approximatively how much time you spent on this assignment

Note that the test should take no more than 3 hours to complete.

## Guidelines for Success

To ensure success and demonstrate your abilities, please adhere to the following guidelines:

- Start with a simple approach to have a baseline of results for comparison
- The last state of your code should be clean and ready to be reviewed by peers in a real-world situation
- Prefer making your code clean and your models evaluation insightful than multiplying the iteration to improve your model performance

## Brief 

When a hospital applies to participate in a clinical trial, they include the CV of the physician responsible for overseeing the trial (referred to as the Principal Investigator, or PI). Pharmaceutical companies (a.k.a sponsors) then review these CVs. As part of their review, they verify which trials the PI has previously participated in. In particular they focus on whether he was involved in publicly available trials that the hospital participated in and that the sponsor has deemed relevant.

The challenge is, manually reviewing CVs is time-consuming and might miss out on potential matches.

*Goal:*
Based on the input data, develop an algorithm that, provided with a PDF CV and a target trial, determines whether the trial is included in the CV.


## Technologies

You can use any library or technology. We will supply you with an OpenAI API key, allowing you to utilize powerful, off-the-shelf LLMs as needed.

## Input data details

**Principal investigators's resumes**
- CVs.zip : 43 resumes in PDF format
- A principal investigator's resume is a document that highlights the researcher’s qualifications, experience, and accomplishments in conducting clinical or scientific research, emphasizing their expertise, leadership in previous studies, and contributions to the scientific community. It serves to demonstrate the investigator's capability and expertise to lead a research project or clinical trial, ensuring adherence to the research plan, ethical guidelines, and regulatory compliance.

**Ground Truth**
- ground_truth.csv: This files provides you with final ground truth
- For each one of the above resumes:
    - The trial we are looking for in the CV
    - Whether it was found in the CV or not

## Enjoy the assignment and good luck! ##
