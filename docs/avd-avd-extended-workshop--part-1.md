# AVD Extended Workshop, Part 1

!!! Warning "Lab Documents Not Finished"

    DO NOT ENTER! :skull_and_crossbones:{ .heartbeat }

    ![stay back](assets/img/pexels-danne-555709.jpg)

    This document is created from a Cookiecutter template.
    If you see this message - the lab is not finished and likely published for testing purposes.
    Don't use it unless you are the author.

## Demo Details

!!! Warning "Container Requirements"

    CPUs: 8  
    Memory: 32 GB  
    Storage: 64 GB  

    :material-alert-circle-outline:{ .heartbeat } Please request high spec Codespace machines from [Github support](https://support.github.com/) first!

[Start "AVD Extended Workshop, Part 1" in Codespace](https://codespaces.new/{{gh.repository}}/tree/{{gh.branch}}?quickstart=1&devcontainer_path=.devcontainer%2Favd-avd-extended-workshop--part-1%2Fdevcontainer.json){ .md-button .md-button--primary target=_blank}

[Slides](https://{{gh.org_name}}.github.io/{{gh.repo_name}}/slides/avd-avd-extended-workshop--part-1.html){ target=_blank }  
[PDF Slides](https://{{gh.org_name}}.github.io/{{gh.repo_name}}/pdfs/avd-avd-extended-workshop--part-1.pdf){ target=_blank }  

!!! Info "Last reviewed: 29/04/2024"

    Demos and labs reviewed over 6 month age may be outdated.

## Lab Topology

![lab topology](assets/img/avd-avd-extended-workshop--part-1/atd-l3ls.png)

## How To Run The Lab on Your Machine

It is possible to run the lab on your local machine (or any server) instead of using Github Codespaces.  
You can [download all required lab files here](https://arista-netdevops-community.github.io/one-click-se-demos/lab_archives/avd-avd-extended-workshop--part-1.tar.gz).  
However you must take care of you VSCode setup and setting up environment variables. Also keep in mind that auto-downloaded image will not work on ARM-based MacBooks.

## How To Run The Demo

???+ Tip "Wait until cEOS-lab image will be imported"

    You can confirm if image was imported correctly with `docker image ls`.  
    In some rare cases the cEOS-lab image may fail to be downloaded.
    For example due to incorrecte token or other API failure on arista.com.  
    In that case you can upload the image manually by right-clicking the Explorer tab of the VSCode interface.

```bash
# 1. start cLab
make start
```

???+ Tip "Wait until all devices will start streaming to CVaaS."

    This may take a while.
