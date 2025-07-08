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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>My Profile</title>
</head>
<body>
    <header>
        <h1>Pravinrajj</h1><hr>
        <h2>Student</h2><hr>
        <h2>Aspiring Web Developer</h2>
    </header>
    <hr>
    <img src="profile.png" alt="Profile picture" width="12%"><hr>
    <article>
        <section>
            <h3>About Me</h3>
            <p>
                I am a dedicated and passionate 3rd year B.Tech student specializing in Artificial Intelligence and Machine Learning. 
                With a strong foundation in programming languages such as C and beginner-level proficiency in Python, SQLite, MongoDB, 
                and Web Development, I am well-equipped to tackle diverse technical challenges. My hands-on experience in creating 
                basic AI models using TensorFlow further underscores my capability and enthusiasm for the field. 
            </p>
        </section>
        <section class="int">
            <h4>Interests</h4>
            <li>Web Development</li>
            <li>App Development</li>
            <li>Programming</li>
        </section>
        <section class="ski">
            <ul>
                <h4>Skills</h4>
                <li>C</li>
                <li>Python</li>
                <li>Java</li>
                <li>Kotlin</li>
                <li>JavaScript</li>
                <li>HTML,CSS</li>
                <li>React,Node</li>
                <li>SpringBoot</li>
            </ul>
        </section>
    </article>
</body>
</html>
```

## CSS Code:
```css
body{
    background-color:lightgray;
    font-family: Georgia,'Times New Roman', serif, Arial, Helvetica;
}
h1{
    text-align: center;
    color:#1342dc;
}
h2{
    text-align: center;
    color:#309ce4;
}
h3{
    text-align: center;
    color: #2646afe9;
}
img{
    border-radius: 50%;
    display: block;
    margin: auto;
}
p{
    padding: 20px;
    background-color: rgb(224, 222, 222);
    border: 2px solid rgb(233, 216, 216);
    border-radius:5%;
}
.int{
    display: inline-block;
    margin: 0 auto 19% 19%;
}
.ski{
    display: inline-block;
    margin:0 auto 19% 19%;
}
```
## Output:
![image](https://github.com/user-attachments/assets/04f67a66-2746-4d44-912a-ebcc282a5c69)

## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
