Dragonfly Image Overlay/Subtraction Protocol


1. Import both files T0 and T20

![alt text](/Users/sarahlozieh/Dropbox/Open_Lab_Notebook_SarahLozieh/images/ParrotfishPic.jpg)

2. Image spacing 1.44um—--> .00144mm X, Y, Z
3. Layout 4 window view
4. Open both eyes to see both skeletons
5. Click T20 & Use opacity (transparency) to see the overlay in window leveling
6. Manually overlay with: Translate/Rotate—>square icon
7. Use full skeleton window (bottom left) from beginning slices to help with overlay
8. Use slice number and square icon to move the skeletons and overlay them
9. Automatic overlay with: Right click on dataset—>image registration
10. Fixed image T0, mobile image T20
11. Click rotation, apply, wait about 10 mins.
12. Fix the alignment in all 3 windows, including rotating
13. To subtract, make an ROI of T20 dataset
14. Select T20 ROI—> image operations(T0 Image)—>Overwrite—> value 0. Wait about 3 mins
15. Close all eyes except T0 dataset
16. See black, make an ROI of the black image by clicking define range, add to new
17. Label the new ROI “skeleton lost” and observe the volume lost
