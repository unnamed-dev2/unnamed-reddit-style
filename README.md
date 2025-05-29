# unnamed-reddit-style

/reddit-clone/
│
├── index.html               # GitHub Pages entry point (must be in root)
│
├── frontend/                # All static assets and logic
│   ├── style.css            # Styling
│   └── script.js            # Frontend logic and API calls
│
├── backend/                 # Google Cloud Functions (Python-based)
│   ├── main.py              # Entrypoint for routing (Flask app or similar)
│   ├── create_post.py       # Create post handler
│   ├── get_posts.py         # Fetch posts handler
│   ├── vote_post.py         # Voting handler
│   ├── requirements.txt     # Python dependencies for GCF
│   └── README.md            # Optional backend info
│
└── .gitignore               # Typical ignores (e.g., __pycache__, etc.)
