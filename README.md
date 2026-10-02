# AutoMemo vehicle generations catalog

This public, data-only repository contains vehicle make, model, and generation suggestions that AutoMemo can use. It does not contain the AutoMemo application source code.

The source data is automatically compiled/curated and can be incomplete or inaccurate for particular markets. AutoMemo keeps manual entry available for every make and model; a suggestion is never required to save a vehicle.

## Data

- `data/vehicle-generations.json` contains 59 makes and 296 models from the upstream dataset.
- It retains source generation names and year ranges when supplied. The source does not provide generation details for every model.
- The file was reshaped to one JSON document and includes only make, model, and generation fields.

## Attribution and license

The data is derived from [vehicle-makes-models](https://github.com/gor3a/vehicle-makes-models), which credits [Autoevolution](https://www.autoevolution.com/) as its upstream source for make/model/generation facts. Changes were made when the per-make source files were combined and reshaped.

The database in `data/` is offered under the [Open Database License 1.0 (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/). See [LICENSE-DATA.md](LICENSE-DATA.md). If you redistribute or adapt this database, keep the attribution and make the adapted database publicly available under ODbL.
