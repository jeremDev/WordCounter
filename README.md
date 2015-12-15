# WordCounter
This is a .htm file that runs in a web browser. The project uses JavaScript to count the number of each character found in a given text. It requires jQuery, but embeds a reference to Google's hosted jQuery file.

I was interested in the Zipf claim about the number of times that words generally appear in texts, so I wrote this to test it.

Sor far, I tested it with a couple text sources and did not find the relationship predicted by Zipf.

TO DO:
* Improve word matching, perhaps to consider "self-contained" as one word; as well as "contain" and "contained" as the same word.
* Add option to display comparisons in a chart

Here are some results so far:

From the Philosophy Wikipedia entry:
628 : of
443 : and
239 : in
216 : philosophy
183 : to
180 : a
154 : is
151 : as
129 : that

From Huckleberry Finn:
Calculation time: 111 ms
6353 : 100% : and
4785 : 75.31874704863843% : the
3665 : 57.68928065480875% : i
3151 : 49.59861482764049% : a
2934 : 46.18290571383598% : to
2541 : 39.9968518810011% : it
2123 : 33.41728317330395% : t
2069 : 32.56729104360145% : was
1860 : 29.277506689752876% : he
1635 : 25.735872815992444% : of
1524 : 23.988666771603967% : you
1434 : 22.572013222099795% : in
1232 : 19.392413033212655% : that
1116 : 17.566504013851723% : s
1035 : 16.29151581929797% : but
964 : 15.173933574689125% : so
961 : 15.126711789705652% : we
887 : 13.961907760113332% : on
862 : 13.568392885251063% : up
853 : 13.426727530300644% : all
846 : 13.316543365339209% : for
