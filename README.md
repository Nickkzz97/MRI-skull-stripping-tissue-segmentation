# MRI-skull-stripping-tissue-segmentation
MRI skull stripping and tissue segmentation using conventional methods and different  available tools

1. Data set references

    https://ida.loni.usc.edu/

    https://drive.google.com/drive/folders/1D4Oih54PM8fMduoDtg_AI1wBpPRgxW4w?usp=sharing 

    https://drive.google.com/drive/folders/15Z5vt7b1fXXepfDeU7ZduT8-e1eHXNdQ?usp=sharing 

2. Basic skull stripping using conventional image processing algorithm
    i) Using Otsu Thresholding and connected component analysis
    ii) Using Active Contour
3. Segment Hemisphere: Using Hough Transform
4. Grouping of tissue (wm, gm, ventricles, csf, …) Using Traditional Image Processing Algorithms:
    i) INTENSITY BASED METHODS:
        a) THRESHOLDING TECHNIQUE(LOCAL,GLOBAL,ADAPTIVE)(Multi Otsu Thresholding)
    ii) CLUSTERING BASED SEGMENTATION:
        a) K-means clustering
        b) Fuzzy C-means Clustering
        c) Gaussian Mixture Model
        d) Watershed Segmentation
    iii) Advanced Grouping of Tissues (wm, gm, ventricles, csf, …) with 
        a) Free Surfer : https://www.opensourceimaging.org/project/freesurfer/
        b) Robex : https://www.nitrc.org/projects/robex
        c) ANTPY : https://github.com/ntustison/KapowskiChronicles
    iv) Comparison by evaluation metrics : Hausdorff distance, DICE, JC, Accuracy
     
