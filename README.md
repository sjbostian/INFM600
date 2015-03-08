# INFM600
This is the dataset created for the INFM600 Information Organization assignment

-------
Version
-------

Version 1.0 (March 2015)

-----------
Description
-----------

	This dataset is a derivative of the MovieLens + IMDb/Rotten Tomatoes dataset 
	(http://grouplens.org/datasets/hetrec-2011/) created by Iván Cantador with the 
	collaboration of Alejandro Bellogín and Ignacio Fernández-Tobías of the Information 
	Retrieval group at Universidad Autonoma de Madrid for the HetRec'11 workshop. Their 
	original dataset links the movies of MovieLens dataset, published by GroupLens 
	research group (http://www.grouplens.org), with their corresponding web pages at the
    Internet Movie Database (IMDb, http://www.imdb.com) and Rotten Tomatoes movie review 
    systems (http://www.rottentomatoes.com).

    From the original dataset, only information necessary to answer the question of 
    which actors made the most films in each genre for a particular year or range of 
    years has been maintained. This includes genres, actors and release years for each 
    movie.
    
    The dataset is released in the framework of INFM 600, Information Environments, Spring 
    2015, at the University of Maryland iSchool, http://ischool.umd.edu/mim.

---------------
Data statistics
---------------

	10,197 unique movies
	98 unique release years from 1903 to 2011
	95,321 unique actors
	20 unique genres
	
-----
Files
-----

	* movies_actors_new_subset.xlsx
		This file contains the main actors IDs, their related film IDs and display names 
		(some display names were not unique).
	
	* movies_genres_new_subset.xlsx
		This file contains the genres and the related film IDs.
	
 	* movies_years_new_subset.xlsx
		This file contains the release years and the related film IDs.

-----------
Data format
-----------

   The data is formatted one entry per line as follows:
   
	* movies_actors_new_subset.xlsx
		movieID		actorID		actorName
	
	* movies_genres_new_subset.xlsx
		movieID		genre
	
 	* movies_years_new_subset.xlsx
		movieID		year

------- 
License
-------

	The data in the INFM600 repository is distributed under a Creative Commons 
	Attribution-NonCommercial-ShareAlike 4.0 International License (see 
	http://creativecommons.org/licenses/by-nc-sa/4.0/).
   
   	The data contained in the original hetrec2011-movielens-2k.zip was distributed with 
   	permission of GroupLens research group.
   
   	The data is made available for non-commercial use. Those interested in using the data 
   	in a commercial context should contact GroupLens members: 
   	http://www.grouplens.org/contact

----------------
Acknowledgements
----------------

   We thank the GroupLens research group at the University of Minnesota 
   (http://www.grouplens.org) for hosting and allowing use of the MovieLens10M dataset 
   in the master dataset and Iván Cantador, Alejandro Bellogín and Ignacio 
   Fernández-Tobías and the Information Retrieval group at Universidad Autonoma de Madrid 
   (http://ir.ii.uam.es) for creating and releasing the master data set.

----------
References
----------

   When using this dataset you should cite:
   
      - the original Movielens dataset from GroupLens research group, http://www.grouplens.org
      
      - IMDb website, http://www.imdb.com
      
      - Rotten Tomatoes website, http://www.rottentomatoes.com
      
      - the HetRec'11 workshop as follows:

   @inproceedings{Cantador:RecSys2011,
      author = {Cantador, Iv\'{a}n and Brusilovsky, Peter and Kuflik, Tsvi},
      title = {2nd Workshop on Information Heterogeneity and Fusion in Recommender Systems (HetRec 2011)},
      booktitle = {Proceedings of the 5th ACM conference on Recommender systems},
      series = {RecSys 2011},
      year = {2011},
      location = {Chicago, IL, USA},
      publisher = {ACM},
      address = {New York, NY, USA},
      keywords = {information heterogeneity, information integration, recommender systems},
   } 

-------
Credits
-------

   This dataset was built by Anuj Sharma and Sandy Bostian.
