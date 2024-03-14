quicksort › should sort numbers in ascending order

    TypeError: quickSort is not a function

      48 |
      49 |   it('should sort numbers in ascending order', function () {
    > 50 |     expect(quickSort([4, 20, 12, 10, 7, 9])).toEqual(
         |            ^
      51 |       [4, 7, 9, 10, 12, 20],
      52 |       "quickSort([4, 20, 12, 10, 7, 9]) should equal [4, 7, 8, 10, 12, 20]"
      53 |     );

      at Object.<anonymous> (quick.test.js:50:12)

Test Suites: 2 failed, 4 passed, 6 total
Tests:       6 failed, 19 passed, 25 total
Snapshots:   0 total
Time:        0.965s
Ran all test suites matching /test/i.
Marli@Marlis-MBP dsa-sorting % jest quick.test.js

 PASS  ./quick.test.js
  pivot
    ✓ should exist (1ms)
    ✓ should return the pivot index (1ms)
    ✓ should mutate the array by placing values on either side of the pivot (1ms)
  quicksort
    ✓ should exist
    ✓ should sort numbers in ascending order

Test Suites: 1 passed, 1 total
Tests:       5 passed, 5 total
Snapshots:   0 total
Time:        0.598s, estimated 1s
Ran all test suites matching /quick.test.js/i.
Marli@Marlis-MBP dsa-sorting % jest test
 PASS  ./bubble.test.js
 PASS  ./radix.test.js
 PASS  ./merge.test.js
 PASS  ./selection.test.js
 PASS  ./insertion.test.js
 PASS  ./quick.test.js

Test Suites: 6 passed, 6 total
Tests:       25 passed, 25 total
Snapshots:   0 total
Time:        0.567s, estimated 1s
Ran all test suites matching /test/i.
Marli@Marlis-MBP dsa-sorting % 