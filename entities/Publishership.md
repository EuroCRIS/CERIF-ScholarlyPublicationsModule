# Publishership

## Definition
The relationship of a publisher to some subclasses of [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md).
A **publisher** (a person or an organization) publishes material.<sup>[1](#fn1)</sup>

## Specialization of
[Contribution](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Authorship.md)

## Attributes

Beside those inherited from [Contribution](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution.md#attributes), there are also the following specific attribute:

leading publisher flag : [Boolean](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Boolean.md) – indicates whether this publisher was the leading one among several (true)

## Relationships

Beside those inherited from [Contribution](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution.md#relationships), there is also a link to *editor*: an instance of [Agent](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Agent.md) 
[FIXME] replacing the derived *contributor* link from [Contribution](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution.md) 

---
## Matches
1. Close match with the **[publisher](https://sparontologies.github.io/pro/current/pro.html#d4e893)** named individual from the SPAR PRO Ontology.<sup>[1](#fn1)</sup>

## References
<a name="fn1">\[1\]</a> Publisher. In: *PRO, the Publishing Roles Ontology*. Shotton, D. and Peroni, S. Available: https://sparontologies.github.io/pro/current/pro.html
