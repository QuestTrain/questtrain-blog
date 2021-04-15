---
layout: post
title: "Why create QuestTrain?"
date: 2021-03-10 15:00:00 -0700
categories: background
---

<head>
    <link rel="shortcut icon" type="image/x-icon" href="/assets/favicon.ico">
    <script>
        !(function (t, e) {
        var o, n, p, r;
        e.__SV ||
            ((window.posthog = e),
            (e._i = []),
            (e.init = function (i, s, a) {
            function g(t, e) {
                var o = e.split('.');
                2 == o.length && ((t = t[o[0]]), (e = o[1])),
                (t[e] = function () {
                    t.push([e].concat(Array.prototype.slice.call(arguments, 0)));
                });
            }
            ((p = t.createElement('script')).type = 'text/javascript'),
                (p.async = !0),
                (p.src = s.api_host + '/static/array.js'),
                (r = t.getElementsByTagName('script')[0]).parentNode.insertBefore(p, r);
            var u = e;
            for (
                void 0 !== a ? (u = e[a] = []) : (a = 'posthog'),
                u.people = u.people || [],
                u.toString = function (t) {
                    var e = 'posthog';
                    return 'posthog' !== a && (e += '.' + a), t || (e += ' (stub)'), e;
                },
                u.people.toString = function () {
                    return u.toString(1) + '.people (stub)';
                },
                o = 'capture identify alias people.set people.set_once set_config register register_once unregister opt_out_capturing has_opted_out_capturing opt_in_capturing reset isFeatureEnabled onFeatureFlags'.split(
                    ' '
                ),
                n = 0;
                n < o.length;
                n++
            )
                g(u, o[n]);
            e._i.push([i, s, a]);
            }),
            (e.__SV = 1));
        })(document, window.posthog || []);
        posthog.init('Me-DWX5oXqZ5yQQQMvGPk0xjasnVcQrvzO5q3KI-QM0', {
        api_host: 'https://questtrain-analytics.herokuapp.com',
        });
    </script>
</head>

**By: Michael Vogelsong**

I've always been fascinated with learning. How do I learn something new? How does a baby figure out movement and language so quickly? How does a community evolve over time to better address the needs of its members - i.e., collectively learn? How do we gain an understanding another person's lived experiences, and gain that sense of empathy and perspective? What happens during that magical transition when a concept goes from foggy foresight to obvious hindsight?

I believe that the root of learning is not about building a big database of "answers." Rather, it's about crafting **trains of questions** that (a) make useful new ideas obvious and natural, and (b) welcomes others into the process. A answer is a wall; a question is an open door.

<div style="text-align:center"><a href="https://www.questtrain.com"><img src="/assets/QuestTrainLogoGreen.png" height="128" /></a></div>

# What is the goal?

You guessed it, there is no single right answer. But here are some useful framing questions:

- **Understanding engine**: What would a search engine look like if the goal was deeper understanding of nuanced topics, rather than webpage traffic?
- **Version control for critical thinking**: How do we bring the advantages of software development into the learning process? How do we make critical thinking cool?
- **Presentations designed for the audience**: Slide decks and journal articles have drawbacks - so what is the best way to share understanding with an audience? Can we make networked science a reality?
- **Efficient teaching**: How do I "hop on the train of thought" of a person I respect? How do I get a feel for how they approach a difficult problem?
- **Empathy**: Would it help to see the types of questions that are top-of-mind for people of different backgrounds? Would that provide a better understanding of their lived experiences, and how that shapes their perspectives?
- **Human-machine learning model**: Can we collectively build an interpretable, inclusive, and diverse AI model of the world? 
- **How-tos for figuring it out**: Rather than blindly following a protocol, how could I have - from first principles - figured out how to accomplish some goal?

Maybe a little too ambitious? Yeah, but it's more fun than shooting for something easy!

# How does it work?

The crux of the platform is a **QuestTrain** - a community-built, composable train of thought. In the simplest case, a train is just a series of questions - users add questions and link them up. Add a bunch of interesting people with interesting questions, and this creates a big ol' network of searchable, pluggable human thought and discovery.

At this point, you may be wondering, "where are the answers?" It may seem weird to build a search engine with no answers, but our hypothesis is that questions (and specifically how questions lead to one another) are far more useful in a creative or generative setting. Plus, QuestTrain is not really a search engine or Q&A forum - it's more like a playground for discovery. Specifically, QuestTrains are designed for making progress on the hard, hairy, ambiguous, and overwhelming problems where there is no single "right answer" - questions like "How does cancer work?" or "How do we solve climate change?" These questions are not going to be solved by a website link or searching for specific, isolated bits of knowledge. Rather, we'll make progress by pulling in ideas from different domains, testing hypotheses, and making connections.

To ground our questions, we provide two additional primitives that can be attached to QuestTrains: data carts and actions. **Data carts** are the placeholders we reserve for data to feed in - the standard-format primary-source information that is relevant to making decisions on our questions. For example, you could specify column names in a table of anticipated clinical trial results or CO2 sensor arrays. **Actions** are automations (APIs and webhooks) that can be triggered based on information in those data carts. These primitives help turn QuestTrain ideas into executable "programs," and turn the whole network into an interpretable and testable model of the world.

# What can you do?

Some of these features exist now, and others are on the roadmap - stay tuned!

- Ask a question and add it to the network
- Search for related questions
- Explore the question network, hop around the links, and spark your creativity
- Explore other QuestTrains and build your own off theirs
- Follow another user and see their QuestTrains
- Share links to QuestTrains
- Specify data carts
- Link data feeds to the data carts
- Do a "what if?" analysis by assuming a value for a data cart, and evaluating how that affects downstream questions
- Add automations / APIs / webhooks that trigger when a question's data cart is filled in a way that meets some question's criteria
- Analyze and sort questions. For example, which questions lead to the most follow-on questions (most interesting)? Which questions have the most data carts filled (most evidence)? Which questions are requested by the most people (broadest reach)?

But wait, there's more! If you order within the next 30 minutes, we'll throw in a FREE travel-size microfiber sham. That's a $20 value! (Some restrictions apply*)

# Why the name *QuestTrain*?

QuestTrain sounds like *question*, and the ".com" domain name was much cheaper. Plus, the train analogy works on many levels: *train of thought*, *learning tracks*, *making the connection*, search *engine*, etc... And finally, we're on a *quest* for understanding. We're very pro-wordplay.

# What's the bottom line?

QuestTrain is an attempt to make questions cool. Interested? [Check out questtrain.com!](https://questtrain.com)

<sub>* Microfiber sham is a sham. Not actually included.</sub> 