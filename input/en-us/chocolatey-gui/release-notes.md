---
Order: 10
xref: chocolateygui-release-notes
Title: Release Notes
Description: Release Notes for Chocolatey GUI
RedirectFrom: docs/release-notes-chocolatey-gui
---

# Chocolatey GUI Release Notes - Open Source

This covers changes for the "chocolateygui" package, which is available as FOSS.

> :memo: **NOTE** For commercial editions, please also refer to [Licensed Release Notes](xref:licensed-extension-release-notes), as well at the [Chocolatey GUI Licensed Extension Release Notes](xref:chocolatey-gui-licensed-extension-release-notes).

<?! Include "../../shared/chocolatey-component-dependencies.txt" /?>

## [1.0.0](https://github.com/chocolatey/ChocolateyGUI/milestone/28?closed=1) (March 21, 2022)

> :warning: **WARNING**
>
> The dependencies of the chocolateygui package have changed in this release. It now requires Chocolatey v1.0.0.

### Breaking Change

- Updates Chocolatey dependency for package to v1.0.0 - see [#928](https://github.com/chocolatey/ChocolateyGUI/issues/928)

### Bug Fix

- Ensure keyboard shortcuts to navigate between sources works correctly when the show aggregated sources feature is enabled - see [#915](https://github.com/chocolatey/ChocolateyGUI/issues/915)

### Documentation

- Fix typo in window seen after export command finishes - see [#924](https://github.com/chocolatey/ChocolateyGUI/pull/924)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/D-Gi463UukQ?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.20.0](https://github.com/chocolatey/ChocolateyGUI/milestone/23?closed=1) (February 10, 2022)

> :warning: **WARNING**
>
> If you install v0.20.0 of Chocolatey GUI then you will also have to install v0.4.0 of Chocolatey GUI Licensed Extension if you use it. You will see errors when attempting to run Chocolatey GUI if you do not do so.

### Breaking Changes

- Change target .NET Framework version to be 4.8 - see [#841](https://github.com/chocolatey/ChocolateyGUI/issues/841)

### Features

- Allow for passing in package parameters / installer arguments when installing a package - see [#545](https://github.com/chocolatey/ChocolateyGUI/issues/545)
- Allow users to change the locale to use - see [#533](https://github.com/chocolatey/ChocolateyGUI/issues/533)
- Provide ability to "see" persisted arguments for installed package - see [#770](https://github.com/chocolatey/ChocolateyGUI/issues/770)
- Provide ability to search/filter features and settings - see [#838](https://github.com/chocolatey/ChocolateyGUI/issues/838)
- Add confirmation dialog for update all button - see [#828](https://github.com/chocolatey/ChocolateyGUI/issues/828)
- Add confirmation dialog when removing a source - see [#827](https://github.com/chocolatey/ChocolateyGUI/issues/827)
- Add confirmation dialog when performing an Uninstall/Reinstall operation from context menu - see [#786](https://github.com/chocolatey/ChocolateyGUI/issues/786)

### Bug Fixes

- Install button is not disabled when installation of packages is not allowed - see [#911](https://github.com/chocolatey/ChocolateyGUI/issues/911)
- Message boxes used to report issues often don't stay open - see [#904](https://github.com/chocolatey/ChocolateyGUI/issues/904)
- All operations on packages with a progress dialog are broken - see [#875](https://github.com/chocolatey/ChocolateyGUI/issues/875)

### Improvements

- Ensure WiX installer verifies that .NET Framework 4.8 is installed - see [#842](https://github.com/chocolatey/ChocolateyGUI/issues/842)
- Order features and settings alphabetically - see [#837](https://github.com/chocolatey/ChocolateyGUI/issues/837)
- Support per-monitor DPI - see [#836](https://github.com/chocolatey/ChocolateyGUI/issues/836)
- Chocolatey GUI doesn't write to chocolatey.log - see [#697](https://github.com/chocolatey/ChocolateyGUI/issues/697)

### Documentation

- Gitter is still mentioned in the Readme - see [#898](https://github.com/chocolatey/ChocolateyGUI/issues/898)
- Fix link to localization article - see [#891](https://github.com/chocolatey/ChocolateyGUI/pull/891)
- Remove package parameters from nuspec file - see [#885](https://github.com/chocolatey/ChocolateyGUI/issues/885)
- Contributing.md has broken links - see [#854](https://github.com/chocolatey/ChocolateyGUI/issues/854)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/8sSp1d7Ni8o?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.19.0](https://github.com/chocolatey/ChocolateyGUI/milestone/26?closed=1) (September 6, 2021)

> :warning: **WARNING**
>
> The dependencies of the chocolateygui package have changed in this release, and it now requires Chocolatey CLI v0.11.1.

> :warning: **WARNING**
>
> If you use Chocolatey GUI alongside the Chocolatey GUI Licensed Extension, if you install v0.19.0 of Chocolatey GUI then you will also have to install v0.3.0 of Chocolatey GUI Licensed Extension, or you will see errors when attempting to run Chocolatey GUI.

### Improvements

- [Security] XML External Entity attack in log4net (CVE-2018-1285) - see [#869](https://github.com/chocolatey/ChocolateyGUI/issues/869)
- Make use of Chocolatey CLI Export command - see [#882](https://github.com/chocolatey/ChocolateyGUI/issues/882)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/6EJKPy4cCKI?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.18.2](https://github.com/chocolatey/ChocolateyGUI/milestone/25?closed=1) (September 2, 2021)

### Bug Fix

- When running Chocolatey GUI, ensure installed Chocolatey assembly is used, rather than locally referenced assembly - see [#857](https://github.com/chocolatey/ChocolateyGUI/issues/857)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/PC00qA4rlkY?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.18.1](https://github.com/chocolatey/ChocolateyGUI/milestone/24?closed=1) (March 29, 2021)

### Bug Fixes

- Chocolatey GUI fails to start in certain circumstances when running as a non-administrator user - [#829](https://github.com/chocolatey/ChocolateyGUI/issues/829)
- Ensure that transactions are persisted to configuration databases when making changes to Chocolatey GUI settings/features - see [#832](https://github.com/chocolatey/ChocolateyGUI/issues/832)
- Chocolatey GUI incorrectly reverts to list view after making a change in settings screen - see [#830](https://github.com/chocolatey/ChocolateyGUI/issues/830)

### Documentation

- Fix incorrect quoting of parameter in package nuspec - see [#831](https://github.com/chocolatey/ChocolateyGUI/issues/831)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/LzMKMZX_ja4?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.18.0](https://github.com/chocolatey/ChocolateyGUI/milestone/19?closed=1) (March 9, 2021)

### Breaking Changes

- Update the default value for tile view for local and remote source to be true - see [#820](https://github.com/chocolatey/ChocolateyGUI/issues/820)
- Update the default value for "NonAdmin Access to Settings" feature to be false - see [#601](https://github.com/chocolatey/ChocolateyGUI/issues/601)

### Features

- Add a feature to toggle on/off the option to not attempt to download icons for packages - see [#811](https://github.com/chocolatey/ChocolateyGUI/issues/811)
- Add a feature to toggle on/off a read only view for installed packages - see [#780](https://github.com/chocolatey/ChocolateyGUI/issues/780)
- Add a feature to toggle on/off the checking for outdated packages automatically - see [#769](https://github.com/chocolatey/ChocolateyGUI/issues/769)
- Add a feature to toggle on/off the preloading of packages when switching to remote views - see [#706](https://github.com/chocolatey/ChocolateyGUI/issues/706)
- Add a feature to toggle on/off dark mode for application UI - see [#685](https://github.com/chocolatey/ChocolateyGUI/issues/685)
- Add a configuration option to specify a default for a particular source when application loads - see [#808](https://github.com/chocolatey/ChocolateyGUI/issues/808)
- Provide ability to control which UI operations are allowed to be executed - see [#757](https://github.com/chocolatey/ChocolateyGUI/issues/757)
- Provide ability to set configuration at the machine level, rather than just at user level - see [#602](https://github.com/chocolatey/ChocolateyGUI/issues/602)
- Enable text search within local and remove views - when not using Tile View - see [#688](https://github.com/chocolatey/ChocolateyGUI/issues/688)

### Bug Fixes

- Option to only show packages with updates doesn't work correctly when automated outdated check is enabled - see [#821](https://github.com/chocolatey/ChocolateyGUI/issues/821)
- Configuration option to default to tile view for remote source is not respected - see [#782](https://github.com/chocolatey/ChocolateyGUI/issues/782)
- Using the UseDelayedSearch package parameter during installation doesn't work - see [#749](https://github.com/chocolatey/ChocolateyGUI/issues/749)
- Ensure that all features/config can be set via parameters during installation of package - see [#741](https://github.com/chocolatey/ChocolateyGUI/issues/741)

### Improvements

- Add keybinding for navigating between sources - see [#513](https://github.com/chocolatey/ChocolateyGUI/issues/513)
- Improve readability of settings description by wrapping text within cell - see [#813](https://github.com/chocolatey/ChocolateyGUI/issues/813)
- Improve how package icons with an svg extension are rendered - see [#756](https://github.com/chocolatey/ChocolateyGUI/issues/756)
- Improve how package icons with an ico extension are rendered - see [#739](https://github.com/chocolatey/ChocolateyGUI/issues/739)
- Improve order and spacing of context menu items to make it easier to use - see [#745](https://github.com/chocolatey/ChocolateyGUI/issues/745)
- Update wording of context menu items to make it clearer what they refer to - see [#730](https://github.com/chocolatey/ChocolateyGUI/issues/730)
- Update Svg.Skia and SkiaSharp dependencies - see [#812](https://github.com/chocolatey/ChocolateyGUI/pull/812)
- Update LiteDB to v5.0.5 - see [#763](https://github.com/chocolatey/ChocolateyGUI/pull/763)
- Update Automapper to v7.0.1 - see [#760](https://github.com/chocolatey/ChocolateyGUI/pull/760)

### Documentation

- Add link to wixtoolset Visual Studio integration - see [#792](https://github.com/chocolatey/ChocolateyGUI/pull/792)
- Update credits to include all 3rd party dependencies that are being used - see [#761](https://github.com/chocolatey/ChocolateyGUI/issues/761)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/eKXPDmqO-hs?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.17.3](https://github.com/chocolatey/ChocolateyGUI/milestone/22?closed=1) (February 1, 2021)

### Bug Fix

- Chocolatey GUI doesn't always shows the right list of software - see [#807](https://github.com/chocolatey/ChocolateyGUI/issues/807)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/SAob-HgTf2Q?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.17.2](https://github.com/chocolatey/ChocolateyGUI/milestone/21?closed=1) (July 13, 2020)

### Bug Fixes

- Ensure earlier versions of Chocolatey GUI assemblies can be resolved when using an older version of Chocolatey GUI extension - see [#785](https://github.com/chocolatey/ChocolateyGUI/issues/785)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/DGpdtcby9N4?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.17.1](https://github.com/chocolatey/ChocolateyGUI/milestone/20?closed=1) (June 11, 2020)

### Bug Fixes

- Language localization files are missing in 0.17.0  - see [#778](https://github.com/chocolatey/ChocolateyGUI/issues/778)
- Chocolatey GUI runs as a 32 bit process when running on a 64 bit machine - see [#779](https://github.com/chocolatey/ChocolateyGUI/issues/779)

### Release Video

A short video explaining what is included in this release can be found here:

<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/1wSwRMbds1k?list=PLGvGJzqY88slZbIf7_6QVAVmrZHujDW44" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>

## [0.17.0](https://github.com/chocolatey/ChocolateyGUI/milestone/18?closed=1) (March 26, 2020)

### Features

- Add ability to show/hide download count on remote source view - see [#710](https://github.com/chocolatey/ChocolateyGUI/issues/710)
- Create and publish additional NuGet packages for Chocolatey GUI - see [#698](https://github.com/chocolatey/ChocolateyGUI/issues/698)
- Provide integration with chocolateygui.extension - see [#679](https://github.com/chocolatey/ChocolateyGUI/issues/679)
- Create commands to allow purging of caches from CLI - see [#673](https://github.com/chocolatey/ChocolateyGUI/issues/673)
- Provide ability to purge Outdated Package cache file - see [#671](https://github.com/chocolatey/ChocolateyGUI/issues/671)
- Separate the app.manifest from the exe [Customer] - see [#629](https://github.com/chocolatey/ChocolateyGUI/issues/629)
- Provide ability to hide packages that are known to already be installed when viewing sources - see [#627](https://github.com/chocolatey/ChocolateyGUI/issues/627)
- Provide ability to refresh cached icons for packages when there are known changes to icon - see [#624](https://github.com/chocolatey/ChocolateyGUI/issues/624)
- Remove admin only sources/repos - see [#603](https://github.com/chocolatey/ChocolateyGUI/issues/603)
- Allow setting of Chocolatey GUI settings via Chocolatey package parameter - see [#592](https://github.com/chocolatey/ChocolateyGUI/issues/592)
- Search in all available repositories - see [#588](https://github.com/chocolatey/ChocolateyGUI/issues/588)
- Hide Download Counters - see [#569](https://github.com/chocolatey/ChocolateyGUI/issues/569)
- Limit non-admin list to self service only - see [#432](https://github.com/chocolatey/ChocolateyGUI/issues/432)

### C4B Features

- Add footer with information about current version in bottom left hand corner - see [#705](https://github.com/chocolatey/ChocolateyGUI/issues/705)
- Add ability to strong name sign the output of the build - see [#704](https://github.com/chocolatey/ChocolateyGUI/issues/704)

### Bug Fixes

- Fix - PackageParameters are not working (when installing Chocolatey GUI via Chocolatey) - see [#716](https://github.com/chocolatey/ChocolateyGUI/issues/716)
- Fix - Context menu not displayed - see [#709](https://github.com/chocolatey/ChocolateyGUI/issues/709)
- Fix - Correctly handle incorrect license installation - see [#686](https://github.com/chocolatey/ChocolateyGUI/issues/686)
- Fix - Packages with pre-release versioning never found on list/search - see [#676](https://github.com/chocolatey/ChocolateyGUI/issues/676)
- Fix - Empty icon doesn't appear on local source view - see [#674](https://github.com/chocolatey/ChocolateyGUI/issues/674)
- Fix - IsPrerelease property is never set - see [#661](https://github.com/chocolatey/ChocolateyGUI/issues/661)
- Fix - nuspec - Remove the upper bound dependency on Chocolatey - see [#656](https://github.com/chocolatey/ChocolateyGUI/issues/656)
- Fix - Prerelease packages not being correctly labeled as "outdated" - see [#653](https://github.com/chocolatey/ChocolateyGUI/issues/653)
- Fix - Tile View - Nitpick inconsistent spacing - see [#652](https://github.com/chocolatey/ChocolateyGUI/issues/652)
- Fix - NotSupportedException:'System.NotSupportedException: UriTypeConverter cannot convert from (null) when viewing Package Details - see [#643](https://github.com/chocolatey/ChocolateyGUI/issues/643)
- Fix - nuspec - Add .NET Framework 4.x Dependency [Customer] - see [#632](https://github.com/chocolatey/ChocolateyGUI/issues/632)
- Fix - Unable to update source after making a change to another source [Customer] - see [#620](https://github.com/chocolatey/ChocolateyGUI/issues/620)
- Fix - Tile selection for Remote Sources is not being used - see [#618](https://github.com/chocolatey/ChocolateyGUI/issues/618)
- Fix - Unable to install a package that uses 64bit PowerShell Modules - see [#610](https://github.com/chocolatey/ChocolateyGUI/issues/610)
- Fix - Locking of generated packages.config file when exporting package list - see [#593](https://github.com/chocolatey/ChocolateyGUI/issues/593)
- Fix - Next/Previous First/Last buttons remain disabled when using Simple.Server [Customer] - see [#590](https://github.com/chocolatey/ChocolateyGUI/issues/590)
- Fix - Chocolatey GUI icon is a blank image - see [#589](https://github.com/chocolatey/ChocolateyGUI/issues/589)
- Fix - GUI misses update that shows in CLI - see [#585](https://github.com/chocolatey/ChocolateyGUI/issues/585)
- Fix - Chocolatey GUI crashes when opening details page for Rufus package - see [#584](https://github.com/chocolatey/ChocolateyGUI/issues/584)
- Fix - Chocolatey GUI crashes when viewing Package Details - see [#578](https://github.com/chocolatey/ChocolateyGUI/issues/578)
- Fix - Package shows as installed in GUI when it did not actually install [Customer] - see [#573](https://github.com/chocolatey/ChocolateyGUI/issues/573)
- Fix - Chocolatey GUI crashes on startup if all sources are disabled. - see [#568](https://github.com/chocolatey/ChocolateyGUI/issues/568)
- Fix - Chocolatey GUI v0.16.0 uninstall errors (but uninstalls) - see [#563](https://github.com/chocolatey/ChocolateyGUI/issues/563)
- Fix - Links in Settings/About page that result in "Page Not Found" errors - see [#562](https://github.com/chocolatey/ChocolateyGUI/issues/562)
- Fix - Icon not showing up in gallery - see [#558](https://github.com/chocolatey/ChocolateyGUI/issues/558)
- Fix - Package source link for ChocolateyGUI 0.15.0 in nuspec is wrong - see [#550](https://github.com/chocolatey/ChocolateyGUI/issues/550)
- Fix - Context Menu Position issue in the package details. - see [#548](https://github.com/chocolatey/ChocolateyGUI/issues/548)
- Fix - On Load of any source, outdated is running (logging) every time - see [#525](https://github.com/chocolatey/ChocolateyGUI/issues/525)
- Fix - Issue where Latest Version is not showing - see [#506](https://github.com/chocolatey/ChocolateyGUI/issues/506)
- Fix - Disable "Show Only Packages with Updates" while information is still loaded - see [#502](https://github.com/chocolatey/ChocolateyGUI/issues/502)

### Improvements

- Prerelease label should not be red as this suggests an error, which isn't the case - see [#711](https://github.com/chocolatey/ChocolateyGUI/issues/711)
- Move Windows specific code into another Common library - see [#682](https://github.com/chocolatey/ChocolateyGUI/issues/682)
- Remove tilting chocolatey logo - see [#680](https://github.com/chocolatey/ChocolateyGUI/issues/680)
- Split CLI functionality into separate exe - see [#675](https://github.com/chocolatey/ChocolateyGUI/issues/675)
- Allow "safe" Chocolatey operations to happen in parallel - see [#672](https://github.com/chocolatey/ChocolateyGUI/issues/672)
- Update to Chocolatey.Lib 0.10.15 - see [#670](https://github.com/chocolatey/ChocolateyGUI/issues/670)
- Ensure all dialogs shown in Chocolatey GUI have localized text on buttons - see [#668](https://github.com/chocolatey/ChocolateyGUI/issues/668)
- Do not display password in source settings screen - see [#665](https://github.com/chocolatey/ChocolateyGUI/issues/665)
- Tile View - Prevent Version text overlap - see [#651](https://github.com/chocolatey/ChocolateyGUI/issues/651)
- Ensure that icons maintain their aspect ratio - see [#633](https://github.com/chocolatey/ChocolateyGUI/issues/633)
- Improve UI for Feature and Settings lists - see [#612](https://github.com/chocolatey/ChocolateyGUI/pull/612)
- Upgrade MahApps.Metro and MahApps.Metro.IconPacks - see [#608](https://github.com/chocolatey/ChocolateyGUI/pull/608)
- Remove multiple uses of SetCustomLogging - see [#607](https://github.com/chocolatey/ChocolateyGUI/issues/607)
- Don't allow navigation to settings or about screen while dialog is open - see [#606](https://github.com/chocolatey/ChocolateyGUI/issues/606)
- Improve the descriptions/explanations used for Chocolatey GUI settings - see [#605](https://github.com/chocolatey/ChocolateyGUI/issues/605)
- Provide separate settings and about views - see [#598](https://github.com/chocolatey/ChocolateyGUI/issues/598)
- Chocolatey GUI not found in the PATH - see [#574](https://github.com/chocolatey/ChocolateyGUI/issues/574)
- Chocolatey GUI pulls download stats only from the community feed  - see [#564](https://github.com/chocolatey/ChocolateyGUI/issues/564)
- Move version on Package view to the left column - see [#530](https://github.com/chocolatey/ChocolateyGUI/issues/530)
- Improve UI by reducing flashing when modal appears - see [#528](https://github.com/chocolatey/ChocolateyGUI/issues/528)
- Package description should use all available client space - see [#501](https://github.com/chocolatey/ChocolateyGUI/issues/501)
- Add different background for outdated packages - see [#431](https://github.com/chocolatey/ChocolateyGUI/issues/431)
- Package details view is missing the 'Gallery' link - see [#430](https://github.com/chocolatey/ChocolateyGUI/issues/430)
- Current prerelease does not display any versioning information in the ABOUT screen - see [#422](https://github.com/chocolatey/ChocolateyGUI/issues/422)
- Fix rendering of headings in package description  - see [#356](https://github.com/chocolatey/ChocolateyGUI/issues/356)
- Add option to show package id column - see [#270](https://github.com/chocolatey/ChocolateyGUI/issues/270)

### Documentation

- Add Czech language map - see [#729](https://github.com/chocolatey/ChocolateyGUI/pull/729)
- Fix typo in readme - see [#693](https://github.com/chocolatey/ChocolateyGUI/issues/693)
- Added Chinese language map - see [#634](https://github.com/chocolatey/ChocolateyGUI/pull/634)
- Fix typo in about page - see [#583](https://github.com/chocolatey/ChocolateyGUI/pull/583)

## [0.16.0](https://github.com/chocolatey/ChocolateyGUI/milestone/17?closed=1) (February 15, 2018)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.16.0)

## [0.15.0](https://github.com/chocolatey/ChocolateyGUI/milestone/6?closed=1) (October 18, 2017)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.15.0)

## [0.13.2](https://github.com/chocolatey/ChocolateyGUI/milestone/14?closed=1) (December 14, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.13.2)

## [0.13.1](https://github.com/chocolatey/ChocolateyGUI/milestone/13?closed=1) (March 29, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.13.1)

## [0.13.0](https://github.com/chocolatey/ChocolateyGUI/milestone/3?closed=1) (March 26, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.13.0)

## [0.12.4](https://github.com/chocolatey/ChocolateyGUI/milestone/10?closed=1) (March 12, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.12.4)

## [0.12.3](https://github.com/chocolatey/ChocolateyGUI/milestone/9?closed=1) (March 3, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.12.3)

## [0.12.2](https://github.com/chocolatey/ChocolateyGUI/milestone/8?closed=1) (March 3, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.12.2)

## [0.12.1](https://github.com/chocolatey/ChocolateyGUI/milestone/7?closed=1) (March 2, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.12.1)

## [0.12.0](https://github.com/chocolatey/ChocolateyGUI/milestone/2?closed=1) (February 28, 2015)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.12.0)

## [0.11.4](https://github.com/chocolatey/ChocolateyGUI/milestone/5?closed=1) (September 16, 2014)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.11.4)

## 0.11.3 (September 16, 2014)

No release notes available.

## [0.11.2](https://github.com/chocolatey/ChocolateyGUI/milestone/4?closed=1) (September 16, 2014)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.11.2)

## [0.11.1](https://github.com/chocolatey/ChocolateyGUI/milestone/11?closed=1) (February 24, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.11.1)

## [0.11.0](https://github.com/chocolatey/ChocolateyGUI/milestone/1?closed=1) (February 24, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.11.0)

## 0.1.4 (February 10, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.1.4)

## 0.1.3 (February 10, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.1.3)

## 0.1.2 (February 10, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.1.2)

## 0.1.1 (February 10, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.1.1)

## 0.1.0 (February 9, 2013)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.1.0)

## 0.0.5 (September 10, 2011)

Release notes can be found [here](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.0.5)

## 0.0.4 (September 10, 2011)

No release notes available.

## 0.0.3 (September 10, 2011)

No release notes available.

## 0.0.2 (September 10, 2011)

No release notes available.

## 0.0.1 (September 10, 2011)

No release notes available.
