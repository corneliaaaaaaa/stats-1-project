# stats-1-project
We use data from Programming Design Online Grading System (PDOGS) in NTU from 2019 to 2021 to analyze students' study behavior and aim to figure out the reasons why one improves or performs worse. The code files are part of the project and contain the following sections:
- Compute the average midterm scores of students who did or didn't do old exams before midterms (for score_oldExam.ipynb)
- Find out whether doing old exams are related to students' performances (for 4group_oldExam.ipynb)
  1. Divide all students into 4 groups according to their first and second midterm scores
    - The 4 groups are high-high, high-low, low-high, low-low.
    - If a student has his/her first midterm score in the top 50% and his/her second midterm score out of the top 50%, he/she will be a member of the "high-low" group.
  2. Plot pie charts to find out the proportions of students in each group who did old exams before midterms
