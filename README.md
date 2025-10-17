
**UC Berkeley Extension - Professional Certificate in AI & Machine Learning Assignment 5.1**

**Assignment:** What factors contribute to a customer accepting the coupon?
Context My objective is to understand the factors that influence a drivers decision to accept a location-based mobile coupon while driving. I aim to explore how variables such as the type of business (e.g., restaurant, bar, coffee house), the presence of passengers (including minors), proximity to the business, weather conditions, and time of day affect coupon acceptance behavior. By analyzing these factorsL, I intend to develop a predictive model or framework that can determine the likelihood of a driver accepting a coupon once it is delivered to them.

**My goal:** in this project is to apply my understanding of visualizations and probability distributions to effectively distinguish between customers who accepted a driving coupon and those who did not. By analyzing patterns in the data, I aim to uncover meaningful insights that can help predict coupon acceptance behavior.*

**Data Dictionary:<br>**
Destination:        Indicates where the person is traveling to (No Urgent Place, Work, or Home).<br>
Passenger:          Indicates if passengers are Friends, Kid(S), or the driver is alone.<br>
Weather:            The type of weather, Sunny,Rainy or Snowy.<br>
Temperature:        Indicates the temperature degrees: (30, 55 or 80).<br>
Time:               Indicates coupon was offered: (10:00AM/PM, 7:00AM, 2:00PM or 3:00PM.<br>
Coupon_Type:        Indicates <br>
Expiration Time Period  Indicates If it's 1 day or 2 hours.<br>
Gender:             Indicates if Male or Female.<br>
Age:                <br>
Marital Status:     <br>
Has Children:       <br>
Education Level:    <br>
Occupation Type:    <br>
Car:                <br>
Bar_Frequency:      <br>
CoffeeHouse:        <br>
CarryAway:          <br>
RestaurantLessThan20:<br>
Restaurant20To50     <br>
Coupon_GEQ5min:     <br>
Coupon_GEQ15min:    <br>
Coupon_GEQ25min:    <br>
Direction_Same:     <br>
Direction_opp:      <br>
Coupon_Acceptance:  <br>
time_24h:           <br>
Income lower bound: <br>
Income upper bound: <br>


**HOW DO I GET THE LINK TO GO DIRECTLY TO THE IPYNB FILE?**

**Website:**
[Assignment 5.1 work product](https://github.com/BrianJohnson100/ML_AI_Class/blob/main/coupon_analysis_10_14_2025.ipynb?short_path=ef19478)


**Getting Started (Using this Repository)**

***1.  Clone the repo***
```bash
git clone https://github.com/BrianJohnson100/ML_AI_Class
cd  ML_AI_Class
```

***2.  (Optional) Create a virtual environment***
```bash
python -m venv .venv
source .venv/bin/activate   # On Mac/Linux
.venv/Scripts/activate      # On Windows
```

***3. Install dependencies***
```bash
pip install -r requirements.txt
```

***4. Launch Jupyter Notebook***
```bash
jupyter notebook
```
This opens a web page in the browser where you can then navigate into your notebooks/ folder and click on a notebook e.g. coupon_analysis_10_14_2025.ipynb.