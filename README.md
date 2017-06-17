# SplitoApp
chat extension app




STRUCTURE Notes

The view in the extension consists of 3 mains views:         extHome.html             extAddPaiment.html       extReimbourse.html

These 3 main views are rendered by three basic nodejs calls which then inject javascript page into this pages. 

When it calls /splito home page of the extension opens up. Called extHome.html
/splito renders this html page by inserting information from the context of the thread it is called from. By getting the context, it gets the information about what group chat this is about. If it exists fetch information in database about this group chat and display it on the extHome.html page. 


