# Introduction to GitHub

## Getting started

- Download [GitHub Desktop](https://desktop.github.com/)

- Use GitHub Desktop to make a new repository `example-NE593-your-last-name` on your computer.

- Create a Jupyter notebook with example code and text; save it in your repository.

    *Here's my first example.*

    ```
    def simple-code-your-name(x):
      y = x*x+1 
      return y
    ```

- Commit the file on GitHub Desktop, with a useful description.

## Making changes


- Make a change on your computer, and commit the change on GitHub Desktop.

     *Now I've modifired my example.*
    
    ```
    def simple-code-your-name(x):
      y = x*x/2+1
      return y
    ```

- Revert the commit on GitHub Desktop.

## Publishing online

- Publish to github.com, and make it public.

- Update the file on github.com, and commit on github.com

- Fetch the file changes on GitHub Desktop.

- Make another change on your computer, commit it on GitHub Desktop, and push it to github.com

    *And other change!*

    ```
    def simple-code-your-name(x):
      y = x*x/2+x+1
      return y
    ```

## Forks

- Fork your neighbor's `example-NE593-your-name` repository on github.com

- Make changes to the forked respository on github.com

- Create a pull request

- Confer with your partner, and accept/reject pull request.

## Branches

If there's time:

- Make a branch `two-inputs` on GitHub Desktop.

- Edit the function on branch `two-inputs` on your computer, and commit it on GitHub Desktop.

    *Now there are two inputs to my function.*

    ```
    def simple-code-your-name(x,z):
      y = x*x/2+z/3+1
      return y
    ```

- Toggle between the two branches (`master` and `two-inputs`) on GitHub Desktop
