# Changelog

## 1.0.0

- Initial open-source stable release.
- Versioned CalendarService contract with Android Calendar Provider, iOS EventKit, and macOS EventKit adapters.
- In-memory mock calendar capability for unit testing and local development.

## 0.1.0

- Add the versioned CalendarService contract.
- Add native Android Calendar Provider, iOS EventKit, and macOS EventKit adapters.
- Return PLATFORM_UNSUPPORTED on Windows, Linux, and web without fabricating events.
