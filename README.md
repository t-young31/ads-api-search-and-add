# ads-api-search-and-add

```bash
# Install the dependencies in a new Python virtual environment
python -m venv .venv
. venv/bin/activate
pip install requests==2.31
# Set the API token (https://ui.adsabs.harvard.edu/user/settings/token) and run
export ADS_API_TOKEN=<token here>
python .github/scripts/add_alps_papers_to_ads_library.py
```
