# Publishership

## Definition
The relationship of a publisher to some subclasses of [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md).
A **publisher** (a person or an organization) publishes material.<sup>[1](#fn1)</sup>

## Specialization of
[Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Authorship.md)

## Attributes
publisher: [Agent](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Agent.md)
* [FIXME] replacing the inherited contributor attribute from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md) 

document: [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md)

[FIXME] is there any sense in the next three inhereted attributes in the context of publisership
affiliations: List<[Affiliation Statement](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Affiliation_Statement.md)> (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md))

contribution statements: List<[Contribution Statement](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution_Statement.md)>  (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md))

contacts: List<[URI](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/URI.md)> (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md))

display name: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)  (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md)) 

leading publisher flag : [Boolean](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Boolean.md) – indicates whether this publisher was the leading one among several

---
## References
<a name="fn1">\[1\] Publisher. In: *PRO, the Publishing Roles Ontology.* Shotton, D. and Peroni, S. Available: https://sparontologies.github.io/pro/current/pro.html

