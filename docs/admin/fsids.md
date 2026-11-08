# FSIDs

## Purpose

Browse and open issued FSID assignments. Raw Fayda (FIN) numbers are not shown in staff views.

## Who sees it

Users with `fsid:read`.

## How to open

Sidebar → **FSID** → **FSIDs** (`/fsids`).

![FSIDs list](../assets/screenshots/admin-fsids-list.png)


## Actions

1. **Search** by name or FSID value using the search box.
2. **Reload** the table when you need fresh data.
3. Open a row to view **FSID detail** (identity summary, Fayda linked flag, issuing institutions, access sessions, audit events).
4. Click **Issue FSID** (requires `fsid:issue`) to start a new admin issuance — see [Issue FSID](issue-fsid.md).

### Detail page notes

- Issuing institutions lists every institution link for that FSID.
- Access sessions and audit events are read-only lists for support and investigation.
