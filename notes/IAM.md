# IAM — Identity and Access Management

## Users, Groups and Policies

**Date:** 2026-09-04

### What I did
- IAM user `Doron-Admin` with console access
- Group `admin` with the `AdministratorAccess` policy
- Added the user to the group
- Set an account alias to shorten the sign-in URL
- Signed in as the IAM user in a private browser window,
  keeping the root session open in the normal window

### Key takeaways

**IAM is a global service.**
A user I create exists in every region.

**Permissions attach to groups, not users** (similar to Security Groups
for managing permissions in AD). Keeps the work much more organised.

**Root is for emergencies only.**
Root sees only the account ID, not a username. After initial setup
we stop using it.

### What surprised me