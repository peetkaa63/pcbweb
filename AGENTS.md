# AGENTS.md — Guidelines for AI coding agents

## Project context
This is the team project "Commit to Learn": a learning platform with Node.js/
Express/Prisma/PostgreSQL backend, React frontend and Docker configuration.
Review README.md and the actual source files before modifying anything.
Respect collaborators' contributions and clearly identify changes you make.

## Workflow
- Prefer feature branches and pull requests rather than commits to main.
- Make focused changes to the relevant frontend/backend package.
- Preserve the API contract between frontend and backend.
- Check project scripts, Prisma schema, migrations and deployment details before editing.
- Add tests or verification steps for behavior changes.
- Report checks actually run; never claim a test passed without execution.

## Safety
- Never commit filled .env files, credentials, secret keys, database dumps or private student data.
- Check authorization and role boundaries for student/instructor functionality.
- Do not run destructive Prisma migrations, production deployment or database resets without explicit approval.
- Do not reveal private course content or personal records in reports, fixtures or logs.

## Handoff
At completion, explain in Russian: what changed, affected files, checks run,
migration/config implications, potential risks and rollback approach.
