# DSA Experiments - Interactive Code Viewer

A modern, single-page web application to display and interact with 16 Data Structures and Algorithms (DSA) experiments written in C.

## Features

- **Interactive Code Viewer**: View C source code with syntax highlighting using Prism.js
- **Output Display**: View sample outputs for each experiment
- **Code Download**: Download individual experiment source files
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Beautiful gradient background with card-based layout using Tailwind CSS
- **Modal Dialogs**: Smooth animations for code and output viewing
- **Keyboard Support**: Press ESC to close modals

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with animations
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Prism.js**: Syntax highlighting for C code
- **Vanilla JavaScript**: No framework dependencies

## Project Structure

```
DSA-code-page/
├── index.html          # Main application file
├── outputs.json        # Experiment outputs data
├── experiments/        # C source code files
│   ├── 01 - Polynomials.c
│   ├── 02 - Sparse Matrix.c
│   ├── 03 - Infix to Postfix.c
│   ├── 04a - Linear Queue.c
│   ├── 04b - Double Ended Queue.c
│   ├── 05 - Circular Queue.c
│   ├── 06 - Browser Navigation.c
│   ├── 07 - Polynomials using linked list.c
│   ├── 08 - Binary Tree.c
│   ├── 09 - Binary Search Tree.c
│   ├── 10 - Breadth First Search.c
│   ├── 12 - Binary Search.c
│   ├── 13a - Bubble Sort.c
│   ├── 13b - Insertion Sort.c
│   ├── 13c - Quick Sort.c
│   ├── 13d - Merge Sort.c
│   ├── 14 - Memory allocation.c
│   ├── 15 - Garbage Collector.c
│   └── 16 - Hash Table.c
└── README.md           # This file
```

## Running the Application

### Option 1: Using Python's HTTP Server

```bash
cd DSA-code-page
python3 -m http.server 8000
```

Then open your browser and navigate to: `http://localhost:8000`

### Option 2: Using Node.js HTTP Server

```bash
cd DSA-code-page
npx http-server -p 8000
```

Then open your browser and navigate to: `http://localhost:8000`

### Option 3: Using Live Server (VS Code Extension)

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Experiments List

1. **Polynomials** - Polynomial addition using arrays
2. **Sparse Matrix** - Sparse matrix representation
3. **Infix to Postfix** - Expression conversion
4. **Queues** - Linear Queue (4a) and Double Ended Queue (4b)
5. **Circular Queue** - Circular queue implementation
6. **Browser Navigation** - Stack-based navigation simulation
7. **Polynomials using Linked List** - Polynomial operations with linked lists
8. **Binary Tree** - Binary tree traversals
9. **Binary Search Tree** - BST operations
10. **Breadth First Search** - BFS graph traversal
11. **Depth First Search** - (Code not available)
12. **Binary Search** - Binary search algorithm
13. **Sorting Algorithms** - Bubble Sort (13a), Insertion Sort (13b), Quick Sort (13c), Merge Sort (13d)
14. **Memory Allocation** - Memory allocation strategies
15. **Garbage Collector** - Garbage collection simulation
16. **Hash Table** - Hash table implementation

## Updating Outputs

To update the output for any experiment, edit the `outputs.json` file:

```json
{
  "experiments": {
    "1": {
      "title": "Polynomials",
      "output": "Your output text here..."
    }
  }
}
```

The JSON structure is flexible and can be easily updated by administrators.

## Features in Detail

### View Code
- Opens a modal with syntax-highlighted C code
- Includes line numbers for easy reference
- Scrollable for long code files

### View Output
- Displays sample program output in a terminal-style view
- Outputs are stored in `outputs.json` for easy updates

### Download Code
- Downloads the C source file directly to your computer
- Preserves original filename and extension

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Credits

**Developer**: [Dario George](https://github.com/dariogeorge21)

**Source Code**: [GitHub Repository](https://github.com/dariogeorge21/S3DSAlgo/tree/main/experiments)

## License

This project is open source and available for educational purposes.

