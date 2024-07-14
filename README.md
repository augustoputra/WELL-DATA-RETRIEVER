This is a program specifically designed for well data retriever in Handil Field, the area where I am working as a geologist. I am writing this code using Google Collab The purpose of this program is to retrieve: 1.Well Head Location coordinate (X, Y)
2.Cluster / name on where the well head is located (the location of the well head in this oil filed, can be grouped based on its location. This is usually known as the well head cluster.)
3. Departure distance (euclidean distance between the well head location and the end of the well in the subsurface)
4. Highest inclination of the well
5.Highest DLS of the well
6. The impact point position of the well when intersecting the surface of marker R29-1 (X, Y, Z)

What we need to do to run the program:
Export the well data from Petrel by right-clicking the wells on the input pane, selecting "Export," then choosing "Export as well path/deviation."
On google collab upload widget, create folder : "wells"
and then put the exported files there.

also don't forget to upload the surface R29-1. as previously mentioned above that we'd like to get the XYZ coordinate of the well when intersecting the R29-1 below in subsurface.

Result example:
![image](https://github.com/user-attachments/assets/a3e1d961-a972-42b0-ad36-cc8f92cebfa6)
