###  CLI Video Editor (Powered by FFmpeg + Mistral API)

A command-line video editor that lets you describe your editing tasks in plain English. It uses the **Mistral API** to interpret commands and leverages **FFmpeg** under the hood for fast, powerful video processing.

---

###  Installation

```sh
pip install -r requirements.txt
```

---

###  Usage

```sh
python app.py
```

Simply run the script and input your editing instructions in natural language — for example:

> "Trim the first 10 seconds, crop to 720p, and speed up by 1.5x."

The app translates your prompt into FFmpeg operations and executes them automatically.

---

