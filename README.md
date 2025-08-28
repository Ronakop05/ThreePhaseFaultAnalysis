# ThreePhaseFaultAnalysis

This project presents the modeling and simulation of a three-phase power system under short-circuit fault conditions, implemented in MATLAB Simulink. A three-phase source is connected to a fault block where a short circuit is introduced at a specific instant, and the resulting current and voltage waveforms are observed. To protect the system, a relay subsystem is designed using comparators, SR flip-flops, and logic gates, which continuously monitor the line currents. When the fault current exceeds the predefined threshold, the relay activates and isolates the faulty section, thereby ensuring safe operation of the system.

The simulation results show that during the fault event, the current in all three phases rises sharply and the voltages experience severe distortion. Immediately after the relay detects the abnormal rise in current, it trips the system, bringing both current and voltage to zero. This demonstrates how protective relays safeguard power systems against short circuits and highlights their importance in stability and reliability. The project not only illustrates the fault behavior and relay operation but also provides a strong foundation for further exploration of advanced power system protection schemes such as differential protection, distance relays, and circuit breaker integration.

How It Works
1)Initially, the system operates under normal balanced condition.
2)At t = 0.1s, a 3-phase short-circuit fault is introduced.
3)The line currents shoot up to very high values.
4)The relay subsystem detects the overcurrent by comparing it with the set threshold.
5)Once detected, the relay trips and isolates the source → current & voltage drop to zero.

This demonstrates protection against short-circuit faults.
