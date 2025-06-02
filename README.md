
# 🔐 Task 2 – File Encryption/Decryption (C++)

This project is part of the **CodeAlpha C++ Internship** and focuses on basic encryption techniques using **Caesar Cipher** to protect text files.

---

## 🎯 Objective

Build a console application that can:
- Encrypt a text file using Caesar Cipher
- Decrypt it back using the same key
- Save the result to a new file

---

## 🛠 Concepts Used

- File Streams (ifstream, ofstream)
- Strings and Characters
- Caesar Cipher (character shifting)
- Loops and User Input

---

## 💡 How the Code Works

1. **User Input**  
   The user is asked to:
   - Choose an option: encrypt or decrypt
   - Provide an input filename and output filename
   - Enter a numeric key for the Caesar Cipher

2. **Encryption/Decryption Logic**  
   - Each character in the file is read one by one.
   - If it’s an alphabetic character, it’s shifted by the key (left for decryption, right for encryption).
   - The result is saved to the output file.

3. **Caesar Cipher**  
   - A basic method where characters are shifted by a fixed number of places in the alphabet.
   - Keeps text readable but obscures the actual content.

---

## ▶ How to Compile & Run

bash
g++ task2_file_encryption.cpp -o encryptor
./encryptor
