[README.md](https://github.com/user-attachments/files/34429910/README.md)
# ECHO: Every Voice Matters

ECHO is a free survey tool for school special education teams. It helps teams hear from the people closest to a student before an IEP meeting or a special education reevaluation: the student, the family, and the student's general education teachers.

Too often, students and families are asked general questions in a room full of people at the meeting itself. ECHO gives them a chance to share their views ahead of time, in their own words, on their own schedule.

**Live tool:** https://statusgrow.github.io/Echo/

## What ECHO Does

1. A school staff member copies the ECHO prompt and uses it with a district-approved AI tool and a **redacted** IEP (personal details removed).
2. The AI returns short "survey code" describing the student's IEP goals, supports, and services in plain language. The code never contains the student's name.
3. The staff member pastes that code into ECHO, which builds three tailored surveys:
   - **Student survey:** mostly tapping, with read-aloud buttons and picture-face ratings for younger students.
   - **Parent/guardian survey:** plain language, works on a phone, asks what the family notices at home.
   - **Teacher survey:** asks about progress, supports in class, and how the student's needs affect access and progress in general education.
4. Each survey ends with a short written summary the team can use in IEP and reevaluation paperwork.

Printable paper versions are also available for anyone who prefers paper or does not have reliable access to a device.

## Privacy and Safety

ECHO was designed so that it stores nothing and collects nothing.

- **No accounts, no logins, no server, no database.** ECHO is a single static web page.
- **Never asks for passwords or payment information.**
- **Student names are never put in survey links** or sent to an AI tool. A first name is typed on the device only to personalize the questions, and it disappears when the page closes.
- **Answers stay on the device** until the person chooses to print, copy, or email them. Emails are sent from the person's own email account; ECHO does not send anything itself.
- **Survey links carry only de-identified survey content** (goals and supports in plain language), and that content sits after the "#" in the link, which browsers do not send to the web server.

ECHO loads fonts from Google Fonts. The optional "Say it instead" voice typing button uses the browser's built-in speech recognition, which in Chrome may be processed by Google.

Districts should review ECHO under their own student privacy policies before use, including which AI tool staff may use with redacted IEP content.

## Who Made It

ECHO was created by a school psychologist in southwest Michigan for use by special education teams. It is shared freely in the hope that it helps more students and families be heard.

## Files in This Repository

- `index.html`: the complete ECHO tool.
- `google81f33658f0daeae2.html`: a Google Search Console ownership verification file. It contains no student information.
