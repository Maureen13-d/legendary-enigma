from typing import List
class Solution:
    def removeElement(self, nums: List[int], val: int) -> int:
        k = 0 #initializing k to zero
        for i in range(len(nums)):# iteration
            if nums[i] != val:#if num is not equal to val
                nums[k] = nums[i]#assigns value of k to i
                k += 1
        return k  # Move the return statement outside the loop
solution = Solution()
nums = [3, 2, 2, 3]
val = 3
k = solution.removeElement(nums, val)

print(f"new array is: {nums[:k]}")
