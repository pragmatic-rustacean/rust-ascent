Purpose: Organized reference material on Rust concepts. My personal knowledge base.

Structure:
    notes/
        ├── fundamentals/
        │   ├── ownership.md
        │   ├── borrowing.md
        │   ├── lifetimes.md
        │   └── types.md
        ├── advanced/
        │   ├── async.md
        │   ├── macros.md
        │   ├── unsafe.md
        │   └── traits-deep-dive.md
        ├── ecosystem/
        │   ├── cargo.md
        │   ├── common-crates.md
        │   ├── testing.md
        │   └── clippy-and-rustfmt.md
        ├── patterns/
        │   ├── error-handling.md
        │   ├── builder-pattern.md
        │   ├── newtype-pattern.md
        │   └── type-state-pattern.md
        ├── tools/
        │   ├── vscode-setup.md
        │   ├── debugging.md
        │   └── profiling.md
        └── README.md               # Index of all notes

Template for each note:

# [Concept Name]
## Summary
[One-paragraph explanation in my own words]

## The Problem It Solves
[Why does this exist in Rust?]

## How It Works
[Detailed explanation with examples]

## Common Patterns
```rust
// Pattern 1: [Name]
[Code example]

// Pattern 2: [Name]
[Code example]
```

## Common Mistakes
```rust
// ❌ Don't do this
[Anti-pattern]

// ✅ Do this instead
[Correct pattern]

// Why: [Explanation]
```

## When to Use
- [Scenario 1]
- [Scenario 2]

## When NOT to Use
- [Scenario where it's wrong]

## Related Concepts
- [Link to related note]
- [Link to related note]

## Resources
- [Rust Book chapter]
- [Blog post that helped]
- [Video explanation]

## Examples in Real Projects
- [Where you used it in your code]
- [Example from popular crate]

## Questions I Still Have
- [Unanswered question 1]
- [Unanswered question 2]

---
Last Updated: [Date]