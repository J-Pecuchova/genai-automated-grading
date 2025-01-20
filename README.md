# **Automated Grading Dataset for Open-Ended Questions in Software Engineering**

## **Overview**
This dataset contains 1885 responses to 24 open-ended questions in the domain of software engineering. The questions focus on key concepts and practices in software development, particularly within the Scrum framework. The dataset is designed to support research and development in automated grading systems using GenAI models.

## **Questions**
The 24 questions cover fundamental concepts in software engineering. Example questions include:
1. Explain the term sprint.
2. Explain the term product backlog.
3. Explain the term sprint backlog.
4. Explain the term user story.
5. What phases does a software product go through in development?
6. How are these phases implemented in Scrum?
7. What do you see as the advantages of using Scrum?
8. What do you see as the disadvantages of using Scrum?


## **Dataset Attributes**
The dataset includes the following attributes:
- **`ID`**: A unique identifier for each response.
- **`Qnumber`**: The number of the question corresponding to the response.
- **`Question`**: The specific open-ended question to which the student responded.
- **`Answer`**: The full text of the student's answer.
- **`Reference`**: A reference answer based on course materials, serving as a baseline for evaluating the student's response.
- **`Grade1`**: Grades assigned by the first human evaluator.
- **`Grade2`**: Grades assigned by the second human evaluator.

## **File Format**
The dataset is stored in a CSV file with the following structure:
## File Format

The dataset is stored in a CSV file with the following structure:

| ID   | Qnumber | Question                | Answer             | Reference         | Grade1 | Grade2 |
|------|---------|-------------------------|--------------------|-------------------|------------------|------------------|
| 1    | 1       | Explain the term sprint | ...student answer... | ...model answer... | D               | D              |
| ...  | ...     | ...                     | ...                | ...               | ...              | ...              |
