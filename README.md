# ResquePay — AI-Native Deterministic Revenue Recovery Daemon
Built for **Razorpay AI Buildathon 2026** | **Track 03: AI Revenue Recovery**

## ⚡ Solution Overview & FinTech Impact
Online transactions see up to a 30% drop-off rate due to banking gateway timeouts, insufficient customer balances, or security authorization drops. ResquePay is an asynchronous operational framework engineered to triage failure codes instantly, design contextual recovery chasers (WhatsApp/Email alerts), and fire automated background retry sequences to restore leaking cash flows for merchants.

## 🧠 High-Availability System Design (The Edge Architecture)
To ensure 100% platform uptime and prevent external network blockages, the repository handles pipeline exceptions through a robust deterministic routing layer. If live external APIs encounter token limits, the daemon switches to pattern-intelligence routing, ensuring zero drop-offs and seamless analytical updates.

## 🛠️ Architecture & Tech Stack
- **Frontend Dashboard & Telemetry:** Streamlit UI with unified charts and live metric data.
- **State Persistence:** Persistent local database layer tracking structured transaction ledgers.
- **Audit Trails:** Strict multi-agent logging tracking granular choices made by the `TriageAgent`, `StrategyPlannerAgent`, and `ExecutionAgent`.

## 🚀 Quick Execution
1. Clone the repository into your local system.
2. Install project components: `pip install -r requirements.txt`
3. Launch the operational control deck: `python -m streamlit run resque_all.py`
4. Use the sidebar controller interface inside the application to trigger batch simulations instantly.
