### Simply Advanced Searchbar

#### A replacement to EPrint's simple searchbar


The simple search functionality in EPrint repositories has some known problems, which lead to inconsistent search results. On the other hand, the advanced search functionality is known for providing more consistent and reliable results.

This plugin aims at combining the ease of use of the simple search bar with the reliability of the advanced search function. 

The trick diverting all the search requests to the advanced search function, allowing the users to specify the search metafields from a drop down menu.

  
Enjoy!


##### How to install

After enabling the EPM, all you need to do is to replace the search bar code in <code>cfg/templates/default.xml</code> with 

<code><epc:phrase ref="simply_advanced_search_searchbar"/></code>

Please note that it is likely that further HTML/CSS adjustments will be needed in order to ensure that the search bar looks right in the specific design of your repository.in order to ensure that the search bar looks right in the specific design of your repository.  
