>**Status:** Executables for N-GenIC & GADGET 2 generated need to run simultion 
# Cosmological Simulations
## Using WSL
https://www.windowscentral.com/how-install-wsl2-windows-10

## Dependencies
Follow these https://masterdesky.github.io/blog/gadget2/gadget2_install  

## N-GenIC
Downloaded from https://wwwmpa.mpa-garching.mpg.de/gadget/  
Edit the make file as in https://masterdesky.github.io/blog/gadget2/gadget2_install  
And run `make` in the directory
>Run the code `sudo apt install $( apt-cache search fftw | cut -d ' ' -f1 | tr "\n" " " )` if you have issues with fttw.  
>If there are any errors, change the include drfftw_mpi.h by srfftw_mpi.h 
>[(reference)](https://snatverk.blogspot.com/2013/02/nbody-simulations-with-gadget2.html)  

## GADGET-2
Downloaded from https://wwwmpa.mpa-garching.mpg.de/gadget/  
Edit the make file as in https://masterdesky.github.io/blog/gadget2/gadget2_install  
And run `make` in the directory

# Other Resourses
### Instalation Tutorial
https://masterdesky.github.io/blog/gadget2/gadget2_install  
https://astrobites.org/2011/04/02/installing-and-running-gadget-2/  
https://astrobites.org/2011/06/11/running-your-first-sph-simulation/  

### Theory Course
https://wintherscoming.no/cmb/theory_math.php  
https://wintherscoming.no/index.php  

### GADGET 4
https://wwwmpa.mpa-garching.mpg.de/gadget4/  

### To get ubuntu GUI
https://github.com/davidbombal/wsl2/blob/main/ubuntu_gui_youtube  
https://askubuntu.com/questions/91657/blank-desktop-when-logging-in-via-xrdp

### N Body Simulation exersises
https://people.ast.cam.ac.uk/~puchwein/NumericalCosmology06.pdf  
https://obswww.unige.ch/lastro/misc/TP4/doc/rst/Exercices/Ex05.html  
https://obswww.unige.ch/lastro/misc/TP4/doc/_downloads/b18a897b99bf2ebbb7413ed151cc8e6b/TP4a_Exercise_5.pdf  

### linux Help
https://thoughtbot.com/blog/the-magic-behind-configure-make-make-install  



