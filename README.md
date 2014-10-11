A Python generator for the [Twitter
Snowflake](https://github.com/twitter/snowflake) scheme in 61 lines of spacious
code.

```python

    >>> import snowflake
    >>> s = snowflake.generator(1, 1)
    >>> s.next()
    1132805160360349696
    >>> s.next()
    1132805164143611904
    >>> s.next()
    1132805168782512128
```
