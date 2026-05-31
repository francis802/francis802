# Projects

A compilation of all my repositories on GitHub. Some may still be private, but I'll publish them once they're finished.

Master's projects (Artificial Intelligence) are listed first, then the bachelor's (Informatics and Computing Engineering).

---

## Master's in Artificial Intelligence (M.IA, FEUP)

| Field | Project | Description |
|---|---|---|
| Deep Learning | **[DeepFake-Detection](https://github.com/francis802/DeepFake-Detection)** | Discriminative **and** generative take on deepfakes using the DeepFakeFace dataset: CNN / ResNet-50 / EfficientNet detectors (~87% accuracy) and GAN / DCGAN / WGAN-GP face generators evaluated with FID. Built in PyTorch. |
| Computer Vision | **[Chess-Vision](https://github.com/francis802/Chess-Vision)** | Turns a photo of a physical chessboard into a digital twin: U-Net board segmentation, homography rectification, and YOLOv8 / YOLO11 piece detection mapped onto an 8×8 grid, rendered as a 2-D diagram. |
| Information Retrieval | **[Argument-Search-Engine](https://github.com/francis802/Argument-Search-Engine)** | A search engine over debate arguments on Apache Solr 9 with three retrieval modes, including semantic kNN via sentence-transformer embeddings. Ships a Flask web UI and a TREC-style evaluation pipeline (P@k, MAP, PR curves). |
| Natural Language Processing | **[Request-Detection-NLP](https://github.com/francis802/Request-Detection-NLP)** | Detects requests vs non-requests in open-source software messages: a Word2Vec + XGBoost / CatBoost baseline extended with fine-tuned transformers (RoBERTa, BERTweet, CodeBERT) and GPT. |
| Data Science | **[Health-Insurance-Prediction](https://github.com/francis802/Health-Insurance-Prediction)** | Imbalanced binary classification predicting health-insurance coverage, following CRISP-DM: benchmarked 10+ models and tuned a LightGBM with oversampling to optimize the minority-class F1 score. |
| Recommender Systems and SNA | **[Yelp-Recommender-SNA](https://github.com/francis802/Yelp-Recommender-SNA)** | Two-part study on the Yelp dataset: a sentiment-enhanced restaurant recommender (NLP + collaborative filtering) and full social-network analysis — centrality, Louvain / Leiden communities, and review-activity forecasting. |
| Dialogue Systems | **[Plato-Dialogue-System](https://github.com/francis802/Plato-Dialogue-System)** | Multi-agent reinforcement-learning dialogue experiments on the Plato Research Dialogue System, replicating a published collaborative-training setup and extending it to a custom Lisbon-Airbnb domain. |

---

## Bachelor's in Informatics and Computing Engineering (L.EIC, FEUP)

<table>
  <thead>
    <tr>
      <th>UC</th>
      <th>Project Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=2>AED</td>
      <td><a href="https://github.com/francis802/Timetable-Manager">Timetable Manager</a></td>
      <td>Project developed in C++ using several data structures such as queue, stack, list, vector, and binary search tree (having in consideration efficiency of the operations over the structures)</td>
    </tr>
    <tr>
      <td><a href="https://github.com/francis802/Airlines-Manager">Airline Manager</a></td>
      <td>Project developed in C++ using real datasets of Airline Graphs, and developing efficient traversal algorithms over it</td>
    </tr>
    <tr>
      <td> LDTS </td>
      <td><a href="https://github.com/francis802/Tetris-Runner">Tetris Runner</a></td>
      <td> Game developed in Java with a fusion of Tetris and platform games, with special emphasis on Test-Driven Development </td>
    </tr>
    <tr>
      <td> SO </td>
      <td><a href="https://github.com/francis802/Fork-Processes">Fork Processes</a></td>
      <td> Project developed in C for solving problems using parallel computing and inter process communication using a Token Ring </td>
    </tr>
    <tr>
      <td> BD </td>
      <td><a href="https://github.com/francis802/Hockey-Database">Hockey Database</a></td>
      <td> Database developed for the games of the Portuguese Hockey League of 2021-2022, using triggers to create a dynamic database on data deletion, change and insertion </td>
    </tr>
    <tr>
      <td rowspan=2>DA</td>
      <td><a href="https://github.com/francis802/Railway-Manager">Railway Manager</a></td>
      <td> Project developed in C++ using <a href="https://www.cp.pt/passageiros/pt">CP</a> Railway dataset, implementing Edmond's Karp algorithms of Maximum Flow </td>
    </tr>
    <tr>
      <td><a href="https://github.com/francis802/TSP-Solver">TSP Solver</a></td>
      <td> Project developed in C++ using real world map datasets, to create heuristics to solve the Travelling Salesman Problem </td>
    </tr>
    <tr>
      <td> LTW </td>
      <td><a href="https://github.com/francis802/heLpEIC">help.eic</a></td>
      <td> Trouble-Ticket Website developed in PHP, for students of L.EIC being able to address their doubts about university Curricular Units </td>
    </tr>
    <tr>
      <td> LCOM </td>
      <td><a href="https://github.com/francis802/Tower-Clash">Tower Clash</a></td>
      <td> Game developed in C using MINIX OS for LCOM, and taking advantage of IO devices manipulation such as: Timer, Keyboard, Mouse, Graphics Card and Real-Time Clock </td>
    </tr>
    <tr>
      <td> ESOF </td>
      <td><a href="https://github.com/francis802/Rate-IT">Rate IT</a></td>
      <td> Mobile App developed in Flutter and using Firebase as Backend Service for rating and reviewing companies, courses and events present in <a href="https://www.itjobs.pt/"> ITJobs </a> API </td>
    </tr>
    <tr>
      <td rowspan=2>RCOM</td>
      <td><a href="https://github.com/francis802/rcom2324/tree/main/lab1">File Transmit</a></td>
      <td>Project developed in C about transferring a file between two computers, following a protocol from the scratch that takes into account problems of timeout, noise and duplication of data frames</td>
    </tr>
    <tr>
      <td><a href="https://github.com/francis802/rcom2324/tree/main/lab2">TCP Downloader</a></td>
      <td>Project consists of constructing an internet network to access the internet from the scratch, and transferring a file using TCP</td>
    </tr>
    <tr>
      <td rowspan=2>PFL</td>
      <td><a href="https://github.com/francis802/Apart-Game">Apart Game</a></td>
      <td> Game developed in Prolog for the UC of Functional and Logic Programming. The <a href="https://kanare-abstract.com/en/pages/apart">Apart Board Game</a> can be played by two players, with one player against a bot, or just be played by two bots. </td>
    </tr>
    <tr>
      <td><a href="https://github.com/francis802/Code-Compiler">Code Compiler</a></td>
      <td> Compiler made in the UC of Functional and Logic Programming. This project was developed in Haskell, and it's composed of the full procedure from parsing a string, until the execution of the code by the assembler </td>
    </tr>
    <tr>
      <td>LBAW</td>
      <td><a href="https://github.com/francis802/Travellers">Travellers</a></td>
      <td>Social Network made in Database and Web Applications Laboratory. Travellers aims to be the global hub where wanderlust meets community. We envision a world where individuals share, connect, and explore together, creating an inclusive space for unforgettable travel experiences. Used: Laravel, AJAX, Pusher, Mailtrap to make website dynamic</td>
    </tr>
    <tr>
      <td>COMP</td>
      <td><a href="https://github.com/francis802/JavaMM-Compiler">Java-- Compiler</a></td>
      <td>Compiler made for a subset of Java. Used an ANTLR Grammar, AST, and the backend engines Ollir and Jasmin to compile a class to executable code. Also implemented a "-o" optimization for constant folding and constant propagation</td>
    </tr>
    <tr>
      <td>CGRA</td>
      <td><a href="https://github.com/francis802/Bee-Life">Bee Life</a></td>
      <td>Project made for the Graphic Computation class. This 3D graphics environment consists of a bee, moved by the player, which has to collect pollen and leave it in its hive. Used shaders</td>
    </tr>
    <tr>
      <td rowspan=2>CPD</td>
      <td><a href="https://github.com/francis802/cpd2324/tree/main/assign1">Matrix Benchmark</a></td>
      <td>Project about benchmarking different algorithms, programming languages and parallelizations, and taking conclusion about their impact on performance and cache usage</td>
    </tr>
    <tr>
      <td><a href="https://github.com/francis802/cpd2324/tree/main/assign2">Price is Right</a></td>
      <td>This project is an implementation of a Server which hosts different games of "Price is Right", with ranked or simple game options. Used concurrency to establish safe access to the server resources, virtual threads to minimize thread overhead, and expiration tokens to create a system of fault tolerance, where a player may return to the same place of the queue where he previously was.</td>
    </tr>
    <tr>
      <td rowspan=2>IA</td>
      <td><a href="https://github.com/francis802/SokobondAI">Sokobond AI</a></td>
      <td>Sokobond game developed for the Curricular Unit of Artificial Intelligence. Developed Artificial Intelligence Algorithms to solve 10 different levels, all with different complexities and new game mechanics</td>
    </tr>
    <tr>
      <td><a href="https://github.com/francis802/NASA-Asteroids">NASA Asteroids</a></td>
      <td>Machine Learning Models applied on a dataset provided by NASA, consisting on categorizing asteroids as Hazardous or Non-Hazardous for planet Earth. Applied different graphics to better see the data and predictions, like Correlation Matrix, Confusion Matrix, and Swarmplots. ML algorithms used: Decision Trees, Random Forest, Gradient Boosting, K-NN, SVM, Neural Networks, Logistic Regression, and Naive Bayes</td>
    </tr>
  </tbody>
</table>
