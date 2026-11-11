# CSC410 Secure Network Design – Term Project

CSC410 Cyber Networking and Security · Fall 2026
**Due:** Wednesday, December 2, 2026

Team name:
Packet Tracer version (everyone must use the same one):

## Team
| Name | GitHub | Responsible for |
|------|--------|-----------------|
|      |        |                 |
|      |        |                 |
|      |        |                 |
|      |        |                 |

## Repo Layout
```
topology/             Packet Tracer (.pkt) files
configs/              running-config of each device, saved as text
docs/                 devices list and addressing plan
report/               term paper drafts
report/screenshots/   screenshots for the report
LOCKS.md              who is currently editing which .pkt file
```

## Workflow
1. **Pull first** — get the latest version before opening anything.
2. **Lock** the .pkt you'll edit in `LOCKS.md`, commit + push.
3. **Edit** in Packet Tracer and save.
4. **Export configs** — run `show running-config` on each device you changed
   and save it in `configs/`.
5. **Commit** your .pkt and config files with a clear message.
6. **Unlock** your row in `LOCKS.md`, commit + push.

## Rules
- Never edit a .pkt someone else has locked.
- Check `docs/addressing-plan.md` before assigning any IP address.

## Final Submission
- [ ] `TeamName_SecureNetworkDesign_Report.pdf`
- [ ] `TeamName_SecureNetworkDesign.pkt`
