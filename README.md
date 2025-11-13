# Room AI

Finding compatible roommates is time-consuming and stressful. Current methods rely on Facebook, WhatsApp or word-of-mouth leading to poor matches,
lifestyle clashes or unsafe housing decisions. Room AI offers a smarter and transparent way of finding the perfect roommate

## Directory Structure

This is a high level view mainly for First Year students. An in-depth structure should be made accordingly by the people in charge of their module.

```
.
├── app
├── CONTRIBUTION.md
├── core
│   ├── agent.py
│   └── utils
├── frontend
└── README.md
```

- `app/` is for FastAPI - will include all models and endpoint logic
- `core/` includes all langgraph logic 
    - `utils/` is a part of core and will include definitions of all states, nodes and edges
    - `agent.py` os where the entire langgraph pipeline will be built
- `frontend/` is for all frontend logic
- `CONTRIBUTION.md` is a must read for all. All third year and second year students when delegating certain tasks can mention how they want the task done in this file.

## Quick Start

1. Fork the repository to your private account
2. Create a new a branch or work on the specific branch you forked
3. Clone the repo to your local machine
```git clone <repo url>```
3. Push all changes with proper descriptions (screenshots are optional)
4. Send a pull request. Assign a senior to check your pull request and ask for approval
