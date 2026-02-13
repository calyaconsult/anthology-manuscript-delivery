# Synthetic Texts

## An Anthology

### Curated by ~~Marcus Antonius~~

Published by Calya Digital Publishing Services  
an imprint of Calya Consult GmbH, Zug, Schweiz

# Introduction

## Can AI write?

### Writing as Text Production

In the technical realm, a text is a sequence of characters, encoded as ASCII, UTF-8, UTF-16, UTF-32, or any other form of character encoding. A character is defined as element of a character set, the non-technical term being "alphabet." Character sets are limited, the Latin Alphabet, for instance, has 26 characters (letters), the Arabic alphabet has two or three more. As of September 2025, the largest character set in use is called Unicode 17.0.0. It defines a set of 159'801 characters, among which 101’996, nearly two-thirds, are CJK (Chinese, Japanese, and Korean) ideographs. But even when an alphabet has a size of one hundred thousand it is still limited and small in comparison to the size of the texts that can be generated based on this, or any other, alphabet.

A text is a sequence of characters, and every character represents a choice made among the letters of the alphabet. If my text starts with 'A' this means I selected 'A' from {'A', 'B', 'C' ... 'X', 'Y,''Z}. For the next letter of my text, I repeat the selection process, choosing, for instance, 'N' and then 'T' and so on. Every position in my text has 26—for the sake of simplicity, we stay with the Classical Latin all-uppercase alphabet—items to choose from and thus, for two positions we have 26 times 26 possible combinations, for three positions 26 times 26 times 26 (26 to the power of 3\) combinations which equals 17'576 possible texts of three letters length.

The number of combinations grows very fast and a text of 40 lines with 80 characters each has such a vast number of possible combinations of letters that our universe would be much too small to hold all the pages we could fill with them.

If we let a machine choose characters at random we'll most likely end up with something like this:

```
     DMBTBQQEOBNCUKJLMNFFLWDWHGQOINRLLEBJHGFYYXKPVKBZEHEXIVLMOJEBHDRRDFMUEGDWZTEKBOHC    LNLDAXVLEUUURCXEZASCMKPUBLAGZQONXUBOLEVDFKXUGDSSMUHSZQKIFEGCCXDEJPPMDWIIBRYSWTDV     BXNJKVZWREDXZRCKTJJZVAQDBUXYEHFLZKUPNTDUWATGLEHOTNWRVOQEKMGCIISSVIDBUHLCBIPDIIWO
```

Technically, every sequence of characters counts as 'text' and can be saved on a computer disk as '.txt' file. The definition of text per se does not restrict the length of a text but in the real world we inhabit the constraints of storage and processing put strict limits on how long our texts can become.

In order to handle text, people who wrote them had to break down the sequence of letters into lines, pages, and books. So we can, for example, have a book with 410 pages, each of which has 40 lines at 80 characters, bringing the total to 1'312'000 characters.

### The Library of Babel

In 1941, the Argentine author and librarian Jorge Luis Borges (1899–1986) published a short story under the title: *La biblioteca de Babel*. In this story, he imagines a vast library filled with books of uniform size, the 410 pages we just mentioned, and convincingly argues that somewhere in this library there must be a book that contains your biography from birth to death with all the exact dates and places. But there will also be false biographies of you or your biography but with another name attached to it and so on.

The problem we, as readers, have with this library is that we can be sure a certain text is there but we have no way to find it. It would take an amount of time greater than the lifespan of the universe to scan the volumes and pages, and we still couldn't be sure where to find our biography or tomorrow's sports results. We'd be facing an ocean of gibberish that conceals the one pearl we are looking for.

Yes, the Library of Babel is there, at least as an idea, but it is a forbidding place, an endless labyrinth where we get lost forever, searching for meaning and finding nothing but random noise.

### An Army of Typing Monkeys

The idea of a The Library of Babel is closely related to the so called Infinite Monkey Theorem which says that a monkey—or a whole army of monkeys—hitting keys independently and at random on a typewriter keyboard for an infinite amount of time will almost surely type any given text, including the complete works of William Shakespeare or your biography, for that matter. However, the monkeys will not do so in the time our universe exists as a study cited by the BBC claimed in 2024\. (Reference: [Monkeys will never type Shakespeare, study finds](https://www.bbc.com/news/articles/c748kmvwyv9o))

To speed up text production, we can use computers and we can generate huge amounts of text in a relatively short time but even with the fastest computers we'd still not be able to exhaust the possibilities of arranging letters on pages and pages in books.

And so, since finding islands of meaning in an ocean of random gibberish is practically impossible, we have to look elsewhere for a way to navigate the rough seas.

### Machines that write

From what we have discussed so far, it should be clear that a definition of text as sequence of characters is far too wide to be useful in the context of writing. Writing is more than randomly stringing characters together. Writing produces texts that have form and structure, obey rules, and finally yield meaning.

Programmable computers first appeared in the 1940s with Konrad Zuse’s Z3 (1941) and Tommy Flowers’s Colossus Mark 1 (1943). A decade later, in 1952, Christopher Strachey wrote a computer program that generated love letters, the first of its kind. In 1959, the German computer scientist Theo Lutz used a Zuse Z22 computer to write “Stochastische Texte,” sequences of words that resembled poems.

The year 1966 marks the creation of two other memorable projects of computer generated text:

- Joseph Weizenbaum’s *ELIZA:* a clever interactive algorithm that simulates a dialogue with its user  
- Nanni Balestrini’s *Tristano:* an experimental generative novel that was conceived to be read by each reader differently, since each sentence is randomly shuffled.

Reference:  
Lutz [https://zkm.de/de/werk/stochastische-texte](https://zkm.de/de/werk/stochastische-texte)  
Balestrini [https://www.theguardian.com/books/2014/feb/13/nanni-balestrini-tristano-novel-technology](https://www.theguardian.com/books/2014/feb/13/nanni-balestrini-tristano-novel-technology)

Ever since John McCarthy coined the term “artificial intelligence” (AI) in 1956, researchers in this field have tried to create algorithms that are able to understand human language and produce output that looks like human language and can be understood by human readers.

The early attempts at text generation resulted in character sequences that had, undeniably, much in common with text written by humans: the sequences were divided into words and sentences, the words were taken from existing dictionaries, the sentences followed the rules of grammar. But, in cases where they were the result of stochastic processes, the texts didn’t make much sense or, in cases where fixed templates were used, they were all variations of one and the same structure.

After early experiments with random and template-based algorithms, a period followed in which rules were thought to be the foundations of language. Prior work by Noam Chomsky had a great if only indirect influence on computer linguistics as the field was now called. Chomsky had proposed a rigorous formalism for the description of syntax and researchers in the fields of machine translation and artificial intelligence hoped to solve some fundamental problems by applying rules to language. But after years of enthusiastic study, efforts to create “expert systems” ran into a cul-de-sac and AI research entered its second winter.

With the exponential growth of storage capacity, memory, and processing power, new approaches to the hitherto unsurmountable barriers proved successful. Statistics and neuronal networks were the keys to the kingdom. They required massive amounts of memory space and huge numbers of calculations but this brute force attack paid out. Finally, with the introduction of the transformer architecture, the machines learned to speak and understand human language.

Author: mtg
Status: draft
