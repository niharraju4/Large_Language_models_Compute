


# shortNotes

1. Define LLMs
   -LLMs are subset of DL </br>
   -LLMs and generative AI intersect, and they are both a part of deep learning </br>
   -This is a type of artificial intelligence that can produce new content - including text, images, audio,</br>
     and synthetic data
   -Large Language Models refer to large, general-purpose language models </br>
    that can be pre-trained and then fine-tuned for specific purposes.

---

Examples:-  
Imagine training a dog.Often you train your dog basic commands such as sit, come, down, and stay. </br>
These commands are normally sufficient for everyday life and help your dog become a good canine citizen. </br>
Good boy! But, if you need a special-service dog, such as a police dog, a guide dog, or a hunting dog, you  </br>
add special trainings, right? 


---

LLMS </br>
-Large </br>
-Large training dataset </br>
-Large number of parameters
General purpose   </br>
-Commonality of human Languagues  </br>General purpose is when the models are sufficient to solve common problems. </br>
-Resouce restriction



---

These models are trained for general purposes to solve commonvlanguage problems such as text classification, 
question answering,document summarization, and text generation across industries.The models can then be tailored 
to solve specific problems in different fields such as retail, finance, and entertainment,
using a relatively small size of field datasets. 




---

3 Major Features of LLMs
1st:- Large: Large indicates two meanings. First, is the enormous size of the training dataset, </br>
sometimes at the petabyte scale.
2nd:-it refers to the parameter count. In machine learning, parameters are often called hyperparameters. </br>
Parameters are basically the memories and the knowledge that the machine learned from the model training. </br>
Parameters define the skill of a model in solving a problem, such as predicting text. 

--

pre-trained and fine-tuned

which mean to pre-train a Large Language Model for a general purpose with a large dataset,
and then fine-tune it for specific aims with a much smaller dataset

---

Prompt design is the process of creating a prompt
that is tailored to the specific task
that the system is being asked to perform. 

---

3 Types of LLMs
1. generic Lang Models </br>
generic or raw lang models Generic language models: predict the next word based (technically token)based on the language in the training data.
Here is a generic language model.
In this example, the cat sat on...
The next word should be ‘the’ and you can see that ‘the’ is most likely the next word.Think of this model type as an ‘auto-complete’ in search.
![image](https://github.com/user-attachments/assets/82734fd6-de30-4d8d-8510-59012190b2a6)


3. instn-Tuned  </br>
Trained to predict a response to the intructions given in the input.  </br>
For example, summarize the text of x, generate a poem in the style of x, give me a list of keywords based on semantic similarity for x.
![image](https://github.com/user-attachments/assets/319b5009-d44d-4e92-bd8c-99b359a23ddd)

 
Examples:  in this ex classify tect into neutral, negative or postive

--

5. dialog-tuned  </br>
This model is trained to have a dialog by predicting the next response

Dialog-tuned models are a special case of instruction tuned where requests are typically framed as questions to a chat bot. </br>
Dialog-tuning is expected to be in the context of a longer back-and-forth conversation, and typically works better with natural, question-like phrasings. </br>
Chain-of-thought reasoning is the observation that models are better at getting the right answer when they first output text that explains the reason for the answer. 

 ![image](https://github.com/user-attachments/assets/9067a2e4-ff14-4f0f-94c8-d23d8e5a0644)
  
  </br>


![image](https://github.com/user-attachments/assets/5928841d-8e64-484e-8804-587412f4b7a7)

![image](https://github.com/user-attachments/assets/a8e54c42-7afc-400d-b70c-6741a0dc73a5)


![image](https://github.com/user-attachments/assets/9cfd27ce-b2d8-4902-aecc-d1ff8c60f1fd)


  

each needs prompting in different way.


---
3. Describe LLM use cases
4. Exp prompt tuning and describe google's gen AI development tools.
