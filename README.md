# Open Source Practice Repository

Welcome to the Open Source Practice Repository! This is a space for you to learn the ropes of contributing to open-source projects. Whether you're a newbie or an experienced developer, this repo will guide you through the process.

If you are new to open source or hacktoberfest and want to learn more, check out [The Beginners Guide to Hacktoberfest](https://blog.timonwa.com/series/the-beginners-guide-to-hacktoberfest).

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Code of Conduct](#code-of-conduct)
- [License](#license)

## How to Contribute

### Fork the Repository

1. Click the "Fork" button in the upper right corner of this repository's page. This will create a copy of the repo in your GitHub account.

### Clone the Repository

1. Go to your forked repo on your GitHub account.
2. Click the "Code" button and copy the repository URL.
3. Open your terminal or command prompt.
4. Navigate to the directory where you want to store your local copy.
5. Run the following command, replacing `<repository-url>` with the URL you copied:
   
   ```
   git clone <repository-url>
   ```

### Create a New Branch

1. Navigate to the repository folder on your local machine:
   
   ```
   cd open-source-practice-repo
   ```
   
2. Create a new branch for your contribution. Give it a descriptive name:
   
   ```
   git checkout -b add-john-doe
   ```

### Make Your Changes

1. Now you can make your changes or additions to the project.

### Add Your Name to the Contributors List

1. Inside the `contributors` folder, you'll find a file named `names.md`. Open it.

2. Add your name to the file in alphabetical order under the respective section (A, B, C, etc.). Follow the format:
   
   ```
   - [Your Name](https://your-website-or-profile-link)
   ```

### Commit and Push Your Changes

1. Save your changes in the `names.md` file:

   ```
   git add .
   ```

2. Commit your changes with a meaningful message:

   ```
   git commit -m "Add [Your Name] to contributors"
   ```

3. Push your changes to your GitHub fork:
   ```
   git push origin add-john-doe
   ```

### Create a Pull Request

1. Go to your forked repository on GitHub.
2. Click the "Pull Request" button.
3. Follow the prompts to create your pull request.

## Code of Conduct

Please review our [Code of Conduct](link-to-code-of-conduct) before participating. We expect all contributors to adhere to it.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

Happy contributing! 🚀
