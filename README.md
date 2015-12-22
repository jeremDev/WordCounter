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

The Merry Adventures of Robin Hood
6515 total words
Calculation time: 90 ms
6093 : 100% : the
4190 : 68.76743804365665% : and
2780 : 45.626128344001316% : of
2540 : 41.68718201214509% : a
2339 : 38.38831445921549% : to
1977 : 32.44707040866569% : he
1805 : 29.624158870835387% : i
1754 : 28.78713277531594% : his
1566 : 25.70162481536189% : in
1561 : 25.619563433448217% : that
1334 : 21.893976694567534% : for
1145 : 18.792056458230757% : thou
1043 : 17.11800426719186% : robin
996 : 16.34662727720335% : with
991 : 16.264565895289675% : as
946 : 15.526013458066634% : so
883 : 14.492040045954374% : but
841 : 13.802724437879535% : all
835 : 13.704250779583127% : it
753 : 12.358444116198916% : was
