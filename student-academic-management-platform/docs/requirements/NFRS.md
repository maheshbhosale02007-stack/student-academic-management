# Non-Functional Requirements Specification (NFRS)

## Security

- NFR-01: Passwords must never be stored as plain text.
- NFR-02: Role-based access control must be enforced on protected operations.
- NFR-03: Sensitive data must be transmitted over HTTPS in production.
- NFR-04: Important security and record-changing actions should be auditable.

## Usability

- NFR-05: Common tasks should require minimal navigation.
- NFR-06: Forms should provide clear validation messages.
- NFR-07: The interface should be responsive for desktop and mobile screens.
- NFR-08: Terminology should be consistent across the platform.

## Reliability

- NFR-09: The system should handle temporary failures gracefully.
- NFR-10: Database backups should be performed according to institutional policy.
- NFR-11: Invalid transactions should not partially update academic records.

## Performance

- NFR-12: Typical dashboard and record searches should return promptly under normal load.
- NFR-13: Report generation should remain usable for large student datasets.

## Scalability

- NFR-14: The architecture should support increasing students, courses, users, and academic years.
- NFR-15: Database design should avoid unnecessary duplication.

## Maintainability

- NFR-16: Code should use modular components and clear naming.
- NFR-17: APIs should be documented.
- NFR-18: Automated tests should cover critical workflows.

## Availability

- NFR-19: Production availability targets should be defined by institutional requirements.
- NFR-20: The system should support monitoring and error logging.
