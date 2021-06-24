# GraphQL's Schema Definition Language (SDL) types

The Schema Definition Language of GraphQL is used to define the schema of data for a GraphQL based API.

Being platform/language agnostic, GraphQL uses it's own language to define and query a GraphQL API, and when you're building the backend, you'll define your schema with SDL.

## Supported Types

Here's a quick round down of this list:

1. Scalar Types
2. Object Types
3. Query Type
4. Mutation Type
5. Input Types
6. Enum Types

So let's start with the simplest type, the Scalars.

1.**Scalar Types**

Scalar types are like the Primitive types in your favorite language (i.e. strings, booleans, floats, etc.).

In GraphQL, we also have these types which we call Scalars:
- **Int**
- **Float**
- **String**
- **Boolean**
- **ID** - *this one serializes to string, so it's safe to say that id's are string*

2.**Object Types**

I like to think of it as a JavaScript object (but defined as it's own type) or a class, as in the class in OOP (Object Oriented Programming).

It holds a key-value pair, where keys are called as fields, and each field defines the types of data they return, which can be either a Scalar or another Object (to emphasize relationships among nodes).

Here's an example of an object in GraphQL:

![GraphQL object types](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9dqf6vpj5huwzzbog9p8.png)

3.**Query Type**

This type is the entry point for the "GET" request (so to speak). It is consistent to call this type **Query**. Each fields in the Query Type defines the type of data that each field will return.

Here's an example of a Query type:

![GraphQL Query Type](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xte8ad3q024mk0bwx4w3.png)

4.**Mutation Type**

This is near identical to **Query** type, but is responsible for the *Writes* of the API. You use it for "CREATE", "UPDATE", and "DELETE".

Like **Query**, **Mutation** type is also named consistently that way, **Mutation**.

Here's an example of a Mutation type:

![GraphQL mutation type](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sypi08fw2l9jllgm1khy.png)

5.**Input Types**

Since the arguments of a field on other types can be lengthy, it will be tricky and hard to understand it if it got too long. And this is the purpose of Input Types.

Input types are special objects which you can pass as argument to an input in a field, just like how I did it on the example above.

Here's an example of an input type:

![GraphQL Input type](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ohybsnxobtz7ia9ctk03.png)

6.**Enum Types**

The **Enum** types are special types since you can create your own type outside the primitive data types.

This type will be more useful for a specified options of values that a field or endpoint can accept as argument or return. An **Enum** can be placed wherever a Scalar is allowed.

Just to be clear, **Enum* serializes into strings.

Here's an example of an **Enum Type**:

![GraphQL Enum Types](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/f3flkgtxpswkiqf75dgo.png)

## Follow Me on Twitter!

[Twitter @menard_codes](https://twitter.com/menard_codes)

