## Love, Bonito Magento Frontend Developer
 
 
If you are here means that you want to work at Love, Bonito. 


During these exercises, we are going to try to understand your Skills. We want to use real case scenarios instead of riddles. 


For this project, we would require to use Bulma as a CSS Framework https://bulma.io/documentation/. We don't require any specific layout or look and feel for the project feel free to do it as you please


### Before you start 

1. Create a new repository, it's important that you don't do Merge Request to this repository, you will do it over your repository.

2. Every Challenge should be 1 open Merge Request/Pull Request, so when you do the Challenge one you will create a Merge Request to `master` and you will leave it open. At then you will have one open Merge Request per Challenge. If your code depends in other Merge Request you will point the MR to the dependant branch instead of `master`

3.  At then you need to share the link of the repository to pablo.morales@lovebonito.com and aman.agarwal@lovebonito.com and remember to let Celeste knows that you finish


### Extra considerations

* Testing is an important part of our development process. Unit test and functional test are required

* Be sure that your code applies the [Javascript Standard Code Style](https://standardjs.com/) 


-
### Challenges

We want to create a website to show all the characters and locations for the universe of Rick and Morty. In order to do that you are going to get the information from the public [Rick and Morty's API](https://rickandmortyapi.com/) 


#### Challenge 1 - Rick and Mory Content

In the home page of our application, we want to see a list of all the locations, you can get them [here](https://rickandmortyapi.com/documentation/#get-all-locations) 

When you click over the location, **without changing our current URL**, we should be able to see all the characters `dead` or `alive` for that specific location. 

Remember it's important to show the images and some brief information for each character. 

When you click on one of the character names you should be redirected to the character page. Here we are going to show as much information we can get for each character. 

-

#### Challenge 2 - PWA

As a frontend Developer, you should be able to understand and implement a Service Worker. This challenge is going to be around PWA. 

At the end of the Challenge, your application needs to pass the PWA section in Lighthouse

1. As a first task, you should be able to identify all the static content that we use and cache it on our service worker. 

2. Now it's time for the offline access content. For this, we need to cache the Locations and the Characters, in order to do this you should use indexDB. If the content already loaded we don't need to load it again. 

3. In the character page, some of the information will come from the list of Characters, so we need to use this information to prepopulate the information on the Character page, and load the missing part later. It's important if you access directly to the URL of a specific character you can still see the whole content.


##### Resoruces for this challenge

- [Service Worker](https://developers.google.com/web/fundamentals/primers/service-workers)
- [Storage for the Web](https://web.dev/storage-for-the-web/) 


-
#### Challenge 3 - Micro-Interactions

We don't have specific requirements for this challenge, here you can use your creativity and knowledge of UI/UX to find some, more than one, micro-interactions that you want to add to the project. It would be great to smooth all the transitions and take properly of the dynamic loading content. 

-
#### Challenge 4 - Performance and wrap-it up

The performance score in your lighthouse should be as close to 100 as possible. In this part of the challenge, you can tune in your application. It's important that you add whatever documentation you think is necessary. 

Lastly, you can use vercel.com or another platform to deploy your notice that you can use the free plan to deploy the app.


### Delivery of the project

After you have your project upload in vecel.com or similar, please share this URL and the github/gitlab repository of the project with all the Pull Request accessible to pablo.morales@lovebonito.com and aman.agarwal@lovebonito.com, remember to let Celeste knows that you finish with the challenge.







