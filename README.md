# Dataset Name Mappings for daten.berlin.de

In August 2024, Berlin's open data portal https://daten.berlin.de received a major overhaul.
As a result, the filenames of many datasets slightly changed.
This repository contains mappings from the old dataset names to the new ones.
The mappings are defined in a simple CSV file with two columns `old_name` and `new_name`:

```csv
old_name,new_name
20-grüne-hauptwege-wanderkarte-wfs,20-grune-hauptwege-wanderkarte-wfs-99a22ff0
20-grüne-hauptwege-wanderkarte-wms,20-grune-hauptwege-wanderkarte-wms-1f028343
3d-gebäudemodelle-im-level-detail-1-lod-1-atom,3d-gebaudemodelle-im-level-of-detail-1-lod-1-atom-e2a1e24e
3d-gebäudemodelle-im-level-detail-2-lod-2-atom,3d-gebaudemodelle-im-level-of-detail-2-lod-2-atom-3c7c49af
3d-gebäudemodelle-im-level-detail-2-lod-2-wms,3d-gebaudemodelle-im-level-of-detail-2-lod-2-wms-f2a8a483
3-eur-ticket,3eurticket
...
```

The entries in the `new_name` column are used both to get to the dataset page (by prefixing with https://daten.berlin.de/datensaetze/) and as ids in the underlying CKAN instance.
Previously, the name in the dataset page URL and the internal CKAN id were often different.

## License

[berlin_dataset_name_mapping](https://github.com/berlinonline/berlin_dataset_name_mapping) is marked with [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

2024, Knud Möller, [BerlinOnline GmbH](https://www.berlinonline.net/)

Last changed: 2024-11-27