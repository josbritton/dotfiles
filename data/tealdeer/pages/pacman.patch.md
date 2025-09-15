> Patch:

- List package contents:
`pacman -Ql {{package}}`

- Set package install reason to explicit:
`pacman -D --asexplicit {{package}}`

- Set package install reason to dependency:
`pacman -D --asdeps {{package}}`

- [R]emove a package and its dependencies, cleaning config files:
`pacman -Rsn {{package}}`

- List (native) orphan packages (installed as [d]ependencies but not actually required by any package):
`pacman -Qndt`

- List explicitly installed native packages:
`pacman -Qne`
