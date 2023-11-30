# AngularJS Code Examples

This repository contains two separate AngularJS code examples:

1. **Password Strength Meter**
   - File: `password-strength.html`
   - This code demonstrates a password strength meter that dynamically assesses the strength of a password based on predefined criteria.

2. **Date Range Picker**
   - File: `date-range-picker.html`
   - This code features a date range picker with custom validation to ensure the end date is later than the start date.

## Password Strength Meter

### How it Works

The password strength meter evaluates the entered password against the following criteria:

- Minimum length of 8 characters.
- Presence of at least one lowercase letter.
- Presence of at least one uppercase letter.
- Presence of at least one numeric digit.
- Presence of at least one special character.

The strength is categorized as follows:

- Weak: Length less than 8 characters or lacking variety.
- Medium: Length between 8 and 12 characters.
- Strong: Length greater than 12 characters.

### Implementation Details

- The AngularJS app is named `passwordStrengthApp`.
- The controller is named `PasswordStrengthController`.
- The `checkPasswordStrength()` function dynamically updates the password strength indicators based on the entered password.

## Date Range Picker

### How it Works

The date range picker ensures that the end date is later than the start date. It includes:

- Start date and end date input fields.
- Custom validation to display an error message if the date range is invalid.

### Implementation Details

- The AngularJS app is named `dateRangeApp`.
- The controller is named `DateRangeController`.
- The `isDateRangeInvalid()` function checks if the end date is earlier than or equal to the start date.
- The `validateDateRange()` function is triggered on date changes.

## Author

- wizcoderx

Feel free to explore, modify, and use these examples in your AngularJS projects!
