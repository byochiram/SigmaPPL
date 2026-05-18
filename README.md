# SigmaPPL

SigmaPPL is a web-based academic course registration system developed as a group project for the Software Engineering Project course in the 5th semester at Informatics, Universitas Diponegoro.

The system is inspired by university academic information systems, where students submit their IRS (Isian Rencana Semester) at the beginning of each semester and academic advisors review the submitted course registration.

## Live Demo

https://sigmappl-production.up.railway.app

## Features

### Student
- Submit IRS for the active semester
- Select courses based on available schedules
- Prevent schedule conflicts
- Prevent course selection beyond the allowed SKS limit
- Request IRS changes or cancellation
- View and print approved IRS history

### Academic Advisor / Lecturer
- View advised students
- Filter students by cohort and IRS status
- Review student IRS submissions
- Approve submitted IRS
- Grant permission for IRS changes
- Grant permission for IRS cancellation
- View student IRS history
- Print approved IRS data

## My Contribution

In this group project, I was responsible for the Academic Advisor / Lecturer module.

My main contributions included:

- Developed the frontend and backend for the Academic Advisor role
- Built the advised-student list page
- Implemented student filtering and search
- Created the IRS approval flow
- Implemented permission flow for IRS changes and cancellation
- Built student IRS history pages
- Added print functionality for approved IRS data
- Supported bug fixing and deployment preparation

## Tech Stack

- Laravel
- PHP
- MySQL
- Blade
- Tailwind CSS
- Bootstrap
- JavaScript
- Vite
- Railway

## Demo Account

| Role | Email | Password |
|---|---|---|
| Academic Advisor / Lecturer | agusdwi@lecturer.com | agus123 |

## Project Context

This project was developed as a team assignment for the Software Engineering Project course. The system focuses on simulating the academic course registration workflow between students and academic advisors.

## Disclaimer

This project is an academic simulation project and is not an official Universitas Diponegoro academic system.
