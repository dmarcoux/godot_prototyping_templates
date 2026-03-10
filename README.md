# <a href="https://github.com/dmarcoux/godot_prototyping_templates">dmarcoux/godot_prototyping_templates</a>

Templates for common files/configs when prototyping games with
[Godot](https://godotengine.org/). Use GDScript over C# as it's faster to
prototype with this programming language.

## How to Use This Template

Create a new repository based on this repository:

- Go to this [repository's page](https://github.com/dmarcoux/godot_templates),
  click on the `Use this template` button and follow instructions.

  *OR*

- With [GitHub's CLI](https://github.com/cli/cli), run `gh repo create
  NEW_REPOSITORY_NAME --template=dmarcoux/godot_templates`.

# Development Environment

Rely on [Mise](https://mise.jdx.dev/) to install tools, set environment
variables, and run tasks. Refer to [mise.toml](mise.toml) for details. The Mise
documentation is there to help you get started, there's no need to repeat it all
here. It boils down to activating Mise (_optional_), installing tools, and
running tasks.

Install tools with:

```bash
mise install
```

See available tasks with:

```bash
mise run
```

## JetBrains Rider

Use the IDE [Rider](https://www.jetbrains.com/rider/) from JetBrains with its
built-in support for Godot, GDScript and C#. Install it via the [JetBrains
Toolbox](https://www.jetbrains.com/toolbox-app/).

To open script files in Rider instead of Godot, open Godot, then go to `Editor` >
`Editor Settings` > `Text Editor` > `External` and enable `Use External Editor`.
Set the `Exec Path` to the path of your Rider executable and the `Exec Flags` to
`{project} --line {line} {file}`. Toggle `Advanced Settings` to see all settings.

More settings/details in the [Rider documentation on
Godot](https://www.jetbrains.com/help/rider/Godot.html).

## Git LFS

1. Install [Git LFS](https://git-lfs.com/).
2. Set it up with:
   ```bash
   git lfs install
   ```
