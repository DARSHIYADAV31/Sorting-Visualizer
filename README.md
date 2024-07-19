Bubble Sort Visualization
This project is a simple Java application that visualizes the Bubble Sort algorithm using Java Swing for graphical representation. It allows users to see how Bubble Sort works step-by-step on a randomly generated array of integers.

Features
Start Button: Begins the sorting visualization.
Reset Button: Resets the array to a new set of random values and stops the current sorting process.
Sorting Visualization: Highlights the elements being compared during the sorting process.

Project Structure
SortingPanel.java: This class extends JPanel and contains the main logic for the Bubble Sort visualization. It includes methods for sorting, resetting the array, and painting the components.
Frame.java: This class extends JFrame and sets up the main window for the application. It adds the SortingPanel to the frame.
sort.java: This class contains the main method, which is the entry point of the application. It initializes and displays the Frame.
How It Works
Initialization:

The SortingPanel initializes with an array of random integers.
The Start button begins the Bubble Sort animation.
The Reset button resets the array and stops the current sorting process.
Sorting Process:

The BubbleSortAnimate method uses a Timer to perform the sorting step-by-step.
The sortOnlyOneItem method performs a single comparison and swap if necessary.
The isSorted method checks if the array is sorted.
Visualization:

The paintComponent method is overridden to draw the array elements as bars.
The bars being compared are highlighted in a different color.
