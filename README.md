# daily-javascript-q103

You need to create a form with the following requirements: 

* The employee name is pre-populated with "John Doe". 
* The password text needs to be obscured with dots (or stars). 
* The user can enter more than one email address in the email field. 

Which form should you use?
<hr/>
Choose the correct answer

Option 1:
```html
<form method="post" enctype="application/x-www-form-urlencoded">
     <div>
          <label for="name">Employee name:</label>
          <input type="text" id="name" name="employeeName" placeholder="John Doe">
     </div>
     <div>
          <label for="employeePassword">Password:</label>
          <input type="password" id="employeePassword" name="employeePassword">
     </div>
     <div>
          <label for="employeeEmail">Email address:</label>
          <input type="email" id="employeeEmail" name="employeeEmail">
     </div>
     <div>
          <input type="submit" value="Submit">
     </div>
</form>
```
Option 2:
```html
<form method="post" enctype="application/x-www-form-urlencoded">
     <div>
          <label for="name">Employee name:</label>
          <input type="text" id="name" name="employeeName" value="John Doe">
     </div>
     <div>
          <label for="employeePassword">Password:</label>
          <input type="password" id="employeePassword" name="employeePassword">
     </div>
     <div>
          <label for="employeeEmail">Email address:</label>
          <input type="email" id="employeeEmail" name="employeeEmail" multiple>
     </div>
     <div>
          <input type="submit" value="Submit">
     </div>
</form>
```
Option 3:
```html
<form method="post" enctype="application/x-www-form-urlencoded">
     <div>
          <label for="name">Employee name:</label>
          <input type="text" id="name" name="employeeName" value="John Doe">
     </div>
     <div>
          <label for="employeePassword">Password:</label>
          <input type="text" id="password" name="password">
     </div>
     <div>
          <label for="employeeEmail">Email address:</label>
          <input type="email" id="employeeEmail" name="employeeEmail">
     </div>
     <div>
          <input type="submit" value="Submit">
     </div>
</form>
```
Option 4:
```html
<form method="post" enctype="application/x-www-form-urlencoded">
     <div>
<label for="name">Employee name:</label>
          <input type="text" id="name" name="employeeName" placeholder="John Doe">
     </div>
     <div>
          <label for="employeePassword">Password:</label>
          <input type="password" id="employeePassword" name="employeePassword">
     </div>
     <div>
          <label for="employeeEmail">Email address:</label>
          <input type="text" id="employeeEmail" name="employeeEmail" multiple>
     </div>
     <div>
          <input type="submit" value="Submit">
     </div>
</form>
```
