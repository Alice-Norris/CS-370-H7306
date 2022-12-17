

# Development Reflection

## Work Done
All code except the training loop in the qtrain() function was provided, along with two \*.py files, one for the agent's experience and one for the game itself. I wrote the training loop in the qtrain function, which determines whether to act randomly or not, performs actions, stores memories, and trains the network on the observed reactions of the environment and game to its actions. Epsilon is decremented gradually upon winning, so that the network has a chance to use its experience.

# Computer Scientists in Machine Learning
   Computer scientists, in general, design, create, and analyze computer software and hardware in order to solve problems. In machine learning, this is done surprisngly abstractly. While an understanding of math certainly helps, machine learning is a much more intuitive pursuit. The design of new neural network architectures and structures is based more on concept than on granularly designing every aspect of the network. Once a design is completed, hyperparameters are finetuned instead of the neural network itself.
    
# Approach to Problem Solving in Computer Science and Machine Learning
   In order to solve a problem, it must be understood. This was generally easier in this particular field of computer science, since understanding the problem in terms of inputs, outputs, states, and actions is more intuitive than what is sometimes required in other fields, such as graphics. Decomposing a machine learning problem is more about breaking the problem to be solved down into details: If you're processing images, what is the optimal size for the purpose? If the network will learn to play a game, what are the states? What information does the network need? That informs the size of the input layer. When determining outputs, I think of the network itself as a mechanism that takes inputs, and what it is doing to those inputs. Then, it becomes easier to decided what size and shape the data coming out needs to be.
    
# Ethical Responsibilities in Computer Science and Machine Learning
   There are several responsibilities to end users and organizations for which computer science are done. Firstly, the software or hardware produced should work. Unless a customer has, for some reason, paid for a product they know will not work, every effort must be taken to ensure that it works. A computer scientist must also make sure the product works well. Failure to do so can result in real harm, injury, or loss to customers, the organization, and the scientist themselves. Perhaps most importantly in the field of machine learning, the function of the product and the way in which it achieves that function should be clear of biases and assumptions about end users. This runs the risk of excluding people from benefiting from your solution, or worse, being harmed by it.
