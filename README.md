# 🛒 Bano Qabil Ecommerce (BQE) — Fine-Tuning Dataset

**Task:** Customer WhatsApp & Support Message Intent + Entity Extraction (`bqe_order_intent_parser`)  
**Big idea:** Prompting gives the model *instructions*, RAG gives it *knowledge*, and fine-tuning gives it *habits* — teaching the model to consistently output clean, machine-readable JSON slips for Bano Qabil Ecommerce without chatty filler.

No GPU and no API key needed for dataset preparation and validation. Only Python's built-in modules (`csv`, `json`, `os`, `random`, `re`, `sys`, `collections`) are used.

---

## Steps to follow

python make_dataset.py bqe_order_intent_parser
python validate_dataset.py bqe_order_intent_parser