# Functional Requirements Specification (FRS)

## 1. Authentication and Authorization

- FR-01: The system shall allow authorized users to sign in.
- FR-02: The system shall assign users a role.
- FR-03: The system shall restrict features according to role.
- FR-04: The system shall allow users to sign out.

## 2. Student Registration

- FR-05: Authorized staff shall create student records.
- FR-06: The system shall validate required student fields.
- FR-07: The system shall prevent duplicate student identifiers.
- FR-08: Authorized staff shall update student records.
- FR-09: Authorized users shall search student records.

## 3. Course Registration

- FR-10: Administrators shall create and update courses.
- FR-11: Students shall be associated with their registered courses.
- FR-12: The system shall prevent invalid duplicate enrollments.

## 4. Attendance

- FR-13: Faculty shall view assigned course/student lists.
- FR-14: Faculty shall record attendance by course and date.
- FR-15: The system shall calculate attendance percentages.
- FR-16: Authorized users shall view attendance history.
- FR-17: The system shall prevent unauthorized editing of attendance.

## 5. Examination and Results

- FR-18: Authorized staff shall record examination marks.
- FR-19: The system shall validate mark ranges.
- FR-20: The system shall calculate applicable totals/grades according to configured rules.
- FR-21: Authorized staff shall publish verified results.
- FR-22: Students shall view published results only.

## 6. Reports

- FR-23: The system shall generate student academic reports.
- FR-24: Reports shall include relevant registration, attendance, and result information.
- FR-25: Authorized users shall be able to export reports.

## 7. Audit and Administration

- FR-26: Important record changes shall be logged.
- FR-27: Administrators shall manage authorized users.
- FR-28: The system shall record timestamps for important operations.

## Acceptance Criteria

Each requirement is considered complete when it is implemented, validated with test cases, and accessible only to the intended roles.
