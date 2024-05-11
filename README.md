# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```

<html>
    <title>OUR PROJECTS</title>
    <style>  
        .footer {
            position: fixed;
            left: 0;
            bottom: 0;
            width: 100%;
            background-color:black;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    body{
        background:url(product.jpg);
        background-size:contain;
    } 
    h1{
        color: aliceblue;
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="mainpage.html">
                    <input type="button" value="HOME">
                </a>
                <a href="projects.html">
                    <input type="button" value="OUR PROJECTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR META PROJECTS</h1>
        <img src="2.jpeg" height="500" width="800">
    </center>
    <footer class="footer">
        <p>&copy; 2024 My Home Page. All rights reserved.</p>
    
    </footer>
    </body>
    
</html>

```


## OUTPUT:

![Screenshot 2024-05-11 113256](https://github.com/jayaseelan2006/Pharma/assets/151389443/7be2486a-9a0d-4ad1-a97a-6f6bb3091a2f)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
