# Fuzzy Cmeans

📁 README.md
🎯 Fuzzy C-Means Clustering from Scratch



🔷 Description
This project implements Fuzzy C-Means (FCM) clustering from scratch (without external libraries) on the Iris dataset, with detailed explanations and comparisons to K-Means clustering.


🧠 What is Fuzzy C-Means?
🔹 Traditional clustering (K-Means):
Each data point belongs strictly to one cluster.


🔹 Fuzzy C-Means:
Each data point has a degree of membership to each cluster. For example, a point can belong to:

Cluster 0: 80%

Cluster 1: 15%

Cluster 2: 5%

This is useful in problems where boundaries between clusters are not well-defined, such as medical diagnosis, image segmentation, or recommendation systems
 

Symbol	Meaning:

n	Number of data points

c	Number of clusters

u   Membership of data point i to cluster j

m	Fuzziness degree (>1)

cj   Cluster centroid j
 

Update membership matrix: inverse distance weighted

Update centroids: weighted average based on memberships


🔧 Installation

git clone https://github.com/YourUsername/fuzzy-c-means.git
cd fuzzy-c-means
pip install -r requirements.txt

📦 Requirements

numpy

pandas

matplotlib

seaborn

scikit-learn

(See requirements.txt)


💻 Usage

1-Run the script / notebook

python fuzzy_c_means.py
or 
open fuzzy_c_means.ipynb to view results step by step.

2-Outputs:

✔️ Fuzzy memberships of each point
✔️ Final centroids
✔️ Confusion Matrix
✔️ Performance metrics (Accuracy, Recall, Precision, F1)
✔️ PCA visualisation of clusters
✔️ Comparison with K-Means clustering

📊 Results
✅ Sample output (Iris dataset):


✅ Converged in 14 iterations

Accuracy: 88.00%
Recall: 87.33%
Precision: 87.50%
F1-Score: 87.41%
(Values vary due to random initialisation)

📈 Visualisations
🔹 Membership degrees for a data point

🔹 Clusters visualised using PCA

🔹 Confusion Matrix
| Predicted vs True classes |


🔄 Comparison with K-Means

Metric	    Fuzzy C-Means	       K-Means
Approach	Soft clustering	       Hard clustering
Accuracy	~88%	               ~90%

(Values vary per run. K-Means often gives slightly higher accuracy on Iris, but FCM provides membership insights.)

✏️ Author
Oussama El Azzouzi

🔗 GitHub
🔗 LinkedIn

