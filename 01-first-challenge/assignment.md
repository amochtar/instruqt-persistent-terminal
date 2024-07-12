---
slug: first-challenge
type: challenge
title: First challenge
tabs:
- title: Terminal
  type: terminal
  hostname: ubuntu
  cmd: screen -DR my-session bash
difficulty: ""
---
The terminal is running a session managed by [`screen`](https://www.gnu.org/software/screen/). This allow you to keep the same terminal session running, and reuse it in subsequent challenges. The command used to start this session is:

```nocopy
screen -DR my-session
```

To demonstrate this, generate some output, by running the following command:

```nocopy,run
top
```

Leave it running, and go to the next challenge. You'll see that you will continue exactly where you left off.
