# CodeLearningWebsite
Overview: CodeWebsiteProject is an educational web application designed to provide lessons, quizzes, and tests to users, facilitating their learning and progress in coding concepts. The application incorporates interactive elements to engage users and track their progress through various learning modules.  

Features: 
  -Home Page: Displays the title "For the Love of Coding." 
  -Provides a brief introduction to coding concepts. 

Lesson Management: 
  -LessonController: Manages the display and completion of lessons. 
  -View Lesson: Shows lesson details with the title and content. Includes a "Complete Lesson" button to mark the lesson as completed and redirect       users accordingly. 
  -Lesson Completion Redirect: Users are redirected to the AllLessonsCompleted page if all lessons are finished; otherwise, they are taken to the       lessonIndex page. 

Quiz Management: 
  -QuizController: Handles quiz operations including displaying questions, submitting answers, and showing the completion view. 
  -Quiz View: Presents quiz questions with multiple-choice options. Includes feedback on user answers and a button to submit responses. Will let        users retry the questions again if they are not correct. 
  -Quiz Completion View: Displays a message indicating quiz completion and provides a button to return to the main menu. 

Test Management: 
  -TestsController: Manages the display and submission of test questions. 
  -Test View: Shows test questions with multiple-choice options. Provides feedback based on user answers and a button to submit responses. Let's       user retry the question if it's not correct. 
  -Test Completion View: Congratulates users on completing the test and offers a button to return to the main menu. 

Design: 
  -Utilizes a light pastel color scheme for a soft and engaging visual experience. 
  -Responsive design to ensure usability across different devices. 

Technology: 
  -Backend: C# for server-side logic. 
  -Frontend: HTML and CSS for layout and styling. 
  -Framework: Built using ASP.NET Core with Razor Pages for server-side rendering. 

Future Enhancements: 
  -More Educational Content: Plan to add additional lessons, quizzes, and tests to expand the learning material and provide more comprehensive coverage of coding concepts. 
  -Progress Feature: Currently in development, aimed at tracking and displaying user progress in lessons, quizzes, and tests. With the progress         feature I wish to provide a graph so that users can truly see their progress. 
  -Login Page: Want to develop a login in page for users. With Google authentication and GitHub. 
  -Text-Editor: Planning to integrate a text editor to allow users to practice coding directly on the website, enhancing their practical coding         skills alongside theoretical knowledge. 

 

 
