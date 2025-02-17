# Philosophy-Quote-Matcher
This project is a machine learning-based quote recommender that analyzes user input and matches it with philosophical quotes from great thinkers like Aristotle, Confucius, Friedrich Nietzsche, Immanuel Kant, Jean-Jacques Rousseau, John Locke, Plato, René Descartes and Socrates. It utilizes NLP (Natural Language Processing) with Sentence-BERT to find the most relevant quote based on the user's thoughts.

# How It Works
1. The user enters a thought or feeling.
2. The model computes a semantic embedding for the input using Sentence-BERT.
3. It compares this embedding with the precomputed embeddings of famous quotes.
4. The system recommends the most relevant philosophical quote based on similarity.

# How to Use
1. After running the script, go to the last cell where you'll be prompted to enter your thoughts 
2. The model will return a philosophical quote that best matches your input.
3. Type 'exit' to stop the program.

# Link for the Dataset
https://huggingface.co/datasets/datastax/philosopher-quotes
