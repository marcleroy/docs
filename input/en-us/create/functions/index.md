﻿---
Order: 40
xref: powershell-reference
Title: PowerShell Reference
Description: PowerShell Functions aka Helpers Reference
RedirectFrom:
  - docs/helpers-reference
  - docs/HelpersReference
---

# PowerShell Functions aka Helpers Reference

<!-- This documentation file is automatically generated from the files at $sourceFunctions using $($sourceLocation)GenerateDocs.ps1. Contributions are welcome at the original location(s). -->

## Summary

In your Chocolatey packaging, you have the ability to use these functions (and others with Chocolatey's [PowerShell Extensions](xref:extensions)) to work with all aspects of software management. Keep in mind Chocolatey's automation scripts are just PowerShell, so you can do manage anything you want.

> :memo: **NOTE** These scripts are for package scripts, not for use directly in PowerShell. This is in the create packages section, not the using Chocolatey section.

## Main Functions

These functions call other functions and many times may be the only thing you need in your [chocolateyInstall.ps1 file](xref:chocolatey-install-ps1).

* [Install-ChocolateyPackage](xref:install-chocolateypackage)
* [Install-ChocolateyZipPackage](xref:install-chocolateyzippackage)
* [Install-ChocolateyPowershellCommand](xref:install-chocolateypowershellcommand)
* [Install-ChocolateyVsixPackage](xref:install-chocolateyvsixpackage)

## More Functions

### Administrative Access Functions

When creating packages that need to run one of the following commands below, one should add the tag `admin` to the nuspec.

* [Install-ChocolateyPackage](xref:install-chocolateypackage)
* [Start-ChocolateyProcessAsAdmin](xref:start-chocolateyprocessasadmin)
* [Install-ChocolateyInstallPackage](xref:install-chocolateyinstallpackage)
* [Install-ChocolateyPath](xref:install-chocolateypath) - when specifying machine path
* [Install-ChocolateyEnvironmentVariable](xref:install-chocolateyenvironmentvariable) - when specifying machine path
* [Install-ChocolateyExplorerMenuItem](xref:install-chocolateyexplorermenuitem)
* [Install-ChocolateyFileAssociation](xref:install-chocolateyfileassociation)

### Non-Administrator Safe Functions

When you have a need to run Chocolatey without Administrative access required (non-default install location), you can run the following functions without administrative access.

These are the functions from above as one list.

* [Install-ChocolateyZipPackage](xref:install-chocolateyzippackage)
* [Install-ChocolateyPowershellCommand](xref:install-chocolateypowershellcommand)
* [Get-ChocolateyWebFile](xref:get-chocolateywebfile)
* [Get-ChocolateyUnzip](xref:get-chocolateyunzip)
* [Install-ChocolateyPath](xref:install-chocolateypath) - when specifying user path
* [Install-ChocolateyEnvironmentVariable](xref:install-chocolateyenvironmentvariable) - when specifying user path
* [Install-ChocolateyPinnedTaskBarItem](xref:install-chocolateypinnedtaskbaritem)
* [Install-ChocolateyShortcut](xref:install-chocolateyshortcut) - v0.9.9+
* [Update-SessionEnvironment](xref:update-sessionenvironment)
* [Get-PackageParameters](xref:get-packageparameters) - v0.10.8+

## Complete List (alphabetical order)

 * [Format-FileSize](xref:format-filesize)
 * [Get-ChecksumValid](xref:get-checksumvalid)
 * [Get-ChocolateyUnzip](xref:get-chocolateyunzip)
 * [Get-ChocolateyWebFile](xref:get-chocolateywebfile)
 * [Get-EnvironmentVariable](xref:get-environmentvariable)
 * [Get-EnvironmentVariableNames](xref:get-environmentvariablenames)
 * [Get-FtpFile](xref:get-ftpfile)
 * [Get-OSArchitectureWidth](xref:get-osarchitecturewidth)
 * [Get-PackageParameters](xref:get-packageparameters)
 * [Get-ToolsLocation](xref:get-toolslocation)
 * [Get-UACEnabled](xref:get-uacenabled)
 * [Get-UninstallRegistryKey](xref:get-uninstallregistrykey)
 * [Get-VirusCheckValid](xref:get-viruscheckvalid)
 * [Get-WebFile](xref:get-webfile)
 * [Get-WebFileName](xref:get-webfilename)
 * [Get-WebHeaders](xref:get-webheaders)
 * [Install-BinFile](xref:install-binfile)
 * [Install-ChocolateyEnvironmentVariable](xref:install-chocolateyenvironmentvariable)
 * [Install-ChocolateyExplorerMenuItem](xref:install-chocolateyexplorermenuitem)
 * [Install-ChocolateyFileAssociation](xref:install-chocolateyfileassociation)
 * [Install-ChocolateyInstallPackage](xref:install-chocolateyinstallpackage)
 * [Install-ChocolateyPackage](xref:install-chocolateypackage)
 * [Install-ChocolateyPath](xref:install-chocolateypath)
 * [Install-ChocolateyPinnedTaskBarItem](xref:install-chocolateypinnedtaskbaritem)
 * [Install-ChocolateyPowershellCommand](xref:install-chocolateypowershellcommand)
 * [Install-ChocolateyShortcut](xref:install-chocolateyshortcut)
 * [Install-ChocolateyVsixPackage](xref:install-chocolateyvsixpackage)
 * [Install-ChocolateyZipPackage](xref:install-chocolateyzippackage)
 * [Install-Vsix](xref:install-vsix)
 * [Set-EnvironmentVariable](xref:set-environmentvariable)
 * [Set-PowerShellExitCode](xref:set-powershellexitcode)
 * [Start-ChocolateyProcessAsAdmin](xref:start-chocolateyprocessasadmin)
 * [Test-ProcessAdminRights](xref:test-processadminrights)
 * [Uninstall-BinFile](xref:uninstall-binfile)
 * [Uninstall-ChocolateyEnvironmentVariable](xref:uninstall-chocolateyenvironmentvariable)
 * [Uninstall-ChocolateyPackage](xref:uninstall-chocolateypackage)
 * [Uninstall-ChocolateyZipPackage](xref:uninstall-chocolateyzippackage)
 * [Update-SessionEnvironment](xref:update-sessionenvironment)
 * [Write-FunctionCallLogMessage](xref:write-functioncalllogmessage)

## Chocolatey for Business Functions

 * [Install-ChocolateyWindowsService](xref:install-chocolateywindowsservice)
 * [Start-ChocolateyWindowsService](xref:start-chocolateywindowsservice)
 * [Stop-ChocolateyWindowsService](xref:stop-chocolateywindowsservice)
 * [Uninstall-ChocolateyWindowsService](xref:uninstall-chocolateywindowsservice)

## Variables

There are also a number of environment variables providing access to some values from the nuspec and other information that may be useful. They are accessed via `$env:variableName`.

### Environment Variables

Chocolatey makes a number of environment variables available (You can access any of these with $env:TheVariableNameBelow):

 * TEMP/TMP - Overridden to the CacheLocation, but may be the same as the original TEMP folder
 * ChocolateyInstall - Top level folder where Chocolatey is installed
 * ChocolateyPackageName - The name of the package, equivalent to the `<id />` field in the nuspec (0.9.9+)
 * ChocolateyPackageTitle - The title of the package, equivalent to the `<title />` field in the nuspec (0.10.1+)
 * ChocolateyPackageVersion - The version of the package, equivalent to the `<version />` field in the nuspec (0.9.9+)
 * ChocolateyPackageFolder - The top level location of the package folder - the folder where Chocolatey has downloaded and extracted the NuGet package, typically `C:\ProgramData\chocolatey\lib\packageName`.

#### Advanced Environment Variables

The following are more advanced settings:

 * ChocolateyPackageParameters - Parameters to use with packaging, not the same as install arguments (which are passed directly to the native installer). Based on `--package-parameters`. (0.9.8.22+)
 * CHOCOLATEY_VERSION - The version of Choco you normally see. Use if you are 'lighting' things up based on choco version. (0.9.9+) - Otherwise take a dependency on the specific version you need.
 * ChocolateyForceX86 - If available and set to `true`, then user has requested 32bit version. (0.9.9+) - Automatically handled in built in Choco functions.
 * OS_PLATFORM - The operating system overall platform. Can be `Windows`, `Linux`, `Mac` or `Unknown`, although in practice it will only be `Windows` as PowerShell automation scripts are not ran on other platforms. (0.9.9+)
 * OS_VERSION - The version of the operating system, like 6.1.x.x for Windows 7. (0.9.9+)
 * OS_NAME - The reported name of the operating system, like `Windows 10` or `Windows Server 2016`. (0.9.9+)
 * IS_PROCESSELEVATED - Is the process elevated? (0.9.9+)
 * ChocolateyToolsLocation - formerly `ChocolateyBinRoot` (`ChocolateyBinRoot` will be removed with Chocolatey v2.0.0), this is where tools being installed outside of Chocolatey packaging will go. (0.9.10+)
 * ChocolateyPackageInstallLocation - Install location of the software that the package installs. Displayed at the end of the package install. (0.9.10+)

#### Set By Options and Configuration

Some environment variables are set based on options that are passed, configuration and/or features that are turned on:

 * ChocolateyEnvironmentDebug - Was `--debug` passed? If using the built-in PowerShell host, this is always true (but only logs debug messages to console if `--debug` was passed) (0.9.10+)
 * ChocolateyEnvironmentVerbose - Was `--verbose` passed? If using the built-in PowerShell host, this is always true (but only logs verbose messages to console if `--verbose` was passed). (0.9.10+)
 * ChocolateyExitOnRebootDetected - Are we exiting on a detected reboot? Set by ` --exit-when-reboot-detected`  or the feature `exitOnRebootDetected` (0.11.0+)
 * ChocolateyForce - Was `--force` passed? (0.9.10+)
 * ChocolateyForceX86 - Was `-x86` passed? (CHECK)
 * ChocolateyRequestTimeout - How long before a web request will time out. Set by config `webRequestTimeoutSeconds` (CHECK)
 * ChocolateyResponseTimeout - How long to wait for a download to complete? Set by config `commandExecutionTimeoutSeconds` (CHECK)
 * ChocolateyPowerShellHost - Are we using the built-in PowerShell host? Set by `--use-system-powershell` or the feature `powershellHost` (0.9.10+)

#### Business Edition Variables

 * ChocolateyInstallArgumentsSensitive - Encrypted arguments passed from command line `--install-arguments-sensitive` that are not logged anywhere. (0.10.1+ and licensed editions 1.6.0+)
 * ChocolateyPackageParametersSensitive - Package parameters passed from command line `--package-parameters-senstivite` that are not logged anywhere.  (0.10.1+ and licensed editions 1.6.0+)
 * ChocolateyLicensedVersion - What version is the licensed edition on?
 * ChocolateyLicenseType - What edition / type of the licensed edition is installed?

#### Experimental Environment Variables

The following are experimental or use not recommended:

 * OS_IS64BIT = This may not return correctly - it may depend on the process the app is running under (0.9.9+)
 * CHOCOLATEY_VERSION_PRODUCT = the version of Choco that may match CHOCOLATEY_VERSION but may be different (0.9.9+) - based on git describe
 * IS_ADMIN = Is the user an administrator? But doesn't tell you if the process is elevated. (0.9.9+)

#### Not Useful Or Anti-Pattern If Used

 * ChocolateyInstallOverride = Not for use in package automation scripts. Based on `--override-arguments` being passed. (0.9.9+)
 * ChocolateyInstallArguments = The installer arguments meant for the native installer. You should use chocolateyPackageParameters instead. Based on `--install-arguments` being passed. (0.9.9+)
 * ChocolateyIgnoreChecksums - Was `--ignore-checksums` passed or the feature `checksumFiles` turned off? (0.9.9.9+)
 * ChocolateyAllowEmptyChecksums - Was `--allow-empty-checksums` passed or the feature `allowEmptyChecksums` turned on? (0.10.0+)
 * ChocolateyAllowEmptyChecksumsSecure - Was `--allow-empty-checksums-secure` passed or the feature `allowEmptyChecksumsSecure` turned on? (0.10.0+)
 * ChocolateyChecksum32 - Was `--download-checksum` passed? (0.10.0+)
 * ChocolateyChecksumType32 - Was `--download-checksum-type` passed? (0.10.0+)
 * ChocolateyChecksum64 - Was `--download-checksum-x64` passed? (0.10.0)+
 * ChocolateyChecksumType64 - Was `--download-checksum-type-x64` passed? (0.10.0)+
 * ChocolateyPackageExitCode - The exit code of the script that just ran - usually set by `Set-PowerShellExitCode` (CHECK)
 * ChocolateyLastPathUpdate - Set by Chocolatey as part of install, but not used for anything in particular in packaging.
 * ChocolateyProxyLocation - The explicit proxy location as set in the configuration `proxy` (0.9.9.9+)
 * ChocolateyDownloadCache - Use available download cache? Set by `--skip-download-cache`, `--use-download-cache`, or feature `downloadCache` (0.9.10+ and licensed editions 1.1.0+)
 * ChocolateyProxyBypassList - Explicitly set locations to ignore in configuration `proxyBypassList` (0.10.4+)
 * ChocolateyProxyBypassOnLocal - Should the proxy bypass on local connections? Set based on configuration `proxyBypassOnLocal` (0.10.4+)
 * http_proxy - Set by original `http_proxy` passthrough, or same as `ChocolateyProxyLocation` if explicitly set. (0.10.4+)
 * https_proxy - Set by original `https_proxy` passthrough, or same as `ChocolateyProxyLocation` if explicitly set. (0.10.4+)
 * no_proxy- Set by original `no_proxy` passthrough, or same as `ChocolateyProxyBypassList` if explicitly set. (0.10.4+)
