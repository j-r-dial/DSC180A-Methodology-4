# Julia Dial

**Email:** [jrdial@ucsd.edu](mailto:jrdial@ucsd.edu)

**Section:** D23

**Mentor:** Lily Weng

**What is the most interesting topic covered in your domain this quarter?**
The most interesting topic I have covered in my domain so far is the different failure types in a Retrieval-Augmented Generation (RAG) system. I had never learned about 
the different sources of RAG errors prior to this quarter, so it has been interesting learning about, for instance, the distinction between failures due to insufficient evidence
retrieved versus failures caused by an LLM generating a response contradictory to the evidence provided.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
A potential investigation that I would like to pursue for my Quarter 2 Project is exploring how diagnosing RAG failure types and adaptively correcting based on the category of failure
can impact the performance of the RAG system. Specifically, I want to investigate when a RAG system should apply correction under three evidence conditions, low distraction, 
high distraction, and missing support, where a policy chooses whether to keep, regenerate, or retrieve and regenerate the answer with and without first diagnosing failure type. For this
investigation, I would compare a baseline to this adaptive correction RAG system across the metrics of repair rate, overcorrection rate, cost, and F1 on HotpotQA questions.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
A potential chance I'd make in my approach of the Quarter 1 Project is focusing more on a few related papers and experiments, rather than trying to find many papers related to my project.
I think this change to my approach would have made my research of RAG and LLM faithfulness more focused, which I think would've helped me solidify what I wanted to accomplish earlier and 
allowed me to go more in depth, opposed to breadth, of my topic area.

**What other techniques would you be interested in using in your project?**
A other technique that I would be interested in using in my project is Reinforcement Learning as one of the corrective strategies when a RAG retrieves distracting evidence, so that the model 
learns reason in quoted evidence. Another technique I could use is LLM activation steering, as this could be used to diagnose if evidence is used correctly, then apply correction during
regeneration.
