# Cukka Page — Functional Spec

## 1. Landing Page (`index.html`)
- **Header**: Displays Cukka branding logo (`favicon.svg`) and navigation link to Privacy Policy (`privacy.html`).
- **Hero Section**:
  - Main Heading: "Your Personal 100% Offline Cookbook & Companion".
  - Subheading: "Store recipes, plan weekly meals, convert kitchen units, and build smart shopping lists. No account, no cloud, no internet required."
  - Primary Call to Action Button: "Download for Android" (links to GitHub latest releases).
  - Secondary Button: "View Source code" (links to GitHub repo).
- **Feature Cards Grid**:
  1. 🔒 100% Offline & Private: No backend, zero tracking.
  2. 🗓️ Weekly Meal Planner: Meal playlists & shopping list generation.
  3. ⚖️ Kitchen Converter: Volume, weight, density, and scoop unit.
  4. ⏱️ Cooking Mode & Timer: Compact scroll wheel timer & screen wakelock.
  5. 🛒 Smart Shopping List: Ingredient aggregation & portion scaling.
  6. 🌐 Full Internationalization: 100% native English & Portuguese (Brasil).
- **Footer**: Branding credits to Zabba Labs with direct link to Privacy Policy.

## 2. Privacy Policy Page (`privacy.html`)
- **Header**: Logo and link back to home page.
- **Content Sections**:
  1. Summary box: Explicitly states zero data collection.
  2. Data Storage: Explains on-device `SharedPreferences` local storage.
  3. Data Export: Explains JSON and PDF file export.
  4. Permissions: Explains storage and wakelock permission scope.
  5. Children's Privacy: COPPA compliance confirmation.
  6. Contact: Support contact email (`zbcdevo@gmail.com`).
