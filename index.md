---
title: Building an e-Ink ToDo list
date: 2022-12-25
---

## eInk ToDo list!

First post!

TODO: include a picture of the result.

## Materials

#### Hardware bill of materials:
TODO: clean this up, make a table with prices

WaveShare 7.5 inch screen TODO: link
Battery
ESP32 driver board from WaveShare
Cable (lol...)
Frame (from Michaels)
Power Bank Keep-Alive
HomeAssistant base station (consider [ODroid](https://www.home-assistant.io/installation/odroid))

### Software

Home Assistant
ESPHome
CloudFlare
NameCheap
Todoist (API, Android App)

## Physical Setup

### Electronics

Connect the screen to the driver board (don't get any cables backwards, this wasted 4 hours of my life). Connect the driver board to the cable (even if the cable says it's a data cable, it might not be. This wasted 4 hours of my life.) Connect the cable to a keep-alive board (this delayed me 2 weeks waiting for a part...). Connect the keep-alive board to the power bank.

### Frame
I used a TODO: dimensions frame from Michaels. Unfortunately, my power bank was too thick, so I added some extra depth to it.

## Digital Setup

Home Assistant: steps to describe (link to starting documentation).
Set up ESPHome
Set up a CloudFlare tunnel
Set up device on ESPHome, download the binary.
Set up esphomeflasher, to flash basic setup on the waveshare board.

### Set up Todoist, retrieve your API Token

### Config for Home Assistant

### Config for ESPHome

### Add device to Home Assistant
