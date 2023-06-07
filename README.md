# plugget-pkgs

### add manifest
`app folder / plugin id / version.json`, 
e.g. blender/bqt/1.0.0.json

manifest should have
| key | description |
| --- | ----------- |
| repo_url|  the URL of the git repo | 
| repo_SHA | commit id if you want to point to a specific version or commit |
| repo_paths | (optional) set a subdirectory if the plugin is not in the root of the repo| 
| name| (optional) display name, not garantueed to be unique, same as folder name? do we need this?| 

public manifest repo for [plugget](https://github.com/hannesdelbeke/plugget), imitating structure of [winget community repo](https://github.com/microsoft/winget-pkgs)
