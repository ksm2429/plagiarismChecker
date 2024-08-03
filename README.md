# Plagiarism-checker-Python

This repository contains the source code of a Python script that detects plagiarism in a textual document using **cosine similarity**.

[![Become a patron](pictures/become_a_patron_button.png)](https://www.patreon.com/ksm2429)

## How is it Done?

You might wonder how plagiarism detection on textual data is done. It's not as complicated as it may seem.

We know that computers are good with numbers, so to compute the similarity between two text documents, the textual raw data is transformed into vectors (arrays of numbers). Using basic vector operations, we can compute the similarity between these vectors.

This repository contains a basic example of how to do that.

## Getting Started

To get started with the code in this repository, you need to either *clone* or *download* it to your machine as shown below:

```bash
git clone https://github.com/ksm2429/Plagiarism-checker-Python

# Plagiarism-checker-Python

This repository contains the source code of a Python script that detects plagiarism in a textual document using **cosine similarity**.

[![Become a patron](pictures/become_a_patron_button.png)](https://www.patreon.com/ksm2429)

## How is it Done?

You might wonder how plagiarism detection on textual data is done. It's not as complicated as it may seem.

We know that computers are good with numbers, so to compute the similarity between two text documents, the textual raw data is transformed into vectors (arrays of numbers). Using basic vector operations, we can compute the similarity between these vectors.

This repository contains a basic example of how to do that.

## Getting Started

To get started with the code in this repository, you need to either *clone* or *download* it to your machine as shown below:

```bash
git clone https://github.com/ksm2429/Plagiarism-checker-Python



Running the App
To run the code, place your textual documents with the .txt extension in your project directory. When you run the script, it will automatically load all the documents with that extension and compute the similarities between them as shown below:

bash
cc
$ cd Plagiarism-checker-Python
$ python3 app.py
('john.txt', 'juma.txt', 0.5465972177348937)
('fatma.txt', 'john.txt', 0.14806887549598566)
('fatma.txt', 'juma.txt', 0.18643448370323362)


A Python Library?
If you'd like to use a Python library instead to help you compare strings and documents without writing the vectorizers yourself, check out Pysimilar.

Credits
All the credit goes to ksm2429.
