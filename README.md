# assign-mentor

# Please check out this netlify URL for access the APIs using front end

https://assign-mentor-task.netlify.app/

Please refer the below endpoint documentation 

#Home:

API:https://assign-mentorapi.herokuapp.com/

Home get method endpoint of API

#Get All Students:

End point :https://assign-mentorapi.herokuapp.com/students/

Get method to fetch all the students

#Get All Mentors:

End point :http://assign-mentorapi.herokuapp.com/mentors/

Get method to fetch all the Mentors

#Create a Student:

Endpoint :https://assign-mentorapi.herokuapp.com/students/

Post method to create a student

Body:
{
  "id": 107,
  "student_name": "swetha",
  "student_email": "swetha@gmail.com"
}

#Create a Mentor:

Endpoint :https://assign-mentorapi.herokuapp.com/mentors/

Post method to create a mentor

Body:
{
  "id": 4,
  "mentor_name": "ganesh",
  "skill": "electron.js"
}

#Students for a particular mentor:

endpoint :http://assign-mentorapi.herokuapp.com/students/mentor/:id

Get method to fetch all the students for particular mentor

#Update mentor for student:

Endpoint :https://assign-mentorapi.herokuapp.com/students/:id

Put Method to update/add a mentor for a particular student with student id

Body:
{
  "mentor_id": 2
}

#Student without Mentor:

Endpoint :https://assign-mentorapi.herokuapp.com/students/withoutmentor/

Get method to fetch all the students with no mentor

#Update Mentor for multiple student:

Endpoint :https://assign-mentorapi.herokuapp.com/mentors/assignmentor/:id

Put method to update mentor mapping for multiple students using mentor id..inputs are students id

Body:
[
  104,
  105
]
