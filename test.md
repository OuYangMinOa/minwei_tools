# minwei_tools

## 📁 專案結構範例

```
minwei_tools/
├── .gitignore
├── .python-version
├── LICENSE
├── README.md
├── file_server.gif
├── loading2.gif
├── minwei_tool.egg-info
│   ├── PKG-INFO
│   ├── SOURCES.txt
│   ├── dependency_links.txt
│   ├── requires.txt
│   └── top_level.txt
├── minwei_tools
│   ├── __init__.py
│   ├── async_dotter.py
│   ├── dotter.py
│   ├── rs_result.py
│   ├── server.py
│   └── uv_doc.py
├── minwei_tools.egg-info
│   ├── PKG-INFO
│   ├── SOURCES.txt
│   ├── dependency_links.txt
│   ├── entry_points.txt
│   ├── requires.txt
│   └── top_level.txt
├── pyproject.toml
├── setup.py
└── uv.lock
```

---

## 🚀 安裝與啟動說明

此專案使用 [uv](https://github.com/astral-sh/uv) 來管理 Python 環境與套件。
以下是安裝與啟動的步驟：

### 1. 安裝 uv

如果已安裝 Rust，可透過 cargo 安裝：

```bash
cargo install uv
```

如果有基本的python跟pip

```bash
pip install uv
```

或使用官方安裝腳本：

```ps
curl -LsSf https://astral.sh/uv/install.sh | sh
```

如果是在 windows底下:
```ps
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

---

### 1. 同步 `pyproject.toml` 

```bash
uv sync
```

---

### 3. 進入開發環境

```bash
source .venv/bin/activate   # 或使用 uv shell
```

### 4. 啟動專案
```bash
uv run main.py
```

