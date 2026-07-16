# 红外焊接文献对比矩阵

> 5 篇红外焊接领域文献的结构化横向对比，涵盖基础信息、研究问题、理论机制、方法、变量、结论、局限、背景与定位 9 个维度。

## 论文索引

- **P1** - ADRC原型 (2025)
- **P2** - 红外热源对比 (2017)
- **P3** - 热流方向 (2018)
- **P4** - FPCB台式炉 (2021)
- **P5** - 可变辐照掩模 (2021)

## 对比矩阵

| 维度 | P1 | P2 | P3 | P4 | P5 |
|------|------|------|------|------|------|
| <strong>1. 基础信息</strong> | <strong>标题：</strong>A prototype for infrared soldering of electronic devices using the active disturbance rejection control structure<br><br><strong>作者：</strong>R C. Anguiano Cota, D I. Rosas Almeida, J R. Herrera García<br><br><strong>期刊：</strong><em>Engineering Research Express</em> 2025, 7(4): 045392<br><br><strong>DOI：</strong>10.1088/2631-8695/ae24c8<br><br><strong>分区：</strong>ESCI Q3, IF=1.8<br><br><strong>机构：</strong>Universidad Autónoma de Baja California, 墨西哥 | <strong>标题：</strong>Comparative Effectiveness of Infrared Heat Sources for Mounting and Dismounting Electronic Modules<br><br><strong>作者：</strong>V. L. Lanin, A. I. Lappo<br><br><strong>期刊：</strong><em>Surface Engineering and Applied Electrochemistry</em> 2017, 53(4)<br><br><strong>DOI：</strong>10.3103/S106837551704010X<br><br><strong>分区：</strong>SCIE Q4, IF=0.7, EI<br><br><strong>机构：</strong>Belarusian State University of Informatics and Radioelectronics, 白俄罗斯 | <strong>标题：</strong>Influence of heat flow direction on solder ball interfacial layer<br><br><strong>作者：</strong>Alexandr Otáhal, Ivan Szendiuch<br><br><strong>期刊：</strong><em>Journal of Electrical Engineering</em> 2018, 69(4): 305-310<br><br><strong>DOI：</strong>10.2478/jee-2018-0043<br><br><strong>分区：</strong>SCIE Q4, IF=0.8, EI<br><br><strong>机构：</strong>Brno University of Technology, 捷克 | <strong>标题：</strong>Investigations of Infrared Desktop Reflow Oven with FPCB Substrate during Reflow Soldering Process<br><br><strong>作者：</strong>M I. Ahmad, M S. Abdul Aziz, M Z. Abdullah, et al.<br><br><strong>期刊：</strong><em>Metals</em> 2021, 11(8): 1155<br><br><strong>DOI：</strong>10.3390/met11081155<br><br><strong>分区：</strong>SCIE Q2, IF=2.5, EI<br><br><strong>机构：</strong>Universiti Sains Malaysia 等 | <strong>标题：</strong>The effect of variable irradiation mask in Focused Infrared Light Soldering Systems for electronic components<br><br><strong>作者：</strong>Citlalli Anguiano, Kiyoshi Natzu, Marco Félix, et al.<br><br><strong>期刊：</strong><em>Optik</em> 2021, 242: 167298<br><br><strong>DOI：</strong>10.1016/j.ijleo.2021.167298<br><br><strong>分区：</strong>EI（已被SCIE剔除）<br><br><strong>机构：</strong>Universidad Autónoma de Baja California / CICESE, 墨西哥 |
| <strong>2. 核心研究问题</strong> | 针对红外焊接热系统存在<strong>输入时滞（input delay）</strong>且缺乏精确数学模型的控制难题，探索将<strong>自抗扰控制（ADRC）</strong>用于电子器件焊接温度曲线的轨迹跟踪。<br><br><strong>研究缺口：</strong>现有聚焦红外焊接系统普遍缺乏闭环温度控制，导致热不均匀和焊锡珠问题；传统时滞系统控制方法（Smith预估器、Padé近似）依赖精确模型。<br><br><strong>核心假设：</strong>通过一阶Padé近似分析，输入时滞可视为有界外部扰动，由ADRC实时估计并补偿，无需对时滞做多项式近似。 | 针对电子模块贴装与拆卸中<strong>红外热源选择缺乏系统量化依据</strong>的问题，评估<strong>短波（近红外0.7-1.5μm）</strong>与<strong>中波（中红外2-10μm）</strong>两类热源的有效性差异。<br><br><strong>具体问题：</strong>①两种热源在PCB和元器件壳体上的热场不均匀性如何？②加热器间距对加热速率和均匀性的影响？③何种热源适用于自动化产线、何种适用于返修站？<br><br><strong>缺口：</strong>热源类型与加热均匀性/速率的定量权衡关系尚不明确。 | 针对BGA封装球贴装工艺中<strong>热流方向这一被忽视的参数</strong>，研究不同热流方向（底部/顶部/双侧红外加热）对SAC305焊球与焊盘间<strong>金属间化合物层（IMC layer）</strong>厚度与粗糙度的影响。<br><br><strong>缺口：</strong>现有文献关注材料兼容性、封装设计、温度曲线等，但<strong>热流方向对焊点微观结构的影响尚未充分探索</strong>。<br><br><strong>假设：</strong>热流方向通过改变焊球内部温度梯度，影响热迁移和液态焊料流动，从而改变IMC层形成与生长。 | 针对<strong>台式红外回流焊炉中FPCB基板回流焊接缺乏系统热场认知</strong>的问题，通过CFD仿真+实验研究炉膛内温度分布特性及FPCB受热行为。<br><br><strong>具体问题：</strong>①炉膛内温度分布是否均匀？不均匀性成因？②风扇转速（Re）、FPCB位置、FPCB厚度如何影响表面温度？③何种位置与厚度组合可获符合JSTD-020E的回流曲线？<br><br><strong>缺口：</strong>前人已仿真FR-4 RPCB台式炉热场，但<strong>未考虑FPCB及其最优放置位置</strong>——FPCB因柔性、薄、热物性差异大，热行为与刚性板不同。 | 针对<strong>光子SMT组件有限面积焊接</strong>中，现有聚焦红外光焊接系统（FILSS）光/热分布覆盖整个BGA面积、无法匹配新型光子器件局部热需求的问题，研究在FILSS输出端插入<strong>可变辐照掩模（VIM）</strong>后能否获得特定尺寸与形状的辐照度和热分布。<br><br><strong>具体问题：</strong>①VIM在近距离（20mm）与远距离（30mm）时靶面辐照度分布差异？②VIM边缘非相干光衍射如何影响热分布？③VIM位置处温度能达到焊接所需范围吗？ |
| <strong>3. 理论视角/机制</strong> | <strong>（1）红外辐射加热：</strong>QTH卤素灯遵循<strong>斯特藩-玻尔兹曼定律</strong>$`P=\varepsilon\sigma A T^4`$，辐射经椭圆镀金反射镜汇聚。<br><br><strong>（2）集中参数热模型：</strong>当 $`Bi \lt 0.1`$ 时，焊接区视为均温体，$`mc_p \frac{dT}{dt}=q_{in}-hA(T-T_\infty)`$，热时间常数 $`\tau_{th}=\frac{mc_p}{hA}`$。<br><br><strong>（3）时滞扰动化：</strong>一阶Padé近似 $`e^{-\tau s}\approx\frac{2-\tau s}{2+\tau s}`$ 将系统转化为非最小相位系统，人工状态变量视为外部扰动。<br><br><strong>（4）ADRC框架：</strong><strong>扩张状态观测器（ESO）</strong>实时估计扰动，结合滑模项实现全局渐近稳定。 | <strong>红外辐射传热：</strong><strong>普朗克定律</strong>给出光谱辐射率；<strong>维恩位移定律</strong>$`\lambda_{max}\cdot T=2.898\times10^{-3}`$ m·K 表明温度越高则峰值波长越短；<strong>斯特藩-玻尔兹曼定律</strong>$`Q=F_s\varepsilon\sigma S_h(T_h^4-T_s^4)`$。<br><br><strong>工程原理：</strong>短波卤素灯温度高、波长短、加热速率快但热场集中不均匀；中波陶瓷加热器温度低、加热均匀但响应慢——存在<strong>速率与均匀性的固有权衡</strong>。 | <strong>IMC形成：</strong>SAC305/ENIG体系中，$`\eta`$相（$`\mathrm{Cu}_6\mathrm{Sn}_5`$）形成快于$`\varepsilon`$相（$`\mathrm{Cu}_3\mathrm{Sn}`$）；三元化合物$`(\mathrm{Ni},\mathrm{Cu})_6\mathrm{Sn}_5`$生长快于$`(\mathrm{Ni},\mathrm{Cu})_3\mathrm{Sn}_4`$；IMC厚度随每次回流累积增长，超过阈值后机械强度下降。<br><br><strong>热流方向效应：</strong>Wang & Panton（2005）证实热流方向反转可减少空洞；Zhao等发现温度梯度下IMC热端薄冷端厚（热迁移效应：Cu向热端迁移，Sn向冷端迁移）。<br><br><strong>液态焊料流动：</strong>Marangoni效应与自然对流促进IMC晶体生长与剥落。<br><br><strong>加热因子：</strong>$`Q_\eta=\int(T(t)-T_m)dt`$保证不同方向的热输入可比性，本文取$`Q_\eta=308`$ s·°C。 | <strong>CFD传热框架：</strong>①连续性方程；②动量守恒（含重力体积力）；③能量方程（含IR热流源项）；④<strong>离散坐标辐射模型（DO model）</strong>求解辐射传输方程RTE，适合局部IR灯热源；⑤<strong>RNG k-ε湍流模型</strong>（含旋流修正，$`\alpha_s=0.07`$），适合离心风扇旋流。<br><br><strong>工程原理：</strong>台式炉IR灯为顶部局部热源，离心风扇产生旋流强制对流；低风速辐射主导（FPCB温度高$`40\sim50`$K），高风速对流增强。<br><br><strong>材料理论：</strong>FPCB用聚酰亚胺（PI, $`T_g=300`$°C）+Cu层，53μm，密度$`3839 \mathrm{kg/m^3}`$，导热0.3 W/mK，比热421 J/kgK。 | <strong>辐射传热：</strong>$`Q_{IR}=V\varepsilon_s\Gamma_i\Gamma_{OE}\alpha_{SMT}\sigma(T_S^4-T_{SMT}^4)`$，含几何视因子V、各界面透射率；$`\sigma=5.67\times10^{-12}`$ W/cm²/K⁴。<br><br><strong>传导传热：</strong>$`Q_C=KA\frac{T_1-T_2}{\Delta x}`$，K为热导率，A为截面积。<br><br><strong>光学衍射：</strong>VIM直边对非相干光产生衍射，强度分布$`I(r)=\frac{1}{2}+\frac{1}{\pi}\mathrm{Si}(r)-\frac{1-\cos(r)}{r}`$，其中$`r=\frac{2a\pi y}{(1+m)\lambda f}`$；直边零位处强度约为总强度<strong>50%</strong>。<br><br><strong>掩模机制：</strong>VIM阻挡部分辐射→边缘衍射使强度渐变→靶面获得特定形状光分布→辐射衰减50%对应导热衰减。<br><br><strong>成像匀化器：</strong>FILSS基于成像匀化器在靶面产生均匀辐照度，VIM"裁剪"该均匀分布。 |
| <strong>4. 研究方法</strong> | <strong>装置：</strong>QTH卤素灯（64635 HLX, 150W, MR16）+ 椭圆镀金反射镜 + 准直透镜（非球面SiO₂, f=40mm）+ 聚焦透镜（双凸SiO₂, f=50mm），焦点达1200°C；加热6×5mm BGA。<br><br><strong>控制系统：</strong>NI cRIO-9074 + NI 9211热电偶模块（24-bit, 14 S/s）+ J型热电偶 + NI 9263模拟输出（16-bit）+ LabVIEW，步长0.001s。<br><br><strong>辨识：</strong>3V阶跃信号测得$`\tau=1.603`$s，$`a=0.094339, b=4.4838`$，$`\tau_{th}=10.61`$s。<br><br><strong>对比实验：</strong>ADRC（$`c_1=200, c_2=50, c_3=70, k=0.9`$）vs PID（$`k_p=0.5, k_i=0.2, k_d=0.2`$）。<br><br><strong>验证：</strong>对损坏BGA执行局部返修，峰值244±2°C，TAL=58s。 | <strong>仿真：</strong>SolidWorks 2012 Flow Simulation，有限元热场仿真，灰体漫辐射假设，40×40mm四层PCB贴装BGA/QFP/SMD器件，加热器距板20mm。<br><br><strong>实验装置：</strong>自制红外焊接站，顶部加热（可切换两种热源）+ 底部预热（2×KI 220-1000卤素灯, 1000W）+ 冷却风扇 + MSP430微控制器 + KhK型热电偶（20Hz采样, 10-bit ADC）。<br><br><strong>对比热源：</strong>①KGM 30/300卤素灯（近红外0.7-1.5μm）；②Elstein SHTS/4陶瓷加热器（中红外2-10μm）。<br><br><strong>间距变化：</strong>10/20/30/40mm。 | <strong>设备：</strong>Power Tower焊接站，2个80×80mm陶瓷红外加热器（水平对置，不锈钢罩）+ 80×80mm冷却风扇。<br><br><strong>三种方向：</strong>①底部IR；②顶部IR；③双侧IR。<br><br><strong>样品：</strong>Dummy BGA（11×11×1.5mm, FR4, 黑色阻焊层, ENIG, 焊盘400μm）+ 500μm SAC305焊球 + SMF-08焊剂。<br><br><strong>温度曲线：</strong>峰值235°C，升温1.2°C/s，TAL 30s，$`Q_\eta=308`$ s·°C；K型热电偶+PID控温。<br><br><strong>表征：</strong>金相截面（IPC-TM-650 2.1.1选择性腐蚀）→光学显微镜→ImageJ分析IMC厚度（MSL）+粗糙度（$`R_{rms}`$）；Tescan MIRA II SEM+EDS验证成分。 | <strong>仿真：</strong>ANSYS Fluent 18，有限体积法，半炉几何（310×195×190mm），SIMPLE算法，二阶迎风，674,521元网格（偏差0.09%）。<br><br><strong>边界条件：</strong>风扇150 rad/s（115mm直径离心风扇），6支IR灯（各100W, ~5400 W/m²），炉壁发射率0.1，FPCB发射率0.9。<br><br><strong>实验：</strong>台式炉（6支红外灯管+2风扇）+ 60根K型热电偶（±2.2°C, 4s间隔）+ PID控温 + JSTD-020E回流曲线（预热140°C/浸泡180°C/回流207°C）。<br><br><strong>变量扫描：</strong>Re $`0.43\times10^5\sim2.05\times10^5`$；FPCB厚度25/53/75/100/125μm；前75mm/后135mm位置。<br><br><strong>FPCB拉伸试验：</strong>ASTM D368, INSTRON 3367, 50mm/min。 | <strong>仿真：</strong>Zemax非序列模式，光源为椭圆反射镜+灯丝（69.8W光功率），透镜用UV级熔融石英与B270玻璃。<br><br><strong>实验装置：</strong>FILSS置于光学台，QTH钨卤素灯 + 成像匀化器光学系统 + VIM（光阻挡元件）+ 热像仪测热分布。<br><br><strong>两种工况：</strong>①VIM近距离$`D_{z1}=20`$mm，x轴偏移$`D_{x1}=2`$mm；②VIM远距离$`D_{z2}=30`$mm，$`D_{x2}=4`$mm。<br><br><strong>靶面：</strong>35×35mm BGA。<br><br><strong>重定位规则：</strong>z轴每10mm偏移需x轴重定位约2mm。<br><br><strong>对比：</strong>仿真辐照度与实测热分布一致性验证。 |
| <strong>5. 关键变量</strong> | <strong>自变量：</strong>控制器类型（ADRC vs PID）；控制增益参数。<br><br><strong>因变量：</strong>温度跟踪误差（°C）、峰值温度误差、控制效率$`ITAE_{eff}`$、控制信号振荡特性。<br><br><strong>控制变量：</strong>QTH光源150W、光学配置固定、BGA 6×5mm、四阶段回流曲线。<br><br><strong>材料体系：</strong>无铅焊料（熔点~217°C）、BGA封装、FR4基板。 | <strong>自变量：</strong>热源类型（KGM卤素灯 vs Elstein陶瓷）；加热器与PCB间距（10/20/30/40mm）。<br><br><strong>因变量：</strong>PCB加热不均匀性（°C）、元器件壳体温度不均匀性（°C）、加热速率（°C/s）。<br><br><strong>控制变量：</strong>PCB 40×40mm四层、底部预热1000W、器件类型（BGA/QFP/SMD）、POS61锡铅钎料。<br><br><strong>材料体系：</strong>FR4 PCB + 多类型封装 + POS61含铅钎料。 | <strong>自变量：</strong>热流方向（底部IR / 顶部IR / 双侧IR）——3水平。<br><br><strong>因变量：</strong>IMC层平均厚度（MSL, μm）、IMC层均方根粗糙度$`R_{rms}`$（μm）。<br><br><strong>控制变量：</strong>温度曲线统一（峰值235°C, TAL 30s, $`Q_\eta=308`$）、焊球SAC305 500μm、焊剂SMF-08、焊盘400μm ENIG、Dummy BGA 11×11mm。<br><br><strong>材料体系：</strong>SAC305无铅焊料 / ENIG表面处理 / FR4基板。 | <strong>自变量：</strong>①风扇转速（Re, $`0.43\times10^5\sim2.05\times10^5`$）；②FPCB放置位置（前75mm/后135mm）；③FPCB厚度（25/53/75/100/125μm）。<br><br><strong>因变量：</strong>FPCB表面温度分布（K）、炉膛空气温度均匀性、温度偏差、von Mises应力、杨氏模量与屈服强度。<br><br><strong>控制变量：</strong>炉膛几何、IR灯功率（6×100W）、回流曲线设定、FPCB材料（PI+Cu, 53μm）。<br><br><strong>材料体系：</strong>FPCB（聚酰亚胺+Cu）+ 无铅SAC焊料。 | <strong>自变量：</strong>VIM放置距离（近20mm / 远30mm）；VIM x轴偏移（2mm / 4mm）。<br><br><strong>因变量：</strong>靶面辐照度分布（峰值、顶宽$`W_t`$、底宽$`W_b`$）、BGA表面温度分布、掩模边缘衍射强度衰减。<br><br><strong>控制变量：</strong>FILSS光学系统固定、BGA 35×35mm、光学功率69.8W、透镜材料。<br><br><strong>材料体系：</strong>BGA光子SMT组件 + 无铅焊料（熔点~217°C）。 |
| <strong>6. 核心结论</strong> | <strong>仿真：</strong>PID稳态误差17-22°C；ADRC近乎消除，峰值过冲约10°C。<br><br><strong>实验：</strong>PID峰值误差约20°C且控制信号剧烈振荡；<strong>ADRC峰值误差仅约4°C</strong>。<br><br><strong>能效：</strong>ADRC的$`ITAE_{eff}=108.62`$ vs $`PID=123.74`$，<strong>改善12.2%</strong>。<br><br><strong>应用验证：</strong>损坏BGA经局部回流后焊球恢复球形，峰值244±2°C，TAL=58s。 | <strong>PCB不均匀性：</strong>卤素灯<strong>45-55°C</strong>（34-36%）；陶瓷仅8-13°C（3-4%）。<br><br><strong>壳体温差：</strong>陶瓷下BGA差28-32°C，QFP差24-26°C；卤素灯壳体温差90-100°C（26-44%）。<br><br><strong>加热速率：</strong>卤素灯峰值20-22°C/s，陶瓷仅3-4°C/s——卤素灯快<strong>5-7倍</strong>（71-74%更高）。<br><br><strong>间距效应：</strong>每增10mm，短波速率减半，中波降50%；间距>20mm时加热趋于均匀（<5-7%）。最优间距20-25mm。<br><br><strong>结论：</strong>卤素灯适合高产能自动化线，陶瓷适合返修站。 | <strong>IMC厚度：</strong>底部IR最薄<strong>$`1.641 \mu\mathrm{m}`$</strong>；双侧$`2.573 \mu\mathrm{m}`$；顶部最厚$`2.715 \mu\mathrm{m}`$。<br><br><strong>IMC粗糙度$`R_{rms}`$：</strong>底部最小$`0.901 \mu\mathrm{m}`$；顶部$`1.296 \mu\mathrm{m}`$；双侧最大$`1.628 \mu\mathrm{m}`$。<br><br><strong>机制：</strong>顶部/双侧加热时焊球直接受红外辐射，温度梯度大，热迁移促进IMC生长；底部加热经基板间接加热，温度梯度小，IMC生长受限。<br><br><strong>关键发现：</strong>测温点位置至关重要——所测温度≠实际供给热量；底部加热产生最薄最平滑IMC层，有利于焊点可靠性。 | <strong>炉膛不均匀性：</strong>对称区温度比中心低<strong>$`1.2`$倍</strong>；超温偏差5-13°C，低温偏差20-30°C。<br><br><strong>辐射主导：</strong>低Re时FPCB表面温度$`\gt 540`$K，比炉温高$`40\sim50`$K；$`Re=1.33\times10^5`$时偏差趋于5%。<br><br><strong>位置效应：</strong>后位（近风扇）温度更高但不推荐；前位（中部）为推荐位置，峰值$`523\sim533`$K可达目标。<br><br><strong>厚度效应：</strong>25μm温差最小$`1.37`$K；75μm最大$`11.61`$K；推荐刚度范围<strong>40-100μm</strong>。<br><br><strong>力学：</strong>屈服强度85MPa，杨氏模量$`5.3\pm0.8`$ GPa。<br><br><strong>验证：</strong>实验-仿真偏差<2%。 | <strong>辐照度：</strong>两距离峰值相近（$`24.4 \mathrm{mW/mm^2}`$）；底宽差异显著——近距$`W_b=6.375`$mm（占面积18%），远距$`W_b=8.625`$mm（占25%）；底辐照度约为峰值<strong>50%</strong>（$`11.08`$ vs $`10.75 \mathrm{mW/mm^2}`$）。<br><br><strong>热分布：</strong>与辐照度仿真一致；近距离峰值$`163`$°C, 底温$`142.5`$°C；远距离峰值$`170`$°C, 底温$`143.8`$°C——底温约为峰值的50%。<br><br><strong>关键限制：</strong>峰值温度163-170°C仅处于<strong>预热区</strong>，不足以达回流区（≥217°C）。<br><br><strong>AR涂层方案：</strong>加增透膜可使温度提升40%，达228-238°C进入回流区。 |
| <strong>7. 批判/局限</strong> | <strong>作者声明：</strong>①仿真精度优于实验；②ADRC控制信号变异性略大；③需后续机械可靠性测试。<br><br><strong>推断局限：</strong>①仅6×5mm小型BGA，未验证大尺寸；②J型热电偶接触式测量引入滞后；③集中参数模型假设$`Bi \lt 0.1`$对大热质量组件可能不成立；④未与Smith预估器等其他时滞方法对比；⑤单点测温无法反映面内温度分布；⑥未做焊点力学表征。 | <strong>作者声明：</strong>未明确声明局限。<br><br><strong>推断局限：</strong>①仅仿真+少量实验，未做统计显著性分析；②使用POS61含铅钎料（非无铅），与RoHS趋势脱节；③仅40×40mm小板；④灰体漫辐射假设未考虑实际器件表面发射率差异；⑤未量化焊点力学可靠性，仅外观检查；⑥未讨论温度曲线跟踪精度。 | <strong>作者声明：</strong>①热电偶置于顶部，底部加热时焊球实际温度低于反馈温度；②Marangoni效应对IMC影响的定量比例未知；③IMC粗糙度与厚度的关联需深入研究。<br><br><strong>推断局限：</strong>①样本量未明确，未报告统计检验；②仅单一焊球尺寸和合金；③IMC测量为2D截面，未做3D形貌；④未进行焊点力学可靠性测试；⑤未分离冷却方向的影响；⑥仅陶瓷IR加热器，未对比卤素灯。 | <strong>作者声明：</strong>①仅台式炉构型，未扩展至其他炉型；②未考虑FPCB翘曲对对流与红外吸收的影响。<br><br><strong>推断局限：</strong>①半炉对称假设可能低估非对称扰动；②DO辐射模型未与其他模型直接对比验证；③IR灯热流用多项式近似，实际光谱时变性未建模；④FPCB发射率固定0.9；⑤仅单面FPCB；⑥力学性能仅拉伸，未做热循环/跌落；⑦Re范围有限。 | <strong>作者声明：</strong>①VIM位置处温度不足（~200°C），需AR涂层辅助；②仅分析直边VIM衍射，未涉及其他掩模形状。<br><br><strong>推断局限：</strong>①仅2种距离工况，未系统扫描参数空间；②未做焊点质量定量表征（剪切力、IMC、X射线）；③AR涂层方案仅为推断，未实验验证；④热像仪测量未报告发射率校准；⑤仅35×35mm单一BGA尺寸；⑥VIM材料热稳定性未讨论；⑦"50%强度→50%温度"的线性假设物理上过于简化（辐射为$`T^4`$关系）。 |
| <strong>8. 情境/背景</strong> | <strong>应用领域：</strong>SMT电子器件回流焊接与返修，尤其是BGA局部选择性加热。<br><br><strong>前序工作：</strong>Anguiano等（2013, Opt. Express）QTH灯+光学装置聚焦红外加热——本文直接延续并补充闭环控制。<br><br><strong>技术路线：</strong>聚焦红外焊接路线的最新进展（2025），从光学设计→掩模整形→闭环控制的完整链条终点。 | <strong>应用领域：</strong>SMD电子组件的贴装与返修拆卸。<br><br><strong>行业相关性：</strong>红外焊接具局部加热、缩短加热时间、降低损伤风险等优势，但热源选型是关键。<br><br><strong>前序工作：</strong>Zvorykin（1985）红外反射加热炉；Lanin（2007）局部红外加热为最佳方法。<br><br><strong>定位：</strong>5篇中最早（2017），是整个文献集的热源选型基石。 | <strong>应用领域：</strong>BGA封装球贴装/重球工艺，关乎微电子封装焊点质量与可靠性。<br><br><strong>行业相关性：</strong>BGA/QFN高密度封装焊盘多、尺寸小，焊接质量突出；IMC层过厚降低机械强度。<br><br><strong>前序工作：</strong>Wang & Panton（2005）热流方向反转减少空洞；Zhao等（2015）温度梯度下热迁移；Otáhal等（2017, EMPC）前期加热方向对晶体取向的影响——本文是EMPC 2017工作的延续。 | <strong>应用领域：</strong>台式红外回流焊炉中FPCB基板SMT回流焊接工艺优化。<br><br><strong>行业相关性：</strong>电子设备小型化下FPCB因轻、薄、柔性成为刚性板替代品；聚酰亚胺（PI, $`T_g=300`$°C）等基材热物性差异大。<br><br><strong>前序工作：</strong>Najib等（3D IR炉+风扇CFD, FR-4 RPCB过热542K）——本文直接延续并补FPCB。FRGS基金支持。 | <strong>应用领域：</strong>光子SMT组件（集成光子器件的BGA）的非接触选择性焊接。<br><br><strong>行业相关性：</strong>电子工业趋向在IC中集成光模块以提升带宽（"Optics on Board"）；光子+半导体材料组合使热分布沿IC变化，传统覆盖整面加热不适用。<br><br><strong>前序工作：</strong>Anguiano等（2013, Opt. Express）FILSS覆盖整个BGA——本文用VIM实现选择性局部分布。PRODEP基金支持。 |
| <strong>9. 定位/对比</strong> | <strong>5篇中唯一的控制算法论文</strong>，与P5（可变掩模）同属墨西哥UABC研究组（第一作者相同），是P5的后续演进。<br><br>P5解决光/热分布形状问题，P1在此基础上增加闭环温度跟踪控制。<br><br>与P2（热源对比）：P1使用短波QTH卤素灯，验证了聚焦卤素灯的局部加热优势。<br><br>与P3（热流方向）：P1仅用顶部单向加热，未涉及热流方向对IMC的影响。<br><br>与P4（FPCB台式炉）：P1是局部聚焦加热（光学级），P4是炉膛级CFD建模。 | <strong>5篇中最基础的热源选型研究</strong>，为其他4篇提供热源类型的量化对比基准。<br><br>与P1（ADRC）：P1使用短波QTH卤素灯（本文KGM同类），本文解释了卤素灯加热快但不均——正是P1需闭环控制补偿的根源。<br><br>与P3（热流方向）：P3使用陶瓷加热器（本文Elstein同类），本文为P3选择中波陶瓷源提供了均匀性依据。<br><br>与P4（FPCB台式炉）：P4的炉膛使用红外灯管+风扇，属本文"混合"思路的延伸。<br><br>与P5（可变掩模）：P5用QTH灯+光学匀化器解决卤素灯不均问题。 | <strong>5篇中唯一的微观组织/机理研究</strong>，与宏观热场研究互补。<br><br>与P1（ADRC）：P1仅用顶部单向加热，本文揭示顶部加热产生最厚IMC（$`2.715 \mu\mathrm{m}`$）——暗示P1的顶部加热策略对IMC可能非最优。<br><br>与P2（热源对比）：本文使用陶瓷IR加热器，间接采用P2的均匀性优势结论，但焦点从热场下沉至IMC微观组织。<br><br>与P4（FPCB台式炉）：P4关注炉膛级温度分布，本文关注单焊点级IMC——不同尺度。<br><br>与P5（可变掩模）：P5通过掩模控制热分布形状，本文通过热流方向控制IMC——均为"热场调控→焊点质量"但调控维度不同。 | <strong>5篇中唯一的炉膛级CFD系统建模研究，也是唯一聚焦FPCB柔性基板</strong>，期刊层级最高（Q2, IF=2.5）。<br><br>与P1（ADRC）：P1是局部聚焦加热（光学级, 6×5mm），P4是炉膛级整体加热（310×195mm）——两种系统架构。<br><br>与P2（热源对比）：P4使用红外灯管+风扇对流，属P2"混合加热"思路延伸。<br><br>与P3（热流方向）：P4的IR灯置于顶部（单向），P3指出顶部加热IMC最厚——暗示P4可考虑增加底部加热。<br><br>与P5（可变掩模）：P5用掩模精控局部热分布，P4用风扇+位置调控整体热场——不同尺度热场调控。 | <strong>5篇中唯一的光学设计/辐照度调控研究</strong>，与P1（ADRC）同属墨西哥UABC研究组，是P1的直接前序工作。<br><br>P1的FILSS光学系统正是本文的延续，P1在此基础上增加ADRC闭环控制。<br><br>与P2（热源对比）：本文使用QTH卤素灯，通过光学匀化器+VIM解决P2指出的卤素灯热场不均问题。<br><br>与P3（热流方向）：本文为顶部单向聚焦加热，未涉及热流方向对IMC的影响。<br><br>与P4（FPCB台式炉）：本文为局部聚焦加热（光学级），P4为炉膛级整体加热。<br><br><strong>本文代表聚焦红外焊接路线的光学整形阶段，上承热源选型（P2），下接闭环控制（P1）。</strong> |

## 详细对比（逐篇展开）

> 由于 GitHub 表格列宽有限，下方逐篇展开各维度详情，公式以 LaTeX 渲染。

### P1 - ADRC原型 (2025)

#### 1. 基础信息

**标题：**A prototype for infrared soldering of electronic devices using the active disturbance rejection control structure<br><br>**作者：**R C. Anguiano Cota, D I. Rosas Almeida, J R. Herrera García<br><br>**期刊：***Engineering Research Express* 2025, 7(4): 045392<br><br>**DOI：**10.1088/2631-8695/ae24c8<br><br>**分区：**ESCI Q3, IF=1.8<br><br>**机构：**Universidad Autónoma de Baja California, 墨西哥

#### 2. 核心研究问题

针对红外焊接热系统存在**输入时滞（input delay）**且缺乏精确数学模型的控制难题，探索将**自抗扰控制（ADRC）**用于电子器件焊接温度曲线的轨迹跟踪。<br><br>**研究缺口：**现有聚焦红外焊接系统普遍缺乏闭环温度控制，导致热不均匀和焊锡珠问题；传统时滞系统控制方法（Smith预估器、Padé近似）依赖精确模型。<br><br>**核心假设：**通过一阶Padé近似分析，输入时滞可视为有界外部扰动，由ADRC实时估计并补偿，无需对时滞做多项式近似。

#### 3. 理论视角/机制

**（1）红外辐射加热：**QTH卤素灯遵循**斯特藩-玻尔兹曼定律**$`P=\varepsilon\sigma A T^4`$，辐射经椭圆镀金反射镜汇聚。<br><br>**（2）集中参数热模型：**当 $`Bi \lt 0.1`$ 时，焊接区视为均温体，$`mc_p \frac{dT}{dt}=q_{in}-hA(T-T_\infty)`$，热时间常数 $`\tau_{th}=\frac{mc_p}{hA}`$。<br><br>**（3）时滞扰动化：**一阶Padé近似 $`e^{-\tau s}\approx\frac{2-\tau s}{2+\tau s}`$ 将系统转化为非最小相位系统，人工状态变量视为外部扰动。<br><br>**（4）ADRC框架：****扩张状态观测器（ESO）**实时估计扰动，结合滑模项实现全局渐近稳定。

#### 4. 研究方法

**装置：**QTH卤素灯（64635 HLX, 150W, MR16）+ 椭圆镀金反射镜 + 准直透镜（非球面SiO₂, f=40mm）+ 聚焦透镜（双凸SiO₂, f=50mm），焦点达1200°C；加热6×5mm BGA。<br><br>**控制系统：**NI cRIO-9074 + NI 9211热电偶模块（24-bit, 14 S/s）+ J型热电偶 + NI 9263模拟输出（16-bit）+ LabVIEW，步长0.001s。<br><br>**辨识：**3V阶跃信号测得$`\tau=1.603`$s，$`a=0.094339, b=4.4838`$，$`\tau_{th}=10.61`$s。<br><br>**对比实验：**ADRC（$`c_1=200, c_2=50, c_3=70, k=0.9`$）vs PID（$`k_p=0.5, k_i=0.2, k_d=0.2`$）。<br><br>**验证：**对损坏BGA执行局部返修，峰值244±2°C，TAL=58s。

#### 5. 关键变量

**自变量：**控制器类型（ADRC vs PID）；控制增益参数。<br><br>**因变量：**温度跟踪误差（°C）、峰值温度误差、控制效率$`ITAE_{eff}`$、控制信号振荡特性。<br><br>**控制变量：**QTH光源150W、光学配置固定、BGA 6×5mm、四阶段回流曲线。<br><br>**材料体系：**无铅焊料（熔点~217°C）、BGA封装、FR4基板。

#### 6. 核心结论

**仿真：**PID稳态误差17-22°C；ADRC近乎消除，峰值过冲约10°C。<br><br>**实验：**PID峰值误差约20°C且控制信号剧烈振荡；**ADRC峰值误差仅约4°C**。<br><br>**能效：**ADRC的$`ITAE_{eff}=108.62`$ vs $`PID=123.74`$，**改善12.2%**。<br><br>**应用验证：**损坏BGA经局部回流后焊球恢复球形，峰值244±2°C，TAL=58s。

#### 7. 批判/局限

**作者声明：**①仿真精度优于实验；②ADRC控制信号变异性略大；③需后续机械可靠性测试。<br><br>**推断局限：**①仅6×5mm小型BGA，未验证大尺寸；②J型热电偶接触式测量引入滞后；③集中参数模型假设$`Bi \lt 0.1`$对大热质量组件可能不成立；④未与Smith预估器等其他时滞方法对比；⑤单点测温无法反映面内温度分布；⑥未做焊点力学表征。

#### 8. 情境/背景

**应用领域：**SMT电子器件回流焊接与返修，尤其是BGA局部选择性加热。<br><br>**前序工作：**Anguiano等（2013, Opt. Express）QTH灯+光学装置聚焦红外加热——本文直接延续并补充闭环控制。<br><br>**技术路线：**聚焦红外焊接路线的最新进展（2025），从光学设计→掩模整形→闭环控制的完整链条终点。

#### 9. 定位/对比

**5篇中唯一的控制算法论文**，与P5（可变掩模）同属墨西哥UABC研究组（第一作者相同），是P5的后续演进。<br><br>P5解决光/热分布形状问题，P1在此基础上增加闭环温度跟踪控制。<br><br>与P2（热源对比）：P1使用短波QTH卤素灯，验证了聚焦卤素灯的局部加热优势。<br><br>与P3（热流方向）：P1仅用顶部单向加热，未涉及热流方向对IMC的影响。<br><br>与P4（FPCB台式炉）：P1是局部聚焦加热（光学级），P4是炉膛级CFD建模。

---

### P2 - 红外热源对比 (2017)

#### 1. 基础信息

**标题：**Comparative Effectiveness of Infrared Heat Sources for Mounting and Dismounting Electronic Modules<br><br>**作者：**V. L. Lanin, A. I. Lappo<br><br>**期刊：***Surface Engineering and Applied Electrochemistry* 2017, 53(4)<br><br>**DOI：**10.3103/S106837551704010X<br><br>**分区：**SCIE Q4, IF=0.7, EI<br><br>**机构：**Belarusian State University of Informatics and Radioelectronics, 白俄罗斯

#### 2. 核心研究问题

针对电子模块贴装与拆卸中**红外热源选择缺乏系统量化依据**的问题，评估**短波（近红外0.7-1.5μm）**与**中波（中红外2-10μm）**两类热源的有效性差异。<br><br>**具体问题：**①两种热源在PCB和元器件壳体上的热场不均匀性如何？②加热器间距对加热速率和均匀性的影响？③何种热源适用于自动化产线、何种适用于返修站？<br><br>**缺口：**热源类型与加热均匀性/速率的定量权衡关系尚不明确。

#### 3. 理论视角/机制

**红外辐射传热：****普朗克定律**给出光谱辐射率；**维恩位移定律**$`\lambda_{max}\cdot T=2.898\times10^{-3}`$ m·K 表明温度越高则峰值波长越短；**斯特藩-玻尔兹曼定律**$`Q=F_s\varepsilon\sigma S_h(T_h^4-T_s^4)`$。<br><br>**工程原理：**短波卤素灯温度高、波长短、加热速率快但热场集中不均匀；中波陶瓷加热器温度低、加热均匀但响应慢——存在**速率与均匀性的固有权衡**。

#### 4. 研究方法

**仿真：**SolidWorks 2012 Flow Simulation，有限元热场仿真，灰体漫辐射假设，40×40mm四层PCB贴装BGA/QFP/SMD器件，加热器距板20mm。<br><br>**实验装置：**自制红外焊接站，顶部加热（可切换两种热源）+ 底部预热（2×KI 220-1000卤素灯, 1000W）+ 冷却风扇 + MSP430微控制器 + KhK型热电偶（20Hz采样, 10-bit ADC）。<br><br>**对比热源：**①KGM 30/300卤素灯（近红外0.7-1.5μm）；②Elstein SHTS/4陶瓷加热器（中红外2-10μm）。<br><br>**间距变化：**10/20/30/40mm。

#### 5. 关键变量

**自变量：**热源类型（KGM卤素灯 vs Elstein陶瓷）；加热器与PCB间距（10/20/30/40mm）。<br><br>**因变量：**PCB加热不均匀性（°C）、元器件壳体温度不均匀性（°C）、加热速率（°C/s）。<br><br>**控制变量：**PCB 40×40mm四层、底部预热1000W、器件类型（BGA/QFP/SMD）、POS61锡铅钎料。<br><br>**材料体系：**FR4 PCB + 多类型封装 + POS61含铅钎料。

#### 6. 核心结论

**PCB不均匀性：**卤素灯**45-55°C**（34-36%）；陶瓷仅8-13°C（3-4%）。<br><br>**壳体温差：**陶瓷下BGA差28-32°C，QFP差24-26°C；卤素灯壳体温差90-100°C（26-44%）。<br><br>**加热速率：**卤素灯峰值20-22°C/s，陶瓷仅3-4°C/s——卤素灯快**5-7倍**（71-74%更高）。<br><br>**间距效应：**每增10mm，短波速率减半，中波降50%；间距>20mm时加热趋于均匀（<5-7%）。最优间距20-25mm。<br><br>**结论：**卤素灯适合高产能自动化线，陶瓷适合返修站。

#### 7. 批判/局限

**作者声明：**未明确声明局限。<br><br>**推断局限：**①仅仿真+少量实验，未做统计显著性分析；②使用POS61含铅钎料（非无铅），与RoHS趋势脱节；③仅40×40mm小板；④灰体漫辐射假设未考虑实际器件表面发射率差异；⑤未量化焊点力学可靠性，仅外观检查；⑥未讨论温度曲线跟踪精度。

#### 8. 情境/背景

**应用领域：**SMD电子组件的贴装与返修拆卸。<br><br>**行业相关性：**红外焊接具局部加热、缩短加热时间、降低损伤风险等优势，但热源选型是关键。<br><br>**前序工作：**Zvorykin（1985）红外反射加热炉；Lanin（2007）局部红外加热为最佳方法。<br><br>**定位：**5篇中最早（2017），是整个文献集的热源选型基石。

#### 9. 定位/对比

**5篇中最基础的热源选型研究**，为其他4篇提供热源类型的量化对比基准。<br><br>与P1（ADRC）：P1使用短波QTH卤素灯（本文KGM同类），本文解释了卤素灯加热快但不均——正是P1需闭环控制补偿的根源。<br><br>与P3（热流方向）：P3使用陶瓷加热器（本文Elstein同类），本文为P3选择中波陶瓷源提供了均匀性依据。<br><br>与P4（FPCB台式炉）：P4的炉膛使用红外灯管+风扇，属本文"混合"思路的延伸。<br><br>与P5（可变掩模）：P5用QTH灯+光学匀化器解决卤素灯不均问题。

---

### P3 - 热流方向 (2018)

#### 1. 基础信息

**标题：**Influence of heat flow direction on solder ball interfacial layer<br><br>**作者：**Alexandr Otáhal, Ivan Szendiuch<br><br>**期刊：***Journal of Electrical Engineering* 2018, 69(4): 305-310<br><br>**DOI：**10.2478/jee-2018-0043<br><br>**分区：**SCIE Q4, IF=0.8, EI<br><br>**机构：**Brno University of Technology, 捷克

#### 2. 核心研究问题

针对BGA封装球贴装工艺中**热流方向这一被忽视的参数**，研究不同热流方向（底部/顶部/双侧红外加热）对SAC305焊球与焊盘间**金属间化合物层（IMC layer）**厚度与粗糙度的影响。<br><br>**缺口：**现有文献关注材料兼容性、封装设计、温度曲线等，但**热流方向对焊点微观结构的影响尚未充分探索**。<br><br>**假设：**热流方向通过改变焊球内部温度梯度，影响热迁移和液态焊料流动，从而改变IMC层形成与生长。

#### 3. 理论视角/机制

**IMC形成：**SAC305/ENIG体系中，$`\eta`$相（$`\mathrm{Cu}_6\mathrm{Sn}_5`$）形成快于$`\varepsilon`$相（$`\mathrm{Cu}_3\mathrm{Sn}`$）；三元化合物$`(\mathrm{Ni},\mathrm{Cu})_6\mathrm{Sn}_5`$生长快于$`(\mathrm{Ni},\mathrm{Cu})_3\mathrm{Sn}_4`$；IMC厚度随每次回流累积增长，超过阈值后机械强度下降。<br><br>**热流方向效应：**Wang & Panton（2005）证实热流方向反转可减少空洞；Zhao等发现温度梯度下IMC热端薄冷端厚（热迁移效应：Cu向热端迁移，Sn向冷端迁移）。<br><br>**液态焊料流动：**Marangoni效应与自然对流促进IMC晶体生长与剥落。<br><br>**加热因子：**$`Q_\eta=\int(T(t)-T_m)dt`$保证不同方向的热输入可比性，本文取$`Q_\eta=308`$ s·°C。

#### 4. 研究方法

**设备：**Power Tower焊接站，2个80×80mm陶瓷红外加热器（水平对置，不锈钢罩）+ 80×80mm冷却风扇。<br><br>**三种方向：**①底部IR；②顶部IR；③双侧IR。<br><br>**样品：**Dummy BGA（11×11×1.5mm, FR4, 黑色阻焊层, ENIG, 焊盘400μm）+ 500μm SAC305焊球 + SMF-08焊剂。<br><br>**温度曲线：**峰值235°C，升温1.2°C/s，TAL 30s，$`Q_\eta=308`$ s·°C；K型热电偶+PID控温。<br><br>**表征：**金相截面（IPC-TM-650 2.1.1选择性腐蚀）→光学显微镜→ImageJ分析IMC厚度（MSL）+粗糙度（$`R_{rms}`$）；Tescan MIRA II SEM+EDS验证成分。

#### 5. 关键变量

**自变量：**热流方向（底部IR / 顶部IR / 双侧IR）——3水平。<br><br>**因变量：**IMC层平均厚度（MSL, μm）、IMC层均方根粗糙度$`R_{rms}`$（μm）。<br><br>**控制变量：**温度曲线统一（峰值235°C, TAL 30s, $`Q_\eta=308`$）、焊球SAC305 500μm、焊剂SMF-08、焊盘400μm ENIG、Dummy BGA 11×11mm。<br><br>**材料体系：**SAC305无铅焊料 / ENIG表面处理 / FR4基板。

#### 6. 核心结论

**IMC厚度：**底部IR最薄**$`1.641 \mu\mathrm{m}`$**；双侧$`2.573 \mu\mathrm{m}`$；顶部最厚$`2.715 \mu\mathrm{m}`$。<br><br>**IMC粗糙度$`R_{rms}`$：**底部最小$`0.901 \mu\mathrm{m}`$；顶部$`1.296 \mu\mathrm{m}`$；双侧最大$`1.628 \mu\mathrm{m}`$。<br><br>**机制：**顶部/双侧加热时焊球直接受红外辐射，温度梯度大，热迁移促进IMC生长；底部加热经基板间接加热，温度梯度小，IMC生长受限。<br><br>**关键发现：**测温点位置至关重要——所测温度≠实际供给热量；底部加热产生最薄最平滑IMC层，有利于焊点可靠性。

#### 7. 批判/局限

**作者声明：**①热电偶置于顶部，底部加热时焊球实际温度低于反馈温度；②Marangoni效应对IMC影响的定量比例未知；③IMC粗糙度与厚度的关联需深入研究。<br><br>**推断局限：**①样本量未明确，未报告统计检验；②仅单一焊球尺寸和合金；③IMC测量为2D截面，未做3D形貌；④未进行焊点力学可靠性测试；⑤未分离冷却方向的影响；⑥仅陶瓷IR加热器，未对比卤素灯。

#### 8. 情境/背景

**应用领域：**BGA封装球贴装/重球工艺，关乎微电子封装焊点质量与可靠性。<br><br>**行业相关性：**BGA/QFN高密度封装焊盘多、尺寸小，焊接质量突出；IMC层过厚降低机械强度。<br><br>**前序工作：**Wang & Panton（2005）热流方向反转减少空洞；Zhao等（2015）温度梯度下热迁移；Otáhal等（2017, EMPC）前期加热方向对晶体取向的影响——本文是EMPC 2017工作的延续。

#### 9. 定位/对比

**5篇中唯一的微观组织/机理研究**，与宏观热场研究互补。<br><br>与P1（ADRC）：P1仅用顶部单向加热，本文揭示顶部加热产生最厚IMC（$`2.715 \mu\mathrm{m}`$）——暗示P1的顶部加热策略对IMC可能非最优。<br><br>与P2（热源对比）：本文使用陶瓷IR加热器，间接采用P2的均匀性优势结论，但焦点从热场下沉至IMC微观组织。<br><br>与P4（FPCB台式炉）：P4关注炉膛级温度分布，本文关注单焊点级IMC——不同尺度。<br><br>与P5（可变掩模）：P5通过掩模控制热分布形状，本文通过热流方向控制IMC——均为"热场调控→焊点质量"但调控维度不同。

---

### P4 - FPCB台式炉 (2021)

#### 1. 基础信息

**标题：**Investigations of Infrared Desktop Reflow Oven with FPCB Substrate during Reflow Soldering Process<br><br>**作者：**M I. Ahmad, M S. Abdul Aziz, M Z. Abdullah, et al.<br><br>**期刊：***Metals* 2021, 11(8): 1155<br><br>**DOI：**10.3390/met11081155<br><br>**分区：**SCIE Q2, IF=2.5, EI<br><br>**机构：**Universiti Sains Malaysia 等

#### 2. 核心研究问题

针对**台式红外回流焊炉中FPCB基板回流焊接缺乏系统热场认知**的问题，通过CFD仿真+实验研究炉膛内温度分布特性及FPCB受热行为。<br><br>**具体问题：**①炉膛内温度分布是否均匀？不均匀性成因？②风扇转速（Re）、FPCB位置、FPCB厚度如何影响表面温度？③何种位置与厚度组合可获符合JSTD-020E的回流曲线？<br><br>**缺口：**前人已仿真FR-4 RPCB台式炉热场，但**未考虑FPCB及其最优放置位置**——FPCB因柔性、薄、热物性差异大，热行为与刚性板不同。

#### 3. 理论视角/机制

**CFD传热框架：**①连续性方程；②动量守恒（含重力体积力）；③能量方程（含IR热流源项）；④**离散坐标辐射模型（DO model）**求解辐射传输方程RTE，适合局部IR灯热源；⑤**RNG k-ε湍流模型**（含旋流修正，$`\alpha_s=0.07`$），适合离心风扇旋流。<br><br>**工程原理：**台式炉IR灯为顶部局部热源，离心风扇产生旋流强制对流；低风速辐射主导（FPCB温度高$`40\sim50`$K），高风速对流增强。<br><br>**材料理论：**FPCB用聚酰亚胺（PI, $`T_g=300`$°C）+Cu层，53μm，密度$`3839 \mathrm{kg/m^3}`$，导热0.3 W/mK，比热421 J/kgK。

#### 4. 研究方法

**仿真：**ANSYS Fluent 18，有限体积法，半炉几何（310×195×190mm），SIMPLE算法，二阶迎风，674,521元网格（偏差0.09%）。<br><br>**边界条件：**风扇150 rad/s（115mm直径离心风扇），6支IR灯（各100W, ~5400 W/m²），炉壁发射率0.1，FPCB发射率0.9。<br><br>**实验：**台式炉（6支红外灯管+2风扇）+ 60根K型热电偶（±2.2°C, 4s间隔）+ PID控温 + JSTD-020E回流曲线（预热140°C/浸泡180°C/回流207°C）。<br><br>**变量扫描：**Re $`0.43\times10^5\sim2.05\times10^5`$；FPCB厚度25/53/75/100/125μm；前75mm/后135mm位置。<br><br>**FPCB拉伸试验：**ASTM D368, INSTRON 3367, 50mm/min。

#### 5. 关键变量

**自变量：**①风扇转速（Re, $`0.43\times10^5\sim2.05\times10^5`$）；②FPCB放置位置（前75mm/后135mm）；③FPCB厚度（25/53/75/100/125μm）。<br><br>**因变量：**FPCB表面温度分布（K）、炉膛空气温度均匀性、温度偏差、von Mises应力、杨氏模量与屈服强度。<br><br>**控制变量：**炉膛几何、IR灯功率（6×100W）、回流曲线设定、FPCB材料（PI+Cu, 53μm）。<br><br>**材料体系：**FPCB（聚酰亚胺+Cu）+ 无铅SAC焊料。

#### 6. 核心结论

**炉膛不均匀性：**对称区温度比中心低**$`1.2`$倍**；超温偏差5-13°C，低温偏差20-30°C。<br><br>**辐射主导：**低Re时FPCB表面温度$`\gt 540`$K，比炉温高$`40\sim50`$K；$`Re=1.33\times10^5`$时偏差趋于5%。<br><br>**位置效应：**后位（近风扇）温度更高但不推荐；前位（中部）为推荐位置，峰值$`523\sim533`$K可达目标。<br><br>**厚度效应：**25μm温差最小$`1.37`$K；75μm最大$`11.61`$K；推荐刚度范围**40-100μm**。<br><br>**力学：**屈服强度85MPa，杨氏模量$`5.3\pm0.8`$ GPa。<br><br>**验证：**实验-仿真偏差<2%。

#### 7. 批判/局限

**作者声明：**①仅台式炉构型，未扩展至其他炉型；②未考虑FPCB翘曲对对流与红外吸收的影响。<br><br>**推断局限：**①半炉对称假设可能低估非对称扰动；②DO辐射模型未与其他模型直接对比验证；③IR灯热流用多项式近似，实际光谱时变性未建模；④FPCB发射率固定0.9；⑤仅单面FPCB；⑥力学性能仅拉伸，未做热循环/跌落；⑦Re范围有限。

#### 8. 情境/背景

**应用领域：**台式红外回流焊炉中FPCB基板SMT回流焊接工艺优化。<br><br>**行业相关性：**电子设备小型化下FPCB因轻、薄、柔性成为刚性板替代品；聚酰亚胺（PI, $`T_g=300`$°C）等基材热物性差异大。<br><br>**前序工作：**Najib等（3D IR炉+风扇CFD, FR-4 RPCB过热542K）——本文直接延续并补FPCB。FRGS基金支持。

#### 9. 定位/对比

**5篇中唯一的炉膛级CFD系统建模研究，也是唯一聚焦FPCB柔性基板**，期刊层级最高（Q2, IF=2.5）。<br><br>与P1（ADRC）：P1是局部聚焦加热（光学级, 6×5mm），P4是炉膛级整体加热（310×195mm）——两种系统架构。<br><br>与P2（热源对比）：P4使用红外灯管+风扇对流，属P2"混合加热"思路延伸。<br><br>与P3（热流方向）：P4的IR灯置于顶部（单向），P3指出顶部加热IMC最厚——暗示P4可考虑增加底部加热。<br><br>与P5（可变掩模）：P5用掩模精控局部热分布，P4用风扇+位置调控整体热场——不同尺度热场调控。

---

### P5 - 可变辐照掩模 (2021)

#### 1. 基础信息

**标题：**The effect of variable irradiation mask in Focused Infrared Light Soldering Systems for electronic components<br><br>**作者：**Citlalli Anguiano, Kiyoshi Natzu, Marco Félix, et al.<br><br>**期刊：***Optik* 2021, 242: 167298<br><br>**DOI：**10.1016/j.ijleo.2021.167298<br><br>**分区：**EI（已被SCIE剔除）<br><br>**机构：**Universidad Autónoma de Baja California / CICESE, 墨西哥

#### 2. 核心研究问题

针对**光子SMT组件有限面积焊接**中，现有聚焦红外光焊接系统（FILSS）光/热分布覆盖整个BGA面积、无法匹配新型光子器件局部热需求的问题，研究在FILSS输出端插入**可变辐照掩模（VIM）**后能否获得特定尺寸与形状的辐照度和热分布。<br><br>**具体问题：**①VIM在近距离（20mm）与远距离（30mm）时靶面辐照度分布差异？②VIM边缘非相干光衍射如何影响热分布？③VIM位置处温度能达到焊接所需范围吗？

#### 3. 理论视角/机制

**辐射传热：**$`Q_{IR}=V\varepsilon_s\Gamma_i\Gamma_{OE}\alpha_{SMT}\sigma(T_S^4-T_{SMT}^4)`$，含几何视因子V、各界面透射率；$`\sigma=5.67\times10^{-12}`$ W/cm²/K⁴。<br><br>**传导传热：**$`Q_C=KA\frac{T_1-T_2}{\Delta x}`$，K为热导率，A为截面积。<br><br>**光学衍射：**VIM直边对非相干光产生衍射，强度分布$`I(r)=\frac{1}{2}+\frac{1}{\pi}\mathrm{Si}(r)-\frac{1-\cos(r)}{r}`$，其中$`r=\frac{2a\pi y}{(1+m)\lambda f}`$；直边零位处强度约为总强度**50%**。<br><br>**掩模机制：**VIM阻挡部分辐射→边缘衍射使强度渐变→靶面获得特定形状光分布→辐射衰减50%对应导热衰减。<br><br>**成像匀化器：**FILSS基于成像匀化器在靶面产生均匀辐照度，VIM"裁剪"该均匀分布。

#### 4. 研究方法

**仿真：**Zemax非序列模式，光源为椭圆反射镜+灯丝（69.8W光功率），透镜用UV级熔融石英与B270玻璃。<br><br>**实验装置：**FILSS置于光学台，QTH钨卤素灯 + 成像匀化器光学系统 + VIM（光阻挡元件）+ 热像仪测热分布。<br><br>**两种工况：**①VIM近距离$`D_{z1}=20`$mm，x轴偏移$`D_{x1}=2`$mm；②VIM远距离$`D_{z2}=30`$mm，$`D_{x2}=4`$mm。<br><br>**靶面：**35×35mm BGA。<br><br>**重定位规则：**z轴每10mm偏移需x轴重定位约2mm。<br><br>**对比：**仿真辐照度与实测热分布一致性验证。

#### 5. 关键变量

**自变量：**VIM放置距离（近20mm / 远30mm）；VIM x轴偏移（2mm / 4mm）。<br><br>**因变量：**靶面辐照度分布（峰值、顶宽$`W_t`$、底宽$`W_b`$）、BGA表面温度分布、掩模边缘衍射强度衰减。<br><br>**控制变量：**FILSS光学系统固定、BGA 35×35mm、光学功率69.8W、透镜材料。<br><br>**材料体系：**BGA光子SMT组件 + 无铅焊料（熔点~217°C）。

#### 6. 核心结论

**辐照度：**两距离峰值相近（$`24.4 \mathrm{mW/mm^2}`$）；底宽差异显著——近距$`W_b=6.375`$mm（占面积18%），远距$`W_b=8.625`$mm（占25%）；底辐照度约为峰值**50%**（$`11.08`$ vs $`10.75 \mathrm{mW/mm^2}`$）。<br><br>**热分布：**与辐照度仿真一致；近距离峰值$`163`$°C, 底温$`142.5`$°C；远距离峰值$`170`$°C, 底温$`143.8`$°C——底温约为峰值的50%。<br><br>**关键限制：**峰值温度163-170°C仅处于**预热区**，不足以达回流区（≥217°C）。<br><br>**AR涂层方案：**加增透膜可使温度提升40%，达228-238°C进入回流区。

#### 7. 批判/局限

**作者声明：**①VIM位置处温度不足（~200°C），需AR涂层辅助；②仅分析直边VIM衍射，未涉及其他掩模形状。<br><br>**推断局限：**①仅2种距离工况，未系统扫描参数空间；②未做焊点质量定量表征（剪切力、IMC、X射线）；③AR涂层方案仅为推断，未实验验证；④热像仪测量未报告发射率校准；⑤仅35×35mm单一BGA尺寸；⑥VIM材料热稳定性未讨论；⑦"50%强度→50%温度"的线性假设物理上过于简化（辐射为$`T^4`$关系）。

#### 8. 情境/背景

**应用领域：**光子SMT组件（集成光子器件的BGA）的非接触选择性焊接。<br><br>**行业相关性：**电子工业趋向在IC中集成光模块以提升带宽（"Optics on Board"）；光子+半导体材料组合使热分布沿IC变化，传统覆盖整面加热不适用。<br><br>**前序工作：**Anguiano等（2013, Opt. Express）FILSS覆盖整个BGA——本文用VIM实现选择性局部分布。PRODEP基金支持。

#### 9. 定位/对比

**5篇中唯一的光学设计/辐照度调控研究**，与P1（ADRC）同属墨西哥UABC研究组，是P1的直接前序工作。<br><br>P1的FILSS光学系统正是本文的延续，P1在此基础上增加ADRC闭环控制。<br><br>与P2（热源对比）：本文使用QTH卤素灯，通过光学匀化器+VIM解决P2指出的卤素灯热场不均问题。<br><br>与P3（热流方向）：本文为顶部单向聚焦加热，未涉及热流方向对IMC的影响。<br><br>与P4（FPCB台式炉）：本文为局部聚焦加热（光学级），P4为炉膛级整体加热。<br><br>**本文代表聚焦红外焊接路线的光学整形阶段，上承热源选型（P2），下接闭环控制（P1）。**

---

## 关于公式渲染

本文档中的数学公式使用 LaTeX 语法。在 GitHub 上：

- 行内公式：`` $`E = mc^2`$ `` → $`E = mc^2`$
- 行间公式：`$$\frac{dT}{dt} = q$$` → $$\frac{dT}{dt} = q$$
- 如果公式未渲染，请确认你已登录 GitHub 账号（GitHub 对未登录用户可能不渲染公式）。
