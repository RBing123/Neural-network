# Neural-network
Activation Function:
Sigmoid:
	Mathematical expression:f(z)=1/(1+e^z)
	The sigmoid function is a nonlinear function used in regression model.
	![image](https://user-images.githubusercontent.com/107789113/197200789-25dad962-fc4d-4548-9496-62561ed99176.png)
	Sigmoid function converts its input into a probability between 0 and 1.
	This function isn't used in hidden layers of a CNN. Since it gives a low gradient for values greater than 3 and less than -3, the network fails to learn and perform.
	(Vanishing gradient problem)
Tanh:
	Mathematical expression:f(x)=a=tanh(z)=(e^x-e^(-x))/(e^x+e^(-x))
	The tanh function is suited for the classification of two different classes.
	![image](https://user-images.githubusercontent.com/107789113/197201986-c1d291d5-117a-4885-b51f-15ee66d39b17.png)
	Its range falls between -1 and 1, and it has fast optimization speed.
ReLU:
	Mathematical expression:f(z)=max(0.0, z)
	ReLU is an alternative to both sigmoid and tanh activation functions, is one of the most widely activated in convolutional neural networks and deep learning. It doesn’t have a vanishing gradient problem unlike sigmoid and tanh.
	![image](https://user-images.githubusercontent.com/107789113/197202543-e1369e19-3054-40d9-8fc5-fd3fed41f0f4.png)
	ReLU function performs faster calculations because it doesn't use exponential.
Softmax:
	Mathmatical expression:f(z)=(e^(z_i))/(sigma(e^(z_i)))
	Softmax is a nonlinear function and it used to handle mulitiple classes.
	![image](https://user-images.githubusercontent.com/107789113/197203298-8f775939-ac6f-41ba-8e29-505ac4f59f92.png)
	It adjusts its output for each class between 0 and 1, then divides them by their sum to determine the likelihood of the input value falling into a specific category of classes.
	
## Tip
![image](https://user-images.githubusercontent.com/107789113/197203839-f19bc72d-d669-4bdf-8a93-6a994c708cd1.png)
