# app-debug-androidTest.apk

Miguel Goncalves silva 
Student ID: 22423 

1. Movie recycler view:
1.1. Create a Movie class with the structure specified in movie.json
1.2. Obtain and fill data (minimum of 4 movies)
1.2.1. Obtain relevant movie data from Vue (https://www.myvue.com/cinema/dublin/whats-on) or your favourite provider and add data credits at the bottom of the app
1.2.2. Generate a random number between 0 and 15 for each movie and assign to seats_remaining
1.2.3. Start with an initial default seats_selected value of 0 for all movies
1.2.4. You shall fill random URLs for images from pixabay or other free image providers to begin with
1.3. Build a Recycler View using the specified template, refer to recycler_view_template_*.jpg
1.4. If any seats are selected, show how many seats are selected and hide remaining seats
2. Seat selection feature:
2.1. Clicking any item (anywhere on the item) on the movie recycler view should open a new MovieActivity, refer to movie_activity_*.jpg
2.2. Add plus and minus icons, show seats_selected in the middle
2.3. On click plus/minus, update both seats_selected and seats_remaining for that movie
2.4. Add validation, when 0 seats selected minus is disabled, when 0 seats remaining plus is disabled
2.5. When back is pressed, the selected seats are retained and reflected in the recycler view. (Hint: If you don’t see any updates, call adapter notifyItemChanged as soon as you return to the recycler view activity)
3. Bonus:
3.1. Add "filling fast" badge if less than 3 seats remaining
3.2. Use "Roboto Condensed" font to replicate same style
3.3. Use original movie images from myvue.com or your favourite provider (Hint: check get_movie_image_url.gif)

----REPORT -----

Developing an app on Android Studio using Kotlin can be a very challenging task. In this project uncontable issues were faced and it could be very frustrating to not be able to understand all the erros it were found, but with some persistence many of the problems were fixed. Although Kotlin is a modern and expressive programming language that has been designed to make Android app development more concise and easier it can be very different faced in practice for beginners users, user friendly might not be the best way to describe the app.

One of the main difficulties of creating an app on Android Studio using Kotlin is the steep learning curve. While Kotlin has many features that can simplify coding and make it more readable, it is still a relatively new language and many developers are still learning how to use it effectively. This can lead to issues with coding efficiency and productivity, especially for developers who are new to the language or do not have a  background with Kotlin.

Another challenge is the complexity of the Android ecosystem. The Android platform is highly fragmented, with numerous devices and versions of the operating system in use so it can lead to some difficulties related to compatibility. This means that developers must consider a wide range of factors when creating an app, such as screen sizes, resolutions, and different hardware configurations and not always this is gonna work. 

Testing is another area where developers can face difficulties when creating an app on Android Studio using Kotlin. The Android platform provides a wide range of testing tools and frameworks, but it can be challenging to create effective and efficient tests for complex apps or even simple ones as the movie one. Kotlin has features such as extension functions and coroutines that can simplify testing, but there are still challenges associated with creating comprehensive and effective tests.

Finally, there are challenges associated with maintaining an app over time. As an app evolves and new features are added, it can become increasingly difficult to manage the codebase and ensure that it remains maintainable and scalable. Kotlin provides features such as data classes and lambdas that can help with this, but developers must still be proactive in managing the codebase and ensuring that it remains efficient and effective over time.

In conclusion, creating an app on Android Studio using Kotlin can be a very challenging task, but it is also highly rewarding when somenthing finnaly works. While there are challenges associated with learning the Kotlin language, dealing with the complexity of the Android ecosystem, testing, and maintaining an app over time, Kotlin provides many features that can simplify coding and improve app quality and youtube tutorials can help to make it work. With the right tools, resources, and mindset, developers can overcome these challenges and create highly effective and successful apps on the Android platform.
