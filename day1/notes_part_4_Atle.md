# Parsing Metadata from Filenames

### Intro text
- Typo in text: "Treatmet"

### Extracting Metadata from Fixed length strings
- Typo in text: "relavant"

### Extracting Metadata from variable length strings
- Info separated by special character, often underscore
- Use split function to extract
    - Idea: Add rsplit setting till what underscore number you want to split?
        - "split" splits from left. Can set till how many underscores you should split. `split('_', 1) splits at 1st underscore only, f. ex.
        - rsplit splits from the right. Could be useful if you want to keep some of the string parts together.
        - Not sure how essential it is that they learn this now, though.

Text change:
- "The example below shows an example" &rarr; "The example below illustrates"

### Using double separator to store keys and values directly in filename

- Keys separated by space and values given by =

### Extra: Making data model contracts explicit with schemas

- from collections import namedtuple
- Stores meta data keys and values with a tuple-like object