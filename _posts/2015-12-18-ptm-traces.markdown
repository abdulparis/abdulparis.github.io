---
title: My First post - Coresight
layout: post
---
In this post, I just wanted to talk about who I am and what I am doing currently.

My name is **Muhammad Abdul WAHAB** and I am currently doing a *PhD* at **_CentraleSupélec (Rennes)_** financed by**_CominLabs and Brittany region_**. I am not going to talk about my PhD subject in today's post. I am planning to do a complete post on my PhD subject. 

The subject of today's blog concerns coresight components. What are these components? Why do we need them ? What are the problems that can occur using these components ? What are the limits of these components ?

In order to debug the software, we usually uses software but we can also use hardware. For example, [ARM](http://www.arm.com/index.php)) offers the possibility to use the Coresight components (CS) in order to debug the processor(s). Other manufacturers of processors offers hardware solution for debug. For example, Intel offers 

Coresight components [ARM Coresight Components](http://infocenter.arm.com/help/index.jsp?topic=/com.arm.doc.ddi0314h/index.html) offers a multi-core debug and trace solution with high bandwidth for systems. 

They are further divided into three types : Sources, Links and Sinks.

Types of Coresight components | Examples | Function 
--- | --- | --- 
Sources | PTM (Program Trace Macrocell), ETM (Embedded Trace Macrocell), ITM (Instrumentation Trace Macrocell) | collect trace from the CPU 
Links | FUNNEL, REPLICATOR | provides a link between the CS sources and CS sinks 
Sinks | ETB (Embedded Trace Buffer), TPIU (Trace Port Interface Unit) | store or export the trace data 

The following list is not exhaustive. 
