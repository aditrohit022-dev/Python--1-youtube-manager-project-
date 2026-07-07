# Python--1-youtube-manager-project-

A comprehensive YouTube video management application built with Python. This project demonstrates how to perform CRUD (Create, Read, Update, Delete) operations using different data persistence approaches, transitioning from local file handling to relational databases and NoSQL solutions.

## 📂 Project Structure

The repository is organized by implementation phases, showcasing different storage backends:

*   **`day 1` & `day 2`**: Initial core logic and CLI interface setups with custom success message handling.
*   **`with sqlite3`**: Relational database implementation using SQLite3 for structured data storage and formatted terminal outputs.
*   **`yutube maneger with mongodb`**: Advanced NoSQL integration connecting the manager application directly to a MongoDB database.

## 🚀 Features

*   **Add Videos:** Save new video titles, durations, and details.
*   **List Videos:** View all saved videos in a clean, readable terminal format.
*   **Update Videos:** Edit existing video details seamlessly.
*   **Delete Videos:** Remove videos from the database tracking system.
*   **Multiple Backends:** Explore implementations using SQLite3 or MongoDB.

## 🛠️ Prerequisites

Before running the application, ensure you have the following installed:
*   Python 3.x
*   MongoDB (for the MongoDB specific module)

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone


   cd Python--1-youtube-manager-project-
   ```

2. **Install dependencies:**
   *(Required if running the MongoDB version)*
   ```bash
   pip install pymongo
   ```

## 💻 Usage

Navigate into your preferred storage implementation folder and execute the main python file. 

**For SQLite3 version:**
```bash
cd "with sqlite3"
python youtube_manager.py
```

**For MongoDB version:**
```bash
cd "yutube maneger with mongodb"
python youtube_manager_mongodb.py
```









   
