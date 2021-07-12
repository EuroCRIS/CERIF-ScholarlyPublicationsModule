# Editorship

## Definition

The relationship of an editor to some specific subclasses of [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md).
An **editor** selects and prepares for publication material created and submitted by authors, having oversight of its content, format and presentation.<sup>[1](#fn1)</sup>

## Specialization of
[Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Authorship.md)

## Attributes
editor: [Agent](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Agent.md)
* [FIXME] replacing the inherited contributor attribute from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md) 

document: [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md)

affiliations: List<[Affiliation Statement](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Affiliation_Statement.md)> (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md))

contribution statements: List<[Contribution Statement](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution_Statement.md)>  (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md))

contacts: List<[URI](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/URI.md)> (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md))

display name: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)  (inherited from [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md)) 

leading editor flag : [Boolean](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Boolean.md) – indicates whether this editor contributed all or major effort (true)

---
## Matches
Close match with the **editor** named individual (http://purl.org/spar/pro/editor) from the SPAR PRO Ontology.<sup>[1](#fn1)</sup>

## References
<a name="fn1">\[1\]</a> Editor. In: *PRO, the Publishing Roles Ontology*. Shotton, D. and Peroni, S. Available: https://sparontologies.github.io/pro/current/pro.html
