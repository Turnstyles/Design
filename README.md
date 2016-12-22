# Design
A design overview and a concrete example to work as a proof of concept and explain the vision

# Graphically
Why this black and white pen and ink style? Some of it is a design discipline. If you can create an interface that works in black and white you can style it in a thousand ways later, so it's a decent default and a way not to get distracted by graphical choices while focusing on the interactions and high level concepts.

It's also a style that I just like and find fun. It reminds me of the 70's and 80's when black and white was a great choice for self publishing because you could just use a photocopier and get your message out. The whole goal of this is a hand crafted asethetic and the goal of these games in my mind are physical books. Art objects that you print out and put on your bookshelf to read and share with your friends later in life. 

Finally, it was fustrating that computer screens did such a poor job with the contrast and fidelity of thin line ink work in the 90's so I'd like to have some fun with the new potential of todays high resolution displays to mirror print and screen. I'd like to see what works and what doesn't.

# Technically
To start, this design is technology neutral. I've done client side experiments with Flex, Backbone, Aurelia, Ember, React and Vue and server side experiments with Python, Ruby, C#, Javascript and Elixir as well as with a variety of databases. These experiments have helped me see a lot of technical trade offs and strengths and weaknesses in these things, but the focus is still always on the higher level concepts which can be implemented technically in any of these things or whatever new thing comes along that is worth experimenting with. At some point there is a core set of related models, ui concepts and flows that can probably be represented with Harel statecharts regardless of language, everything else is agnostech.

The goal was to focus on the high level design concepts and keep moving them along so that whatever I'm using technically when the design is complete, the design will be good. At this point I'm using Postgres, Elixir and Vue for my experiments, but that could change at any time.


