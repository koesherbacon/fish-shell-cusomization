# fish-shell-cusomization
I'll use this repo to share my Fish Shell customizations, such as my prompts, color schemes, and aliases

I have created several prompts.  My latest consists of one for my normal every-day user and another for the root user when using 'sudo su'.  They've very similar, each shows the current directory.  The root one shows a message indicating that you're currently using the root account, which may come in handy to avoid any accidents.

My aliases cover everything from short-hand repo updates, software upgrades, opening various files and folders without having to navigate to them, and many more personal time-savers.  Naturallly, you're totally free to use them yourself, although you will probably want to change them to better suit your own wants and needs.  For example, Nemo is the file-manager I prefer to use; therefor any alias which opens a folder uses Nemo.  I also use Thunar on occasion, so there are other aliases which include using Thunar instead of Nemo for that particular opperation.  

My desktop preference is XFCE, therefor a significant number of commands are made for it.  Currently, my locker is light-locker, which means my shortcut for locking my computer utilizes it.  In the past I also used xflock4 in the past so there's a commented-out line for it as well.

Finally, I'm a distro-tester.  Although I tend to only have one distro installed on my computer I have used several while becoming moroe proficient with Linux overall.  Currently, I am using Manjaro, so my package manager is 'yaourt' and/or 'yay.  (Yes, I know that yaourt is become depreciated but I still prefer it over yay... I'm slowly adapting to the change!).  In the past, I used MX-Linux, which is a Debian-based distro.  Not wanting to simply overwrite all my aliases for it, I commented them out, which means aliases for updating the system and repos using 'apt' are commented out, as well as an alias to open the folder '/etc/apt/sources.list.d/' when editing any custom repos.  I also spent a large amount of time using Sabayon, which is a Gentoo-based distro.  It uses a pacmage manager called 'equo', and you guessed it, I have aliases for using it to install, remove and update software.  

Well, I suppose that about covers what this github repo is going to be used for!
