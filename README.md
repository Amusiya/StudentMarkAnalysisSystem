# StudentMarkAnalysisSystem
This project is based on Student Mark Details.
In this student mark analysis system having 3 main modules. which all created by using two Software.
This project inserted the students mark details and stored in Mysql database.

    MODULES:
         1.   #Student
                  ##Student Registration
                  ##student Login
                  ##Student Semester Mark Details
         2.   #Faculty
                   ##Faculty Registration
                   ##Faculty Login
                   ##Student Overall Mark Details
          3.   #Admin
                   ##Admin Login
                   ## Faculty Details
                 n ##Students Resume & Picture Details.
   REQUIREMENTS:
           ## Java
           ## Mysql Server(JDBC)
                    
    Module Description:
        #### Student ####
            1.In this project first will show 2 option 
            ## student Registration ##student Login.
            Student Registration has validation and that all datas stored in mysql database.
            ##Student semester mark details having each and every semester mark details.
            
        #### Faculty ####
            1.In this faculty registration having basic information about facylty.
            2.Faculty login will fire after faculty registration process completed.
            3.This student overall mark details contains 6 semester score and it will calculate CGPA, based on the cgpa it will calculate CLASS.
            If cgpa greater than 6.0 then it will diaplay Top 5 companies for 1 st class Students, if cgpa less than 5.0 it will display 5 IT companies for 2 nd class students,
            If cgpa less than 4.0 it will display medium level of IT companies for 3 rd class students.
        #### Admin ####
            1.Admin login simply has username and password validation.
            2.Faculty details having faculty bio-information of staff.
            3.In this class stored students image and resume by using blob commands.
            
            
