# 🌟 Étoile Language Design: Step-by-Step Guide

So, you want to create your own programming language. Cool.  
But before you dive into syntax and emojis and compilers, there’s something important you need to get:

> **What actually makes a programming language a language?**

Let’s break it down.

---

## 🔍 High-Level Languages Are Just… Text?

Yep. At the end of the day, a programming language—no matter how powerful or elegant—is just a bunch of **text**.

Just like how we speak and write in natural languages (like English, Russian, or Armenian), programming languages are made up of **words**, **symbols**, and **patterns** that humans can understand—and more importantly, that machines can be taught to understand.

The real magic isn’t in the words themselves.  
It’s in the **rules** that say *how* those words can be used.

---

## 🧠 Learning to Code Feels a Bit Like Learning to Speak

Think about it. You speak your native language without even thinking. You don’t pause mid-sentence to figure out grammar or vocabulary. It just flows.

But when you try to learn a foreign language—say, Russian—it gets tricky.

Let’s say you’re just starting out, at **A2 level**, and you’re trying to talk to **Andrey**, a native Russian speaker. You want to say:

> `"I see the dog."`

In your head, you start translating word by word (let’s remember this moment—there exists a language we already know, our *mother tongue*, and we’re trying to map from it):

- `"I"` → `"Я"`  
- `"see"` → `"видеть"`  
- `"the dog"` → `"собака"`

So you say:

```text
Я видеть собака
```

But Andrey blinks. The words are technically right, but the sentence doesn't make sense. He doesn’t know if you’re seeing the dog now, saw it earlier, or what you mean at all.

He might ask:
> `“Did you mean: Я вижу собаку?”`

You say it correctly this time:

>`"Я вижу собаку."`

And now everything clicks.
That’s our second big idea:

*✅ The order and form of words matter.*

## 🧩 Programming Languages Work the Same Way
Writing code is like talking to a very strict, very literal friend who only listens when you speak their language perfectly.

Programming languages have their own:

- Syntax – how you’re allowed to structure things

- Grammar – rules that give structure and meaning

- Vocabulary – the set of keywords, functions, and symbols it understands

Mess those up—even just a little—and your code won’t work. The computer won’t “guess” what you meant. It just says: ❌ 

```Etoile
🖨️"Hello"    # ✅ This works
"Hello" 🖨️      # ❌ This breaks did you mean 🖨️"Hello"
```
Just like Andrey, the machine might ask you to clarify—but you have to fix it. 
Even though the words are right, the order isn’t. And programming languages really care about order.

