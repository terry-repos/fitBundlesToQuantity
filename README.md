# fitBundlesToQuantity

## Task:
Given a customer order you are required to determine the cost and bundle breakdown for
each product. To save on shipping space each order should contain the minimal number
of bundles.
## Input:
Each order has a series of lines with each line containing the number of items followed by
the product code
## An example input:
10 R12
15 L09
13 T58
## Output:
A successfully passing test(s) that demonstrates the following output: (The format of the
output is not important)
10 R12 $12.99
1 x 10 $12.99
15 L09 $41.90
1 x 9 $24.95
1 x 6 $16.95
13 T58 $25.85
2 x 5 $9.95
1 x 3 $5.95

## To run
#. Git Clone
#. npm install
#. sudo tsc --outDir ./build ./src/index.ts; node ./build/index.js;   
#. Enjoy
