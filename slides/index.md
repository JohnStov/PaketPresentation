- title : Paket
- description : What is Paket & why should you use it?
- author : John Stovin
- theme : simple
- transition : default

***

# Paket
## John Stovin
### Twitter : @johnstovin

***

## What is Paket?

Paket is a better package manager for .Net

It fixes several of the annoyances of NuGet

It plays nice with nuget.org

It can manage other resources as well

***

## Where has it come from?

Paket was developed by members of the FSharp community

They were frustrated with the shortcomings of NuGet

They tried to submit patches to NuGet, but the NuGet team refused them

So they wrote their own dependency manager

***

## What problems does it solve?

---

__Paket prevents you from having different versions of the same dependent assembly in different projects of the same solution__

Paket stores all the depencies for a solution in one place. All projects within the solution have to reference the same version of the dependency.

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
- GitHub respositories & Gists

and unversioned dependencies on any url

***

## How does Paket work?

***

## Who uses Paket?

Paket is the depencie manager of choice in the FSharp community



***

## Can I rely on Paket?

Paket is in _very_ active development. 



***

## You've convinced me. Where can I get Paket?