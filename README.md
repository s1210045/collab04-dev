# collab04-devUpdate for prototype 1
Haemah Akhtar, Nunzio D'amelio, Brian DeLorenzo, Eric Rivera
Dr. Ferdous
CSC415 Software Engineering
October 20th, 2024
Group #4 Proposal Pitch


Description of the problem to be solved. 

The problem we believe that needs to be addressed is a more effective way of communicating between the workers, students, and outside organizations. From what was explained to us there seems to be an inefficient way of going about it

The objective of the proposed project, to address the problem.

	The objective of our project is too figure out a better way of communicating amongst all 
            Parties of WorkWell, so we propose a chat log that would host all communication.

Engaging description of the project, including how and why it will meet this objective.

We suggest implementing a chat log that will be the host of communication amongst all parties involved in workwell. Administrators users can make announcements for all to see that can be listed at the top, students can ask questions on the form that can be answered by all, and most importantly we believe that it would be super effective if alumni of workwell are involved in this feature as we know that workwell is low on numbers so alumni can be seen as one more hand in terms of helping out and/or job searching

Stakeholders of the project, and explanation of why it is important for the team to be in ongoing contact with them.

	It is very important to be in contact with the stakeholders. Internal stakeholders(workwell employees and returning citizens) we need to keep good communication with in order to ensure what would be the most effective and functional for them along with our external stakeholders (alumni and jobs) to ensure that it is very easy for them to make listings or such with the organization, if it is not it is very likely they will shy away from using it.

Discussion of the social, ethical, economiThe c and real-world issues that must be addressed for the project to deliver value, and how the team will do this.
A large emphasis of the platform we are providing WorkWell with is to encourage a welcoming atmosphere where returning citizens feel secure and encouraged. Our team will accomplish this goal by putting in place moderation tools to promote professional conversation flow. In addition to this, the securement of user information and further sensitive data is required to better maintain the validity of private conversations. To do this, our team is set out to develop encrypted messaging platforms, where viewing access is limited to solely the sender and receiver. From an economic perspective, WorkWell has a very restricted budget which we are working with, thus in order to keep costs down, the system will utilize the web-browser on any computer with access to the internet. We are setting out to ensure the long-term success of this program, by providing users with an easy, and enjoyable experience overall; this will be achieved to ensure that all members of WorkWell are granted access to any opportunity: past or present.

Descriptive analysis of security and privacy concerns, and how you will address these.
Our biggest concert is user data protection, having user information that is sensitive that if leaked it could cause risk. With that having access control as well, making sure that the user is the only one who can access certain information as well as features To address these concerns, we will have to protect user data where there will be limited permission to who access the account and when. Monitoring the website and even adding authentication factors will help provide proper security and safety for the users.


Other systems being used by WorkWell, and how your project will work with those.
Other systems being used by WorkWell can vary from emails, phone calls, and even messages. The whole point of this system is to engage , having chat logs to be a form of communication amongst all parties involved in workwell. Which is how existing communication tools would be simply used. The chat log would work as a communication hub which can be accessed by all the users that would cause integration between email systems having notifications and updates be sent to users when needed.




A simple use case diagram showing the project functionality, and primary actors. Identify the functionality that will be implemented in each prototype (iteration) that can be completed within the time constraints of the semester. Specify functionality that is beyond the semester scope but could be added in future versions.

The main actors in the use case diagram will be:

Student: Can send messages, search chat logs, and filter messages.
Alumni: Can participate in chats and provide mentorship to students.
Administrator: Can make announcements and moderate conversations.
IT Support: Can manage user access and fix technical issues.
For the first iteration, basic messaging functionality will be implemented. Advanced features like message filtering and attachments can be added in future versions.





Detailed (step-by-step) Use Case Descriptions for all the major use cases you will implement. Do not include login functionality.
Use Case: Send Message

The student logs in and accesses the chat system.
The student selects an existing chat or starts a new chat with an alumni.
The student types a message and clicks "Send."
The system validates the message and stores it in the database.
The message is displayed in the chat log and is visible to the recipient(s).
Use Case: View Chat Logs

The user logs in and navigates to the chat log section.
The user views past messages in the chat logs.
The user can filter the logs by date or keywords to find specific conversations.

Design Class Diagram for the system; focus on the entities and relationships between them.
The main entities in the system are:

User: Contains details about the user (name, email, role: student, alumni, admin).
Message: Represents individual messages with attributes like content, timestamp, sender, and chat room.
ChatRoom: Represents a conversation between two or more users.
Admin: Inherits from User, with additional privileges like sending announcements and moderating content.
The relationships would show that users send messages to a chat room, and admins have additional permissions.


Software engineering course content, concepts, and technologies each team member will need to learn, and a plan with an estimated timeline for how this will be done.
Eric:
Brian:
Nunzio:
Haemah: Learn more about ruby on rails and how we can integrate it into using this website.

Week 1: Have the basic foundations of the project make sure we are working with our partners to create a website that is to their satisfaction

Following weeks: Begin to create the website, every individual in the group will have certain tasks they will need to complete the following week to make sure that everything is going smoothly. Every week we will have tasks to complete.

Usability and testing: Begin to test the website and get critical feedback from the website

Implementing: Creating the website after the feedback that was given

Final Week: Putting everything together and presenting it to the partners.
