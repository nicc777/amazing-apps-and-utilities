
- [amazing-apps-and-utilities](#amazing-apps-and-utilities)
- [Command Line Utilities for Laptop/Workstation](#command-line-utilities-for-laptopworkstation)
  - [Command Line](#command-line)
  - [GUI Applications](#gui-applications)
  - [Containers/Docker and Kubernetes](#containersdocker-and-kubernetes)
  - [My favorite `krew` plugins](#my-favorite-krew-plugins)
- [Emulation and Retro Computing](#emulation-and-retro-computing)
  - [Software Repositories](#software-repositories)
- [Online Tools (Websites/Plugins/Etc.)](#online-tools-websitespluginsetc)
- [My Own Homegrown Stuff](#my-own-homegrown-stuff)
- [List of Interesting Web Sites (various topics)](#list-of-interesting-web-sites-various-topics)
- [GitHub Projects of Interest](#github-projects-of-interest)
- [Development and Software Engineering](#development-and-software-engineering)
  - [Python](#python)
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
| [irssi](https://irssi.org/          )        | Internet Relay Chat (IRC) Client                             | Be sure to check out the [Docker Version](https://hub.docker.com/_/irssi) - easy to get started and probably a little more secure.                                                                                                                                                  |
| [mc](https://midnight-commander.org/)        | File Manager                                                 | For those old enough to remember, this is a [Norton Commander](https://en.wikipedia.org/wiki/Norton_Commander) clone, arguably one of the best CLI visual file managers which is why it is still widely used today. IMHO this should be default even with OS minimal installations. |
| [nmap](https://nmap.org/)                    | Network Security Scanner                                     | If you work with networks or with network services, you need this tool!                                                                                                                                                                                                             |
| [Oh My Zsh](https://ohmyz.sh/)               | Managing Zsh configs                                         | I can't live in ZSH without this! Period!                                                                                                                                                                                                                                           |
| [wget](https://www.gnu.org/software/wget/)   | Retrieve web pages and web content                           | Easily download content from HTTP or FTP sites. You can also mirror sites. Lots of command line options and a really powerful tool. I often switch between both `curl` and `wget`, depending on specific needs. `curl` is more for troubleshooting and `wget` to retrieve content.  |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp)   | Command line web video downloader                            | I use this to save important videos from various online sources.                                                                                                                                                                                                                    |


## GUI Applications

| Name                                                | Description              | Personal Notes                                                                                                                                   |
|-----------------------------------------------------|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| [draw.io](https://github.com/jgraph/drawio-desktop) | Diagram Tool             | Excellent selection of stencils including AWS, Kubernetes and many more. Includes stencils for modeling like UML and [C4](https://c4model.com/). |
| [Nyxt Browser](https://nyxt.atlas.engineer/)        | Web Browser              | The hacker's power-browser. Lots of emacs vibes (key bindings, buffers etc.)                                                                     |
| [VSCode](https://code.visualstudio.com/)            | IDE                      | Currently my favorite IDE. Runs basically anywhere - even in a web browser if you use services like [GitPod](https://gitpod.io/).                |


## Containers/Docker and Kubernetes

| Name                                                       | Description                                                                         | Personal Notes                                                                                                            |
|------------------------------------------------------------|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [Docker](https://docs.docker.com/get-docker/)              | Basically the industry standard container engine                                    | I use this as my primary tool for creating container images.                                                              |
| [Helm](https://helm.sh/)                                   | The package manager for Kubernetes. Think APT, RPM etc. but for Kubernetes.         | Powerful package management option. Works great with GitOps tools like [ArgoCD](https://argoproj.github.io/cd/)           |
| [k9s](https://k9scli.io/)                                  | K9s is a terminal based UI to interact with your Kubernetes clusters.               | Great for viewing a lot of information quickly. Delve into detail quickly. A tool I now use on a daily basis.             |
| [kube-ps1](https://github.com/jonmosco/kube-ps1)           | Adds the current K8s info on `kubectl` to Bash/Zsh prompt (i.e. the `$PS1`).        | Very quick way to see to which cluster you are issuing commands to from the prompt                                        |
| [kustomize](https://kustomize.io/)                         | Kubernetes native configuration management                                          | A simple/easy to use utility to maintain different configuration per environment - a lightweight Helm values if you will. |
| [krew](https://github.com/kubernetes-sigs/krew)            | Krew is the package manager for kubectl plugins                                     | Installation and usage is straight forward and easy.                                                                      |

## My favorite `krew` plugins

| Name                                                                               | Description                                                                         | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [ktop](https://github.com/vladimirvivien/ktop)                                     | A top-like tool for your Kubernetes cluster.                                        |                                                                                                |
| [resource-capacity](https://github.com/robscott/kube-capacity) aka `kube-capacity` | Provides an overview of the resource requests, limits, and utilization in a cluster | Convenient way to keep an eye on resources from the command line.                              |

# Emulation and Retro Computing

| Name                                                                               | Description                                                                         | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [PCem](https://pcem-emulator.co.uk/)                                               | Emulate older hardware.                                                             | v17 Still worked great on Ubuntu 20.04, but I have my doubts about the future of this project. |
| [qemu](https://www.qemu.org/)                                                      | A generic and open source machine emulator and virtualizer                          | Also refer to [my Qemu Notes](https://github.com/nicc777/qemu-notes)                           |


## Software Repositories

| Name                                               | Description                                                                                                             | Personal Notes                                                                                 |
|----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [WinWorld](https://winworldpc.com/home)            | WinWorld is an online museum dedicated to the preservation and sharing of vintage, abandoned, and pre-release software. | Great resource for software if you are into retro computing.                                   |
| [RPM Pbone](http://rpm.pbone.net/)                 | RPM Repository that contains a lot of older RPM's as well.                                                              | Great for searching for older RPM's                                                            |


# Online Tools (Websites/Plugins/Etc.)

_**Note**_: My preferred web browser is [Firefox](https://www.mozilla.org/en-US/firefox/new/). Therefore, any plugins I mention is what I use in Firefox. Occasionally there might be an exception, and I will try to remember to point these out. On the other hand, most plugins support multiple browsers.

| Name                                          | Description                                                      | Free/Paid   | Personal Notes                                                                                                                                                                                                                             |
|-----------------------------------------------|------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Diigo](https://www.diigo.com/)               | Online Bookmarks, notes and annotation site with Browser plugins | Either      | Been using it for years, before browsers supported cloud sync. I still have a lot of stuff there and still use it occasionally. With the browser plugin, it can augment your google searches with results from your diigo library as well. |
| [GitPod](https://gitpod.io)                   | VSCode (and InteliJ) IDE in the web browser.                     | Either      | Seamlessly integrate with GitHub and/or GitLab. Really good for on the move coding, especially from iPad.                                                                                                                                  |
| [JWT.io](https://jwt.io/)                     | JWT.IO allows you to decode, verify and generate JWT             | Free        | I use it mostly to decode JSON Web Tokens (JWT). Works great.                                                                                                                                                                              |
| [MS Office 365](https://www.office.com/)      | Office productivity suite. SaaS.                                 | Paid        | I switch often between Windows, Linux and Mac. MS Office 365 is my goto office suite that I now use almost exclusively in the browser.                                                                                                     |
| [Wunderground](https://www.wunderground.com/) | Great weather site                                               | Adds        | My goto for daily weather. Has a 10 day forecast. Allows to connect to personal weather stations for detailed observation at a location. Historic weather data, air quality and various other features.                                    |

# My Own Homegrown Stuff

| Name                                                                                                                                                       | Description                                                                         | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [get_kubectl.sh](https://gist.githubusercontent.com/nicc777/1475f894261f17dcd5c71b24e3f2f81d/raw/4c24cd8fe2cf787948f04e188560f11514ac170d/get_kubectl.sh)  | Always get the latest version of `kubectl` on Linux with this command               | Quick and easy way for me to keep `kubectl` up to date.                                        |

# List of Interesting Web Sites (various topics)

Maintained on a separate page [here](./websites.md)

# GitHub Projects of Interest

| Name                                                                               | Description                                                                                                                                                          | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [NiceGUI](https://github.com/zauberzeug/nicegui)                                   | NiceGUI is an easy-to-use, Python-based UI framework, which shows up in your web browser. You can create buttons, dialogs, Markdown, 3D scenes, plots and much more. | Still need to try this out...                                                                  |
| [Diagrams](https://github.com/mingrammer/diagrams)                                 | Diagrams lets you draw the cloud system architecture in Python code. It was born for prototyping a new system architecture design without any design tools.          | Interesting, but is there a real use case?                                                     |
| [Mermaid](https://github.com/mermaid-js/mermaid)                                   | Generate diagrams from markdown-like text.                                                                                                                           | Interesting, but is there a real use case?                                                     |
| [GoAccess](https://github.com/allinurl/goaccess)                                   | Quick access log analysis.                                                                                                                                           | [private gist notes](https://gist.github.com/nicc777/f677f35391831c4b898027bfba2223d9)         |

# Development and Software Engineering

## Python

| Name                                                                               | Description                                                                                                                                                          | Personal Notes                                                                                 |
|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)      | Style guide                                                                                                                                                          | I use it mostly for the docstring templates.                                                   |

# NO LONGER USING

| Name                                         | Description             | Why I stopped                                                                                                                                 |
|----------------------------------------------|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| [atuin](https://github.com/ellie/atuin)      | Better shell history    | The initial experience was amazing, but after a while I found it annoying. The standard ZSH history features is what I'm sticking to for now. |



