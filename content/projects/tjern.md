+++
title = 'Tjern'
date = '03 May 2024'
+++
In the past, I often found myself with feelings that I wanted to quickly express, but couldn't, being next to a computer with my journal and pen out of reach. Privacy has also appealed to me, the idea of nobody else being able to read my content. Combining these two motivations, I created Tjern (terminal journal), a lightweight command line journaling app that encrypts all your entries on your machine before saving them to the cloud, never lost.

The client facing app is built with the delightful [Bubble Tea](https://github.com/charmbracelet/bubbletea) framework. 

The server is built using [Cloudflare Workers](https://developers.cloudflare.com/workers/).

The data is stored with [Turso](https://turso.tech/).

[Check it out!](https://github.com/sdrshnv/tjern)