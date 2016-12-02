# ELIZA-ChatterBot

I am interested into creating customized ChatBots, mainly in Python. So far in my self-study I have found two ways to go about that.
First I found ChatterBot, developed by gunthercox right here on GitHub. He uses Machine Learning to train the chatbots how to respond to familiar statements.
Second was ELIZA, a simple, yet sophisticated 'dictionary-and-list' chatbot that acted like a therapist.

However, I found that ELIZA didn't do well responding to statements outside of her 'comfort zone,' and ChatterBot was a bit difficult to train for customized response (at least to me).
So I combined the two!! Given normal psychobabble, this program will produce an Eliza response, but for statements that dont match (e.g. Clouds are pretty.) the ChatterBot will come up with a best match response.
I was able to wrap this program inside guntercox's tkinter-gui example, which works really well.

My goal with this project is to tweak some of the customizations and eventually use it a template for other conversational chatbots that know how to respond to everyday social niceties and can generate responses outside of that scope!


ELIZA: https://www.smallsurething.com/implementing-the-famous-eliza-chatbot-in-python/

ChatterBot: https://github.com/gunthercox/ChatterBot

ChatterBot/examples/tkinter-gui: https://github.com/gunthercox/ChatterBot/blob/master/examples/tkinter_gui.py
