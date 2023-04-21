
# Useful Keyboard Maestro macros

These are some of my most used Keyboard Maestro shortcuts, which address my most often repeated (or sufficiently annoying) tasks. Keyboard Maestro is a powerful automation tool available exclusively on MacOS that enables users to automate repetitive tasks and streamline their workflow. With a vast library of available actions, Keyboard Maestro allows you to create custom shortcuts that can execute complex tasks with just a few keystrokes or be triggered by various events (such as widow of a specific app coming into focus). 

I am only touching the surface of what Keyboard Maestro is capable of, there are many other actions and features it offers that I have yet to explore. There are many other third party apps on Mac which accomplish some of the following tasks, but few (if any) can do them all. 

If you have your own favourites, please do share them with me. I am always happy to pick up new tricks. 

## Window manipulation

Possibly the greatest use-case for KM allowing me to quickly arrange windows on my screen (also using the [Alt-Tab](https://alt-tab-macos.netlify.app) app which fixes how windows are handled on MacOS). 
This includes
- moving active window to any of a myriad of location on the screen.
- hiding every window to clean up

![Window manipulation](https://user-images.githubusercontent.com/77053094/233570778-50ba46b4-4904-468f-a13f-dd6d5dd3293a.gif)

## Window set-ups

"Briefing" is my most used macro. It creates a consistent briefing screen from where I start my every day. It includes my Obsidian with particular notes I want to see when planning my day, calendar to see what is going on and all my scheduled tasks for today and beyond. 

As my responsibilities change, I am adjusting the set-up with Slack, Notion and email. It (as many macros here) is a continuous process of finding what is needed, what is distracting and what no longer necessary. What stays though is consistency and easy of access to any information I need. 

![Briefing_screenshot_edited_low_res](https://user-images.githubusercontent.com/77053094/233572053-147cb053-e46c-4d33-b155-b61aff442869.jpg)


## Quick app switcher

The [[80-20 rule]] comes with app use as well. Finding apps by names in Spotlight work pretty well, but with things one uses dozens times a day it is worth finding the fastest way possible. Here comes KM where I set up a keyboard shortcut which invokes my most used apps. 
- Ctrl+S for Safari
- Ctrl+V for VS code
- Ctrl+O for Obsidian
...


## Text Expander 

I use Obsidian and thus Markdown a lot during my day and like to style my documents a certain way. If it is the format for question for Anki, code blocks or latex equations, I want to have a quick way to insert the Markdown fluff and get to the content. These come and go as necessary but many stick around for a long time. 

My favourite macro takes a photo from my clipboard, asks me how to name it, saves it to a specific folder in Obsidian and pastes a markdown formatted link to the newly created file to show up as an image in Obsidian. 

![Text Expander](https://user-images.githubusercontent.com/77053094/233570992-7367f69a-b371-4177-8281-704465a42366.gif)

## Multiple clipboard and appending

Another great feature of Keyboard Maestro is the ability to have multiple clipboards and append text to them. This saves me a lot of time when I need to copy and paste multiple things in a specific order or when I need to keep track of information from different sources. 

Once I needed to read a lot of webpages and take notes on them. Copy pasting one highlight after another was tedious so I made a KM script which takes new text and appends it to my clipboard with some extra Markdown formatting thrown in as a bonus.

## Apple Shortcuts and Text Sniper

The recently added Apple Shortcuts are pretty good, but they can be taken to another level when combined with KM. They can be run via terminal (as any script you would like KM to run, including shared variables) and combined with whatever you need in KM. 

Text Sniper takes an image from my clipboard, runs it through Shortcuts which detects and reads any text that the image contained and saved is as plain text in my clipboard instead. Copy paste even where they don't allow you to. 

![Text Sniper](https://user-images.githubusercontent.com/77053094/233571118-6e02a493-6e93-4939-b211-9e86a00d3671.gif)

## True automation

Some apps are just annoying. Timery (a companion app for Toggl) craves attention and comes into foreground every time you start a new timer from the Mac widget. Instead of pressing Command+H every time, I set up a KM shortcut which hides Timery every time it comes into foreground (and another macro which turn the previous one off when I need to actually use Timery). 

## But how do you remember all these shortcuts?
I don't. 

KM has a function similar to Spotlight from which you can trigger any of your macros just by typing its name. Sounds inefficient, but after trying to (again and again) remember the weird combination of keys for this macro you use once a week you will know. 
