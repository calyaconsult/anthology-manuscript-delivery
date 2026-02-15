# A Simple Guide: How to Upload to GitHub

Follow these steps exactly to make sure your upload has a safe, official timestamp.

1. **Go to the Website**  

   - Open your web browser and go to the GitHub repository address you were given. (This link will look something like: `github.com/Project-Name/...`). You will need to be logged into your GitHub account.

2. **Find the Upload Button**  

   - Look for a button that says **"Add file"** (it's usually near the top right of the file list). Click it, then choose **"Upload files"** from the dropdown menu.

3. **Upload Your Document**  

   - Drag and drop your manuscript file into the browser window, or click "choose your files" to find it on your computer.

4. **Write a Clear Note (Commit Message)**  

   - You will see a small form at the bottom of the page. In the first box, write a short, clear note about what you are uploading. For example:  
     - `First draft of Chapter 1`  
     - `Final version after edits`  
   - **Avoid** writing things like "update" or "asdf" – this helps us track the history later.

5. **Save (Commit) the Upload**  

   - Make sure the option **"Commit directly to the main branch"** is selected.  
   - Click the green **"Commit changes"** button.

6. **Check the Timestamp**  

   - That's it\! The file is now uploaded. GitHub has automatically recorded the exact date and time of your upload. You have successfully created a permanent, time-stamped record of your draft.

# For Advanced Users: Manuscript Delivery Protocol

**Secure Your Account:** Enable two-factor authentication (2FA) on GitHub to prevent unauthorized access that could alter timestamps.

**For Maximum Timestamp Reliability (recommended):**

- Upload drafts directly via the **GitHub Web Interface**. This records the exact server time, which is more credible than a local clock.  
- After upload, note the commit hash and timestamp (visible in the commit history) and store them externally (e.g., in a secure log).

**If Working Locally (advanced users only, not recommended):**

- Set up **GPG signing** (upload your public key to GitHub) to get a "Verified" badge. This proves authorship and integrity but **does not secure the timestamp**—the local commit date can be faked.  
- To mitigate, push immediately after committing; GitHub will display a "Pushed" time that can be used as a reference.  
- Never use `git commit --date` to manipulate timestamps.

**Use Meaningful Commit Messages:** Avoid vague messages like "update." Use specific descriptions, e.g., *"Chapter 5 completion \- First Draft" or "Final edits per editorial review 2024-10-25."* This aids future audits.

**Tag Significant Milestones:** When a major draft is complete, create a **Git Tag** (e.g., `v1.0-complete`) via the command line or a **GitHub Release** (recommended). This marks the exact commit.

**Protect the History:**

- **Never use `git push --force`** on shared branches—it erases history.  
- Repository owners should enable **branch protection rules** to block force-pushes and optionally require signed commits.

**Choose Stable File Formats:** Use widely readable formats like `.pdf` (preferably PDF/A), `.md`, or `.docx`. Avoid obscure or proprietary formats that may become unreadable.

**Consider External Timestamping (Optional but Recommended for Legal Proof):** For critical documents, use a service like **OpenTimestamps** to anchor the file hash (or commit hash) in a blockchain. This provides independent, immutable proof of existence prior to a given time.

**Verify Your Submission:** After uploading, visit the repository on GitHub, locate your commit, and confirm the timestamp and content are correct. Take a screenshot or record the details for your records.

*This document is machine-generated.*
*License: public domain*
