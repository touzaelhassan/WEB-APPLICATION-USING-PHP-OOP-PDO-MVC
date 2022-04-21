-----| MVC

       MVC : Model View Controller = Software design pattern That seperates application functions into 3 different areas :
       ---------------------------

           1 - MODEL

               + used to deal with The data of The application 
               + Interacts with The database ( INSERT - SELECT - UPDATE - DELETE )
               + Communicate with The Controller

           2 - VIEW

               + What The user sees in The browser (UI) usually consists of HTML and CSS
               + Communicate with The Controller
               + Can be passed dynamic values from The Controller

           3 - CONTROLLER

               + Receives input from The URL and Forms and processes requests ( GET - POST )
               + Gets data from The Model
               + Passes data To The views

       MVC WORKFLOW
       ------------