*This project has been created as part of the 42 curriculum by scamlett.*

# Python Module 01: Garden Classes

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![42](https://img.shields.io/badge/42-Málaga-000000)

## Description

An introduction to object-oriented programming, told through a garden. It
starts with a few plain variables and grows, one exercise at a time, into a
small class hierarchy of plants that can grow, age, bloom and keep track of
their own statistics.

| Exercise | File | Topic |
|----------|------|-------|
| ex0 | `ft_garden_intro.py` | Typed variables and a `main()` entry point |
| ex1 | `ft_garden_data.py` | A first `Plant` class with `__init__` and a method |
| ex2 | `ft_plant_growth.py` | Methods that change an object's state over a week |
| ex3 | `ft_plant_factory.py` | Creating many objects from one class |
| ex4 | `ft_garden_security.py` | Encapsulation: "private" `_attributes` with getters and setters that reject bad values |
| ex5 | `ft_plant_types.py` | Inheritance: `Flower`, `Tree` and `Vegetable` extend `Plant` |
| ex6 | `ft_garden_analytics.py` | A nested stats class, `@staticmethod`, `@classmethod` and a multi-level subclass (`Seed`) |

## Instructions

Every exercise runs on its own:

```bash
python3 ex5/ft_plant_types.py
```

## What I learned

- Writing a class with `__init__` and using `self` to store state
- The `if __name__ == "__main__":` guard and why it matters for imports
- Encapsulation by convention: a leading `_` means "don't touch from outside",
  and setters are the place to validate input
- Inheritance with `super().__init__()` and overriding methods like `show()`
  and `grow()` while still reusing the parent's version
- The difference between instance methods, `@staticmethod` (no `self`) and
  `@classmethod` (an alternate constructor such as `create_anonymous()`)
- Checking an object's type with `isinstance()`
