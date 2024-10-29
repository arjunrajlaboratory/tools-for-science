---
description: >-
  Arjun Raj, with input from Anne Carpenter and the members of Mid-Career PI
  Slack
---

# Using AI in academia

AI is everywhere these days, from AlphaFold to image analysis, allowing for incredible scientific advances. However, another compelling use case for AI in science is using AI to help with the procedural aspects of science—things like writing letters, filling out forms, giving initial basic quality check-style feedback, and so on. Used with care and skill, AI chatbots can substantially reduce the time spent on many of these tasks, giving us back time to spend on the aspects we enjoy the most, like thinking about science, guiding trainees, and interacting with other scientists. These opportunities are particularly salient these days when levels of faculty stress and burnout are at sky-high levels, with increased paperwork burden coming from all directions. We recently held a meeting with several members of Mid-career PI Slack in which we discussed the various ways one can use AI to improve work efficiency, upon which this blog post is based (along with some of Arjun’s own personal thoughts and observations).

Note that there are several other uses and misuses of AI in science and academia. Aside from actual research using AI, AI is also extremely helpful for coding. We didn’t really cover coding with AI, but I will say that if you haven’t tried Cursor, you should 😀. Another whole area is teaching, for which the changes wrought by AI can be profound in some instances and surprisingly negligible in others. Both of these topics are worthy of their own blog posts but weren’t really touched upon much in our discussions.

If you are looking for a bottom-line recommendation for how to get started, I can save you some time and recommend the following course of action:

{% hint style="info" %}
It is critically important to consider privacy as you use AI, because your data may end up in a company database. Please see [this section](using-ai-in-academia.md#privacy-and-ethical-use) for a more detailed discussion.
{% endhint %}

1. Subscribe to Claude 3.5 Sonnet (new) from Anthropic. _It’s $20, just do it for a month._
2. Actually commit to trying to use it for various tasks. It takes at least a few days of concerted effort to get a feel for it. Don’t expect an immediate “eureka” moment.
3. Ask it for a critique of a recent grant aims page or paper abstract, asking it to focus on specific problems.
4. Ask it to write a letter of reference after pasting in a couple of example letters. [Hide identifying information for privacy reasons.](using-ai-in-academia.md#privacy-and-ethical-use)
5. Paste in at least one or two screenshots (AI tools like Claude can “see” what you pasted in), and ask it questions. For example, “Here’s a figure with some genes that go up and down, what can you tell me about what pathways are likely activated?”
6. Make sure to go back and forth with it if it doesn’t give you what you want initially.

### What AI tools are out there?

AI comes in many different flavors, but the one that has captured the general imagination is the large language models (LLMs) that power the various “chat” style interfaces currently available. Basically, these models are extremely powerful text generation engines that predict the next best word and chain that together to come up with text output. ChatGPT from OpenAI is perhaps the best-known example, but there are many others, notably Claude from Anthropic, Gemini from Google, and Llama from Meta (open source). Each company has several models, which are basically a set of weights that provide certain kinds/quality of output. For instance, you may have heard of “GPT-4o”, “o1-preview”, “Sonnet 3.5”, or “Haiku”. These are different models, each with different strengths and weaknesses. I will say that I have not played around much with Gemini—I did for a bit and found it to be the least useful model, but I do think that there are other reasons to be very optimistic about Gemini in the long term.

It’s well beyond the scope of this post to go into all the differences here, but I will highlight a couple of points that I think are worth considering. Each company offers a free-tier model, either with limited capabilities or limited bandwidth. I strongly recommend trying the paid models. I have found that many people who shrug at the capabilities of AI have typically only ever used the free versions. I think it is well worth spending $20 a month (the typical subscription price) to gain access to the latest versions. These more powerful models produce higher-quality output and are also a lot “smarter” than the free versions. Just try it for a month.

Another common question is which one to get. For me, I derive enough value from these services that I pay for multiple. But I think if I had to pick just one, **I would pick Claude 3.5 Sonnet (new) from Anthropic**. Its coding skills are spooky good, and it also is a very strong writer. Included with Claude is also the Claude 3 Opus, which is better for some more complex writing tasks. ChatGPT-4o is great for many things, and the o1-mini and o1-preview, which have been designed for more sophisticated reasoning, have some clear use cases. (Note that the ability of these models to reason—whatever that means—has been [hotly debated](https://arxiv.org/abs/2410.05229), but regardless of their actual ability to reason, in practical terms, these models can certainly perform better at tasks that require somewhat more complex thought patterns.) But Claude 3.5 Sonnet is probably going to get you the most bang for your buck out of the gate.

### What can they be used for in academia?

The answer to this question is really just about everything 😀. An enormous amount of our work is based on text generation, summarization, and editing, and virtually all of these tasks can be streamlined in some way, shape, or form by AI. Here are a few of the more well-known examples:

1. Letters of recommendation/Tenure letters
2. Grant writing, including associated boilerplate documents
3. Progress reports
4. Paper writing
5. Literature review
6. Summarizing large numbers of documents or providing a “chat” interface to those documents.

However—and I cannot emphasize this enough—think creatively. There is no instruction set for these tools, and they are capable of a great many things. I still find myself amazed at what these things can do. For instance, I was working on our departmental ABET accreditation 🫠 and I had to take a bunch of data from some junky website that was organized by course and somehow tabulate it by year or something like that. I just pasted in a bunch of raw, copy-pasted text and asked it to tabulate it… and voila, perfect job!

**I will give a few use cases and then some general principles.**

### Content generation

#### Letters of recommendation

Perhaps the most illustrative example of how to use it is in writing letters of recommendation. Most academics I know have folders filled with existing letters, which they then copy and paste mad-lib style into a new doc to start a letter for someone. (I think we’ve all read the letter about Jim that still has a few references to Jane in it, right?) AI provides a great way to automate the writing of these letters, and going over this particular use also provides a window into how to use these chatbots most effectively for these sorts of tasks.

A common complaint is that the letters it generates are filled with “fluff”. Certainly, if you go to a chatbot and give it a prompt like this “Write a letter for Jane, who was an undergrad in the lab. She did some nice work and I give her a strong recommendation”, then sure, it’s going to be pretty fluffy. It’s worth noting here that AIs cannot make up the details, and they generally are not particularly good at reasoning (although that point is increasingly debatable).

Now try again, but this time, paste in a couple of examples of letters you’ve already written (for someone else is fine), maybe also the trainee’s CV **(with** [**identifying information removed**](using-ai-in-academia.md#privacy-and-ethical-use) **from letters and CV)**, and then give a few more details. See the difference?

{% hint style="info" %}
Another reminder: it is critically important to consider privacy as you use AI, because your data may end up in a company database. Please see [this section](using-ai-in-academia.md#privacy-and-ethical-use) for a more detailed discussion.
{% endhint %}

This illustrates a couple of points that are really important in working with AI:

1. Give it examples (i.e. model the output in the context window—to be discussed more later).
2. Provide it with clear, specific instructions.
3. If there’s something you don’t like, ask it to fix it.

The same goes for tenure letters. It really helps to be able to upload the large morass of documentation and have it parse and distill it for you.

I will also note that AI will save you some time, but it won’t always reduce your work down to 0. As in, it may save you 50-75% of the time spent, but not 95%. That’s still a HUGE savings! But often, people get frustrated because they expect it to just magically do all the work for you. Sometimes it can, and it does indeed feel magical. But that doesn’t mean that it doesn’t save substantial time in aggregate.

#### Grant writing

Another huge task for many academics is grant writing. While the science itself can be enjoyable to write about (itself perhaps a debatable point 😀), there are so many other documents, many of which are tedious to write but are required for submission. AI can greatly assist with a lot of these things.

Here are a couple of workflows/tips:

For writing the science

1. Give it a relatively detailed outline.
2. Ask it for feedback on the outline and what might be missing.
3. Then ask it to turn the outline into text. Give examples of grants/text you’ve already written so it can mimic your style.
4. Ask it to come up with some pitfalls and alternatives.

A few notes: Don’t ask it to write huge chunks all at once. Often, it will get confused. Going section by section, maybe a paragraph or a page at a time, is often more effective.

Try also using it to help you with budget justifications and other random documents. Often, it’s helpful to paste in everything else so it has the full context. Again, giving it examples will be very helpful.

Often, you will find yourself rewriting what the AI did, and you may wonder what the whole point of using it was. I have found that it often gets you over the hump, effectively getting you past the “staring at the blank page” issue. It can be helpful to use it to help organize thoughts. For instance, I will sometimes take a bunch of random thoughts and ideas. Then I’ll use o1-preview to help me reason through the organization of those thoughts into a logical flow. Then I’ll make a detailed outline, both manually and with AI. Then I’ll have the AI take a stab at converting to text. I may end up rewriting a lot of it, and that’s okay. Overall, I feel like it definitely saves me substantial time.

Another mode of use that is easy to miss is as an adversary. Use it as reviewer #3! Ask it for critical feedback. What parts are not clear? Where could the language be improved? Any suggestions for improvement? I’ve found that it often catches the same things that humans do, but much more efficiently, comprehensively, and without nearly as much of the fear of being judged.

#### Paper writing

Much of the above can also be applied to paper writing, in particular the adversarial mode.

Beyond that, it’s also very helpful for proofreading various parts and also shortening text. I like using it for methods to help look for ambiguities. Also, it is good at looking over figure legends and the such. Again, I think there are dozens of ways one could interact with text here. I personally have not found much use in generating large parts of the main text because I tend to pore over every word. I’m not sure this is a good thing, though… my approach tends to lead to fairly dense text, and perhaps some fluff might be helpful here (same with grants).

Also, don’t sleep on the vision features! Ask it to look at your figures and give you feedback.

Anne notes that we are still on the lookout for AI tools that do a good job at editing text from scientific papers and grants. We are looking for a tool like Grammarly that works natively in our regular word processing software but points out more than just minor copyedits—we would be hoping for PI-level suggested edits, like code autocomplete but for text. We’d be delighted to hear if anyone has suggestions for such tools (ideally, trained on a professor’s past edits in their Google Docs history!).

#### Principles of generative applications

Okay, so now that we’ve gone through a couple of examples, perhaps there are some general principles that we can distill. First, though, there is an important concept in LLMs that is useful to keep in mind: the context window. You can think of the context window as the working memory—it’s where your current conversation with all the back and forth is stored, along with all the documents and images you uploaded. You may have noticed a “Your chat is getting very long, do you want to start a new chat?” warning, which is the LLM telling you you’re about to run out of context window. LLMs are able to distill and synthesize and work with all the things that are in the context window. Knowing what is in the context window is a key aspect of using LLMs effectively.

Anyway, some principles:

1. Effective prompting requires explicit, clear instructions. The better the quality of your thought going in, the better the quality of the output it will generate.
2. That said, you can iterate towards high quality. Ask it to fix things and interact with it.
3. Over time, you will gain an appreciation of the “chunk size” that an LLM can handle. Give it problems that are too big, and it will get confused. Too small, and it’s not worth the effort. This requires experience.
4. Recognize when it’s just not capable of the task. Sometimes, you give it something too big and it can’t figure it out. One sign is that it will start going back and forth on something and just can’t get there. My rule of thumb is that if you go back and forth 3 times and are not getting anywhere, just start over.
5. Think of it as a collaborator rather than a “bot”. That will help you get over the fact that sometimes you need to rewrite what it does, but it’s still useful.

### Summarization and knowledge tasks

Another broad category of tasks is the summarization and synthesis of knowledge. Examples would include literature review or asking declarative facts (“What was the first paper that identified CRISPR?”). These tasks are a bit murkier for the following reasons: LLMs are not particularly good at declarative knowledge. I’ll give an example. Early on, I gave ChatGPT a URL to a bioRxiv paper and asked it to summarize it for me. It gave me a wonderful summary of a paper that seemed highly relevant to my research interests. Only thing is… that paper did not exist. Like, it straight up fabricated the whole thing. This “hallucination” problem is a known issue with LLMs, and while it has gotten better, it still makes these sort of tasks very dicey.

That said, there is a lot of power here. You are basically talking with the most knowledgeable single entity that humanity has ever created, which is pretty insane if you think about it.

Here is also where the context window makes a big difference. LLMs tend to hallucinate a lot less frequently if you give them the content you want to summarize or otherwise interact with directly into the context window. What this means is upload a substantial number of PDFs into the chat, and it will do a much better job of working with it. Of course, these context windows are limited, but you can still do a lot. There are other approaches, like retrival augmented generation (often referred to as RAG), that allow you to have much larger knowledge bases, but I haven’t played with those as much.

#### Document chatbot

One useful scenario is to build a chatbot that can take a ton of information (think of a user manual or a set of lab documents) and provide a conversational interface. For instance, I made a chatbot using NotebookLM (Google) into which I uploaded a bunch of our lab protocols and information. Now, instead of searching for, say, our shipping address, you can just ask the chatbot “What is the lab shipping address?” and it spits it right out.

The same could be used for uploading health and safety regulations or any number of other things. Again, you are only really limited by your imagination here.

#### Literature summarization and fact-finding

Keeping on top of the literature is a difficult task due to its sheer enormity. LLMs provide several ways of interacting with the literature. I have found that it does well with things like “Summarize what is known about XYZ” or “What are connections between fields A and B?”. As noted, it does a lot less well with “Find me the paper that shows factoid X”, in which case it will often either come up with the wrong reference or make something up for you.

That said, again, the context window can help you out. NotebookLM, for instance, will take up to 50 PDFs, which you can then chat with interactively. The difference is that because it is all in the context window, you will get answers that call out particular pieces of text from your PDFs, effectively providing citations. Very handy.

There are many other services out there that are trying to solve the hallucination problem. Examples include Perplexity, Elicit, Consensus, and probably a dozen others. I can’t say that I have a lot of experience with them, but I’ve heard some good and bad things about all of them. I have found that while they are more reliable than a straight chatbot, they will often miss the forest for the trees in the sense that they will find a bunch of papers that are seemingly relevant but not the key papers that drove the field. I’m sure they are well aware of these issues and are working hard to solve them, so stay tuned.

One fun thing I have found is that you can sometimes just paste in a list of genes and ask it what pathways are involved, and you will often get far more useful results than a standard pathway analysis. I think overall, the LLMs are a lot better at summarizing and synthesizing than pointing you toward specific declarative knowledge.

### Using AI for training

I think there is enormous potential for AI to help us train people in our labs. I suppose there is a view that this is in a sense, abdicating our responsibility as mentors. Rather, I think of AI as a supplement in this regard. First, it is available around the clock and is not moody or judgemental. Second, it will make sure you cover all the bases. Third, if AI can provide low-level feedback, it preserves a PI’s time for more advanced feedback. Nobody says PIs should spent time training their team to spot spelling errors—automated spellchecking does just fine. Over time, we will see the bar shift ever higher in this regard as the quality and depth of feedback that AI can provide steadily improves. (I will note that this trend does give me a bit of existential despair.)

For instance, one member of the group shared with us how they work with trainees on papers with ChatGPT. They sits with them and models the behavior, going through line by line and showing them how ChatGPT can help them out. I think it’s a really great way to help trainees learn to help themselves by using these tools.

You may be thinking, “Well, I have my style that I want to teach my trainees, not some generic ChatGPT fluff”. Again, here is where the context window can help. ChatGPT has the notion of custom GPTs and Claude calls these projects. These are basically chatbots that have custom instructions and examples that can guide it to give better feedback. For instance, I made a figure review bot. I gave it our checklists and guides and then a bunch of custom instructions telling it to generate a report about basic things like font sizes, alignments and so on. Then you just paste in a figure and it gives you a report, and will even give you instructions on how to fix it using Illustrator. I also recently made a similar bot to help people review their papers.

A common frustration is getting trainees to actually begin using these tools. I will say that (and this is my opinion) it is, at this point, borderline negligent for trainees not to use AI to help with coding. The productivity gains are enormous, both in terms of time spent and code quality. It’s like giving someone a calculator and them saying, “Nah, I’ll just do it by hand”. Similarly, there is no excuse to be handed a poor draft of text or a figure anymore. I think the above approach is a nice way to help trainees get on board.

Anyway, I think there’s actually a lot of untapped potential here for training, and I think we will be hearing more and more about these possibilities in the near future.

### Creative uses of AI

I think there are also just so many fun little one-off cases. Here’s a couple:

1. Formatting a bunch of emails into a table.
2. Turning the methods section of a paper into a protocol (and vice versa)
3. Looking at a protocol and pointing out areas that are unclear or ambiguous.
4. Use voice mode to take freeform dictation and summarize and turn it into organized text.
5. Summarizing meetings and providing action items (e.g. read.ai and Zoom’s built-in AI features).
6. Turning a full-length paper into a [chatty podcast](https://podcasters.spotify.com/pod/show/arjunrajlab/episodes/Can-cancer-cells-learn-e2ovak9) using NotebookLM (seriously it’s alarmingly good at this).

### Privacy and ethical use

A number of people in our meeting raised concerns about the privacy and ethical aspects of using AI. Privacy is a critical practical consideration in many cases. This is because when you use AI, whatever you put in the chat is uploaded to some private company, which may then incorporate it into their training data, meaning that it is in some way publicly accessible. _For instance, if you uploaded a grant you are reviewing (expressly forbidden, BTW) or writing (not forbidden), that grant could become part of the training data._ In theory, someone else could ask a question and get an answer that is related to the confidential materials in the grant. I don’t actually know how real this possibility is in practice, but it is a legitimate concern, especially since these are private companies with not much regulatory oversight. Many of these companies have some version of a “private chatting mode” where your data is supposedly not used for training, but… well, given that Google’s incognito mode was not quite so incognito, you can be forgiven for not taking these companies at their word. I certainly do not trust they honor such promises.

How much you care… well, that’s a personal matter. One person in the group said that they redact all names in letters of recommendation to maintain some degree of confidentiality for the trainee, and this is required for FERPA compliance, so we recommend doing this for all letter-writing tasks.

There are other strategies as well, including the use of fully local models (no uploading). The Llama models from Meta have been released as open source, so you can run them locally, sometimes even on a relatively modest laptop. While these models have tended to lag considerably behind the paid services in terms of power and sophistication, that gap may be closing. It is more technically challenging to use them, but they do provide a solution to the privacy issue, so they are worth following. Many institutions are also negotiating private versions of the large paid models, too, that are HIPAA compliant and so forth.

Another person raised the issue of the environmental impact of using LLMs. I don’t know exactly what the implications are, to be honest. I’ve seen numbers that are all over the place regarding the amount of energy consumed. Certainly, training the models is an extremely energy and resource-intensive activity, but that’s not something that is done very often. If this is a concern, I would recommend doing some more digging because I suspect many of the hot takes on the internet don’t hold much water. But I am certainly not an expert.

### What does AI mean for the future of academic science?

I don’t have a crystal ball, but I think there are a number of changes to academic science processes that the advent of AI stands to change in a rather profound way.

One is that it holds out the possibility of freeing us from much of the drudgery that we are increasingly mired in. The amount of paperwork in our lives has increased dramatically, and computerization has actually, in many ways, made this worse, requiring faculty to do things (like file Concur or sign up as a vendor in some arcane university procurement system just to get reimbursed for your flights) that previously were handled by admins. AI might very well free us from many of these tasks. I think in the very near future, many of these things will be at least partially automated.

Another huge change will be in our evaluative processes, like how we choose which people to hire, what grants to fund, and so on. Many of our systems use sheer document length as either a proxy for merit (as in “Wow this letter is long, they must really think highly of this candidate”) or as a rate-limiter (as in “It is not physically possible for me to write more grants this year so that’s all I can do”). AI nullifies both of these. For evaluations, I think it will be increasingly important to have actual, real things to say about people and their abilities. Moreover, I firmly believe that the granting system will crumble under the weight of an enormous number of submissions and require a complete rethink.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXe82nCDz2g3oqGx5wKgzsi-mTR-OIQiiHkKNgF-lpK1qIDXYW77HDX-S1EA-wegphe3YCjd9Eb7KrjE4CyD56RSi4M-HW50MR8jdS35t1x90i42YmpmdIWMktwpguE_9CQ-n1d8RXiR1f5-nQcbQF75V-w?key=ND-favj1OvPP69Cn7X_aRg" alt=""><figcaption></figcaption></figure>

The bar for quality will also increase. There’s almost no excuse for a poorly written paper anymore. Same with poorly written and documented code.

Overall, I think a lot of these changes are welcome. Currently, a lot of our evaluative systems have gotten so overwhelmed that they become exercises in box-ticking rather than actually deliberating on the quality of the ideas. I think the days of the 12-page grant, with its endless sections on “pitfalls” and “timelines”, are numbered. Given that these can largely be automatically generated, why are we bothering? I think short proposals that focus on the core idea and its feasibility will be the only path forward.

On the other hand, if you have used AI for a while, you may have a “What’s the point of me doing anything as these AIs get better and better at doing more and more of my job?” moment 😀. This thought passes through my mind probably at least once a day. Not sure what to do about that. May you be cursed to live in interesting times.
