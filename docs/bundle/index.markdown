---
layout: default
title: "Kelly's Kendo Journey"
---

This website is dedicated to the many great teachers and fellow kenshi I've had the honor of crossing swords with. 

[LinkedIn](https://www.linkedin.com/in/kelly-corwin-36449a165/).

“Today is victory over yourself of yesterday; tomorrow is your victory over lesser men.”
― Miyamoto Musashi, A Book of Five Rings: The Classic Guide to Strategy

# About Me

The broad stroke is that I'm a Software Engineer currently pursinging a CS major at Weber State University.
Happily married father of three boys, avid retro and AAA gamer, and practionor of both Kendo and Iaido.

## One of many great quotes from Alan Watts

> "You didn't come into this world... you came out of it. 
Just as an apple tree apples, the universe peoples, and you are one of those peoplings. 
Most of us feel seperate, like tiny egos trapped inside these bags of skin.
Looking out at a world that's over there full of objects and others, but that's a trick of perception. 
In reality, there's no line where you stop and the world begins. 
You are continuous with it like a wave is with the ocean. 
It's a process, a happening, a flow, and so are you.
You are not a static thing, you are a verb disguised as a noun."

### JavaScript and Ruby examples

```js
// FF7 Nibelheim Flashback Combat
const cloud = { name: "Cloud", hp: 500, attack: 50 };
const sephiroth = { name: "Sephiroth", hp: 1000, attack: 80 };
function attack(attacker, target) 
{ target.hp -= attacker.attack;
  console.log(`${attacker.name} attacks for ${attacker.attack} damage!`);}
console.log("BATTLE START");
attack(cloud, sephiroth);
attack(sephiroth, cloud);
console.log(`Cloud: ${cloud.hp} HP, Sephiroth: ${sephiroth.hp} HP`);
```

```ruby
# FF7 Nibelheim Flashback Combat
cloud = { name: "Cloud", hp: 500, attack: 50 }
sephiroth = { name: "Sephiroth", hp: 1000, attack: 80 }
def attack(attacker, target)
  target[:hp] -= attacker[:attack]
  puts "#{attacker[:name]} attacks for #{attacker[:attack]} damage!"
end
puts "BATTLE START"
attack(cloud, sephiroth)
attack(sephiroth, cloud)
puts "Cloud: #{cloud[:hp]} HP, Sephiroth: #{sephiroth[:hp]} HP"
```

#### Facts

*   There are those that make things happen.
*   There are those that watch things happen. 
*   There are those that wonder "What the #@$%! happened?".

##### Additional Facts

1.  "The Hunt For Red October" deserved an Oscar for more than just sound design...
2.  The likelihood of being born on February 29th is 0.068% which makes me feel so special...
3.  Lobsters would live forever if it weren't for the amount of energy necessary for them to molt... 

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Me in my "Onikuma" zekken

![Onikuma]({{ "/assets/images/Onikuma.jpg" | relative_url }})

### My first time fighting Alexander Bennett PhD (7th Dan, Kyoshi)

![Nito-Ryu Kendo]({{ "/assets/images/Kelly_Nito.jpg" | relative_url }})


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Kratos</dd>
<dt>Born</dt>
<dd>early-to-mid 500s B.C.E</dd>
<dt>Birthplace</dt>
<dd>Sparta, Greece</dd>
<dt>Color</dt>
<dd>White; ash fused to his skin</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```