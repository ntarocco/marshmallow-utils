..
    Copyright (C) 2020-2021 CERN.
    Copyright (C) 2020-2021 Northwestern University.

    Marshmallow-Utils is free software; you can redistribute it and/or
    modify it under the terms of the MIT License; see LICENSE file for more
    details.

Changes
=======

Version 0.3.10 (released 2021-04-12)

- Fix TZDateTime field serialization of None values.

Version 0.3.9 (released 2021-04-12)

- Adds TZDateTime field.

Version 0.3.7 (released 2021-03-05)

- Fix issue in SanitizedHTML to allow passing empty lists to remove all tags.

Version 0.3.6 (released 2021-03-04)

- Serializes None ISODates by removing them.

Version 0.3.5 (released 2021-01-25)

- Adds BabelGettextDictField for dumping translation strings from dicts.

Version 0.3.4 (released 2021-01-24)

- Makes Link field a bit easier to use by allowing a string to be passed
  in addition to an URITemplate.

Version 0.3.3 (released 2021-01-20)

- Adds support for automatic scheme detection on identifiers.
- Adds support for identifier sets.

Version 0.3.2 (released 2020-11-10)

- Adds support for GeoJSON geometry object validation.

Version 0.3.1 (released 2020-11-08)

- Adds support for localization of date, time, datetime, EDTF with string
  parsing support.

Version 0.3.0 (released 2020-11-06)

- Adds support for proper localization of EDTF dates.
- Refactored EDTFDateString field.

Version 0.1.5 (released 2020-09-24)

- Fix to expand querystring params correctly

Version 0.1.4 (released 2020-09-17)

- Adds LinksSchema similar to LinksField

Version 0.1.3 (released 2020-09-16)

- Moved additional utilities into the library.

Version 0.1.2 (released 2020-09-16)

- Ported GenFunction and GenMethod

Version 0.1.1 (released 2020-09-11)

- Minor fix to allow a lower ftfy package version than the latest.

Version 0.1.0 (released 2020-09-11)

- Initial public release.
