附录C 楼面等效均布活荷载的确定方法
=======================================

.. raw:: html

  <h2 id="test111">附录C 楼面等效均布活荷载的确定方法</h2>

.. raw:: html

 <p style="text-align:justify;"><a href="#idC.0.1">C.0.1</a> <span id="idC.0.1">楼面（板、次梁及主梁）的等效均布活荷载，应在其设计控制部位上，根据需要按内力、变形及裂缝的等值要求来确定。在一般情况下，可仅按内力的等值来确定。</span></p>
 <p style="text-align:justify;"><a href="#idC.0.2">C.0.2</a> <span id="idC.0.2">连续梁、板的等效均布活荷载，可按单跨简支计算。但计算内力时，仍应按连续考虑。</span></p>
 <p style="text-align:justify;"><a href="#idC.0.3">C.0.3</a> <span id="idC.0.3">由于生产、检修、安装工艺以及结构布置的不同，楼面活荷载差别较大时，应划分区域分别确定等效均布活荷载。</span></p>
 <p style="text-align:justify;"><a href="#idC.0.4">C.0.4</a> <span id="idC.0.4">单向板上局部荷载（包括集中荷载）的等效均布活荷载可按下列规定计算：</span></p>
 <ol>
 <li style="text-align:justify;">等效均布活荷载<i>q</i><sub>e</sub>可按下式计算：</li>
 </ol>

$$q_{e} =\\frac{8M_{max}}{bl^{2}} \\tag{B.0.4-1}$$

.. raw:: html
 
 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs">l</td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">板的跨度；</td>
 </tr>
 <tr>
 <td id="eqzs"></td>
 <td id="eqzs">b</td>
 <td id="eqzs">——</td>
 <td id="eqzs">板上荷载的有效分布宽度，按本附录C.0.5确定；</td>
 </tr>
 <tr>
 <td id="eqzs"></td>
 <td id="eqzs"><i>M</i><sub>max</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">简支单向板的绝对最大弯矩，按设备的最不利布置确定。</td>
 </tr>
 </table>
 <p></p>
 <ol start="2">
 <li style="text-align:justify;">计算<i>M</i><sub>max</sub>时，设备荷载应乘以动力系数，并扣去设备在该板跨内所占面积上由操作荷载引起的弯矩。</li>
 <li style="text-align:justify;">竖向撞击力的作用区域宜取2mx2m。</li>
 <li style="text-align:justify;">竖向撞击力的作用区域宜取2mx2m。</li>
 </ol>
 <p style="text-align:justify;"><a href="#idC.0.5">C.0.5</a> <span id="idC.0.5">单向板上局部荷载的有效分布宽度b，可按下列规定计算：</span></p>
 <ol>
 <li style="text-align:justify;">当局部荷载作用面的长边平行于板跨时，简支板上荷载的有效分布宽度b为（<a href="#imageC05-1">图C.0.5—1</a>）:</li>
 </ol>
 <ul>
 <li style="text-align:justify;">当<i>b</i><sub>cx</sub>≥<i>b</i><sub>cy</sub>，<i>b</i><sub>cy</sub>≤0.6<i>l</i>，<i>b</i><sub>cx</sub>≤<i>l</i>时：</li>
 </ul>

$$b =b_{cy}+0.7l \\tag{C.0.5-1}$$

.. raw:: html

 <link rel="stylesheet" type="text/css" href="./_static/viewer.min.css"/>
 <script src="./_static/viewer.min.js" type="text/javascript" charset="utf-8"></script>
 <div><img id="imageC05-1" src="./_static/C05-1.png" alt="Picture"></div>
 <p style="color: dimgray;text-align: center;">图C.0.5—1 简支板上局部荷载的有效分布宽度（荷载作用面的长边平行于板跨）</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('imageC05-1'));</script>
 <ul>
 <li style="text-align:justify;">当<i>b</i><sub>cx</sub>≥<i>b</i><sub>cy</sub>，0.6<i>l</i><<i>b</i><sub>cy</sub>≤<i>l</i>，<i>b</i><sub>cx</sub>≤<i>l</i>时：</li>
 </ul>

$$b =0.6 b_{cy}+0.94l \\tag{C.0.5-2}$$

.. raw:: html
 
 <ol start="2">
 <li style="text-align:justify;">当荷载作用面的长边垂直于板跨时，简支板上荷载的有效分布宽度b按下列规定确定（<a href="#imageC05-2">图C.0.5—2</a>）:</li>
 <div><img id="imageC05-2" src="./_static/C05-2.png" alt="Picture"></div>
 <p style="color: dimgray;text-align: center;">图C.0.5—2 简支板上局部荷载的有效分布宽度（荷载作用面的长边垂直于板跨）</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('imageC05-2'));</script>
 </ol>
 <ul>
 <li style="text-align:justify;">当<i>b</i><sub>cx</sub><<i>b</i><sub>cy</sub>，<i>b</i><sub>cy</sub>≤2.2<i>l</i>，<i>b</i><sub>cx</sub>≤<i>l</i>时：</li>
 </ul>

$$b =\\frac{2}{3} b_{cy}+0.73l \\tag{C.0.5-3}$$

.. raw:: html

 <ul>
 <li style="text-align:justify;">当<i>b</i><sub>cx</sub><<i>b</i><sub>cy</sub>，<i>b</i><sub>cy</sub>>2.2<i>l</i>，<i>b</i><sub>cx</sub>≤<i>l</i>时：</li>
 </ul>

$$b =b_{cy}\\tag{C.0.5-4}$$

.. raw:: html
 
 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="60px" align='right' id="eqzs">l</td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">板的跨度；</td>
 </tr>
 <tr>
 <td id="eqzs"></td>
 <td id="eqzs"><i>b</i><sub>cx</sub>、<i>b</i><sub>cy</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">荷载作用面平行和垂直于板跨的计算宽度，分别取<i>b</i><sub>cx</sub>＝<i>b</i><sub>tx</sub>＋2s＋h，<i>b</i><sub>cy</sub>＝<i>b</i><sub>ty</sub>＋2s＋h。其中<i>b</i><sub>tx</sub>为荷载作 用面平行于板跨的宽度，<i>b</i><sub>ty</sub>为荷载作用面垂直于板跨的宽度，s为垫层厚度，h为板的厚度。</td>
 </tr>
 </table>
 <p></p>
 <ol start="3">
 <li style="text-align:justify;">当局部荷载作用在板的非支承边附近，即d＜<math><mfrac><mn>2</mn><mn>3</mn></mfrac></math>时(<a href="#imageC05-1">图C.0.5—1</a>)，荷载的有效分布宽度应予折减，可按下式计算：</li>
 </ol>

$${b}'= \\frac{b}{2} +d\\tag{C.0.5-5}$$

.. raw:: html
 
 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs"><math><msup><mrow><mi>b</mi></mrow><mo>′</mo></msup></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">折减后的有效分布宽度；</td>
 </tr>
 <tr>
 <td id="eqzs"></td>
 <td id="eqzs">d</td>
 <td id="eqzs">——</td>
 <td id="eqzs">荷载作用面中心至非支承边的距离。</td>
 </tr>
 </table>
 <p></p>
 <ol start="4">
 <li style="text-align:justify;">当两个局部荷载相邻且e＜b时（<a href="#imageC05-3">图C.0.5—3</a>），荷载的有效分布宽度应予折减，可按下式计算：</li>
 </ol>

$${b}'= \\frac{b}{2} +\\frac{e}{2}\\tag{C.0.5-6}$$

.. raw:: html
 
 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs">e</td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">相邻两个局部荷载的中心间距。</td>
 </tr>
 </table>
 <p></p>
 <div><img id="imageC05-3" src="./_static/C05-3.png" alt="Picture"></div>
 <p style="color: dimgray;text-align: center;">图C.0.5—3 相邻两个局部荷载的有效分布宽度</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('imageC05-3'));</script>
 <ol start="5">
 <li style="text-align:justify;">悬臂板上局部荷载的有效分布宽度（<a href="#imageC05-4">图C.0.5—4</a>）按下式计算：</li>
 </ol>

$$b= b_{cy} +2x\\tag{C.0.5-7}$$

.. raw:: html
 
 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs">x</td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">局部荷载作用面中心至支座的距离。</td>
 </tr>
 </table>
 <p></p>
 <div><img id="imageC05-4" src="./_static/C05-4.png" alt="Picture"></div>
 <p style="color: dimgray;text-align: center;">图C.0.5—4 悬臂板上局部荷载的有效分布宽度</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('imageC05-4'));</script>
 <p style="text-align:justify;"><a href="#idC.0.6">C.0.6</a> <span id="idC.0.6">双向板的等效均布荷载可按与单向板相同的原则，按四边简支板的绝对最大弯矩等值来确定。</span></p>
 <p style="text-align:justify;"><a href="#idC.0.7">C.0.7</a> <span id="idC.0.7">次梁（包括槽形板的纵肋）上的局部荷载应按下列规定确定等效均布活荷载：</span></p>
 <ol>
 <li style="text-align:justify;">等效均布活荷载应取按弯矩和剪力等效的均布活荷载中的较大者，按弯矩和剪力等效的均布活荷载分别按下列公式计算：</li>
 </ol>

$$q{eM} =\\frac{8M_{max}}{sl^{2}}\\tag{C.0.7-1}$$
$$q{eV} =\\frac{2V_{max}}{sl}\\tag{C.0.7-2}$$

.. raw:: html
 
 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="90px" align='right' id="eqzs">s</td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">次梁间距；</td>
 </tr>
 <tr>
 <td id="eqzs"></td>
 <td id="eqzs" align='right'>l</td>
 <td id="eqzs">——</td>
 <td id="eqzs">次梁跨度；</td>
 </tr>
 <tr>
 <td id="eqzs"></td>
 <td id="eqzs" align='right'><i>M</i><sub>max</sub>、<i>V</i><sub>max</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">简支次梁的绝对最大弯矩与最大剪力，按设备的最不利布置确定。</td>
 </tr>
 </table>
 <p></p>
 <ol start="2">
 <li style="text-align:justify;">按简支梁计算<i>M</i><sub>max</sub>与<i>V</i><sub>max</sub>时，除了直接传给次梁的局部荷载外，还应考虑邻近板面传来的活荷载（其中设备荷载应考虑动力影响，并扣除设备所占面积上的操作荷载），以及两侧相邻次梁卸荷作用。</li>
 </ol>
 <p style="text-align:justify;"><a href="#idC.0.8">C.0.8</a> <span id="idC.0.8">当荷载分布比较均匀时，主梁上的等效均布活荷载可由全部荷载总和除以全部受荷面积求得。</span></p>
 <p style="text-align:justify;"><a href="#idC.0.9">C.0.9</a> <span id="idC.0.9">柱、基础上的等效均布活荷载，在一般情况下，可取与主梁相同。</span></p>

:math:`\ `