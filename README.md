# Admission_Enquiry_Form
## Date:

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body>
    <h1 align="center">Admission Enquiry Form</h1>
    <form>
        <label><b>Full Name</b></label>
        <input type="text" placeholder="Enter your name here">
        <br>
        <br>

        <label><b>Email Address</b></label>
        <input type="email" placeholder="Enter your email here">
        <br>
        <br>

        <label><b>Mobile Number</b></label>
        <input type="number" placeholder="Enter your mobile number">
        <br>
        <br>

        <label><b>Gender</b></label>
        <input type="radio" name="gender">Male</input>
        <input type="radio" name="gender">Female</input>
        <br>
        <br>

        <label><b>Date of birth</b></label>
        <input type="date">
        <br>
        <br>

        <label><b>Departments interested</b></label>
        <select>
            <option selected="true">Select a deparment</option>
            <option>CSE</option>
            <option>IT</option>
            <option>ECE</option>
            <option>MECH</option>
            <option>ECE</option>
            <option>AGRI</option>
        </select>
        <br>
        <br>

        <label><b>Academic Qualificatons</b></label>
        <br>
        <textarea columns = 10 rows = 5></textarea>
        <br>
        <br>

        <label><b>Address</b></label>
        <br>
        <textarea columns = 10 rows = 5></textarea>
        <br>
        <br>

        <label><b>Preferres mode of contact</b></label>
        <input type="checkbox">Email</input>
        <input type="checkbox">Phone</input>
        <br>
        <br>

        <button type="submit">Submit</button>

    </form>

</body>
</html>
```

## Output:
![Screenshot 2025-07-07 131514](https://github.com/user-attachments/assets/bd4427a9-2d2a-4ab4-be42-feb6886256b5)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
