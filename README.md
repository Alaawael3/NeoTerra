# NeoTerra: An Interactive Geospatial AI Agent

NeoTerra is an intelligent and interactive AI agent built to assist in satellite imagery analysis. It combines conversational AI with advanced geospatial processing tools, empowering users to query, preprocess, segment, and visualize remote sensing data — all in one seamless platform.

---

## Overview

NeoTerra bridges the gap between AI-driven dialogue systems and geospatial data processing. By integrating satellite data pipelines with natural language understanding, it enables researchers, analysts, and environmental experts to interact with geospatial tools as naturally as chatting with an assistant.

The platform leverages cutting-edge deep learning models and geospatial libraries to provide an intuitive interface for Earth observation workflows, democratizing access to sophisticated satellite imagery analysis.

---

## Core Features

### 💬 Interactive Chatbot
Conversational interface for querying and executing geospatial operations with natural language access to advanced Earth observation workflows. Users can describe their analysis needs in plain English and let NeoTerra handle the technical implementation.

### 🌊 Oil Spill Segmentation
Automatic detection and segmentation of oil spills in satellite imagery using advanced deep learning models. The system intelligently differentiates between oil, look-alikes (such as natural seeps or weathered surface features), and background water regions.

### 🛰️ Satellite Metadata Extraction
Easily extract essential geospatial metadata from satellite imagery, including:
- Image dimensions and resolution
- Coordinate Reference System (CRS) information
- Geospatial bounds and geographic extent
- Temporal and sensor-specific metadata

### ⚙️ Image Preprocessing
- Normalization and scaling for consistent analysis
- Histogram equalization for contrast enhancement
- Radiometric and geometric corrections
- Band arithmetic and spectral indexing

### ☁️ Cloud Handling
- Advanced cloud segmentation and detection from optical imagery
- Intelligent cloud masking for clearer analysis
- Cloud removal techniques to generate cloud-free composite imagery
- Preparation of analysis-ready data products

### 📊 Visualization Tools
- Quick and interactive plotting of TIFF and georeferenced images
- Multi-band visualization with customizable color schemes
- Overlay model predictions and segmentation masks on source imagery
- Interactive maps with zoom and pan capabilities

### 🌍 Image Download & Integration
- Fetch remote satellite imagery directly from public data sources
- Seamless preprocessing and ingestion workflows
- Integration with major satellite data providers
- Automated pipeline for end-to-end analysis

---

## Tech Stack

- **Languages & Frameworks**: Python, TensorFlow, PyTorch
- **Geospatial Libraries**: GDAL, Rasterio, GeoPandas, Shapely
- **Image Processing**: OpenCV, Pillow, SciPy
- **Data Science**: NumPy, Pandas, Scikit-learn
- **Visualization**: Matplotlib, Folium, Plotly
- **AI & ML**: Deep Learning models (U-Net, ResNet), transformer-based architectures
- **Deployment**: Docker, FastAPI (optional for API endpoints)

**Core Domains**: Geospatial AI · Deep Learning · Remote Sensing · Interactive Agents

---

## Supported Data Formats

NeoTerra seamlessly handles various geospatial data formats:
- GeoTIFF (.tif, .tiff)
- NetCDF (.nc)
- HDF5 (.h5)
- Shapefile (.shp)
- GeoJSON (.geojson)
- Raster formats (JPEG, PNG, etc.)

---

## Use Cases

**Environmental Monitoring**: Track oil spills, detect deforestation, monitor glacial retreat, and identify wetland changes in near real-time.

**Cloud-Free Image Generation**: Generate high-quality, analysis-ready remote sensing datasets by removing cloud cover and atmospheric artifacts for improved scientific accuracy.

**Smart Metadata Extraction**: Automate geospatial metadata extraction for streamlined GIS workflows, reducing manual preprocessing time and improving data quality.

**Disaster Response**: Rapidly analyze satellite imagery following natural disasters to assess damage and guide emergency response efforts.

**Agricultural Analysis**: Monitor crop health, detect crop stress, and optimize resource allocation in precision agriculture applications.

**Urban Planning**: Track urban expansion, infrastructure development, and land-use changes over time for evidence-based urban planning decisions.

---

## Workflow Architecture

The NeoTerra workflow consists of the following integrated stages:

1. **Data Ingestion**: Retrieve and load satellite imagery from cloud or local sources
2. **Preprocessing**: Normalize, scale, and prepare data for analysis
3. **Feature Extraction**: Compute spectral indices and relevant geospatial features
4. **Model Inference**: Apply trained deep learning models for segmentation and classification
5. **Postprocessing**: Refine predictions, filter noise, and generate final outputs
6. **Visualization**: Create interactive maps and publication-ready visualizations
7. **Export**: Save results in standard geospatial formats (GeoTIFF, Shapefile, etc.)

---

## Media & Resources

| Type | Link | Description |
|------|------|-------------|
| 💼 Demo Video | [LinkedIn](https://www.linkedin.com/posts/alaa-wael-boghdady-338bb02a9_finally-i-can-introduce-neoterra-%D8%A8%D8%B9%D8%AF-activity-7381430823411040256-nyK9?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEpk0NwB6QWIAaxIX53R0WLZK11UrsCguaM) | A short demonstration of NeoTerra's capabilities and interactive workflows |
| 📑 Presentation Slides | [Presentation](https://drive.google.com/file/d/1uIuWwApFXvblsUI22IlaiBA6hLg8CUrq/view?usp=drive_link) | Detailed presentation covering motivation, architecture, and outcomes |
| 📖 Documentation | [View Docs](NeoTerra_paper.pdf) | Complete documentation |

---

## 👥 Authors & Contributors

**Lead Developers**: Alaa Wael and the NeoTerra AI Team

**Affiliation**: Cairo University, Egypt

**Acknowledgments**: We extend our gratitude to all contributors and the open-source geospatial community for their invaluable support and resources.

---

Together, we're advancing geospatial AI for a better understanding of our planet.
