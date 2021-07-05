# FIG
>**About FIG**  
>
>I am creating the *FIG* operating system, which stands for FIG isn't GNU. GNU inturn stands for GNU's Not UNIX.  
>*Look at https://www.gnu.org*.  
>Unix stylized as UNIX is the most copied operating system as it relatively simple to implement, manage, recreate, etc.  
>*look at https://en.wikipedia.org/wiki/Unix*.  
>In Unix and other systems, like FIG, GNU/Linux, FreeBSD, ... everything just plain works.  
>Enough of this, to the main point now:

The FIG operating system will have the following structure  
**the :DIRNAME indicates that there is/are  these regular directories as well as these in the /Computer directory are symlinked to the regular directories**  
- /  
    - /Computer  
        -  /Computer/Applications:/usr/bin  
        - /Computer/Boot:/boot  
        - /Computer/Devices:/dev  
        - /Computer/CD-ROM:/cdrom  
        - /Computer/ConfigFiles:/etc  
        - /Computer/Users:/home 
          - /Computer/Users/username:/home/username:~
            - /Computers/Users/username/ConfigFiles:~/.config  
        - /Computer/Library:/usr/lib  
        - /Computer/Media:/media  
        - /Computer/OptionalSoftware:/opt  
        - /Computer/RunningPrograms:/proc  
        - /Computer/Admin:/root  
        - /Computer/TemporaryFiles:/tmp  
        - /Computer/Resources:/usr  
        - /Computer/System:/
        - /Computer/AppInstallations:/usr  
## I have two problems with GNU/Linux
- First is that it is GNU/Linux that means it is really not a single project. 
- For example, the Linux *foundation* which develops the kernel, the GNU project which develops the whole core opeating system,
- the X.org foundation which build the X server, individual window managers or desktop environments
- (which are independant of distros or combined) and 
- individual distributions which develop their own systems.
- GNU was intended as to be a complete and one operating system like FreeBSD, NetBSD, MINIX, or proprietary SunOS, 
- NeXTSTEP, IRIX, MacOS, ..., or non-UNIX: MS-DOS,Windows,VMS but the GNU project has failed to do so because of the
- kernel and the time to respond of the GNU project.
- Eventhough the GNU operating system is fragmented, I still use it,
- as I like the free software philosophy and is  better than proprietary software because of this.
- The license of FIG is GNU GPL because  I want to pass these freedoms to everyone.
- The common proprietary operating systems like Windows and MacOS are single operating systems as are
- free/libre ie FreeBSD, MINIX.
- I left out the graphical system in the last one on purpose. 
- Graphical systems are the most common method of interaction to the computer.
- I have kept a huge focus on the graphical and command-line systems. The structure of the system reflects this.   
- Everyone uses the graphical user interface or GUI,so
- FIG will have a really good graphical intreface like MacOS, but
    - FIG is completely free/libre software
    - FIG doesn't hide things from you for example hidden files and diretories are named .dir instead of dir and can be easily found.
    - FIG also encourages command line usage, so all the software is in /usr/ or /usr/share and can be easily removed.
    - Config files are in /Computer/ConfigFiles/*ProgramName* or /etc/*ProgramName* or ~/.config/*ProgramName*
    - All of these directories are wiped in updation and rewritten, through the regular mechanism as *pkgman-name* install *pkg-name*
    - can be used, the root directory of the package should contain
    - etc, .config, lib, rootdir(*only for special packages*) and *programname* as subdirectories
    - so that other files can be put for example in specific locations during installation and be rewritten during update.
    - FIG doesn't have dependancies.
    - FIG has it's own advanced interface similar to X11 and maybe called X12.
    - FIGUI or X12 is better as it is linked together and has the GPL license.
    - [video](https://www.youtube.com/watch?v=cj02_UeUnGQ)
    - The improvements were proprietarized by the companies, or distributed under different license, this not only
    - reduced freedom, but also caused the thing to be fragmented, so there were different X11 servers, toolboxes,
    -  display engines, window managers, desktop environments, default apps, all in myriads of licenses.
    - It will be licensed under the GPL to prevent fragmentation and prevent UNIX wars 2.0
    - FIG will have a better toolbox and everything than X11 because of the GPL license and hindsight.
    - there will be a newer executable format, that is easier to understand and library files, not like ELF
    - there will be an easier git-like program that is better than git  because it has subdirectories
    - visible and hashes and timestamps in a hidden file, hidden files don't count in hashes so it can be reverted without the command,
    - and the history is visible in folder structure. 
 - Let's hope either this is implemented in GNU itself, so GNU has this, or FIG or  *new name of FIG* is implemented. 








- (Please don't  refer to them as win such-and-such but w something, like w32 or windows32 instead win32)
- FIG may/may not be the real/final name, and just be a code name.
