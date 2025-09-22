# 🤝 Friend Seeker

**Friend Seeker** 🚀 is an application built with **Streamlit** that helps you find people with similar interests 👥. Based on a short survey, it matches you to the right group and shows you its characteristics.

------------------------------------------------------------------------

## 🛠️ Technologies

-   🐍 **Python**
-   📊 **Streamlit** - web interface
-   🤖 **PyCaret** - machine learning model (clustering)
-   📈 **Plotly Express** - interactive charts
-   📄 **Pandas** - data processing

------------------------------------------------------------------------

## 🔍 How it works?

1.  📝 **Fill out a short survey** in the sidebar (age, education, favorite places, pets, gender).  
2.  🤖 The **ML model** predicts which cluster (group) you belong to.  
3.  📊 **You receive a description of your group** + interactive charts showing its composition.  
4.  🔄 **You can also browse other groups** and see their characteristics. 

------------------------------------------------------------------------

## 🚀 Running the app

1.  Install the required libraries:

    ``` bash
    pip install -r requirements.txt
    ```

2.  Run the application:

    ``` bash
    streamlit run app.py
    ```

3.  Open in your browser 👉 <http://localhost:8501>

------------------------------------------------------------------------

## 📂 Project structure

    .
    ├── app.py                                # Streamlit app code
    ├── welcome_survey_simple_v2.csv          # Input data
    ├── welcome_survey_clustering_pipeline_v2 # Trained ML model
    ├── welcome_survey_cluster_names_and_descriptions_v2.json # Cluster descriptions
    └── README.md                             # Documentation

------------------------------------------------------------------------

## 🎉 App features

-   ✅ Match to a group based on a short form  
-   ✅ View a description of the group and its characteristics  
-   ✅ Interactive charts 📊  
-   ✅ Compare different groups  

------------------------------------------------------------------------

💡 **Friend Seeker** helps you discover which community fits you best and connect with people who share your interests!
