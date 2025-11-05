# doc.md

## Add-ons install 

### SMPL-X Add-ons 

smpl-x add-ons: [https://smpl-x.is.tue.mpg.de/](https://smpl-x.is.tue.mpg.de/)

It is used for creating the standard SMPL-X model with bones in blender.


### Rokoko Add-ons 

rokoko add-ons: [https://github.com/Rokoko/rokoko-studio-live-blender](https://github.com/Rokoko/rokoko-studio-live-blender)

It is used for retargeting the BVH motion into standard SMPL-X model.

### SMPL-X Animation Exporter Add-ons 

You can download form github and get the zipped file of whole repository.

```
git clone https://github.com/Beat-in-our-hearts/Blender-SMPL-X-Animation-Exporter.git
```

### Install all Add-ons

1. Open Blender
2. Go to `Edit` → `Preferences` → `Add-ons`
3. Click the  `Install from Disk` and select the zipped file.

## Usage

1. Go to `File` import the bvh file.
2. Go to the sidebar `SMPL-X` create the 3d human object.
3. Go to the sidebar `Rokoko`, select bvh and smpl-x, bulid bone list, than retargeting.
4. Go to the `SMPL-X` and put the first frame of smpl-x body on ground.
5. Go to the sidebar `SMPL-X Animation Exporter`, select smpl-x, antodetect the frame nums or reedit, export the motion.