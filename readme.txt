Gnome-Cupertino
Author: Rafa Cobreros rafacobreros@gmail.com
License: GPL
Original theme in: http://gnome-look.org/content/show.php/Gnome+Cupertino?content=147061

Customization tips:
1.- Select enviroment Unity or Gnome-Shell
2.- Style for nautilus
3.- Style for titlebar buttons
4.- Style for tabs

NOTE:
	- Some changes require close and open session after them


recommended font:
http://www.fontpalace.com/font-details/Lucida+Sans/

------------------------------------------------
* 1.- Select your enviroment *
------------------------------------------------
Edit (gedit) the file ../Gnome-Cupertino/gtk-3.0/gtk.css, go to the last line of the file

You'll find two options

	a.- If you use Gnome-shell and/or Cinnamon
	@import url("gnome-apps.css");

	b.- If you use Unity (GlobalMenu)
	@import url("unity-apps.css");

	(edit the line 'import' according your enviroment) 

------------------------------------------------
* 2.- Select style for nautilus and enviroment *
------------------------------------------------
If you use nautilus 3.6.x not need to do anything in this section !!

Edit (gedit) the file ../Gnome-Cupertino/gtk-3.0/gtk.css
go to the last line of the file, there are seven options for nautilus:

	- If you use Nautilus 3.6.x for gnome-shell 3.6.x and/or unity (by default)
		@import url("nautilus36.css"); 

    - If you use Nautilus 3.4.x, depending on whether you use gnome-shell or unity:
	(3 options for gnome-shell)
	1.- "gnome-nautilus34-gray.css"  		(nautilus sidebar and toolbar dark gray)
	2.- "gnome-nautilus34-light.css" 		(nautilus sidebar and toolbar light)
	3.- "gnome-nautilus34-gray-light.css"   (nautilus sidebar dark gray and toolbar light)

	(3 options for UNITY)
	1.- "unity-nautilus34-gray.css"  		
	2.- "unity-nautilus34-light.css" 		
	3.- "unity-nautilus34-gray-light.css" 

edit (please carefully) the corresponding line "@import" according to the style of nautilus you want,
to make it ONE of the seven (not both)

@import url("nautilus36.css"); 
	or
@import url("gnome-nautilus34-gray.css");
	or
@import url("gnome-nautilus34-light.css"); 
	or
@import url("gnome-nautilus34-gray-light.css"); 
	or
@import url("unity-nautilus34-gray.css");
	or
@import url("unity-nautilus34-light.css"); 
	or
@import url("unity-nautilus34-gray-light.css"); 


-----------------------------------------
* 3.- Select style for titlebar buttons *
-----------------------------------------
If you prefer the buttons Lion style for titlebar:
Copy the contents of the file "metacity-lion-buttons.tar.gz" in folder .. /Gnome-Cupertino/metacity-1/

If you prefer the buttons Snow Leopard style for titlebar:
Copy the contents of the file "metacity-sl-buttons.tar.gz" in folder .. /Gnome-Cupertino/metacity-1/

also for unity if necessary:
"unity-lion-buttons.tar.gz" in folder .. /Gnome-Cupertino/unity/
or
"unity-sl-buttons.tar.gz" in folder .. /Gnome-Cupertino/unity/

------------------------------
* 4.- Select style for TABS *
------------------------------
Edit (gedit) the file ../Gnome-Cupertino/gtk-3.0/gtk.css

Go to the line where it says
@import url("tabs.css");

and modify it according to the option you want

1.- tabs dark gray (full)
@import url("tabs-dark.css");

2.- tabs themed blue (full)
@import url("tabs-themed.css");

3.- tabs with  blue highlight 
@import url("tabs.css");

4.- tabs with dark gray highlight
@import url("tabs-mono.css");

5.- more traditional style tabs
@import url("tabs-classic.css");

(Be careful to leave only ONE of the five)


