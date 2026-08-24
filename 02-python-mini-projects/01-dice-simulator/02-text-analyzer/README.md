# Smart Text & Word Analyzer Tool

An interactive Python CLI application designed to clean, process, and analyze paragraph-level text inputs. It generates real-time text analytics, identifies word frequencies, and features dynamic word lookups.

---

## Project Overview & Objective

The main goal of this project is to apply Python string handling, collection data structures, and dictionary-based algorithms to turn raw text into structured analytics.

### Key Features:
- **Punctuation Cleaning:** Removes punctuation marks using `string.punctuation` for accurate word parsing.
- **Detailed Analytics:** Calculates total words, character counts (with/without spaces), longest/shortest words, and average word length.
- **Top 3 Frequent Words:** Tracks word counts using Python Dictionaries and extracts top occurrences with `sorted()` and `lambda`.
- **Interactive Word & Symbol Search:** Allows users to query specific word frequencies or punctuation mark occurrences directly from the analyzed text.
- **Robust Input Handling:** Prevents empty inputs and manages continuous tool usage through replay prompts.

---

## Python Concepts Applied

- **String Manipulation:** `split()`, `strip()`, `lower()`, `replace()`, and `translate()`.
- **Data Structures:** `List` for word sequences and `Dictionary` (`dict`) for frequency mapping.
- **Built-in Functions & Sorting:** `len()`, `max()`, `min()`, and `sorted()` with `lambda` functions.
- **Control Flow:** `while` loops for continuous flow and conditional statements (`if-else`).
- **Standard Libraries:** `string` module for pre-defined punctuation sets.

---

## How to Run

1. Clone or download this repository.
2. Open the `02-text-analyzer.ipynb` file in **Jupyter Notebook** or **VS Code**.
3. Run all cells sequentially to execute the analyzer tool.

```python
analyze_text()
