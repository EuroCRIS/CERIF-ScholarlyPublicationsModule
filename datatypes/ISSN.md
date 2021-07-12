# The ISSN datatype

The datatype that represents the ISSN identifier.

It is based on the [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md) datatype with the additional restriction that the string must match the following regular expression:
```
[0-9]{4}-[0-9]{3}[0-9xX]
```

---
