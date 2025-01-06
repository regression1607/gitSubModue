To create a Git submodule, you can follow these steps:

1. Navigate to your main repository:
    ```sh
    cd /path/to/your/main/repo
    ```

2. Add the submodule:
    ```sh
    git submodule add https://github.com/username/repo.git path/to/submodule
    ```

3. Initialize and update the submodule:
    ```sh
    git submodule update --init --recursive
    ```

4. Commit the changes:
    ```sh
    git add .gitmodules path/to/submodule
    git commit -m "Add submodule"
    ```

Replace `https://github.com/username/repo.git` with the URL of the repository you want to add as a submodule and `path/to/submodule` with the desired path in your main repository.

Here is an example of how your `Readme.md` might look:

```markdown
# Main Repository

This repository contains a submodule.

## Adding a Submodule

To add a submodule, run the following commands:

```sh
cd /path/to/your/main/repo
git submodule add https://github.com/username/repo.git path/to/submodule
git submodule update --init --recursive
git add .gitmodules path/to/submodule
git commit -m "Add submodule"
```
```