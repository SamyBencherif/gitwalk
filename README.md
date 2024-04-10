# GitWalk

Let's go for a walk through the history of an open source project.

GitWalk allows you to explore the history of a git repository and watch it unfold the same way the original developers did.

## Usage

```
gitwalk [branch] [index]
```

### Viewing early history

1. cd into a git repository
2. use `gitwalk main 0` to checkout the first commit on the main branch
3. use `gitwalk main 1` to checkout the second commit on the main branch
4. and so on...

### Viewing recent history

1. cd into a git repository
2. use `gitwalk main -1` to checkout the last commit on the main branch
3. use `gitwalk main -2` to checkout the second last commit on the main branch
4. and so on...

## Installation

```
cp gitwalk /usr/local/bin
```
