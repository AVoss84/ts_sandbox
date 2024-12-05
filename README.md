# Time series analysis sandbox

### Create virtual environment with required packages 

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh                  # get uv manager
# or from PyPi: pip install uv

uv venv ts_sandbox --python 3.12
source ts_sandbox/bin/activate

uv pip install -r requirements.txt
```
