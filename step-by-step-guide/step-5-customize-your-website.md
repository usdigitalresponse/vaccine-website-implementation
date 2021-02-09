# Step 5: Customize your website

In this section, you will customize all the pages of your website to fit your county’s needs. To complete this step, you will need:

* [ ] Your office contact details, 
* [ ] Lists of vaccine locations with links to schedule, 
* [ ] A timeline image, and 
* [ ] Data for the percent of county/city vaccinated by week \(can be removed if you don’t have access to such data\). 

This is the longest step of the setup process. Don’t forget, we’re always here to help you with questions about formatting, content, or anything else related to the website.

{% embed url="https://youtu.be/mzNuCTg0i1A?t=65" caption="Step 5 instructions to customizing your website" %}

### **Preview your website as you edit**

* **From WP Admin:** In the WP Admin settings page, you will see a button in the top left corner labeled “My Sites.” Tap this button, and click on the “View Site” button to preview your site. There will also be a banner at the top reminding you that your website is not launched yet - you can dismiss that. 
* **From Wordpress.com:** In the WordPress.com dashboard, you will see a button in the right-hand corner labeled “Visit Site.” Tap this button to preview your site. You can leave the tab open as you’re editing and refresh to show new, saved changes. Preview as often as you can to see how your changes are reflected on the site. 

### **Customize your site’s name, colors, and menu**

1. In the “Design” setting menu, click “Customize”, which will open a new interface. 
2. Site Identity: Here you can update Site Title and a logo \(if desired\).
   * Colors & Backgrounds: Here you can customize your site’s overall colors.
   * Menu → Primary: Here you can add or remove pages from the menu \(click the drop-down on an item and click “Remove” to remove\). 
   * Tap “Save Changes” and click the “X” in the upper left-hand corner.

### **Customize your homepage**

These settings control the content on your homepage: a great place to highlight essential information or announcements related to the vaccines. Best Practice: Do NOT add additional components to the home page other than the banner and tiles.

Your homepage is the first screen every visitor sees on your website. Based on our research, we’ve suggested a banner and 6 links that we think your residents will find the most useful. However, you can always customize the links on your homepage if you would like to. 

1. Click on the “Pages” setting menu, then open the page that is “Untitled”.
2. **Banner**
   1. For some reason, the banner is cut off in the preview \(but appears normal on the site\). While editing, you will need to change the height. To do this, click on the blue section, click “Block” on the right-hand side, and change “Height in Pixels” from 150 to 500.
   2. “Color Settings” under “Block” will allow you to change the background color.
   3. You should now be able to edit the text, image, and/or button by simply clicking on them.
      1. Text: Simply edit.
      2. Image: Click Replace to replace.
      3. Button: A second box should appear allowing you to edit the link. 
   4. Finally, click on the blue section again, click “Block” on the right-hand side, and change “Height in Pixels” back from 500 to 150 \(or whichever height you prefer!\).  
3. **Tiles**
   1. You will see six default tiles on your homepage. Each of these tiles is a link to part of your website. We need to update each link, which is currently still pointing to the US Digital Response demo site. 
   2. Update each homepage tile link: 
      1. Hover over the first tile, “How does the vaccine work?” 
      2. A menu will come up over the tile. Click edit and replace “[https://vaccinestemplate.wpcomstaging.com/faqs\#vaccine-work](https://vaccinestemplate.wpcomstaging.com/faqs#vaccine-work)” with “https://\[domain\_name\].com/faqs\#vaccine-work”.
   3. Repeat the steps listed above for each of the tiles on your homepage. NOTE: Please keep everything the same after the “.com/” for each tile to ensure the links function correctly.
4. You may want to customize your homepage with different tiles. To do so click on any tile, click the 3 dots icon \(“More Options”\), and click Duplicate. Then, update as needed. The left and right arrows allow you to position the tile as desired. NOTE: We recommend returning to do this after you’ve edited all the content across your website.
5. Make sure you click “Update” in the top right-hand corner once you’ve made the changes, before exiting the page!

### **Edit the content across your website** 

For the rest of this section, you will be updating each page on your website. To edit a page, go to “Pages” and select the relevant page as you did in the previous section. As you edit each page, take care to make the following updates: make sure any navigation tiles are linked accurately, make sure all text is accurate, and make sure any links are updated. 

As you update each page, you have a few choices: 

1. You can use our pre-written content for that page. Make sure to update all text or links for your county. 
2. You can copy and paste content you have prepared elsewhere. For example, you may have text from a previous website. 
3. You can unpublish the page if you don’t think it belongs on your website. Please see the “Customize your site’s name, colors, and menu section” above for instructions on how to remove a page.

The rest of this section includes descriptions and instructions for updating each page. When you’re finished updating all the pages, continue on to the next step \(6. Launch your website\).

#### **Page: “FAQs”** 

1. This page is mostly text, so feel free to update as desired! Note that we have separated each FAQ into a different block, as this preserves formatting across devices. 
2. To add a new text block, click on the “+” icon on the top left and select “Paragraph”. Then, simply add the FAQ you’d like.
3. To remove a text block, select the FAQ, click the 3 dots icon \(“More Options”\), and select “Remove Block”.
4. Optional: To implement a language, your content must already be translated and you will need to create a new page.
   1. Go back to the “Pages tab”, click “Add New Page” in the top right, click “Use Blank Layout”, and then paste your content to the new page.
   2. You will then need to update the language link \(e.g., Español\) on the main FAQs page to point to the newly-created language FAQ page.
   3. Feel free to remove the language line if you don’t have translations. NOTE: We are still working on translating the pre-written content.
5. Optional: If you’d like to link a homepage tile to an FAQ:
   1. Click on the FAQ, click on the 3 dots icons \(“More Options”\), click on “Block”.
   2. Click on “Advanced” and type a short word to describe the FAQ under “HTML Anchor”.
   3. Update the homepage tile’s link to /faqs\#\[htmlanchor\].

#### **Page: “Timeline”** 

1. Update the first paragraph to include your county name and remove “\[EXAMPLE BELOW\]”.
2. Simply update the image with your timeline image by clicking on the image and clicking “Replace”. Format as needed using “Block”.

#### **Page: “Find Vaccines”** 

1. Update the first paragraph to include your county name and remove “\[EXAMPLE BELOW\]”.
2. To update map:
   1. Click on map.
   2. Click on marker plus sign icon \(“Add a Marker”\) to add a new location.
   3. Click on each red marker to update/remove.

#### **Page: “Contact Us”** 

1. Update Contact Us and Info sections with accurate information.
2. Click on the “Name” field under “Send a Message”. At the very bottom of the page, click the link “Form” that is right before “--&gt; Name”. In “Block”, update the email address to your own.

#### **Page: “Our Impact”** 

This page is unique as it shows vaccinations served in your country, similar to a COVID-19 chart of cases overtime. To implement, this requires weekly vaccination data of your county, along with the ability to make a one-minute update every week. We believe this is an extremely useful addition to help build trust in the vaccine. However, if you do not have the data or the time for this page \(or would like to replace it with something else\), simply follow instructions above to remove this page from the menu, and it will not appear.

1. Update the first paragraph to include your county name and remove “\[EXAMPLE BELOW\]”.
2. In the block of code below, make sure you DO NOT change any of the code except for the following:

\['Date', '% of County\],  
\['Dec 1',  1\],  
\['Dec 8',  2.3\],  
\['Dec 15',  4.8\],  
\['Dec 22',  7.8\],  
\['Dec 29',  10.2\],  
\['Jan 4',  15.5\],

1. To update the labels, change ‘Date’ and ‘% of County’ \(make sure you keep apostrophes\).
   1. Ex: ‘% of County’ → ‘% of Alameda County’
2. To update the existing sample data, simply replace the dates and percentages accordingly \(make sure you keep apostrophes around the dates, omit apostrophes for the percentage, and keep the commas\).
   1. Ex: \[‘Dec 1’, 1\], → \[‘Dec 5’, 0.3\],
3. To add new data, simply copy and paste one line and replace the values.
   1. \['Jan 4',  15.5\], → \['Jan 11',  20.3\],
4. If you would like to use a different metric \(e.g., number of people vaccinated\), simply follow step 3 to update the label, and step 4 to update the dates/numbers accordingly.
   1. Ex: ‘% of County’ → ‘Number of People Vaccinated in County’
   2. Ex: \[‘Dec 1’, 1\], → \[‘Dec 1’, 1078\],

