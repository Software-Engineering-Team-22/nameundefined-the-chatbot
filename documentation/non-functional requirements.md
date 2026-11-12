## Non-Functional Requirements



### Performance and Scalability
- The system shall display a response to a user's message within 60 seconds under normal operating conditions.

- The website's elements shall load within 5 seconds of user's interaction.

- The system shall be able to respond up to 50 users at a time without the degradation of performance.
  
- The system shall be able to process and interpret standard ASCII characters and symbols within user inputs.
  
- The system shall remain operational under load of processing 50 concurrent messages a second.

- The system shall be accessible on any device used to interact with the it.



### Reliability 

- The system shall maintain an uptime of at least 99% during scheduled operating hours.

- During any unscheduled maintenance hours the system shall go back online within 12 hours.

- The chatbot shall provide historically accurate and consistent responses based on its approved knowledge sources.



### Usability

- The system shall provide an intuitive and user-friendly interface that accommodates users with varying levels of technological experience."



  

### Availability 








### Security
- The system shall prevent unauthorised access to stored conversation histories.
 
- The system shall provide a mechanism for deleting stored conversation data where applicable.
 
- The system shall require authorised maintenance personnel to complete two-factor authentication before granting access to administrative functionality.

- The system shall encrypt data during transmission and storage to provide a basic level of security.

- The system shall validate user input to prevent malicious code or scripts from being executed.

- The system shall implement protection against common web application vulnerabilities.

- The system shall limit the size of user inputs to prevent excessive resource consumption.

- The system shall temporarily restrict requests from users who exceed predefined usage limits.
  
- The system shall restrict modifications to the chatbot's knowledge base to authorised personnel.

- The system shall ensure that software dependencies and components are regularly updated to address known security vulnerabilities.



### Legal and regulatory compliance
- The system shall comply with the UK General Data Protection Regulation (UK GDPR) and the Data Protection Act 2018 when collecting, processing and storing personal data.
 
- The system shall only collect personal information necessary for the operation of the chatbot.

- The system shall obtain user consent before using non-essential cookies where legally required.

- The system shall comply with the applicable requirements of the European Union Artificial Intelligence Act (EU AI Act), Regulation (EU) 2024/1689.



## Please read
 
- If the chatbot is for personal use or for a museum this might change. Private chats with our bot must obviously be private, if it is for public use in an exhibit that is a little less possible because it's a public place and a public tool. **(I don't think we will ever know the answer to that suggestion. I suggest we implement a sufficient level of security that will allow us to support both outcomes.)**

- If we ever need to or want to upgrade or change something about our bot it must be hassle free and we need to have a way to do it seamlessly. **(Already mentionued in previous requirements. perhaps this is redundant.)**

- If there is a problem, it has to be easily identifiable and fixed quickly. **(same as the previous one)**

- - The system shall adhere to industry-specific regulations and standards, ensuring legal compliance in data handling, accessibility, and operational practice. **(each requirement has been made atomic and testable as per Ben's instructions)**
