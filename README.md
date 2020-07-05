# Virtual-Environment-for-Data-Science
Creating a github repo and a virtual environment for jupyter lab

1. Create a new repository `virtual_env` on the github portal.
2. Select `Public`
3. Check `Initialize this repository wit a README`.
4. Add .gitignore: `Python`.
5. Add a license: `MIT License`
6. Click `Create Repository`.
7. Once the repository is created, copy the link for cloning the respository.
8. Go to the terminal and create a new directory `myEnvironments`.<br/>`> mkdir myEnvironments`
9. Open the `myEnvironments` directory.
10. Run following command <br/>`> git clone <<repository link>>`
11. You will find a new directory created with `virtual_env` name. Open it. <br/>`> cd virtual_env`
12. This directory contains following three files.<br/>i. .gitignore<br/>ii LICENSE<br/>iii README.md
13. Create additional three directories :<br/>`> mkdir data`<br/>`> mkdir notebooks`<br/>`> mdkir test`
14. Let us install with following command <br/>`> pipenv shell`
This will create a new folder `Pipfile`
15. Now open a new terminal and go the 'virtual_env' directory and run command `> jupyter lab`<br/> This will open a new browser with Jupyter environment.
(If already know what you want in this virtual environment, you can directly install the required packages with `pipenv install <<packages>>` command.)
