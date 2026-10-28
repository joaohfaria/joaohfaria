# João Henrique

I'm learning software development with a focus on Python and back-end, building projects to strengthen my programming fundamentals.

## Currently learning

- Python fundamentals
- Web development with Flask (routing, templates, sessions)
- SQL and SQLite
- Authentication and password hashing
- Git and GitHub
- Code organization and clean code practices

## Projects

### Oficina — Online Booking System
A web application that lets customers of a car repair shop book a service online, replacing phone calls written down by hand.

Built with Python, Flask, SQLite and HTML. Customers pick a service and an available time slot; the server validates the request before saving it — no past dates, business hours only (Mon–Fri, with a lunch break), no double booking, and no service that the shop doesn't offer. Staff log in to see the schedule, with passwords stored as hashes.

Available time slots are generated from the shop's opening hours, so changing the schedule doesn't require changing code.

I'm building this for the shop where I currently work, so the rules come from how the business actually runs.

### DevManager
A command-line task manager built with Python.

Tasks are created with an ID, title, description, priority and status, and are stored in a JSON file so they persist between runs. Includes input validation and error handling for invalid input and missing data files.

The project started with in-memory storage only. After noticing that tasks were lost when the program closed, I implemented persistence with JSON — which led me to learn file handling and error handling in practice.

## Next steps

- Deployment
- REST APIs and JSON endpoints
- Automated testing with pytest
- JavaScript on the front-end
