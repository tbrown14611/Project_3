# README for Project_3 (Working Document) This document will be replaced. 

Project ideation - Started 07/18/2024
Project Team

Data fetching - Started 07/18/2024
Chris and Team

Data exploration
Chris and Team

Data transformation
Chris and Team

Data analysis
Chris and Team

Data cleaning and preprocessing
Chris and Team

Testing ML models
scikit-learn
Keras
TensorFlow

PyTorch - Thomas 


Integrate AI tools into the project for deployment

Creating documentation - Started 07/18/2024
Thomas and Team

Communication Plan (creating the presentation):

 Project Purpose / Description
    Executive Overview
 Goal/Questions to be addressed
 Data Sources
    Clean and Consistent Data
Approach taken to achieve goals
Result/Conclusion
Summary
Future Considerations



Abstract: (sourceHighway traffic accident prediction using VDS big data analysis
Authors: Seong-Hun Park, Sung-Min Kim, and Young-Guk HaAuthors Info & Claims
The Journal of Supercomputing, Volume 72, Issue 7
Pages 2815 - 2831
https://doi.org/10.1007/s11227-016-1624-z
Published: 01 July 2016 Publication History)


 Traffic accidents that cause a lot of damages are occurring in Colorado (how many?). The most effective solution to these types of accidents can be to predict future accidents in advance, giving drivers chances to avoid the dangers or reduce the damage by responding quickly. 
 
 Predicting accidents on the road can be achieved using classification analysis, a data mining procedure requiring enough data to build a learning model. However, building such a predicting system involves several problems. It requires many hardware resources to collect and analyze traffic data for predicting traffic accidents since the data are extremely large.

 Our Team will choose from the traffic data currently available that will be used for predicting accidents.


## Final Project Overview
For the Final Project, you will work with your group to collaboratively solve or analyze a problem using advanced ML methodologies. In your solution, you will incorporate transformer models, natural language processing (NLP) techniques, and other tools acquired throughout the course, in addition to at least one new technology that we haven’t covered together.

Here are the specific requirements:

Identify a problem worth solving or analyzing.
Find a dataset or datasets that are sufficiently large enough to effectively train a ML model or neural network with a high degree of accuracy to ensure that your results are reliable.
Evaluate the trained model(s) using testing data. Include any calculations, metrics, or visualizations needed to evaluate the performance.
You must use at least two of the following:
scikit-learn
Keras
TensorFlow
Hugging Face
spaCy or Natural Language Toolkit (NLTK)
LangChain
OpenAI
You must use one additional library or technology NOT covered in class, such as:
Valence Aware Dictionary for Sentiment Reasoning (VADER)
Whisper (OpenAI’s automatic speech recognition system)
DALL·E (OpenAI’s text-to-image model)
Other OpenAI capabilities, including:
Text-to-speech
GPT-4 with vision (GPT-4V)
PyTorch
For this project, you can focus your efforts within a specific industry, as detailed in the following examples.

Finance
Build a customer service chatbot for a financial firm that analyzes a user’s request and makes customized recommendations in one or more languages.

Develop a deep learning model that forecasts and predicts stock prices for at least three publicly traded companies.

Use NLP, transformers, or OpenAI to summarize key takeaways from a company’s earnings call.

Healthcare
Build a transformer model that captions medical images in one or more languages.

Develop a deep learning model to distinguish between malignant and benign moles.

Use NLP to de-identify medical data such as name, birthdate, and ID number.

Custom
We’ve only specified healthcare and finance, but any industry can benefit from applying NLP, transformers, or OpenAI technologies. Consider preparing a data deep dive or infrastructure review that shows ML in the context of what we’ve already learned.

Develop an integrated AI model that accurately detects and filters out spam messages.

Use NLP to analyze social media data or customer reviews to understand user sentiment about a product, service, or issue.

Develop a transformer model that translates between two or more languages of your choice.

Working with Your Group
When working on an online group project, it’s crucial to meet with your group and communicate regularly. Plan for significant collaboration time outside of class. The following tips can help you make the most of your time:

Decide how you’re going to communicate with your group members when you begin. Create a Slack channel, exchange phone numbers, and ensure that the group knows each group member’s available working hours.

Set up an agile project by using GitHub ProjectsLinks to an external site. so that your group can track tasks.

Create internal milestones to ensure that your group is on track. Set due dates for these milestones so that you have a timeline for completing the project. Some of these milestones might include:

Project ideation;

Data fetching;

Data exploration;

Data transformation;

Data analysis;

Data cleaning and preprocessing

Testing ML models;

Integrate AI tools into the project for deployment

Creating documentation; and

Creating the presentation.

Since this is a two-week project, make sure that you have completed at least half of your project by the end of the first week in order to stay on track.

Although you will divide the work among the group members, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your teammates regularly and offer support.

Support and Resources
Your instructional team will provide support during classes and office hours. You will also have access to learning assistants and tutors to help you with topics as needed. Make sure to take advantage of these resources as you collaborate with your group on this project.

Requirements
Model Implementation (25 points)
There is a Jupyter notebook that thoroughly describes the data extraction, cleaning, preprocessing, and transformation process, and the cleaned data is exported as CSV files for a machine or deep learning model, or NLP application. (10 points)

A Python script initializes, trains, and evaluates a model or loads a pre-trained model. (10 points)

At least one additional library or technology NOT covered in class is used. (5 points)

Model Optimization (25 points)
The model optimization and evaluation process showing iterative changes made to the model and the resulting changes in model performance is documented in either a CSV/Excel table or in the Python script itself. (15 points)

Overall model performance is printed or displayed at the end of the script. (10 points)

GitHub Documentation (25 points)
GitHub repository is free of unnecessary files and folders and has an appropriate .gitignore in use. (10 points)

The README is customized as a polished presentation of the content of the project. (15 points)

Presentation Requirements (25 points)
Your presentation should cover the following:

An executive summary or overview of the project and project goals. (5 points)

An overview of the data collection, cleanup, and exploration processes. Include a description of how you evaluated the trained model(s) using testing data. (5 points)

The approach that your group took to achieve the project goals. (5 points)

Any additional questions that surfaced, what your group might research next if more time was available, or a plan for future development. (3 points)

The results and conclusions of the application or analysis. (3 points)

Slides that effectively demonstrate the project. (2 points)

Slides that are visually clean and professional. (2 points)


 ## Data Dictonary  https://smoosavi.org/datasets/us_accidents
 #	Attribute	Description	Nullable
1	ID	This is a unique identifier of the accident record.	No
2	Severity	Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).	No
3	Start_Time	Shows start time of the accident in local time zone.	No
4	End_Time	Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.	No
5	Start_Lat	Shows latitude in GPS coordinate of the start point.	No
6	Start_Lng	Shows longitude in GPS coordinate of the start point.	No
7	End_Lat	Shows latitude in GPS coordinate of the end point.	Yes
8	End_Lng	Shows longitude in GPS coordinate of the end point.	Yes
9	Distance(mi)	The length of the road extent affected by the accident.	No
10	Description	Shows natural language description of the accident.	No
11	Number	Shows the street number in address field.	Yes
12	Street	Shows the street name in address field.	Yes
13	Side	Shows the relative side of the street (Right/Left) in address field.	Yes
14	City	Shows the city in address field.	Yes
15	County	Shows the county in address field.	Yes
16	State	Shows the state in address field.	Yes
17	Zipcode	Shows the zipcode in address field.	Yes
18	Country	Shows the country in address field.	Yes
19	Timezone	Shows timezone based on the location of the accident (eastern, central, etc.).	Yes
20	Airport_Code	Denotes an airport-based weather station which is the closest one to location of the accident.	Yes
21	Weather_Timestamp	Shows the time-stamp of weather observation record (in local time).	Yes
22	Temperature(F)	Shows the temperature (in Fahrenheit).	Yes
23	Wind_Chill(F)	Shows the wind chill (in Fahrenheit).	Yes
24	Humidity(%)	Shows the humidity (in percentage).	Yes
25	Pressure(in)	Shows the air pressure (in inches).	Yes
26	Visibility(mi)	Shows visibility (in miles).	Yes
27	Wind_Direction	Shows wind direction.	Yes
28	Wind_Speed(mph)	Shows wind speed (in miles per hour).	Yes
29	Precipitation(in)	Shows precipitation amount in inches, if there is any.	Yes
30	Weather_Condition	Shows the weather condition (rain, snow, thunderstorm, fog, etc.)	Yes
31	Amenity	A POI annotation which indicates presence of amenity in a nearby location.	No
32	Bump	A POI annotation which indicates presence of speed bump or hump in a nearby location.	No
33	Crossing	A POI annotation which indicates presence of crossing in a nearby location.	No
34	Give_Way	A POI annotation which indicates presence of give_way in a nearby location.	No
35	Junction	A POI annotation which indicates presence of junction in a nearby location.	No
36	No_Exit	A POI annotation which indicates presence of no_exit in a nearby location.	No
37	Railway	A POI annotation which indicates presence of railway in a nearby location.	No
38	Roundabout	A POI annotation which indicates presence of roundabout in a nearby location.	No
39	Station	A POI annotation which indicates presence of station in a nearby location.	No
40	Stop	A POI annotation which indicates presence of stop in a nearby location.	No
41	Traffic_Calming	A POI annotation which indicates presence of traffic_calming in a nearby location.	No
42	Traffic_Signal	A POI annotation which indicates presence of traffic_signal in a nearby loction.	No
43	Turning_Loop	A POI annotation which indicates presence of turning_loop in a nearby location.	No
44	Sunrise_Sunset	Shows the period of day (i.e. day or night) based on sunrise/sunset.	Yes
45	Civil_Twilight	Shows the period of day (i.e. day or night) based on civil twilight.	Yes
46	Nautical_Twilight	Shows the period of day (i.e. day or night) based on nautical twilight.	Yes
47	Astronomical_Twilight	Shows the period of day (i.e. day or night) based on astronomical twilight.	Yes
