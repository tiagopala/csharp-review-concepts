# Escaping Strings in C#: A Safe Approach to Handling Data

## Character Escape Sequences

- `\n`: new line
- `\t`: tab
- `\\`: backslash
- `\"`: double quote

## Verbatim String Literal

By using the `@` it will keep all the whitespace and characters without the need to escape the backslash.

Example:
```csharp
Console.WriteLine(@"    c:\source\repos
        (this is where your code goes)");
```

Output:
```
c:\source\repos
        (this is where your code goes)
```

## Unicode Escape Characters

With `\u` + four-character code it's possible to add encoded characters in string.

Example:
```csharp
// Kon'nichiwa World
Console.WriteLine("\u3053\u3093\u306B\u3061\u306F World!");
```

Output:
```
こんにちは World!
```