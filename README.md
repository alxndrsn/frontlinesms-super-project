FrontlineSMS Super Project
==========================

This is the FrontlineSMS super project.  It is used to manage the separate modules of FrontlineSMS.

Making a workspace
------------------

This project will set up a workspace for FrontlineSMS in e.g. **Eclipse** quite nearly:

    git clone git://github.com/frontlinesms/frontlinesms-super-project.git frontlinesms-workspace

To then check out the source for the project's modules, run the following:

    cd frontlinesms-workspace
    git submodule init
    git submodule update

Once this is done you will need to change your eclipse workspace to `./frontlinesms-workspace`, and then create a new Java project for each of the child directories of `./frontlinesms-workspace`.  After creating each project, enable Maven dependency management for it.
