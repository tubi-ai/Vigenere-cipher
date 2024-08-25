This code implements a simple version of the Vigenère cipher, a classical method of encryption that uses a key to encode a message.

Key Points:
Simplicity and Flexibility: The code is straightforward, making it easy to understand and modify. The use of dictionaries for alphabet mapping is a clever approach that simplifies the indexing process.
Reusability: The separation of functionality into distinct methods and classes (Utils.split_text and Vigenere.vigenere) makes the code modular and reusable.
Bidirectional Process: The code effectively handles both encryption and decryption using the same method, controlled by a simple boolean flag (cipher). This dual functionality within a single method is a neat feature.
Handling Spaces: The alphabet includes a space character, allowing the cipher to process natural language text more accurately without losing spaces between words.
