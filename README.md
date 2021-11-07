## Client did not pay?


Add opacity to the Class "sidebar-nav" and decrease it every day until their menu completely fades away. Set a due date and customize the number of days you offer them until the menu is fully vanished.

Once the menu has vanished a ```window.alert``` pop up box will appear that you can put a custom message in. Where the menu once was the message "Disabled. Please speak to site owner" will appear.


```javascript
/* change these variables as you wish YYYY-MM-DD */
var due_date = new Date('2017-02-27');
var days_deadline = 60;
/* stop changing here */
```

```javascript
/* Edit the message in between the "" *\
document.getElementById("sidebar-wrapper").innerHTML="Disabled. Please speak to site owner";
```

## Usage
Just load the not-paid.js file in ```<head>```
