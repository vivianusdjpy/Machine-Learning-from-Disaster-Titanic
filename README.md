# Machine Learning From Disaster - Titanic
      Business Understanding
      
RMS Titanic was a British passenger liner operated by the White Star Line,
that sank in the North Atlantic Ocean in the early morning hours of April 15, 1912.
The Titanic struck an iceberg during her maiden voyage from Southampton to New York City. 
Of the estimated 2,224 passengers and crew aboard, more than 1,500 died, 
making the sinking one of modern history's deadliest peacetime commercial marine disasters. 

RMS Titanic was the largest ship afloat at the time she entered service and was the second 
of three Olympic-class ocean liners operated by the White Star Line. She was built by the Harland
and Wolff shipyard in Belfast. Thomas Andrews, chief naval architect of the shipyard at the time, 
died in the disaster.

Titanic was under the command of Capt. Edward Smith, who also went down with the ship.
The ocean liner carried some of the wealthiest people in the world, 
as well as hundreds of emigrants from Great Britain and Ireland,
Scandinavia and elsewhere throughout Europe, who were seeking a new life in the United States.

The first-class accommodation was designed to be the pinnacle of comfort and luxury, with a gymnasium,
swimming pool, libraries, high-class restaurants and opulent cabins.
A high-powered radiotelegraph transmitter was available for sending passenger "marconigrams" 
and for the ship's operational use.
Although Titanic had advanced safety features, such as watertight compartments and remotely activated 
watertight doors, it only carried enough lifeboats for 1,178 people—about half the number on board, 
and one third of her total capacity—due to outdated maritime safety regulations. 

After leaving Southampton on 10 April 1912, Titanic called at Cherbourg in France and Queenstown 
(now Cobh) in Ireland, before heading west to New York.

On 14 April, four days into the crossing and about 375 miles (600 km) south of Newfoundland, 
she hit an iceberg at 11:40 p.m. ship's time. 
The collision caused the hull plates to buckle inwards along her starboard (right) side and opened 
five of her sixteen watertight compartments to the sea; she could only survive four flooding. 
Meanwhile, passengers and some crew members were evacuated in lifeboats, many of which were launched only
partially loaded.

A disproportionate number of men were left aboard because of a "women and children first" protocol for 
loading lifeboats. At 2:20 a.m., she broke apart and foundered with well over one thousand people still aboard.
Specifying the Data Analytic Question
Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

    Defining the Metric for Success

1)We Identify the most importaint features for predicting the chances of survival.

2)The model achieves atleast 80% accuracy.

3)The Confusion Matrix has the lowest possible false positives and false neagtives.

    Data Understanding
    
    
VARIABLE DESCRIPTIONS

Pclass Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
survival Survival (0 = No; 1 = Yes)
name Name
sex Sex
age Age
sibsp Number of Siblings/Spouses Aboard
parch Number of Parents/Children Aboard
ticket Ticket Number
fare Passenger Fare (British pound)
cabin Cabin
embarked Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)


    Recording the Experimental Design

The project was undertaken using the following design Datasets(titanic.csv)

Exploratory Data Analysis

Data Cleaning

External Data Source Validation

Univariate Analysis

Bivariate Analysis

Multivariate Analysis

Modelling: KNN(K- Nearest Neighbor), Naive Bayes

Challenging the solution: Modelling using the first 5 principal Components
    
Follow up Questions

    Conclusion

Data Relevance

How accurate is the data at predicting whether a passenger survived or not?

Was the dataset sufficient?

Was the data biased?

Is the data source a reliable source?
