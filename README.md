# Web-Development#
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewpoint" content="width=device-width,intial-scale">
        <title>Employee Portal</title>
        <link rel="icon" href="/html/download.png">
        <style>
            body{
                margin:0;
                padding:0;
                 font-family:Arial, sans-serif;
                 background-color:rgb(123, 184, 203);
            }
            header,footer{
                background-color: #163f43;
                color: aliceblue;
                text-align: center;
                padding: 2px;

            }
            .nl{
                display: inline;
                padding: 10px;
            }
            .nl a { 
                text-decoration: none;
                color:antiquewhite;
            }
            .rf{
                width:max-content;
                margin-left: auto; 
                margin-right: auto;
            }
            
            .ed{
                text-align: center;
            }
            table{
                margin-left: auto;
                margin-right: auto;
                width: 100%;
               border-collapse:collapse ;
               padding:8px;
            }
            .cu{
                text-align: center;

            }
        </style>
    </head>
    <body>
        <header>
            <h1>Welcome to Dmart Employee Portal</h1>
           <nav>
             <ul>
                <li class="nl"><a href="#Employee-Registration">Employee Registration</a></li>
                <li class="nl"><a href="#Employee-Directory">Employee Directory</a></li>
                <li class="nl"><a href="#Contact Us">Contact Us</a></li>
            
            </ul>
        </nav>

        </header>
        <img src ="/html/Project(html)/Employee_Engagement_1200x630-768x403.png" height="400" width=100% alt="Company image" title="Dmart">
        <section id="Employee-Registration" class="rf">
            <h2> Employee Registration</h2>
            <p>Fill the below form to register as <em>employee</em></p>
            <form>
                
                <label>Name:  </label>
                <input type="text"><br><br>
                <label>Age:   </label>
                <input type="number"><br><br>
                <label>Email-Id:   </label>
                <input type="email"><br><br>
                <label>Password:</label>
                <input type="password"><br><br>
                <label>Qualification: </label>
                <input type="text"><br><br>
                <label>Mobile No:</label>
                <input type="number"><br><br>
                <label>Country:</label>
                <input type="text"><br><br>
                <label for="state">  State: </label>
                <select id="state">
                <option  value="Maharashtra">Maharashtra</option>
                <option value="Karnataka">Karnataka</option>
                <option value="Delhi">Delhi</option>
                <option value="Kerala">Kerala</option>
                <option value="Telagana">Telagana</option>
            </select><br><br>
            <label for ="gender"> Gender:</label>
            <input type="radio"  value="male" id="male" name="gender">
            <label for ="male">Male</label>
            <input type="radio"  value="female" id="female" name="gender">
            <label for ="female">Female</label><br><br>
                <label>DOB:</label>
                <input type="date"><br><br>
                <label>DOJ:</label>
                <input type="date"><br><br>
                <label for ="role"> Role:</label>
                <select id="role"> 
                    <option>Software Engineer</option>
                    <option>Product Manager</option>
                    <option>Accountant</option>
                    <option>Cleaner</option>
                    <option>Inventory Manager</option>
                    <option>Security</option>
                </select><br><br>
                <textarea placeholder="Explain your interest in registration." rows="5" cols="50"></textarea><br><br>
            <label for="file"> Upload file:</label>
            <input type="file" value="file" id="file"><br><br>
            <input type="checkbox" id="terms" value="agree">
            <label for="terms">I agree on the terms and conditions</label>
            <br><br>
            <input type="SUBMIT" style="background-color: green;color: antiquewhite;"><br><br>
            <input type="RESET" style="background-color: red;color: antiquewhite;"><br><br>
            
            </form>

        </section>
<!--section2-->
        <section id="Employee-Directory" class="ed">
            <h2>Employee Directory</h2>
            <p>List of all registered employees</p>
            <table border="">
    <tr>
        <th>
            Employee Id
        </th>
        <th>Employee Name</th>
        <th> Employee Role</th>
    </tr>
    <tr>
        <td> BHAKTI L.MALWANKAR</td>
        <td>E0005
        </td>
        <td>Software Engineer</td>
    </tr>
    <tr>
        <td> SUREKHA L.MALWANKAR</td>
        <td>E0031
        </td>
        <td>Accountant</td>
    </tr>
    <tr>
        <td> SHRIGANDHA L.MALWANKAR</td>
        <td>E0006
        </td>
        <td>Product Manager</td>
    </tr>
    <tr >
        <td> SHREE L.MALWANKAR</td>
        <td>E0029
        </td>
        <td>Inventory Manager</td>
    </tr>
            </table>


        </section>
        <section id="Contact Us" class="cu">
            <h2>Contact Us</h2>
            <p>You can contact us at Dmart@official.com  Or Visit us between 9AM To 7:30 PM</p>
            <p>Office Location:</p><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3838.4536470442167!2d74.51235807489881!3d15.832736984813044!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bbf6689173fbedb%3A0xa1672921dd6f87ba!2sShiv%20Shakti%20Apartment!5e0!3m2!1sen!2sin!4v1708455778484!5m2!1sen!2sin" width="480" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

        </section>
        <footer>
            <p>&copy;2024 Dmart</p>
        </footer>
    </body>
</html>
