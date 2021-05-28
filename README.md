# Web attacks detection with machine learning
Machine learning algorithms applied on HTTP logs analysis to detect intrusions and suspicious activities.

## Usage
### Encode your http logs and save the result into a csv file
<code> $ python3 label-raw-data.py -l ./raw-http-logs-samples/access-2018-12-15.log -d ./labeled-data-samples/access-2018-12-15.csv</code>

### Train a model and test the prediction
<code> $ python3 logistic-regression-classifier.py -t ./labeled-data-samples/all.csv -v ./labeled-data-samples/access-2018-12-15.csv </code>

<br>
Details could be found here: 
<br>
http://enigmater.blogspot.fr/2017/03/intrusion-detection-based-on-supervised.html
