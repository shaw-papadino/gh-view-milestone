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

```json
{"CLOSED":3,"id":1,"title":"hoge"}
{"OPEN":2,"id":1,"title":"hoge"}
{"CLOSED":3,"id":2,"title":"fuga"}
.
.
.
```

## Tasks
- [ ] more visible
