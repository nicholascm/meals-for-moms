Meals For Moms

Goal User Stories
    * User can create a list with a unique ID for sharing 
    * User can search and find a list via a unique ID
    * User can add themselves to the list to bring a meal for a specific date 
    
Models
    * User
        * name
        * email
        * phone
         
    * Meal 
        * user_id
        * meal_list_id
        * description
        * date
        
    * MealList
        * start_date
        * end_date
        * beneficiary_id (user_id))
        * days_needed ?
        * coordinator_id (user_id)
        
    # future
    
    * Reminder 
    * 
        
    