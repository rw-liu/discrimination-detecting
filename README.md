# discrimination-detecting
Final project for the Building AI course


## Summary

In the Chinese internet community, many individuals tend to use offensive statements, especially regarding gender and racial discrimination. Given the complexity of the Chinese language, I believe AI can be applied to address these issues, tailored for the Chinese online environment.

## Background

Chinese is extremely complex, especially with some commonly used characters and vocabulary. There's a significant amount of gender-discriminatory content that even Chinese speakers find challenging to recognize. My idea differs from the current content moderation AIs. I aim to identify discriminatory content stemming from the language itself and alert users to avoid using it.

The primary problems this AI project addresses are:

* The prevalent occurrence of offensive statements on the Chinese internet.
* Due to the complexity of the Chinese language, there's a lack of effective tools to identify and handle these statements.
* Comments on social media and forums involving gender and racial discrimination.

Personal motivation: I believe that everyone deserves to browse the internet in an environment free from discrimination.

This topic is crucial as fostering a respectful and friendly online community is essential for encouraging positive interactions and mutual understanding.

## How is it used?

Websites and social media platforms can integrate this AI tool:

* As users post content, the AI will automatically scan and flag offensive statements.
* Flagged content can be automatically hidden or sent to moderators for review.
* Users might receive feedback on the content they've posted, encouraging more positive interactions.

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Data will be sourced from public postings on Chinese social media and forums.

AI methods:

Deep learning text classification models to identify offensive statements.
Sentiment analysis to determine the emotional tone of the text.

## Challenges

* Users might find ways to bypass the AI, phrasing their offensive content differently.
* Due to the complexity and context variation in the Chinese language, there could be false positives or false negatives.
* Ethical considerations:
    * Respecting user privacy by not storing personal data.
    * Ensuring the AI's decision-making process is transparent and devoid of biases.
* The history of Chinese characters is extremely long, and the nation's and culture's history is also intricate. To determine whether a character or term is discriminatory, one needs to trace back and consult numerous ancient texts. For modern AI methods, these complexities are very challenging to recognize.

## What next?

Implement more advanced technologies to improve detection accuracy.
Collaborate with more social media platforms to apply the tool extensively.
Collect user feedback for continuous model optimization.
Find more girl talents to discuss.

## Acknowledgments

* Inspired by the voices on the internet that face discrimination.
* Utilizing NLP research published by OpenAI and other organizations.
* ...
