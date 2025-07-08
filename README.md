# Styled_Profile_Card
## Date:

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My Profile</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <h1>Shabreena Vincent</h1>
        <hr>
        <h2>Student</h2>
        <hr>
        <h3>Fullstack Developer</h3>
        <hr>
        <img src="profile.jpg" alt="Profile Picture" width="200" height="200">
        <hr>
        
        <section>
            <h3>Profile</h3>
            <p>Highly motivated Artificial Intelligence and Data Science student with a solid foundation in machine learning,
 data analysis, and software development. Proficient in programming languages like Python,c,html,css, data
 visualization, and algorithm development. Passionate about applying AI techniques to solve real-world challenges
 and contributing to innovative projects. </p>
        </section>
           <section>
        <h3>Interests</h3>
        <p>
        Reading books,Colouring,Playing Chess,dancing
        </p>
    </section>

    <hr>

  <section>
        <h3>Skills</h3>
        <p>soft skills:Communication,Problem Solving,Leadership</p>
        <p>technical skills:Java,Python,C programming,html javascript</p>
    </section>
</hr>

    <hr>
    <section>
        <h3>Contact</h3>
        <p>Email:shabs1162@gmail.com</p>
        <p>Location: Chennai, Tamil Nadu</p>
    </section>
    </body>
</html>
```
## CSS CODE
```
body{
    background-color: #f2f2f2;
    font-family: Arial, Helvetica, sans-serif;
    margin:0;
    padding:20px;
}
h1,h2,h3{
    text-align:canter;
    margin:10px 0;
    color:rgb(169, 32, 32);
}
h1{
    font-size:2em;
}
h2{
    font-size:1.5em;
    color:#8f4c05;
}
h3{
    font-size:1.2em;
    color:black;
}
img{
    display:block;
    margin:20px auto;
    border: radius 50%;
    box-shadow:0 0 10px rgba(199, 92, 31, 0.2);
}
section{
    background-color:aliceblue;
    padding: 15px 20px;
    margin: 20px auto;
    max-width:600px;
    border-radius:10px;
    box-shadow: 0 4px 8px rgba(222, 188, 251, 0.721);
}
p{
    line-height:1.6;
    color: rgba(200, 170, 18, 0.948);
}
hr{
    border:none;
    height:1px;
    background-color: blanchedalmond;
    margin:20px auto;
    max-width: 80%;
}
```

## Output:
![image](https://github.com/user-attachments/assets/35210357-56b2-47c0-a680-a791b4f8959b)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
