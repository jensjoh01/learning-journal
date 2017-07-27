# Learning Journal Code 201

### Day 11 - Monday July 24
Covered CSS for the wireframe project. It was a good review, can always use some CSS practice. Lab for the day was starting bus mall; an application that displays three pictures and tracks which picture the user clicks on.  I was able to complete it but with very messy, wet (with extra text; opposite of dry; just made that up..) code.

I used a new function to track which image was clicked...there has to be a better way...

### Day 12 - Tuesday July 25
* review code
* make my bus mall dry
* use chartjs to make bar chart

### Day 13 - Wednesday July 26
* Learned indexof and includes for handling arrays
* talked about persistence
* local storage w/ JSON

  Working with local storage:
  variable -> stringify it -> store it

To get it:
getItem('key') -> parse it -> assign it where you want it.

When working with object arrays like Image.all, you need to parse using 'key' or else the '.' in name will screw it up:

JSON.parse(localStorage.getItem('key')) instead of first getting it and then JSON.parse(<name>)
