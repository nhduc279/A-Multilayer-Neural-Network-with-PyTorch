Hi everyone,

I just want to share one of my experiences that made my day!

I learned deep learning and neural networks last year, I have never tried building, designing, and tuning a neural network for an ML problem with tabular data though. This is because the idea of using deep learning algorithms on tabular datasets is quite weird.

However, when I observed and read some discussions on Twitter about using deep learning and deep neural network for tabular data. I was motivated to decide “Well, I will try building a multilayer neural network to solve an ML problem with tabular data!”. To carry out this:

- I first picked out a small toy dataset for a regression problem
- Next, I created a baseline model, namely Random Forest (thoroughly tuned for best performance)
- Then I built a network to surpass that baseline.
- After 3 days, I am constantly testing and tuning the network by trying many different number of layers, number of neurons for each layer, minibatch sizes, activation functions, learning rates, and optimization methods.

Today, I finally build a multilayer network that outperforms the Random Forest model. :joy:

**Check out my work**: :point_right: https://github.com/nhduc279/A-Multilayer-Neural-Network-with-PyTorch/blob/main/code.ipynb :robot:

**My thoughts**:
- A well-built NN may outperform tree-based models and generalized linear models, but it requires more work.
- Deep learning or deep neural networks are FLEXIBLE
- PyTorch is efficient, flexible, and convenient (I am now a PyTorch lover ^-^)
- So far, I have another option for using DDNs to take into account when competing on tabular data (not only using XGBoost, HistGB, LightGBM, or CatBoost).
- If you’re interested in using DDNs for tabular data, Sebastian Raschka has recently written a great blog about this topic and a curated list of research papers and his advice on the idea of using deep learning for tabular data :point_right: [“Short Chronology Of Deep Learning For Tabular Data”](https://sebastianraschka.com/blog/2022/deep-learning-for-tabular-data.html).
