Author Checklist: Manuscript Delivery Protocol

* **Enable Verified Commits:** If the author works locally, they must set up GPG signing on GitHub. This attaches a **"Verified"** badge to every update, proving it came from them and wasn't tampered with.  
* **Standardized Delivery via Web UI:** For authors who aren't technical, have them upload drafts directly via the **GitHub Web Interface**. This automatically uses GitHub’s server time for the timestamp, which is more credible in court than a local computer clock.  
* **Meaningful Commit Messages:** Avoid "update" or "asdf." Use specific descriptions like *"Chapter 5 completion \- First Draft"* or *"Final edits based on editorial review dated 2024-10-25."*  
* **Tag Significant Milestones:** Once a major draft is finished, have the author create a Git Tag (e.g., `v1.0-complete`). This "freezes" that version of the manuscript in the history.  
* **No Force-Pushing:** Authors must never use `git push --force`. This overwrites history and destroys the chronological "paper trail" you need for legal proof.  
* **File Integrity:** Ensure the manuscript is uploaded in a stable format (like `.docx`, `.pdf`, or `.md`). Avoid proprietary formats that might not be readable in 5–10 years.

This document is machine-generated  
License: public domain

