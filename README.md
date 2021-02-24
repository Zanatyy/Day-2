# Reflection
# Day 1's Reflection
I met my team and our instructor, looking forward to learn from this training enough to make me begin path to learn ML and continue my career shift. Dr Taniya is such a great person and a high achiever. I felt this is the right place to start learning when I saw everybody from everywhere are gathered for the same goal I want. I also like to get to know my team better.
# Day 2's Reflection
Well I was kinda confused at first but I managed to pick up many things and learned a lot from the attached links and tutorials so everything is gucci.
# Day 2's Q&As
Q. What is the difference between supervised and unsupervised learning?
A. In supervised ML the machine is trained on predefined set of datasets to be trained and be able to reach a conclusion when the machine is given new data. In unsupervised ML well you just have a pile of data without previous training or predefined datasets and the machine is set to find or discover patterns between data.

Q. Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries.
A. The statement is completely false since Scikit-Learn is built on these libraries and it uses NumPy, SciPy, Matplotlib, IPython, Sympy and Pandas.

# Day 3's Q&As
Q. What are “Tensors” and what are they used for in Machine Learning?
A. In mathematics, Tensors are algebraic objects that describes relationship between objects and vector space. In TensorFlow, Tensors are multi-dimensional arrays (like vectors or matrices) and it's the way the data is being handled by the machine. It's used in Machine Learning because It makes sense to be encoded as a tensor.

Q. What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?
A. In order to get our calculations from the machine we start a session for the graph to get an unassigned variable which is only valid within the session and when the session closed this variable will be unaccessable like placeholders.

# Day 9's Q&As
Q. How do you think Machine Learning or AI concepts were utilized in the design of this game?

A. Concepts were represented as simple as possible. Collecting data is an important process and A machine needs more and more data to be collected as much as possible. The game explained that if the data wasn't enough and didn't contain enough samples on a specific aspect like it was shown on the game, this will create a problem called machine bias. Machine bias happens as a result of a lack of cognitive assessment of data. Even when I was as objective as possible the machine found a pattern in the data due connected to human interactions which resulted in this issue.

Another explanation I found interesting for this problem: "Overfitting would be like training your dog raise his paw when you hold out your hand, and he learns the trick perfectly, but he only does it when it's *you* holding out *your* hand, and only your right hand because that's all he's been trained on. He won't do it for anyone else, and he won't do it when you raise your left hand. So his "model" of the trick works perfectly, but because there hasn't been enough variation in the training activity, or because of the way that the training was done (or perhaps just because of the way the dog's brain works), his trick doesn't generalize correctly to other stimuli that was intended to yield the same result."-u/RWYAEV from Reddit r/artificial.

Q. Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.

A. Let's talk about something I loved since I was three years old, Video Games, Especially Online/Multiplayer. Every game developer is having hard time trying to solve problems regarding griefing or trolling. What most developers do is collecting manual banned accounts data on their gameplay that led to being reported and what the observer -who has the authority to ban the account- was thinking of and his decision. The problem with this approach: 

-It's not accurate since in some complex games people have different approach on how the play the game and sometimes when the machine thinks that this griefing pattern applies to someone who is just playing the game differently can lead to a ban.

-No enough data. A machine needs a lot of data to analyse and train/test. Manual bans are not enough since observers can't ban too many people in just short amount of time.

Why is this problem important? In the last 10 years Esports have experienced a large amount of growth and in US alone esports' profits reached $950M and what keeps these games alive is a health game that has a good system that is actively tries to put players on a healthy game without trollers/griefers. Also it's expected to reach $1.1B so it's a lot of money at stake.

# Day 10's Q&As
Convolutional Neural Network is a class of deep neural networks used and specializied in analyzing visuals and images. CNN consists of two main parts: -Pooling mechanism that divides images into features and analyze them. -Fully connected neural network that predicts the right label for the image after getting the output of the pooling/convolution layer.

A Fully Connected Neural Network is a classic neural network architecture which all the nodes, or neurons, in one layer are connected to the neurons in the next layer.

CNN architecture types of layers are:

-Convolutional layer which is a filter that scans small number of pixels, then creates a feature map which helps to predict the class of each feature.

-Pooling layer. Its function is to reduce the amount of output data of the convolutional layer to reduce the amount of parameters and computation in the network.

-Fully connected input layer which takes the output of the pooling layer and turns it into a single vector (Flattening).

-Fully connected output layer provides the final predictions for every label.

# Day 16 Q&As
ReLU or Rectified Linear Activation Function is a simple function that outputs directly if the input is positive, otherwise, it returns zero. It has become the most common activation function for many types of networks and It's definitely the most used function for hidden layers in networks for several reasons:
 
-Efficiency: Faster to compute than Sigmoid Function and its derivative is faster to compute.

-Simple to use.

-Overcomes the vanishing gradient problem, allowing models to learn faster and perform better.

However, the only problem with the output is when x= the point which the function is bent because the derivative here is not defined. The solution here is to simply define the bent point's derivative with 0 or 1, So it's not a big problem.
