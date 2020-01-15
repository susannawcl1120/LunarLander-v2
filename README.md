# LunarLander-v2

The training model of LunarLander-v2 is using SARSA as policy in OpenAI gym box2D environment.

It requires keras-rl 2 as the framework and trains on the Google Colab.

Neural network is the important in the model, changing the hyper parameters can received a better result. The following shows the demostration video:

---

Before training

![aaa](https://github.com/susannawcl1120/LunarLander-v2/blob/master/before_training.gif)

---

After traning for 150000 steps(Dense 128 units, activation="relu")

(It should be remind that next_action need to adjust for different gym game, Lunarlander need to adjust 4 actions)

![bbb](https://github.com/susannawcl1120/LunarLander-v2/blob/master/lunarLander_best_result.gif)

