LEARN HTML
Wine Festival Schedule
The Aguillar Family is hosting their annual wine festival and they have asked you to build a web page for the event schedule! Use your knowledge of HTML to display a table to the attendees.

You can preview the final version at this link.

Let’s begin!

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Unstuck“ to see a project walkthrough video.

Tasks
10/10 Complete
Mark the tasks as complete by checking them off
1.
In index.html, inside of the <div> element that has the attribute class with a value of "container", create a new <table> element.


Stuck? Get a hint
2.
Inside of the <table> element, add a section for table headings using <thead>.

Then, add two rows inside of it using the table row element.


Stuck? Get a hint
3.
Inside the first table row element, from task 2, add a table heading element.

Inside of that, include an <h1> with the following text: Wine Festival Schedule.


Stuck? Get a hint
4.
Inside the second table row element, from task 2, add two <th>s:

In the first, add an <h2> that says Time.

In the second, add an <h2> that says Event.


Hint
<table>
  <thead>
    <tr>
      <th>
        <h1>Wine Festival Schedule</h1>
      </th>
    </tr>
    <tr>
      <th>
        <h2>Time</h2>
      </th>
      <th>
        <h2>Event</h2>
      </th>
    </tr>
  </thead>
</table>
5.
You may notice that “Wine Festival Schedule” does not stretch across the entire table. Let’s fix that!

In the opening <th> tag of this element, add colspan="2".


Hint
Like so:

<th colspan="2">
  <h1>Wine Festival Schedule</h1>
</th>
So now your code should look like:

<table>
  <thead>
    <tr>
      <th colspan="2">
        <h1>Wine Festival Schedule</h1>
      </th>
    </tr>
    <tr>
      <th>
        <h2>Time</h2>
      </th>
      <th>
        <h2>Event</h2>
      </th>
    </tr>
  </thead>
</table>
6.
Below the closing </thead> tag, section off the table using the table body element.


Hint
Long tables can be sectioned off using the table body element <tbody>.

<table>
  <thead>
    <tr>
      <th colspan="2">
        <h1>Wine Festival Schedule</h1>
      </th>
    </tr>
    <tr>
      <th>
        <h2>Time</h2>
      </th>
      <th>
        <h2>Event</h2>
      </th>
    </tr>
  </thead>
  <tbody>
    ...
  </tbody>
</table>
7.
Inside of the table body you created in the previous task, create 5 rows using the table row element.


Stuck? Get a hint
8.
Inside each row, create two cells using the table data element.

The first table data in each row should have the attribute class with the value "left".


Stuck? Get a hint
9.
Inside each of the 5 <td class="left"> elements, add <h3> elements that include the times of the events:

12:00 PM
01:00 PM
02:00 PM
03:00 PM
04:00 PM
Feel free to look back at the live site to compare.


Hint
By this point, your <tbody> should look like:

<tbody>
  <tr>
    <td class="left"><h3>12:00 PM</h3></td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"><h3>01:00 PM</h3></td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"><h3>02:00 PM</h3></td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"><h3>03:00 PM</h3></td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"><h3>04:00 PM</h3></td>
    <td> ... </td>
  </tr>
</tbody>
10.
Inside each of the <td> elements that does not have a class attribute with a value of "left", add <h3> elements that include the name of events:

Welcome Reception
Storytelling & Tasting
Wine Luncheon
Aguillar Family Wines
Wine & Cheese Tasting
You have created the events table. Cheers!


Hint
By this point, your <tbody> should look like:

<tbody>
  <tr>
    <td class="left"><h3>12:00 PM</h3></td>
    <td><h3>Welcome Reception</h3></td>
  </tr>
  <tr>
    <td class="left"><h3>01:00 PM</h3></td>
    <td><h3>Storytelling & Tasting</h3></td>
  </tr>
  <tr>
    <td class="left"><h3>02:00 PM</h3></td>
    <td><h3>Wine Luncheon</h3></td>
  </tr>
  <tr>
    <td class="left"><h3>03:00 PM</h3></td>
    <td><h3>Aguillar Family Wines</h3></td>
  </tr>
  <tr>
    <td class="left"><h3>04:00 PM</h3></td>
    <td><h3>Wine & Cheese Tasting</h3></td>
  </tr>
</tbody>
If you are feeling ambitious, try adding another column for the locations of events and one more row for the after-party!

YOUTUBE VIDEO
https://www.youtube.com/watch?v=BF2VlsM1UjA