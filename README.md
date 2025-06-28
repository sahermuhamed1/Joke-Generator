# Joke Generator using recurrent networks (RNN, LSTM, GRU)

A simple joke generation model using an RNN architecture trained on the [Good Joke Dataset](https://huggingface.co/datasets/diwank/good_joke-dataset). Given a joke prompt, the model generates a humorous completion.

## Dataset
We use the Hugging Face dataset: [`diwank/good_joke-dataset`](https://huggingface.co/datasets/diwank/good_joke-dataset).

## Example Usage
Input:

```bash vbnet
Knock, knock.
Who's there?
```

Output:
```bash
Dwayne
Dwayne who?
Dwayne the bathtub mommy, I'm dwowning.
```

## Notes
- Model uses a many-to-many simple RNN architecture only till now.
- User inputs a prompt; model continues the joke word by word.
- Tokenizer and model are saved for reuse during inference.

