# debtap

> Convert .deb packages into Arch Linux packages.
> More information: <https://github.com/helixarch/debtap>

- Update debtap database (before first run)

`sudo debtap -u`

- Convert a package

`debtap {{package.deb}}`

- Convert a package (bypass all questions)

`debtap -Q {{package.deb}}`
