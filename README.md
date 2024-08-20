# admin-dashboard

The goal of this project was to replicate the full design of the admin dashboard using primarily CSS Grid for the page layout.

This one took way longer than I expected, I spent 2 days working on this project and it made me realize that I don't yet have
a deep understanding of CSS Grid. I struggled with positioning some elements on the grid, especially when I had multiple grids
in one container, also I didn't structure some sections properly so I had to rework them. I had some trouble with svgs too,
never worked with them before in a project so that was another learning experience.

I had one annoying problem - vertical scrollbar with slight vertical scroll issue on my page. I spent at least an hour trying to
figure out what was the problem and I couldn't find it initially. Next morning when I had some rest I managed to find it almost
instantly - problem was caused by hard-coded value of 40px for the first row of my .projects-section and .container grids.
What a difference does it make when you look at the problem with a fresh mind.

Some of the things I learned:

- placing elements on the grid and better understanding of CSS Grid overall
- adding, resizing and changing the color of SVGs
- z-index when setting box-shadow on grid elements

Mistakes I've made / things to improve:

- I feel I need more practice with CSS Grid to fully understand how everything comes together
