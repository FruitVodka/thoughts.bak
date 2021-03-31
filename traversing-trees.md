# Traversing Trees

`dabbling`:
  consuming knowledge breadth-first aka me in college
  
## What is a tree?
A tree is a hierarchical way of representing data. The most intuitive way to understand a tree would probably be: a categorisation of elements into groups whose definitions get consecutively narrower.
We've been building trees our whole lives to store away some kinds of information. For example, we have one big bucket called 'animals'. Now under this, we have categories, say, 'micro-organisms', 'reptiles', 'birds', 'mammals' and so on. We keep dividing animals into smaller groups in this manner, until we reach the tree's leaves - individual animals that we can't (or don't want to) further divide into groups.

## How do you traverse - travel through - a tree?
If you saw a diagram of a tree, your eyes would scan the elements in the tree and make sense of it.
You would find the 'root' element, or the widest category (in the above example, 'animals'). After this, you could scan the next element in one of two ways
1. Depth-first: You see the first subcategory 'micro-organisms' and think "Ah, that's interesting! I like micro-organisms. They're so tiny and yet clearly, they can make the entire world grind to a halt for over a year." So now you're invested in micro-organisms and proceed to the subcategories under it. At each step, without looking at the neighbouring subcategories, you go one level deeper into the one you are already seeing.
2. Breadth-first: You look at 'micro-organisms' and like any normal people, you say "Eh. Moving on already." You look at all the sub-categories under 'animals'. (Maybe your attention span is dangerously low, maybe you want to acclimate yourself with what is to come before diving in too deep.) You scan the tree level-by-level, looking at all the subcategories in one level before moving on to the next.

## Extended Sidenote

