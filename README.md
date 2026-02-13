# OJS
Journals using OJS in Vietnam

## Hình 2.5 – Sơ đồ khung khái niệm

```mermaid
%%{init: {
  "flowchart": { "curve": "basis", "nodeSpacing": 30, "rankSpacing": 36 },
  "themeVariables": {
    "fontFamily": "Inter, Segoe UI, Arial",
    "fontSize": "14px",
    "primaryTextColor": "#0b1f44",
    "lineColor": "#3b3b3b"
  }
}}%%
flowchart TB

%% ===================== STYLE =====================
classDef tier fill:#EAF2FF,stroke:#2F5FB3,stroke-width:1.6px,color:#0B1F44,rx:12,ry:12;
classDef tier2 fill:#E9FBF2,stroke:#1F8A4C,stroke-width:1.6px,color:#0B2B18,rx:12,ry:12;
classDef tier3 fill:#FFF4E6,stroke:#B35C00,stroke-width:1.6px,color:#3A1E00,rx:12,ry:12;
classDef ai fill:#EFE9FF,stroke:#5B35D5,stroke-width:1.6px,color:#1F0F55,rx:12,ry:12;
classDef chip fill:#FFFFFF,stroke:#9AA4B2,stroke-width:1px,color:#111,rx:10,ry:10;
classDef note fill:#F6F7F9,stroke:#9AA4B2,stroke-width:1px,color:#111,rx:10,ry:10;

linkStyle default stroke:#3b3b3b,stroke-width:1.4px;
linkStyle 0 stroke:#2F5FB3,stroke-width:1.8px;
linkStyle 1 stroke:#1F8A4C,stroke-width:1.8px;
linkStyle 2 stroke:#5B35D5,stroke-width:1.6px,stroke-dasharray: 5 4;
linkStyle 3 stroke:#4B5563,stroke-width:1.4px,stroke-dasharray: 2 4;
linkStyle 4 stroke:#4B5563,stroke-width:1.4px,stroke-dasharray: 2 4;

%% ===================== HEADER =====================
T["**Khung Khái Niệm Vận Hành Hệ Thống OJS & Tích Hợp AI**"]:::note

%% ===================== CORE (3 TIERS) =====================
A["**Tầng 1 · Chất lượng vận hành kỹ thuật (OJS)**<br/>⏱️ thời gian · ✅ đúng hạn · 🧭 dễ dùng"]:::tier
B["**Tầng 2 · Hiệu quả tổ chức quy trình**<br/>🧩 chuẩn hoá · 🔎 minh bạch · 📌 kiểm soát"]:::tier2
C["**Tầng 3 · Trải nghiệm & kết quả người dùng**<br/>😊 hài lòng · 👍 chấp nhận · 💬 trải nghiệm"]:::tier3

D["**Nhánh AI · Chỉ báo trưởng thành số**<br/>🤖 mức tích hợp · ⚖️ lợi ích/rủi ro · 📈 trưởng thành số"]:::ai

%% ===================== CHIPS (SUB-NODES) =====================
subgraph S1[" "]
direction LR
A1["⏱️ Thời gian xử lý"]:::chip
A2["🔁 Số vòng PB"]:::chip
A3["✅ PB đúng hạn"]:::chip
A4["⚠️ Lỗi thao tác"]:::chip
A5["🧭 Dễ dùng"]:::chip
end

subgraph S2[" "]
direction LR
B1["🧩 Chuẩn hoá"]:::chip
B2["🔎 Trách nhiệm rõ"]:::chip
B3["📌 Tiến độ"]:::chip
B4["✉️ Thư mời PB"]:::chip
B5["🎯 Phù hợp CM"]:::chip
end

subgraph S3[" "]
direction LR
C1["😊 Hài lòng"]:::chip
C2["🧭 Dễ dùng"]:::chip
C3["👍 Chấp nhận"]:::chip
end

subgraph S4[" "]
direction LR
D1["🤖 Tích hợp"]:::chip
D2["⚖️ Nhận thức"]:::chip
D3["📈 Chỉ báo số"]:::chip
end

%% Attach chips (light dotted)
A -.-> A1
A -.-> A2
A -.-> A3
A -.-> A4
A -.-> A5

B -.-> B1
B -.-> B2
B -.-> B3
B -.-> B4
B -.-> B5

C -.-> C1
C -.-> C2
C -.-> C3

D -.-> D1
D -.-> D2
D -.-> D3

%% ===================== MAIN FLOWS =====================
T --> A
A -->|chuyển hoá hiệu suất kỹ thuật → hiệu quả quản trị| B
B -->|tối ưu quy trình → nâng trải nghiệm| C
C -.->|biểu hiện trưởng thành số| D

%% ===================== FEEDBACK (LEFT) =====================
N["Kết quả từ người dùng<br/>được phản hồi để<br/>điều chỉnh kỹ thuật &<br/>tái cấu trúc quy trình"]:::note
C -.-> N
N -.-> A
N -.-> B
```
