# Riksdagen-as-a-Service

Building AI course  project - "Swedish Parliament as a Service"

## Summary

This is a project to create a model capable of generating text based on all the speeches from the last 20 years in the Swedish Parliament. By comparing the output from models trained on speeches from different parties and different times it could help highlight the main similarities and differences in the public debate.


## Background

While this might not be a problem to solve world hunger or achieve world peace, it's still an interesting topic and could provide a basis for further discussions on the public discourse in Sweden. Reading and listening to the speeches give a sometimes robotic feel sometime, where politicians talk more based on their party stance rather than expressing their own opinions in a free way. This could help highlight these similarities, in order to create a talking point of how we could bring more individuality and diversity of opinions as well. 


## How is it used?

The initial prototype would just be an interface where you choose some key parameters and let it generate text. This can then be developed to allow to provide it with topics or questions to allow it generate text in specific areas. It could also be used to automatically collect information on the discussions going on in public (e.g. through scraping the main headlines from the newspapers) and create a proposed reaction for different parties. 


## Data sources and AI methods

The data to train the model will be collected from the open database provided by the Swedish Parliament, which can be found on [this link](https://data.riksdagen.se/data/anforanden/)

The solution will be created in multiple steps

* Prepare and clean the data and create Vector Representation of the data in each speech
* Build a text genrerating model that can train the model  entire data set or chosen subsets 
* Build interface for interacting with the model and presenting the generated text
* Extend interface with additional controls (eg. based on specific time, party or speakers)


## Challenges

There will be lot of technical issues to deal with thoughout the project. The most important thing is however to always think of the ethical aspects, e.g. by making sure that it is clear that the generated texts are from a Bot, and not being seen as real text created by humans. 


## What next?

There are multiple improvements that could be made to the model, such as:

* Expanding the bots functionalities to also be able to respond to given texts and issues. This could be done by not only looking at the individual speeches made, but instead also include information on the speeches that they responded to in the different cases
* Expand the source material, e.g. from the Party Programs, official communications, social media feeds, etc. 
* Add the opportunity to segment on more factors of the user's choosing, e.g. specific topics, time, etc. 

In addition to this there are also a lot of new models for text generation that could be explored to further enhance the quality of the outpot from the bot. 


## Acknowledgments

* I'd like to thank the people behind the [Building AI course](https://buildingai.elementsofai.com/) for the course and the inspiration to further explore the opportunities with ML and AI
* The Swedish Parliament for providing their data in an accessible and comprehensive way
