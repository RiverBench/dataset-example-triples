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

- **<abbr title="A name given to the resource.">Title</abbr>**: Example triples dataset
- **<abbr title="An unambiguous reference to the resource within a given context.">Identifier</abbr>**: example-triples
- **<abbr title="Version tag of an artifact">Has version</abbr>**: dev
- **<abbr title="A main category of the resource. A resource can have multiple themes.">Theme</abbr>**: Abstract ([rbt:abstract](https://riverbench.github.io/schema/theme#abstract))
- **<abbr title="An entity responsible for making the resource.">Creator</abbr>**: 
    - **<abbr title="A name for some thing.">Name</abbr>**: Piotr Sowiński
    - **<abbr title="A short informal nickname characterising an agent (includes login identifiers, IRC and other chat nicknames).">Nickname</abbr>**: Ostrzyciel
    - **<abbr title="A homepage for some thing.">Homepage</abbr>**: [https://github.com/Ostrzyciel](https://github.com/Ostrzyciel)
- **<abbr title="A legal document giving official permission to do something with the resource.">License</abbr>**: CC0-1.0 ([http://spdx.org/licenses/CC0-1.0](http://spdx.org/licenses/CC0-1.0))
- **<abbr title="Date of formal issuance of the resource.">Date Issued</abbr>**: 2023-03-13
- **<abbr title="Date on which the resource was changed.">Date Modified</abbr>**: 2023-03-13
- **<abbr title="A Web page that can be navigated to in a Web browser to gain access to the catalog, a dataset, its distributions and/or additional information.">Landing page</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev](https://riverbench.github.io/datasets/example-triples/dev)

## Technical metadata

- **<abbr title="Indicates the type of contents of each stream element">Has stream element type</abbr>**: <abbr title="Triple streams consist of elements, where each element is an RDF graph.">Triples</abbr> ([rb:triples](https://riverbench.github.io/schema/dataset#triples))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 132432
- **Has stream element split**: 
    - **Type**: Stream elements split by time ([rb:TimeStreamElementSplit](https://riverbench.github.io/schema/dataset#TimeStreamElementSplit))
    - **<abbr title="A description of the subject resource.">Comment</abbr>**: The stream is split into 1 second intervals. Each element is one observation.
- **<abbr title="Indicates that the dataset uses an ontology. The object must be a resource, but it doesn't neccesarily have to be an OWL ontology.">Uses ontology</abbr>**: [https://name-example/p2](https://name-example/p2)
- **<abbr title="Whether the dataset is RDF 1.1-compliant, i.e., does not use any non-standard features, like generalized triples.">Conforms to W3C RDF 1.1 specification</abbr>**: yes
- **<abbr title="Whether the dataset is RDF-star compliant, i.e., does not use any non-standard features. Note that all standard RDF 1.1 datasets also qualify, as RDF-star is a superset of RDF 1.1.">Conforms to W3C RDF-star draft specification as of December 17, 2021</abbr>**: yes
- **<abbr title="Whether the dataset uses the non-standard generalized triples feature">Uses generalized triples</abbr>**: no
- **<abbr title="Whether the dataset uses the non-standard generalized datasets feature. A 'dataset' here is used in the same meaning as in the RDF 1.1 specification.">Uses generalized RDF datasets</abbr>**: no
- **<abbr title="Whether the dataset uses RDF-star features.">Uses RDF-star</abbr>**: no
- **<abbr title="minimum time period resolvable in a dataset.">Temporal resolution</abbr>**: PT1S

## Distributions

### 100K elements flat distribution

- **<abbr title="A name given to the resource.">Title</abbr>**: 100K elements flat distribution
- **<abbr title="Canonical file name of this distribution">Has file name</abbr>**: `flat_100K.nt.gz`
- **<abbr title="Indicates the type of RiverBench dataset distribution">Has distribution type</abbr>**: 
    - <abbr title="The dataset is distributed as a single flat file.">Flat distribution</abbr> ([rb:flatDistribution](https://riverbench.github.io/schema/dataset#flatDistribution))
    - <abbr title="A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.">Partial distribution</abbr> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 100000
- **<abbr title="The size of a distribution in bytes.">Byte size</abbr>**: 9578677
- **<abbr title="The media type of the distribution as defined by IANA">Media type</abbr>**: application/n-triples
- **<abbr title="The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.">Compression format</abbr>**: application/gzip
- **<abbr title="The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.">Download URL</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev/files/flat_100K.nt.gz](https://riverbench.github.io/datasets/example-triples/dev/files/flat_100K.nt.gz)

### 100K elements triple stream distribution

- **<abbr title="A name given to the resource.">Title</abbr>**: 100K elements triple stream distribution
- **<abbr title="Canonical file name of this distribution">Has file name</abbr>**: `stream_100K.tar.gz`
- **<abbr title="Indicates the type of RiverBench dataset distribution">Has distribution type</abbr>**: 
    - <abbr title="A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.">Partial distribution</abbr> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
    - <abbr title="The dataset is distributed as a stream of RDF triples.">Triple stream distribution</abbr> ([rb:tripleStreamDistribution](https://riverbench.github.io/schema/dataset#tripleStreamDistribution))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 100000
- **<abbr title="The size of a distribution in bytes.">Byte size</abbr>**: 12561073
- **<abbr title="The media type of the distribution as defined by IANA">Media type</abbr>**: text/turtle
- **<abbr title="The package format of the distribution in which one or more data files are grouped together, e.g. to enable a set of related files to be downloaded together.">Packaging format</abbr>**: application/tar
- **<abbr title="The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.">Compression format</abbr>**: application/gzip
- **<abbr title="The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.">Download URL</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev/files/stream_100K.tar.gz](https://riverbench.github.io/datasets/example-triples/dev/files/stream_100K.tar.gz)

### 10K elements flat distribution

- **<abbr title="A name given to the resource.">Title</abbr>**: 10K elements flat distribution
- **<abbr title="Canonical file name of this distribution">Has file name</abbr>**: `flat_10K.nt.gz`
- **<abbr title="Indicates the type of RiverBench dataset distribution">Has distribution type</abbr>**: 
    - <abbr title="The dataset is distributed as a single flat file.">Flat distribution</abbr> ([rb:flatDistribution](https://riverbench.github.io/schema/dataset#flatDistribution))
    - <abbr title="A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.">Partial distribution</abbr> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 10000
- **<abbr title="The size of a distribution in bytes.">Byte size</abbr>**: 961030
- **<abbr title="The media type of the distribution as defined by IANA">Media type</abbr>**: application/n-triples
- **<abbr title="The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.">Compression format</abbr>**: application/gzip
- **<abbr title="The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.">Download URL</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev/files/flat_10K.nt.gz](https://riverbench.github.io/datasets/example-triples/dev/files/flat_10K.nt.gz)

### 10K elements triple stream distribution

- **<abbr title="A name given to the resource.">Title</abbr>**: 10K elements triple stream distribution
- **<abbr title="Canonical file name of this distribution">Has file name</abbr>**: `stream_10K.tar.gz`
- **<abbr title="Indicates the type of RiverBench dataset distribution">Has distribution type</abbr>**: 
    - <abbr title="A partial distribution, including only a subset of the data in the dataset. The rb:hasStreamElementCount property indicates the length of this distribution.">Partial distribution</abbr> ([rb:partialDistribution](https://riverbench.github.io/schema/dataset#partialDistribution))
    - <abbr title="The dataset is distributed as a stream of RDF triples.">Triple stream distribution</abbr> ([rb:tripleStreamDistribution](https://riverbench.github.io/schema/dataset#tripleStreamDistribution))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 10000
- **<abbr title="The size of a distribution in bytes.">Byte size</abbr>**: 1259435
- **<abbr title="The media type of the distribution as defined by IANA">Media type</abbr>**: text/turtle
- **<abbr title="The package format of the distribution in which one or more data files are grouped together, e.g. to enable a set of related files to be downloaded together.">Packaging format</abbr>**: application/tar
- **<abbr title="The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.">Compression format</abbr>**: application/gzip
- **<abbr title="The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.">Download URL</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev/files/stream_10K.tar.gz](https://riverbench.github.io/datasets/example-triples/dev/files/stream_10K.tar.gz)

### Full flat distribution

- **<abbr title="A name given to the resource.">Title</abbr>**: Full flat distribution
- **<abbr title="Canonical file name of this distribution">Has file name</abbr>**: flat_full.nt.gz
- **<abbr title="Indicates the type of RiverBench dataset distribution">Has distribution type</abbr>**: 
    - <abbr title="The dataset is distributed as a single flat file.">Flat distribution</abbr> ([rb:flatDistribution](https://riverbench.github.io/schema/dataset#flatDistribution))
    - <abbr title="A full distribution, including all data in the dataset.">Full distribution</abbr> ([rb:fullDistribution](https://riverbench.github.io/schema/dataset#fullDistribution))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 132432
- **<abbr title="The size of a distribution in bytes.">Byte size</abbr>**: 12675847
- **<abbr title="The media type of the distribution as defined by IANA">Media type</abbr>**: application/n-triples
- **<abbr title="The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.">Compression format</abbr>**: application/gzip
- **<abbr title="The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.">Download URL</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev/files/flat_full.nt.gz](https://riverbench.github.io/datasets/example-triples/dev/files/flat_full.nt.gz)

### Full triple stream distribution

- **<abbr title="A name given to the resource.">Title</abbr>**: Full triple stream distribution
- **<abbr title="Canonical file name of this distribution">Has file name</abbr>**: stream_full.tar.gz
- **<abbr title="Indicates the type of RiverBench dataset distribution">Has distribution type</abbr>**: 
    - <abbr title="A full distribution, including all data in the dataset.">Full distribution</abbr> ([rb:fullDistribution](https://riverbench.github.io/schema/dataset#fullDistribution))
    - <abbr title="The dataset is distributed as a stream of RDF triples.">Triple stream distribution</abbr> ([rb:tripleStreamDistribution](https://riverbench.github.io/schema/dataset#tripleStreamDistribution))
- **<abbr title="Number of elements in the stream">Has stream element count</abbr>**: 132432
- **<abbr title="The size of a distribution in bytes.">Byte size</abbr>**: 16625234
- **<abbr title="The media type of the distribution as defined by IANA">Media type</abbr>**: text/turtle
- **<abbr title="The package format of the distribution in which one or more data files are grouped together, e.g. to enable a set of related files to be downloaded together.">Packaging format</abbr>**: application/tar
- **<abbr title="The compression format of the distribution in which the data is contained in a compressed form, e.g. to reduce the size of the downloadable file.">Compression format</abbr>**: application/gzip
- **<abbr title="The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType.">Download URL</abbr>**: [https://riverbench.github.io/datasets/example-triples/dev/files/stream_full.tar.gz](https://riverbench.github.io/datasets/example-triples/dev/files/stream_full.tar.gz)

