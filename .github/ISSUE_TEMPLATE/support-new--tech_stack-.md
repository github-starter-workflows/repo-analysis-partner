---
name: Support new `tech_stack`
about: Request support for new `tech_stack` in repo analysis
title: ''
labels: ''
assignees: NinadKavimandan

---

**Name of the `tech_stack`**
A distinct name for the `tech_stack`

**Filenames to look for in the repository**
This defines the name of the file used as the criteria of detection. For eg, the presence of `yarn.lock` is the detection criteria for `Yarn`.

**File extensions to look for in the repository**
This defines the extensions of files used as the criteria of detection. For eg, the presence of `.csproj` extension is a detection criteria for `AspNetCore`.

**Content/Regex to look for in the above-mentioned filename/extensions**
This defines the content to look for in the file with the name/extensions defined above. For eg, the presence of `<Project Sdk="Microsoft.NET.Sdk.Web">` in a file with extension `.csproj` is the detection criteria for `AspNetCore`

**Sample public repository which we can add to our test suite**
Provide a public repo which contains relevant files and is expected to have the above mentioned tech_stack. This repo will be added to our regression test suite. 

**Additional context**
Add any other context or screenshots about the feature request here.
