# Project - GOGOPAINTING
Use Golang with Gopherjs to make a web multiplayer draw and guess chatroom.

## Language Used
1. Golang (by GopherJS to JS)
2. JS

## FlowChart
![image](https://imgur.com/a/n2TL17S)

## How to Mousemove, Mouseclick
#### -By Golang
Use the Ebiten engine to make the Mousemove and Mouseclick effect.

## How to put Mouse effect on web
#### -By GopherJS
Unfortunately, if only do with Ebiten, we can not make the Mouse effect on the web. It can only be an .exe file. So we use GopherJs to make the Golang become JS code, and put it on the open source "Beego Chatroom". Then we can see the mouse effect on the web.

## About the chatroom
#### -BY Beego
When we have already implement Mouse effect on the web chatroom. We add some code on the Beego open source code. With these codes, we can achieve the Guess capability.

## How to send plots
#### -By JS socket
Use socket to send the points which is drawed to the JS server when the plot was drew, then the server will send the whole plots were drew to all of the clients. As this way, the whole players would see the plots which were drew by the drawer immediately.
