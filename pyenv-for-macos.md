# Pyenv for MacOS
Like many things IT, there are multiple ways of doing the same thing and sometimes it just boils down to preference. There are multiple ways that you can install Pyenv on the MacOS (see Pyenv’s repository on Github for more install options. Here we are going to show how to install Pyenv using the package installer Homebrew. If you your Mac doesn’t have Homebrew installed or if you want to learn more about Homebrew see their [homepage](https://brew.sh/).

1. Before starting the installation to the pyenv first review this page Pyenv's [suggested build environment's page](https://github.com/pyenv/pyenv/wiki#suggested-build-environment) to ensure that your environment has the correct dependencies installed. 
2. Verify that you have homebrew on your Mac. Open your terminal and for your Mac and type the following.
   
   <code>> brew --version</code>
   
   ![screen shot here](assets/screenshots/macos/step2.png)

   If there is an error then you will probably need to install Homebrew on your machine.
3. Next update Homebrew and then install the pyenv package.
   
   <code>> brew update && brew install pyenv</code>

   Please be aware that brew may take a bit as it updates and install pyenv.

4. Once the installation has completed, then verify that that pyenv has been installed properly. You should see the latest version installed if you used the instructions from above.