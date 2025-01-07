# rareGroups (rareDoc)

rareGroups is an intelligent, group-focused messaging platform designed to streamline communication by targeting relevant audiences with tailored messages. This application allows users to join specific groups, create unique profiles, and receive targeted, meaningful messages based on their profile data. With AI-powered message parsing and filtering, rareGroups ensures that only the most relevant information reaches the intended audience.

# Adding Members to group
![image](https://github.com/user-attachments/assets/91640174-f021-4a34-86c5-efc0c576610a)

# Filter Members on Command
![image](https://github.com/user-attachments/assets/e526da05-4072-4d6e-a4b8-aceb49c79452)

# Sending Mail
![image](https://github.com/user-attachments/assets/92699ee8-2339-416d-9dfc-d0b6705a6096)

![image](https://github.com/user-attachments/assets/624952e9-228e-4a2b-950f-b17c6804e1b3)

## Features

- **Dynamic Group Profiles**: Users can create detailed group-specific profiles with custom fields, such as academic details for college groups or professional details for workgroups.
  
- **Targeted Messaging**: Send messages to specific profiles based on pre-defined filters (e.g., "Send message to all CSE students with CGPA > 7"). This allows group admins to target relevant members effectively.

- **Seamless User Interaction**: The platform offers an intuitive user interface to join groups, complete profiles, and engage in group conversations with ease.

- **AI-Powered Message Parsing**: Integrated with AI to parse messages and extract relevant tags and profile filters, enhancing the efficiency of communication.

- **Role-Based Communication**: Admins can send messages to specific roles or filter messages based on custom profile tags.

## Tech Stack

- **Backend**: Java with Spring Boot framework for RESTful API development, enabling seamless communication between the frontend and the database.
- **Database**: MySQL, with Spring Data JPA for ORM management and relational data handling.
- **Frontend**: HTML, CSS, and JavaScript for responsive and user-friendly design.
- **AI Integration**: Utilizes **Google Gemini API** for natural language processing (NLP) and message filtering.
- **Version Control**: Git for code versioning and project management.

## Getting Started

Follow these steps to get the project running locally:

### Prerequisites

- Java 11 or higher
- Spring Boot
- MySQL
- Google Gemini API credentials

### Clone the Repository

```bash
git clone https://github.com/MrRare/RareGroups.git
cd rareGroups
