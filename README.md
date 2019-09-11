
gapFinisher - a reliable gap filling pipeline for SSPACE-LongRead scaffolder output

Juhana Kammonen 8.12.2017

-------------------------------

PREREQUISITE: A successful run of SSPACE-LongRead so that the directory "inner-scaffold-sequences" is created.

a. Installation
---------------

1. Get and install MATLAB Compiler runtime (MCR) from:

	https://sourceforge.net/projects/fgap/files/MCR_LINUX64b.tar.gz

UNIX archives are in the center column of that webpage

2. In your preferred installation directory (e.g. /usr/bin/ ; /home/user/bin/ ):

	wget http://www.helsinki.fi/~jkammone/gapFinisher.zip
	unzip gapFinisher.zip
	cd gapFinisher
	chmod -R 775 *

NOTE: sudo these if needed


b. Running gapFinisher
----------------------

After steps in a.

	./gapFinisher -i <PATH_TO_SSPACE_LONGREAD_OUTPUT_FOLDER> -l <PATH_TO_PACBIO_LONG_READS_USED_BY_FGAP> -m <MCR_LOCATION>
	

c. Contributors

Since version 0.1, following people have contributed to gapFinisher:

Juhana I Kammonen
Olli-Pekka Smolander
Ari Löytynoja
Pia K Laine
Lars Paulin
Pedro AB Pereira
Patrik Koskinen
Jukka Jernvall
Petri Auvinen
Carolin Kolmeder
Tarja Sundell


d. Disclaimer

GPL version 3:

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>



e. How to cite gapFinisher

Where applicable, please cite gapFinisher as:

Kammonen, J.I, Smolander, OP., Paulin, L., Laine, P., Pereira, PAB., Koskinen, P., Jernvall J. & Auvinen, P.
gapFinisher: a reliable gap filling pipeline for SSPACE-LongRead scaffolder output. PLoS ONE 14(9): e0216885.

