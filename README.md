# Impresso Schemas

Repository of JSON schemas (draft 06) used in the [Impresso project](https://impresso-project.ch/).

We define schemas for:

- Newspaper
    - [Issue](docs/issue.md)
    - [Page](docs/page.md)
    - [Content Item](docs/contentitem.md)
- Topic Model
    - [Topic Assignment](docs/topic_assignment.md)
    - [Topic Description](docs/topic_description.md)
- Language Identification
    - [Language Identification](docs/language_identification.md)

## File organisation

 - `json/` subdirectory for JSON schemas
 - `examples/` subdirectory for example/test files
 - `docs/` documentation of schemas in markdown format

## Validation examples

Run:

```bash
make tests
```

## Documentation

Generated by using [`jsonschema2md`](https://github.com/adobe/jsonschema2md) with the following commands:

```bash
make documentation
```


## Project

The 'impresso - Media Monitoring of the Past' project is funded by the Swiss National Science Foundation (SNSF) under grant number [CRSII5_173719](http://p3.snf.ch/project-173719) (Sinergia program). The project aims at developing tools to process and explore large-scale collections of historical newspapers, and at studying the impact of this new tooling on historical research practices. More information at https://impresso-project.ch.

## License

Copyright (C) 2020  The *impresso* team. Contributors to this program include: [Simon Clematide](https://github.com/simon-clematide), [Maud Ehrmann](https://github.com/e-maud) and [Matteo Romanello](http://github.com/mromanello/) ).

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. 
This program is distributed in the hope that it will be useful, but without any warranty; without even the implied warranty of merchantability or fitness for a particular purpose. See the [GNU Affero General Public License](https://github.com/impresso/impresso-schemas/blob/master/LICENSE) for more details.




