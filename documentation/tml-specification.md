(TML Specification v.1.01)

# PAGE LAYOUT
## Page sizes by name
{papersize:letter}
{papersize:legal}
{papersize:statement}
{papersize:tabloid}
{papersize:ledger}
{papersize:folio}
{papersize:quarto}
{papersize:trade}
		
{papersize:executive}
{papersize:10x14}
{papersize:a3}
{papersize:a4}
{papersize:a5}
{papersize:b4}
{papersize:b5}
{papersize:6x9}
		
{pagesize:letter}
{pagesize:legal}
{pagesize:statement}
{pagesize:tabloid}
{pagesize:ledger}
{pagesize:folio}
{pagesize:quarto}
{pagesize:trade}
		
{pagesize:executive}
{pagesize:10x14}
{pagesize:a3}
{pagesize:a4}
{pagesize:a5}
{pagesize:b4}
{pagesize:b5}
{pagesize:6x9}

## Page width and height
{pagewidth:nx}
{pageheight:nx}
		
{paperwidth:nx}
{paperheight:nx}

## MARGINS
{marginleft:nx}
{marginright:nx}
{margintop:nx}
{marginbottom:nx}
{margins:nx nx nx nx}

## FONTS
{fontfamily:avant-garde}
{fontfamily:avantgarde}
{fontfamily:avant-garde}
{fontfamily:bookman}
{fontfamily:helvetica}
{fontfamily:helvetica-narrow}
{fontfamily:helveticanarrow}
{fontfamily:new-century-schoolbook}
{fontfamily:newcenturyschoolbook}
{fontfamily:palatino}
{fontfamily:times-roman}
{fontfamily:times}
{fontfamily:zapf-chancery}
{fontfamily:zapf}
		
## FONT STYLE
{fontstyle:roman}
{fontstyle:r}
{fontstyle:italic}
{fontstyle:i}
{fontstyle:bold}
{fontstyle:b}
{fontstyle:bold-italic}
{fontstyle:bolditalic}
{fontstyle:bi}
{fontstyle:smallcaps}
{fontstyle:sc}
		
## FONT SIZE
{fontsize:x}

## LINE SPACING/LEADING
{leading:10/13} => sets PT_SIZE to 10 and .LS to 13 at same time
{autoleading: [factor of] 2}  => not implemented yet. 
{linespacing:13}

## JUSTIFICATION 
{justfication:left}
{justfication:right}
{justification:center}
{justification:full}

## PARAGRAPHS
{paragraphindent:nx}
{paragraphspace:nx}
{linelength:3i}

## KERNING/LIGATURES
{kerning:on}
{kerning:off}
{ligatures:on}
{ligatures:off}

## HYPHENATION
{hyphenation:on}
{hyphenation:off}
{hyphenationlanguage:spanish} => not implemeted yet
{hyphenationmax:x}
{hyphenationmargin:x}
{hyphenationspace:x}
{hyphenation:reset}

## SMARTQUOTES
{smartquotes:on}
{smartquotes:off}
{smartquotes:danish}
{smartquotes:german}
{smartquotes:spanish}
{smartquotes:french}
{smartquotes:italian}
{smartquotes:dutch}
{smartquotes:norwegian}
{smartquotes:portugese}
{smartquotes:swedish}

{smartquotes:da}
{smartquotes:ge}
{smartquotes:es}
{smartquotes:fr}
{smartquotes:it}
{smartquotes:nl}
{smartquotes:no}
{smartquotes:pt}
{smartquotes:sv}

# LANGUAGE
{language:spanish} => (not implemented yet) maybe make it so that language also determines hyphenation language automatically.

# PRINT STYLE
{typeset}
{typewriter}
{typewriter:singlespace}

## METADATA TAGS
[author]
[title]
[doctitle]
[subtitle]
[chaptertitle]
[draft]
[revision]
[covertitle]
[doccovertitle]
[pdftitle]

## DOCUMENT ELEMENT TAGS
[include] path-to-external-file.xxx
[start]
[tableofcontents]
[epigraph]
[epigraphblock]
[h1]/[heading1]/[chapter]/[chap]
[h2]/[heading2]/[section]/[sec]
[h3]/[heading3]/[subsection]/[subsec]
[blockquote]
[quote]
[list]
[list:digit]
[list:dash]
[list:bullet]
[list:alpha]
[list:ALPHA]
[list:romanX]
[list:ROMANx]
[list:square]
[list:hand]
[list:arrow]
[list:dblarrow]
[list:checkmark]
[list:user x]
[*footnote]
[endnote*]
[newpage]
[break] / [br] / [linebreak]
[finis]

## COMMANDS
### Pseudo
<bolder x<...>
<slant x<...>
<condense x<...>
<extend x<...>
<up x<...>
<down x<...>
<forward x<...>
<back x<...>
<caps -1<...>

### Size
<+n<...>
<-n<...>
<n<...>
<size n<...>

<bold<...> / <bld<...> / <b<...>
<italic<...> / <it<...> / <i<...>
<smallcaps<...> / <sc<...>
<uppercase<...> / <caps<...> / <uc<...>
<lowercase<...> / <lc<...>


## Kerning
<-x> / <+n> => T<-2>he trees turned to dust.

# Alignment

#


## COMMENTS:
# => the # symbol denotes a comment.  replaced with \#

## SPECIAL CHARS
|en| / .. - .. 
|em| / ..--.. 

### Plus/minus (arithmetic) \[+-] 
|+/-|

### Subtract (arithmetic) \[mi]
|-|

### Multiply (arithmetic) \[mu]
|x|

### Divide (arithmetic) \[di]
|/| 

### Left double-quote \[lq] 
|lq|

### Right double-quote \[rq]
|rq|

### Open (left) single-quote \[oq]
|oq|

### Close (right) single-quote \[oq]
|oq|

### Bullet \[bu] 
|bu| / [bullet]

### Ballot box \[sq]
|sq|
|square|

### One-quarter \[14] 
|1/4|

### One-half \[12] 
|1/2|

### Three-quarters \[34] 
|3/4|

### Degree sign \[de] 
|de| / [deg] / [degree]

### Dagger \[dg] 
|dg| / [dagger]

### Foot mark \[fm] 
|fm| / [footmark]

### Cent sign \[ct] 
|ct| /[cent]

### Registered trademark \[rg] 
|rg| / |tm| / [trademark]

### Copyright \[co] 
|co| / [copyright]

### Section symbol \[se]
|se] 

### Foot and Inch \[foot] \[inch]
|'|
|"|

### Braces and brackets (curly, square and greater/less than symbols have special significance in TML. enclosing them within [] treats them as tags
|{| / |lc|
|}| / |rc| 
|<| / |lt| 
|>| / |gt| 
|[| / |ls| 
|]| / |rs| 
