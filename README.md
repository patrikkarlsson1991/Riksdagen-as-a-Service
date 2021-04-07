# Riksdagen-as-a-Service

Final project for the Building AI course - "Swedish Parliament as a Service 

## Summary

This is a project to create a chatbot capable of generating novel twitter posts as well as responding to others. Based on all the speeches from the last 20 years we get a chatbot capable of talking like a true politician. By comparing the output from bots trained on speeches from different parties and different times it could help highlight the main similarities and differences in the public debate.


## Background

While this might not be a problem to solve world hunger or achieve world peace, it's still an interesting topic and could provide a basis for further discussions on the public discourse in Sweden. Reading and listening to the speeches give a sometimes robotic feel sometime, where politicians talk more based on their party stance rather than expressing their own opinions in a free way. This could help highlight these similarities, in order to create a talking point of how we could bring more individuality and diversity of opinions as well. 



## How is it used?



The initial prototype would just be an interface where you choose some key parameters and let it generate text. This can then be developed to allow to provide it with topics or questions to allow it generate text in specific areas. It could also be used to automatically collect information on the discussions going on in public (e.g. through scraping the main headlines from the newspapers) and create a proposed reaction for different parties. 


## Data sources and AI methods

The data to train the model will be collected from the open database provided by the Swedish Parliament, which can be found on [this link](https://data.riksdagen.se/data/anforanden/)

The solution will be created in multiple steps

* Prepare data: Create a Vector Representation of the data in each speech
* Create text generation 
* Build interface for presenting text
* Extend interface with additional controls (eg. based on specific time, party or speakers)


## Challenges

It's important to always make sure that it is clear that the generated texts are from a Bot, and not being seen as real text created by humans. 

## What next?

There are multiple improvements that could be made to the model, such as:

* Expanding the bots functionalities to also be able to respond to given texts and issues. This could be done by not only looking at the individual speeches made, and include information on the speeches that they responded to in the different cases
* Expand the source material, e.g. from the Party Programs, official communications, social media feeds, etc. 
* Add the opportunity to segment on more factors of the user's choosing, e.g. specific topics, time, etc. 

In addition to this there are also a lot of new models for text generation that could be explored to further enhance the quality of the outpot from the bot. 


## Acknowledgments

* ...
