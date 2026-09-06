# 04 Product Backlog and Estimation

## Acceptance Criteria

| Story | Acceptance Criteria |
|---|---|
| US01 | Login page opens; registered user can enter credentials; valid credentials open the dashboard; invalid credentials show an error. |
| US03 | Required student fields are validated; a valid record is saved; duplicate/invalid data is handled with a suitable message. |
| US04 | Search accepts a relevant student identifier/name; matching records are displayed; no-match condition is shown clearly. |
| US05 | Existing details can be edited; required fields are validated; updated data is saved and visible after refresh. |
| US07 | Course details can be entered; required fields are validated; valid course is saved and displayed in the course list. |
| US08 | A course can be selected; eligible students can be assigned; assignment is saved and can be viewed later. |
| US09 | Faculty can select course and date; attendance can be marked; record is saved successfully; duplicate entry is prevented/handled. |
| US10 | Faculty can select course/date or relevant filters; attendance data is displayed; report can be generated. |
| US11 | Faculty can select a student/course; marks are validated; valid marks are saved; updated marks are reflected in the record. |
| US12 | Student can access own result; marks and grades are displayed correctly; unauthorized results are not shown. |
| US13 | Notification contains relevant academic information; intended users can view it; old notifications remain accessible when required. |
| US14 | Authorized user can select report type; report contains correct data; report can be viewed/exported. |

## Prioritized Product Backlog

| ID | Story | Epic | Priority | Points |
|---|---|---|---|---:|
| US01 | User Login | Authentication | High | 5 |
| US03 | Add Student | Student Management | High | 3 |
| US04 | Search Student | Student Management | High | 3 |
| US09 | Record Attendance | Attendance | High | 5 |
| US07 | Add Course | Course Management | High | 3 |
| US05 | Update Student | Student Management | Medium | 3 |
| US08 | Assign Students to Course | Course Management | Medium | 5 |
| US11 | Enter Marks | Marks | Medium | 5 |
| US10 | Attendance Report | Reporting | Medium | 5 |
| US12 | View Result | Marks | Medium | 3 |
| US02 | Logout | Authentication | Medium | 2 |
| US14 | Generate Academic Reports | Reporting | Low | 8 |
| US13 | Notifications | Notifications | Low | 5 |
| US06 | Delete Student | Student Management | Low | 3 |

## Story Point Estimation

| Points | Complexity | Typical Meaning |
|---:|---|---|
| 1 | Very Easy | Small change |
| 2 | Easy | Simple feature |
| 3 | Moderate | Normal feature with validation/testing |
| 5 | Difficult | Multiple screens, logic or dependencies |
| 8 | Very Difficult | Large feature needing considerable design/testing |
| 13 | Highly Complex | Should normally be split |

The team uses Planning Poker style discussion. Story points represent relative effort, not exact hours.
