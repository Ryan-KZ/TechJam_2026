# HPE TechJam 2026 — Module 2: Venue Operations Intelligence
## "The Halftime Meltdown" — Meridian Stadium Scenario

A hands-on AI lab (~30 minutes) where participants act as Operations Intelligence Analysts for a fictional stadium. Using an AI assistant (Kaizen), trainees investigate a live crowd analytics anomaly, trace the root cause across multiple data sources, and deliver an actionable briefing to the ops director before the third quarter starts.

---

## Scenario

It's halftime of the biggest home game of the season. The WaitTime crowd analytics system has flagged a critical alert: hot dog carts on the Section 114 concourse have 30+ people in line and climbing, while the burger stand one level up is nearly empty. The ops director wants answers — and a dollar figure on the damage — before kickoff.

---

## Files Included

| File | Description |
|------|-------------|
| `waittime_sensor_feed.json` | Live crowd analytics snapshot from all concourse sensors |
| `waittime_historical_queues.csv` | Queue data from the last 3 home games |
| `waittime_pos_sales.csv` | Sales transactions by stand and period |
| `waittime_staffing.csv` | Scheduled vs. actual staffing by stand |
| `waittime_supply_inventory.csv` | Inventory levels and equipment status |
| `waittime_fan_feedback.csv` | Fan ratings and comments submitted during the game |
| `MODULE_TRAINEE_GUIDE.md/.pdf` | Step-by-step trainee guide with sample prompts |
| `API.pdf` | Reference documentation for the WaitTime API |
| `TechJam.zip` | Full module archive |

---

## How to Run the Module

1. Open your AI assistant (Claude / Kaizen).
2. Upload all six `waittime_*` data files.
3. Follow the four phases in `MODULE_TRAINEE_GUIDE.md`:
   - **Phase 1** — What's happening right now? (~5 min)
   - **Phase 2** — Is this normal for halftime? (~5–7 min)
   - **Phase 3** — What caused this? (~10 min)
   - **Phase 4** — What does it cost and what do we fix? (~8 min)
4. Deliver a concise ops briefing as your final output.
