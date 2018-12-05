# Minimizing Food wastage in Mess using Machine Learning

The project is divided into several parts.

## An android application:
- This will help to know how many students will be coming for a meal of the day. 
- By default, we assume that, if a student doesn't mark himself present, he won't be coming for the meal.
- The student marks himself atleast 3 hours before the meal. 
- This will help estimate the quantity of food prepared to some extent.
- This will be demonstrated during presentation on 9th December.

## Detecting food wastage:
- A camera near the dumping area will recognize the plates, and estimate what quantity of a particular food item is wasted.
- Also, the face of the person dumping will be detected to estimate the quantity of wastage done by each person individually.
- The data for wastage will be collected for atleast 2 week for our model to recognize some patterns in the wastage data.
- We will take some data for plates with food leftover, and demonstrate the quantity predicted by our model for the items in the plate. Along with it, the face recognization system will be demonstrated. 

## Estimating quantity of raw materials:
- Linear regression will be used to estimate the quantity of raw materials to be required.
- This will be demonstrated, for eg. for a particular meal of a particular day. 
- The training data will include the raw material used, the no. of students that came to eat and the amount of each food item wasted.
- Once the model is trained, we will have the prediction data as the projected quantity of raw materials required, the projected no. of students attending the meal and as an output, we will get the amount of food item that will be wasted. 
- So, the raw material usage will be minimized so as to waste the least quantity of food. A threshold will be kept on the amount of wastage, because if more students come for this meal in the next week, we have sufficient raw material. That is, we will predict the raw material in order to make some threshold amount of food wastage.

### Project work was divided as follows:
- Android application made by Pratik Parmar.
- Food wastage detection done by Kunal Parihar.
- Raw material quantity estimation done by Vaibhav Vashisht and Sahil.
