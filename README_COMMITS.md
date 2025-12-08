# 1Panel Commit Hashes: v2.0.13 to v2.0.14

This directory contains the list of commit hashes from the 1Panel project between versions v2.0.13 and v2.0.14.

## Files

### 1. `commit_hashes_v2.0.13_to_v2.0.14.txt`
A plain text file containing just the commit SHA hashes, one per line. This is useful for scripts or automated processing.

**Format:**
```
<commit-sha>
<commit-sha>
...
```

**Usage Example:**
```bash
# Count commits
grep -v "^#" commit_hashes_v2.0.13_to_v2.0.14.txt | grep -v "^$" | wc -l

# Process each commit
while read -r commit; do
  [[ "$commit" =~ ^# ]] && continue
  [[ -z "$commit" ]] && continue
  echo "Processing commit: $commit"
  # Your processing logic here
done < commit_hashes_v2.0.13_to_v2.0.14.txt
```

### 2. `commit_details_v2.0.13_to_v2.0.14.md`
A Markdown file containing the commit hashes along with their commit messages. This provides more context about what each commit does.

**Contents:**
- Source URL to the GitHub compare page
- Total number of commits
- List of commits with SHA and message
- Additional notes

## Summary

- **Repository:** [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel)
- **Version Range:** v2.0.13 → v2.0.14
- **Total Commits:** 93
- **Date Generated:** 2025-12-08
- **Source:** https://github.com/1Panel-dev/1Panel/compare/v2.0.13...v2.0.14

## Version Details

- **v2.0.13 Commit:** `217d780ed1820178a8d54def6d4b4189c1e78afd`
- **v2.0.14 Commit:** `b3350b54b3f885a03674b86642b9f1ff73cfb43f`

## Notes

The commits are listed in chronological order from newest (v2.0.14) to oldest (commits right after v2.0.13). All 93 commits represent changes that are included in v2.0.14 but were not part of v2.0.13.

## Related Links

- [1Panel GitHub Repository](https://github.com/1Panel-dev/1Panel)
- [Compare v2.0.13...v2.0.14](https://github.com/1Panel-dev/1Panel/compare/v2.0.13...v2.0.14)
- [v2.0.13 Release](https://github.com/1Panel-dev/1Panel/releases/tag/v2.0.13)
- [v2.0.14 Release](https://github.com/1Panel-dev/1Panel/releases/tag/v2.0.14)
