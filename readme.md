Make: Projects Step Editor
==========================

Summary
-------

MAKE needs a tool that can both read, and write all of the data points that exist as a result of the Make: Projects API. Editors can manage the steps of posts, and also create new projects with steps.

Requirements
------------

1. If this is a new project, when a user is on the projects edit screen, they have a meta box that allows them to upload up to three images, and step heading, and a then an unordered list of sub steps. They can add as many sub steps as needed.
2. When the post is saved, all of the steps are saved into a custom field array that matches the data structure of `print_r` of `$steps`.
3. If this is an older project, all of the steps are loaded into the form, and can be edited/saved by the editor working on the project.
4. Ideally, each of the steps and substeps are sortable, but not a requirement for the initial project.
5. The provided wireframe should be followed generally, but is open to interpretation.
6. Development must follow WordPress.com VIP best practices. MAKE will work with developer on requirements there.
7. Development is complete when live on site.