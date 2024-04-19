---

# Text Summarization with Text Extraction Techniques

## Description
This Jupyter Notebook implements a text summarization tool using text extraction techniques in Python. It provides a simple graphical user interface (GUI) for users to input text and specify the desired number of sentences in the summary.

## Features
- Extractive text summarization technique
- GUI using `customtkinter` for user interaction
- Ability to specify the number of sentences in the summary

## Requirements
- Jupyter Notebook
- Python 3.x
- `spacy` library
- `customtkinter` library

## Usage
1. Open the Jupyter Notebook `text_summarization.ipynb`.
2. Run the notebook cells sequentially to understand the code.
3. Execute the cell containing theGui function (`The GUI`) to generate the GUI.
4. Enter the text you want to summarize into the input textbox.
5. Specify the desired number of sentences in the summary and click summarize button.
6. The summary will be displayed in the output textbox.

## Example
Here's a basic example of how to use the tool:

Input:
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam vestibulum sem eget ex vehicula, nec accumsan justo varius. Curabitur pharetra malesuada ultricies. Sed vel purus non est ultrices malesuada ac eu neque. Proin eu convallis arcu. Vivamus vel neque at arcu viverra rutrum. Integer maximus ultricies diam a vestibulum. Suspendisse potenti. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Integer semper leo justo, id finibus dolor facilisis et. Ut sit amet ligula vehicula, luctus ipsum vel, dapibus turpis. Mauris efficitur consequat magna id eleifend. Aliquam auctor justo at libero blandit auctor.
```

Output (with 2 sentences):
```
Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Integer semper leo justo, id finibus dolor facilisis et. Ut sit amet ligula vehicula, luctus ipsum vel, dapibus turpis.
```

## Credits
- [Spacy](https://spacy.io/) - For natural language processing capabilities
- [CustomTkinter](https://github.com/codesworth/customtkinter) - For customizing the appearance of Tkinter GUI

---
