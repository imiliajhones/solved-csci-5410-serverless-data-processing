Download Link: https://assignmentchef.com/product/solved-csci-5410-serverless-data-processing
<br>






Objective:

This assignment covers concepts of containerization and Serverless components of cloud computing. The primary objective of this assignment is to introduce you to the cloud computing containerization application using Docker and creation of a chatbot using Lex.







Plagiarism Policy:

<ul>

 <li>This assignment is an individual task. Collaboration of any type amounts to a violation of the academic integrity policy and will be reported to the AIO.</li>

 <li>Content cannot be copied verbatim from any source(s). Please understand the concept and write in your own words. In addition, cite the actual source. Failing to do so will be considered as plagiarism and/or cheating.</li>

 <li>The Dalhousie Academic Integrity policy applies to all material submitted as part of this course. Please understand the policy, which is available at:</li>

</ul>

https://www.dal.ca/dept/university_secretariat/academic-integrity.html










Tasks:

This assignment has 2 parts. Part A is related to coding, and development. Part B is related to exploring a service.




Part A. Build, deploy, and run a Containerized Application using GCP. Using GCP create and validate an online meeting account.

<table width="608">

 <tbody>

  <tr>

   <td colspan="2" width="415">take screenshots at every step and submit as part of the PDF:</td>

   <td width="193"> </td>

  </tr>

  <tr>

   <td rowspan="3" width="17"> </td>

   <td colspan="2" width="591">a.     Create three containers using Docker. These containers are responsible for the backend logic. The database you will be using here is, MySQLb.     Container #1 is responsible for accepting registration details from frontend and store it in backend database. (image 1)c.      Container #2 is responsible for validating the Login information (image 2)d.     Once a user is logged in – the state changes to online, and it appears on the front page (image 3)e.     Your database should contain only 2 tables. One to contain data, another to contain user state (online, offline, timestamp etc.) information.f.      Container #3 is responsible for extracting state information from database. E.g.who is online. You need to maintain the session from login to logout. The session must expire after clicking the logout, which should update the state table.g.     Once the docker images are built, you need to run those using Google Cloud Run.h.     In order complete the tasks, and perform interaction, you need build 3 simple web pages (or 1), using any technology of your choice.</td>

  </tr>

  <tr>

   <td colspan="2" width="591">i. Write test case to test your application, and perform testing</td>

  </tr>

  <tr>

   <td colspan="2" width="591">j. You need to explore, Google Cloud Run, GCR, Docker Container documents, and write a summary of ½ page explaining how you have used these technologies in your application.</td>

  </tr>

  <tr>

   <td width="17"></td>

   <td width="398"></td>

   <td width="193"></td>

  </tr>

 </tbody>

</table>



















Part B. Building a Chatbot:

Using AWS Educate account perform the following:

take screenshots at every step

<ol>

 <li>Using AWS Lex – Create a chatbot on OrderFood</li>

 <li>Consider it as a pizza place. (assumptions: they have 3 types of regular size pizzas –veg, cheese, pepperoni.</li>

 <li>The chatbot can accept information on food delivery or pickup</li>

 <li>If it is delivery, then customer address, delivery date, and time is important</li>

 <li>If it is takeaway, then assuming same day, it should ask arrival time of customer.</li>

</ol>

E.g.

Utterances – “I want to place an order for pickup”

Prompts – “When are you coming to get your parcel?”

Slots – “I will come around noon”

Prompts – “What do you want today?”

Slots – “cheese pizza”

Prompts – “How many?”

Slots – “2”

Fulfillment –

“You have ordered 2 regular cheese pizza, and you will be arriving at 12:00 pm”  “Yes”

“Your order has been placed successfully”











