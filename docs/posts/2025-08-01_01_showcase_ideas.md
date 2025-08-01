---
draft: false
date:
  created: 2025-08-01
categories: 
  - Oracle
  - Apex
tags: 
  - Technology
  - Oracle
  - Apex
authors:
  - graham
---

# Showcase Ideas - My First Blog Post

I've got a great idea but I'm only supposed to blow the bloody doors off!

<!-- more -->
That's a reference to a scene in the [Italian Job](https://www.imdb.com/title/tt0064505){:target="_blank"} and I'm referring to it as a reminder to self to not get carried away.

## My Attestation

I need to create a showcase of Oracle, Apex and PL/SQL work: initially to demonstrate my skills to potential employers and then afterwards as a playground for trying and testing new things - plenty of exiting stuff in the latest version of Oracle!

My first idea is to create an Apex website starting from a set of data that I obtained from [Kaggle](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025){:target="_blank"}.

It's a list of many electric vehicles that you can buy in 2025.

I figured that I could firstly get this data into Oracle as a single table and then wrangle it from there to separate the makes from models (to normalise the data a bit) and create a table for LOVs which will be used on a form (or forms) to create/maintain vehicles in the application.

The data lends itself well to a faceted search report, which will be fun to set up.

After that, I want to add in the ability for (make-believe) 'customers' to register interest in a vehicle and then to order customisations to it if they wish to (thinking that a shuttle would be good for selecting the features to add/remove).

I'm going to be making the actual custom options **rather ridiculous**, like:

*  Paint job: vehicle painted in red with decals of flames on the sides.
*  Additions: Put a Lotso stuffed bear (from Toys 3 movie) on the grill. 
*  Wheels: Change the wheels to a set of CMST Forged Alloys Ct208.

Then, as a "side effect", I'll get the shuttle to build up a prompt that can be pasted into an AI LLM to generate an image of the car with the customisations.
I've experimented using Chat GPT already and have gone from this:

![Boring Car](../images/car_before_image.png)

to this:

![Eye-catching Car](../images/car_after_image.png)

:smile::smile::smile:

I also want to add the functionality where the "customer" can have an email sent to them confirming their "order".
I've never tried the PDF generation facilities within Apex. So I'm going to do that to create a good-looking professional document as an attachment.

I didn't mention that I'll be using [ORDS](https://www.oracle.com/uk/database/technologies/appdev/rest.html){:target="_blank"} as well.