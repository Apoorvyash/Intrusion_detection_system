# Enhanced Intrusion detection system using Machine learning techniques
I have developed this model during my internship under University of Galway,Ireland under the supervision of senior researchers of the Institute.
# Abstract
The threat of unwanted actions like invasions and
cyber attacks has grown in importance as the reliance on com-
puter networks for crucial functions increases. The identification
and prevention of such assaults depend heavily on intrusion
detection systems (IDS). Due to the complexity and diversity
of threats, traditional IDS methods frequently have significant
false positive and false negative rates. Hence, to improve the
precision and efficacy of IDS, new machine learning approaches
are required.
In this study, we provide an improved intrusion detection
strategy that makes use of outlier identification with Isolation
Forest and Edited Nearest Neighbor (ENN). Isolation Forest is
an ensemble-based approach for detecting anomalies that can
isolate outliers into their own trees in order to find them in
a dataset.By reducing noisy and redundant data points, ENN
is a technique used to clean and refine the dataset.Along with
RobustScaler that is an efficient tool for normalization.
We use a Convolutional Neural Network (CNN) coupled with
an LSTM architecture as the classification model following
dataset refinement. The CNN-LSTM model can extract both spa-
tial and temporal information from network traffic data, allowing
it to recognise the complex multiclass attack patterns. The CNN-
LSTM model is trained for multiclass intrusion detection using
the revised dataset. Using the UNSW-NB15 dataset, we assess
our suggested strategy and compare it to other cutting-edge
intrusion detection techniques. Experimental findings show that
our system detects multiclass incursions accurately while limiting
false positives and false negatives. It also achieves much higher
accuracy, precision, recall, and F1-score than older methods.
Additionally, our method demonstrates robustness in managing
a range of assault situations. Further research can be conducted
to investigate the scalability, generalizability, and applicability of
our approach to other real-world network security datasets
# Results
![WhatsApp Image 2023-04-14 at 18 48 36](https://user-images.githubusercontent.com/96018168/234259923-efdd6b93-1693-4be9-8c13-09e9056b0541.jpeg)

