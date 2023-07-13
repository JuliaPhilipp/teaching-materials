# Markdown Workshop

## Tools
Text editor - not word and not notepad / textedit, e.g. sublime editor or text wrangler - these are free

## What is markdown
- a markup language (in German Auszeichnungssprache), a machine readable language for organising and formatting text (a famous exmaple is html)
- a play of words on markup, maybe because it is so easy?
- used e.g. by Github. You can upload a markdown file and view a beautifully formatted text page, like this one :wink

## What do you need to do?
1. Use a text editor (see tools above) to create a file containing text and saving it as an .md file
2. Format the text using markdown language to include things like headers, links, checklist, and bullet points.
3. Upload it to Github to see the magic happen

## Markdown Formatting

### Headers
Use Hashtags to mark headers. The more hashtags, the smaller the header. So start with one # to mark the biggest header
```
# Header
## Subheader
### Subsubheader
```

### Lists
Use Dashs for unordered lists, numbers for ordered lists, brackets for checklists. By the way, the numbers for the numbered list don't actually have to be in numerical order. Try it out!
```
- this
- is
- an
- unordered
- list

1. this
2. is
3. an
4. ordered
5. list

1. this
8. is
4. also
3. an ordered list


- [ ] this
- [ ] is
- [ ] a
- [x] checklist
```
The part above will interpreted to look like this
- this
- is
- an
- unordered
- list

1. this
2. is
3. an
4. ordered
5. list

1. this
8. is
4. also
3. an ordered list

- [ ] this
- [ ] is
- [ ] a
- [x] checklist

### Emphasis & Links
Highlight words in text using the following markup. Notice that these markup symbols are placed *before* and *after* the highlighted portion of the text.
```
**bold text**

*italicized text*

_also cursive text_

*_bold and italicized text_*

~~strike through text~~

[a link to google](www.google.de)
```

#### The part above will interpreted to look like this

**bold text**

*italicized text*

_*bold and italicized text*_

~~strike through text~~

[a link to google](www.google.de)

### Code (Highlights)
Two backticks \`\` will highlight code in line with normal text. Like this `.md` \
Three backticks \`\`\` at the beginning and end will be interpreted as whole chunks of code. Notice the little copy symbol in Github!

\`\`\`

plot(  
    c(0, 1, 1),  
    c(0, 0, 1),  
    pch = 16,  
    cex = 2,  
    xaxt = "n",  
    yaxt = "n",  
    xlab = "",  
    ylab = "",  
    bty = "n",  
    xlim = c(-0.25, 1.25),  
    ylim = c(-0.25, 1.25)  
)

\`\`\`

will look like this
```
plot(
    c(0, 1, 1),
    c(0, 0, 1),
    pch = 16,
    cex = 2,
    xaxt = "n",
    yaxt = "n",
    xlab = "",
    ylab = "",
    bty = "n",
    xlim = c(-0.25, 1.25),
    ylim = c(-0.25, 1.25)
)
```

### A word on line breaks
Just hitting the enter/return key is not going to create a line break in markdown, unlike in Word. But you can use two or more whitespaces at the end of your line (so called trailing whitespace) to mark line breaks.  
Alternatively, you can use the html code ``<br>`` for a line break. <br>
Not all markdown applications accept this for security reasons.

## Resources
- [Basic Syntax of Markdown](https://www.markdownguide.org/basic-syntax/)

