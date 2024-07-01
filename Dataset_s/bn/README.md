## IIIT-INDIC-HW-WORDS 

To extract annotations from the zip file, follow the given instructions

- Download the appropriate zip for a specific language from the Project page.

- The zip file contains train, val and test image folders 

- The labels for these images are provided in train.txt, val.txt and test.txt respectively

- Each row in the label file is of the format: <FileName>, <VocabId>

- vocab.txt contains the full lexicon used in the dataset.

- <VocabId> starts with 0 in the label file and the unicode label string for this Id can be extracted from
  that specific line number in vocab.txt
