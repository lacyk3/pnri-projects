# pnri-projects

This repository houses projects completed in collaboration with the [Dudley lab](https://www.pnri.org/research/labs/dudley-lab/) at Pacific Northwest Research Institute.

![Patches of yeast cells display diverse phenotypes.](yeastpic.png)

The ability to automatically quantify phenotypic traits of microbial communities from images in an accurate and robust manner is crucial to advancing high-throughput genetic studies. Using tools from the python scientific stack, we have developed a flexible, free pipeline to automate the extraction of meaningful quantitative features characterizing colony size, color, morphology, and more from plate images. Visit the [github page for PyPl8](https://github.com/lacyk3/PyPl8) to explore a comprehensive package for utilizing these tools. You can also download PyPl8 from [PyPI](https://pypi.org/project/PyPl8/). 

##

* [**Funnel Cross Project**](https://github.com/lacyk3/pnri-projects/tree/Image-Analysis-Demos/Funnel%20Cross%20Project): This repository contains the jupyter notebooks used to process phenotype images for  <`link coming soon`>. 
  - `RenameImages.ipynb` was used to rename phenotype images by reading the bar code present in each image and matching it to a human-readable plate name saved in a csv master list.
  - `ExtractValues.ipynb` was used to automatically crop images to the region of interest, segment patches from the background, and extract growth data: the area in pixels and the sum of the intensities of all pixels within the colony. 

## Contributors

* [@lacyk3](https://github.com/lacyk3) 📖

## Contact

If you want to contact me you can reach me at <lacyk3@uw.edu>.

## License
<!--- If you're not sure which open license to use see https://choosealicense.com/--->

This project is available under the following license: [<GNU General Public License, version 2>](<http://www.gnu.org/licenses/old-licenses/gpl-2.0.html>). 
