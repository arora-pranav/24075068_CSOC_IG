ok there are two ways in which you can create neural networks. one by just hardcoding each layer(initialising every weight matrix and biases matrix individually) or you can create a class `dense_layer` and for creating different layers you just create a object of that class

[like this](https://cdn.discordapp.com/attachments/1371908100965138553/1375323427845570560/image.png?ex=68314541&is=682ff3c1&hm=d8cb01d5b09893985e8ae092579c18c1bc7ab348b4b27dd49aa8882b2dd0b47c&)

or you can hardcode them [like this](https://cdn.discordapp.com/attachments/1371908100965138553/1375323781354098759/image.png?ex=68314595&is=682ff415&hm=cdfe5d7d496dc4ef3b2b67133c76811422bc5cddf10b049001a58104c1819697&)

If you guys could try using a better optimizer than SGD, that would be great
Also check about weight initialization strategies

class imbalance ki wajah se model ne sabko negative label krdia LMAO 
help somebody
should I make a custom sampler jo ki har batch mein sare tarah ke data points include krta ho?
my model cheated on me 😢

Tanishq Ahuja — 13:24
Read how to handle class imbalance https://drive.google.com/file/d/13dmlGavqr5XtZijQuwfcHAc7cY4k4-l8/view&sa=D&source=apps-viewer-frontend&ust=1747984721585804&usg=AOvVaw1m5Zu5646sdJmxdJ6hQhWv&hl=en
chapter 4
since we cannot do resampling, use algorithmic methods, for example changing the loss function

Tanishq Ahuja — 13:28
I think iske liye scikit learn me stratified k folds karke hota hai ek, check that out


Google colab says i ran out of ram and crashed mid-session. what should i do?
Tejbir — 10:45
If you are doing part2(pytorch) decrease the batch size
Or you can use efficient dtypes
Like float32 for weights
Manas — 10:52
what are you trying to do?
I mean is your architecture too big
Sompat07 — 11:24
im doing part 1 using numpy
the data is too large i guess
yashashwi — 12:22
there is something wrong with your configuration


https://discord.com/channels/1371538800735424512/1371908100965138553/1377548129347309640

right!! Suppose you want to detect some anomaly in a system
The chances of an anomaly being there is really low
hence even if your model predicts no anomaly for every test data point, your accuracy will be high
Hence you need to do a little study for the correct type of metric to be used