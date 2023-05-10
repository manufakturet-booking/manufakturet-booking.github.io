---
category:   {{ test.Category[0] }}
tags: testtag1 testtag2 # add tags here, space delimited, as many as you want
quantity: 0 # How many are in circulation? (in the booking office + known to be lent out)
maxLoan: 7 days #
aaunumbers: AAU-CPH0640 AAU-CPH0642 AAU-CPH0641 AAU-CPH0639 AAU-CPH0638 AAU-CPH0643
---
<ul>
{% for test in site.data.tests %}
  <li>

      {{ test.Title[0] }}
    </a>
  </li>
{% endfor %}
</ul>
