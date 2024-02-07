# NYC-Baby_names_Viz_WordCloud_Python_Tableau
This project analyzes popular baby names using data visualization techniques, particularly focusing on generating word clouds based on gender-specific datasets. The dataset used contains information about baby names, their frequencies, and genders. The project utilizes Python libraries such as Pandas, NumPy, Matplotlib, PIL (Python Imaging Library), and WordCloud.

1. Data Preparation:
   The dataset is loaded into a Pandas DataFrame and basic exploratory data analysis is conducted to understand its structure.

3. Data Segmentation by Gender:
   The dataset is split into two separate datasets based on gender—girls' names and boys' names—using conditional queries.

5. Word Cloud Generation:
   Word clouds are generated separately for girls' and boys' names using the WordCloud library. The word clouds visualize the frequency of names, with larger font sizes indicating higher frequencies.

7. Export to CSV:
   The layouts of the word clouds, containing information such as name, size, coordinates, direction, and color, are exported to CSV files.

9. Tableau Visualization:
    The CSV files containing the word cloud layouts are then connected to Tableau Public for further visualization. Tableau is used to create visualizations incorporating the word cloud layouts, allowing for interactive exploration of popular baby names. Additionally, pictures created from the code, such as maps generated from images, are integrated into the Tableau visualizations to enhance the presentation.
