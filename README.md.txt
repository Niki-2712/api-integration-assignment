# API Integration Project

This project fetches data from the JSONPlaceholder REST API using two endpoints:
- /posts
- /users

## Features
- Cache API responses in a local file (cache.json)
- List posts with optional filtering (userId)
- Show detailed view for a post by ID
- Error handling for:
  - Network issues
  - Timeouts
  - Invalid API responses
  - Malformed JSON

## Setup
1. Install dependencies:
   pip install -r requirements.txt

2. Run the project:
   python app.py

## Endpoints Used
- https://jsonplaceholder.typicode.com/posts
- https://jsonplaceholder.typicode.com/users

## Notes
- Only first 10 posts are printed for readability.
- Cache updates automatically on first run.
