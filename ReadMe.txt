Database from Mai Xu, Lai Jiang, Xin Deng in Beihang University(2015). 

This database contains the fixation data of 15 standard video sequences of HEVC.

In 'video_database.mat', you can find

	videos_info: the information of 15 videos 

	video_names_list: the index for 15 videos

	subj_info: the information of 32 participants 

	subj_names_list: the index for 32 participants

	fixdata: contains fixation data of all videos from all participants.

	fixdata_fields: 
    '1: SubjectIndex (see subj_names_list)'
    '2: VideoIndex (see video_names_list)'
    '3: Timestamp (milliseconds after image display)'
    '4: GazeDuration'
    '5-6: fixation position (take upper-left corner as origin )'
   


As a test, you can run 'demo.m' to view the heat-map series of the target video.  

Should you have any queries, please contact Maixu@buaa.edu.cn


Have fun!

----------------------------


