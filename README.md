# PEFT-for-Text-summarization

This repository demonstrates the parameter-efficient fine-tuning (PEFT) of language models for text summarization tasks using LoRA (Low-Rank Adaptation). We utilize T5 and Facebook's BART-large-cnn models, fine-tuning them on the SAMSum dataset for efficient and effective summarization, all within a single Jupyter Notebook.

## Learning Objectives

By the end of this experiment, you will be able to:
- Understand the workings of LoRA, a parameter-efficient fine-tuning method.
- Fine-tune T5 and Facebook's BART-large-cnn on the SAMSum dataset for summarization using LoRA.
- Push the fine-tuned LoRA adapter to the Hugging Face model hub.
- Load the fine-tuned adapter from the hub for inference.

## Dataset Description

The SAMSum dataset contains about 16,000 messenger-like conversations, each with summaries. These were created by English-fluent linguists to reflect real-life conversations and are annotated with summaries in the third person.

### Data Splits
- **Train**: 14,732 samples
- **Validation**: 818 samples
- **Test**: 819 samples

### Data Fields
- `dialogue`: Text of the dialogue.
- `summary`: Human-written summary of the dialogue.
- `id`: Unique ID of an example.

### Example
```json
{
  "id": "13818513",
  "summary": "Amanda baked cookies and will bring Jerry some tomorrow.",
  "dialogue": "Amanda: I baked cookies. Do you want some?\r\nJerry: Sure!\r\nAmanda: I'll bring you tomorrow :-)"
}
```

## How to Use

### Requirements
Ensure you have Python and the following packages installed:
- `transformers`
- `torch`
- `datasets`

You can install these packages using pip:
```bash
pip install transformers torch datasets
```

### Getting Started

1. **Clone the Repository:**
```bash
git clone https://github.com/Praveen76/PEFT-for-Text-summarization.git
cd PEFT-for-Text-summarization
```

2. **Open the Jupyter Notebook:**
   - Launch Jupyter Notebook in the project directory:
   ```bash
   jupyter notebook
   ```
   - Open the `PEFT_for_Text_Summary.ipynb` file.

3. **Follow the Instructions in the Notebook:**
   - The notebook includes detailed steps for loading the data, training the model, pushing the adapter to the Hugging Face Hub, and running inference.
---

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.

---

## License

This project is licensed under the [MIT License](LICENSE).

# Issues:
If you encounter any issues or have suggestions for improvement, please open an issue in the Issues section of this repository.

---
# Contact:
The code has been tested on Windows system. It should work well on other distributions but has not yet been tested. In case of any issue with installation or otherwise, please contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/)

Happy coding!!

---
## **About Me**:
I’m a seasoned Data Scientist and founder of [TowardsMachineLearning.Org](https://towardsmachinelearning.org/). I've worked on various Machine Learning, NLP, and cutting-edge deep learning frameworks to solve numerous business problems.
