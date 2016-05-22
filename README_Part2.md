<blockquote>April 20th, 2016</blockquote>
# Collections

### Lists
```
val fruits = List("apples","oranges")
val nums: List[Int] = List(1,2,3)
val listList: List[List[Int]] = List(List(1,3,4),List(2,3,4))
val empty: List[Nothing] = List()

```
List has mainly three operations, 
- head : first element of list
- tail : list of elements except the first
- isEmpty : if list is empty or not

lists are immutable in Scala

#### Cons
construction operation `::`
```
fruits = "apples" :: ("oranges" :: Nil)
```
operators ending in ":" reverse are considered right hand operand in infix rotation<br/>
Here **::** is considered as a function of it's right hand side. either the list, or Nil in the above example

#### List patterns
```
1 :: 2 :: xs \\lists that start with 1 and then 2
x :: Nil \\list of length 1 (x means it can be anything, but only 1 item present)
List() \\empty list

```