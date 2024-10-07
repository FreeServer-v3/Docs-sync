# 活躍獎勵

{% hint style="info" %}
此方式會被 FBooster 影響。關於更多，請參考 [FBooster 頁面](../../fbooster/)
{% endhint %}

活躍獎勵是一種透過活躍於 Discord 伺服器，會獲得的獎勵。

每次活躍升級，會獲得 [50 FreeCoin](#user-content-fn-1)[^1]。

只要獲得的經驗足夠，即可升級。 經驗可以透過打字聊天、文字反應等獲得；每種方式獲得的經驗不盡相同，且有加以隨機因素。

每個等級所需升級經驗皆不同。下圖是一個10等以內的範例倍率曲線，算式如:\
$$f: y=(0.05 x)^{0.8}+0.909$$\
可以看見，該曲線是一個趨緩的指數函數。

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

將所得數字乘以 1000並取整(高斯符號)，即可得到升級所需經驗；可以使用以下算式來計算升級所需經驗:

$$
所需經驗=[1000*\{(當前等級*{0.05})^{0.08}+0.909\}]
$$

使用指令 `/level` 可以查看你當前的等級與經驗

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>



[^1]: \*在沒有 FBooster 作用下
