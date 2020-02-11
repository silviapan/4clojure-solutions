# 4clojure-solutions
Solutions for problems on 4clojure (http://www.4clojure.com/)

[1. Nothing but the Truth](http://www.4clojure.com/problem/1)
```clojure
true
``` 
<br/>

[2. Simple Math](http://www.4clojure.com/problem/2)
```clojure
4
```
<br />

[3. Intro to Strings](http://www.4clojure.com/problem/3)
```clojure
"HELLO WORLD"
```
<br />

[4. Intro to Lists](http://www.4clojure.com/problem/4)
```clojure
:a :b :c
```
<br />

[5. Lists: conj](http://www.4clojure.com/problem/5)
```clojure
'(1 2 3 4)
```  
<br/>

[6. Intro to Vectors](http://www.4clojure.com/problem/6)
```clojure
:a :b :c
```
<br/>

[7. Vectors: conj](http://www.4clojure.com/problem/7)
```clojure
[1 2 3 4]
```
<br />

[8. Intro to Sets](http://www.4clojure.com/problem/8)
```clojure
#{:a :b :c :d}
```
<br />

[9. Sets: conj](http://www.4clojure.com/problem/9)
```clojure
2
```
<br />

[10. Intro to Maps](http://www.4clojure.com/problem/10)
```clojure
20
```
<br />

[11. Maps: conj](http://www.4clojure.com/problem/11)
```clojure
{:b 2}
```
<br />

[12. Intro to Sequences](http://www.4clojure.com/problem/12)
```clojure
3
```
<br />

[13. Sequences: rest](http://www.4clojure.com/problem/13)
```clojure
[20 30 40]
```
<br />

[14. Intro to Functions](http://www.4clojure.com/problem/14)
```clojure
8
```
<br />

[15. Double Down](http://www.4clojure.com/problem/15)
```clojure
* 2
```
<br />

[16. Hello World](http://www.4clojure.com/problem/16)
```clojure
(fn [name]  
  (str "Hello, " name "!"))
```
<br />

[17. Sequences: map](http://www.4clojure.com/problem/17)
```clojure
'(6 7 8)
```
<br />

[18. Sequences: filter](http://www.4clojure.com/problem/18)
```clojure
'(6 7)
```
<br />

[19. Last Element](http://www.4clojure.com/problem/19)
```clojure
#(nth % (dec (count %)))
```
<br />

[20. Penultimate Element](http://www.4clojure.com/problem/20)
```clojure
#(nth % (- (count %) 2))
```
<br />

[21. Nth Element](http://www.4clojure.com/problem/21)
```clojure
#(get (into [] %1) %2)
```
<br />

[22. Count a Sequence](http://www.4clojure.com/problem/22)
```clojure
#(reduce + (vals (frequencies %)))
```
<br />

[24. Sum It All Up](http://www.4clojure.com/problem/24)
```clojure
reduce +
```
<br />

[25. Find the odd numbers](http://www.4clojure.com/problem/25)
```clojure
filter odd?
```
<br />

[29. Get the Caps](http://www.4clojure.com/problem/29)
```clojure
#(apply str (re-seq #"[A-Z]" %))
```
<br />

[35. Local Bindings](http://www.4clojure.com/problem/35)
```clojure
7
```
<br />

[36. Let it Be](http://www.4clojure.com/problem/36)
```clojure
[x 7 y 3 z 1]
```
<br />

[37. Regular Expressions](http://www.4clojure.com/problem/37)
```clojure
"ABC"
```
<br />

[38. Maximum value](http://www.4clojure.com/problem/38)
```clojure
#(last (sort %&))
```
<br />

[42. Factorial Fun](http://www.4clojure.com/problem/42)
```clojure
#(reduce * (range 1 (inc %)))
```
<br />


[48. Intro to some](http://www.4clojure.com/problem/48)
```clojure
6
```
<br />

[52. Intro to Destructuring](http://www.4clojure.com/problem/52)
```clojure
[c e]
```
<br />

[57. Simple Recursion](http://www.4clojure.com/problem/57)
```clojure
'(5 4 3 2 1)
```
<br />

[64. Intro to Reduce](http://www.4clojure.com/problem/64)
```clojure
+
```
<br />

[68. Recurring Theme](http://www.4clojure.com/problem/68)
```clojure
[7 6 5 4 3]
```
<br />

[134. A nil key](http://www.4clojure.com/problem/134)
```clojure
(fn [k m]
  (if (contains? m k)
    (= (m k) nil)
    false))
```
<br />

[145. For the win](http://www.4clojure.com/problem/145)
```clojure
'(1 5 9 13 17 21 25 29 33 37)
```
<br />

[161. Subset and Superset](http://www.4clojure.com/problem/161)
```clojure
#{1 2}
```
<br />

[162. Logical falsity and truth](http://www.4clojure.com/problem/162)
```clojure
1
```
<br />


















