# Twitter-SparkStreaming-SentimentAnalysis

Real time twitter sentiment analysis application built using Twitter | Spark Streaming | Redis | Java Swing

</br>

## Introduction

Sentiment Analysis is the process of determining whether a piece of writing is positive, negative or neutral. It's also known as opinion mining, deriving the opinion or attitude of a speaker. knowing this, companies and brands can leverage the information to alter their communication strategy or to recognize events that may need to be addressed before it becomes a full-blown crisis. On the other hand, companies can, in various ways, capitalize on things that seem to be creating more positive buzz within their target audience.

Sentiment Analysis answers to questions like below:

  How do your customers feel about your brand?

  What is the opinion about your brand against your competitors?

  What are the latest trends related to your brand?


Need more information about sentiment click below URL

https://www.lexalytics.com/technology/sentiment

</br>

## Goal

• The goal is to show users sentiment analysis results based on given trending topics while running the application. 

• The project was developed using Twitter 4j, Spark Streaming(Scala), Redis, Java Swing

</br>

## Architecture

![alt text](https://github.com/RepakaRamateja/Twitter-SparkStreaming-SentimentAnalysis/blob/master/images/arch.png)

Application streams data from twitter using Spark Streaming and then sends them t

another layer with spark lib which does classification

which is an machine learning module

Application collects tweets from trending topics, creates a pipeline for sentiment and emotion analysis and finally displays results of the sentiment analysis in a dashboard.

</br>

## Technology stack

![alt text](https://github.com/RepakaRamateja/Twitter-SparkStreaming-SentimentAnalysis/blob/master/images/stack.png)


</br>    


<table>
<thead>
<tr>
<th>Area</th>
<th>Technology</th>
</tr>
</thead>
<tbody>
    <tr>
        <td>Front-End</td>
        <td> Java swing </td>
    </tr>
    <tr>
        <td>Cluster Computing Framework</td>
        <td>Apache Spark Streaming using Scala (extension of the core Spark API) </td>
    </tr>
    <tr>
        <td>Machine learning </td>
        <td>MLlib library (Apache Spark's scalable machine learning library)</td>
    </tr>
    <tr>
        <td>In-Memory Caching / Datastore</td>
        <td>Redis</td>
    </tr>
    <tr>
        <td>Other APIs Used</td>
        <td>Twitter streaming using Twitter 4j api</td>
    </tr>
</tbody>
</table>

</br>   

## Use Cases

Sentiment Analysis can be applied to variety of Use cases:

1) Predict the success of a political/social campaign

2) Decide whether to invest in a certain company

3) Targeted advertizing

4) Product and service review

5) Research in sociology and psychology

6) Discover how people feel about a particular topic


