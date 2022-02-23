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
12. As you have realized, functions in a class are a delicate business. So the first function you will need to know is constructor `__init__`. it is special and comes after declaring class attributes. `def __init__(self):` creates a template of attributes each instance should have. In the image below I move the name attribute to the 'right' place after the init. Use my Employee class as a template and correct all of the attribute variables in your class. We'll revisit class attributes later on (when and why to use).  

![image](https://user-images.githubusercontent.com/55643060/155260535-d6ab205f-9155-426d-bd8d-c0b6e84a35e8.png)

13. Create a method(function) in your class called `print_all`. This method should print all of the attributes you have in a created object. I should be able to create an object and then call the `print_all` method.
14. Ok so you created a class without having to put any attributes upon creation of the instance. I now want you to modify your class to now require a `name` attribute when an instance is initiated. So creating an object using the sample Employee code would be `sales_person = Employee("Gina")`
15. Write code that will allow a user to input an number. Then use that number to in the creation of a new object so that an attribute of the new object has the user input. 
16. Make a class called `SKU` with the following attributes: part number, color, price, make, model, grade.
17. modifiy your code from #16 so that part number and make are required when a `SKU` object is created. 
18. Add all your SKU objects into a list (you should have at least 10 objects in your list). Write code to print the whole list.
19. Add a method to the SKU class called `print_stats`, this method shoud show print all the attributes of the object. 
20. Remember that list of 10 colors from week 4? Use that list to give each SKU object in your list a color. Meaning the color attribut for each object needs to be updated. I advise using a loop. The color given to any of the SKU should be a random selectiong from your color list (ask Junior)
