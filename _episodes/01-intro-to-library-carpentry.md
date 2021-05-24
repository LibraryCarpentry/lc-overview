---
title: "Introduction to Data and Programming in Libraries"
teaching: 20
exercises: 10
questions:
- What is Library Carpentry and how does it fit in the broader Carpentries organization?
- How can you apply the skills and tools you learn in Library Carpentry in your work? 
objectives:
- Learn about the different places data are collected in libraries.
- Establish why it is important to think about the data and how it is collected and stored.
- Understand how the different tools we will learn about can be used together to make your work easier.
- See examples of how these skills and tools are used in libraries.

---

## Scenario: Your library needs to think about space!

Space planning is a common project that faces libraries big, small, and in between. In order to make the most of the time and money that needs to be invested to make a space design project a success you will need to bring together departments from all over your library to supply expertise and data. You will need details about many things like your collections, how the spaces are used now, how your community wants to use your spaces and services, and how you might make adjustments in your stacks to accomodate your plans. We will talk about tools and strategies you can use to make your work easier, no matter what you do in the library, and how you can make the data you collect and create easier to use by others at your library now or in the future.

## Library Carpentry and The Carpentries

[Library Carpentry](https://librarycarpentry.org/) is one of three Lesson Programs that make up [The Carpentries](https://carpentries.org/). Where Software Carpentry and Data Carpentry are aimed at researchers in a variety of fields, Library Carpentry was developed specifically with the needs of library and information-related communities in mind. "Our goal is to empower people in these roles to use software and data in their own work and to become advocates for and train others in efficient, effective and reproducible data and software practices." [(Library Carpentry About Us)](https://librarycarpentry.org/about/)

The lessons that make up the Library Carpentry curriculum are always evolving, with new lessons being developed as needs arise. The Core Curriculum includes Introduction to Data (this lesson), Unix Shell, Git, and OpenRefine, but the lessons are also taught individually or in combination with other lessons from from [the expanded curriculum](https://librarycarpentry.org/lessons/). 

Library Carpentry workshops follow [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html). Please be respectful of everyone in the workshop; we are all here to learn and support each other as we expand our knowledge.


## Where are data and software skills useful in library work?

Whatever kind of library work you do, you have probably come across situations where you are either looking at tables of data, using data  to make decisions, talking to someone about systems related to data, or creating data in one way or another. Whichever flavor of lessons you are covering in your Library Carpentry workshops, you will take away knowledge and skills that will help you:
- evaluate data that you are using and collecting for possible sources of error
- consider ways to automate processes to make your work easier
- talk to vendors about the data structures built-in to their software
- work with faculty members and campus IT on ways to manage research data
- identify data that needs to be better secured to maintain patron privacy
- document your work so that you and your colleagues know how and why your data were created and organized

The point of the Library Carpentry sessions is to help you become data and software savvy; you will have an idea of what different tools can do to help you with your work and know where to go to find out more.

## Data collected in libraries

There are many sources of data in libraries. Some examples are:
- bibliographic information about physical collections
- circulation statistics
- metadata from items in institutional repositories
- contact information for patrons
- reference and instruction statistics
- responses to surveys or other forms of feedback 
- journal and ebook turn-aways
- gate counts

These are just a few examples of the kinds of data that you might have in your library. These data are often stored in different locations and systems, like your library management software, shared network or cloud drives, reference statistics software, or even as paper records. It will likely take a lot of communication and collaboration between individuals and departments to think about how you can bring these data sources together to better understand your library's collections, services, spaces, and community.

> ### Sources of data
> What kinds of data do you come across in your library work? Where are those data stored?
>
{: .challenge}

## The why, how, and where of library data

Just like the communities we support in our library work, we have to think about why and how we are collecting data and where we store it. 

### Why?

We collect data in libraries for a number of different reasons. We might need to report statistics to a bigger organization (like the [Association of College & Research Libraries](http://www.ala.org/acrl/publications/trends)) or our institution's fact book. We also want to understand our collections and how they have changed over time or where we have opportunities to add, shift, or remove items. Sometimes it is for our own research projects to investigate some aspect of our work that we want to understand better.

Whatever the reason for collecting data, it is important to record **why** we collect those data. Data are never neutral and one of the first places that bias is introduced into a dataset is when you are creating it. This is a step that a lot of people skip because when you are collecting and using data *you* know what you are doing with the data and it seems unneccesary and time-consuming to write down why. Documenting the reason for collecting data, whether it is a subset of a larger database or data you are collecting from scratch, will help you and your colleagues use the data in the future. The documentation can be a text file stored with the datasets or a section in a larger data dictionary or codebook, which we will discuss a little later in the lesson.


### How?

Libraries have been collecting data for centuries in the form of catalog records, but we also collect data through other methods. Some of those methods are automatically built into our systems, like circulation data, and others require new datasets and data collection instruments to be created, like a survey of community members. The method you use to collect your data will influence how it can be used and what kinds of conclusions you can draw from it. Keeping track of how you collected the data will help you repeat the process in the future so that you can compare results over time.   

> ## Documenting your data
> Whether you create a text README file, a data dictionary, a codebook, or a project notebook, it is important
> to document your data. This includes things like:
> - where your came from
> - why you collected it
> - the time period that the data refer to
> - who collected and analyzed them
> - the software you used
> - information about what is in the columns and rows in your dataset
> 
> You can learn more about README files, data dictionaries, and codebooks, including examples, at the [University of Iowa Guide to Readme, Data Dictionaries, Codebooks](https://www.lib.uiowa.edu/data/manage/documenting/readme/).
{: .callout}

### Where?

Where your data are stored is something that you might take for granted, but it is important to think through your storage options based on your sharing, backup, and security needs. While it can be convenient to use the default places your computer wants to save files, this can make it difficult to find them later and, if they are on your laptop or desktop hard drive, can cause hassles if your computer crashes and hasn't been backed up. It also makes it impossible for your colleagues to use the data unless you send it to them, which can mean that there are versions of your files out there that are not the most recent copy. Sharing files on a shared drive or cloud storage platform (like Box, DropBox or Google Drive) can help more people have access and provide a place to back up your files. 

No matter where you are storing your data you should consider any security concerns, particularly when dealing with any data that might lead to the identification of your community members. If it is essential that you collect and store this information, check in with your local IT group to learn about which systems at your institution are safe for storing sensitive information.

> ## Data about human subjects
> 
> Any time we collect and use data about other humans we have to think carefully about why, how, and where we are storing it.
> Like so many systems that we use every day, our library and learning management systems are collecting increasing amounts of data about the people who use them, and we
> need to respect their privacy. If you plan to use any data about your communities in presentations or publications it is a good idea to go through the process 
> of filling out a request with your local Institutional Review Board (IRB) and going through the ethics training program. It is a great way to learn more about human
> subjects research. 
> 
> If you want to learn more about privacy in libraries from the student perspective, check out the [Data Doubles Project](https://datadoubles.org/).
> 
{: .callout}

## Using data tools together

It is unlikely that any of the software that we use to work with data will have all of tools we need to complete our project from beginning to end. Thinking through the workflow that you will use to complete all of the steps in your project before you start will help you choose the file types, naming conventions, and software to complete your tasks. Let's take a look at a few examples of what this might look like in our hypothetical library space planning project.

1. 








