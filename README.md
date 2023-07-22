# The English Programming Language

![Static Badge](https://img.shields.io/badge/version-4.2023.7-blue) ![Static Badge](https://img.shields.io/badge/status-stable-green) ![Static Badge](https://img.shields.io/badge/forks-150-red) ![GitHub Repo stars](https://img.shields.io/github/stars/theletterf/english-lang) [![Twitter Follow](https://img.shields.io/badge/follow-remoquete?logo=twitter&style=social)](https://twitter.com/remoquete)


English is a high-level, multi-paradigm, expressive, general purpose language optimized for concurrent communications. English has been successfully used in a wide variety of scenarios, such as long-term data storage, analog and digital arts, and text-based adventures, to name a few. To date, English is used on more than 1,456 million carbon-based devices, and powers more than five million books.

English has been designed over the course of fourteen centuries. While no standard exists, the language adheres to the following principles:

- Portability: English follows a Write Once, Read Anywhere, Then Rewrite (WORATR) philosophy.
- Extensibility: Like Lua, English can borrow constructs and keywords from other languages.
- Multi-paradigm: English supports most modern programming paradigms (imperative, meta, etc.)
- Resilience: English programs can execute on organic hardware despite severe syntax errors.
- Polymorphism: English evolves over time without having to refactor existing codebases.

English's stability makes it ideal for long-term projects where data integrity is more important than precision: The last breaking change in the specifications happened five centuries ago and there are no plans for further major releases.

English's mantra is "there's more than one way to say it".
 
## Syntax

This is a typical English program that implements the Frost pathfinding algorithm:

```
Two roads diverged in a yellow wood,
And sorry I could not travel both
And be one traveler, long I stood
And looked down one as far as I could
To where it bent in the undergrowth;

Then took the other, as just as fair,
And having perhaps the better claim,
Because it was grassy and wanted wear;
Though as for that the passing there
Had worn them really about the same,

And both that morning equally lay
In leaves no step had trodden black.
Oh, I kept the first for another day!
Yet knowing how way leads on to way,
I doubted if I should ever come back.

I shall be telling this with a sigh
Somewhere ages and ages hence:
Two roads diverged in a wood, and I—
I took the one less traveled by,
And that has made all the difference.
```

- English uses whitespace and commas to delimit words, relying heavily on punctuation. 
- Correct statements within a block are written in sentence case, except:
    - Independent declaratory statements of class "title" or class "headline" may be _all upper case_, or _title case_
    - Title case is similar to pascal case, but with whitespace between each keyword.
- Statements can end with a period or, less frequently, with a semicolon.
    - Statements of the list, title, or headline classes can end with a line break.
- Blocks using hard-wrap are separated by two or more line breaks. 
- Blocks using soft-wrap are separated by a single line break.
    - Most modern English IDEs default to soft wrap, however hard wrap is a requirement for some legacy devices such as the one called "typewriter" and the one known colloquially as "pen & paper".
- Line numbering is still used in some paradigms such as legal.


### Operators

English uses the following operators:

- `!`: Emphasize execution (similar to CSS's `!important`). Can be stacked
- `?`: Request information or open data stream thread. Can be stacked
    - `?!` The request and emphasize operators can be stacked together. See _overloading_
- `,`: Concatenate statements in the same block. See keywords _and or_
- `.`: End of statement  
- `;`: End of statement (weak, can not end a block)
- `\n`: End of block, immediately after the `.` (hard-wrap IDEs require `\n\n`)
- `:`: Definition, for example for functions or clauses  
- `...`: Temporarily suspend async execution (similar to `await`)
- `—`: Short break in execution or definition of list items
- `-`: Combine keywords into a group or split a keyword across a newline
- `&`: Combine keywords or sub-statements into a non-exclusive set
- `/`: Combine keywords maintaining independence and/or exclusivity
- `†`: Reference to a footnote class comment and comment identifier
- `(`: Open inline code comment<sup>†</sup>, close with `)`
- `"`: Import value from another module or class
- `'`: Nested imported value inside another import
- `¶`: Indicate block start in some paradigms (arcane)
- `§`: Indicate section break in some paradigms (such as legal)


<sup>†</sup>Code comments are added using parentheses or round brackets. Unlike other programming languages, English executes code comments with lower priority to enrich execution context and debug logging. For example:

```
(This is silly.)
```
However comments of the footnote class, and related external reference classes, are only executed optionally as determined at runtime, therefore the main code must not be dependent on footnote class or external reference class objects.

**Overloading:** English operators can be overloaded, although this is not recommended by the ENG23 committee.

### Statements and control flow

English statements are free-form and execution depends on the interpreter's training, as well as word order. Conditional execution and exception handling also depend on the mood and tense of the keywords, as well as resources available.

### Keywords

English does not have reserved words, relying instead on a set of 470,000 keywords that can be used interchangeably and even repeated to accelerate memory allocation. The training process results in scores that make the usage of certain keywords less likely. Keywords that score higher in the profanity dimension might cause the system to panic.

## Data structures

English only has two data structures, Lists and Raw. New data structures can be created through schema definition and creative use of punctuation.

## Typing

English uses context-sensitive and duck typing. The only base types are `strings` and `numbers`, with no size limit. Buffer overflows are typically handled by the interpreter, which performs just-in-time (JIT) type casting and guessing. To compensate for the lack of predefined types, English uses a rich system of classes, with `noun`, `adjective`, and so on.

## Documentation

English programs are self-documenting and implement literate programming.

## Tooling

Currently, the only compiler available is Wernicke. It requires a temporal lobe trained in social settings for at least three to four years, though better results can be achieved with training runs in excess of 30 years.

Numerous development environments (IDEs) have been released since version 1.0. The most common editors for English are Word and Docs, although programs can still be written in WordPerfect, Vi, and emacs. English is unique in that it can be coded on almost any medium capable of supporting scratches and marks, such as paper, stone, or clay.

There are millions of English libraries available. You can look for the closest in Google Maps.

## Community

The English community is vibrant, with more than 150 distributions available. For a complete list of forks see [List of dialects](https://en.wikipedia.org/wiki/List_of_dialects_of_English).
