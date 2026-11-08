# SASE in Practice

Interactive companion to the TorNOG Fall Meetup talk *SASE in Practice: Lessons from the Field (and What AI Changes)*, November 12, 2026.

Step through a typical migration (legacy hub and spoke, remote users first, branches in waves, target state) and follow eleven traffic flows (branches, HQ / DC and remote users to SaaS, the internet, generative AI, the DC and a public cloud VPC) through each phase: how the packet gets there, which capabilities act on it, the legacy issues and how SASE fixes each one, and the pitfalls seen in real migrations.

A "Why SASE" slide (`W`) builds in three steps: the legacy network's issues, what SASE is, and how SASE covers each issue. A one-screen intro (`I`, or ← from phase 0) then explains what SASE means (SD-WAN + SSE under one policy, and what changes for the operator).

Keys: `←` `→` phase, `↑` `↓` flow, `F` SASE fixes or migration pitfalls, `I` what SASE means, `G` talk mode, `P` present (full screen), `T` theme. Links such as `#p2/branch-dc` open a specific phase and flow, and `#intro` the intro.

Talk mode (`G`, or the Talk button) steps through a fixed run order for a 10- or 15-minute slot with `→`, Space or a presentation clicker, and shows the step, a progress bar and a clock. `#talk15/3` opens step 3 of the 15-minute run.

On the diagram, drag from a source (a user, a branch, the DC or the cloud) to a destination to trace that flow: the path is drawn and the panel shows how it passes in each phase (`D` turns on trace mode for touch screens). `E` (Edit layout) lets you drag boxes around while links and flows follow; it is saved in your browser only, and Copy layout exports the moved positions.

Vendor-neutral and simplified, for discussion. The network is fictional. Views are my own, not my employer's.

The whole site is a single file, `index.html`, with no build step or server.
