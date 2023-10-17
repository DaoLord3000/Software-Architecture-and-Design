# ADR 1: Implementing Biometric Authentication

## Status
Proposed

## Context
We are facing security and authentication challenges in our attendance register system. Current authentication methods are vulnerable to unauthorized access, leading to potential data breaches.

## Decision
We propose implementing biometric authentication (fingerprint recognition) for users. This will enhance security and streamline the attendance tracking process.

## Consequences
Easier: Enhanced security, reducing the risk of unauthorized access.
More Difficult: Implementation and integration of biometric authentication may require additional development effort and hardware procurement.

# ADR 2: Transitioning to a Cloud-Based Database

## Status
Accepted

## Context
Our current on-premises database is causing performance issues, especially during peak attendance registration periods. This hampers the system's reliability and scalability.

## Decision
We have decided to transition to a cloud-based database solution to improve system performance, scalability, and reliability. We will migrate our data and update the system accordingly.

## Consequences
Easier: Improved scalability, data accessibility, and disaster recovery.
More Difficult: Data migration, potential integration challenges, and subscription costs for cloud services.

# ADR 3: Implementing Mobile App for Attendee Registration

## Status
Proposed

## Context
Our attendance registration system is currently web-based, which can be inconvenient for users on the go. We've received feedback requesting a mobile app for easier registration.

## Decision
We propose developing a mobile app for attendees to register and mark their attendance conveniently. This change aims to enhance user experience.

## Consequences
Easier: Improved user experience and convenience for attendees.
More Difficult: Mobile app development, maintenance, and potentially additional support resources.

# ADR 4: Integrating Real-time Reporting

## Status
Accepted

## Context
Our current reporting system is manual and time-consuming. Users have expressed a need for real-time attendance reports and analytics.

## Decision
We have decided to integrate a real-time reporting system into the attendance register. This will provide users with up-to-date attendance data and analytics.

## Consequences
Easier: Real-time access to attendance data for administrators and attendees.
More Difficult: Development and integration of the real-time reporting feature.

# ADR 5: Enabling Two-Factor Authentication (2FA)

## Status
Proposed

## Context
To enhance security further, there is a growing need for two-factor authentication (2FA) in the attendance register system. This will reduce the risk of unauthorized access.

## Decision
We propose implementing 2FA for user authentication, adding an extra layer of security to the system.

## Consequences
Easier: Improved security, reducing the risk of unauthorized access.
More Difficult: Development and implementation of 2FA methods and user education on 2FA usage.
