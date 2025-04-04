# Advanced HTML5 Elements and Forms
## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Webpage</title>
    </head>
<body>
    <header>
        <h1>Welcome to My Website!</h1>
        <p>Exploring different HTML elements.</p>
    </header>

   <main>
        <section>
            <h2>Ordered List with Roman Numerals</h2>
            <ol type="i">
                <li>First item</li>
                <li>Second item</li>
                <li>Third item</li>
                <li>Fourth item</li>
                <li>Fifth item</li>
            </ol>
        </section>

   <section>
            <h2>External Image</h2>
            <img src="https://images.pexels.com/photos/1001953/pexels-photo-1001953.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                 alt="Scenic Mountain Landscape" width="600">
            <p><small>Image source: Pexels.com</small></p>
        </section>

   <section>
            <h2>Contact List</h2>
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
                    <tr>
                        <td>Brian Manoah</td>
                        <td>P.O. Box 123-00100, Ruiru</td>
                        <td>+254 700 000 000</td>
                        <td>brian.manoah@example.com</td>
                    </tr>
                    <tr>
                        <td>Jane Smith</td>
                        <td>P.O. Box 456-00200, Nairobi</td>
                        <td>+254 711 111 111</td>
                        <td>jane.smith@example.org</td>
                    </tr>
                    <tr>
                        <td>Peter Kariuki</td>
                        <td>P.O. Box 789-00300, Thika</td>
                        <td>+254 722 222 222</td>
                        <td>peter.kariuki@sample.net</td>
                    </tr>
                    <tr>
                        <td>Siah Waweru</td>
                        <td>P.O. Box 101-00400, Kiambu</td>
                        <td>+254 733 333 333</td>
                        <td>siah.waweru@test.co.ke</td>
                    </tr>
                    <tr>
                        <td>Bilha Wanjiku</td>
                        <td>P.O. Box 222-00500, Machakos</td>
                        <td>+254 744 444 444</td>
                        <td>bilha.wanjiku@domain.info</td>
                    </tr>
                </tbody>
            </table>
        </section>

   <section>
            <h2>Registration Form</h2>
            <form action="#" method="POST">
                <fieldset>
                    <legend>User Information</legend>

   <div>
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" placeholder="Your Full Name" required>
                    </div>

   <div>
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" placeholder="your.email@example.com" required>
                    </div>

   <div>
                        <label for="password">Password:</label>
                        <input type="password" id="password" name="password" placeholder="Enter Password" required minlength="8">
                        <small>Password must be at least 8 characters long.</small>
                    </div>

   <div>
                        <label for="birthdate">Date of Birth:</label>
                        <input type="date" id="birthdate" name="birthdate">
                    </div>
                </fieldset>

   <fieldset>
                    <legend>Preferences</legend>

   <div>
                        <label for="country">Country:</label>
                        <select id="country" name="country">
                            <option value="">-- Select Country --</option>
                            <option value="kenya">Kenya</option>
                            <option value="uganda">Uganda</option>
                            <option value="tanzania">Tanzania</option>
                            <option value="rwanda">Rwanda</option>
                            <option value="burundi">Burundi</option>
                            <option value="other">Other</option>
                        </select>
                    </div>

   <div>
                        <span>Gender:</span>
                        <input type="radio" id="male" name="gender" value="male">
                        <label for="male">Male</label>

   <input type="radio" id="female" name="gender" value="female">
                        <label for="female">Female</label>

   <input type="radio" id="other_gender" name="gender" value="other">
                        <label for="other_gender">Other</label>
                    </div>

   <div>
                        <span>Interests:</span>
                        <input type="checkbox" id="sports" name="interests" value="sports">
                        <label for="sports">Sports</label>

  <input type="checkbox" id="music" name="interests" value="music">
                       <label for="music">Music</label>

   <input type="checkbox" id="reading" name="interests" value="reading">
                        <label for="reading">Reading</label>

   <input type="checkbox" id="travel" name="interests" value="travel">
                        <label for="travel">Travel</label>
                    </div>
                </fieldset>

   <button type="submit">Register</button>
            </form>
        </section>
    </main>

   <footer>
        <p>&copy; 2025 My Awesome Webpage</p>
        <p>Located in Ruiru, Kiambu County, Kenya.</p>
    </footer>

</body>
</html>
