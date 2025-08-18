# CLI Video Editor

**Powered by FFmpeg + Mistral API**

A command-line video editor that lets you describe editing tasks in plain English.
It uses the **Mistral API** to interpret your commands and leverages **FFmpeg** for fast, powerful video processing.

<img width="1920" height="1080" alt="CLI Video Editor Demo" src="https://github.com/user-attachments/assets/5e3e03da-76fd-4136-bc9b-634a3dbeec15" />

---

##  Installation & Usage

You can use this tool in two ways:

---

### **Method 1: Install as a Library**

**Install:**

```sh
pip install clivid
```

**Run:**

```sh
clivid
```

---

### **Method 2: Clone from GitHub**

**Install:**

```sh
git clone https://github.com/localhost969/clivid.git
cd clivid
pip install -r requirements.txt
```

**Run:**

```sh
python main.py
```

---

##  How It Works

Simply run the command and input your editing instructions in natural language. For example:

> "Trim the first 10 seconds, crop to 720p, and speed up by 1.5x."

The app will automatically translate your prompt into FFmpeg operations and execute them.

---

