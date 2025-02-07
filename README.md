# Sorting Visualizer

A **Sorting Visualizer** web application that visually demonstrates various sorting algorithms, making it easier to understand how sorting works step by step. This project is built using **HTML, CSS, and JavaScript**.

## 🚀 Features
- Visualization of multiple sorting algorithms:
  - **Bubble Sort** 🟡
  - **Insertion Sort** 🔵
  - **Heap Sort** 🔴
  - **Quick Sort** 🟣
  - **Merge Sort** 🟢
  - **Selection Sort** 🟠
- Speed control to adjust sorting speed dynamically.
- Ability to generate new arrays with random values.
- Responsive and interactive UI.

## 🛠️ Technologies Used
- **HTML5**: Structure of the webpage
- **CSS3 (Tailwind CSS)**: Styling and layout
- **JavaScript (ES6)**: Sorting algorithms and UI interactions

## 📌 Getting Started
### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/sorting-visualizer.git
cd sorting-visualizer
```

### Step 2: Open the Project
- You can run the project using **Live Server** in VS Code
- Or simply open the file in a browser:
  ```bash
  http://127.0.0.1:5500/index.html
  ```

### Step 3: Use the Sorting Visualizer
1. Select a sorting algorithm.
2. Adjust the speed using the speed slider.
3. Click **Start Sorting** to begin visualization.
4. Click **Generate New Array** to create a new dataset.

## 📊 Sorting Algorithms Explained
### 1️⃣ Bubble Sort
- **Time Complexity:**
  - Worst: O(N²)
  - Average: Θ(N²)
  - Best: Ω(N)
- **Space Complexity:** O(1)
- **Concept:** Repeatedly swaps adjacent elements if they are in the wrong order.

### 2️⃣ Insertion Sort
- **Time Complexity:**
  - Worst: O(N²)
  - Average: Θ(N²)
  - Best: Ω(N)
- **Space Complexity:** O(1)
- **Concept:** Builds the sorted array one element at a time.

### 3️⃣ Heap Sort
- **Time Complexity:**
  - Worst: O(N log N)
  - Average: O(N log N)
  - Best: O(N log N)
- **Space Complexity:** O(1)
- **Concept:** Uses a binary heap structure to sort elements.

### 4️⃣ Quick Sort
- **Time Complexity:**
  - Worst: O(N²)
  - Average: O(N log N)
  - Best: O(N log N)
- **Space Complexity:** O(log N)
- **Concept:** Uses a pivot to partition elements recursively.

### 5️⃣ Merge Sort
- **Time Complexity:**
  - Worst: O(N log N)
  - Average: O(N log N)
  - Best: O(N log N)
- **Space Complexity:** O(N)
- **Concept:** Divides the array into halves and merges them back in sorted order.

### 6️⃣ Selection Sort
- **Time Complexity:**
  - Worst: O(N²)
  - Average: Θ(N²)
  - Best: Ω(N²)
- **Space Complexity:** O(1)
- **Concept:** Repeatedly selects the minimum element and swaps it with the first unsorted element.
