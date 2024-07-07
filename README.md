Overview
This README file provides a detailed explanation of the JSON format for a resume of an individual named U Sriram. The JSON captures all the key details from the resume, including contact information, education, internships, projects, technical skills, assessments/certifications, extra-curricular activities, personal interests/hobbies, and instant messaging details.

JSON Structure
Root Object
The root object contains the following properties:

name: A string representing the name of the individual.
contact: An object containing contact information.
location: An object containing current and permanent addresses.
personal_details: An object containing personal details.
education: An array of objects, each representing an educational qualification.
internships: An array of objects, each representing an internship experience.
projects: An array of objects, each representing a project.
technical_skills: An array of strings, each representing a technical skill.
assessments_certifications: An array of objects, each representing an assessment or certification.
extra_curricular_activities: An array of strings, each representing an extra-curricular activity.
personal_interests_hobbies: An array of strings, each representing a personal interest or hobby.
ims: An object containing instant messaging details.
Properties
name
Type: String
Description: The full name of the individual.
contact
Type: Object
Properties:
phone: An array of strings representing the phone numbers.
email: An array of strings representing the email addresses.
linkedin: A string representing the LinkedIn profile URL.
location
Type: Object
Properties:
current: A string representing the current address.
permanent: A string representing the permanent address.
personal_details
Type: Object
Properties:
gender: A string representing the gender of the individual.
marital_status: A string representing the marital status of the individual.
date_of_birth: A string representing the date of birth of the individual.
languages: An array of strings representing the languages known by the individual.
education
Type: Array of Objects
Object Properties:
institution: A string representing the name of the institution.
duration: A string representing the duration of the education.
degree: A string representing the degree obtained.
cgpa (optional): A string representing the CGPA.
percentage (optional): A string representing the percentage obtained.
internships
Type: Array of Objects
Object Properties:
company: A string representing the name of the company.
duration: A string representing the duration of the internship.
role: A string representing the role during the internship.
key_skills: An array of strings representing the key skills acquired or used during the internship.
description: A string describing the responsibilities and experiences during the internship.
projects
Type: Array of Objects
Object Properties:
name: A string representing the name of the project.
duration: A string representing the duration of the project.
team_size: An integer representing the size of the project team.
key_skills: An array of strings representing the key skills used in the project.
description: A string describing the project.
technical_skills
Type: Array of Strings
Description: An array representing the technical skills possessed by the individual.
assessments_certifications
Type: Array of Objects
Object Properties:
name: A string representing the name of the assessment or certification.
key_skills: An array of strings representing the key skills acquired or demonstrated.
extra_curricular_activities
Type: Array of Strings
Description: An array representing the extra-curricular activities the individual is involved in.
personal_interests_hobbies
Type: Array of Strings
Description: An array representing the personal interests and hobbies of the individual.
ims
Type: Object
Properties:
skype: A string representing the Skype ID.
