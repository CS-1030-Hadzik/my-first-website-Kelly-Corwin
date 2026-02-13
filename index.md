---
layout: default
title: "Kelly's CS 1030 Website"
---

This is my website

[LinkedIn](https://www.linkedin.com/in/kelly-corwin-36449a165/).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# About Me

I'm the dude playin' a dude disquised as another dude... 
I'm also a Software Engineer currently pursinging a CS major at Weber State University.
Married father of three boys, avid retro and AAA gamer, and practionor of both Kendo and Iaido.

## Header 2

> " You didn't come into this world... you came out of it. Just as an apple tree apples, 
> the universe peoples, and you are one of those peoplings. You're not a stranger wandering 
> through a foreign land. You are this place, its eyes, its thoughts, its wonderings about 
> itself. Most of us were brought up to feel separate as though we're tiny egos trapped inside 
> these bags of skin looking out at a world that's over there full of objects and others, but 
> that is a trick of perception. An illusion of language and labelling. In reality, there's no 
> line where you stop and the world begins. You are continuous with it like a wave is with the 
> ocean. Look at a flame. Does it have a boundary, a fixed shape? It's a process, a happening, 
> a flow. So are you, and you’re not a static thing. You are a verb disguised as a noun. 
> A whirl of consciousness, feelings, memories, all shimmering like light on water. When you 
> were born the universe didn't make a mistake. It wasn't trying to test you, fix you, or mold 
> you into something better. It was expressing itself as you, and what a peculiar, delightful, 
> and intricate expression you are.                                               – Alan Watts

### Header 3

```js
// Javascript code with syntax highlighting.
// Simplified Combat
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
# Ruby code with syntax highlighting
# Simplified Combat
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

#### Header 4

*   There are those that make things happen.
*   There are those that watch things happen. 
*   There are those that wonder "What the #@$%! happened?".

##### Header 5

1.  Samurai care about honor.
2.  Knights care about sovereignty. 
3.  Vikings don't care and take all your stuff anyway. 

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

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```