DeployVMs
=========

SYNOPSIS:
Deploying multiple Windows and/or Linux VMs using PowerCli

DESCRIPTION:
This repo contans the following powershell scripts. Each of the powershell scripts contains detailed description within.
Please review the scripts for more details.

ExportVMfolders.ps1  -  This script will export all Virtual Machine folders to an ExportVMfolder.csv file.
                        A sample export (ExportVMfolders_EXAMPLE.csv) is included in this repo.

DeployVM.ps1         -  This script is used to first export a DeployVM.csv file to be used to populate with the
                        desired Virtual Machines to be created.  A sample export (DeployVM_EXAMPLE.csv) is included
                        in this repo. The DeployVM.ps1 will then use the DeployVM.csv to automatically create multiple
                        Virtual Machines.

This repo is a fork of Everything-Virtual. My additions and modifications consist
of adding the ExprtVMfolder.ps1 and several features to the DeployVM.ps1 which is detailed within the script.


CREDITS:
Everything-Virtual
https://github.com/Everything-Virtual/DeployVMs
Vidanez
https://github.com/Vidanez/DeployVMs

Credit goes to Everything-Virtual, Vidanez and Lucd for providing much of the code within this repo.



