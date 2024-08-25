# Exegesis

Processing gutenberg books for finetuning purposes.

Run `preprocess_par` then `check_ft`.

## Preprocessing

Each file needs to be processed in a different way. Here are some examples.

### An Outline of Occult Science

-   manually

    -   remove guttenberg front
    -   remove guttenberg back
    -   remove front matter
    -   remove footnotes
    -   remove -------
    -   collapse small sentences

-   automatic
    -   remove footnotes `(30)`
    -   remove titles
    -   collapse paraghraphs
    -   remove multiple spaces

## Documents

-   `steiner.txt`: [An Outline of Occult Science by Rudolf Steiner](https://www.gutenberg.org/ebooks/30718)

## TODO

-   add graphs min/max sentence length
