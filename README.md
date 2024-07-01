# spineA-SDF

We propose a framework used in the operating room (OR) forecasting the upright spine geometry at the first visit following surgery in idiopathic scoliosis patients. The approach first creates a 3D model of the spine while the patient is on the operating table. For this, multiview Transformers that combine images from different viewpoints are used to generate the intra-operative pose. The post-operative upright shape is predicted on-the-fly using implicit neural fields, which are trained from geometries at different time points and conditioned with surgical parameters. A Signed Distance Function for shape constellations is used to handle the variability in spine appearance, capturing in a disentangled latent space the articulation vectors, with separate encoding vectors representing both articulation and shape parameters. A regularization criterion enables smooth outputs by using a pre-trained group-wise trajectory of spine transformations. 

## Description

This is the code for spineA-SDF: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction by Sylvain Thibeauly, Stefan Parent and Samuel Kadoury.

<p align="center">
  <img src="logo.png" width="350" title="hover text">
</p>


## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
