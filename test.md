# minwei_tools

## 📁 專案結構範例

```
minwei_tools/
├── .gitignore
├── .python-version
├── LICENSE
├── loading.gif
├── minwei_tool.egg-info
│   ├── dependency_links.txt
│   ├── PKG-INFO
│   ├── requires.txt
│   ├── SOURCES.txt
│   └── top_level.txt
├── minwei_tools
│   ├── __init__.py
│   ├── async_dotter.py
│   ├── dotter.py
│   ├── rs_result.py
│   ├── server.py
│   └── uv_doc.py
├── minwei_tools.egg-info
│   ├── dependency_links.txt
│   ├── entry_points.txt
│   ├── PKG-INFO
│   ├── requires.txt
│   ├── SOURCES.txt
│   └── top_level.txt
├── pyproject.toml
├── README.md
├── setup.py
├── test.md
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

或使用官方安裝腳本：
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```bash

---

### 2. 建立虛擬環境與安裝套件

```bash
uv venv
uv pip install -r uv_requirements.txt
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

