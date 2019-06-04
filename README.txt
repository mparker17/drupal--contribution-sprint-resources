Contribution sprint resources
-----------------------------

This USB stick is supposed to help people get Drupal set up on their computers so they can participate in certain tasks during contribution sprints.

A local installation of Drupal is useful if you want to...

1. Contribute code or API documentation,
2. Try to reproduce issues that other people have filed tickets about,
3. Test other people's patches,
4. Write documentation for a specific module, theme, or feature

... but might not be so useful if you want to...

1. Curate old tickets by closing them,
2. Provide support,
3. Write general documentation,
4. Contribute translations
5. Conduct design or usability studies, or contribute a design,
6. Help get the word out about Drupal by marketing it,
7. Donate money to the Drupal community to keep the lights on or empower others to contribute



Set up a local installation
---------------------------

Drupal needs three other programs (Apache HTTP Server, MySQL database, and PHP) in order to work properly. These three programs is called a "stack". 

This USB stick provides you with some options to help you set up an Apache+MySQL+PHP stack...

* Acquia Dev Desktop,
* Docksal,
* DrupalVM,
* Lando, and
* MAMP (which has a version for both MacOS and Windows now).

They all have their advantages and disadvantages - like text editors, different people have strong opinions on which one works best for their use-case.

* I (mparker17) personally prefer Lando, because it's an "all in one" solution that can configure itself depending on the project you are working on.
* Docksal can also self-configure for the project you're working on. It is a little bit more complex to set up, but unlike Lando which only uses Docker, you can use Docksal with Docker, VirtualBox, or Windows' linux subsystem.
* Both Lando and Docksal use the command-line a lot. If you'd prefer a more-visual solution with a UI, then Acquia Dev Desktop might be for you: it's optimized to get Drupal up and running quickly.
* MAMP also has a UI, but is not optimized for Drupal, so you'll need to know a bit about how to write Apache, MySQL, and PHP configuration files. Still, MAMP is a reliable solution that I used for years before Lando. Unlike all of the other options presented thus far, it runs everything natively instead of in a virtual machine, so it tends to be a lot faster.

Once you've chosen an Apache + MySQL + PHP stack, open the INSTALL.txt in that folder to find out more about how to install it.


Docker, Vagrant, and VirtualBox
-------------------------------

Docker, Vagrant, and VirtualBox are prerequisites for Docksal and DrupalVM, which need to be set up before those programs will run.
