<h1 align="center">PyTorch Chatbot</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />
</p>

A work-in-progress. Currently a very rudimentary chat bot.

## Author

👤 **Lora Johns**

## Data

The Cornell Movie-Dialogs Corpus

- 220,579 conversational exchanges between 10,292 pairs of movie characters
- 9,035 characters from 617 movies
- 304,713 total utterances

## Models

This chatbot implements a sequence-to-sequence (seq2seq) model with an encoder based on Cho et. al.'s dual Gated Recurrent Unit model and a decoder that incorporates Luong's attention mechanism.

TO DO:

- Implement pretrained word embeddings with torchtext instead of this dinky dictionary that can't handle out-of-vocabulary words!
- I have a function for generating random circulant embeddings that would go here nicely, as well.
- Ngrams would be neat.
- Different data.
- TBD.

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
