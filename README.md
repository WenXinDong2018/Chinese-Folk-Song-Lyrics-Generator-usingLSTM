# Chinese-Folk-Song-Lyrics-Generator-using-LSTM
Generate random Chinese Folk song style lyrics starting with a user-defined-seed. Model built using Tensorflow and Keras, inspired by the course "Natural Language Processing in Tensorflow taught by Laurence lmoroney on Coursera.

Training Data is lyrics1.txt, where I gather about 30 folk song lyrics. I have preprocessed the training data using Jieba, an API that splits Chinese sentences into words. 

Training Model is a neural network built using the Keras Sequential API, with an Embedding layer followed by two LSTM layers, followed by two Dense layers. 
Accuracy reaches about .85. 

Say the seed text is "姑娘", the generated lyrics is:

姑娘 你 陪你到 永久 

有房 所有 你 呢 

我 明白 酒杯 会 有 我 的 芳香 

也 对 你 了 自己 向 我 的 奔 向 

我 的 在 驻足 谁 夕阳 

为 你 明白 最 平静 优雅 的 少年 

一直 姑娘 想 看 喝 的 人 心里 梦 

唱 她 她 来 一个 心头 

哎 嗨 嗨 

填满 提及 你 的 回眸 

言语 诉说 的 芳香 

放肆 最 轻易 的 年华 

一起 再 跳动 

那么 温柔 秋夏 不容 山水 江湖 

人 睡意 

鸟 睡意 

有霜 回眸 

向 的 你 的 心头 哎 嗨 

填满 回眸 

睡眠 芳香 

你 安慰 理想 必须 热爱

睡意 睡意 睡意 

半块 陪伴 寒 必须 问 我 

太慢 平凡 太慢 

太慢 太慢 太慢 

橡皮 共 准备 来 来 了 

给 的 她 给 我 再 去 一样 

刺激 我 的 我 梦 是 风 力量 

安慰 的 心头 

嗨 嗨 

which doesn't really make too much sense but might help one get inspiration when writing lyrics.
