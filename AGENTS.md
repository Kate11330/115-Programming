# AGENTS.md

- 所有回應一律使用繁體中文。
- 專案語言為 Python；一律使用 conda 管理套件，環境名稱為 `iem_python`。
- 執行 Python 前先確認環境：`conda env list`，執行時使用 `conda run -n iem_python python ...`，避免用到錯誤的直譯器或 pip 環境。
- Repo 目前近乎空 scaffold：僅有 `README.md`（# 115-Programming / 程設115）與 Python 樣板 `.gitignore`，尚無 source、manifest、測試或 CI 設定；新增程式前先以實際存在的檔案（`pyproject.toml`、`requirements*.txt`、`pytest.ini` 等）確認工具鏈。
- Shell 為 Windows PowerShell，路徑含空白或特殊字元時須加引號。
