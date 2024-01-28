---
;layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
;{% if author.googlescholar %}
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
;{% endif %}

;{% include base_path %}

Journals
=====
1. Hao Xu, Harry Chang, **Kun Qiu**, Yang Hong, Wenjun Zhu, Xiang Wang, Baoqian Li, Jin Zhao, “Accelerating Deep Packet Inspection With SIMD-Based Multi-Literal Matching Engine", IEEE Transactions on Network and Service Management, to be published, Jan. 2024
2. **Kun Qiu**, Jin Zhao, Xin Wang, Xiaoming Fu, Stefano Secci, “Efficient Recovery Path Computation for Fast Reroute in Large-scale Software Defined Networks,” IEEE Journal on Selected Areas in Communications, Vol. 37(8):1755-1768, Aug. 2019.
3. **Kun Qiu**, Jing Yuan, Jin Zhao, Xin Wang, Stefano Secci, and Xiaoming Fu, “FastRule: Efficient Flow Entry Updates for TCAM-Based OpenFlow Switches,” IEEE Journal on Selected Areas in Communications, Vol. 37(3):484-498, Mar. 2019.
4. **Kun Qiu**, Siyuan Huang, Qiongwen Xu, Jin Zhao, Xin Wang, Stefano Secci, “ParaCon: A Parallel Control Plane for Scaling Up Path Computation in SDN,” IEEE Transactions on Network and Service Management, 2017, 14 (4):978-990.
5. **Kun Qiu**, Fang Yuquan, Lu Wei, Jin Zhao, “A Design of OpenFlow Switch Based on General Broadband Router", 《基于通用宽带路由器的OpenFlow交换机设计》(in Chinese), Computer Applications and Software, 2016, Vol.33(11):84-89, Nov. 2016.

Conferences
=====
1. Hao Xu, Harry Chang, Wenjun Zhu, Yang Hong, Geoff Langdale, **Kun Qiu**, Jin Zhao, “Harry: A Scalable SIMD-based Multi-literal Pattern Matching Engine for Deep Packet Inspection”, IEEE International Conference on Computer Communications (INFOCOM), 2023, New York area
2. **Kun Qiu**, Harry Chang, Ying Wang, Xiahui Yu, Wenjun Zhu, Yingqi Liu, Jianwei Ma, Weigang Li, Xiaobo Liu, Shuo Dai, “Traffic Analytics Development Kits (TADK): Enable Real-Time AI Inference in Networking Apps”, International Conference on Ubiquitous and Future Networks (ICUFN), 2022, 
 Barcelona, Spain
3. Wenjun Zhu, Harry Chang, Yang Hong, Xiang Wang, Geoff Langdale, **Kun Qiu**, Mingyi Zhang, “Hyperverse: A High Throughput Pattern Matching Engine for Metaverse”, IEEE International Conference on Distributed Computing Systems Workshops (ICDCSW) 2022, Bologna, Italy
4. **Kun Qiu**, Harry Chang, Yang Hong, Wenjun Zhu, Xiang Wang, Baoqian Li, “Teddy: An Efficient SIMD-based Literal Matching Engine for Scalable Deep Packet Inspection”, International Conference on Parallel Processing (ICPP), 2021, Lemont, Illinois
5. **Kun Qiu**, Yuanyang Zhu, Jing Yuan, Jin Zhao, Xin Wang, and Tilman Wolf, “ParaPLL: Fast Parallel Shortest-path Distance Query on Large-scale Weighted Graphs,” in Proc. International Conference on Parallel Processing(ICPP 2018), Eugene OR, USA, Aug. 2018
6. **Kun Qiu**, Jing Yuan, Jin Zhao, Xin Wang, Stefano Secci, and Xiaoming Fu, “Fast Lookup Is Not Enough: Towards Efficient and Scalable Flow Entry Updates for TCAM-based OpenFlow Switches,” in Proc. IEEE International Conference on Distributed Computing Systems (ICDCS 2018), Vienna, Austria, Jul. 2018
7. **Kun Qiu**, Renlong Tu, Siyuan Huang, Jin Zhao, Xin Wang, “cCluster: A Highly Scalable and Elastic OpenFlow Control Plane,” IEEE IWQoS 2015, short paper, Portland OR, Jun. 2015
8. **Kun Qiu**, Zhe Chen, Yang Chen, Jin Zhao, Xin Wang, “GFlow: Towards GPU-based High-Performance Table Matching in OpenFlow Switches,” IEEE International Conference on Information Networking (ICOIN), Siem Reap, Cambodia, Jan. 2015

Patents
=====
1. **Kun Qiu**. (2024), "NeoHarry - High-performance Parallel Multi-literal Matching Algorithm", United States Patent, In Publishing
2. **Kun Qiu**. (2023). “Heavy Hitter Flow Detection”, United States Patent, US20230239244A1, Filed: Mar. 2023. Published: Jul. 2023.
3. **Kun Qiu**. (2022). “Techniques to encode and decode for character class matching”. United States Patent, US20220171628A1. Filed: February 17, 2022. Published: June 2, 2022.
4. **Kun Qiu**. (2022). “Flexible deterministic finite automata (DFA) tokenizer for AI-based malicious traffic detection”. United States Patent, US20220279013A1”. Filed: May 13, 2022. Published: Sep. 1, 2022
5. **Kun Qiu**. (2022). “Techniques for use of a large scale multi-literal matching algorithm”. United States Patent, US20220113969A1. Filed: December 22, 2021. Published: April 14, 2022.

Talks
=====
1. AI Security Talk (in Chinese)


Whitepapers
=====


;{% for post in site.publications reversed %}
;  {% include archive-single.html %}
;{% endfor %}
