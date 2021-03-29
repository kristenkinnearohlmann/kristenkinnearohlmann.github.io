---
layout: post
title:      "Take Note Of: Using the `params` hash to create objects in Sinatra"
date:       2021-03-29 02:38:40 +0000
permalink:  take_note_of_using_the_params_hash_to_create_objects_in_sinatra
---


The biggest issue I encountered in the final ActiveRecord lab in Section 5 of Sinatra was having thrown away the knowledge about creating an object with a `params` hash. During earlier lessons and code-alongs, my `params` hashes always seemed to have extra "junk" in them, like the Submit button information, so I started creating objects very explictly by passing each attribute in separately. 

But in this lab, there was a key critial point where I encountered the warning regarding your site working through `shotgun` but not passing tests. I spent a lot of time combing through the official solution but got nowhere. 

I got on Ask A Question with a coach and almost made them late for a project review trying a bunch of different things, including reviewing other students solutions, and we concluded perhaps the test was wrong. I couldn't shake the feeling that I was missing something and I was conflicted about pursuing it further. 

But as scared as I am of not finishing by June 30, I talked myself down into a calm place and tried looking again at a student solution, someone who I had been Slacking with as they are working to complete the program far ahead of me. That's when I realized that all the solutions were creating an object with a whole portion of the `params` hash that contained the necessary attributes, while I was trying to handle all the pieces separately. 

I felt embarrassed about not remembering this tool at all and having to "cheat" to find the answer. Then I thought about it - if I'm stuck on an issue at work or a project with others, I Google it, I rubber-duck it with others, I examine similar code for solutions, and I learn. That's exactly what I did today - once I studied the working solution, I could thoroughly explain how I had gone wrong before and how I could do it differently next time. I added comments to my code as a future-self reminder if I decided to use this lab as a reference.

I stopped panicking a tiny bit. I know I need to continue to hit my studying hard because time is short, but I know I can continue to learn and make progress. I will graduate on June 30 and it's going to feel great.
