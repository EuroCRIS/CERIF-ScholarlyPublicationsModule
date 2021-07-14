# Journal Article

An article on a particular topic and published in a journal issue. <sup>[1](#fn1)</sup>

## Usage notes
[FIXME] This class should be used for any type of journal article such as review article or researh article. 

## Specialization of

[Textual Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document.md)

## Attributes

DOI: [DOI_Type](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/DOI.md) (inherited from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md))

title: [Multilingual String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Multilingual_String.md) (inherited from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md))

publication date: [Date](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Date.md) (inherited from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md))

access rights: [Textual Document Accessibility Specification](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document_Accessibility_Specification.md)

contributorships: List<[Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md) (inherited from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md))

authorships: List<[Authorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Authorship.md) (inherited from [Textual Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document.md))

authors: List<[Agent](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Agent.md) (inherited from [Textual Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document.md))

startPage: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

endPage: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

volume: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

number: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

journal: [Journal](../entities/Journal.md)

![The JournalArticle diagram](../diagrams/journalArticle.svg)

## Matches

1. Close match of [COAR Journal Article](http://vocabularies.coar-repositories.org/documentation/resource_types/#http://purl.org/coar/resource_type/c_6501)
2. Close match of [Fabio Journal Article](https://sparontologies.github.io/fabio/current/fabio.html#d4e3646)
3. Narrow match of [Bibo Article](http://purl.org/ontology/bibo/Article)
4. Narrow match of [Schema.org Article](https://schema.org/Article) 

## References

<a name="fn1">\[1\]</a> Source: COAR resource types vocabulary, http://purl.org/coar/resource_type/c_6501
