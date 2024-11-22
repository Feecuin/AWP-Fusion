### Adverse Weather Multi-Modality Image Fusion via Global and Local Text Perception

##  Network Architecture
![](./figs/overview.jpg)

## Contents
- [Testing](#Testing)
- [Gallery](#Gallery)
- [Table](#Table)
- Waiting....

<h2 id="Testing"> Testing</h2>

Testing( An example of Haze.)
```
python test.py \
 --ir_path ./Test_imgs/Haze/ir \
 --vi_path ./Test_imgs/Haze/vi \
 --weights_path ./checkpoint/AWM_Fuse.pth \
 --save_path ./result/Haze  \
 --input_text ./Test_imgs/Haze/Haze_captions \
 --blip_vi_text ./Test_imgs/Haze/vi_npy \
 --blip_ir_text ./Test_imgs/Haze/ir_npy
```
<h2 id='Table'> Table</h2>
Table1. Comparison of quantitative results of different methods in ideal and adverse weather scenes. The best scores are in bold, while the second-best scores are in blue.

![Table](./figs/table.jpg)



<h2 id='Gallery'> Gallery</h2>

![Gallery](./figs/Rain.jpg)
Fig1. Comparison of fusion results obtained by the proposed algorithm under rain weather and the results of the comparison methods under ideal condition.

![Gallery](./figs/Haze.jpg)
Fig2. Comparison of fusion results obtained by the proposed algorithm under haze weather and the results of the comparison methods under ideal condition.

![Gallery](./figs/Snow.jpg)
Fig3. Comparison of fusion results obtained by the proposed algorithm under snow weather, and the results of the comparison methods under ideal condition.




