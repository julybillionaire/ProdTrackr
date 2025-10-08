# ProdTrackr
Custom-built productivity tracker with integrated payroll and performance monitoring for remote teams.

Overview:

ProdTrackr was built to solve a simple problem:

Why pay monthly for third-party time trackers when you can own your own system forever?

Instead of using services like Time Doctor, we developed an in-house platform that:

Tracks agent productivity in real-time

Randomly captures screenshots for accountability

Detects idle time automatically

Integrates directly with payroll for faster computation

This system has saved our company thousands of dollars annually and improved transparency and performance tracking across all departments.

⚙️ Key Features

✅ Clock In / Clock Out System
Agents log in and out through a desktop app that records time directly to the database.

✅ Automated Payroll Integration
Hours tracked feed directly into a payroll computation module.

✅ Random Screenshot Captures (every 15 mins)
Ensures visibility into real-time activity while maintaining fairness and privacy.

✅ Idle Detection & Productivity Scoring
If idle for over 5 minutes, the user’s utilization score drops automatically.

✅ Productivity Reports
Generates daily and weekly utilization reports for management overview.

✅ One-Time Cost, Lifetime Use
No recurring SaaS payments — fully owned and scalable internal solution.

🧠 Tech Stack (Example)

(You can fill this in with what your dev used — or keep generic if unsure.)

Frontend: Electron / React

Backend: Node.js / Express

Database: MySQL

Other: Cron Jobs, Cloud Storage for screenshots

🧩 How It Works

Each agent installs the ProdTrackr client on their PC.

At the start of the shift → they click Clock In.

The program runs quietly in the background, capturing random screenshots every 15 minutes.

If idle (no keyboard/mouse activity for 5 minutes), the system logs an idle flag.

At end of shift → they click Clock Out.

The system automatically calculates total productive hours, deducts idle time, and syncs to payroll.

📊 Results

Reduced payroll processing time by 70%

Improved team accountability and focus

Completely eliminated monthly SaaS fees

Provided management with transparent productivity insights

🧑‍💻 About the Project Lead

Created by: Bernard Jedy Q. Torres
Role: Senior Marketing Manager & Operations Designer
Focus: Growth, Systems Design, and Operational Automation

“I wanted a system that empowered accountability and transparency — not one that charged us endlessly.”

💬 Future Improvements

Web-based dashboard for managers

Advanced analytics and utilization trends

Optional AI-driven anomaly detection (detects suspicious activity or patterns)

