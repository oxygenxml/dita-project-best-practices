# dita-reuse-best-practices
A small DITA project skeleton exemplifying best practices to reuse content and to manage links. The project favors using DITA 1.2 keyref indirect links over direct DITA 1.1 links.

If you want to start a DITA project from zero, obeying such a structure may help you in:

1. Growing the project in a healthy sustainable way.
2. Give you a good overview over what you are reusing. 
3. Allow easier link management.

Let's try to take a look at the resources which comprise this project:

- "talking-circle.ditamap" - The main project DITA Map. In our case it's a small example DITA Map discussing about an hypothetical software application.
- "filters" - This folder contains all DITAVAL filter files which are used to obtain various outputs from the project contents. 
- "images" - This folder contains all image files used in the project. You can add various subfolders to it.  
- "links" - This folder contains various link-related mappings: 
     - "externalLinks.ditamap" - Contains key definitions for all your external links, usually links to external web resources.
     - "internalLinks.ditamap" - Contains key definitions for the project's topics referenced from other topics.
     - "relationshipTable.ditamap" - Contains the relationship table describing links between various topics.
- "reuse" - This folder contains mappings for reused content:
    - "reusableComponents.dita" - This topic contains a list of reusable elements. For each element there is a description which instructs the technical writer how to reuse it. In a larger project there are probably more than one such topics.
    - "reusableImageReferences.ditamap" - Maps keys for each used image.
    - "reusableProductNames.ditamap" - Defines small pieces of text which can be reused using keyref.
    - "reusables.ditamap" - Binds together all these resources, assigns a key for the reusable components topic. 
- "tasks, topics, concepts, references, etc" - Folders which contain the actual DITA content, either split in subfolders by topic type or by some other project-specific role.

