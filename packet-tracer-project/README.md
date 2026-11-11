# <Project Name>

Cisco Packet Tracer group project for <Course Name>.
Packet Tracer version: **<e.g. 8.2.2>** — everyone must use the same version.

## Team
| Name | GitHub | Responsible for |
|------|--------|-----------------|
|      |        |                 |
|      |        |                 |
|      |        |                 |

## Repo Layout
```
topology/    .pkt files (one per section, e.g. hq.pkt, branch.pkt, final.pkt)
configs/     running-config of every device as text (R1.txt, SW1.txt, ...)
docs/        addressing plan, notes, report material
LOCKS.md     who is currently editing which .pkt file
```

## Workflow (read this!)
1. **Pull first** — always get the latest version before opening anything.
2. **Lock** the .pkt you'll edit in `LOCKS.md`, commit + push.
3. **Edit** in Packet Tracer and save.
4. **Export configs** — on each device you changed, run `show running-config`
   and paste it into `configs/<DEVICE>.txt`.
5. **Commit** the .pkt + config files with a clear message
   (e.g. "Add OSPF between R1 and R2").
6. **Unlock** your row in `LOCKS.md`, commit + push.

## Rules
- Never edit a .pkt someone else has locked.
- Check `docs/addressing-plan.md` before assigning any IP address.
- Each person builds their own section file; one person merges everything
  into `topology/final.pkt` at the end.
- Don't commit huge test files or random copies (`hq-v2-final-REAL.pkt`) —
  Git keeps the history for you.

## Progress
- [ ] Addressing plan agreed
- [ ] Sections built
- [ ] Configs exported
- [ ] Merged into final.pkt
- [ ] Tested end-to-end (ping / traceroute)
- [ ] Report written
