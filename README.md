# List of practiced topics
|[Header](#header)|[Emphasis](#emphasis)|[Image](#image)|[Button](#button)|[Dropdown](#dropdown)|[Blockquote](#blockquote)|[List & Task](#list)|[Reference link](#reference-link)|[Hightlight](#hightlight)|[Color](#color)|
|---|---|---|---|---|---|---|---|---|---|

## Basic
- **Emojis:** [Cheat sheet](https://www.emojicopy.com)
- **Mention:** @97noob @cpulover-projects
- **Issue mention:** ```[Issue 1](#1)``` &#x27A1; [Issue 1](#1)
- **Horizontal line:** ```---``` or ```***``` or ```___```
- **Line break:** ```<br>``` or `2 whitespace` or `\`
- **Blackslash escape:** ```*Italic*``` => *Italic* vs. ```\*Not italic\*``` => \*Not italic\*
- **Header anchor link:** ```[Go to bottom](#bottom)``` &#x27A1; [Go to bottom](#bottom)
- **Manual anchor link:** ```[Manual anchor](#just-a-random-anchor)``` &#x27A1; [Manual anchor](#just-a-random-anchor)
- **Link:** ```[My GitHub profile](https://github.com/cpulover)``` &#x27A1; [My GitHub profile](https://github.com/cpulover)
- **Code block:** \`\`\`System.out.println("Hello!");\`\`\` &#x27A1; ```System.out.println("Hello!");```
- **Hidden comment:** ```[//]: # (You can not see this on a seperate line)```

[//]: # (You can not see this on a seperate line)

## Header 
```
# <h1> heading
## <h2> heading
### You get it!
```

## Emphasis
 Syntax | Output |
---|---|
 ```*This text will be italic*```|*This text will be italic* 
```_This will also be italic_ ```|_This will also be italic_
```**This text will be bold** ```|**This text will be bold**
```__This will also be bold__```|__This will also be bold__
```Text with `backticks` inside```|Text with `backticks` inside
```~~This text will be deleted~~```|~~This text will be deleted~~
```*You **can** `combine` ~~them~~*```|*You **can** `combine` ~~them~~*

## Image

<details>
 <summary><b>Left align</b></summary>
 <pre>&lt;img align="left" width="150" src="https://github.com/cpulover-practice/markdown/blob/master/images/avt2.jpg"&gt;</pre>
 </details>
 <details>
 <summary><b>Right align</b></summary>
 <pre>&lt;img align="right" width="150" src="./images/avt2.jpg"&gt;</pre>
 </details>
 <details>
 <summary><b>Center align</b></summary>
 <pre>&lt;p align="center"&gt;&lt;img width="150" src="./images/avt2.jpg"&gt;&lt;/p&gt;</pre>
 </details>

<img align="left" width="150" src="https://github.com/cpulover-practice/markdown/blob/master/images/avt2.jpg"> 
<img align="right" width="150" src="./images/avt2.jpg"> 
<p align="center"><img width="150" src="./images/avt2.jpg"></p>

## Button

<details> 
<summary><b>A single button</b></summary>
<pre>[GitHub](https://github.com/)
|---|</pre>
</details>

[GitHub](https://github.com/)
|---|

<details>
 <summary><b>A row of buttons</b></summary>
 <pre>|[Google](https://www.google.com/)|[Facebook](http://facebook.com/)|[Youtube](https://www.youtube.com/)|
|---|---|---|</pre>
 </details>

|[Google](https://www.google.com/)|[Facebook](http://facebook.com/)|[Youtube](https://www.youtube.com/)|
|---|---|---|

<a name="just-a-random-anchor">
   
 ⚓  
\<a name="just-a-random-anchor"\>

## Dropdown

<details>
<summary>Dropdown contains a list</summary>
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  </ul>
</details>

<details> 
<summary>Dropdown contains a code block</summary>
<pre>$ This dropdown contains<br>a code block!</pre>
</details>

<details open>
<summary>Opening dropdown</summary>
<pre>
&lt;details open&gt;
&lt;summary&gt;Want to ruin the surprise?&lt;&#47;summary&gt;
&lt;br&gt;
Well, you asked for it!
&lt;&#47;details&gt;
</pre>
</details>
  
## Blockquote

<details>
 <summary><b>Code</b></summary>
 <pre>
 As Kanye West said:
> We're living the future    
> so the present is our past.
</pre>
 </details>

As Kanye West said:
> We're living the future    
> so the present is our past.

## List

<details>
 <summary><b>Unordered list</b></summary>
 <pre>
- Item 1
- Item 2
  - Item 2a
  - Item 2b</pre>
</details>
  
- Item 1
- Item 2
  - Item 2a
  - Item 2b

<details>
 <summary><b>Ordered list</b></summary>
 <pre>
1. Item 1
2. Item 2
   * Item 2a
   * Item 2b
</pre>
</details>

1. Item 1
2. Item 2
   * Item 2a
   * Item 2b

<details>
 <summary><b>Task list</b></summary>
 <pre>
- [x] This is a complete item
- [ ] This is an incomplete item
</pre>
 </details>
 
- [x] This is a complete item
- [ ] This is an incomplete item

## Reference link

<details>
 <summary><b>Declare links</b></summary>
 <pre>
[//]: # (Declared links are invisible, can be put anywhere)
[cat]: https://en.wikipedia.org/wiki/Cat
[github-profile]: https://github.com/cpulover
</pre>
 </details>

[//]: # (Declare reference links, they are invisible, can be put anywhere)
[cat]: https://en.wikipedia.org/wiki/Cat
[github-profile]: https://github.com/cpulover

<details>
 <summary><b>Use links</b></summary>
 <pre>
I like [cat][]. So check out my [profile][github-profile]!
</pre>
 </details>
 
I like [cat][]. So check out my [profile][github-profile]!

## Hightlight

<details>
 <summary><b>Code</b></summary>
 <pre>
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
</pre>
</details>

```diff
- Text in red.
+ Text in green.
! Text in orange.
# Text in gray.
@@ Text in purple (and bold).@@
```

## Color

<details>
 <summary><b>Inline style</b></summary>
 <pre>
![#ff0000](https://placehold.it/12/ff0000?text=+) Small red 
![#9900c5](https://placehold.it/15/9900c5?text=+) Medium purple 
![#157500](https://placehold.it/20/157500?text=+) Large green
</pre>
 </details>
 
![#ff0000](https://placehold.it/12/ff0000?text=+) Small red 
![#9900c5](https://placehold.it/15/9900c5?text=+) Medium purple 
![#157500](https://placehold.it/20/157500?text=+) Large green

<details>
 <summary><b>Block style</b></summary>
 <pre>
![](https://placehold.it/300x90/ff0000/000000?text=IMPORTANT!)
![](https://placehold.it/250x90/ff6600/000?text=WARNING!)
![](https://placehold.it/200x90/009955/fff?text=SUCCESS!)
</pre>
 </details>
 
![](https://placehold.it/300x90/ff0000/000000?text=IMPORTANT!)
![](https://placehold.it/250x90/ff6600/000?text=WARNING!)
![](https://placehold.it/200x90/009955/fff?text=SUCCESS!)

---

#### Bottom
[**Go to top**](#list-of-practiced-topics)
