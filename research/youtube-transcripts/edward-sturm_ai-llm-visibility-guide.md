# Edward Sturm — AI & LLM Visibility: A Practical Guide for Ranking in AI Results

**Channel:** https://www.youtube.com/@buildinpublic
**URL:** https://www.youtube.com/watch?v=ZXR1HvUU1kI
**Published:** ~October 2025
**Views:** 6.8K

---

## Transcript

David Quaid is joining the podcast once again and David, you're going to be talking about how to rank in LLMs.

Absolutely. And thanks for having me back. I think there's a lot of information or misinformation about how people get visibility in search engines and LLM search engines. And this is something that is really close to my heart because I'm a big believer in SEO and the democratization of access to people. And I think you covered a story that was on our SEO a while back about how GEO companies were paying SEOs to spread disinformation. And there's a lot of things about like how LLMs cite things and how LLMs are looking for things like schema which is not true. Mark Williams Cook did an excellent debunking of that. And I made an episode on that as well.

So what I wanted to share with people today is understanding the query fanout. And if you can understand the query fanout, you can directly link SEO to LLM visibility. What's interesting is that Profound actually came out with a blog post last week saying it's the query fanout. And I think for a while they had been in the camp of "oh it's all about citations and you know brand marketing and things like that." It's not. LLMs are not search engines. And I think that's a fundamental sort of default thinking that a lot of people have. They assume that an LLM is trained with all this information. It's sort of like a cached version of the entire web and that they can give results. They don't. They cannot store that amount of information — they couldn't store the amount of information that Google handles in an hour.

And so it's very important to know that with PageRank, with Google, even if they're using Bing or Brave Search in the case of Claude, they're actually using standard SEO to rank things, but they're breaking down the query — the prompt — into different queries. So I just pulled up a random example here: "best SaaS SEO case studies," and you'll see Zapier ranking, Slack, Ahrefs. And a lot of people see the citations, and what people might see is that they're putting in a search phrase that they're not ranking for. The first thing — and the reason I'm using Perplexity is this is just a little bit easier to do in Perplexity and a little harder to do in ChatGPT, but you can do the same. You just need a QFO tool.

So when you look at the assistant steps in this case, it's the same thing, right? So "best SaaS SEO case studies" — but I wanted to have a look at something that I rank for because I'm also really really skeptical about EAT in SEO. And I don't think that EAT is something that Google can detect. Google has said that they can't detect it, but it's ever-present in a lot of marketing information on LinkedIn and X and on Reddit. So let's put in "EEAT SEO guide" and see what comes back.

And so here we can see the change straight away. That's what I would be looking at if I was looking for ranking. So I try to rank for these phrases to sort of help balance the amount of information out there. And what Perplexity is searching today — and this would have been different a month ago — and we call that difference or that change the "drift" — is it's broken up into "EEAT SEO guide" and "2025." So adding 2025 is very common in the query fanout and you'll see it matches a lot of the page titles for some of the content that's ranking here.

So if you go to your search console and start looking at what do you rank for, if you're ranking for "EEAT guide" and then you go to ChatGPT and type in the same search phrase and you see different results, it's not because the LLM has a different search ranking algorithm. It's because it's changed the search query. And if I take this search query instead of the prompt and I do a search in Google, I'll see that all of the results are exactly the same in almost exact order.

And what happens is Perplexity actually sends its crawlers to fetch each of these documents in real time to make that synthesized answer on the homepage. The crawler — I think people think that the crawlers go out all day every day like Google crawlers and are building up a copy of the web. This is a real time scenario and you can literally rank in Google now and in two minutes repeat the search in Perplexity and see that you're actually in the results even if you weren't there 10 minutes ago.

And you're saying the query fanouts are different for different LLMs?

They're different for different LLMs and they're different at different times of the day. So let's take another one that I think a lot of your audience might be interested in. Let's take an example for "best SaaS CRM for a company with 200 people." One of the big differences with LLMs is that people are getting into deeper, more complex prompts. They know they're not dealing with Google anymore. And so sometimes we can actually see much more complicated fanouts with up to three queries.

So recommend a better CRM for my sales team at my car parts website. And again, it's actually broken the query down into something much more simple. Before I would have actually expected maybe three fanouts and then we would have got 30 results. Here you can see they're just eight results. And again, if we take the search, we'll see that basically a lot of big websites ranked.

I think this is adding to the frustration and the confusion that the LLMs are preferring more bigger brands. But what happens is with these drifts is that they tend to rank sites with a lot more authority. And you can see that if you're ranking for "best CRM" or "car parts website" without 2025, you may actually see a different set of results. And if you're ranking in this, here we see Smith.ai, now we see Reddit appearing. And so that also brings into play this other idea that LLMs prefer Reddit. It's not that they prefer Reddit, it's just that Reddit often crops up in Google's rankings.

That's a good point. That's a very important point. Absolutely.

So where does that leave us with regard to how to actually rank in LLMs? I would start at my different LLM tools — whether it's Grok or Perplexity or Claude — and I would just start thinking about what are people searching for? You don't have to have a subscription. And I would just start trying to think about what I'm ranking for in Google. So "top SEO agencies in New York." I think a better question is: to what extent should people be focused on ranking in LLMs versus trying to do the best SEO that they can, knowing that the more SERPs that they appear in the more they'll be covered in LLM?

Absolutely. That's why I would start here, right? In the sense that I'm ranking first here simply because I'm ranking in this list of results. And I'm ranking in here twice because I'm in here and I'm in Clutch. And you gave the example — you changed your page, you submitted it to Google Search Console. So then the LLMs are going to pick it up.

Exactly. And you can literally take a search where you don't appear, go and create content for it, publish it, and come back and test. And you need to test it a few times so that you can figure out how the query drifts and changes over time. And then you can account for that or modify or add to your content so that you can be ever-present. So you're looking at the searches that Perplexity is doing so that you know the right language to use in your content.

Exactly. And here's Claude — Claude doesn't use Google. It uses Brave Search, which is a German search tool, but it's 100% a PageRank clone and it works almost exactly the same way as Google. And I think I said on our first cast — nothing has beaten PageRank. And this stands over that.

Yeah. For people who haven't listened to that one — that's episode 8446 of the show: "The SEO Playbook That Actually Works: PageRank, Topical Authority and Real Results" — and that one is like a 2-hour banger episode that people just love.

Yeah. And this episode too, you shared some cool stuff. Especially just seeing the language, showing how to see the language here. So do you know the dev tools way to do it in ChatGPT?

I don't. Do you want to show me?

Yeah, I'll show you. So this is how to find query fanouts in ChatGPT. So search something that ChatGPT will actually search the web for — like "fall winter 2025 fashion trends." And we're going to — this is to see the actual language that ChatGPT is searching with.

So we have this. And what's so funny is if you ask ChatGPT what it searched, it won't actually tell you the exact query. It doesn't know. If you say "What did you search to find this?" it doesn't know. It'll tell you what it thinks it searched, but it won't actually tell you what it searched. So, what you have to do is you have to right-click, inspect, go to Network, copy the string that starts after the C forward slash, paste that into the filter and then refresh the page. Click on the orange bracket, go to Response, and then do a search within this for "quer" — as in "quer" — and then it'll show what it actually queries.

Yeah. Yeah. And there — this is what it searched.

Amazing. Yeah. I got this from Chris Long who shared this on LinkedIn and I'm like, that's cool. And then I learned it and I made videos on it.

That's so interesting because like one of the things I found is there's a lot of dead web happening on Reddit. There's a lot of subs that are allowing bots and companies have five bots in one conversation. One bot will come in and go "hey, we have a case study of 400 data points" and there's no reference to the data. And I think that's got to be a red flag. If you can't point to where the data is, and then you'll see other bots coming in and saying "oh yeah, this is exactly what I thought." And you see the bots talking. It's like the dead web in real life.

And I think that's awful because the bots are never going to respond to you and the same bots are having the same conversation in other Reddits that allow them to have that conversation. But if you actually start to challenge the people who spread this information, if you go to Perplexity and say "How do you work?" or like you said, if you ask ChatGPT how it works, it either makes it up or Perplexity will actually go and do a Google search and come back and share what a blog post tells it how it works. And you know, I think we said as well that these aren't research tools. And I think that's a real danger.

Yeah, it's really scary. So the key takeaway here is really that LLM ranking is just SEO. If you're ranking in Google and Bing and Brave, you're going to rank in the LLMs that use those search engines. And the query fanout explains why sometimes you rank in LLMs for terms you're not directly targeting — because the LLM breaks your search down into component queries and finds you via those. The drift also explains why your LLM rankings can change from day to day even when your Google rankings haven't moved.

So the practical advice is: do great SEO, study your Google Search Console data carefully to understand what queries you're actually being found for, use those to understand what the LLMs are likely searching, and create content that comprehensively covers those topics.

All right, David. Thank you. And for everybody watching and listening, this is episode 859 of the Edward Show. 859 days in a row. Thank you. I will talk to you again tomorrow.
