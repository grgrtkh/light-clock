# light-clock

light-clock は３つの引数を持ち, それぞれbeta, interval, time です．betaは光速と座標系の移動速度との比であり，intervalは描画間隔(ms)，timeはアニメーションの描画時間(s)です．
３つの引数の範囲はそれぞれ，0<=beta<1, interval>0, time>0であり，初期値はそれぞれbeta=0, interval=100, time=5 です．
intervalを小さく，またはtimeを大きくすると計算時間が増加します．
