# temprods



sudo subscription-manager repos --enable codeready-builder-for-rhel-9-$(arch)-rpms

sudo dnf install https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm




doesn't work

dnf config-manager --set-enabled crb
