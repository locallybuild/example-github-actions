```
ooooo                                      oooo  oooo              
`888'                                      `888  `888              
 888          .ooooo.   .ooooo.   .oooo.    888   888  oooo    ooo 
 888         d88' `88b d88' `\"Y8 `P  )88b   888   888   `88.  .8'
 888         888   888 888        .oP\"888   888   888    `88..8'
 888       o 888   888 888   .o8 d8(  888   888   888     `888'
o888ooooood8 `Y8bod8P' `Y8bod8P' `Y888\"\"8o o888o o888o     .8'
                                                       .o..P'
                                                       `Y8P'
```

# Example: Running Locally in GitHub Actions

This example shows how to use [Locally Build](https://locally.build) in GitHub Actions, in which we'll be:

* Installing and then launching Locally using the `locallybuild/setup-locally@v1` GitHub Action.
* Provisioning a Resource Group and Storage Account using the Azure CLI.
* Creating a Container within the Storage Account using the Locally CLI.

Since this is running in GitHub Actions and not on your local machine, it's a little different to our other examples (in that there's no "how to run the example" section here), but you can find the source code in [`./.github/workflows/locally.yml`](./github/workflows/locally.yml) and see it in [the Actions Tab](https://github.com/locallybuild/example-github-actions/actions/new) within this GitHub repository.
