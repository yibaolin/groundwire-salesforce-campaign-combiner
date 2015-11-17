The Campaign Combiner is a Visualforce page that can be installed into Salesforce to allow users to add campaign members from multiple campaigns into a target campaign, or exclude members who belong to multiple campaigns.

The page uses several interesting features of Apex and Visualforce, such as batch apex and group by (aggregate) queries.  Because campaigns may have many members, the controller uses standard apex for small campaigns and falls back to batch apex for larger ones.

This project was created by Groundwire (http://groundwire.org/labs).  At Groundwire, we are on a mission to get affordable and innovative online tools and strategies into the hands of organizations building a sustainable world.