[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/FgMJElkj)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.


The three reasons why asymptotic analysis may be misleading is:
1: The amount of constants, these are disregarded factors. With a high asymptotic complexity an algorithm might have a lot of constant factors so they're not ideal for small input sizes becasue they're just approximations.
2: Physical resstraints like hardware aren't taken into account becasue the analysis is abstract and may preform better or worse on different machines.
3: Becasue they're abstract they might not repersent real world data very well.
Using big 'O', $n$ equals the number of elements you get $5 * log(10,000)=20$ so we can assume checking 10,000 elements would take 20 seconds.

1: The elements are not evenly distributed so you have to search more levels of the tree
2: There might be hardware issues causing the slowdown.
3: Having the data be unbalanced causes the worst case "Linear Time" for $O(n)$
