# cs50-python-problem-sets.
Solutions to three CS50 Python problem sets: File Extensions, Coke Machine, and Vanity Plates.

## Problems

### 1. File Extensions

The program asks the user for a file name and identifies its media type based on the file extension.

The program handles:

- `.gif`
- `.jpg`
- `.jpeg`
- `.png`
- `.pdf`
- `.txt`
- `.zip`

Unknown or missing extensions return `application/octet-stream`.

### 2. Coke Machine

The program simulates a Coke machine that costs 50 cents.

It accepts only:

- 25 cents
- 10 cents
- 5 cents

The program continues requesting coins until at least 50 cents has been inserted and then displays the change owed.

### 3. Vanity Plates

The program checks whether a vanity license plate satisfies the required rules.

The plate must:

- contain between 2 and 6 characters;
- start with at least two letters;
- contain only letters and numbers;
- have numbers only at the end;
- not have 0 as the first number.

## Testing

All three programs were tested using CS50's `check50` testing system.

### File Extensions

```bash
check50 cs50/problems/2022/python/extensions
```

### Coke Machine

```bash
check50 cs50/problems/2022/python/coke
```

### Vanity Plates

```bash
check50 cs50/problems/2022/python/plates
```
