
# ****Passenger Registration****

To create a new passenger, the following information is required:

1. **Name**: The full name of the passenger.
    - Type: Text
    - Required field
2. **Passport**: The passport number of the passenger.
    - Type: Text
    - Required field
3. **Email**: The email address of the passenger.
    - Type: Text (valid email format)
    - Required field
4. **Birthdate**: The birthdate of the passenger.
    - Type: Date
    - Required field
5. **Gender**: The gender of the passenger. (Choose one from the following options)
    - Male
    - Female
    - Non-binary
    - Other

All fields mentioned above are mandatory.

Additionally, the following fields will be automatically generated and tracked:

- **ID**: Unique identifier for the passenger in the database.
- **UUID**: Universally Unique Identifier (UUID) assigned to the passenger and exposed publicly.
- **Created Date**: Date and time when the passenger record was initially created.
- **Updated Date**: Date and time when the passenger record was last updated.
- **Version**: Version number indicating the current version of the passenger record.

Please ensure that all required fields are provided when creating a new passenger. The automatically generated fields will be managed by the system.
