# Logistic-Regression-with-TensorFlow
This repo helps to know more about Logistic Regression and it executes with the help of TensorFlow Library <br><br><br>
<b>Tensorflow<b> is a large Open-source Software library by Google.
<br>It is used for numerical computation using data flow graphs.
<br>It helps in Faster Compilation and used in many ML and Deep neural network applications.
<br><br><br>
<b>Logistic regression<b> is one of the Supervised Learning Algorithm where it allows categorizing data into discrete classes by learning the relationship from a given set of labeled data.<br> It learns a linear relationship from the given dataset and then introduces a non-linearity in the form of the Sigmoid function. 
<br><br>
Now, We understand this logistic regression using "Iris Dataset"
<br> <b>Source<b> : https://archive.ics.uci.edu/dataset/53/iris
<br><br>
This dataset was introduced by British Statistician and Biologist Ronald Fisher, it consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). In total it has 150 records under five attributes - petal length, petal width, sepal length, sepal width and species.
<!DOCTYPE html>
<html>

<body>
    <h2>Attributes</h2>
    <ul>
        <li>Petal length</li>
        <li>Petal width</li>
        <li>Sepal length</li>
        <li>Sepal width</li>
    </ul>
    <h2>Variables</h2>
    <ol>
        <li>Independent Variable
            <ul>
                <li>Petal length</li>
                <li>Petal width</li>
                <li>Sepal length</li>
                <li>Sepal width</li>
            </ul>
        </li>
        <li>Dependent Variable
            <ul>
                <li>Species
                    <ul>
                        <li>Iris setosa</li>
                        <li>Iris virginica</li>
                        <li>Iris versicolor</li>
                    </ul>
                </li>
            </ul>
        </li>
    </ol>
</body>
</html>

<br><br>
<!DOCTYPE html>
<html>

<body>
    <h2>Logistic Regression Model</h2>
    <p>Logistic regression is typically thought of as a single equation:</p>
    <p><strong>ŷ = sigmoid(WX + b)</strong></p>
    <p>However, for the sake of clarity, we can have it broken into its three main components:</p>
    <ol>
        <li>A weight times features matrix multiplication operation
            <p><strong>WX</strong></p>
        </li>
        <li>A summation of the weighted features and a bias term
            <p><strong>WX + b</strong></p>
        </li>
        <li>Finally, the application of a sigmoid function
            <p><strong>sigmoid(WX + b)</strong></p>
        </li>
    </ol>

</body>
</html>
<br><br>
The plot below gives a visualization illustartion of sample parameters extracted from the iris dataset. 
![git1](https://github.com/Yuvasree9/Logistic-Regression-with-TensorFlow/assets/95610545/7efb82ec-b802-40b0-b4fa-7223cd94d94c)


