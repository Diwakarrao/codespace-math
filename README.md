Android Project Specification: QuickquzzMath
Act as a Senior Android Developer. Build a Kotlin/Jetpack Compose app called Quick Math using a WhatsApp Dark Mode UI (#0b141b, #202c33, #00a884).
Core Logic:
Implement a ForegroundService for "forced learning" math overlays. Use DataStore for settings and Coroutines for timers.
Setup Flow: 1. Language Selection (EN, HI, TE).
2. 18+ Gate.
3. Mock OTP Verification UI.
4. Permission Requests: SYSTEM_ALERT_WINDOW ,REQUEST_IGNORE_BATTERY_OPTIMIZATIONS, and TileService registration.
Home & Features:
Controls: Session Duration (5-15m), Frequency (30s-5m), and Answer Timer (5-60s).
Overlay: Trigger max vibration and "Please answer quickly" TTS.
Modes: * Strict: High-contrast problems (Full/Half screen).
Fun: Bouncing Red/Green bubbles or smoking ring animations.
Trial: 4-day free trial logic for Strict Mode.
Settings: Toggle Haptics/Audio, Language, and Menu (Share, Contact, About).
Technical Deliverables:
Provide the full project structure: AndroidManifest.xml (with service/permissions), build.gradle.kts, MainActivity.kt, MathOverlayService.kt, TileProvider.kt, and all Compose UI screens (Onboarding, Home, Overlay). Ensure the app is fully offline-capable after the initial mock OTP.
