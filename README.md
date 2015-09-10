DL4J Release 0.4 Examples for Scala 
=========================

 This project is a simple Scala porting of [deeplearning4j-0.4-example](https://github.com/deeplearning4j/dl4j-0.4-examples).

The main purpose of this project is:

* Show example of how to use deeplearning4j Java API from scala

* Provide a sbt project template depends on DL4J


Every examples in this demonstration directly calls Java APIs of DL4J.
If you want to write codes in the scala manner strongly,
you should consider to use [deeplearning4s](https://github.com/deeplearning4j/deeplearning4s).


---

Repository of Deeplearning4J neural net examples:

- Convolutional Neural Nets
- Deep-belief Neural Nets
- Glove Example
- Restricted Boltzmann Machines
- Recurrent Neural Nets
- Recursive Neural Nets
- TSNE
- Word2Vec

---

## Documentation
For more information, check out [deeplearning4j.org](http://deeplearning4j.org/) and its [JavaDoc](http://deeplearning4j.org/doc/).

If you notice issues, please log them, and if you want to contribute, submit a pull request. Input is welcome here.

## Performance

| **Model Name**      | **Accuracy** | **F1** | **Training**  |
|---------------------|--------------|--------|---------------|
| CNNIris             | 0.7          | 0.75   | batch         | 
| CNNMnist            | 0.73         | 0.74   | batch         |
| DBNIris             | 0.33         | 0.5    | full          | 
| DBNMnistFull        | 0.10         | 0.35   | batch         |
| DBNMnistSingleLayer | 0.41         | 0.61   | full          |
| MLPBackpropIris     | 0.55         | 0.70   | full          |
| RBMIris             |              | NA     | full          |
| TSNEStandard        |              | NA     | NA            |
| Word2VecRawText     |              | NA     | batch         |
    

    * Accuracy and F1 depends on how many examples the model is trained on.
