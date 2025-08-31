---
hide:
  - toc
---

# Chapter 11: Citing and Referencing

> *“Every citation is a signal: I’ve done the work, I’ve read the field, and I know where my ideas fit.”*

---

## Why This Chapter Matters

Citation isn’t just about avoiding plagiarism.  
It’s how you **enter the conversation** of research.

Citations show that:

- You’re building on credible, peer-reviewed work  
- You understand the state of the art  
- You know which ideas are yours—and which came from others

This chapter will help you **cite responsibly**, **format correctly**, and **stay organized**—so that your thesis, research papers, and presentations are all built on a strong foundation of attribution.

---

## Conceptual Breakdown

**🔹 What to Cite (and When)**

You should cite when:

- An idea, method, result, or dataset comes from another paper  
- You paraphrase or summarize someone’s work  
- You reuse figures, tables, or even experimental setup  
- You're inspired by a framework, tool, or model implementation

> 💡 You *don’t* need to cite common knowledge (e.g., “deep learning models use backpropagation”).

---

**🔹 Common Citation Formats in CS**

| Format | Common In                             | Looks Like                              |
|--------|----------------------------------------|------------------------------------------|
| **IEEE**  | Engineering, CS, AI conferences       | [1] J. Smith, “Title,” *IEEE Trans. on X*, 2020. |
| **ACM**   | ACM conferences, SIG venues           | [Smith 2020]                             |
| **APA**   | Interdisciplinary, HCI, social science | Smith, J. (2020). *Title*. Journal Name. |

> 📌 Always check your target venue’s **template and formatting rules**. They usually provide `.cls` or `.bst` files for LaTeX.

---

**🔹 Tools to Manage Your References**

| Tool        | What It Does                                                             |
|-------------|--------------------------------------------------------------------------|
| **Zotero**  | Collect, organize, tag, and cite references; integrates with Word/LibreOffice |
| **Mendeley**| Similar to Zotero, stronger PDF annotation features                      |
| **BibTeX**  | Plaintext reference format for LaTeX documents                           |
| **Overleaf**| Online LaTeX editor with built-in BibTeX integration                     |

> ✅ Pro Tip: Use **Zotero + BibTeX** for the best of both worlds: visual management and LaTeX compatibility.

---

**🔹 How to Generate a `.bib` File (for LaTeX Users)**

1. Add your papers to **Zotero**
2. Select the papers → Right click → Export as BibTeX  
3. Save as `refs.bib`  
4. In your `.tex` file:

```latex
\bibliographystyle{IEEEtran}
\bibliography{refs}
````

> 🎯 You can also use Google Scholar to export BibTeX entries—but double-check for formatting errors.

---

**🔹 Citing Code and Tools**

When using open-source projects, APIs, or models:

* Look for a **CITATION.txt** file in the GitHub repo
* If none, cite the original paper associated with the tool (e.g., “Transformers” → cite the BERT or HuggingFace paper)

> ⚠️ Don’t cite GitHub URLs without context. Always include author, year, title, and version if possible.

---

## Self-Check Questions

1. Are you using a reference manager (Zotero, Mendeley, or BibTeX)?
2. Do you know your target venue’s citation format?
3. Have you double-checked for missing or incorrect citations in your drafts?

---

## Try This Exercise

> **Build Your Citation Workflow**
>
> 1. Install Zotero + browser connector
> 2. Add 5 papers you’ve read this week
> 3. Tag each by topic (e.g., `#LLM`, `#legalNLP`, `#transformers`)
> 4. Export to BibTeX and integrate into an Overleaf project

You now have a clean, searchable citation workflow—and a `.bib` file ready for use.

---

## Researcher’s Compass

Citing is more than just “giving credit.”

It’s how you build trust. It’s how you acknowledge the community.
And it’s how you show that your work **belongs** in the field.

> A well-cited paper says: *I know where I stand—and I know whose shoulders I’m standing on.*

---