# [Project Name]

> Time-box this whole document to 30 minutes. If it takes longer, you're overplanning.

---

## 1. What is this, in one sentence


> One sentence. If you can't write it, the idea isn't ready.
> Example: "A solo roguelike where you play a courier delivering packages in a hostile forest."




---

## 2. What v1 does (three bullets max)


> The smallest version that's recognizably the thing.
> Not a vertical slice. Not "the full game." The embarrassing-but-real minimum.

-
-
-

---

## 3. What v1 explicitly does NOT do


> The most important section. Should be LONGER than section 2.
> Every item here is a decision you don't have to make later.


-
-
-
-
-

---

## 4. Data model

> The nouns in your system and what they hold.
> Just shapes — no protocols, no architecture yet.


```swift
struct Example {
    let id: UUID
    var name: String
}
```

---

## 5. State machine


> 3–7 states. More than that = v1 is too big.
> Format: stateA → stateB → stateC
-->

```
launching → main → detail
```

---

## 6. The one scary thing


> The part you don't know how to build yet.
> Prototype this FIRST in a Playground or test target,
> before building the app shell around it.

> If there's no scary thing, the project is too small to learn from.
-->



---

## Notes

> Revise this doc as you learn what's actually hard.
> If you're rewriting it more than twice, cut scope.
> v2 doesn't exist until v1 ships.

