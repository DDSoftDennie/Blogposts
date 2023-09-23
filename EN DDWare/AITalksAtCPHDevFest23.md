# AI Talks at Copenhagen Developer Festival 2023

## Introduction

I went to a festival, I went to a conference. A conference in a festival. A festival in a conference.
From August 30th till September 1st 2023 I went to the Copenhagen Developer Festival organized by NDC Conferences. NDC aka 'Norwegian Developers Conference' started as a Software Developers Conference in Oslo, Norway and has grown to an organization with conferences nearly all over the world.

NDC Conferences will always have a special place in my heart. Why? In 2017 my career as a speaker at conferences started at NDC Sydney.

But this one was special. Copenhagen Developer Festival is the first conference they organized (as far as I know) without the name NDC {Name_of_city} or a variant for example: NDC {Security_name_of_city}. They experimented with 3 days of software conference and 2 nights of festival. The festival had the well known Linebreakers, comedy acts, keynotes about space, balloon-games, guitaraoke (karaoke with guitars), music bands and more.

Although, for the rest of this blog I will focus on AI talks at the conference part.

## AI

I attended some talks about the amazing current times and future of AI. I chose to attend AI talks because I really do believe AI can make the world a better place. Although, I know there are some dangers too. Let's acknowledge the dangers and learn how the innards of AI work but focus on the possibilities AI can bring to the world.

### Iron Man or Ultron: Is AI here to help or hurt us?

As an AI lover and believer it's awesome to see the the one and only Scott Hanselman, Vice President of Developer Community at Microsoft presented his new keynote: "Iron Man or Ultron: Is AI here to help or hurt us?". In this talk Scott presented how AI can be both: good and evil. How human interactions will decide if the world is going to be a better or worse place. The technical focus was more on the newer forms of AI like LLM's (Large Language Models) and GenAI (Generative AI). Here, I will dig a bit deeper into 2 specific topics Scott talked about.

#### Large Language Models

Large Language Models (or LLM's) are large models that are trained on a lot of data and can be used to generate text. The most famous LLM is GPT-3 and GPT-4 is already born. GPT-3 is a model trained on 175 billion parameters. Those parameters are data from the public internet: A lot of e-books, articles, blogs, tweets, etc. It's trained by big companies or startups. For example GPT-3/GPT-4 is build by OpenAI, a company from the US.

Microsoft has a partnership with OpenAI, and provides a gateway to OpenAI's LLM services via Azure in the Azure OpenAI Portal. When you create an instance of 'Azure OpenAI' Service, you can go to a specific portal.

#### Temperature

With understanding what modern AI solutions like LLM technology are, you don't know the answer if the AI will help or hurt us. To understand this specific topic I need to introduce you with Temperature settings like Scott did for us in his keynote.

When you spin off an OpenAI instance on Microsoft Azure and go to the specific portal. The first thing you do is deploy a model. Once you deployed a model, you can start to fine tune it in the Playground (Playground is a part of the Azure OpenAI Portal). One of the important settings is called 'Temperature'. Temperature is a setting that can be used to control the randomness of the generated text. The higher the temperature, the more random the generated text will be. The lower the temperature, the more predictable the generated text will be. Scott presented this concept with a nice metaphor. Look to temperature as in the temperature of water. If you set it to the maximum (remember: water boils at 100 degrees Celsius) It will spit out! It will overcook! It will generate random hallucinations.

And of course you can set the temperature to the maximum, let the LLM hallucinate and publish an article how evil (Ultron in the talk) AI is. Or should you finetune the temperature, so that the AI behaves to assist human and we live with an Iron Man as our own copilot?

### Large Language Models: An Overview and Integration into Your Workflow

To learn even more about Large Language Model (LLM) technology I went to Ben Hall & Barbara Fushinka's talk called: 'Large Language Models: An Overview and Integration into Your Workflow'. As software developers, as companies, organizations and businesses it's not about just going to a website of a public AI provider but it's about implementing the (not so?) magic in your own applications and workflows. This talk was all about this process. I will dig deeper about the technology family where LLM's live: Transformers.

### Transformers

Everything starts with the Model.
To explain this concept I go a few years back in time when 'regular' AI showed up into cloud platforms and how software developers like me learned about the concept of AI compared to regular software development. If you write a program you write the logic. When applications are running there's an input flowing through your written logic and gives you the output. In fact here you can say that your program transforms the input via your written logic to the output.

AI is different. You don't write the program (or use another name: the model). You select a pretrained model and let the model refine itself via lots of inputs. This process is called 'Training'. During training phase you collect the output and measure if the outcome is good. If the outcome is desirable you praise the model, if the outcome is not good you punish the model. All of this you do on a cloud and let it run until it refined itself.

All Models have an architecture, just like you have differences and architecture in coded software. Transformers are a specific architecture of models. The Large Language Model GPT is a Transformer because it's just in the name! Generative Pretrained Transformer. A large Transformer model that is pretrained on lots of data to generate text. This pretraining is done by big companies like OpenAI.

### Applied AI and Accessibility to Play Games in New Ways

And because I do believe that a better world created with AI is a more Inclusive and Accessible world, I am lucky that Alex Dunn Presented his talk: 'Applied AI and Accessibility to Play Games in New Ways'.

Alex was an employer at a software company. After a while had the luck to form his own business from a pet project close to his heart. Alex is a gamer and has a nephew with a disability. Alex' passion in gaming and love for his sibling made him to create a pet project to make gaming more accessible. With AI models he captured gestures and translated them to keyboard and mouse input to control games.

### Hackathons

The project got a boost when Alex subscribed to a hackathon. A hackathon is a competition where you create a software solution to a problem. Like in each good competition, winners gain a price. What I learned in this talk is that it's really possible to win quite a bunch of money when winning a hackathon. Winning the hackathon combined with his passion made him to start his own business.

### The Solution

The solution he build was training a model that recognizes specific gestures via your device camera and audio input and link this to macro's, shortcuts and different kind of controls. A person who's not able to use keyboard, mouse, touchscreen or controller via the regular way can use this solution to play games and have loads of fun.

It uses Azure Cognitive Services, voice assistance services, custom Web API's and SignalR services from the Microsoft Azure Cloud.

### Use Cases

You can smile, move your head left or right, shout to your device via a computer or laptop. There 's even an iteration that works via Snapchat. And of course: Current days require to be playable via Twitch. Of course Alex' solution does this too! Even more: different gamers can help each other via giving specific Twitch command's in the chat.

Gaming can provide Quality of Life to people. So, why should we take this away from people with disabilities? Alex's solution is a great example how AI can make the world a better place.

## Conclusion

In this blog I wrote about AI talks at Copenhagen Developers Festival by NDC Conferences. I started with a short introduction about the festival and conference. I touched 3 AI talks I attended: Scott Hanselman's keynote about how AI can be good and evil. I went deeper into Large Language Model technology with Ben Hall & Barbara Fushinka's talk. I showed a use case how AI can be a solution to create a better world for people with disabilities with Alex Dunn's talk about how he created a solution to make gaming more accessible for people with disabilities.

