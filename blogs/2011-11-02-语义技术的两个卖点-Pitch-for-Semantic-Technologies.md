语义技术的两个卖点 Pitch for Semantic Technologies
---
    
> Categories: 语义网  
> Time: 2011-11-02  
> Original url: <http://baojie.org/blog/2011/11/02/pitch-for-semantic-technologies/>
    
很多时候遇到质疑语义技术的人的，要废很多口舌解释什么是语义技术，以及为什么它比X技术好。这里X可以是数据库，信息检索，一阶逻辑，等等。这里写两个我常用的论证备用。

【对CS背景的人】为什么你要用数据库呢？其实如果你有文件系统，所有数据库系统能做的事，在文件系统上都能做。我见过很多很棒的数据应用，用很多技巧(workaround)，直接在文件系统上更高效率地实现了数据库的功能。问题是，如果100个优秀的程序员来设计这样的应用，大概会有100种不同的数据管理方法。对大多数人，大多数应用，没有必要这样重新发明轮子。数据库提供了一种通用的数据管理解决方案：尽管大多数数据库系统本身还是基于文件系统的，但是它包装和抽象了数据建模、查询、索引、读写的方法，不再需要100种不同的技巧。语义技术和X技术比，就好象数据库之于文件系统，提供了一个更高层次的抽象，长远看，降低了开发和维护的成本，提高了系统间的可交互性，也避免了重新发明轮子。

【对非CS背景的人】你为什么要用手机？其实你在手机上可以做的事，在电脑上都可以做的，还可以做得更好。问题的关键，不在于手机（或者电脑）能不能做这个，能不能做那个，而在于能有多方便，效率怎么样。我们很少会看到有人抱着笔记本带着耳机在大街上和人家skype，不就是这样不方便吗！语义技术也是一样，它和X技术比，最大的卖点还不是能做更多的事（尽管我认为是这样），而是可以更方便地做。【如果遇到特别较真的，继续说】当然，第一代手机也是很笨重、很贵的，不过那时候的电脑也更笨重、更贵。第一代火车还跑不过马呢。火车、手机的潜力，大家现在都看到了；语义技术的潜力，也是类似的。

参考

- [Making the Argument for Semantic Technologies](http://www.mkbergman.com/974/making-the-argument-for-semantic-technologies/)
- [Excecutive Briefing on Linked Data](https://www.youtube.com/watch?feature=player_embedded&v=sjt5ZzXBlLQ) （YouTube Video）
- [What is the Semantic Web? (for a general, non-technical audience)](http://semanticweb.com/semantic-web-pitch-of-the-week_b17527) by Sandro Hawke
- [The Personal Data Locker Vision Video](http://thepowerofpull.com/pull/the-personal-data-locker-vision-video) by David Siegel
- [Semantic Web Enterprise Elevator Pitch](https://www.youtube.com/watch?v=5WugA0t4L54)

More on Elevator Pitch: <http://semanticweb.com/category/elevator-pitch>

P.S. 2011-12-07 (原文是我2011-04-30的话)：我自己对我自己的一个“反驳”

> 我也听W3C的[Sandro Hawke](https://www.w3.org/People/Sandro/)说过这个观点。就是数据交换，数据集成，其实每个公司都在做，每个公司都在重新发明轮子。那为什么不用一个标准来做呢？RDF就是这样一个标准。这个我同意。如果良好的数据已经有了，RDF应该是一个不错的选择。可是这个前提，往往不成立，就是数据杂乱，本身就不好结构化；或者，是数据库的那种结构化。这时，RDF就不那么吸引人了。重复上面的比喻，连路都没有的地方，要的不是轮子，而是腿，各种各样的腿。各种机器学习和自然语言理解的方法，就是这种腿。


P.S. 2 2011-12-08 另一个pitch，参《[与数据与时俱进](http://www.baojie.orghttp/baojie.org/blog/2011/12/09/data-evolving-model/)》     
    