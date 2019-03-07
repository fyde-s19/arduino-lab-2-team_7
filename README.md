# arduino-lab-2-team_7
arduino-lab-2-team_7 created by GitHub Classroom
1. The dimmer code is showing how much time the LED is spent on (high) and how much it's spent off (low). The percentage of on/off time changes depending on the duty cycle which is changed in a loop, causing the dimming and strobing effect.
2. The decoded message contains the information that would be transferred with UART and what is picked up when we open Serial Monitor. For example, we can decode 51.1.80 or a value similar to that.
3. 3.643 ms
4. 1.5 ms
5. 1.1113 ms
6. 984.5 us
7. Serial monitor debugging is much easier and faster to do since all you do is read text that is printed on the screen that you deem necessary to see while debugging. However, you can analyze more data and signals with the logic analyzer since it directly connects to them through GPIO pins and displays the infomation in a more graphical approach. Logic analyzers also require external programs and devices while you can easily access the serial monitor through the arduino IDE. Logic analyzers also can take less processing time than serial monitors as well.
8. We need to connect the logic analyzer to the same ground as the Arduino so it can have a reference voltage to the Arduino and correctly rad the voltages since they both share the same reference node.
