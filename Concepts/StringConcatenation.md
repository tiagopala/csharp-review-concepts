# String Concatenation & Interpolation

## Intermediate string variables

Unless you have a good reason to do store the result of a string concatenation in a variable, you can (**and should**) avoid using intermediate variables by performing the concatenation operation as you need it.

> Avoid intermediate variables, just simply concatenate the strings instead.

## String Interpolation

Always prefer to use string interpolations over concatenation when possible.

Examples:
```csharp
string message = greeting + " " + firstName + "!";
```

```csharp
string message = $"{greeting} {firstName}!";
```

In this simple example, you save a few keystrokes. You can imagine how much more concise string interpolation can be in more complex operations. Moreover, many find the string interpolation syntax cleaner and easier to read.

### Combine verbatim literals + string interpolation

When needed you can combine both of them in one string, by using the prefix `$` followed by the `@` suffix, as could seen in the example below:

```csharp
string projectName = "First-Project";
Console.WriteLine($@"C:\Output\{projectName}\Data");
```

Output:
```
C:\Output\First-Project\Data
```