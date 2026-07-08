# DSA Practice — Nikhil

No notes. No theory dumps. Just solved problems, committed daily.

## Rules
1. One folder = one pattern. Solve in order, don't skip ahead.
2. Every solve gets its own file: `NN-problem-name.py` (e.g. `01-two-sum.py`).
3. Commit message = just the problem names solved that day. That's the only "note" this repo needs.
   Example: `git commit -m "arrays: two sum, group anagrams"`
4. If you needed the video to solve it, mark the file with `# assisted` at the top.
   If you solved it cold, mark it `# blind`. This is how you see real progress over time —
   assisted-to-blind ratio going up is the actual signal, not the raw count.
5. Weekly: redo one old problem from scratch with zero help. Log the result in PROGRESS.md.

## Structure
```
01-arrays-hashing/
02-two-pointers-sliding-window/
03-stack-binary-search/
04-linked-list/
05-trees/
06-tries-heap/
07-backtracking/
08-graphs/
09-dp-1d/
10-dp-2d/
11-greedy-intervals/
12-review/
```

## Workflow (per problem)
1. Open the problem on NeetCode/LeetCode. 15 min blind attempt.
2. Stuck? Watch the NeetCode video once. Close it. Re-implement from memory.
3. Copy `_template.py`, rename it, solve, add Big-O comment at the bottom.
4. Push same day. Don't batch — daily commits are the point (streak = proof of consistency).

## Progress
See [PROGRESS.md](./PROGRESS.md) for the full 12-week checklist.

## Setup
```bash
git init
git add .
git commit -m "init: dsa-practice structure"
git remote add origin <your-github-repo-url>
git push -u origin main
```
