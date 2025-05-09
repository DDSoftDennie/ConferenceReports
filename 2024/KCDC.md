# KCDC

## Building Accessible Android Apps

**Speaker**: Devarsch Chandra

**Notes**:

Devarsch works at Deque Systems.

WCAG2ICT

MATF: Mobile Acessibility Task Force

Accessibility Services in Android:

> **Warning**: Today, Accessibility services are misused to train AI, Spyware, etc.

| XML                           | Jetpack Compose                  |
|-------------------------------|----------------------------------|
| Rigid                         | Little code                      |
| A lot of code                 | API's                            |
| Hard to find and change nodes | Semantics                        |
|                               | Easy to access with Assistive tech |

Jetpack Compose is reinventing Android Legacy! And makes it easy to build accessible apps. More, it makes it difficult to make inaccessible apps.
It's great how Jetpack Compose implemented Textfields and their labels. The label stays visible (it goes up).

> **Question**: What about Accessibility in .NET Maui?
>> Not great, A lot of needed accessibility API's are missing.

## Move Thoughtfully an build things

**Speaker**: Sharat Chander

**Notes**:

Building for people vs Building for profit

Helpful software vs Harmful software

> **Warning**: Move Fast and Break Things
>> Mark Zuckerberg

Bad idea. If you follow engineering principles, **this is really bad and dangerous**.

People first, technology secod.

If your company's mission is "Move fast and break things", you should RUN!

> **Important Question**: Will it benefit the people?
>> Or **only** the capitalistic system?


## Responsible AI and Content Safety

**Speaker**: Veronika Kolesnikova

**Notes**:

Don't ever include PII data in your model to train it!

People (developers, data scientists, ML engineers) need to be **accountable** for their AI!
This is an MLOps practice.

Generative AI Risk tools

**Todo**: Play with the tools launched ad Build!

Principles:

1. Ungrounded outcomes and errors (a.k.a. hallucinations)
2. Jailbreaks & Prompt Injection Attacks
3. Harmful Content & code
4. Copyright Infringement
5. Manipulation & Human-like behavior

> An app about travelling shouldn't answer questions about mushrooms
>> Veronica Kolesnikova

Hmm, Dennie (About chicken stew and mushrooms).

Azure Content Safety System  
Groundness detection, Prompt shield, content filters

**Todo**: Play with the tools launched ad Build! Play with Dall-E & GPT4 (create some 'down' images).
**AHA!**

Own Azure vs Bing Copilot. Play also for "Medical Zinner".

## Testing .NET Web APIs from A to Z

**Speaker**: Egil Hansen

**Notes**:

Json.
What to test for API users?
What are breaking Changes?

Value Effort vs Gain

OpenAPI Specification!

4 Properties of valuable test:

1. Protect against regression
2. Resistance to refactoring
3. Fast Feedback
4. Maintainable

Make a test strategy.

You can use anonymous objects in c# to use with JSON!

## Building a terrible API for the people you hate

**Speaker**: Jim Bennett

**Notes**:

And Good API's for the people you love.

OpenAPI Specification JSON Spec File Generation
Generate Client Library (C# SDK Generation) is possible to use with web API's.

## Run to the Light Carol Anne: Auditing with Lighthouse

**Speaker**: Chris DeMars

**Notes**:

## 10 Tiny updates in .NET 8 you should know

**Speaker**: Tim Corey

**Notes**:

[GitHub Repo](https://www.github.com/IAmTimCorey/TenTinyDotNet8Updates)

### Primary Constructors

```csharp

public class Person(string firstName, string lastName)
{
    public string FirstName { get; } = firstName;
    public string LastName { get; } = lastName;
}

```

### Collection Expressions

```csharp
List<string> Names = ["Tim", "Bob", "Sue"];
```

## 10 seconds at a time - Learning how to embrace change in an uncertain world

**Speaker**: Sharon Weaver

**Notes**:

## Communicating technical concepts to non-technical audience

**Speaker**: Elena Marquetti-Ali

**Notes**:

[Terug](conferenties.md)