# Holidays
A new evaluation data set of pairwise image comparisons.

SUMMARY 
=============================================

Holidays data set is one of the evaluation data sets in my newly published research paper [1]. It contains 10 users' 6682 pairwise comparisons on 260 different scenery images sampled from the INRIA Holidays image set [2]. 

[1] Jun Chen, Chaokun Wang, Jianmin Wang, Xiang Ying, and Xuecheng Wang. 2017. Learning the Personalized Intransitive Preferences of Images. In IEEE Transactions on Image Processing. 26(9):4139-4153.

[2] Hervé Jégou, Matthijs Douze, and Cordelia Schmid. 2008. Hamming Embedding and Weak geometry consistency for large scale image search. In ECCV. 304–317.



STATS
=============================================

    10		users
    260		images
    6682	pairwise comparisons


FILE FORMAT
=============================================

user#.txt (#=1,2,...,10) - Each file corresponds to the records of a unique participant. Each line in these files is a pairwise comparison in the format "img1,img2" indicating this user prefers img1 (the left) to img2 (the right).


ImageID.txt - This file shows the matching between the image ID in user#.txt and the corresponding image file name in the original image set [2].
 

REFERENCE 
=============================================

When using this dataset, you should cite:

@ARTICLE{JunChen:tip2017,
	AUTHOR = "Jun Chen and Chaokun Wang and Jianmin Wang and Xiang Ying and Xuecheng Wang",
	TITLE = "Learning the Personalized Intransitive Preferences of Images",
	JOURNAL = "IEEE Transactions on Image Processing",
	VOLUME = {26},
	NUMBER = {9},
	PAGES = {4139--4153},
	YEAR = {2017}	}

