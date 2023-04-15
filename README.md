<!--
--
-- THIS FILE IS AUTOGENERATED. DO NOT EDIT.
-- Please edit the metadata.ttl file instead. The documentation
-- will be regenerated by the CI.
--
-- You can place additional docs in the /doc directory. Remember to link
-- to them from the description in the metadata.ttl file.
--
-->
[![.github/workflows/release.yaml](https://github.com/RiverBench/dataset-example-triples/actions/workflows/release.yaml/badge.svg?event=push)](https://github.com/RiverBench/dataset-example-triples/actions/workflows/release.yaml)


# example-triples (development version)

This is an example dataset that is a triple stream.

*This README is a snapshot of documentation for the latest development version of the dataset.
Full documentation for all versions can be found [on the website](https://riverbench.github.io/datasets/example-triples/dev).*


## Dataset information

- **Title<sup>[?](## "A name given to the resource.")</sup>**: Example triples dataset
- **Identifier<sup>[?](## "An unambiguous reference to the resource within a given context.")</sup>**: example-triples
- **Has version<sup>[?](## "Version tag of an artifact")</sup>**: dev
- **Theme<sup>[?](## "A main category of the resource. A resource can have multiple themes.")</sup>**: Abstract ([rbt:abstract](https://riverbench.github.io/schema/theme#abstract))
- **Creator<sup>[?](## "An entity responsible for making the resource.")</sup>**: 
  - **Name<sup>[?](## "A name for some thing.")</sup>**: Piotr Sowiński
  - **Nickname<sup>[?](## "A short informal nickname characterising an agent (includes login identifiers, IRC and other chat nicknames).")</sup>**: Ostrzyciel
  - **Homepage<sup>[?](## "A homepage for some thing.")</sup>**: https://github.com/Ostrzyciel
- **License<sup>[?](## "A legal document giving official permission to do something with the resource.")</sup>**: CC0-1.0 ([http://spdx.org/licenses/CC0-1.0](http://spdx.org/licenses/CC0-1.0))
- **Date Issued<sup>[?](## "Date of formal issuance of the resource.")</sup>**: 2023-03-13
- **Date Modified<sup>[?](## "Date on which the resource was changed.")</sup>**: 2023-03-13
- **Landing page<sup>[?](## "A Web page that can be navigated to in a Web browser to gain access to the catalog, a dataset, its distributions and/or additional information.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev

## Technical metadata

- **Has stream element type<sup>[?](## "Indicates the type of contents of each stream element")</sup>**: Triples<sup>[?](## "Triple streams consist of elements, where each element is an RDF graph.")</sup> ([rb:triples](https://riverbench.github.io/schema/dataset#triples))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 132432
- **Has stream element split**: 
  - **Type**: Stream elements split by time ([rb:TimeStreamElementSplit](https://riverbench.github.io/schema/dataset#TimeStreamElementSplit))
  - **Comment<sup>[?](## "A description of the subject resource.")</sup>**: The stream is split into 1 second intervals. Each element is one observation.
- **Uses ontology<sup>[?](## "Indicates that the dataset uses an ontology. The object must be a resource, but it doesn't neccesarily have to be an OWL ontology.")</sup>**: https://name-example/p2
- **Conforms to W3C RDF 1.1 specification<sup>[?](## "Whether the dataset is RDF 1.1-compliant, i.e., does not use any non-standard features, like generalized triples.")</sup>**: yes
- **Conforms to W3C RDF-star draft specification as of December 17, 2021<sup>[?](## "Whether the dataset is RDF-star compliant, i.e., does not use any non-standard features. Note that all standard RDF 1.1 datasets also qualify, as RDF-star is a superset of RDF 1.1.")</sup>**: yes
- **Uses generalized triples<sup>[?](## "Whether the dataset uses the non-standard generalized triples feature")</sup>**: no
- **Uses generalized RDF datasets<sup>[?](## "Whether the dataset uses the non-standard generalized datasets feature. A 'dataset' here is used in the same meaning as in the RDF 1.1 specification.")</sup>**: no
- **Uses RDF-star<sup>[?](## "Whether the dataset uses RDF-star features.")</sup>**: no
- **Temporal resolution<sup>[?](## "minimum time period resolvable in a dataset.")</sup>**: PT1S

## Distributions

### 100K elements flat distribution

- **Title<sup>[?](## "A name given to the resource.")</sup>**: 100K elements flat distribution
- **Has file name<sup>[?](## "Canonical file name of this distribution")</sup>**: `flat_100K.nt.gz`
- **Has distribution type<sup>[?](## "Indicates the type of RiverBench dataset distribution")</sup>**: 
  - Flat distribution<sup>[?](## "The dataset is distributed as a single flat file.")</sup> ([rb:flatDistribution](https://riverbench.github.io/schema/dataset#flatDistribution))
  - Partial distribution<sup>[?](## "A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.")</sup> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 100000
- **Byte size<sup>[?](## "The size of a distribution in bytes.")</sup>**: 9578677
- **Media type<sup>[?](## "The media type of the distribution as defined by IANA")</sup>**: application/n-triples
- **Compression format<sup>[?](## "The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.")</sup>**: application/gzip
- **Download URL<sup>[?](## "The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev/flat_100K.nt.gz

### 100K elements triple stream distribution

- **Title<sup>[?](## "A name given to the resource.")</sup>**: 100K elements triple stream distribution
- **Has file name<sup>[?](## "Canonical file name of this distribution")</sup>**: `stream_100K.tar.gz`
- **Has distribution type<sup>[?](## "Indicates the type of RiverBench dataset distribution")</sup>**: 
  - Partial distribution<sup>[?](## "A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.")</sup> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
  - Triple stream distribution<sup>[?](## "The dataset is distributed as a stream of RDF triples.")</sup> ([rb:tripleStreamDistribution](https://riverbench.github.io/schema/dataset#tripleStreamDistribution))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 100000
- **Byte size<sup>[?](## "The size of a distribution in bytes.")</sup>**: 12562016
- **Media type<sup>[?](## "The media type of the distribution as defined by IANA")</sup>**: text/turtle
- **Packaging format<sup>[?](## "The package format of the distribution in which one or more data files are grouped together, e.g. to enable a set of related files to be downloaded together.")</sup>**: application/tar
- **Compression format<sup>[?](## "The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.")</sup>**: application/gzip
- **Download URL<sup>[?](## "The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev/stream_100K.tar.gz

### 10K elements flat distribution

- **Title<sup>[?](## "A name given to the resource.")</sup>**: 10K elements flat distribution
- **Has file name<sup>[?](## "Canonical file name of this distribution")</sup>**: `flat_10K.nt.gz`
- **Has distribution type<sup>[?](## "Indicates the type of RiverBench dataset distribution")</sup>**: 
  - Flat distribution<sup>[?](## "The dataset is distributed as a single flat file.")</sup> ([rb:flatDistribution](https://riverbench.github.io/schema/dataset#flatDistribution))
  - Partial distribution<sup>[?](## "A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.")</sup> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 10000
- **Byte size<sup>[?](## "The size of a distribution in bytes.")</sup>**: 961030
- **Media type<sup>[?](## "The media type of the distribution as defined by IANA")</sup>**: application/n-triples
- **Compression format<sup>[?](## "The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.")</sup>**: application/gzip
- **Download URL<sup>[?](## "The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev/flat_10K.nt.gz

### 10K elements triple stream distribution

- **Title<sup>[?](## "A name given to the resource.")</sup>**: 10K elements triple stream distribution
- **Has file name<sup>[?](## "Canonical file name of this distribution")</sup>**: `stream_10K.tar.gz`
- **Has distribution type<sup>[?](## "Indicates the type of RiverBench dataset distribution")</sup>**: 
  - Partial distribution<sup>[?](## "A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.")</sup> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
  - Triple stream distribution<sup>[?](## "The dataset is distributed as a stream of RDF triples.")</sup> ([rb:tripleStreamDistribution](https://riverbench.github.io/schema/dataset#tripleStreamDistribution))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 10000
- **Byte size<sup>[?](## "The size of a distribution in bytes.")</sup>**: 1259418
- **Media type<sup>[?](## "The media type of the distribution as defined by IANA")</sup>**: text/turtle
- **Packaging format<sup>[?](## "The package format of the distribution in which one or more data files are grouped together, e.g. to enable a set of related files to be downloaded together.")</sup>**: application/tar
- **Compression format<sup>[?](## "The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.")</sup>**: application/gzip
- **Download URL<sup>[?](## "The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev/stream_10K.tar.gz

### Full flat distribution

- **Title<sup>[?](## "A name given to the resource.")</sup>**: Full flat distribution
- **Has file name<sup>[?](## "Canonical file name of this distribution")</sup>**: flat_full.nt.gz
- **Has distribution type<sup>[?](## "Indicates the type of RiverBench dataset distribution")</sup>**: 
  - Flat distribution<sup>[?](## "The dataset is distributed as a single flat file.")</sup> ([rb:flatDistribution](https://riverbench.github.io/schema/dataset#flatDistribution))
  - Full distribution<sup>[?](## "A full distribution, including all data in the dataset.")</sup> ([rb:fullDistribution](https://riverbench.github.io/schema/dataset#fullDistribution))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 132432
- **Byte size<sup>[?](## "The size of a distribution in bytes.")</sup>**: 12675847
- **Media type<sup>[?](## "The media type of the distribution as defined by IANA")</sup>**: application/n-triples
- **Compression format<sup>[?](## "The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.")</sup>**: application/gzip
- **Download URL<sup>[?](## "The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev/flat_full.nt.gz

### Full triple stream distribution

- **Title<sup>[?](## "A name given to the resource.")</sup>**: Full triple stream distribution
- **Has file name<sup>[?](## "Canonical file name of this distribution")</sup>**: stream_full.tar.gz
- **Has distribution type<sup>[?](## "Indicates the type of RiverBench dataset distribution")</sup>**: 
  - Full distribution<sup>[?](## "A full distribution, including all data in the dataset.")</sup> ([rb:fullDistribution](https://riverbench.github.io/schema/dataset#fullDistribution))
  - Triple stream distribution<sup>[?](## "The dataset is distributed as a stream of RDF triples.")</sup> ([rb:tripleStreamDistribution](https://riverbench.github.io/schema/dataset#tripleStreamDistribution))
- **Has stream element count<sup>[?](## "Number of elements in the stream")</sup>**: 132432
- **Byte size<sup>[?](## "The size of a distribution in bytes.")</sup>**: 16626831
- **Media type<sup>[?](## "The media type of the distribution as defined by IANA")</sup>**: text/turtle
- **Packaging format<sup>[?](## "The package format of the distribution in which one or more data files are grouped together, e.g. to enable a set of related files to be downloaded together.")</sup>**: application/tar
- **Compression format<sup>[?](## "The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.")</sup>**: application/gzip
- **Download URL<sup>[?](## "The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.")</sup>**: https://riverbench.github.io/datasets/example-triples/dev/stream_full.tar.gz

