# epiphyte reference photographs

Reference photographs of 978 Oregon plant species, up to three per species,
taken from different individual plants. They are published here so the epiphyte
app can download them on request. The app's code is not in this repository.

The files are on the [`reference-photos-v1`](../../releases/tag/reference-photos-v1) release:

| file | bytes | sha256 |
|---|---|---|
| `thumbs_hi.jpgs` | 62,003,297 | `8b0a31029c1a918f4a60429ddfc98663e278ab43be25d07603117e774cb17b5f` |
| `thumbs_hi.json` | 57,121 | `cfaf0e0afd558e492d617785c1a5f5d69628fe6c3e0767fb80946e446bbe4a82` |

`thumbs_hi.jpgs` is the 256 px JPEGs, concatenated. `thumbs_hi.json` is
`{"side": 256, "offsets": [[[offset, length], ...], ...]}`, with one list per
species in the app's species order.

## Licences and attribution

The 2,934 photographs are iNaturalist observations retrieved through GBIF, and
each was chosen because its licence permits redistribution:

| licence | photographs |
|---|---|
| [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | 1,894 |
| [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) | 1,040 |

[`ATTRIBUTION.csv`](ATTRIBUTION.csv) has one row per photograph, in the order the
photographs appear in the pack (`species_index`, `photo`). Each row gives the
species, the licence, the photographer (`recorded_by`), the original image URL
and the GBIF occurrence. **The images have been modified**: each was
centre-cropped to a square, resized to 256 px, and re-encoded as JPEG.
The photographs belong to the people listed in that file, and none of them
endorse the app.
