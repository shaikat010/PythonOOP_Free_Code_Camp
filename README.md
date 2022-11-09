# PythonOOP
The Original Code repository for my Python OOP Series











Points to be Noted:

Functions inside the classes are called methods,
Self: Python passess the object itself as the first argument in the method,








We can avoid hard coding the attributes and rather make sure that the attributes are being instantiated automatically with the __init__ or the other methods. 





__init__ → This is a special method with a unique name that does a very work for us. 
The collection of the methods starting with __ are called Magic Methods



The __init__ function is instantiated automatically when the instance is created for the first time.


We will see the term “ I AM CREATED” 2 times here because there are two instance of the Item class.



Here we are passing the name in the __init__ special method and then we are making the instance. We are printing the name that was passed when the instance was created as a parameter.
The interesting thing that we can do is that we can assign the attribute of the class from the __init__ method itself as shown below:







We can actually check if the attributes were set in the instances using the following code line.




Check for yourself with the above code of the quantity and the price of the object was actually set to it.
You can also put some type of default value for a parameter,



So below you can see that you no longer need to assign the parameters to the function anymore as the calculation can be done like this:





So far our code looks like this:


Sometimes it is important to be able to specify the type of data that the class init method should be taking, hence we do something like this:



