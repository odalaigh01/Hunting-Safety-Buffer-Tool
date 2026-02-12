# Hunting-Safety-Buffer-Tool
The Hunting Safety Buffer Tool is a web-based interactive mapping application designed to help hunters, landowners, and land managers visualize and plan safe hunting zones by automatically generating and merging safety buffers around structures.

Main Features & Workflow

Upload Property Boundary
Load your parcel or hunting property as a zipped shapefile (.zip containing .shp, .shx, .dbf, and ideally .prj). The tool automatically zooms to your land and creates a small search buffer around it.
Incorporate Structures & Trails
Fetch public GIS data — one-click buttons pull building footprints from USA Structures dataset and trails from public trail services (within a search radius around your property).
Manual addition — toggle "Add Manual Points" mode to click and place additional structures (barns, cabins, sheds, residences, camps, etc.) not captured in public data.

Generate Safety Buffers
Set a custom buffer distance in feet (defaults to 450 ft — ≈150 yards — matching many state safety zone laws for firearms near occupied buildings/dwellings).
The tool buffers every structure point/polygon and merges/unions overlapping zones into a single combined safety area (red semi-transparent fill on the map).
This merged zone clearly shows where hunting with firearms may be restricted or require landowner permission.

Visual Layers on Dark Imagery Basemap
Orange → property boundary
Blue → fetched building footprints
Yellow dots → manually added structures
Green dashed → trails
Red → final merged safety buffer zones
Draggable map legend for clear interpretation

Export Options
JPG map snapshot — exports the current map view (centered & locked on your property for clean presentation) — useful for sharing with hunting party, neighbors, or posting on property.
GeoJSON of the merged buffer — for use in other GIS software, GPS devices, or record-keeping.
