# 集群访问及测试

当通过云控制台成功创建USDP集群后，为方便用户便捷访问USDP管理服务以及对大数据实现管理和维护工作，可选择一下几种方式进行操控USDP；当然还有其他的方法可用，譬如用户办公网与云端专线打通方案、自建VPN方案等；您可以根据您的实际情况选择其中一种，或根据实际情况调整更好的更安全的集群访问方式即可。

--------

### 访问云端USDP服务的其它方式：

* **访问方式1：**[本地直接访问云端USDP集群](/USDP/operate/access/internet)

  该方式配置相对简单，适用于集群规模较小，或服务测试等临时情况，该方式的缺点是，需为集群的各个节点单独绑定EIP地址，会增加用户云端管理员维护复杂度。

  --------

  

* **访问方式2：**[通过云端Windows主机访问USDP集群](/USDP/operate/access/cloud)

  该方式配置略复杂，管理较为便利，有助于提升云端环境的安全性，但大数据研发、运营人员可能不够灵活。适用于操作及访问大数据集群的人数较少、频率较低等情况。

  --------

  

* **访问方式3：**[配置openvpn访问USDP集群](/USDP/operate/access/openvpn)

  该方法为常见的方式，即通过openvpn将云端及用户本地网络进行内网打通，用户访问及操控云端大数据集群时较便捷，但用户较多的情况下，需要针对不的用户做一定的权限控制，以便较好的完成对云端大数据集群的安全性保护。

  --------

  

  相较于直接在UCLOUD云控制台中打开USDP服务控制台的方式，以上几种方式均可以较全面的操控USDP服务的WebUI中所有的功能，以及集群中各大数据服务原生的WebUIs。

  

* **其他访问方式：**

  如专线打通云端及办公网络、多种方式组合配置等方式，来平衡访问/操控便捷性与网络/数据安全性保护。

------------

!> 注意：</br>原则上，若非必要，尽可能减少将大数据集群的访问及连接方式暴露在公网中，数据安全、业务安全等时刻需要警惕。