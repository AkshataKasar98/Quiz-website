Java Quiz Web Application
This project is a simple and interactive Java Quiz Web App developed using HTML, CSS, and JavaScript. The quiz features multiple-choice questions about Java programming, a timer, real-time score calculation, and a downloadable certificate upon passing.

🚀 Features
Multiple-choice Quiz: 20 questions focused on Java programming.

User Authentication: Users enter their name (letters and spaces only) before starting the quiz.

Countdown Timer: A 15-minute timer begins as soon as the quiz starts.

Real-time Scoring: Automatically calculates the score upon quiz completion.

Certificate Generation: A certificate is displayed along with the score if the user scores 80% or higher.

PDF Download: Users can download their certificate in PDF format using the jsPDF library.

Retake Option: For users scoring below 80%, the option to retake the quiz is provided.

🛠️ Technologies Used
HTML5

CSS3

JavaScript (Vanilla)

jsPDF for PDF generation

🖥️ How It Works
Welcome Screen: User clicks on "Start Quiz" from the home page.

Login: User is prompted to enter their name, which is validated to include only alphabetic characters and spaces.

Quiz:

The quiz starts with a 15-minute countdown.

Multiple-choice questions are displayed with radio button options.

Submission:

The score is calculated and displayed.

If the score is 80% or higher, a certificate is made accessible; otherwise, an option to retake the quiz is provided.

Certificate: Displays the user’s name and final score, with the option to download the certificate as a PDF.

📁 File Structure
QUIZ.html: The main file containing the HTML, CSS, and JavaScript code for the quiz.

Images: External resources such as bg1.png, bg6.png for background images and favicon.ico for the page icon are used.

📌 Running the Application
No backend setup is necessary. Simply open the QUIZ.html file in a web browser to start the quiz.

✅ Future Enhancements
Add a backend database to store user scores and quiz attempts.

Implement user authentication with login credentials.

Randomize quiz questions for a unique user experience each time.

Add more interactive elements and animations to enhance the user interface.

📜 License
This project is for educational and demonstration purposes.
