## 步骤1：创建VPN网关
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/)，选择【云产品】>【网络】>【私有网络】进入私有网络控制台。
2. 在左侧目录中单击【VPN 连接】>【VPN 网关】，进入管理页。
3. 选择地域，如示例中的**东京**，单击【新建】。

>? 若【新建】显示灰色，且鼠标移至上方时显示“无可用私有网络”，请 [创建私有网络](https://cloud.tencent.com/document/product/215/36515#.E5.88.9B.E5.BB.BA-vpc.3Ca-id.3D.221.22.3E.3C.2Fa.3E) 后再进行新建 VPN 网关。 

4. 在弹出的创建对话框中填写 VPN 网关名称（如 VPN1），选择关联网络为私有网络、所属网络选择VPC1，设置带宽上限及计费方式等。
 ![](https://main.qcloudimg.com/raw/bac4553ea54d1bf01374bdca084f4ba5.png)
5. 单击【创建】。VPN 网关创建完成后，系统随机分配公网 IP，如：`124.156.239.133`。
  ![](https://main.qcloudimg.com/raw/e906f7c547bb29fb267c3370039c3541.png)
