# index1.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        /* Add some basic styling to make the page look better */
        body {
            font-family: Arial, sans-serif;
        }
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>

    <!-- Ordered List -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>Object 1</li>
        <li>Object 2</li>
        <li>Object 3</li>
    </ol>

    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/248797/pexels-photo-248797.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" 
         alt="Beautiful Landscape" width="500" height="300">

    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>Kevin Mwangi</td><td>123 Westlands</td><td>0712345678</td><td>kevin.mwangi@outlook.com</td></tr>
            <tr><td>Aisha Njeri</td><td>456 Mombasa</td><td>0723456789</td><td>aisha.njeri@outlook.com</td></tr>
            <tr><td>Samuel Kiptoo</td><td>789 Eldoret</td><td>0734567890</td><td>samuel.kiptoo@outlook.com</td></tr>
            <tr><td>Brenda Wanjiru</td><td>101 Kisumu</td><td>0745678901</td><td>brenda.wanjiru@outlook.com</td></tr>
            <tr><td>Peter Odhiambo</td><td>202 Nakuru</td><td>0756789012</td><td>peter.odhiambo@outlook.com</td></tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required placeholder="Enter your name"><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required placeholder="Enter your password"><br><br>

        <label for="date">Date:</label>
        <input type="date" id="date" name="date" required><br><br>

        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="">Select a country</option>
            <option value="Uganda">Uganda</option>
            <option value="Tanzania">Tanzania</option>
            <option value="Kenya">Kenya</option>
        </select><br><br>

        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>

        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>

        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label><br><br>

        <label for="hobbies">Hobbies:</label>
        <input type="checkbox" id="reading" name="hobbies" value="reading">
        <label for="reading">Reading</label>

        <input type="checkbox" id="writing" name="hobbies" value="writing">
        <label for="writing">Writing</label>

        <input type="checkbox" id="coding" name="hobbies" value="coding">
        <label for="coding">Coding</label><br><br>

        <input type="submit" value="Submit">
    </form>

    <!-- Audio and Video Elements -->
    <h2>Audio and Video Elements</h2>
    <audio controls>
        <source src="audio.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

    <video controls width="500">
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>

</body>
</html>
