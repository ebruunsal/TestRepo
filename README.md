# The User Interface Specification Document

## The Requirements
- A dynamic web page with a button to redirect to the new user add web page.
- A dynamic web page where new users can enter their information.
- A database where users' data is kept.

## UI Components and The Behavior of The Page When Using UI Components
- <kbd> + New User </kbd> button to redirect new users to the web page where they are added.
- - [X] *Hide Disabled User* checkbox to check the hide disabled user option.
- <kbd> Save User </kbd> button to write users information to database.
- A user interface to enter users' information:
  1. 4 textboxes one below the other where users' *Username , Display Name , Phone , Email* information will be entered.
  2. A dropdown button where we will select the users role:
  3. - [ ] *Enabled* checkbox.
    > - Username:     <kbd>      </kbd> 
    > - Display Name: <kbd>      </kbd> 
    > - Phone:        <kbd>      </kbd> 
    > - Email:        <kbd>      </kbd> 
    > - User Roles:   <details>
                      <summary>Select user roles...</summary>
                      <br>
                          Guess
                      <br>
                          Admin
                      <br>
                          SuperAdmin
                      </details>
    > -   - [X] *Enabled* 
 

## Database
- The user information entered in the new user screen is transferred to this designed database.
- A table with user information will be created.
- This table will contain *id, username, email, enabled* fields and these fields will be filled according to the data entered in the New User page.
- The primary key of this table will be ID field.
- UserTable

<table>
   <thead>
      <tr>
         <th>ID</th>
         <th>UserName</th>
         <th>Email</th>
         <th>Enabled</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>data1</td>
         <td>data2</td>
         <td>data3</td>
         <td>data4</td>
      </tr>
      <tr>
         <td>data11</td>
         <td>data12</td>
         <td>data13</td>
         <td>data14</td>
      </tr>
   </tbody>
</table>

   
   




 
