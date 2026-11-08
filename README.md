# Java Loops Example

A small Java program that shows the three basic loop types in Java: `while`, `do-while`, and `for`. Each loop prints the numbers 1 to 5, so you can compare how they are written.

## The Three Loops

### 1. `while` loop

Checks the condition **before** each pass.

```java
int i = 1;
while (i <= 5) {
    System.out.println(i);
    i++;
}
```

### 2. `do-while` loop

Checks the condition **after** each pass, so the body always runs at least once.

```java
int j = 1;
do {
    System.out.println(j);
    j++;
} while (j <= 5);
```

### 3. `for` loop

Puts the initialization, condition, and update in one line.

```java
for (int k = 1; k <= 5; k++) {
    System.out.println(k);
}
```

## Comparison

| Loop | Condition checked | Runs at least once | Best used when |
|------|-------------------|--------------------|----------------|
| `while` | Before the body | No | The number of repeats is not known in advance |
| `do-while` | After the body | Yes | The body must run once before checking, such as a menu |
| `for` | Before the body | No | The number of repeats is known |

## Output

```
While Loop:
1
2
3
4
5
Do-While Loop:
1
2
3
4
5
For Loop:
1
2
3
4
5
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### Compile

```bash
javac Main.java
```

### Run

```bash
java Main
```

## Project Structure

```
.
├── Main.java
└── README.md
```

## Next Steps

- Count down instead of up
- Print only even numbers
- Use a loop to add up the numbers from 1 to 100
- Try nested loops to print a multiplication table
