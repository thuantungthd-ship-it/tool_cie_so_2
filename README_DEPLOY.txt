CIE STREAMLIT DEPLOY

Files to put in GitHub ROOT:
- app.py
- engine.py
- requirements.txt
- runtime.txt

IMPORTANT:
1) Set Streamlit entrypoint to app.py (NOT app_v2.py).
2) Remove/rename old app_v2.py and engine_v2.py from the repository to avoid confusion.
3) If the existing Streamlit app was deployed with Python 3.14, changing runtime.txt may not change the deployed Python version. Streamlit Cloud documents that Python version is selected at deployment and cannot be changed after deployment; delete/redeploy and choose Python 3.12 in Advanced settings.
4) Keep existing Streamlit Secrets exactly as configured.
