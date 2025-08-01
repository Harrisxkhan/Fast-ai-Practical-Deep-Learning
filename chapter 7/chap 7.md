Collabortaive filterig: we use CF in recommendations systems. it heavily relies on CF.
IT predeicts the next thing based on user previous data.


Vector is just a list of numbers,
embedding is a special vecotros that repsresint meaniinf ofsomthing

First its just rraw vectors , and ten its trained and then in convers into embedding vectors thayt catoptures sementic meaning and represent somethig meaning.


Each user has their vector embedding showinf their taste
each movie shpwing tgheir vecotre embedding showing its style , comedy action style etc..

Then we take the users embedding vectro amd amd the user embedding vector,.. anf then do a dot product between them shpwinf thier taste..
if the reuslt is high then its a good match,
if low the nsuer might not likr it..

When we multiply two vetors togeaher and add them up this is called dot product, we use this a lot in machine learning, and Matrix Multiplication  as well.

The users data are so big, so fat traning it compresses them, its like hidden cahratristics. which humans cant see, and model discoverst his automatically. 

Weight decay is method we use in regulirzation, it is to stop overfitt.   

If thw weigt becomes to large, we set up the penalty, by using lamba, it pulls extra weight to zero.
