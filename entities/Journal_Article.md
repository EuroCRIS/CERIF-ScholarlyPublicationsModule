# Journal Article

An article on a particular topic and published in a journal issue. <sup>[1](#fn1)</sup>

## Usage notes
[FIXME] This class should be used for any type of journal article such as review article or researh article. 

## Specialization of

[Scholarly Publication](../entities/Scholarly_Publication.md)

## Attributes

Beside those inherited from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md#attributes), and [Scholarly Publication](../entities/Scholarly_Publication.md#attributes), there are the following attributes specific for this type of scholarly publication:

startPage: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

endPage: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

volume: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

number: [String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/String.md)

## Relationships
Those from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md#relationships), and [Scholarly Publication](../entities/Scholarly_Publication.md#relationships).

<a name="journal"><a name="rel9cce29d9-c141-4947-be73-4058e52d377a">A journal article should contain information about the *[journal](../entities/Journal.md#user-content-articles)* in which it is published: an instance of [Journal](../entities/Journal.md).</a></a>

## Illustrative Diagram

### Class diagram
![The JournalArticle diagram](../diagrams/journalArticle.svg)

### Example usage

Please, find an example at [Juurnal Article example](../examples/Journal_Article_Example1.md)

## Matches

1. Close match of [COAR Journal Article](http://vocabularies.coar-repositories.org/documentation/resource_types/#http://purl.org/coar/resource_type/c_6501)
2. Close match of [Fabio Journal Article](https://sparontologies.github.io/fabio/current/fabio.html#d4e3646)
3. Narrow match of [Bibo Article](http://purl.org/ontology/bibo/Article)
4. Narrow match of [Schema.org Article](https://schema.org/Article) 

## References

<a name="fn1">\[1\]</a> Source: COAR resource types vocabulary, http://purl.org/coar/resource_type/c_6501
