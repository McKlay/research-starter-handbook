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

Proper citation is a mark of professionalism and respect. It shows that you’ve done your homework, that you value the contributions of others, and that you’re committed to building knowledge collaboratively. Mastering citation practices will make your writing stronger and your research more credible.

Citations show that:

- You’re building on credible, peer-reviewed work  
- You understand the state of the art  
- You know which ideas are yours—and which came from others

This chapter will help you **cite responsibly**, **format correctly**, and **stay organized**—so that your thesis, research papers, and presentations are all built on a strong foundation of attribution.

You’ll also learn how to streamline your workflow, avoid common mistakes, and use tools that make managing references much easier.

---

## Conceptual Breakdown

**🔹 What to Cite (and When)**

You should cite when:

Citation is about transparency. If a reader could reasonably wonder where an idea, method, or result came from, you should provide a reference. This helps others trace your intellectual path and builds trust in your work.

- An idea, method, result, or dataset comes from another paper  
- You paraphrase or summarize someone’s work  
- You reuse figures, tables, or even experimental setup  
- You're inspired by a framework, tool, or model implementation

> 💡 You *don’t* need to cite common knowledge (e.g., “deep learning models use backpropagation”).

When in doubt, ask your advisor or check published papers in your field to see what’s considered common knowledge.

---

**🔹 Common Citation Formats in CS**

| Format | Common In                             | Looks Like                              |
|--------|----------------------------------------|------------------------------------------|
| **IEEE**  | Engineering, CS, AI conferences       | [1] J. Smith, “Title,” *IEEE Trans. on X*, 2020. |
| **ACM**   | ACM conferences, SIG venues           | [Smith 2020]                             |
| **APA**   | Interdisciplinary, HCI, social science | Smith, J. (2020). *Title*. Journal Name. |

Each format has its own rules for author order, punctuation, and abbreviations. Always use the template or style file provided by your target venue to avoid formatting errors.

> 📌 Always check your target venue’s **template and formatting rules**. They usually provide `.cls` or `.bst` files for LaTeX.

If you’re using Word, citation plugins can help you switch between formats as needed. For LaTeX users, BibTeX and BibLaTeX are essential tools.

---

**🔹 Tools to Manage Your References**

| Tool        | What It Does                                                             |
|-------------|--------------------------------------------------------------------------|
| **Zotero**  | Collect, organize, tag, and cite references; integrates with Word/LibreOffice |
| **Mendeley**| Similar to Zotero, stronger PDF annotation features                      |
| **BibTeX**  | Plaintext reference format for LaTeX documents                           |
| **Overleaf**| Online LaTeX editor with built-in BibTeX integration                     |

Choose a tool that fits your workflow and writing environment. Many researchers use a combination (e.g., Zotero for collection, BibTeX for LaTeX writing). Explore plugins and integrations to make your process seamless.

> ✅ Pro Tip: Use **Zotero + BibTeX** for the best of both worlds: visual management and LaTeX compatibility.

Regularly back up your reference library and keep it organized with folders or tags by topic, project, or paper section.

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

Check your exported `.bib` file for errors or missing fields. Sometimes, imported entries from Google Scholar or other sources need manual cleanup.

> 🎯 You can also use Google Scholar to export BibTeX entries—but double-check for formatting errors.

If you’re collaborating, share your `.bib` file or use a shared reference manager to keep everyone on the same page.

---

**🔹 Citing Code and Tools**

When using open-source projects, APIs, or models:

Citing software and datasets is increasingly important in CS research. Many projects now provide a preferred citation format—use it whenever possible. If not, cite the original paper or describe the tool clearly in your methods section.

* Look for a **CITATION.txt** file in the GitHub repo
* If none, cite the original paper associated with the tool (e.g., “Transformers” → cite the BERT or HuggingFace paper)

> ⚠️ Don’t cite GitHub URLs without context. Always include author, year, title, and version if possible.

Properly citing code and tools helps others reproduce your work and gives credit to developers who support the research community.

---

## Self-Check Questions

1. Are you using a reference manager (Zotero, Mendeley, or BibTeX)?
2. Do you know your target venue’s citation format?
3. Have you double-checked for missing or incorrect citations in your drafts?

Take time to review your references before submitting any paper. Incomplete or incorrect citations can delay publication or weaken your credibility.

---

## Try This Exercise

> **Build Your Citation Workflow**
>
> 1. Install Zotero + browser connector
> 2. Add 5 papers you’ve read this week
> 3. Tag each by topic (e.g., `#LLM`, `#legalNLP`, `#transformers`)
> 4. Export to BibTeX and integrate into an Overleaf project

As you practice this workflow, you’ll find it easier to keep your references organized and ready for any writing project.

You now have a clean, searchable citation workflow—and a `.bib` file ready for use.

Update your reference library regularly and use tags or folders to keep track of sources for different sections of your thesis or papers.

---

## Researcher’s Compass

Citing is more than just “giving credit.”

It’s also a way to map the intellectual landscape of your field. Well-chosen citations show that you understand the context of your work and can guide readers to further information.

It’s how you build trust. It’s how you acknowledge the community.
And it’s how you show that your work **belongs** in the field.

> A well-cited paper says: *I know where I stand—and I know whose shoulders I’m standing on.*

Make citation a habit, not an afterthought. Your future self—and your readers—will thank you.

---