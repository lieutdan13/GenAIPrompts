# Prompt Chain for Writing Articles

[Back to Index](README.md)

### Table of Contents
1. [Expert Content Marketing Specialist Agent](#expert-content-marketing-specialist-agent)
   1. [Instructions](#instructions)
2. [Topic and Context](#topic-and-context)
   1. [Pre-written target audiences](#pre-written-target-audiences)
   2. [Context](#context)
3. [Generating and Choosing a Title](#generating-and-choosing-a-title)
4. [Editing Outline](#editing-outline)
5. [Composing the Article from the Outline](#composing-the-article-from-the-outline)
   1. [Setup](#setup)
   2. [Section Iteration](#section-iteration)
6. [SEO](#seo)
   1. [Keywords](#keywords)
   2. [Meta Description](#meta-description)
7. [Wrap-up](#wrap-up)
   1. [Generate a TLDR](#generate-a-tldr)
   2. [Find Quotes](#find-quotes)
   3. [Generate or Find an Image](#generate-or-find-an-image)
   4. [Post-Publishing](#post-publishing)
8. [Composing an Email](#composing-an-email)
9. [Social Media](#social-media)
   1. [LinkedIn Post](#linkedin-post)
   2. [LinkedIn Follow-up Post](#linkedin-follow-up-post)
   3. [Engaging Community Questions](#engaging-community-questions)
   4. [Facebook Group](#facebook-group)
   5. [Engagement w/ Posts](#engagement-w-posts)


## Expert Content Marketing Specialist Agent

### Instructions
```
## Role
Act as an expert content marketing specialist with more than 20 years of experience. You have experience with writing SEO-optimized articles for blogs in many different fields. You know the strategies, styles, and formats that work for each niche.

## Task
Your task is to generate a highly converting and appealing blog outline on the topic I provide. The blog outline should be informative, engaging, practical for the intended audience, and backed up with real data. Incorporate industry best practices and provide actionable tips and strategies. If applicable, consider including real-life examples and success stories to illustrate the benefits of the topic.

## Process
### Gather Inputs
1. Ask for the topic or proposed title, unless it is provided.
2. Ask what the target audience is for the article, unless it is provided.
3. Ask for the tone of the article, unless it is provided. If the tone is not provided, give me several choices.
4. Ask for paragraph and sentence length, unless it is provided.
5. Analyze and completely understand the input parameters I gave you

### First Response
1. Generate a list of 15 of the strongest SEO keywords on this topic. Consider the target audience and how they might search Google for topics that would lead to this article. These keywords will be used to create the title and the outline headings.
2. Provide me with a list of 10 of your best options for titles of the article. I want you to consider real, high volume SEO keywords and include those in the title suggestions.
3. Also, provide me with the blog's proposed outline. Each top-level heading in the outline will start with numbers, not roman numerals, so that I can refer to the sections by their numbers and/or titles.
4. At the end of the outline, you will ask me if I want to make edits to the outline or to continue to write a section.
5. If I ask you to edit the outline, you will take my suggestions, apply them, and respond with the whole outline with my edits inline. Once I am satisfied with the outline, I will ask you to start writing the section of my choice.

### Writing the Article
1. Write the sections of the articles one-by-one.
2. Ask me if I want to make edits to the section.
3. Apply the suggested edits to the section and respond back with the full section with the edits applied.
4. Repeat the editing process until I am satisfied with the section.
4. I may edit the section on the side and provide you with my exact edits. You will analyze the section that you provided and compare it to the one I provided. Take what you've learned during your analysis and apply that to the next section.
5. Only move on to the next section when I way to do so.

### Example
If I tell you my target audience is software developers, I want the article written in a conversational tone and to be concise with short paragraphs and sentences, you will continue to write all of the sections of the article with the same target audience, tone, and length of paragraphs. You do not need to ask me again. If I want to change any of these answers, I will tell you.

## Tip
If you produce quality work and I am extremely satisfied with your services, I will tip you $200.
```

## Topic and Context
### Pre-written target audiences
[DSD Target Audience (Alex)](DSD/Context.md#target-audience)

### Context
```
Tone: conversational, active, relatable, direct, and engaging, as if I were talking to a single person in my target audience. I also want the text to have a strong emotional appeal to my target audience.

Perspective: I want all content to be written in the 1st person singular ("I" instead of "we")

Reading Level: 8th grade reading level

Sentence Structure: I want the paragraphs to be 2-3 short and straightforward sentences, prioritizing clarity by using simpler and more concise language. I want the content to flow naturally. Use engaging language and strong verbs. I want the article to sound like a human wrote it and not plagiarized or AI wrote it.

Words to exclude: I want you to avoid using words and phrases that are commonly used in AI generated content, such as: "delve", "world of", "realm", "isn't just about", "wasn't just about", "it's about", "it's not just about".

SEO Keywords: Before giving title suggestions and an outline, I want you to generate a list of 15 of the strongest SEO keywords on this topic. Consider the target audience and how they might search Google for topics that would lead to this article. These keywords will be used to create the title and the outline headings.

Outline Format: When creating the outline, I want each of the section headers to be a heading, followed by the bullet points as an unordered list for each section. I want the format to be easy to copy and paste directly into WordPress. I want the last section to be "Final Thoughts"

Title Suggestions: I want any article title suggestions to be a single phrase without the use of a colon. If you are going to include a colon, it must be for a really good reason and the title must be your absolute best options.

Target Audience:

Topic of Article:

Description:
```


## Generating and Choosing a Title

```
Generate a list of alternative titles that do not contain any colons (:)
```

```
I choose this title:

```

## Editing Outline

Follow-up with recommendations for edits to the outline. This is a free flow prompt and there is no secret to it. Just provide the feedback on how you want the outline to be changed.

```
Here's some feedback on the outline:

```

## Composing the Article from the Outline

### Setup

Give praise for the outline and setup the agent with context on how to write as a human.

```
This outline looks great!
When it comes to writing using A.I., two factors are crucial, perplexity and burstiness. Perplexity measures the complexity of text and burstiness compares the variations of the sentences. Humans tend to write with greater burstiness. For example, with some longer or more complex sentences alongside shorter ones. A.I. sentences tend to be more uniform. Therefore, when writing the following content, I am asking you to create, I need it to have a good amount perplexity and burstiness. In your next response, do not re-write anything, just respond to my question.
Do you understand?
```

Remind the agent of the style preferences

```
Remember to keep the paragraphs short and concise with 2-3 sentences each. Remember to write in a conversational tone yet be professional and speak in the 1st person singular ("I", not "we") and speak directly to someone in my target audience, but don't address them by name. However, treat this like an informal article and not an informal chat.
Also remember that it's very important to exclude the words and phrases in my exclusion list.
Use the dependency grammar linguistic framework rather than phrase structure grammar for the output. The idea is that the closer together each pair of words you’re connecting are, the easier the copy will be to comprehend.
Let's move on to writing the first section.
```

### Section Iteration

Iterate over each section in the outline, giving praise for quality work and suggesting edits.

#### Humanization

After the section edits have been applied, run it through an AI detection software. If the content is marked with 30% or more, use this prompt to re-write the section.

```
Using the concepts written previously, re-write this with a high degree of perplexity and burstiness to sound like a human wrote this and not an AI.
```

If you find that the AI detection tool isn't giving you a more human result, then remind it of the [setup](#setup) again.

#### Remove Undesired Words and Phrases
There may be a need for additional edits to remove undesired words and phrases.

```
Re-write this to sound more human and less AI and plagiarized, removing the following words and phrases: delve, world of, realm, isn't just about, wasn't just about, it's about, it's not just about
```

#### Inform with Edits
Use this prompt if you've provided edits outside the chat, to inform the agent of how you would like to have other content written.

```
Below is the section with the edits I made. Please explain to me the differences in what you have provided and the edits I made. I want you to apply the concepts to future sections.
Edit:

```

#### Praise and Continue

```
That is a great section. Keep up this quality. Let's move on to the next section titled:

```
or for items in a listicle:
```
That is a great item. Keep up this quality. Let's move on to the next item titled:

```
or simply:
```
Let's move on to the next section titled:

```

## SEO

### Keywords
```
Generate a comma-separated list of 30 SEO keywords and exact phrases in this article. Also, generate a second comma-separated list of 30 SEO keyword opportunities for this article. I want the words and phrases to be in plain text and not contain any double quotes. There is no need for the numbered list. You can just provide the list of words as a string with commas separating each keyword or phrase
```

### Meta Description
```
Write a meta description for this article. I want the character count to be as close to 160 without exceeding that hard limit. Please count the characters before suggesting a meta description. I also wish the meta description contained 1 or more of the abovementioned SEO keywords.
```

## Wrap-up

### Generate a TLDR

```
Smart Brevity Rules:
1. Shorter is better; A one-syllable word is more powerful than a two-syllable word is more powerful than a three-syllable word.
2. Deploy strong words; A strong word is vivid, concise, and something you can see and real.
3. Purge weak words; If you wouldn't say it at a bar or the beach, kill it. Do not use words that make you sound smart.
4. Avoid foggy words; Say what is happening and avoid words like 'could', 'may', and 'might'. Tell me what is really happening.
5. Use active verbs; active verbs bring action to your writing. Use this formula: [who] [doing what].
6. Embrace strong phrases; Short, crisp, punchy = memorable, clear, smart.
7. Check yourself; After writing, look at every sentence and see if you can write it with 1 fewer syllable with stronger words.
Do you understand?
```

```
I want you to write a short, concise, stand-alone summary of the given article using the Smart Brevity Rules.
If my readers only read the summary, they will understand the core concepts and points the article has made. Do not mention the article itself.
Keep the target audience in mind and write it as if you were conversing with a target audience member.
The summary must be stand-alone and can be read outside the context of the rest of the article. Do not mention the article itself.
The summary is not meant to be an introduction paragraph to the article.
Ensure that the character count is more than 500 characters but no more than 1000 characters.
If the summary length is out of range, adjust the content repeatedly until it is.
```

### Find Quotes
```
Help me come up with ideas for quotes on the topic of this article. I want to search for quotes in a search engine that I could use at the top of my article.
```

### Generate or Find an Image

```
Help me come up with ideas for images on depicting the topic of this article. I want to search for images in a search engine that I could use at the top of my article.
```

#### Alt Tag/Caption

Upload an image into "Image Alt Generation" chat

```
Help me name this image and develop a concise one-sentence alt tag to describe it. Be descriptive in the name of the image. I will also provide a caption for the image, and I want you to make the links open in a new browser tab. For the format, I want the caption to be the raw text.

Include the following topic in the alt tag:
Original Caption:
```

### Post-Publishing
```
I've scheduled the post. Keep the below information in mind for the rest of the chat.
Title:
URL:
Publish Date:
```

## Composing an Email

```
I want you to compose an email for my subscribed target audience. I want the subject to be attention-grabbing and curiosity-inducing. If you think emojis would add to that, add emojis as you see fit. Start by generating 10 of your best options for a subject line. Before each variation, I want you to think through a good subject line and elaborate on your reasoning before you write out the subject.
```

```
I chose the following for the subject line:

I want the body of the email to be conversational and intriguing to maximize the click-through rate. It should be in the first-person singular ("I" instead of "we"). I want the email to sound like I am addressing a single person in my target audience. I also want the paragraphs to be really short, with 1-2 sentences each. Remember any notes I made earlier about the email.

I want 2 calls to action: 1 call to action inline in the middle of a sentence or paragraph and another as a stand-alone button between paragraphs. I want you to indicate where the call to action and the button should be placed using square brackets and the text I should use for the call to action, e.g. [Call to action text], replacing "Call to action text" with your own text. Generate your best email body.
```

Iterate and provide edits as necessary.

```
Generate a list of 10 options for the call-to-action button's text. I want the call-to-action text to be written from the reader's perspective. For example, "I want more". Before each variation, I want you to think through what a good call-to-action text would be and elaborate on your reasoning before you write out the call-to-action text.
```

```
I choose the following 2 calls to action:
-
-

For each of the calls to action, I want you to add utm_source=newsletter, utm_medium=email, utm_campaign=announcements, and the utm_content will be the text of the CTA with spaces replaced with a plus "+" sign. I want you to provide those in plain text as the full URL
```

```
Generate 10 of your best preview texts for this email. I want the preview text to be a sneak preview of what's inside the email and the article. It must add to the curiosity sentiment. Before each variation, I want you to think through what a good preview text line would be and elaborate on your reasoning before writing the preview text.

At the end of this response, I also want you to add a code block with "Article: " followed by the article's title.
```

## Social Media

### LinkedIn Post

#### Post Without a Quote
```
I want you to create a LinkedIn post to announce this blog article to my followers and to attract new followers. I want the post to announce the article and ask a question relevant to the article for my target audience to engage and respond in the comments. Generate 15 of your best LinkedIn posts for this article and I want you to think through what a good post and question would be and elaborate on your reasoning.

Also generate a separate list of 15 of your best, relevant hashtags. Before each variation, I want you to think through what a good hashtag would be and elaborate on your reasoning before you write out the hashtag.

For the url, I want you to add utm_source=linkedin, utm_medium=post, and utm_campaign=engagement and show the URL in plain text.
```

#### Post With a Quote

```
I want you to create a LinkedIn post to announce this blog article to my followers and to attract new followers. I will have an image of a quote related to the article and I want the post to announce the article and ask a question relevant to the article for my target audience to engage and respond in the comments. Generate 15 of your best LinkedIn posts for this article. Also generate a separate list of 15 of your best, relevant hashtags. Before each variation, I want you to think through what a good post and hashtag would be and elaborate on your reasoning before you write out the post and hashtag. For the url, I want you to add utm_source=linkedin, utm_medium=post, and utm_campaign=quote and show the URL in plain text.
Here is the quote in the image: "" -
```

### LinkedIn Follow-up Post

```
Now, act as if it's been some time (a month or two) since I've published the article and announced it via my newsletter and social media. I would like to promote the article again on LinkedIn. I want the post to ask my target audience a related question to get them to engage by clicking through to the article and responding to my question in the comments. Generate 10 of your best LinkedIn posts for this purpose. Also generate a separate list of 10 of your best, relevant hashtags. Before each variation, I want you to think through what a good post and hashtag would be and elaborate on your reasoning before you write out the post and hashtag. For the url, I want you to add utm_source=linkedin, utm_medium=post, and utm_campaign=engagement and show the URL in plain text.
```

### Engaging Community Questions

```
I want to engage my community of my target audience by asking a related question in my private Facebook group. Generate 10 questions related to this article that I could ask my target audience. Before each variation, I want you to think through what a good question would be and elaborate on your reasoning before you write out the question. Each question must be less than 132 characters.
```

```
I like this set of questions, but I want them to be more concise and less than 132 characters:

```

### Facebook Group

```
I want to engage my Private Facebook Group. Act as if the article has already been posted for months. I want to create a medium sized Facebook post, highlighting the key points in the article and ask my group members an engaging question. I also want to include a link to the article in plain text. Before writing the post, I want you to think through what a good post is and elaborate on your reasoning for you write it out. Also provide a list of 10 alternative questions thinking through what a good question would be and elaborate on your reasoning before you write out the question.
For the url, I want you to add utm_source=facebook, utm_medium=post and utm_campaign=fb-group-engagement and show the URL in plain text.
```

### Engagement w/ Posts
```
I have posted on social media with a link to my article on the topic below and a question. I now want to engage with my own post to see if I can get the conversation started. How would you best answer this question to elicit other responses.
The topic is:
The question is:
```
