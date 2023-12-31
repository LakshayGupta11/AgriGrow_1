# AgriGrow 🌿
#### A simple and easy to use Machine Learning and Deep Learning based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

-Since independence and even before, India has been regarded as an Agrarian economy with almost 44% of its population deriving livelihood from it, making it a major sector to focus upon but the problem remains in its contribution to the GDP which remains significantly lower to about (18-20) %.
-India being on the road to become the most populated nation by 2023 surpassing China, one of the major challenges is to support and sustain the food security as well as welfare in India by backing and assisting the farmers of the nation.
-Major issue among all is the scattered availability of educational and assistive sources to farmers which are not personalized according to their land and needs, cannot be accessed easily and are difficult to understand hence,
-There is a need to develop and implement a single user-friendly web-based platform that acts as a ‘one stop solution’  for farmers and addresses all problems faced by them in every sphere of the work involved in agriculture. It also assist and educate them to extract maximum profit out of their land using environmentally sustainable practices in order to make them financially stable, self-reliant and socially responsible.



## MOTIVATION 💪
- Farming is one of the major sectors that influences a country’s economic growth. 

- In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield. 

- In this project, we present a Web Application in which the following applications are implemented: 
                


   1. Fertilizer recommendation and 
   2. Plant disease prediction, respectively. 
   3. Crop recommendation, 

- In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow. 
    
- For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements. 
    
- For the last application, that is the plant disease prediction application, the user can input an image of a diseased plant leaf, and the application will predict what disease it is and will also give a little background about the disease and suggestions to cure it.

## DATASETS USED 📊
- [Crop recommendation dataset ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset) (custom built dataset)
- [Fertilizer suggestion dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv) (custom built dataset)
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

##Future problems that can be resolved through a digital platform: 
-Use of primitive and unsustainable agricultural practices (leading to environmental degradation).
-Meagre income of farmers, problems of financial inclusion, farmers in debt traps and low profitability of farmers .
-Low agricultural trade and export. 
-Small size or largely divided agricultural lands in India. 
-Lack of communication between farmers living in the same geographical area and less co-operation among them (social division between large and small farmers) 
-Minimal use of new innovations and technology.
-Illiteracy and unawareness about: 
-New government welfare schemes and incentives launched for farmers.
-Advanced agricultural techniques and technology that is efficient as well as sustainable
-More profitable and environment-friendly crops that they can grow on their land  
-Market prices of their agricultural products.
-More efficient and eco-friendly sources of energy they can use to power their machines. 
-The impact of climate change on agriculture.




## Built with 🛠️
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>
<code><img height="30" src="https://cdn.iconscout.com/icon/free/png-256/heroku-225989.png"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pytorch/pytorch/39fa0b5d0a3b966a50dcd90b26e6c36942705d6d/docs/source/_static/img/pytorch-logo-dark.svg"></code>

## DEPLOYMENT 🚀


 This website is deployed at [Heroku](https://www.heroku.com/)
 You can access it [here](https://AgriGrows.herokuapp.com/)
 <br>
 **_Note: The website may take a minute to load sometimes, as the server may be in hibernate state_**

## HOW TO USE 💻
- Enter you email address and password and get yourself registered with the Application. You will receive a mail highlighting the login credentails.
- Crop Recommendation system ==> enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity, temperature data is fetched.

- Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

- Disease Detection System ==> Upload an image of leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest you how to prevent/cure the disease accordingly.
Note that, for now it only supports following crops

## SUPPORTED CROPS
- Apple
- Blueberry
- Cherry
- Corn
- Grape
- Pepper
- Orange
- Peach
- Potato
- Soybean
- Strawberry
- Tomato
- Squash
- Raspberry

## HOW TO RUN LOCALLY 🛠️
- Before the following steps make sure you have [git](https://git-scm.com/download), [Anaconda](https://www.anaconda.com/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your system
- Clone the complete project with `https://github.com/LakshayGupta11/AgriGrow_1.git` or you can just download the code and unzip it


- Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block
  ```
  conda create -n AgriGrow python=3.10
  pip install -r requirements.txt
  conda activate AgriGrow
  ```
- And finally run the project with
  ```
  python app.py
  ```
- Open the localhost url provided after running `app.py` and now you can use the project locally in your web browser.
## DEMO

- ### Crop recommendation system

![Crop Recommendation](https://user-images.githubusercontent.com/83203229/167293953-a40bbfdf-2a8f-4d2d-bbfa-929dec0d19f9.gif)

- ### Fertilizer suggestion system

![Fertiliser Recommendation](https://user-images.githubusercontent.com/83203229/167294466-b26375b9-1a8c-4e28-be5b-011f243b20e7.gif)


<!-- - ### Disease Detection system
![demo](https://media.giphy.com/media/NnMwEp2tGZdfnJbyjr/giphy.gif) -->







## FURTHER IMPROVEMENTS 📈
This was my first big project so there are lot of things to improve upon

- CSS code formatting needs to be done (some code in file and some inline)
- The UI can be made better
- More data can be collected manually via web scrapping to make the system more accurate 
- Additional plant images can be collected to make the disease detection part more robust and generalized
- Modularized code can be written instead of writing in Jupyter Notebooks

  # DEVELOPERS 👨‍💻

#### [Lakshay](https://github.com/LakshayGupta11)
#### [Nischay](https://github.com/NischayGoyal1)
#### [Samridhi](https://github.com/samridhikapoor)








