Purpose: Curated list of resources that actually helped me.

Structure:
    resources/
        ├── README.md               # Master list
        ├── books.md
        ├── articles.md
        ├── videos.md
        ├── crates.md
        ├── tools.md
        └── people-to-follow.md

Template:
    # Resources That Actually Helped

**Note:** These are resources I personally used and found valuable.
Your mileage may vary, but these worked for me.

## 📚 Books
[Link to books.md](books.md)

**Top 3:**
1. The Rust Programming Language (The Book)
2. Rust for Rustaceans
3. [Your third favorite]

## 📝 Articles & Blogs
[Link to articles.md](articles.md)

**Must-reads:**
- [Article that changed your understanding]
- [Blog post that solved a specific problem]

## 🎥 Videos & Talks
[Link to videos.md](videos.md)

## 📦 Essential Crates
[Link to crates.md](crates.md)

## 🛠️ Tools I Use Daily
[Link to tools.md](tools.md)

## 👥 People Worth Following
[Link to people-to-follow.md](people-to-follow.md)

## 🌐 Communities
- Rust Users Forum
- Rust Zulip
- Symposium Zulip
- [Others you're active in]

## 💡 Pro Tips

### For Learning
- [Technique that works for you]
- [Pattern that helped]

### For Contributing
- [Advice for first-timers]
- [How to find good projects]

### For Staying Motivated
- [What helps when you're stuck]
- [How to avoid burnout]

---

*Updated: [Date]*
*These resources got me from Day 1 to Day [X]*

---
books.md template:
# Books

## Currently Reading
- **[Title]** by [Author]
  - Status: Page X / Y
  - Why: [What you hope to learn]
  - Rating so far: [X/5]

## Completed

### The Rust Programming Language (The Book)
- **Author:** Steve Klabnik & Carol Nichols
- **Link:** https://doc.rust-lang.org/book/
- **When Read:** [Date range]
- **Rating:** 5/5
- **Key Takeaways:**
  - [Insight 1]
  - [Insight 2]
- **Best For:** Absolute beginners
- **Pro Tip:** Read chapters 4, 10, 15 twice

### [Next Book]
- **Author:**
- **When Read:**
- **Rating:**
- **What I learned:**
- **Would I recommend:** Yes/No and why

## Want to Read
- [ ] [Book title]
- [ ] [Book title]

---
*Updated: [Date]*

---
crates.md template:
# Essential Crates

Crates I use regularly and recommend.

## CLI Development
- **clap** - Command-line argument parsing
  - Why: Most popular, great macros
  - Alternatives: structopt (now merged into clap)
  
- **colored** - Terminal colors
  - Why: Makes CLI output beautiful
  - Used in: [Your project]

## Web Development
- **axum** - Web framework
  - Why: Ergonomic, built on tokio
  - Learning curve: Medium
  - Used in: [Your project]

## Error Handling
- **anyhow** - Easy error handling
  - Why: Great for applications
  - Alternative: thiserror (for libraries)

## Testing
- **proptest** - Property-based testing
  - Why: Catches edge cases
  - Used in: [Your project]

## Utilities
- **serde** - Serialization/deserialization
  - Why: JSON, YAML, TOML support
  - Essential: Yes

[Continue for each crate you actually use]

---
*This is what's actually in my Cargo.toml files*
