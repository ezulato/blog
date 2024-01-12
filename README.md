<header>
  
<!-------------------------------------------------------------------------------------------------------------------------------------
 
. Style	Syntax	Keyboard shortcut	Example	Output
Bold	** ** or __ __	Command+B (Mac) or Ctrl+B (Windows/Linux)	**This is bold text**	This is bold text
Italic	* * or _ _     	Command+I (Mac) or Ctrl+I (Windows/Linux)	_This text is italicized_	This text is italicized
Strikethrough	~~ ~~	None	~~This was mistaken text~~	This was mistaken text
Bold and nested italic	** ** and _ _	None	**This text is _extremely_ important**	This text is extremely important
All bold and italic	*** ***	None	***All this text is important***	All this text is important
Subscript	<sub> </sub>	None	This is a <sub>subscript</sub> text	This is a subscript text
Superscript	<sup> </sup>	None	This is a <sup>superscript</sup> text	This is a superscript text

. Quoting text
You can quote text with a >.
Text that is not a quote
> Text that is a quote

. Color	Syntax	Example	Output
HEX	`#RRGGBB`	`#0969DA`	Screenshot of rendered GitHub Markdown showing how HEX value #0969DA appears with a blue circle.
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	Screenshot of rendered GitHub Markdown showing how RGB value 9, 105, 218 appears with a blue circle.
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`	Screenshot of rendered GitHub Markdown showing how HSL value 212, 92%, 45% appears with a blue circle.

. Lists
  You can make an unordered list by preceding one or more lines of text with -, *, or +.
  
  - George Washington
  * John Adams
  + Thomas Jefferson
  Screenshot of rendered GitHub Markdown showing a bulleted list of the names of the first three American presidents.
  
  To order your list, precede each line with a number.
  
  1. James Madison
  1. James Monroe
  1. John Quincy Adams
  Screenshot of rendered GitHub Markdown showing a numbered list of the names of the fourth, fifth, and sixth American presidents.
  
  Nested Lists
  You can create a nested list by indenting one or more list items below another item.
  
  To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Visual Studio Code, you can align your list visually. Type space characters in front of your nested list item until the list marker character (- or *) lies directly below the first character of the text in the item above it.
  
  1. First list item
     - First nested list item
       - Second nested list item
  Note: In the web-based editor, you can indent or dedent one or more lines of text by first highlighting the desired lines and then using Tab or Shift+Tab respectively.
  
  Screenshot of Markdown in Visual Studio Code showing how indented bullets align vertically with the first letter of the text lines above them.
  
  Screenshot of rendered GitHub Markdown showing a numbered item followed by a bulleted item nested one level to the right, and another bulleted item nested yet further to the right.
  
  To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.
  
  In this example, you could add a nested list item under the list item 100. First list item by indenting the nested list item a minimum of five spaces, since there are five characters (100 .) before First list item.
  
  100. First list item
       - First nested list item
  Screenshot of rendered GitHub Markdown showing a list item prefaced by the number 100 followed by a bulleted item nested one level to the right.
  
  You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven characters (␣␣␣␣␣-␣) before the nested list content First nested list item, you would need to indent the second nested list item by at least two more characters (nine spaces minimum).
  
  100. First list item
         - First nested list item
           - Second nested list item
  Screenshot of rendered GitHub Markdown showing a list item prefaced by the number 100 followed by a bulleted item nested one level to the right, and another bulleted item nested yet further to the right.
  

---------------------------------------------------------------------------------------------------------------------->
  
<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Blog
<!-----------------------------------------------------------------------------------------------------------------------

_IoT_ 
What I've found useful during my work experience or around Internet in my troubleshooting path to reach the goal

The World’s Only Consensus-Based Automation and Control Systems Cybersecurity Standards
https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards

Operation Technology OT - ISA/IEC 62443 standards 
https://verveindustrial.com/resources/blog/the-ultimate-guide-to-protecting-ot-systems-with-iec-62443/
------------------------------------------------------------------------------------------------------------------------>

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

# Step 2: Configure your site



We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---



&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
