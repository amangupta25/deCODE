# Machine Learning for Earthquakes Prediction

## Objective:
Forecast the intensity, time and the, to be affected areas by observing the pre-Earthquake events data.

An earthquake is preceded by several pre-occurrence stages/phenomena:
These pre-stages include: 
- Abnormal ionic emissions
- Sudden variations in seismic shift velocities.
- Anomalies in electric and gravitational field
- Sudden groundwater level changes 

## Model Parameters
Various parameters which can be noticed with the increase in the intensity of earthquakes
- Hydrochemical precursors - Appreciable increase in concentration of dissolved minerals 2 to 8 days before an earthquake.
- Temperature Change - A considerable rise of temperature is usually observed before earthquakes
- Water Level - There are drastic changes in water level in several wells just before a major earthquake. 
- Radon Gas - Radon is a radioactive gas which is discharged from rock masses prior to earthquake. 
- Oil Wells - Large scale fluctuations of oil flow from oil wells prior to earthquakes were reported at many places
- Changes in Seismic Wave Velocity - Seismologists have found that this lead time began to decrease significantly for days, weeks and even months before the earthquake. 

## Prediction Models
These pre-stages data can be treated as parameters into our prediction model.
Even though the efficiency of a model can’t be determined beforehand without analyzing the data, still we can fall to a few models:
#### 1. Logistic Regression: 
The parameters most like interact in a non-linear fashion and in such a case logistic regression approach is the best classic way.Intensity prediction might be an issue with this model as even though it's a fast model to learn its mainly effective on binary classification problems. 
#### 2. Linear Discriminant Analysis: 
As the project goes on, more and more are parameters are most likely to come into the picture. When we have more than two classes then the Linear Discriminant Analysis algorithm is the preferred linear classification technique.
The representation of LDA is pretty straightforward. It consists of the statistical properties of your data, calculated for each class. For a single input variable this includes:
- The mean value for each class.
- The variance calculated across all classes.
#### 3. Artificial neural network
Backpropagation algorithm is widely suggested as the most efficient procedure in the training of neural networks. In this technique, in the forward pass, first of all, a specific value for connections between neurons is assigned. Afterward, in the backpropagation pass, the differences between predicted and measured values are calculated. Then, the error, which is calculated during forward pass, is backpropagated through the network to update the weights.

## Unusual Animal Behaviour
Studying earthquakes has inherent diffculties because of its infrequent and unpredictable nature. Reports indicate that animals have unusual behaviour prior to an earthquake. Some animals have a remarkable ability of sensing things that humans cannot. Animals can sense even small changes in the environment and this changes their behaviour which when studied can often lead to inferences and predictions about earthquakes. Studying animal behaviour can help us build better sensors to detect the earthquake signals. 
