# vagrant-rainbond

> 基于`vagrant`快速部署开发测试环境,仅在Mac上测试过.

## 版本信息

```
vagrant: 2.2.3
packer: v1.3.4(可选)
VBoxManage: 6.0.4r128413
```

## 介质

需要安装[vagrant](https://www.vagrantup.com/)和[virtualbox](https://www.virtualbox.org/)

## 使用方式

### 配置

默认配置2核4G,CPU使用率50%,可以根据物理机适当调高配置

### 单节点

```
git clone https://github.com/goodrain/vagrant-rainbond.git
cd vagrant-rainbond
vagrant up
# 单节点ip
172.20.0.101
# 管理员
root/vagrant
```

