# CHEK Validation Info Viewer

This is a lightweight Flask-based web application for uploading, validating, and visualizing [CityJSON](https://www.cityjson.org/) files. It leverages the [CHEK Validator](https://defs-dev.opengis.net/chek-validator) to validate CityJSON data against building profiles (SHACL) and converts the data to a GLB format for 3D visualization.

## 🚀 Features

- Validates CityJSON against standard or custom SHACL profiles via the CHEK validator backend.
- Fetches and parses the validation results for a user-friendly representation.
- Visualizes the validation results on the 3D model view by highlighting

## 🛠️ Tech Stack

- Python 3
- Flask
- [cjio](https://github.com/cityjson/cjio) for CityJSON parsing and GLB export
- HTML (frontend in `templates/index.html`)
- [CHEK Validator API](https://defs-dev.opengis.net/chek-validator)

## 📦 Installation

### Prerequisites

- Python 3.8+
- pip

### Clone & Install Dependencies

```bash
git clone https://github.com/alpertungakin/chek-validation_info_view.git
cd chek-validation_info_view
pip install -r requirements.txt
