<h2>Laravel Chat Application (Laravel + Reverb ) </h2>
<p>Welcome to the Laravel Chat Application! This application allows you to create real-time chat conversations between users using the Laravel framework. It includes features such as user authentication, chat rooms, and real-time messaging.</p>

<h2>Features </h2> 
Real-time messaging: Chat messages are sent and received instantly using WebSocket technology.<br>
User authentication: Register, login, and logout functionality for users.<br>
Chat rooms: Users can create or join chat rooms to communicate with other users.<br>
User profiles: View and edit user profile information.<br>
Secure communication: Messages are transmitted securely over the network.<br>

 
 
composer install <br>
npm install  <br>

Copy the .env.example file to a new file named .env: <br>

cp .env.example .env <br>
Configure the .env file with your database and other settings. <br>

Step 5: Generate an Application Key <br>
Generate a new application key: <br>

php artisan key:generate <br>
Step 6: Run Migrations and Seed the Database <br>
Run the migrations to set up the database schema: <br>

php artisan migrate <br>
Seed the database with default data (if available):  <br>

php artisan db:seed <br>
 Start the WebSocket Server <br> <br>
To enable real-time messaging, you need to start the Reverb server: <br>

php artisan reverb:start <br>
 Start the Application <br><br>
Start the Laravel application:

php artisan serve <br>
The application will run on http://127.0.0.1:8000.
<br>
License <br><br>
This project is licensed under the MIT License.<br>

Contributing<br>
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or bug fixes.

