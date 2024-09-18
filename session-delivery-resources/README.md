## How To Use 

Welcome,

We're glad you are here and look forward to your delivery of this amazing content. As an experienced presenter, we know you know HOW to present so this guide will focus on WHAT you need to present. It will provide you a full run-through of the presentation created by the presentation design team. 

Along with the video of the presentation, this document will link to all the assets you need to successfully present including PowerPoint slides, demo instructions & code.

1.  Read document in its entirety.
2.  Watch the video presentation
3.  Ask questions of the Lead Presenter

## File Summary

| Resources          | Links                            | Description |
|-------------------|----------------------------------|-------------------|
| PowerPoint        | [Presentation - slides](https://aka.ms/AArxx4v) | Slides |
| PPT Recording     | [Presentation - video](https://aka.ms/AAs4l8x) | Video Recording of the PowerPoint slides with audio |
| Videos            | [Full Workshop Presentation - video](https://aka.ms/AAs50ni) | Example Presetation of this Session |
| Demos             | [Contoso Creative Writer - code](https://github.com/Azure-Samples/contoso-creative-writer) | The Source Code | 
| Demo Recordings           | [Contoso Creative Writer - app demo - video](https://aka.ms/AAs4t0n) | Recording of the Demo Live 1 | 
| Demo Recordings           | [Contoso Creative Writer - Skillable lab manual walk through - video](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/ERnYuMS_ZAxMslEipbzS5AwB4mPVRREWiAzG51kkf2cVEg?e=aGLtmq) | Recording of the Demo Live 2 | 


## Get Started

This training repository is divided in to the following sections:

| [Slides](#slides) | [Demos](#demos) | [Deployment](#deployment-Preparation) | 
|-------------------|---------------------------|--------------------------------------
| 12 slides - 8 minutes| 2 demos - 10 minutes | Self paced walk through - 50 minutes

## Slides

The [Presentation slides](https://aka.ms/AArxx4v) has incomplete presenter notes. Please use the [Presenter Script](SCRIPT.md) as a guide on what to say for each slide instead. 

You can also watch a video walk through of the PPT slides with the script being read [here](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/EeRakQoGGvJEiplsCiH39DsBdLhomjkXkxBPQzct9WhozA?e=0lYV7w). 

### Presenting the slides: 

- As attendees enter the room have `slide 2` up on the screen. (Preferably add Wi-Fi information to this slide.)
  
- Once everyone is seated jump to `slide 5`, which is the 'Meet the Instructor and Proctors" slide. For the sake of time this is the slide you must begin with. Please **edit this slide** with relevant information including:
  
    * Lead instructor name and picture
    * Proctor names and pictures 
    * Wi-Fi information
    * Link to Skillable which is [https://aka.ms/skillable-wrk551](https://labondemand.com/LabProfile/171046)
      
- Let the attendees connect to the Wi-Fi and instruct them to navigate to the skillable link and press the `Launch` button. Launching the lab may take some time so start the presentation once the majority of participants have cliked the launch button. 
  
- Slide 10 is the slide that says "DEMO". Once you get to this slide share your screen and:
  
    1. Play the [Contoso Creative Writer App demo video](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/Ecryff-J5pdIvkPEmDjCVRABvORXWvO6dX7yHPisSCVS0w?e=CeskSB ). You could also deploy the application on your own screen and show that instead. 
    2. Switch to the Skillable Lab Manual page and complete each step of the instructions with the attendees. They should be carrying out the steps on their own machines at the same time. You can watch a video walk through of this process here:  [Contoso Creative Writer - Skillable lab manual walk through - video](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/ERnYuMS_ZAxMslEipbzS5AwB4mPVRREWiAzG51kkf2cVEg?e=aGLtmq).
       
- Once the lab instructions are completed by the majority of participants come back to the slides and begin on `slide 11`, "How does the assistant work." You should **stop presenting the slides** and let attendees work on their own once you reach `slide 16` and have discussed the workshop goals. (**Slide 17 is outdated so please do not show this slide**.) 

Overall this section of the workshop, including showing the app demo and completing the lab instructions, should not take a **maximum of 20mins**. The [presenter script](SCRIPT.md) includes time estimates for each section! (Do not use the time estimate from the agenda section in the powerpoint.)

### Timing

| Time        | Description 
--------------|-------------
0:00 - 2:00   | Meet the instructors 
2:00 - 8:00  | What are we building?
8:00 - 18:00 | DEMO and Lab Manual walk through (participant initial set up)
18:00 - 22:00 | How does the assitant work?
22:00 - 24:00 | Workshop Goals 
24:00 - 75:00 | Self paced walk through(50 mins)

## Deployment / Preparation

There are two parts of this lab the participants will need to complete for succesful deployment: 

1. Pre-requisites, getting Azure Credentials, and launching Github Codepsaces using the instructions in the Skillable Lab Manual

    * This part of the workshop should be completed during the `DEMO and Lab Manual walk through` section of the workshop, after you show a quick demo of what the final deployed app should look like. You can read the [Skillable Lab Manual](LAB_MANUAL.md) for this workshop in this repository but on the day you should open it in the Skillable environment. 

    * The instructor should share their screen and walk through the Skillable Lab Manual Instructions in the Skillable environment and instruct the participants to follow along doing the same on their own machines. 

    * Once the majority of participants have launched their Github Codespace environment you should discuss the `How does the assitant work?` and `Workshop Goals` sections from the slides while the Codespaces loads. 

    * We will not be using the Skillable VM for the workshop but participants will need to get their Azure credentials from the Skillable `Resources` tab. 

    * Skillable will have already provisioned the workshop resources, however participants will be instructed in the lab manual to download an env file with their environment variables in it. (Read the Skillable Lab Manual for Pre-requisites and details.)

2.   Following the self paced instructions in the [contoso-chat-writer](https://github.com/Azure-Samples/contoso-creative-writer) repository.

        * Instructions for this part of the workshop will be in the `./docs/workshop` folder of the repository.
          
        * Participants should complete this section without need for guidance from the instructors, however please help if a participant is stuck.  


## Demos

Detailed explanations of each demonstration associated with this presentation can be found in this section. There is:
    * one pre-recorded video of the completed app 
    * one pre-recorded app walking through the lab manual instructions (you should walk through the lab instructions yourself with participants but the video is to guide you and in case of technical difficulties). 
You will actively present these two demos in the workshop during the `DEMO and Lab Manual walk through` section. 

We have also included a complete walkthrough of the entire workshop for your convinience. 
Before the workshop it is important for you to login to skillable and ensure that you are able to follow the instructions in the manual. If not please reach out to the content creators for help.

| Demo 	                                                                                               | Minutes | Video |
-------------------------------------------------------------------------------------------------------|---------|----------------- | 
|  [1 - PPT Presentation Recording](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/EeRakQoGGvJEiplsCiH39DsBdLhomjkXkxBPQzct9WhozA?e=0lYV7w) | 9mins       | [Link](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/EeRakQoGGvJEiplsCiH39DsBdLhomjkXkxBPQzct9WhozA?e=0lYV7w) |
|  [2 - Contoso Creative Writer - Application DEMO](https://github.com/Azure-Samples/contoso-creative-writer) | 2       | [Link](https://github.com/Azure-Samples/contoso-creative-writer) |
|  [3 - Contoso Creative Writer - Skillable Lab Manual Walk Through](LAB_MANUAL.md) | 8       | [Link](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/ERnYuMS_ZAxMslEipbzS5AwB4mPVRREWiAzG51kkf2cVEg?e=aGLtmq) |
|  [3 - Contoso Creative Writer - Full Workshop Presentation](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/EUJWupuJWoJFjdghJmYbqvYBRJ767qT_BavoM3ks2L4RqQ?e=KHoDfP) | 20       | [Link](https://microsoft.sharepoint.com/:v:/t/AI-Tour-FY25/EUJWupuJWoJFjdghJmYbqvYBRJ767qT_BavoM3ks2L4RqQ?e=KHoDfP) |

 
