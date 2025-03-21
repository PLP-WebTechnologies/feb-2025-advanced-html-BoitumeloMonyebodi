<!DCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Registration and Contact Page</title>
    <style>
        body {
            background-color: lightblue;
            text-align: center;
            font-family: verdana;
            line-height: 1,6;
        }
            
        table{
            border-collapse: collapse;
            width: 100%;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        table,th, td {
            border: 1px solid black;
            
        }
        th, td {
            padding: 15px;
            text-align: left;
        }
        form{
            margin-top: 20px;
            margin-bottom: 20px;
            margin: auto;
            width: 50%;
        }
        label{
            padding: 12px 12px 12px 0;
            display: inline-block;{
                margin-top: 10px;
                margin-bottom: 10px;
            
        }
    </style>
</head>
<body>
 <h1>Welcome to the Registration and Contact Page </h1>
            <h2>Significant Points</h2>
            <ol type = "I">
                <li>Complete the form below to register.</li>
                <li>Provide accurate contact information.</li>
                <li>Make sure all required fields are filled out.</li>
            
            </ol>
            <h2> HTML Images</h2>
            <img src="https://www.w3schools.com/html/pic_trulli.jpg" alt="Trulli" width="500" height="333">
            <H2>Contact Information</H2>
            <p>For more information, please contact us at:</p>
            <address>
                <strong>Phone:</strong> 012 345 6789<br>
                <strong>Email:</strong>
            <table border="1" width="50%" align="center">
                <thead>
                <tr>
                    <th>First Name</th>
                    <th>Last Name</th>
                    <th>Address</th>
                    <th>Email</th>
                </tr>
                </thead>
                <tbody>
                    <td>Keamogetswe</td>
                    <td>Monyebodi</td>
                    <td>unit 18komati tembisa</td>
                    <td>happinessboitumelo101@gmail.com</td>
                </tr>
                <tr>
                    <td>Boitumelo</td>
                    <td>Monyebodi</td>
                    <td>678 birchacressst,maplefood</td>
                    <td>linkymonyebodi1@gmail.com</td>
                </tr>
                </tbody>
            </table>
        </section>
        <section>
            <h2>Audio</h2>
            <audio controls>
                <source src="horse.ogg" type="audio/ogg">
                <source src="horse.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <section>
                <h3>Video</h3>
                <video width="320" height="240" controls>
                    <source src="movie.mp4" type="video/mp4">
                    <source src="movie.ogg" type="video/ogg">
                    Your browser does not support the video tag.
                </video>
            </section>

            <h>HTML Forms</h7>
            <form action="index.html" method="post">
                <label for="fname">First Name:</label><br>
                <input type="text" id=fname" name="fname" placeholder="Enter your name" required><br><br>
        
                <label for="lname">Last Name:</label><br>
                <input type="text" id="lname" name="lname" placeholder="Enter your last name" required><br><br>
        
                <label for="address">Address:</label><br>
                <input type="text" id="address" name="address" placeholder="Enter your address" required><br><br>
            
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
            
                <label for="dropdown">Choose a role:</label>
                <select id="dropdown" name="dropdown">
                    <option value="student">Student</option>
                    <option value="teacher">Teacher</option>
                    <option value="parent">Parent</option>
                    <option value="other">Other</option>
                </select><br><br>
                <label for=Hobbies:</label><br>
                <input type="checkbox" id="hobbies" name="hobbies" value="reading">Reading<br>
                <input type="checkbox" id="hobbies" name="hobbies" value="writing">Writing<br>
                <input type="checkbox" id="hobbies" name="hobbies" value="cooking">Cooking<br>
                <input type="checkbox" id="hobbies" name="hobbies" value="baking">Baking<br><br

                <input type="submit" value="Register">
            </form>
            </section>

</body>

</html>
