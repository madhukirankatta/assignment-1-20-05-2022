# assignment-1-20-05-2022
class Solution: 
     def singleNumber(self,nums): 
        sum=0 
        for i in nums: 
            sum=i^sum 
         return sum
