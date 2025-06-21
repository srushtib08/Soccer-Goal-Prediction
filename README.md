# Soccer-Goal-Prediction using Linear Regression


Objective:
To predict how many goals a soccer player might score based on their performance metrics, physical attributes, and transfer history using a Linear Regression model.


Dataset Overview:
The dataset contains information about 202 soccer players, with features that can influence goal scoring. Key columns include:

-- PlayerName, Club: Identification details

-- DistanceCovered(InKms): Total kilometers covered in matches

-- MinutestoGoalRatio: Average minutes needed per goal

-- ShotsPerGame: Number of shots taken per game

-- AgentCharges, Cost, PreviousClubCost: Financial data

-- BMI, Height, Weight: Physical attributes

-- Score: A performance score

-- Goals (Target Variable): Total goals scored (this is what we want to predict)


Approach:
Data Preprocessing:

1. Remove non-numeric columns like PlayerName and Club (not used in modeling directly).

2. Check for null values (none in this case).

3. Normalize or scale features if needed.


Feature Selection:

Choose numeric features like DistanceCovered, ShotsPerGame, MinutestoGoalRatio, BMI, Height, Weight, etc., to use as predictors.


Model Training:

1. Use Linear Regression to learn the relationship between input features and the Goals scored.

2. Split the data into training and testing sets (e.g., 80% train, 20% test).


Evaluation:

1. Measure the accuracy of predictions using metrics like:

2. Mean Absolute Error (MAE)

3. R² Score (how well the model explains the variation in goals)

4. Plot actual vs predicted goals for visualization.



Expected Insights:
-- Players with more shots per game and lower minutes-to-goal ratios tend to score more.

-- Physical attributes like BMI and performance indicators like Score may also influence goal count.

-- Financial variables (e.g., Cost, AgentCharges) might indirectly reflect player quality and popularity.



Conclusion:
This project uses a simple, explainable machine learning model—Linear Regression—to predict soccer player performance in terms of goals scored. It helps in talent scouting, performance assessment, and transfer market decisions.
