# 🟢 #15 - 1. Two Sum

## Problem Info
| Field | Value |
|-------|-------|
| **Difficulty** | Easy |
| **Topics** | Array, Hash Table |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Solved** | 10/17/2026 |

## Solution
```txt
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        for x in range(len(nums)):
            for y in range(len(nums)):
                if nums[x] + nums[y] == target and x != y:
                    return [x, y]

```



---
*Auto-synced by [LeetPush](https://github.com/yourusername/leetpush) 🚀*
