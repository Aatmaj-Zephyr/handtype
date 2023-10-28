<div align="center">
<h1> HandType </h1>

<h3 >Text-to-handwriting converter using fonts and image processing. </h3>

<img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FAatmaj-Zephyr%2Fhandtype&label=visitors&countColor=%2337d67a&style=for-the-badge&labelStyle=upper" />

</div>

---

## 📃 Table of Contents

1. [Aim](#aim)
2. [Getting started with HandType](#start)
3. [How to Contribute?](#contributing)
4. [Open for Hacktoberfest!](#hacktoberfest)
5. [Lint](#lint)
6. [License](#license)

<a name="aim"></a>

## Aim

**To convert text to handwriting in a seemingly authentic manner. To achieve a realistic conversion of typed text into handwritten-style content, creating a genuine vintage appearance through deep learning techniques, commonly referred to as 'deep faking.'**

<br>

**Example -**

![image](https://github.com/Aatmaj-Zephyr/handtype/assets/83284294/6144bccb-8576-41f9-86c8-f0f9e81002dc)

---

<a name="start"></a>

## Getting started with HandType

- Step 1: make your handwriting font at https://www.calligraphr.com/en/
- Step 2: Load font ttf file in colab
- Step 3: Load an old paper image (the more dirty, the more real it looks)
- Step 4: Enter the text you want
- Step 5: Set the fint size
- Step 6: Adjust the line spacing according to the line spacing in the paper
- Step 7: Download the image. Enjoy!
- Step 8: Star this repository and follow me on github😇

---

<a name="contributing"></a>

## ⚒ How to Contribute?

1. Find Issue

- go to the Issues tab of the repository and click on the issue you want to work on.
- Under that issue, write a comment asking permission for the admin of the repository to assign you the issue you want to work on.
- For example,
  ```
  I would like to work on this issue. Can you assign it to me?
  ```

2. Fork the Repository: <br>

- Click the "Fork" button in the upper-right corner of the repository's page. This creates a copy (fork) of the repository in your GitHub account.

3. **Clone the Repository**: Clone your forked repository to your local machine using the following command:

   ```bash

   git clone https://github.com/Aatmaj-Zephyr/handtype.git

   ```

4. Create a Branch: Create a new branch for your work with a descriptive name. Use the following format:

   ```bash
   git checkout -b feature/your-feature-name
   ```

   Prefix your branch name with "feature/" for feature additions, "bugfix/" for bug fixes, or choose an appropriate prefix that reflects the purpose of your branch.

5. Make Changes: Implement your changes and ensure that they adhere to our coding and style guidelines.

6. Commit Your Changes: Commit your changes with a meaningful commit message. Include a reference to relevant issues or pull requests.

   ```bash
   git commit -m "Add your descriptive commit message here"
   ```

7. Push to Your Fork: Push your branch to your forked repository on GitHub.

   ```bash
   git push origin feature/your-feature-name
   ```

8. Open a Pull Request: Go to the original repository on GitHub and click the "New Pull Request" button. Provide a clear and concise title and description for your pull request, and reference any related issues.

<a name="hacktoberfest"></a>

## 👨‍💻 Open for Hacktoberfest!

- Fix known issues
- Add new issues
- Ask for an issue to be assigned to you
- Make a Pull Request
- Bag a PR!

<a name="lint"></a>

## ⚒ Lint

This repository ensures the quality of Jupyter `.ipynb` notebooks by integrating a linting process using GitHub Actions. Here's a brief overview of how it works and why it's essential:

### Overview

Jupyter notebooks, while extremely versatile, pose a challenge when it comes to maintaining code quality. They intermingle code, output, and markdown in a JSON format, which makes traditional Python linting tools incompatible with `.ipynb` files out of the box.

To address this challenge, we use a tool called `nbqa`. `nbqa` acts as a bridge, allowing us to run popular Python linting tools, like `flake8`, directly on Jupyter notebooks.

### How It Works

1. **Setting Up Locally**: Before pushing to the repository, you can check for linting errors locally. To do this, ensure you have `nbqa` and `flake8` installed:

   ```bash
   pip install nbqa flake8
   ```

   With the tools installed, you can lint your notebooks:

   ```bash
      nbqa flake8 handtype.ipynb
   ```

This command will highlight any linting errors in your notebook based on PEP-8 standards.

2. **GitHub Actions Integration**: Every time you push your changes or create a pull request, GitHub Actions will automatically run the linting checks on all notebooks in the repository. This process ensures that any new or modified notebooks adhere to our coding standards.

### Why It's Important

Linting provides several benefits:

- Consistency: It ensures a uniform coding style across notebooks, which is especially important in collaborative projects.
- Error Reduction: Linting helps catch and reduce errors, leading to more reliable notebooks.
- Best Practices: Linting encourages adherence to best practices, resulting in better and more readable code.

We strongly encourage all contributors to run the linting checks locally before pushing, to ensure faster integration and fewer CI build failures.

<a name="license"></a>

## 📄 License

[MIT](https://github.com/Aatmaj-Zephyr/handtype/blob/main/LICENSE)

---

**Note:** Currently, work in progress of making the paper folded in the centre using image processing for a more faking effect. It currently is just a google collab file, but let's see what happens in the future. #goOpenSource

<h4> Happy coding!~ </h4>
