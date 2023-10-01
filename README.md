# Exercise 2: Publishing Jupyter Notebooks with Quarto 📔

**Objective**: Explore the power of Quarto and GitHub to seamlessly publish Jupyter notebooks. By the end of this exercise, you will have your own live, web-accessible Jupyter notebook and experience in managing and updating its content.

### Instructions:

1. **Fork the Project**:
   - Fork the target [repository](https://github.com/grundkurs-git/exercise-2). This creates your personal copy of the project on GitHub.

2. **Launch GitHub Codespace**:
   - Navigate to your forked repository.
   - Click on the green "Code" button and from the dropdown, select "Open with Codespaces". This initiates a cloud-based development environment directly within GitHub, tailored for the repository.

3. **Publish with Quarto**:
   - Within your Codespace terminal, enter the command:
     ```
     quarto publish gh-pages
     ```
   - This command instructs Quarto to compile and publish your notebook content to the `gh-pages` branch, which GitHub automatically uses to host web-accessible content.

4. **Modify the Jupyter Notebook**:
   - In your Codespace, locate the `hello.ipynb` Jupyter notebook and open it.
   - Make some changes or additions to the notebook content. Feel free to get creative!
   - Save your changes once done.

5. **Commit & Push**:
   - In the source control panel of Codespaces (typically an icon that looks like a branching tree), stage your changes and commit them with a descriptive message.
   - Push your committed changes to your GitHub repository.

6. **Review Your Live Notebook**:
   - Once the changes are pushed, navigate to the URL associated with the `gh-pages` of your forked repository (typically in the format `https://[your-username].github.io/[repository-name]/`). You should see the updated Jupyter notebook content live!

### Reflection:

1. How do Codespaces enhance the experience of remote development and publishing?
2. Discuss the significance of the `gh-pages` branch in the context of GitHub.

Great work! 🌟 Leveraging Quarto and GitHub functionalities, you've just broadened your toolkit for publishing interactive content online. Dive deeper, and explore more possibilities!
