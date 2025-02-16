[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/NbcI-sBg)
# INST377-Lab

# Name (Ihsane Abdeddaim):

# Comments: 

<!DOCTYPE html>
<html>
<head>
    <title>Rock Paper Scissors</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #333;
            color: white;
            padding: 20px;
            margin: 10px;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 0;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
        }
        nav ul li a:hover {
            color: red;
        }
        .content {
            display: flex;
            justify-content: space-between;
            padding: 20px;
        }
        main {
            width: 60%;
        }
        aside {
            width: 35%;
            background-color: lightgray;
            padding: 10px;
        }
        aside:hover {
            background-color: darkgray;
        }
        input:focus {
            width: 250px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rock Paper Scissors</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="https://example.com">Home</a></li>
            <li><a href="https://example.com">Rules</a></li>
            <li><a href="https://example.com">Contact</a></li>
        </ul>
    </nav>
    
    <div class="content">
        <main>
            <h2>Play Now</h2>
            <form>
                <label>Name:</label>
                <input type="text" required>
                
                <label>Choose:</label>
                <select>
                    <option>Rock</option>
                    <option>Paper</option>
                    <option>Scissors</option>
                </select>
                
                <button type="submit">Submit</button>
            </form>
        </main>
        
        <aside>
            <h2>How to Play</h2>
            <p>Rock beats Scissors, Scissors beats Paper, Paper beats Rock.</p>
        </aside>
    </div>
    
    <footer>
        <p>&copy; 2025 Rock Paper Scissors</p>
    </footer>
</body>
</html>

