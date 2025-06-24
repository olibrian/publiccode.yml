.. _italian-sections:

Switzerland
-----------

All the keys listed below are specific for Switzerland and, as such, they must
be inserted in a section named with the ``ch`` code. Every Country is specified
using a two letters *country code* following the ISO 3166-1 alpha-2 standard.


Key ``countryExtensionVersion``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Type: string
- Presence: mandatory
- Value: ``"1.0"``


This key **MUST** always be set to ``1.0``.

Key ``applicableLegislation``
~~~~~~~~~~~~~~~~

- Type: string
- Presence: optional

Applicable legal framework, particularly for internally developed software. The key is optional, but highly recommended.
