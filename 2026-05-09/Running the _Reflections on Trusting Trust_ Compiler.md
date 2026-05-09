### Main Topic: Backdoors in Compilers
**Main Thesis:** This article explains how a clever trick can be used to secretly put a hidden instruction (a backdoor) into a computer program by modifying the compiler itself, leaving no trace in the original program’s code.

**Simple Summary:** A long time ago, a computer expert named Ken Thompson figured out a way to sneak a secret instruction into computer programs. He did this by changing a compiler – the program that turns code into programs – so it automatically adds a hidden command. The trick involves a “quine,” which is a program that copies itself, and then carefully modifying the compiler to recognize and act on specific programs, like a hidden key.

**The Bottom Line:** > It’s important to understand that even if you trust a computer program, the tool that makes it (the compiler) could be secretly altered to do something unexpected, highlighting the need to carefully examine how software is built and maintained.

---
*Original article: https://research.swtch.com/nih*
