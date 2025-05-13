# 📝 Rust Terminal To-Do List App

A simple command-line To-Do list application written in Rust. This app allows users to add tasks, list them, and mark them as completed — all from the terminal.

## 📦 Features

- Add new to-do items
- View the current list of items
- Mark items as completed
- Exit the application gracefully

## 🚀 Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (Make sure you have Rust installed)

### Running the App

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/rust-todo-app.git
   cd rust-todo-app
    ```

2. Run the app using `cargo`:

   ```bash
   cargo run
   ```

3. Follow the on-screen menu options.

## 🖥️ Usage Example

```bash
1. Add Item
2. List Items
3. Complete Item
4. Exit
```

### Sample Interaction

```
1. Add Item
Enter the title of the new item:
Buy groceries
Added: Buy groceries

2. List Items
Your to-do list:
[ ] 1 - Buy groceries

3. Complete Item
Enter the ID of the completed item:
1
Completed: Buy groceries

2. List Items
Your to-do list:
[X] 1 - Buy groceries
```

## 📂 Project Structure

* `src/main.rs`: Main application logic

## 📄 License

[MIT License](LICENSE).
