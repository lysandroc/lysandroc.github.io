This repository contains my resume, which can be accessed [here](https://lysandroc.github.io/).

## Prerequisites

Before working with this repository, ensure that you have the following tools installed:

- Visual Studio Code
- Docker and docker-compose

Additionally, it is recommended to accept the extension recommendations provided in the [resume.code-workspace](./resume.code-workspace) file. You can do this by opening Visual Studio Code, navigating to the Extensions view, and accepting the recommendations.

If you prefer to allow automatic tasks in the folder, follow these steps:

Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) in Visual Studio Code.
Type "Tasks: Allow Automatic Tasks in Folder" and select it from the dropdown.
This will enable automatic task execution, so you don't need to run docker-compose manually.

## Building the Resume

To build the resume, you need to pull the Docker image by running the following command:

```
$ docker pull tianon/latex
```

It is recommended to use the [james-yu.latex-workshop](https://github.com/James-Yu/LaTeX-Workshop) extension in Visual Studio Code, as it allows you to have the text, build, and preview side by side for a better editing experience.

## References:

- https://towardsdatascience.com/three-ways-to-create-dockernized-latex-environment-2534163ee0c4
- https://github.com/qdm12/latexdevcontainer
