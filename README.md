# Neural-network
Activation Function:
Sigmoid:
	Mathematical expression:f(z)=1/(1+e^z)
	The sigmoid function is a nonlinear function used in regression model.
	![image](https://user-images.githubusercontent.com/107789113/197200789-25dad962-fc4d-4548-9496-62561ed99176.png)
	Sigmoid function converts its input into a probability between 0 and 1.
	This function isn't used in hidden layers of a CNN. Since it gives a low gradient for values greater than 3 and less than -3, the network fails to learn and perform.
	(Vanishing gradient problem)
