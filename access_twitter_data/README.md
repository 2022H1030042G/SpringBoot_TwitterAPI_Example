## Deployment
Steps:

* Clone this github repo
* Import project to Intellij
* Import the required dependencies in pom.xml
* Create developer app on twitter and put your details in applications.properties
```
spring.social.twitter.app-id=
spring.social.twitter.app-secret=
```
* Go to project directory and run below command
```
mvn spring-boot:run
```

Hit below url
```
http://localhost:8080/tweets/%23canada

Note: %23 is #(hash)
```
you will get latest 20 tweets for that hashtag

* You can replace canada with any other hashtag of your choice in browser

## Output

Below is a snapshot. 

```
For canada hashtag
```
<img src="snapshots/canada.jpg" width="100%" >

```


 
