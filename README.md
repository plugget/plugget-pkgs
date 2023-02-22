# plugget-pkgs

### add manifest
`app folder / plugin id / version.json`, 
e.g. blender/bqt/1.0.0.json

manifest should have
- name: display name, not garantueed to be unique, same as folder name? do we need this?
- plugin_name: name used by the app to call the plugin, usually needs to be the same as the name of the plugin folder or python module
- repo_url: the URL of the git repo 
- subdir (optional): set a subdirectory if the plugin is not in the root of the repo

public manifest repo for [plugget](https://github.com/hannesdelbeke/plugget), imitating structure of [winget community repo](https://github.com/microsoft/winget-pkgs)
