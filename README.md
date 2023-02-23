# Jupyter Python Script to Reverse a User's Name

This Jupyter Python script takes input from the user in the form of their first and last name and then prints their full name and their name in reverse order.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

- Fork this repository to your own GitHub account.
- Clone the forked repository to your local machine.
- Create a new branch for your feature or bug fix: `git checkout -b your-feature-or-bug-fix-name`
- Make changes to the codebase and commit them: `git commit -am 'Add some feature or fix some bug'`.
- Push your changes to your forked repository: `git push origin your-feature-or-bug-fix-name`.
- Create a pull request from your forked repository to this repository.
- Make sure to write a clear and concise description of the changes you've made in the pull request description.

Thank you for contributing to this project!

## Prerequisites

To run this script, you should have Python 3 and Jupyter installed on your computer.

## Input

The script takes two inputs from the user:

1. First name
2. Last name

## Output

The script prints the following two messages on the screen:

1. Your full name is: [first name] [last name]
2. Your name in reverse is: [reversed name]

For example, if the user enters "John" as their first name and "Doe" as their last name, the output will be:

```
Your full name is: John Doe
Your name in reverse is: eoD nhoJ
```

## Note

- The script uses Python's string slicing feature (`[::-1]`) to reverse the user's name.
