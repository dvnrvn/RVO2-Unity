# RVO2‑Unity

Based on [https://github.com/snape/RVO2-CS]

With some modifications:

1. Unity JobSystem integration

2. Runtime agent and obstacle add/remove support

3. Some API modifications

4. Multi simulator instances support

5. New samples

---

Screen recordings for samples:

- Block

![image](./Screenshots/sample_01.gif)

- Circle

![image](./Screenshots/sample_02.gif)

- Interactive

![image](./Screenshots/sample_03.gif)

- Dynamic

![image](./Screenshots/sample_04.gif)

- Work with GameObjects and MonoBehaviours

![image](./Screenshots/sample_05.gif)

## Modifications in this fork
* **NativeParallelMultiHashMapExtensions.cs** — 2025-05-02  
  Added unmanaged generic constraints to compile on Unity 6 (Roslyn CS8377).


> Forked from [Aillieo/RVO2-Unity](https://github.com/aillieo/RVO2-Unity)

This project is distributed under the Apache License 2.0
(see `LICENSE` for full text).

