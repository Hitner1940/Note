這份是幫你量身打造的 **Trigonometry Master Note (全章通一書)**。結合了三個章節（Trigonometric Ratios, Relations, and Applications）的所有精華，重點全部極度精簡，用點列式（bullet points）排版，方便你最快速度溫書、清 concept！

### Part 1: Trigonometric Ratios (基本三角比)

要搞定三角函數，第一步一定要分清直角三角形（Right-angled triangle）的三條邊：

- **Hypotenuse (斜邊)**：永遠是直角（$90^\circ$）對面的那條最長的邊 。
    
- **Opposite side (對邊)**：指定角 $\theta$ 正正對面的那條邊 。
    
- **Adjacent side (鄰邊)**：夾在指定角 $\theta$ 和直角之間的那條邊 。
    

#### 核心公式：SOH-CAH-TOA (老鼠拉龜必背口訣)

- **$\sin\theta = \frac{\text{Opposite (對)}}{\text{Hypotenuse (斜)}}$**
    
- **$\cos\theta = \frac{\text{Adjacent (鄰)}}{\text{Hypotenuse (斜)}}$**
    
- **$\tan\theta = \frac{\text{Opposite (對)}}{\text{Adjacent (鄰)}}$**
    

> **Master Exam Tip**: 題目不給圖形時，先自己 sketch 一個 right-angled triangle 填資料，如果已知兩條邊求未知邊，別忘了先考慮 **Pythagoras' Theorem (勾股定理)**：$a^2 + b^2 = c^2$。

### Part 2: Special Angles & Identities (特殊角與恆等式)

#### 1. Special Angles Table (特殊角數值表)

考試一定要記得這三個重要角度（$30^\circ, 45^\circ, 60^\circ$）的準確數值（Leave in surd form，不可以用小數計）：

- **$\sin\theta$**: $\sin 30^\circ = \frac{1}{2}$ | $\sin 45^\circ = \frac{\sqrt{2}}{2}$ | $\sin 60^\circ = \frac{\sqrt{3}}{2}$
    
- **$\cos\theta$**: $\cos 30^\circ = \frac{\sqrt{3}}{2}$ | $\cos 45^\circ = \frac{\sqrt{2}}{2}$ | $\cos 60^\circ = \frac{1}{2}$
    
- **$\tan\theta$**: $\tan 30^\circ = \frac{\sqrt{3}}{3}$ | $\tan 45^\circ = 1$ | $\tan 60^\circ = \sqrt{3}$
    

#### 2. Trigonometric Identities (三角恆等式)

這三條公式是用來簡化（Simplify）或證明（Prove）對手題目的最強武器：

- **Quotient Identity (商數關係)**: $\tan\theta \equiv \frac{\sin\theta}{\cos\theta}$
    
- **Pythagorean Identity (平方關係)**: $\sin^2\theta + \cos^2\theta \equiv 1$
    
- **Complementary Angles (餘角關係)**:
    
    - $\sin(90^\circ - \theta) \equiv \cos\theta$
        
    - $\cos(90^\circ - \theta) \equiv \sin\theta$
        
    - $\tan(90^\circ - \theta) \equiv \frac{1}{\tan\theta}$
        

### Part 3: Applications of Trigonometry (三角學應用)

這部分基本上是文字題（Word Problems），重點在於將中文字轉化為正確的三角形圖形 。

#### 1. Gradient and Inclination (斜率與傾斜角)

- **Gradient (斜率)**: $\text{Gradient} = \frac{\text{Vertical distance (垂直距離)}}{\text{Horizontal distance (水平距離)}}$
    
    - 寫法可以寫成**分數 (Fraction)**、**小數 (Decimal)** 或者 **$1 : n$** 的形式 。
        
- **Inclination (傾斜角)**: 條路與水平線（Horizontal ground）之間的夾角 $\theta$ 。
    
    - **核心關係**: $\text{Gradient} = \tan\theta$ 。
        

#### 2. Contour Maps (等高線地形圖)

- **Vertical distance (垂直距離)**: 兩點之間等高線數值的差（e.g., $300\text{m} - 100\text{m} = 200\text{m}$）。
    
- **Horizontal distance (水平距離)**: 在地圖上用間尺量度的長度（Measured length） $\times$ **Map Scale (地圖比例尺)** 。
    

#### 3. Angles of Elevation and Depression (仰角與俯角)

- **Angle of Elevation (仰角)**: 視線（Line of sight）往**上看**時，與**水平線 (Horizontal line)** 的夾角 。
    
- **Angle of Depression (俯角)**: 視線（Line of sight）往**下看**時，與**水平線 (Horizontal line)** 的夾角 。
    

> **🚨 Warning 🚨**: 俯角最容易畫錯！記住，仰角和俯角不論如何都**必須緊貼着「水平線」**。因為兩條水平線互相平行，所以「A 看 B 的仰角」永遠等於「B 看 A 的俯角」（Alternate angles, // lines）。

#### 4. Bearings (方位角)

用來表示一條線的方向，有兩種玩法：

- **True Bearing (真方位角)**:
    
    - 必須由**正北 (North)** 開始計 。
        
    - 永遠**順時針 (Clockwise)** 轉過去 。
        
    - 必須寫成 **3 個位數字**（e.g., $045^\circ$, $230^\circ$） 。
        
- **Compass Bearing (羅盤方位角)**:
    
    - 由**正北 (N)** 或**正南 (S)** 開始出發 。
        
    - 向**正東 (E)** 或**正西 (W)** 偏轉一個銳角 。
        
    - 格式（Format）: `N/S 角度 E/W`（e.g., $\text{N}50^\circ\text{E}$） 。
        

### 範例輸出與測試案例 (Example & Test Cases)

#### 題目 1：利用 Identities 簡化表達式 (Simplify Expression)

**Question**: Simplify $\frac{\sin^2(90^\circ-\theta)}{1+\sin\theta} - 1$

**Solution**:

1. 套用餘角關係：$\sin(90^\circ-\theta) = \cos\theta \implies \sin^2(90^\circ-\theta) = \cos^2\theta$
    
2. 套用平方關係：$\cos^2\theta = 1 - \sin^2\theta$
    
3. 利用因式分解：$1 - \sin^2\theta = (1 - \sin\theta)(1 + \sin\theta)$
    
4. 代入算式：
    
    $$\frac{(1 - \sin\theta)(1 + \sin\theta)}{1+\sin\theta} - 1$$
    
    $$= (1 - \sin\theta) - 1$$
    
    $$= -\sin\theta \quad (\text{或 } -\cos(90^\circ-\theta))$$
    

**Output**: $-\sin\theta$

#### 題目 2：求 Gradient 及 Inclination

**Question**: 一架巴士沿斜路向下行，當它向下行了垂直距離 $4\text{ m}$ 時，它行過的水平距離是 $28\text{ m}$ 。 (a) 以 $1:n$ 的形式表示這條路的 Gradient 。 (b) 求這條路的 Inclination $\theta$（準確至最接近的 $0.1^\circ$） 。

**Solution**: (a) $\text{Gradient} = \frac{\text{Vertical}}{\text{Horizontal}} = \frac{4}{28} = \frac{1}{7} \implies \mathbf{1:7}$ (b) $\tan\theta = \frac{1}{7} \implies \theta = \text{shift tan}(1/7) \approx \mathbf{8.1^\circ}$

這份筆記涵蓋了你工作紙上的所有核心考點，可以直接保存！如果有那一個部分想做更多特別題目的分析（例如 Cross-chapter 複雜的方位角 DSE 題），隨時話我知！