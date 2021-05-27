# Installing And Running Sitecore XP With Docker

**By:** Baxter Lane

**On:** May 25, 2021

# Abstract

This document will detail the steps to install Containerized Sitecore XP with Docker

As well as how to login to Sitecore for the first time 

It assumes the Prerequisite steps have all been successfully completed

[VM Prerequisite Setup Instructions](VMPrerequisiteSetupLog.md)

# Steps

<h2>1. Execute a Docker Build</h2>

**From an elevated powershell window run the following commands**

```Powershell
Set-Location -Path "$($env:devReposFolder)sitecore-global-components-server$([System.IO.Path]::DirectorySeparatorChar)"
docker-compose build
```