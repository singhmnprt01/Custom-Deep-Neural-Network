# Custom DNN - Build and Learn Customized Deep Neural Network
With customdnn the user can build his own neural networ by simply passing few neural network required/optional parameters. The user need not to have advance knoeldge of modern APIs like PyTorch, Tensorflow, Keras etc.

# Overview
The idea behind building this package is to learn and implement the mathematics behind neural network without using any single modern API, but matrices(NumPy). It has following key features:-
- It is simple to use as the user just needs to pass the x(feature dataset) and y(target variable) in a dataframe and rest will be taken care.
- If the user wants change the default network architecture and build a customized NN, you can pass upto 7 parameters from learninng rate to gradient descent algorithms (GDM,RMSprop,Adam).
- User can split the dataset by giving percentage of data to be test data, use it to predict and test his network's performance. (Area under the curve is current evaluation matrix)

# Using it
It is very handy and easy to use. User needs to install the package and all the classes of the package. User needs to separate the data into x and y (as dataframe) and can simply pass to split the data in to training amnd test data along with test percentage. 
Now, training function can ben called by passing training data along with custom variables to build the customized Deep Network.
Output will give suitable parameters (a discionary) and cost fucntion vs epoch graph.
This parameter dictionary can be used to predict on test data and check model's performce as well (AUC value).

# Limitations
Currently the package is limited to binomial classification problems, and doesn't support/solve  multinomial , image and regression problems. 

# Website 
Other details of the package and the paclage itself can be found at https://github.com/singhmnprt01/Custom-Deep-Neural-Network/tree/master/customdnn

# Defaults
The current default output activation function is sigmoid and inner layers' is ReLU.

# References & credits
I got the isnpiration from Andre NG's deeplearning.ai certification. It inspired me to build my own custom dnn library.

# License
GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU General Public License is a free, copyleft license for
software and other kinds of works.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
the GNU General Public License is intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.  We, the Free Software Foundation, use the
GNU General Public License for most of our software; it applies also to
any other work released this way by its authors.  You can apply it to
your programs, too.

  When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
them if you wish), that you receive source code or can get it if you
want it, that you can change the software or use pieces of it in new
free programs, and that you know you can do these things.

  To protect your rights, we need to prevent others from denying you
these rights or asking you to surrender the rights.  Therefore, you have
certain responsibilities if you distribute copies of the software, or if
you modify it: responsibilities to respect the freedom of others.

<customdnn>  Copyright (C) <2020>  <singhmnprt01@gmail.com>
