# Development Model (Klea)
### Plan Driven Model – Waterfall Model

GoDrive Albania is a plan-driven software model designed to achieve all the phases required to develop the application. GoDrive Albania is a generic product, based even in the market absences that generate user issues as user requirements which are later translated into important part of the software structure.

Documentation of each phase of developing the model is a key factor in work organization and its veracity. Using this model will help us to be careful in the designing and its requirements because if there is something to change during the time evolution, step by step processing will lead in better coordination and work division.

_Phase 1_ - Requirements Definition  
_Phase 2_ - System and Software Design  
_Phase 3_ - Implementation and Unit Testing  
_Phase 4_ - Integration and System Testing  
_Phase 5_ - Operation and Maintenance  


# User and System Requirements (Glen)
### User Requirements
 1. The website's home page shall contain general information, as well as links to other related webpages.  
 2. Guests shall be able to register into the website as a registered user.  
 3. Registered users shall be able to book cars for rent and keep track of their rentals.  
 4. Website users shall be able to filter vehicles up for rent to easily find what they are looking for.  
 5. Users shall request to be verified as rental businesses by system admins in order to gain special privileges.  
 6. Rental companies shall be able to create (and remove) their own listings.  
 7. The application should be easy-to-use, in order to maximize its efficiency.  
 8. The application shall have security features, in order to ensure the privacy of its users.  
 9. The application shall offer a way for users to contact customer support, in the case they need assistance.  

### System Requirements
 1. **Home Page**  
 1.1 The home page shall offer basic information on what the website does, its purpose and how to use it.  
 1.2 The home page shall link to other webpages, such as: Profile, Gallery, Help.  
 2. **Registration and Login**  
 2.1 Guests shall click on a Log-in option on the home page to Login or Register as desired.  
 2.2 If the guest does not have a registered account, they can press Register, and provide the necessary information to create an account.  
 2.3 To register, the guest shall submit a form containing a username, email, password, and cellphone number.  
 2.4 Upon registration, a verification email shall be sent to the user's provided email to confirm their identity.  
 2.5 The user can login using their Username and password.  
 2.6 Users can logout at the press of a button. 
 3. **Registered Users' Privileges**  
 3.1 Registered users shall be able to request reservation of cars online at the press of a button.  
 3.2 Registered users shall contact rental companies via email or phone number to complete payment and pick-up/drop-off.  
 3.3 Registered users shall be able to book a maximum of 2 cars at the same time.
 3.4 A user's current listing details shall be listed on their Profile page.
 3.5 A user's listing history shall be displayed on their Profile page.
 4. **Browsing Rental Listings**  
 4.1 Users can filter vehicles that show up by certain attributes, such as: manufacturer, model, year, and color.  
 4.2 Users can search for specific rental companies, and access their profiles to see their listings.
 5. **Registration of Rental Companies**  
 5.1 After registration, logged-in users can request to be recognized as rental businesses, to receive the right to create (and delete) their own listings.  
 5.2 To apply for this recognition, users should supply their business ID number, owner's full name, and one (or more) store locations.  
 5.3 These requests are to be handled by the System Admins, and should be approved or rejected within a week of the original request.  
 6. **Creating Rental Listings**  
 6.1 To create a listing, Rental Users should go their Profile page, and click on the Create Listing button.  
 6.2 A listing will only be created once the Rental User has specified the car's details, and verified its' ownership.  
 6.3 A full history of a company's listings will be displayed on the company's Profile page.  
 7. **User-friendly Website Design**  
 7.1 The menu should be minimalistic.  
 7.2 The content should stand out.  
 7.3 Users should know exactly what each button does prior to pressing it.  
 8. **User Privacy**  
 8.1 User data should be protected, as it is private information.  
 9. **Customer Support**  
 9.1 The Help webpage will be available 24/7.  
 9.2 It will contain a Frequently Asked Questions (FAQ) section, to deal with the blunt of the possible issues that users may have.  
 9.3 A contact form can be filled in to directly contact a system admin who will provide users with more information.  
 9.4 A cellphone number will be displayed so that users can phone in at certain hours to talk and resolve any issues, misunderstandings, or fulfill any information needs that they may have.  
 
 
# External Interface Requirements (Klea)
### User Interface

GoDrive Albania software will be equipped with attractive, clear, consistent and responsive UI.
UI requirements are briefly mentioned below:

- Easy navigation  
- Simple interface  
- Responsive  
- Consistent UI elements  
- Feedback mechanism  
- Attractive layout  
- Strategic use of color and texture  
- Provide helpful information  
 
### Hardware Interface  
- Hardware required: none  
- Nature of the data: image data, text data, number data, date  
### Software Interface Requirements  

- Connection of the software with Operating System: GoDrive Albania software is developed for Android, iOS, Windows 7, Windows 8, Windows 10

### Communication Interface Requirements

- Communication standards and network server communication protocols: HTTP or HTTPS 
- Electronic forms: HTML forms to get feedback and data from the user  
- Message formatting: image based, text based, number based  
- Email  
- Communication security and encryption issues  

# Functional Requirements (Artea)
Functional requirements are the desired operations of a program, or system as defined in software development and systems engineering. It specifies the application functionality that the developers must build into the product to enable users to accomplish their tasks.

**Log in:**
- The administrator and employees can log in with their account and password.
- After logging in, they have the right to edit, add and delete information.
- Meanwhile, for a user there are two options.
- A new user must sign up. This will require to insert name, contact number, an email address and the creation of an 8-digit password.
- While an old user can log in with the profile he opened in the application before.

**Car & Reservation:**
- The system will allow staff to register new cars.
- The system will allow staff to update information of the car in need of modification.
- The system will allow staff to display all lists of cars.
- The system will allow staff to display all available car.
- Customer will be able to search the car name and then sort them by price or year model.
- By clicking on a specific car all the details will show up such as: Name and model with picture; Registration number; Fuel consumption; Insurance details; Cost; Availability; Previous feedbacks etc.
- The system will allow the customers to cancel reservation using reservation confirmation number.
- The system will also allow the employee to view every action made by customers.

**Calculate cost:**
- The user can calculate the cost for the renting process after selecting the car.
- The cost will be calculated using input and the cost information in the system such as: Time duration(days), car brand etc.

**Collect feedback from customer:**
- The user will be provided by a new tab where he can add feedback about the car and the service provided.
- Admin can read feedback and then decide to send it to the history of customer activities.
- Then every user can see the feedbacks.





# Non-functional Requirements (Deniz)
**Non-Functional System Requirements**
Non-Functional System Requirements
1. **Performance**: the system should be able to handle a certain number of users and respond within a specific time frame.  
1.1 Optimizing the algorithms and data structures: We should minimize the number of operations used to perform a task by optimizing the algorithms and data structures.   
1.2 Optimizing network usage: We should minimize the amount of data transmitted over the network and use low-sized data by optimizing network usage.    
1.3 Improving the database performance: We should use indexes and caching techniques to speed up database queries and reduce the number of databases calls to improve the database performance.  
1.4 Using optimized code: We should optimize the code by removing unnecessary code, reducing the number of function calls, and optimizing loops and conditionals to use optimized code.  
2. **Usability**: the system should be easy to use, intuitive, and provide clear and concise feedback to the users.  
 2.1 User-Centered Design: We should design the application with the user in mind by identifying the user's needs and preferences and creating a design that is intuitive, user-friendly, and easy to use with a user-centered design.  
 2.2 Simplify Navigation: We should ensure that the navigation is simple and easy to use by providing clear and concise labels and making sure that the user can easily find what they are looking for with simplified navigation.  
 2.3 Reduce Cognitive Load: We should avoid unnecessary complexity and information overload by simplifying the interface and providing only the information that is necessary to reduce cognitive load.  
 2.4 Consistent and Clear Design: We should maintain consistency throughout the design of the application by using clear and concise language and following consistent patterns in layout, color, and typography to achieve a consistent and clear design.  
3. **Security**: the system should have the necessary security measures in place to protect against unauthorized access, data breaches, and other security threats.  
 3.1 Secure Coding Practices: We should use secure coding practices, such as input validation, error handling, and proper authentication and authorization mechanisms, to prevent security vulnerabilities in the application with secure coding practices.  
 3.2 Strong Passwords: We should encourage users to create strong passwords and enforce password policies that require regular password changes and prohibit the use of weak passwords by promoting the use of strong passwords.  
 3.3 Use Encryption: We should use encryption to protect sensitive data, both in transit and at rest. This includes using secure protocols, such as HTTPS, and encryption algorithms, such as AES to use encryption.  
4. **Reliability**: the system should be able to function as intended without crashing or producing errors.  
 4.1 Continuous Integration and Deployment: We should use continuous integration and deployment practices to ensure that code changes are properly tested and integrated into the application without introducing new errors or issues with continuous integration and deployment.  
 4.2 Load Balancing: We should use load balancing techniques to distribute the workload across multiple servers to prevent overloading and system crashes by implementing load balancing.  
 4.3 Backup and Recovery: We should implement a backup and recovery plan to ensure that data is not lost in case of a system failure or data corruption by implementing backup and recovery.  
5. **Maintainability**: the system should be easy to maintain and update, with clear documentation and code structure.  
 5.1 Consistent Coding Practices: We should use consistent coding practices, such as naming conventions, code formatting, and commenting, to make it easier for developers to understand and modify the code by maintaining consistent coding practices.  
 5.2 Modular Architecture: We should use a modular architecture to break down the application into smaller, independent components that can be easily modified or replaced without affecting other parts of the application with modular architecture.  
 5.3 Documentation: We should provide comprehensive documentation, including user manuals, technical documentation, and code documentation, to help developers understand the application and make modifications more easily by providing documentation.  
6. **Scalability**: the system should be able to handle increasing amounts of data or users without compromising performance.  
 6.1 Horizontal Scaling: We will use horizontal scaling techniques, such as load balancing and auto-scaling, to distribute the workload across multiple servers and increase the capacity of the system.  
 6.2 Caching: We will use caching techniques to store frequently accessed data in memory and reduce the number of requests to the database or other external systems.  
 6.3 Stateless Architecture: We will use a stateless architecture, where each request is independent and does not rely on previous requests, to make it easier to scale horizontally.  
7. **Portability**: the system should be able to run on different platforms and environments.  
 7.1 Minimize Platform-Specific Code: We will minimize the use of platform-specific code and libraries and use cross-platform alternatives when possible.  
 7.2 Use Standard Protocols: We will use standard protocols, such as HTTP, SMTP, or FTP, to ensure that the application can communicate with other systems and services regardless of the platform or environment.  
 7.3 Test on Multiple Platforms: We will test the application on multiple platforms and environments to ensure that it works correctly and does not have any platform-specific issues.  
8. **Availability**: the system should be available for use at all times, with minimal downtime or scheduled maintenance.  
 8.1 Load Balancing: We will use load balancing techniques to distribute the workload across multiple servers and prevent any single server from becoming overloaded.  
 8.2 Automatic Scaling: We will use automatic scaling techniques, such as auto-scaling or elastic load balancing, to automatically adjust the system capacity based on demand and prevent overload or downtime.  
 8.3 Proactive Maintenance: We will perform proactive maintenance, such as regular system updates and patches, to prevent potential issues and reduce the risk of failures or outages.  
 8.4 Data Replication: We will use data replication techniques, such as mirroring or log shipping, to ensure that data is always available and up-to-date even in case of a failure or outage.  
9. **Compliance**: the system should comply with applicable laws, regulations, and standards.  
 9.1 Compliance Framework: We will implement a compliance framework, such as ISO/IEC 27001 or PCI DSS, that provides guidelines and requirements for information security and data protection.  
 9.2 Access Controls: We will implement access controls to ensure that only authorized users can access sensitive data or perform critical functions.  
 9.3 Data Protection: We will implement data protection techniques, such as encryption or data masking, to protect sensitive data and prevent unauthorized access or disclosure.  
 9.4 Security Testing: We will perform security testing, such as penetration testing or vulnerability scanning, to identify potential security issues or compliance gaps.  
 9.5 Regular Audits: We will conduct regular audits to assess the compliance of the application and identify potential issues or non-compliance areas.  
10. **Localization**: the system should support multiple languages, currencies, and cultural conventions.  
 10.1 Internationalization: We will implement internationalization techniques, such as Unicode support and date/time formatting, to ensure that the application can handle different languages and regions.  
 10.2 User Feedback: We will solicit feedback from users in different regions and languages to identify issues and opportunities for improvement in the localization of the application.  
 10.3 Cultural Adaptation: We will adapt the application to different cultures and regions by considering local customs, values, and preferences.  
 10.4 User Testing: We will conduct user testing with representatives from different regions and languages to ensure that the application is accessible and usable for all users.  
11. **Data Privacy**: the system should protect the privacy of sensitive user data and adhere to data protection laws.  
 11.1 Data Classification: We classify data based on its sensitivity level and implement appropriate controls and protections for each classification level.  
 11.2 Access Controls: We implement access controls to ensure that only authorized users can access sensitive data.  
 11.3 Data Anonymization: We anonymize data, such as by replacing identifiable information with pseudonyms, to prevent unauthorized access or disclosure.  
