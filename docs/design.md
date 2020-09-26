# Golem click
---
# Introduction
You are a mage, out to make your fortune.  Of course, fortunes are best made the easy way, and what could be easier than letting golems do it for you?!  Gather raw materials and create golems to perform a variety of tasks that make you rich and famous!

---
# Overall Design

## Objective
Riches

## Primary Mechanic
Clicking

## Starting Conditions
- One Clay source
- No other resources  

## Progression
|Object | Type | Uses | Produces|
|-------|------|------|---------|
|Clay Pit | Manual | None | 1 Clay |
|Ritual | Manual | None | 1 Magic |
|Craft Golem | Manual | 10 Clay, 10 Magic| 1 Clay Golem |
|Clay Golem | Automatic | 1 Magic | 10 Clay |

---
# System Design
- *Main Clock* ticks 10 times per second
- *Tick* - each *Automation* produces 1/10 prod value
- *Tick* - update production options
- *Click* - Produce full prod value.
- *Produce* - *Use* resource.  *Add* output.
