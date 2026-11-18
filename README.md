# Benjamin Shado

**Backend Software Engineer · Python, FastAPI, PostgreSQL**

I build products from the database to the screen: the data model, the APIs and the interface on top. Based in Lagos, open to backend and full-stack roles.

🌐 [benjaminshado.com](https://benjaminshado.com) · 💼 [LinkedIn](https://www.linkedin.com/in/benjaminshado/) · ✉️ benjamin.shado@gmail.com

## Featured work

**Farm operations platform** · *private, in daily use since Oct 2026* · [case study](https://benjaminshado.com/work/poultry-farm)
Sole engineer on the system a commercial egg farm runs on: production, sales, inventory, feed costing and payroll. Staff report from their phones, and the backend cross-checks every report against the others, so mistakes surface the same day instead of at month-end.
`FastAPI` `PostgreSQL` `React` `Redis` `Docker` · 110+ endpoints · 300+ tests · month-end reporting cut from ~2 days to real time

**NextWatch** · *private, in development* · [write-up](https://benjaminshado.com/work/next-watch)
I own the backend for an iOS and Android app for tracking movies and TV episode by episode, and built its auth service.
- Redis-cached TMDB integration with retries, backoff and a fallback to the last good copy when rate-limited
- Separate auth service (Better Auth) issuing short-lived EdDSA JWTs, verified by the FastAPI backend against cached public keys
- Ownership checks return 404 so resource IDs can't be probed
`FastAPI` `PostgreSQL` `Redis` `SQLAlchemy` `TypeScript` · 135 tests

**[Credit card fraud detection](https://github.com/hxxisq/credit_card_fraud_detection)**
XGBoost on 284K+ transactions with <0.2% fraud: catches 84% of fraud (0.97 AUC-ROC, 0.86 F1), with SHAP to explain each prediction.

## Stack

**Backend:** Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Redis · pytest
**Frontend:** React · TypeScript
**Data:** Pandas · NumPy · Scikit-learn · XGBoost
**Tools:** Docker · Git
