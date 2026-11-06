HEALTHCARE DATA STORYTELLING DASHBOARD

1. Extract this folder.
2. Open the extracted folder in VS Code.
3. Open Terminal > New Terminal.
4. Run these commands:

   py -m venv .venv
   .venv\Scripts\activate
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   python -m streamlit run app.py

5. The dashboard opens in your browser. Keep the terminal open while using it.

IMPORTANT:
- Run app.py, not an extension-output file.
- Do not press F5 / Run Code for this Streamlit app.
- If PowerShell blocks activation, use:
  Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
  .venv\Scripts\activate

The built-in records are fictional educational sample data, not real patient records.
