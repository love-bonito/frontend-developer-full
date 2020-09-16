## Love, Bonito VueJS Frontend Developer
 
 
If you are here, it means that you want to work at Love, Bonito. 


Through these exercises, we will be able to understand your skills. We will be using real case scenarios instead of riddles. 


### Before you start 

1. For this challenge you will use VueJs. 

2. Create a new repository on Github or Gitlab, whatever you fancy more

3. Every Challenge should have 1 `closed` Merge Request/Pull Request, so when you do the Challenge 1 you will create a Merge Request to `master` and you will leave it close. At the end of the test, you  will end up having one closed Merge Request per Challenge.


### Extra considerations

* Testing is an important part of our development process. Both unit testing and functional testing are required.

* Be sure that your code applies the [Javascript Standard Code Style](https://standardjs.com/) 


-
### Challenges

We want to create a website to show all the characters and locations for the universe of Rick and Morty. In order to complete that, you will have to get the information from the public [Rick and Morty's API](https://rickandmortyapi.com/). 


#### Challenge 1 - Rick and Morty Content

In the home page of our application, we want to see a list of all the locations, you can get them [here](https://rickandmortyapi.com/documentation/#get-all-locations) 

When you click over the location, **without changing our current URL**, we should be able to see all the characters `dead` or `alive` for that specific location. 

Remember it's important to show the images and some brief information for each character. 

When you click on one of the character names you should be redirected to the character page. Here we are going to show as much information we can get for each character. The Character page should have a unique url.

> Do not forget the tests


-

#### Challenge 2 - PWA

As a frontend developer, you should be able to understand and implement a Service Worker. This challenge is going to be around PWA. 

At the end of the Challenge, your application needs to pass the PWA section in Lighthouse

1. As a first task, you should be able to identify all the static content that we use and cache it on our new service worker. 

2. Now it's time for the offline access content. For this, we need to cache the Locations and the Characters, in order to do this you should use indexDB. If the content is already loaded we don't need to load it again. The way to test this, is load the page and then open the Chrome console and select `offline` in the network section, reload the page should show the content, even offline.

3. In the character page, some of the information will come from the list of Characters, so we will need to use this information to pre-populate the information on the Character page, and load the missing part later. It's important that if you directly access the URL of a specific character, you can still see the whole content.
One simple way to test this functionality go to the `home page`, and then when you click a character you will load the new page without calling yet to the api, and we should be able to see some information. 


##### Resources for this challenge

- [Service Worker](https://developers.google.com/web/fundamentals/primers/service-workers)
- [Storage for the Web](https://web.dev/storage-for-the-web/) 


-
#### Challenge 3 - Micro-Interactions

You can use your creativity and knowledge of UI/UX to find some, or more than one, micro-interactions that you want to add to the project. It would be great to smoothen all the transitions and take the dynamic loading content properly. 

##### Resources for this challenge
- [Micro-interactions: why, when and how to use them to improve the user experience](https://uxdesign.cc/micro-interactions-why-when-and-how-to-use-them-to-boost-the-ux-17094b3baaa0)

-
#### Challenge 4 - Performance

The performance score in your lighthouse should be as close to 100 as possible. In this part of the challenge, you can fine-tune your application. It's important that you add whatever documentation you think is necessary. 


#### Challenge 5 - CI/CD

If you are using Github for the project everytime we push a new code on the system we should run, eslint, unit test, and functional test using [Github Actions](https://github.com/features/actions), it will be the same for Gitlab but you should use [Gitlab PIpeline](https://docs.gitlab.com/ee/ci/pipelines/)

Lastly, you can use vercel.com or another platform to deploy your notice that you can use the free plan to deploy the app. The Deploy need to happens from Github Actions or Gitlab Pipeline


### Wrapping up
In the README file we should be able to find all the information necessary to run the project/test and deploy. It'd be helpful if you can add extra relevant information. 

### Delivery of the project

Please share the URL of the repository and the vercel.com URL with pablo.morales@lovebonito.com and aman.agarwal@lovebonito.com, remember to let Celeste (celeste.ngooi@lovebonito.com) know that you have finished the challenge.








