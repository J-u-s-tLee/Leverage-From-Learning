# Leverage From Learning (LFL)

---

## Overview
Leverage From Learning (LFL) is a one-day event organized by students, dedicated to students and individuals interested in leveraging learning. This repository contains the information system designed to coordinate lectures, workshops, and coffee breaks for all attending participants and speakers.

---

## System Entities and Logistics

The information system models several entities to manage event operations, activities, and attendees:

### Attendees
*   **Person**: The base profile for everyone, tracking an identifier number, name, age, job description, and food restrictions.
*   **Participants**: Attendees who must enroll in the event, which generates a registration containing the admission date and price.
*   **Speakers**: Have a nationality and place of residence. They are divided into two distinct roles:
    *   **Lecture Speakers**: Professionals delivering lectures who may require travel and accommodation. The system tracks their travel (departure/arrival times, start/end locations, price) and hotel stays (name, address, available rooms, price).
    *   **Workshop Speakers**: Professionals leading workshops. A workshop speaker may be responsible for multiple workshops, but each workshop must have strictly one speaker.

### Activities
Every activity is assigned a room, a start time, and an end time. The system coordinates three main types of activities:
*   **Lectures**: Feature a title (theme of the event) and a maximum capacity.
*   **Workshops**: Feature a title, capacity, and an associated price for the organization.
*   **Coffee Breaks**: Two coffee breaks occur during the event, each with an associated organizational price. Attendees have different menus at their disposal, tracking meat, veggie, vegan, and gluten-free dietary needs.

### Attendance Permissions
*   Participants and Lecture Speakers can attend workshops, lectures, and coffee breaks.
*   Workshop Speakers are permitted to attend only coffee breaks and workshops.

---

## Academic Context

This project was developed for the Information Systems Engineering (Engenharia de Sistemas de Informação) course - 2024/2025. 
*Master in Bioengineering - Biomedical Engineering, FEUP (Faculdade de Engenharia da Universidade do Porto)*.
