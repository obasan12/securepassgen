
```markdown
# 🔐 SecurePassGen-Advanced

**SecurePassGen-Advanced** is a Python package for generating secure, customizable passwords. It supports CLI usage and programmatic integration — perfect for developers who want a quick, flexible way to generate strong passwords.

---

## ✨ Features

- ✅ Choose password length
- 🔠 Toggle uppercase and lowercase letters
- 🔢 Include digits
- 🔣 Add symbols
- 💻 Use as CLI or import as a library

---

## 🚀 Installation

Install from PyPI:

```bash
pip install securepassgen-advanced
```

Or clone and install locally:

```bash
git clone https://github.com/obasan12/securepassgen.git
cd securepassgen
pip install .
```

---

## 🧪 Usage

### ▶️ CLI

After installation, run:

```bash
securepassgen-cli
```

You'll be prompted for:

- Length of password
- Whether to include uppercase, lowercase, digits, symbols

Example output:

```bash
🔐 SecurePassGen CLI 🔐
Enter password length: 12
Include uppercase? (y/n): y
Include lowercase? (y/n): y
Include digits? (y/n): y
Include symbols? (y/n): y

✅ Generated Password: T9#zvL!8n@qR
```

---

### 📦 Programmatic

Use it in your Python scripts:

```python
from securepassgen_advanced.generator import generate_password

password = generate_password(
    length=16,
    use_upper=True,
    use_lower=True,
    use_digits=True,
    use_symbols=True
)

print("Generated Password:", password)
```

---

## 📂 Project Structure

```
securepassgen_advanced/
├── __init__.py
├── cli.py
├── generator.py
```

---

## 🤝 Contributing

Pull requests are welcome! Here's how to contribute:

1. Fork this repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to your branch (`git push origin feature-name`)
5. Open a PR 🚀

---

## 📜 License

MIT License. See `LICENSE` file for details.

---

## 🙋‍♂️ Author

**cipherh4ck**  
📧 [emerickcipher@gmail.com](mailto:emerickcipher@gmail.com)  
🔗 [github.com/obasan12](https://github.com/obasan12)

---

## 🌐 PyPI

[securepassgen-advanced on PyPI](https://pypi.org/project/securepassgen-advanced/)
```
Thanks 😊 
