## 🚀 Project Setup Command

Use the following command to initialize the Next.js project with all required configurations:

```bash
npx create-next-app@latest my-app --yes
```

## 📝 Cursor AI Resources

These resources are essential for configuring and utilizing the Cursor editor effectively for strong reasoning and task management.

### **Planning & Task Management**

  - **BRD/PRD Prompts for Reasoning Model & Creating `tasks.md`:**
    [https://chatgpt.com/share/67c5ee78-0b94-800d-b467-ceecdbf6ce70](https://chatgpt.com/share/67c5ee78-0b94-800d-b467-ceecdbf6ce70)
  - **Updating `tasks.md`:**
    ```bash
    Go through each story and Find the next story to work on. Review each unfinished story and correct issues if any. Then proceed to create or edit files to complete each story.     After you complete all the tasks in the story, update the file to check off any completed story.
    ```

    

-----

## 🏗️ Post-Functionality Development

Once core functionality is complete, use the following plans for quality assurance, planning, and design implementation.

### **Option 1: Planning and Prioritization**

1.  **Evaluate using UX Rubric:** Review the project against the rubric linked below.
      - **Rubric Video:** [https://youtu.be/5Lu7k2SShNw?t=748](https://youtu.be/5Lu7k2SShNw?t=748)
      - **UX Rubric Plan:** [https://gist.github.com/kleneway/10b3848d60553e794ada863d3393544e](https://gist.github.com/kleneway/10b3848d60553e794ada863d3393544e)
2.  **Create a Plan:** Develop a plan using the UX rubric guidelines.
3.  **Cherry-Pick:** Select and prioritize the **most important items** from the plan to build.

### **Option 2: Design Override (Cosmetic Changes)**

Alternatively, use this prompt to enforce a specific design aesthetic:

> 'Analyze my existing project, then override all CSS and visual styling to match the uploaded **design.md** specifications while preserving all functionality and HTML structure'

  - **Design Guidelines Reference:** [https://github.com/ankitpandey2708/dhbvn-web/blob/main/design.md](https://github.com/ankitpandey2708/dhbvn-web/blob/main/design.md)

-----

## 🧹 Code Cleanup and Security Audits

**Execute the following steps in the specified order, performing the entire cleanup process at least two times.**

### **1. Security & Data Audit**

  - **Browser Data Storage:** Check for any data being stored in the browser (e.g., Local Storage, Session Storage). **Confirm deletion with me first.**
  - **Data Exposure:** Check for any sensitive data being exposed in the browser (e.g., API keys, secrets).

### **2. Code Quality & Optimization**

1.  **Run Knip:** Execute the following command to find unused files, dependencies, and exports.
    ```bash
    npm run knip
    ```
2.  **Delete Unused Code :** If entire files need to be deleted, consolidate the list and provide a **single command** to delete multiple files at once (e.g., `rm file1.ts file2.tsx`).
3.  **Check for Code Duplication.**
4.  *Repeat Step 2.*
5.  **Check for Code Refactoring:** Identify and implement improvements for code structure, readability, and maintainability.
