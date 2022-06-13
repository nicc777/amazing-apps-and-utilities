
- [amazing-apps-and-utilities](#amazing-apps-and-utilities)
- [Command Line Utilities for Laptop/Workstation](#command-line-utilities-for-laptopworkstation)
  - [Command Line](#command-line)
  - [GUI Applications](#gui-applications)
  - [Containers/Docker and Kubernetes](#containersdocker-and-kubernetes)
  - [My favorite `krew` plugins](#my-favorite-krew-plugins)
- [Online Tools (Websites/Plugins/Etc.)](#online-tools-websitespluginsetc)
- [My Own Homegrown Stuff](#my-own-homegrown-stuff)
- [NO LONGER USING](#no-longer-using)


# amazing-apps-and-utilities

Applications, tools, utilities etc. I find interesting and useful.

I use this repo is a kind of a list of useful stuff I run into. Some I use often, while others where just really interesting. 

This is obviously personal and may include a lot of stuff more-or-less useless for most average computer users. But you are still welcome to explore of course :-)

The list is will grow over time. At some point I may create a way to document old/unmaintained/defunct apps - mainly just for historic reference.

# Command Line Utilities for Laptop/Workstation

## Command Line

| Name                                         | Description                                                  | Personal Notes                                                                                                                                                                                                                                                                      |
|----------------------------------------------|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [btop](https://github.com/aristocratos/btop) | A nicer `top`                                                | Get a much better view of your system resources from the command line                                                                                                                                                                                                               |
| [curl](https://curl.se/)                     | Tool and library for transferring data with URL              | My goto for testing web apps and API's                                                                                                                                                                                                                                              |
| [duf](https://github.com/muesli/duf)         | Disk Usage/Free Utility                                      | Occasionally I use this tool to view my disk space usage. Love the layout.                                                                                                                                                                                                          |
| [dua](https://github.com/Byron/dua-cli/)     | Disk Usage Analyzer                                          | More granular than `duf` and interactive. Find what is actually using all your disk space.                                                                                                                                                                                          |
| [mc](https://midnight-commander.org/)        | File Manager                                                 | For those old enough to remember, this is a [Norton Commander](https://en.wikipedia.org/wiki/Norton_Commander) clone, arguably one of the best CLI visual file managers which is why it is still widely used today. IMHO this should be default even with OS minimal installations. |
| [nmap](https://nmap.org/)                    | Network Security Scanner                                     | If you work with networks or with network services, you need this tool!                                                                                                                                                                                                             |
| [Oh My Zsh](https://ohmyz.sh/)               | Managing Zsh configs                                         | I can't live in ZSH without this! Period!                                                                                                                                                                                                                                           |
| [wget](https://www.gnu.org/software/wget/)   | Retrieve web pages and web content                           | Easily download content from HTTP or FTP sites. You can also mirror sites. Lots of command line options and a really powerful tool. I often switch between both `curl` and `wget`, depending on specific needs. `curl` is more for troubleshooting and `wget` to retrieve content.  |


## GUI Applications

| Name                                                | Description              | Personal Notes                                                                                                                                   |
|-----------------------------------------------------|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| [draw.io](https://github.com/jgraph/drawio-desktop) | Diagram Tool             | Excellent selection of stencils including AWS, Kubernetes and many more. Includes stencils for modeling like UML and [C4](https://c4model.com/). |
| [VSCode](https://code.visualstudio.com/)            | IDE                      | Currently my favourite IDE. Runs basically anywhere - even in a web browser if you use services like [GitPod](https://gitpod.io/).               |


## Containers/Docker and Kubernetes

| Name                                                       | Description                                                                         | Personal Notes                                                                                                   |
|------------------------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| [Docker](https://docs.docker.com/get-docker/)              | Basically the industry standard container engine                                    | I use this as my primary tool for creating container images.                                                     |
| [Helm](https://helm.sh/)                                   | The package manager for Kubernetes. Think APT, RPM etc. but for Kubernetes.         | Powerfull package management option. Works great with GitOps tools like [ArgoCD](https://argoproj.github.io/cd/) |
| [kube-ps1](https://github.com/jonmosco/kube-ps1)           | Adds the current K8s info on `kubectl` to Bash/Zsh prompt (i.e. the `$PS1`).        | Very quick way to see to which cluster you are issuing commands to from the prompt                               |
| [krew](https://github.com/kubernetes-sigs/krew)            | Krew is the package manager for kubectl plugins                                     | Installation and usage is straight forward and easy.                                                             |

## My favorite `krew` plugins

| Name                                                                               | Description                                                                         | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [ktop](https://github.com/vladimirvivien/ktop)                                     | A top-like tool for your Kubernetes cluster.                                        |                                                                                                |
| [resource-capacity](https://github.com/robscott/kube-capacity) aka `kube-capacity` | Provides an overview of the resource requests, limits, and utilization in a cluster | Convenient way to keep an eye on resources from the command line.                              |


# Online Tools (Websites/Plugins/Etc.)

_**Note**_: My preferred web browser is [Firefox](https://www.mozilla.org/en-US/firefox/new/). Therefore, any plugins I mention is what I use in Firefox. Occasionally there might be an exception, and I will try to remember to point these out. On the other hand, most plugins support multiple browsers.

| Name                                     | Description                                                      | Free/Paid   | Personal Notes                                                                                                                                                                                                                             |
|------------------------------------------|------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Diigo](https://www.diigo.com/)          | Online Bookmarks, notes and annotation site with Browser plugins | Either      | Been using it for years, before browsers supported cloud sync. I still have a lot of stuff there and still use it occasionally. With the browser plugin, it can augment your google searches with results from your diigo library as well. |
| [GitPod](https://gitpod.io)              | VSCode (and InteliJ) IDE in the web browser.                     | Either      | Seamlessly integrate with GitHub and/or GitLab. Really good for on the move coding, especially from iPad.                                                                                                                                  |
| [MS Office 365](https://www.office.com/) | Office productivity suite. Saas.                                 | Paid        | I switch often between Windows, Linux and Mac. MS Office 365 is my goto office suite that I now use almost exclusively in the browser.                                                                                                     |

# My Own Homegrown Stuff

| Name                                                                                                                                                       | Description                                                                         | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [get_kubectl.sh](https://gist.githubusercontent.com/nicc777/1475f894261f17dcd5c71b24e3f2f81d/raw/4c24cd8fe2cf787948f04e188560f11514ac170d/get_kubectl.sh)  | Always get the latest version of `kubectl` on Linux with this command               | Quick and easy way for me to keep `kubectl` up to date.                                        |

# NO LONGER USING

| Name                                         | Description             | Why I stopped                                                                                                                                 |
|----------------------------------------------|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| [atuin](https://github.com/ellie/atuin)      | Better shell history    | The initial experience was amazing, but after a while I found it annoying. The standard ZSH history features is what I'm sticking to for now. |

