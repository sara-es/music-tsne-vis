<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.5.1/katex.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/github-markdown-css/2.2.1/github-markdown.css"/>

This is a small report for my MATH48061 Multivariate Statistics course. For now I've only uploaded a couple plots.

Music can be said to be more than a collection of sounds. Perhaps we can say that one song sounds similar to another because of a melody or collection of instruments used, but describing exactly *how* different say, Joni Mitchell's "Blue" is from David Bowie's "Starman" can be quite difficult. In this report I try a technique called t-distributed Stochastic Neighbor Embedding (t-SNE) to try to visualise the similarities of songs from my music library. Such a technique could be interesting as a visual starting point for e.g. how services such as YouTube suggest similar songs. It was found that the algorithm was very sensitive to initialisation parameters, and while results could perhaps be improved by higher resolution reduction of the song data, the generated plots did display some expected clustering of songs.

[Full report](Assessment2-Summerton.pdf)

[Main plot](plot_cluster_f.html)

[Fewer songs](plot_cluster_small3.html)

[All songs](plot_cluster_all.html) (CAREFUL: 4178 data points!) 


This project was heavily inspired by [Alex Clarke's Music and Machine Learning](https://sites.google.com/view/informationcake/music/machine-learning) ongoing project, whose code was helpful.
