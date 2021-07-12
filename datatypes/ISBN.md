# The ISBN datatype

The datatype that represents the ISBN identifier.

It is based on the [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md) datatype with the additional restriction that the string must match the following regular expression:
```
(97(8|9))?[0-9]{9}[0-9X]
```

---
