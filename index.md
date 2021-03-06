<img src="mugshot.jpeg"
     alt="Macy Beach mugshot"
     style="float: left; margin-right: 20px; width:200px;" />

### Macy Beach

**University of Delaware Computer Science B.S. '23**

Email: <maybe@udel.edu>

[Github repository](https://github.com/maybeep/maybeep.github.io.git) 

<br>

## Technologies &amp; Concepts Mastered

- **React** 
    - Made a [mineral quiz app](https://maybeep.github.io/mineral-quiz/) with the help of several different websites but the general design is fully original (albeit not that creative).
        - Got comfortable with states; using them for the score, changing images, and questions.
        - More familiar with components. Definitely think my code could be a lot cleaner (via more components).
        - Got practice with *Hooks* using `useState`.
    - Followed React [tutorial](https://reactjs.org/tutorial/tutorial.html) to make a [tic-tac-toe game](https://maybeep.github.io/tic-tac-toe/).
    - Learned how to deploy a React app.
    - Added some features:
        - Functionality to display the location for each move in the format (col, row) in the move history list.
        - Made currently selected item in the move list bold.
        - When no one wins, my program displays draw.
    - Key takeaways from React [tutorial](https://reactjs.org/tutorial/tutorial.html):
        - React is a JavaScript library for building user interfaces.
        - Components tell React what to display on the screen. They take in parameters called **props** and return a hierarchy of views to display via **render**.
        - Each React element is a JavaScript object that you can store in a variable or pass around.
        - Information flows from parents to children.
        - Components use state to remember things

- **TypeScript** 
    - Wrote [mineral quiz app](https://maybeep.github.io/mineral-quiz/) in TypeScript rather than JavaScript.
        - [Link to GitHub repository](https://github.com/maybeep/mineral-quiz).
    - Key takeaways from TS [tutorial](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html):
        - Thought it was interesting that Visual Studio Code uses TypeScript under the hood to make writing JavaScript easier.
        - TypeScript is a superset of JavaScript meaning I can take working JS code and put it in a TS file. Then just follow the TS rules regarding types.
        - TypseScript never changes the runtime behavior of JavaScript code which also allows for easy transition between the two.
        - *"TypeScript is JavaScript's runtime with a compile-time type checker."* 
        - Use `interface` declaration for objects and classes to set types as well as for annotating parameters and returning values to functions.
        - TypeScript extends JavaScript's primitive types with `any`(bad!), `unknown`, `never`, and `undefined`.
        - Unions declare that a type could be one of many. e.g. `type door_states = "open" &#124; "closed";`
        - `typeof` returns the type of a variable; useful in functions that return different values depending on what is passed into it.
        - Generics provide variables to types. For example, an array with generics explains what values it contains.

- **JavaScript** 
    - Followed a tutorial to make a basic whack-a-mole [game](https://maybeep.github.io/whack-a-mole/index.html).
    - Followed this [tutorial](https://www.youtube.com/watch?v=3PHXvlpOkf4&t=28874s) to make an image slider on my [site](https://maybeep.github.io/brian-site/brian_css.html) about Brian. Learned how to link a separate JavaScript file to my site. Combined CSS and JavaScript to make it look nice.

- **HTML** 
    - I made an [HTML Reference Guide](html_site.html) in HTML. 
    - I used tables to organize HTML tags with their explanations. 
    - I learned about HTML escape characters so I could print tags such as &lt;strong&gt;. 
    - I became comfortable with both block and inline nesting by emphasizing certain words, using tables, structuring my site using the &lt;head&gt; and &lt;body&gt; tags, etc.
    - Learned about inline styles by making the tables have different background colors.

- **CSS** 
    - I made a pretty [website](https://maybeep.github.io/brian-site/brian_css.html) bragging about my dog Brian.
    - I used &lt;style&gt; tags to add background color to the header and different sections of the body. Changed font and font size of the body text.
    - Spent way too long figuring out how to horizontally align three images in the center of the page.
    - Eventually learned the difference between padding and margins.
    - Used percentages for image dimensions to make my site more responsive.
    - Practiced responsive web design by making the images adjust with the size of the window.
    - Added a menu that links to the different sections of the site.
    - Made Brian's seal of approval spin in the [contact](https://maybeep.github.io/brian-site/brian_css.html#contact) section using CSS.

- **Git**
    - Learned in class on 9/9 that there is a local way of viewing my site. Before, I kept making extremely small edits, submitting to Git, waiting for my site to refresh, then finally reloading my site to see my change. This is obviously extremely inefficient compared to opening html_site.html locally and seeing my changes immediately. Now I can make Git commits often rather than *constantly*.

- **Etc.**
    - Used Bootstrap in [mineral quiz app](https://maybeep.github.io/mineral-quiz/).
        - Learned how to format page using containers, rows, and columns.
        - Used buttons.

<details>
    <summary>TODO</summary>
<html>
<table>
    <tr>
        <td> By 9/16 </td>
        <td>
            <ul>
                <li> Add interactive "fan mail" section to brian_css.html site. </li>
                <li> JavaScript: Read HTML Dog tutorial </li>
                <ul>
                    <li> Project: Add image slider to Brian site </li>
                </ul>
                <li> Typescript: start <a href="https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html">tutorial</a></li>
                <ul>
                    <li> Project: Whack-a-mole? </li>
                </ul>
                <li> React: Make tabs for portfolio (<a href="https://www.freecodecamp.org/news/javascript-projects-for-beginners/#how-to-create-tabs-for-a-portfolio-page">link</a>)</li>
            </ul>
        </td>
    </tr> 
    <tr>
        <td> By 9/23 </td>
        <td>
            <ul>
                <li> Updates to whack-a-mole project </li>
                <ul>
                    <li> Start game button, pause button </li>
                    <li> Add CSS to make it look a little better; different font, header </li>
                    <li> Add buttons for different difficulties? </li>
                </ul>
                <li> Finish TypeScript <a href="https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html">tutorial</a></li>
                <li> Complete React <a href="https://reactjs.org/tutorial/tutorial.html">tutorial</a> building tic-tac-toe</li>
                <li> Go through Hooks <a href="https://reactjs.org/docs/hooks-intro.html">tutorial</a></li>
                <li> Start a React project; to-do list <a href="https://youtu.be/nUl5QLkVdvU">(tutorial)</a>, quiz app <a href="https://youtu.be/aq-fCtg_gG4">(tutorial)</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td> By 9/30 (FINAL) </td>
        <td>
            <ul>
                <li> New React project from scratch: mineral quiz app </li>
                <li> Add bootstrap to React project </li>
                <li> Add tests to tic-tac-toe project </li>
                <li> (opt.) Add more features to tic-tac-toe project </li>
                <li> Read about <a href="https://sun.iwu.edu/~mliffito/cs_codex/posts/requirements-gathering/">(requirements gathering)</a></li>
            </ul>
        </td>
    </tr>
</table>
</html>
</details>
<br>
<details>
    <summary>Change Log</summary>
<html>
<table>
    <tr>
        <td> 9/2/21 - 9/9/21 </td>
        <td> 
            <ul>
                <li> Added headshot to portfolio using html; played around with floating the image to the left of my introduction text with a margin to make it look nice. </li>
                <li> Began laying out portfolio; bulleted list for tech & concepts mastered. </li>
                <li> Created <a href="https://maybeep.github.io/brian-site/brian_css.html">HTML Reference Guide</a> in HTML. </li>
                <li> Created site about my dog to practice CSS. The biggest challenge was centering the three images in a line. Couldn't figure out how to make the yellow header section reach all the way to the edge of the page. </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td> 9/10/21 - 9/16/21 </td>
        <td>
            <ul>
                <li> Started by looking at a <a href="https://www.w3schools.com/html/html_responsive.asp">tutorial</a> on content folding and responsive web design. Updated my <a href="https://maybeep.github.io/brian-site/brian_css.html">Brian site</a> to have images and text that move with the size of the window. </li>
                <li> Added menu to my <a href="https://maybeep.github.io/brian-site/brian_css.html">Brian site</a> and used CSS for styling. </li>
                <li> Added a 'fan mail' section to my <a href="https://maybeep.github.io/brian-site/brian_css.html">Brian site</a> using inputs and CSS styling </li>
                <li> Put an image slider in my <a href="https://maybeep.github.io/brian-site/brian_css.html">Brian site</a> using Javascript. </li>
                <li> Followed this (<a href="https://www.youtube.com/watch?v=lhNdUVh3qCc&t=699s">tutorial</a>) and built a whack-a-mole game in JavaScript. </li>
                <li> Separated my style tags into a separate style.css file. Made Brian's seal of approval spin in the <a href="https://maybeep.github.io/brian-site/brian_css.html#contact">contact</a> section of my Brian site using CSS. </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td> 9/17/21 - 9/23/21 </td>
        <td>
            <ul>
                <li> Finished building tic-tac-toe following the <a href="https://reactjs.org/tutorial/tutorial.html">tutorial</a>. </li>
                <li> Added some suggested features to tic-tac-toe such as showing locations of moves, bolding the current move, declaring a draw, etc. </li>
                <li> Miscellaneous updates & changes to tic-tac-toe </li>
                <li> Learned how to deploy a React app </li>
                <li> Added tests to ta-trainer (<a href="https://github.com/maybeep/ta-trainer-main">repository</a>) </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td> 9/24/21 - 9/30/21 </td>
        <td>
            <ul>
                <a href="https://maybeep.github.io/react-quiz.jpg">
                <img src="react-quiz.jpg" 
                style="float: right; width:275px;"/>
                </a>
                <li> Made <a href="https://maybeep.github.io/mineral-quiz/">mineral quiz app</a> basically from scratch with the help of this <a href= "https://www.freecodecamp.org/news/how-to-build-a-quiz-app-using-react/">tutorial</a>. </li>
                <li> Learned how to use hooks, functions, TypeScript, Bootstrap. </li>
                <li> Played around with user interface design by mapping out my design for the quiz app on my iPad (click image to the right to expand). </li>
                <li> Miscellaneous CSS updates to tic-tac-toe <a href="https://maybeep.github.io/tic-tac-toe/">game</a> and whack-a-mole <a href="https://maybeep.github.io/whack-a-mole/index.html">game</a>. </li>
            </ul>
        </td>
    </tr>
</table>
</html>
