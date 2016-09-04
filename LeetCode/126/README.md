# <a title="题目直达"  href="https://leetcode.com/problems/word-ladder-ii/" target="_blank"> 126 Word Ladder II </a>
做了很久，最后勉强过，想一起做做讨论一下。
## 题目描述
Given two words (*beginWord* and *endWord*), and a dictionary's word list, find all shortest transformation sequence(s) from *beginWord* to *endWord*, such that: <br />
<ol>
  <li> Only one letter can be changed at a time </li>
  <li> Each intermediate word must exist in the word list </li>
</ol>
<p>
example,
</p>
<p>
Given: <br>
*beginWord* = <code>"hit" </code><br>
*endWord* = <code>"cog" </code><br>
wordList = <code>["hot","dot","dog","lot","log"]</code><br>
</p>
<p>
Return<br>
</p><pre> [
    ["hit","hot","dot","dog","cog"],
    ["hit","hot","lot","log","cog"]
  ]
</pre>

<p></p>
<p>
<b>Note:</b><br>
</p>
<ul>
<li>All words have the same length.</li>
<li>All words contain only lowercase alphabetic characters.</li>
</ul>
<p></p>


