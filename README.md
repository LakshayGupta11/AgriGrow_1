AgriGrow 🌿
A simple and easy to use Machine Learning and Deep Learning based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.
MOTIVATION 💪
Farming is one of the major sectors that influences a country’s economic growth.

In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield.

In this project, we present a Web Application in which the following applications are implemented:

Fertilizer recommendation and
Plant disease prediction, respectively.
Crop recommendation,
In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow.

For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements.

For the last application, that is the plant disease prediction application, the user can input an image of a diseased plant leaf, and the application will predict what disease it is and will also give a little background about the disease and suggestions to cure it.

DATASETS USED 📊
Crop recommendation dataset (custom built dataset)
Fertilizer suggestion dataset (custom built dataset)
Disease detection dataset
Built with 🛠️
       

    

DEPLOYMENT 🚀
This website is deployed at Heroku You can access it here
Note: The website may take a minute to load sometimes, as the server may be in hibernate state

HOW TO USE 💻
Enter you email address and password and get yourself registered with the Application. You will receive a mail highlighting the login credentails.

Crop Recommendation system ==> enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer this website for more information. Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the Weather API from where humidity, temperature data is fetched.

Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

Disease Detection System ==> Upload an image of leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest you how to prevent/cure the disease accordingly. Note that, for now it only supports following crops

SUPPORTED CROPS
Apple
Blueberry
Cherry
Corn
Grape
Pepper
Orange
Peach
Potato
Soybean
Strawberry
Tomato
Squash
Raspberry
HOW TO RUN LOCALLY 🛠️
Before the following steps make sure you have git, Anaconda or miniconda installed on your system

Clone the complete project with https://github.com/NischayGoyal1/cultyvate.git or you can just download the code and unzip it

Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block

conda create -n cultyvate python=3.10
pip install -r requirements.txt
conda activate cultyvate
And finally run the project with

python app.py
Open the localhost url provided after running app.py and now you can use the project locally in your web browser.

DEMO
Crop recommendation system
Crop Recommendation

Fertilizer suggestion system
Fertiliser Recommendation

FURTHER IMPROVEMENTS 📈
This was my first big project so there are lot of things to improve upon

CSS code formatting needs to be done (some code in file and some inline)
The UI can be made better
More data can be collected manually via web scrapping to make the system more accurate
Additional plant images can be collected to make the disease detection part more robust and generalized
Modularized code can be written instead of writing in Jupyter Notebooks
