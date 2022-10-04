---
layout: post
author: joe
---

<img src="{{ site.baseurl }}/assets/images/PostTitle.jpg" width="400">

Image by <a href="https://pixabay.com/users/geralt-9301/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2167835">Gerd Altmann</a> from <a href="https://pixabay.com//?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2167835">Pixabay</a>

### Witch sofware enviroment tools are state of the art for AI development?
A data based approach using Stack Overflow´s developer survey data from 2022.

### Introduction:
**When starting with AI development, the first point is to know the state of the art in SW development.  In order to select the best tools that past for you is not trivial. 
You can look at several blogs in internet and develop your oppinion. 
I want to take you in my journey for the search of such tools for my case. This way I hope you can apply the same argumentation and data search for finding the right setup for your case.**

Stack overflow is a well known blog site and they make every year a survey with very interesting questions about the programming field where people arround the world answer. This seems to me a good source of data in order to take my decission based on such facts, avoiding the bias of searching on the web.

At our group, we want to start AI development. We usually use Matlab in order to write algorithms. And Windows is often used. We don´t use a version management tool at the moment. Therefore we want to answer following questions:

1. Witch operating system is most adequate?

2. Does Matlab fits as AI programming language?

3. Witch code editors are more appropiated?

4. Witch AI libraries should we use?

5. Witch version managment is recomended?

So I took the most up-to-date data (survey 2022) and looked for answers.


### Operating System.
Looking at the survey, Windows, Linux and macOS are the most used operating systems. 

![OS]({{ site.baseurl }}/assets/images/OperatingSystem.png)

For our AI purpose we select the people that indicated to work as data scientist or machine learning.

![Development types]({{ site.baseurl }}/assets/images/ML_group.png)

About 5% of the people work as data scientist or machine learning. 

If we look in the group of people that work with data science or machine learning, windows and Linux are the most used operating systems.


![OS for machine learning]({{ site.baseurl }}/assets/images/OperatingSystemML.png)

As at my group Windows is good available, we can say that this is an appropriate operating system for us.

### Programming language for AI.

At our group there is a main stream for programming SW and working with data: Matlab.
Looking at the survey it seems not to be the main stream.

![Weight of MATLAB]({{ site.baseurl }}/assets/images/Matlab.png)

Only about 4% of the people work with Matlab. 
If we look into the group of people working in data science/machine learning, the most used language is Python:

![Language for AI]({{ site.baseurl }}/assets/images/AI_language.png)

And Matlab is way back with under 2%. 
Therefore we have the first answer to the state of the art language for the AI development: Python.
In this case the move from Matlab to Python is a strong recommendation for our group.

### Programming environment:
Looking the programming environment, the most used for AI and Python are Visual Studio, Jupyter and PyCharm:

![Code editor for AI]({{ site.baseurl }}/assets/images/AI_ProgEnv.png)

### AI Library/tools: 
Another big question is witch AI libraries to use. In my experience, it depends a lot on with witch libraries the people started to learn AI algorithms with.
On the survey we find four very usual AI libraries: TensorFlow, Scikit-learn, Torch, PyTorch and Keras.

![AI tools and packages]({{ site.baseurl }}/assets/images/AI_libraries.png)

Looking at the group of people working on AI, Sckit-learn  is the most used. But all four libraries are relevant on the field.  Keras and Tourch are very similar.


### Version Management tool:
GIT is the most used version management tool with a lot of distance to the well known SVN. 

![Version managment tools]({{ site.baseurl }}/assets/images/GIT.png)

Therefore GIT is a good recommendation for our group. This is independent of AI development or other SW development. 

## Conclusions

In this post I show you how I searched for a optimal software setup based on data. 
In my case the data from Stack Overflow survey gave me a good basis.
You can find my code at the following Github repository:
https://github.com/user235p/Survey

Applied to my case, the optimal setup for developing AI SW at my group would be:
Operating System: Windows
Language: Python
Code editor: Visual Studio
Version managment: GIT 



I hope it helps you find your right set!





