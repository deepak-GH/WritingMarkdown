# single hash is heading one (similar to html tag)
## double hash is heading two (similar to html tag)
###### six hashes indicate heading six (similar to html tag)

NORMAL TEXT IS WRITTEN DIRECTLY.

*Italic text is wrapped in single asterics.*

**Bold text is wrapped in double asterics.**

~~A strikethrough is wrapped in double tilders on both sides.~~

ITALIC/BOLD/STRIKETHROUGH TAGS MUST HAVE A TRIMMED STRING WITHING IT.
UNNECESSARY SPACES AT START AND END MAKE THEM A NORMAL TEXT.


- UNORDERD LIST is made with a hyphen.
- I'm list item as well.
    - I am subItem of 2nd.
- I am 3rd item.
    - I am subItem of 3rd.
    - I am second subItem of 3rd.


1. ORDERED LIST is made with **1.**  *for all of its elements*
1. I am item 2.
1. I am item 3.
7. We can ALSO use numbering if we want to do explicitely. It shows Sequential number only irrespective of explicitely passed numbering.

For creating a CHECKLIST: we use *hypen-space-[space]* for Unchecked  and   *hyphen-space-[x]* for Checked item.
- [ ] this is unchecked.
- [x] this is checked.


For displaying a link use **(url)**   and   for showing a custom text for a given link use: **[customText]** before **(url)**

[customTextForMyProfileLink](https://github.com/deepak-GH)

For displaying an image SAME Approach is used with a *!* mark. 

Syntax:   **'!'+' [ '+' customText '+' ] '+' ( '+' path '+' ) '**

![A Watch](https://www.pexels.com/photo/round-gold-colored-analog-watch-with-pink-leather-strap-on-pink-notebook-1162519/)


Now, Moving on to use **TABLES**: 

First line is used for ColumnTitles separated by PIPE OPERATORS.

Second line uses colon and dashes (**:---**) to represent the ALIGNMENT of respective column.

Left = (**:---**)   and   Right = (**---:**)   and   Centre = (**:---:**)

Third line onwards, we fill the contents of each row keeping in mind the respective column order as used above.

| ID | NAME |
|:---|---:|
|130|Deepak Gupta|
|143|Sandesh Verma|

HOW TO INSERT CODE BLOCKS? Here it is: 

For Inline code use Single Backtick for enclosing code line.

This is inline code: `System.out.println();`

For Multiline code use Triple Backticks for enclosing code lines.   Example below:
```
System.out.println();
System.out.printf();
```

For Syntax Highlighting in the code lines put language name after Triple Backticks.   Example below:
```java
System.out.println();
System.out.printf();
```

To show the difference between two code blocks; Instead of using two different blocks we use **diff** in place of *Language name.*

Use **+** for Green highlighting and **-** for red highlighting, Before the codeLine.   Example below:
For Multiline code use Triple Backticks for enclosing code lines.   Example below:
```diff
- System.out.println();
+ System.out.printf();
```

Still wondering on How to enter QUOTES? 

Quotes are used to remove ambiguity for expressing the ideas clearly. 
We simply use **>** before Quoting any Statement.

Example below:

> I have idea1 to remove `System.out.println();` statement.

I agree with this.
> I have idea2 to remove `System.out.printf();` statement.

I do not agree with this.





**PRO TIP:**

*Automatically closing the ISSUE when the PULL request gets CLOSED/MERGED.*   Syntax is :  **closes #39709** 

Number represents the number of the issue/request. There MUST NOT be any SPACE between *#* and ID_Number. 
