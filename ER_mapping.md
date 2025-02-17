#############------ Entity Relationship Diagram --------###########

Entities-

1 User
user_id (Primary Key)
username
password
email
role (Member/Trainer/Admin)

2 Member
member_id (Primary Key)
user_id (Foreign Key)
name
contact_info
membership_id (Foreign Key)

3 Trainer
trainer_id (Primary Key)
user_id (Foreign Key)
name
specialization
contact_info

4.Class
class_id (Primary Key)
class_name
schedule
trainer_id (Foreign Key)

5 Membership
membership_id (Primary Key)
plan_name
duration
price

6 Attendance
attendance_id (Primary Key)
member_id (Foreign Key)
class_id (Foreign Key)
date



Relationships -
User can be either a Member or a Trainer.
Member can enroll in multiple Classes.
Trainer can conduct multiple Classes.
Member can have one Membership.
Attendance records link Members to Classes.

Flow Diagram -
User Registration/Login: Users (members/trainers) register and log in.
Membership Management: Members select and manage their memberships.
Class Scheduling: Trainers create and manage class schedules.
Class Enrollment: Members enroll in classes.
Attendance Tracking: Attendance is recorded for each class.
Admin Management: Admins manage users, memberships, and classes.
