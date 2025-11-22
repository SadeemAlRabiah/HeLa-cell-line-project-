# HeLa-cell-line-project-
This project performs exploratory analysis on a HeLa cell mutation dataset to identify mutation patterns, quantify mutation types, and detect genes with multiple mutation occurrences. It uses Python, Pandas, and Matplotlib to process the dataset and visualize mutation distribution.
The project performs:

1. Data Loading & Quality Check
	•	Reads a CSV file containing HeLa mutation annotations.
	•	Displays dataset columns and initial rows.
	•	Detects missing values across all features.
	•	Prints a summary of columns with incomplete data.

2. Mutation Analysis
	•	Groups entries by Gene to compute mutation counts.
	•	Identifies genes with more than one mutation.
	•	Counts occurrences of each Variant Info (mutation type).
	•	Sorts mutation types by frequency to highlight dominant patterns.

3. Visualization

Generates a bar chart showing:
	•	Number of non-unique gene occurrences per mutation type.
	•	Clear count labels above each bar.
	•	Easy comparison between mutation categories.
