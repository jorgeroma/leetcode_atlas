# LeetCode Atlas

An interactive study guide for the algorithm patterns behind coding interviews. Instead of grinding random problems, it teaches you to **recognize which pattern a problem needs** and then how to apply it.

> **Note:** the site content is written in Spanish. Code samples are in Python 3 and TypeScript.

## What's inside

**24 patterns**, ordered by how often they show up in interviews versus how much effort they take to learn:

| Tier | Focus | Patterns |
|------|-------|----------|
| **1** | The 20% that covers most problems | Arrays + hash map/set, two pointers, sliding window, binary trees (DFS/BFS), binary search |
| **2** | The rest of the frequent ones | Stack & monotonic stack, graphs (BFS/DFS, grids), heap & top-K, linked list (fast/slow), data structure design (LRU), intervals, greedy, prefix sum, 1D dynamic programming |
| **3** | Diminishing returns | Backtracking, 2D dynamic programming, topological sort, union-find, trie, monotonic deque, bit manipulation, string matching (KMP, rolling hash), Dijkstra, segment & Fenwick trees |

Each pattern includes:

- The core idea and quick signals to recognize it
- Time and space complexity
- A step-by-step visualization
- Implementation guide with code in **Python** and **TypeScript**
- Common mistakes
- 9 free LeetCode problems to practice (3 easy, 3 medium, 3 hard)
- Links for further reading

### Practice mode

- **Mixed quiz:** read a problem and guess which pattern solves it
- **Mock interview:** a random problem with a 45-minute timer and the pattern hidden, with optional hints. Filter by difficulty and tier
- **Decision tree:** a guided "which pattern should I use?" flow

Your progress (solved problems, quiz results) is saved in your browser's `localStorage`. Nothing is sent to any server.

## Usage

It's a single self-contained HTML file. No build step, no dependencies to install.

```bash
git clone https://github.com/jorgeroma/leetcode_atlas.git
cd leetcode_atlas
open index.html        # macOS
xdg-open index.html    # Linux
```

Or serve it locally:

```bash
python3 -m http.server
# then visit http://localhost:8000
```

An internet connection is needed for fonts (Google Fonts) and syntax highlighting (Prism.js via cdnjs). Light and dark themes follow your system preference.

## Contributing

Issues and pull requests are welcome: typo fixes, better explanations, new problems or patterns.

## License

[MIT](LICENSE)
