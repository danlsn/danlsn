# git-tags
___

## Summary
What on earth are git-tags and when should I use them???

### Version Naming
```text
# Do v1.2.3 over 1.2.3
```

### What are git tags?
> "Specific reference points in the Git history"
- They mark release points
- A tag does not change, they have no further history of commits

#### Annotated Tags
```sh
git tag -a v1.2.3 -m "Release version v1.2.3"
```
- Git recommends storing annotated tags over lightweight
- Stores extra metadata information
- Saved as full object in the git database


#### Lightweight Tags
```sh
git tag v1.2.3-lw
```
- Much like bookmarks for a commit
- Pointer to a commit
- Quick link creation to relevant commits

___
## References
- https://linuxhint.com/use-git-tags/
- https://www.atlassian.com/git/tutorials/inspecting-a-repository/git-tag