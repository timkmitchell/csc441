# Rough Outline #

## Introduction: ##
  **

## Background and Topic Prerequisites: ##
  *Optical Character Recognition is a technology used to identify text within images like documents and photos. Its function is to convert any image containing written text (typed, handwritten or printed) into machine-readable text data.

  The first OCR tools in modern history were developed in the early-to-mid 1900’s, but the ideas were brewing for years before that.The Nipkow Disk was an image scanning device all the way back in 1885. Later devices started by interpreting Morse Code to read text aloud. The first scanners capable of reading text required that the text be in a special font that was easy for the scanning software to recognize. In 1974, Kurzweil Computer Products developed the first omni-font software.

  Much of the first work in this space was in English, using the Latin alphabet. In 1992, the Cyrillic alphabet got some love and Russian text could be digitized.
  By the year 2000 we had online OCR services that could translate scanned text into other languages, and this is when OCR really picked up some steam.

  By moving the processing from the scanner (or the computer it was attached to) up into the cloud allowed OCR to shift from being a product to becoming a service.

  Their(Companies) large volumes of paper files are being converted into digital format, which improves efficiency, speeds up operations, reduces storage costs, and improves data security. This process is not about simply converting paper documents to digital format. OCR (Optical Character Recognition) Software can help extract important information from the scanned documents and store the data in such a way that it is easily available.*
    - https://docparser.com/blog/what-is-ocr/
    - https://www.cloud-trade.com/2019/03/19/a-brief-history-of-ocr/#:~:text=OCR%20traces%20its%20roots%20back,first%20electronic%20document%20retrieval%20system.
    - https://blog.filestack.com/thoughts-and-knowledge/history-of-ocr/
    - https://www.managedoutsource.com/blog/importance-ocr-and-data-extraction-from-paper-documents-for-businesses/#:~:text=OCR%20(Optical%20Character%20Recognition)%20Software,into%20editable%20and%20searchable%20data.
  **Libraries Used:**
    1. Tesseract
    2. Tensorflow
    3. Opencv
    4. Sklearn
    5. Pillow

## The Topic: ##
  *Developing a script that uses handwritten character recognition to make tasks, such as, grocery shopping less tedious.*

## Topic Implementation: ##
  *Given an image of a grocery list, the script should:*
    - take the uploaded image
    - be able to recognize characters
    - insert bounding boxes around those characters
    - allow the user a way to mark through, or give some indication that this item is secured

## Conclusions ##
  **
