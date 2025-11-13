# CATS_THE_MUSICAL
# Cat Class

## Description
The `Cat` class represents a cat with specific attributes such as:
- Name
- Species
- Claws
- Tail
- Whiskers
- Sharp Teeth
- Collar (associated as a separate object)

This class provides methods to access and modify these attributes, as well as additional behaviors such as making sounds, moving its tail, and scratching.

## Features
- **Attributes**:
  - `name`: The name of the cat.
  - `species`: The species of the cat.
  - `claws`: Indicates whether the cat has claws.
  - `tail`: Indicates whether the cat has a tail.
  - `whiskers`: Indicates whether the cat has whiskers.
  - `sharpTeeth`: Indicates whether the cat has sharp teeth.
  - `collar`: A `Collar` object associated with the cat.

- **Methods**:
  - Getters and setters for all attributes.
  - `sound()`: Makes the cat produce a "Meow!" sound.
  - `tailMove()`: Makes the cat move its tail if it has one.
  - `scratch()`: Makes the cat scratch if it has claws.
  - `toString()`: Returns a string representation of the `Cat` object.

## Constructor
The `Cat` class includes a constructor to initialize all attributes:
```java
public Cat(String name, String species, boolean claws, boolean tail, boolean whiskers, boolean sharpTeeth, Collar collar)

# Collar Class

## Description
The `Collar` class represents a collar that can be associated with a cat. It includes attributes such as:
- **Color**: The color of the collar.
- **Size**: The size of the collar.

This class provides methods to access and modify these attributes.

## Features
- **Attributes**:
  - `color`: The color of the collar.
  - `size`: The size of the collar.

- **Methods**:
  - Getters and setters for both `color` and `size`.

## Constructor
The `Collar` class includes a constructor to initialize its attributes:
```java
public Collar(String color, String size)

<img width="2464" height="2644" alt="image" src="https://github.com/user-attachments/assets/613dfa0f-9bdf-48d0-847a-a223c96824da" />
