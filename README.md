# Udagram Image Filtering Microservice

## How to run the 
There two ways you can run this application, either clone the github repo and run locally or use the elastic beanstalk URL.

### 1. Using the elastic beanstalk URL.
> To run the application using the URL, simply open the link 

'http://udacity-udagram-image-filter-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url={{image_url}}'

eg 

'http://udacity-udagram-image-filter-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg'

### 2. Cloning the git repo
If you decide to clone the git repo, do the following,
> Download the application with:

'git clone https://github.com/ndakena/udacity-udagram-image-filter.git'

> Initialize a new project:      `npm i`
> run the development server with `npm run dev`
> The you can access the application through the link

'http://localhost:8082/filteredimage?image_url={{image_URL}}'

eg 

'http://localhost:8082/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg'




