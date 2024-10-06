
# Student Registration Automation System

The Student Registration Automation System is designed for AIMS-Senegal to streamline the registration process for students. This Python program automates the creation of unique student registration numbers based on specific criteria.

The registration number is generated using the following mechanism:

### Identification Fields:

The first three consonants of the student's last name are extracted to form the first part of the registration number.
The first three letters of the student's first name form the second part. If either name has fewer than three letters, the program replaces missing letters with "X".


### Unique identifier

To ensure uniqueness, a third field consisting of a three-digit number is appended to the registration number. This number represents the order of registration, allowing for differentiation between students with similar names. For example, if two students named Gnansounou Marcel and Gnonas Marcellin register, their identifiers will be GNNMAR001 and GNNMAR002, respectively.


## Contributing

1. Agnes IKUZWE
2. Denyse AKAYEZU
3. Ndim Handson NSANI
4. Vincent ONDENG




