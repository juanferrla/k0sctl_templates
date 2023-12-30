# k0sctl_templates
A command-line bootstrapping and management tool for k0s zero friction kubernetes clusters.

#Linux K0sctl bin Installation
wget https://github.com/k0sproject/k0sctl/releases/download/v0.16.0/k0sctl-linux-x64
ln -s k0sctl-linux-x64 k0sctl
chmod +x k0sctl-linux-x64
./k0sctl apply --config k0sctl.yaml
k0sctl init > k0sctl.yaml
#Kubeconfig generation
./k0sctl kubeconfig --config k0sctl.yaml > k0s.config

#Windows K0sctl bin Installation
choco install k0sctl