# OIBSIP Internship Context and Progress

This file is a handoff summary for continuing work on the OIBSIP Data Science internship repository.

## Student Information

- Name: Sumeet Kailash Chauhan
- GitHub username: SumeetChauhan27
- Education: B.Tech Computer Science Engineering
- Internship: Oasis Infobyte Internship Program
- Domain: Data Science
- Internship start date: 05 June 2026
- Submission deadline: 15 July 2026

## GitHub Repository

- Repository name: OIBSIP
- Repository URL: https://github.com/SumeetChauhan27/OIBSIP
- Local path: `C:\Users\Sumeet\Desktop\OIBSIP`
- Active branch: `main`
- Remote name: `origin`
- Remote URL: `https://github.com/SumeetChauhan27/OIBSIP.git`

## Internship Submission Rules

All tasks must be submitted through the official Oasis Infobyte submission form only.

Submission form should include:

- GitHub repository link
- Live demo link, only if applicable
- Proper README documentation
- Correct file naming format

Required file naming format:

```text
YourName_TaskNumber
```

For Sumeet Chauhan, Task 1 notebook should be named:

```text
SumeetChauhan_Task1.ipynb
```

## Assistant Role Preference

Act as an internship mentor.

When helping with tasks:

- Keep explanations beginner-friendly.
- Do not make the project unnecessarily advanced.
- Avoid overengineering.
- Use simple code that a beginner intern can understand and explain.
- Keep project structure GitHub-ready but not too complex.
- Prioritize internship submission requirements.
- Help with README, notebook, screenshots, GitHub push, and submission readiness.

## Task 1 Completed

Task 1 is Iris Flower Classification.

Objective:

Build a machine learning model to classify iris flowers into:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Dataset features:

- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

Target:

- Species

Algorithm used:

- Random Forest Classifier

Libraries used:

- Pandas
- Scikit-learn
- Jupyter Notebook

Evaluation metrics:

- Accuracy Score
- Classification Report
- Confusion Matrix

## Current Repository Structure

Current important files:

```text
OIBSIP/
├── README.md
├── .gitignore
├── Context/
│   └── OIBSIP_Context.md
└── Task_1_Iris_Flower_Classification/
    ├── Iris.csv
    ├── SumeetChauhan_Task1.ipynb
    ├── README.md
    ├── requirements.txt
    ├── assets/
    │   └── .gitkeep
    └── screenshots/
        ├── output.png
        ├── confusion_matrix.png
        └── .gitkeep
```

There was an older local folder named `task1/` from initial notebook work. It was not deleted, but it was added to `.gitignore` so it is not tracked in Git.

## Task 1 Work Done

The original notebook had an absolute dataset path:

```text
C:\Users\Sumeet\Desktop\Iris.csv
```

The project was cleaned so the dataset is inside the task folder and the notebook uses:

```python
pd.read_csv("Iris.csv")
```

This makes the notebook portable on GitHub.

The Task 1 notebook was intentionally simplified after feedback because the first version was too advanced for a beginner intern. The final notebook is beginner-level and contains:

1. Import libraries
2. Load dataset
3. Check shape
4. Drop `Id` column
5. Split features and target
6. Train-test split
7. Train Random Forest Classifier
8. Predict
9. Print accuracy
10. Print classification report
11. Print confusion matrix
12. Conclusion

Extra advanced files were removed:

- `iris_flower_classification.py`
- `INTERVIEW_QA.md`

The current Task 1 notebook name follows the required format:

```text
SumeetChauhan_Task1.ipynb
```

## Task 1 README

The Task 1 README is intentionally simple and beginner-friendly.

It includes:

- Project overview
- Objective
- Dataset information
- Technologies used
- Project workflow
- Algorithm used
- Results
- Submission details
- Author information

It also mentions:

- Main file: `SumeetChauhan_Task1.ipynb`
- GitHub repository link
- Submission through official Oasis Infobyte form

## Screenshots

The `screenshots/` folder contains:

- `output.png`
- `confusion_matrix.png`

These were generated earlier and kept for submission evidence.

## Git Work Already Done

Git was initialized in the local `OIBSIP` folder.

Remote was added:

```bash
git remote add origin https://github.com/SumeetChauhan27/OIBSIP.git
```

Branch was renamed to:

```bash
main
```

Task 1 was committed and pushed successfully.

Previous pushed commit:

```text
e84b164 - Add Task 1 iris flower classification
```

Git user config found:

```text
user.name = SumeetChauhan27
user.email = sumeetchuhan428@gmail.com
```

Git safe directory was also configured for:

```text
C:/Users/Sumeet/Desktop/OIBSIP
```

## Important Style Decision

Do not make future tasks too advanced unless Sumeet asks.

Preferred style:

- Simple folder structure
- One main notebook per task
- README for each task
- Dataset file if needed
- Screenshots folder if output images are required
- Basic `requirements.txt`
- Clear beginner explanations

Avoid by default:

- Extra Python scripts
- Extra interview Q&A files
- Complex functions/classes
- Advanced visualizations unless required
- Deployment/live demo unless the task asks for it

## What To Do Next

For the next task:

1. Create a new folder like `Task_2_Project_Name`.
2. Use notebook naming format:

```text
SumeetChauhan_Task2.ipynb
```

3. Keep the notebook beginner-friendly.
4. Add a simple task README.
5. Add `requirements.txt` only with needed libraries.
6. Add screenshots if the task has visible output.
7. Commit and push to GitHub after checking everything.

## Useful Git Commands

Check status:

```bash
git status --short
```

Stage files:

```bash
git add .
```

Commit:

```bash
git commit -m "Add Task 2 project"
```

Push:

```bash
git push
```

## Final Current State

Task 1 is uploaded to GitHub and ready for the Oasis Infobyte submission form.

Submission repository link:

```text
https://github.com/SumeetChauhan27/OIBSIP
```

