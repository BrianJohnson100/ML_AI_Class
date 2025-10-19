
**UC Berkeley Extension - Professional Certificate in AI & Machine Learning Assignment 5.1**

**Assignment:** What factors contribute to a customer accepting the coupon?
Context My objective is to understand the factors that influence a drivers decision to accept a location-based mobile coupon while driving. I aim to explore how variables such as the type of business (e.g., restaurant, bar, coffee house), the presence of passengers (including minors), proximity to the business, weather conditions, and time of day affect coupon acceptance behavior. By analyzing these factorsL, I intend to develop a predictive model or framework that can determine the likelihood of a driver accepting a coupon once it is delivered to them.

**My goal:** in this project is to apply my understanding of visualizations and probability distributions to effectively distinguish between customers who accepted a driving coupon and those who did not. By analyzing patterns in the data, I aim to uncover meaningful insights that can help predict coupon acceptance behavior.*

**Data Dictionary**<br*
**Destination:**    			*Indicates where the person is traveling to (No Urgent Place, Work, or Home).*<br>
**Passenger:**      			*Indicates if passengers are Friends, Kid(S), or the driver is alone.*<br>
**Weather:**        			*The type of weather, Sunny, Rainy or Snowy.*<br>
**Temperature:**        		*Indicates the temperature degrees: (30, 55 or 80).*<br>
**Time:**               		*Indicates coupon was offered: (10:00AM/PM, 7:00AM, 2:00PM or 3:00PM.*<br>
**Coupon Type:**        		*Indicates the types of establishments Bar, Coffee House, Restaurant.*<br>
**Expiration Time Period**  	*Indicates if it's 1 day or 2 hours.*<br>
**Gender:**             		*Indicates if a person is Male or Female.*<br>
**Age:**                		*Indicates ages of below 21, 21, 26, 31, 36, 41, 46, and above 50.*<br>
**Marital Status:**     		*Indicates Unmarried, partner, Single, Divorced or Widowed.*<br>
**Has Children:**       		*Indicates if person has kids or not.*<br>
**Education Level:**    		*Indicates Some college - no degree, Bachelors, Associates, Graduate degree.*<br>
**Occupation Type:**    		*Indicates type of Occupation.*<br>
*Car:**                			*Indicates if person was in a car.*<br>
**Bar Frequency:**      		*Indicates if person goes to a bar.*<br>
**CoffeeHouse:**        		*Indicates if person goes to a coffeehouse.*<br>
**CarryAway:**          		*Indicates if person accepts take out food.*<br>
**Direction_Same:**     		*Indicates the direction traveled.*<br>
**Coupon_Acceptance:**  		*Indicates if person took a coupon.*<br>
**time_24h:**           		*Indicates the time frame the person was offered a coupon.*<br>
**Income lower bound:**			*Indicates the lower bound of the income braker.*<br>
**Income upper bound:** 		*Indicates the upper bound of the income braker.*<br>


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
This opens a web page in the browser where you can then navigate into your notebooks/ folder and click on a notebook. eg.,.Final_Version.ipynb.