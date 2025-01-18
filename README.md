# Emotion Analysis from Text

This project performs emotion analysis from a given text file. It reads a text, processes it by removing punctuation, stop words, and then matches the remaining words with predefined emotions to generate a bar graph representation of the emotions present in the text.

## Project Files
- `main.py`: The main script that performs the emotion analysis.
- `read.txt`: The input text file that contains the content for analysis.
- `emotions.txt`: A file that contains words associated with different emotions.
- `graph.png`: The output graph that visualizes the emotions present in the text.
- `requirements.txt`: Contains the dependencies for the project.

## How to Run the Project

1. Clone this repository to your local machine.
2. Install the required dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure that the `read.txt` and `emotions.txt` files are in the same directory as `main.py`.
4. Run the `main.py` script:
    ```bash
    python main.py
    ```
5. The program will process the text in `read.txt`, match the words with the emotions in `emotions.txt`, and generate a bar chart of the detected emotions. The graph will be saved as `graph.png`.

## Output

The output will be a bar chart (`graph.png`) showing the count of each emotion present in the text.

## Requirements

- Python 3.x
- `matplotlib` for plotting the graph
- `nltk` for natural language processing (if used in additional steps)

## License

This project is open source and available under the MIT License.
