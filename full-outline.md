# Full Outline #

## Introduction ##
  1. What is a brief definition of the topic?

    *Using OCR to heighten the effectiveness of practical tasks that involve characters
    created through penmanship. Essentially, I am creating a piece of software that
    allows an individual to manage an uploaded handwritten grocery lists.
    This should allow them to mark out selected items, categorize items, etc.*

  2. Why should I read your paper about this topic?

    *To get a glimpse of one the practical ways OCR can be implemented into peoples every day lives. People would give a lot in order to do things quickly and easy with little or no thought given at all. This could inspire you to come up with your own way of deteriorating the mind of the human species. Making things easier for the average person will always be met with support.*

  3. What did you find out, and what will you discuss in the paper?

## Background and Topic Prerequisites ##
  1. What is the history and background of your topic? I.e. why is it even a thing?

    *Optical Character Recognition is a technology used to identify text within images
    like documents and photos. Its function is to convert any image containing written
    text (typed, handwritten or printed) into machine-readable text data.

    The first OCR tools in modern history were developed in the early-to-mid 1900’s,
    but the ideas were brewing for years before that.The Nipkow Disk was an image
    scanning device all the way back in 1885. Later devices started by interpreting
    Morse Code to read text aloud. The first scanners capable of reading text required
    that the text be in a special font that was easy for the scanning software to
    recognize. In 1974, Kurzweil Computer Products developed the first omni-font software.

    Much of the first work in this space was in English, using the Latin alphabet.
    In 1992, the Cyrillic alphabet got some love and Russian text could be digitized.
    By the year 2000 we had online OCR services that could translate scanned text
    into other languages, and this is when OCR really picked up some steam.

    By moving the processing from the scanner (or the computer it was attached to)
    up into the cloud allowed OCR to shift from being a product to becoming a service.*

  2. What are the seminal or foundational works (commercial, industrial, or academic) in the field?

  3. What other topics need to be (briefly) explained in order to properly frame the discussion of your topic?

    *To better understand the use of OCR, we need to take brief dive into machine
     learning, object tracking using opencv, and pytesseract.*

## The Topic ##
  1. What is the core idea of the topic?

    *The core idea is to bring the valuable commodity of convenience to the stay-at-home
     moms and dads, the nine-to-fivers, the broke college students, the housekeepers
     and caretakers, etc. Americans are all about wanting things done quickly and
     efficiently, and this just helps perpetuate that need for expediency.*

  2. Why is it important?

    *The significance isn't quantifiable by its benefit to the entirety of the human
    race, but by an individuals need to reduce the time spent on a small, tedious
    task. It's just something for the sake of convenience. For the modern day shopper.
    It would be important to a person whose life may be a bit hectic. When everything
    requires depth and is time consuming, it is nice to have something quick and
    mindless for a change.*

  3. Who cares about this topic?

    *Any shopper essentially. Think about the husband who spends an hour and thirty minutes at the grocery store, even though his wife only sent him to get four things. Give other examples.... This is for the modern consumer who is all about getting done right and now.*

  4. What are the worldview implications of your topic?

## Topic Implementation ##
  1. What is a concrete, implementable example of the topic?

    *Given an image of a grocery list, the topic should able to identify, if the
     list is ordered as one item on each row, each item on that list separately,
     and provide them each with its own corresponding bounding box. Once all the
     bounding boxes are set, it should allow you, for the time being, to mark
     picked items at your leisure and to rearrange boxes in what ever order you choose.*

  2. What goes into implementing this example? How would someone build it? What is the process?

    *In progress.....*

  3. What are the potential difficulties or complications in implementing this topic?

    *The biggest challenge is the accuracy of the OCR. Peoples handwriting tends
    to differ vastly and the smallest detail could throw the system off. Cursive
    is especially hard because it is hard to interpret handwriting with no distinct
    separation of characters. In my case, however, this is not that big of a deal
    since it has to recognize whole words instead of individual characters. Individual
    char recognition is still important though. Without it, how will the system know
    where the words begin and end, and whether or not the thing it is looking at is
    actually a word. Another issue could arise from a lack of examples for the
    system to learn from in the database. The training of a system requires an
    immense amount examples in order to account for unique cases.*

## Conclusion ##
