This is a simple script to test the efficiency of multiple Java threads versus one. From the information gathered here, it seems multiple threads have a faster execution time with diminishing returns. Another thing to note is how inefficient for loops can become. I have also exceeded my CPU capacity at 4(+1) threads and therefore did not test any further.

The test is generating 200 million random integers and adding their sum as the base method.
