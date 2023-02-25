# Moving Bones From Armature To Armature  
  
> WARNING incomplete information 
  
> WARNING merge first scale aftarwards  

To move bones from armature to armature  
- start on armature you will be adding from  
- press 'p' to sepreate bones to new armature (cleans all the rubbish off them)  (must be in edit mode)  p
- select that new armature  
- press ctl (left) and click on target armature then press 'ctl+j' to join  
- remove scrap armature  
- bind mesh to primary armature  
- bind new bones to correct parent bone (they will start out in the root of the primary armature) (one bone at a time) (has to be done in edit mode)  
- added mesh should auto link to intigrated bones  (test in pose mode)  
- perform scaling and repositioning (in pose mode)  
- go to the added mesh and add an armature modifyer (mesh will move up)  
- remove the old modifyer (mesh will move back down and line up with bones)  
- switch main object back to object mode (new mesh should stay put on bones)  
