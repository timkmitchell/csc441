# Full Outline #

## Introduction ##
  1. What is a brief definition of the topic?

    *Using OCR to heighten the effectiveness of practical tasks that involve characters
    created through penmanship. Essentially, I am creating a piece of software that
    allows an individual to manage an uploaded handwritten grocery lists.
    This should allow them to mark out selected items, categorize items, etc.*

  2. Why should I read your paper about this topic?

    *To get a glimpse of one the practical ways OCR can be implemented into peoples
    everyday lives. People would give a lot in order to do things quickly and
    easily with little or no thought given at all. This could inspire you to come
    up with your own way of deteriorating the mind of the human species.
    Making things easier for the average person will always be met with support.*

  3. What did you find out, and what will you discuss in the paper?

    *This paper will include a discussion on the difficulties of working with OCR,
    the importance convenience has on people, how it influences how people shop, and
    how we can combine shopping with OCR to bring that convenience to the consumer.*

## Background and Topic Prerequisites ##
  1. What is the history and background of your topic? I.e. why is it even a thing?

    *Optical Character Recognition is a technology used to identify text within images
    like documents and photos. Its function is to convert any image containing written
    text (typed, handwritten or printed) into machine-readable text data.

    The first OCR tools in modern history were developed in the early-to-mid 1900s,
    but the ideas were brewing for years before that.The Nipkow Disk was an image
    scanning device all the way back in 1885. Later devices started by interpreting
    Morse Code to read text aloud. The first scanners capable of reading text required
    that the text is in a special font that was easy for the scanning software to
    recognize. In 1974, Kurzweil Computer Products developed the first omni-font software.

    Much of the first work in this space was in English, using the Latin alphabet.
    In 1992, the Cyrillic alphabet got some love and Russian text could be digitized.
    By the year 2000, we had online OCR services that could translate scanned text
    into other languages, and this is when OCR really picked up some steam.

    By moving the processing from the scanner (or the computer it was attached to)
    up into the cloud allowed OCR to shift from being a product to becoming a service.*

  2. What are the seminal or foundational works (commercial, industrial, or academic) in the field?

    *OCR got its foundation from an Australian engineer Gustav Tauschek, who got
    a patent on OCR, or Reading Machine, in Germany in 1929. From then on, we have
    substantial growth and improvement in the OCR. Convenience is the paramount
    factor here, and it is what those who use OCR strive to create.
    It has been used to scan and file documents for companies with thousands of
    clients, to self check-in hotel guests, to copy-paste documents, assist the
    blind(text to speech), etc.*

  3. What other topics need to be (briefly) explained in order to properly frame the discussion of your topic?

    *To better understand the use of OCR, we need to take brief dive into machine
     learning, object tracking using opencv, and pytesseract.*

## The Topic ##
  1. What is the core idea of the topic?

    *The core idea is to bring the valuable commodity of convenience and an
    improvement to customer experience to the stay-at-home moms and dads, the
    nine-to-fivers, the broke college students, the housekeepers and caretakers,
    etc. Americans are all about wanting things done quickly and efficiently, and
    this just helps perpetuate that need for expediency.*

  2. Why is it important?

    *The significance isn't quantifiable by its benefit to the entirety of the human
    race, but by an individual need to reduce the time spent on a small, tedious
    task. It's just something for the sake of convenience. For the modern-day shopper.
    It would be important to a person whose life may be a bit hectic. When everything
    requires depth and is time-consuming, it is nice to have something quick and
    mindless for a change.*

  3. Who cares about this topic?

    *Any shopper essentially. Think about the husband who spends an hour and
    thirty minutes at the grocery store, even though his wife only sent him to
    get four things. Give other examples.... This is for the modern consumer
    who is all about getting done right and now.*

  4. What are the worldview implications of your topic?

    *

## Topic Implementation ##
  1. What is a concrete, implementable example of the topic?

    *Given an image of a grocery list, the topic should able to identify, if the
     list is ordered as one item on each row, each item on that list separately,
     and provide them each with its own corresponding bounding box. Once all the
     bounding boxes are set, it should allow you, for the time being, to mark
     picked items at your leisure and to rearrange boxes in whatever order you choose.*

  2. What goes into implementing this example? How would someone build it? What is the process?

    *In progress.....*

  3. What are the potential difficulties or complications in implementing this topic?

    *The biggest challenge is the accuracy of the OCR. People's handwriting tends
    to differ vastly and the smallest detail could throw the system off. Cursive
    is especially hard because it is hard to interpret handwriting with no distinct
    separation of characters. In my case, however, this is not that big of a deal
    since it has to recognize whole words instead of individual characters. Individual
    char recognition is still important though. Without it, how will the system know
    where the words begin and end, and whether or not the thing it is looking at is
    actually a word? Another issue could arise from a lack of examples for the
    system to learn from in the database. The training of a system requires an
    immense amount of examples in order to account for unique cases. The quality of the image can also affect the accuracy.*

## Conclusion ##
  1. What did you discuss?

    *How OCR can provide us convenience in our everyday lives. The difficulties
    concerning OCR.The importance convenience has on people, Why shoppers need
    convenience, and how we can combine shopping with OCR to bring that
    convenience to the consumer.*

  2. What do you plan to do with what you discussed

    *I plan to publish a piece discussing what I have learned and the steps I
    have taken to overcome any challenges that I encountered. I also plan on
    developing software that is given a detailed list of items, and with a list,
    it searches the internet for the best prices. It will give a detailed report
    back to the user for them to verify everything. And, finally, it will place
    the order. Sort of like hands-free shopping.*

  3. How will what you plan to do affect your professional development?

    *It will award me with experience and it will allow me to receive criticism,
    hopefully constructive, from more sound individuals who can see all of the
    flaws that I couldn't. It will force me to expand my skill set and help me
    develop into a more creative person.
