# Personalized Dictionary---Text transformation
**The function will help readers sort out their notes of new words and their meanings.**


This Python function will help readers build their customized dictionary for each book. It will sort out all new words in alphabetical order and allow readers to look up new words or special terms more easily. The process is keeping all new words and their meaning in one document file (getting updated this file as the reader goes along with one book reading) and then putting it into the Python function. Then, you have a mini dictionary with details about the book you are reading.
-----------
The input is in MS Word or text format, including the new words attached with their meanings. 
The output is the table with two columns ( one is New words, and the other is Meaning/Definition) represented in word format.
-----------
**This process will boost the reader's performance by solving issues:**
* New words are often stored in different places( notes, phones, laptops, etc.). Many people might have said this before: Where is my note for this word? I definitely wrote it down somewhere.
* Avoid duplicated words. Writing the same new words in different places.
* Disorganizing new words. Since new words appear randomly in a book, it makes it hard to manage their new words in order. The physical notebook or paper can just store and add new words, but it can't re-arrange words in order.

## The function process:
  1. Select and get data from the Word file
  2. Split text and put these word pairs into a list
  3. Sorting the list into alphabetical order
  4. Transform in table-alike format
  5. Store the output file in MS Word and choose the desired folder/ destination.

## Further Development:

* Identify and warn readers of the wrong spelling of words.
* Auto-correct spelling. 
* Integrating with online looking up for meaning.
