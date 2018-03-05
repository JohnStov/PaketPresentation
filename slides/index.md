- title : Paket
- description : What is Paket & why should you use it?
- author : John Stovin
- theme : moon
- transition : convex

***

# Paket

## .NET Package Management Done Right

### John Stovin
#### Twitter : @johnstovin

***

## What is Paket?

A better package manager for .Net

Fixes several NuGet annoyances

Plays nice with nuget.org

Manages other resources besides NuGet packages

***

## Where has it come from?

Developed by members of the FSharp community frustrated with the shortcomings of NuGet

They tried to submit patches to NuGet, but the NuGet team refused them

So they wrote their own dependency manager

***

## Who uses Paket?

Paket is the dependency manager of choice in the FSharp community

Most F# open source projects use Paket

Paket deserves more exposure within the wider .NET community

***

## Why is Paket better than Nuget?

---

__Paket prevents you having different versions of the same dependent assembly in different projects of the same solution__

Paket stores all the depencies for a solution in one place. All projects within the solution have to reference the same version of the dependency.

---

__Paket guarantees stable versions of all dependencies__

Paket works out the best combination of versions of all dependencies based on _your_ constraints. These are stored in the paket.lock file, which only changes when _you_ decide. This guarantees repeatable builds.

---

__Paket gives you reliable paths to dependencies__


Paket does not put the version number in the path to the dependency. This means that command line tools get a reliable path to dependencies that will not change when you update the dependency.

---

__Paket hides transitive dependencies__

You only need to care about your direct dependencies. If your dependencies have dependencies of their own, Paket handles it gracefully without forcing you to care about them.

---

__Paket lets you take dependencies on more than just NuGet packages__

With paket you can take _versioned_ dependencies on:

- Git repositories
- GitHub respositories
- Gists

as well as an unversioned dependency on any url

***

## What tooling support is there for Paket?

Visual Studio plugin

Visual Studio Code plugin (Ionide)

Automatic conversion from NuGet

Integrates with MS Build, .Net Core cmdline

Also support for Atom, Emacs, Xamarin Studio, JetBrains Rider

***

## Can I rely on Paket?

Paket is in _very_ active development

Patches released every few days

Patch for GitHub TLS deprecation available within hours

Paket always tries to update itself

Updates always available on chocolatey.org

***

## You've convinced me. Where can I get Paket?

Go to <https://fsprojects.github.io/Paket/> and follow the links

***

## Thank you

Slides available at:

https://johnstov.github.io/PaketPresentation

Slide source at:

https://github.com/JohnStov/PaketPresentation

Slides produced with FsReveal:

https://fsprojects.github.io/FsReveal