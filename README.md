Algorithm Explanation
STEP 1:
Calculate the effective number of rotations needed using d = d % n. This handles cases where the number of rotations is greater than the length of the array and ensuring that we don't perform unnecessary full cycles.
STEP 2:
Initialize a new array rotatedArray to store the rotated result. This array has the same length as the original array.
STEP 3:
Loop through each element of the original array and calculate its new position in the rotated array using the formula (i + n - d) % n. This formula ensures that elements are moved d positions to the left in a circular manner.
STEP 4:
Return the Result.
