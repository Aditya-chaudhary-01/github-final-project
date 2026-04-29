# Simple Interest Calculator

A lightweight calculator to compute simple interest using the standard formula.

## Formula

```
Simple Interest (SI) = (Principal × Rate × Time) / 100
```

- **Principal (P)** – The initial amount of money
- **Rate (R)** – Annual interest rate (in percentage)
- **Time (T)** – Duration (in years)

**Total Amount = Principal + Simple Interest**

## Usage

```python
def simple_interest(principal, rate, time):
    si = (principal * rate * time) / 100
    return si

# Example
principal = 1000   # $1000
rate = 5           # 5% per annum
time = 3           # 3 years

si = simple_interest(principal, rate, time)
print(f"Simple Interest: ${si}")
print(f"Total Amount: ${principal + si}")
```

**Output:**
```
Simple Interest: $150.0
Total Amount: $1150.0
```

## Example Calculation

| Principal | Rate | Time | Simple Interest | Total Amount |
|-----------|------|------|-----------------|--------------|
| $1,000    | 5%   | 3 yr | $150            | $1,150       |
| $5,000    | 8%   | 2 yr | $800            | $5,800       |
| $2,500    | 10%  | 5 yr | $1,250          | $3,750       |

## License

MIT
