# Working in this repository

Read README.md and the service catalog before changing runtime behavior. Preserve public contracts, account ownership, idempotency and existing data. Use frozen uv environments for Python and npm ci for JavaScript. Keep credentials and model weights outside Git. Run the focused checks for changed code. Build and release only affected targets. Production deployment is owned by zenora-platform; never run a platform-wide rebuild for a single-service fix.
