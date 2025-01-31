<div align="center">
  <a href="https://www.suneet.codes/articles/linting-formatting-setup-deno">
    <picture>
      <img alt="Next.js logo" src="https://res.cloudinary.com/suneet-codes/image/upload/v1738312771/suneet-codes/articles/linting-formatting-deno_z91i9v.jpg" height="300">
    </picture>
  </a>
  <h1 >Node Projects: Linting + Formatting + Conventional Commits</h1>
</div>

This repo demonstrates a workflow for using git hooks to automate the linting
and formatting of files and for the standardization of commit messages within a
deno project.

# Documentation

The workflow is documented in
[this article](https://suneet.codes/articles/linting-formatting-setup-deno).

## Usage

To experience the automation, clone the project

```bash
git clone https://github.com/sun33t/0002-linting-formatting-setup-deno
```

Go to the project directory

```bash
cd linting-formatting-setup-deno
```

Install dependencies

```bash
deno install && deno task prepare
```

Make a change in any file and commit the change. The toolchain will
automatically execute and you can see its output in the terminal.

## Authors

- [@sun33t](https://github.com/sun33t)
