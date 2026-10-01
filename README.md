# aituner issues

Bug reports for [aituner](https://aituner.app), the tool that benchmarks Apple Silicon Macs for local AI.

## Reporting a bug

The easiest way is from the app: **Report a bug** (the bug icon). aituner collects what it needs to
investigate (its version, your Mac's model, chip and memory, and recent log lines), shows you everything before
anything is sent, and files the report here for you. No GitHub account is needed.

You can also [open an issue](../../issues/new/choose) yourself. Please do not post security problems here: email
[info@aituner.app](mailto:info@aituner.app) instead.

## What the status labels mean

Every report gets one `status:` label, so you can see where it stands.

| Label | Meaning |
|---|---|
| `status: new` | Received, not looked at yet. |
| `status: checking` | Being checked against the logs and the code. |
| `status: needs info` | We need something from you: see the latest comment. |
| `status: confirmed` | Reproduced: it is a real bug. |
| `status: planned` | Will be fixed. |
| `status: in progress` | Being fixed now. |
| `status: fixed` | Fixed; it ships in the next release. |
| `status: released` | Fixed in a release (the comment says which). Update aituner to get it. |
| `status: cannot reproduce` | We could not make it happen. Tell us if it happens again. |
| `status: not a bug` | Works as intended (the comment explains why). |
| `status: duplicate` | Already reported: the comment links the original. |
| `status: won't fix` | Not something aituner will change (the comment explains why). |

The app shows the status of the reports you sent from it, too.

## Releases

Downloads and release notes are in [aituner-app/releases](https://github.com/aituner-app/releases). Each release's
notes list the reports it fixes.
