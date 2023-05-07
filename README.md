Download Link: https://assignmentchef.com/product/solved-employee-java
<br>
Assignment 8 (Winter 2017)

Write the code to implement this class.  You MUST use the data and method names given as well as the types provided. You may implement the internal parts of the methods as you see fit.  A (-) indicates that the data or method type is private.  A (+) indicates that the data or method type is public.  Your methods must be instance methods.  The type indicates the return type, the parameter type or the data type, depending on where it occurs.  You must use the constructors with fewer parameters to code the constructors with more parameters.  We will work some of this in class.

<table>

 <tbody>

  <tr>

   <td colspan="2" width="638">Class: Employee </td>

  </tr>

  <tr>

   <td width="319">(-) surName : String (-) givenName : String (-) birthYear : int (-) birthMonth : int (-) birthDay : int (-) streetAddress : String (-) city : String (-) state : String (-) zipCode : String (-) phoneNumber : String (-) jobTitle : String (-) salary : double </td>

   <td width="319">Last name of employee First name of employee Year Month Day Address Ex: “123 My Street” City Ex: Seattle State Ex: WA Zip Code Ex: 98124 Phone number Ex: 2536575431 Name of position Ex: Supervisor Annual Pay  Ex: 75000.0 </td>

  </tr>

 </tbody>

</table>




Constructors

<table>

 <tbody>

  <tr>

   <td width="319">Employee(surName, givenName) Employee(surName, givenName, birthYear, birthMonth, birthDay) Employee(surName, givenName, birthYear, birthMonth, birthDay, salary)</td>

   <td width="319">Constructor Constructor  Constructor </td>

  </tr>

 </tbody>

</table>




Accessors (getters)

<table>

 <tbody>

  <tr>

   <td width="319">(+) getName( ) : String  (+) getSurName( ) : String (+) getGivenName( )  : String (+) getBirthDate( )  : String     (+) getStreetAddress( )  : String (+) getCity( )  : String (+) getState( ) : String (+) getZipCode( )  : String (+) getPhoneNumber( )  : String  (+) getJobTitle( )  : String (+) getSalary( )  : String    (+) toString( ) : String     (+) equals(otherEmployee) : boolean </td>

   <td width="319">Return the name formatted as “surname, given name” Return the surname Return the given name Return the birth date formatted as YYYY-MM-DD where the YYYY is the 4 digit year, the MM is the 2 digit month, and the DD is the 2 digit day.  You must pad with 0’s if needed and you must have the “-“’s . Return the street address Return the city Return the state Return the Zip code Return the phone number formatted as (xxx)-xxx-xxxx.  Where the x’s represent the digits Return the job title Return the salary formatted as $xxxxx.xx where the x’s represent the dollars and cents.  Cents must be two digits only and you must include the “$” sign. Returns the String containing: The surname, the given name, the address, and the phone number. Where the names are on one line, the address is on three lines (street, city , state and zip) , and the phone number is on one line. Returns true if the employee name (surname and given) and birthdate (year, month, and day)  are the same as the other Employee otherwise returns false </td>

  </tr>

 </tbody>

</table>










Mutators (setters)

<table>

 <tbody>

  <tr>

   <td width="319">(+) setSurName(String) (+) setGivenName(String) (+) setBirthYear(int) (+) setBirthMonth(int) (+) setBirthDay(int) (+) setStreetAddress(String) (+) setCity(String) (+) setState(String) (+) setZipCode(String) (+) setPhoneNumber(String) (+) setJobTitle(String) (+) setSalary( double) (+) raise(int) </td>

   <td width="319">Set or Replace the surname Set or Replace the given name Set or Replace the birth year Set or Replace the birth month Set or Replace the birth day Set or Replace the street address Set or Replace the city Set or Replace the state Set or Replace the Zip code Set or Replace the phone number Set or Replace the job title Set or Replace the salary Change the salary to reflect the raise as an increase of the given percent.  The percent is in integer form where 100 is 100 percent.</td>

  </tr>

 </tbody>

</table>





