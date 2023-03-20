# Transformer-Based Arithmetic Solver
The task involves solving arithmetic word problems by translating natural language queries into arithmetic expressions. The model processes the problem statement, extracts numerical values, generates an arithmetic equation, and computes the final result.
- Utilizes a **Transformer-based** model (T5) to convert word problems into arithmetic expressions.
- The model is fine-tuned on a dataset ArithOpsTrain.csv containing problem descriptions, questions, and expected outputs.
- The trained model generates equations for unseen questions and evaluates them using input numbers.
