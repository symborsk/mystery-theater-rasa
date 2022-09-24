# mystery-theater-rasa
Rasa portion of mystery theater game.

## Setup 

- Set up a python virtual environment:
- Download dependencies specified in requirements.txt
- Run the pip3 install -r requirements.txt
- Run rasa shell to test out latest model it out full command line found at this link: https://rasa.com/docs/rasa/command-line-interface#rasa-shell
- Have fun!


## Running models

### Spacy Model

Will need to install spacy and download the training set.

```bash
pip3 install spacy
python3 -m spacy download en_core_web_md
```

```bash
rasa train --config config-spacy.yml
```

### White space tokenizer

```bash
rasa train --config config.yml
```

## Testing

```bash
rasa shell 
```
