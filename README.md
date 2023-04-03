# Huizhe Di's Curriculum Vitae

[![Build](https://github.com/core-man/cv/actions/workflows/build.yaml/badge.svg)](https://github.com/core-man/cv/actions/workflows/build.yaml)

These are the LaTeX sources for my academic CV.

## Build

I used [TinyTeX](https://yihui.org/tinytex/) to build the my CV on WSL2 (Ubuntu 20.04) and M2 pro Macbook Pro

1. 	Install TinyTeX:

		wget https://yihui.org/tinytex/install-bin-unix.sh
		./install-bin-unix.sh

2. 	Install LaTeX packages needed by the CV template:

		make install_packages

3. 	Build the CV:

		make

## Acknowledgemnt

The CV templates are modified from https://github.com/leouieda/cv and https://github.com/core-man/cv.
