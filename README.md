# EBA - Environment Build Automation

This is a collection of tools to aid creating environments in the Cloud from Visio diagrams 

## Structure
This repo has 2 directories, eba-acloud and eba-visio. Environments are designed in Visio using the stencil in eba-visio/src/VisioStencil.vss, then exported to XML by the export tool in eba-visio/src/VisioExport.vsd. This XML is then passed to the eba-acloud tool.

Please see the readme files in /eba-acloud and /eba-visio for more details.


## Licence

See the LICENCE (/LICENCE) file.

## Documentation

The user guide for the Visio stencil and export tool can be found in the docs folder at ./eba-visio/docs/index.html

The user guide for the eba-acloud tool can be found in the docs folder at ./eba-acloud/docs/index.html
