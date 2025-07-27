# 📚 Library Inventory Query Explorer

A simple MongoDB-powered backend project to manage and query a collection of book data. This repo showcases advanced query operations using operators like `$and`, `$or`, and `$exists`, with focus on real-world troubleshooting and clean data design.

## 🔍 Features

- Filter books using compound conditions (`$and`, `$or`)
- Identify incomplete data with `$exists` checks
- Learn to debug and refine queries with typo analysis (e.g., `grnre` vs `genre`)
- Output example documents with real structure (ObjectId + metadata)

## 🛠️ Tech Stack

- **Database**: MongoDB
- **Backend (optional extension)**: Express.js for REST API layer
- **Data Format**: JSON documents


##✨ Improvements
Use $rename to fix typo in grnre → genre

Add input validation and schema enforcement (e.g., Mongoose if using Express)

Include field projections for cleaner client-side responses

##🚀 Getting Started
Clone repo

Run MongoDB shell or connect via Compass

Insert data and experiment with query logic

Extend with Express routes to expose endpoints (GET, POST, etc.)

##📬 Feedback
Feel free to reach out or fork this project if you're curious to extend it. Queries welcome, questions celebrated!
