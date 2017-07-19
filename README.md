# Deep-Learning
Repository for Deep Learning class in Udacity

[//]: # (Image References)

[image1]: ./images/start_docker.PNG

## Set working environment
1. Install Docker for Window on local PC
2. Start Docker for Window, Click Docker for Window icon on desktop
3. Open a Window terminal
4. Run Docker image in Window terminal: 
    
        docker run -p 8888:8888 --name tensorflow-udacity -it gcr.io/tensorflow/udacity-assignments:1.0.0_ 

        if you ever exit the container, you can return to it using:
        
        docker start -ai tensorflow-udacity

![Start Docker][image1]

5. Open a browser using URL: _http://localhost:8888_
6. Reference:

    http://cs231n.github.io/linear-classify/
    
    https://classroom.udacity.com/courses/ud120
    
7. Add jupyter notebook file in the github.com repository

    File => Download as => Notebook (.ipynb)
    
    Copy dowmlorded file to the local repository folder
    
    Use _git add <notebook file name>_ to upload the file
    
    


        
