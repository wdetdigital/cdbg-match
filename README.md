# cdbg-match
A multiple choice quiz for readers to test their knowledge of local Community Development Block Grant projects.

Built using only HTML5/CSS3 so it's easy to paste directly into the Source of your text editor.

We store each question and its respective answer choices as siblings within an HTML5 `<section>` element using one `<h3>` and four `<p>` tags respectively. The right answer choice is assigned `class=correct`.

Using CSS3's `~` combinator magic, readers click and hold a question to reveal the right answer. We use this general sibling selector to style the correct answer whenever the question is `:active`.

## In the wild
This quiz lives in the post <a href="http://wdet.org/posts/2016/03/04/82640-federal-money-local-communities-quiz/">Federal Money, Local Communities</a> and is part of the 2016 Elections: Issues & Candidates series.

## Make your own
This repo contains two files: the code for the CDBG quiz made for WDET and a generalized template for coding your own called `mult-choice-template.html`.

Start by replacing the sample questions and answers with your own, adding more sections as needed.

If you're using a text editor like we do at WDET, switch to Source, then copy and paste everything between the `<style>...</style>` and `<section>...<section>` tags. You'll inherit font and additional styles from your page, so plan to make small adjustments as needed.

If you also want to wrap your questions in the expandable accordion layout used in the CDBG quiz, find that template in our sister repo <a href="https://github.com/wdetdigital/primaries-quiz">wdetdigital/primaries-quiz</a>.
