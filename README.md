# Assignment-1
# Blog

***Understanding Union and Intersection Types in TypeScript, and Differences Between Interfaces and Types**


Today we are discuse about Union and intersection  and  Diffrences between interfaces and types. 
1. Union & intersection 
Union types allow a variable to hold different types, but only one at a time. Think of it is  like choosing between Pizza or Pasta — you can pick one, but not both.

Example:
If you're ordering food, you can choose  only one  Pizza or Pasta. Similarly, in TypeScript, a union type lets you pick one type from many options.

Intersection types combine multiple types into one. Imagine a Car-Boat Hybrid that can both drive and float. In TypeScript, intersection types combine properties from multiple types.
Example:
A Vehicle that’s both a Car (can drive) and a Boat (can float).



2. Differences Between Interfaces and Types in TypeScript


Interfaces:
An interface is like a object structure. It defines the structure of an object, look like an architect's blueprint for a house. Interfaces can be extended and merged.

Types:
A type is more flexible, like mixing different ingredients to bake a cake. Types can combine multiple types (using unions and intersections) but can’t be merged like interfaces.

When to Use:
Use Interfaces for defining object shapes, especially if you need to extend or merge them.

Use Types for complex combinations or when you need more flexibility.

Conclusion



Union Types: Pick one type from many options.

Intersection Types: Combine multiple types into one.

Interfaces: Use them to define and extend object structures.

Types: Use them for more flexibility with complex data combinations.