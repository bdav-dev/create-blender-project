# create-blender-project
A command line tool to create a new blender project with common directories.

```Project language: English```

## Description
`create-blender-project` is a tool accessible via the command line / terminal.

It creates a new blender project with the following directories:
- `assets`
- `blend-files`
- `render-output`
- `results`

The directory `blend-files` will contain a blank blender file with the name of the project: `<projectName>.blend`<br/>
The tool also sets the directoy `render-output` as the default render output directory of the newly created blender file.

## Parameters
The command has one (optional) parameter: Project name.<br/>
If the parameter is not specified, the terminal will ask for a project name.

## Use `create-blender-project`

### Run
1. Download the source code of the project (as a .zip file or via `git clone`).
2. Make sure the `create-blender-project` file is flagged as executable, if not run `$ chmod +x create-blender-project`
3. Open a new terminal window and navigate to the directory in which you want to create a new blender project (using `cd`)
4. Run `$ /path/to/file/create-blender-project <Optional parameter: Project name>`

### Install (Make accessible in terminal)
If you want to install `create-blender-project` and make the command accessible in the terminal, copy the `create-blender-project` file to the following directory: `/usr/local/bin/`

Now you can access it without specifing the location of the file, like this: `$ create-blender-project <Optional parameter: Project name>`.
