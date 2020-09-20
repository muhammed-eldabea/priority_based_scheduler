# priority_based_scheduler
priority based scheduler 
______________________________________________________________________

## USED APIs 
1. **void SOS_voidCreatTask(u8 Copy_u8Periority , void(*ptr)(void) ,u16 Copy_u8Peridicity, u8 Copy_u8FIRSTdelay )** ; 
- **Usage** : creat a task and pass it to the scheduler containter 
- **Parameter** :   
                  - Copy_u8Periority  : the  Periority of task and ID 
                  - ptr : a pointer to function  
                  - Copy_u8Peridicity : periodic time of function 
                  - First delay : the first delay ticks of function 

2. **void SOS_voidStart() ;** 
- **Usage** : start the schedular 
- **Parameter** :   void

3. **void SOS_voidSetTaskState(u8 Copy_TaskID,u8 Copy_u8State) ;** 
- **Usage** : change the task state 
- **Parameter** :   state of the task  
______________________________________________________________________________________________
