# Movie-booking-backend
<h3> A multi user movie ticket booking system that enables administrators to manage movie listings and users to book movies.This repo contains the backend source code functionality.</h3> <br>
<ul>
<li> A data model schema is created for entities such as users/clinets, administrators, movies information and booking information.</li>
<li> Clients can login into the system using email and password, after that only they will be able to see all movies which were booked by them or they can also create a new booking. Clients can also update their personal information which is taken care with the help of CRUD APIs. </li>
<li> Similarly admins can also login to the system and perform CRUD actions. Moreover they can add a new movie to the system which will release in the upcoming future and can remove a movie from the system as well. </li>
<li> Clients and admins private information like password is stored in hashed/ encrypted format in the database using bcrypt algorithm.</li>
<li> Authentication and authorization is also taken care of with the help of JWT(JSON Web Token) so that only authorized users can access the certian parts of the system.</li>
<li> Tech Stack(for backend): Node.js | Express.js framework | JavaScript | MongoDB(for database) | JWT | Bcrypt Algorithm | Postman(for API testing) </li>
</ul>
