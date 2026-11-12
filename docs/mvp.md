# MVP

## Core problem

Students and campus equipment lenders sometimes have difficulty coordinating access and knowing an item's current loan status because information depends on individual availability, memory, and scattered records.

**HMW:** How might we help students and campus equipment lenders coordinate access and understand current loan status while preserving the ease and flexibility of informal borrowing?

## Must-have features

- Sign in and access the equipment, requests, and loans relevant to the user's permissions.
- Let lenders add and update their own equipment and availability.
- Let borrowers submit equipment requests.
- Let lenders approve or reject requests and attach a short decision or pickup note.
- Let lenders or authorized staff record physical collection separately from approval.
- Show current loan status to the borrower, lender, and authorized staff.
- Let borrowers add an ongoing-use or ready-to-return update without closing the loan.
- Let borrowers report a return and attach a short location or arrangement note.
- Let lenders or authorized staff confirm receipt before closing the loan.
- Record an agreed return date or a flexible return arrangement.
- Save and retrieve shared data across devices, with clear empty states, unavailable or rejected states, and failed-save errors.

Pickup notes can describe a staff handover or an agreed prepared collection location. The app records the arrangement and actual collection. Approval alone does not establish that the borrower has received equipment.

A short note stays attached to its request or loan. This is not a full chat system.

## Nice to have, but not MVP

- Push notifications.
- QR scanning.
- Equipment photos.
- Advanced search and filters.

## Out of scope for now

- Full chat or social features.
- Payments, deposits, penalties, or a campus-wide deadline policy.
- Automated lockers, smart locks, or equipment-tracking hardware.
- Campus-wide inventory imports.
- App Store or Google Play publication.

## Key assumptions to test

- Borrowers, lenders, and staff will use and update the shared record.
- The flow adds little effort to informal loans that already work.
- People understand the difference between approved, collected, return reported, and return confirmed.
- Short notes make pickup and return arrangements clear.
- Authorized staff can verify approvals and record handovers.
- A prepared pickup location is practical when explicitly arranged by the lender.
- People will adopt an Expo-based phone prototype despite the additional access step.

The selected platform is documented in [platform-decision.md](platform-decision.md). The [proposed system diagram](system-diagram.png) describes the planned build.
