LOCAL PATIENT RECORDS — FAST CONSULTATION UPDATE

Files in this update:
- index.html: adds a Doctor’s Fast Consultation screen. It saves a new patient and their first visit together in the existing encrypted IndexedDB vault.
- service-worker.js: bumps the cache name so the updated app files can be fetched.
- manifest.webmanifest: unchanged app manifest, included for convenience.

UPLOAD
1. Export an encrypted backup from your currently working app and verify that the backup file was downloaded. Keep it private.
2. In your GitHub repository, replace index.html and service-worker.js with these files. Keep your existing icons/ folder and repository structure. The manifest is unchanged; you may keep your current one or upload this copy.
3. Commit the changes.
4. Open the app online once while connected to the internet. If the old screen remains, close the app fully and reopen it, or clear only the site's cached files (do not clear site data/storage).
5. Test with fictional records first. Confirm old patients and visits still appear and test a new consultation.

IMPORTANT
- This remains a single-device, browser-local app; it does not sync between devices.
- The new screen creates a new patient and first visit in one encrypted vault save. It does not yet provide existing-patient consultation from this screen; use Patients to find returning patients and add a visit.
- The current visit form remains available for editing visits, entering multiple medicines and taking prescription photos.
- The app is a prototype and has not been independently security audited or certified for clinical use.
- Never upload patient data, backups, passwords or encryption keys to a public GitHub repository.
