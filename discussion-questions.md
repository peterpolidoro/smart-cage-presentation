# SmartCage

## Discussion Questions

Some cages will contain a small computer running Windows and Matlab. How do you
update and maintain a set of Windows computers remotely?

What is the best way to create a GUI that can be accessed remotely? If it is a
webpage, where should the server be located, on one or more of the cages, on
another computer on the LAN, offsite? Are there any commercial sites that host
webpages with real-time updates, like Github or Twitter or somewhere else?

Each Linux single board computer will just have the bare minimum installed, plus
Docker. What is the best way to manage such a computer? Is it best to clone one
or more git repositories in a user home directory and generate Docker images
from them? Or is it better to host all Docker images externally and just run
images from a link? What is the best way to pass information into each image,
environment variables or something else?

What is the best way to manage data from all of the cages? Sets of files stored
locally on each cage that then get backed up to a remote site? Or stored in a
database somewhere?
