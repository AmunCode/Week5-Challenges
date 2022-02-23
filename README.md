# Week5-Challenges

1. Let's create a class. I created one called 'Employee'.

![image](https://user-images.githubusercontent.com/55643060/155210653-3c965e54-b3cb-4ed3-bb1d-eb7e19141cfd.png)

This should feel familiar. The syntax in the first line is similar to function definitions. Make your own class, use capital case for the name of your class. 

2. Create 3 objects of your class. 

![image](https://user-images.githubusercontent.com/55643060/155213730-75565662-f052-47be-9671-7038f6bd61fc.png)

3. This point you should have 3 objects. Each is an instance of your class. What type are they? write code to print the type of each of your objects.
4. Write code that prints the types you have already encountered? Print out at least 4 different types.
5. OK, so your class isn't really doing much. Let's add some attributes.

![image](https://user-images.githubusercontent.com/55643060/155216858-4c0bf8a4-07b5-4f02-b1a0-ea4306505c11.png)

You should add at least 5 attributes to your class. Think of attributes as facts about each instance of the class you created. In my case, each employee has number, name, department, supervisor, and salary.

6. How would you go about printing these attributes? The same way you print variables. One slight difference is the ".", the format should look like this: `object name.attribute`. Write code that will print the first attribute of all the objects you created.
7. Change the value of the attributes for yout objects, `object name.attribute` = blah. Then print all the attributes for all of your objects. Notice how each objects attribute is indendent of other object's, they are all of the same class but different objects.

8. Add an attribute `magic_number` to your class. Set the `magic_number` value for each of th eobjects you created. 
9. Add all of your objects into a list. Then write code to print the `magic_number` of each item in your list. 
10. Write code that will print the average of the `magic_number` of all your objects. 
11. Ok so we've played around with attributes (specifically class attributes). Let's talk about class functions! Try to create a function in your class that will change one of your attributes. Stop when you are utterly flustered. I would like to see some of the failed attempts.
12. As you have realized, function in a class are a delicate business. So the first function you will need to know is constructor `__init__`. it is special and comes after declaring class attributes. 

    `def __init__(self):`
