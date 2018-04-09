<h1>Java API-Independent-Study</h1>
<p>Learning to make a game out of Java for the next 9 nine week, the first two week allow me to finish Codecademy lessons on the current Java course.</p>
<a href = "https://www.codecademy.com/learn/learn-java">Codecademy Java Course</a><br>


<h2>During the second week before spring break:</h2>

<h3>Conditionals and Control Flow</h3>
<p>The second week of Independent Study and currently will be able to finish up the Codecademy lessons on Java by the end of Spring Break. First, I completed my review on "Conditionals and Control Flow"</p>

<li><a href = "https://www.codecademy.com/courses/learn-java/lessons/conditionals-control-flow/exercises/decisions?action=resume_content_item">Conditionals and Control Flow</a><br></li>

<p>For the second week before Spring Break, I began to learn Conditionals and Control Flow on Wednesday and completed the lessons by late evening Friday. I learned how to control the flow of a program with different values.</p>


<ol>

<li>Boolean Operators <b>&& / || / !</b> Precedence - Allows for boolean operators to be used coincide with other larger form of the expression. A summary of this below.</li>

<p>&& - Is an <b>and</b> operator returning true if both value are the same. Allow a set of code to be equal (below) to print out as true.</p> 

``System.out.println(true && true); // prints true``

<p> Another set of line with false to print (below) print out as false. </p>

``System.out.println(true && true); // print false``

<p>This line similar (below) to the second example will also print out as false.</p> 

``System.out.println(true && false) or (false && true); // print false``

<p>Expression used as (below) will print out as true. But it will be the opposite if not used correctly with <b>< or ></b>.</p>

``System.out.println(2 < 3 && 4 < 5);``

<p>|| - Is an <b>or</b> operator and returns the value as true if one other expression is the opposite is also 'true'. Allow a set of code to used "or" (below) to print out false.</p>

``System.out.println(false || false); // prints false``

<p>This lines of codes are opposite if using (below) to print out true.</p>

``System.out.println(false || true); // prints true / System.out.println(true || false); // prints true / System.out.println(true || true); // prints true``

<p>! - Is an <b>not</b> operator and returns the opposite expression by returning "true" as "false" and "false" as "true". Allow a set of code to used "not" within "System.out.println(!false); // prints true" to return as true.</p>

<p>This lines of codes is opposite if using "System.out.println(!true); // prints false" to return as false</p>

<p>Expression used (below) to print out as false. But it will be the opposite if not used correctly with "< or >".</p>

``System.out.println( !(4 <= 10) );``

<li>If-ElseIf-Else Statement - A summary of the if-elseif-else statements below.</li>

<p>If - If is a conditionals statements and is followed by a block of code with the expression as true and run forever. (Below) is an example of conditionals expression as it will return true for <b>Control flow rocks!</b> as printed in the console. If the line of code is not currently using <b>;</b>, it will use curly bracket <b>{}</b> to run the block of code as true.</p>

``if (9 > 2) {System.out.println("Control flow rocks!");}``

<p>If-Else - To activate a block of code, you can used <b>if/else</b> after <b>if</b> will return <b>true</b>. Anything else that is false equal to <b>if</b>, it will prints out the <b>else</b> statement (example below).</p>

``if (1 < 3 && 5 < 4) {System.out.println("I defy the Boolean laws!")} else {System.out.println("You can thank George Boole!");}``

<p>ElseIf -  If the statement is not true to the <b>if</b> statement, but it is equal to another statement, it should print out the <b>elsif</b> statement, but will print out <b>else</b> if non of the following statement is true (example below).</p>

``int shoeSize = 10; if (shoeSize > 12) { System.out.println("Sorry, your shoe size is currently not in stock.");} else if (shoeSize >= 6) {System.out.println("Your shoe size is in stock!");} else { System.out.println("Sorry, this store does not carry shoes smaller than a size 6.");}``

<li>Ternary Conditional - Both statements of <b>if / else</b> statements can be long when returning the value of the boolean. Ternary conditionals statements is a latin term for <b>composed of three parts</b> as:</li>

``1) A Boolean expression``
``2) A single statement that gets executed if the Boolean expression is true``
``3) A single statement that gets executed if the Boolean expression is false``

<p>More example can be shown (below). the <b>int</b> can be called to equal to the number 21 or greater than 20. Whatever value is can be printed in a console if the current state is true.</p>

``int pointsScored = 21; char gameResult = (pointsScored > 20) ? 'W' : 'L'; System.out.println(gameResult);``

<li>Switch Statement - A way to activate a code block is providing an equal block specific variable as the switch statement. It is organizable and can contain less word (below).</li>

``int restaurantRating = 3; switch (restaurantRating) { case 1: System.out.println("This restaurant is not my favorite."); break; case 2: System.out.println("This restaurant is good."); break; case 3: System.out.println("This restaurant is fantastic!"); break; default: System.out.println("I've never dined at this restaurant."); break; }``

<p><b>int</b>is used the variable <b>restaurantRating</b> as the value of 3, then can be printed on console by the variable values. If that variable number is equal between 1-3, it should return one of the following <b>case 1-3</b>, but if the number is not equal to the variable, then it should return the <b>default</b> statement.</p>


<li>Generalizations - The summary of the recent lessons on Conditionals and Control Flow:</li>

<p>Boolean Operator - <b>&& / || / !</b> are used to create a boolean expressions with a defined order.</p>

<p>Statements - <b>if / if/else / if/elseif/else</b> are used to activate the conditional blocks of code.</p>

<p>Ternary Conditional - Used shortened version of the variable <b>if/else</b> to return to value of the expression</p>

<p>Switch - Allow the user to check for equality in the variable/expression with the value that is not needed by boolean</p>

</ol>


<h2>During the second week of Spring Break:</h2>

<h3>Object-Oriented Java</h3>
<p>For the first half of Spring Break, I began to learn Object-Oriented Java on Saturday and completed the lessons by Sunday afternoon.</p>

<li><a href = "https://www.codecademy.com/courses/learn-java/lessons/object-oriented-programming/exercises/object-oriented-overview?action=resume_content_item">Object-Oriented Java</a><br></li>

<p>For the second week before Spring Break, I began to learn Object-Oriented Java on Saturday and completed the lessons by Sunday afternoon. I learned how to create the class with the void and attempt to learn about "public" variable.</p>


<ol>

<li>Classes: Syntax - The class sets how the data is structured and behaved by its instructions. It can be used to create a pre-defined class, but the freedom to create a personal custom class (example below).</li>

``class Dog { }``

<li>Classes:Constructors - The class constructor allows to create the <b>variable</b> instances. The class constructor can receive information about the <b>variable</b>. Java does provide a pre-intial information for the constructor (example below).</li>

``class Car { //The class constructor for the Car class public Car() {}}``

<li>Classes:Instance Variable - The <b>variable</b> class is used to describe the details on what is needed to be associated with (example below). Instance variable is represented as <b>int</b> data type</li>

``class Car { //Using instance variables to model our Car class after a real-life car int modelYear; public Car() {}}``

<li>Classes: Constructor Parameter - Parameter allows for a different variable to be used inside the variable method that is being called from. So parameter would allow data types to create the specific attributes needed (example below). The <b>int variable</b> would be equal to the specific value of the constructor.</li>

``class Car { //Use instance variables to model our Car class after a real-life car int modelYear; public Car(int year) {modelYear = year;}}``

<li>Main Method - Main is used when Java is running in the program and the code of the current <b>main</b> method is executed.</li>

<li>Object - The object is the instance of the current class. Which is currently known as the <b>object</b> within Java (example below). The variable looks for the <b>int</b> parameter.</li>

``class Car { int modelYear; public Car(int year) { modelYear = year; } public static void main(String[] args){ Car myFastCar = new Car(2007);}}``

<li>Methods 1/2 - The method allows the instruction to be pre-defined set. It is declared within the class variable.  It can be provided by Java pre-defined methods of all classes, but we can create our own methods (example below). <b>Void</b> is the keyword that shows no value being returned to the method after the methods are executed. You can specify the location where the data is returning to the return type. The term <b>void</b> is "completely empty" and no values are returned to the method that is being called from. You can also use <b>int and char, etc.</b> to specify the method return value type (example below).</li>

``class Car { int modelYear; public Car(int year) { modelYear = year;} //Our new method to help us get "started" public void startEngine() { System.out.println("Vroom!"); } public static void main(String[] args){ Car myFastCar = new Car(2007); }}``

``class Car { int modelYear; public Car(int year) { modelYear = year; } public void startEngine() { System.out.println("Vroom!"); } public void drive(int distanceInMiles) { System.out.println("Your car drove " + distanceInMiles + " miles!"); } public int numberOfTires() { return 4; } public static void main(String[] args){ Car myFastCar = new Car(2007) myFastCar.startEngine(); myFastCar.drive(1628); int tires = myFastCar.numberOfTires(); System.out.println(tires); }}``

<li>Inheritance - To recycle a programme concept and can be maintained efficiently is called <b>inheritance</b>. It can be shared and used or can inherit the behavior of another class (example below).</li>

``class Car extends Vehicle { int modelYear; public Car(int year) { modelYear = year; } //Other methods omitted for brevity... public static void main(String[] args){ Car myFastCar = new Car(2007) myFastCar.checkBatteryStatus(); }}``

``class Vehicle { public void checkBatteryStatus() { System.out.println("The battery is fully charged and ready to go!"); }}``


<li>Generalizations - The summary of the recent lessons on Object-Oriented Java:</li>

<p>Class - The blueprint for data structure functionality.</p>

<p>Constructor - Instructs for the class to create the intial object state.</p>

<p>Object - The class instance that is storing the state.</p>

<p>Method - The instruction of the object that can be called from.</p>

<p>Parameter - The values that are specifically used to create the object or calling the method.</p>

<p>Return Value - Is the specific data type  that the method runs to and return to the data type.</p>

<p>Inheritance - One class funtion to define an another class.</p>

</ol>


<h3>Data Structures</h3>
<p>For the second half of Spring Break, I began to learn Data Structures on Wednesday and completed the lessons by Friday morning.</p>

<li><a href = "https://www.codecademy.com/courses/learn-java/lessons/data-structures/exercises/data-structures?action=resume_content_item">Data Structures</a><br></li>

<p>For the second week before Spring Break, I began to learn Object-Oriented Java on Wednesday and completed the lessons by Friday morning. I learned how to create the iterate over Hash Map while collecting the Array List.</p>


<ol>

<li>For Loop - The For Loop is repeatly run through the block of code with specific condition (example shown). Intializzation is the variable of <b>int</b> as the <b>counter</b> to intialize the value of the 0 before the loop can be run. To test conditionals of the boolean <b>counter < 5</b> to evaluate the code when the control statement is run the code statement after running every loop. It can be return as <b>true</b> to let the code block run or <b>false</b> to stop the loop from running. The <b>increment of each loop is completed, the statement is run as the <b>counter</b> increase after each loop.</b></li>

``for (int counter = 0; counter < 5; counter++) { System.out.println("The counter value is: " + counter); }``

<li>Array List - IS a list of data for the specific type of data (example below). It is a pre-defined Java class that requires the Array List object.</li>

``ArrayList<Integer> quizGrades = new ArrayList<Integer>();``

<li>Array List Manipulation - To create something that can contain the variable use the following example (below).</li>

``ArrayList<Integer> quizGrades = new ArrayList<Integer>(); quizGrades.add(95); quizGrades.add(87); quizGrades.add(83);``

<li>Array List Access - It is an element index that can refer to the location of the Array list and in Java are a zero-indexed which mean it is at the position of 0 for the Array List (example below). the following example will print out the number 95 with the position at 0 in the Array List by accessing the <b>get</b> method</li>

``ArrayList<Integer> quizGrades = new ArrayList<Integer>(); quizGrades.add(95); quizGrades.add(87); quizGrades.add(73); System.out.println( quizGrades.get(0) );``

<li>Array List Insertion - In order to insert a new element, you can use a different version of the <b>get</b> method (example below).</li>

``ArrayList<Integer> quizGrades = new ArrayList<Integer>(); quizGrades.add(95); quizGrades.add(87); quizGrades.add(73); quizGrades.add(0, 100); System.out.println( quizGrades.get(0) );``

<li>Iterating Array List - We can attempt to retrieve the value, by accessing the specific index Array List (example below). The example initialize the <b>int</b> variable of 1 to set as 0. Then the test condition will run the code block. Finally, the increment increases as the code loops every time. The <b>size</b> method returns the <b>int</b> by how many total elements stored to the variable, as it goes through each element, it is called iteration.</li>

``for (int i = 0; i < quizGrades.size(); i++) { System.out.println( quizGrades.get(i) ); }``

<li>For Each loop - Java can require a shortcut for the amount of code written for the loop of each loop (example below). The colon <b>;</b> is read as "in" and the code is read that each integet element calls the grade within the variable, printing the grade out.</li>

``for (Integer grade : quizGrades){ System.out.println(grade); }``

<li>Hash Map - HashMap has the keys and values of each key.</li>

``HashMap<String, Integer> myFriends = new HashMap<String, Integer>();``

<li>Hash Map Manipulation - The (example below) shows adding the keys and values.</li>

``HashMap<String, Integer> myFriends = new HashMap<String, Integer>(); myFriends.put("Mark", 24); myFriends.put("Cassandra", 25); myFriends.put("Zenas", 21);``

<li>Hashmap Access - You use a specific key to access the Array List data.</li>

``HashMap<String, Integer> myFriends = new HashMap<String, Integer>(); myFriends.put("Mark", 24); myFriends.put("Cassandra", 25); myFriends.put("Zenas", 21); System.out.println( myFriends.get("Zenas") );``

<li>Iterating HashMap - To access the properties of the HashMap, you want to print out the contents variable (example below).</li>

``HashMap<String, Integer> myFriends = new HashMap<String, Integer>(); myFriends.put("Mark", 24); myFriends.put("Cassandra", 25); myFriends.put("Zenas", 21); System.out.println( myFriends.size() ); for (String name: myFriends.keySet()) { System.out.println(name + " is age: " + myFriends.get(name)); }``

<li>Generalizations - The summary of the recent lessons on Data Structures:</li>

<p>For Loops - Used repeated run of a block of code.</p>

<p>For Each Loops - The concise version of the loop.</p>

<p>Array List - The data that is stored.</p>

<p>Hash Map - The keys that are stored for associated values such as the dictionary.</p>

</ol>



<h2>Takeaway on java on Codeacademy</h2>
<p>The following takeaway is learning how to find the format for a game in Java as a foundation to start with. My partner Simeon, told me to watch a tutorial video on this and I am going to spend some time with the video. Adding on, we are planning to use Eclispe and I am going to need to review myself on the Eclispe function before starting out. What I had learned is learning how to make a shorter block of code using the switch method. I a still a bit confuse on Arrays and hashes but I can understand that hash grabs a specific keys and arrays is where data from the current block of code is stored inside a variable.</p>