Here are the guidelines for submitting machine-generated texts, written in a clear, actionable format suitable for all users, followed by a simple supplement on saving files in Markdown.

---

## Guidelines: Submitting Machine-Generated Texts

Follow these rules exactly when uploading texts created by artificial intelligence (like ChatGPT, DeepSeek, Claude, or similar tools). This ensures that the machine-generated content is properly labeled, traceable, and preserved in a stable format.

### 1. Use the Correct Repository
- Upload your file **only** to the repository named **`machine-generated-texts`**.
- Do not upload machine-generated texts to other repositories (like those used for human-written manuscripts).

### 2. Preserve the Raw Output
- **Do not edit** the generated text in any way.
- Do not fix typos, do not rephrase sentences, do not add commentary or explanations within the text itself.
- The goal is to archive the output exactly as the machine produced it.

### 3. Include the Full Prompt
- At the very **beginning of the file**, include the exact prompt you gave to the machine.
- This allows others to understand what instruction led to the generated text and, if desired, to attempt to reproduce the result.
- Format it clearly, for example:
  ```
  Prompt: Write a short story about a cat who learns to play the piano.
  ```
  (Followed by the generated text.)

### 4. Identify the Language Model
- Clearly state which AI model generated the text. Be as precise as possible.
- Instead of just "ChatGPT," use the full model name, e.g., "ChatGPT-4 Turbo" or "DeepSeek-V3" or "Claude 3.5 Sonnet".
- This information is crucial because different models produce different kinds of output, and it helps track the evolution of machine-generated content over time.

### 5. Use Markdown Format
- All machine-generated texts must be saved in **Markdown format** (file extension: **`.md`**).
- Markdown is a simple, plain-text format that will remain readable for decades and works perfectly with GitHub.
- *See the supplement below for instructions on how to save a text as Markdown.*

---

## Supplement: How to Save a Text as Markdown

Markdown is a way to format text using simple symbols. It is saved as a plain text file, which means it does not contain complex hidden codes (like Word files do). This makes it ideal for long-term storage and version control.

### Step-by-Step Instructions

**If you are copying text from a word processor (like Microsoft Word or Google Docs):**

1.  **Copy the text** from your word processor.
2.  **Open a plain text editor**. Do not use Word.
    - On **Windows**: Use **Notepad** (search for it in the Start menu).
    - On **Mac**: Use **TextEdit**. **Important:** In TextEdit, go to the `Format` menu and select `Make Plain Text` *before* you paste.
3.  **Paste the text** into the plain text editor.
4.  **Save the file** with a name that ends in **`.md`** .
    - For example, name your file `cat-story.md` instead of `cat-story.txt`.
    - In the "Save as type" dropdown (if available), choose "All Files" or simply type the `.md` extension yourself.

**If you are copying text directly from a chat interface (like ChatGPT):**

1.  Select and copy the generated text.
2.  Open a plain text editor (Notepad or TextEdit as described above).
3.  Paste the text.
4.  Save the file with a **`.md`** extension (e.g., `output.md`).

### What About Formatting?

If the machine-generated text includes formatting like **bold text**, *italics*, or bullet points, you can keep the simple symbols that Markdown uses:

- `**bold**` will look like **bold**.
- `*italic*` will look like *italic*.
- `- item` creates a bullet point.

You do not need to do anything special; just leave the text as the machine provided it. If the machine outputs plain text without symbols, that is perfectly fine too.

**Remember:** The most important thing is that the file is a plain `.txt` file saved with the extension **`.md`** . This tells GitHub that it is a Markdown file and ensures it will be displayed correctly.

*This document is machine-generated.*
*License: public domain*
