# py_GTA5

Finally, use the model in game with test_model.py.

I upload the coades about Curriculum Project.
The code can be used for learning artificial intelligence in a game called Grand Theft Auto 5.
While I was looking for the contents of professional books and writing the AI development codes, I referred to the open source to study by myself.

Here's some information about the codes.

Explorations of Using Python to play Grand Theft Auto 5, mainly for the purposes of creating self-driving cars and other vehicles.

We read frames directly from the desktop, rather than working with the game's code itself. This means it works with more games than just GTA V, and it will basically learn (well, attempt to learn...) whatever you put in front of it based on the frames as input and key presses as output.

Currently, to use this version of AI, you will need to run first "Create_training_data.py," then balance this data with "Balance_data.py."

When creating training data, this works when you have the game in windowed mode, 800x600 resolution, at the top left of your screen. You need this for both training and testing. Eventually we can go off the window's name, but, for now, the current code wants the window in the corner.

Do this for as many files/training samples as you wish. I suggest 100K+ after balancing, but the more the merrier. ext, Train the model with train_model.py.

Finally, use the model in game with test_model.py.  


## model.py

This is my result that one of Ai model drving scene.
![Cap 2021-08-08 22-33-20-971](https://user-images.githubusercontent.com/86881143/129468422-31c75d42-dd8a-4ef5-b65f-f4067bd68663.jpg)

I collected a lot of data, and based on the data I collected, I was able to create a driving artificial intelligence model like the picture above through many learning processes.


## Also

Pull requests are welcomed!
