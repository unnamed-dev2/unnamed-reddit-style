# unnamed-reddit-style

/reddit-clone/
│
├── frontend/                    # Hosted on GitHub Pages
│   ├── index.html               # Main HTML
│   ├── style.css                # Custom CSS (Tailwind or vanilla)
│   ├── script.js                # Main JS that fetches from Cloud Functions
│   └── assets/                  # Icons, images, logos
│
├── functions/                   # Google Cloud Functions backend
│   ├── index.js                 # Entry point that exports your HTTP functions
│   ├── createPost.js            # Cloud Function for creating posts
│   ├── getPosts.js              # Cloud Function for fetching posts
│   ├── votePost.js              # Cloud Function for upvote/downvote
│   ├── firebase.json            # Firebase config (if using Firebase)
│   ├── .env                     # Your secret keys (not committed)
│   └── package.json             # Dependencies for backend functions
│
├── .github/
│   └── workflows/               # Optional CI/CD configs
│
├── README.md                   # Project overview and setup
└── .gitignore                  # Ignore node_modules, .env, etc.
