# XplainIQ Lite (Streamlit)

Minimal, friction-free Streamlit app for the Channel Readiness Index.

## Files
- `XplainIQLite.py` — the app (client form only; admin view with `?admin=1`).
- `requirements.txt` — pinned deps that work reliably on Streamlit Cloud.
- `runtime.txt` — forces Python 3.11 on Streamlit Cloud.

## Deploy
1. Put all three files at the **repo root**.
2. Deploy via https://share.streamlit.io → New app → Main file: `XplainIQLite.py`.
3. After deploy, use:
   - Client link: `...streamlit.app`
   - Admin link: `...streamlit.app/?admin=1`

## No Zapier/Sheets required
Leads are saved to `leads.csv` in the app working directory. See/admin-download in `?admin=1`.
