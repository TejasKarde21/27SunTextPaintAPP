# 27SunTextPaintAPP

Our today task was to create an pain-drawing web app .

So for this i use a Html ,css ,JS

Html - Here it consist of main feield div with inside there are canva tag .
        also a two button tag for delete and one for undo.
        And in extra i make four more div to slect and colour and one colour container.
        And also a width of pen.

Css : -  I use flex to the body to make all content in the container in the centre.
         In color field to make it in circle i made it bored radius 50%.
         In tools div to make all atom in like i make them flex with an row direction.
         for button i make the context centre make a border to look attractive .
         In canvas to look attactive i make it a shadow to the box it look so nice.

javaScript : -  I get canvas in java by get elemnt by id function of web.
                then i give a width and hight to it;
                Then a get the context of canvas in 2d.
                set a baground color.
                Then a give a origin to a canva to draw in x=0, y= 0 upto length and width of 
                canva.
                i consided a three varible draw_color is use to select an differnt color as we c
                click on a div of a put on that background
                For that i make a event listener on the color div on html.
                second  width of the pen of draw that also i make a eventlisner with an 
                function to get input on the width as we chose on the bar.
                last one is_drawing make as false becose it should not be draw with a click 
                mouse event.
                ..
                I make an a event listner how to start to draw on which moving effect of moise.
                i make four event to start and draw .
                Then also to stop the event i make 3 event outofboundry of canva mouse realse 
                etc.
 .
                Then to start the event i make start function in that is_draw is make true to 
                draw. and draw should be on the context path.
                there we can move the mouse as x and y and left and top.
.
                Draw function to draw is drawind is true then draw in a direction . all the  
                default nature of it well get stop by preventing on it
.
                Same Stop function if we stop is_drawing will false and costxt.path(close)
.
                Delete entire so its simple we have to make screen as white. 
                all orighin should be from 0 to end will be blank.
.
                At last undo Function is toughf function : - first all we have to maake an 
               empty array with intial index = -1 ;
               beause as we draw an sigle like it well be an a 0 index of array.
               so it well start withempty as -1;
               In stop if we stop drwaing mouseout we have to push an a last elemnt draw before 
               mouse out to the array.
               and index should be increase by 1.
               Also when we Delete the function we have to make array empty and index back to 
                -1;
.
                Undo  will if it is nuthing in array then it well call delete function.
                else it get a store element and pop(), lasl element in the array it get store.


  This was a Painting Draw application.
               
                
                
          
                
                 
              
