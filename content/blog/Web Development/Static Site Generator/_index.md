+++
title = 'Static Site Generator'
date = 2023-10-25T09:58:21-04:00
draft = true
+++
Cloudflare Pages can be configured to use a number of static sight generators (SSG) and some frameworks to create content served by Pages. Most of the SSGs use javascript node packages to process the sight. I've notice that there can be problems with incompatible packages or variance in OS file layout with some of these products. That may simply be the result of my inexperience, but the generation time compared to Hugo (a golang application) is significantly longer. A knock on Hugo seems to be that it uses the GoLang, I assume this is a negative because most ewb developers are use to using javascript. I prefer to deal with GoLang for a number of reasons beyond the SSG.