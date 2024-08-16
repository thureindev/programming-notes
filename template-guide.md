> [!IMPORTANT]
> Please make sure to review the [Disclaimer](./README.md#disclaimer) in README.md document for important information about the use of this repository.

# 1. **Document Template**

- Following is the example file structure. Feel free to adjust the template and structure based on your needs.

# [Title of the Conversation]
> [!NOTE]
> Title should be same as filename. filename should replace whitespaces with dash '-'

**Date:** YYYY-MM-DD  
**Keywords:** keyword1, keyword2, keyword3
> [!NOTE]
> Having formated date and keywords can be a great help when you search topics in previous conversations.

## [Conversation Keyword]
> keyword that defines the conversation topic, notes, headline, etc.

### [Username]
> User's question goes here

### [ChatAI]
> ChatAI's response goes here

### Example:
```markdown
# Asynchronous JavaScript

**Date:** 2024-03-16  
**Keywords:** async, javascript, programming

### thureindev
> You are my programming mentor. Explain asynchronous javascript with real code scenarios. 
> Also define asynchronous and synchronous in programming. 

### ChatGPT
> [Response goes here]

### thureindev
> What is the difference between using promises and async-await. 
> Aside from readability are there any technical differences?

### ChatGPT
> [Response goes here]
```

---

# 2. **File Structure**

- Following is the example file structure. Feel free to adjust the template and structure based on your needs.

```
my-study-tracking-repo/
│
├── README.md
| 
├── cooking/
| |
│ ├── how-to-choose-ingredients/
│ │ ├── how-to-select-spices.md
│ │ └── how-to-buy-fresh-produce.md
| |
│ ├── bakery-and-pastries/
│ │ ├── baking-basics.md
│ │ └── favorite-pie-recipes.md
| |
│ └── nutritious-breakfast/
│   ├── healthy-smoothies.md
│   └── overnight-oats.md
|
├── some-subject/
| |
| ├── sub-category/
│ | ├── title.md
│ | └── title.md
| |
| └── optional-date-prefix-filename/
|   ├── YYYY-MM-DD-title.md
|   └── YYYY-MM-DD-title.md
```

---

# 3. **Instructions for Use and Maintenance**

## 3.1 - **Setting Up the Repository:**
   - **Create the Repository:** Start by creating a new repository on GitHub.
   - **Clone the Repository:** Clone it to your local machine using:
     ```bash
     git clone https://github.com/thureindev/study-with-ai.git
     ```
   - **Set Up Folder Structure:** Create folders for each subject and sub-categories as shown in the file structure above.

## 3.2 - **Documenting Conversations:**
   - **Export Conversations:** Export your ChatGPT conversations to text files. You can copy and paste them into Markdown files in your repository.
   > [!TIP] 
   > Consider using a script to automate the export, copy and paste onto markdown actions.
   - **Label Conversations:** Reference the Markdown template to structure each file. Label questions with `### User` and answers with `### ChatGPT` or any label choice of yours.
   - **Add Metadata:** Include date and keywords at the beginning of each file for easier searching and indexing.
   > [!TIP] 
   > Having formated date and keywords can be a great help when you search topics in previous conversations.

## 3.3 - **Maintaining the Repository:**
   - **Daily Updates:** Regularly add new conversation logs. Create new files in the appropriate directories and follow the Markdown template.
   > [!NOTE] 
   > Consider using a script or creating a GUI for this action.
   - **Collaborating:** If working with others, make sure to pull changes frequently and push your updates to avoid conflicts. Communicate with collaborators about file naming conventions and structure.
   > [!NOTE] 
   > Again, a GUI app would help a lot. Yet, I haven't started working on it. 

## 3.4 - **Using Text Editor (VSCode):**
   - **Editing Markdown Files:** Open and edit Markdown files in VSCode (as it is my favourite text editor). You can preview the Markdown files by using the VSCode built-in preview feature.
   - **Code Snippets and Media:** Use VSCode's extension for Markdown to handle code snippets and media links easily.

## 3.5 - **Automation and Integration:**
   - **Automate File Naming:** Consider using a script to automate file naming based on the date. This can be a simple Python script or a shell script.
   - **Set Up Git Hooks:** Use Git hooks to automate tasks such as formatting or linting Markdown files before committing.

## 3.6 - **Search and Navigation:**
   - **Directory Structure:** Organize files into directories and subdirectories based on categories. Use descriptive filenames for easy navigation.
   - **Search:** Use GitHub's built-in search functionality to find specific topics or keywords within your repository.

---

***Feel free to adjust the template and structure based on your needs. If you want to collaborate more features on this project, just let me know!***

***Reach out to me at: thureindev@outlook.com***

---