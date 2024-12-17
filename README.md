# HybridDemucsPlayground

Hybrid Demucsを使って遊ぼ

## 必要なパッケージのインストール

### Python

```powershell
python3.exe -m pip install --upgrade pip
```

C.F. [Start Locally](https://pytorch.org/get-started/locally/)

```powershell
python3 -m venv .venv
.venv/Scripts/activate
python3.exe -m pip install --upgrade pip
pip3 install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu126
pip3 install matplotlib IPython mir_eval ipykernel pylint
python3 -m ipykernel install --user --name=.venv --display-name "Python (.venv)"
pip3 freeze > requirements.txt
deactivate
```

### node

```powershell
npm install markdownlint-cli
```
