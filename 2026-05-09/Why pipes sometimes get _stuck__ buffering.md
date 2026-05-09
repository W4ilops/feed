### Main Topic: Log File Problems
**Main Thesis:** The frustrating issue of “nothing showing up” when using pipes to watch log files is caused by programs temporarily holding onto their output before sending it, not a problem with the pipes themselves.
**Simple Summary:** Sometimes, when you’re watching a log file for specific information using a series of commands connected together (like “look at this file, then find these words”), you might not see anything happening. This is because many programs hold onto their results for a bit before sending them along. It’s like they’re saving up their work before sending it. This happens to make things faster, but it can cause confusion when you’re using pipes.
**The Bottom Line:** > Don’t assume a problem with your commands or pipes – it’s likely a program is temporarily holding onto its output. Knowing which commands don’t buffer their output (like `tail` and `cat`) can help you avoid this issue.

---
*Original article: https://jvns.ca/blog/2024/11/29/why-pipes-get-stuck-buffering/*
