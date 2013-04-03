writedown
=========

Attempting a blogging system that suits my particular tastes

## Goals
* Web-based posting
  * insert images/files inline
  * upload images/files
* Posts composed as markdown
* Posts saved as markdown
* All content is flat files in a sensible archive structure
* All pages are static html files

## Stretch Goals
* Insert social media inline with posts (twitter, facebook)
* Light RESTful resource api
* REST resource responses also generated (for speed)

## Technical goals
* Independent sub systems
  * Composition app
  * Content server
  * Content api service
  * Persistence manager
* Subsystems have programmatic interface

## Technical stretch goals
* Optional integration with a git repo
* Subsystem dependencies are injected
* Static content can be generated and served from memory
