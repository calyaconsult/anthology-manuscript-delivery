# Synthetic Texts

## An Anthology

### Curated by Michael Glünz

Published by Calya Digital Publishing Services  
an imprint of Calya Consult GmbH, Zug, Schweiz

# Introduction

## Can AI write?

### Writing as Text Production

In the technical realm, a text is a sequence of characters, encoded as ASCII, UTF-8, UTF-16, UTF-32, or any other form of character encoding. A character is defined as element of a character set, the non-technical term being "alphabet." Character sets are limited, the Latin Alphabet, for instance, has 26 characters (letters), the Arabic alphabet has two or three more. As of September 2025, the largest character set in use is called Unicode 17.0.0. It defines a set of 159,801 characters, among which 101’996, nearly two-thirds, are CJK (Chinese, Japanese, and Korean) ideographs. But even when an alphabet has a size of one hundred thousand it is still limited and small in comparison to the size of the texts that can be generated based on this, or any other, alphabet.

A text is a sequence of characters, and every character represents a choice made among the letters of the alphabet. If my text starts with 'A' this means I selected 'A' from {'A', 'B', 'C' ... 'X', 'Y', 'Z'}. For the next letter of my text, I repeat the selection process, choosing, for instance, 'N' and then 'T' and so on. Every position in my text has 26—for the sake of simplicity, we stay with the Classical Latin all-uppercase alphabet—items to choose from and thus, for two positions we have 26 times 26 possible combinations, for three positions 26 times 26 times 26 (26 to the power of 3\) combinations which equals 17,576 possible texts of three letters length.

The number of combinations grows very fast and a text of 40 lines with 80 characters each has such a vast number of possible combinations of letters that our universe would be much too small to hold all the pages we could fill with them.

If we let a machine choose characters at random we'll most likely end up with something like this:

```
     DMBTBQQEOBNCUKJLMNFFLWDWHGQOINRLLEBJHGFYYXKPVKBZEHEXIVLMOJEBHDRRDFMUEGDWZTEKBOHC    LNLDAXVLEUUURCXEZASCMKPUBLAGZQONXUBOLEVDFKXUGDSSMUHSZQKIFEGCCXDEJPPMDWIIBRYSWTDV     BXNJKVZWREDXZRCKTJJZVAQDBUXYEHFLZKUPNTDUWATGLEHOTNWRVOQEKMGCIISSVIDBUHLCBIPDIIWO
```

Technically, every sequence of characters counts as 'text' and can be saved on a computer disk as '.txt' file. The definition of text per se does not restrict the length of a text but in the real world we inhabit the constraints of storage and processing put strict limits on how long our texts can become.

In order to handle text, people who wrote them had to break down the sequence of letters into lines, pages, and books. So we can, for example, have a book with 410 pages, each of which has 40 lines at 80 characters, bringing the total to 1,312,000 characters.

### The Library of Babel

In 1941, the Argentine author and librarian Jorge Luis Borges (1899–1986) published a short story under the title: *La biblioteca de Babel*. In this story, he imagines a vast library filled with books of uniform size, the 410 pages we just mentioned, and convincingly argues that somewhere in this library there must be a book that contains your biography from birth to death with all the exact dates and places. But there will also be false biographies of you or your biography but with another name attached to it and so on.

The problem we, as readers, have with this library is that we can be sure a certain text is there but we have no way to find it. It would take an amount of time greater than the lifespan of the universe to scan the volumes and pages, and we still couldn't be sure where to find our biography or tomorrow's sports results. We'd be facing an ocean of gibberish that conceals the one pearl we are looking for.

Yes, the Library of Babel is there, at least as an idea, but it is a forbidding place, an endless labyrinth where we get lost forever, searching for meaning and finding nothing but random noise.

### An Army of Typing Monkeys

The idea of a Library of Babel is closely related to the "infinite monkey theorem" which says that a monkey—or a whole army of monkeys—hitting keys independently and at random on a typewriter keyboard for an infinite amount of time will almost surely type any given text, including the complete works of William Shakespeare or your own biography. However, a study published in 2024 by Stephen Woodcock and Jay Falletta took a closer look at the numbers and reached the conclusion that in a finite universe there is simply not enough time, nor are there enough monkeys, to generate even a relatively short non-trivial text by letting the monkeys do the typing.

Reference: [A numerical evaluation of the Finite Monkeys Theorem](https://www.sciencedirect.com/science/article/pii/S2773186324001014)

To speed up text production, we nowadays have computers that are able to generate vast amounts of text almost in an instant but even with the fastest computers we would still not come anywhere near the immense number of possible combinations of letters on a page, let alone the number of books filled with such pages.

And so, since finding islands of meaning in an ocean of random gibberish is practically impossible, we have to look elsewhere for a way to navigate the rough seas.

### Machines that write

From what we have discussed so far, it should be clear that a definition of text as sequence of characters is far too wide to be useful in the context of writing. Writing is more than randomly stringing characters together. Writing produces texts that have form and structure, obey rules, and finally yield meaning.

Programmable computers first appeared in the 1940s with Konrad Zuse’s Z3 (1941) and Tommy Flowers’s Colossus Mark 1 (1943). A decade later, in 1952, Christopher Strachey wrote a computer program that generated love letters, the first of its kind. In 1959, the German computer scientist Theo Lutz used a Zuse Z22 computer to write “Stochastische Texte,” sequences of words that resembled poems.

The year 1966 marks the creation of two other memorable projects of computer generated text:

- Joseph Weizenbaum’s *ELIZA:* a clever interactive algorithm that simulates a dialogue with its user; to Weizenbaum's surprise, some users of *ELIZA* entered into discussions of real-life problems with this algorithmic "therapist."
- Nanni Balestrini’s *Tristano:* an experimental generative novel that was conceived to be read by each reader differently, since each section is randomly shuffled. Owing to the technical limitations of 1960s printing presses, it took several decades for the author’s vision to materialize as a series of printed books, each featuring a unique arrangement of sections.

Reference:  
Lutz [Stochastische Texte](https://zkm.de/de/werk/stochastische-texte)  
Balestrini [Tristano](https://www.theguardian.com/books/2014/feb/13/nanni-balestrini-tristano-novel-technology)

Ever since John McCarthy coined the term “artificial intelligence” (AI) in 1956, researchers in this field have tried to create algorithms that are able to understand human language and produce output that looks like human language and can be understood by human readers.

The early attempts at text generation resulted in character sequences that had, undeniably, much in common with text written by humans: the sequences were divided into words and sentences, the words were taken from existing dictionaries, the sentences followed the rules of grammar. But, in cases where they were the result of stochastic processes, the texts didn’t make much sense or, in cases where fixed templates were used, they were all variations of one and the same structure.

Noam Chomsky's 1957 book "Syntactic Structures" marks a breakthrough in structural linguistics. Chomsky separates language as an abstract system (competence) from the concrete utterances of human speakers (performance) and defines syntax as a finite set of rules capable of generating an unlimited number of sentences. Chomsky's work not only had a profound influence on theories of human language but it also laid the foundations for the development of programming languages, i.e., formal systems that transform human readable program input into the executable machine code of computers.

For some time, culminating in the 1980s, rules were thought to be the solution for understanding language as well as  solving many other kinds of problem. A lot of research went into “expert systems.” An expert system is a collection of rules that, when applied in the right sequence to a basis of known facts, can map a question to its correct answer. In 1972, Alain Colmerauer and Philippe Roussel at the University of Aix-Marseille in France developed a special programming language for the PROcessing of LOGical problems and named it PROLOG. In numerous cases, it proved its eminent value as a tool for implementing expert systems but it missed its original goal, namely to facilitate language processing.

In the 1990s, the enthusiasm that had accompanied visions of artificial intelligence based on expert systems and rule-based problem solving cooled off and most research activity went into a different direction. Human language in all its complexity seemed out of reach for computers. Speech synthesis resulted in unnatural sounding voices, speech recognition reached its limits when more than one speaker or more than simple sentences were involved, and machine translation produced awkward, sometimes even laughable results.

But slowly, new methods of studiying language gained traction. Reserchers in the field of Natural Language Processing (NLP) experimented with neural networks and statistical approaches like Markov models or Bayesian networks. And with the exponential growth of storage capacity, computer memory, and processing power, new approaches to some of the hitherto insurmountable barriers were, at last, successful. Statistics and neural networks proved to be the keys to the kingdom. They required massive amounts of memory space and huge numbers of calculations but this brute force attack paid out. Finally, with the introduction of the transformer architecture, the machines learned to speak and understand human language.

In todays's parlance, outside the acadamic circle opd AI researchers, the term "Artificial Intelligence" (AI) is used more or less as a synonym for "Large Language Model" (LLM). An LLM is a statistical model of how different aspects of language are related to each other. They are usually based on very large amounts of text, going into the billions of individual documents. In a process called "training," the documents are broken down into pieces called "tokens"-which can be words or parts of words-and represented by mathematical vectors. These vectors are fed into gigantic neural networks with billions of "weights" (also called "parameters") which are then repetedly adjusted until the accuracy of predicting the next token in a sequence of tokens satisfies the expected value.

Author: mtg
Status: draft
