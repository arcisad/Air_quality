### Matching between the actual NO2 concentrations and sensor measurements.

Open the solution here please:

https://github.com/arcisad/Air_quality/blob/master/sensor_esimation.ipynb

Alternatively please open the link below if the notebook fails to open in GitHub.

https://nbviewer.jupyter.org/github/arcisad/Air_quality/blob/master/sensor_esimation.ipynb

This is a solution including a regression and a Kalman filtering method.

**RMSE** and **R-Squared** metrics are used for evaluation. **Dynamic Time Wrapping** is also another metric for evaluating the similarity between temporal sequences, which is not used.

Resluts are more in favour of regression comapred to Kalman filtering in this use case.

### Two-Sample t-test

this wasn't inferred from the question but if we could assume that the dataset is a subset of a larger dataset, then a t-test is useful to check if there is any meaningful differences between the actual sensor data and the new estimates. 

https://github.com/arcisad/Air_quality/blob/master/sensor_t_test.ipynb

Alternatively:

https://nbviewer.jupyter.org/github/arcisad/Air_quality/blob/master/sensor_t_test.ipynb

**Regression** showed to be the better estimate in this case.
