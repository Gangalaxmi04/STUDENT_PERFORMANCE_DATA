# STUDENT_PERFORMANCE_DATA
Project Overview
The objective of this project is to analyze the factors that impact students' GPA using a dataset containing information about 2392 students. The dataset includes demographic information, extracurricular activities, academic performance, and other related factors. The goal is to gain insights into how these various factors influence students' GPA and to build a predictive model for GPA.

Dataset Description
The dataset contains the following columns:

StudentID: Unique identifier for each student.

Age: Age of the student.

Gender: Gender of the student (possibly encoded as integers).

Ethnicity: Ethnicity of the student (encoded as integers):

0: White
1: Black or African American
2: Hispanic or Latino
3: Asian
4: Native American or Alaska Native
5: Native Hawaiian or Other Pacific Islander
6: Other
ParentalEducation: Education level of the student's parents (encoded as integers).

StudyTimeWeekly: Number of hours spent studying per week.

Absences: Number of school absences.

Tutoring: Whether the student receives tutoring (encoded as integers):
0: Did not receive tutoring
1: Received tutoring
ParentalSupport: Level of parental support (encoded as integers).

Extracurricular: Participation in extracurricular activities (encoded as integers):
0: Did not participate in extracurricular activities
1: Participated in extracurricular activities

Sports: Participation in sports activities (encoded as integers):
0: Did not participate in sports
1: Participated in sports

Music: Participation in music activities (encoded as integers):
0: Did not participate in music activities
1: Participated in music activities

Volunteering: Participation in volunteering activities (encoded as integers).

GPA: Grade Point Average of the student (target variable).

GradeClass: The class/grade level of the student.

Data Cleaning and Preprocessing
Removing Irrelevant Features: Dropped features that do not significantly impact the target variable (GPA).
Checking for Multicollinearity: Ensured that there is no multicollinearity among the features to maintain model performance and interpretability.
Encoding Categorical Variables: Encoded categorical variables to numerical values for model compatibility.

Modeling
A Linear Regression model was used to predict the GPA of students based on the given features.

Linear Regression Results
Mean Squared Error (MSE): 0.037752808292322124
R² Score: 0.9536427015756929
The high R² score indicates that the model explains 95.36% of the variance in the GPA, suggesting a strong predictive performance.

