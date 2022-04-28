# Conventions: Commit Messages
___
## Summary
Try to do things right. Create commits as if you are working for an actual company. Be professional in all you do.

## Structure

```text
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Case
- Write first line in lowercase (?)

### Types
```md
1. Fix: patches a bug
2. Feat: introduces a new feature
3. Build: 
4. Chore: 
5. CI: ???
6. Docs: add or edit docs
7. Style: linting and reformatting
8. Refactor: eg. renaming variable, extracting methods
9. Revert: undoing mistakes???
10. Perf: performance improvements???
11. Test: add tests
```

### Breaking Changes
```md
Commit message with !
feat!: introduces a new breaking feature
```

### Footer
```md
Resolves: #123
Fixes Issue: ???
```

## cbeams - How to Write a Git Commit Message
```md
1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
   - If applied, this commit will {{ subject_line }}
6. Wrap the body at 72 characters
7. Use the body to explain _what_ and _why_ vs. _how_
```

## References
- https://cbea.ms/git-commit/
- 
