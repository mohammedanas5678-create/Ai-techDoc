Ai-techDoc Pro — Heal Bay SECURE BETA 1

SECURITY: AES-256-GCM encrypted IndexedDB vault, 650,000-iteration PBKDF2-SHA256 passphrase derivation with random salt, per-save random nonce, encrypted exported backups, 2-minute idle auto-lock. No external JS or network backend.

LIMITATIONS: Not independently audited, not production approved, no recovery if passphrase lost, device loss/cleared Safari storage can destroy local data, no multi-device sync, no audit log, and old plaintext data from prior app versions is not migrated or deleted. Security of a GitHub Pages-hosted application depends on protecting the GitHub account and its published source. Do not use identifiable real patient data until review, verified restore, iPad printing, and operational checks.

CRITICAL: Before deploying, export a backup from the old app. New encrypted vault is SEPARATE from old plaintext data and does not import it. Do not delete old data until a safe migration is verified. Upload all 8 files to root of repository. Test on Safari iPad with fictional patients.

Saved medication/lab presets are clinician-created and never dose recommendations.
