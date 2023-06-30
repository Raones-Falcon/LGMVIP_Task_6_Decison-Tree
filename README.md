# LGMVIP_Task_6_Decison-Tree
Prediction using Decision Tree  Algorithm 
The project focuses on implementing and visualizing a Decision Tree algorithm for prediction. The example code provided utilizes the scikit-learn library in Python to create a Decision Tree classifier and visualize it graphically.

The project starts by loading the Iris dataset, which is commonly used for classification tasks. The dataset contains four features (sepal length, sepal width, petal length, and petal width) and three classes (setosa, versicolor, and virginica). The features and target variables are stored in the variables X and y, respectively.

A Decision Tree classifier is then created using the DecisionTreeClassifier class from scikit-learn. The classifier is trained on the dataset using the fit() method.

To visualize the Decision Tree, the code employs the tree.plot_tree() function, which generates a graphical representation of the tree. The feature names and class names are provided to label the tree nodes accurately. Additionally, the filled=True argument is used to color the tree nodes based on the majority class.

The visualization of the Decision Tree is saved as a PNG image using fig.savefig(). This image can be referenced and shared as a graphical representation of the trained Decision Tree model.
