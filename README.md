# WordCounter
This is a .htm file that runs in a web browser. The project uses JavaScript to count the number of each character found in a given text. It requires jQuery, but embeds a reference to Google's hosted jQuery file.

I was interested in the Zipf claim about the number of times that words generally appear in texts, so I wrote this to test it.

Sor far, I tested it with the main text on the Wikipedia article for "Philosopy" and did not find the relationship predicted by Zipf. The first 10 most common words and their counts were:
628 : of
443 : and
239 : in
216 : philosophy
183 : to
180 : a
154 : is
151 : as
129 : that

TO DO:
* Improve word matching, perhaps to consider "self-contained" as one word; as well as "contain" and "contained" as the same word.
* Add option to display comparisons in a chart
