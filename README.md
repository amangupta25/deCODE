# Machine-Learning in Earthquakes prediction

## Objective:
Forecast the intensity, time and the, to be affected areas by observing the pre-Earthquake events data.

An earthquake is preceded by several pre-occurrence stages/phenomena:
These pre-stages include: 
- Abnormal ionic emissions
- Sudden variations in seismic shift velocities.
- Anomalies in electric and gravitational field
- Sudden groundwater level changes 

These pre-stages data can be treated as parameters into our prediction model.
Even though the efficiency of a model can’t be determined beforehand without analyzing the data, still we can fall to a few models:
### 1. Logistic Regression: 
The parameters most like interact in a non-linear fashion and in such a case logistic regression approach is the best classic way.Intensity prediction might be an issue with this model as even though it's a fast model to learn its mainly effective on binary classification problems. 
### 2. Linear Discriminant Analysis: 
As the project goes on, more and more are parameters are most likely to come into the picture. When we have more than two classes then the Linear Discriminant Analysis algorithm is the preferred linear classification technique.
The representation of LDA is pretty straightforward. It consists of the statistical properties of your data, calculated for each class. For a single input variable this includes:
- The mean value for each class.
- The variance calculated across all classes.