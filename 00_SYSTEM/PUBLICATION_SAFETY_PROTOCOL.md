# Publication Safety Protocol

## Purpose

Prevent private project data from leaking into a public-safe template repository.

## Mandatory Review Areas

1. Names and identities
2. Contact details
3. Property or client specifics
4. Incident and claim details
5. Policy and legal references
6. Local path and machine details
7. Hidden tool metadata
8. Obsidian local workspace artifacts

## Blocking Conditions

Block publication if any file contains:
- a real name
- a real email address
- a real phone number
- a real policy number
- a real incident summary
- a local machine path
- non-template operational data

## Safe Release Sequence

1. Run `TEMPLATE/SANITIZATION_CHECKLIST.md`.
2. Review examples for hidden private references.
3. Confirm `.gitignore` excludes local Obsidian workspace artifacts.
4. Replace placeholder `LICENSE` text with the approved publication license.
5. Record the review outcome in a pull request or release note.
