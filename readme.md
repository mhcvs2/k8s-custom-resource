
cd $GOPATH
mkdir -p krds && cd krds

git clone git@github.com:mhcvs2/k8s-custom-resource.git

cd 8s-custom-resource

go mod vendor

./hack/update-codegen.sh