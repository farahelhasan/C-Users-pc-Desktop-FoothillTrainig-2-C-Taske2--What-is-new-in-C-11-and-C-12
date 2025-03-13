
# C# 11 and C# 12 New Features

## C# 11 Features

| Feature | Description |
|---------|------------|
| **Raw String Literals (`"""` syntax)** | Allows multi-line string literals without escape sequences. |
| **UTF-8 String Literals (`u8` suffix)** | Supports UTF-8 encoded string literals for better performance. |
| **List Patterns** | Enables pattern matching on arrays and lists. |
| **Generic Math Support** | Introduces interfaces like `INumber<T>` for generic mathematical operations. |
| **Ref Fields in Structs** | Allows structs to have `ref` fields for better memory management. |
| **Required Members** | Uses `required` keyword to enforce properties in constructors. |
| **File-Scoped Types** | Declares types using `file` access modifier to limit visibility to the same file. |
| **Auto-Default Structs** | Automatically initializes struct fields to default values. |
| **Extended Nameof Scope** | `nameof` now works with method parameter names inside attributes. |
| **Improved `span` Support in `string`** | Enhances performance by improving `Span<T>` usage. |

## C# 12 Features

| Feature | Description |
|---------|------------|
| **Primary Constructors for Classes** | Enables constructor parameters directly in class declarations. |
| **Collection Expressions (`[...]`)** | Simplifies collection initialization using a new shorthand. |
| **Inline Arrays** | Improves performance by reducing memory allocation. |
| **Alias Any Type (`using MyType = SomeType`)** | Expands `using` aliasing beyond namespaces. |
| **Interceptable Method Calls (`[InterceptsLocation]`)** | Allows code to intercept and modify method calls. |
| **Params Span (`params Span<T>`)** | Enhances `params` support for `Span<T>` arguments. |
| **Default Lambda Parameters** | Supports default values for lambda function parameters. |
| **Enhanced `switch` Expressions** | Improves pattern matching capabilities. |
| **Required Members for Interfaces** | Introduces `required` members in interfaces. |
| **Ref Readonly Parameters** | Adds `ref readonly` for method parameters to prevent modifications. |

