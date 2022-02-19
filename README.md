Unrefined questions (& their potential categories) that may be worthy in a Rust Jeopardy competition. Not in any particular order, needs refinement (categorization, sequencing, and "hints")

Category Name: "Memory Constrained Systems" / "Type Layout" / "In Memory Representation"

Lots of good concepts & examples can be pulled from: https://www.youtube.com/watch?v=rDoqT-a6UFg&t=915s

Q1
- String is to Box\<str\>, as Vec\<T\> is to ___.
- The difference between String and Box<str> is that Box<str> does not store _____ on the _____, and therefore is not _____.

Q2
- Difference between \<show example enum with large field\> and <example enum with Box<of that field> is a saving of _____ bytes.

Q3
- ______ enables types to be created such that they are: 1) interoperable with the C Language and 2) able to have its values soundly reinterpreted as a different type.

 Q4
- ______ removes all byte padding from a type.
