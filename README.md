# Biomorphic AI

D. O. Chergikalo,
denischergicalo@gmail.com

Человек постоянно учиться у природы: генетические алгоритмы, алго-ритмы нейросетей, роевой интелект и т.д.
Самые эффективные методы ИИ являются эффективным упрощением и моделированием процессов в природе.
Но к сожелению специалисты часто хорошо разбираются только в не-скольких моделях, об остальных они только слышали, от статей на другие темы у них разбегаються глаза и они все равно выхватывают только то что касаеться их темы.
Для того чтобы каждый смог раскрыть для себя такую нелегкую тему как биоморфный ИИ мы предлагаем формат иерархии : тема –> статья –> при-менение –> плюсы и минусы.

Для демонстрации того как это работает мы покажем описание положи-тельных применений связи алгоритмов с их бтологическими корнями.

БиоморфныйИИ 
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Расмотрение несколько вариантов вычислительного упрощения изначального алгоритма соблюдая соответствие биологическим корням|  Потенциальное увеличение эффективности| Возможное сужение области применения |
| Расмотрение нескольких вариантов как сделать алгоритм более подходящим к биологическим корням | возможность моделирования некоторых биологических процесов; Улучшение адаптивности алгоритма к «природным» данным | Возможное понижение эффективности |


## Abstract. 

In this chapter, we will consider modern advances in the field of AI develop-ment and their biological meaning. Critical cell reconstruction of the brain by the BlueBrain project is criticized. The direct presentation of some methods of AI as biological processes is also formulated, which, possibly, will make it possible in the future to improve these methods, or to make standard those modifications of which we will discuss. Using the terms of teaching neural networks, the teacher expresses the complex internal mechanisms of intuition and unconscious infor-mation processing. In addition, as a “game with reality” according to the Monte Carlo method, conscious thinking is modeled, including common sense and plan-ning. Based on the conducted analogies, improvements in AI are proposed that will make the complexity of his thinking similar in complexity to human and lead to the creation of a strong AI.

Keywords: Artificial Intelligence, Biomorphic AI, Artificial Intuition, Strong AI.

## Setting the scene
Artificial intelligence technologies are increasingly moving away from where they started — from modeling human behavior. Currently, quite a few people use processes associated with neural networks of the brain to implement software, and all funding depends on the specific tasks performed on time.
If to take into account the generally accepted point of view “Everything is complicated,” as well as bitter experience in this area (for example, two AI win-ters), then we have no choice but to accept status quo, and slowly make small steps improving existing algorithms in order to increase profit for various compa-nies by increasing the accuracy of methods.
But is the brain really so complex to simulate it as a black box? Below we de-scribe what technologies applicable to create humanoid AI have appeared recent-ly. But before that, we emphasize that the practical ideas of AI undergo the same evolution as the behavior and brain of animals.
Scientists are constantly improving old models, combining methods, experi-menting with their models, choosing the best ones, and when it comes to practice, those models are selected that are best suited for specific tasks, finding their niche, so AI ideas have even more similarities with biology than the researchers them-selves might suppose at first glance. In the next subsection, “The Parallel Path of Smart Technologies and the Recreating of Biological Processes,” we will discuss just that.

## The Parallel Path of Smart Technologies and the Recreating of Biological Processes

[Srivastava N, Hinton G, Krizhevsky A et al. (2014) Dropout: a simple way to prevent neural
networks from overfitting. J Mach Learn Res 15 (1):1929–1958](https://dl.acm.org/doi/10.5555/2627435.2670313)
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| отсеивание 20% - 30% нейронов|  Эффективность редко понижаеться и достаточно хорошо повышаеться| При сильном переобучении может не дать оптимальный результат |
| отсеивание 30% - 50% нейронов | Может хорошо повысить эффективность при сильном переобучении | Вероятность небольшого понижения эффективности |

As is well known, neural networks have recently undergone a period of inten-sive development. There are many intriguing parallels between artificial and natu-ral neural networks. An interesting example is dropout algorithm — random re-moval of neurons in an artificial neural network that helps to make the neural network more stable and reduces overfitting on the available data. The authors of that papers note that neurons during the dropout process can be compared with genes during sexual reproduction — only a certain part of them is realized in the descendant. Therefore, if an individual possessed good features, but these fea-tures were determined by a large set of genes, in other words, a whole large co-adaptation of genes, then this set is very likely to be passed on to the next genera-tion due to the random nature of their transmission, therefore only genes that themselves remain in nature benefit, or small sets of such genes.

Masters D, Luschi C (2018) Revisiting small batch training for deep neural networks.
https://arxiv.org/pdf/1804.07612.pdf . Accessed at 22 February, 2020.
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Виборка из 2-4 екземпляров| Иногда может дать более обобщеный; Устойчивый результат сравнительно с другими вариантами использования| Большее увеличение времени на эпоху; Риск получения неудволетворительного результата |
| Виборка из 4-16 екземпляров | Обычно имеет оптимум по времени обучения до конвергенции и оптимум в улучшение эффективности| Небольшое увеличение трат времени на эпоху |
| Виборка из 16+ екземпляров | Меньшее время на эпоху; Иногда, при не сильно чуствительных данных может дать оптимальный результат | Менее устойчывый результат |

The artificial neural networks that we program usually develop normally in iso-lation from the outside world. They have the opportunity to learn all the variety of information at the same time, without intermediate tests of performance. On the contrary, a person needs to develop gradually and immediately apply his knowledge in practice. Information appears in the brain in certain portions, hav-ing received which, it can immediately switch to using the knowledge gained. Nat-urally, these portions cannot describe the whole variety of information, so such training will constantly make random deviations from training based on complete information. But this turns out to be not even bad: if the portion of information (sample) has small deviations, then they will not allow to leave the region of the global minimum of error (corresponding to complete information), but at the same time they will help to leave the region of local minimums. 
In the field of artificial neural networks, this approach is called Small Batch Training, and its effectiveness is well described in the article. It also indicates that it is optimal to take a sample with sizes ranging from m = 2 to m = 32. In other words, even m = 2 may turn out to be the most effective option for a specific problem.
If we consider the approach described above from a social point of view, then Small Batch Training can be compared to lessons in schools where students are given information in portions, which allows them to change their unconscious ide-as about objects in accordance with new information. But first, the schools teach the most basic, and only then they give more and more complex information, meanwhile the AI should be able to learn on its own —that is, independently go from simple to complex.
In addition, new information or a tactical move made by a person is not al-ways immediately clear, therefore information is transferred from short-term to long-term memory at the end of the day - during sleep (because of which the most ordinary part of life can be well remembered if after it a bright event happened on that day). 
These two problems are partially resolved, which we will discuss later in the subsection “AlphaZero ideas as a basis for the AI algorithm”.
It is worth noting that convolutional neural networks are also quite close to real analysis in the human brain, although the biological implementation of filters that emit abstract objects is rather complicated. It is carried out not only through gen-eral training of the entire network (based on internal rewards for good work), but so that similar filters are applied at different places in the layer, self-organization within each layer is applied. If you create an AI model, then you need to develop a similar process of self-organization, so as not to reduce everything to a fixed set of filters. Therefore, as an approximation to real AI, we will use a conventional convolutional neural network, which will immediately train a finite number of fil-ters over the entire area.


Girshick R (2015) Fast R-CNN. In: The IEEE International Conference on Computer Vision
(ICCV), pp. 1440–1448.

общие минусы: не самый быстрый метод, сложная архитектура(сложнее обучать вместе с другими нейросетями)
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Локализация маленьких обьектов| работает достаточно хорошо|  |
| Локализация средних обьектов | работает достаточно хорошо|  |
| Определение границ обьекта | работает достаточно хорошо |  |

But for a person’s hearing and vision, different architectures are provided. On one hand, hearing is a sequential model of neural networks that leads from sen-sors to the analysis of complex sound signals and words, on other hand vision is divided into two directions: one leads to an analysis of the image itself, and the other leads to location where this image is.
This is fully consistent with the architecture this of one of the main neural net-work architectures for image detection.

Ren S, He K, Girshick R, Sun J (2015) Faster R-CNN: Towards Real-Time Object Detection
with Region Proposal Networks. In: Advances in neural information processing systems, pp.
91–99.

общие минусы: немного сложная архитектура(немного сложнее обучать вместе с другими нейросетями)
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Локализация маленьких обьектов| | работает не очень хорошо |
| Локализация средних обьектов | работает достаточно хорошо|  |
| Определение границ обьекта |  | работает не сильно точно |

A similar process always occurs in a person, when he, analyzing the image, can focus attention on only one thing. This process is closer to another of the main neural network architectures for pattern detection.


George D et al. (2017) A generative vision model that trains with high data efficiency and breaks
text-based CAPTCHAs. Science, 358(6368), art. no. eaag2612.
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Определение иерархии обьектов| работает достаточно хорошо| слишком долго работает из-за чего пока неэффективно применять к реальным изображениям |
| Распознавание обьектов системы обьектов | работает достаточно хорошо| работает только для системы простых обьектов |

In addition, a person has his own maxpool layer, but it works harder than choosing a maximum from several neighbors. There is a choice from an object-oriented structure, due to which an unconscious understanding arises where to choose an object. This corresponds to the self-organization described above, only for significant correlations with more distant neurons. However, if this choice is correctly implemented programmatically, then the programs become more re-sistant to deformation and changes in the picture that they analyze.
For example, Vicarious, an artificial intelligence company, has developed Re-cursive Cortical Network (RCN) technology for biologically plausible image anal-ysis. Their algorithm, unlike its predecessors, does not reduce accuracy when the text is deformed, and almost does not decrease when using various effects and styles to complicate the text and overlap it with other objects. This will be dis-cussed in more detail in the subsection “Overview of basic algorithms for AI and their achievements”.
About primary treatment for vision, hearing, etc. we will tell in “Primary pro-cessing of sensory signals”.
We believe that transferring the useful properties of natural neural networks to computer models is an optimal resource option, and we also assume that while maintaining the qualitative properties of the neural network, its other more com-plex properties are also preserved. Researchers have shown that RSN has many more complex properties that they consider to be similar to human ones.
It seems to us that the study of such computer models will help not only to create AI, but to simulate various brain diseases and to study their effect on AI, which may prompt researchers to solve real medical problems with the brain by studying them on the models.
Another example of the Recursive Cortical Network, mentioned earlier, made it possible to correctly guess Captha in 66.6% of cases, and after determining the style and additional training — 90%. Moreover, this network uses only 5000 ex-amples of resolved examples and a small number of layers. It simulates the work of the primary visual cortex. A description of the work and experiments with this neural network is given in this paper. What we called the connection with more distant neurons in this article is called the lateral connection..


## Overview of basic algorithms for AI and their achievements 

AlphaGo was the first program to defeat the professional, and even the best player in Go. But it was un-usual only because of the convolutional neural network as a function of evaluat-ing and determining profitable moves. Its algorithm could be compared with an intuitive assessment of the situation on the board by a person, i.e. with his trained unconscious appreciation. In combination with the Monte Carlo method, this al-lows successfully simulating the game thinking of a person (we’ll talk about this in more detail in the subsection “AlphaZero Thedes as a Base for AI Algorithms”)


AlphaGo Zero

The next version of the AlphaGo program, AlphaGo Zero, learned to train its intuition not on examples of other people's games, but on examples of games with itself. This not only saved it from dependence on external data, but also sig-nificantly improved the program. 


AlphaZero
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Самообучение техникам в настольных играх| выводит новые техники игры на которых могут поучиться люди| Сложность восприятие техник для непрофесионалов |
| Обучение на играх которые симулируют полезные модели | может дать новые методы конкуренции и продвижения| методы сложно понять полностью |
| Победы в играх | Опыт для чемпионов мира соревнования с очень сильным протвником, зрелищность на начальных этапах | После постоянных побед машин зрелищность падает |

AlphaZero is a program that, learning from scratch, has won all the people and the rest of the algorithms in chess, segos and Go. Go’s game runs on board 1919 and generates a huge number of options. Conventional algorithms were powerless and reached the maximum level of average amateur in Go. 
AlphaZero program can in a matter of hours learn to play any game and become the best in it. It itself adapt to the game, which makes it quite flexible and easily customizable to different types of games.


Beheshti Z et al. (2010) A Review of Emotional Learning And It’s Utilization in Control
Engineering. Int. J. Advance. Soft Comput. Appl., 2(2):191–208.
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Симулирование живых существ| Хорошая для симулирования небольшой группы простых животных| со сложностями описывает поведение умных жывотных; вычислительно сложная для симуляции большого количества особей|
| Моделирование эмоций | Хорошо симулирует эмоциональные реации жывотных и человека| не включает в себя планирование жывотными а уж тем более сознание |
| Динамическая адаптация | Вычислительно небольшая модель | Небходимость совмещать с более стабильными алгоритмами |

Those who are interested in the idea of modeling precisely neural networks with similar properties to real ones, as the closest of the classical general models, we suggest exploring the LSTM model and the rhythms in it, especially with regard to long-term information. But if we talk about the closest of the simply classical models, then we propose to consider the rhythms and similar biological character-istics for the BELBIC model.
The emotional component of learning is important for our model as it helps to filter and remember important information. Models of emotional brain training are called BEL models (Brain Emotional Learning). Unfortunately, at the mo-ment we do not know any complex models for emotional learning that would adapt to complex mechanisms of thinking.
The most advanced of these models is the BELBIC model (Beheshti et al., 2010). It has practical applications for real-time control systems, since it is com-putationally efficient and at the same time gives quite acceptable results (Package with BELBIC controller, 2020). It is similar to an RNN network, which pre-dicts the necessary action, which should be chosen, but has one big difference from it — the network learns directly during operation, thus constantly adapting to new conditions. Models of emotional thinking model the functioning of the limbic system and their relationship with other areas during emotional perception and memorization.



## Общие принципы Proposed Architecture

Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model 
https://arxiv.org/pdf/1911.08265.pdf

оющие минусы: нестабильное обучение, для того чтобы довести до найвисшего уровня уровня нужно чтобы был набор нейросетей-игроков повышающегося уровня сложности для того чтобы сама нейросеть смогла постепенно выиигрывая одного за другим дойти до пика возможного уровня
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Самообучение техникам в любых играх | выводит новые техники игры на которых могут поучиться люди| Сложность восприятия техник для непрофесионалов |
| Использование для получения новых лекарств в медицине | высокая скорость работы | Необходимоть безопасности и контролироля рисков |
| Ислользование  компьютерных или настольных играх | Опыт для чемпионов мира соревнования с очень сильным протвником, зрелищность на начальных этапах | После постоянных побед машин зрелищность падает |
| Симуляция поведения человека | Учитивает планирование и обучаеться правильно упрощать свое восприятие | Не учитываються особености человеческих эмоций и поведения |
| Симуляция других полезных моделей | может дать новые методы конкуренции и продвижения| методы сложно понять полностью |


Сам процесс выделения игры и “мыслительная” симуляция случайных игр с реальностью – реализован в улучшении AlphaZero – MuZero.
модель реальности в ней вкладывается в - hidden state – в нашей модели за нее отвечает “цифровой гиппокамп”.

## Multi-task learning



Zweig A, Weinshall D (2013) Hierarchical Regularization Cascade for Joint Learning. In:
Proceedings of the 30 th International Conference on Machine Learning, Atlanta, Georgia,
USA, 2013.Part 2, pp. 1074–1082.
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Определение иерархии информации| предотвращает переобучение, выделяет систему в информации| немного большее время, необходимость предворительной начальной группировке задач, субьективность выделяемой иерархии отношений|
| Взаимное улучшение качеств существующих нейросетей | Повышение стабильности, возможное повышение эффективности| необходимость найти нейросети обучение на схожых данных |

Описанный выше подход может найти полезные применения в области многозадачного обучения. Задачи обычно связаны друг с другом  - и объ-единяются в иерархию, подобный подход может дать большое улучшение. 

Jawanpuria, P., & Saketha Nath, J., (2012) A Convex Feature Learning Formulation for Latent Task Structure Discovery. http://icml.cc/2012/papers/90.pdf
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Определение иерархии информации| предотвращает переобучение, полностью самостоятельно выделяет систему в информации| большее время, субьективность выделяемой иерархии отношений|
| Разделение признаков в иерархии | наличие четкого графа указывающего на иерархию;Возможность эфективно дообучить алгоритм к новому отвлевлению без перестройки иерархии| Сложность єффективного расширения алгоритма на большое количество новых задач|

Даже если какую-то широкую тему не удается разбить на подразделы – задачи в рамках этой темы бессвязны относительно друг друга, в случае связанности она при правильном выделении структуры подзадач может разбиться.

Romera-Paredes et al. (2012) Exploiting Unrelated Tasks in Multi-Task Learning. Proceedings
of the Fifteenth International Conference on Artificial Intelligence and Statistics, PMLR
22:951-959
| Применение | плюсы | минусы |
|----------------|:---------:|----------------:|
| Взаимное улучшение качеств существующих нейросетей | Повышение стабильности, возможное повышение эффективности| Из-за штрафов на задачи разных груп, сильные взаимосвязи между групами задач могут нарушить работу алгоритма |


то даже в этом случае можно все равно получить хорошое улучшение общего обучения по сравнению с отдельным обучением для каждой задачи, как причину этого можно назвать более хорошие выделение абстрактного навыка анализировать который уже при различных умениях по разному актуализируется.

Argote L and Ingram P (2000). Knowledge transfer: A Basis for Competitive Advantage in
Firms . Organizational Behavior and Human Decision Processes. 82(1):150–169.

 Когда выделяется новое применение навыка(когда старые применения на нужную деятельность уже не работают эффективно) - то начинается определяться новое умение основанное на этом навыке - что можно рассмотреть как Transfer of knowledge когда область применения нового навыка схожая с той что была раньше  - то тогда используется близкое умение - но для которого делают слой интра-претации,  и это тоже можно рассмотреть как  вариант Transfer of knowledge. И как уже было сказано оба эти варианта взаимно дополняют друг друга.
