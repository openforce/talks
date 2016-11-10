## What is it?

An [activator tutorial][1] designed to show how to leverage the Lightbend Stack and build a machine learning application with a real world example.

[1]: https://www.lightbend.com/activator/template/spark-mllib-scala-play

>>>

## A two-part project

 1. An [activator tutorial][1]
 2. Twitter Sentiment Analysis

[1]: https://www.lightbend.com/activator/template/spark-mllib-scala-play

---

## Activator

[Activator][1] is the Lightbend Reactive Platform's build and tutorial tool  

Comes with a web UI to explore, build, run and test projects

[1]: https://www.lightbend.com/activator/download

Note:
Activator uses sbt (simple build tool included with scala) to build
Activator tutorial: Template that contains a detailed documentation about what's going on

>>>

## Activator tutorial

A template that contains a detailed explanation about how the project works

Note:
Template that contains a detailed documentation about what's going on

---

## Twitter Sentiment Analysis

Web application that let's you search for tweets and automatically classifies these messages as either positive or negative with respect to the query term you've entered.

Note:
Sentiment analysis aims to determine the attitude of a speaker or a writer with respect to some topic.

>>>

## Functionality

 1. Fetch twitter messages based on a given keyword
 2. Preprocess each tweet <!-- .element: class="fragment" -->
 3. Apply an algorithm to determine the sentiment <!-- .element: class="fragment" -->
   - Classic supervised learning (batch trainer)
   - Distant supervision (online trainer)

>>>

## Compare two different approaches

Batch Trainer (classic supervised learning)  
Online Trainer (distant supervision)

Note:
Classic supervised learning

>>>

## What does it look like?

![Snapshot of the application](/images/twitter-sentiment-analysis.png)
