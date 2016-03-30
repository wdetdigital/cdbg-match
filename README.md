# cdbg-match
A multiple choice quiz for readers to test their knowledge of local Community Development Block Grant projects.

We store each question and its respective answer choices within an HTML5 `<section>` element using an `<h3>` and `<p>` tags respectively. The right answer choice is assigned `class=correct`. 

Using CSS3's `~` combinator magic, readers click and hold the question to reveal the right answer. Since a question and its answer choices are siblings within a given section, we use the general sibling selector to apply special styles to the correct answer choice when the question is `:active`.

This quiz is built using HTML5/CSS3 only, so it's easy to paste directly into the Source of your text editor.

## In the wild
This quiz lives on wdet.org in the post <a href="http://wdet.org/posts/2016/03/04/82640-federal-money-local-communities-quiz/">Federal Money, Local Communities [QUIZ]</a> and is part of the 2016 Elections: Issues & Candidates series.

## Make your own
This repo contains two files: the code for the CDBG quiz made for WDET and a generalized template for coding your own called `mult-choice-template.html`.

Start by replacing the sample text with your own. If you're using a text editor like we do at WDET, switch to Source, copy and paste everything between the `<style>...</style>` and '<section>...<section>' tags. You'll inherit font and other styles from your page, to so plan to make small adjustments as needed.

If you also want to wrap your questions in the expandable accordion layout used in the CDBG quiz, find that template in our sister repo <a href="https://github.com/wdetdigital/primaries-quiz">wdetdigital/primaries-quiz</a>.
