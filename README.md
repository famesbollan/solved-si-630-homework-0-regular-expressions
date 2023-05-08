Download Link: https://assignmentchef.com/product/solved-si-630-homework-0-regular-expressions
<br>
You’ve been asked to perform a security audit for a large university. They want to know what kinds of email addresses might be recoverable from each web page. Conveniently, they’ve already put together all of the web pages for you into a single file, where the HTML page for each page is on one line. Further, every page is guaranteed to have one email on it at most, since no one lists two email addresses for themselves on a page. However, not everyone lists their email on a page, so some pages have no email addresses! The big challenge is that there is no consistency in how the addresses are formatted!

<strong>Problem 1. </strong>Write a program that uses regular expressions to extract and canonicalize email addresses from web pages. Hint: regex groups may come in handy here. You will be provided with a large file of web pages on Canvas where each page is on a separate line. Your program will produce a new file the canonicalized email address found on each page or the word None if no email address was found. By canonicalized, we mean that if the author wrote myname at domain dot edu, you would output <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f39e8a9d929e96b3979c9e929a9ddd969786">[email protected]</a> in your file. Your output should have the same number of output lines as the input file.