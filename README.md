# dotfiles
Clone into `$HOME`. 
cd into the repo and run `stow foo` to create symlinks for program foo in `~/.config/foo`.

To run stow for all directories run `stow */`

```
~
├── Desktop
├── Documents
├── dotfiles (this repo)
│   ├── foo
│   │   └── .config
│   │       └── foo
│   │           ├── foo-theme.conf
│   │           └── foo.conf
│   └── README.md
├── Public
├── .config
│   ├── foo
│   │   ├── foo-theme.conf (link)
│   │   └── foo.conf (link)
├── Templates
└── Videos

```
