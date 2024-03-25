# valiantlynx general-config

default configurations for valiantlynx fleet of projects. so it only contains the configurations that are common to all projects.
e.g. themes, colors, fonts, etc.

# current configurations
- [x] theme
- [x] icons
- [x] site metadata
- [] fonts
- [] colors
- [] images
- [] social media


# usage of changeset
- `git tag -l`
- `yarn changeset`

git subtree add --prefix=packages/general-config https://github.com/valiantlynx/general-config.git main --squash
git subtree pull --prefix=packages/general-config https://github.com/valiantlynx/general-config.git main --squash
git subtree push --prefix=packages/general-config https://github.com/valiantlynx/general-config.git main
