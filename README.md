# Hi, I'm Hùng

IT student at University of Science, VNU-HCM (High-Quality Program, graduating 2028). I mostly work on back-end and systems code, and right now I'm looking for a back-end internship.

## Things I've built

### [Filer task board server](https://github.com/NgTHung/Filer/tree/main/tools/filer-task-web)
A self-hosted task board for a small team. There are no passwords: to sign in on a new browser, you type a six-digit PIN from a browser you're already using. The PIN expires after five minutes and stops working after one use or five wrong guesses. Every edit is tied to a user, so the activity log shows who changed what.

`Rust` `Axum` `SQLx` `SQLite` · 146 integration tests

### [Tourgether](https://github.com/NgTHung/Tourgether) · [live demo](https://tourgether-rosy.vercel.app)
Fresh tourism graduates struggle to get a first job without experience. On Tourgether, tour companies post tours, graduates apply to assist or shadow, and the feedback they collect becomes a portfolio. I did most of the database schema, the login and onboarding flow, and file uploads.

`Next.js` `tRPC` `PostgreSQL` `Drizzle` `AWS S3`

### [Filer](https://github.com/NgTHung/Filer)
A file explorer engine for folders with tens of thousands of files. Results come back in pages, and older requests get dropped when you navigate again, so the window doesn't freeze. On my benchmark machine the first page of a 10,000-file folder arrives in about 0.3 ms.

`Rust` `async`

### [PetGuard](https://github.com/NgTHung/PetGuard)
Firmware for a pet collar and base station that report vitals and location (simulated in Wokwi). When the network drops, the collar buffers its readings and sends them once it reconnects. I led the three-person team.

`C++17` `ESP32` `MQTT/TLS` `ESP-NOW`

## Also

- Top 50, VinUni Datathon 2026
- Technical committee for the HCMUS Coding Challenge, 2025 and 2026

[LinkedIn](https://www.linkedin.com/in/nguyentuanhung06/)
