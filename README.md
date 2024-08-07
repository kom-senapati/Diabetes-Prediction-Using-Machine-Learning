# Diabetes Prediction Using Machine Learning

🔮 Welcome to the Diabetes Prediction project! This repository predicts diabetes using the PIMA Indians Diabetes Database.

$~$

## 📁 Project Structure

```
|__ data/
|   |__ diabetes.csv
|   
|__ gui/
|   |__ gui.py
|   |__ gui_ctk.py
|
|__ flask/
|   |__ app.py
|   |__ templates/
|       |__ index.html
|       |__ result.html
|
|__ api/
|   |__ main.py
|   
|__ streamlit/
|   |__ app.py
|   |__ page/
|       |__  build.py
|       |__  predict.py
|       |__  visualize.py
|
|__ model/
|   |__ model_joblib_diabetes
|
|__ Diabetes Prediction + Gradio Interface.ipynb 
|__ Diabetes Prediction.ipynb
|__ EDA_of_the_dataset.ipynb
|__ LICENSE
|__ README.md
|__ .gitignore
|__ CODE_OF_CONDUCT.md
|__ CONTRIBUTING.md
```

$~$

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Set up virtual environment (optional but recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   pip install --upgrade numpy
   ```
   > **NOTE**
   > 
   > Make sure you have installed numpy>=2.0.0 (pip will raise a dependency conflict error since ydata-profiling currently requires numpy<2, >=1.16 but that's not a problem for this project)

## 📊 How to Run Jupyter Notebook

- Start Jupyter Notebook server:
  ```bash
  jupyter notebook
  ```
- Navigate to `Diabetes Prediction.ipynb` and run the cells.

## 🖥️ How to Run GUI App

- Navigate to the `gui` folder:
  ```bash
  cd gui
  ```
- Run the GUI (Tkinter) application:
  ```bash
  python gui.py
  ```
- Run the GUI (Custom Tkinter) application:
  ```bash
  python gui_ctk.py
  ```

## 🌐 How to Run Flask Web App

- Navigate to the `flask` folder:
  ```bash
  cd flask
  ```
- Run the flask application:
  ```bash
  python app.py
  ```

## How to Run Streamlit Web App 📊 🛠️ 🔎

- Navigate to the `streamlit` folder:
  ```bash
  cd streamlit
  ```
- Run the streamlit application:
  ```bash
  streamlit run app.py
  ```
- Wait for the pages to load
     - Predict from the pre-existing model
     - Build your own (Random Forest Classifier) model and get insights on it
     - Visualize any dataset by generating its Exploratory Data Analysis

## 🌐 How to Run FastAPI API

- Navigate to the `api` folder:
  ```bash
  cd api
  ```
- Run the FastAPI application:
  ```bash
  fastapi dev main.py
  ```

$~$

## 📸 Screenshots

<details>
   <summary>
      <h4>Tkinter UI</h4>
   </summary>
   
   ![nd](https://github.com/SiddharthBahuguna/Diabetes-Prediction-Using-Machine-Learning/assets/112819453/58a43b40-76c4-471f-b143-bc5d619e3648)
</details>


<details>
   <summary>
      <h4>Gradio UI</h4>
   </summary>
   
   ![Gradio UI](https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/698ccb3d-916a-4858-9365-3d43c99ce358)
</details>


<details>
   <summary>
      <h4>Flask Web App</h4>
   </summary>

![Screenshot_26-6-2024_95820_127 0 0 1](https://github.com/kom-senapati/Diabetes-Prediction-Using-Machine-Learning/assets/92045934/f11a164f-befe-4b63-bf39-0a0ecad72009)
![Screenshot_26-6-2024_95830_127 0 0 1](https://github.com/kom-senapati/Diabetes-Prediction-Using-Machine-Learning/assets/92045934/474c2527-fb83-4eb8-9a1a-0bce7b0fb325)
</details>

<details>
   <summary>
      <h4>FastAPI API</h4>
   </summary>

![image](https://github.com/kom-senapati/Diabetes-Prediction-Using-Machine-Learning/assets/92045934/71ef099c-c8fd-490b-ad4d-09f731dd983e)
![image](https://github.com/kom-senapati/Diabetes-Prediction-Using-Machine-Learning/assets/92045934/72665cc2-69b7-4f55-81bd-5f164c78b6cc)
</details>



<details markdown='1'>
   <summary><h3>EDA Screenshots</h3> <br>
            <p>Click and Zoom on the Image for Better Visibility</p> 
   </summary>
      <h4>Histogram</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/7a0e54ec-3642-475e-9bae-e5de07963d25" alt="Histogram" width=60% height=60%>
      <br><br><br>
      <h4>Histplot and Kde</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/6c9a91e1-efaa-4f8d-8c87-b49f1e02f5f4" alt="Histplot+kde" width=60% height=60%>
      <br><br><br>
      <h4>Pie and Bar chart of Outcome</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/069bd677-9218-49d7-959c-bdab4e6d015a" alt="pie+bar of outcome" width=60% height=60%>
      <br><br><br>
      <h4>Correlation Matrix</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/026c91ae-680a-48fd-916d-58c7a620204a" alt="correlation_matrix" width=60% height=60%>
      <br><br><br>
      <h4>Boxplot</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/f036193e-d388-450b-83e1-5a59e3ba3fb6" alt="BOXPLOT" width=60% height=60%>
      <br><br><br>
      <h4>Countplot</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/0f667fa9-615e-4049-91e4-eb21165f87cc" alt="countplot" width=60% height=60%>
      <br><br><br>
      <h4>Scatterplot</h4>
      <img src="https://github.com/shravn-10/Diabetes-Prediction-Using-Machine-Learning/assets/109055682/7d44b143-a773-4be6-a047-27131aa407cf" alt="scatter-plot" width=60% height=60%>
</details>

<details>
   <summary>
      <h3>Streamlit Web App / UI</h3>
      <p>A multi-page Web Application consisting of three pages </p>
   </summary>
      <details styles={margin-left: 10px}>
         <summary>
            <p>🔮Predict : Using the pre-built GBC model</p>
         </summary>
         <img src="https://github.com/raokarthik15/Diabetes-Prediction-Using-Machine-Learning/assets/99039316/5e7d00ca-1d5b-41fe-9ae7-2ae62dbf0f5a" alt="Predict-page-light-mode" width=70%>
         <img src="https://github.com/raokarthik15/Diabetes-Prediction-Using-Machine-Learning/assets/99039316/6904a4f1-22ea-4382-98af-06311062f1bf" alt="Predict-page-dark-mode" width=70%>
      </details>
      <details>
         <summary>
            <p>🛠️Build : A custom RFC model by optimizing hyperparameters</p>
         </summary>
         <img src="https://github.com/raokarthik15/Diabetes-Prediction-Using-Machine-Learning/assets/99039316/690822d5-1829-4f47-aeaf-799ce05f7395" alt="Build-page-light-mode" width=70%>
         <img src="https://github.com/raokarthik15/Diabetes-Prediction-Using-Machine-Learning/assets/99039316/abaaea2a-7118-4e92-b525-f7b8e46204e4" alt="Build-page-dark-mode" width=70%>
      </details>
      <details>
         <summary>
            <p>📊Visualize : A dataset by generating EDA as html using ydata-profiling</p>
         </summary>
         <img src="https://github.com/raokarthik15/Diabetes-Prediction-Using-Machine-Learning/assets/99039316/651bce3e-ea6f-4630-876f-ca13d52c4e4b" alt="Visualize-page-light-more" width=70%>
         <img src="https://github.com/raokarthik15/Diabetes-Prediction-Using-Machine-Learning/assets/99039316/96f040d1-b71a-4d7e-be98-df7c7096bd98" alt="Visualize-page-dark-mode" width=70%>
      </details>
</details>

## :bicyclist: Roadmap
- [x] EDA
- [x] Model
- [X] Tkinter Application
- [X] Custom Tkinter Application
- [X] Flask Web Application
- [X] Streamlit Application
- [X] FastAPI API

$~$

## Acknowledgement

- PIMA Indians Diabetes Database

$~$

## Description of EDA_of_the_dataset.ipynb

This notebook file contains the Exploratory Data Analysis of the Diabetes Dataset. It includes the visualization that helps understand the features present in the dataset and their relation with the outcome label. 

$~$

## 🤝 Contributing

Please read our [Contributing Guidelines](CONTRIBUTING.md).

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📜 Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

$~$

---

<!-- Open Source Programs -->
  <div>
    <h2><img src="https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/blob/master/Emojis/Hand%20gestures/Flexed%20Biceps.png?raw=true" width="35" height="35" > Open Source Programs</h2>
  </div>

  <table border="1" cellpadding="10">
        <tr>
            <td rowspan="2">
                <img src="https://vinyasa-summer-of-code-vsoc.devfolio.co/_next/image?url=https%3A%2F%2Fassets.devfolio.co%2Fhackathons%2F39347ec8c7be4f5ba28169197ce5dbfc%2Fassets%2Fcover%2F19.png&w=1440&q=100" alt="GSSOC Logo" width="400" height="85">
            </td>
            <td>
                <strong>VSOC 2024</strong>
            </td>
        </tr>
        <tr>
            <td>
                This project is part of Vinyasa Summer of Code. We warmly welcome contributions from the community to help elevate Diabetes-Prediction-Using-Machine-Learning.
            </td>
        </tr>
    </table>

---

$~$

![Line](https://user-images.githubusercontent.com/85225156/171937799-8fc9e255-9889-4642-9c92-6df85fb86e82.gif)

<div align="center">
  <h1>Tip from us 😇</h1>
  <p>It always takes time to understand and learn. So, don't worry at all. We know <b>you have got this</b>! 💪</p>
  <h3>Show some &nbsp;❤️&nbsp; by &nbsp;🌟&nbsp; this repository!</h3>
  <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60"> <em>Lets build <b>a cool community!</b></em>
</div>
