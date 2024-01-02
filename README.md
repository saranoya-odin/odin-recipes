# What is this? 

This is a collection of silly recipes, to be prepared by or alongside small children (2-4 years old). It was created using only pure HTML.  

It is the first small project I created while running through the Foundations portion of the free and open Full Stack Web Develoopment course at [The Odin Project][TOP paths]. It is not intended to be a real, functional web application. Rather, TOP includes it in the curriculum as a way to have course participants familiarize themselves with how to use HTML - and some of its most basic tags - to structure very simple pages on the web.  

# What did I learn? 

## Prerequisites

This wasn't my first ever project working with HTML - not by a long shot. The strictly HTML-related requirements for this project taught me nothting I hadn't done before. That said, doing this [recipes assignment][recipes project assignment] provided me with an excuse to brush up on the following webdev-adjacent topics:

* How to set up a [VPS on Linode / Akamai][Linode getting started guide]. TOP recommends the use of Linux or MacOS as a development platform. However, at the time of starting this course I only had access to my work laptop running Windows, without the admin privileges to install Linux or a Virtual Machine on it. Therefore, I chose to go the slightly unothodox route of 'renting' SSH access to a virtual private server running Ubuntu, from Linode / Akamai.
* How to [install OpenSSH][Microsoft get started guide openSSH] via GUI on a Windows laptop to which one lacks admin access. 
* How to [generate a public/private SSH key pair][GitHub SSH keygen instructions] for SSH access without requiring a password, both to my development environment (Linode / Akamai) and to GitHub, from within VSCode.
* Where to find and how to [edit the hosts file on Windows][Wikiversity hosts file], to enable SSH access by hostname rather than by IP address.  
* How to [edit remote files in VSCode][VSCode remote dev SSH docs] over SSH.
* How to set up the [Apache Web Server][Linode Apache setup docs] to enable live preview of changes made to files on the remote VPS.  

## HTML

* How to generate [HTML boilerplate][TOP HTML boilerplate] in VSCode.

# Acknowledgements

All images used on this website were generated using Bing Image Creator, which is an AI text-to-image tool powered by [DALL-E 3][ChatGPT homepage for DALL-E 3].

[TOP paths]: https://theodinproject.com/paths
[recipes project assignment]: https://www.theodinproject.com/lessons/foundations-recipes
[Linode getting started guide]: https://www.linode.com/docs/products/compute/compute-instances/guides/set-up-and-secure/
[VSCode remote dev SSH docs]: https://code.visualstudio.com/docs/remote/ssh
[Microsoft get started guide OpenSSH]: https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse
[GitHub SSH keygen instructions]: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
[Wikiversity hosts file]: https://en.wikiversity.org/wiki/Hosts_file/Edit#:~:text=The%20hosts%20file%20is%20a,System32%5Cdrivers%5Cetc%20folder.
[TOP HTML boilerplate]: https://www.theodinproject.com/lessons/foundations-html-boilerplate
[ChatGPT homepage for DALL-E 3]: https://openai.com/dall-e-3
[Linode Apache setup docs]: https://www.linode.com/docs/guides/apache-configuration-basics/