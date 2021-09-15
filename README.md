# Workstation-Price-Prediction

**This is part of MachineHack.com Hackthon**


### **Overview**

The new covid-era has provided a new way of living the work-life balance. We have seen a lot of different websites providing packages to work from different locations. From Kashmir to Kanyakumari, from Gujarat to Assam we have collected packages in and around India. It becomes really difficult to find the best place with all the amenities such as high-speed internet, a comfortable stay as well as within the budget. To solve the real-world problem of finding the best deals for a calm and enjoying workation trip. Workation is the best way to work at a remote location with a recreational and rejuvenating vacation for the team.

In this competition, one has to use the knowledge of machine learning, deep learning, and model building **to predict the price per person for your next workstation trip**. The data has more than 18000+ rows of different packages with the details like start location, hotel type, cost per person, destination, Itinerary, and many more.


#### **Attributes:**

- **Uniq Id** - Unique Identifier per row sample
- **Package Name** - Name of the tour package
- **Package Type** - Type of the tour package
- **Destination** - A destination place
- **Itinerary** - complete itinerary
- **Places Covered** - covered places in the itinerary
- **Travel Date** - Date of travel
- **Hotel Details** - Details of the hotel stay
- **Start City** - Start place for the travel
- **Airline** - Flight details
- **Flight Stops** - Intermediate stops if any
- **Meals** - Inflight meals or services
- **Sightseeing Places Covered** - Itinerary details regarding sightseeing
- **Cancellation Rules** - Cancellation policy as per travel company


- **Per Person Price** - Price of the tour package per person **(Target Column)**

##### Skills:
- Advanced Regression Modeling
- Feature Engineering, Ensemble Modeling
- Optimizing RMSLE(Root Mean Squared Log Error) as a metric to generalize well on unseen data


### Evaluation

  + using the **RMSLE metric**. 
      - use **np.sqrt(mean_squared_log_error(actual, predicted))**
