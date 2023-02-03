# Learn-and-Earn-basic-code
# It is a basic front-end website which is developed by using very basic HTML commands 
<!DOCTYPE html>
<head>
<title>My First Webpage</title>
<style>
    h1{
        text-align: center;
        background-color: bisque;
        font-style: oblique;
        font-size: 50px;
        color:rgb(0, 0, 0)
        text-decoration:underline;
        
    }
        
    body{
        background-color: bisque;
        font-size:20px;
        font-weight: 300;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        background-image: -moz-element(web image);
    }
    .labels{
        font-style: italic;
        color: black;
        font-weight: 400;
    }
   .firstlabels{
    font-weight: 400;
    font-style: italic;
    color: black;

    }
    .Gamesection{
        font-size:large;
        color: black;
        padding-left: 10px;
        padding-right: 10px;
        padding-top: 10px;
        padding-bottom: 10px;

    }
    .topnav{
        font-size:large;
        color: red;
        padding-left: 10px;
        padding-right: 10px;
        padding-top: 10px;
        padding-bottom: 10px;
        text-align:left;
        margin: left 40px;;
    

    }
    .topnav2{
        text-align:center;
        font-size:large;
        color: red;
        padding-left: 10px;
        padding-right: 10px;
        padding-top: 10px;
        padding-bottom: 10px;
        margin-left: 40px;
    }

</style>
</head>

<body>
    <h1 style="color:red"">Learn and Earn...</h1>
    <div class="topnav">
        <a class="active" href="#home">Home</a></div>
        <div class="topnav2"><a href="#news">News</a></div>
        
        <div class="topnav3"><a href="#contact">Contact</a></div>
        <div class="topnav4"><a href="#about">About</a></div>
      </div>
    <class id="firstlabels"><label for="first name">First Name:</label>
    <input type="text" id="first name" Name>
    </class>

    <br>
    <br>
   <class id="Labels"><label for="last name">Last Name:</label>
    <input type="text" id="last name" Name></class> 
    
    <br>


    <class id="Gamesection">
    <p>Please Select Your favourite Game:</p>
    <input type="checkbox" name>
    Football
    <br>
    <input type="checkbox" name>
    Cricket
    <br>
    <input type="checkbox" name>
    Kabaddi
    <br>
    <input type="checkbox" name>
    Basket Ball
    <br>
    <input type="checkbox" name>
    Chess
    <br>
   </class>
    <p>Enter Your Age:</p><input type="number" min="0" max="100">

    <br>
    <fieldset>
        <legend>
            Please Select The Course
        </legend>
        <select>
            <option value="Data Structures and Alogorithms:">Data Structures and Alogorithms</option>
            <option value="Web Development">Web Development</option>
            <option value="Devops">Devops</option>
            <option value="Artificial Learning">Artificial Learning</option>
            <option value="Machine Learning">Machine Learning</option>
        </select>
    </fieldset>
<p>Please Enter the Starting Date of Course:</p>
<input type="date" name="day">
<br>
<p>Please Enter DOB:</p>
<input type="date" name="day">
<br>

<p>Total Duration of Course:(in Days)</p>
<input type="number" name>
<br>
<p>Please Submit Your Feedback:</p>
<textarea rows="9" coloumns:"50"> </textarea>
<br>
<input type="Submit">

    
</body>
