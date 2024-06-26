# Journal

A journal is a serial publication devoted to disseminating original research and current developments on a subject. <sup>[1](#fn1)</sup>

## Usage notes
A [journal article](../entities/Journal_Article.md) should contain information about journal in which it is published. 

## Specialization of
[Publication Series](../entities/Publication_Series.md)

## Attributes

Beside those inherited from [Publication Channel](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/PublicationChannel.md#attributes), and [Publication Series](../entities/Publication_Series.md#attributes):

DOI: [DOI](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/DOI.md) 

title: [Multilingual String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Multilingual_String.md)

acronym: [Multilingual String](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Multilingual_String.md)

start date: [Date](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Date.md)

end date: [Date](https://github.com/EuroCRIS/CERIF-Core/blob/main/datatypes/Date.md)

## Relationships

A journal can have any number of *publishers*: instances of [Agent](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Agent.md) 

Moreover, a journal can have any number of its *predecessors*, i.e. it might be a journal which change the title or ISSN, or it might be two journals merged into the new one.  

<a name="articles"><a name="rel9cce29d9-c141-4947-be73-4058e52d377a">A journal contains a list of *[articles](../entities/Journal_Article.md#user-content-rel9cce29d9-c141-4947-be73-4058e52d377a)* which were published in it: instances of [Journal_Article](../entities/Journal_Article.md).</a></a>

## Matches

1. Close match of [COAR Journal](http://vocabularies.coar-repositories.org/documentation/resource_types/#http://purl.org/coar/resource_type/c_0640)
2. Close match of [Fabio Journal](https://sparontologies.github.io/fabio/current/fabio.html#d4e3613)
3. Close match of [Bibo Journal](http://purl.org/ontology/bibo/Journal) 

## References
<a name="fn1">\[1\]</a> Source: COAR resource types vocabulary, http://purl.org/coar/resource_type/c_0640
