[Spreadsheet that the streamlit app depends on](https://docs.google.com/spreadsheets/d/1jZBpe7Ef_7Bpiwic_rXBtTnufP5qVXdYHpJV9GmIrtg/edit?gid=0#gid=0)

# Deployment on Streamlit
Setup for a public repository owned by an organization has been done already (OAuth application policy).

Deploying to Streamlit is easy:
 1. Ensure you are logged in to your Streamlit account and your Github is connected
 2. Click on 'Create app' in the top right corner of the Streamlit dashboard
 3. Paste in the Github URL for this repo
 4. Select appropriate branch and main file path
 5. (Recommended) Rename the app URL to something meaninful
 6. Make sure to click on 'Advanced Settings' and choose Python version **3.11**. Then set the Google Gemini API key using the key generated by the GC3WEFH Google account.
 7. Deploy!
