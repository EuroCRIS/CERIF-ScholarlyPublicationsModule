# Monograph

[FIXME] Book is a non-serial publication that is complete in one volume or a designated finite number of volumes. <sup>[1](#fn1)</sup> 
Monograph is a scholarly book or a treatise on a single subject or a group of related subjects.

## Specialization of

[Scholarly Publication](../entities/Scholarly_Publication.md)

## Attributes

Beside those inherited from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md#attributes), and [Scholarly Publication](../entities/Scholarly_Publication.md#attributes), there are the following attributes specific for this type of scholarly publication:

ISBN: [ISBN](../datatypes/ISBN.md)

eISBN: [ISBN](../datatypes/ISBN.md)

## Relationships
Those from [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md#relationships), and [Scholarly Publication](../entities/Scholarly_Publication.md#relationships).

A Monograph has any number of *editorships*: instances of [Editorship](../entities/Editorship.md). This relationship is derived from *Document.Contributions* by including just those [Contributions](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution.md) that are [Editorships](../entities/Editorship.md).

A Monograph has any number of *publisherships*: instances of [Publishership](../entities/Publishership.md). This relationship is derived from *Document.Contributions* by including just those [Contributions](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution.md) that are [Publisherships](../entities/Publishership.md).

## Matches

1. Narrow match of [COAR Book](http://vocabularies.coar-repositories.org/documentation/resource_types/#http://purl.org/coar/resource_type/c_2f33)
2. Narrow match of [Fabio Book](https://sparontologies.github.io/fabio/current/fabio.html#d4e2263)
3. Narrow match of [Bibo Book](http://purl.org/ontology/bibo/Book)
4. Narrow match of [Schema.org Book](https://schema.org/Book) 

## References
<a name="fn1">\[1\]</a> Source: COAR resource types vocabulary, http://purl.org/coar/resource_type/c_2f33
