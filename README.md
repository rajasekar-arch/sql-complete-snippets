# sql-complete-snippets README

This is the README for your extension "sql-complete-snippets".

# SQL Snippets for VS Code

[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/YourPublisher.SQLSnippets?style=for-the-badge&label=Installs)](https://marketplace.visualstudio.com/items?itemName=YourPublisher.SQLSnippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/YourPublisher.SQLSnippets?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=YourPublisher.SQLSnippets)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

An essential VS Code extension for developers working with SQL. This extension provides a rich collection of SQL snippets covering DDL, DML, DQL, DCL, and TCL commands, designed to boost your productivity by auto-completing common SQL queries.

## ✨ Features

- **Comprehensive Snippets:** Access a wide range of SQL commands for Data Definition Language (DDL), Data Manipulation Language (DML), Data Query Language (DQL), Data Control Language (DCL), and Transaction Control Language (TCL).
- **Intuitive Prefixing:** Simply type `sql` followed by a common SQL keyword (e.g., `select`, `delete`, `update`, `create`, `grant`, `commit`) to get a curated list of related snippets.
- **Accelerated Development:** Reduce repetitive typing and minimize syntax errors, allowing you to focus more on your database logic.
- **Contextual Suggestions:** Snippets are designed to offer useful starting points for various SQL operations.

## 🚀 Installation

1.  Open VS Code.
2.  Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
3.  Search for "SQL Snippets" (or "Your Publisher Name SQL Snippets").
4.  Click **Install**.

Alternatively, install directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=YourPublisher.SQLSnippets).

## 💡 Usage

Using the snippets is straightforward and designed for maximum efficiency:

1.  Open any file with a SQL language mode (e.g., `.sql` file, or within a `.js`/`.ts` file if you have a SQL formatter/syntax highlighter extension that recognizes embedded SQL).
2.  Start typing the prefix `sql` followed by the SQL command you need.
3.  **Examples:**

    - To get a `SELECT` statement: Type `sql-select`
    - To get an `INSERT` statement: Type `sql-insert`
    - To get an `UPDATE` statement: Type `sql-update`
    - To get a `DELETE` statement: Type `sql-delete`
    - To get a `CREATE TABLE` statement: Type `sql-create` or `sql-createtable`
    - To get a `GRANT` statement: Type `sql-grant`
    - To get a `COMMIT` statement: Type `sql-commit`

    The IntelliSense suggestions will appear as you type, guiding you to the specific snippet you need.

4.  Select the desired snippet from the list, and it will be inserted into your code. Use `Tab` to navigate through the placeholder values (e.g., table names, column names, conditions) and customize the query.

### Snippet Examples (Non-exhaustive)

Here are just a few examples of the types of snippets you'll find:

#### DDL (Data Definition Language)

- `sql-create`: `CREATE TABLE`, `CREATE INDEX`, `CREATE VIEW`, `CREATE DATABASE`
- `sql-drop`: `DROP TABLE`, `DROP INDEX`, `DROP VIEW`, `DROP DATABASE`
- `sql-alter`: `ALTER TABLE ADD COLUMN`, `ALTER TABLE MODIFY COLUMN`, `ALTER TABLE DROP COLUMN`

#### DML (Data Manipulation Language)

- `sql-insert`: `INSERT INTO ... VALUES`, `INSERT INTO ... SELECT`
- `sql-update`: `UPDATE ... SET ... WHERE`
- `sql-delete`: `DELETE FROM ... WHERE`
- `sql-merge`: `MERGE INTO ... USING ... ON`

#### DQL (Data Query Language)

- `sql-select`: `SELECT * FROM`, `SELECT ... FROM ... WHERE`, `SELECT ... JOIN ... ON`, `SELECT ... GROUP BY`, `SELECT ... ORDER BY`, `SELECT ... LIMIT/OFFSET`
- `sql-distinct`: `SELECT DISTINCT`
- `sql-union`: `UNION ALL`

#### DCL (Data Control Language)

- `sql-grant`: `GRANT SELECT ON ... TO ...`
- `sql-revoke`: `REVOKE INSERT ON ... FROM ...`

#### TCL (Transaction Control Language)

- `sql-begin`: `BEGIN TRANSACTION` (or `BEGIN WORK`)
- `sql-commit`: `COMMIT` (or `COMMIT WORK`)
- `sql-rollback`: `ROLLBACK` (or `ROLLBACK WORK`)
- `sql-sp`: `SAVEPOINT`

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 🐛 Issues and Feedback

If you encounter any bugs, have feature requests, or just want to provide feedback, please open an issue on the [GitHub repository](https://github.com/YourGitHubUsername/your-repo-name/issues).

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🔗 Links

- [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=YourPublisher.SQLSnippets)
- [GitHub Repository](https://github.com/YourGitHubUsername/your-repo-name)

---

**Happy Coding with SQL Snippets!**
