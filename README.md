# LLaMA Factory Guide 🦙⚙️

This notebook is a quick guide to **training and fine-tuning LLaMA models** using [LLaMA Factory](https://github.com/hiyouga/LLaMA-Factory).

## 🚀 Usage
```bash
# Clone repo & install
git clone https://github.com/hiyouga/LLaMA-Factory.git
cd LLaMA-Factory
pip install -r requirements.txt

# Open the notebook
jupyter notebook llama_factory_guide.ipynb

# Run training
llamafactory-cli train examples/train_lora/your_config.yaml
