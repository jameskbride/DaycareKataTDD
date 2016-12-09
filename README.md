# Daycare Kata
In this exercise you will build daycare management system. It will allow you to enroll children, hire the appropriate number of teachers, and insure the daycare center is profitable.  The point of the kata is to provide a larger than trivial exercise that can be used to practice TDD.  A significant portion of the effort will be in determining what tests should be written, and more importantly, written next.

## User Stories

### Enroll children
The daycare center can enroll children between 6 weeks and 12 years of age.

When a child is enrolled they are placed within one of the following age groups:
* Infant: 6 weeks to 18 months
* Toddler: 18 months to 3 years
* Preschooler: 3 years to 5 years
* Schoolagers: 5 years to 12 years

When a child is enrolled the system will display "SUCCESSFULLY ENROLLED <AGE_GROUP>" where <AGE_GROUP> is the group in which the child was enrolled.  If a child is too young then the system will display "UNABLE TO ENROLL".

*As the Owner*
*In order to make a profit*
*I want to enroll children*

### Meet Licensing Requirements
In order to operate as a childcare provider businesses must follow the rules dictated by a Licensing Agency.
* Infant: max group size of 12
* Toddler: max group size of 16
* Preschooler: max group size 28
* Schoolagers: max group size of 36

*As the Owner*
*In order to follow the law*
*I want to meet Licensing requirements*


### Be Profitable

*As the Owner*
*In order to continue business operations*
*I want to make a profit*
