# Health_Checker
**Creators**: Dagmara Krenich, Daniel Sterzel

Welcome to **Health_Checker** – a unique experiment that combines data analysis and machine learning to assess health risks and emotional well-being!

---

## 🔍 Overview

Our project is divided into two main parts:

- **Analytical Side**: Led by Dagmara Krenich, responsible for data processing and analysis.
- **Programming Side**: Led by Daniel Sterzel, responsible for the development of the ML model and the application.

**The Goal**: 
The program collects daily data from participants, processes it, and uses a trained ML model to predict health status, likelihood of illness, and other health metrics based on the input data. The model also provides feedback about the user's emotional and physical state.

---

## ⚙️ How It Works

1. **User App**: 
   Participants receive a simple Python application that assigns them a random color, ensuring anonymity in Google Sheets.
   [more info soon.....]
   
3. **Daily Data Collection**: 
   Each day, participants enter their data in a pre-designed format, including:
   - **Sleep Duration** 💤
   - **Body Temperature** 🌡️
   - **Human Benchmark Test Results** (e.g., Reaction Time) ⏱️
   - **Emotional State** 😊😟
   Each row in the Google Sheets contains data collected from participants for a specific day.

   The structure of each row is as follows:
   - day 1 -> person 1
   - day 1 -> person 2
   - day 1 -> person 3
   - day 2 -> person 1
   etc.

4. **Daily Drawing**: 
   Participants draw a representation of their emotional state for the day.  
   Each day, all participants receive a white sheet of paper with a large black rectangle in the center.  
   Their task is to visually express their emotional state by using four basic shapes — **rectangle**, **square**, **triangle**, and **circle** — in any arrangement they choose and the limit is 20 figures per one drawing.

   These drawings are later analyzed by the model, which interprets them based on a predefined psychoanalytic framework. The insights from this analysis help improve the personalization and accuracy of the           feedback given to each participant.

5. **Data Analysis**: 
   After the experiment concludes, the data is processed, visualized, and analyzed using **SQL** and **Python**. It is then input into the trained ML model, which provides insights into the user's:
   - **Health Status** 🏥
   - **Illness Risk** 🤒
   - **Fatigue Level** 😴

6. **Feedback**: 
   A small personalized feedback message is generated based on the model's findings.

---

## ⚠️ Important

**This is not medical advice** – this experiment is purely for data collection and analysis purposes.

---

## 🛠️ Tools & Technologies

- **Python**: For the main application and data analysis.
- **Machine Learning**: For building the prediction model.
- **SQL**: For managing and analyzing the collected data.

---

## 📅 Next Steps

- Experiment phase
- Model training and evaluation
- Report generation and final analysis

---

Stay tuned for more updates and feel free to contribute to the project!

