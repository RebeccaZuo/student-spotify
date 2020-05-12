# cs0320 Term Project 2020

**Team Members:** 
Rebecca Zuo, Rachel Souza, Katherine Kwan, Ambika Miglani

**My Role**
Created the K-cluster algorithm in python for the 11 attributes we chose for each song. Imported those clusters to Java, and applied a kd-tree so that the closest songs could be found. Created database queeries, to get song and user data. As a result, created two functions 1) get song recommendations for a new user based on a song they selected 2) get song recommendations for an existing user, based on the songs that they favorited in their user library. 

I also turned the features that we wanted in to tasks, and divided the labor. 

Problem to solve: 
Student’s currently have little exposure to the student audio(music, podcasts, dj set) creators on campus. Furthermore, student creators don’t have a platform to share their work with other students in a way that will garner their work the attention that they deserve. 

Algorithm: We were thinking of implementing the Collaborative Filtering algorithm which is reliant on user feedback where it uses streaming counts and user visits to artists' pages. It is essentially an algorithm used for recommendation where it makes song/artist recommendations for users based on their connection with other users. The data used for recommendations is stored in user vectors that store a listeners music preferences and song vectors that store a song's music profile. These vectors are then compared with each other in order to recommend songs to users. We can use this algorithm to recommend users with different artists at Brown!

Requirements: 
Users are very interested in learning more about student musicians on campus. Thus, we need to create a platform that is user friendly for both the content creators and the student listener. We should be able to upload different forms of audio in order to present creators with a platform to share their work. The audio should be displayed on the website, so that students on campus would have greater access and exposure to it, because currently students are gaining exposure to new music through concert attendance and friend recommendations. There should also be some sort of filtering/record keeping for the audio that is inputted, so that the website would be easier to use, and the work of the student artists could be highlighted. Lastly, users should be able to interact with the audio in order to garner more user engagement, because the survey indicated a high interest in what types of music one’s peers were creating and listening to. 

Potential Roadblocks: 
There will have to be two different types of interfaces for the two different user profiles that we will have: the audio creator, and the student listener. Furthermore, later we will have to determine a mechanism for filtering the media on our platform. For a user friendly platform, we will also need to think of modes of garnering user involvement such as keeping track of likes, etc. 

User Perspective: 
We created a google form with a few interview questions that we gave to students at Brown, because our target demographic is Brown University students. From survey results, all interviewed participants said that they are interested in learning more about student musicians on campus. The majority of users said that they discover new music through friends recommendations, going to concerts, and through spotify while a minority said they discovered new music through Youtube and Soundcloud. From a scale of 1-5, the majority of users said that how easy it is to access student produced audio is a 2. The people who said that they do create content said that they are maybe empowered to share their work, and they are doing so through social media and soundcloud. 
