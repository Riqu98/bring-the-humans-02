# Workflow — how to build a make.fun entry

This is the pipeline I run for every make.fun bounty, written down so the next build follows the same gates and so a reviewer can see what was actually done. It is a short summary of the working method, not a copy of any other document.

## The pipeline

```text
Research → Design → Build → Independent QA → Submit → Track
```

| Stage | Job | Output |
|---|---|---|
| Research | Read the bounty, the kit, and the rules to the end. | Bounty, scope, deadline, fee, scoring, and what is in and out. |
| Design | Decide what to build, in what order, and what "done" looks like. | A short design the owner reviews before any build starts. |
| Build | Build it in the recorded session, from the design. | Code and README, committed. |
| QA | Verify independently: re-run every gate, re-read the code. | Pass, conditional pass, or fail, with evidence. |
| Submit | Submit through the kit CLI, after the owner approves the preview. | Submission ID and status. |
| Track | Watch the entry and report only when its status changes. | Status changes, to the owner. |

## Rules that never bend

1. **No invented data.** Every number, date, score, rank, and price comes from something read, checked live, or measured. If the data is not enough, say so and say what is missing.
2. **Research first.** For a game, research the real games in the genre first — the core loop, why it is fun — then design something original in that spirit. Never clone a specific game.
3. **Build to win, not to take part.** Every entry is built to compete for the top places. If it cannot be competitive with the time and resources available, say so before building, rather than submitting a filler entry.
4. **Two reviews by the owner.** The design goes to the owner for review before the build starts, and the finished preview goes to the owner before submission. Submit only after the owner approves the preview.
5. **QA is never overridden by the coordinator.** Only the owner can override a QA verdict, and only by saying so directly.
6. **Record cleanly.** The build happens in one recorded session that started after the bounty opened. While it runs, nothing else writes sessions that could get swept into the bundle.
7. **No spending without an explicit order.** Entry fees, minting, offers, and transfers need the owner's explicit order naming the amount.
8. **Own work only.** Every line of the entry is written by the agent in the sessions that are uploaded. Never clone, download, copy, or re-type someone else's entry.

## How to reuse this workflow

Copy the pipeline table and the eight rules into your own notes, in your own words, in your own session. Then run a small bounty through it end to end before you trust it on a big one. The pipeline is only real when a QA verdict has actually stopped a bad entry from going out.
