---
layout: default
title: "Kelly's Kendo Journey"
---

This website is dedicated to the many great teachers and fellow kenshi I've had the honor of crossing swords with. Domo arigato gozaimasu.
![Menjo]({{ "/assets/images/Menjo.jpeg" | relative_url }})

[My_Nidan_Exam](https://youtu.be/GbLVNVQrdx4?si=h-ko71h8eOXg4G-y).

“Today is victory over yourself of yesterday; tomorrow is your victory over lesser men.”
― Miyamoto Musashi, 'Gorin no Sho' The Book of Five Rings

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
// Kendo Sparring Match
const white = { name: "White", score: 0 };
const red   = { name: "Red",   score: 0 };

const targets = ["Men", "Kote", "Do", "Tsuki"];

function strike(attacker, targetKey) {
  if (!targets.includes(targetKey)) {
    console.log("Invalid target!"); return;
  }
  attacker.score++;
  console.log(`${attacker.name} lands ${targetKey}! Ippon! (+1)`);
}
```

```ruby
# Kendo Sparring Match
white = { name: "White", score: 0 }
red   = { name: "Red",   score: 0 }

TARGETS = %w[Men Kote Do Tsuki]

def strike(attacker, target)
  unless TARGETS.include?(target)
    puts "Invalid target!"; return
  end
  attacker[:score] += 1
  puts "#{attacker[:name]} lands #{target}! Ippon! (+1)"
end
```

#### Striking targets in Kendo

*   Men (面) - Strike to the head.
*   Kote (小手) - Strike to the wrist.  
*   Dō (胴) - Strike to the torso.
*   Tsuki (突) - Thrust to the throat. 

##### Major components of 'Yuko-datotsu'

1.  Ki-Ken-Tai-Icchi (Spirit, Sword, and Body as One): The mental, technical, and physical components must unify at the moment of impact.
2.  Datotsu-bui (Valid Target Area): The strike must land on the designated, protected areas.
3.  Zanshin (Awareness): A state of continued, physical, and mental alertness and readiness to make a subsequent attack after the initial strike. 

###### Criteria for scoring 'Ippon'

| Components             | Requirements           |
|:----------------------:|:----------------------:|
| Maai (Distance)        | Shisei (Posture)       |
| Kikai (Opportunity)    | Kisei (Spirit)         |
| Tai-sabaki (Movement)  | Datotsu-bui (Target)   |
| Tenouchi (Grip)        | Hasuji (Cutting Angle) |

### I am the "Onikuma" when doing Nito-Ryu (Two Sword Style)

![Onikuma]({{ "/assets/images/Onikuma.jpg" | relative_url }})

### My first ippon in Nito against Alex Bennett of all people!

![Kelly_Nito]({{ "/assets/images/Kelly_Nito.jpg" | relative_url }})

### Getting to meet Alex Bennett (7th Dan, Kyoshi) and Hiro Imafuji (7th Dan, Renshi)

![Great_Sensei]({{ "/assets/images/Bennett_Imafuji.jpeg" | relative_url }})

### See you at the dojo!

<dl>
<dt>Name</dt>
<dd>Kelly Corwin</dd>
<dt>Dojo</dt>
<dd>Zen Bu Kan - School of Japanese Swordsmanship</dd>
<dt>Location</dt>
<dd>777 South 1300 East, Salt Lake City, UT 84102</dd>
</dl>

```
“One-thousand days of training to forge, ten-thousand days of training to refine. But a [Kendo] bout is decided in a split second.”
```