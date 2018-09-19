# Accessibility Support

> Status: Stable | [Please Provide Feedback via GitHub](https://github.com/openactive/accessibility-support/issues)

This repository holds the [JSON-LD definition](https://www.openactive.io/accessibility-support/accessibility-support.jsonld) of the OpenActive Accessibility Support controlled vocabulary.

This controlled vocabulary MUST be referenced within a `Concept` via `inScheme` using the URL `"https://openactive.io/accessibility-support"` (which will return the [JSON-LD definition](https://www.openactive.io/accessibility-support/accessibility-support.jsonld) if the `Accept` header contains `application/ld+json`).

Please raise requests for content or issues related to this controlled vocabulary via [GitHub](https://github.com/openactive/accessibility-support/issues). 

## Example use

The example below illustrates an `"accessibilitySupport"` property for an `Event` that supports all defined accessibility groups.

```json
"accessibilitySupport": [
  {
    "type": "Concept",
    "id": "https://openactive.io/accessibility-support#1393f2dc-3fcc-4be9-a99f-f1e51f5ad277",
    "prefLabel": "Visual impairment",
    "inScheme": "https://openactive.io/accessibility-support"
  },
  {
    "type": "Concept",
    "id": "https://openactive.io/accessibility-support#2bfb7228-5969-4927-8435-38b5005a8771",
    "prefLabel": "Hearing impairment",
    "inScheme": "https://openactive.io/accessibility-support"
  },
  {
    "type": "Concept",
    "id": "https://openactive.io/accessibility-support#dd026873-6713-4ea1-af5a-08901f651d98",
    "prefLabel": "Physical impairment",
    "inScheme": "https://openactive.io/accessibility-support"
  },
  {
    "type": "Concept",
    "id": "https://openactive.io/accessibility-support#67902468-fd49-4238-8650-20a22d7f0e40",
    "prefLabel": "Learning impairment",
    "inScheme": "https://openactive.io/accessibility-support"
  },
  {
    "type": "Concept",
    "id": "https://openactive.io/accessibility-support#40b9b11f-bdd3-4aeb-8984-2ecf74a14c7a",
    "prefLabel": "Mental health issues",
    "inScheme": "https://openactive.io/accessibility-support"
  },
  {
    "type": "Concept",
    "id": "https://openactive.io/accessibility-support#69b689d4-be04-4e6d-be56-4ac72ec82444",
    "prefLabel": "Social or behavioural problems",
    "inScheme": "https://openactive.io/accessibility-support"
  }
]
```

## Concepts in this Vocabulary

- [Visual impairment](https://openactive.io/accessibility-support#1393f2dc-3fcc-4be9-a99f-f1e51f5ad277)
- [Hearing impairment](https://openactive.io/accessibility-support#2bfb7228-5969-4927-8435-38b5005a8771)
- [Physical impairment](https://openactive.io/accessibility-support#dd026873-6713-4ea1-af5a-08901f651d98)
- [Learning impairment](https://openactive.io/accessibility-support#67902468-fd49-4238-8650-20a22d7f0e40)
- [Mental health issues](https://openactive.io/accessibility-support#40b9b11f-bdd3-4aeb-8984-2ecf74a14c7a)
- [Social or behavioural problems](https://openactive.io/accessibility-support#69b689d4-be04-4e6d-be56-4ac72ec82444)


## Licence

The documentation and data in this repository is published under the [Creative Commons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

