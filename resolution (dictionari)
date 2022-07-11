#second day of LeetCode.

#after studying some python I was able to achieve a better code, with much more optimization and speed


class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        numeros = {}
        
        for index, value in enumerate(nums):
            a = target - value
            if a in numeros:
                return [numeros[a],index]
            else:
                numeros[value] = index
                
#the operation is simple, you save all the numbers in "numbers"
#then you create a variable and give it as value, the first position of the numbers and subtract the target
#if that value is in the list it shows it
