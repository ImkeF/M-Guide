# Number.Mod

## About

Divides two numbers and returns the remainder of the resulting number.

```Number.Mod(number as nullable number, divisor as nullable number, optional precision as nullable number) as nullable number ```


## Arguments

| Argument | Description |
| ------------------------- | --------------------------------- |
| number                    | Dividend or numerator             |
| divisor                   | Divisor or denominator            |

## Example

```Number.Mod(83, 9)  ```   equals 2 



## Caveats
- Diverging signs at numerator and divisor will lead to different results compared to Excel and DAX (https://github.com/ImkeF/Caveats-in-native-M-functions/blob/master/Number.Mod/Number.ModX.pq) 


## Alternatives
- [Number.ModX](../Number.ModX.pq) : Returns the same results than the modulo-function in Excel and DAX 


## Performance

## Link to official documentation
https://msdn.microsoft.com/en-us/library/mt253344.aspx
