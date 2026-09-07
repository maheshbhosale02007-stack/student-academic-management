# Acceptance Criteria Document

| ID | User Story | Acceptance Criteria |
|---|---|---|
| US-01 | Add Student | Required fields validate; unique student ID is enforced; record saves successfully; confirmation is shown. |
| US-02 | Search Student | Search accepts valid criteria; matching records are displayed; no-result state is clear; unauthorized data is hidden. |
| US-03 | Update Student | Authorized user can edit permitted fields; validation runs; changes save; updated data is displayed. |
| US-04 | Delete Student | Only authorized users can perform the action; confirmation is required; record is removed/deactivated according to policy; action is logged. |
| US-05 | Add Course | Required course fields validate; unique course code is enforced; course saves successfully. |
| US-06 | Update Course | Authorized user can edit course details; validation runs; changes persist. |
| US-07 | Assign Students | Valid students and courses can be selected; duplicate enrollment is prevented; assignment is saved. |
| US-08 | View Course | User can view permitted course details; unavailable data is not exposed. |
| US-09 | Record Attendance | Faculty selects course/date; students are displayed; attendance can be marked; records save; duplicate entry is prevented. |
| US-10 | View Attendance | Student sees only their records; attendance percentage is displayed correctly; history can be reviewed. |
| US-11 | Attendance Report | Authorized user selects scope/date; report contains correct attendance data; report can be viewed/exported. |
| US-12 | Enter Marks | Authorized faculty selects course/assessment; marks are validated; valid marks save successfully. |
| US-13 | Update Marks | Authorized user can edit allowed marks; new values validate; changes are logged. |
| US-14 | Calculate Grades | Configured grading rules are applied consistently; invalid marks are rejected; calculated grade is displayed. |
| US-15 | Result Sheet | Verified results are included; unauthorized drafts are excluded; result sheet is generated successfully. |
| US-16 | User Login | Login page loads; valid credentials work; invalid credentials show an error; successful login opens the dashboard. |
| US-17 | Logout | Logout terminates the session; protected pages require authentication afterward. |
| US-18 | Password Reset | Reset flow validates user identity; new password meets policy; user can sign in with the new password. |
| US-19 | Role-Based Access | Each role receives only permitted features/actions; unauthorized operations are blocked. |
| US-20 | Attendance Alert | Alert is triggered according to configured threshold; correct student receives it; duplicate alerts are controlled. |
| US-21 | Examination Notification | Notification contains relevant examination information; eligible users receive it. |
| US-22 | Result Notification | Notification is sent when results are published; student can access the published result. |
| US-23 | Student Report | Authorized user can select a student; report contains permitted information; report is generated. |
| US-24 | Attendance Report | Authorized faculty can select a course/date range; report is accurate; output is readable. |
| US-25 | Performance Report | Authorized user can select required scope; report reflects verified marks/results. |
| US-26 | Course Report | Authorized user can select a course; report contains permitted enrollment and academic information. |

## Definition of Done

A user story is Done when all acceptance criteria pass, testing is completed, the implementation is reviewed, and the feature is demonstrable.
