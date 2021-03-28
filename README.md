# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

### How to run this project?

After cloning the project, open a terminal and run:

```
npm i
```

After the dependencies are installed, run:

```
npm run dev
```

The API to apply a filter to the image, will be available at the URL: http://localhost:8082/filteredimage

To test you must pass an image URL, for example:

```
http://localhost:8082/filteredimage?image_url=https://super.abril.com.br/wp-content/uploads/2019/04/gato_site.png
```

Image before filter

![cat](https://raw.githubusercontent.com/msmagnanijr/udacity-image-filter-starter-code/master/deployment_screenshots/gato_site.png) 

Image after filter

![cat-filter](https://raw.githubusercontent.com/msmagnanijr/udacity-image-filter-starter-code/master/deployment_screenshots/filteredimage.jpeg) 


### AWS Elastic Beanstalk Application

![elasticbeanstalk](https://raw.githubusercontent.com/msmagnanijr/udacity-image-filter-starter-code/master/deployment_screenshots/eb-dasboard.png) 

 Elastic Beanstalk App URL: 
 
 http://image-filter-starter.us-east-1.elasticbeanstalk.com
 
 http://mmagnani-udacity-image-filter-starter-c.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://super.abril.com.br/wp-content/uploads/2019/04/gato_site.png