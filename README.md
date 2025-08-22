# DSA_Visual_Debugger  
*See your code come alive: step-by-step visual debugging for data structures.*

---

## Overview  
**DSA_Visual_Debugger** is an interactive tool that helps students and developers **understand, debug, and learn data structures and algorithms** by providing step-by-step **visualizations of code execution**.  

Instead of staring at failing test cases or scattered print statements, users can see:  
- How **pointers/links** are created, updated, or broken.  
- How arrays, linked lists, stacks, queues, and trees evolve **step by step**.  
- Which **line of code** caused each change.  
- Where **dangling pointers, missing updates, or logical errors** occurred.  

---

## Motivation  
Debugging DSA problems on platforms like **LeetCode, Neetcode, or Codeforces** can be challenging:  
- You only see failing input/output.  
- Pointer-heavy structures (linked lists, trees) are hard to trace mentally.  
- Small bugs (like forgetting to update `prev` in a doubly linked list) can break everything.  

This project bridges that gap by giving users a **“Visualize Test Case”** experience — turning invisible pointer manipulations into clear, interactive animations.  

---

## Features (MVP)  
- **Code + Visuals in Sync** → highlights the line of code currently executing.  
- **Step-by-Step Playback** → move forward, backward, or auto-play through execution.  
- **Pointer Visualization** → clearly shows `.next`, `.prev`, and `null` references.  
- **Supported Structures** (initially):  
  - Arrays (sorting, swapping)  
  - Singly & doubly linked lists  
  - Stacks & queues  
  - Binary search trees (insert/search/delete)  

---

## Roadmap  
- [ ] Support arrays & basic sorting algorithms.  
- [ ] Add linked list visualization (insert, delete, swap nodes).  
- [ ] Add BST visualization (insert/delete, highlight rotations).  
- [ ] Allow test case replay for failed inputs.  
- [ ] Sandbox arbitrary student code safely.  
- [ ] Browser extension to integrate with LeetCode.  

---

## Contributing  
Contributions are welcome! You can help by:  
- Adding new data structures/algorithms.  
- Improving visualizations and animations.  
- Expanding test case coverage.  
- Enhancing UI/UX.
  
---

## License  
MIT License – free to use, modify, and share.  
