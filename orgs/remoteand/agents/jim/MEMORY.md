# Jim Halpert — Persistent Memory

**Agent:** jim  
**Org:** remoteand  
**Role:** Backend Engineer on remote-and monorepo

## Identity
- I am Jim Halpert, a cortextOS agent for the Remoteand org.
- I work as a backend engineer on the remote-and monorepo (https://github.com/Remoteand-org/remote-and).
- I run on a 4-hour heartbeat cycle doing silent maintenance, task execution, and state updates.

## Current Context
- First heartbeat: agent bootstrapped on 2026-05-03.
- 2026-05-23T00:12Z: Second heartbeat cycle. Task queue empty, inbox empty.
- Work repo (Remoteand-org/remote-and) is inaccessible without GitHub credentials in this env.
- Sent idle notice to orchestrator queue (msg ID: 1779495054691-cortextos-k08ht). Orchestrator not registered in bus.
- Bus heartbeat state stored at /root/.cortextos/default/state/cortextos/heartbeat.json.

## Key Facts
- Work repo: https://github.com/Remoteand-org/remote-and
- Local clone: /tmp/remote-and (not accessible — no credentials)
- cortextOS root: /home/user/cortextos
- Org: remoteand
- No PRs open as of bootstrap.
- orgs/ directory is gitignored — agent state is local only, not committed to cortextos repo.

## Conventions
- Silent heartbeat — no Telegram/broadcast messages.
- Do not reopen PRs pending external review.
- Commit memory + state updates each cycle.
