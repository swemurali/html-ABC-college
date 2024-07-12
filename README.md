## AIM:
 Html file to display the contents as seen in the following image

 ## PROGRAM:
 ## HTML CODE:
 ```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table border="1px"width="100%">
        <tbody>
                <tr>
                    <td colspan="2" align="center">
                        <strong>My Day</strong>
                    </td>

                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Wake up only
                                <ul>
                                    <li>
                                        2 am
                                    </li>
                                    <li>
                                        walk
                                    </li>

                                    <li>
                                        jpg
                                    </li>
                                </ul>
                            </li>    
                        </ol>
                    </td>
                    <td rowspan="4" width="50%">
                        <table border="1px" width="50%" align="center">
                            <tr>
                                <td colspan="2" align="center">
                                    <strong>Things to Watch</strong>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <img src="images/car.jpeg" width="100%">
                                </td>
                                <td>
                                    <img src="images/cat.jpeg" width="100%">
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <img src="images/food.jpeg" width="100%">
                                </td>
                                <td>
                                    <img src="images/trees.jpeg" width="100%">
                                </td>
                            </tr>
                        </table>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Wake up only
                                <ul>
                                    <li>
                                        2 am
                                    </li>
                                    <li>
                                        walk
                                    </li>

                                    <li>
                                        jpg
                                    </li>
                                </ul>
                            </li>
                            
                            
                        </ol>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Breakfast
                                <ul>
                                    <li>
                                        8 am
                                    </li>
                                    <li>
                                        eggs
                                    </li>

                                    <li>
                                        Coffee
                                    </li>
                                </ul>
                            </li>
                        </ol>
                    </td>                    
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Go to Saveetha Engineering college
                                <ul>
                                    <li>
                                        8 am
                                    </li>
                                    <li>
                                        attend classes
                                    </li>

                                    <li>
                                        to be continued
                                    </li>
                                </ul>
                            </li>
                        </ol>
                    </td>                
                </tr>

                
        </tbody>

        
    </table>
</body>
</html>


```

## OUTPUT:
![image](https://github.com/Ramsai1234/html-ABC-college/assets/94269989/e3f5c42c-4bae-4f17-8df0-bf811ec80af9)




## Exp 2

Design a website for a College. There should be at least 15 web-pages present in the web-site.

## HOME HTML:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Saveetha Engineering College</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="images/ss.jpeg" alt="College Logo" style="max-width: 20spx; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <img src="images/saveetha.jpeg" alt="Gallery Image 1" style="width: 100%; max-width: 600px;">
    <h2>Description</h2>
    <p>Welcome to SEC - Saveetha Engineering College (Autonomous), a distinguished institution established in 2001 under the visionary leadership of Dr. N. M. Veeraiyan— a committed medical professional and philanthropist par excellence. With over 35 years of unwavering commitment to excellence in education, our college has emerged as the forefront of engineering education and research.</p>
    
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>

```

## academics.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Computer Science - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Science</h2>
    <a href="../Assignment_2/courses/Computer_Science.html">Computer Science</a><br>
    <a href="../Assignment_2/courses/Mathematics.html">Mathematics</a>
    <h2>Arts</h2>
    <a href="../Assignment_2/courses/English.html">English</a><br>
    <a href="../Assignment_2/courses/Sociology.html">Sociology</a>
    <h2>Commerce</h2>
    <a href="../Assignment_2/courses/Economics.html">Economics</a><br>
    <a href="../Assignment_2/courses/Business.html">Business Management</a>

    
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>
```
## admission.html:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Admission - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Admission Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>
        
        <label for="phone">Phone:</label><br>
        <input type="tel" id="phone" name="phone"><br><br>
        
        <label for="course">Course:</label><br>
        <select id="course" name="course">
            <option value="computer-science">Computer Science</option>
            <option value="mathematics">Mathematics</option>
            <option value="english">English</option>
            <option value="sociology">Sociology</option>
            <option value="economics">Economics</option>
            <option value="business-management">Business Management</option>
        </select><br><br>
        
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
        
        <input type="submit" value="Submit">
    </form>
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>


```
## gallery.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Gallery - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Gallery</h2>
    <img src="image/H1.jpg" alt="Gallery Image 1" style="width: 100%; max-width: 600px;">
    <img src="image/H2.jpg" alt="Gallery Image 2" style="width: 100%; max-width: 600px;">
    <img src="image/H3.jpg" alt="Gallery Image 3" style="width: 100%; max-width: 600px;">
    <img src="image/H4.jpg" alt="Gallery Image 4" style="width: 100%; max-width: 600px;">
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>
```
## Computer_Science.html:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Computer Science - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

    <header>
        <img src="logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
        <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
    </header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="../index.html">Home</a> |
    <a href="../academics.html">Academics</a> |
    <a href="../admission.html">Admission</a> |
    <a href="../gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Computer Science</h2>
    <p>The Computer Science course offers an in-depth understanding of computer systems, programming, and data structures. This course prepares students for careers in software development, data analysis, and more.</p>
    <h3>Teachers</h3>
    <ul>
        <li>Dr. John Doe</li>
        <li>Prof. Jane Smith</li>
    </ul>
    <h3>Timetable</h3>
    <ul>
        <li>Monday: 9:00 AM - 11:00 AM</li>
        <li>Wednesday: 1:00 PM - 3:00 PM</li>
        <li>Friday: 10:00 AM - 12:00 PM</li>
    </ul>
</section>

</body>
</html>

```
## output:
![image](https://github.com/Ramsai1234/html-ABC-college/assets/94269989/c2f80fe2-9bb3-4ca8-942b-88dfebd6e253)
![image](https://github.com/Ramsai1234/html-ABC-college/assets/94269989/5cf96e9c-b01d-4917-9069-4086964b87db)
![image](https://github.com/Ramsai1234/html-ABC-college/assets/94269989/f938c344-3897-4093-af85-fd8ecd520074)

![image](https://github.com/Ramsai1234/html-ABC-college/assets/94269989/756983db-bab6-414f-83bf-a297bd58ad05)
![image](https://github.com/Ramsai1234/html-ABC-college/assets/94269989/211ff5eb-bbf6-4e29-ad8e-18062dda9f59)






