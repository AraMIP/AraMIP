# Selecting a small corpus from BAREC-10M

We select 300 sentences for our pilot annotation study from BAREC-10M. We consider balanced text domains, categories and readership group level.

Our selection procedure is implemented in the `select_sentences.ipynb` notebook. To reproduce our selection procedure, you have to download the [BAREC-10M](https://huggingface.co/datasets/CAMeL-Lab/BAREC-10M) corpus and store it in the current folder.

To explore the selected sentences directly without reproducing the procedure, check the following folders:

- `selected_sentences_by_category`: six files, each contains 50 sentences of a certain category.
    1. `LAM`: Literature; Art & Music
    2. `MC`: Media & Culture
    3. `ELL`: Educational Materials; Language & Linguistics
    4. `AC`: Academic
    5. `RP`: Religion & Philosophy
    6. `EN`: Encyclopedic - Arts & Humanities

- `annotation_sets`: mixed sentences randomly divided on 6 sets for the annotations pilot study.