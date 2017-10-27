### Using Images with Relative Paths in README.md

In GitHub-Flavoured Markdown (GFM), when you want to include an image using its
relative path you do either this:


> This file includes an image directly by its relative path:
>
>     ![description of the image](relative/path/to/image.ext)
>
> ![svg image](assets/readme-images-image-300.svg)
> ![png image](assets/readme-images-image-300.png)

or this:

> This file includes an image indirectly by a reference to its relative path:
>
>     ![description of the image][asset-1]
>
> Where somewhere in the file (not sure if the order is a factor):
>
>     [asset-1]: relative/path/to/image.ext
>
> ![svg image][asset-1-svg]
> ![png image][asset-1-png]
>
> [asset-1-svg]: assets/readme-images-image-300.svg
> [asset-1-png]: assets/readme-images-image-300.png



At the moment, both Yarn & NPM
