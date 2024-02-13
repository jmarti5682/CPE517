### Question 5: 
**P1:** <br>
Clock Rate = 3 GHz <br>
CPI = 1.5 <br>
CPU<sub>Time</sub> = 10s <br> 

**P2:** <br>
Clock Rate = 2.5 GHz <br>
CPI = 1 <br>
CPU<sub>Time</sub> = 10s <br>

$$CPU \ Time = \frac{IC \times CPI}{Clock \ Rate}$$ 

$$\$$

$$CPI = \frac {CPU \ Clock \ Cycle}{IC}$$

**P1** <br>
$$10 = \frac{IC \times 1.5}{3 \times 10^9}$$
$$3.10^{10} = IC_1 \times 1.5$$
$$IC_1 = 2 \times 10^{10}$$

$$\$$

$$1.5 = \frac{CPU \ Clock \ Cycle}{2 \times 10^{10}}$$

$$CPU \ Clock \ Cycle_1 = 3 \times 10^{10}$$

**P2** <br>
$$10 = \frac{IC \times 1}{2.5 \times 10^9}$$
$$IC_2 = 2.5 \times 10^{10}$$

$$\$$

$$1 = \frac{CPU \ Clock \ Cycle}{2.5 \times 10^{10}}$$

$$CPU \ Clock \ Cycle_2 = 2.5 \times 10^{10}$$

**P3** <br>
$$10 = \frac{IC \times 2.2}{4 \times 10^9}$$
$$IC_3 = 1.82 \times 10^{10}$$

$$\$$

$$2.2 = \frac{CPU \ Clock \ Cycle}{1.82 \times 10^{10}}$$

$$CPU \ Clock \ Cycle_3 = 4 \times 10^{10}$$


### Question 6:
**P1**<br>
Clock Rate = 2.5 GHz<br>
IC = 1.0E6<br>

**P2**<br>
Clock Rate = 3.0 GHz<br>
IC = 1.0E6<br>

IC = .10A, .20B, .50C, .20D

**Part A:** <br>
$$AVG \ CPI_1 = \frac{\sum (IC \times CPI)}{IC}$$

$$\begin{align}
AVG \ CPI_1 &= \frac{(1 \times 10^6)(.10)(1) + (1 \times 10^6)(.20)(2) + (1 \times 10^6)(.50)(3) + (1 \times 10^6)(.20)(3) }{1.0 \times 10^6} \\
&= \frac{(1 \times 10^6)((.10)(1) + (.20)(2) + (.50)(3) + (.20)(3))}{1.0 \times 10^6} \\
&= \frac{\cancel{(1 \times 10^6)}((.10)(1) + (.20)(2) + (.50)(3) + (.20)(3))}{\cancel{1.0 \times 10^6}} \\
&= {(.10)(1) + (.20)(2) + (.50)(3) + (.20)(3)} \\
AVG \ CPI_1 &= 2.6
\end{align}$$



$$\ $$

$$\begin{align}
AVG \ CPI_2 &= {(.10)(2) + (.20)(2) + (.50)(2) + (.20)(2)} \\
AVG \ CPI_2 &= 2.0
\end{align}$$

$$\ $$

$$Execution \ Time = \frac {IC \times AVG \ CPI}{Clock \ Rate}$$

$$\begin{align}
Execution \ Time_1 &= \frac{1.0 \times 10^6 \times 2.6}{2.5 \times 10^9} \\
&= 1.04 \times 10^{-3} \ s \\
Execution \ Time_1 &= 1.04 \ ms
\end{align}$$



$$\ $$

$$\begin{align}
Execution \ Time_2 &= \frac{1.0 \times 10^6 \times 2.0}{3.0 \times 10^9} \\
&= 6.67 \times 10^{-3} \ s \\
Execution \ Time_2 &= 0.667 \ ms
\end{align}$$

$$\ $$

$$\therefore \text{P2 is faster}$$ 

$$\ $$

**Part B** <br>

$$\begin{align}
AVG \ CPI_1 = 2.6 \\
AVG \ CPI_2 = 2.0
\end{align}$$

**Part C** <br>

$$Clock \ Cycle = IC \times AVG \ CPI$$

$$\begin{align}
Clock \ Cycle_1 = 1 \times 10^{6}(2.6) = 2.6 \times 10^{6} \ \text{cycles}\\
Clock \ Cycle_2 = 1 \times 10^{6}(2.0) = 2.0 \times 10^{6} \ \text{cycles}
\end{align}$$







