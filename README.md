# OSEP

MONTH 1 — Foundations & Methodology

Week 1 — Linux Privilege Escalation

Day 1-2: SUID/SGID abuse, cron job exploitation, PATH hijacking → TryHackMe "Linux PrivEsc" room
Day 3: Kernel exploits, capabilities (getcap/setcap abuse)
Day 4-5: Practice on 5 easy HTB Linux boxes, privesc only (skip initial foothold if it's a known CVE, just focus on the privesc chain)
Day 6: LinPEAS deep-dive — run it, read every section of output, understand why each flag matters
Day 7: Rest / catch-up / write notes

Week 2 — Windows Privilege Escalation

Day 1-2: Service misconfigs, unquoted service paths, weak folder permissions → TryHackMe "Windows PrivEsc" room
Day 3: Token impersonation (JuicyPotato, PrintSpoofer, RoguePotato) — understand SeImpersonatePrivilege
Day 4: Registry-based privesc (AlwaysInstallElevated), scheduled tasks
Day 5-6: 5 easy HTB Windows boxes, privesc-only practice
Day 7: WinPEAS deep-dive, build a personal cheat sheet

Week 3 — Web App Exploitation Depth

Day 1: Manual SQLi (union-based, blind, time-based) then sqlmap for verification
Day 2: File upload bypass (extension tricks, magic bytes, race conditions)
Day 3: LFI/RFI → log poisoning → RCE chain
Day 4: Command injection, filter bypass techniques
Day 5: Insecure deserialization basics (PHP/Java/.NET — just enough to recognize it)
Day 6-7: 3 full HTB "easy" web-focused boxes end-to-end, timed at 3 hrs each

Week 4 — Methodology & Note-Taking

Day 1-2: Build your enumeration checklist (nmap all-ports → service-specific enum → gobuster/feroxbuster → manual testing)
Day 3: Set up Obsidian or CherryTree with box templates (recon/foothold/privesc/loot sections)
Day 4-6: 2-3 full "easy" HTB boxes end-to-end, timed, using only your own checklist (no walkthroughs unless truly stuck)
Day 7: Write a full penetration test report for one box, as if submitting it — this is real exam practice
Milestone: Buy PWK subscription by end of this week if you haven't (get 90-day lab access to cover months 2-3)
MONTH 2 — Active Directory

Week 5 — AD Fundamentals

Day 1-2: Kerberos auth flow (AS-REQ/AS-REP, TGT, TGS) — watch ippsec's AD talks or read the Kerberos section of TCM's PEH course
Day 3: Domain/forest structure, trusts, GPOs, OUs
Day 4-5: Set up a small AD lab yourself (2 VMs — DC + workstation) if you haven't; this cements concepts fast
Day 6-7: Read through HackTricks' AD section fully once, just for exposure

Week 6 — AD Enumeration

Day 1-2: BloodHound + SharpHound — collect and analyze data from your lab domain
Day 3: PowerView — manual enumeration without BloodHound (exam sometimes restricts tool use)
Day 4: enum4linux-ng, ldapsearch, rpcclient for external enum
Day 5-7: TryHackMe "Attacktive Directory" + HTB "Forest", "Sauna", "Active" — classic beginner AD boxes

Week 7 — AD Attacks

Day 1: Kerberoasting + AS-REP roasting (GetUserSPNs.py, Rubeus)
Day 2: Pass-the-hash, pass-the-ticket (Impacket's psexec.py, wmiexec.py)
Day 3: DCSync attack, secretsdump.py
Day 4: Unconstrained and constrained delegation abuse
Day 5-6: HTB AD boxes — "Resolute", "Monteverde", "Cascade" — full chains
Day 7: Consolidate an "AD attack playbook" doc — command-by-command reference

Week 8 — Start PWK Labs

Day 1-3: Work through PWK course material (skim familiar sections, slow down on AD modules)
Day 4-7: Start PWK lab machines, prioritize AD sets first while concepts are fresh — take detailed notes on every box
MONTH 3 — Lab Grinding & Exam Simulation

Week 9-10 — Heavy Lab Grinding

Alternate days between PWK labs and PG Practice "OSCP-like" tagged machines
Target: mix of standalone Linux, standalone Windows, and full AD sets
Hard rule: 3-4 hrs max per box before checking a hint — the exam has no unlimited time
End each day by writing a short report entry for what you did (builds report-writing speed)

Week 11 — Mock Exams

Day 1-2: First 24-hour mock exam (2-3 standalone machines + partial AD set), no walkthroughs
Day 3: Write a full report for the mock, as if submitting for real
Day 4-5: Second 24-hour mock exam
Day 6-7: Review both mocks — identify where you lost the most time, drill that specific skill

Week 12 — Final Prep

Day 1-3: Targeted review of weak spots found in mocks
Day 4: Polish your report template, double check screenshots/proof format requirements
Day 5: Light review only — re-read your AD playbook and enum checklist, no new material
Day 6-7: Rest, sleep well, book/confirm exam if not already scheduled



