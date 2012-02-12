# Solarized

## Precision colors for machines and people

---

### Solarized

Solarized was created by [Ethan Schoonover][ES] and you can find out more
about the design work that went into it on his [project page][ES-solarized]. If
you would like to use Solarized in editors other than Gedit or on your terminal,
Ethan hosts a [repo][SolarizedRepo] that combines all the available ports in one
place.

### Solarized for Gedit

Solarized was initially ported for Gedit by [Matthew Cantelon][MC] and can be
found at <http://github.com/mattcan/solarized-gedit>.

### Installation

You can download the files in one of two ways:

* using `git clone git://github.com/mattcan/solarized-gedit.git`
* using the **Download** button to get the ZIP file and extracting the files to
  a folder

Once the files are on your PC, copy `solarized-light.xml` and `solarized-dark.xml`
to one of these folders:

* if you are the only user on your computer

		cp solarized-* ~/.local/share/gtksourceview-3.0/styles

* if you want everyone on your PC to be able to use the styles (*Note: below
  path is for Ubuntu*)

		sudo cp solarized-* /usr/share/gtksourceview-3.0/styles
	
[ES]: http://ethanschoonover.com
[ES-Solarized]: http://ethanschoonover.com/solarized
[SolarizedRepo]: https://github.com/altercation/solarized
[MC]: http://matthewcantelon.ca
