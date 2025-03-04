body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #ddd3d3;
}

header {
    background-color: #0b78ed;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo img {
    height: 75px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;

}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;

}

main {
    padding: 20px;
    text-align: center;

}

.container{
   padding: 4px 4p 5px 5px;
   margin: 4px 4px 4px 4px;
    display: flex;
    position: relative;
    



}
.row{
    padding: 6px 6px 4px 4px;
    margin:4px 4px 4px 4px ;
    height: 200px;
    display: inline-flex;
    position: relative;
    justify-content: space-between;
}
.col-md-4{
    padding: 4px 4px 2px 2px;
    margin: 3px;
    border: 2px solid blue;

    
}
.card{
    height: 70px;
    padding: 2px 2px 2px 2px;
    margin: 3px 3px 3px 3px;
    border: 2px solid ;
    position: relative;
    display: inline-block;
}
.card-body{
    padding: 0;
    margin: 0;
}
.product-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.product-card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 4px;
    padding: 20px;
    margin: 10px;
    width: 200px;
    text-align: center;
}
.product-card img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
}

.product-card h2 {
    font-size: 1.2em;
    margin: 10px 0;
}

.product-card p {
    font-size: 0.9em;
    color: #555;
}
.product-card .price {
    font-size: 1.1em;
    color: #007bff;
    font-weight: bold;
}

.product-card button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 4px;
    cursor: pointer;
    width: 100%;
}

.product-card button:hover {
    background-color: #0056b3;
}
footer {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

.doctor-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.doctor-card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 4px;
    padding: 20px;
    margin: 10px;
    width: 200px;
    text-align: center;
}

.doctor-card img {
    max-width: 100%;
    height: auto;
    border-radius: 50%;
}
.doctor-card h2 {
    font-size: 1.2em;
    margin: 10px 0;
}

.doctor-card p {
    font-size: 0.9em;
    color: #555;
}

.doctor-card button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 4px;
    cursor: pointer;
    width: 100%;
}
.doctor-card button:hover {
    background-color: #0056b3;
}
footer {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
form {
    max-width: 300px;
    margin: 0 auto;
    text-align: left;
}

form label {
    display: block;
    margin-bottom: 5px;
}

form input {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    
}

form button {
    width: 100%;
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #0056b3;
}
form {
    max-width: 400px;
    margin: 0 auto;
    text-align: left;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

form input, form select {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 16px;
}
form button {
    width: 100%;
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
}

form button:hover {
    background-color: #0056b3;
}

footer {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
/* after changes the login dropdown */
#loginOptions {
    margin-top: 10px;
    border: 1px solid #ccc;
    padding: 10px;
    background-color: #f9f9f9;
}

#loginOptions ul {
    list-style-type: none;
    padding: 0;
}

#loginOptions ul li {
    margin: 5px 0;
}

#loginOptions ul li a {
    text-decoration: none;
    color: #333;
}

#loginOptions ul li a:hover {
    color: #007BFF;
}
/* styles for doctor login pages */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo img {
    height: 50px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

fieldset {
    border: 1px solid #ccc;
    padding: 20px;
    margin-bottom: 20px;
    background-color: white;
}

legend {
    font-weight: bold;
    font-size: 1.2em;
}

label {
    display: block;
    margin-top: 10px;
}

input[type="text"],
input[type="email"],
input[type="tel"],
input[type="number"],
textarea,
input[type="file"] {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button[type="submit"] {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1em;
}

button[type="submit"]:hover {
    background-color: #0056b3;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #007BFF;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}
