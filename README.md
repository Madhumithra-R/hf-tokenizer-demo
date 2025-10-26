# 🧠 GPT-2 Tokenizer Demo

A simple Python script demonstrating the core **tokenization**, **encoding**, and **decoding** process using the **`GPT2Tokenizer`** from the Hugging Face **`transformers`** library.

This example clearly illustrates how **Byte Pair Encoding (BPE)** works by analyzing the sentence:  
> **"HuggingFace makes Natural Language Processing incredibly easy."**

---

## 💡 Key Concepts Demonstrated in the Output

The output confirms the following principles of the GPT-2 tokenizer:

1. **Subword Tokenization (BPE):**  
   The longer word **"transformers"** is split into two smaller, more frequent subwords: **`'Ġtransform'`** and **`'ers'`**.  
   This is the core mechanism allowing the model to handle unseen words.

2. **Space Handling:**  
   The **`Ġ`** prefix is used on tokens like **`'Ġlove'`** to indicate that a space precedes that token in the original text.

3. **Reversibility:**  
   The process is fully reversible, as shown by the **`Decoded Text`** perfectly matching the **`Original Text`**.

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Madhumithra-R/hf-tokenizer-demo.git
cd hf-tokenizer-demo
```

> *(Replace the URL with your actual repository link if different)*

---

### 2️⃣ Set Up Virtual Environment (Recommended)

```bash
# Create a virtual environment
python -m venv venv

# Activate it
# On Linux/macOS:
source venv/bin/activate

# On Windows:
.\venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

Only the **transformers** library is needed for this example.

```bash
pip install transformers
```

> *(If you used a `requirements.txt` file, you can instead run:)*  
> `pip install -r requirements.txt`

---

### 4️⃣ Run the Script

Execute the Python file:

```bash
python tokenizer_example.py
```

---

## 🖥️ Sample Output

Below is the exact sample output produced by the script:

<img width="1180" height="181" alt="image" src="https://github.com/user-attachments/assets/a0cfe25d-9d4a-40df-8c9b-86af18210a71" />


## 🧩 File Structure

```
hf-tokenizer-demo/
├── tokenizer_example.py
├── README.md
└── requirements.txt  (optional)
```

---

## 📚 Reference

- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers/)
- [GPT-2 Tokenizer Details](https://huggingface.co/transformers/model_doc/gpt2.html)

---

**✨ Author:** Madhumithra R  
**📅 Project Type:** Educational Demo  
**🧰 Tech Stack:** Python · Hugging Face Transformers
