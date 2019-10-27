# HospitalRun design ![Size](https://img.shields.io/github/repo-size/hospitalrun/design)

## Structure

What you can find in this repo:

- [Social media avatar and covers](/social)
- [Logo files](/logo)
  - .png, .jpg, .svg
  - Native logo artwork files
- [Common images](/images)
- [UI](/ui)
  - color palette (scss, png, svg)
- [All assets of v1.0.0-beta](/archive)
  - avatar
  - beta
  - email
  - images
- Marketing
  - [Stickers](/marketing/stickers) (157mmx30 mm and 47mmx50mm) print with [stickerrmule](https://www.stickermule.com/it/unlock?ref_id=0665902701&utm_medium=link&utm_source=invite)
  - Slides
- UI design files (Sketch file, mocks of various screens)

What we plan to add:

- New frontend mockups
- New HR marketing photos
- Brand guide
- HospitalRun frontend CSS styleguide
- HospitalRun frontend pattern library

## Contributing

Contributions are always welcome. If you’re serious about contributing, we also encourage you to [join our Slack](https://hospitalrun-slackin.herokuapp.com/), where the majority of the project communication happens.

**Read carefully before committing!**

This repo use Git Large File Storage (LFS) that replaces large files with text pointers inside Git, while storing the file contents on a remote server like GitHub.com.

Currently, the associated files are:

- psd
- ai
- sketch

If you add a new file format, you need to associate it with a large file in this repository. You need Git LFS, if you don't have it, [follow this guide](https://help.github.com/en/articles/installing-git-large-file-storage).
To associate a file type in your repository with Git LFS, enter git lfs track followed by the name of the file extension you want to automatically upload to Git LFS.

For example, to associate a .psd file, enter the following command:

```
$ git lfs track "*.psd"
> Adding path *.psd
```

Every file type you want to associate with Git LFS will need to be added with git lfs track. This command amends your repository's `.gitattributes` file and associates large files with Git LFS.

[Further reading](https://help.github.com/en/articles/configuring-git-large-file-storage)

## Branding

Default logo:

![logo-on-white](logo/logo-on-white.png)

Logo on navy bg:

![logo-on-white](logo/logowh-on-blue.png)

Logo with transparent bg:

![logo-on-white](logo/logo-on-transparent.png)

### Color palette

[Here](https://coolors.co/1abc9c-009b9e-273647-011627-fdfffc) you can find an initial reference of the official HospitalRun colours.

![color palette](https://github.com/HospitalRun/design/blob/master/ui/color%20palette/palette.png)

Hexadecimal

```
#1abc9c
#009b9e
#273647
#011627
#fdfffc
```

SCSS

```scss
/* HSL */
$color1: hsla(168%, 76%, 42%, 1);
$color2: hsla(181%, 100%, 31%, 1);
$color3: hsla(212%, 29%, 22%, 1);
$color4: hsla(207%, 95%, 8%, 1);
$color5: hsla(100%, 100%, 99%, 1);

/* RGB */
$color1: rgba(26, 188, 156, 1);
$color2: rgba(0, 155, 158, 1);
$color3: rgba(39, 54, 71, 1);
$color4: rgba(1, 22, 39, 1);
$color5: rgba(253, 255, 252, 1);
```
