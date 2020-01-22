## Practice Sheet (OOP Fundamentals)


1.	Consider we have two classes: A Box class and a Giftcard class.
2.	These classes will have an aggregation form of the association relationship.
3.	The Giftcard class should contain the names of the sender and receiver and a message which should be provided when an object is created.
4.	Define a getter function getMsg that will return the message provided in the giftcard.
5.	The Box class should store an ArrrayList of Giftcards with a maximum capacity or size.
6.	This list should start out as empty. 
7.	The Box class should also have:
I)	Three constructors including the default constructor which sets its height, weight and width to zero
II)	 second constructor takes the value for each property as parameter and sets the values.
III)	Third constructor sets all sides equal.
IV)	Each box can contain a certain number of giftcard within it to parcel.
V)	Define a setter and getter method for the number of giftcard a box can contain or the capacity of the box.
VI)	Include addGiftcard method to add a list of giftcards in the box.
VII)	When adding, check whether the box is already full means the length of the array is less than the capacity of the box.
VIII)	Add a method showGiftCards that prints the number of giftcards stored in the box.
8.	Create a separate class with main to create multiple objects of Giftcards and Boxes.

