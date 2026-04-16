# payment-processing-backend
# 💳 Mini Payment Processing Backend

A backend system simulating digital payment operations including wallet management, transactions, and fraud validation.

 Features
- User creation with wallet initialization
- Add money to wallet
- Peer-to-peer money transfer
- Fraud detection (transaction limits)
- Transaction history tracking

 Tech Stack
- Python
- FastAPI
- SQLite
 API Endpoints

| Method | Endpoint | Description |
|--------|---------|------------|
| POST | /users | Create user |
| POST | /wallet/add | Add money |
| GET | /wallet/{user_id} | Check balance |
| POST | /transfer | Transfer money |
| GET | /transactions/{user_id} | View transactions |

 Run Locally

```bash
pip install fastapi uvicorn

---

STEP 4: Push README

```bash
git add README.md
git commit -m "Added README"
git push
python -m uvicorn payment_app:app --reload
