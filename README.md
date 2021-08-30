# gh-milestone-view
Github CLI extension to displays the status of milestones.

**It's still a work in progress.**

## Installation:

```bash
gh extension install shaw-papadino/gh-view-milestone
```

The extension depends on jq.

```bash
brew install jq
```

## Usage

```bash
gh view-milestone
```

```bash
Id | Title | OPEN | CLOSED | COMPLETE
1 "Add HOGE" 0 3 100%
2 "Fix SUSHI" 5 2 28%
4 "Delete FUGA" 4 0 0%
5 "Add FUJI" 0 3 100%
6 "Fix MOJYA" 2 0 0%
.
.
.
```

## Tasks
- [ ] more visible
