### **Instructor's Script: Planet API 101 Workshop**

---

### **1. Introduction to Planet Products**
- **Goal**: Provide an overview of the products offered by Planet, including Planetscope, SkySat Archive, and SkySat Tasking.

#### **Instructor Notes**:
- **Highlight Key Products**:
    - **Planetscope**: Daily imaging capabilities with medium-resolution imagery.
    - **SkySat Archive**: High-resolution satellite imagery; archive data covers several years.
    - **SkySat Tasking**: Tasked satellite imagery for specific, high-priority locations.
  
- **Use Cases**: Share a few real-world examples where these products are used for agricultural monitoring, disaster response, or urban planning.

#### **Activity**: Open the **Planet Explorer** to show a live example of product coverage in a specific area.
- **Tip**: Use **San Francisco** or another well-known region to show Planetscope imagery.
- **Additional Information**: Mention that SkySat tasking is used when users need customized, high-resolution data for dynamic events.

---

### **2. Introduction to Planet Explorer (Searching, Previewing, and Ordering Imagery)**

- **Goal**: Show participants how to use the Planet Explorer GUI to search, preview, and order imagery.

#### **Instructor Notes**:
- **Demo Features**:
    - Walk through searching by area of interest (AOI) using bounding boxes or polygons.
    - Show participants how to apply filters like date range, cloud cover, and product types.
    - Demonstrate how to preview imagery in Planet Explorer.
    - Explain how imagery ordering works, especially for new users unfamiliar with data access.

- **Additional Highlights**:
    - Emphasize the **cloud coverage filter** to help participants narrow down clear images.
    - Mention the **“Order to Download”** feature for immediate access once the imagery is processed.

#### **Activity**:
- **Live Search Exercise**: Ask participants to choose an AOI (e.g., their hometown or a region of interest) and guide them through the search, preview, and ordering steps.
  
---

### **3. Introduction to the Basemaps Viewer and Using XYZ Tiles**
  
- **Goal**: Explain the utility of Planet’s basemap services and how to use them in external platforms through XYZ tiles.

#### **Instructor Notes**:
- **Basemaps Overview**: Basemaps are seamless mosaics built from daily satellite imagery, ideal for long-term monitoring.
  
- **Demonstrate XYZ Tile Usage**:
    - Explain what **XYZ tiles** are and how they integrate into web apps or GIS platforms.
    - Show how to obtain and use XYZ tile URLs for projects like QGIS or Leaflet-based web maps.

#### **Activity**:
- **Hands-On with QGIS**: Show how to load Planet’s basemaps using XYZ tiles into QGIS or demonstrate how it can be embedded in a web map using **Leaflet.js** or **Mapbox**.

---

### **4. Introduction to Planet API and SDK Using Python Notebooks (Lake Lagunita Exercise)**

- **Goal**: Introduce the Planet API and SDK for programmatic access to satellite data. Guide participants through the **Lake Lagunita** Python Notebook to showcase practical usage.

#### **Instructor Notes**:
- **API and SDK Basics**:
    - Explain what the Planet API is: a tool that allows users to search, download, and analyze satellite imagery programmatically.
    - Cover SDK basics, including authentication and how the API integrates with Python.

#### **Lake Lagunita Notebook Exercise**:
- **Setup**: Ensure participants have their API keys and Python environments ready.
- Walk through the **Lake Lagunita** example notebook:
    - **Querying the API**: Guide users to query Planetscope imagery over Lake Lagunita, showing how to filter results based on cloud cover and date range.
    - **Downloading Data**: Show participants how to download imagery metadata and actual data.
    - **Visualization**: Use Matplotlib to visualize the imagery and discuss how to analyze different spectral bands.

- **Additional Highlights**:
    - Discuss filtering by AOI, cloud coverage, and date range.
    - Emphasize how to use Jupyter Notebooks for iterative analysis.

#### **Activity**:
- **Notebook Hands-On**: Have participants run the Lake Lagunita notebook on their local machines. Encourage them to tweak the AOI and date ranges to observe different imagery outputs.

---

### **5. Overview of Support Resources**
  
- **Goal**: Provide a guide to available support and resources for continued learning.

#### **Instructor Notes**:
- **Planet University**: Highlight the extensive resources available through Planet University for self-paced learning.
- **Stanford Geospatial Center Support**: Mention any specific support channels or documentation available via the SGC.
- **Planet Community Forum**: Encourage participants to join the **Planet Community** for peer support and networking.
  
#### **Closing Remarks**:
- **Tip**: Remind participants to explore further using Planet’s API documentation and the Python SDK for custom integrations.
- **Encouragement**: Highlight the flexibility of Planet’s products and APIs for a wide range of applications in environmental monitoring, urban planning, and more.

