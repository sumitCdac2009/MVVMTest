# CountValidation

 
### Tasks is to implement below functionality to the existing base application

#### Requirements

    Please complete below requirements for Android native project with architecture components includes MVVM and Data binding concept

	Create one layout with button, Sample Image attached
	Based on button click increase count for likes and based on conditions Star symbol will change (Assets given)



1) On every click event count for likes will increase by 1
2) On every 5 increments star symbol will change accordingly
3) (0-5 -> not filled star),(5-10 -> Half filled star),(10-20 -> filled star),(20 is maximum limit)
4) On 20 likes completion stop counter and inform user in a Toast message "Reached maximum limit"



#### Write UI test cases with help of espresso for the below scenario

1) Check all the UI components are visible
2) Validate changes on star image based on counter and clicks


#### Write unit test cases for the below scenario

1) Validate number of button clicks against counter (Example : If user clicked on button 5 times then likes value should be 5)
2) Validate after more than 10 clicks star symbol state is filled image/state. (Use any constant variable name for validation)