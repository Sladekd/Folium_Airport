# Folium_Airport
Jupyter Notebook for creating Folium Map displaying events on aerodrome. This work is to be presented as part of the research at the ICMT 2023 conference. So if you make use of this work, feel free to cite:

J. Vomela and D. Sládek, "Towards Automatic Processing of Georeferenced Information Within Airport Services," 2023 International Conference on Military Technologies (ICMT), Brno, Czech Republic, 2023, pp. 1-6, doi: 10.1109/ICMT58149.2023.10171328.

This notebook provides a basic procedure to create a map in the folium library, retrieve points from the pandas dataframe and display them. Random coordinates are generated around the area of interest for each point, in practice they would probably already be assigned.

![Folium output 27APR 2023](https://github.com/Sladekd/Folium_Airport/blob/main/App_crop.PNG)


The notebook can be further developed 
(1) by creating additional layers via the UDF get_layer
(2) by applying additional plugins
(3) by creating analyses, e.g. calculating distances traveled between events, etc.

This is a universal baseline that can be user modified as needed for a specific application (facility management, airport, agricultural activities in forest, location database...).


If you have any improvements or suggestions, let me know!
