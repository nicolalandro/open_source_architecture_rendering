# open_source_architecture_rendering
That include a toy example made for studiing how to create architecture render with opensosurce software.
(The blender project can be finded into [realeases](https://github.com/nicolalandro/open_source_architecture_rendering/releases/tag/0.1) because of it is larger than 20 MB)

The working pipeline:
* [SweetHome3D](www.sweethome3d.com/it/download.jsp): create house and export .obj
* [fSpy](https://fspy.io/): analize the prospective of an image and export a camera
* [Blender](https://www.blender.org/) (with [fspy plugin](https://github.com/stuffmatic/fSpy-Blender)): import camera, place object and render with alpha background
* [GIMP](https://www.gimp.org/): mount images togheder

![](casaabbusiva_gimp.png)
