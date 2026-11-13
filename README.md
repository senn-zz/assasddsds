# AgriMarket
A Flask + MySQL web app connecting farmers and buyers (Laguna University – IPT1/OOP/Web Systems final project).

## Setup
1. `python -m venv venv && source venv/bin/activate` (Windows: `venv\Scripts\activate`)
2. `pip install -r requirements.txt`
3. Import the database: `mysql -u root -p < schema.sql`
4. Set environment variables (optional but recommended):
   `SECRET_KEY`, `DB_HOST`, `DB_USER`, `DB_PASS`, `MAIL_USERNAME`, `MAIL_PASSWORD` (Gmail app password)
5. Run: `python app.py` then open http://127.0.0.1:5000

## Roles
- **Farmer**: create/edit/delete own product listings, dashboard of stock.
- **Buyer**: browse and search the market.

## Client documentation
Add: client name, interview notes, and sign-off here.
