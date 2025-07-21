# 🛡️ Rasa AI Bot

---

## 📦 Initialization & Installation.

---

## 🧰 Setup Instructions (Step-by-Step)

### 🐍 Python Environment Setup

1. **Install Python 3.7.10**
2. **Install Microsoft Visual Studio C++ 2019**
3. **Install VS Code**

### 💻 Create and Activate Virtual Environment

```bash
python -m venv venv
.\venv\Scripts\activate    # For Windows
# OR
source venv/bin/activate   # For Linux/macOS
```

### ⬆️ Upgrade pip
Use the upgrade command shown in the warning message (typically):
```bash
python -m pip install --upgrade pip
```

### 🤖 Rasa Installation and Initialization

```bash
pip install rasa                    # Install Rasa inside your virtual environment
rasa init                           # Initialize Rasa project with basic files
rasa train                          # Train the NLU and Core models after editing intents
rasa shell                          # Start chat with the bot in shell
```

### 📦 Install Additional Project Dependencies

```bash
pip install -r requirements.txt
```

<!-- 
command for run the front end:  ng serve -o
command for run the debug mode: rasa run --enable-api --cors "*" --debug
command for run the rasa: rasa run actions
 -->


<!-- 
command to train the rasa model: rasa train --domain data/domain/ 
 -->