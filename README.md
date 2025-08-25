# CAP Data Schema

The [Cell Annotation Platform (CAP)](https://celltype.info/) is a community-driven platform for creating, exploring, and storing cell annotations. It provides infrastructure to accumulate, share, and analyze annotation terms with associated molecular signatures to interpret cellular identities, encouraging researchers to converge on consensus nomenclature.

The platform requires `.h5ad` [AnnData](https://anndata.readthedocs.io/en/stable/) files formatted according to a standard schema. The required fields are defined in [CAP-AnnData-Schema](./cap-anndata-schema.md).

## Useful Resources

- CAP [AnnData schema](./cap-anndata-schema.md)
- CAP [documentation](https://celltype.info/docs) - general project documentation
- CAP [upload validator](https://pypi.org/project/cap-upload-validator/) - a Python package that automatically validates whether a provided AnnData file follows the CAP schema.
- CAP [Seurat Converter](https://github.com/cellannotation/capseuratconverter) - an R tool that converts CAP-published files into Seurat v5 objects.
