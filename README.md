# User Story

```
As a manager
I want to generate a webpage that displays my team's basic info
so that I have quick access to emails and GitHub profiles
```

## Classes

`Employee`, `Manager`, `Engineer`, `Intern`.
The tests for these classes in the `tests` directory must pass.

The first class is an `Employee` parent class with the following properties and
methods:

- name
- id
- email
- getName()
- getId()
- getEmail()
- getRole() // Returns 'Employee'

The other three classes will extend `Employee`.

In addition to `Employee`'s properties and methods, `Manager` will also have:

- officeNumber

- getRole() // Overridden to return 'Manager'

In addition to `Employee`'s properties and methods, `Engineer` will also have:

- github // GitHub username

- getGithub()

- getRole() // Overridden to return 'Engineer'

In addition to `Employee`'s properties and methods, `Intern` will also have:

- school

- getSchool()

- getRole() // Overridden to return 'Intern'

### npm run test

Outcome results of test

<img src ="assets\testRun_pass.png" width ="900">

### User input

The project must prompt the user to build an engineering team. An engineering
team consists of a manager, and any number of engineers and interns.

The way the user enters the information is by using inquirer thru node CLI

### Roster output

The project must generate a `team.html` page in the `output` directory, that displays a nicely formatted team roster. Each team member should display the following in no particular order:

- Name

- Role

- ID

- Role-specific property (School, link to GitHub profile, or office number)

## Bonus

- Use validation to ensure that the information provided is in the proper expected format.

- Add the application to your portfolio.

## Submission on BCS

You are required to submit the following:

- The URL of the GitHub repository

- A video demonstrating the entirety of the app's functionality
