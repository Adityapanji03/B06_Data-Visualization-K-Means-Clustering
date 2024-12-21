# B06_Data-Visualization-K-Means-Clustering

Before you run the program, you must download the dataset from Kaggle with this link https://www.kaggle.com/datasets/ermila/klasifikasi-tingkat-kemiskinan-di-indonesia
Then, you put the dataset to google drive or place to one of your file folder and change the program by removing:
from google.colab import drive
drive.mount('/content/gdrive')

And change data = pd.read_csv('gdrive/My Drive/Klasifikasi Tingkat Kemiskinan di Indonesia.csv', sep=';') into:
data = pd.read_csv('Klasifikasi Tingkat Kemiskinan di Indonesia.csv', sep = ';')

And enjoy for run the program code
