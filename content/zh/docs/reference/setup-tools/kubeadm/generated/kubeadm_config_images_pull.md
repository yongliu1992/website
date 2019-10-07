
拉取 kubeadm 使用的图像。
<!--
Pull images used by kubeadm.
-->

### 概要

<!--
### Synopsis
-->

拉取 kubeadm 使用的图像。
<!--
Pull images used by kubeadm.
-->

```
kubeadm config images pull [flags]
```

### 选项

<!--
### Options
-->

<!--
<td></td><td style="line-height: 130%; word-wrap: break-word;">Path to kubeadm config file.</td>

<td colspan="2">--cri-socket string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "/var/run/dockershim.sock"</td>

<td></td><td style="line-height: 130%; word-wrap: break-word;">Specify the CRI socket to connect to.</td>

<td></td><td style="line-height: 130%; word-wrap: break-word;">A set of key=value pairs that describe feature gates for various features. Options are:<br/>Auditing=true|false (ALPHA - default=false)<br/>CoreDNS=true|false (default=true)<br/>DynamicKubeletConfig=true|false (BETA - default=false)</td>

<td></td><td style="line-height: 130%; word-wrap: break-word;">help for pull</td>

<td colspan="2">--kubernetes-version string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "stable-1"</td>

<td></td><td style="line-height: 130%; word-wrap: break-word;">Choose a specific Kubernetes version for the control plane.</td>

-->

<table style="width: 100%; table-layout: fixed;">
  <colgroup>
    <col span="1" style="width: 10px;" />
    <col span="1" />
  </colgroup>
  <tbody>

    <tr>
      <td colspan="2">--config string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">kubeadm 配置文件的路径。</td>
    </tr>

    <tr>
      <td colspan="2">--cri-socket string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值："/var/run/dockershim.sock"</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">指定要连接的 CRI 套接字。</td>
    </tr>

    <tr>
      <td colspan="2">--feature-gates string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">一组键=值对，用于描述各种特性的特性门。选项：<br/>Auditing=true|false (ALPHA - default=false)<br/>CoreDNS=true|false (default=true)<br/>DynamicKubeletConfig=true|false (BETA - default=false)</td>
    </tr>

    <tr>
      <td colspan="2">-h, --help</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">pull 操作的帮助信息</td>
    </tr>

    <tr>
      <td colspan="2">--kubernetes-version string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值： "stable-1"</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">为控制平面选择一个特定的 Kubernetes 版本。</td>
    </tr>

  </tbody>
</table>


### 从父命令继承的选项

<!--
### Options inherited from parent commands
-->

<table style="width: 100%; table-layout: fixed;">
  <colgroup>
    <col span="1" style="width: 10px;" />
    <col span="1" />
  </colgroup>
  <tbody>

    <tr>
      <td colspan="2">--kubeconfig string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值： "/etc/kubernetes/admin.conf"</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">用于和集群通信的 KubeConfig 文件。如果它没有被设置，那么 kubeadm 将会搜索一个已经存在于标准路径的 KubeConfig 文件。</td>
    </tr>

    <tr>
      <td colspan="2">--rootfs string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">[实验] 到'真实'主机根文件系统的路径。</td>
    </tr>

  </tbody>
</table>

<!--
<td colspan="2">--kubeconfig string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "/etc/kubernetes/admin.conf"</td>

<td></td><td style="line-height: 130%; word-wrap: break-word;">The KubeConfig file to use when talking to the cluster. If the flag is not set, a set of standard locations are searched for an existing KubeConfig file.</td>

<td></td><td style="line-height: 130%; word-wrap: break-word;">[EXPERIMENTAL] The path to the 'real' host root filesystem.</td>
-->

