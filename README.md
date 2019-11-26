# Machine Learning : Predicting Body Postures using KNN
<i>A Machine Learning Project for Predicting Body Postures using K Nearest Neighbour Algorithm in Python</i>

Attribute Information:

   1. lhx - Position of left hand (x coordinate)
   2. lhy - Position of left hand (y coordinate)
   3. lhz - Position of left hand (z coordinate)
   4. rhx - Position of right hand (x coordinate)
   5. rhy - Position of right hand (y coordinate)
   6. rhz - Position of right hand (z coordinate)
   7. hx - Position of head (x coordinate)
   8. hy - Position of head  (y coordinate)
   9. hz - Position of head  (z coordinate)
   10. sx - Position of spine (x coordinate)
   11. sy - Position of spine (y coordinate)
   12. sz - Position of spine (z coordinate)
   13. lwx - Position of left wrist (x coordinate)
   14. lwy - Position of left wrist (y coordinate)
   15. lwz - Position of left wrist (z coordinate)
   16. rwx - Position of right wrist (x coordinate)
   17. rwy - Position of right wrist (y coordinate)
   18. rwz - Position of right wrist (z coordinate)
   19. timestamp - 
   20. phase: 
		-- Rest
		-- Preparation
		-- Stroke
		-- Hold
		-- Retraction


       Gesture phase segmentation is a task with several inherent difficulties. First, it is a subjective task, since there
       is no clear point where a phase begins. Thus, different specialists may provide different segmentations for the same
       video. Also, some phases may present similar patterns, such as rest position and hold, where the hands remain paused.
       Finally, gesture phase segmentation has open issues among researchers, such as if the phases should be segmented 
       separatedly for each hand or if meaningless gesture -- such as touching the glasses while speaking -- may be considered
       for gesture phase segmentation.

       Also, it is important to consider that the gesticulation behavior may influence the performance of a classifier built 
       for gesture segmentation. Thus, it is important to highlight that videos A1 and A2 were recorded in the same session, 
       while video A3 was recorded in a different session, which may yield different gesticulation behaviour. 


Dataset : https://archive.ics.uci.edu/ml/machine-learning-databases/00302/
