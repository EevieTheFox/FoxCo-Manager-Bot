# FoxCo Manager Bot - Publication Notes

These drafts are written for the current planned version of FoxCo Manager Bot: a private bot used only within FoxCo Armory & Marketplace.

Before publishing or collecting Torn API keys:

1. Display the exact Torn API access level or custom selections at the key-submission screen.
2. Link the public Privacy Policy in the Discord Developer Portal and make both policies easy to reach from the bot or server.
3. Configure the deletion/unlink workflow and verify that rolling deletion actually enforces the stated periods:
   - active keys and linked-account records: retained while needed;
   - unlinked/revoked records: deleted within 7 days;
   - ordinary operational records: deleted within 7 days;
   - completed-contract records: deleted within 24 hours.
4. Encrypt API keys and user-identifying fields at rest, keep encryption secrets out of the source repository, and restrict decrypted access to the owner.
5. Update the policies if the bot expands beyond FAM, begins processing real-money payments, adds a raffle system, changes retention, changes sharing, or materially changes its Torn API permissions.
6. Once a hosting/database provider is chosen, confirm its logging, backup, encryption, breach-notification, and deletion behavior is compatible with the policy.

These are practical drafts, not a substitute for advice from a licensed attorney in the relevant jurisdiction.
