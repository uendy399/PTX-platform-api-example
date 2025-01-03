# PTX-platform-api-example
交通部運輸資料流通服務平臺(TDX) 數據交換API實作

## 1.事前準備
首先您會需要到 TDX (https://tdx.transportdata.tw ) 取得帳號，帳號角色分為三大類
#### 學研單位
1. 公私立大專院校所屬教職人員、學生
2. 公立學研機構所屬研究人員
#### 學研單位的帳號限制
1. 使用帶有edu或org域名的學研單位所屬電子郵件信箱進行註冊
2. 可註冊至多三把API金鑰
3. 可查詢資料服務
4. 可申請下載歷史資料
#### 公部門會員
1. 中央政府機關
2. 交通部及部屬機關
3. 地方政府機關
#### 公部門帳號限制
1. 使用帶有gov域名的公部門所屬電子郵件信箱進行註冊
2. 可註冊至多三把API金鑰
3. 可查詢資料服務
4. 可申請下載歷史資料
#### 一般會員
1. 個人身份
2. 私人企業
3. 非公務機關之協作單位
#### 一般會員限制
1. 使用合法電子郵件信箱進行註冊
2. 使用edu、org、gov域名信箱無法註冊為一般會員
3. 可註冊至多三把API金鑰
4. 可查詢資料服務
5. 可申請下載歷史資料

## 2.帳號申請審核過後

這步驟預計需要2~3天審核，耐心等吧

## 3.部署一個API Tester : 目前本例使用Hoppscotch 

#### 境外IP阻擋 ? -->目前使用GCP/AWS 皆可接入

![IPS](![image](https://github.com/user-attachments/assets/325e1d0e-38ee-4a04-a946-bbfcd2c06d87)"IP")
![dbip](https://cf-content-x.yws.tw/images/dbip.jpg "dbip")

### API設定細則可以參照: https://github.com/tdxmotc/SampleCode

本例發現建議可以將Access Key cache 到本地，這樣就可以減少重複與端點索取金鑰


