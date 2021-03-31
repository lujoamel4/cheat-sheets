# FAQ
## mvn clean install don´t work without sudo 
For Linux Users
What caused the problem:

    sudo mvn clean install on base pom.xml - linking all sub-projects to the root user

How I fixed the problem:

    Checked that all target folders belonged to the root user through ls -al * | grep target
    On the main project folder, where the base pom.xml is run:
        sudo chown -R username:username .
        Alternatively: sudo chown -R username:username /home/username/path/to/project

