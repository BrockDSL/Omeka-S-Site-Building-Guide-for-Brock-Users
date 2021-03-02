![Banner Image][imglogo]


Welcome to the Omeka S Site Building Guide!  This guide will walk through all of the steps you will need in order to build an Omeka S site that adheres to the guidelines required by the Brock University Digital Scholarship Lab.  If you have any questions or suggestions while working through the guide, please reach out to the DSL at DSL@Brocku.ca.

Without further ado, lets get building!

# Step 1 - Make a Site

Log in to the Brock University Library instance of Omeka S by going to https://exhibits.library.brocku.ca/login and signing in using the credentials set up for you by the Brock DSL. This will bring you to your Omeka S Dashboard.  From here, click on "Sites" in the left-hand menu to get to the site list and then click the "Add new site" button in the top right.

Fill in the fields provided with the following:

* A descriptive title that describes the content that the site will contain
* A URL slug for the web address of the site (if left blank a slug will be generated from your site title)
* A descriptive summary detailing the purpose and contents of the site

Next you will go to the "Theme" tab at the top of your screen and select a theme from the 5 available options.  If you want to see what each theme looks like beforehand, take a look at the demo sites for each theme created by the DSL.

* [Cozy Theme](https://exhibits.library.brocku.ca/s/dsldemo_01/page/welcome)
* [Center Row Theme](https://exhibits.library.brocku.ca/s/dsldemo_02/page/welcome)
* [The Daily Theme](https://exhibits.library.brocku.ca/s/dsldemo_03/page/welcome)
* [Default Theme](https://exhibits.library.brocku.ca/s/dsldemo_04/page/welcome)
* [Foundation Theme](https://exhibits.library.brocku.ca/s/dsldemo_05/page/welcome)

Once you have chosen a theme, click the "Add" button at the top right of the screen.

<iframe src="https://h5pstudio.ecampusontario.ca/h5p/18304/embed" width="993" height="584" frameborder="0" allowfullscreen="allowfullscreen"></iframe><script src="https://h5pstudio.ecampusontario.ca/modules/contrib/h5p/vendor/h5p/h5p-core/js/h5p-resizer.js" charset="UTF-8"></script> 

---

# Step 2 - Make an Item Set

Next step is to make an item set to store all of the items that will be used on your site.  Click on "Item Sets" in the menu on the left to get to the item set list and then click the "Add new item set" button in the top right.

By default, there will be two properties to fill in for the item set, Title and Description.  The title of your item set should be **exactly** the same as the title of your site.  The description property can be left blank or filled with a brief description of the type of items that will be contained within the item set.

You can add any other properties you want to your item set but the only requirement to adhere to the DSL guidelines is to have a title that matches the name of the site the item set is for.

Click the "Save" button in the top right.

<iframe src="https://h5pstudio.ecampusontario.ca/h5p/18367/embed" width="993" height="584" frameborder="0" allowfullscreen="allowfullscreen"></iframe><script src="https://h5pstudio.ecampusontario.ca/modules/contrib/h5p/vendor/h5p/h5p-core/js/h5p-resizer.js" charset="UTF-8"></script>

---

# Step 3 - Set up your site settings

Next, we will need to set up all of our site settings so everything works the way we want it to.  Click on "Sites" in the left menu to get to the site listing then find your site and click on its name.

Now that your site is open you will see some new option in the left menu.  To begin, click "Site Admin" to open up your site options then click on the "Settings" tab.  In the options listed, check the following:

* Make sure that the "Auto-assign new items" toggle is turned **off**
* Make sure that the "Restrict browse to attached items" toggle is turned **on** (unless you are displaying content collected by the collecting module in which case this will need to be off)
* Check that the eye icon in the top right of the screen is toggled to private (eye with a line through it)

Click the "Save" button in the top right when you are done.

After admin settings are saved, click on "Resources" in the left menu.  You should see a message that says: "There are currently 0 items assigned to this site".  If the message is different go back to your admin setting and check that you saved everything properly.

Open the "Item Sets" tab.  Find your item set in the list on the right by clicking on your name (or the name of the person who made your item set) and clicking the item set.  It will disappear from the list on the right and be added to the list in the middle area.  Click the "Save" button in the top right.

The last settings to adjust are found by clicking on "Theme" in the menu on the left.  You will see your selected theme at the top of the page with a button labeled "Edit theme settings".  Click that button.

Depending on the theme you have chosen the options in this area will change.  Feel free to experiment with your theme setting to make your site look and act the way you want it to.  The only thing you need to do here to adhere to the DSL guidelines is to include the following line of code into your footer content.

`Powered by Omeka S and created with the support of the Brock University Digital Scholarship Lab – <a href = "mailto: DSL@Brocku.ca">DSL@Brocku.ca</a>`

Once you have adjusted your settings click the "Save" button in the top right.

---

# Step 4 - Item Assignment

With that your site is set up and ready to start building but before you start making items and building pages there is one more guideline to be aware of.  As of Omeka S 3.0 items must now be assigned to sites in order to be used on that site.  This is to prevent issues where items not contained in a site were being connected to that site by the google search algorithm.  What this means for you is that when you are making items there are now two very important steps that must be done.

When creating a new item, you must:

* Assign it to an item set by opening the "Item sets" tab and adding the item sets for any site that the item will be used on from the right menu to the central area
* Assign it to a site set by opening the "Sites" tab and adding all of the sites that the item will be used on from the right menu to the central area

---

# Step 5 - Build and enjoy

That concludes this guide on how to set up your Omeka S site so that it adheres to the Brock University Digital Scholarship Lab Omeka S Guidelines.  If you want to discuss these guidelines or set up a meeting with a member of the DSL staff to discuss your site, please contact us at DSL@Brocku.ca










**This guide is brought to you by the Brock University Digital Scholarship Lab.  For more information on the DSL check out our website at [www.brocku.ca/library/dsl/](https://brocku.ca/library/dsl/) or you can e-mail us at dsl@brocku.ca.**  
  
You can also find us on:  
[Facebook](https://www.facebook.com/Brock-University-Digital-Scholarship-Lab-349407235866792/)  
[Twitter](https://twitter.com/brock_dsl)  
[Instagram](https://www.instagram.com/brock_dsl/?hl=en)  
[YouTube](https://www.youtube.com/channel/UC2eEqPkDo-1N3qilxv-N_1g/featured?view_as=subscriber)










<!--- Please use reference style images so that it is easier to update pictures later --->

[imglogo]: guide_logo.png

