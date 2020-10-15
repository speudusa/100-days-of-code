# 100 Days Of Code - Log

### Day 0: TEMPLATE


**Today's Progress**: 

**Thoughts/Notes/Braindump space:** 

**Pre-Build Space -->**  

**Post-Build Space: -->**

**Link to work:**

**------------------------------------------------------**

### Day 10: Thurs, Oct 15, 2020


**Today's Progress**: Step 1:  Complete final class survey [check]
Step 2: Creating Reader Option (DD to select who is reading which book)

**Thoughts/Notes/Braindump space:**   This is the start of creating relationships between 2 tables.  

**Pre-Build Space -->**  Have my book table ready to go.  Need to create Reader (Model, Controller, and View)

**Post-Build Space: -->**
Okay, so I now have a Reader Controller, Model, ViewModel, and Views(Index,CreateReader)

Ran into issues with converting my Edit function to start using my dBContext

**Link to work:** https://github.com/speudusa/BearPawPages

**------------------------------------------------------**

### Day 9: Tues, Oct 13, 2020


**Today's Progress**: Initalized persistent data storage

**Thoughts/Notes/Braindump space:**  Remember to download nuget packages

**Pre-Build Space -->**  Want to create presisent data to create other tables using my book object and edit functions

**Post-Build Space: -->**  mySQL Db is connected to my initial table.  Time to start planning relationships and how I want to build new tables

**Link to work:**  https://github.com/speudusa/BearPawPages

**------------------------------------------------------**

### Day 8: Mon, Ocy 12, 2020


**Today's Progress**: created viewmodles to assist with validation

**Thoughts/Notes/Braindump space:** 

**Pre-Build Space -->**  

**Post-Build Space: -->**  i want to do this with my edit function...

**Link to work:**  https://github.com/speudusa/BearPawPages

**------------------------------------------------------**


### Day 7: Fri, Oct 9, 2020

**Today's Progress**:  Created the Edit features

**Thoughts/Notes/Braindump space:**  Using ViewBags right now.  

**Pre-Build Space -->**   Want to be able to edit entire book object, and update page numbers and notes

**Post-Build Space: -->**  
   - Created edit function to edit the entire book object.
   - Created "Bookmark featuer that ONLY updates the page number and notes
 
**Link to work:** https://github.com/speudusa/BearPawPages

**------------------------------------------------------**


### Day 6: Thurs, Oct 8, 2020

**Today's Progress**:  Delete functionallity

**Thoughts/Notes/Braindump space:**  delete functionality 
updated data management.

**Pre-Build Space -->** need to add some ids to my objects, and create data management.  

created data folder which will be responsible for the data instead of the book controller.

**Post-Build Space: -->**  
it works.  
  * I can add a book, and the ids
  * each new book is stored in a dictionary in the data folder at the moment.  (eventually this will move to a database)
  * I can select books to delete 


I like where this is going so far.  Slowing down and starting over has really helped.  Also, as this is the second time around, my build has less bugs in it and I'm able to free-form more to fit the needs of my project.  (highfive!)

**Link to work:** https://github.com/speudusa/BearPawPages

**------------------------------------------------------**

### Day 5: Wed, Oct 7, 2020

**Today's Progress**:  Started a new project.  It's cleaner.    

**Thoughts/Notes/Braindump space:** I know what I want, but a clean space will help me build it.  I can use my last project to help me keep things straight.  

**Pre-Build Space -->**  Using my textbook and videos, I started at the VERY VERY beginning.  As in "In the beginning there was only a Home Controller..."   While this feels VERY underwhelming and takes a hit at the morale, I know that I need the space and blank slate to rebuild.

**Post-Build Space: -->**  Created *Books Controller* and the following Books *View:  /Add and /Index*
The **Index view** will list all books (it's basically a bookshelf)
    - initially I hard coded this to verify that it works
    - I then replaced it with an Add and NewBook method
          - **Add** = HttpGet and takes us to the Add View
          - **NewBook** = HttpPost and allows us to update the view after the for is filled out (in the Add view)
    - titles are posted via foreach loop
The **Add view** will allow us to add books
     - contains a form to collect titles at this time

**Link to work:** https://github.com/speudusa/BearPawPages

**------------------------------------------------------**


### Day 4: Tues, Oct 6, 2020


**Today's Progress**: Simplify.  All I need right now, is a MVP.  User Account and CRUD features are all I need.  

**Thoughts/Notes/Braindump space:** KISS.  

**Pre-Build Space -->**  What can I use my home controller for?  Add methods, About method?  
Need an Add View, About view.

Where will editing/deleting happen?  On the About View.  Think about that.  

**Post-Build Space: -->**  
Decided to start over.  


**Link to work:** https://github.com/speudusa/OPM


### Day 3: Mon, Oct 5, 2020


**Today's Progress**: Working on the AddBook feature 

**Thoughts/Notes/Braindump space:** Want to create book object and have it appear on the home view in a table

**Pre-Build Space -->**  KISS
    - create book object (check)
    - pull book object back onto home index view <--
    - have buttons work:  Add new book -> Book ViewModel  and then Actually add book button -> return to home index and appear on the home index table
          - SOOO close to having this.  

**Post-Build Space: -->**
    - Removed ReadingList Contrller to create Shelf items (Model, View, ViewModel - using Home as Controller)
    - Stuck with importing book data.
    - plans for tonight = pick up here

**Link to work:**  https://github.com/speudusa/OPM

**------------------------------------------------------**

### Day 2: Oct 2, 2020


**Today's Progress**: Created new branch that has my notes

**Thoughts/Notes/Braindump space:** 

**Pre-Build Space -->**  

**Post-Build Space: -->**

**Link to work:**

**------------------------------------------------------**

### Day 1:  Oct 1, 2020

**Today's Progress**: Building One Page More

**Thoughts/Notes/Braindump space:**   

**Pre-Build Space -->** The Reading List (RL) can exist without the Book (B) objects.  RL is basically a shelf to display things, anything really, books, people, rotary phones, etc.  The shelf can exist without the book in this context.  The B can not exist without the shelf (they would be floating like fruit in a jello ring.  We need to bring jello rings back.)

Okay, so now that I better understand this relationship, I see how I need to incorporate the ORM and collections.  

**Post-Build Space -->**  So, don't get mad.  I added Users instead.  This made a lot of sense with the section of the book I was reading.  While I was trying to figure out how to build the Book/RL relationship, the set up in the book made the most sense here.  Parent can add child AND book, but can now assign book to specific child (I hope)

(having a hard time testing this right now since I didn't finish my inital task and that is full of errors preventing me from running it, BUT in spirit I think it is a good start)

**Link to work:**  https://github.com/speudusa/OPM

**------------------------------------------------------**

### Day 0: Oct 1, 2020


**Today's Progress**: I did code, but I wanted to set my intention and create a space for me to work through my blocks.  This Project is my final project for LaunchCode's LiftOff.  It is the (first) and biggest thing I have ever build on my own.  I am trying to make space for it in my day to day life, and hope that creating a place to plan, ponder, and grow from will be more helpful than just a list of Ta-Da's!  For me.  

I added a place to drop things.  I added space to list my goal for the day and a place to list where I stopped.  But these spaces are also places that can hold more than just facts and figures, but the story behind it all, the place when connections are made.  So, if you want to read along, you are welcome to.  I will try to keep these updates short and to the point.  

I should make a parking lot...  but not here.  

**Thoughts/Notes/Braindump space:** 

**Pre-Build Space -->**  Rethink my process.  How do I best learn?  Stories, writing about it, making connections.

**Post-Build Space: -->**  So, here is my redesigned log.  My rekindled passion to make this project happen.  

**Link to work:**  https://github.com/speudusa/OPM

**------------------------------------------------------**

**------------------------------------------------------**

### Day 0: TEMPLATE


**Today's Progress**: 

**Thoughts/Notes/Braindump space:** 

**Pre-Build Space -->**  

**Post-Build Space: -->**

**Link to work:**

**------------------------------------------------------**
