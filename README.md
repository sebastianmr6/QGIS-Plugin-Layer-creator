# LayersFromField - QGIS Plugin

## Overview

**LayersFromField** is a versatile QGIS plugin that allows users to generate new layers based on field categories from any vector layer, regardless of its geometry or use. This plugin is particularly useful for GIS professionals who need to categorize and separate data into distinct layers efficiently.

## Features

- **Field-Based Layer Creation**: Automatically generate new layers from unique field values.
- **Supports Multiple Formats**: Export to GeoPackage or Shapefile formats.
- **Customizable**: Choose to add the exported layers directly to your QGIS project.

## Export Options

### GeoPackage (GPKG)
- **Single File Format**: Stores multiple layers in a single file.
- **Advanced Features**: Supports complex geometries, SQL queries, and large datasets.
- **Modern and Efficient**: Ideal for projects requiring comprehensive data management.

### Shapefile (SHP)
- **Multiple Files**: Each layer is stored in a set of files (`.shp`, `.shx`, `.dbf`).
- **Legacy Format**: Limited in complexity, but widely compatible with older systems.
- **Simple and Effective**: Best for straightforward projects or when backward compatibility is needed.

## Installation

1. Download the plugin from the repository.
2. Install it through the QGIS Plugin Manager.

## Usage

1. Select the vector layer and field.
2. Choose the output format (GeoPackage or Shapefile).
3. Click "Run" to generate new layers.

## License

This plugin is released under the GNU General Public License v2.0 or later.

## Author

Sebastian Mejia Rios  
Contact: sebastianmr6@hotmail.com