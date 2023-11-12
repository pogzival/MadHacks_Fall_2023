# Project: Sift Scheduler for UW Madison Class Enrollment
*Inspiration*
The inspiration for this project stemmed from the challenging experience of selecting schedues for many different courses here at UW Madison. The process often lacked personalized filters to give way to individual preferences in terms of both average GPA and class timings. This led us to create a tool that would streamline this process, allowing students to control their scheduling and planning more than ever before!

*Main Elements*
-In order to create this web application, we needed to first obtain an accurate record of all Spring 2023 course offerings, including their meeting times, locations, professors, and more. This data was stored in a MongoDB which allowed for ease of use when web scraping (which was an around 4 hour process in total) and retriving data. 

-We additionally had to obtain accurate grade averages for these classes to give students the ability to filter by classes with the lowest or highest GPAs in the past. We accessed MadGrades through webscraping and stored this additional data in our MongoDB.

-By using a Python Backend, we are able to create a comprehensive list of schedules for the class options provided, and then filter them based on the user's input preferences on the various factors.

-Once we determine the optimal schedule for the user, we create an image file as well as a bit of detailed text to return back to the user through the Flask frontend.