First Steps
===========

This section will show you how to setup a development environment, what software packages are necessary, and provide you with a general template to add new features.

Requirements
------------
Because of how intertwined the various software modules are, when adding new features to C.I.N.E.M.A. you will most likely be working across the spectrum of C.I.N.E.M.A. software for this reason it is recommended you install ALL of the software in this section.

- Linux 
- Python
- NPM
- Ionic
- Some other stuff
- LAMP stack
- Wordpress

Installation
------------
Once you have installed the requirements in the previous section, you will want to install our development server.

    sudo apt-get install stuff

Design & Implementation
-----------------------
C.I.N.E.M.A. doesn't look to bind you to any one method of programming, so you are free to setup your project any way you wish. However, we do have a recommended process for programmers to follow when adding features onto our codebase:
    #. Analysis
    #. Design
    #. Development
    #. Testing
    #. Debug
    #. Polish

Analysis
--------
The recommended Analysis workflow is:

    #. Define Scope
        - When developing a new feature for C.I.N.E.M.A. you should first create a well defined scope. C.I.N.E.M.A has to handle massive amounts of data every second, so it is not wise to pollute and bloat the codebase with unnecessary features.
    #. Collect End User Requirements (optional)
        - client interviews.
        - observation.
        - questionnaires.
    #. Start Documenting
        - Documentation should start EARLY in the process.
        - If you are unsure how or what to document, templates are available here.

Design
------
The recommended Design workflow is:

    #. Define Inputs/Outputs
        - Whether it's a database, a JSON object, or just a tweak to the code; you want to know the inputs/outputs 
        - For UI outputs it's recommended you sketch the layout(s) that will be included.
        - In addition to the UI layout, you want to include that actual I/O data structures
    #. Process Flow Diagrams
        - With your I/O clearly defined, you now need to determine what steps you need to take to transform your inputs into their desired outputs.
        - It's recommended you create multiple diagrams, examples can be found here to help you along.
    #. Pseudocode
        - Pseudocode will become a part of the documentation
        - Pseudocode has no standard syntax, however examples of what we consider good and bad psuedocode can be found here (https://users.csc.calpoly.edu/~jdalbey/SWE/pdl_std.html)
    #. Create Milestones
        - To prevent burnout and keep you focused on the task at hand, we strongly suggest you create milestones.
        - Examples of milestones can be found on our github. 

Coding
------
The recommended Coding workflow is fairly simple, with your pseudocode written you translate into the language you are coding in.


Testing & Debugging
-------------------
Testing and Debugging are processes that should occur at all stages of development throughout the life of the software.

Publishing
----------
We have no formal method of publishing additional features, addons, plugins, etc. at this time. If you would like to see your feature included in the main software suite, make a pull request on our github and we will review it.

End...?
-------
Congratulations! With any luck, you've created a new feature that will be used and shared with the greater IPTV community at large! 

Contribute
----------

- Issue Tracker: github.com/First Steps/First Steps/issues
- Source Code: github.com/First Steps/First Steps

Support
-------

If you are having issue, please let us know.
We have a mailing list located at: project@google-groups.com

License
-------

This project is licensed under the (insert license) license.
