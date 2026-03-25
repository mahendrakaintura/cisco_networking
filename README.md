# 🌐 Cisco Enterprise Network Portfolio


## 👤 About Me / 自己紹介

> 専門学校でネットワーク技術を学び、授業外でも自主的にPacket Tracerや自宅ラボを使った実践検証を続けているネットワーク志望エンジニアです。
> JLPT N1取得済み。ヒンディー語・日本語・英語の3言語対応可能。

I am a network engineer fresher independently building and verifying enterprise-grade topologies using Cisco Packet Tracer and open-source tools — beyond classroom curriculum. My goal is to grow into a network specialist supporting next-generation infrastructure including 5G, SD-WAN, and cloud-native networking.

---

## 📁 Project List / プロジェクト一覧

---

### 1. 🔀 L3スイッチによる高速VLAN間ルーティング構成
**Advanced L3 Inter-VLAN Routing**

#### 概要
Cisco 3560シリーズのL3スイッチを使用し、従来のRouter-on-a-stick構成に代わる高速なVLAN間ルーティングを実装。ハードウェアレベルでの処理により、大規模オフィス環境でのパフォーマンスを最大化。

| 項目 | 内容 |
|------|------|
| 使用機器 | Cisco Catalyst 3560 (L3 Switch), ISR 4331 Router |
| プロトコル | OSPF, EIGRP, STP, VTP |
| セキュリティ | ACL (Standard / Extended), Port Security |
| 設計モデル | 拠点間接続 (Site-to-Site Connectivity) |

**学習ポイント**
- Router-on-a-stickとL3スイッチの性能差の実践的理解
- SVIインターフェースによるVLAN間通信の実装
- OSPFによる動的ルーティングとフェールオーバー設計

---

### 2. 🏢 Enterprise Three-Tier Network
**三層階層型ネットワークアーキテクチャ**

#### 概要
コア層・ディストリビューション層・アクセス層からなる三層モデルを設計。コア層にロードバランサーとCisco ASA Firewallを配置し、高可用性とスケーラビリティを両立。

| 項目 | 内容 |
|------|------|
| コア層 | Load Balancer + Cisco ASA Firewall |
| ディストリビューション層 | L3スイッチ (VLAN間ルーティング制御) |
| アクセス層 | Cisco Catalyst 2960 (L2 Switch) |
| 冗長化 | HSRP / Spanning Tree Protocol |

**学習ポイント**
- 階層型設計によるスケーラビリティと管理性の確保
- Cisco ASA FirewallによるDMZ設計の基礎
- HSRPを用いたデフォルトゲートウェイ冗長化

---

### 3. 🌍 Inter-VLAN & Site-to-Site Connectivity
**マルチ拠点ネットワーク統合設計**

#### 概要
複数のマルチレイヤスイッチをISR 4331ルーターに集約し、シリアル接続・VPNを介した遠隔拠点間通信をシミュレーション。実際の企業WANを想定した設計。

| 項目 | 内容 |
|------|------|
| WAN接続 | Serial Link / Site-to-Site VPN |
| ルーティング | OSPF Area設計, Inter-Area Routing |
| VLAN管理 | VTP Server/Client構成 |
| セキュリティ | Extended ACL, IPSec基礎 |

---

### 4. 🌐 Hybrid Star-Bus-Tree Topology
**ハイブリッドWANトポロジー**

#### 概要
スター型・バス型・ツリー型を組み合わせたハイブリッドトポロジー。複数拠点がCisco 1941ルーターを介して接続され、セルタワーによるワイヤレスWAN接続も統合。

| 項目 | 内容 |
|------|------|
| アクセス層 | Cisco 2960-24TT Switch (スター型) |
| WAN | Partial Mesh (シリアルリンク) |
| ワイヤレス | セルタワー統合 (モバイルWAN) |
| 接続方式 | Point-to-Point, Broadcast |

---

### 5. 📡 IoT統合次世代ネットワーク
**L3 Switch + IoT Ecosystem Integration**

#### 概要
L3スイッチにIoTエコシステムを統合した次世代ネットワーク設計。Webカメラ・スモークディテクター・スマートカーなどのIoTデバイスがホームゲートウェイ・クラウドを経由して相互接続。

| 項目 | 内容 |
|------|------|
| IoTデバイス | Webカメラ, スモークディテクター, スマートカー |
| ゲートウェイ | Home Gateway → Cloud Integration |
| 上位接続 | ISR Router (セキュア拠点間接続) |
| セキュリティ | デバイス認証, IoT専用VLAN分離 |

**学習ポイント**
- IoTデバイスの専用VLAN分離によるセキュリティ設計
- クラウド接続ゲートウェイの役割と実装イメージ
- スマートオフィス・産業自動化を意識したネットワーク設計

---

## 🛠️ Skills & Tools / 使用技術一覧

### Network Simulation & Monitoring
| Tool | 用途 |
|------|------|
| Cisco Packet Tracer | ネットワークトポロジー設計・構築・検証 |
| Zabbix | ネットワーク監視・死活監視・SNMP連携 |
| Wireshark | パケットキャプチャ・プロトコル詳細解析 |

### Protocols & Technologies
| カテゴリ | 技術 |
|----------|------|
| ルーティング | OSPF, EIGRP, BGP (基礎), Static Routing |
| スイッチング | VLAN, VTP, STP, RSTP, Inter-VLAN Routing |
| WAN | MPLS, SD-WAN基礎, Site-to-Site VPN, IPSec |
| 負荷分散 | ECMP (Equal-Cost Multi-Path) |
| セキュリティ | ACL, Port Security, Cisco ISE (基礎), Cisco ASA |
| 無線 | Cisco WLC, Cisco Meraki, Wi-Fi設計基礎 |
| クラウド | Amazon EC2, クラウドネットワーク基礎 |
| 自動化 | Ansible (Playbook基礎), Python (ネットワーク自動化スクリプト) |

### CLI & Admin Tools
| Tool | 用途 |
|------|------|
| PuTTY | SSH / Telnet コンソール接続 |
| Nmap | ネットワークスキャン・ポート状態確認 |
| Ping / Traceroute | 疎通確認・経路調査・遅延測定 |

---

## 📡 Continuously Learning / 継続学習中の技術

> ネットワーク業界は常に進化しています。以下の技術について、日々情報収集・自主学習を続けています。  
> *This section is updated regularly as new technologies emerge.*  
> **最終更新 / Last updated: March 2026**

---

### 🔵 Next-Gen Physical Infrastructure

| 技術 | 学習内容・関心ポイント |
|------|----------------------|
| **400G / 800G Ethernet** | データセンター間の超高速接続。PAM4変調・コヒーレント光通信の基礎を学習中 |
| **DWDM (Dense Wavelength Division Multiplexing)** | 1本の光ファイバーで複数波長を多重化するキャリア幹線技術。ITU-Tグリッド設計を調査中 |
| **FTTH / XGS-PON** | 家庭向け光アクセス網の進化。OLT・ONUの役割と次世代PON規格を学習中 |

---

### 🟢 Wireless & Mobile

| 技術 | 学習内容・関心ポイント |
|------|----------------------|
| **Wi-Fi 7 (IEEE 802.11be)** | MLO（マルチリンクオペレーション）による超低遅延設計。6GHz帯活用を調査中 |
| **5G NR スタンドアロン (SA)** | ネットワークスライシング・MEC（Multi-access Edge Computing）の仕組みを学習中 |
| **Private 5G / ローカル5G** | 企業・工場向けローカル5Gの設計モデルと周波数割り当てを調査中 |
| **Open RAN (O-RAN)** | 5G基地局のオープン化・仮想化アーキテクチャ（vRAN）を調査中 |

---

### 🟡 Cloud & Software-Defined Networking

| 技術 | 学習内容・関心ポイント |
|------|----------------------|
| **SD-WAN** | Cisco Viptela / Meraki SD-WANのアーキテクチャ・ゼロタッチプロビジョニングを学習中 |
| **SASE (Secure Access Service Edge)** | SD-WANとクラウドセキュリティ (CASB・SWG) を統合したアーキテクチャを調査中 |
| **Network as Code** | Ansible・Python・Terraformによるインフラ自動化・構成管理を実践中 |
| **Cloud-Native Networking** | AWS VPC設計・Transit Gateway・Direct Connectの基礎を学習中 |
| **SR (Segment Routing)** | MPLSに代わる次世代トラフィックエンジニアリング技術を調査中 |

---

### 🔴 Security & Observability

| 技術 | 学習内容・関心ポイント |
|------|----------------------|
| **Zero Trust Architecture** | 「信頼しない、常に検証する」モデル。Cisco ISE・microsegmentationを調査中 |
| **AIOps for Networks** | AIを活用した障害予測・異常検知・自動対応。ThousandEyesを調査中 |
| **BGP Security (RPKI)** | BGPハイジャック対策のRPKI（Resource Public Key Infrastructure）を学習中 |
| **NDR (Network Detection & Response)** | ネットワークトラフィック異常をAIで検知するセキュリティ技術を調査中 |

---

### 🟣 Emerging & Future Technologies

| 技術 | 学習内容・関心ポイント |
|------|----------------------|
| **IPv6 完全移行技術** | デュアルスタック・6to4・NAT64などの移行手法を学習中 |
| **Quantum Networking (基礎)** | 量子鍵配送（QKD）の概念と将来の通信セキュリティへの影響を調査中 |
| **Digital Twin for Networks** | ネットワークのデジタルツイン化による障害シミュレーション技術を調査中 |
| **Edge Computing × Networking** | 5G MEC・CDNエッジとネットワーク設計の関係を学習中 |

---

> 💡 *All topologies are built and verified in Cisco Packet Tracer. This portfolio represents independent self-study beyond classroom curriculum, demonstrating proactive learning and practical network design capability.*
