+++
date = "2018-12-17T00:00:00"
title = "なぜ不確実性をモデルする必要があるのか ~より安全なディープラーニングの医療画像解析応用に向けて"
abstract = "このセミナーでは、以下の二つの関連するテーマについてお話しします。

パート１では、ディープラーニングシステムの「推定の不確かさ」（不確実性）をどうやって数値化し、失敗を防ぐかということについてお話しします。推定の不確かさは、「データ」そして「モデル」という二つの根源から発生します。例えば、ヒストロジーの画像から、がん細胞の悪性度を測定するシステムをディープラーニングを使って行ったとします。インプット画像が曖昧で、十分な情報が含まれていない場合、悪性度を推定することは難しくなります。これはデータが原因となる、推定の「不確かさ」です。もしくは、十分に情報が含まれていたとしても、学習データに似たようなケースがなかった場合、推定は難しくなります。これは「モデル」が原因となる「不確かさ」の良い例です。「データ」と「モデル」ということなる要素から発生する不確かさを、別々にモデルすることにより、推論のリスクの数値化をするだけではなく、説明できるようになるのではないかと考えています。このことについては、Image Quality Transferという応用例を通してお話ししたいと思います。

パート２では、「人為的不確かさ」をモデル化することにより、ノイズが多いデータから効率的に学習する方法についてお話ししたいと思います。多くの医療画像解析のアプリケーションでは、学習データを用意するとき、医療知識のある専門家たちに、画像のラベル付けをしていただく必要があります。お医者さんの技量やバイアスによって、ラベルの質が変わってくる上、間違えが含まれていること、意見が一致しないことも多々有ります。データの量が限られている場合、ラベルの間違いやノイズは、機械学習システムの精度に影響を与えかねません。ですが仮に、お医者さん一人一人の間違えの傾向を把握していたとしたら、間違えを修正して、きれいなラベルを使ってモデルを学習させることができます。人間の間違えの傾向をモデル化することで、ラベルの修正と、アルゴリズムの学習を同時に行う方法について、お話します。"
abstract = "Access to clean and voluminous datasets is a piece of luxury confined to academic research for many machine learning applications. In practice, such datasets are hard to come by, and consequently limit the performance of deployed machine learning systems. This problem is pervasive in medical imaging applications where the cost of data acquisition and labelling is high. In this talk, I will present a method that is capable of learning more intelligently from such noisy data by modelling the human annotation process. This is particularly relevant in situations where data is labelled by multiple annotators of varying skill levels and biases. "
abstract_short = ""
event = "Hiroshima City University, Department of Information Science "
event_url = "" 
location = "Hiroshima, Japan"

selected = false
math = true

url_pdf = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
Invited by [Prof. Yoshitaka Masutani](http://rsw.office.hiroshima-cu.ac.jp/Profiles/13/0001203/profile.html)
