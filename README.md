# SVM-Implementation-in-Python-From-Scratch
BUILD AN SVM CLASSIFIER FROM SCRATCH



            THIS PROJECT IS FOR (COGNITIVE APPLICATION) AI & ML WORKSHOP               




What is Support Vector Machine?

SVM ( Support Vector Machine) is a supervised machine learning algorithm. That’s why training data is available to train the model. SVM uses a classification algorithm to classify a two group problem. SVM focus on decision boundary and support vectors, which we will discuss in the next section.

How SVM Works?

Here, we have two points in two-dimensional space, we have two columns x1 and x2. And we have some observations such as red and green, which are already classified. This is linearly separable data.

![1](https://user-images.githubusercontent.com/60067836/131161026-b1bbf0e7-bbb7-44be-a1a7-4c5cc8fbbf54.jpg)

But, now how do we derive a line that separates these points. This means a separation or decision boundary is very important for us when we add new points.

So to classify new points, we need to create a boundary between two categories, and when in the future we will add new points and we want to classify them, then we know where they belong. Either in a Green Area or in Red Area.

So how can we separate these point?

One way is to draw a vertical line between two areas, so anything in the right is Red and anything in the left is Green. Something like that-

![2](https://user-images.githubusercontent.com/60067836/131161157-1459708b-dd68-4525-9a89-8ca0c94cbb28.jpg)

However, there is one more way, draw a horizontal line or diagonal line. You can create multiple diagonal lines, which achieve the similar results to separate our points into two classes.

But our main task is to find the optimal line or best decision boundary. And for this SVM is used. SVM finds the best decision boundary, which helps us to separate points into different spaces.

SVM finds the best or optimal line through the maximum margin, which means it has max distance and equidistance from both classes or spaces. The sum of these two classes has to be maximized in order to make this line as maximum margin.

![3](https://user-images.githubusercontent.com/60067836/131161243-d7a9699b-548f-45ba-b521-67a301375ae9.jpg)

These, two vectors are support vectors. In SVM, only support vectors are contributing. That’s why these points or vectors are known as support vectors. Due to support vectors, this algorithm is called a Support Vector Algorithm(SVM).

In the picture, the line in the middle is a maximum margin hyperplane or classifier. In a two-dimensional plane, it looks like a line, but in a multi-dimensional, it is a hyperplane. That’s how SVM works.
