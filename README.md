# goit-js-hw-01

Task 1. Ordering droids

Perform this task in the task-1.js file

The repair droids sales station is ready to run, all that remains is to write the software for the sales department.

Declare the makeTransaction function, which expects two parameters, the values ​​of which will be set when it is called: • quantity— the first parameter, a number containing the number of droids ordered • pricePerDroid — the second parameter, a number containing the cost of one droid

Add the function code so that it returns a string with a message about the purchase of repair droids: "You ordered <quantity> droids worth <totalPrice> credits!", where: • <quantity> — is the number of droids ordered • <totalPrice> — is the total cost of the order, i.e. the cost of all droids ordered

Take the code below and insert it after the declaration of your function to check that it works correctly. The results of its work will be displayed in the console.

console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000 credits!"
console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth 3000 credits!"
console.log(makeTransaction(10, 500)); // "You ordered 10 droids worth 5000 credits!"

Leave this code for the mentor to review.

What the mentor will look for when reviewing:

The declared function makeTransaction(quantity, pricePerDroid)
Calling makeTransaction(5, 3000) returns "You ordered 5 droids worth 15000 credits!"
Calling makeTransaction(3, 1000) returns "You ordered 3 droids worth 3000 credits!"
Calling makeTransaction(10, 500) returns "You ordered 10 droids worth 5000 credits!"
Output all call results to the console
Calling makeTransaction with any valid arguments returns the correct value

Task 2. Delivery of goods

Perform this task in the file task-2.js

Declare the function getShippingMessage, which expects three parameters, the values ​​of which will be set when it is called: • country — the first parameter, a string containing the country of delivery • price — the second parameter, a number containing the total cost of the goods • deliveryFee — the third parameter, a number containing the cost of delivering the goods

Add the function code so that it returns a string with a message about the delivery of the goods to the user's country: "Shipping to <country> will cost <totalPrice> credits", where: • <country> — is the country of delivery • <totalPrice> — is the total cost of the order, including the cost of the goods and their delivery

Take the code below and insert it after the declaration of your function to check the correctness of its operation. The results of its operation will be displayed in the console.

console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia will cost 170 credits"
console.log(getShippingMessage("Germany", 80, 20)); // "Shipping to Germany will cost 100 credits"
console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will cost 120 credits"



Leave this code for a mentor to review.



What the mentor will pay attention to when checking:

The function getShippingMessage(country, price, deliveryFee) is declared
The call getShippingMessage("Australia", 120, 50) returns "Shipping to Australia will cost 170 credits"
The call getShippingMessage("Germany", 80, 20) returns "Shipping to Germany will cost 100 credits"
The call getShippingMessage("Sweden", 100, 20) returns "Shipping to Sweden will cost 120 credits"
The call getShippingMessage with any valid arguments returns the correct value

Task 3. Element width

Perform this task in the file task-3.js

Declare the function getElementWidth, which expects three parameters, the values ​​of which will be set when it is called: • content— the first parameter, the width of the content • padding — the second parameter, the value of the horizontal padding for each side • border — the third parameter, the value of the border thickness for each side The values ​​of all parameters will be strings of the format Npx where N is an arbitrary integer or fractional number.

Complete the function code so that it returns a number — the total width of the element. When calculating the total width, be guided by the fact that the value of box-sizing is equal to border-box.

Take the code below and insert it after the declaration of your function to check the correctness of its operation. The results of its operation will be displayed in the console.

console.log(getElementWidth("50px", "8px", "4px")); // 74
console.log(getElementWidth("60px", "12px", "8.5px")); // 101
console.log(getElementWidth("200px", "0px", "0px")); // 200

Leave this code for verification by a mentor.

What the mentor will pay attention to when checking:

The function getElementWidth(content, padding, border) is declared
The call getElementWidth("50px", "8px", "4px") returns the number 74
The call getElementWidth("60px", "12px", "8.5px") returns the number 101
The call getElementWidth("200px", "0px", "0px") returns the number 200
The call getElementWidth with any valid arguments returns the correct value
