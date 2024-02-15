## Rant on Modern Programming

After checking various resources, I've come to the conclusion that programming, reverse engineering, & cybersecurity are subjects that are too technical and time consuming to be written & shared within a commercially simplistic product as a book. There are too many variables that could lead to misinformation. Else, it's all over the place. Some of the best resources I've found were free; books, videos, even the occasional post on some obscure forum with a unique answer to my problem that no one else could figure out how to solve. Why is it that the best answers are hidden off in some corner of the internet? This information should be public and easy to understand. Why is it that after so many strenuous years of confusion, professional and hobbyists programmers struggle to solve their own problems? *such as installing Linux*

Yes, free or 'open source' books & resources are the best with the authors intent in their readiness of distributing that knowledge. Paid content is usually a one and done case, proceeded by the next book or sponsor in the chain... more importantly tech books are useless anyway. Ironically, even though the OP of this repo is the type of person that would acquire any book with the word 'modern' in the title, as soon as that info is released, it's no longer relevant, while the latest technology is often theoretical. Most of you have books obsolete due to the tech gaps jumping every *roughly* five years. So how do we escape this 'problem'? This endless sea, this despair we call ever changing technology? We simply abandon whatever new tools arise or become defunct, and stick with what works, until it doesn't.

I was tired of finding 10+ year old rhetoric that has already changed or subject to. However, some of these old books were future proofed by genius authors.. perhaps they had the ability to see into the future. Topics like AI have hardly changed, a lot of old school techniques are probably even more effective now than when they were first discovered. Try playing the original 'F.E.A.R'. Decent AI and is a challenge even on normal difficulty. Much harder than any modern title released today, what with lazy AI, glitches, and pigeon holed programming. 

### So what do we do?

Use a fresh resource you get within the same year-2. If the data isn't new, but can be improved, do so. Several times over, have I discovered that, in my search for quality tutorials and info, these 'prestigious' books were filled with redundant code/architecture which wouldn't even compile. Do not waste your money with outsourced, non-debugged commercial products written by so-called 'experts' of these languages. Working 2x as hard carries the same risks. <a href="https://www.atlassian.com/blog/productivity/this-is-how-many-hours-you-should-really-be-working">Don't overwork yourself</a>. <a href="https://www.cnbc.com/2015/01/26/working-more-than-50-hours-makes-you-less-productive.html">Avoid productivity loss</a>. Only work more if you absolutely have to. I.E you owe the mafia. 

An alternative to looking for outdated resources, free or no, is to frequent blogs, forums, & videos. You may not learn much or as quickly had you simply picked 
up a book. But if you aren't reading, then you're probably coding anyway. And if you aren't coding, then what are you here for? This project is for coders, go on.

* Most of Windows & Linux API is in C. C++ was the defacto language for projects.
* Companies are now shifting toward Rust, Go, etc. Google is attempting to supercede C++ with Carbon.
* Rust is popular amongst programmers, but still not prevalent in business, despite recent implementation.

  Binary = Assembly > C, C++ etc > Javascript etc > Python > Java(sucks). 
Learn C, x86, Rust, Go, & Python

Seems like Cybersecurity is a vague term, there are a lot of different names for the same thing, but the most general and accesible field is networking. It's easier to learn than Assembly since the internet is constantly being updated, so knowing network administration is great.

### Status

* Ghidra has been gaining popularity despite using Java.
* IDA industry standard, but policies restrict use.
* Binja has been improving recently.

There are too many assembly languages, some are now depreciated.
ARM, NASM, FASM/G & YASM are good to learn. Users mentioned NASM is bloated with C and the source code is not as elegant as FASM(100% assembly of itself).
Conversely, FASM has *many* resources to get up to speed with it. YASM might replace NASM due to features.

YASM is about as popular as both NASM & FASM, however the utility is more important for a
general assembly language to learn. In general, I'd learn YASM or FASM. Followed by ARM if necessary.
Pro reversers recommend to start with ARM, not Intel x86/64 due to using deeper infrastracture, ARM is simple, 
and used for many embedded devices. You may even own an ARM device right now. Or you could emulate it.

<details><summary>High level languages</summary> 

Personal Recommendation:
Learn C, C++, and Python, then [Rust](https://github.com/anshulrgoyal/rust-web-developer-roadmap)/[Go](https://roadmap.sh/golang)

You'll need C and C++ for legacy hardware, games, and Windows stuff.
Python is just good to have. Rust is convienent, powerful, it might replace C/C++
'Go' for the same reasons, it's another modern language to know that may transition over into Carbon's release.

Go is easier to learn than Rust due to simplicity, but it 
also has similiar effectiveness to Rust and C. (Meaning it's faster than
Python). </details>

Python is the most popular language in the world right now, but Julia can do the same things and is faster, with a potentially better syntax and documentation.
Because of this, Python tutorials are saturated as everyone has an interest in data science right now, picking Python as a first language may be dangerous if it's 
not for personal projects. Even with the simplicity of the language, many authors simply want to ride the stream of it's recent success. Perhaps pick a more general language?

### Funny quotes

> I threw it away. I resent the entire premise of being asked stupid coding puzzles that have nothing to do with the job at hand. I've interviewed at Google, Amazon, Microsoft and a dozen other smaller companies. Got rejected from some, got offers from others, now I'm an engineering manager at one of them. I still think coding interviews are a scourge on this industry that select the types of people that study coding problems instead of how to write and deliver good software.

``` The proper answer is never to utilize these skid forums and tutorials on how to "hack games". You might learn a little, but you will also learn many incorrect things. Don't be a victim of information pollution and people trying to monetize mediocre content. ```

  * Learn [cpp](https://www.learncpp.com/)
  * Learn [Windows Internals](https://www.amazon.com/Windows-Kernel-Programming-Pavel-Yosifovich/dp/B0BW2X91L2/)
  * Learn how to use IDA Pro or Ghidra
  * Read RE for Beginners
  * Find some targets to test & learn from
  * Eventually, pick up some assembly 

> The solution is easy; do not use Windows. 
<pre>I am convinced that 90% of all computer books are written to obscure a fairly straightforward subject, and <a href="https://www.amazon.com/product-reviews/1118290275">this one</a> is no 
exception. Computerese, like mathematical rigor, resents the practical nature of its chosen study. Turing proved way back 
that an extremely abbreviated constellation of computational constructs can solve any problem -- and the world's mathematically 
inclined but equally <em>moronic</em> fools have, ever since, labored hard and diligently to heap confusion over this simplicity. 
Ever wonder why your applications are so frustrating, and seem to become moreso with every update and reincarnation? Read this book.
</pre> 

```The complexity is unnecessary. A good technical book must be either **crystal clear** or *extremely accurate*. To be dense and careless is unfair to the reader, who must take the time to decode each and every word carefully in order to determine the meaning.```

> What one fool can do, another can. And in **mathematics**, *we are all fools..*

> In theory, practice and theory are the same. In practice, they're *different*.

<pre>It is utterly horrible. Very simple concepts explained in such a way as to make them confusing, with strange notation, 
terrible figures, and very little English analysis or context. I only read the first thirty pages, but oh man were they 
bad. I have some background in ML, a pretty strong math background, and a PhD in biophysics, and there is nothing I hate 
more than simple things I already understand or could easily understand, explained so as to be incomprehensible.
</pre> 
