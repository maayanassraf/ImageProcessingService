# Image processing service


Developed Image Processing Service, Using Telegram as a front, 
data will reach from telegram to the bot, which will process the image
and returns the result to the chat, like the below demo: 


![](.img/demo.gif)

# Guidelines

## How To Use

For using the bot you'll need a telegram account, 
when you have an account all you need to do is to get in the app chats and search 
for ImageProcessingBot, then you can just send to the chat the photo and the filter you want 
to apply, and if everything all right and the filter exists, the filtered photo will return.

## Available Filters

There are variety filters available, each will affect differently, as described below:  

### Blur

The blur filter, as it names will blur the image, you can control the blur level, 
by forwarding in addition a blur level as a number, the default level is 16.

### Contour

The contour filter, will apply a contour effect on the image.

### Rotate

The rotate filter will rotate the photo sent in 90 degrees.

### Segment

The segment filter will represent the photo in a more simplified manner,
so objects and boundaries will be able to identify easily.

### Salt And Pepper

The salt and pepper filter will "distort" the photo, 
reflects as the appearance of these randomly scattered bright and dark pixels, 
resembling grains of salt and pepper sprinkled on an image.

### Concat

The concat filter will concatenate two images together horizontally (side by side).
the dimensions of both images needs to be compatible for concatenate.
You have to provide 2 photos for this filter.

## Hope you will enjoy from the image processing!