# makdocs-pyscript-python

## Usage/Deployment
  * Create a virtual environment of your choice
  * install `mkdocs` and `mkdocs-pyscript`
  * Add `mkdocs-pyscript` to your list of plugins in `mkdocs.yml`
  * Write your documentation - all codeblocks will (by default) be converted to runnable code blocks in the browser.
    ``````
    ```py
    for i in range(20):
        print(i)
    ```
    ``````
  * Publish!