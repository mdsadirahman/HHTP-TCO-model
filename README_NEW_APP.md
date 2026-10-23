# Full TCO — standalone new Streamlit app

This is a new app independent of the previous deployed repository.

## Files to upload to a NEW GitHub repository
- `app.py` – revised Full TCO application
- `requirements.txt` – Python dependencies

## Deployment
1. Create a NEW GitHub repository (`full-tco-payload-model`), with a README.
2. Upload `app.py` and `requirements.txt` to the `main` branch and commit.
3. On Streamlit Community Cloud, create an app from an existing repository.
   Repository: `<your GitHub username>/full-tco-payload-model`
   Branch: `main`
   Main file path: `app.py`
4. Choose Python 3.12 in Advanced settings (if needed), and deploy.
5. Run the Drayage case and review pre-tax, after-tax, total PV, and ton-mile charts.

## Calculation note
Payload reduction changes freight ton-mile denominator only; it is not a separate operating cost or a stacked cost segment. BEV GVW default 83,000 lb is an editable user scenario assumption and not a universal legal entitlement. Base 22.79 metric tonnes and non-battery BEV tare difference remain assumptions to verify.
