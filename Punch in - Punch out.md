**Test Case Id**- TC-Punch_01

**Test case title**:  

Verify that the system calculates the employee’s total work duration correctly based on the punch-in and punch-out times.

**Module**: Punch in - Punch out

**Priority**: High

**Preconditions**:

-Employee account exists.  
-Employee has valid login credentials.  
-Employee is logged into the application.  
-Employee has access to the Time/Attendance functionality.  
-Employee has not already punched in.  


**Test Data**:

Employee ID: 78900  
Punch In: 11:00 PM (2026-20-08)
Punch Out: 05:00 AM (2026-21-08) 
Expected Duration: 6 hours  


**Test Steps**:

-Log in using valid employee credentials.  
-Navigate to Time → Attendance.  
-Click Punch In.  
-Verify that the punch-in time is recorded.  
-Wait/work for the required test interval.  
-Click Punch Out.  
-Navigate to the attendance record.  
-Check the recorded punch-in and punch-out times.  
-Verify the displayed work duration.  



**Expected Result**:

The system should record the correct punch-in and punch-out times and calculate the employee’s total work   
duration correctly based on those times. For example, the punch-in time is 11:00 PM ( and punch-out time   
is 05:00 PM, the displayed duration should be 6 hours.  

**Expected Result**:

The system recorded the correct punch-in and punch-out times and calculate the employee’s total work   
duration correctly based on those times. The punch-in time is 11:00 PM and punch-out time   
is 05:00 PM, the displayed duration should be 6 hours.  

**Status**:  Pass  

**Test Evidence**

![TC-Punch_01 Execution Evidence](https://github.com/saba4firdous-ui/OrangeHRM-/blob/main/Screenshot%20punch%20in%20&%20out.png?raw=true)
