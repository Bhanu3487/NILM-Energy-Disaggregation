# NILM-Energy-Dissaggregation-
---

## Project Overview

In this project, we have studied the Non-Intrusive Load Monitoring (NILM) problem and its solutions proposed in the paper [NILMTK](NILMTK.pdf) and [NILM contrib](NILMTK Contrib.pdf) in detail and are contributing to the NILMTK contrib by converting the codes from keras to pytorh and integrating the methods with attention mechanisms. We are also experimenting to deal the NILM problem with prompt engineering by using techniques like zero-shots and few shots by finetuning local LLMs.

### Dataset and Model
We have chosen Reference Energy Disaggregation Data Set (redd) as for training LLMs in prompt engineering. We have used multiple models including Llama 3(8b), Llama 3(70b), LLama3 (8b Instruct). We have used open source inference model like Groq, Ollama for running LLMs locally and finally finetuning the model on our dataset. We have compared the results of energy disaggregation by using LLMs and also parallely with the models ingerated with attention mechanism.
