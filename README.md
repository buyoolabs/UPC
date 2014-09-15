UPC
===

Check Digit
-----------

Suppose that you want to find the check digit of UPC-A number 72641217542.

* From the right to the left, start with odd position, assign the odd/even position to each digit.
* Sum all digits in odd position and multiply the result by 3: (7+6+1+1+5+2)*3=66
* Sum all digits in even position: (2+4+2+7+4)=19
* um the results of step three and four: 66+19=85
* Divide the result of step four by 10. The check digit is the number which adds the remainder to 10. In our case, divide 85 by 10 we get the remainder 5. The check digit then is the result of 10-5=5. If there is no remainder then the check digit equals zero.

##### Resources

* [gtin]
* [ehow]

APIs
----

* [ean-search-database]
* [ean-search]
* [product-open-data]
* [searchupc]
* [outpan]




[gtin]:http://www.gtin.info/upc/
[ehow]:http://www.ehow.com/how_7506505_identify-manufacturer-bar-code.html

[ean-search-database]:http://www.ean-search.org/ean-database-api.html
[ean-search]:http://www.ean-search.org/perl/ean-search.pl?q=662774013688
[product-open-data]:http://product-open-data.com/download/
[searchupc]:http://searchupc.com/default.aspx
[outpan]:http://www.outpan.com/index.php

