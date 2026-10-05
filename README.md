# Explaining Loops

Teach a brand new programmer when to reach for a `for` loop and when to reach
for a `while` loop.

- [AI Use on This Assignment](#ai-use-on-this-assignment)
- [Setup](#setup)
- [Instructions](#instructions)
- [Short Response Questions](#short-response-questions)
  - [Prompt 1](#prompt-1)
- [Submitting](#submitting)

## AI Use on This Assignment

These are your own words. Do not use AI to draft or rewrite your responses —
that holds in every mode, including implementer mode. You may use it to check
grammar and spelling on writing you have already done, and you may use it
before you start to quiz you until you can explain both loops without notes.
Paste this if you want that kind of help:

> You are acting as a tutor. Quiz me on Python for loops, while loops and
> range() until I can say what each one is for without looking anything up.
> Tell me when my reasoning is wrong or imprecise. Do not write or rewrite any
> part of my response for me.

A response you did not write is worth nothing to you in an interview, which is
where this writing is really aimed.

## Setup

Work in `development/mod-1`. Make a draft branch before you start.

```sh
git checkout -b draft
```

There is no code to run here. Pushing tells GitHub to check whether you have
written a response yet, which you can see in the **Actions** tab. That check
counts words. Your instructor reads what you wrote and replies on your pull
request.

## Instructions

Write your response in `short_response.md`. Aim for a response with these
qualities. Your instructor will give you feedback on each one:

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

## Short Response Questions

### Prompt 1

Python gives you two ways to repeat work, and a new programmer picking between
them is usually guessing. Write them a short lesson that stops the guessing.

Your lesson should have four parts:

- A plain-language rule for choosing between a `for` loop and a `while` loop.
  One sentence, and it should actually decide the question.
- An example of each, in a Python code block, with a sentence saying why that
  loop fits that job.
- An explanation of what `range(2, 10, 2)` produces and why the last number it
  gives you is 8.
- What goes wrong with a `while` loop that a `for` loop cannot do to you, and
  how you would get out of it.

Use these terms correctly: **iterable**, **infinite loop**, and either
**`break`** or **`continue`**.

Defining them is the assignment, so we are not defining them here.

A rule that says "use a for loop when you are looping over something" is not
a rule yet, because it does not tell anyone what to do with a job that has no
collection in it. Push until yours decides.

## Submitting

```sh
git add -A
git commit -m "your message"
git push
```

Open a pull request to your instructor for feedback.
