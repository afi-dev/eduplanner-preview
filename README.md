# EduPlanner — EPSI schedule, improved by a student, for students.

**EPSI**'s unofficial student-designed schedule that offers a smarter, more intuitive and visually refined alternative to the official schedule system. With features such as automated course reminders, real-time change alerts and an elegant, user-friendly interface, it streamlines time management for EPSI students.


> [!NOTE]  
> This project is **unofficial** and in no way affiliated with EPSI. The features and activities offered are not related to [EPSI](https://www.epsi.fr/), and this project is not directly supported by the school. It is an independent initiative, developed by a student, aimed at improving the timetable management experience.


> [!IMPORTANT]  
> This project is currently in **active development**. Some features may be in the process of being implemented and **bugs** may be encountered. I am actively working on EduPlanner. Please share your feedback to help me make this application even better.

![eduplanner_banner_github](https://github.com/user-attachments/assets/ea3b1802-ea9b-42d3-aa39-e6a4fce3d280)

# Why EduPlanner ?

The goal of this project is to provide an alternative to the current schedule system used by the **EPSI** higher education institution, which is often criticized for being unintuitive, visually unappealing, and lacking practical features for students. The official schedule suffers from poor readability and limited usability, making daily planning cumbersome and time-consuming. This project aims to address these shortcomings by delivering a reimagined and enhanced unofficial version of the schedule. Designed by a student, this application focuses on a more user-friendly and visually appealing interface, allowing users to easily access their courses while benefiting from additional features. These include automatic reminders for upcoming classes, notifications for last-minute schedule changes, and personalized tools to better organize their time. The ambition of this project is to simplify students' daily routines while providing a superior user experience tailored to their needs and expectations. Although not officially affiliated with EPSI, this solution leverages available data to offer a reliable, practical, and modern alternative to the existing scheduling system.

# Features

The EduPlanner for EPSI application has been developed to improve student schedule. Here's an overview of the main features:

- Intuitive, modern interface
The application's interface is clear, elegant and easy to navigate. Unlike the official tool, which often lacks legibility, the application allows students to consult their timetable in a fluid and pleasant way, facilitating daily organization.

- Automatic reminders
Students receive automatic notifications before each class, so they never forget a session. These reminders can be customized according to the user's preferences, by choosing the ideal time to be alerted before each lesson. This feature enables students to better manage their schedules and avoid forgetting.

- Real-time change alerts
In the event of a timetable change, course cancellation or room relocation, the application sends real-time alerts, ensuring that students are always informed of last-minute adjustments. A history of changes is also available, making it easy to track the evolution of the timetable.

- Overview of upcoming courses
The application offers a complete overview of courses scheduled for the coming days. This feature allows students to consult their schedule in advance, with the option of filtering courses by date or type to better organize their day.

# How does it work?

**EduPlanner** is a **Next.js** application designed to retrieve **EPSI**'s schedule data. Due to the lack of a public API provided by EPSI, the application uses a web scraper (a bot) to fetch upcoming classes directly from the official schedule website. The bot logs in using a student's account credentials, allowing it to access and analyze the schedule data. It then updates an independent database, ensuring that any changes to the courses (such as room changes, cancellations, or time adjustments) are automatically handled and reflected in the application. The web application can be installed as a Progressive Web App (PWA), enabling users to receive notifications about upcoming courses. This allows students to stay up-to-date with any changes and helps them better manage their schedules in real-time.

# How to Deploy EduPlanner

## Requirements

Before deploying EduPlanner, it’s important to consider a few key factors to ensure the application works as expected.

### Login credentials for one or more student accounts

> [!IMPORTANT]
>
> To function properly, the application requires user-specific login credentials. This means that the credentials of a particular student need to be used to access the schedule data. If the class shares a similar schedule, one set of credentials will be sufficient. However, if there are variations in the schedule based on different programs or courses for certain students in the class, you will need to provide the credentials of multiple students. This way, you can retrieve several schedules based on the specific program or course type of each student.

# License

This project is licensed under the **Mozilla Public License 2.0**. You are free to use, modify, and distribute the code under the terms of this license. For more details, please refer to the **LICENSE** file in the repository.
