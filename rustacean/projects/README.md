Purpose:
 All the Rust code I write while learning. My portfolio of progress.

Structure:
projects/
├── cli-tools/
│   ├── todo-cli/           # Simple todo app
│   ├── file-organizer/     # Organize files by type
│   └── git-stats/          # Git repo statistics
├── web-experiments/
│   ├── rust-api-server/    # REST API with Axum
│   └── websocket-chat/     # Real-time chat
├── learning-exercises/
│   ├── ownership-practice/
│   ├── async-experiments/
│   └── macro-playground/
├── contributions/
│   ├── symposium/          # Clone for contributing
│   ├── other-project/
│   └── CONTRIBUTIONS.md    # Log of all contributions
└── personal-tools/
    ├── dev-setup-script/
    └── rust-snippets/

What goes here:
1. Learning Projects (/learning-exercises/)
    Small experiments to understand concepts:
    ownership-practice/
        ├── Cargo.toml
        ├── src/
        │   ├── main.rs             # Experiments with ownership
        │   ├── borrowing.rs        # Borrow checker practice
        │   └── lifetimes.rs        # Lifetime scenarios
        └── README.md               # What you learned
2. Portfolio Projects (/cli-tools/, /web-experiments/)
    Real applications:
    todo-cli/
        ├── Cargo.toml
        ├── src/
        │   ├── main.rs
        │   ├── commands.rs
        │   ├── storage.rs
        │   └── lib.rs
        ├── tests/
        │   └── integration_tests.rs
        ├── README.md               # How to use it
        ├── CHANGELOG.md            # What you added/fixed
        └── screenshots/
            └── demo.png

3. Contribution Workspace (/contributions/)
    Clones of projects you're contributing to:
    contributions/
        ├── symposium/              # Git clone of project
        │   └── [their structure]
        ├── my-symposium-notes.md   # Your understanding of codebase
        └── CONTRIBUTIONS.md        # Track all your PRs

4. Personal Tools (/personal-tools/)
    Scripts and tools that make my life easier:
    Dev environment setup scripts
    Custom cargo commands
    Automation tools
    Code snippets library
    project-name/
        ├── Cargo.toml              # Dependencies, metadata
        ├── README.md               # What it does, how to use
        ├── src/                    # Source code
        ├── tests/                  # Test suite
        ├── examples/               # Usage examples (optional)
        ├── docs/                   # Additional docs (optional)
        └── LEARNINGS.md            # What you learned building it

