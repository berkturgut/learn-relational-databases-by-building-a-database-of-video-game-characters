# Learning Relational Databases with Video Game Characters

This project follows the **Learn Relational Databases by Building a Database of Video Game Characters** course, aiming to learn SQL and relational database concepts by applying them to a real video game character database.

## 🚀 Project Overview

- **Real database application:** Information about 7 characters from the Mario universe, related tables, and sample queries.
- **SQL command history and tests:** All steps and query outputs are recorded in the `queryResults.log` file.
- **Study materials:** Anki flashcards and course dialogues are in the `learning-aids` folder.

## 📁 Folder Structure

```
├── .freeCodeCamp/              # Course framework and tests
├── .git/                       # Git repository data
├── .vscode/                    # VS Code settings
├── learning-aids/              # Study materials
│   ├── anki_cards_tr.apkg      # Turkish Anki flashcards
│   ├── dialogues.md            # Course dialogues and step-by-step 
│   └── index.md                # Topic summaries and key concepts
├── .bash_history               # Bash command history
├── .gitignore                  # Git ignore rules
├── .gitpod.yml                 # Gitpod configuration
├── bash log                    # Bash log file
├── bash_history_db             # Bash history database
├── CHANGELOG.md                # Changelog
├── coderoad.yaml               # Coderoad configuration
├── pg.log                      # PostgreSQL log file
├── queryResults.log            # All SQL commands and output logs
├── README.md                   # This documentation
├── query_result                # Query result file
├── tutorial.json               # Tutorial configuration
├── TUTORIAL.md                 # Tutorial documentation
```

## 🗄️ Database Structure

### Tables

- **characters:** Basic character info (name, homeland, favorite color)
- **more_info:** Extra info like birthday, height, weight
- **sounds:** Sound files for each character
- **actions:** In-game actions (run, jump, duck)
- **character_actions:** Which actions each character can perform (many-to-many relation)

### Sample Characters

| character_id | name   | homeland           | favorite_color |
|--------------|--------|-------------------|---------------|
| 1            | Mario  | Mushroom Kingdom  | Red           |
| 2            | Luigi  | Mushroom Kingdom  | Green         |
| 3            | Peach  | Mushroom Kingdom  | Pink          |
| 4            | Toad   | Mushroom Kingdom  | Blue          |
| 5            | Bowser | Koopa Kingdom     | Yellow        |
| 6            | Daisy  | Sarasaland        | Orange        |
| 7            | Yoshi  | Dinosaur Land     | Green         |

### Relationships

- Each character's extra info is stored in the `more_info` table (birthday, height, weight).
- Character sound files are in the `sounds` table, matched by character_id.
- Actions performed by characters are linked via `character_actions` to the `actions` table.

### Sample Query Outputs

- All basic character info, related sounds, actions, and extra info are shown step-by-step in the `queryResults.log` file.
- You can access all character details using JOIN operations between tables.

## 📚 Study Materials

- **Anki flashcards:** Turkish cards for reviewing SQL commands and concepts (`anki_cards_tr.apkg`).
- **Course dialogues:** All steps and explanations (`dialogues.md`).
- **Additional notes:** Short summaries and tips (`index.md`).

## 🛠️ Usage

1. **Review the database schema:** See table structures and relationships in the `queryResults.log` file.
2. **Practice SQL commands:** Reinforce your knowledge using the Anki flashcards.
3. **Follow the course steps:** Progress step-by-step with instructions in `learning-aids/dialogues.md`.

## 🎯 What I Learned

- Creating, inserting, updating, and deleting tables with SQL
- Building table relationships with PRIMARY KEY and FOREIGN KEY
- Using JOIN to fetch data from multiple tables
- Grouping and sorting data with GROUP BY and ORDER BY
- Applying data integrity constraints like UNIQUE and NOT NULL
- Generating automatic IDs with SEQUENCE and AUTO INCREMENT
- Practical use of INSERT, UPDATE, DELETE, and SELECT queries
- Managing related data such as characters, actions, and sounds in a real data model
- Analyzing SQL command outputs and debugging errors
- Database schema design

## 🤝 Contributing

Feel free to suggest improvements or share your own study materials!

## 📄 License

This project follows the [freeCodeCamp license](https://github.com/freeCodeCamp/learn-relational-databases-by-building-a-database-of-video-game-characters).

---

*My SQL learning journey with a relational database of Mario characters.*