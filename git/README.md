$e^{i \pi} + 1 = 0, \ give \ or \ take...$


Please place some version of these notes; as you like; someplace stable. I treat GitHub as my 
"someplace stable" these days. Regardless of whether my laptop falls into a volcano on the sea floor: 
GitHub abides. 


I am writing these notes in the order they occur to me; so this is based on ***improvised pragmatism***.
This first part began as an enumeration but quickly devolves into a story.


> Another version of this material is in a Jupyter notebook in my **`ocean`** repo but it is a 
> bit hard to find. Chapter 5 I believe.


## 1. Markdown


GitHub supports markdown format: When a github file with extension `.md` is opened in Chrome
(say) the view reflects the rules of "markdown" as a formatting protocol. This includes a "default" 
file at the top of the repo called `README.md`. You might create a repo under your user account 
called **`howto`** which contains your notes for important / commonly used procedures. 
That repo need not have any Python or java or whatever; it might be entirely markdown. 


Common markdown formatting includes....


# Major Heading
## Subsection
### Subsubsection
#### Pretty fine grained at this point
##### Very fine grain


## 2. The back-tick character 


This is very useful: The back-tick usually found at keyboard upper left: \` .
Of course to print this character here I used 
the backslash *literal* delimiter; so what is in the markdown file is **\\\`**  . 


Use: Back-ticks create blocks of fixed-width font text, as in an older-style
computer terminal. This is useful for indicating or quoting `commands` and 
`computer code`. 


A single back-tick is used as a delimiter for 
code that remains inline with surrounding text. For example this sentence has a `True` in it. 


Use three back-ticks to delimit multi-line code blocks


```
def Bumpkins(n, iq):
    for i in range(n):
        print('oh dear, this is tragic...')
```

Notice that the back-tick is a *verbatim* delimeter. Other delimiters are not respected when they occur 
inside back-ticks. 
On the other hand, asterisk delimiters *outside* of backtick delimiters work great. 
`**this**` versus **`this`**. 


## 3. asterisks


In this text please find single, double, and triple asterisk delimiters. 
*Single*. **Double**. ***Triple***. Do ****four in a row**** do anything different? 


## 4. quotations


A leading `>` character renders text as a quotation. 


> This is useful to offset "special note" blocks of text. 


## 6. hyperlinks 


Place the text to appear within square bracks and follow it with no spaces by the link URL 
in parentheses. [This link goes to the Google search page](https://google.com). It
is constructed as `[link text](https://google.com)`. 


Within a document, cursor hover over headings reveals they have intrinsic link addresses.
You can copy and paste those links into the (hyperlink) following a \[link name\].
However for linking within a page you can just use the pound sign \# followed by
the header name; with spaces replaced by hyphens.
[This one goes up to the back-tick section](#2-the-back-tick-character), for
example. The link string here is `#2-the-back-tick-character`.



## 6. html


HTML can be embedded in a markdown file. This is useful, for example, to embed an image 
in a markdown page. More detail is out of scope at the moment. 


## 7. wandering off into the story


Now I turn to the last topic of this segment, a digression. The practical matter of `git` is 
deferred to a subsequent page.


Some years ago -- never mind how long precisely -- one of our heroes to whom you have not yet been 
introduced was asked to write a book. 
He was working as an assistant professor at a small college in Pasadena at the time; and he took a 
close look at the idea and upped
the ante in reply: "Yes, but wait! My idea is a more ambitious and a better book... in 12 chapters."  
Upon receiving approval 
he embarked on the project which has occupied him to this day, some 60 years later. He appears to 
have done some other work as well
in the mean time. 


The history of this book, which I shall refer to using the title acronym TAOCP, is beyond the 
scope of these notes. But it is 
by all accounts a remarkable book, or really collection, in six volumes so far. I have not read 
it as I have not needed it. 
But since I'm discovering it right now I shall check out a copy and we can take a look. It 
concerns algorithms, particularly 
computer algorithms. But back to our story. 


Some years went by from that 1962 starting point; and as technical books are often periodically 
revised. Volume 2 went through
this process in 1976. So it was that our subject received the proofs for TAOCP Volume 2; 
which had been 
typeset in a new manner. 


As an aside you might look up a thumbnail sketch of 'Tao'. It seems poetically appropriate
and when Professor Knuth is involved, I am starting to suspect that any found poetry is not 
accidental when he is involved. I offer as evidence the version numbering system used for
the software described below.
Ah, and it seems I have neglected to provide this individual's name so far.


Enter stage left one Donald Ervin Knuth. Just one anecdote from his biography: It is not common, 
upon an individual's completing their bachelor's degree, for the
faculty of their institution to conclude that they should also award the individual a master's degree. 


Anyway the proofs were considered inferior compared to how things looked in the first edition. 
So Professor Knuth did what anyone else would do upon receiving proofs that are plagued by inferior 
quality typesetting. He designed and wrote his own typesetting system and made sure it would 
be universally available for anyone's use at no cost. This system he named TeX. It went through
many revisions from 1978 to 1989 when it was 'officially' released; but I believe it was in
serious academic use when I started college in 1982.


This contribution to
open source usefulness has proven successful: Academics (and publishing companies and many
other adopters) have learned and adopted
TeX according to need; and have created thousands of books and hundreds of thousands of
articles that are readable. I would say transcend readable to beautiful. 
Forty years and counting, for decades to come. 


I do not write using TeX. To write my graduate thesis I became moderately 