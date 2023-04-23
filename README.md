Download Link: https://assignmentchef.com/product/solved-airline-reservations
<br>



<h2></h2>

This program will allow the user to keep track of airline reservations. The program should display the seating chart for the airplane. It will use an * to indicate a seat is taken and the # to indicate the seat is available. The program will also display a menu which provides the user with several options. There will be two types of seats in the airplane: first class and coach, each of which will have a different cost. The program must make use of files, arrays and functions.

The airplane will have 5 rows in the first class section with 4 seats in each row, 2 on each side of the aisle and 10 rows in the coach section with 3 seats on each side of the aisle. The prices for all the first class seats will be the same. The first 5 rows of coach will be more expensive than the last 5 rows. The prices for the seats will be stored in a file called SeatPrices.txt  The program should read these values from the file and store the values in an array of doubles. This is an example of the seating chart:

<table>

 <tbody>

  <tr>

   <th></th>

   <th>1  2</th>

   <th>3  4</th>

  </tr>

  <tr>

   <td>Row 1</td>

   <td>#  #</td>

   <td>#  #</td>

  </tr>

  <tr>

   <td>Row 2</td>

   <td>#  #</td>

   <td>#  #</td>

  </tr>

  <tr>

   <td>Row 3</td>

   <td>#  #</td>

   <td>#  #</td>

  </tr>

  <tr>

   <td>Row 4</td>

   <td>#  #</td>

   <td>#  #</td>

  </tr>

  <tr>

   <td>Row 5</td>

   <td>#  #</td>

   <td>#  #</td>

  </tr>

  <tr>

   <th></th>

   <th>1  2  3</th>

   <th>4  5  6</th>

  </tr>

  <tr>

   <td>Row 6</td>

   <td>#  #  #</td>

   <td>#  #  #</td>

  </tr>

  <tr>

   <td>Row 7</td>

   <td>#  #  #</td>

   <td>#  #  #</td>

  </tr>

  <tr>

   <td></td>

   <td>Etc.</td>

   <td></td>

  </tr>

 </tbody>

</table>

The menu will provide choices to reserve a seat(s) and display the total number of seats sold (indicating first class and coach), the total number of seats empty in a row, the total number of seats empty in the plane (indicating first class and coach), and the total amount of sales (in dollars).

Validation: The seat requested by the user is a valid row and seat number. The program should also make sure the seat is not already taken.