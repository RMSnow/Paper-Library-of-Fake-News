# Notes

## Conclusions

### Social Science

**A Study On The Factors Affecting The Behavior Of Spreading Online Rumors: Focusing On The Rumor Recipient's Emotions. PACIS 2011.**

- 社会心理学(Social Psychological Theory)：Congnitive Emotion Theory, Dual Process Theory。
- `LITERATURE REVIEW` 一节中，关于`Source Credibility`的探讨：交流者本身的可信度，决定了它们所讨论话题的可信度；以及关于`Prior Belief`、`Prior Attitude`。
- 谣言的传播是由于人们主观的情绪因素（Emotional Factor）、感知因素(Congnitive Factor)。
- 情绪过程（Emotional Process）指的是被外界引发的情绪；感知过程（Congnitive Process）指的是人们对谣言相关信息的处理。
- 情绪会直接促进人们接下来的行为。
- Dual Process Theory 分为信息影响、一致性影响。信息影响：人们本身对事实（信息的真实性）的判断；一致性影响：人对群体的趋同性，比如很容易被群体的意见所左右。

**The spread of true and false news online. Science 2018.**

- 信息中的**Novelty**因素能够吸引人的注意力，影响决策，促进信息分享。
- 可以通过比较**情感内容**，来衡量用户对于新闻信息的感知。

### Data Science

**Information Credibility on Twitter. WWW 2011.**

- 对可信度影响较大的因素有：
  - 人们的反应（reaction）、用户在讨论话题时的情绪（emotion）。例如：他们是否使用一些观点性的表达方式（opinion expression）来表达特定的（positive/negtive）情感。
  - 用户对信息的确定程度（certainty）。例如：他们是否会质疑当前的信息。
  - 新闻所引用的外部资源（external resources）。如URL等。
  - 用户的特点（characteristic）。如粉丝数、关注数等。
- 基于情感的feature（sentiment-based）很重要。如：负面情绪词（negative sentiment）、感叹词（exclamation mark）很接近树模型的根结点。
- 观点（opinion）对于此任务很重要，其可以检测出公众对当前事件可信度的认识（perception）。

**Detecting Rumor Patterns in Streaming Social Media. Big Data 2015.**

- 在「**支持；反对；质疑**」这三种**态度（观点）**中：对于真实新闻，表示支持的人数更多；对于谣言，表示反对、质疑的人数更多。
- Rumor与Truth相比，其独有的Patter，比如 `Deny->Question->Question`。

**The spread of true and false news online. Science 2018.**

- 谣言的在人群中的**传播特点**：更远、更快、更深、更广；**政治类谣言**比其他谣言更具此特性。
- 谣言的**topic**更**新奇（novel）**，而人们更乐意分享novel的信息。
- 在**情感**方面：人们对于谣言的**评论**含有较多的fear、disgust、surprise，而对于真实新闻，则含有更多的anticipation、sadness、joy、trust；除了novelty，**情感因素**对于谣言也十分重要。

**Can Rumour Stance Alone Predict Veracity? COLING 2018.**

- `Mendoza et al. (2010)`的工作表明：对于真实新闻，人们90%以上的时间都在affirm；对于谣言，人们50%以上的时间都在challenge (deny, question)。

## Examples

**Detecting Rumor Patterns in Streaming Social Media. Big Data 2015.**

- 2010年智利地震，在Twitter上的信息传播

**The spread of true and false news online. Science 2018.**

> False rumors have affected stock prices and the motivation for large-scale investments, for ex-
> ample, wiping out $130 billion in stock value after a false tweet claimed that Barack Obama
> was injured in an explosion (7).

- 谣言影响**股市投资**

> Current work analyzes the spread of single rumors, like the discovery of the Higgs boson
> (13) or the Haitian earthquake of 2010 (14), and multiple rumors from a single disaster event, like the Boston Marathon bombing of 2013 (10).

- 谣言事件：科学研究（新发现）、自然灾害（地震）、恐怖袭击（波士顿马拉松爆炸案）、2016年美国大选（政治事件）

[315-央视也传谣](<http://www.sohu.com/a/129239849_164550>)

- 2017年中央电视台3·15晚会中所曝光的“无印良品部分进口食品产自日本核污染区”事件。上海国检：未发现无印良品有来自日本核污染区的产品。

## Resources

### Fake News

**The spread of true and false news online. Science 2018.**

- snopes.com
- politifact.com
- factcheck.org
- truthor-fiction.com
- hoax-slayer.com
- urbanlegends. about.com

### Others

- 情感分析

  **The spread of true and false news online. Science 2018.**

  - National Research Council Canada (NRC)

  - *Plutchik’s (31) work on basic emotion*