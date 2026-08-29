# EVSC Member Intelligence — demo

A member-retention dashboard concept for East Valley Strength & Conditioning.

**Live:** https://powerliftlog.github.io/evsc-dashboard/

## What this is

A single self-contained HTML page. No server, no install, no login. It answers one
question a gym owner can't easily get from Mindbody or a door-scan system:

> Which members are quietly on their way out, and what do I do about it this week?

Four screens: a ranked call list with a reason and a message to send, the member roster,
floor utilization by day and hour, and business health.

## The numbers are fake

Everything on screen is generated: ~240 fictional members and ~58,000 simulated door
scans. No real member data is used, stored, or transmitted. The figures are realistic, but
they are not East Valley Strength's actual numbers.

Every value is computed live from that simulated event stream — none of it is hardcoded —
so the same engine runs unchanged against real data.

## Loading real data

The **Load my data** button accepts a member export and a door-scan log as CSV. Files are
parsed **entirely in your browser**: nothing is uploaded anywhere, and closing the tab
discards it.

## Assumptions

Floor capacity (42 people) and class cap (20) are estimates, not measured. The dashboard
says so on screen rather than presenting them as fact.
