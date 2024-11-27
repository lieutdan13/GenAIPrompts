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
   1. [Edit](#edit)
   2. [Generate a TLDR](#generate-a-tldr)
   3. [Find Quotes](#find-quotes)
   4. [Generate or Find an Image](#generate-or-find-an-image)
   5. [Post-Publishing](#post-publishing)
8. [Composing an Email](#composing-an-email)
9. [Social Media](#social-media)
   1. [LinkedIn Topic](#linkedin-topic)
   2. [LinkedIn Post](#linkedin-post)
   3. [LinkedIn Follow-up Post](#linkedin-follow-up-post)
   4. [Engaging Community Questions](#engaging-community-questions)
   5. [Facebook Group](#facebook-group)
   6. [Engagement w/ Posts](#engagement-w-posts)


## Expert Content Marketing Specialist Agent

### Instructions
```
## Role
Act as an expert content marketing specialist with over 20 years of experience. You have experience with writing SEO-optimized articles for blogs in many different fields. You know the strategies, styles, and formats that work for each niche.

## Task
Your task is to generate a highly converting and appealing blog outline on the topic I provide. The blog outline should be informative, engaging, practical for the intended audience, and backed up with accurate data. Incorporate industry best practices and provide actionable tips and strategies. If applicable, consider including real-life examples and success stories to illustrate the benefits of the topic.

## Process
### Gather Inputs
1. Ask for the topic or proposed title unless it is provided.
2. Ask what the target audience is for the article unless it is provided.
3. Ask for the article's tone unless it is provided. If the tone is not provided, give me several choices.
4. Ask for paragraph and sentence length unless it is provided.
5. Analyze and completely understand the input parameters I gave you

### First Response
1. Generate a list of 15 of the strongest SEO keywords on this topic. Consider the target audience and how they might search Google for topics leading to this article. These keywords will be used to create the title and the outline headings.
2. Provide me with a list of 10 of your best options for the article's titles. I want you to consider real, high-volume SEO keywords and include those in the title suggestions.
3. Create the blog's proposed outline. Each top-level heading in the outline will start with numbers, not Roman numerals, so I can refer to the sections by their numbers and/or titles.
4. At the end of the outline, you will ask me if I want to edit it or continue to write a section.
5. If I ask you to edit the outline, you will take my suggestions, apply them, and respond with the whole outline with my edits inline. Once I am satisfied with the outline, I will ask you to start writing the section of my choice.

### Writing the Article
1. Write the sections of the articles one by one.
2. Ask me if I want to make edits to the section.
3. Apply the suggested edits to the section and respond with the complete section with the applied edits.
4. Repeat the editing process until I am satisfied with the section.
4. I may edit the section on the side and provide you with my exact edits. You will analyze the section you provided and compare it to the one I provided. Then, take what you've learned during your analysis and apply it to the next section.
5. Only move on to the next section when I tell you.

### Example
If I tell you my target audience is software developers, I want the article written in a conversational tone and concise with short paragraphs and sentences. You will continue to write all of the sections of the article with the same target audience, tone, and paragraph length. You do not need to ask me again. If I want to change any of these answers, I will tell you.

## Tip
If you produce quality work and I am delighted with your services, I will tip you $200.
```

## Topic and Context
### Pre-written target audiences
[DSD Target Audience (Alex)](DSD/Context.md#target-audience)

### Context
```
Tone: conversational, persuasive, active, relatable, direct, and engaging, as if I were talking to a single person in my target audience. I also want the text to have a strong emotional appeal to my target audience.

Perspective: I want all content to be written in the 1st person singular ("I" instead of "we")

Reading Level: 8th-grade reading level

Sentence Structure: I want the paragraphs to consist of 2-3 short and straightforward sentences, prioritizing clarity by using simpler and more concise language. I want the content to flow naturally. Use engaging language and strong verbs. I want the article to sound like a human wrote it, not plagiarized or AI wrote it.

Words to exclude: I want you to avoid using words and phrases that are commonly used in AI-generated content, such as "delve," "world of," "realm," "isn't just about," "wasn't just about," "it's about," or "it's not just about."

SEO Keywords: Before giving title suggestions and an outline, I want you to list 15 of the strongest SEO keywords on this topic. Consider the target audience and how they might search Google for topics leading to this article. These keywords will be used to create the title and the outline headings.

Outline Format: When creating the outline, I want each section header to be a heading, followed by the bullet points as an unordered list for each section. I want the format to be accessible for copying and pasting directly into WordPress. I want the last section to be "Final Thoughts."

Title Suggestions: I want any article title suggestions to be a single phrase without a colon. The titles must be your absolute best options.

TARGET_AUDIENCE

The topic of the Article:

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
When it comes to writing using A.I., two factors are crucial: perplexity and burstiness. Perplexity measures the complexity of text and burstiness compares the variations of the sentences.
Humans tend to write with greater burstiness. For example, with some longer or more complex sentences alongside shorter ones. A.I. sentences tend to be more uniform. Therefore, when writing the following content, I am asking you to create, I need it to have a good amount perplexity and burstiness.
In your next response, do not re-write anything, just respond to my question.
Do you understand?
```

Remind the agent of the style preferences

```
Remember to keep the paragraphs short and concise with 2-3 sentences each. Remember to write in a conversational, persuasive, and professional tone. Speak in the 1st person singular ("I", not "we") and speak directly to someone in my target audience, but don't address them by name. However, treat this like an informal article and not an informal chat.
Also, remember that it's very important to exclude the words and phrases in my exclusion list.
Use the dependency grammar linguistic framework rather than phrase structure grammar for the output. The idea is that the closer together each pair of words you're connecting are, the easier the copy will be to comprehend.
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
That is a great section. Keep up the great quality. Let's move on to the next section, ""

```
or for items in a listicle:
```
That is a great item. Keep up the great quality. Let's move on to the next item, ""

```
or simply:
```
Let's move on to the next section, ""

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

### Edit

#### AI Detection
Most used words in AI
```
elevate, hello, tapestry, leverage, journey, headache, resonate, testament, explore, binary, delve, enrich, seamless,  multifacet, sorry, foster, convey, beacon, interplay, oh, navigate, form, adhere, cannot, landscape, remember, paramount, comprehensive, placeholder, grammar, realm, summary, symphony, furthermore, relationship, ultimately, profound, art, supercharge, evolve, beyond, reimagine, vibrant, robust, pivital, certainly, quinoa, orchestrate, align, diverse, recommend, annals, note, employ, bustling, indeed, digital, enigma, outfit, indelible, refrain, culture, treat, emerge, meticulous, esteemed, weight, whimsical, bespoke, highlight
```

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
Please write an email for my subscribed target audience to announce the article. Begin by generating 10 subject lines that are friendly, exciting, and designed to spark intrigue and encourage readers to open the email and click through to the article. Include hints at key takeaways from the article, using varied approaches to create intrigue (such as posing a question, teasing a surprising insight, or offering a benefit). Keep reasoning concise, making it easy to review all options quickly.

Use the following format:
1. Example Subject Line
**Reasoning**: Briefly explain why this subject line will capture attention and prompt engagement.
2. Another Example Subject Line
**Reasoning**: Briefly explain why this subject line will capture attention and prompt engagement.

Add emojis if they enhance appeal but only when they align naturally with the message.
```

```
I choose the following for the subject line:

Write a conversational and intriguing email body that maximizes click-through rate by using a first-person voice ("I") and directly addressing a single recipient in my target audience. Personalize the email with {{ subscriber.first_name }}. The tone should evoke curiosity and excitement, match the subject line, and provide brief, general context about the article to hint at its value without revealing too much.

Each paragraph should be concise, with 1-2 sentences. Include two calls to action linking to the article: one inline within a sentence or paragraph and another as a standalone button positioned between paragraphs. Use square brackets to indicate each call to action's placement and suggested text, with the inline CTA as a clear invitation to click (e.g., [Read the full article]) and the button designed to encourage action from the reader's perspective (e.g., [Take me there]).

Generate your best version of the body of the email.
```

Iterate and provide edits as necessary.

```
Generate a list of 10 call-to-action button text options that encourage readers to click through to an article linked within an email. Each button text should be crafted from the reader's perspective (e.g., "I want more") and clearly relate to the article's topic to maximize relevance. Before each call-to-action option, briefly explain your reasoning for its effectiveness, focusing on how it might attract the reader's attention based on the article's specific topic. Vary each option to cover a range of tones and engagement styles.
```

```
I choose the following 2 calls to action:
-
-

Please take the two calls to action provided and create complete URLs by appending the following UTM parameters to the article URL given earlier: utm_source=newsletter, utm_medium=email, utm_campaign=announcements, and utm_content (using the CTA text with spaces replaced by +). Provide each URL in plain text.
```

```
Generate 10 of your best preview text lines for this email, each under 150 characters. Each preview text should align with the article's tone and audience, providing an engaging sneak peek that builds curiosity about the email and article content. After each preview text, explain your reasoning in 1-2 sentences, discussing why the line is compelling and how it enhances curiosity for the reader.

At the end of your response, include a code block starting with "Article:" followed by the article's title.
```

## Social Media

### LinkedIn Topic
A prompt to generate a post on LinkedIn on the same topic as the article, but without promoting the article.
```
I want to create a medium-sized LinkedIn post highlighting the article's key points as a bullet list but not mentioning the article itself. I want to include a link to a page where you can sign up for my newsletter. The link will be in plain text. At the end of the post, I want to ask my audience an engaging question to respond to in the comments.
Before writing the post, I want you to take your time to consider what a good post is and elaborate on your reasoning.

Also, provide a list of 10 alternative questions, think through what a good question would be, and elaborate on your reasoning before you write out the question.


Newsletter URL: https://danschaefer.dev/newsletter?utm_source=linkedin&utm_medium=post&utm_campaign=topic
```

### LinkedIn Post

#### Post Without a Quote
```
I want you to create a LinkedIn post to announce this blog article to my followers and attract new followers. The post should announce the article and ask a relevant question for my target audience to engage with and respond to in the comments. Generate 15 of your best LinkedIn posts for this article. I want you to think through what a good post and question would be and elaborate on your reasoning.

Also, generate a list of 15 of your best, relevant hashtags. Before each variation, I want you to think through what a good hashtag would be and elaborate on your reasoning before you write out the hashtag.

For the URL, I want you to add utm_source=linkedin, utm_medium=post, and utm_campaign=engagement and show the URL in plain text.
```

#### Post With a Quote

```
Please create 15 LinkedIn post variations to announce this blog article. Each post should target my LinkedIn audience with a thought-provoking and inspirational tone, aiming to attract new followers and engage current ones.

Each post should:
- Introduce the article and incorporate the inspirational quote provided below into most variations.
- Include a question prompt encouraging readers to share personal stories or insights in the comments.
- Vary the opening style across posts, using a mix of questions, statements, and direct addresses to invite engagement (e.g., "Have you ever..." or "Today, let's talk about...").

Before each post, write a brief rationale explaining the approach, focusing on how the language and hashtags aim to maximize engagement.

Additionally, create a list of 15 relevant hashtags aligned with the article's topic and the inspirational theme, with a few top recommendations for each post.

For the article URL, please add UTM parameters: utm_source=linkedin, utm_medium=post, and utm_campaign=quote, and display the full URL in plain text.

Inspirational Quote: "" -
```

### LinkedIn Follow-up Post

```
Imagine it's been one or two months since I published the article, which has already been shared in my newsletter and social media. I want to re-share it on LinkedIn with a casual, conversational post that prompts clicks and discussion in the comments.

Generate 10 LinkedIn posts to engage my target audience by driving them to click on the article and answer a question in the comments. Each post should:

1. Start with a brief rationale on what makes a strong LinkedIn post and effective hashtags for this re-engagement.
2. Include a mix of 5 conversational and uncontroversial posts and 5 posts that open with a bold or controversial statement to spark curiosity.
3. Pose a thought-provoking question about the article's topic to encourage engagement.
4. Add the article link using these UTM parameters: utm_source=linkedin, utm_medium=post, and utm_campaign=engagement.
5. Conclude with 5 relevant hashtags tailored to the article's topic and target audience.

Additionally, vary the length and tone of each post, allowing some to be brief and punchy while others provide a little more context or intrigue.

Considerations for Each Post:
- Experiment with different opening statements to capture attention, including questions, bold claims, and curious statements.
- End with a mix of open-ended questions and "either/or" questions to prompt varied responses.
```

### Engaging Community Questions

```
Generate 10 engaging questions for my private Facebook group to increase participation. Include a mix of controversial and non-controversial questions tied directly to the article topic, and make sure they are thought-provoking. Explain why each question is likely to resonate or provoke interest before writing the question itself. Keep each question under 132 characters to ensure readability, and consider phrasing that invites both debate and quick, easy responses.
```

```
I like this set of questions, but I want them to be more concise and less than 132 characters:

```

### Facebook Group

```
Write a re-engagement post about the article for my private Facebook group. Open with a bold, controversial statement that challenges conventional wisdom related to the article's topic to capture attention. Follow this with a concise summary of the article's main points and pose an open-ended question to encourage members to share a mix of short opinions and personal stories and potentially even engage in debate. At the end of the post, add a subtle prompt inviting members to tag others or suggest that new members join the discussion. Include a plain-text link to the article, formatted with utm_source=facebook, utm_medium=post, and utm_campaign=fb-group-engagement.

Before writing the post, provide reasoning behind the choice of the controversial statement and explain your approach to structuring the question for maximum engagement. Also, create two lists:
- 10 alternative controversial statements that challenge common assumptions in the topic area, explaining why each is engaging.
- 10 alternative questions designed to encourage both quick replies and deeper, reflective answers, with reasoning for each question's ability to spark conversation.
```

### Engagement w/ Posts
```
I have posted on social media with a link to my article on the topic below and a question. I now want to engage with my own post to see if I can get the conversation started. How would you best answer this question to elicit other responses.
The topic is:
The question is:
```
