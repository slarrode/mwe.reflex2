```bash
mkdir mwe
cd mwe
python -m venv .venv  # w11 py3.12.1
# echo reflex >> requirements.txt
source .venv/bin/activate # bash
.venv/Scripts/activate # powershell
pip install reflex  --use-deprecated=legacy-resolver  # en linux, mejor
pip install reflex                                    # powershell
reflex init
```