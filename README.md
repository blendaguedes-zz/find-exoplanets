<h1>Discovering Exoplanets Using Neural Networks</h1>


In 2009 the Kepler Space Observatory was launched by NASA, with the aim to answer the question: ”How frequent are other Earths in our galaxy?” [2]. The observatory is on its second mission since 2014, and had labeled more than 10, 000 possible exoplanets [3].

Kepler scanned 1,284 new exoplanets in 2016. As in 2017, there were more than 3,000 exoplanets confirmed in total (using all detection meth- ods, including ground-based ones). The observatory still works and keep on searching for other exoplanets [3].

Our goal with this project is to use the data collected by the Kepler Space Observatory during all these years and build a Neural Networks model solution that, given the characteristics collected by Kepler, is feasible to identify exoplanets.

<h3>Methodology</h3>

The machine used was a MacBook Pro 2017, with a Mac OS Mojave operating system, 500Gb SSD, RAM 16Gb, processor of 2.9 GHz Quad-Core Intel Core i7.
The programming language used was Python 3 and PyTorch [9] library was used to built the Neural Networks.

<h4>Data Base</h4>

The database was taken by the Kaggle <a src="www.google.com">[3]</a> platform. And the data cleaning was based in the work referenced in [10]. After that we have 7803 samples. It was divided in three parts where 70% was to training, 15% to validation and 15% to testing. The features were normalized using min-max scaling.
Finally we had 37 different characteristics to use as a input and a binary output.
