# WebApp-using-Streamlit
 Data Science Web Application using Python

 This web app has been created using Python and Streamlit. 
 The data is taken from Motor Vehicle Collisions from Official website of City of New York.

Install and import the below mentioned libraries.
```
pip install streamlit
pip install pandas
pip install numpy
pip install pydeck
pip install plotly.express
```
- Pandas is used to create Dataframes out of the .csv file to help select required columns and sort through the data.
- Pydeck and Plotly.express is used to create graphs
- The application itself is created using ``Streamlit``

1. The user can view the number of accidents according to time of the day by adjusting the slider provided.
2. The user can also view the most dangerous streets according to the mode of transportion.

To run the Application locally, type 
```
Streamlit run App.py
```
