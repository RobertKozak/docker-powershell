# Docker PowerShell
Microsoft's PowerShell on Ubuntu 16.04 (Xenial) running in a docker container.

[![](https://images.microbadger.com/badges/image/robertkozak/docker-powershell.svg)](https://microbadger.com/images/robertkozak/docker-powershell "Get your own image badge on microbadger.com")

[![](https://images.microbadger.com/badges/version/robertkozak/docker-powershell.svg)](http://microbadger.com/images/robertkozak/docker-powershell "Get your own version badge on microbadger.com")

A simple demonstration of getting Powershell into a Docker container. 

This is now using a bash script to build from the source (based off of https://github.com/PowerShell/PowerShell/blob/master/tools/download.sh)

See [Dockerfile](https://raw.githubusercontent.com/RobertKozak/Docker-Powershell/master/Dockerfile) for more information.

# Usage
To run PowerShell:

    docker run -it --rm robertkozak/docker-powershell

 
As an alias:
    
    alias posh='docker run -it --rm robertkozak/docker-powershell'
    posh get-command
