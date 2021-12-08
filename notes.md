# COSC 6510 Business Intelligence Final Project Planning

Things to remember:
- looking into how to separate comment tree into subtrees (R data.tree package?)
- how to strip out formatting from comment text field
- `parent_id` field is prefixed with `t3_` for top-level comments
  + try breaking the tree based on top level comments?
  
  
  
Pruning idea:
- unique trees
- find replies to top level comment
- which have more than one reply
- if multiple subtrees, pick one with most comments
- if multiple subtrees with equal comments, pick one with most text?



questions:
- compare sentiment of top-level response to their immediate children
  + follow up with adding the grandchildren, great-grandchilden etc. as able
- consider different ways of summarizing the word-level sentiment scores
  + variance
  + mean