# GoogleDraw
UofT Hackathon Project :confetti_ball: - A voice assistant that helps you draw art using "Google Assistant"

## Our Logo - 

<img width="690" alt="screen shot 2018-01-21 at 10 19 52 pm" src="https://user-images.githubusercontent.com/15865085/35204184-718c3206-fefa-11e7-8909-17ffec947a0d.png">

## Screenshots from the Assistant-App in action - 

- How it greets us -

<img width="693" alt="screen shot 2018-01-21 at 10 20 06 pm" src="https://user-images.githubusercontent.com/15865085/35204203-900d904e-fefa-11e7-931a-1743b79a8290.png">

- Help functionality - 

<img width="688" alt="screen shot 2018-01-21 at 10 20 15 pm" src="https://user-images.githubusercontent.com/15865085/35204216-a307acc0-fefa-11e7-9ee3-88a4278a3df3.png">

- The very first drawing we've done by Google Draw -

<img width="692" alt="screen shot 2018-01-21 at 10 20 24 pm" src="https://user-images.githubusercontent.com/15865085/35204218-adc444c0-fefa-11e7-9c23-4438407ef9e5.png">

## Project Story - 

The inspiration for Google Draw came about when one of our team members experienced the struggle of attempting to draw with a fractured wrist. Google Draw allows users to provide the Google Assistant with vocal direction to create sketches, construct geometric shapes and fill in colours. As hands are a key element to this creative process, it is especially useful for individuals who want to express their creative side through art but have limited hand mobility or are amputees. The Google Draw works based on a coordinate-grid system. We require from the user to select indices in the number-labeled grid to create points and join them using keywords, such as “connect” or “link”. Once enclosed shapes are produced, then users may choose to fill them in with colour. We used a NodeJS library to create our own blank canvas image that updates with every dialog instruction the user provides. Using the intents and entities for the DialogFlow AI API we were able to train the Google Assistant. Lastly, we used Firebase Server SDK and Storage to integrate it all. We hit a few bumps on the way when we were trying to find out which library would be most suitable for the creation of the canvas image, without using HTML rendering. Although the documentation of the Firebase SDK Server and Storage is very well-written, we had a tough time going about the bugs due to the limited resources online. After overcoming the difficulties and engaging with new programs, the demo is now complete and this already gives a means of self-expression similar to that of able-bodied digital artists. Additionally, we have future plans of implementing an important key feature called the “Poetic Colour Palette”. This feature allows users to verbally express how they are feeling and the Google Draw application will prompt the user with appropriate colour palettes. If the user is sad, we might offer a more blue-toned palette whereas if they are relaxed, we might offer a purple palette. We hope that our innovative attempt to provide an inclusive art-based application for this standing issue sparks your interest and ignites the passion that will boost this project to its full potential.
