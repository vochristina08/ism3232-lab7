# debug_log.md
# Author: Christina Vo

## Bug 1
Error type: KeyError: 'amount'
File + line: week8_buggy.py, line 12
What the error means: Python could not find the amount key in one of the records.
What I told the duck:I explained that the function starts at zero and adds each record's amount to the total. I noticed that the function needs an 'amount' key in every record to work.
What I tried:I added a DEBUG print statement inside get_total() to see each record before the error. When I ran the program again, I noticed the first record had 'amout' instead of 'amount'.
How I fixed it:I corrected the misspelled key from 'amout' to 'amount' in the first record and removed the DEBUG print statement.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 17
What the error means: Python cannot compare an integer with a string using >.
How I fixed it:I removed the quotation marks around 1000 so Python would compare two integers instead of an integer and a string.

## After Fixing Both Bugs
Final output:
Total: $5150.00 across 3 records
True

Did pytest pass? Yes, all 13 tests passed.

## AI Literacy Reflection
Did I use AI? Yes

If yes -- exact prompt I used:
"how do i add this file to my ISM3232 folder"

What AI explained:
AI helped me understand the KeyError, TypeError, and how to read the error messages.

What I changed myself:
I corrected the misspelled 'amout' key to 'amount', removed the quotation marks around 1000, and added the five required tests.

Can I explain every fixed line? Yes

## What I learned
I learned how to read Python error messages and use print statements to find bugs in my code. I also learned how important data types are when comparing values and how pytest can verify that my functions work correctly.