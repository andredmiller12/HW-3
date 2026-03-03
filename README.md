# HW-3
Discussion Questions:

-  The method doesn't need to know the exact type because of the generic placeholder <T>. The place holder <T> eliminates the need for casting and reduces the runtime errors and potentially improve performance. The <T> placeholder is consistent and allows any type like String, Integer and Double to work.
- If <T> was removed, the method would no longer be able to adjust to the user's input. Its functionality comes from its ability to adapt to different data types.
- Generics are important for larger systems because they allow code to be reused. Instead of creating separate methods or classes for Strings, Integers, or Doubles, one generic version can handle everything. Generics can also reduce runtime errors and make code cleaner by eliminating the need for casting when retrieving objects.
