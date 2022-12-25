---
title: Building an e-Ink ToDo list
date: 2022-12-25
---

## Building an e-Ink ToDo list

First post!

<img src="images/calm-todo/final_frame.jpg" width="40%" height="40%" />

## Materials

#### Hardware bill of materials:
<img src="images/calm-todo/guts.jpg" width="40%" height="40%" />

<table>
  <tr><td>Name</td><td>Price</td><td></tr>
  <tr><td><a href="https://www.waveshare.com/7.5inch-e-paper-g.htm">WaveShare 7.5 inch screen</a></td><td>$69.99</td></tr>
  <tr><td><a href="https://www.waveshare.com/product/e-paper-esp32-driver-board.htm">WaveShare ESP32 Driver Board</a></td><td>$14.99</td></tr>
  <tr><td><a href="https://www.waveshare.com/product/e-paper-driver-hat.htm">WaveShare Driver HAT</a></td><td>$9.99</td></tr>
  <tr><td><a href="https://www.adafruit.com/product/1566">AdaFruit USB Battery Pack - 10000mAh</a></td><td>$39.95</td></tr>
  <tr><td><a href="https://www.tindie.com/products/plop211/power-bank-keep-alive-based-on-555-timer-smd/">Tindie Power Bank Keep Alive</a></td><td>$13.50</td></tr>
  <tr><td>HomeAssistant base station (consider <a href="https://www.home-assistant.io/installation/odroid">ODroid</a>)</td><td /></tr>
  <tr><td>A frame that can display 163.2 × 97.92mm</td><td /></tr>
</table>

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
