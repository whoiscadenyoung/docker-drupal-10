# docker drupal 10
 Dockerized version of Drupal 10

My work environment restricted the use of homebrew, which made it difficult to install PHP and Composer. And I wanted to be able to have control over Drupal files on my local machine, so I could make updates faster to themes and modules. The default drupal package didn't allow for this very easily from what I could find, so I decided to build a version of Drupal on my local machine and copy this to the docker image. Not exactly the peak of efficiency but it gets the job done.

If you would like to use this, make sure you have docker-compose installed. Additionally, make sure to change the variables in the .env file for a production-level build.
