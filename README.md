# G-ratio automation
Computer Vision application of g-ratio measurement 

### Description
g-ratio parameter takes a cross section image of a nerve (obtained by Electron Microscopy) and measures the diameter of single fibers (axons) with and without the insulating layer (called Myelin). This ratio indicates the velocity in which electrical signals travel in the fibers and intern reflect on the properties and health of the nerve.

###### Diagram of nerve cell
![alt text](/github_images/diagram0.PNG)

Currently, g-ratio quantification is done manually in Leah Amit lab, a task which is tedious and extremely time-consuming. Using Computer Vision, this software is able to detect the outline of the myelin layer and calculate the g-ratio automatically after setting a single threshold parameter for each image. This allows to collect data on a much larger scale in just a few minutes.

#
### Login Page
![alt text](/github_images/login_page.PNG)

#
### Load images
![alt text](/github_images/upload_images.PNG)

#
### Image output
![alt text](/github_images/result.PNG)
![alt text](/github_images/g-ratio.PNG)

#
### Final result
The excel table exported includes details on every insulated fiber that was detected. Each row is a different fiber, consisting of the inner and outer outline. Columns include the following details for each fiber: Inner and outer circle area, Inner and outer circle radius, axon diameter, genes (group it belongs to - WT or KO) and finally g-ratio.

After going through all the images, a scatter plot will pop up: comparing 2 groups: “WT” (untreated) in red, and “KO” (treated) in blue. This is the classic plot used in papers by scientists studying electrical current in nerve cells.
![alt text](/github_images/diagram3.PNG)


## Authors
* [Itay Nave] Computer Vision & Embedded Enginner
* [Amit Leah] Msc student biological researcher
