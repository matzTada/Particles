# Particles
Particles

<a href="http://www.youtube.com/watch?feature=player_embedded&v=w7VFCeh_oME
" target="_blank"><img src="http://img.youtube.com/vi/w7VFCeh_oME/0.jpg"
alt="movie on youtube" width=40% border="10" /></a>  
[movie on youtube](https://www.youtube.com/watch?v=w7VFCeh_oME)  
  
## To Do
* (OK)まずは領域に分けて
* (OK)APESみたいなのを適用する
* パネルの代わりに向かってく方向に対し、一定範囲で衝突するか確かめるのもありそう
* 衝突して止まっちゃうときにどうするのか考える。+, -どちらの方向も速度を適用するとぶつかるから。
* 「競合(同じマスに複数が侵入)」判定と譲り合い。
* とりあえず色塗るか

## Ideas, memo
* ドロネー三角形分割
* 写真にトレースペーパー引いて上から直線だけで描写←一部三角形で埋めてもよさそう
* 等距離線、競合
* ASEP, 自己駆動粒子、粉流体、パーコレーション
* 渋滞もナッシュ均衡か
* 合流・分散は確率的な発生・消失で表せる

## Delaunay triangulation
* 肝は「どの点も三角形に内包されないこと。」
* そのものズバリがありましたので、参考にさせていただいてます。 <http://30min-processing.hatenablog.com/entry/2017/02/09/000000>
