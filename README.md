# sealer-nvidia-plugin-pack
## preparation
1. centos 7.9 with nvidia driver installed
2. sealer 0.4.0 installed
## build
sealer build -b lite -t sealer-test:v0.1 .
## apply
1. Modify Clisterfile according to the environment
2. sealer apply -f ./Clusterfile
## results
nvidia.com/gpu shows on 'Allocated resources' with command 'kubectl describe node' 