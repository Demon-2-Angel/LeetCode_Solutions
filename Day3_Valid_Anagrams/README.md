#Question
[Link to the question](https://leetcode.com/problems/valid-anagram/description/)

#Code
```
class Solution 
{
    public boolean isAnagram(String s, String t) 
    {
     char[] sChars = s.toCharArray();
     char[] tChars = t.toCharArray();

     Arrays.sort(sChars);
     Arrays.sort(tChars);

     return Arrays.equals(sChars, tChars);
     }
}
```
