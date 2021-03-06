---
layout: page
title: About
permalink: /about/
---

<head>
    <link rel="shortcut icon" type="image/x-icon" href="/assets/favicon.ico">
    <script async defer data-domain="blog.questtrain.com" src="https://plausible.io/js/plausible.js"></script>
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
        if (!window.location.href.includes('localhost:')) {
            posthog.init('Me-DWX5oXqZ5yQQQMvGPk0xjasnVcQrvzO5q3KI-QM0', {
                api_host: 'https://questtrain-analytics.herokuapp.com',
                disable_cookie: true,
            }
        });
    </script>
</head>

This is the official blog for [QuestTrain.com](https://questtrain.com).

QuestTrain is a small startup run by Michael Vogelsong, and based in Seattle, WA. Feel free to reach out and say hello at [hello@questtrain.com](mailto:hello@questtrain.com)! I promise we're friendly.

<div style="text-align:center"><a href="https://www.questtrain.com"><img src="/assets/QuestTrainLogoGreen.png" height="128" /></a></div>