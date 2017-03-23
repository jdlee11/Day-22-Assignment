# Day 21/22 Assignment - Messaging App

#### Purpose
- a simple messaging app that allows anyone to enter a username and post messages to a global chatroom. Messages posted by the logged in user show up differently from those posted by any one else

#### Contents
- Log in (does not require password or verification, just saves the username to a session)
- POST/DELETE functionality for user's own messages
- periodic update to load/remove messages quickly
- relies solely on jQuery and fetching from heroku server. Outfitting with React would allow for state change updates rather than periodic fetching
