<img src="app-icon.png" align="right" width="200px">

# Disqus 2 App for .net CMSs

> This is a [2sxc](https://2sxc.org) App for [DNN ☢️](https://www.dnnsoftware.com/) and [Oqtane 💧](https://www.oqtane.org/)

An app to integrate Disqus to your page

| Aspect              | Status | Comments or Version
| ------------------- | :----: | -------------------
| 2sxc                | ✅    | requires 2sxc v17.07.00
| Dnn                 | ✅    | For v9.6.1+
| Oqtane              | ✅    | Requires v05.00+
| No jQuery           | ✅    | 
| Live Demo           | ➖    |
| Install Checklist   | ✅    | See [Installation](https://azing.org/2sxc/r/fT9O-8LH) on [azing.org](https://azing.org/2sxc)
| Source & License    | ✅    | included, ISC/MIT
| App Catalog         | ✅    | See [app catalog](https://2sxc.org/en/apps/app/disqus-app-v3-hybrid-for-dnn-and-oqtane)
| Screenshots         | ✅    | See [app catalog](https://2sxc.org/en/apps/app/disqus-app-v3-hybrid-for-dnn-and-oqtane)
| Best Practices      | ✅    | Uses v13.10 conventions
| Bootstrap 3         | ❌    | Last supported in v03.21.00
| Bootstrap 4         | ❌    | Last supported in v03.21.00
| Bootstrap 5         | ✅    |

## Manuals / Instructions

Consult the [azing recipes](https://azing.org/2sxc/l/Mek_MCqz/app-disqus) for this

## Customize the App

There is only one app setting and only a few app resources you can change.

If you want to customize the CSS, you will usually follow the ["Create Custom Styles in a Standard 2sxc App" checklist](https://azing.org/2sxc/r/gg_aB9FD).
But note that you usually don't want to do this, as added snippets should just be as-is

## History

* v03.21.01 2026-10
  * Removed Bootstrap 3 and Bootstrap 4 support; the app is now Bootstrap 5 only
  * For Bootstrap 3 or Bootstrap 4, use v03.21.00

* v02.00 2022-03
  * Upgrade to v12.05 conventions
  * Switched all injects to use Razor
* v02.01 2022-05
  * Moved inline scripts to files for CSP
* v02.02 2022-06
  * Changed all base classes to their 2sxc 14 equivalents 
  * Changed from GetService<> to the new ServiceKit14
* v02.03.00 2023-05
  * Removed _ from Filenames
  * Replaced turnOn Tag with `Kit.Page.TurnOn`
* v02.04.00 2023-07
  * 2sxc 16.02 coding conventions
  * everything typed
* v02.17.00 2024-04
  * strong Typed
  * Auto Generated Class
* v02.17.01 2024-07
  * Update app.sln and app.csproj
