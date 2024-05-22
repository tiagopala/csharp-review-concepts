# Data Types & Literals

## Hard-coded Values

Static values that do not change can be called constants or literal values.

## Char (Character)

Abbreviated version of character in C#. It is indicated using single quotes, for example: `'b'`.

## Int (Integer)

Abbreviated version of integer in C#, and should be used for whole numbers.

## Floating-Point Literals

A floating-point number is a number that contains decimals. In C#, we have 3 data types to represent decimal numbers: `float`, `double`, and `decimal`.

| Type     | Precision          |
|----------|--------------------|
| `float`  | ~6-9 digits        |
| `double` | ~15-17 digits      |
| `decimal`| 28-29 digits       |

### Usage Examples:

#### Float

- To create a float with the value 0.25: `Console.WriteLine(0.25F);`
- `F` is called a literal suffix.

#### Double

It is the default data type for decimal numbers in c#, and does not need any literal suffix. For example: `Console.WriteLine(2.625);`

#### Decimal

- To indicate that you want to create a number that uses a decimal data type you can use both `m` or `M` as literal suffixes.

## Boolean Literals

It's the abbreviated version of boolean and can be represented as `true` or `false`.