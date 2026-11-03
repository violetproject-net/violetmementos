# violetmementos
memento repo for https://violetproject.net

static/mementos is where memento json files go
format is as such 
<pre>
{
    "name": "example badge",
    "desc": "this is the description",
    "cond": "this is how you get it as text",
    "art": "the artist who made the badge, or more than one",
    "anim": "y(whether it is animated or not)",
    "game": "blackrain (game badge is in, leave line out if N/A)",
    "reqtrigger": "1 (amount of required triggers, NOT the limit)",
    "t1": {  
    "map": "67 (map id of trigger)",
    "x1": "67 (left boundary x value)",
    "x1": "67 (left boundary x value)",
    "y2": "67 (bottom boundary y value",
    "y2": "67 (top boundary y value",
    "evinteract": "67 (event id for interaction trigger)",
    "evcollision": "67 (event id for collision trigger)",
    "var1": {
    "id": "67 (the variable id)",
    "op": "<= (the operation)",
    "val": "67 (the value of the variable)"
    },
    "switch1": {
    "id": "67 ( the switch id)",
    "val": "on (on or off switch)"
    }},
}
</pre>
art is put in static/img/mementos with the filename the same as the "name" field, e.g example badge.png example badge.gif

adding more todo
we need translation capability aswell
