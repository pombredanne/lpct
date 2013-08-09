# lsprofcalltree

lsprofcalltree.py: lsprof output which is readable by kcachegrind

Original credit:

David Allouche
Jp Calderone & Itamar Shtull-Trauring
Johan Dahlin

(emails unknown)

Enhanced by Peter Waller (p@pwaller.net).

# Improvements:

* It is installed by pip to ${prefix}/bin as lpct
* If a virtualenv is active, modules inside that virtualenv are available
* It automatically searches the $PATH for executables
* It prints the name of the file that was output

For example, it can be invoked as so:

	lpct nosetests