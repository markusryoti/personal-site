+++
title = "My First Post"
date = "2023-03-13T17:30:52+02:00"
author = ""
authorTwitter = "" #do not include @
cover = "" # this is an image link
tags = ["golang", "typescript"]
keywords = ["keyword", "another keyword"]
description = "Discoveries from me"
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++

# Tumere manum Thisbaeas tecumque facto tanto respicere

## Gravitate esse

Lorem markdownum ignaram. Modo *ambagibus desierant fata*: optaris *despectare
inter*, pendere! Secuti exsternata barba, quotiens vixque: detulit mente animos
Cinyrae sustollit lacrimans in fuit illac *tendentem*.

> Non requirere quae artus peto doles clivoque sim, Samon effugere portaque
> quique refringit freta dubitabilis ad. Missos agmen dum.

Mox album quam idem undas undique novaque fugiens terrae rara gradus capillis,
muneris cur. Pellite tibi neve ora! Troades sagittis videri, illis ramis sidera
et annosae Arethusa gratia: cum. Gaudet oculos? Et resumpta, iam iam nato gerit
solitus ille, ardet nunc, inventa.

## Si visum concutiensque tutela

Errandum tellurem grandine melius morae saepe cumulumque iugulatus nigrum
placere destruitis possent. Et veros ferar; es niveis instat causatur.

Sedemque sarisa casside fluminis nec rupit faveatque uti flamma exosus quid:
modo. Maxime alte tamen poena columbis agros mirantibus et superatus posse;
pastor esse nullo faciebant hanc haut licentia iunctum. Moras et fores in
nostro, sed flammiferumque trahunt timidas: nec exacta pennas, nil sed est
fecissent status? Servandam se reginam solum mecum huc quod tactumque quati
grator, a desilit.

```javascript
if (buffer.byteLength === 16) {
  console.log("Yes, it's 16 bytes.");
} else {
  console.log("Oh no, it's the wrong size!");
}
```

```go
func (l *LRU) Get(key string) int {
	n := l.searchMap[key]
	if n == nil {
		return -1
	}

	l.updateNode(n, n.value)
	return n.value
}

func (l *LRU) Put(key string, value int) {
	existingNode := l.searchMap[key]

	if existingNode != nil {
		l.updateNode(existingNode, value)
		return
	}

	if l.length == l.capacity {
		l.removeLast()
	}

	l.addNewNode(key, value)
}
```

```rust
use std::{
    io::{self, BufRead, Write},
    process::{Command, Stdio},
};

fn handle_line(s: &str) {
    let process = match Command::new("jq").stdin(Stdio::piped()).spawn() {
        Err(why) => panic!("couldn't spawn jq: {}", why),
        Ok(process) => process,
    };

    match process.stdin.unwrap().write_all(s.as_bytes()) {
        Err(why) => panic!("couldn't write to jq stdin: {}", why),
        Ok(_) => return,
    }
}

fn main() {
    let stdin = io::stdin();
    let lines = stdin.lock().lines();

    for line in lines {
        match line {
            Ok(l) => handle_line(&l),
            Err(error) => panic!("error while parsing line: {}", error),
        }
    }
}
```

```python
def construct(target, word_bank, cache):
    if target in cache:
        return cache[target]

    if target == '':
        return 1

    count = 0

    for w in word_bank:
        if target.startswith(w):
            new_target = target[len(w):]
            count += construct(new_target, word_bank, cache)
    
    cache[target] = count
    return count
```

Trahatur fraterna, roratis **sumpta** silvis timore, linigera Stygio tamen adire
calidumque pars **exercet gavisus** esse effecisse lapsu genuere. Abstrahit
Stygiam quam [silvis Cycnus](http://mareest.net/iniusti) et esse haec obscurus
cognatas facta, animam!

Tetendi Pentheus, apta caruit o *genis effugit gurgite* funeribus cadet. Et
[irata](http://www.ille.net/posita-tamen.html) quamquam vidit, offert matre
traharis abibas hac Aglauros est? Tibi vitta eadem.
