## Python Address Book with Advanced Features

This project enhances the previous Python Address Book tasks with additional functionalities, including:

- **Birthday Management:**
  - `add-birthday` command to add a birthday to a contact.
  - `show-birthday` command to display a contact's birthday.
  - `birthdays` command to list upcoming birthdays for the next week.
- **Data Validation:**
  - Validates birthday format (DD.MM.YYYY).
  - Validates phone number format (10 digits).
- **Graceful Exit:**
  - Handles `close` or `exit` commands to properly terminate the program.

### Installation

1.  Install Python 3.x if you haven't already.
2.  Download the provided code files.

### Usage

1.  Open a terminal or command prompt.
2.  Navigate to the directory containing the code files.
3.  Run the program using `python main.py`.
4.  Follow the prompts and commands to interact with the address book.

### Features

- **Add Contacts:**
  - Use `add [name] [phone]` to add a new contact or update an existing one.
- **Change Phone Number:**
  - Use `change [name] [old_phone] [new_phone]` to modify a contact's phone number.
- **Display Contacts:**
  - Use `phone [name]` to show a contact's phone numbers.
  - Use `all` to display all contacts in the address book.
- **Birthday Management:**
  - Use `add-birthday [name] [birthday]` to add a birthday to a contact.
  - Use `show-birthday [name]` to display a contact's birthday.
  - Use `birthdays` to list upcoming birthdays for the next week.
- **Greetings:**
  - Use `hello` to receive a greeting from the bot.
- **Exit:**
  - Use `close` or `exit` to terminate the program.

### Error Handling

- Input errors (invalid formats, missing data) are gracefully handled with informative messages.
- Data validation ensures the integrity of contact information.

### Testing

- Manually test the commands with various scenarios to ensure proper functionality and error handling.
- Consider adding automated tests for comprehensive coverage.

### Conclusion

This enhanced address book demonstrates the practical application of object-oriented programming and data validation in Python. It provides a solid foundation for building more complex and interactive applications.
