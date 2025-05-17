# DeepSeek Code Generator

Generate Python code with inline comments from natural language prompts using the `deepseek-ai/deepseek-coder-1.3b-base` model with a Gradio interface.

## 🚀 Features

- Python code generation from natural language
- Uses DeepSeek Coder 1.3B model
- Gradio web interface for interaction
- CPU-based (can be modified for GPU)

## 📦 Requirements

- Python 3.8+
- `torch`
- `transformers`
- `gradio`

## 🛠 Installation

```bash
git clone (https://github.com/Agent47c/DeepSeek_Code_Generator.git   )
cd deepseek-code-generator
pip install torch transformers gradio
```
## Set your Hugging Face token if required:
```bash
export HF_HOME="your_token_here"
```
## ▶️ Run the App
```bash
python app.py
```
## 💡 Example Prompt
```bash
Write a Python function to calculate factorial using recursion with inline comments.
```
## Demo Screenshot
![App UI showing code generation output](/Demo.png)

## 📄 License
MIT License

## Acknowledgements

- [DeepSeek](https://huggingface.co/deepseek-ai)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers)
- [Gradio](https://gradio.app)
