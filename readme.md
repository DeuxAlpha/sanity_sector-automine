# Overview

This is a simple mod for the 'Sector Automine' job in X4 Foundations,
which allows for ships to harvest more than one resource and sell its
wares in external sectors.

# Reasoning

In the original game, the ship executing the order would get stuck in
the anchor sector if it had nowhere to sell its resources. This seemed
silly, as no matter what level your pilot was, you would get no benefits
out of the job in the long run, unless you had the resource and stations
to sell it to in the same sector.

# Features

- Allows for selecting multiple resources to mine (like Advanced
  AutoMine)
- Allows for selecting the range of sectors in which miners may sell the
  harvested resources
  - The max range is calculated in the same way as the other mining
    jobs. This means that a level 5 pilot can sell up to five sectors
    away, while a level 0 pilot can still only sell in the same sector.
    I'm sorry, but level 0 pilots are morons. I did this to ensure the
    job stays fair, but feel free to raise an issue if you have a better
    idea.