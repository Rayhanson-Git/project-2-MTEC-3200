# Platform Decision

**Selected platform:** Expo / React Native, running in Expo Go.  
**Shared services:** Supabase Database and Auth.

## Why this platform

The research includes requests before a visit, handovers in labs or club spaces, and later loan updates. A phone-based prototype can support those situations. I chose the native route for the project after comparing it with a mobile-friendly web app.

The research does not establish that a native-only phone feature is necessary. A web app remains a feasible alternative and could reduce installation effort, which matters given P4's concern about adoption.

Supabase will host shared records and provide the API and authentication. Equipment entries belong to lenders. Building the app still requires defining the data and access rules, but does not require operating a database server.

## Alternatives considered

| Platform | Assessment |
| --- | --- |
| Mobile-friendly web | Strong fit for requests and shared status on phones or computers, with access through a link |
| Expo native app | Selected for the phone-based prototype and on-location collection and return interactions |
| ESP32 device | Not selected. The core flow does not require sensing or controlling physical equipment |

## Course requirements

The app must run in Expo Go using compatible libraries and include a flow that saves and retrieves data on a phone. The native demonstration will use an Expo link and screen recording. App Store or Google Play publication is outside the course scope.

This decision uses the Class 10 assignment's filename, `docs/platform-decision.md`. The general brief also mentions `docs/design/platform-decision.md`.

## Sources

- [Class 10: Ideation](https://app.notion.com/p/de83d2939d2f83f5a92f01649acfe88e)
- [Project 2 brief](https://app.notion.com/p/eaa3d2939d2f83ee841881b984c31562)
- [Expo: Using Supabase](https://docs.expo.dev/guides/using-supabase/)
