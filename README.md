# JDBCMVCAPP


JDBCMVCAPP(servlets, jdbc,mysql,html, hikaricp connection pooling)
1. Created a dynamic web project and with the following packages controller, service, dao, bean
2. Created a html forms with frameset template.
3. created a index file and Servelt controller. In the index file, We will give a link that will trigger the controller. The link href=/controller/layout. The servlet controller with web url pattern(/controller/*). It means the controller will accept any URL pattern. and then after accepting it will get the requestURI. and then it will check endsWith(). based on that condition respective page will trigger.
4. In the layout form we mention as ../controller. It means it will come back from the controller path and it will check there.
5. if we click on Add. it will open addform.html, in the addform.html, after save it will come back to the same servlet.  
