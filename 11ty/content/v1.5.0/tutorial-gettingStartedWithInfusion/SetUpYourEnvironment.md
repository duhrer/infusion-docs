---
title: Set up your environment
layout: default
---

# Set up your environment #

---
Part of the [Getting Started with Infusion Tutorial](GettingStartedWithInfusion.md)

---

## Background ##

If you haven't already, it might be helpful to read our [Developer Introduction to the Infusion Framework](../to-do/DeveloperIntroductionToInfusionFramework.md) before starting this tutorial.

## Set Up Directory Structure ##

For this tutorial we'll assume this component is being created for your own use, not as a contribution to Infusion. If you do want to contribute your component to Infusion, the directory set-up and requirements will be a little different and is explained in [Contributing Code](http://wiki.fluidproject.org/display/fluid/Contributing+Code).

Let's suppose you're creating a component that will display a bar graph of some data. First, set up your file folders in the following structure.

Create:

* Two directories called "bargraph" and "shared"
* A directory called "sample-data" within bargraph
* Two directories within shared called "css" and "js"
* A directory within css called "fss"
* A directory within js called "infusion"

Your directories should now appear like the following:

* bargraph
    * sample-data
* shared
    * css
        * fss
    * js
        * infusion

Add Infusion

A lot of the functionality of our component will be driven by Infusion code, so we'll need to add these dependencies to our component.

* Download the [latest release of Fluid Infusion](http://fluidproject.org/products/infusion/download-infusion/) and unzip it.
* Copy the contents of the src/framework/fss/ into our shared/css/fss directory.
* Copy the infusion-all.js file into js/infusion
