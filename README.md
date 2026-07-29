# 樋川 颯人 / Hayato Hikawa

## 目の前のものをつくることから、社会の構造を捉えることへ

私は、神山まるごと高専でハードウェア、AIソフトウェア、ロボット開発に取り組んでいます。

中学生の頃、私が見ていたのは回路や基板でした。
しかし、ロケット開発、40人を超えるチームでの活動、Atraの開発を経験するなかで、技術だけを正しくつくっても、物事は前に進まないと知りました。

必要な情報が届かない。判断の前提が共有されない。誰が決めるのかが曖昧になる。目の前の作業に追われ、本当に解くべき問題を見失う。

異なる現場で、同じ問題が何度も現れました。

その経験から、私の関心は一つの部品やプロダクトを設計することから、**人・情報・意思決定がどうつながれば、チームや社会がより良い行動を選べるのか**を考えることへ広がっています。

---

## My Story

### 1. 「動くもの」をつくれば十分だと思っていた

中学生の頃、CanSatとロケットの開発に取り組み、ロケット甲子園の全国大会に出場しました。

全国大会では、設定した高度でパラシュートを展開するシステムを搭載したロケットを制作し、私は電装系、特に電子回路と基板設計を担当しました。

<table>
  <tr>
    <td width="50%">
      <img src="./images/DSC_0287.JPG" alt="Rocket avionics board" />
      <p align="center"><b>製作したロケット搭載基板</b></p>
    </td>
    <td width="50%">
      <img src="./images/ex_PCB.png" alt="Rocket PCB layout" />
      <p align="center"><b>PCBレイアウト</b></p>
    </td>
  </tr>
</table>

当初の私は、回路が正しく動けば開発は成功すると考えていました。

しかし実際には、部品配置、電源の安定性、機体との干渉、作業時間、担当者同士の認識差など、回路図の外側にある条件が結果を左右しました。

ここで初めて、設計とは単に実装方法を決めることではなく、

- 何が起こり得るかを想定すること
- 限られた時間と人員の使い方を決めること
- 異なる担当者が同じ前提で動けるようにすること
- 失敗したときに原因を見つけ、改善できる形を残すこと

まで含むものだと学びました。

私にとっての「設計力」は、この経験から始まりました。

---

### 2. 技術の問題だと思っていたものが、人と組織の問題でもあった

高専入学後、世界規模の高校生ロボット競技であるFIRST Robotics Competitionに出場する、FRC Team Hanabiに参加しました。

Hanabiには40人を超えるメンバーが所属し、ロボット制作だけでなく、資金調達、社会貢献活動、広報、遠征準備までを学生主体で進めています。

私は、ロボットの設計に加え、資金調達と社会貢献活動の管轄を担当しています。

ここで直面したのは、ロケット開発のときよりも大きな規模の「設計」の問題でした。

技術的に優れた案があっても、目的や判断の前提が共有されなければ実行されません。あるチームの変更が別のチームに伝わらなければ、全体では矛盾が生まれます。人数が増えるほど、個人の努力だけでは解決できない問題が増えていきました。

私はこの経験から、チームもまた一つのシステムであり、成果は個人の能力だけでなく、**情報の流れ、意思決定の仕方、互いの信頼**によって決まると学びました。

同時に、自分の考えを通すことよりも、異なる役割の人が何を見ているのかを理解し、全体として前に進めることの重要性を知りました。

---

### 3. 異なる現場に、同じ問題が存在していた

ロケットとHanabiで経験した問題は、ソフトウェア開発でも現れました。

仕事を始める前には、Slack、GitHub、カレンダー、資料などに散らばった情報を探し、照合し、整理しなければなりません。必要な情報を見落としたまま動けば、間違った作業に時間を使います。情報が増えるほど、本当に重要な判断へたどり着くことが難しくなります。

この問題に対して開発しているのが、**Atra**です。

Atraは、仕事を始める前に必要な情報探索・照合・整理を終わらせ、状況を理解したうえで「正しい最初の行動」へ到達するためのソフトウェアです。本プロジェクトは、地域版未踏型プログラムであるLE四国に採択されました。

しかし、Atraをつくる過程で、私はさらに大きな問いに直面しました。

AIを使えば、情報整理や開発の速度は大きく上がります。一方で、生成されるものが増えるほど、人間が内容や判断の背景を理解できなくなる可能性があります。速く進んでいるように見えても、誰も全体を説明できない状態が生まれます。

私はこれを、単なる技術上の問題ではなく、**人が理解し、判断し、責任を持つための環境をどう残すかという問題**だと考えるようになりました。

現在のAtraでは、機能を増やすこと以上に、AIを用いた開発における認知負債を減らし、検証や監査を再現できる環境を整えることを課題としています。

Atraは私にとって完成した答えではありません。

ロケットやHanabiで感じてきた問題を、より広い視点から問い直すための実験です。

---

## 視点が変わった瞬間

以前の私は、目の前にある問題を技術で解決することに集中していました。

しかし、異なる現場で同じ問題に出会ったことで、個別の失敗の背後には、より大きな構造があると考えるようになりました。

- なぜ必要な情報が、必要な人へ届かないのか
- なぜ人は、目的よりも目の前の作業に追われるのか
- なぜチームが大きくなると、意思決定が分断されるのか
- AIが判断を支援する時代に、人間はどこで理解し、責任を持つのか

この問いは、一つの学校や一つのチームだけの問題ではありません。

文化、組織、産業、国によって、情報の共有方法やリーダーシップ、責任の持ち方は異なります。自分が今いる環境だけを見ていては、想定できる選択肢にも限界があります。

だから私は、グローバルな環境に挑戦したいと考えるようになりました。

海外に行くこと自体が目的なのではありません。

異なる背景や価値観を持つ人と協働し、自分が当然だと思っている前提を壊し、より多くの社会や人に通用する問いへ育てたいからです。

---

## Why TOMODACHI Boeing Entrepreneurship Seminar

私は、すでに答えを持っているからこのプログラムに参加したいのではありません。

自分の問いが、今の自分の経験だけでは扱いきれないほど大きくなってきたから参加したいと考えています。

TOMODACHI Boeing Entrepreneurship Seminarで、特に成長したいことは三つあります。

### 1. 自分の仮説を手放し、他者から学ぶこと

私は、問題を構造化し、自分なりの仮説をつくることを得意としています。
一方で、考え抜いた仮説ほど、自分の視点に閉じる危険があります。

ユーザーリサーチを通じて、自分が解きたい問題ではなく、相手が本当に抱えている問題に向き合う力を身につけたいです。

### 2. 異なる背景を持つ人と、一つの答えをつくること

Hanabiでは大人数での協働を経験しましたが、同じ学校や活動を共有するメンバーが中心です。

地域、専門、年齢、価値観の異なる人と出会い、意見の違いを避けるのではなく、違いをより良い設計へ変える経験をしたいです。

### 3. 「グローバル」を自分の行動に変えること

現在の私にとって、グローバルな挑戦はまだ抽象的です。

英語で自分の考えを伝え、海外で活躍する人や異なる文化の考え方に触れることで、自分の将来の選択肢と、取り組む問題のスケールを広げたいです。

---

## 私がチームへ持ち込めるもの

私が持ち込めるのは、完成された技術力ではなく、異なる領域をつなぎながら考える姿勢です。

- ハードウェアの制約を、実物を通じて考えてきた経験
- 40人を超えるチームで、立場の異なる人と活動してきた経験
- AIを活用しながら、その危うさや人間の責任にも向き合ってきた経験
- 失敗を個人の能力不足だけで終わらせず、仕組みの問題として捉え直す視点
- 自分の考えを更新し続けることへの意欲

私は、チームの中で最初から正解を示す人ではなく、問いを深め、異なる意見をつなぎ、全員が次の一歩を選べる状態をつくる人でありたいです。

---

## 今、向き合っている問い

> **技術が人の行動を速くする時代に、人が考え、判断し、責任を持ち続けられる仕組みをどう設計できるか。**

中学生の頃は、一枚の基板をどう動かすかを考えていました。

今は、人と情報と意思決定がどうつながれば、チームや社会がより良い方向へ動けるかを考えています。

そして次は、この問いを自分一人の経験から切り離し、異なる地域、文化、専門を持つ人たちと共に考えたいです。

---

## English Summary

I am Hayato Hikawa, a student at Kamiyama Marugoto College of Technology.

My journey began with CanSat and rocket development in middle school. I competed in the national Rocket Koshien competition and designed the electronics and PCB for a rocket equipped with a parachute deployment system.

At first, I believed that success meant making the technology work. Through rocket development, FRC Team Hanabi, and my AI software project Atra, I learned that technology alone does not move a project forward. Information must reach the right people, assumptions must be shared, and teams need a clear way to make decisions.

This realization changed my focus from designing individual products to understanding the larger systems that connect people, information, and decisions.

I am developing Atra to help people collect, verify, and organize scattered work information before taking their first action. While building it, I have also begun exploring a broader question: as AI makes work faster, how can humans continue to understand, decide, and take responsibility?

I want to join the TOMODACHI Boeing Entrepreneurship Seminar not because I already have the answer, but because my questions have grown beyond what I can explore within my current environment. I want to learn from users, collaborate with people from different backgrounds, challenge my assumptions, and turn “global” from an abstract idea into a real direction for my future.
